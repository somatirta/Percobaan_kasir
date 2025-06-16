/* Import Google Fonts Inter for Modern Typeface */
@import url('https://fonts.googleapis.com/css2?family=Inter&display=swap');

/* Base Reset */
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  scroll-behavior: smooth;
  --fb-blue: #1877f2;
  --fb-blue-dark: #165ecc;
  --fb-bg: #f0f2f5;
  --fb-content-bg: #ffffff;
  --fb-text-primary: #050505;
  --fb-text-secondary: #606770;
  --fb-border: #dddfe2;
  --fb-shadow: rgba(0,0,0,0.1);
  --fb-focus-outline: var(--fb-blue);
}

/* Body and Main Wrapper */
body {
  background-color: var(--fb-bg);
  color: var(--fb-text-primary);
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  line-height: 1.5;
}

/* App Container */
.app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

/* Header - Sticky with glass morphism */
header.app-header {
  position: sticky;
  top: 0;
  height: 64px;
  background: rgba(255 255 255 / 0.9);
  backdrop-filter: saturate(180%) blur(16px);
  border-bottom: 1px solid var(--fb-border);
  box-shadow: 0 2px 6px var(--fb-shadow);
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 0 24px;
  z-index: 1000;
}

header.app-header .logo {
  font-weight: 700;
  font-size: 1.8rem;
  color: var(--fb-blue);
  user-select: none;
  cursor: pointer;
  letter-spacing: 1.1px;
}

header.app-header nav {
  display: flex;
  align-items: center;
  gap: 24px;
}

header.app-header nav a {
  color: var(--fb-text-secondary);
  font-weight: 600;
  font-size: 1rem;
  text-decoration: none;
  padding: 8px 12px;
  border-radius: 8px;
  transition: background-color 0.2s ease, color 0.2s ease;
}

header.app-header nav a:hover,
header.app-header nav a:focus-visible {
  background-color: #e7f3ff;
  color: var(--fb-blue-dark);
  outline: none;
}

header.app-header nav a.active {
  color: var(--fb-blue);
  font-weight: 700;
}

/* Sidebar - sticky on desktop, slide-out on mobile */
.sidebar {
  width: 280px;
  background: var(--fb-content-bg);
  box-shadow: 1px 0 5px var(--fb-shadow);
  display: flex;
  flex-direction: column;
  padding: 24px 0;
  gap: 16px;
  position: sticky;
  top: 64px;
  height: calc(100vh - 64px);
}

.sidebar nav {
  display: flex;
  flex-direction: column;
  gap: 12px;
  padding: 0 16px;
}

.sidebar nav a {
  display: flex;
  align-items: center;
  gap: 16px;
  color: var(--fb-text-primary);
  font-weight: 600;
  font-size: 1rem;
  padding: 12px 16px;
  border-radius: 12px;
  text-decoration: none;
  transition: background-color 0.3s ease;
  position: relative;
}

.sidebar nav a .material-icons {
  font-size: 24px;
  color: var(--fb-blue);
}

.sidebar nav a:hover,
.sidebar nav a:focus-visible {
  background-color: #e7f3ff;
  outline: none;
}

.sidebar nav a.active {
  background-color: #e7f3ff;
  font-weight: 700;
  color: var(--fb-blue-dark);
}

/* Notification badge */
.sidebar nav a .badge {
  position: absolute;
  right: 12px;
  top: 50%;
  transform: translateY(-50%);
  background-color: #ff3b30;
  color: white;
  font-size: 0.75rem;
  font-weight: 700;
  border-radius: 12px;
  padding: 2px 8px;
  min-width: 20px;
  text-align: center;
  user-select: none;
}

/* Main content area */
main.app-main {
  flex-grow: 1;
  min-height: calc(100vh - 64px);
  background-color: var(--fb-bg);
  padding: 24px 32px;
  display: flex;
  flex-direction: column;
  gap: 24px;
  overflow-y: auto;
  scroll-behavior: smooth;
}

/* Cards */
.card {
  background-color: var(--fb-content-bg);
  border-radius: 16px;
  box-shadow:
    0 1px 2px rgba(0,0,0,0.07),
    0 2px 6px rgba(0,0,0,0.1);
  padding: 24px;
  transition: box-shadow 0.3s ease;
  cursor: default;
}

.card:hover,
.card:focus-within {
  box-shadow:
    0 5px 15px rgba(24, 119, 242, 0.35);
}

/* Buttons */
button,
button.material-button {
  font-family: inherit;
  font-weight: 700;
  font-size: 1rem;
  padding: 12px 24px;
  border: none;
  border-radius: 12px;
  background-color: var(--fb-blue);
  color: white;
  cursor: pointer;
  transition: background-color 0.3s ease, transform 0.2s ease;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: 8px;
  user-select: none;
  box-shadow: 0 3px 8px rgba(24, 119, 242, 0.6);
}

button:hover,
button:focus-visible {
  background-color: var(--fb-blue-dark);
  outline: none;
  transform: translateY(-2px);
}

/* Form Elements */
input[type="text"],
input[type="email"],
input[type="password"],
select,
textarea {
  font-family: inherit;
  font-size: 1rem;
  padding: 10px 14px;
  border-radius: 12px;
  border: 1.5px solid var(--fb-border);
  background-color: var(--fb-content-bg);
  color: var(--fb-text-primary);
  box-shadow: inset 0 1px 3px rgba(0,0,0,0.05);
  transition: border-color 0.3s ease, box-shadow 0.3s ease;
  resize: vertical;
  outline-offset: 2px;
}

input[type="text"]:focus,
input[type="email"]:focus,
input[type="password"]:focus,
select:focus,
textarea:focus {
  border-color: var(--fb-blue);
  box-shadow: 0 0 8px rgba(24, 119, 242, 0.4);
  outline: none;
}

/* Headings and Typography */
h1, h2, h3, h4, h5, h6 {
  font-weight: 700;
  color: var(--fb-text-primary);
  line-height: 1.2;
}

h1 {
  font-size: clamp(2rem, 5vw, 3rem);
}

h2 {
  font-size: clamp(1.5rem, 4vw, 2.5rem);
}

h3 {
  font-size: clamp(1.25rem, 3vw, 2rem);
}

h4 {
  font-size: 1.125rem;
}

p, span, label {
  font-size: 1rem;
  color: var(--fb-text-secondary);
  line-height: 1.5;
}

/* Footer */
footer.app-footer {
  background: var(--fb-content-bg);
  border-top: 1px solid var(--fb-border);
  padding: 16px 24px;
  text-align: center;
  font-weight: 500;
  color: var(--fb-text-secondary);
  box-shadow: inset 0 1px 2px rgba(0,0,0,0.05);
  user-select: none;
  position: sticky;
  bottom: 0;
  z-index: 1000;
}

/* Scrollbar Customization */
::-webkit-scrollbar {
  width: 12px;
  height: 12px;
}

::-webkit-scrollbar-track {
  background: var(--fb-bg);
}

::-webkit-scrollbar-thumb {
  background-color: var(--fb-blue);
  border-radius: 12px;
  border: 3px solid var(--fb-bg);
  transition: background-color 0.3s ease;
}

::-webkit-scrollbar-thumb:hover {
  background-color: var(--fb-blue-dark);
}

/* Responsive Layout */

/* Mobile First: Single Column Layout */
@media (max-width: 767px) {
  .app {
    flex-direction: column;
  }
  .sidebar {
    position: fixed;
    top: 64px;
    left: -280px;
    width: 280px;
    height: calc(100vh - 64px);
    background: var(--fb-content-bg);
    box-shadow: 2px 0 10px var(--fb-shadow);
    transition: left 0.3s ease;
    z-index: 1500;
  }
  .sidebar.open {
    left: 0;
  }
  main.app-main {
    padding: 16px;
  }
}

/* Tablet Layout */
@media (min-width: 768px) and (max-width: 1023px) {
  .app {
    flex-direction: row;
  }
  .sidebar {
    position: sticky;
    top: 64px;
    height: calc(100vh - 64px);
  }
  main.app-main {
    padding: 24px;
    min-width: 0;
  }
}

/* Desktop Layout */
@media (min-width: 1024px) {
  .app {
    flex-direction: row;
  }
  .sidebar {
    display: flex;
  }
  main.app-main {
    padding: 32px 48px;
  }
}

/* Focus visible states for accessibility */
a:focus-visible,
button:focus-visible,
input:focus-visible,
select:focus-visible,
textarea:focus-visible {
  outline: 3px solid var(--fb-focus-outline);
  outline-offset: 3px;
}

/* Smooth transitions for buttons and cards */
.card,
button {
  transition-timing-function: cubic-bezier(0.22, 1, 0.36, 1);
}

/* Material Icons Base Style */
.material-icons {
  font-family: 'Material Icons';
  font-weight: normal;
  font-style: normal;
  font-size: 24px;
  line-height: 1;
  letter-spacing: normal;
  text-transform: none;
  display: inline-block;
  white-space: nowrap;
  direction: ltr;
  -webkit-font-feature-settings: 'liga';
  -webkit-font-smoothing: antialiased;
  user-select: none;
}

/* Utility classes */
.hidden {
  display: none !important;
}

.visually-hidden {
  position: absolute !important;
  height: 1px;
  width: 1px;
  overflow: hidden;
  clip: rect(1px, 1px, 1px, 1px);
  clip-path: inset(50%);
  white-space: nowrap;
  border: 0;
}

/* Badge Utility */
.badge {
  background-color: #ff3b30;
  color: #fff;
  font-weight: 700;
  font-size: 0.75rem;
  padding: 2px 8px;
  border-radius: 12px;
  user-select: none;
  display: inline-block;
  min-width: 20px;
  text-align: center;
}

/* Sticky footer shadow on mobile */
@media (max-width: 767px) {
  footer.app-footer {
    position: sticky;
    bottom: 0;
    box-shadow: 0 -2px 8px var(--fb-shadow);
  }
}

