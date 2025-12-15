# Eatery – Restaurant Website

## Project Overview

**Eatery** is a full-stack restaurant website that allows customers to browse the menu, make reservations, contact the restaurant, and submit reviews.  
The admin dashboard lets the restaurant manage menu items, reservations, contact messages, and customer reviews.

---

## Features

### Customer-facing:
- Home page with hero section and About Us  
- Menu section with featured dishes  
- Full Menu page  
- Reservation booking page  
- Contact Us page  
- Customer Reviews section  
- Write a review form  

### Admin Dashboard:
- Manage menu items (add, edit, delete)  
- Manage reservations (add, edit, delete)  
- View contact messages  
- Approve, unpublish customer reviews  

---

## Tech Stack

- **Frontend:** React.js, React Router, Axios, Vite  
- **Backend:** Node.js, Express.js, MongoDB  
- **Styling:** CSS, FontAwesome (for stars)  
- **Deployment:** Vercel (frontend), Render (backend) Note: After deployment, some sections may require CORS or URL adjustments. Local setup ensures all features work.

---

# How to Run Eatery Project Locally

## 1. Clone the Repository
- git clone <repo-url>
- Go to the project folder on your computer.  

2. **Backend Setup**
   - Navigate to the backend folder.  
   - Install dependencies. npm install 
   - Create a `.env` file containing the port and your MongoDB connection string:
     - PORT=5000
     - MONGO_URI= <your-mongodb-connection-string>  
   - Start the backend server and go to that url and enter /admin.
   - npm run dev
   
3. **Frontend Setup**
   - Navigate to the frontend folder.  
   - Install dependencies. npm install  
   - Start the frontend server.
   - Open your browser and go to http://localhost:5173 to use the website. 




