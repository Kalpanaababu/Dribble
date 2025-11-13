# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Dribbble Clone</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <style>
    body {
      background-color: #f8f9fa;
    }

    .navbar-dark {
      background-color: #333;
    }

    .card-img-top {
      height: 150px;
      object-fit: cover;
    }

    .card {
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: scale(1.03); /* Slight elongation (~5px) in all directions */
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
    }

    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem 0;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Dribbble Clone</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Shots</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Designers</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Teams</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Jobs</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Sign In</a></li>
          <li class="nav-item"><a class="btn btn-primary" href="#">Sign Up</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Content Section -->
  <div class="container mt-5">
    <h2 class="mb-4">Popular Shots</h2>
    <div class="row g-4">
      <!-- Cards -->
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215146.png" class="card-img-top" alt="Dashboard UI">
          <div class="card-body">
            <h5 class="card-title">Data Analytics Certificate</h5>
            <p class="card-text">by Ramesh V</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215158.png" class="card-img-top" alt="Profile Card Design">
          <div class="card-body">
            <h5 class="card-title">Course Profile UI</h5>
            <p class="card-text">by Sneha K</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215228.png" class="card-img-top" alt="Ecommerce Mockup">
          <div class="card-body">
            <h5 class="card-title">Cybersecurity Dashboard</h5>
            <p class="card-text">by Arjun S</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 214646.png" class="card-img-top" alt="Music App">
          <div class="card-body">
            <h5 class="card-title">Corporate Meeting Interface</h5>
            <p class="card-text">by Kavya R</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215240.png" class="card-img-top" alt="Analytics Dashboard">
          <div class="card-body">
            <h5 class="card-title">Hugging Face AI Showcase</h5>
            <p class="card-text">by Deepak T</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215250.png" class="card-img-top" alt="Dark Mode UI">
          <div class="card-body">
            <h5 class="card-title">Llama 3.2 Launch UI</h5>
            <p class="card-text">by Anjali N</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215305.png" class="card-img-top" alt="News Portal">
          <div class="card-body">
            <h5 class="card-title">Excel Dashboard Mockup</h5>
            <p class="card-text">by Rohit M</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215322.png" class="card-img-top" alt="Travel App">
          <div class="card-body">
            <h5 class="card-title">Spreadsheet Analysis Tool</h5>
            <p class="card-text">by Priya S</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215349.png" class="card-img-top" alt="Fitness Tracker UI">
          <div class="card-body">
            <h5 class="card-title"	Python App Landing Page</h5>
            <p class="card-text">by Rahul V</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215403.png" class="card-img-top" alt="Education Portal">
          <div class="card-body">
            <h5 class="card-title">Learning Platform Logo</h5>
            <p class="card-text">by Meena P</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215417.png" class="card-img-top" alt="Blog Layout">
          <div class="card-body">
            <h5 class="card-title">AI Brainstorm Interface</h5>
            <p class="card-text">by Faizal A</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 col-lg-3">
        <div class="card">
          <img src="Screenshot 2025-05-23 215556.png" class="card-img-top" alt="Crypto Wallet">
          <div class="card-body">
            <h5 class="card-title">AI Finance and Crypto Wallet</h5>
            <p class="card-text">by Nithya G</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    KALPANAA BABU TM
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

## OUTPUT:

<img width="1900" height="955" alt="image" src="https://github.com/user-attachments/assets/89d530b2-c578-4be9-8d4d-4e675f323f15" />



## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
