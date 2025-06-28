
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>RK INSTITUTE VUYYURU</title>
  <link rel="stylesheet" href="/css/RKinstitute.CSS">
  
</head>

<body>

  <header>
    <div class="container">
        <img src="/media/rk.jfif" alt="" width="70px" style="float: left;">
        <h1 class="logo" style="text-align: justify;">RK INSTITUTE VUYYURU</h1> since 2004
      <nav>
        <ul class="nav-links">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#courses">Courses</a></li>
          <li><a href="#contact">Contact</a></li>
          <li><a href="#application forms">application forms</a></li>
        </ul>
      </nav>
    </div>
  </header>
  
 

  <section class="hero" id="home">
    <div style="width: 100%;"> 
        <marquee behavior="" direction="left" loop="-1" scrollamouint="10" > <img src="/media/rk institute banner.jfif" alt=""> </marquee>
        <div class="container" style="width: 70;">
        <h2>Welcome to RK INSTITUTE</h2>
        <p>Empowering Future Generations through Quality Education</p>
        <a href="#about" class="btn">Learn More</a>
        </div>
        
    </div>
  </section>

  <section class="about" id="about">
    <div class="container">
      <h2>About Us</h2>
      <p>My Institution has been delivering excellent education since 2004. Our mission is to provide affordable and quality education for all learners across the India.</p>
    </div>
  </section>

  <section class="courses" id="courses">
    <div class="container">
      <h2>Our Programs</h2>
      <div class="course-list">
        <div class="course">
          <h3>Computer Education</h3>
          <p>MS.OFFICE,PHOTOSHOP,TELUGU TYPING,C,C++JAVA,PHYTON,DBMS,DATA STRUCTURES,WEB DEVELOPMENT......AND MORE.</p>
        </div>
        <div class="course">
          <h3> Compitative</h3>
          <p>SI, CONSTIBALES, RRB,POSTAL, VRO, VRA, GROUP4, PANCHAYATHI SECRETARIES.....AND MORE</p>
        </div>
        <div class="course">
          <h3> ENTERANCE EXAM</h3>
          <p> IIT-NEET, EAPCET/EAMCET, E-SET, I-CET,TTC, LLB, POLYTECHNIC, APRJC,NMMMS,NOVADAYA,SAINIK SCHOOL, GURUKALA.....AND MORE.</p>
        </div>
        <div class="course">
          <h3> Distance Education</h3>
          <p>Open 10th, Open Inter (DISTANCE)
            <hr>
            DEGREE.(B.A,  B.Com,  BSC COMPUTERS,  BLISC,  BBA, B.Com Computers)
            <hr>
            PG. M.A,  M.Com, M.Sc (Maths), MLISc, MA (JOURNALISIM),  MA (POLITICAL SCIENCE), MA (ENGLISH),  MBA, MCA </p>
        </div>
      </div>
    </div>
  </section>
  <section class="application forms" id="APPLICATION FORMS">
    <div class="container">
        <h2> APPLICATION FORM</h2>
        <br><br>
        <div class="Form">
            <a href="https://tinyurl.com/5n6m6s9d"> Open 10th</a>
            <br><br>
            <a href="https://tinyurl.com/5n6m6s9d">Open INTER</a>
            <br><br>
            <a href="https://tinyurl.com/5n6m6s9d">Distance DEGREE</a>
            <br><br>
            <a href="https://tinyurl.com/5n6m6s9d">Distance PG</a>
            <br><br>
            <a href="https://tinyurl.com/5n6m6s9d">COMPUTER EDUCATION</a>
            <br><br>
            <a href="https://tinyurl.com/5n6m6s9d">ENTRANCE EXAM</a>
            <br><br>
    </div>

  </section>
  <section class="contact" id="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Email:rkinstitute99@gmail.com</p>
      <p>Phone: 7396889699</p>
      <p>Address: Pedda Masid Center Behind Of HDFC Bank RK INSTITUTE VUYYURU Krishna District Andhra Pradesh Pin:-521165</p>
      <img src="/media/42x12 ...2...Right & Left Hole.jpg" width="100%" height="200px">
      <hr>
      <a href="http://www.youtube.com/@rkinstitutevuyyuru-ho2lp">youtube</a>

      <a href="https://www.facebook.com/profile.php?id=100004674756048&sk=about">faccebook</a>

      <a href="https://www.instagram.com/krama345/?hl=en">intagram</a>
    </div>
  </section>
  
  <footer>
    <div class="container">
      <p>&copy; 2025 RK INSTITUTEVUYYURU. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>	
/* Reset and basic styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f4f4f4;
}

/* Container */
.container {
  width: 90%;
  max-width: 1100px;
  margin: auto;
}

/* Header */
header {
  background: #003366;
  color: #fff;
  padding: 20px 0;
}

.logo {
  float: left;
}

nav {
  float: right;
}

.nav-links {
  list-style: none;
}

.nav-links li {
  display: inline;
  margin-left: 20px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

header::after {
  content: '';
  display: block;
  clear: both;
}

/* Hero Section */
.hero {
  background: url('https://via.placeholder.com/1200x400') center/cover no-repeat;
  color: solid blue;
  text-align: center;
  padding: 100px 20px;
}

.hero .btn {
  background: #ff6600;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  margin-top: 20px;
  display: inline-block;
}

/* About */
.about, .courses, .contact {
  padding: 60px 20px;
  background-color: white;
  margin-bottom: 20px;
}

.about h2, .courses h2, .contact h2 {
  text-align: center;
  margin-bottom: 20px;
}

/* Courses */
.course-list {
  display: flex;
  justify-content: space-between;
  gap: 20px;
  flex-wrap: wrap;
}

.course {
  flex: 1 1 30%;
  background: #eaeaea;
  padding: 20px;
  border-radius: 5px;
  text-align: center;
}

/* Contact */
.contact p {
  text-align: center;
  margin-bottom: 10px;
}

/* Footer */
footer {
  background: #003366;
  color: white;
  text-align: center;
  padding: 20px;
}

/* Responsive */
@media (max-width: 768px) {
  .nav-links li {
    display: block;
    margin: 10px 0;
  }

  .course-list {
    flex-direction: column;
  }
}
