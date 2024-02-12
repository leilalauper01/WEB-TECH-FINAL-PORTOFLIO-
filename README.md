# WEB-TECH-FINAL-PORTOFLIO-
WEB TECH FINAL PORTOFLIO 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Leila Lauper Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #F8F8F8;
            margin: 0;
            padding: 0;
            font-family: Didot, sans-serif;
        }

        /* Set Didot font for all headings */
        h1, h2, h3, h4, h5, h6 {
            font-family: Didot, serif;
            color: black; /* Set heading color to black */
        }

        /* CSS for About Me, Portfolio, and Contact links */
        nav ul li a {
            color: black; /* Set the text color to black */
            text-decoration: none; /* Remove the underline */
            cursor: pointer;
        }

        /* Your existing CSS styles */
        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li:first-child {
            margin-left: 0;
        }

        h1 {
            text-align: center;
        }

        @media screen and (max-width: 768px) {
            header .container {
                justify-content: center;
            }
        }

        /* Add more CSS styles as needed */
        .intro-section {
            padding: 50px 0;
            text-align: center;
        }

        .intro-section h2 {
            margin-bottom: 20px;
        }

        .intro-section p {
            margin-bottom: 30px;
        }

        .start-journey-btn {
            background-color: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }

        /* Slideshow container */
        .slideshow-container {
            max-width: 100%;
            position: relative;
            margin-top: 50px;
        }

        /* Hide the images by default */
        .mySlides {
            display: none;
        }

        /* Next & previous buttons */
        .prev, .next {
            cursor: pointer;
            position: absolute;
            top: 50%;
            width: 30px; /* Adjusted width */
            height: 30px; /* Adjusted height */
            padding: 8px;
            margin-top: -15px; /* Adjusted margin */
            color: white;
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 5px;
            user-select: none;
            text-align: center;
            font-size: 16px; /* Adjusted font size */
        }

        /* Position the "next button" to the right */
        .next {
            right: 0;
        }

        /* Caption text */
        .caption {
            color: black;
            font-size: 15px;
            padding: 8px 12px;
            position: absolute;
            bottom: 8px;
            width: 100%;
            text-align: center;
        }

        /* Number text (1/3 etc) */
        .numbertext {
            color: black;
            font-size: 12px;
            padding: 8px 12px;
            position: absolute;
            top: 0;
        }

        /* Preview section */
        .portfolio-preview {
            text-align: center;
            padding: 50px 0;
        }

        .portfolio-preview img {
            max-width: 100%;
            height: auto;
            margin-bottom: 20px;
        }

        .portfolio-preview h3 {
            margin-bottom: 10px;
        }

        .portfolio-preview p {
            margin-bottom: 20px;
        }

        /* Center the interests and hobbies section */
        #interests-hobbies {
            text-align: center;
        }

        /* Contact section */
        .contact-section {
            background-color: #f2f2f2;
            padding: 50px 0;
            text-align: center;
        }

        .contact-form {
            max-width: 500px;
            margin: auto;
        }

        .form-group {
            margin-bottom: 20px;
        }

        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
            text-align: left;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        textarea {
            resize: vertical;
        }

        .submit-btn {
            background-color: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
        }

        .submit-btn:hover {
            background-color: #333;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            left: 0;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <div class="container">
            <h1>Leila Lauper</h1>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="https://www.instagram.com/your_instagram_username" target="_blank">Instagram</a></li>
                    <li><a href="https://www.linkedin.com/in/your_linkedin_username" target="_blank">LinkedIn</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- About Me section -->
    <section id="about" class="intro-section">
        <h2>Hi! Welcome to my Portfolio!</h2>
        <p>I'm Swiss, raised on the Northern Coast of Kenya. Growing up I was immersed in marine life and wildlife. I went to a British International School where I was exposed to Shakespeare, Tchaikovsky. I went on then to pursue an LLB in Law at the University of Exeter. At Exeter, I founded a women's eco-friendly swimwear start-up and now I'm pursuing a Masters in Computer Science with the aims of integrating my entrepreneurial interests, tech interests in successfully carving a career in Intellectual Property law.</p>
        <button class="start-journey-btn" onclick="openSlideshow()">Start Journey</button>
    </section>

    <!-- Slideshow container -->
    <div class="slideshow-container">
        <div class="mySlides fade">
            <img src=""C:\Users\AdminUser\Downloads\Photos Web TechProject"/IMG_0887.png" style="width:100%">
            <div class="caption">Caption</div>
        </div>
        <div class="mySlides fade">
            <img src="C:\Users\AdminUser\Downloads\Photos Web TechProject" style="width:100%">
            <div class="caption">Caption Two</div>
        </div>
        <div class="mySlides fade">
            <img src="image3.jpg" style="width:100%">
            <div class="caption">Caption Three</div>
        </div>
        <!-- Next and previous buttons -->
        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
    </div>

    <!-- Portfolio preview section -->
    <section id="portfolio" class="portfolio-preview">
        <img src="portfolio_image.jpg" alt="Portfolio Project 3">
        <h3>ERATO SWIM</h3>
        <p>Women's eco-friendly swimwear line founded in 2020</p>
        <p>Erato Swim was founded in 2020 at Exeter Innovation Hub. The fashion label is inspired by nature and Hellenistic art.
            This was a fun project to work on during Covid. I collaborated with Parisienne atelier during the making of the first collection. 
            The second collection I traveled to Kenya for 7 months and collaborated with local creatives.</p>
        <!-- Add any additional information or links here -->
    </section>

    <!-- Portfolio preview section for Law School -->
    <section id="law-school" class="portfolio-preview">
        <img src="law_school_image.jpg" alt="Law School Project">
        <h3>Law School</h3>
        <p>My experience at law school</p>
        <!-- Add slideshow container for Law School -->
        <div class="slideshow-container">
            <div class="mySlides fade">
                <img src="law_school_image1.jpg" style="width:100%">
                <div class="caption">Law School Image 1</div>
            </div>
            <div class="mySlides fade">
                <img src="law_school_image2.jpg" style="width:100%">
                <div class="caption">Law School Image 2</div>
            </div>
            <!-- Next and previous buttons -->
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
        <!-- Add any additional information or links here -->
    </section>

    <!-- Portfolio preview section for Computer Science Project -->
    <section id="computer-science" class="portfolio-preview">
        <img src="computer_science_image.jpg" alt="Computer Science Project">
        <h3>Computer Science Project</h3>
        <p>Description of Computer Science Project</p>
        <!-- Add slideshow container for Computer Science Project -->
        <div class="slideshow-container">
            <div class="mySlides fade">
                <img src="computer_science_image1.jpg" style="width:100%">
                <div class="caption">Computer Science Image 1</div>
            </div>
            <div class="mySlides fade">
                <img src="computer_science_image2.jpg" style="width:100%">
                <div class="caption">Computer Science Image 2</div>
            </div>
            <!-- Next and previous buttons -->
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
        <!-- Add any additional information or links here -->
    </section>

    <!-- Interests and Hobbies section -->
    <section id="interests-hobbies" class="intro-section">
        <h2>Interests and Hobbies</h2>
        <!-- Slideshow container for interests and hobbies -->
        <div class="slideshow-container">
            <div class="mySlides fade">
                <img src="interest1.jpg" style="width:100%">
                <div class="caption">Caption Text 1</div>
            </div>
            <div class="mySlides fade">
                <img src="interest2.jpg" style="width:100%">
                <div class="caption">Caption Text 2</div>
            </div>
            <!-- Next and previous buttons -->
            <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
            <a class="next" onclick="plusSlides(1)">&#10095;</a>
        </div>
    </section>

    <!-- Contact section -->
    <section id="contact" class="contact-section">
        <div class="contact-form">
            <h2>Contact Me</h2>
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="5" required></textarea>
                </div>
                <button type="submit" class="submit-btn">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Interactive Portfolio</p>
    </footer>

    <!-- Your JavaScript code goes here -->
    <script>
        var slideIndex = 0;
        showSlides();

        function showSlides() {
            var i;
            var slides = document.getElementsByClassName("mySlides");
            for (i = 0; i < slides.length; i++) {
                slides[i].style.display = "none";
            }
            slideIndex++;
            if (slideIndex > slides.length) { slideIndex = 1 }
            slides[slideIndex - 1].style.display = "block";
            setTimeout(showSlides, 2000); // Change image every 2 seconds
        }

        function plusSlides(n) {
            showSlides(slideIndex += n);
        }

        function currentSlide(n) {
            showSlides(slideIndex = n);
        }

        function openSlideshow() {
            var slides = document.getElementsByClassName("mySlides");
            for (var i = 0; i < slides.length; i++) {
                slides[i].style.display = "block";
            }
        }
    </script>
</body>

</html>
