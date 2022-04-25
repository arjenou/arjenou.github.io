<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="./css/index.css">
    <title>Arjen</title>
</head>

<body>
    <!-- 上部 ------------------------------------------------------------------------------------>
    <header>
        <a href="./index.html" class="logo">Yunjie</a>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="./html/Arjen.English.html">About</a></li>
        </ul>
    </header>
    <section class="banner"></section> 
    <script type="text/javascript">
    window.addEventListener("scroll",function(){
        var header = document.querySelector("header");
        header.classList.toggle("sticky",window.scrollY > 0);
    })
    </script>
    <!-- 中部 ------------------------------------------------------------------------------------>
    <div class="pimg1">
        <div class="ptext">
            <span class="border">
                Arjen
            <h2>SINCE 2021 | TOKYO</h2>
            </span>
        </div>
    </div>
    <section class="section section-light">
        <h2>Select your language for localized experience</h2>
        <div class="btn-a">
            <a href="./html/Arjen.Chinese.html" class="btn chinese">中国语</a>
            <a href="./html/Arjen.Japanese.html" class="btn japanese">日本語</a>
        </div>
    <!-- 下部 ------------------------------------------------------------------------------------>
        <p class="footer"> &copy;2021 Yunjie Wang </p>
 
</section>

</body>
    
