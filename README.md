<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewpoint" content="width=device-width, initial-scale=1.0" />
    <title>KomalBasit Portfolio Website</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/modern-normalize/2.0.0/modern-normalize.min.css" integrity="sha512-4xo8blKMVCiXpTaLzQSLSw3KFOVPWhm/TRtuPVc4WG6kUgjH6J03IBuG7JZPkcWMxJ5huwaBpOpnwYElP/m6wg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
<style>
h1.a {font-family: "Audiowide", sans-serif;}
h1.b {font-family: "Sofia", sans-serif;}
h1.c {font-family: "Trirong", serif;}
</style>
    <link rel="stylesheet" href="css/style.css">


  </head>
  <body>
    <header>
        <div class="logo">
            <img src="komal.jpeg" alt="">
        </div>
        <button class="nav-toggle" aria-label="toggle navigation">
            <span class="hamburger"></span>  
        </button>
        <nav class="nav">
            <ul class="nav__list">
                <li class="nav__item"><a href="#home" class="nav__link">Home</a></li>
                <li class="nav__item"><a href="#services" class="nav__link">My Services</a></li>
                <li class="nav__item"><a href="#about" class="nav__link">About me</a></li>
                <li class="nav__item"><a href="#work" class="nav__link">My Work</a></li>
            </ul>
        </nav>         
    </header>

  <!-- Introduction-->
<section class="intro" id="home">
    <h1 class="section__title section__title--intro">
        Hello I am <strong>Komal Basit</strong> 
    </h1> <p class="section__subtitle section__subtitle--intro"><strong>Front-end Developer</strong></p>
        <img src="komal.jpg" alt="Intro Image" class="intro-image">
</section>

    <!--My Services-->
    <section class="My-Services" id="services">
        <h2 class="section__title section__title--services">What I do</h2>
        <div class="services">
            <div class="service">
                <h3>E-Commerce Websites</h3>
                <p>Looking to launch or revamp your online store? I excel at building SEO-friendly e-commerce platforms that not only look stunning but also rank high in search engine results. With a focus on optimized site structure, fast loading times, and mobile responsiveness, I'll help you create an online shopping experience that drives sales and fosters customer loyalty.</p>
            </div> <!-- /services-->
            <div class="service">
                <h3>Custom Website Development</h3>
                <p>Your website is often the first impression customers have of your business, so it needs to make a statement. I specialize in creating custom websites that captivate audiences and perform well in search engine rankings. By strategically optimizing keywords, meta tags, and content structure, I'll ensure that your website attracts the right audience and drives conversions.</p>
            </div> <!-- /services-->
            <div class="service">
                <h3>Website Modification and Enhancement</h3>
                <p>Already have a website but not seeing the results you want? Let me help. I specialize in modifying and enhancing existing websites to improve their SEO performance. Whether it's refining site navigation, optimizing meta tags, or enhancing site speed, I'll implement targeted SEO strategies to boost your website's visibility and drive more organic traffic.</p>
            </div> <!-- /services-->
        </div>
        <a href="#work" class="btn">My Work</a>
    </section>
    <!--About me-->
    <section class="About-Me" id="about">
        <h2 class="section__title section__title--about">Who I am</h2>
        <p class="section__subtitle section__subtitle--about"><strong>Designer & Developer</strong></p>

        <div class="about-me__body">
            <p>
                
            </p>
            <p>Welcome to my Portfolio! I'm a forward-thinking engineering graduate with a diverse background and a passion for leveraging technology to drive innovation.

                My journey began with a solid foundation in engineering, where I honed my analytical and problem-solving skills. Intrigued by the power of words and ideas, I ventured into academic freelance writing, where I cultivated a knack for effective communication and research.
                
                Driven by a desire to delve deeper into the realm of technology, I embarked on a transformative path in Generative Cloud Innovative AI Engineering. Here, I immersed myself in learning JavaScript, Python, CSS, and other languages, equipping myself with the tools to navigate the dynamic landscape of artificial intelligence.
                
                My unique blend of engineering expertise, writing prowess, and tech proficiency positions me as a versatile professional ready to tackle complex challenges and drive meaningful change. Whether it's developing innovative solutions, crafting compelling narratives, or collaborating with like-minded individuals, I thrive in environments that foster creativity, growth, and collaboration.</p>
            <p></p>
        </div>

        <img src="komalk.jpeg" alt="komal" class="About-Me__img">
    </section>

    <!--work-->
    <section class="my-work" id="work">
        <h2 class="section__title section__title--work">My Work</h2>
        <p class="section__subtitle section__subtitle--work">A selection of my written codes</p>

        <div class="portfolio">
            <a href="#" class="Portfolio__item">
                <img src="work1 (1).png" alt="" class="portfolio__image">
            </a>
            <a href="#" class="Portfolio__item">
                <img src="work1 (5).png" alt="" class="portfolio__image">
            </a>
            <a href="#" class="Portfoli__item">
                <img src="work1 (2).png" alt="" class="portfolio__image">
            </a>
            <a href="#" class="Portfolio__item">
                <img src="work1 (4).png" alt="" class="portfolio__image">
            </a>
            <a href="#" class="Portfolio__item">
                <img src="work1 (3).png" alt="" class="portfolio__image">
            </a>
        </div>
    </section>

    <!--footer-->
    <footer class="footer">
        <a href="Minimalist White and Grey Professional Resume (1).pdf" class="resume">My resume to gain insights of my skills and experience</a><br>
        <a href="mailto:komalbasit2018@gmail.com" class="footer__link">komalbasit2018@gmail.com</a>
        <ul class="social-list">
            <li class="social-list__item">
                <a class=social-list__link href="https://www.linkedin.com/in/komal-basit-a92999185/"></a>
                <i class="fa-brands fa-linkedin"></i>
            </li>
            <li class="social-list__item">
                <a class=social-list__link href="https://github.com/komalb19"></a>
                <i class="fa-brands fa-github"></i>
            </li>
        </ul>
    </footer>

    <script src="index.js"></script>

  </body>
</html>

