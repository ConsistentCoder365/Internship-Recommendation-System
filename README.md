# Internship Recommendation System


## Table of Contents

- [Project Overview](#project-overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Backend Setup](#backend-setup)
- [Frontend Setup](#frontend-setup)
- [Usage](#usage)



## Project Overview

This platform empowers users to:
- Discover internships and jobs tailored to their profiles.
- Build and export resumes.
- Participate in mock interviews and skill assessments.
- Track learning progress and certifications.
- Access career guidance, community support, and mentorship.
- Stay updated on job market trends, skills demand, and career events.

A professional UI, collapsible sidebar, infographics, and accessibility support are built in for a modern, inclusive experience.

## Key Features

### User & Career Management
- Register, login, and manage profiles.
- Update skills, education, work experience.
- Automated resume wizard and customizable templates.
- Export resumes (PDF, DOCX).
- Link third-party profiles (LinkedIn, GitHub).

### Recommendations & Insights
- Personalized internship/job recommendations.
- Real-time job market analysis and alerts.
- Competency diagnostic tests and skill gap analysis.
- Career roadmap and goal tracking.

### Learning & Community
- Suggest training courses and workshops.
- Track progress in skill development.
- Badges, certifications, and achievement sharing.
- Mock interviews, webinars, and virtual job fairs.
- Community forums, peer-to-peer mentoring, and career counseling.

### Application & Notifications
- Apply directly to jobs from the platform.
- Track application status and feedback.
- Set reminders for deadlines and events.
- Job alerts and notifications based on preferences.

### Accessibility & Inclusion
- Dedicated features for users with special needs.
- Inclusive design and technology adaptation.


## Technologies Used

- **Backend:**
  - Python
  - Django (RESTful APIs, authentication, admin panel)

- **Frontend:**
  - React (UI components, state management)
  - Vite (development/build tooling)
  - JavaScript & TypeScript (frontend logic and type safety)
  - CSS & HTML (styling and structure)

- **Others:** 
  - npm/yarn (package management)
  - Various libraries for skills, resume building, and UI components

## Installation

To get started with the project, follow these steps:

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Python (v3.8 or higher)
- pip
- Virtualenv

### Backend Setup

1. Clone the repository:

   ```sh
   https://github.com/ConsistentCoder365/Internship-Recommendation-System.git
   cd hireme/backend
   ```

2. Create a virtual environment and activate it:

   ```sh
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
   ```

3. Install the required Python packages:

   ```sh
   pip install -r requirements.txt
   ```

4. Set up the database:

   ```sh
   python manage.py migrate
   ```

5. Create a superuser to access the Django admin panel:

   ```sh
   python manage.py createsuperuser
   ```

6. Run the development server:

   ```sh
   python manage.py runserver
   ```

### Frontend Setup

1. Navigate to the frontend directory:

   ```sh
   cd ../frontend
   ```

2. Install the required npm packages:

   ```sh
   npm install
   ```

3. Start the development server:

   ```sh
   npm run dev
   ```

## Usage

### Accessing the Application

- The backend server will be running at `http://127.0.0.1:8000/`.
- The frontend server will be running at `http://localhost:5173/`.

### Admin Panel

- Access the Django admin panel at `http://127.0.0.1:8000/admin/` using the superuser credentials created during setup.

### User Registration and Login

- Navigate to the registration page at `http://localhost:5173/register` to create a new account.
- Navigate to the login page at `http://localhost:5173/login` to log in to your account.
