### Text Editor App

Welcome to the Text Editor App repository! This project showcases my skills in full-stack web development, particularly in building a text editor application with offline capabilities using modern web technologies.

## Overview

As part of a coding bootcamp challenge, I developed a text editor application that runs in the browser. This single-page application (SPA) meets the criteria of a Progressive Web App (PWA), ensuring a seamless user experience even when offline. The app utilizes IndexedDB for data persistence, providing redundancy in case certain browser features are not supported.

**Note**: While the application is mostly complete, I encountered difficulties in deploying the server component to Render. As a result, the project is still a work in progress, and the server deployment is pending completion.

## Features

- **Offline Functionality**: Users can create, edit, and save notes or code snippets even without an internet connection, ensuring reliability and accessibility.
- **IndexedDB Integration**: The application leverages IndexedDB for storing and retrieving data, offering a robust solution for client-side storage.
- **PWA Compliance**: The app meets the requirements of a Progressive Web App, allowing users to install it as an icon on their desktop for quick access.
- **Service Worker**: A registered service worker, implemented using Workbox, ensures that static assets are pre-cached for faster loading and seamless offline usage.
- **Webpack Bundling**: JavaScript files are bundled using Webpack, optimizing performance and facilitating development.

## Deployment

The application frontend is successfully deployed to Render, showcasing the ability to deploy full-stack applications to a hosting platform. However, the server deployment is pending completion.

## Usage

To use the Text Editor App:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npm run start` to start the application.
5. Access the application in your browser.

## Issues & Contributions

If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request. Your contributions are highly appreciated!

## Credits

This project was completed as part of a coding bootcamp challenge. Credits to the bootcamp instructors and course materials for providing guidance and resources throughout the development process.

---

Thank you for visiting the Text Editor App repository! I hope you find the project informative and engaging. If you have any questions or feedback, don't hesitate to reach out.