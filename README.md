# 📘 HTML BASICS  

## 📅 Day 1: HTML Basics  

### 🔹 What is HTML?

HTML stands for **HyperText Markup Language**.  
It is the standard language used to create and structure web pages.

HTML does not add design — it gives structure to the content like:

- Headings  
- Paragraphs  
- Images  
- Links  
- Sections  

It is the foundation of every website.

---

### 🔹 HTML Document Structure

Every HTML document follows a basic structure:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Web Page</title>
</head>
<body>
    <h1>Hello World</h1>
    <p>This is my first HTML page.</p>
</body>
</html>
 ```

### Explanation:

- `<!DOCTYPE html>` → Defines the document type  
- `<html>` → Root element of the page  
- `<head>` → Contains title and meta information  
- `<body>` → Contains visible content  

---

### 🔹 Create a Simple Profile Page

For practice, I created a simple profile page using:

- Heading (`h1`)  
- Image (`img`)  
- Paragraph (`p`)  
- Sections using (`div`)  
- Basic styling  

---

## ✅ What I Learned Today

- How HTML works  
- Basic structure of a webpage  
- Difference between block and inline elements  
- How to add images and links  
- How to organize content properly

## My Profile
```html


<!DOCTYPE html>
<html>
<head>
    <title>Web Page</title>

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
        }

        p {
            margin: auto;
        }
    </style>
</head>

<body>

    <div class="container">

        <h1>My Profile</h1>

        <img src="photo2.jpeg" width="300" height="200" style="border-radius: 100%;">

        <h2>About Me</h2>

        <p style="width: 50%;">
            My name is Hanok Kumar, and I am currently learning Full Stack Development.
            I am very interested in building modern and interactive websites.
            I am passionate about improving my skills and growing as a web developer every day.

            If you want it more powerful and confident sounding, I can upgrade it.
        </p>

        <h2>Skill</h2>

        <strong>html</strong>
        <strong>java</strong>
        <strong>dsa</strong>

        <h2>Contact Me</h2>

        <p>E mail : sadharlahanok@gmail.com</p>
        <p>GitHub : https://github.com/HANOK18</p>

    </div>

</body>
</html>
```
 




