# Demo-Website
# A simple landing page using HTML,CSS,JavaScript
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css" integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">

    <title>Car Trader</title>
  </head>
  <style>
    nav
    {
        background-color: red;
    }
    a img
    {
        height: 100px;
        width: 100px;
    }
    .divScroll {
    overflow:scroll;
    height:auto;
    width:auto;
    }
    

  </style>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark">
  <a class="navbar-brand" href="#"><img src="Imageq/car trader.png" alt="Logo"/></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Current Available Cars</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Sell Your Car</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
<div>
    <h1 align="center">Car Trader</h1>
    <div id="carouselExampleCaptions" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleCaptions" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
          <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="Imageq/us.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Buy Second Hand Cars</h5>
              <p>Quality is assured here and the best price is brought to you through us.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="Imageq/sell.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Hassle Free Sale</h5>
              <p>Sell your cars easily for the best possible price.</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="Imageq/Beaut.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block">
              <h5>Quality Is Assured</h5>
              <p>Leave it to our experts and we will bring you the best cars Available.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-target="#carouselExampleCaptions" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-target="#carouselExampleCaptions" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </button>
      </div>
</div>
<div class="divScroll">
    <h1>Current Selection of Cars</h1>
    <div class="card-deck">
        <div class="card">
          <img src="Imageq/swift.jpg" class="card-img-top" alt="..." style="height: 400px; width: 275px;">
          <div class="card-body">
            <h5 class="card-title">Maruti Suzuki Swift</h5>
            <p class="card-text">2016<br>35,000 Km<br>3,50,000 ₹</p>
          </div>
          <div class="card-footer">
            <small class="text-muted"><button class="btn btn-lg btn-dark">Place Order</button></small>
          </div>
        </div>
        <div class="card">
          <img src="Imageq/honda.jpg" class="card-img-top" alt="..." style="height: 400px; width: 275px;">
          <div class="card-body">
            <h5 class="card-title">Honda City</h5>
            <p class="card-text">2014<br>50,000 Km<br>5,00,000 ₹</p>
          </div>
          <div class="card-footer">
            <small class="text-muted"><button class="btn btn-lg btn-dark">Place Order</button></small>
          </div>
        </div>
        <div class="card">
          <img src="Imageq/verna.jpg" class="card-img-top" alt="..." style="height: 400px; width: 275px;">
          <div class="card-body">
            <h5 class="card-title">Hyundai Verna</h5>
            <p class="card-text">2016<br>75,000 Km<br>4,00,000 ₹</p>
          </div>
          <div class="card-footer">
            <small class="text-muted"><button class="btn btn-lg btn-dark">Place Order</button></small>
          </div>
        </div>
        <div class="card">
            <img src="Imageq/ciaz.jpg" class="card-img-top" alt="..." style="height: 400px; width: 275px;">
            <div class="card-body">
              <h5 class="card-title">Nexa Ciaz</h5>
              <p class="card-text">2018<br>20,000 Km<br>6,75,000 ₹</p>
            </div>
            <div class="card-footer">
              <small class="text-muted"><button class="btn btn-lg btn-dark">Place Order</button></small>
            </div>
          </div>
          <div class="card">
            <img src="Imageq/alto.jpg" class="card-img-top" alt="..." style="height: 400px; width: 275px;">
            <div class="card-body">
              <h5 class="card-title">Alto</h5>
              <p class="card-text">2015<br>35,000 Km<br>75,000 ₹</p>
            </div>
            <div class="card-footer">
              <small class="text-muted"><button class="btn btn-lg btn-dark">Place Order</button></small>
            </div>
          </div>
      </div>
</div>
<div>
    <h1 align="center">Sell Your Car</h1>
    <form>
        <table border="5px solid" style="margin-left: 575px;">
            <tr><th align="center" colspan="2">Information</th></tr>
            <tr><th>Car Model</th><th><input type="text"></th></tr>
            <tr><th>Year Brought</th><th><input type="text"></th></tr>
            <tr><th>Registeration Number</th><th><input type="text"></th></tr>
            <tr><th>Distance Travelled</th><th><input type="text"></th></tr>
            <tr><th>Aadhar Number</th><th><input type="text"></th></tr>
            <tr><th>Mobile Number</th><th><input type="text"></th></tr>
            <tr><th>Image</th><th><input type="file"></th></tr>
            <tr><th colspan="2"><input type="submit"></th></tr>
        </table>
    </form>
</div>
<div>
    <h1>About</h1>
    <p>**No need to worry about your vehicles,our Technicians are on it.</p>
    <p>**During the sale we will contact you within 5-6 working days.</p>
</div>
<footer style="bottom: 0px; position: relative; background-color: black; color: white; height: 200px;">
    <h1>Contact Us</h1>
    <p>Tollfree Number - 0731-4319908</p>
    <p>43012 Powai<br>Mumbai</p>
    <p> &copy; All Rights Reserved | Car Trader</p>
</footer>


    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct" crossorigin="anonymous"></script>
  </body>
</html>
