# MDAP-EX_01-Portfolio
## Date: 12.08.2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Daksha C - Portfolio</title>
  <style>
    /* Reset & basics */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: #333;
      line-height: 1.6;
      padding: 20px;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: flex-start;
    }
    .container {
      max-width: 900px;
      background: #fff;
      margin: 40px 0;
      padding: 30px 40px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.15);
      border-radius: 15px;
      width: 100%;
    }
    header {
      text-align: center;
      margin-bottom: 50px;
      color: #fff;
    }
    header h1 {
      font-size: 3.2rem;
      letter-spacing: 5px;
      font-weight: 700;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.3);
    }
    h1.name {
      color: #2c3e50;
      letter-spacing: 2px;
      margin-bottom: 30px;
    }
    h2 {
      color: #2c3e50;
      margin-bottom: 15px;
      border-bottom: 3px solid #764ba2;
      padding-bottom: 8px;
      font-weight: 600;
    }
    p {
      margin-bottom: 20px;
      font-size: 1.1rem;
    }
    ul {
      margin-left: 20px;
      margin-bottom: 30px;
    }
    ul li {
      margin-bottom: 10px;
      font-size: 1.05rem;
      padding-left: 10px;
      position: relative;
    }
    ul li::before {
      content: "•";
      position: absolute;
      left: 0;
      color: #764ba2;
      font-weight: bold;
      font-size: 1.2rem;
      line-height: 1;
      top: 0;
    }
    a {
      color: #764ba2;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    a:hover {
      color: #667eea;
      text-decoration: underline;
    }
    .section {
      margin-bottom: 40px;
    }
    .contact-item {
      margin-bottom: 12px;
      font-size: 1.1rem;
    }
    .contact-item strong {
      display: inline-block;
      width: 100px;
      color: #34495e;
    }
    /* Responsive */
    @media(max-width:600px) {
      .container {
        padding: 20px;
      }
      header h1 {
        font-size: 2.5rem;
      }
      h1.name {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>PORTFOLIO</h1>
    </header>

    <h1 class="name">Daksha C</h1>

    <div class="section about-me">
      <h2>About Me</h2>
      <p>
        I am a passionate AI and Data Science student dedicated to learning and applying machine learning, data analysis, and programming to solve real-world problems. Currently, I am exploring projects and research in AI to build a strong foundation for my career.
      </p>
    </div>

    <div class="section skills">
      <h2>Skills</h2>
      <ul>
        <li>Python</li>
        <li>Machine Learning</li>
        <li>Data Analysis (Pandas, NumPy)</li>
        <li>Deep Learning basics</li>
        <li>HTML, CSS, JavaScript</li>
        <li>SQL</li>
        <li>Tableau (for data visualization)</li>
        <li>Git & GitHub</li>
      </ul>
    </div>

    <div class="section projects">
      <h2>Projects & Experience</h2>
      <ul>
        <li>Built a simple handwritten digit recognition model using Python and TensorFlow.</li>
        <li>Data analysis project on COVID-19 dataset using Python libraries.</li>
        <li>Created a responsive personal portfolio website with HTML, CSS, and JavaScript.</li>
      </ul>
    </div>

    <div class="section contact">
      <h2>Contact</h2>
      <p class="contact-item"><strong>Email:</strong> <a href="mailto:daksha.email@example.com">daksha.email@example.com</a></p>
      <p class="contact-item"><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/dakshac" target="_blank">linkedin.com/in/dakshac</a></p>
      <p class="contact-item"><strong>GitHub:</strong> <a href="https://github.com/dakshac" target="_blank">github.com/dakshac</a></p>
      <p class="contact-item"><strong>Phone:</strong> +91-XXXXXXXXXX</p>
    </div>
  </div>
</body>
</html>
```


## OUTPUT


<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/dd557153-67af-475c-87ed-60a63c7655df" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
