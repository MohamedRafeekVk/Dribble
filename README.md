# Project Responsive Web Design using Bootstrap
## Date:25/12/2024

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

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Webpage</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav class="navbar navbar-expand-lg">
        <a class="navbar-brand" href="#">Dribbble Clone</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#about">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#gallery">Gallery</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>
    <section id="about" class="content-section bg-light">
        <div class="container text-center">
            <h2>What are you working on?</h2>
            <p class="lead">Dribbble is show and tell for Designers</p>
        </div>
    </section>
    <section id="gallery" class="content-section">
        <div class="container">
            <h2 class="text-center mb-4">BMW M3 COMPETITION</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <img src="bmw1.jpg" class="img-fluid gallery-img" alt="Gallery 1">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="bmw2.jpg" class="img-fluid gallery-img" alt="Gallery 2">
                </div>
                <div class="col-md-4 mb-4">
                    <img src="bmw3.jpg" class="img-fluid gallery-img" alt="Gallery 3">
                </div>
            </div>
            <div class="text-center mt-4">
                <a href="#" class="btn btn-primary">View More</a>
            </div>
        </div>
    </section>
    <section id="contact" class="content-section bg-light">
        <div class="container text-center">
            <h2>Contact Us</h2>
            <p>Feel free to reach out for inquiries or collaborations!</p>
            <a href="mailto:info@example.com" class="btn btn-outline-dark">Email Us</a>
        </div>
    </section>
    <footer class="footer">
        <div class="container">
            <p>Designed and Developed by Mohamed Rafeek</p>
        </div>
    </footer>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.4.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

styles.css

body {
    font-family: Arial, sans-serif;
}
.navbar {
    background-color: #333;
}
.navbar-brand, .nav-link {
    color: white !important;
}
.content-section {
    padding: 4rem 0;
}
.footer {
    background-color: #333;
    color: white;
    padding: 1rem 0;
    text-align: center;
}
.gallery-img {
    max-height: 430px;
    object-fit: cover;
    border-radius: 50px;
}
.about {
    max-height: 430px;
    object-fit: cover;
    border-radius: 50px;
}

```

## OUTPUT:
![alt text](<Screenshot (40).png>)
![alt text](<Screenshot (41).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
