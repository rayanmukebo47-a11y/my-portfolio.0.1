# Layout 

Future Tech Conference 2026 website project:

# Future Tech Conference 2026 Website
A responsive conference landing page** for the Future Tech Conference 2026, built with **HTML**, **CSS**, and **Bootstrap 5**. Designed mobile-first and adapts to tablets and desktops.
##  Features
* Responsive Layout**: Mobile-first design with media queries for tablet and desktop.
* Banner / Hero Section**: Full-screen header with gradient background and call-to-action button.
* Speakers Section**: Cards for speakers with images, names, and titles. Responsive grid layout:

   Mobile: 1 per row
   Tablet: 2 per row
   Desktop: 3 per row
*Activities Section: Grid of conference activities.
* Schedule Section: Grid layout showing time, session title, and speaker.
* Bootstrap : Utilizes Bootstrap 5 for responsive grid and styling.
##  Technologies Used
HTML5
  CSS3 (with mobile-first design)
 [Bootstrap 5](https://getbootstrap.com/)
Responsive CSS Grid
##  Preview
![Conference Website Preview](https://via.placeholder.com/800x400)
##  Project Structure
future-tech-conference-2026/
│
├── index.html        # Main HTML file
├── css/
│   └── styles.css    # Custom styles (optional if embedded in HTML)
└── assets/
    └── images/       # Speaker images and other media
## Sections
1. Navbar\– Site header with conference title.
2. Banner / Hero – Eye-catching full-screen introduction.
3. Speakers – Cards displaying speaker details.
4. Activities – Grid showcasing main activities.
5. Schedule– Grid showing conference schedule with times, sessions, and speakers.
## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/future-tech-conference-2026.git
   ```
2. Open `index.html` in your browser.
3. Customize speakers, schedule, and activities as needed.
##  Notes
 Fully responsive design using CSS Grid and Bootstrap classes.
 Mobile-first approach ensures optimal display on smartphones.
 Placeholder images can be replaced with real speaker photos.
This version works well for GitHub, highlighting features, technologies, structure, and usage.

# bootstrap 

# Tech Conference Website (Bootstrap)

A responsive conference landing page** built with **HTML**, **CSS**, and **Bootstrap 5**. Designed mobile-first and enhanced for tablets and desktops.

##  Features

* Responsive Design**: Mobile-first layout with CSS Grid and Bootstrap 5.
* Banner / Hero Section**: Full-screen header with gradient background and a call-to-action button.
* Speakers Section**: Bootstrap cards with images, names, and descriptions of conference speakers.
* Activities Section**: CSS Grid layout showcasing key conference activities.
* Contact Form**: Simple, user-friendly contact form for inquiries.
* Bootstrap 5**: Leveraging Bootstrap’s grid system and styling utilities.

##  Technologies Used

* HTML5
* CSS3 (Mobile-first with CSS Grid)
* [Bootstrap 5](https://getbootstrap.com/)
* Responsive design principles

##  Preview

![Conference Website Preview](https://via.placeholder.com/800x400)

##  Project Structure

```text
tech-conference-bootstrap/
│
├── index.html        # Main HTML file
├── css/
│   └── styles.css    # Custom styles (optional if embedded in HTML)
└── assets/
    └── images/       # Speaker images and other media
```

---

##  Sections

1. Navbar – Header with conference title.
2. Banner / Hero – Eye-catching full-screen introduction with registration button.
3. Speakers – Responsive cards showing speaker photo, name, and bio.
4. Activities – Grid layout for workshops, networking, live coding, and startup pitch.
5. Contact Form – Form for attendees to get in touch.

##  How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/tech-conference-bootstrap.git
   ```
2. Open `index.html` in a web browser.
3. Customize speakers, activities, and contact form fields as needed.

##  Notes

* Fully responsive design using CSS Grid and Bootstrap’s responsive classes.
* Mobile-first design ensures smooth display across all devices.
* Placeholder images can be replaced with real speaker photos.

# Styles.css 

Here’s how you can turn your **Schedule section** into a standalone **`styles.css`** file for better organization and maintainability. You can link it in your HTML instead of embedding the CSS in the `<style>` tag.

### `styles.css`

```css
/* ===== SCHEDULE SECTION USING PURE CSS GRID ===== */
.schedule {
    display: grid;
    grid-template-columns: 1fr 3fr 2fr; /* 3 columns: Time, Session, Speaker */
    gap: 20px; /* Space between columns and rows */
    margin-top: 40px;
}

/* Styling for the schedule cells */
.schedule .time,
.schedule .session,
.schedule .speaker {
    padding: 10px;
    background-color: #f8f9fa;
    border: 1px solid #ddd;
    border-radius: 5px;
}

/* Responsive layout for mobile devices */
@media (max-width: 768px) {
    .schedule {
        grid-template-columns: 1fr; /* Stack vertically on mobile */
    }
}
```

### Updated HTML

Then, in your HTML `<head>`, replace the embedded `<style>` with a link to your external stylesheet:

```html
<link href="styles.css" rel="stylesheet">
```

✅ Benefits of this approach:

* Keeps HTML clean and easier to read.
* Makes it easier to maintain and update CSS for multiple pages.
* Works seamlessly with Bootstrap 5 grid and your responsive design.

git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/G4vi333/my-portfolio.0.1.git
git push -u origin master

# when you want to update the files 

first save your file 
git status-track files
git add .
git add the name of the file you change
git co;;it -m"write something to descripes what you change in your file it not necessary be longer"
git push origin master 
