# portfolio
The portfolio website is developed using HTML, CSS, and JavaScript:

1. HTML Structure

Header & Navigation:
The header contains a logo image and the user’s name, plus a navigation bar with anchor links to different sections.
Content Sections:
Each major area (Summary, Skills, Experience, Other Info) is placed in its own <section> with a .card class for styling.
Footer:
A simple footer provides copyright.

2. CSS Styling
->Reset & Base Styles:
Universal selector (*) resets margin, padding, and sets box-sizing: border-box for consistent sizing.
->Body Background:
The body uses a full-screen background image with background-size
->Fixed Header:
The header is fixed at the top using position: fixed, with a set height and z-index to stay above content.
->Frosted Glass Effect:
backdrop-filter: blur(8px) and semi-transparent backgrounds create a frosted glass look for the header.
->Flexbox & Grid:
Flexbox is used for horizontal and vertical alignment in the navigation bar and logo area. 
CSS Grid is used for the skills section to create a responsive grid of skill tags.
->Cards:
Content sections use the .card class for white backgrounds, rounded corners, box shadows, and padding.
-> Responsive Design:
Grid and flexible units (rem, fr, minmax) ensure the site adapts to different screen sizes.

3. JavaScript Functionality

A small JavaScript function intercepts anchor link clicks and uses scrollIntoView({ behavior: "smooth" }) for smooth transitions between sections.
No Heavy Interactivity:
The site is mostly static, focusing on content presentation, but the smooth scroll improves user experience.

4. Extensibility
Easy to Add Sections:
New sections or cards can be added by duplicating the <section class="card"> structure.
Customizable Styles:
Colors, fonts, and layout can be easily changed in the CSS.

Summary:
This portfolio is built with clean, semantic HTML for structure, 
modern CSS for layout and design (including flexbox, grid, and effects), and a touch of JavaScript for smooth navigation. 


