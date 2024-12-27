# Project Responsive Web Design using Bootstrap
# Date:7-12-2024
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
project.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Home - BATA COMPANY</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">BATA COMPANY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="web.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Register</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Welcome to BATA COMPANY</h1>
        <p>Welcome BATA COMPANY,we have multinational foot wears,apparel and fashion accessesories manufacture and retailer of moravian
         origin,headquarters in lausanne,switzerland. the co operation is one of the worlds leading shoe makers.</p>
        <p>we have online delivery or you can choose offline delivery..</p>
        <p>we will be having lots of designs we have footwears,shoes,cutshoes,so many models. </p>
        <p>Thank you for choosing bata company for your daily needs. We look forward to serving you and the best.</p>
      </div>
      <div class="col-md-4">
       
      </div>
    </div>
  </div>
  <body background="bg.jpeg" style="background-repeat: no-repeat; background-size: cover;">


  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-4 mt-3">
    <p>&copy; 2024 BATA COMPANY. All rights reserved. BY GANGA DEVI</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About BATA COMPANY</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">BATA COMPANY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1>ABOUT BATA COMPANY</h1>
        <div id="vision">
          <h2>Vision</h2>
          <p>To be the leading online platform for accessible, affordable, and reliable  empowering individuals to take control of their well-being from the comfort of shoes.</p>
        </div>
        <div id="mission">
          <h2>Mission</h2>
          <p>Our mission at bata company is a family owned business,making it possible to provide customers around the world with the best :
.`             shoes at the best prices backed by unparalled service for over 125 years we live the bata way by improving the life
                of each community in which we operate.</p>
        </div>
        <div id="values">
          <h2>Values</h2>
          <ul>
            <li>Be bold: WE are pioneers .we value individuals with the courage to change and to be prepared to fail sometimes.</li>
                <li>count on me:we lead by example and follow when called we value those who take accountability for their successes and failures.we take responsibility.</li>
                    <li> Excellence: We are committed to excellence in everything we do, from the quality of our shoes to the efficiency of our services, aiming for continuous improvement and innovation.</li>
                        <li> improving lives:every one is treated and given equal oppurtuniyies for employyment regrdless .</li>
                            <li>Collaboration: We value collaboration and teamwork, working closely with professionals, industry partners, and our community to achieve common goals and drive positive change.</li>
                                <li>Customer-Centricity: We prioritize the needs and satisfaction of our customers above all else, striving to exceed their expectations and deliver exceptional value at </
                              
                                <li>Responsibility: We recognize our responsibility to , the t, and future generations, and are committed to conducting our business in a sustainable, socially responsible manner
                            </li>
            
                            </ul>
                          </div>
                          <!-- Add more subheadings as needed -->
                        </div>
                      </div>
                    </div>
                    <body background="bg.jpeg" style="background-repeat: no-repeat; background-size: cover;"></body>
                    <!-- Footer -->
                    <footer class="bg-dark text-white text-center py-4 mt-3">
                      <p>&copy; 2024 BATA COMPANY. All rights reserved.  BY GANGA DEVI</p>
                    </footer>
                  
                    <!-- Bootstrap JS -->
                    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
                    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
                    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
                  </body>
                  </html>
                  ```
                  
                  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us -BATA COMPANY</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">BATA COMPANY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html">Products</a>
        </li>
        <li class="nav-item active">
            <a class="nav-link" href="contact.html">Contact <span class="sr-only">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1>Contact Us</h1>
        <p>For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name">Your Name</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email">Your Email</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea class="form-control" id="message" rows=3" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4"></h2>
        <address>
          <strong>Address:</strong><br>
        <h2>BATA COMPANY
          23-422/tilak road kadapa<br>
          India, 510501<br><br>
          <strong>Email:</strong><br>
          Batacompany@.com<br><br>
          <strong>Phone:</strong><br>
          9876543210
        </address>
    </div>
  </div>
</div>
<body background="back.png" style="background-repeat: no-repeat; background-size: cover;">


<!-- Footer -->
<footer class="bg-dark text-white text-center py-4 mt-2">
  <p>&copy; 2024 BATA COMPANY. All rights reserved.BY GANGA DEVI</p>
</footer>

<!-- Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

```

   <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products - BATA COMPANY</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#">BATA COMPANY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html">Home</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="about.html">About</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
              Products
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item" href="#">Shoes</a>
              <a class="dropdown-item" href="#">cut shoes</a>
              <a class="dropdown-item" href="#">heels</a>
              <a class="dropdown-item" href="#">crocks</a>
            </div>
          </li>
          <li class="nav-item active">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Login</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Register</a>
          </li>
        </ul>
      </div>
    </nav>
  
    <!-- Page Content -->
    <div class="container mt-3">
      <div class="row">
        <div class="col-md-12">
          <h1>Our Product categories</h1>
          <div class="card-deck">
            <div class="card">
              <img src="https://baccabucci.com/cdn/shop/products/MG_5242.jpg?v=1633514122" class="card-img-top" alt="Product 1" width="200" height="200">
              <div class="card-body">
                <h5 class="card-title">Shoes</h5>
                <p class="card-text">These shoes is so comfortable use .the colour will be so good it can be used by both men and women.</p>
                <a href="#" class="btn btn-primary">Buy Now</a>
              </div>
            </div>
            <div class="card">
              <img src="https://shoethatfitsyou.in/cdn/shop/products/Black_stiletto.jpg?v=1571967681" class="card-img-top" alt="Product 2" width="200" height="200">
              <div class="card-body">
                <h5 class="card-title">High heels</h5>
                <p class="card-text">High heels are used for girls it will be very good for girls. they can walk easily.</p>
                <a href="#" class="btn btn-primary">Buy Now</a>
              </div>
            </div>
            <div class="card">
              <img src="https://images-cdn.ubuy.co.in/66b285262ff9d276ac70a574-musshoe-flat-shoes-women-comfortable.jpg" class="card-img-top" alt="Product 3" width="200" height="200">
              <div class="card-body">
                <h5 class="card-title">flats shoes</h5>
                <p class="card-text">In this we have so many colours it is used for only women nit for men.</p>
                <a href="#" class="btn btn-primary">Buy Now</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  
    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-4 mt-5">
      <p>&copy; 2024 BATA COMPANY. All rights reserved. By GANGA DEVI</p>
    </footer>
    <body background="bg.jpeg" style="background-repeat: no-repeat; background-size: cover;">
  
  
<!-- Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>


```
  
# OUTPUT:
![Screenshot 2024-12-26 140421](https://github.com/user-attachments/assets/623ee586-27b4-452c-ad55-8e04f55daa85)
![Screenshot 2024-12-26 144619](https://github.com/user-attachments/assets/c172216d-bce0-4c8d-b96d-d08951922e5a)
![Screenshot 2024-12-26 143359](https://github.com/user-attachments/assets/54faed7c-a127-41e9-b0ad-1b6f8484d790)
![Screenshot 2024-12-26 143929](https://github.com/user-attachments/assets/f7bcae7a-881d-4ba2-b52b-b929f3f8019f)




# RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
