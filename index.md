<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mark Erwin Serna</title>
    <meta name="description" content="inspired front-end developer with more than two years of experience in the field of web development">
    
    <meta property="og:title" content="Mark Erwin Serna">
    <meta property="og:description" content="inspired front-end developer with more than two years of experience in the field of web development">
    <meta property="og:image" content="/assets/imgs/avatar.png">


    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css"
        integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
    <link rel="stylesheet" href="assets/css/main.css">

    <link rel="preload" href="assets/fonts/Gotham/GothamBook.ttf" as="font" type="font/ttf" crossorigin="anonymous">
    <link rel="preload" href="assets/fonts/Gotham/GothamBold.ttf" as="font" type="font/ttf" crossorigin="anonymous">
    <link rel="preload" href="assets/fonts/Gotham/GothamLight.ttf" as="font" type="font/ttf" crossorigin="anonymous">

    <style>
        @font-face {
            font-family: 'Gotham';
            src: url('assets/fonts/Gotham/GothamBook.ttf');
            font-display: swap;
        }
        @font-face {
            font-family: 'Gotham Bold';
            src: url('assets/fonts/Gotham/GothamBold.ttf');
            font-display: swap;
        }

        @font-face {
            font-family: 'Gotham Light';
            src: url('assets/fonts/Gotham/GothamLight.ttf');
            font-display: swap;
        }
    </style>

</head>

<body>

    <header>
        <div class="container">
            <nav class="navbar navbar-expand-lg navbar-light">
                <a class="navbar-brand text-primary" href="#">
                    <h1 class="logo">MES</h1>
                </a>
                <button class="navbar-toggler" type="button" data-toggle="collapse"
                    data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#works">Works</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link cta" href="#contact">Contact</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
    </header>

    <section class="intro-block">
        <div class="container text-center">
            <h2 class="section-title">
                I'm a <span class="text-primary">frontend developer</span>, with +2 years of experience
            </h2>
        </div>
    </section>

    <section class="about-block" id="about">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <p>Hi! I'm Mark Erwin, inspired front-end developer with more than two years of experience building
                        and maintaining responsive websites, mobile apps, content management systems and progressive web
                        apps.</p>
                    <p>Proficient in responsive web design, mobile first approach principle and translating mockups to
                        interactive web and mobile applications. </p>
                    <a href="assets/pdf/resume.pdf" target="_blank" rel="noopener" class="btn btn-dark">Download CV</a>
                </div>
                <div class="offset-md-1 col-md-5 d-flex align-items-center justify-content-center">
                    <img src="assets/imgs/avatar.png" alt="Mark Erwin Avatar" style="max-width: 400px;">
                </div>
            </div>
        </div>
    </section>

    <section class="works-block" id="works">
        <div class="container">
            <h3 class="text-center">My Recent Works</h3>
            <p class="section-description">Here are a few website projects I've worked on recently.</p>
            <div class="row">
                <div class="col-md-6">
                    <div class="project">
                        <figure class="gmgvisasolutions">
                            <div class="overlay-container entry-media d-flex align-items-center justify-content-center">
                                <img src="assets/imgs/gmgvisasolutions.png" alt="GMG Visa Solutions">
                            </div>
                            <figcaption class="overlay-container d-flex align-items-center justify-content-center">
                                <p>Immigration & naturalization service in Blakeview, South Australia</p>
                                <a href="https://gmgvisasolutions.com.au/" target="_blank" rel="noopener"
                                    class="btn btn-outline-light">Visit Website</a>
                            </figcaption>
                        </figure>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="project">
                        <figure class="moggvisuals">
                            <div class="overlay-container entry-media d-flex align-items-center justify-content-center">
                                <img src="assets/imgs/moggvisuals.png" alt="Mogg Visuals">
                            </div>
                            <figcaption class="overlay-container d-flex align-items-center justify-content-center">
                                <p>Adelaide videographer for your weddings, events, promotions and vlogs.</p>
                                <a href="https://moggvisuals.com.au/" target="_blank" rel="noopener"
                                    class="btn btn-outline-light">Visit Website</a>
                            </figcaption>
                        </figure>
                    </div>
                </div>
            </div>
            <p class="text-muted text-center px-md-5 mt-2">These websites are made with love using frontend technologies such as HTML, SCSS, jQuery and PHP.</p>
        </div>
    </section>

    <section class="contact-block" id="contact">
        <div class="container">
            <div class="row">
                <div class="col-md-5 d-flex align-items-center justify-content-center">
                    <img src="assets/imgs/avatar-2.png" alt="Avatar 2" style="max-width: 400px;">
                </div>
                <div class="col-md-6 offset-md-1 offset-lg-0">
                    <h3>Contact</h3>
                    <div class="contact-item">
                        <i class="custom-icon-envelope"></i>
                        <div>
                            <h4>Email</h4>
                            <p><a href="mailto:markerwin.serna@gmail.com">markerwin.serna@gmail.com</a></p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="custom-icon-phone"></i>
                        <div>
                            <h4>Contact</h4>
                            <p><a href="tel:+639954196573">+63 995 4196 573</a></p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <i class="custom-icon-linkedin"></i>
                        <div>
                            <h4>LinkedIn</h4>
                            <p><a href="https://www.linkedin.com/in/markerwinserna/" target="_blank"
                                    rel="noopener">markerwinserna</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container text-center">
            <div class="copyright">
                Copyright ?? <span id="year"></span> All rights reserved.
            </div>
        </div>
    </footer>

    <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"
        integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n"
        crossorigin="anonymous"></script>

    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"
        integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6"
        crossorigin="anonymous"></script>

</body>
<script>
    $(function () {
        $('#year').text(new Date().getFullYear());
    });
</script>

</html>
