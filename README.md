
# appt_tracking_app

## Overview

**appt_tracking_app** is a Django-based appointment tracking application designed primarily for tutor-student scheduling. It helps tutors and students keep track of session attendance, manage appointments, and streamline communication. The app is built with extensibility in mind and may support other appointment types in the future.

## Features

- **Student Management:**
  - Tutors can add, list, and view student summaries.
  - Students can view their own information.
- **Session Management:**
  - Tutors can mark sessions as scheduled, completed, cancelled, or no-show.
- **Validation:**
  - Prevents invalid IDs or status values.
  - Prevents scheduling for non-existing students.
- **Data Storage:**
  - Uses PostgreSQL as the database backend.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd appt_tracking_app
   ```
2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Configure the database:**
   - Update your `settings.py` with your PostgreSQL credentials.
4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```
5. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

## Planned Features

- Email or SMS notifications for scheduled sessions
- Calendar integration (Google Calendar, Outlook, etc.)
- Session feedback and rating system
- Analytics dashboard for tutors and students
- User authentication and role management
- File sharing for session materials
- Mobile-friendly interface

---
Feel free to contribute or suggest new features!

