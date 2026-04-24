# Licensing Expo 2026 — Exhibitor Guide

This is a Single Page Application (SPA) designed specifically for the Licensing Expo 2026. It provides an interactive exhibitor directory to help users efficiently browse, filter, and bookmark key exhibitors, maximizing the ROI of attending the expo.

## ✨ Core Features

*   **🌓 Dark/Light Mode Toggle**: Supports both Light and Dark themes to adapt to different environments and personal preferences.
*   **📊 Data Dashboard**: A top-level overview showing the count of Tier 1 to Tier 3 exhibitors, allowing quick grasp of key targets.
*   **🔍 Powerful Search & Filter System**:
    *   **Priority Filter (Tier)**: Categorizes exhibitors into Tier 1 (Must-visit), Tier 2 (Priority), Tier 3 (Explore), and Tier 4 (Skip).
    *   **Category Filter**: Filters by IP attributes, such as Gaming, Anime, Entertainment, Sports, Lifestyle, Services, etc.
    *   **Keyword Search**: Quickly search for exhibitor names or related descriptions.
*   **🔀 Flexible Sorting**: Supports sorting by Priority (Tier), Name (A-Z), Category, and Booth number.
*   **👀 Dual View Modes**:
    *   **Table View**: Best for quickly scanning a large amount of information.
    *   **Card View**: Provides richer visual presentation and detailed descriptions.
*   **⭐ Bookmarking**: Click the star icon to bookmark an exhibitor, and use the "Bookmark" button to quickly filter out your saved targets.
*   **📱 Responsive Web Design (RWD)**: Perfectly adapts to desktops, tablets, and mobile phones, featuring a dedicated sidebar filter menu for mobile users.

## 🚀 How to Use

This project is developed using pure front-end technologies (Vanilla HTML/CSS/JavaScript), requiring no backend environment or dependency installations.

1.  **Download/Clone the Project**: Download the project files to your local machine.
2.  **Open the File**: Simply double-click `index.html` (or your saved HTML file) to run it in any modern web browser (e.g., Chrome, Safari, Edge, Firefox).

## 🛠 Tech Stack

*   **HTML5**: Semantic structure.
*   **CSS3**: 
    *   Utilizes CSS Custom Properties (Variables) to unify the design system and manage light/dark theme colors.
    *   Pure CSS implementation for smooth transition animations and flexible Grid/Flexbox layouts.
*   **JavaScript (Vanilla)**: Handles DOM manipulation, data filtering, pagination logic, and state management without any third-party framework dependencies.

## 📂 Data Structure Explanation

Exhibitor data is built-in within the `DATA` constant in the JavaScript section. The fields in the array correspond to the following:
`[Exhibitor Name, Category, Priority(Tier), Booth, Description/Angle, Tag(e.g., "New"), Country, Role/Type, Logo Image URL, Exhibitor Official Link]`

To update the data, simply open the HTML file with a text editor, locate the `const DATA = [...]` block, and modify the array content. The changes will automatically apply to the entire site.
