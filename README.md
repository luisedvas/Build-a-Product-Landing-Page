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
  <section id="page-wrapper">
    <header id="header">
      <nav id="nav-bar">
        <ul>
          <li>
            <a class="nav-link" href="features">Features</a>
            <a class="nav-link" href="#video">How It Works</a>
            <a class="nav-link" href="#pricing">Pricing</a>
          </li>
        </ul>
      </nav>
      <img id="header-img" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/product-landing-page-logo.png">
      <h1 class="heading-1">Handcrafted, home-made masterpieces</h1>
    </header>
  </section>
  <section id="form-input">
    <form id="form" action="https://www.freecodecamp.com/email-submit">
      <input id="email" name="email" placeholder="Enter your email address" type="email"></input>
      <input id="submit" type="submit"></input>
    </form>
  </section>  
  <section id="features">
    <div class="premium">
      <img class="premium-img" src="" alt="">
      <h2 class="heading-2">Premium Materials</h2>
      <p>Our trombones use the shiniest brass which is sourced locally. This will increase the longevity of your purchase.</p>
    </div> 
    <div class="fast">
      <img class="fast-img" src="" alt="">
      <h2 class="heading-2">Fast Shipping</h2>
      <p>We make sure you recieve your trombone as soon as we have finished making it. We also provide free returns if you are not satisfied.</p>
    </div>
    <div class="quality">
      <img class="quality-img" src="" alt="">
      <h2 class="heading-2">Quality Assurance</h2>
      <p>For every purchase you make, we will ensure there are no damages or faults and we will check and test the pitch of your instrument.</p>
    </div>
  </section>
    <section class="video">
      <iframe id="video" src="https://www.youtube.com/watch?v=y8Yv4pnO7qc&feature=emb_title" controls="1"></iframe>
    </section>
  <section id="pricing">
    <article>
      <p class="tenor">Tenor Trombone<br>$600<br>Lorem ipsum. Lorem ipsum. Lorem ipsum dolor. Lorem ipsum.</p> 
    </article>
    <article>  
      <p class="bass">Bass Trombone<br>$600<br>Lorem ipsum. Lorem ipsum. Lorem ipsum dolor. Lorem ipsum.</p>
    </article>
    <article>  
      <p class="valve">Valve Trombone<br>$600<br>Lorem ipsum. Lorem ipsum. Lorem ipsum dolor. Lorem ipsum.</p>
    </article>  
  </section>
    <footer id="footer">
      <p>Privacy</p>
      <p>Terms</p>
      <p>Contact</p>
        <article>
          <h5 class="heading-5">Copyright 2016, Original Trombones</h5>
        </article>
    </footer>
 </body> 
</html>

