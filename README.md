# html-ABC-college

One Home page that leads to other pages. The Home page should contain the name of the City as heading along with a logo. There should be a tab with the following links:
 Home;
 Heritage;
 Hotel Booking;
 Gallery.
There should be an appropriate description of the college on the home page.

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Website - Academics</title>
</head>
<body>
    <header>
        <div class="container">
            <img src="c:\Users\Lenovo\Downloads\sairam.png" alt="College Logo">
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="academics.html">Academics</a></li>
                    <li><a href="admission.html">Admission</a></li>
                    <li><a href="gallery.html">Gallery</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container">
        <section>
            <h2>Academics</h2>
            <p>The Sairam Engineering College has an excellent academic coordination methodology which has evolved over a period of more than 17 years and 
                has been producing excellent results in terms of students pass percentage and university ranks.
                 
            </p>
            <ul>
                <li>Science
                    <ul>
                        <li><a href="courses/computer-science.html">Computer Science</a></li>
                        <li><a href="courses/mathematics.html">Mathematics</a></li>
                    </ul>
                </li>
                <li>Arts
                    <ul>
                        <li><a href="courses/english.html">English</a></li>
                        <li><a href="courses/sociology.html">Sociology</a></li>
                    </ul>
                </li>
                <li>Commerce
                    <ul>
                        <li><a href="courses/economics.html">Economics</a></li>
                        <li><a href="courses/business-management.html">Business Management</a></li>
                    </ul>
                </li>
            </ul>
        </section>
    </div>
    <footer>
        <div class="container">
            <p>&copy; 2024 Sairam Engineering College. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
```
