# Build-a-Product-Landing-Page
<!-- Project #3 freeCodeCamp Responsive Certification -->
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Product Landing Page</title>  
    <link rel="stylesheet" type="text/css" href="styles.css">
  </head>
  <body>
  <div id="page-wrapper">
    <header id="header">
      <div class="logo">
        <img id="header-img" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/product-landing-page-logo.png" alt="original trombone logo">
      </div>
      <nav id="nav-bar">
        <ul>
          <li>
            <a class="nav-link" href="#features">Features</a>
          </li>
          <li>
            <a class="nav-link" href="#how-it-works">How It Works</a>
          </li>
          <li>
            <a class="nav-link" href="#pricing">Pricing</a>
          </li>
        </ul>
      </nav>
    </header>
    <div class="container"></div>
  <section id="hero">
    <h2>Handcrafted, home-made masterpieces</h2>
    <form id="form" action="https://www.freecodecamp.com/email-submit">
      <input id="email" name="email" placeholder="Enter your email address" type="email" required></input>
      <input id="submit" type="submit" value="Get Started" class="btn"></input>
    </form>
  </section>  
  <div class="container">
    <section id="features">
      <div class="grid">
        <div class="icon"></div>
        <div class="desc"></div>
      </div>
      <div class="grid">
        <div class="icon"></div>
        <div class="desc"></div>
      </div>
      <div class="grid">
        <div class="icon"></div>
        <div class="desc"></div>
      </div>
    </section>   
    <footer id="footer">
      <ul>
        <li>
          <a href="#">Privacy</a>
        </li>
        <li>  
          <a href="#">Terms</a>
        </li>
        <li>
          <a href="#">Contact</a>
        </li>  
      </ul> 
          <span>Copyright 2016, Original Trombones</span>
    </footer>
  </div>
 </body> 
</html>
