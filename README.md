# Microfrontend Project with CI/CD Pipeline for AWS Deployment
This project demonstrates the implementation of a web application using the microfrontend architecture. Microfrontends allow for the independent development, testing, and deployment of individual frontend modules, which are then composed into a unified user interface.

## Architecture Overview
The project consists of 3 frontend modules, each representing a specific feature or functionality of the application. The main application shell serves as the container for these modules and orchestrates their composition on the user's browser.

## Technologies Used
- **Microfrontend Frameworks**: The project utilizes webpack to achieve the micro-frontend architecture  
- **AWS Services**: Deployment is done on AWS, leveraging services like AWS S3 for hosting static assets and AWS CloudFront for content delivery and caching.  
- **GitHub Actions**: Continuous Integration and Deployment (CI/CD) pipelines are set up using GitHub Actions. Each push to the repository triggers a build and deployment process to AWS.  
## Setup and Deployment
- **Clone the Repository**: Start by cloning the project repository to your local machine.
- **Install Dependencies**: Navigate to the root directory of the project and install dependencies for each frontend module using __npm install__.
- **Deployment**: To deploy the application, simply push your changes to the main branch or raise a PR against it. GitHub Actions will automatically trigger the CI/CD pipeline, building and deploying the frontend modules to AWS. Each micro-frontend is deployed separately.
