# College Admission Portal — Mini Project Report

## 1. Project title
**UniApply — College Admission Portal**

## 2. Objective
The objective of UniApply is to provide a simple, responsive web interface for managing college admission applications. It demonstrates how students can submit academic and personal details and how an administrator can review applications and monitor admission progress.

## 3. Technologies used
- **HTML5:** Page structure, forms, tables and semantic elements.
- **CSS3:** Responsive layout, visual styling, cards, navigation and mobile support.
- **JavaScript (ES6):** Form validation, application management, status updates, sorting, filtering and CSV export.
- **Browser LocalStorage:** Persistence of demo application records.

## 4. Main features
1. Dashboard showing application statistics and course demand.
2. Application form for personal, contact and academic information.
3. Document selection for photograph and marksheet (demo metadata only).
4. Application listing with search and filters.
5. Application detail view with approve, reject and pending actions.
6. Merit list sorted by Class 12 percentage.
7. Reports for approval rate, average score, courses and document counts.
8. CSV export and responsive mobile layout.

## 5. Working
When the portal opens, sample application objects are loaded into the dashboard. The user can create a new application through the form. JavaScript validates required fields, creates a unique application ID and saves the record in LocalStorage. The applications page reads the saved records and provides search and filter controls. The administrator can open an application and change its status. The merit list sorts applicants by percentage, while the reports page calculates summary values from the same application array.

## 6. Learning outcomes
- Creating responsive layouts with HTML and CSS.
- Handling form input and validation with JavaScript.
- Working with arrays and objects.
- Persisting browser data using LocalStorage.
- Rendering dynamic tables and dashboard statistics.
- Filtering and sorting records.
- Exporting data as CSV.

## 7. Limitations
This is a front-end demonstration. It does not provide real user authentication, a server-side database, secure document storage, email notifications or official admission decisions. Data is stored only in the browser where the project is opened. A production version would require a backend API, database, secure authentication, role-based access control and protected file storage.

## 8. Conclusion
UniApply demonstrates the core user interface and client-side workflow of a college admission portal. It brings application entry, review, status tracking, merit ranking and basic reporting into one responsive web application.
