# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.
   
 /* General page styling */
body {
  font-family: 'Helvetica Neue', sans-serif;
  background-color: #ffffff;
  color: #333;
  margin: 0;
  padding: 0;
}

/* Headings */
h1, h2 {
  font-family: 'Georgia', serif;
  color: #1a1a1a;
  margin-bottom: 10px;
}

/* Paragraph styling */
p {
  font-size: 16px;
  line-height: 1.6;
  color: #555;
}

/* Class for a section container */
.section {
  padding: 20px;
  margin: 20px;
  border: 2px solid #e0e0e0;
  border-radius: 10px;
}

/* Class for button styling */
.button {
  background-color: #2d89ef;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.button:hover {
  background-color: #1c6ec7;
}

/* ID for a specific title */
#main-title {
  font-size: 32px;
  color: #222;
  margin: 20px;
}


Happy Coding! 💻✨
