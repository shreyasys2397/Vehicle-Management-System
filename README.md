# 🚗 Vehicle Management System

A web-based Vehicle Management System developed using **HTML, CSS, JavaScript, AngularJS and Supabase**. The application allows users to manage vehicle records through a simple and user-friendly interface with real-time database integration.

## 🌐 Live Demo

**[View Vehicle Management System](https://shreyasys2397.github.io/AngularJS-Project/)**

## 📌 Project Overview

The Vehicle Management System is designed to simplify the process of maintaining vehicle records. Users can add new vehicles, view existing records, update vehicle information and delete records.

The application uses Supabase as its backend database to store and manage vehicle information online.

## ✨ Features

- **Add Vehicles:** Add new vehicle records with relevant details.
- **View Vehicles:** Display all stored vehicle records.
- **Update Vehicles:** Modify existing vehicle information.
- **Delete Vehicles:** Remove unwanted vehicle records.
- **Search Vehicles:** Find vehicles using the available search functionality.
- **Data Validation:** Validate user inputs before saving records.
- **Cloud Database:** Store vehicle information using Supabase.
- **Responsive Interface:** Simple and user-friendly design.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and layout |
| JavaScript | Application functionality |
| AngularJS | Frontend framework |
| Supabase | Backend database and REST API |
| GitHub | Version control |
| GitHub Pages | Website hosting |

## 🗄️ Database Structure

The project uses a Supabase table named `vehicles`.

| Column | Data Type | Description |
|---|---|---|
| id | TEXT | Unique vehicle ID |
| number | TEXT | Vehicle registration number |
| name | TEXT | Vehicle name |
| type | TEXT | Vehicle category |
| owner | TEXT | Vehicle owner |
| model | INTEGER | Manufacturing year |

## 📂 Project Structure

```text
AngularJS-Project/
│
├── index.html       # Main application
├── vehicles.json    # Initial vehicle records
└── README.md        # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/shreyasys2397/AngularJS-Project.git
```

### 2. Open the Project

```bash
cd AngularJS-Project
```

### 3. Configure Supabase

- Create a project in Supabase.
- Create a table named `vehicles`.
- Configure the required database columns and permissions.
- Add your Supabase Project URL and Publishable API Key to the application configuration in `index.html`.

### 4. Run the Application

Open `index.html` using a local development server or deploy it using GitHub Pages.

## ☁️ Deployment

This project is hosted using **GitHub Pages**.

Live URL:

https://shreyasys2397.github.io/Vehicle-Management-System/

## 🔮 Future Enhancements

- User authentication and role-based access.
- Advanced vehicle search and filtering.
- Vehicle image uploads.
- Vehicle maintenance history.
- Dashboard with vehicle statistics.
- Improved database security.

## 👨‍💻 Developer

**Shreyas Y S**

GitHub: [@shreyasys2397](https://github.com/shreyasys2397)

## 📄 License

This project is available for educational and learning purposes.
