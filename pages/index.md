---
layout: sti
title: Overview
weight: 0
permalink: /
---

<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Save The Island | Home</title>
    <link rel="stylesheet" href="https://tfngamesofficial.github.io/assets/css/navbar.css">
	  <link rel="shortcut icon" type="image/x-icon" href="{{ '/assets/favicon.ico' | relative_url }}">
    <style>
        body {
            background-color: #141414 !important;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
/* Rounded Picture Styles */
.rounded-picture {
    text-align: center;
    margin-top: 20px;
padding: 25px;
    position: relative; /* Set the position to relative for absolute positioning */
}

.rounded-picture img {
    max-height: 500px;
    min-height: 500px;
    width: 1328px;
    padding: 25px;
    margin-top: -50px;
    border-radius: 40px;
    object-fit: cover; /* or use 'cover' based on your preference */
}

 .overlay {
    max-height: 500px;
    min-height: 500px;
    width: 1328px;
    margin-top: -25;
    margin-left: 84px;
    border-radius: 15px;
    text-align: center;
    position: absolute;
    background-color: rgba(0, 0, 0, 0.72);
    } 

.image-text {
    position: absolute;
    top: 45%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: #fff;
}

.image-text h2 {
    font-size: 80px;
    margin-bottom: 10px;
line-height: 45px;
}

.image-text p {
    font-size: 30px;
line-height: -45px;
    color: #ddd;
}

	    /* Bootstrap-ähnliche Button-Klasse */
.btn {
  display: inline-block;
  font-weight: 400;
  text-align: center;
  white-space: nowrap;
  vertical-align: middle;
  user-select: none;
  border: 1px solid transparent;
  padding: 0.375rem 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 0.25rem;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
  cursor: pointer;
}

/* Bootstrap-ähnliche primäre Button-Farbe */
.btn-primary {
  color: #fff;
  background-color: #a60303;
  border-color: #a60303;
}

/* Bootstrap-ähnliche Hover- und Focus-Effekte */
.btn:hover, .btn:focus {
  color: #fff;
  background-color: #A60F0F;
  border-color: #A60F0F;
}

/* Bootstrap-ähnliche aktive und gedrückte Effekte */
.btn:active {
  color: #fff;
  background-color: #A60F0F;
  border-color: #A60F0F;
  box-shadow: 0 0.2rem 0.5rem rgba(167, 7, 7, 0.5);
}

/* Bootstrap-ähnliche deaktivierte Button-Stile */
.btn:disabled {
  color: #fff;
  background-color: #6c757d;
  border-color: #6c757d;
  cursor: not-allowed;
}

	            /* Rounded Box Styles */
        .rounded-box-container {
	    text-align: center;
            display: flex;
            justify-content: space-around;
    	   /* margin: -10px; */
	    padding-left: 90px;
	    padding-right: 90px;
        }

	roundtext {
		color: rgba(255, 255, 255, 0,1);
		padding: 15px;
}

        .rounded-box {
            background-color: #141414;
            border: 1px solid #272727;
            border-radius: 10px;
            padding: 10px;
            text-align: center;
            width: 30%; /* Adjusted width for responsiveness */
        }

        /* FAQ Styles */
        h3, h4 {
            color: #fff;
        }

        p {
            font-size: 16px;
            color: #aaa;
        }

        /* Support Page Styles */
        .support-text {
            margin-top: 20px;
        }
        text {
    font-size: 16px;
    font-weight: 700;
    line-height: 40px;
    text-transform: capitalize;
padding: 6px;
    }
.left {
    font-size: 11px;
    line-height: 16px;
    text-transform: capitalize !important;
    padding: 6px;
    padding-top: 17px;
    padding-left: calc(100% - 30%);
    }
.btn1.dropdown-toggle {
    font-size: 11px;
    line-height: 40px;
  color: #fff;
  text-transform: uppercase;
  border: 0px solid #dee2e6; /* Menu border */
  outline: none;
  box-shadow: none;
}

.dropdown-menu {
  background-color: rgb(39, 39, 39); /* Menu background color */
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Menu shadow */
  border: 0px solid #dee2e6; /* Menu border */
}

nav a.dropdown-item {
  color: #fff; /* Text color of dropdown items */
  padding: 8px 16px; /* Padding of dropdown items */
  text-decoration: none; /* No underline for links */
  display: block; /* Display each item as a block */
}

/* Highlight effect on hover of a dropdown item */
nav a.dropdown-item:hover {
  background-color: rgb(45, 45, 45); /* Background color on hover */
  color: #fff; /* Text color on hover */
}
</style>
</head>
<body>

    <!-- Custom Navbar
    <nav>
        <text href="#">Save The Island</text>
        <a href="#" class="active">OVERVIEW</a>
        <a href="/save-the-island/help" class="nav-link">HELP</a>
	    <a class="nav-link" id="loggedInMessage" onclick="loginWithEpic()">LOGIN</a>
	    <div class="left">
	    <button style="background-color:rgb(39,39,39); color:#fff; border-color:#ffffff00;" onclick="logout()">Logout</button>
	    </div>
    </nav> -->


    <div class="rounded-picture">
    <img src="https://wallpaper.dog/large/10812313.jpg" alt="Save The Island">
    <div class="image-text">
        <h2>Save The Island</h2>
        <p>The Save The Island event quests are now available! Earn In-Game rewards and more. By joining you will add "Save The Island" to your Epic Games account!</p>
<button class="btn btn-primary" onclick="saveAccessToken()">Try it now!</button>

    </div>
</div>
<center><h4>Steps</h4></center>
	<div class="rounded-box-container">
	<div class="rounded-box">
            <img src="https://cdn2.unrealengine.com/earn-rewards-120x120-ccb3638290e7.png">
            <h3>JOIN</h3>
            <roundtext>Login with our Epic Games account and join the event.</roundtext>
        </div>
	<div class="rounded-box">
            <!-- <img src="https://cdn2.unrealengine.com/earn-rewards-120x120-ccb3638290e7.png"> -->
            <h3>COMPLETE QUESTS</h3>
            <roundtext>Complete quests for new stages and to get in-game rewards.</roundtext>
        </div>
	<div class="rounded-box">
            <!-- <img src="https://cdn2.unrealengine.com/earn-rewards-120x120-ccb3638290e7.png"> -->
            <h3>MORE FUN</h3>
            <roundtext>Complete additional "Fun Quests" in Battle Royale for additional xp.</roundtext>
        </div></div>
</body></html>
