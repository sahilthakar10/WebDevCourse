---
id: HomePage
title: Home Page
sidebar_label: Home Page
---
```
<!DOCTYPE html>
<html>

<head>
    <title> Home Page </title>
    <!-- Start CSS here -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
        crossorigin="anonymous">
    <style>
        body {
            padding-top: 2rem;
            padding-bottom: 2rem;
        }
		div.card {
  width: 250px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  text-align: center;
}
	div.cardb {
  width: 100%;
  height: 225.328px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  text-align: left;
}

div.header {
    background-color: #4CAF50;
    color: white;
    padding: 10px;
    font-size: 40px;
}
div.Blogtext {
    color: black;
    padding: 10px;

}

div.container {
    padding: 10px;
}

        h3 {
            margin-top: 2rem;
        }

        .row {
            margin-top: 1rem;
            margin-bottom: 0;
        }

        hr {
            margin-top: 2rem;
            margin-bottom: 2rem;
        }
        .col-sm-2 {
            text-align: center;
        }
        .logo {
            height: 100px;
            width: 100px;
            vertical-align: center;
        }
        .title {
            text-align: left;
            vertical-align: center;
        }
		
		ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
	width : 100%;
}

li a:hover:not(.active) {
    background-color: #111;
}

.active {
    background-color: #4CAF50;
}
    </style>
    <!-- End CSS here -->
</head>

<body>
    <div class="container">
        <div class="row">
            <div class="col-sm-2 col-md-2 col-lg-2">
                <img class="logo" align="right" src="./img/logo.png" alt="Logo Here" />
            </div>
            <div class="col-sm-10 col-md-10 col-lg-10">
                <h1 class="title">Your Site Name here</h1>
            </div>
        </div>
		<ul>
			<li><a class="active" href="./index.html">Home</a></li>
			<li><a href="./profile.html">Profile</a></li>
			<li><a href="./contact.html">Contact</a></li>
		</ul>
		
		<div class="row">
			<div class="col-sm-3 col-md-3 col-lg-3">
				<div class="card">
					<img src="http://www.thebluediamondgallery.com/tablet/images/blog.jpg" alt="blog" style="width:100%">
					<div class="container">
						<p>August, 2010</p>
					</div>
				</div>
			
			</div>
			<div class="col-sm-9 col-md-9 col-lg-9">
			
				<div class="cardb">
					<div class="Blogtext">
						<p> Donec a lectus ut purus scelerisque ultrices sagittis ut diam. Duis ullamcorper, metus vel vulputate blandit, ipsum odio finibus neque, sed tempus risus diam et nulla. In sed nulla ligula. Morbi varius tincidunt imperdiet. Suspendisse libero enim, maximus at blandit eget, semper tempus leo. Interdum et malesuada fames ac ante ipsum primis in faucibus. Vivamus lectus metus, tempor et placerat ut, feugiat ac mi. Aliquam vel elit magna. Aliquam facilisis nunc nec eros venenatis laoreet.</p>
						</div>

					
				</div>
			</div>
		</div>
		<div class="row">
			<div class="col-sm-9 col-md-9 col-lg-9">
				<div class="cardb">
					<div class="Blogtext">
						<p>Suspendisse id mattis justo. Nullam convallis ex eu justo gravida, tristique cursus libero consectetur. Pellentesque ut nulla varius massa rutrum placerat. Ut ut dolor urna. Fusce viverra dictum sapien at maximus. Proin egestas erat condimentum, euismod leo sed, congue nisl. Suspendisse vel elit pretium, sodales elit mattis, tristique lectus.</p>
					</div>

					
				</div>
			</div>	
			<div class="col-sm-3 col-md-3 col-lg-3">
			<div class="card">
					<img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Gull_portrait_ca_usa.jpg" alt="Gull_portrait_ca_usa" style="width:100%">

					<div class="container">
						<p>May 22, 2014</p>
					</div>
				</div>
			</div>
			</div>
		<div class="row">
			<div class="col-sm-3 col-md-3 col-lg-3">
			<div class="card">
					<img src="https://libreshot.com/wp-content/uploads/2017/09/hallucination-861x574.jpg" alt="hallucination-861x574" style="width:100%">

					<div class="container">
						<p>January 12, 2017</p>
					</div>
				</div>
			</div>
			<div class="col-sm-9 col-md-9 col-lg-9">
				<div class="cardb">
					<div class="Blogtext">
						<p> Phasellus hendrerit massa eget velit accumsan, sed pulvinar quam gravida. Aliquam convallis convallis orci a malesuada. Nulla elementum ultrices tortor eu auctor. Cras sodales felis quis ex pellentesque elementum id ut felis. Donec ut orci vulputate, aliquam ex sed, congue purus. Pellentesque semper ipsum vel fermentum lacinia. Pellentesque eu tincidunt dui. Etiam nulla purus, sodales nec lectus et, maximus laoreet ex.</p>
					</div>

					
				</div>
		</div>
    </div>
	



</body>
<!-- Start Javascript here -->
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
    crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49"
    crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T"
    crossorigin="anonymous"></script>
<!-- End Javascript here -->

</html>
```