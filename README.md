# ✈️ EaseMyTrip – Flight Booking Web Application

A full-stack flight booking web application inspired by EaseMyTrip, developed to provide users with a simple and convenient flight booking experience. The application includes flight search, user authentication, booking functionality, simulated payment processing, and an admin dashboard.

## 📌 About the Project

EaseMyTrip is a flight booking web application that allows users to search for flights based on their travel preferences, view available flights, and complete a simulated booking process.

The application also provides an administrative dashboard to manage flight details, registered users, and booking-related information.

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| ODM | Mongoose |
| Development Tools | VS Code, MongoDB Compass, Git, GitHub |

## ✨ Features

### 👤 User Features
- User registration and login
- Search flights by source and destination
- Select travel date and travel class
- Choose the number of adults and infants
- View available flights
- Apply discount coupon codes
- Simulated payment process
- Generate booking bills

### 🔐 Admin Features
- Admin login
- View registered users
- Add new flight details
- Update existing flight information
- Delete flight details
- Manage flight records
- View revenue dashboard

## 📸 Project Screenshots

Explore the different modules and interfaces of the application.

### 1. Home Page

The landing page provides the flight search interface and booking options.

![Home Page](Screenshots/index.png)

![Home Page](Screenshots/index%20(2).png)

### 2. Flight Search and Booking

Users can enter their travel details and search for available flights.

![Flight Search](Screenshots/flight.png)

![Flight Booking](Screenshots/booking.png)

### 3. User Authentication

User registration and login interfaces.

![User Login](Screenshots/userlog.png)

![User Registration](Screenshots/usersig.png)

### 4. Admin Authentication

Secure login interface for accessing the admin panel.

![Admin Login](Screenshots/adlog.png)

### 5. Admin Dashboard

The dashboard provides an overview of administrative and revenue-related information.

![Admin Dashboard](Screenshots/ad%20dash.png)

### 6. User Management

Displays registered user information for administrative management.

![User Management](Screenshots/use.png)

### 7. Flight Management – CRUD Operations

Allows the administrator to create, read, update, and delete flight records.

![Flight Management](Screenshots/crud.png)

### 8. Booking Details

Displays relevant booking information.

![Booking Details](Screenshots/det.png)

### 9. Payment and Bill Generation

Demonstrates the simulated payment process and generated booking bill.

![Payment Page](Screenshots/pay.png)

![Generated Bill](Screenshots/bill.png)

### 10. Database Management

MongoDB collection views used for storing and managing application data.

![Database Collections](Screenshots/collect.png)

![Collection Details](Screenshots/coll.png)

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

**Step 2: Navigate to the project directory**

```bash
cd EaseMyTrip-Final
```

**Step 3: Install dependencies**

```bash
npm install
```

**Step 4: Configure MongoDB**

Ensure MongoDB is running and configure the database connection based on the project configuration.

**Step 5: Start the application**

```bash
node index.js
```

**Step 6: Open the application**

Visit the following URL in your browser:

```text
http://localhost:5005
```

## 📁 Project Structure

```text
EaseMyTrip-Final/
│
├── public/
├── views/
├── models/
├── routes/
├── index.js
├── package.json
├── package-lock.json
├── Screenshots/
└── README.md
```

*Note: This is an illustrative structure. Refer to the actual repository for the complete folder organization.*

## 🎯 Learning Outcomes

- Understanding full-stack web application development.
- Implementing REST API functionality using Express.js.
- Performing CRUD operations with MongoDB and Mongoose.
- Connecting frontend interfaces with backend services.
- Understanding user authentication and booking workflows.

## 🚀 Future Enhancements

- Responsive design for mobile and tablet devices.
- Integration of a real payment gateway.
- Improved flight booking and seat management functionality.

---

**Built with HTML, CSS, JavaScript, Node.js, Express.js, and MongoDB.**
