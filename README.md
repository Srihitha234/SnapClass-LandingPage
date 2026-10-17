# SnapClass – AI-Powered Attendance System

SnapClass is an AI-powered attendance management platform designed to simplify classroom attendance using facial recognition and voice biometrics. This repository contains the **SnapClass landing page**, which introduces the platform, highlights its features, and guides users to the live attendance application.

## Live Applications

- **Landing Page (Vercel):** https://snap-class-landing-page-kappa.vercel.app/
- **AI Attendance Application (Streamlit):** https://snapcl-main.streamlit.app/

## Overview

SnapClass aims to make classroom attendance faster, smarter, and more convenient by combining artificial intelligence with a user-friendly interface.

The landing page presents the platform's capabilities, technology stack, and workflows for teachers and students.

## Features

- **Modern Landing Page:** A responsive interface introducing SnapClass.
- **AI Face Recognition:** Information about automated attendance using classroom photos.
- **Voice-Based Attendance:** Highlights voice biometric verification.
- **Teacher Workflow:** Showcases login, dashboard, course management, attendance, and record management.
- **Student Workflow:** Introduces enrollment, biometric registration, and the student dashboard.
- **Technology Overview:** Presents the technologies used in the SnapClass platform.
- **Application Integration:** Direct links to the live AI attendance application.

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend application logic |
| Flask | Landing page backend and routing |
| HTML5 | Page structure |
| CSS3 | Styling and responsive layouts |
| JavaScript | Client-side interactions |
| Streamlit | AI attendance application |
| Git and GitHub | Version control |
| Vercel | Landing page deployment |

## Project Structure

```text
SnapClass-LandingPage/
├── app.py
├── templates/
│   └── index.html
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   └── img/
│       ├── logo.png
│       └── demo/
├── requirements.txt
├── vercel.json
└── README.md
```

*Note: The image directory may contain additional assets, and the exact project structure can evolve as the project develops.*

## Run Locally

### Prerequisites

- Python 3
- Git

### 1. Clone the repository

```bash
git clone https://github.com/Srihitha234/SnapClass-LandingPage.git
cd SnapClass-LandingPage
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```powershell
.\venv\Scripts\activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Start the Flask application

```bash
python app.py
```

Open the local website at:

http://127.0.0.1:5002

## Deployment

The landing page is deployed on Vercel and connected to the GitHub repository. When changes are pushed to the configured production branch, Vercel can automatically build and deploy the updated version.

The AI attendance application is hosted separately on Streamlit Community Cloud.

## Repository

GitHub: https://github.com/Srihitha234/SnapClass-LandingPage

## Future Improvements

- Further improve mobile responsiveness and accessibility.
- Add more product demonstrations and screenshots.
- Enhance animations and interactive elements.
- Expand documentation for the AI attendance platform.

## License

No license has been specified yet. Add a suitable `LICENSE` file if you intend to distribute this project as open source.

---

**SnapClass — Making classroom attendance smarter with AI.**
