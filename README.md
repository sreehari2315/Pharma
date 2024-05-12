# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Product Page</title>
    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
      }
      .banner {
        width: 100%;
        height: 95vh;
        background-image: linear-gradient(
            rgba(0, 0, 0, 0.75),
            rgba(0, 0, 0, 0.75)
          ),
          url(BG.jpeg);
        background-size: cover;
        background-position: center;
      }
      .navbar {
        width: 85%;
        margin: auto;
        padding: 35px 0;
        display: flex;
        align-items: center;
        justify-content: space-between;
      }
      .bg-product {
        border: 1px;
        padding: 10px;
        color: white;
        background-color: red;
        border-radius: 30px;
      }
      .logo {
        color: #fb0b0b;
        font-size: 40px;
        font-weight: 700;
        letter-spacing: 3px;
      }
      span {
        color: white;
      }
      form {
        width: 300px;
        height: 40px;
        display: flex;
        background: rgba(255, 255, 255, 0.2);
        padding: 1px 1px;
        font-size: 15px;
        border-radius: 10px;
        backdrop-filter: blur(4px) saturate(180%);
      }
      form input {
        background: transparent;
        flex: 1;
        border: 0;
        outline: none;
        padding: 12px 20px;
        font-size: 15px;
        color: white;
      }
      ::placeholder {
        color: white;
      }
      form button {
        border: 0;
        outline: none;
        padding: 5px 20px;
        color: white;
        border-radius: 10px;
        background: red;
        cursor: pointer;
      }
      .navbar li {
        list-style: none;
        display: inline-block;
        margin: 0 20px;
        position: relative;
      }
      .navbar li a {
        text-decoration: none;
        color: white;
        text-transform: uppercase;
      }
      .navbar li:hover {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: red;
        color: #081b29;
        box-shadow: 0 0 20px red;
      }
      .container {
        background: transparent;
        padding: 10px 5%;
        padding-bottom: 100px;
      }
      .container .box-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(170px, 1fr));
        gap: 100px;
      }
      .container .box-container .box {
        color: white;
        box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
        border-radius: 20px;
        background: transparent;
        border: 1px solid white;
        padding: 30px 20px;
      }
      .container .box-container .box img {
        height: 70px;
        border-radius: 20px;
      }
      .container .box-container .box h3 {
        color: red;
        font-size: large;
        padding: 20px 0;
      }
      .container .box-container .box p {
        color: white;
        font-size: small;
        line-height: 1.5;
      }
      footer {
        border: 1px;
        padding: 10px;

        transition: 0.5s;
        cursor: pointer;
        border-radius: 30px;
        background: red;
        color: #081b29;
        box-shadow: 0 0 20px red;
      }
    </style>
  </head>
  <body>
    <div class="banner">
      <br />
      <div class="navbar">
        <h1 class="logo">H<span>ARI</span>T<span>ECH</span></h1>
        <ul>
          <li><a href="home.html"> Home </a></li>
          <li><a href="product.html" class="bg-product"> Products </a></li>
          <li><a href="council.html"> People </a></li>
          <li><a href="contact.html"> Contact </a></li>
        </ul>
        <form action="" method="get">
          <input type="text" placeholder="Enter to Search" />
          <button type="submit">Search</button>
        </form>
      </div>
      <div class="container">
        <div class="box-container">
          <div class="box">
            <h3>C++</h3>
            <p>
              Efficiency Redefined: Harnessing the Power of C++ for Next-Level Development
            </p>
          </div>
          <div class="box">
            <h3>C</h3>
            <p>
              Crafting Performance: Where Precision Meets C Programming.
            </p>
          </div>
          <div class="box">
            <h3>JAVASCRIPT</h3>
            <p>
              Scripting Success: Unleashing the Power of JavaScript.
            </p>
          </div>
          <div class="box">
            <h3>PHP</h3>
            <p>
              PHP is a server side scripting language that is embedded in HTML.
            </p>
          </div>
          <div class="box">
            <h3>PYTHON</h3>
            <p>
              Unlocking Innovation: Python Paving the Way to Progress.
            </p>
          </div>
          <div class="box">
            <h3>SQL</h3>
            <p>
              SQL is a standard language for accessing and manipulating
              databases.
            </p>
          </div>
          <div class="box">
            <h3>SHELL</h3>
            <p>
              Shell can be accessed by users using a command line interface.
            </p>
          </div>
          <div class="box">
            <h3>RUBY</h3>
            <p>
              Ruby: Where Simplicity Meets Power in Programming
            </p>
          </div>
          <div class="box">
            <h3>TYPESCRIPT</h3>
            <p>
              Empower Your Code: Embrace the Future with TypeScript
            </p>
          </div>
          <div class="box">
            <h3>F#</h3>
            <p>
              F# is an Open-source programming language with a lot of features.
            </p>
          </div>
        </div>
      </div>
    </div>
    <footer>
      <center>Designed and DEVELOPED BY SREE HARI K (212223230212)</center>
    </footer>
  </body>
</html>
```

## OUTPUT:
![Screenshot 2024-05-12 120729](https://github.com/sreehari2315/Pharma/assets/139331590/a9c55397-3d48-45e9-9ca0-f642487b1b86)


## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
