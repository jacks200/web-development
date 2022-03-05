# college fest web-development



<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <!-- Web page CSS -->
    <link rel="stylesheet" href="assets/css/styles.css" />

    <!-- Simple lightbox CSS -->
    <link rel="stylesheet" href="assets/css/simple-lightbox.min.css" />

    <!-- Favicons -->
    <link
      rel="apple-touch-icon"
      sizes="180x180"
      href="assets/icons/apple-touch-icon.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="32x32"
      href="assets/icons/favicon-32x32.png"
    />
    <link
      rel="icon"
      type="image/png"
      sizes="16x16"
      href="assets/icons/favicon-16x16.png"
    />

    <title>Ramco Fest Landing Page</title>
  </head>
  <body>
    <!-- Navbar -->

    <!-- Dark/light theme switcher -->

    <!-- Bars -->

    <!-- Events section -->

    <!-- About section -->

    <!-- Lightbox image gallery -->

    <!-- Event teams -->

    <!-- Contact -->

    <!-- Social icons -->

    <!-- Scroll to top button -->

    <!-- Web page script -->
    <script src="assets/js/app.js"></script>

    <!-- Ion icons CDN -->
    <script
      type="module"
      src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"
    ></script>

    <!-- Simple lightbox -->
    <script src="assets/js/simple-lightbox.min.js"></script>
    <script>
      // Simple lightbox initializer
    </script>
  </body>
</html>
<nav>
      <a href="#" class="logo">
        <h1>
          <span class="ramco">RAMCO</span><span class="fest">FEST</span
          ><span class="fist">&#x1F44A;</span>
        </h1>
      </a>
</nav>

<ul>
        <li class="nav-item">
          <a href="#about" class="nav-link" id="nav-link">About</a>
        </li>
        <li class="nav-item">
          <a href="#events" class="nav-link" id="nav-link">Events</a>
        </li>
        <li class="nav-item">
          <a href="#eventteams" class="nav-link" id="nav-link"
            >Eventteams</a
          >
        </li>
        <li class="nav-item">
          <a href="#contact" class="nav-link" id="nav-link">Contact</a>
        </li>
</ul>
<div class="hamburger" id="hamburger">
    <span class="bar"></span>
    <span class="bar"></span>
    <span class="bar"></span>
</div>
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,900;1,700&display=swap");

/* CSS Variables */
:root {
  --normal-font: 400;
  --bold-font: 600;
  --bolder-font: 900;
  --primary-color: #0652dd;
  --secondary-color: #ea2027;
  --line-height: 1.7rem;
  --transition: 0.4s ease-in;
}

html {
  scroll-behavior: smooth;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  transition: var(--transition);
}

 body {
  font-family: "Roboto", sans-serf;
}

ul li {
  list-style-type: none;
}

a {
  text-decoration: none;
  color: var(--primary-color);
}

a:hover {
  color: var(--secondary-color);
} 
.fist {
    color: var(--secondary-color);
  }
  
  .ramco {
    color: var(--primary-color);
  }
  
  .fest {
    color: var(--secondary-color);
  }
  nav {
    background:rgb(238, 184, 148);
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 1.5rem;
    box-shadow: 2px 3px 2px#bbbbbb;
  }
position: sticky;
   top: 0;
   left: 0;
   z-index: 1;
.hamburger {
display: none;
}
.logo {
    font-size: 2rem;
    font-weight: 500;
  }
  
  ul {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .nav-item {
    margin-left: 2rem;
  }
  
  .nav-link {
    font-weight: var(--bold-font);
  }
  <section class="events">
      <div class="intro-text">
        <h1>
          <span class="see"> You can See Various Events </span> <br />
          <span class="connecting"> Connecting</span>
        </h1>
        <p>
          An online streaming platform for our college fest <br />
          All the events of our college fest can be view by onlone
        </p>
        <a class="btn red" href="#">Learn More</a>
        <a class="btn blue" href="#">Contact</a>
      </div>
      <div class="i-frame">
        <iframe
          width="560"
          height="315"
          src="https://youtu.be/vio-sP0qsdw"
          title="YouTube video player"
          frameborder="10"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        ></iframe>
        <div class="stand-1"></div>
        <div class="stand-2"></div>
      </div>
    </section>
display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1.9rem;
    max-width: 1100px;
    margin: 2rem auto -6rem;
  }
  .intro-text h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
  }
  
  .intro-text h3 {
    margin-bottom: 0.5rem;
  }
  
  .hero p {
    line-height: var(--line-height);
  }
  
  .hear {
    color: var(--primary-color);
  }
  
  .connecting {
    color: var(--secondary-color);
  }
  .btn {
    margin-top: 1rem;
    display: inline-block;
    padding: 0.8rem 0.6rem;
    border: none;
    font-size: 1.4rem;
    border-radius: 5px;
    color: #fff;
  }
  
  .red {
    background-color: var(--secondary-color);
    margin-right: 1.5rem;
  }
  
  .red:hover {
    background-color: #f1262d;
    color: #fff;
  }
  
  .blue {
    background-color: var(--primary-color);
  }
  
  .blue:hover {
    background-color: #095cf7;
    color: #fff;
  }
  iframe {
    max-width: 30rem;
    border-top: 40px groove var(--primary-color);
    border-bottom: 40px groove var(--primary-color);
    border-right: 28px solid var(--secondary-color);
    border-left: 28px solid var(--secondary-color);
  }
  
  .stand-1 {
    height: 90px;
    width: 6px;
    background-color: var(--primary-color);
    transform: rotate(40deg);
    position: relative;
    top: -16px;
    left: 200px;
  }
  .stand-2 {
    height: 90px;
    width: 6px;
    background-color: var(--secondary-color);
    transform: rotate(-40deg);
    position: relative;
    top: -105px;
    left: 255px;
  }
  <section class="about" id="about">
  <h3>Watch the Fest Events</h3>
  <p>
    Our primary objective is to bring live events and programs to students all around
    the world
  </p>

  <h3>Not some Events</h3>
  <p>
    We also air documentaries specially made for the every year fest programs can be seen at any time</p>
</section>
.about {
    position: relative;
    background: url("../images/ramco fest.png") no-repeat top center/cover;
    height: 600px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    gap: 1.5rem;
    margin: 2rem 0;
  }
  .about h3 {
    font-size: 3em;
    margin-bottom: -20px;
  }
  
  .about p {
    font-size: 1.5em;
  }
  
  .about h3 {
    text-shadow: 2px 2px 2px #333;
  }
  
  .about p {
    text-shadow: 2px 2px 2px #333;
    font-size: 1.8rem;
  }
  <section class="events" id="events">
  <div class="events-gallery">
    <a href="assets/images/dancing.jpg" class="big">
      <img
        src="assets/images/dancing.jpg"
        alt="Dancing"
        title="Dance"
      />
    </a>

    <a href="assets/images/singing.jpg" class="big">
      <img
        src="assets/images/singing.jpg"
        alt="Singing"
        title="Songs"
      />
    </a>

    <a href="assets/images/drama.webp.jpg" class="big">
      <img
        src="assets/images/drama.webp.jpg"
        alt="Drama"
        title="Drama"
      />
    </a>

    <a href="assets/images/speech.jpg" class="big">
      <img
        src="assets/images/speech.jpg"
        alt="Speech"
        title="Speech"
      />
    </a>

    <a href="assets/images/mime.jpg" class="big"
      ><img
        src="assets/images/mime.jpg"
        alt="Mime"
        title="MIME"
      />
    </a>

    <a href="assets/images/prize.jpg" class="big">
      <img
        src="assets/images/prize.jpg"
        alt="prize"
        title="Prize"
      />
    </a>
  </div>
</section>
<script>
     var lightbox = new SimpleLightbox(".events-gallery a");
</script>
.events-gallery {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
  }
  .events-gallery img,
  .events-gallery a {
    width: 100%;
    height: 100%;
  }
  <section class="people" id="Events team">
  <div class="teams">
    <div class="persons">
      <div class="person-1">
        <img src="assets/images/john.jpg" alt="John Doe" />
        <p class="name">John Doe</p>
        <p class="role">Event Head</p>
      </div>
      <div class="person-2">
        <img src="assets/images/jane.jpg" alt="Jane Doe" />
        <p class="name">Jane Doe</p>
        <p class="role">Supervisor</p>
      </div>
      <div class="person-3">
        <img src="assets/images/jnr.jpg" alt="John Doe Jnr" />
        <p class="name">John Doe JNR</p>
        <p class="role">Host</p>
      </div>
    </div>
  </div>
</section>
.people {
    margin-top: 2rem;
    padding: 1rem 0;
  }
  
.eventteams {
    margin: 2rem auto;
    max-width: 1100px;
  }
  
.eventteams img {
    border-radius: 0.6rem;
  }
  .persons {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    place-items: center;
    gap: 1rem;
  }
  .name {
    color: var(--primary-color);
    text-align: center;
  }
  
  .role {
    color: var(--secondary-color);
    text-align: center;
    font-size: 0.8rem;
  }
  <section class="contact" id="contact">
  <h3>Send newsletter for queries</h3>
  <form action="#">
    <input
      type="queries"
      name="queries"
      id="queries-contact"
      class="queries-contact"
      required
    />
    <input
      type="submit"
      value="submit"
      id="submit-btn"
      class="submit-btn"
    />
  </form>
</section>
.sub {
    margin-top: 2rem;
  }
  
.sub h3 {
    text-align: center;
  }
  
form {
    text-align: center;
    margin: 0.4rem 2rem;
  }
  .queries-contact {
    padding: 0.2rem;
    border: 1px solid var(--primary-color);
    border-radius: 4px;
  }
  
  .queries-contact:focus {
    border: 1px solid var(--secondary-color);
    outline: none;
  }
  <section class="social">
  <h3>Connect with us on Social Media</h3>
  <div class="socicons">
    <a href="#"> <ion-icon name="logo-twitter"></ion-icon> </a>
    <a href="#"> <ion-icon name="logo-instagram"></ion-icon> </a>
    <a href="#"> <ion-icon name="logo-facebook"></ion-icon> </a>
  </div>
</section>
.social {
    text-align: center;
    margin: 2rem;
  }
  
.socicons {
    font-size: 1.3rem;
  }
footer {
    border-top: 1px solid #f1f1f1;
    box-shadow: 0px -2px 3px #f1f1f1;
    text-align: center;
    padding: 2rem;
  }
<i class="scroll-up" id="scroll-up"
  ><img
    src="assets/icons/icons8-upward-arrow.png"
    class="socicon up-arrow"
    alt="up-arrow"
/></i>
.scroll-up {
    position: fixed;
    right: 0.5%;
    bottom: 3%;
    cursor: pointer;
  }
  
.up-arrow {
    width: 3rem;
    height: 3rem;
  }
const scrollUp = document.querySelector("#scroll-up");

scrollUp.addEventListener("click", () => {
    window.scrollTo({
      top: 0,
      left: 0,
      behavior: "smooth",
    });
  });


