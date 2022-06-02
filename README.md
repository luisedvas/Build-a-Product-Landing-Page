<!DOCTYPE html>
<html>
  <head>
    <title>Product Landing Page</title>
    <meta charset="utf-8">
    <link rel="stylesheet" href="styles.css">
    <link
      rel="stylesheet"
      href="https://use.fontawesome.com/releases/v5.8.1/css/all.css"
      integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf"
      crossorigin="anonymous"
    />      
  </head>
  <body>
    <div id="page-wrapper">
      <header id="header">
        <div class="logo">
          <img id="header-img" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/product-landing-page-logo.png" alt="original trombones logo">
        </div>
        <nav id="nav-bar">
          <ul>
            <li><a class="nav-link" href="#features">Features</a></li>
            <li><a class="nav-link" href="#how-it-works">How It Works</a></li>
            <li><a class="nav-link" href="#pricing">Pricing</a></li>
          </ul>
        </nav>
      </header>
      <!-- Inicio del segundo DIV -->
      <div class="container"></div> 
      <section id="hero">
        <h2>Handcrafted, home-made masterpieces</h2>
        <form id="form" action="https://www.freecodecamp.com/email-submit">
          <input name="email" id="email" type="email" placeholder="enter your email address" required>
          <input id="submit" type="submit" value="Get Started" class="btn">
        </form>
      </section>
      <!-- Inicio del primer DIV -->
      <div class="container">
        <section id="features">
          <div class="grid">
            <div class="icon"><i class="fa fa-3x fa-fire"</i></div>
            <div class="desc">
              <p>
                Our trombones use the shiniest brass which is sourced locally.
                This will increase the longevity of your purchase.
              </p>
            </div>
          </div>
          <div class="grid">
            <div class="icon"><i class="fa fa-3x fa-truck"></i></div>
            <div class="desc">
              <h2>Fast Shipping</h2>
              <p>
                We make sure you recieve your trombone as soon as we have
                finished making it. We also provide free returns if you are not
                satisfied.
              </p>
            </div>
          </div>
          <div class="grid">
  <div class="icon">
    <i class="fa fa-3x fa-battery-full" aria-hidden="true"></i>
  </div>
  <div class="desc">
    <h2>Quality Assurance</h2>
    <p>
      For every purchase you make, we will ensure there are no damages
      or faults and we will check and test the pitch of your
      instrument.
    </p>
  </div>
</div>
</section>
          
        </section>
      </div>
    </div>
      <!-- Aquí quedé en la última línea de código  -->
  </body>
</html>
