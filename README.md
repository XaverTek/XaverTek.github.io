<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="google-site-verification" content="Wj8kmqLDou7goEh6BlOckRK-ta1AC5b8wYZ6AyyvL9w" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Xaver Technologies - Empowering Tomorrow's Innovations Today">
  <meta name="keywords" content="Xaver Technologies, technology solutions, innovation, quality assurance, global impact">
  <title>XaverTek Technologies</title>
  
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  
  <!-- Custom CSS -->
  <style>
    /* Custom CSS Styles */
    body {
      padding-top: 4.5rem; /* Adjust for fixed navbar height */
      background-color: #f0f0f0; /* Default background color */
      transition: background-color 0.3s ease;
      font-family: Arial, sans-serif; /* Example custom font */
    }
    section {
      margin-bottom: 3rem;
    }
    .footer {
      padding: 2rem 0;
      background-color: #030111;
      color: white;
      text-align: center;
    }
    .footer ul {
      list-style: none;
      padding: 0;
    }
    .footer ul li {
      display: inline;
      margin-right: 10px;
    }
    .card {
      transition: transform 0.3s ease, box-shadow 0.3s ease; /* Hover effect transition */
    }
    .card:hover {
      transform: translateY(-10px); /* Hover effect */
      box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Hover effect shadow */
    }
    .dark-mode body {
      background-color: #222; /* Dark mode background color */
      color: #fff; /* Dark mode text color */
    }
    .company-logo {
      width: 150px; /* Adjust logo size */
      height: auto;
      margin-bottom: 20px;
    }

    /* Additional CSS Enhancements */
    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      transition: opacity 0.5s ease, transform 0.5s ease;
    }
    .fade-in.active {
      opacity: 1;
      transform: translateY(0);
    }
    .btn-outline-light:hover {
      color: #17a2b8;
      background-color: transparent;
    }
    .testimonial {
      margin-bottom: 30px;
    }
    .carousel-item img {
      width: 100%;
      height: auto;
    }
  </style>
</head>
<body>
  
  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top" role="navigation">
    <div class="container">
      <a class="navbar-brand" href="#">XaverTek Technologies</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#services">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#industries">Industries</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#our-staff">Our Staff</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
          <li class="nav-item">
            <button id="darkModeToggle" class="btn btn-outline-light">Toggle Dark Mode</button>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  
  <!-- Main Content -->
  <div class="container mt-5">
    <section id="home">
      <h1>Welcome to XaverTek Technologies</h1>
      <img src="image.png" class="company-logo" alt="Company Logo">
      <p>Empowering Tomorrow's Innovations Today</p>
      <p>Welcome to Xaver Technologies, where innovation meets excellence. We are at the forefront of cutting-edge technology solutions, dedicated to transforming industries and empowering businesses worldwide. Explore how our passion for innovation drives us to redefine what's possible in:</p>
      <ul>
        <li>Technology Solutions: Discover our comprehensive suite of products and services tailored to meet the needs of specific industries or clients.</li>
        <li>Quality Assurance: Our commitment to excellence ensures every solution we deliver meets the highest standards of quality and reliability.</li>
        <li>Global Impact: See how our innovative solutions are making a positive impact on businesses and communities around the globe.</li>
      </ul>
      <p>Join us on our journey towards a smarter, more connected future.</p>
    </section>
    
    <section id="about">
      <h2>About Us</h2>
      <p>XaverTek Technologies is dedicated to delivering cutting-edge technology solutions that empower businesses and transform industries. Our commitment to innovation and quality assurance sets us apart, ensuring that every solution we deliver meets the highest standards of excellence.</p>
      <p>Discover how we harness the power of technology to drive global impact, making a difference in businesses and communities worldwide.</p>
    </section>
    
    <section id="services">
      <h2>Our Services</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Technology Solutions</h5>
              <p class="card-text">Explore our innovative technology solutions designed to meet the unique needs of various industries.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Quality Assurance</h5>
              <p class="card-text">Our rigorous quality assurance processes ensure that every solution we deliver meets the highest standards.</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title">Global Impact</h5>
              <p class="card-text">See how our technology solutions are making a positive impact on a global scale.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <section id="industries">
      <h2>Industries We Serve</h2>
      <p>Our technology solutions are tailored to meet the unique needs of various industries, including:</p>
      <ul>
        <li>Creating and game development</li>
        <li>We help to create anti-viruses of all kinds</li>
        <li>We develop wesites of agencies,businesses,instites</li>
        <li>Provide software cerations of all kinds </li>
        <li>Telecommunications</li>
        <li>create applications for businesses among others</li>
      </ul>
      <p>Discover how our industry expertise and innovative solutions can drive your business forward.</p>
    </section>
    
    <section id="our-staff">
      <h2>Our Staff</h2>
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="staff1.jpg" class="card-img-top" alt="Staff Member">
            <div class="card-body">
              <h5 class="card-title">Chelangat Pius Starling</h5>
              <p class="card-text">Position: Co-founder/Chief Executive Officer</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="staff2.jpg" class="card-img-top" alt="Staff Member">
            <div class="card-body">
              <h5 class="card-title">Nsabimana Shadrach</h5>
              <p class="card-text">Position: Senior Graphics Designer</p>
            </div>
          </div>
        </div>
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="staff3.jpg" class="card-img-top" alt="Staff Member">
            <div class="card-body">
              <h5 class="card-title">Gertrude Dianah Muhumua</h5>
              <p class="card-text">Position: Senior Software Engineer</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <section id="contact">
      <h2>Contact Us</h2>
      <div class="row">
        <div class="col-md-6">
          <form id="contactForm" action="mailto:info@example.com" method="POST" enctype="text/plain">
            <div class="form-group">
              <label for="name">Name:</label>
              <input type="text" class="form-control" id="name" name="name" required>
            </div>
            <div class="form-group">
              <label for="email">Email:</label>
              <input type="email" class="form-control" id="email" name="email" required>
            </div>
            <div class="form-group">
              <label for="message">Message:</label>
              <textarea class="form-control" id="message" name="message" rows="5" required></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send Message</button>
          </form>
        </div>
        <div class="col-md-6">
          <h3>Visit Us</h3>
          <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3861.423757842412!2dYOUR_LONGITUDE!3dYOUR_LATITUDE!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zYOUR_LOCATION!5e0!3m2!1sen!2sus!4v1623801621902!5m2!1sen!2sus" 
                  width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
      </div>
    </section>
  </div>
  
  <!-- Testimonials -->
  <div class="container mt-5">
    <section id="testimonials">
      <h2>Client Testimonials</h2>
      <div class="row">
        <div class="col-md-6">
          <div class="testimonial">
            <blockquote>
              "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante."
            </blockquote>
            <p class="testimonial-author">John Doe, CEO of Company X</p>
          </div>
        </div>
        <div class="col-md-6">
          <div class="testimonial">
            <blockquote>
              "Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam."
            </blockquote>
            <p class="testimonial-author">Jane Smith, Director of Operations</p>
          </div>
        </div>
      </div>
    </section>
  </div>
  
  <!-- Footer -->
  <footer class="footer">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#industries">Industries</a></li>
            <li><a href="#our-staff">Our Staff</a></li>
            <li><a href="#contact">Contact</a></li>
          </ul>
        </div>
        <div class="col-md-6">
          <p>&copy; 2024 XaverTek Technologies. All rights reserved.</p>
        </div>
      </div>
    </div>
  </footer>
  
  <!-- jQuery and Bootstrap Bundle (includes Popper) -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  
  <!-- Custom JavaScript -->
  <script>
    // Dark Mode Toggle
    const darkModeToggle = document.getElementById('darkModeToggle');
    darkModeToggle.addEventListener('click', function() {
      document.body.classList.toggle('dark-mode');
    });

    // Form Submission
    const contactForm = document.getElementById('contactForm');
    contactForm.addEventListener('submit', function(event) {
      event.preventDefault();
      const formData = new FormData(contactForm);
      const name = formData.get('name');
      const email = formData.get('email');
      const message = formData.get('message');
      // Replace with your email handling logic or API call
      console.log(`Name: ${name}, Email: ${email}, Message: ${message}`);
      alert('Message sent successfully!');
      contactForm.reset();
    });

    // Image Lazy Loading
    document.addEventListener("DOMContentLoaded", function() {
      const lazyImages = document.querySelectorAll('img');
      const options = {
        rootMargin: '0px 0px 100px 0px', // Adjust as needed
        threshold: 0.1
      };
      const observer = new IntersectionObserver(function(entries, observer) {
        entries.forEach(entry => {
          if (entry.isIntersecting) {
            const img = entry.target;
            const src = img.getAttribute('data-src');
            img.setAttribute('src', src);
            observer.unobserve(img);
          }
        });
      }, options);

      lazyImages.forEach(img => {
        observer.observe(img);
      });
    });
  </script>
</body>
</html>
