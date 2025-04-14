---

# 🏠 PG Life – Full-Stack Web Application

PG Life** is a fully functional web-based application developed during my **Web Development Training Internship in the Summer of 2025**. This project was the result of intensive training in both front-end and back-end technologies, where I learned and implemented everything used in this project — from UI design to server-side scripting and database management.

---

## 📌 Project Overview

**PG Life** is a student accommodation platform that allows users to search, browse, and view details of PG (Paying Guest) properties in different cities. The application supports user authentication, listing filtering, and secure access to property details.

![image](https://github.com/user-attachments/assets/8f67b59d-640f-4343-a3a5-9e727261386a)



---

## 🧰 Tech Stack

### ✅ Front-End

- **HTML5** – Page structure and markup
- **CSS3** – Layout and visual design
- **Bootstrap 4** – Responsive design and pre-built UI components
- **JavaScript** – Dynamic content and interaction handling
- **AJAX (with jQuery)** – Smooth data fetching without reloading pages

### ✅ Back-End

- **PHP** – Server-side scripting and backend logic
- **MySQL** – Database for user data, PG details, and city listings
- **Session Handling** – Secure user login/logout functionality

---

## 🌟 Key Features

### 🧑‍💼 User Features

- **User Signup/Login**  
  Secure user authentication using email and password. Sessions are maintained throughout browsing.

  ![image](https://github.com/user-attachments/assets/3d2bc97c-14e6-4d89-98e8-ae4e4c08a6fb)


- **City-Based PG Browsing**  
  Homepage provides options for cities like Delhi, Mumbai, Bengaluru, and Hyderabad. Clicking a city shows all PGs in that city.

  ![image](https://github.com/user-attachments/assets/2356860e-eae0-406d-a32c-f695581364d8)



- **Property Listings**  
  Each property shows an image, title, location, gender preference (boys/girls), rent, and amenities.

- **Search & Filter**  
  Users can search PGs by city and filter by amenities (Wi-Fi, meals, AC, laundry, etc.).

- **Property Detail Page**  
  Full detail view of selected PGs, including:
  - Large image banner
  - Description
  - Facilities
  - Address & gender suitability
  - "Contact Owner" button (visible only when logged in)
    ![image](https://github.com/user-attachments/assets/d5aea17a-3775-4fd6-b457-7bd0a4a3df67)


- **Dashboard Page**  
  Logged-in users can view PG details and access the user dashboard.

  ![image](https://github.com/user-attachments/assets/1c353b1e-277f-408a-b8a3-8ff6dcecf731)


- **Logout Functionality**  
  Secure logout functionality to destroy the session and redirect to the home page.

---

### 🔒 Backend / Admin Features

- **Session-Based Access Control**  
  Prevents unauthenticated users from accessing property details or dashboards.

- **Secure Database Integration**  
  All PG data, user data, and city info are stored and fetched dynamically via MySQL.

- **Dynamic Content Loading**  
  PG details are fetched and rendered using PHP, ensuring content is not hardcoded.

- **Database Seeding**  
  Sample entries for PGs and cities help in testing and running the project smoothly.

---

## 📁 Project Structure

```
PG-Life-Project/
├── api/                     # Backend logic (login, signup, city listings)
├── css/                     # Custom and Bootstrap styles
├── img/                     # All images and icons
├── includes/                # Common page elements (header, footer, navbar)
├── js/                      # JavaScript and AJAX files
├── dashboard.php            # User's personal dashboard
├── index.php                # Home page with city links
├── login.php                # Login page
├── signup.php               # Registration page
├── property_list.php        # List PGs by city
├── property_detail.php      # View full PG info
├── logout.php               # Logout script
├── README.md                # Project documentation
└── pglife.sql               # MySQL DB file
```

---

## 🚀 Getting Started (Local Setup)

1. **Clone the Repository**
   ```bash
   git clone https://github.com/naqeebansari2004/PG-Life-Project.git
   ```

2. **Set Up Local Server**
   - Install [XAMPP](https://www.apachefriends.org/index.html)
   - Move the project folder to `htdocs/`

3. **Import Database**
   - Open `phpMyAdmin`
   - Create a database named `pglife`
   - Import `pglife.sql` file from the root directory

4. **Run the Project**
   - Start Apache and MySQL via XAMPP
   - Visit `http://localhost/PG-Life-Project/index.php` in your browser

---

## 🔮 Future Enhancements

- 📝 Add review and rating system for PGs
- ✉️ Email verification during signup
- 📱 Mobile-first redesign
- 🔐 Admin panel for PG management
- 🗂 Pagination and search sorting
- 🌐 Location-based search using Google Maps API

---

## 🎓 Internship Background

This project was created during my **Web Development Internship** in **Summer 2025**. During this training, I learned and applied:

- Web design principles (HTML/CSS/Bootstrap)
- JavaScript for interactivity and AJAX for smooth UX
- PHP & MySQL for backend logic and data management
- Deployment and database setup using XAMPP

This hands-on project helped me understand full-stack web development from scratch and gave me real-world development experience.

---

## 🤝 Contributing

Contributions are welcome!  
1. Fork this repo  
2. Create a new branch: `feature/YourFeatureName`  
3. Commit your changes  
4. Push and create a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
