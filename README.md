<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Web Layout</title>
    <style>
        /* Reset default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

  body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

  /* Navigation Bar */
        nav {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }

  nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }

  nav ul li {
            margin: 0 15px;
        }

  nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s;
        }

   nav ul li a:hover {
            color: #00bcd4;
        }

   /* Responsive Grid Layout */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }

  .box {
            background-color: white;
            padding: 20px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

   .box:hover {
            transform: scale(1.05);
        }

  /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
            }

  .container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

   <div class="container">
        <div class="box">Welcome to our responsive website!</div>
        <div class="box">Easily adaptable to any screen size.</div>
        <div class="box">Built with CSS Grid and Flexbox.</div>
    </div>
</body>
</html>













# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨
