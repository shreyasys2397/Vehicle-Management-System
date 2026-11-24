🚗 Vehicle Management System

A web-based Vehicle Management System developed using HTML, CSS, JavaScript, AngularJS and Supabase. The application provides a simple and user-friendly interface to manage vehicle records with real-time database integration.

🌟 Features

Dashboard

View total number of registered vehicles.

View vehicle statistics by type.

Track vehicles currently in service.

View average fleet age.

Display recently added vehicles.

Vehicle Management

Add new vehicle records.

View all registered vehicles.

Edit existing vehicle information.

Delete vehicle records with confirmation.

Prevent duplicate vehicle registration numbers.

Search and Organization

Search vehicles by number, name, type, owner, year or status.

Filter vehicles by type and status.

Sort vehicle records by different columns.

Pagination for easier record navigation.

Data Export

Export filtered vehicle records to CSV format.

Download vehicle information for offline use.

User Interface

Responsive design for desktop and mobile devices.

Simple navigation and dashboard layout.

Status indicators for vehicle records.

Notifications for successful and unsuccessful operations.

🛠️ Technologies Used

Technology

Purpose

HTML5

Webpage structure

CSS3

Styling and responsive design

JavaScript

Application logic

AngularJS 1.8.3

Frontend framework

Supabase

Database and REST API

GitHub

Version control

GitHub Pages

Web hosting

🗄️ Database Structure

The application uses a Supabase PostgreSQL database.

Table: public.vehicles

Column

Description

id

Unique vehicle identifier

number

Vehicle registration number

name

Vehicle name

type

Vehicle category

owner

Owner name

model

Manufacturing year

status

Current vehicle status

Vehicle Status Options

Active

In Service

Retired

⚙️ Installation and Setup

1. Clone the repository

git clone https://github.com/shreyasys2397/Vehicle-Management-System.git

2. Open the project

Navigate to the project directory:

cd Vehicle-Management-System

3. Configure Supabase

Create or use an existing Supabase project.

Update the database configuration in index.html:

var SUPABASE_URL = "YOUR_SUPABASE_PROJECT_URL";
var SUPABASE_KEY = "YOUR_SUPABASE_PUBLISHABLE_KEY";

Use your Supabase project URL and publishable key. Never expose your service-role key in frontend code.

4. Configure the database

Add the vehicle status column if it does not already exist:

ALTER TABLE public.vehicles
ADD COLUMN IF NOT EXISTS status TEXT NOT NULL DEFAULT 'Active';

Ensure appropriate Row Level Security policies are configured for the database operations used by the application.

5. Run locally

Open index.html using Visual Studio Code with the Live Server extension.

🌐 Deployment

The application can be hosted using GitHub Pages.

Push the application files to your GitHub repository.

Open repository Settings.

Navigate to Pages.

Select the deployment branch and root folder.

Save the configuration.

🔐 Security

Uses Supabase API authentication through a publishable key.

Database access should be protected with appropriate Row Level Security policies.

Never include private service-role credentials in frontend files.

Validate and restrict database operations through Supabase policies.

🚀 Future Enhancements

Vehicle maintenance tracking.

Service and insurance reminders.

Advanced fleet analytics.

PDF report generation.

User authentication and role-based access.

Vehicle history tracking.

👨‍💻 Developer

Shreyas Y S

GitHub: @shreyasys2397

📄 License

This project is open for educational and learning purposes.

Vehicle Management System | Version 2.0