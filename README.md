<!DOCTYPE html>

<html>
  <!--Header-->
  <header>
    <!--Link to Call in Google Font-->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Frank Ruhl Libre:wght@400;700&display=swap"
      rel="stylesheet"/>
    <meta charset="UTF-8" />
    <!--Link to Call in Css File-->
    <link rel="stylesheet" href="styles.css" />
    <!--Favicon-->
    <link rel="icon" type="image/x-icon" href="Images/favicon.png" />
    <!--Site Name-->
    <title>My Site</title>
  </header>

  <!--Content-->
  <body>
    <!--Navigation-->
    <nav>
      <!--Nav Item 1-->
      <div class="nav-link">
        <span></span>
        <a href=""> About Me </a>
      </div>

      <!--Nav Item 2-->
      <div class="nav-link">
        <a href=""> Projects</a>
      </div>

      <!--Nav Item 3-->
      <div class="nav-link">
        <a href="">Resume</a>
      </div>

      
      
      </div>
    </nav>
    
<!--Mobile Nav - Hidden on Desktop -->
  <section class="nav-mobile" role="navigation">
  <div id="menuToggle">
    <input type="checkbox" />
    
    <!--Hamburger Lines -->
    <span></span>
    <span></span>
    <span></span>
    
    <!--Links Inside of Drop Down-->
    <ul id="menu">
      <a href="#"><li>Nav One</li></a>
      <a href="#"><li>Nav Two</li></a>
      <a href="#"><li>Nav Three</li></a>
      <a href="#"><li>Nav Four</li></a>
    </ul>
  </div>
</section>

    <!--Hero-->
    <section class="hero-container">
      <!--Image-->
      
      </div>

      <!--Text Info-->
      <div class="hero-container_copy">
        <h1 class="margin-bottom_five">Hi I'm  Rachel</h1>
        <h2 class="hero-container_sub-copy">UX/UI Designer</h2>
      </div>
    </section>

    <!--Case Study Cards-->
    <section>
      <h2 class="center">Case Studies &amp; Recent Work</h2>

      <!--Card Container-->
      <div class="card-container">

        <!--Card 1-->
        <div class="card">
          <a href="">
            <!--Image-->
              <img src="Screenshot 2023-12-07 3.59.35 PM">
            <!--Copy-->
              <div class="card-copy">
              <h3 class="margin-bottom_five">Bunny World Foundations</h3>
              <p class="margin-top_zero"> Is a redesign of this non-profit organization that saves bunnies that were sold illegally and places them for adoption in better homes.</p>
              <p class="link">Bunny World Foundations </p>
            </div>
          </a>
        </div>

        <!--Card 2-->
         <div class="card">
          <a href="">
            <!--Image-->
              <img src="Screenshot 2023-12-07 3.49.17 PM">
            <!--Copy-->
              <div class="card-copy">
              <h3 class="margin-bottom_five">Loop</h3>
              <p class="margin-top_zero">Is an app that assists you find parking in areas where it's difficult to find public parking. You can pay for the parking in advance to make the process easier, and you can take a picture of your spot to remember where you parked.</p>
              <p class="link">Loop</p>
            </div>
          </a>
        </div>

        <!--Card 3-->
         <div class="card">
          <a href="">
            <!--Image-->
              <img src="Screenshot 2023-12-07 3.52.07 PM">
            <!--Copy-->
               <div class="card-copy">
              <h3 class="margin-bottom_five">TAV</h3>
              <p class="margin-top_zero">Is an app that assists you find parking in areas where it's difficult to find public parking. You can pay for the parking in advance to make the process easier, and you can take a picture of your spot to remember where you parked.</p>
              <p class="link">TAV</p>
            </div>
          </a>
        </div>


            </div>
          </a>
        </div>

      </div>
    </section>

<!--Footer-->
    <footer>
        <!--Contact-->
        <h2 class="margin-bottom_five">Let's Connect</h2>
        <p>I'd Love the Chance to Collaborate</p>
        <a class="link" href="mailto:myemail@gmail.com" target="blank">LinkeIn</a>
        <a class="link" href="tel:123-456-7890">Racheldm421@gmail.com</a>

        <!--Copyright-->
        <p class="copyright">&copy; 2023 Rachel Miller. All Rights Reserved</p>
    </footer>

  </body>
</html>
<!DOCTYPE>

/* Define Global Css*/
body {
 font-family: 'Frank Ruhl Libre",;
 font-weight: 700;
 color: #000000; 
 line-height: 1.5;
 margin: 0; 
}

/* Define Default Global Font Sizes */

h1 {
    font-size: 40px;
}

h2 {
    font-size: 32px;
}

h3 {
    font-size: 24px;
}

h4 {
    font-size: 18px;
}

h5 {
    font-size: 16px;
}

p {
    font-size: 16px;
    font-weight: 400;
}

a {
    font-size: 16px;
    font-weight: 400;
    color: #000000;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}

/*Define Global Helper Styles*/

.center {
    text-align: center;
}

.margin-bottom_five {
    margin-bottom: 5px;
}

.link {
    text-decoration: underline;
}

.link:hover {
    text-decoration: none;
}

.margin-top_zero {
    margin-top: 0;
}

.hero-container_sub-copy {
    font-weight: 400;
}

/*Define Navigation Styles*/

nav {
    background-color: #ffffff;
    display: flex;
    flex-direction: row wrap;
    justify-content: flex-end;
    padding-right: 20px;
    position: sticky;
    top: 0;
}

.nav-link {
/*     display: flex; */
    padding: 20px;
}


.nav-link > span{
  height: 30px; 
  width: 50px;
/*   background-color: #ffffffab; */
  position: absolute;
  

}

span:hover{
  background-color: #00000;
  width: 100px;
    transition: background-color .5s, width .5s, ease;
/*   animation: 3s infinite alternate slidein; */
}

@keyframes slidein{
  from{
    width: 20px;
    
  }
  to{
    width: 100px;
  }
}

.nav-mobile {
  display: none;
}

#menuToggle
{
  display: block;
  position: relative;
  top: 10px;
  left: 10px;
  z-index: 1;
  -webkit-user-select: none;
  user-select: none;
  margin: 20px 20px 30px 20px;
}

#menuToggle a
{
  text-decoration: none;
  color: #000000;
  transition: color 0.3s ease;
}


#menuToggle input
{
  display: block;
  width: 40px;
  height: 32px;
  position: absolute;
  top: -7px;
  left: -5px;
  cursor: pointer;
  opacity: 0; /* hide this */
  z-index: 2; /* and place it over the hamburger */
  
  -webkit-touch-callout: none;
}

/*
 * Just a quick hamburger
 */
#menuToggle span
{
  display: block;
  width: 33px;
  height: 4px;
  margin-bottom: 5px;
  position: relative;
  background: #000000;
  border-radius: 3px;
  z-index: 1;
  transform-origin: 4px 0px;
  transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
              background 0.5s cubic-bezier(0.77,0.2,0.05,1.0),
              opacity 0.55s ease;
}

#menuToggle span:first-child
{
  transform-origin: 0% 0%;
}

#menuToggle span:nth-last-child(2)
{
  transform-origin: 0% 100%;
}

/* 
 * Transform all the slices of hamburger
 * into a crossmark.
 */
#menuToggle input:checked ~ span
{
  opacity: 1;
  transform: rotate(45deg) translate(-2px, -1px);
  background: #000000;
}

/*
 * But let's hide the middle one.
 */
#menuToggle input:checked ~ span:nth-last-child(3)
{
  opacity: 0;
  transform: rotate(0deg) scale(0.2, 0.2);
}

/*
 * Ohyeah and the last one should go the other direction
 */
#menuToggle input:checked ~ span:nth-last-child(2)
{
  transform: rotate(-45deg) translate(0, -1px);
}

/*
 * Make this absolute positioned
 * at the top left of the screen
 */
#menu
{
  position: absolute;
  width: 300px;
  margin: -100px 0 0 -50px;
  padding: 50px;
  padding-top: 125px;
  
  background: #ededed;
  list-style-type: none;
  -webkit-font-smoothing: antialiased;
  /* to stop flickering of text in safari */
  
  transform-origin: 0% 0%;
  transform: translate(-100%, 0);
  
  transition: transform 0.5s cubic-bezier(0.77,0.2,0.05,1.0);
}

#menu li
{
  padding: 10px 0;
  font-size: 22px;
}

/*
 * And let's slide it in from the left
 */
#menuToggle input:checked ~ ul
{
  transform: none;
}
/* Define Hero Styles */
 
.hero-container {
    background-color: #f2f2f2;
    display: flex;
    align-items: center;
    margin-bottom: 60px;
}

.hero-container_img {
   width: 40%;
}
.hero-container_img img {
    width: 100%;
}

.hero-container_copy {
    width: 60%;
    padding: 5%;
}

/* Define Card Styles */

.card-container {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    margin: auto auto 60px auto;
    max-width: 1000px;
}

.card {
    background-color: #f2f2f2;
    width: 40%;
    margin: 20px;
}

.card a:hover {
    text-decoration: none;
}

.card-copy {
    padding: 0 20px 20px 20px;
}

footer {
    background-color: #f2f2f2;
    text-align: center;
    padding: 40px;
}

.copyright {
    font-size: 10px;
    margin-top: 30px;
}

/*Define Media Queries Which Tell the Code How Resize*/

@media screen and (max-width: 768px) {
  .nav-mobile {
    display: block;
  }

    h1 {
        font-size: 24px;
    }

    h2 {
        font-size: 18px;
    }

    .hero-container {
        display: flex;
        flex-direction: column;
    }

    .hero-container_img {
        min-width: 100%;
    }

    .hero-container_copy {
        min-width: 100%;
        margin: 20px;
        padding: 0;
        text-align: center;
    }

}

@media screen and (max-width: 1024px) {
    nav {
        display: none;
    }
    .nav-mobile {
    display: block;
    }
  
    p {
        font-size: 14px;
    }

    .hero-container_img {
        width: 50%;
    }

    .hero-container_copy {
        width: 50%;
    }

    .card {
            width: 100%;
        }

    .card img {
        width: 100%;
    }
}





