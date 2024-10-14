<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>Editkaro Portfolio</title>
 <link rel="stylesheet" href="styles.css">
</head>
<body>
 <!-- Header Section -->
 <header>
 <h1>Editkaro.in Portfolio</h1>
 <p>Showcasing our finest work in social media marketing and video editing</p>
 </header>
 <!-- Filter Buttons -->
 <div class="filter-buttons">
 <button onclick="filterVideos('all')">All</button>
 <button onclick="filterVideos('short')">Short-form Videos</button>
 <button onclick="filterVideos('long')">Long-form Videos</button>
 <button onclick="filterVideos('gaming')">Gaming Videos</button>
 <button onclick="filterVideos('football')">Football Edits</button>
 <button onclick="filterVideos('ads')">eCommerce Ads</button>
 <button onclick="filterVideos('color')">Color Grading</button>
 <button onclick="filterVideos('anime')">Anime Videos</button>
 </div>
 <!-- Video Portfolio Section -->
 <section id="video-gallery">
 <!-- Short-form Videos -->
 <div class="video-container short">
 <h2>Short-form Videos</h2>
 <video controls>
 <source src="video1.mp4" type="video/mp4">
 </video>
 <!-- Add more videos here -->
 </div>
 <!-- Long-form Videos -->
 <div class="video-container long">
 <h2>Long-form Videos</h2>
 <video controls>
 <source src="video2.mp4" type="video/mp4">
 </video>
 </div>
 <!-- Add other categories following the same structure -->
 </section>
 <script src="scripts.js"></script>
</body>
</html>
