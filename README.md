
<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Spruce University</title>
   <link rel="stylesheet" href="style.css">
</head>
<body>
   <!-- Header with Navigation -->
   <header>
     <div class="container">
       <!-- University Logo -->
       <div class="logo">
         <h1>Spruce University</h1>
       </div>
       <!-- Navigation Bar -->
       <nav>
         <ul class="nav-links">
           <li><a href="#about">About Us</a></li>
           <li><a href="#programs">Programs</a></li>
           <li><a href="#admissions">Admissions</a></li>
           <li><a href="#student-life">Student Life</a></li>
           <li><a href="#contact">Contact</a></li>
         </ul>
       </nav>
     </div>
   </header>

   <!-- Hero Section -->
   body {
   font-family: Arial, sans-serif;
   margin: 0;
   padding: 0;
   box-sizing: border-box;
}

header {
   background-color: #003366;
   color: white;
   padding: 1em 0;
   text-align: center;
}

.nav-links {
   list-style-type: none;
   padding: 0;
}

.nav-links li {
   display: inline;
   margin: 0 10px;
}

.nav-links a {
   color: white;
   text-decoration: none;
}

.hero {
   height: 100vh;
   background: url('https://example.com/hero-image.jpg') no-repeat center center/cover;
   display: flex;
   align-items: center;
   justify-content: center;
   color: #fff;
   text-align: center;
}

.hero-content h1 {
   font-size: 3.5em;
   margin-bottom: 10px;
}

.hero-content p {
   font-size: 1.5em;
   margin-bottom: 20px;
}

.hero-buttons .btn, .hero-buttons .btn-secondary {
   padding: 12px 24px;
   font-size: 1.2em;
   border-radius: 5px;
   text-decoration: none;
   margin: 10px;
}

.hero-buttons .btn {
   background-color: #ffcc00;
   color: #003366;
}

.hero-buttons .btn-secondary {
   background-color: #fff;
   color: #003366;
   border: 2px solid #ffcc00;
}

.hero-buttons .btn:hover, .hero-buttons .btn-secondary:hover {
   opacity: 0.8;
}

   <section class="hero">
     <div class="hero-content">
       <h1>Welcome to Spruce University</h1>
       <p>Explore Programs, Campus Life, and Online Services</p>
       <div class="hero-buttons">
         <a href="#apply" class="btn">Apply Now</a>
         <a href="#visit" class="btn-secondary">Visit Us</a>
       </div>
     </div>
   </section>
</body>
</html>
<!-- About Us Section -->
<section id="about">
   <div class="container">
      <h2>About Us</h2>
      <p>Spruce University is dedicated to providing high-quality education and fostering an inclusive, engaging community for all students.</p>
   </div>
</section>

<!-- Programs Section -->
<section id="programs">
   <div class="container">
      <h2>Programs</h2>
      <p>We offer a wide range of undergraduate, graduate, and professional programs to help students achieve their academic and career goals.</p>
   </div>
</section>

<!-- Admissions Section -->
<section id="admissions">
   <div class="container">
      <h2>Admissions</h2>
      <p>Learn more about our admissions process and how to apply to Spruce University.</p>
   </div>
</section>

<!-- Student Life Section -->
<section id="student-life">
   <div class="container">
      <h2>Student Life</h2>
      <p>Discover the vibrant student life at Spruce University, including clubs, organizations, and events.</p>
   </div>
</section>

<!-- Contact Section -->
<section id="contact">
   <div class="container">
      <h2>Contact</h2>
      <p>Get in touch with us for more information or any questions you may have.</p>
   </div>
</section>
