#CS360-Mobile_Architecture - Android Inventory Management App
#Project Overview

The Android Inventory Management App is designed to simplify tracking and managing inventory items for users, ensuring efficiency and ease of use. This mobile-friendly application provides a comprehensive solution for monitoring stock levels, updating quantities, and receiving notifications for low inventory.

#Key Features

1. User Authentication: Secure login and account creation.
2. Inventory Management: Create, read, update, and delete inventory items.
3. Database Integration: Persistent data storage with SQLite database.
4. SMS Notifications: Optional alerts for low inventory levels.
5. User-Friendly Interface: Grid-based inventory item display for efficient management.


#User-Centered Design

The app’s user interface prioritizes simplicity and functionality to ensure a seamless user experience. Key screens include:

1. Login/Registration Screen: For secure user access.
2. Main Inventory Grid View: Displays items in an organized grid layout.
3. Item Detail/Edit Screen: Allows viewing and updating individual item details.
4. Add New Item Screen: Simplifies adding new inventory items.
5. Settings Screen: Manages app permissions, including SMS notifications.

The grid layout is designed for quick navigation, with intuitive icons and buttons enabling swift actions like adding, editing, or deleting items.

#Development Approach

Coding Strategies

1. Modular Development: Divided the app into distinct components such as authentication, database operations, and notification features.
2. Version Control: Employed Git for tracking changes and managing code collaboratively.
3. Agile Methodology: Followed iterative development cycles with frequent testing and updates.

These strategies ensure the app is well-structured, maintainable, and scalable for future enhancements.

#Testing Methodology

1. Android Emulator: Tested on multiple device configurations and Android versions.
2. Unit Testing: Validated core components like database operations and authentication.
3. User Permission Testing: Ensured smooth functionality with and without SMS permissions.
4. Edge Case Testing: Evaluated performance with empty inventories, large datasets, and unstable networks.
   
Thorough testing was integral to identifying and resolving issues, ensuring reliability and an optimal user experience across diverse scenarios.

#Challenges and Innovations

A key challenge was designing a notification system that respected user permissions. To address this, a fallback notification mechanism was implemented, allowing users without SMS permissions to receive in-app alerts for critical inventory updates. This innovation enhanced user accessibility without compromising functionality.

#Highlight: SQLite Database Integration
The integration of an SQLite database is a standout feature, showcasing:

1. Efficient Data Modeling: Tailored for inventory management.
2. CRUD Operations: Seamless implementation for creating, reading, updating, and deleting data.
3. Data Persistence: Ensures information is retained across app sessions.
4. Performance Optimization: Handles large inventories with responsive queries.

This robust backend system is vital to the app’s core functionality and demonstrates proficiency in database management.

#Conclusion
The Android Inventory Management App delivers a reliable, user-friendly solution for individuals and small business owners to manage their inventory effectively. By combining secure authentication, efficient data handling, and optional SMS notifications, the app offers versatility and adaptability to various user needs. This project serves as a practical example of thoughtful design, rigorous testing, and innovative problem-solving in mobile application development.






