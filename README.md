# StudentHub – Web Development Frameworks Practicals

**Student Name:** Lakshit Hirpara  
**Student ID:** 25CS019  
**Course:** ITUE203 – WEB DEVELOPMENT FRAMEWORKS  
**Academic Year:** 2nd  
**College:** Chandubhai S. Patel Institute of Technology 
**Repository:** https://github.com/LakshitPrime01/student-hub

---

## About the Project

StudentHub is a student portal built step by step across eight lab practicals. It starts as a plain multi-page HTML site and grows into a responsive, JavaScript-driven web app with a PHP and MySQL backend. Each practical adds one new layer, so the project shows how a web application is built from static pages up to a database-backed system.

## Practicals

| # | Folder | Topic | Technologies |
|---|--------|-------|--------------|
| 1 | `Practical 1` | StudentHub multi-page website: home, login, register, dashboard, courses, attendance, notices, profile, contact, about | HTML, CSS |
| 2 | `practical 2` | HTML5 semantic page conversion, with added events, FAQ, feedback and admin pages | Semantic HTML5, CSS |
| 3 | `Practical 3` | Responsive UI using CSS Grid, Flexbox and Bootstrap/Tailwind | HTML, CSS, Bootstrap/Tailwind |
| 4 | `Practical 4` | Responsive UI with interactive behaviour, such as menus and modals | HTML, CSS, JavaScript |
| 5 | `Practical 5` | Registration form with frontend validation, regular expressions, password strength check and friendly error messages | HTML, CSS, JavaScript |
| 6 | `Practical 6` | Fetch API with JSON data: search, filter, sort and pagination | JavaScript, Fetch API, JSON |
| 7 | `Practical 7` | PHP form processing with server-side validation, sanitization and CSV/JSON storage | PHP, CSV, JSON |
| 8 | `Practical 8` | Database design (students, events, registrations) and PDO connection with prepared statements | PHP, MySQL, PDO |

## Folder Structure

```text
student-hub/
├── Practical 1/    # Static multi-page site
├── practical 2/    # Semantic HTML5
├── Practical 3/    # Responsive UI (Grid, Flexbox, Bootstrap/Tailwind)
├── Practical 4/    # Responsive UI + JavaScript interactions
├── Practical 5/    # Form validation
├── Practical 6/    # Fetch API + JSON (data/ and js/ folders)
├── Practical 7/    # PHP form handling + CSV/JSON storage
├── Practical 8/    # MySQL + PDO
└── README.md
```

Each practical folder has its own `README.md` with the problem statement, objective, file structure and key code.

## How to Run

**Practicals 1 to 5 (static)**
Open `index.html` in a browser, or use the VS Code *Live Server* extension.

**Practical 6 (Fetch API)**
Run it through a local server such as *Live Server*. Browsers block `fetch()` on `file://` pages, so double-clicking the HTML files will not load the JSON data.

**Practical 7 (PHP)**
1. Install XAMPP or any PHP 8+ environment.
2. Copy the `Practical 7` folder into `htdocs`.
3. Open `http://localhost/Practical%207/index.php`.

**Practical 8 (PHP + MySQL)**
1. Start Apache and MySQL in XAMPP.
2. Create a database named `studenthub` in phpMyAdmin with the `students`, `events` and `registrations` tables.
3. Check the credentials in `db.php`. They default to user `root` with an empty password, which is only suitable for local use.
4. Open `test_connection.php` to confirm the connection works.

## Skills Demonstrated

- Semantic HTML5 and accessible page structure
- Responsive layout with CSS Grid, Flexbox and Bootstrap/Tailwind
- DOM manipulation, event handling and form validation in JavaScript
- Consuming JSON with the Fetch API, with search, filter, sort and pagination
- Server-side validation, sanitization and CSRF protection in PHP
- Relational database design and PDO with prepared statements to prevent SQL injection

## Tools Used

VS Code, XAMPP (Apache, MySQL, phpMyAdmin), Git and GitHub, a modern web browser.

## Author

**Lakshit Hirpara** – 25CS019
CSE - CSPIT
