# UniApply — College Admission Portal

A responsive front-end college admission portal built with **HTML5, CSS3 and vanilla JavaScript**. It is designed as an internship/demo project and uses browser `localStorage` for data persistence.

## Features

- Dashboard with total, approved, pending and rejected application counts
- Student application form with required-field and basic format validation
- Course selection and academic details
- Small document file selection (file names and document labels are recorded)
- Application list with search and status/course filters
- Application detail modal with approve, reject and mark-pending actions
- Merit list sorted by Class 12 percentage
- Reports with approval rate, average score, course demand and document counts
- CSV export for applications and merit list
- Responsive layout for desktop, tablet and mobile
- Demo sign-in role selector

## Run the project

**Option 1 — easiest**
1. Extract `College-Admission-Portal.zip`.
2. Open the extracted folder.
3. Double-click `index.html`.

**Option 2 — recommended local server**
1. Open the folder in VS Code.
2. Install the Live Server extension if needed.
3. Right-click `index.html` → **Open with Live Server**.

No database or build step is required.

## Demo access

The sign-in screen accepts any email and password. Choose either:
- Administrator
- Student demo

This is a role-selection demonstration, not production authentication.

## Project structure

```text
College-Admission-Portal/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
├── assets/
│   └── images/
└── README.md
```

## Data and privacy notes

- Application records are saved in the current browser's `localStorage`.
- The app starts with sample applications so the dashboard is populated.
- Use **Clear site data** in browser settings to reset the demo, or open DevTools Console and run:
  `localStorage.removeItem('uniapply_portal_v1'); location.reload();`
- Uploaded documents are not sent to a server. The demo checks selected file size and records the file name/type as metadata only. Do not upload real sensitive documents.
- `localStorage` and the demo login are not secure enough for real admissions. A production portal needs a backend, database, secure authentication, server-side validation, encrypted file storage, access control and audit logs.

## Suggested submission checklist

- [ ] Push this project to a **public GitHub repository**.
- [ ] Add screenshots of Dashboard, Application Form, Applications, Merit List and Reports.
- [ ] Record a 3–5 minute walkthrough.
- [ ] Upload the walkthrough to YouTube as Public or Unlisted and copy its URL.
- [ ] Deploy the static site using GitHub Pages, Netlify or Vercel.
- [ ] Submit the GitHub URL, live URL, video URL and project report in the internship dashboard.

## Technologies

HTML5 · CSS3 · JavaScript (ES6) · LocalStorage · CSV export
