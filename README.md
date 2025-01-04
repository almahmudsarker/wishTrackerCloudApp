# Wish Tracker Cloud App

Welcome to the **Wish Tracker Cloud App**, a serverless, scalable, and user-friendly application that lets users track and manage their bucket list items. This project was built using modern AWS cloud services and React, leveraging the power of serverless architecture for optimized performance and minimal management overhead.

---

## Live Demo
Experience the app live: [Wish Tracker Cloud App](https://main.dj3yk9sp70762.amplifyapp.com)

---

## Overview
The Wish Tracker Cloud App provides an intuitive platform where users can:
- Add, update, and delete bucket list items.
- Authenticate securely for personalized user experiences.
- Upload and manage images for bucket list items.

Built on AWS Amplify, this application highlights how to integrate modern cloud technologies to create a fully functional, highly available, and cost-effective web application.

---

## Features
- **User Authentication:**
  - Secure signup, login, and session management using AWS Amplify Authentication.
- **Data Management with DynamoDB:**
  - Persistent storage of bucket list items using a serverless DynamoDB table.
- **GraphQL API with AWS AppSync:**
  - Flexible and efficient data fetching using a custom GraphQL schema.
- **Image Storage in S3:**
  - Seamless integration with AWS S3 for managing user-uploaded images.
- **AWS Amplify Hosting:**
  - Continuous deployment directly from GitHub for the frontend.

---

## Technologies and Services Used
| **Technology**       | **Purpose**                                                    |
|----------------------|---------------------------------------------------------------|
| AWS Amplify          | Frontend and backend deployment, authentication, and storage   |
| AWS AppSync          | Managing and querying GraphQL APIs                             |
| GraphQL              | Custom schema for precise and efficient data operations        |
| DynamoDB             | NoSQL database for bucket list items                           |
| S3 Bucket            | Storage for user-uploaded images                               |
| React                | Frontend development framework                                |

---

## Project Structure
```
root/
├── public/
├── src/
│   ├── components/
│   │   └── ...
│   ├── pages/
│   │   └── ...
│   ├── App.js
│   └── index.js
├── amplify/
│   ├── backend/
│   │   ├── api/
│   │   │   └── GraphQL schema
│   │   └── auth/
│   └── team-provider-info.json
├── README.md
├── package.json
└── amplify.yml
```
### Architectural Diagram
![Architectural Diagram Screenshot](./screenshots/homepage.png)
---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/wish-tracker-cloud-app.git
   cd wish-tracker-cloud-app
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure AWS Amplify:
   ```bash
   amplify init
   amplify push
   ```
4. Start the development server:
   ```bash
   npm start
   ```

---

## Screenshots
### Homepage
![Homepage Screenshot](./screenshots/homepage.png)

### User Authentication
![Login Screenshot](./screenshots/login.png)
![Verification Screenshot](./screenshots/login.png)

### Bucket List Management
![Bucket List Screenshot](./screenshots/bucket-list.png)

---

## Deployment
This project is deployed using AWS Amplify. Any changes pushed to the GitHub repository automatically trigger a new deployment.

---

## Future Enhancements
- Enhanced UI/UX with a more dynamic design.
- Notifications and reminders for pending tasks.
- Custom domain registration.

---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Acknowledgments
Special thanks to AWS and the React community for providing the tools and resources to build this project.
