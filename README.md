# GSU-Share
The primary objective of this project is to raise awareness about these resources and encourage students to make the most of them during their time at Georgia State University.

IV.	Description

Key features of the GSU Share website include:
1.	Home Page: The landing page of the website serves as an entry point for users, displaying an overview of the available resources and latest updates, along with options to log in or sign up for an account.
2.	Login / Sign Up: Users can create an account using their email address and a password. Upon successful registration, they can log in to access their personal dashboard, where they can post and view resources, and manage their account settings.
3.	Resource Categories: The resources are organized into distinct categories, such as academic support, extracurricular activities, and wellness services, allowing users to quickly locate relevant information.
4.	Admin and User Permissions: The website features a user management system that differentiates between admin and user roles. Admins have full access to all features, including the ability to delete users and resources that do not comply with the website's policies. Users, on the other hand, can post and view resources but have limited moderation capabilities.
5.	Other Resources: This section of the website highlights additional on campus and external resources, that may be of interest to GSU students and staff.
6.	About Us Page: The About Us page provides an overview of the mission, vision, and objectives of GSU Share, as well as a brief introduction to the team behind the platform.
7.	Privacy Policy: The Privacy Policy page outlines the website's commitment to protecting user data, detailing how personal information is collected, used, and stored.
8.	Contact Us Page: Users can reach out to the GSU Share team through a contact form provided on this page, allowing for efficient communication and feedback.
9.	Terms and Conditions Page: This page outlines the rules and guidelines governing the use of GSU Share, ensuring that users understand their rights and responsibilities while using the platform.
By incorporating these features, the GSU Share website aims to provide a comprehensive and easily navigable platform for students and staff at Georgia State University, fostering a collaborative and supportive community where users can effectively access and share information about available resources.

V.	Installation
This section outlines the steps and modules required to execute the GSU Share web application. The current setup hosts the website locally, and we plan to transition to IONOS, a cloud server renowned for its startup-friendly features.
Step 1: Set up the local development environment To begin, ensure that you have a suitable Integrated Development Environment (IDE) installed on your computer. Popular choices include Visual Studio Code, Sublime Text, or Atom.

Step 2: Install necessary software and dependencies For this project, we will be using the following technologies and dependencies:
•	Frontend: HTML, CSS, and JavaScript
•	Backend: Node.js and Express.js
•	Database: MongoDB
Ensure that you have Node.js installed on your computer. If not, download the latest version from the official Node.js website (https://nodejs.org/). Once installed, use the Node Package Manager (npm) to install Express.js and other required dependencies.

Step 3: Clone the project repository Clone the project repository from your preferred version control system, such as GitHub, GitLab, or Bitbucket, to your local computer.

Step 4: Install project dependencies Navigate to the project directory using the command line or terminal and run the following command to install all necessary dependencies:
Copy code:
npm install

Step 5: Set up the MongoDB database Install MongoDB on your local machine by following the official MongoDB installation guide (https://docs.mongodb.com/manual/installation/). After installation, create a database and collection for the GSU Share project.

Step 6: Configure environment variables Create a .env file in the project directory to store sensitive information, such as database credentials and session secrets. Make sure to include this file in your .gitignore to prevent accidental exposure of sensitive data.

Step 7: Start the development server Run the following command in the project directory to start the development server:
