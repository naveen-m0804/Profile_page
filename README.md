# Profile Page
## Date: 07-07-2025
## Objective:

To design a simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes.

## Tasks:

#### 1. Set Up the HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the basic structure.

Add an appropriate <title> such as "My Profile".

#### 2. Add Page Headings:

Insert a main heading using ```<h1>``` for the user's name.

Include subheadings such as ```<h2>``` or ```<h3>``` for titles or roles (e.g., "Student", "Web Developer").

#### 3. Insert a Profile Image:

Use the ```<img>``` tag to display the user’s profile picture.

Add alt text and set basic attributes like width and height.

#### 4. Include a Short Bio Section:

Add a paragraph using <p> to provide a short introduction or biography.

The content may include education, interests, or a personal statement.

#### 5. Organize Content Using HTML Elements:

Use ```<section>```, ```<div>```, or ```<article>``` for logical grouping.

Add a horizontal line (```<hr>```) to separate sections.

#### 6. Keep the Design HTML-Only:

Do not use CSS or JavaScript.

Focus on semantic HTML and readability.
## HTML Code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Naveen M | Profile</title>
</head>
<body>
    <header>
        <h1>Naveen M</h1>
        <h2>Engineering Student</h2>
    </header>

    <section>
        <h3>About Me</h3>
        <img src="image.png" alt="Profile Picture" width="150" height="150">
        <p>
            Aspiring software developer with a solid foundation in Data Structures and Algorithms, seeking an opportunity to apply and grow my skills. 
            Eager to contribute to tasks in a dynamic team environment. I want to be a part of your incredible growth journey and 
            I will be able to add value to the organization.
        </p>
    </section>

    <hr>

    <section>
        <h3>Education</h3>
        <p>
            <B>Bachelor of Engineering in Computer Science Engineering (Internet of Things) </b><br>
            Saveetha Engineering College, 2022 - 2026 <br>
            IV year
        </p>
    </section>

    <hr>

    <section>
        <h3>Techinal Skills</h3>
        <ul>
            <li>C</li>
            <li>C++</li>
            <li>Python</li>
            <li>Java</li>
            <li>SQL</li>
            <li>MongoDB</li>
            <li>SpringBoot</li>
            <li>Cloud Computing</li>
        </ul>
        <h3>Non Techinal Skills</h3>
        <ul>
            <li>Communication</li>
            <li>Analytical Skills</li>
            <li>Creativity</li>
            <li>Leadership</li>
            <li>Self Motivated</li>
        </ul>
    </section>
</body>
</html>

```
## Output:
![alt text](image-1.png)
## Result:
A simple Profile Page using HTML that displays a user's profile image, name, headings, and a short bio, suitable for personal or academic purposes is designed successfully.
