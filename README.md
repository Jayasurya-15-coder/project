# Project Responsive Web Design using Bootstrap
# Date:
# AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.

# DESIGN STEPS:
## Step 1:
Clone the repository from GitHub.

## Step 2:
Create Django Admin project.

## Step 3:
Create a New App under the Django Admin project.

## Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

## Step 5:
Create a HTML file and include the needed Bootstrap components.

## Step 6:
Publish the website in the LocalHost.

# PROGRAM :

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
    }
    .hero {
      background-color: #f8f9fa;
      padding: 80px 0;
      text-align: center;
    }
    .features {
      padding: 60px 0;
    }
    .footer {
      background-color: #212529;
      color: white;
      padding: 30px 0;
    }
    .nav-link {
      color: #000 !important;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg bg-white shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">DribbbleClone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item"><a class="nav-link" href="#">Inspiration</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Find Work</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Learn Design</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Go Pro</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Login</a></li>
          <li class="nav-item">
            <a class="btn btn-primary ms-2" href="#">Sign Up</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1 class="display-5 fw-bold">Discover the world’s top designers & creatives</h1>
      <p class="lead mt-3 mb-4">Dribbble is the leading destination to find & showcase creative work.</p>
      <a href="#" class="btn btn-dark btn-lg">Get Started</a>
    </div>
  </section>

  <!-- Feature Sections -->
  <section class="features text-center">
    <div class="container">
      <div class="row g-4">
        <div class="col-md-4">
          <h4>Browse Shots</h4>
          <p>Explore thousands of design shots from talented designers.</p>
        </div>
        <div class="col-md-4">
          <h4>Hire Designers</h4>
          <p>Connect with the best freelance and full-time creatives.</p>
        </div>
        <div class="col-md-4">
          <h4>Showcase Work</h4>
          <p>Share your portfolio and get discovered by clients and peers.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="footer text-center">
    <div class="container">
      <p class="mb-1">© 2025 Dribbble Clone. All rights reserved.</p>
      <small>Inspired by <a href="https://dribbble.com/" class="text-white text-decoration-underline">Dribbble</a></small>
    </div>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```
# OUTPUT:

![Screenshot 2025-05-18 153823](https://github.com/user-attachments/assets/ab4d1100-5e43-4931-99a6-3e532104ea84)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
