# InventoryApp

OVERVIEW
The app I developed is an Inventory Management App, designed to help users track and manage their inventory more efficiently. The primary goal was to create a simple yet functional application that enables users to store, view, and manage the quantities of items in their inventory, with the added benefit of receiving alerts when stock is low. This app was specifically designed to address the need for a user-friendly solution for personal or small business inventory tracking.

FEATURES
To support user needs and provide a user-centered UI, I designed several key screens:

    Main Screen: Displays the list of inventory items with a grid view, making it easy to scan and identify items. Each item has a quantity and can be updated directly from this screen.

    Add Item Screen: Allows users to add new inventory items, complete with details like name and quantity.

    Low Stock Alert: If a user’s stock of an item is running low, they receive an SMS alert to notify them of the issue.

    Permissions Screen: Ensures that the app requests the necessary permissions from the user (e.g., SMS permissions).
    
The designs were kept minimalistic, with clean, simple layouts that are easy to navigate. I used wireframes in the planning stage to ensure the UI was intuitive, and kept accessibility in mind, using larger fonts and touch-friendly buttons. The design was successful because users could quickly understand how to interact with the app, and the interface provided clear, easily accessible information about their inventory status.

CODING APPROACH
For coding, I focused on breaking down the app into manageable components, starting with the database setup, followed by building the UI screens, and finally, implementing the SMS notification feature. I followed a modular approach, ensuring that each feature (such as adding an item or sending an SMS) could be developed, tested, and updated independently. I used Git for version control and Android Studio as the main development environment, which allowed me to stay organized and track changes efficiently. The strategies I used, like incremental development and modularization, can be applied in future projects to improve organization and minimize errors.

TESTING
To ensure the functionality of my code, I tested both the UI and backend extensively. I manually tested the app on different devices and emulators to confirm that all screens were responsive and that interactions (like adding an item or receiving an SMS alert) worked as intended. I also conducted unit testing on the database operations to ensure data integrity. This process was crucial because it helped me identify and fix bugs, such as incorrect handling of null values in the database, and confirmed that the app’s features were functional in real-world scenarios.

INNOVATION AND CHANGES
During the development, one challenge I had to innovate around was handling the SMS permission in a way that provided a smooth user experience. Initially, I struggled with ensuring that users would be prompted for the correct permissions at the right time without interrupting their workflow. I had to tweak the logic for permission requests and integrate feedback messages to ensure users were informed and confident in allowing the permissions. This taught me the importance of clear communication with the user and anticipating potential hurdles before they occur.

KNOWLEDGE AND SKILLS DEMONSTRATION 
I believe the database management component of the app is where I demonstrated my knowledge, skills, and experience most effectively. Designing the database schema, ensuring efficient querying, and implementing the CRUD (Create, Read, Update, Delete) operations taught me how to manage and manipulate data efficiently. I also integrated real-time updates to the UI based on database changes, which was an important feature for keeping the app dynamic and responsive to user input. This component highlights my ability to design a scalable backend while maintaining a seamless user experience on the frontend.
