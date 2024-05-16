# Project Responsive Web Design using Bootstrap
## Date:15.05.2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.

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

## PROGRAM:
home.html
```


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HOME</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #00eaff; 
      color: rgb(0, 217, 255);
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body style= "background-image: url('pharm bg.jpg!sw800')" align="center">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-info">
    <a class="navbar-brand" href="#">NS PHARMACY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="home.html">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html">Contact</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#">Login</a>
        </li>
        
      </ul>
    </div>
  </nav>

  <!-- Page Content -->
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1> <b><font face="Harlow Solid Italic" size="6" color= "bronze">WELCOME TO NS PHARMACY</font></h1>
            <br></h1>
        <p>Welcome to our pharmacy! We're delighted to be your trusted healthcare partner, committed to providing you with top-notch pharmaceutical services and expert advice. Whether you're seeking medication, wellness products, or professional guidance, our team is here to support you every step of the way. At our pharmacy, your health and well-being are our utmost priorities. Explore our wide range of products and services, and let us help you live your healthiest life possible. Thank you for choosing us as your pharmacy of choice.</p>
        
      </div>
      <div class="col-md-5">
        
      </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-info text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-NITHISHKUMAR S</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
    position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #000000; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body style= "background-image: url('2nd page.webp')" align="center">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-info">
    <a class="navbar-brand" href="#">NS PHARMACY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            About
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision">Vision</a>
            <a class="dropdown-item" href="#mission">Mission</a>
            <a class="dropdown-item" href="#values">Values</a>
            <!-- Add more subheadings as needed -->
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
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
        <h3> <b><font face="Harlow Solid Italic" size="6" color= "bronze">ABOUT NS PHARMACY</font></h1>
            <br></h3>
        <div id="Expert Care">
          <h4>Expert Care: </h4>
          <p>Our team of pharmacists and healthcare professionals are highly trained and dedicated to providing personalized care. Whether you have questions about medication, managing a chronic condition, or leading a healthier lifestyle, we're here to help.</p>
        </div>
        <div id="Comprehensive Services">
          <h4>Comprehensive Services:</h4>
          <p>From filling prescriptions accurately and efficiently to offering immunizations, medication therapy management, and health screenings, we offer a wide range of services to meet your healthcare needs.</p>
        </div>
        <div id="Quality Products">
          <h4>Quality Products:</h4>
          <p>We stock a carefully curated selection of high-quality medications, over-the-counter remedies, vitamins, supplements, and wellness products. You can trust that the products you find on our shelves meet stringent quality standards.</p>
        </div>
        <div id="Technology Integration">
            <h4>Technology Integration:</h4>
            <p>We leverage cutting-edge technology to enhance our services and improve patient outcomes. From electronic prescribing to medication synchronization programs, we're constantly innovating to better serve you.</p>
          </div>
        <!-- Add more subheadings as needed -->
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-info text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-NITHISHKUMAR S</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
products.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Products</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("pr.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #000000; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body style= "background-image: url('bg3.jpg')" align="center">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-info">
    <a class="navbar-brand" href="#">NS PHARMACY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="products.html">Products <span class="sr-only">(current)</span></a>
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
      <div class="col-md-12">
        <h3> <b><font face="Harlow Solid Italic" size="6" color= "navy blue">OUR PRODUCTS</font>
          <br></h3>
          <h3> <b><font face="Harlow Solid Italic" size="6" color= "warning">Vitamins and Supplements:</font></h3>
            <br></h3>
        <div class="card-deck">
          <div class="card">
            <img src="image1.png" class="card-img-top" alt="Product 1">
            <div class="card-body">
              <h5 class="card-title">Centrum Multivitamins :</h5>
              <h6 class="card-text">Centrum Multivitamins provide essential nutrients to support overall health and fill nutritional gaps in the diet.</h6>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="image2.png" class="card-img-top" alt="Product 2">
            <div class="card-body">
              <h5 class="card-title">Fish oil supplements :</h5>
              <h6 class="card-text">Fish oil supplements are commonly taken to support heart health, reduce inflammation, and promote overall wellness due to their high omega-3 fatty acid content.</h6>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="image3.jpg" class="card-img-top" alt="Product 3">
            <div class="card-body">
              <h5 class="card-title">Calcium supplements :</h5>
              <h6 class="card-text">Calcium supplements are often used to support bone health, prevent osteoporosis, and maintain strong teeth.</h6>
              <a href="#" class="btn btn-primary">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-info text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-NITHISHKUMAR S</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact</title>
  <!-- Bootstrap CSS -->
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  <!-- Custom CSS -->
  <style>
    body {
      background-image: url("pr.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      font-size: 19px;
    }
    footer{
      position: fixed;
      left: 0;
      bottom: 0;
      width: 100%;
      background-color: #ffffff; 
      color: white;
      text-align: center;
      padding: 10px 0; 
    }
  </style>
</head>
<body style= "background-image: url('page 3.jpg')" align="center">

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-info">
    <a class="navbar-brand" href="#">NS PHARMACY</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="home.html">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="products.html">Products</a>
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
        <h3> <b><font face="Harlow Solid Italic" size="6" color= "white">CONTACT US</font>
            <br></h3>
            <h5> <b><font face="Harlow Solid Italic" size="5" color= "white">For any queries please fill the form given below.</font>
                <br></h5>
        
        <form>
          <div class="form-group">
            <h3> <b><font face="Harlow Solid Italic" size="3" color= "white">YOUR NAME:</font>
                <br></h3>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <h3> <b><font face="Harlow Solid Italic" size="3" color= "white">YOUR EMAIL :</font>
                <br></h3>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <h3> <b><font face="Harlow Solid Italic" size="3" color= "white">MESSAGE :</font>
                <br></h3>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Submit</button>
        </form>
      </div>
      <div class="col-md-4">
        <h1> <b><font face="Harlow Solid Italic" size="6" color= "white">NS PHARMACY</font>
            <br></h1>
        <address><font face="Harlow Solid Italic" size="4" color= "white">
          <strong>Address:</strong><br>
          chennai,tambaram,nshospital opposite<br>
          <br>
          <strong>Email:</strong><br>
          nspharm@gmail.com<br><br>
          <strong>Phone:</strong>
          <br>
          +919876543210</br><font>
        </address>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer class="bg-info text-white text-center py-4 mt-5">
    <p>&copy; 2024 PharmaCompany-NITHISHKUMAR S</p>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (69).png>)
![alt text](<Screenshot (70).png>)
![alt text](<Screenshot (71).png>)
![alt text](<Screenshot (72).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
