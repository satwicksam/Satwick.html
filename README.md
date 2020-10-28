# Satwick.html
optimize my html tag
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resturant</title>
    <link rel="stylesheet" href="food.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css"> 
</head>
<body>
    <div class="hero">
        <div class="nav-bar">
            <div class="nav-logo">
                <img src="logo.png">
            </div>
            <div class="nav-links" id="nav-links">
                <i class="fa fa-close" onclick="closeMenu()"></i>
                <ul>
                    <a href="#"><li>HOME</li></a>
                    <a href="#"><li>ABOUT</li></a>
                    <a href="#"><li>RECIPE</li></a>
                </ul>
                <button type="button" class="btn">SIGN UP</button>
            </div>
            <i class="fa fa-bars" onclick="showMenu()"></i>
        </div>
        <div class="banner-title">
            <h1>Food <span>Dosen't have<br> a religion.</span> It is a religion</h1>
            <button type="button" class="btn">EXPLORE</button>
        </div>
        <div class="vertical-bar">
            <div class="search-icon">
                <i class="fa fa-th-list"></i>
                <i class="fa fa-search"></i>
            </div>
        <div class="notification">
            <div class="contents">
                <small>Subscribe my youtube channel and never miss any nem video</small>
                <p><a href="#">PREV</a><a href="#">NEXT</a></p>
            </div>
            <div class="notification-img">
                <img src="youtube.jpg">
            </div>
        </div>
    </div>
    <script>
        var show = document.getElementById("nav-links")
        function showMenu() {
            show.style.right = "0";
        }
        function closeMenu() {
            show.style.right = "-200px";
        }
    </script>

</body>
</html>
