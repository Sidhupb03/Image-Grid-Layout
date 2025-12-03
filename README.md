# Image-Grid-Layout
Image Grid Layout Project
📌 Overview

This project is a responsive image grid layout built using HTML and CSS.
It displays images in three columns, each containing a combination of portrait and landscape photos.
The layout automatically adjusts based on screen size using CSS Grid and media queries.

🗂 Project Structure
project-folder/
│
├── index.html
├── styles.css
└── images/
    ├── 1.jpg
    ├── 2.jpg
    ├── 3.jpg
    ├── 4.jpg
    ├── 5.jpg
    └── 6.jpg

🚀 Features

Fully responsive CSS Grid layout

Supports both portrait and landscape images

Simple, clean, and modern look

Uses separate HTML and CSS files

Adjusts margins and layout with media queries for smaller screens

🧩 Technologies Used

HTML5

CSS3 (Grid, Media Queries)

📄 Code Explanation
HTML

A main .container div holds three columns

Each column contains two images

Images are given classes:

.portrait → vertical orientation

.landscape → horizontal orientation

CSS

display: grid creates a responsive grid that automatically fits columns

minmax(250px, 1fr) ensures each column stays flexible

Specific margin adjustments for different screen sizes

Images are fully responsive using width: 100%

📱 Responsive Design

Tested breakpoints include:

1044px — Adjusted margins

574px — Increased margin for smaller screens

462px & 400px — Re-adjusted spacing for mobile usability

The gallery maintains image proportions and readability on all devices.

🔧 How to Use

Download the project

Place your images inside the /images folder

Open index.html in your browser

Replace image files with your own if needed

✨ Future Improvements

Add hover effects for image zoom

Add captions below images

Improve mobile layout with single-column stacking

Add animation on load

🙌 Credits

Created by Gurvinder Singh using HTML & CSS.
Feel free to customize and improve the design!
