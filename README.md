# Wordpress_Setup_Commands
---
# 📝 WordPress Local Installation Guide (Windows + XAMPP)

This guide helps beginners install and run WordPress locally on a Windows system using **XAMPP**.

---

## 🧰 Requirements

- Windows PC
- XAMPP (Apache + MySQL)
- WordPress (latest version)

---

## 🚀 Step-by-Step Installation

### ✅ 1. Download and Install XAMPP

- Download from [https://www.apachefriends.org](https://www.apachefriends.org)
- Install with default settings
- Open **XAMPP Control Panel**
- Start services:
  - ✅ Apache
  - ✅ MySQL

---

### ✅ 2. Download WordPress

- Go to [https://wordpress.org/download/](https://wordpress.org/download/)
- Download the ZIP file
- Extract it to:  
  `C:\xampp\htdocs\wordpress`

---

### ✅ 3. Create a Database

- Open browser → [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
- Click on **Databases**
- Enter a database name (e.g., `wordpress_db`)
- Click **Create**

---

### ✅ 4. Run WordPress Installer

- Open browser → [http://localhost/wordpress](http://localhost/wordpress)
- Choose language → Continue
- Enter database info:
  - **Database Name**: `wordpress_db`
  - **Username**: `root`
  - **Password**: *(leave blank)*
  - **Database Host**: `localhost`
  - **Table Prefix**: `wp_`
- Click **Submit** → **Run the Installation**

---

### ✅ 5. Setup WordPress Site  [http://localhost/wordpress/wp-admin](http://localhost/wordpress/wp-admin)

- Set **Site Title**
- Create admin **Username** and **Password**
- Enter an **Email**
- Click **Install WordPress**
- Then **Log In**

---

## 🖥️ Accessing Your Site

- **Admin Panel**: [http://localhost/wordpress/wp-admin](http://localhost/wordpress/wp-admin)
- **Frontend Site**: [http://localhost/wordpress](http://localhost/wordpress)

---

## 🎨 Build Your First Website

### 1. Install a Theme
- Go to: `Appearance → Themes → Add New`
- Recommended themes: **Astra**, **Neve**, **Hello Elementor**
- Click **Install** → **Activate**

### 2. Install Elementor (Optional Page Builder)
- Go to: `Plugins → Add New → Search "Elementor"`
- Click **Install** → **Activate**

### 3. Create Pages
- Go to: `Pages → Add New`
- Create:
  - `Home`
  - `About`
  - `Contact`
- Use “Edit with Elementor” for design (optional)

### 4. Set Static Homepage
- Go to: `Settings → Reading`
- Choose:
  - Homepage: `Home`
  - Posts Page: *(optional)*

### 5. Create Navigation Menu
- Go to: `Appearance → Menus`
- Add Home, About, Contact
- Set Display Location → Primary
- Save Menu

---

## 🛠 Customize Your Site

- Go to: `Appearance → Customize`
- Set:
  - Site Title
  - Logo
  - Colors & Fonts

---

## ✅ Done!

You now have a fully functional local WordPress site ready for development and testing.

---

## 📁 Folder Structure

```
C:\
└── xampp\
    └── htdocs\
        └── wordpress\
            ├── wp-admin\
            ├── wp-content\
            ├── wp-includes\
            └── ...
```

---

## 📌 Notes

- Username: `root`
- Password: *(leave blank)*
- DB Host: `localhost`
- Admin Panel: `/wp-admin`

---

## 📚 Resources

- [WordPress.org](https://wordpress.org/)
- [Elementor](https://elementor.com/)
- [LocalWP (Alternative Tool)](https://localwp.com/)

---

```

---

You can copy and paste this into your repo’s `README.md` file. Let me know if you'd like to add screenshots or customize this for your own WordPress project.
