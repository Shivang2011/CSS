<!DOCTYPE html>
<html>
<head>
<style>
.ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: rgb(238, 228, 228);
}

.li {
  float: left;
}

.li a {
  display: block;
  color: rgb(5, 4, 4);
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.li a:hover {
  background-color: rgb(53, 190, 184);
}

.video{
  position: fixed;
  
}

</style>
</head>
<body>

  <div class="li"><a href="a.html">Home</a></div>
  <div class="li"><a href="#news">News</a></div>
  <div class="li"><a href="#contact">Contact</a></div>
  <div class="li"><a href="12.html">About</a></div>
  <div class="li" style="float:right"><a class="active" href="#models">Models</a></div>
<video autoplay muted loop id="video" width="100%">
    <source src="C:\Users\Riddhi\Desktop\Habibi.mp4" type="video/mp4">
    <source src="C:\Users\Riddhi\Desktop\Habibi.ogg" type="video/ogg">
</video>
</body>
</html>
