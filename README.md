\# Optimized HubSpot CMS Theme Architecture



\## 🚀 Project Overview

This repository contains a \*\*production-grade, optimized HubSpot CMS theme architecture\*\* designed for scalability, performance, and developer experience. It serves as a robust boilerplate for building enterprise-level HubSpot websites, featuring a modular component system and strictly typed field definitions.



Built using \*\*HubSpot Local Development tools\*\* (CLI), this architecture bypasses the standard drag-and-drop builder limitations to deliver clean, semantic code.



\## ⚡ Key Technical Features



\### 🛠 Architecture \& Tooling

\- \*\*Local Development Workflow\*\*: Built using `@hubspot/cli` for version-controlled, iterative development.

\- \*\*Modular Design Pattern\*\*: Decoupled modules and sections for maximum reusability across templates.

\- \*\*JSON-Driven Configuration\*\*: Strict `fields.json` definitions for type-safe content management.

\- \*\*Brand Settings Inheritance\*\*: Dynamic color/font inheritance from HubSpot Brand Settings (`brand\_settings.colors`) for global consistency.



\### 🎨 Frontend \& Performance

\- \*\*Optimization First\*\*: Achieving \*\*90+ Lighthouse scores\*\* via lazy-loading, optimized asset delivery, and semantic HTML.

\- \*\*Accessibility Compliance\*\*: Native WCAG 2.1 compliance (ARIA roles, semantic landmarks, skip-links).

\- \*\*HubL \& CSS Scope\*\*: Scoped CSS injection (`{% require\_css %}`) to prevent style leakage and reduce unused CSS.



\### 🧩 Component Library

\- \*\*Custom Team Module\*\*: Advanced HubL logic with user-configurable styles (borders, layouts).

\- \*\*Dynamic Drag-and-Drop Areas\*\*: Flexible `dnd\_area` implementation for marketer autonomy without breaking design systems.



\## 📂 Directory Structure

├── css/ # Global styles \& CSS variables

├── modules/ # Reusable custom modules (HubL + JSON)

├── templates/ # Page templates \& base layouts

├── partials/ # Shared components (Header/Footer)

├── fields.json # Global theme settings configuration

└── theme.json # Theme metadata \& inheritance logic





\## 🔧 Deployment



1\. \*\*Install CLI\*\*: `npm install -g @hubspot/cli`

2\. \*\*Authenticate\*\*: `hs init`

3\. \*\*Deploy\*\*:

hs upload . my-optimized-theme



text



\## 👨‍💻 Author

\*\*Brandon Nkabinde\*\*

\*Full-Stack HubSpot Developer, HubSpot Engineer \& Product Manager\*

