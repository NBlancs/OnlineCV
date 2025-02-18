<!DOCTYPE html>
<html>
<head>
    <title>Personal CV</title>
    <style>
        .page-content {
            padding: 20px;
        }
        .purple-star {
            width: 100px;
            height: 100px;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <p>I am Header with unordered list of hyperlinks</p>
    
    <header>
        <ul>
            <li><a href="#about">I am About link and my href value is #about</a></li>
            <li><a href="#education">I am Education link and my href value is #education</a></li>
            <li><a href="#skills">I am Skills link and my href value is #skills</a></li>
            <li><a href="#portfolio">I am Portfolio link and my href value is #portfolio</a></li>
            <li><a href="#contact">I am Contact link and my href value is #contact</a></li>
        </ul>
    </header>

    <!-- Sharingan image -->
    <img src="sharingan.jfif" alt="I am an image and I'm all by myself" class="purple-star">
    
    <p>I am division with class equal to page-content that encloses all other division elements below</p>

    <div class="page-content">
        <!-- Main heading -->
        <h1>Hello! I am a text with the largest heading</h1>

        <!-- Content sections -->
        <div id="about">I am division with id equal to about</div>
        <div id="education">I am division with id equal to education</div>
        <div id="skills">I am division with id equal to skills</div>
        <div id="portfolio">I am division with id equal to portfolio</div>
        <div id="contact">I am division with id equal to contact</div>

        <!-- Footer -->
        <footer>I am a footer the last section of this page</footer>
    </div>
</body>
</html>
