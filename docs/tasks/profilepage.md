---
id: ProfilePage
title: Profile Page
sidebar_label: Profile Page
---

```
<!DOCTYPE html>
<html>

<head>
    <title> Profile Page </title>
    <!-- Start CSS here -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB"
        crossorigin="anonymous">
    <style>
        body {
            padding-top: 2rem;
            padding-bottom: 2rem;
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
        .field
        {
            margin-right: 5px;
            padding: 10px;
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
  <li><a href="./index.html">Home</a></li>
  <li><a class="active" href="./profile.html">Profile</a></li>
  <li><a href="./contact.html">Contact</a></li>
</ul>
        <div class="row">
            <table>
                <tr>
                    <td rowspan="5"><img src="./img/user.png" alt="User Photo" /></td>
                    <td class="field">Name :</td><td> Mr. Robison</td>
                </tr>
                <tr>
                        <td class="field">Email :</td><td><a href="mailto:mail@example.com">mail@example.com</a></td>
                </tr>
                <tr>
                        <td class="field">Contact No : </td><td>+1 246 678 889</td>
                </tr>
                <tr>
                        <td class="field">Website :</td><td><a target="_blank" href="http://www.google.com">www.google.com</a></td>
                </tr>
                <tr>
                        <td class="field">Country :</td><td>Canada</td>
                </tr>
                
            </table>
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