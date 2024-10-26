# React App with AWS Amplify: Serverless Deployment 
![aws-amplify-arch-diagram](https://github.com/user-attachments/assets/7fd05ab3-5b14-4f95-a1be-54c40649afc1)

# Project Architecture:

# Introduction
In this project, we will develop a modern web application using React, one of the most popular JavaScript libraries for building user interfaces. To streamline our development and deployment process, we will leverage AWS Amplify, a comprehensive platform that provides tools and services for building scalable applications. AWS Amplify simplifies the integration of various backend functionalities, including authentication, storage, and APIs, allowing us to focus on creating a seamless user experience. By the end of this project, we will have a fully functional, deployed React application that showcases the capabilities of AWS Amplify in facilitating efficient app development and deployment.

# Why Use AWS Amplify for This Project?
AWS Amplify simplifies the process of deploying full-stack web applications by providing ready-to-use backend services, including hosting, authentication, API management, and data storage. By using Amplify, you can focus on building the application’s functionality rather than managing infrastructure.

# Tech Stack:
This project uses the following services and technologies: \
•	AWS Amplify: Provides end-to-end services for hosting and managing the web application. \
•	AWS AppSync: Facilitates real-time API creation and management. \
•	React: The frontend framework used to build the web application. \
•	Node.js & npm: For managing dependencies and running the React app. \
•	Git & GitHub: Version control and repository hosting.

# Major Advatages of using AWS Amplify:
1.	Streamlined Development Workflow: Amplify provides a comprehensive set of tools and libraries that simplify the development process. Developers can focus on building features rather than worrying about infrastructure management.
	
2.	Continuous Deployment: Amplify supports CI/CD workflows, enabling automatic deployment of updates whenever changes are made in the code repository. This ensures that the latest code is always available in production.

3. Security Best Practices: Amplify helps in implementing security best practices, such as user authentication and authorization, with minimal configuration. This is crucial for protecting applications and user data.

4. The major advantage is With AWS Amplify, you don’t have to manually configure SSL certificates using ACM or other methods, as it automatically manages SSL certificates to ensure the security of your applications.

# Problem Statement or Use Case
Web applications today require features like user authentication, data storage, and API integration. Setting up and managing these services can be challenging, especially for scalability and real-time capabilities. Using AWS Amplify simplifies this by offering a fully managed backend that integrates seamlessly with the frontend.

# Step-by-Step Implementation
Tasks:

# Overview
AWS Amplify offers a Git-based CI/CD workflow for building, deploying, and hosting single-page web applications or static sites with backends. When connected to a Git repository, Amplify determines the build settings for both the frontend framework and any configured backend resources and automatically deploys updates with every code commit.

you will start by creating a new React application and pushing it to a GitHub repository. You will then connect the repository to AWS Amplify web hosting.

# Step 1:
Open aws console and search for aws amplify:
![step1](https://github.com/user-attachments/assets/b3321186-b54a-411e-bc17-4640affd347b)

# Step 2:
Choose **Github** as a source provider and click next.
![step2](https://github.com/user-attachments/assets/7336485a-8c56-496a-b56e-579ea118f957)


# Step 3:
Authenticate with github account and choose the repo which has your source code to deploy.
![step3](https://github.com/user-attachments/assets/e6bba2a2-844e-4eab-b176-d352755eebed)

# Step 4:
Choose your repo and branch appropriately.
![step4](https://github.com/user-attachments/assets/8b5bfcdc-95fa-484b-b794-9a639921feec)

# Step 5:
Leave the settings as deafult and click next.
![step5](https://github.com/user-attachments/assets/078ede76-d9e0-4f90-8014-319ed7ea3de5)

![step6](https://github.com/user-attachments/assets/f675366d-1a77-4ef7-ba05-3c057b8e0e68)

click on save and deploy

# Step 6:

Application started to build and deploy:
![step7](https://github.com/user-attachments/assets/b3e562cf-ce06-4e55-a376-a772abc94068)


![step8](https://github.com/user-attachments/assets/e3008d59-7f49-4ee3-8a93-5bc30f194787)


# Step 7:

Aplication got succesfully build and deployed:
![step9](https://github.com/user-attachments/assets/26c4b436-f748-4fab-9388-e8763a19c937)

![step10](https://github.com/user-attachments/assets/d0808073-8d42-43bb-8f03-132937761ed9)


# Click on the domain URL to access your application
![step11](https://github.com/user-attachments/assets/17e8c946-8555-4ceb-923d-7e0e7b59067d)

# We are able to access the app successfully:
![app-deployed](https://github.com/user-attachments/assets/d8e2c5a2-c4b2-43c0-9aad-edd34ab261ab)


# AWS Amplify automatically handles the SSL certificates making sure our application is secured:

![conn_sec](https://github.com/user-attachments/assets/b4c8bdb3-35f1-4007-ad9a-53b176a24610)

![conn_sec1](https://github.com/user-attachments/assets/da6e38f9-f549-4e59-b1fc-80625ba62935)
























