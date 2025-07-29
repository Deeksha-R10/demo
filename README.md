# 📋Online Feedback Management System 

## 📝Description:
This project is a web-based Feedback Management System designed specifically for cafes. It allows customers and employees to easily submit their feedback, and provides an admin dashboard to manage, review, and respond to feedback. The system helps improve customer satisfaction and service quality through efficient feedback handling.


## ✨ Features
### 🧑‍💼User & Admin Management
- Separate login for Admin
- Feedback access without login for customers/employees
- Admin dashboard with categorized views
- Review and status management (Pending, Approved, Resolved)

### 📝Feedback Submission
- Customer and employee feedback forms
- Star rating system (1–5 stars) 
- Text-based feedback messages
- Feedback category selector (Food, Service, Cleanliness, etc.)

### ✅Verified Reviews (Visible to All)
- This section displays feedback that has been approved by the admin.
- It is publicly visible — anyone (customer, visitor, or employee) can view the reviews without logging in.
- Ensures that only genuine and respectful feedback is displayed.
- Helps build trust with new visitors by showing real experiences from other customers and staff.

### ℹ️About
- Provides visitors with insight into the cafe’s story and values
- Shares details about the ambience, menu highlights, and customer philosophy
- Creates a sense of trust and connection with new customers
- Includes:
    - Cafe’s vision and mission
    - What the cafe serves (coffee, snacks, meals, specials)
    - Description of the space and vibe (e.g., cozy, work-friendly)
    - Location or general info (if applicable)
- Helps users understand the purpose behind the feedback system

### 🔐Admin Login Page
- Secure login for the admin using a username and password
- Protects the review management system from unauthorized access
- Once logged in, admin can:
- View all submitted feedback
- Approve or reject reviews
- Track feedback status (Pending / Approved / Resolved)
- Delete or archive inappropriate responses

### 📊Admin Dashboard
- All Feedback section to view every submitted feedback in one place
- Customer Feedback tab to filter and manage reviews from cafe visitors
- Employee Feedback tab for internal staff suggestions or concerns
- Admin Profile section to manage admin information and change password
- Notifications area to view real-time alerts about new or pending feedback
- Logout button to securely exit the dashboard

### 📥All Feedback
- Displays all submitted feedback (customers + employees)
- Sorted by most recent by default
- Shows rating, message, category, and submission time
- Action buttons: Approve, Reject, Resolve

### 👨‍💼Customer Feedback
- Shows only feedback submitted by cafe customers
- Categories like Food, Cleanliness, Service
- View detailed rating and message per submission
- Admin can take actions: Approve, Reject, or mark as Resolved
- Shows date of submission for tracking trends

### 🧑‍🍳Employee Feedback
- Internal feedback submitted by staff members
- Focuses on issues like workplace, hygiene, or staff support
- Only visible to admin — private & confidential
- Message and optional rating system
- Admin can reply or mark status (Approved/Resolved/Rejected)

### 💬Admin Response to Feedback
- After approval, admin can write a custom response
- Useful for addressing concerns or thanking for positive reviews
- Response box appears only for approved feedback
- Submitted responses are saved and visible with the feedback

### 🔔Notifications
- Instant alerts for new feedback submissions
- Notification for pending feedback awaiting admin review
- Updates when feedback is approved, rejected, or resolved
- Displayed on the admin dashboard for quick access and action

### 👤Admin Profile 
- Admin name and username
- Email and phone number
- Role: Feedback Admin
- Last login timestamp
- Account status (e.g., Active)

### 🚪Logout
- Securely ends the current admin session
- Prevents unauthorized access by clearing login data
- Redirects to the Admin Login or Home Page
- Protects dashboard data after logout
- Confirms logout with a success message or alert

### 🔐Authentication & Security
- Secure admin login with unique credentials
- Session-based access to protect sensitive data
- Only authorized admins can access dashboard features
- No public access to admin pages without login

## 🛠️Technology Stack

### Frontend
- HTML – Structure of the web pages
- CSS – Styling and responsive design
- JavaScript – Interactivity and dynamic behavior
- Responsive Design – Optimized layout for mobile, tablet, and desktop screens

### Backend
- Java – Core backend logic and server-side processing
- Spring Boot – Web framework for handling requests and responses

### Database
- MySQL – Relational database for storing feedback, user data, and admin responses
- Structured schema for efficient data retrieval and management

## 🎨UI/UX Design
### 💡Design Principles
- Clean and minimal layout for smooth navigation
- Consistent color scheme – calming tones suitable for a cafe theme
- Readable typography – Easy-to-read fonts with proper spacing
- Accessible design – Ensures usability for all users
- Feedback-focused interface – Designed around collecting and reviewing feedback easily
- Responsive design for mobile, tablet, and desktop

### Navigation Structure
Simple and intuitive menu for both users and admin

├── 🏠Home <br>
├── ⭐Verified Reviews <br>
├── ℹ️About <br>
├── 🔐Admin Login <br>
│ ├── 📊Admin Dashboard <br>
│ │ └──🗂️Feedback  <br>
│ │ └──🧑‍💼Customer Feedback <br>
│ │ └── 👨‍🔧Employee Feedback <br>
│ │ └──🔔Notifications <br>
│ │ └── 👤Profile <br>
│ │ └──🚪Logout <br>


