# Project Responsive Web Design using Bootstrap
# Date:07/12/2024.
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

~~~

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Dribble.io</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  </head>
  <body>
    <nav class="navbar navbar-expand-sm navbar-dark bg-dark">
      <div class="container">
        <a href="#Logo" class="navbar-brand mb-0 h1">
          <img src="dlogo.png" width="120" height="30" alt="Logo">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a href="#" class="nav-link active" aria-current="page">Shots</a>
            </li>
            <li class="nav-item">
              <a href="sign_in.html" class="nav-link">Designer</a>
            </li>
            <li class="nav-item">
              <a href="sign_in.html" class="nav-link">Sign up</a>
            </li>
            <li class="nav-item">
              <a href="sign_in.html" class="nav-link">Sign in</a>
            </li>
          </ul>
          <div class="ms-auto">
            <form class="d-flex" role="search">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-primary" type="submit">Search</button>
            </form>
          </div>
        </div>
      </div>
    </nav>

    <section class="text-center py-4 bg-dark text-white">
      <div class="container">
        <h2 class="lead fw-bold mb-4">Discover the world's top Designer.</h2>
        <div class="d-inline-flex gap-2">
          <a href="#" class="btn btn-primary">Learn More</a>
          <a href="sign_in.html" class="btn btn-outline-danger">Sign Up</a>
        </div>
      </div>
    </section>

    <div class="container py-4">
      <div class="row justify-content-center g-4">
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="d1.jpeg" class="card-img-top" alt="Joshua's design">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Joshua's work</h5>
              <a href="creating web.html" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="d2.jpeg" class="card-img-top" alt="Anderson's design">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Anderson's Work</h5>
              <a href="creating web.html" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="d3.jpeg" class="card-img-top" alt="Style Designer's work">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Style Designer</h5>
              <a href="creating web.html" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="d4.jpeg" class="card-img-top" alt="Mathew's design">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Mathew's work</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="d6.jpeg" class="card-img-top" alt="Jslash's design">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Jslash's work</h5>
              <a href="#" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card shadow rounded-3">
            <img src="d7.png" class="card-img-top" alt="Ulquira's design">
            <div class="card-body text-center">
              <h5 class="card-title fw-bold">Ulquira's work</h5>
              <a href="creating web.html" class="btn btn-primary btn-sm">View</a>
            </div>
          </div>
        </div>
      </div>
    </div>

    <footer class="bg-dark text-white text-center py-3">
      <h2 class="h6 m-0">Designed and developed by Santhosh .V (24901020)</h2>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
  </body>
</html>

~~~
# OUTPUT:
![Screenshot 2024-12-25 174932](https://github.com/user-attachments/assets/cdf2c317-7713-4277-b463-7caf29697e8b)

![Screenshot 2024-12-25 174131](https://github.com/user-attachments/assets/0d09264d-7f86-4cfe-98d6-0433522f3c71)


# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
