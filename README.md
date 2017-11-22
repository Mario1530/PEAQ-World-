# PEAQ-World-
<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css" type="text/css">
  <link rel="stylesheet" href="PEAQSYS.css" type="text/css">
  <title>Peaqsys.com</title>
  <meta name="keywords" content="PEAQ Systems"> 
</head>

<style> 
// Semantic color scheme
$theme-colors: (
  primary: #007bff,
  secondary: #004EA3,
  success: #28a745,
  info: #00fbff,
  warning: #ffc107,
  danger: #dc3545,
  light: #f8f9fa,
  dark: #343a40
);

// Options
//
// Quickly modify global styling by enabling or disabling optional features.
 
$enable-rounded:            true !default;
$enable-shadows:            false;
$enable-gradients:          false;
$enable-transitions:        true !default;
$enable-hover-media-query:  false !default;
$enable-grid-classes:       true !default;
$enable-print-styles:       true !default;

// Variables
//
// Theme settings.

$body-bg: white;
$body-color: #292b2c;
$body-color-inverse: invert($body-color) !default;
$link-color: #007bff;


$font-family-base: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
$headings-font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif !default;

$font-size-base: 1rem; // Assumes the browser default, typically `16px`
$font-size-h1: 2.5 * $font-size-base;
$font-size-h2: 2 * $font-size-base;
$font-size-h3: 1.75 * $font-size-base;
$font-size-h4: 1.5 * $font-size-base;
$font-size-h5: 1.25 * $font-size-base;
$font-size-h6: $font-size-base;

$display1-size: 6 * $font-size-base;
$display2-size: 5.5 * $font-size-base;
$display3-size: 4.5 * $font-size-base;
$display4-size: 3.5 * $font-size-base;

$border-radius: .25rem;


@import 'bootstrap-4.0.0-beta.1';


body > * {
  background-size: cover; 
}

.opaque-overlay {
  overflow: hidden;
  position: relative; 
  > *:first-child:before {
    content: '';
    width: 100%;
    height: 100%;
    display: block;
    position: absolute;
    left: 0px;
    top: 0px; 
    pointer-events:none;
    background: rgba(map-get($theme-colors, 'dark'), 0.25);
  }
}


.gradient-overlay {
  overflow: hidden;
  position: relative; 
  > *:first-child:before {
    content: '';
    width: 100%;
    height: 100%;
    display: block;
    position: absolute;
    left: 0px;
    top: 0px; 
    pointer-events:none;
    background: linear-gradient(to bottom right, map-get($theme-colors, 'primary') 20%, transparent 80%);
    font-size: 50px;
  }
}



.style {
 Margin-bottom: 50px; 
 overflow: scroll;  
}
</style>

<body class="">
  <nav class="navbar navbar-expand-md bg-secondary navbar-dark">
    <div class="container">
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"> <span class="navbar-toggler-icon"></span> </button>
      <a class="navbar-brand p-0 ml-auto text-muted" href="#">PEAQ</a>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Company</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-white" href="#">Contact us</a>
          </li>
        </ul>
        <form class="form-inline m-0">
          <input class="form-control mr-2" type="text" placeholder="Search">
          <button class="btn btn-primary" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <div class="py-5 gradient-overlay h-75" style="background-image: url(&quot;https://pingendo.github.io/templates/sections/assets/cover_event.jpg&quot;);">
    <div class="container py-5">
      <div class="row">
        <div class="col-md-12 text-white align-self-center">
          <h1 style="font-size: 70px" class="display-3 mb-4 text-center">PEAQ SYSTEMS&nbsp;</h1>
          <p style="font-size: 30px" class="lead mb-5 text-center text-capitalize w-100 text-secondary">Peaq Systems provides business process and automation products and services supporting the medical equipment industry&nbsp;</p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-3">
          <a href="#" class="btn btn-lg btn-primary mx-5">About Us</a>
        </div>
        <div class="col-md-3">
          <a href="#" class="btn btn-secondary mx-4 btn-lg">Learn More&nbsp;</a>
        </div>
        <div class="col-md-3"></div>
      </div>
    </div>
  </div>
  <div class="text-center p-0 m-5">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <h1 class="pb-3 text-secondary p-4">Business Solutions For Growth &nbsp;</h1>
        </div>
      </div>
      <div class="row">
        <div class="text-right col-md-6">
          <div class="row my-5">
            <div class="col-2 order-lg-2 col-2 text-center"><i class="fa fa-3x d-block fa-handshake-o"></i></div>
            <div class="col-10 text-lg-right text-left order-lg-1">
              <h4 class="text-primary">Sales&nbsp;</h4>
              <p>Instant access to Sales History, Open Orders, Back Orders, Pricing, and Contracts</p>
            </div>
          </div>
          <div class="row my-5">
            <div class="col-2 order-lg-2 col-2 text-center"><i class="d-block fa fa-credit-card-alt fa-3x"></i></div>
            <div class="col-10 text-lg-right text-left order-lg-1">
              <h4 class="text-primary">Accounts Payable&nbsp;</h4>
              <p>Internet-based Purchasing Functionality, with Displayed Vendor Payments and Dates&nbsp;</p>
            </div>
          </div>
          <div class="row my-5">
            <div class="col-2 order-lg-2 col-2 text-center"><i class="d-block fa  fa-3x fa-cloud-download"></i></div>
            <div class="col-10 text-lg-right text-left order-lg-1">
              <h4 class="text-primary">Cloud Based&nbsp;</h4>
              <p>Global Access with 24/7 active support.
                <br>The support you need, with.</p>
            </div>
          </div>
        </div>
        <div class="text-left col-md-6">
          <div class="row my-5">
            <div class="col-2 text-center"><i class="d-block fa fa-3x fa-list-alt"></i></div>
            <div class="col-10">
              <h4 class="text-primary">Inventory&nbsp;</h4>
              <p>inventory management with Physical Inventory, Shipping, and Receiving details and real time Core Tracking&nbsp;</p>
            </div>
          </div>
          <div class="row my-5">
            <div class="col-2 text-center"><i class="d-block mx-auto fa  fa-credit-card fa-3x"></i></div>
            <div class="col-10">
              <h4 class="text-primary">Accounts Receivable&nbsp;</h4>
              <p>A/R Data made available by design for immediate access and Customer Designation&nbsp;</p>
            </div>
          </div>
          <div class="row my-5">
            <div class="col-2 text-center"><i class="d-block fa  fa-3x fa-arrows-alt"></i></div>
            <div class="col-10">
              <h4 class="text-primary">Seamless Integration&nbsp;</h4>
              <p>Integrate your CRM, Fiancials, and Back office seamlessly with our interface.&nbsp;</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="py-5 text-white h-50" style="background-image: url(&quot;PEAQ PIC 3.jpeg&quot;);">
    <div class="container">
      <div class="row style">
        <div class="col-md-4">
          <p style="font-size: 40px" class="lead"><i contenteditable="true" class="text-secondary">PEAQ with Control and Simplicity&nbsp;</i>
            <br> </p>
          <p class="lead m-0 text-dark text-left">PEAQ Provides Value Through Transforming Critical Processes By Simplifying And Eliminating Inefficiencies While Convieniently offering the Value of both Speed and Automation&nbsp;</p>
          <div class="row">
            <div class="col-md-4">
              <p style="font-size: 40px" class="lead">
                <br> </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="py-5">
    <div class="container">
      <div class="row">
        <div class="col-md-12 text-center">
          <h1 class="pb-4 text-center text-capitalize text-secondary opaque-overlay">PEAQ Mobility&nbsp;</h1>
        </div>
      </div>
      <div class="row">
        <div class="align-self-center text-md-right text-center col-md-4">
          <h3 class="text-primary">Customized Settings&nbsp;</h3>
          <p class="mb-5 text-capitalize">Choose settings and features depending on the criteria you value the most</p>
          <h3 class="text-primary">Scheduling&nbsp;</h3>
          <p class="mb-5 text-capitalize">Effeciently schedule orders that can be tracked and viewed in real time</p>
          <h3 class="text-primary">Connectivity&nbsp;</h3>
          <p class="text-capitalize">In-app chat panel Active&nbsp;24/7&nbsp;
            <br>support you need, right when you need It</p>
        </div>
        <div class="my-3 col-md-4">
          <img class="img-fluid d-block ml-1 mx-auto" src="PEAQ Tablet 2.png"> </div>
        <div class="align-self-center text-md-left text-center col-md-4">
          <h3 class="text-primary">Tracking&nbsp;</h3>
          <p class="mb-5" contenteditable="true">Track Core Inventory and Sales With rovided work order system on both business and client end&nbsp;</p>
          <h3 class="text-primary">Invoicing&nbsp;</h3>
          <p class="mb-5 text-capitalize">generate daily, weekly, monthly invoices with ease&nbsp;</p>
          <h3 class="text-primary">Order-Entry&nbsp;
            <br> </h3>
          <p class="text-capitalize">Fufill client or customer orders on the spot with our simple and user-friendly platform&nbsp;</p>
        </div>
      </div>
    </div>
  </div>
  <div class="py-5 bg-light">
    <div class="container">
      <div class="row text-center">
        <div class="col-md-12">
          <h1 class="mb-4 text-primary">Benefits and Features</h1>
          <p class="lead text-secondary text-uppercase">Built in customizable features designed the way you want&nbsp;</p>
          <div class="row text-left mt-5">
            <div class="col-md-4 my-3">
              <div class="row mb-3">
                <div class="text-center col-2"><i class="d-block mx-auto fa fa-3x fa-slideshare"></i></div>
                <div class="align-self-center col-10">
                  <h5 class="text-secondary"><b>Sales Support&nbsp;</b></h5>
                </div>
              </div>
              <p>Support your most critical team. Define custom process flow for your Sales activity, with unlimited access. The support you need, automatically accessible and just one click away.&nbsp;</p>
            </div>
            <div class="col-md-4 my-3">
              <div class="row mb-3">
                <div class="text-center col-2"><i class="d-block mx-auto fa fa-3x fa-random"></i></div>
                <div class="align-self-center col-10">
                  <h5 class="text-secondary"><b>CRM Integration&nbsp;</b></h5>
                </div>
              </div>
              <p>Seamlessly intergrate within your current CRM application. If in need of CRM Modules, no worries, simply ask and we shall provide.&nbsp;</p>
            </div>
            <div class="col-md-4 my-3">
              <div class="row mb-3">
                <div class="text-center col-2"><i class="d-block mx-auto fa fa-3x fa-folder-open"></i></div>
                <div class="align-self-center col-10">
                  <h5 class="text-secondary"><b>Administration&nbsp;</b></h5>
                </div>
              </div>
              <p>Ensure efficient performance of all departments within your Organization. Implement processing with user defined functionality in all modules.&nbsp;</p>
            </div>
            <div class="col-md-4 my-3">
              <div class="row mb-3">
                <div class="text-center col-2"><i class="d-block mx-auto fa fa-3x fa-truck"></i></div>
                <div class="align-self-center col-10">
                  <h5 class="text-secondary"><b>Vendor Management&nbsp;</b></h5>
                </div>
              </div>
              <p>Strengthen your vendor relationships globally with structure. Manage schedule, contracts, pricing and payments all in one accessible application.&nbsp;</p>
            </div>
            <div class="col-md-4 my-3">
              <div class="row mb-3">
                <div class="text-center col-2"><i class="d-block mx-auto fa fa-3x fa-expeditedssl"></i></div>
                <div class="align-self-center col-10">
                  <h5 class="text-secondary"><b>Security&nbsp;</b></h5>
                </div>
              </div>
              <p>Peace of mind with an application tailored to your organization with customized systems, dependent and secured.&nbsp;</p>
            </div>
            <div class="col-md-4 my-3">
              <div class="row mb-3">
                <div class="text-center col-2"><i class="d-block mx-auto fa fa-3x fa-line-chart"></i></div>
                <div class="align-self-center col-10">
                  <h5 class="text-secondary"><b class="text-center">Reporting + Analytics &nbsp;</b></h5>
                </div>
              </div>
              <p>Extract and analyze meaningful insight to help better understand and improve your business performance.&nbsp;</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="py-5 text-center text-white opaque-overlay gradient-overlay h-50 my-5 bg-light" style="background-image: url(&quot;https://pingendo.github.io/templates/sections/assets/gallery_architecture_3.jpg&quot;);">
    <div class="container">
      <div class="row">
        <div class="p-4 col-md-3"> <i class="d-block fa fa-3x fa-pie-chart"></i>
          <h2 class="my-3">Improve</h2>
          <p class="">Improve your organizations efficency through time and cost effective automation &nbsp;</p>
        </div>
        <div class="col-md-3 p-4"> <i class="d-block fa fa-3x fa-th"></i>
          <h2 class="my-3">Scale</h2>
          <p class="">Allow your business to flourish with advance technology that frees up both time and effort</p>
        </div>
        <div class="col-md-3 p-4"> <i class="d-block fa fa-3x fa-globe"></i>
          <h2 class="my-3">Grow</h2>
          <p class="">&nbsp;Tackle more business with ease now that processes are streamlined</p>
        </div>
        <div class="col-md-3 p-4"> <i class="d-block fa fa-3x fa-money"></i>
          <h2 class="my-3">Profit&nbsp;</h2>
          <p>Generate more revenue, cut cost and increase gross margins</p>
        </div>
      </div>
    </div>
  </div>
  <div class="py-5 text-center bg-light">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <h1 style="font-size:70px;" class="text-secondary">PEAQ TEAM&nbsp;</h1>
          <p class="lead">How It All Got Started&nbsp;</p>
        </div>
      </div>
      <div class="row">
        <div class="col-md-4 p-4">
          <img class="img-fluid d-block rounded-circle mx-auto" src="user2.jpg">
          <p class="my-4"><i>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa.</i></p>
          <p><b>Steve</b>&nbsp;
            <br>Founder&nbsp;</p>
        </div>
        <div class="col-md-4 p-4">
          <img class="img-fluid d-block rounded-circle mx-auto" src="user3.jpg">
          <p class="my-4"><i>Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec. </i></p>
          <p><b class="text-center">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Natalie</b>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;
            <br>Principal&nbsp;</p>
        </div>
        <div class="col-md-4 p-4">
          <img class="img-fluid d-block rounded-circle mx-auto" src="user1.jpg">
          <p class="my-4"><i>Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem. Cum sociis natoque penatibus et magnis dis par</i></p>
          <p><b>Mario</b>&nbsp;
            <br>Co-Founder</p>
        </div>
      </div>
    </div>
  </div>
  <div class="py-5 text-white opaque-overlay my-5" style="background-image: url(&quot;https://pingendo.github.io/templates/sections/assets/cover_restaurant.jpg&quot;);">
    <div class="container">
      <div class="row">
        <div class="col-md-3"></div>
        <div class="col-md-6">
          <h1 class="text-gray-dark">Contact form</h1>
          <p class="lead mb-4">Complete all the fields below to let us know you're interested!</p>
          <form class="" method="post" action="https://formspree.io/">
            <div class="form-group"> <label>Email address</label>
              <input type="email" name="email" class="form-control" placeholder="Enter email"> </div>
            <div class="form-group"> <label>Contact Number</label>
              <input type="text" name="Contact Number" class="form-control" placeholder="Phone Number"> </div>
            <button type="submit" class="btn btn-primary">Send</button>
          </form>
        </div>
      </div>
    </div>
  </div>
  <div class="bg-dark text-white">
    <div class="container">
      <div class="row">
        <div class="p-4 col-md-3">
          <h2 class="mb-4 text-secondary">PEAQ SYSTEMS</h2>
          <p class="text-white">Reach PEAQ performance through speed and convenience&nbsp;</p>
        </div>
        <div class="p-4 col-md-3">
          <h2 class="mb-4 text-secondary">Mapsite</h2>
          <ul class="list-unstyled">
            <a href="#" class="text-white">Home</a>
            <br>
            <a href="#" class="text-white">Services</a>
            <br> Products&nbsp;
            <br>Company</ul>
        </div>
        <div class="p-4 col-md-3">
          <h2 class="mb-4">Contact</h2>
          <p>
            <a href="tel:+1 (914)&#10; 653-6767" class="text-white"><i class="fa d-inline mr-3 text-secondary fa-phone"></i>+1 (914) 653-6767</a>
          </p>
          <p>
            <a href="mailto:info@pingendo.com" class="text-white"><i class="fa d-inline mr-3 text-secondary fa-envelope-o"></i>Marboite@peaqsys.com</a>
          </p>
          <p>
            <a href="https://goo.gl/maps/AUq7b9W7yYJ2" class="text-white" target="_blank"><i class="fa d-inline mr-3 fa-map-marker text-secondary"></i>1000 PEAQ Way Dallas, TX &nbsp; &nbsp; &nbsp; 75071</a>
          </p>
        </div>
        <div class="p-4 col-md-3">
          <h2 class="mb-4 text-light">Subscribe</h2>
          <form>
            <fieldset class="form-group text-white"> <label for="exampleInputEmail1">Get our newsletter</label>
              <input type="email" class="form-control" id="exampleInputEmail1" placeholder="Enter email"> </fieldset>
            <button type="submit" class="btn btn-outline-secondary">Submit</button>
          </form>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12 mt-3">
          <p class="text-center text-white">© Copyright 2017 PEAQ Systems - All rights reserved. </p>
        </div>
      </div>
    </div>
  </div>
  <div class="text-center bg-dark" style="background-image: url(&quot;none&quot;);">
    <div class="container-fluid">
      <div class="row">
        <div class="py-5 col-3" style="background-color:#3b5998">
          <a href="https://www.facebook.com/" target="_blank"><i class="fa fa-fw fa-facebook fa-3x text-white"></i></a>
        </div>
        <div class="py-5 col-3" style="background-color:#00b2ff">
          <a href="https://twitter.com/" target="_blank"><i class="fa fa-fw fa-twitter fa-3x text-white"></i></a>
        </div>
        <div class="py-5 col-3 bg-primary" style="background-color:#C92228">
          <a href="https://pinterest.com/" target="_blank"><i class="fa fa-fw fa-3x text-white fa-google-plus"></i></a>
        </div>
        <div class="py-5 col-3" style="background-color:#4c68d7">
          <a href="https://www.instagram.com/" target="_blank"><i class="fa fa-fw fa-instagram fa-3x text-white"></i></a>
        </div>
      </div>
    </div>
  </div>
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>
</body>

</html>
