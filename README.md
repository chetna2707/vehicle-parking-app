# Vehicle Parking App

Vehicle Parking App is a Flask-based web application for managing 4‑wheeler parking lots, parking spots, and reservations. It supports separate admin and user roles so that day‑to‑day parking operations can be handled digitally instead of through manual records. 

## Features

- Admin login to create, edit, and delete parking lots and parking spots. 
- User registration and secure login with hashed passwords and session management.
- Reserve and release parking spots with timestamps, vehicle number, and cost per unit time. 
- View user-specific parking history and active bookings.
- Basic admin dashboards and charts for monitoring parking usage. 

## Tech Stack

- **Backend:** Flask, Flask-Login, Flask-SQLAlchemy, Werkzeug.
- **Frontend:** HTML, CSS, Bootstrap, JavaScript, Jinja templates. 
- **Database:** SQLite via SQLAlchemy ORM. 

## Usage Overview

- Admins configure parking lots, define spots, and monitor all reservations and revenue summaries from their dashboard.
- Users register, log in, book an available spot, release it when leaving, and review their historical parking records.
