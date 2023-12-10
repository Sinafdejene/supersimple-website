<!-- Home Page -->

<!DOCTYPE html>
<html>
<head>
<title>Adama Polytechnic College</title>
<style>
body {
  background-color: #f2f2f2; 
  font-family: Arial, sans-serif;
}

h1 {
  text-align: center;  
}

nav {
  background-color: #333;
  overflow: hidden;
}

nav a {
  float: left;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

nav a:hover {
  background-color: #ddd;
  color: black;
}

.logo {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 150px;
}

</style>
</head>
<body>

<h1>Adama Polytechnic College</h1>

<img src="college-logo.png" alt="College Logo" class="logo">

<nav>
  <a href="index.html">Home</a>
  <a href="academics.html">Academics</a>
  <a href="admissions.html">Admissions</a>
  <a href="gallery.html">Gallery</a> 
</nav>

<p>Welcome to Adama Polytechnic College! We offer diploma programs in various streams...</p>

</body>
</html>

<!-- Academics Page -->

<!DOCTYPE html>
<html>
<head>
<title>Academics</title>

<style>
/* Same as home page */  
</style>

</head>
<body>

<h1>Academics</h1> 

<nav>
  <!-- Same nav as home page -->
</nav>

<h2>Departments</h2>

<ul>
  <li>Arts
    <ul>
      <li><a href="english.html">English</a></li>
      <li><a href="sociology.html">Sociology</a></li>
    </ul>
  </li>
  
  <li>Science
    <ul>
     <li><a href="computerscience.html">Computer Science</a></li>
     <li><a href="mathematics.html">Mathematics</a></li>
    </ul>
  </li>   
  
  <li>Commerce
   <ul>
     <li><a href="accounting.html">Accounting</a></li>
     <li><a href="economics.html">Economics</a></li>
   </ul>
  </li>
</ul>

</body>
</html>

<!-- Example Course Page -->

<!DOCTYPE html>  
<html>
<head>
<title>English</title>

<style> 
/* Same as home page */
</style>
</head>

<body>

<h1>English</h1>

<nav>
 <!-- Same nav as home page -->  
</nav>

<p>English course teaches literature, reading, writing, analysis...</p>

<h2>Teachers</h2>
<ul>
  <li>Mrs. Sharma</li>
  <li>Mr. Raman</li> 
</ul>

<h2>Timetable</h2>  
<table>
  <tr>
    <th>Day</th>
    <th>Timing</th> 
  </tr>
  <tr>
    <td>Monday</td>
    <td>9 - 10 AM</td>
  </tr>
  <tr>
    <td>Wednesday</td>
    <td>11 - 12 PM</td>
  </tr>
</table>

</body>
</html>

<!-- Admissions Page -->

<!DOCTYPE html>
<html>
<head>
<title>Admissions</title>

<style>
/* Same as home page */ 
</style>
</head>

<body>

<h1>Admissions</h1>

<nav>
<!-- Same nav as home page -->
</nav>

<form>
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name"><br>
  
  <label for="email">Email:</label><br>  
  <input type="email" id="email" name="email"><br>
   
  <label for="department">Department:</label><br>
  <select id="department" name="department">
    <option value="arts">Arts</option>
    <option value="science">Science</option>
    <option value="commerce">Commerce</option>
  </select><br>
    
  <label for="courses">Courses:</label><br>
  <input type="text" id="courses" name="courses"><br>
  
  <input type="submit" value="Apply">
</form> 

</body>
</html>

<!-- Gallery Page -->

<!DOCTYPE html>
<html>
<head>
<title>Gallery</title>

<style>
/* Same as home page */
</style>  
</head>

<body>

<h1>Gallery</h1>

<nav>
<!-- Same nav as home page --> 
</nav>

<img src="pic1.jpg">
<img src="pic2.jpg"> 
<img src="pic3.jpg">

</body>
</html>
