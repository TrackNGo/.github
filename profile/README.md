# Smart Public Transport App
A comprehensive digital solution for public transportation in Sri Lanka, providing real-time bus tracking, route information, fare estimation, lost and found management, and user feedback. Built for enhancing commuter convenience, security, and transparency in the public transit system.

---

## 📑 Table of Contents
- [Smart Public Transport App](#smart-public-transport-app)
  - [📑 Table of Contents](#-table-of-contents)
  - [Features](#features)
    - [User Features](#user-features)
    - [Conductor Features](#conductor-features)
    - [Admin Features](#admin-features)
  - [🎥 Demo](#-demo)
    - [Live Application Walkthrough](#live-application-walkthrough)
  - [🚀 Tech Stack](#-tech-stack)
    - [Backend](#backend)
    - [Frontend](#frontend)
    - [Authentication \& Validation](#authentication--validation)
  - [📦 Package Management](#-package-management)
    - [Adding Dependencies](#adding-dependencies)
    - [Updating Dependencies](#updating-dependencies)
  - [🎨 Interface Designs](#-interface-designs)
    - [Conductor Interfaces](#conductor-interfaces)
    - [User Interfaces](#user-interfaces)
    - [Admin Interfaces](#admin-interfaces)
  - [📚 Documentation Repository](#-documentation-repository)
  - [👥 Team Members](#-team-members)
    - [Troubleshooting Common Issues](#troubleshooting-common-issues)
    - [🤝 Contributing](#-contributing)
    - [Commit Message Convention](#commit-message-convention)
    - [Types:](#types)
    - [Rules:](#rules)
    - [Breaking Changes:](#breaking-changes)
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

## 🎥 Demo 

### Live Application Walkthrough
[![TrackNGo Smart Public Transport Demo](https://img.youtube.com/vi/boOtgpuamzw/0.jpg)](https://www.youtube.com/watch?v=boOtgpuamzw)

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

<!-- ### 🚦 Getting Started
## Prerequisites
- Node.js: [Download here](#https://nodejs.org/).
- MongoDB: Local or cloud-based MongoDB setup. [See MongoDB Atlas](https://www.mongodb.com/atlas/database).
- Postman: For API testing (optional). [Download here](https://www.postman.com/).

--- 

<!-- ### Setup Steps
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


## 🎨 Interface Designs

### Conductor Interfaces
| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
| **(a) Conductor Login**<br>![Conductor Login](../Screenshots/Conductor/(a)%20Conductor%20Login.png) | **(b) Change Password**<br>![Change Password](../Screenshots/Conductor/(b)%20Change%20Password.png) | **(c) Conductor Dashboard**<br>![Conductor Dashboard](../Screenshots/Conductor/(c)%20Conductor%20Dashboard.png) |
| **(d) Emergency Report View**<br>![Emergency Report View](../Screenshots/Conductor/(d)%20Emergency%20Report%20View.png) | 

---

### User Interfaces
| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
| **(a) User HomePage**<br>![User HomePage](../Screenshots/User/a.%20User%20HomePage%20.png) | **(b) Bus Search By Route**<br>![Bus Search By Route](../Screenshots/User/b.%20Bus%20Search%20By%20Route.png) | **(c) Bus Fare Estimator**<br>![Bus Fare Estimator](../Screenshots/User/c.%20Bus%20Fare%20Estimator.png) |
| **(d) Bus Tracking 01**<br>![Bus Tracking 01](../Screenshots/User/d.%20Bus%20Tracking%2001.png) | **(e) Bus Tracking 02**<br>![Bus Tracking 02](../Screenshots/User/e.%20Bus%20Tracking%2002.png) | **(f) Lost and Found**<br>![Lost and Found](../Screenshots/User/f.%20Lost%20and%20Found.png) |
| **(g) All Lost and Found Items**<br>![All Lost and Found Items](../Screenshots/User/g.%20All%20Lost%20and%20Found%20Items.png) | **(h) Report Found Item**<br>![Report Found Item](../Screenshots/User/h.%20Report%20Found%20Item.png) | **(i) Report Lost Item**<br>![Report Lost Item](../Screenshots/User/i.%20Report%20Lost%20Item.png) |
| **(j) Time Table**<br>![Time Table](../Screenshots/User/j.%20Time%20Table.png) | **(k) Time Table View**<br>![Time Table View](../Screenshots/User/k.%20Time%20Table%20View.png) | **(l) Submit Report**<br>![Submit Report](../Screenshots/User/l.%20Submit%20Report.png) |
| **(m) News View**<br>![News View](../Screenshots/User/m.%20News%20View.png) | **(n) Contact Us**<br>![Contact Us](../Screenshots/User/n.%20Contact%20Us.png) |

---

### Admin Interfaces
| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
| **(a) Admin Login**<br>![Admin Login](../Screenshots/Admin/a.%20Admin%20Login.png) | **(b) Admin Dashboard**<br>![Admin Dashboard](../Screenshots/Admin/b.%20Admin%20Dashboard.png) | **(c) Admin Accounts**<br>![Admin Accounts](../Screenshots/Admin/c.%20Admin%20Accounts.png) |
| **(d) Admin Change Password**<br>![Admin Change Password](../Screenshots/Admin/d.%20Admin%20Change%20Password.png) | **(e) Admin All Accounts**<br>![Admin All Accounts](../Screenshots/Admin/e.%20Admin%20All%20Accounts.png) | **(f) Admin Create Account**<br>![Admin Create Account](../Screenshots/Admin/f.%20Admin%20Create%20Account.png) |
| **(g) Bus Dashboard**<br>![Bus Dashboard](../Screenshots/Admin/g.%20Bus%20Dashboard.png) | **(h) Admin Bus View**<br>![Admin Bus View](../Screenshots/Admin/h.%20Admin%20Bus%20View.png) | **(i) Admin Add Bus**<br>![Admin Add Bus](../Screenshots/Admin/i.%20Admin%20Add%20Bus.png) |
| **(j) Admin Add Bus Route**<br>![Admin Add Bus Route](../Screenshots/Admin/j.%20Admin%20Add%20Bus%20Route.png) | **(k) Bus Details Edit**<br>![Bus Details Edit](../Screenshots/Admin/k.%20Bus%20Details%20Edit.png) | **(l) Admin Timetable**<br>![Admin Timetable](../Screenshots/Admin/l.%20Admin%20Timetable.png) |
| **(m) Add Timetable**<br>![Add Timetable](../Screenshots/Admin/m.%20Add%20Timetable.png) | **(n) Fare Estimate View**<br>![Fare Estimate View](../Screenshots/Admin/n.%20Fare%20Estimate%20View.png) | **(o) Add Fare Estimate**<br>![Add Fare Estimate](../Screenshots/Admin/o.%20Add%20Fare%20Estimate%20%20.png) |
| **(p) Reports View**<br>![Reports View](../Screenshots/Admin/p.%20Reports%20View.png) | **(q) Report View**<br>![Report View](../Screenshots/Admin/q.%20Report%20View.png) | **(r) Technical and Requests**<br>![Technical and Requests](../Screenshots/Admin/r.%20Technical%20and%20Requests.png) |
| **(s) View Submission**<br>![View Submission](../Screenshots/Admin/s.%20View%20Submission.png) |

## 📚 Documentation Repository
The project documentation includes:
- Initial Project Proposal Document
- Proposal Presentation Deck
- Progress Presentation Slides
- Final Presentation Materials
- Final Technical Report
- All interface design specifications
- System architecture diagrams
- User manuals and technical guides

---

## 👥 Team Members
1. **Mr. Nalawansa U.K** - 2020/ICT/07
2. **Mr. Bandara R.M.M.T** - 2020/ICT/49
3. **Mr. Kalhara K.A.T** - 2020/ICT/32
4. **Mr. Naveen P.R** - 2020/ICT/23
5. **Ms. M.T.F.Shazna** - 2020/ICT/118
6. **Ms. Dhanapala D.M.C.S** - 2020/ICT/36
7. **Ms. Perera KNR** - 2020/ICT/88

**Project Supervisor:**  
Mr. K. Mathanaharan
Lecturer 
University of Vavuniya

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
