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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
   
    <style>
        body {
            background-color: #a8acb1;
        }
        .navbar {
            margin-bottom: 30px;
           
        }
        .card img {
            object-fit: cover;
            height: 150px;
            
        }
        .card {
            border: none;
            border-radius: 10px;
            
        }
        .card-footer {
            background-color: transparent;
        }
        .footer {
           color: rgb(255, 255, 255);
           padding-left:40% ;
           padding-top:20px ;
           padding-bottom:20px ;
           background-color: rgb(0, 0, 0);
           margin-top: 90px;
           
        } 
        .navbar-brand{
            color: white;
        }
    </style>
</head>
<body>
 
    <nav class="navbar navbar-light bg-black shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold" href="#">Dribbble Clone</a>
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-primary" type="submit">Search</button>
            </form>
        </div>
    </nav>

 
    <div class="container text-center mb-5">
        <h1>What are you working on?</h1>
        <p class="text-muted">Dribbble is show and tell for designers.</p>
        <button class="btn btn-primary">Sign up</button>
    </div>


    <div class="container">
        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-4">
         
            <div class="col">
                <div class="card shadow-sm">
                    <img src="1img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Mr.Cashly App</span>
                        <span class="text-muted">4,044 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="2img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Holiday Gift Delivery</span>
                        <span class="text-muted">2,404 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="3img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Banking Mobile App</span>
                        <span class="text-muted">8,909 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="4img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Argus 3D Mobile</span>
                        <span class="text-muted">4,567 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="5img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Finance App Design</span>
                        <span class="text-muted">3,908 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="6img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Protectimus Mobile</span>
                        <span class="text-muted">2,445 views</span>
                    </div>
                </div>
            </div>
            <div class="col">
                <div class="card shadow-sm">
                    <img src="7img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Cryptalize</span>
                        <span class="text-muted">7,078 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="8img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Ray-Ban</span>
                        <span class="text-muted">5,860 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="9img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Marketing And Analytics</span>
                        <span class="text-muted">8,090 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="10img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Try Angle Dashboard</span>
                        <span class="text-muted">5,908 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="11img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Logofolio</span>
                        <span class="text-muted">3,096 views</span>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card shadow-sm">
                    <img src="12img.webp" class="card-img-top" alt="Sample Design">
                    <div class="card-footer d-flex justify-content-between align-items-center">
                        <span>Web3Developer</span>
                        <span class="text-muted">2,435 views</span>
                    </div>
                </div>
            </div>

        </div>
    </div>
    <footer class="footer">Designed and Developed by Mohamed Rafeek</footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
