<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Paul Levites</title>
    <style>
    /* google fonts */
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,400;0,600;0,700;1,500&display=swap');
*{
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    scroll-padding-top: 2rem;
    scroll-behavior: smooth;
    box-sizing: border-box;
    list-style: none;
    text-decoration: none;
}

:root {
    --main-color: #fd4646;
    --text-color: #171427;
    --bg-color: #ffffff;
}
img{
    width: 100%;
}
body{
    color: var(--text-color);
}
.container{
    max-width: 1068px;
    margin: auto;
    width: 100%;
}
section{
    padding: 7rem 0 3rem;
}
header{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background:  var(--bg-color);
    box-shadow: 0 1px 4px hsl(0 4% 15% / 10%);
}
nav{
    display: flex;
    align-items: center;
    justify-content: right;
    font-size: 1.1rem;
}
span{
    text-align: center;
    background-color: var(--bg-color);
    color: var(--text-color);
    font-family: 'Times New Roman', Times, serif;
    font-size: 15px;
}
footer{
  background-color: black;
  color: white;
  background: black;
}
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  flex: 25%;
  max-width: 50%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    flex: 100%;
    max-width: 100%;
  }
}

/* Three columns side by side */
.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

/* Display the columns below each other instead of side by side on small screens */
@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

/* Add some shadows to create a card effect */
.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

/* Some left and right padding inside the container */
.About_container {
  padding: 0 16px;
}

/* Clear floats */
.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}



 /* Style the form element with a border around it */
 form {
  border: 4px solid #f1f1f1;
}

/* Add some padding and a grey background color to containers */
.Form_container {
  padding: 20px;
  background-color: #f1f1f1;
}

/* Style the input elements and the submit button */
input[type=text], input[type=submit] {
  width: 100%;
  padding: 12px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

/* Add margins to the checkbox */
input[type=checkbox] {
  margin-top: 16px;
}

/* Style the submit button */
input[type=submit] {
  background-color: Black;
  color: white;
  border: none;
}

input[type=submit]:hover {
  opacity: 0.8;
} 
    </style>
  </head>
  <body>
    <script src="home.js"></script>
    <header style="background-color: black">
      <div class="class container">
        <a href="Home.html" class="logo" style="color: gold">Paul Levites</a>
      </div>
      <!--Menu Bar/Icons-->
      <nav style="background-color: black">
        <span style="background-color: black">
          <a href="Home.html" style="margin-right: 15px; color: gold">Home</a>
        </span>
        <span style="background-color: black">
          <a href="about.html" style="margin-right: 15px; color: gold">About</a>
        </span>
        <span style="background-color: black">
          <a href="Contact.html" style="margin-right: 15px; color: gold"
            >Contact Us</a
          >
        </span>
        <span style="background-color: black">
          <a href="Take quote.html" style="margin-right: 15px; color: gold"
            >Take a quote</a
          >
        </span>
      </nav>
    </header>
    <!--First section of Home-->
    <section class="Welcome" style="background-color: black; color: gold">
      <h2
        style="
          font-size: 40px;
          font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
          font-weight: lighter;
          text-align: center;
          margin-top: -50px;
        "
        class="section-title"
      >
        Welcome To The Official Website Of <br />
        <h1 style="text-align: center">Paul Ifeoluwa-Levites</h1>
      </h2>
      <!--content-->
      <div class="head picture">
        <img
          src="Images/251579258_227759512782657_3864943739883121752_n.jpg"
          alt=""
        />
      </div>
    </section>
    <hr />
    <!--About Paul Levites-->
    <section>
      <h1
        style="
          text-align: center;
          margin-top: -100px;
          font-family: 'Times New Roman', Times, serif;
        "
      >
        Meet Me
      </h1>
      <div class="row" style="align-content: center">
        <div class="column">
          <div class="card">
            <img
              src="Images/251579258_227759512782657_3864943739883121752_n.jpg"
              alt="Paul"
              style="width: 100%"
            />
            <div class="About_container">
              <h2>Paul Levites</h2>
              <p class="title">Web Designer &amp; Photographer</p>
              <p>
                Hi there, Welcome to my website. My name is Paul Levites.
                <br />I am a web designer, and a photographer.
              </p>
            </div>
          </div>
        </div>
        <div class="column">
          <div class="card">
            <img src="Images/Paul Levites.jpg" alt="Paul" style="width: 100%" />
          </div>
        </div>
      </div>
    </section>
    <!--Subscription Form-->
    <form action="action_page.php">
      <div class="Form_container">
        <h2 style="text-align: center">Subscribe To Get More Info</h2>
      </div>

      <div class="Form_container" style="background-color: white">
        <input type="text" placeholder="Name" name="name" required />
        <input type="text" placeholder="Email address" name="mail" required />
        <label>
          <input type="checkbox" checked="checked" name="subscribe" /> Daily
          Newsletter
        </label>
      </div>

      <div class="Form_container">
        <input type="submit" value="Subscribe" />
      </div>
    </form>
    <footer style="text-align: center; font-size: small">
      <h3 style="text-align: center; color: gold">Socialize with me @</h3>
      <span style="color: black; background-color: blue">
        <a
          class="_26AQd"
          data-testid="linkElement"
          href="http://facebook.com/PaulLevites"
          target="_blank"
        >
          <img
            src="https://static.wixstatic.com/media/0fdef751204647a3bbd7eaa2827ed4f9.png/v1/fill/w_20,h_20,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Facebook.png"
            alt="Facebook"
            style="
              width: 20px;
              height: 20px;
              object-fit: cover;
              object-position: 50% 50%;
            "
          />
        </a>
      </span>
      <span style="color: black; background-color: Pink">
        <a
          href="https://www.instagram.com/Paullevites_official/"
          target="_blank"
        >
          <img
            src="https://static.wixstatic.com/media/01c3aff52f2a4dffa526d7a9843d46ea.png/v1/fill/w_16,h_16,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Instagram.png"
            alt="Instagram"
            style="
              width: 20px;
              height: 20px;
              object-fit: cover;
              object-position: 50% 50%;
            "
          />
        </a>
      </span>
      <br />
      <span style="color: gold; background-color: black">
        © Paul Levites 2022. <br />
      </span>
    </footer>
  </body>
</html>
