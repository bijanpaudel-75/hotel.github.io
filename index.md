---
layout: default
title: Home
---
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>StayFinder</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    StayFinder <i class="fas fa-hotel"></i>
</header>

<div class="page active" id="search-page">
    <div class="search-box">
        <div class="search-input-group">
            <i class="fas fa-dollar-sign"></i>
            <input type="text" id="name_hotel" placeholder="name of hotel" />
        </div>
        <button onclick="searchHotels()"><i class="fas fa-search"></i> Search Stays</button>
    </div>

    <div id="hotel-list"></div>
</div>

<div class="page" id="details-page">
    <button onclick="goBack()" class="go-back-btn">
        <i class="fas fa-arrow-left"></i> Back to Search
    </button>
    <div id="hotel-details" class="details-container"></div>
</div>
<script src="script.js"></script>
</body>
</html>
# Welcome to my Hotel Website!
This is the main page that people will see when they visit my URL.
