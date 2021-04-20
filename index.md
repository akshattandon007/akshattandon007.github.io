<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<header>
  iZooto
</header>
<nav>
<a style="color:#2D2363 padding-left: 17px;" href="/Assignment/Index.html">SignUp</a> 

</nav>
<body>

<h1 align="center">Assignment Website</h1>
<h2 align="center">Get ready to signup!</h2>
<input type = "image" name = "learn" value = "myimage" class="ImageButton alignimg" onClick="PageReload()" src="https://yt3.ggpht.com/a/AATXAJyRxTrSa_WkQG9ATqH0ViRzbOAdW_TLJ_gpbw=s900-c-k-c0xffffffff-no-rj-mo" >
   
 <br>
<button style="width: 150px; margin-left: 45%"  class="button button1 " onClick="LoadNextPage()">Sign Up</button>

</body>
<footer>
  <p>Copyright</p>
</footer>
</html>
<script>
function PageReload()
{
 window.location.reload();
}
function LoadNextPage()
{
window.location.href = "/Assignment/Form.html";
}
</script>


<style>
.alignimg {
    margin: 5px auto  10px;
    display: block;
}
.ImageButton{
height:207px;
width:210px;
}
.button {
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}
.button1:hover {
  background-color: #2D2363;
  color: white;
}
.button1 {
  background-color: white;
  color: black;
  border: 2px solid #2D2363
  }
  header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  text-margin-top:0px;
 
  font-size: 35px;
  color: white;
  height:26px;
}
footer {
  background-color: #777;
 position: absolute;
  bottom: 0;
  width: 100%;
  text-align: center;
  color: white;
 height: 50px;
}

  </style>
