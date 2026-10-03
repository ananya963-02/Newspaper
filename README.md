📰 Times of India - Newspaper Layout

A simple newspaper-style webpage layout created using HTML5 and CSS3. This project demonstrates how CSS multi-column layouts can be used to arrange text like a traditional newspaper.

📌 Project Overview

This webpage is designed as a basic newspaper interface inspired by a newspaper layout.

It includes:

- Centered newspaper title
- Scrolling latest-news banner
- Three-column text layout
- Column borders and spacing
- Multiple article sections
- Beige newspaper-style background
- Justified text alignment

🛠️ Technologies Used

- HTML5
- CSS3

📂 Project Structure

Times-of-India/
│
├── index.html
└── README.md

✨ Features

📰 Newspaper Header

The page starts with a centered heading:

<h1>TIMES OF INDIA</h1>

This represents the newspaper title.

📢 Breaking/Latest News Banner

A "<marquee>" element is used to create a horizontally scrolling news update:

<marquee behavior="" direction="" scrollamount="20">
    <h2>Last Updated News Date:30 july 2026</h2>
</marquee>

The banner also has borders at the top and bottom.

📰 Three-Column Layout

The ".three" class uses CSS multi-column properties:

.three {
    column-count: 3;
    column-rule: 3px solid black;
    column-gap: 40px;
}

This divides the content into three columns, similar to a traditional newspaper.

📑 Multiple Article Columns

The ".a" class also creates a three-column layout:

.a {
    column-count: 3;
    column-rule: 3px solid black;
    column-gap: 40px;
}

Multiple headings and paragraphs are automatically distributed across the columns.

🎨 CSS Styling

Background

The webpage uses a beige background:

* {
    background-color: beige;
}

This gives the page a newspaper-like appearance.

Text Alignment

All elements use justified text:

* {
    text-align: justify;
}

This makes the text align evenly along both the left and right edges.

Column Rule

A black vertical line is placed between columns:

column-rule: 3px solid black;

Column Gap

The space between columns is controlled using:

column-gap: 40px;

Headings

The main heading is centered:

h1 {
    text-align: center;
}

The smaller article headings are also centered:

h4 {
    text-align: center;
}

🚀 How to Run

1. Create a folder for the project.

2. Create a file named:

index.html

3. Paste the HTML code into the file.

4. Open "index.html" in any modern web browser.

You can also use VS Code Live Server to view the project.

📖 HTML Concepts Demonstrated

This project demonstrates several important HTML concepts:

- HTML document structure
- Headings
- Paragraphs
- "<div>" containers
- "<marquee>" element
- HTML attributes
- CSS integration

🎨 CSS Concepts Demonstrated

The project demonstrates:

- "text-align"
- "background-color"
- "column-count"
- "column-rule"
- "column-gap"
- Borders
- Universal selector
- CSS class selectors

🔮 Future Improvements

The project could be improved by:

- Replacing "<marquee>" with CSS animations
- Adding real news articles
- Adding images to articles
- Creating a responsive mobile layout
- Adding navigation menus
- Adding different article sections
- Using CSS Grid or Flexbox for advanced layouts
- Adding date and author information
- Improving typography
- Adding responsive media queries

📱 Responsive Design

The current layout uses a fixed three-column structure. For better mobile support, the number of columns can be reduced on smaller screens.

Example:

@media (max-width: 768px) {
    .three,
    .a {
        column-count: 2;
    }
}

@media (max-width: 480px) {
    .three,
    .a {
        column-count: 1;
    }
}

This allows the content to display in fewer columns on smaller screens.

⚠️ Note

The "<marquee>" HTML element is obsolete in modern HTML and should generally be replaced with CSS animations for production websites.

👨‍💻 Author

BCA 1st Year Student
Dezyne Ecole College

📄 License

This project is created for educational and learning purposes. You are free to modify, improve, and reuse the code for your own projects.# Newspaper
