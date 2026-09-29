Task 3 – HTML & CSS Styling Practice

A simple HTML and CSS practice project demonstrating basic CSS selectors, colors, typography, element IDs/classes, pseudo-classes, and links.

Project Structure

Task 3/
├── Index.html
├── Style.css
└── README.md

Technologies Used

HTML5

CSS3

Project Overview

The project contains a basic HTML page with three headings, paragraphs, unordered and ordered lists, and external links. The page is styled using a separate Style.css file.

The HTML document uses the viewport meta tag and links the external stylesheet from the <head> section. fileciteturn0file1L1-L8

Features

1. Page Background

The entire page uses a coral background through the body selector.

2. Heading Styling

Headings using the .head class are displayed in dark blue.

The second heading additionally uses the #bglime ID, giving it a lime background and red text. fileciteturn0file0L5-L11

3. Paragraph Styling

Regular paragraphs use white text.

The paragraph with id="para" uses green text.

The <span> inside #para is black and has a font size of 20px. fileciteturn0file0L14-L24

4. Link Styling

All <a> elements have a font size of 10px.

The project also demonstrates the :first-child and :nth-child() pseudo-classes:

The first list link has a yellow background.

The second list link has a blue background. fileciteturn0file0L27-L38

5. Ordered List Styling

The ordered list has a font size of 20px.

The second ordered-list item is blue, while the third item is red, demonstrating :nth-child() selectors. fileciteturn0file0L40-L50

Links Included

The unordered list contains links to:

Google

TuteDude Dashboard

These links are defined directly in Index.html. fileciteturn0file1L27-L29

How to Run

Download or clone the project.

Keep Index.html and Style.css in the same folder.

Open Index.html in any modern web browser.

No additional installation or dependencies are required.

Learning Objectives

This project demonstrates:

Basic HTML page structure

External CSS files

Class selectors

ID selectors

Element selectors

Descendant selectors

:first-child

:nth-child()

Text and background colors

Font sizing

HTML links

Ordered and unordered lists

Author

Created as an HTML & CSS practice task.
