# Learner's Platform

A modern, responsive educational website providing free resources, video lectures, sample papers, and interactive content for students preparing for competitive exams like JEE and GATE, as well as foundational computer science courses.

## Features

- **Home Page**: Introduction to the platform, navigation to all major sections, and contact form.
- **Login/SignUp**: User-friendly login and registration interface with social sign-in options.
- **Subjects**: Dedicated pages for Computer Science, GATE, and JEE with:
  - Curated playlists for Java, C++, Python, Data Structures, Digital Logic, Chemistry, Physics, and more.
  - Quick links to key topics and external resources.
  - Embedded YouTube video playlists for self-paced learning.
  - Downloadable sample papers (PDFs) for practice (2014-2019).
- **Sample Papers**: Download section for past exam papers.
- **Responsive Design**: Optimized for desktop and mobile devices.
- **Modern UI**: Clean, visually appealing design using custom CSS and Google Fonts.
- **Contact & Newsletter**: Contact form and newsletter subscription in the footer.

## Project Structure

```
/ (project root)
├── index.html               # Main landing page
├── login.html               # Login/SignUp page
├── loginStyle.css           # Styles for login page
├── style.css                # Main CSS for home and general pages
├── script.js                # JavaScript for UI interactivity
├── images/                  # All images and icons used in the site
│   ├── courses/             # Course-related images
│   ├── extra/               # Decorative and background images
│   └── icon/                # Icons and logos
├── samplePapers/            # PDF sample papers for exams
│   ├── p1.pdf
│   ├── p2.pdf
│   └── p3.pdf
├── subjects/                # Subject-specific pages and CSS
│   ├── computer_courses.html
│   ├── gate.html
│   ├── jee.html
│   └── subjects.css
└── .vscode/                 # VSCode settings (optional)
```

## How to Run

1. **Clone or Download** this repository.
2. Open `index.html` in your web browser.
3. No backend/server is required; all content is static and runs locally.

## Customization
- Update images in the `images/` folders as needed.
- Add new sample papers (PDFs) to `samplePapers/` and link them in the HTML.
- Edit or add new subject pages in the `subjects/` directory.

## Credits
- Developed by Satvik Verma
- Graphics and icons from [Google Fonts](https://fonts.google.com/) and custom assets.
- Video content linked from YouTube playlists.


