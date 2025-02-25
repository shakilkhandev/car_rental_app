# 🚗 Car Rental Management System

A **Car Rental Management System** built using **Laravel**, **Vue.js**, and **Inertia.js**. This full-featured platform provides a seamless experience for customers to rent cars and for admins to manage rentals efficiently.

## 📌 Features

### 🧑‍💼 Customers
- **Car Rental Request**: Users can submit rental requests, including car selection, rental duration, and additional details. A confirmation email is sent after submission.
- **Secure Authentication**: Registration and login functionality.
- **Access Control**: Rentals can only be created by logged-in users.
- **Rental Status Tracking**: Users can monitor their rental progress via the dashboard.
- **Profile Management**: Customers can update personal details in their profile.

### 👨‍💻 Admin Panel
- **Admin Authentication**: Only login access (no registration for admins).
- **Car Management**: Add, edit, and remove cars from the rental inventory.
- **Rental Oversight**: Admins can monitor and update rental statuses.
- **Manual Rental Creation**: Ability to create rental requests on behalf of customers.
- **Rental History Review**: Access detailed rental records.

## 🛠️ Technology Stack

- **Backend**: Laravel (PHP Framework)
- **Frontend**: Vue.js (Modern JavaScript Framework)
- **Routing & Data Handling**: Inertia.js
- **Database**: MySQL
- **Package Management**: Composer & npm

## 🚀 Installation Steps

1. **Clone the Project:**
```bash
git clone https://github.com/shakilkhandev/car_rental.git
cd car_rental
```

2. **Set Up Environment:**
```bash
cp .env.example .env
php artisan key:generate
```

3. **Install Dependencies:**
```bash
composer install
npm install
```

4. **Configure Database:**
- Update `.env` with the database credentials.

```env
DB_DATABASE=your_database_name
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

5. **Build Frontend:**
```bash
npm run build
```

6. **Run the Application:**
```bash
php artisan serve
```

For admin login : use route: http://127.0.0.1:8000/admin/login

email:shakilkhanfv@gmail.com
password : 123456

for customer side login :

email:customer@gmail.com
pass: 123456


## 📄 How It Works

**#intro_video_link:: https://drive.google.com/file/d/1Nv2kA3pgZL1TL8eE4bLH6MGdx_l-7tTt/view?usp=sharing

1. Customers sign up and log in to rent a car.
2. Admins manage car listings and oversee rentals.
3. Rental statuses (e.g., Pending, Ongoing, Completed) can be updated by admins.
4. Users can modify profiles and track their rental status.

## 📊 Project Structure

```
├── app/          # Backend (Laravel)
├── resources/    # Frontend (Vue.js)
├── routes/       # Web Routes
└── database/     # Migrations
```

## 🤝 Contributions

Contributions are welcome! Feel free to submit a Pull Request or open an issue.

## 📧 Contact
For inquiries or feedback, reach out at: [shakilkhanfv@gmail.com]    (mailto:shakilkhanfv@gmail.com)

---

**© 2025 Car Rental Management System - Built with Laravel, Vue.js, and Inertia.js**

