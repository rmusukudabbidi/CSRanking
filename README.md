CSRankings Mobile App Overview
==============================

This project is a React Native implementation of the **CSRankings** website, designed specifically for mobile devices. The goal was to provide an optimized, user-friendly experience for Android and iOS users to explore and interact with computer science rankings.

* * * * *

Features
--------

-   **Homepage**: Displays a list of institutions ranked by publication data, with a search bar and dynamic filters.
-   **Institution Details**: A detailed page for each institution, showcasing faculty, publication statistics, and external links (Google Scholar, DBLP, etc.).
-   **Charts**: Interactive bar charts for visualizing publication data by research areas.
-   **About Page**: Provides information about CSRankings, including helpful links and acknowledgments.
-   **Cross-Platform Compatibility**: Fully functional on both Android and iOS.

* * * * *

Getting Started
---------------

### Installation

1.  Install the required dependencies:

    bash

    `npm install`

2.  Start the app:

    bash

    `npx expo start`

3.  Open the app in an emulator, simulator, or physical device using the Expo Go app or a development build.

* * * * *

Project Structure
-----------------

### Key Components

-   **HomeScreen.js**: Implements the homepage with a ranking list, search bar, and filter functionality.
-   **InstitutionDetails.js**: Displays detailed information about selected institutions.
-   **ChartScreen.js**: Provides dynamic bar charts for research area publication data.
-   **AboutScreen.js**: Includes information about CSRankings, useful links, and acknowledgments.

### Data Handling

-   Static JSON files (`universities.json`, `rank.json`, `subarea.json`, `faculty.json`) were created and used to simulate backend data.
-   Data was dynamically linked and parsed to maintain accurate relationships between institutions and their faculty/publications.

* * * * *

Usage
-----

1.  **Homepage**: Start by searching or filtering through the list of ranked institutions.
2.  **Institution Details**: Tap an institution to view its faculty and publication details.
3.  **Charts**: Navigate to the charts page to explore visualized data by research areas.
4.  **About Page**: Learn more about CSRankings and access external resources.

* * * * *

Testing
-------

-   **Manual Testing**: Verified all screens and features on Android and iOS simulators.
-   **Automated Testing**:
    -   Unit tests were written using **jest** and **@testing-library/react-native**.
    -   Major tests included:
        -   Verifying the rendering of components such as filters and charts.
        -   Validating navigation and data integrity.
        -   Ensuring dynamic filtering and sorting functions work correctly.

* * * * *

Future Enhancements
-------------------

1.  **Backend Integration**: Replace static JSON files with live data from a server.
2.  **Advanced Charts**: Include additional visualizations and real-time interactivity.
3.  **Responsiveness**: Improve layout optimization for tablets and larger devices.
4.  **User Profiles**: Add functionality to save preferences or favorite institutions.