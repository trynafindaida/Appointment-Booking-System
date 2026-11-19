# VisitYar — Doctor Appointment Booking UI

VisitYar is a static, Persian (right-to-left) user interface prototype for an online doctor appointment booking system. This version focuses on the visual layout and page structure built with **HTML5** and **CSS3**.

## Preview the Project

No installation or local server is required.

1. Download or clone this repository.
2. Open `index.html` in a web browser.

## Features Included

- Responsive landing page and navigation
- Doctor cards with names, specialties, and avatar illustrations
- Appointment booking layout with doctor, date, and time sections
- Static Jalali (Persian) calendar preview
- Appointment summary panel
- Sign-in and registration form layouts
- Patient appointments section layout
- Right-to-left Persian interface

## Built With

- **HTML5** — page structure and content
- **CSS3** — styling, layout, and responsive design
- **CSS Grid and Flexbox** — page and component layouts
- **Media Queries** — responsive behavior on smaller screens

## Project Structure

```text
visit-yar/
├── index.html
├── README.md
└── static/
    ├── style.css
    ├── avatar-female.svg
    └── avatar-male.svg
```

## Current Scope

This repository contains the **UI-only static prototype**. The content is sample content for demonstration purposes.

The following functionality is not implemented in this version:

- Dynamic doctor or appointment data
- Interactive doctor, date, or time selection
- User authentication
- Appointment creation, cancellation, or management
- Backend services, APIs, or database integration

The calendar is a static visual preview. Its panel can be opened and closed using the browser's native HTML disclosure element; selecting a date does not update the appointment summary.

## Next Development Steps

1. Add client-side interactions with JavaScript.
2. Connect the interface to a Python backend.
3. Store users and appointments in a database.
4. Implement and test the complete booking workflow.
