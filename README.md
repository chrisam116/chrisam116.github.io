<!DOCTYPE html>
<html>
  <head>
    <style>
      p.rtl {
  direction: rtl;
}

* {
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 30px;
}

header {
  background-color: #4CAF50;
  color: #fff;
  padding: 10px 0;
}

header h1 {
  margin: 0;
  display: inline-block;
}

nav {
  display: inline-block;
  float: right;
}

nav ul {
  margin: 0;
  padding: 0;
  list-style: none;
}

nav ul li {
  display: inline-block;
  margin-left: 20px;
}

nav ul li:first-child {
  margin-left: 0;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  padding: 50px 0;
  background-color: #fff;
}

h2 {
  color: #4CAF50;
  margin-top: 0;
}

.places {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  margin-top: 30px;
}

.place {
  width: calc(33.33% - 10px);
  background-color: #f2f2f2;
  border-radius: 5px;
  padding: 20px;
  text-align: center;
  margin-bottom: 20px;
  transition: box-shadow 0.2s ease-in-out;
}

.place:hover {
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
}

.place img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  border-radius: 5px;
  margin-bottom: 10px;
}

.place h3 {
  margin-top: 0;
}

.place p {
  margin-bottom: 0;
}

.place a {
  display: inline-block;
  margin-top: 10px;
  padding: 10px 20px;
  background-color: #4CAF50;
  color: #fff;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.2s ease-in-out;
}

.place a:hover {
  background-color: #3e8e41;
}

footer {
  background-color: #ccc;
  color: #333;
  padding: 10px 0;
  text-align: center;
}
    </style>
  </head>
  <body>
    <header>
      <div class="container">
        <h1>مقرات دير الأنبا انطونيوس</h1>
        <nav>          <ul>            <li><a href="index.html">Home</a></li>           </ul>        </nav>
      </div>
    </header>
    <main>
      <div class="container">
        <h2>مقرات دير الأنبا انطونيوس</h2>
        <p>اختر محافظتك</p>
        <div class="places">
          <div class="place">
            <img src="H:\DDMPV\Pictures\IMG_20230420_183254.jpg" alt="Place 1">
            <h3>البحر الأحمر</h3>
            <p>الغردقة</p>
            <a href="place1.html">Learn More</a>
          </div>
          <div class="place">
            <img src="place2.jpg" alt="Place 2">
            <h3>Place 2</h3>
            <p>Los Angeles</p>
            <a href="place2.html">Learn More</a>
          </div>
          <div class="place">
            <img src="place3.jpg" alt="Place 3">
            <h3>Place 3</h3>
            <p>Chicago</p>
            <a href="place3.html">Learn More</a>
          </div>
        </div>
      </div>
    </main>
    <footer>
      <div class="container">
        <p>&copy; 2023 Places. All rights reserved.</p>
      </div>
    </footer>
  </body>
</html>	
