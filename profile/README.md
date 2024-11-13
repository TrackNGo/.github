# Smart Public Transport App
A comprehensive digital solution for public transportation in Sri Lanka, providing real-time bus tracking, route information, fare estimation, lost and found management, and user feedback. Built for enhancing commuter convenience, security, and transparency in the public transit system.

---

## 📑 Table of Contents
- [Features](#features)
  - [User Features](#user-features)
  - [Conductor Features](#conductor-features)
  - [Admin Features](#admin-features)
- [🚀 Tech Stack](#-tech-stack)
  - [Backend](#backend)
  - [Frontend](#frontend)
  - [Authentication & Validation](#authentication--validation)
- [📦 Package Management](#-package-management)
- [🚦 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Setup Steps](#setup-steps)
  - [Troubleshooting Common Issues](#troubleshooting-common-issues)
- [🤝 Contributing](#-contributing)
  - [Commit Message Convention](#commit-message-convention)
- [Conclusion](#conclusion)

---

## Features

### User Features
- **Real-Time Tracking**: View live bus locations on a map.
- **Route Information**: Receive route suggestions by selecting origin and destination points.
- **Schedule & Estimated Times**: Access accurate bus schedules and estimated arrival times.
- **Fare Estimation**: Calculate fares for different routes.
- **Notifications**: Receive updates on delays, route changes, and announcements.
- **Lost and Found Reporting**: Report and view lost or found items with bus-specific details.
- **Feedback & Ratings**: Provide feedback and rate transport services.

### Conductor Features
- **Location Updates**: Update live location data to facilitate accurate tracking.
- **Lost and Found Management**: Monitor lost and found reports specific to assigned routes.
- **Passenger Notifications**: Send and receive notifications regarding changes or alerts on routes.

### Admin Features
- **Route Management**: Add, update, or delete routes.
- **Schedule Management**: Manage and update bus schedules.
- **Fare Management**: Adjust fare rates based on route and distance.
- **User & Conductor Activity Reports**: Monitor user activity, lost item claims, and feedback metrics.

---
## 🚀 Tech Stack

### Backend
- **Node.js**: JavaScript runtime for backend server.
- **Express.js**: Backend API framework.
- **MongoDB**: NoSQL database for efficient data storage.
- **Mongoose**: ODM library for MongoDB integration.
- **bcryptjs**: Password hashing library.
- **dotenv**: Manages environment variables.

### Frontend
- **React**: Library for building interactive UIs.
- **Redux & Redux Toolkit**: State management for efficient data handling.

### Authentication & Validation
- **JWT Authentication**: Secures API endpoints with token-based authentication.

---
## 📦 Package Management

### Adding Dependencies
To add a new package:
```sh
npm install [package-name]
```
### Updating Dependencies
To update all dependencies:
```sh
npm update

```

---

### 🚦 Getting Started
## Prerequisites
- Node.js: [Download here](#https://nodejs.org/).
- MongoDB: Local or cloud-based MongoDB setup. [See MongoDB Atlas](https://www.mongodb.com/atlas/database).
- Postman: For API testing (optional). [Download here](https://www.postman.com/).

---

### Setup Steps
<!--
1. Clone the repository:

    ```sh
    git clone https://github.com/SGopinath89/IT22242024taskflow.git
    ```

2. Navigate to the Project Directory:

    ```sh
    cd IT22242024taskflow
    ```

3. Open two Command terminals.

4. In the first terminal, navigate to the backend directory and install packages:

    ```sh
    cd backend
    npm install
    ```

5. Create a `.env` file in the backend directory similar to `.env.sample` and enter the required variables:

    ```env
    MONGODB_URI="mongodb://localhost:27017/mydb"
    PORT=3000
    JWT_SECRET=mysecretkey
    TOKEN_EXPIRE_TIME=xh
    ```

    **To generate the `JWT_SECRET`, use the following command:**

    ```sh
    node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"
    ```

6. Start the backend server:

    ```sh
    npm run start
    ```

7. Switch to the second terminal. Navigate to the frontend directory and install packages:

    ```sh
    cd frontend
    npm install --force
    ```

    **Note:** `--force` is required to install the packages. Ignore the Vulnerabilities Warning.

8. Create a `.env` file in the frontend directory similar to `.env.sample` and enter the required variables:

    ```env
    REACT_APP_BACKEND_URL=http://localhost:port
    ```

    **Note:** Replace `port` with the backend server port number.

9. Start the client:

    ```sh
    npm run start
    ```

This command will start the server, and you can access the application at `http://localhost:3000`. !-->
---

### Troubleshooting Common Issues

- MongoDB Connection Issues: Verify MONGODB_URI and ensure MongoDB is running.
- Port Conflicts: Modify PORT in .env to resolve any conflicts.

---
### 🤝 Contributing

Contribution Steps
- Fork the repository.
- Create a feature branch.
- Commit changes following the commit message convention.
- Push changes and create a Pull Request.

  
### Commit Message Convention
This project follows Conventional Commits.  
The Conventional Commits specification provides a way to create a consistent commit history, making it easier to automate release notes and versioning.  

A commit message must have the structure  
```sh 
<type>(<scope>): <description>.
```

- type: Describes the nature of the change (e.g., feat, fix, docs, style, refactor, test, chore).
- scope: An optional section specifying the part of the codebase affected (e.g., parser, button, api). This is usually in parentheses.
- description: A short, imperative mood description of what was done (e.g., "add new login validation").

### Types:
- feat: New feature  
- fix: Bug fix  
- docs: Documentation changes only  
- style: Changes that don’t affect meaning (e.g., white-space, formatting)  
- refactor: Code changes that neither add a feature nor fix a bug   
- test: Adding or modifying tests   
- chore: Updates to build process or auxiliary tools  

### Rules:
- Use lowercase for types and scopes.
- Keep descriptions short (under 50 characters if possible).
- Begin the description with a lowercase letter.
- Don’t end the description with a period.

### Breaking Changes:
Indicate breaking changes with a BREAKING CHANGE section in the footer or within the commit message if the change introduces incompatibility with the previous version.
- For more details, refer to the [Conventional Commits Specification](https://www.conventionalcommits.org).

### Conclusion
The Smart Public Transport App marks a significant advancement in modernizing and
improving public transportation in Sri Lanka, with a particular emphasis on bus services. As
commuters increasingly demand more accessible, efficient, and real-time transport
information, the need for such a solution has become clear. By tackling major issues like poor
scheduling, the absence of real-time tracking, and inefficient routes, the app provides a strong
solution that benefits both transport operators and users
