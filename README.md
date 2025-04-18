backend repo :- https://github.com/VedantBhawsar/Analytical-website-backend

Project Status Report

This project is an analytics website frontend.

Key files and directories:

- `.eslintrc.js`, `.gitignore`, `.prettierrc`, `eslint.config.js`, `jsconfig.json`, `package-lock.json`, `package.json`, `postcss.config.js`, `tailwind.config.js`, `vite.config.js`: Configuration files for linting, formatting, and building the project.
- `index.html`: Main HTML file.
- `README.md`: This file (will be updated with this report).
- `vercel.json`: Vercel deployment configuration.
- `public/`: Directory for public assets.
  - `dashboard-preview.png`: Dashboard preview image.
  - `vite.svg`: Vite logo.
- `src/`: Source code directory.
  - `App.css`, `App.jsx`, `index.css`, `main.jsx`: Main application files.
  - `api/`: API related files.
    - `axios.js`: Axios configuration.
  - `assets/`: Assets directory.
    - `react.svg`: React logo.
  - `components/`: Reusable components.
    - `WebsiteIntegrationFlow.jsx`: Website integration flow component.
    - `Headers/`: Header components.
      - `Header.jsx`: Main header.
      - `PublicHeader.jsx`: Public header.
      - `components/`: Header sub-components.
        - `UserProfileDropdown.jsx`: User profile dropdown.
        - `WebsiteSwitcher.jsx`: Website switcher.
    - `Layout/`: Layout components.
      - `Footer.jsx`: Footer.
      - `Sidebar.jsx`: Sidebar.
    - `ui/`: UI components.
      - `badge.jsx`, `button.jsx`, `card.jsx`, `dialog.jsx`, `dropdown-menu.jsx`, `errorMessage.jsx`, `input.jsx`, `label.jsx`, `loadingOverlay.jsx`, `navigation-menu.jsx`, `progress.jsx`, `scroll-area.jsx`, `select.jsx`, `separator.jsx`, `table.jsx`, `tabs.jsx`: Various UI components.
  - `contexts/`: Contexts.
    - `authContext.jsx`: Authentication context.
    - `websiteContext.jsx`: Website context.
  - `hooks/`: Custom hooks.
    - `use-mobile.jsx`: Mobile detection hook.
    - `use-toast.js`: Toast hook.
  - `layouts/`: Layouts.
    - `LayoutWithPublicHeader.jsx`: Layout with public header.
    - `LayoutWithSidebar.jsx`: Layout with sidebar.
  - `lib/`: Utilities.
    - `utils.js`: Utility functions.
  - `middlewares/`: Middlewares.
    - `ProtectedRoute.jsx`: Protected route.
    - `UnprotectedRoute.jsx`: Unprotected route.
  - `pages/`: Pages.
    - `About.jsx`: About page.
    - `Home.jsx`: Home page.
    - `auth/`: Authentication pages.
      - `Siginup.jsx`: Signup page.
      - `Signin.jsx`: Signin page.
    - `Dashboard/`: Dashboard pages.
      - `Dashboard.jsx`: Main dashboard.
      - `Events.jsx`: Events page.
      - `RealTimeView.jsx`: Real-time view page.
      - `Reports.jsx`: Reports page.
      - `SessionDetails.jsx`: Session details page.
      - `SessionList.jsx`: Session list page.
      - `Settings.jsx`: Settings page.
  - `services/`: Services.
    - `authService.js`: Authentication service.
    - `websiteService.js`: Website service.

This project is a React-based web application for analytics. It features a dashboard with pages for events, real-time view, reports, session details, session list, and settings. The application uses a variety of UI components and includes authentication and website contexts. It also utilizes custom hooks for mobile detection and toast notifications. It has layouts with public headers and sidebars, and uses axios for API requests.
