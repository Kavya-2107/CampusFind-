# CampusFind – Smart Campus Lost & Found Management Platform

CampusFind is a web-based Lost & Found management platform designed to help students and faculty report, discover, and claim lost belongings within a college campus.

The platform provides a centralized-looking interface for managing Lost and Found listings, searching for items, submitting claims, and tracking reports. It is developed as a frontend college project using HTML, CSS, Vanilla JavaScript, and browser LocalStorage.

## 📌 Project Overview

Losing personal belongings on campus can be frustrating, and traditional methods of finding lost items are often unorganized and time-consuming.

CampusFind aims to simplify this process by providing a digital platform where users can report lost or found items, browse listings, and submit claims for found belongings.

## ✨ Features

- **User Authentication:** Registration and login functionality.
- **User Roles:** Student, Faculty, and Administrator roles.
- **Report Lost Items:** Submit details of lost belongings.
- **Report Found Items:** Add details of items found on campus.
- **Browse Listings:** View reported Lost and Found items.
- **Search and Filters:** Search using keywords and filter by item type and category.
- **Item Details:** View complete information about individual listings.
- **Claim Management:** Submit claims for found items.
- **Claim Approval/Rejection:** Item owners can approve or reject pending claims.
- **My Listings:** Manage and view your own reports and related claims.
- **Dashboard:** View personal listing statistics and recent activity.
- **Smart Matching:** Rule-based JavaScript logic identifies possible matches between Lost and Found listings.
- **Admin Dashboard:** View statistics and records of registered users, reports, and claims.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and responsive layouts |
| JavaScript | Functionality and application logic |
| LocalStorage | Browser-based data storage |
| Web Crypto API | SHA-256 password hashing in the prototype |

## 📂 Project Structure

```text
CampusFind/
│
├── index.html
├── login.html
├── register.html
├── dashboard.html
├── report.html
├── browse.html
├── my-listings.html
├── item-details.html
├── admin.html
│
├── css/
│   ├── style.css
│   ├── auth.css
│   ├── report.css
│   ├── browse.css
│   ├── my-listings.css
│   ├── item-details.css
│   ├── dashboard.css
│   └── admin.css
│
├── js/
│   ├── script.js
│   ├── auth.js
│   ├── report.js
│   ├── browse.js
│   ├── my-listings.js
│   ├── item-details.js
│   ├── dashboard.js
│   └── admin.js
│
└── assets/
```

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Extract the project folder if downloaded as a ZIP.
3. Open the `CampusFind` folder in Visual Studio Code.
4. Open `index.html` in your browser, preferably using the Live Server extension.
5. Register a new account or log in to explore the application.

## 💾 Data Storage

CampusFind uses browser LocalStorage to store application data, including user information, reports, claims, and session details.

Since the project does not use a backend or centralized database, stored data is limited to the same browser and website origin. It is not synchronized across different devices or browsers.

## 🔍 Smart Matching

The Smart Matching module uses rule-based JavaScript comparisons to identify potentially related Lost and Found listings.

It considers factors such as:
- Item category
- Item name
- Common words in descriptions
- Location information

This is a rule-based matching mechanism and does not use artificial intelligence or machine learning.

## ⚠️ Current Limitations

- No backend server or centralized database.
- No cross-device data synchronization.
- No real-time notifications.
- No in-app chat or messaging.
- No AI-based image recognition.
- No interactive campus map.
- No automated ownership verification.

## 🔮 Future Scope

Possible future enhancements include:

- Backend integration and centralized database.
- Secure authentication and improved access control.
- Cross-device synchronization.
- Email and notification functionality.
- In-app messaging between users.
- AI-based image matching.
- Interactive campus map integration.
- Listing editing and item resolution functionality.
- Enhanced administrative management.

## 🎯 Project Objective

The main objective of CampusFind is to provide a simple and organized digital platform for managing lost and found belongings within a college campus, making it easier for students and faculty to report items and reconnect belongings with their owners.

## 👩‍💻 Developer

**Kavya Sunil Chanap**

B.Tech – Computer Science and Engineering

Maulana Azad National Institute of Technology (MANIT), Bhopal

## 📄 License

This project was developed for academic purposes.

