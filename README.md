<html class="no-js" lang="en">

<head>
    <meta charset="utf-8">
    <title>Atlass Innovations</title>
    <meta content="width=device-width, initial-scale=1.0" name="viewport">
    <meta name="keywords"
        content="IT solutions, software engineering, web design, graphic design, technology consulting, IT services Nigeria, global IT company, software development, digital transformation, IT consulting, tech solutions, cloud services, cybersecurity, mobile app development, IT infrastructure, Nigerian tech company, global IT solutions">
    <meta name="description"
        content="Leading Nigerian-based IT company providing cutting-edge software engineering, web and graphic design, network engineering, and comprehensive IT solutions. We partner with clients globally to deliver innovative technology services, digital transformation, and scalable IT infrastructure. Your trusted partner for all things IT.">

    <!-- Favicon -->
    <link rel="apple-touch-icon" sizes="180x180" href="/Assets/images/favicon folder/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/Assets/images/favicon folder/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/Assets/images/favicon folder/favicon-16x16.png">
    <link rel="manifest" href="/Assets/images/favicon folder/site.webmanifest">
    <link rel="shortcut icon" href="/Assets/images/favicon folder/favicon.ico" type="image/x-icon">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css?family=Inconsolata:400,700|Open+Sans:300,400,600&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <!-- Libraries CSS -->
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.0/css/all.min.css" rel="stylesheet">
    <link href="lib/lightbox/css/lightbox.min.css" rel="stylesheet">

    <!-- Main Stylesheet -->
    <link href="./css/style.css" rel="stylesheet">
</head>
<style>
    /**************************************/
/************ General CSS *************/
/**************************************/
body {
    color: #555555;
    font-family: 'Open Sans', sans-serif;
    background: #ffffff;
}

a {
    color: #61daff;
    transition: 0.3s;
}

a:hover,
a:active,
a:focus {
    color: #666666;
    outline: none;
    text-decoration: none;
}

p {
    color: #555555;
    font-weight: 400;
    padding: 0;
    margin: 0 0 15px 0;
}

h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: 'Inconsolata', monospace;
    font-weight: 700;
    color: #666666;
    margin: 0 0 15px 0;
    padding: 0;
}

h4,
h5,
h6 {
    font-weight: 400;
}

img {
    border-radius: 4px;
}



/**************************************/
/********** Back to Top CSS ***********/
/**************************************/
.back-to-top {
    position: fixed;
    display: none;
    background: #111111;
    width: 45px;
    height: 45px;
    text-align: center;
    line-height: 45px;
    font-size: 35px;
    right: 15px;
    bottom: 15px;
    border-radius: 4px;
    transition: all 0.3s;
    z-index: 9;
}

.back-to-top i {
    color: #61daff;
}

.back-to-top:hover {
    background: #61daff;
}

.back-to-top:hover i {
    color: #ffffff;
}


/**************************************/
/************** Nav CSS ***************/
/**************************************/
#nav {
    position: fixed;
    top: 0;
    width: 100%;
    height: 100px;
    padding: 20px 0;
    background: transparent;
    border-bottom: 1px solid #61daff;
    transition: all .3s;
    z-index: 999;
}

#nav.nav-sticky {
    height: inherit;
    padding: 0;
    background: #ffffff;
    transition: all .3s;
    border-bottom: none;
    box-shadow: 0 2px 5px rgba(0, 0, 0, .3);
}

#nav .navbar {
    transition: all .3s;
    background: transparent !important;
}

#nav.nav-sticky .navbar {
    transition: all .3s;
    background: #ffffff !important;
}

#nav .navbar-brand {
    font-size: 35px;
    font-weight: 700;
    line-height: 0;
    font-family: 'Inconsolata', monospace;
}

#nav .nav-link,
#nav .nav-link:focus,
#nav .nav-link:hover,
#nav .nav-link.active {
    color: #21abc4;
}

#nav.nav-sticky .nav-link,
#nav.nav-sticky .nav-link:focus,
#nav.nav-sticky .nav-link:hover,
#nav.nav-sticky .nav-link.active {
    color: #666666;
}

#nav .nav-link:hover,
#nav .nav-link.active {
    color: #111111;
}

#nav.nav-sticky .nav-link:hover,
#nav.nav-sticky .nav-link.active {
    color: #61daff;
}

#nav .dropdown-menu {
    margin-top: 0;
    border: 0;
    border-radius: 0;
    background: #f8f9fa;
}

#nav .navbar-logo {
    height: 40px;
    width: auto;
    max-width: 150px;
}

#nav .navbar-brand {
    display: flex;
    align-items: center;
}


@media (max-width: 768px) {

    #nav,
    #nav .container,
    #nav .navbar {
        background: #ffffff !important;
    }

    #nav .navbar-logo {
        height: 30px;
        max-width: 120px;
    }

    #nav .nav-link,
    #nav .nav-link:focus,
    #nav .nav-link:hover,
    #nav .nav-link.active {
        color: #666666;
    }

    #nav .nav-link:hover,
    #nav .nav-link.active {
        color: #4F84C4;
    }
}



/**************************************/
/************* Header CSS *************/
/**************************************/
.header {
    position: relative;
    padding: 180px 0 100px 0;
    text-align: center;
    background: linear-gradient(hwb(184 38% 0% / 0.95), rgba(71, 230, 230, 0.95)), url(/Assets/images/header.jpg) no-repeat top center;
    background-size: cover;
}

.header h1 {
    position: relative;
    display: inline-block;
    color: #ffffff;
    font-size: 80px;
    font-weight: 700;
    text-transform: uppercase;
    margin-bottom: 40px;
    padding-bottom: 45px;
}

.header h1 span {
    color: #111111;
}

.header h1::after {
    position: absolute;
    content: "";
    width: 90%;
    height: 1px;
    left: 5%;
    bottom: 0;
    background: #61daff;
}

.header p {
    color: #ffffff;
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 40px;
}

.header .btn {
    padding: 15px 35px;
    color: #61daff;
    font-size: 22px;
    font-weight: 500;
    background: #ffffff;
}

.header .btn:hover {
    background: #111111;
}

.header .btn i {
    margin-right: 5px;
}

@media(max-width: 767.98px) {
    .header h1 {
        font-size: 60px;
    }

    .header p {
        font-size: 25px;
    }
}

@media(max-width: 575.98px) {
    .header h1 {
        font-size: 40px;
    }

    .header p {
        font-size: 20px;
    }
}



/**************************************/
/******** Section Header CSS **********/
/**************************************/
.section-header {
    position: relative;
    max-width: 700px;
    margin: 0 auto 60px auto;
    text-align: center;
}

.section-header h4 {
    color: #61daff;
    font-size: 18px;
    letter-spacing: 3px;
    margin-bottom: 5px;
}

.section-header h2 {
    display: inline-block;
    color: #111111;
    font-size: 45px;
    text-transform: uppercase;
    letter-spacing: 5px;
}

.section-header h2::after {
    position: absolute;
    content: "";
    width: 60px;
    height: 1px;
    left: calc(50% - 30px);
    bottom: 0;
    background: #61daff;
}

@media(max-width: 767.98px) {
    .section-header h4 {
        font-size: 17px;
    }

    .section-header h2 {
        font-size: 40px;
    }
}

@media(max-width: 575.98px) {
    .section-header h4 {
        font-size: 16px;
    }

    .section-header h2 {
        font-size: 35px;
    }
}



/**************************************/
/************* About CSS **************/
/**************************************/
.about {
    position: relative;
    padding: 100px 0;
    background: #ffffff;
}

.about .about-img {
    position: relative;
    overflow: hidden;
}

.about .about-img img {
    width: 100%;
    height: 625px;
}

.about .about-content {
    position: relative;
    width: 100%;
}

.about .about-content:first-child {
    margin-bottom: 30px;
    padding-bottom: 20px;
    border-bottom: 1px solid rgba(0, 0, 0, .125);
}

.about .about-content h3 {
    font-size: 30px;
    letter-spacing: 1px;
    text-transform: capitalize;
}

.about .about-content p {
    position: relative;
    font-size: 18px;
}

.about .btn {
    position: relative;
    font-size: 14px;
    letter-spacing: 1px;
    color: #ffffff;
    background: #61daff;
}

.about .btn:hover {
    color: #61daff;
    background: #111111;
}

@media(max-width: 767.98px) {
    .about .about-img {
        margin-bottom: 30px;
    }
}



/**************************************/
/*************** Team CSS *************/
/**************************************/
.team {
    position: relative;
    padding: 100px 0 70px 0;
    background: #f6f8fa;
}

.team .team-item {
    margin-bottom: 30px;
    overflow: hidden;
}

.team .team-item .team-img {
    position: relative;
    overflow: hidden;
    border-radius: 4px;

}

.team-img {
    height: 250px;
}

.team .team-item .team-link {
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba(97, 250, 255, 0.95);
    transition: 0.3s;
    opacity: 0;
}

.team .team-item .team-link a {
    display: inline-block;
    width: 35px;
    height: 35px;
    margin: 0 2px -100px 2px;
    padding: 6px 0;
    text-align: center;
    font-size: 16px;
    color: #61daff;
    background: #ffffff;
    border-radius: 4px;
}

.team .team-item:hover .team-link {
    opacity: 1;
}

.team .team-item:hover .team-link a {
    margin: 0 2px;
}

.team .team-item .team-link a:hover {
    color: #ffffff;
    background: #111111;
}

.team .team-item .team-info {
    position: relative;
    width: 100%;
    padding-top: 15px;
}

.team .team-item .team-info h4 {
    font-size: 18px;
    margin-bottom: 10px;
}

.team .team-item .team-info p {
    margin: 0;
    font-size: 14px;
    font-weight: 300;
    text-transform: uppercase;
}



/**************************************/
/************ Services CSS ************/
/**************************************/
.service {
    position: relative;
    padding: 100px 0 40px 0;
    background: #ffffff;
}

.service .row {
    margin-bottom: 60px;
}

.service .service-img {
    position: relative;
    overflow: hidden;
}

.service .service-img img {
    width: 100%;
}

.service .service-detail h3 {
    font-size: 30px;
    letter-spacing: 1px;
    text-transform: capitalize;
}

.service .service-detail h3 i {
    margin-right: 20px;
}

@media(max-width: 767.98px) {
    .service .service-img {
        margin-bottom: 30px;
    }
}



/**************************************/
/********* Call To Action CSS *********/
/**************************************/
.call-to-action {
    position: relative;
    padding: 100px 0;
    background: #61daff;
}

.call-to-action .container {
    max-width: 700px;
}

.call-to-action .section-header h4 {
    color: #ffffff;
}

.call-to-action .section-header h2::after {
    background: #111111;
}

.call-to-action .section-header p {
    color: #ffffff;
}

.call-to-action .btn {
    padding: 15px 30px;
    color: #61daff;
    font-size: 18px;
    letter-spacing: 1px;
    text-transform: uppercase;
    background: #ffffff;
}

.call-to-action .btn:hover {
    color: #61daff;
    background: #111111;
}

.call-to-action .btn i {
    margin-right: 5px;
}



/**************************************/
/************ Portfolio CSS ***********/
/**************************************/
.portfolio {
    position: relative;
    padding: 100px 0 70px 0;
    background: #ffffff;
}

.portfolio .portfolio-item {
    margin-bottom: 30px;
    overflow: hidden;
}

.portfolio .portfolio-item .portfolio-img {
    position: relative;
    overflow: hidden;
    border-radius: 4px;

}

.portfolio .portfolio-item .portfolio-link {
    position: absolute;
    display: flex;
    align-items: center;
    justify-content: center;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba(97, 210, 255, 0.95);
    transition: 0.3s;
    opacity: 0;
}

.portfolio .portfolio-item .portfolio-link a {
    display: inline-block;
    width: 40px;
    height: 40px;
    margin: 0 5px -100px 5px;
    padding: 6px 0;
    text-align: center;
    font-size: 18px;
    color: #61daff;
    background: #ffffff;
    border-radius: 4px;
}

.portfolio .portfolio-item:hover .portfolio-link {
    opacity: 1;
}

.portfolio .portfolio-item:hover .portfolio-link a {
    margin: 0 5px;
}

.portfolio .portfolio-item .portfolio-link a:hover {
    color: #ffffff;
    background: #111111;
}

.portfolio .portfolio-item .portfolio-info {
    position: relative;
    width: 100%;
    padding-top: 15px;
}

.portfolio .portfolio-item .portfolio-info h4 {
    font-size: 18px;
    margin-bottom: 10px;
}

.portfolio .portfolio-item .portfolio-info p {
    margin: 0;
    font-size: 14px;
    font-weight: 300;
    text-transform: uppercase;
}



/**************************************/
/************* Pricing CSS ************/
/**************************************/
.pricing {
    position: relative;
    padding: 100px 0 70px 0;
    background: #f6f8fa;
}

.pricing .price-content {
    position: relative;
    background: #ffffff;
    text-align: center;
    margin-bottom: 30px;
    border-radius: 4px;
    overflow: hidden;
}

.pricing .price-plan {
    position: relative;
    background: #61daff;
    padding: 30px;
}

.pricing .price-plan h3 {
    color: #111111;
    font-size: 35px;
    letter-spacing: 5px;
    text-transform: uppercase;
    margin-bottom: 5px;
}

.pricing .price-plan p {
    color: #ffffff;
    font-size: 18px;
    margin-bottom: 15px;
}

.pricing .price-plan i {
    color: #ffffff;
    font-size: 45px;
}

.pricing .price-details {
    padding: 30px 0;
    font-size: 16px;
    list-style: none;
    text-align: center;
}

.pricing .price-details li {
    padding: 6px 30px;
    border-bottom: 1px solid #f6f8fa;
}

.pricing .price-details li:last-child {
    border: none;
}

.pricing .price-content .btn {
    margin-bottom: 30px;
    padding: 10px 30px;
    color: #ffffff;
    background: #61daff;
    border: none;
}

.pricing .price-content .btn:hover {
    color: #61daff;
    background: #111111;
}



/**************************************/
/************* Contact CSS ************/
/**************************************/
.contact {
    position: relative;
    padding: 30px 0;
    text-align: center;
    background: linear-gradient(rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0.7)), url(/Assets/images/contact.jpg) no-repeat top left;
}

.contact .contact-form {
    max-width: 600px;
    margin: 0 auto;
}

.contact .form-control:focus {
    border: 1px solid #61daff;
    box-shadow: none;
}

.contact .btn {
    display: block;
    width: 100%;
    color: #ffffff;
    background: #61daff;
}

.contact .btn:hover {
    color: #61daff;
    background: #111111;
}



/**************************************/
/************* Footer CSS *************/
/**************************************/
.footer {
    position: relative;
    background: #61daff;
}

.footer .footer-top {
    padding: 60px 0;
    border-bottom: 1px solid #61daff;
}

.footer .footer-top h2 {
    position: relative;
    color: #ffffff;
    font-size: 30px;
    padding-bottom: 10px;
    margin-bottom: 30px;
}

.footer .footer-top h2::after {
    position: absolute;
    content: "";
    width: 100px;
    height: 1px;
    left: 0;
    bottom: 0;
    background: #61daff;
}

.footer .contact-info h4 {
    color: #ffffff;
    font-size: 18px;
    margin-bottom: 0;
}

.footer .contact-info p {
    color: #ffffff;
    font-size: 16px;
}

.footer .contact-info p:last-child {
    margin-bottom: 0;
}

.footer .social-links a {
    display: inline-block;
    width: 45px;
    height: 45px;
    font-size: 22px;
    line-height: 1;
    padding: 11px 0;
    margin-right: 4px;
    text-align: center;
    background: #ffffff;
    color: #61daff;
    border-radius: 4px;
    transition: 0.3s;
}

.footer .social-links a:hover {
    background: #111111;
    color: #61daff;
}

.footer .subscribe {
    position: relative;
    width: 100%;
}

.footer .subscribe .form-control {
    float: left;
    width: calc(100% - 115px);
    margin-right: 15px;
    border: none;
}

.footer .subscribe .form-control:focus {
    box-shadow: none;
    color: #ffffff;
    background: #111111;
}

.footer .subscribe .btn {
    width: 100px;
    color: #61daff;
    background: #111111;
}

.footer .subscribe .btn:hover {
    color: #61daff;
    background: #ffffff;
}

.footer .subscribe label {
    margin-top: 5px;
    font-size: 14px;
    color: #ffffff;
}

.footer .footer-bottom {
    padding: 30px 0;
}

.footer .copyright {
    color: #ffffff;
    text-align: left;
}

.footer .credit {
    color: #ffffff;
    text-align: right;
}

.footer .copyright a,
.footer .credit a {
    color: #111111;
    font-weight: 600;
}

.footer .copyright a:hover,
.footer .credit a:hover {
    color: #ffffff;
}

@media (max-width: 768px) {

    .footer .contact-info,
    .footer .social-links {
        margin-bottom: 30px;
    }

    .footer .copyright,
    .footer .credit {
        text-align: center;
    }
}
</style>

<body data-spy="scroll" data-target=".navbar" data-offset="51">
    <!-- Nav Start -->
    <div id="nav">
        <div class="container">
            <nav class="navbar navbar-expand-md bg-light navbar-light">
                <div class="navbar-brand">
                    <img src="./images/Logo (1).png" alt="Website Logo" class="navbar-logo">
                </div>
                <a href="index.html" class="navbar-brand">Atlass Innovations</a>
                <button type="button" class="navbar-toggler" data-toggle="collapse" data-target="#navbarCollapse">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <div class="collapse navbar-collapse justify-content-between" id="navbarCollapse">
                    <ul class="navbar-nav ml-auto">
                        <li class="nav-item"><a href="#header" class="nav-link">Home</a></li>
                        <li class="nav-item"><a href="#about" class="nav-link">About</a></li>
                        <li class="nav-item"><a href="#team" class="nav-link">Team</a></li>
                        <li class="nav-item"><a href="#service" class="nav-link">Service</a></li>
                        <li class="nav-item"><a href="#portfolio" class="nav-link">Portfolio</a></li>
                        <li class="nav-item"><a href="#pricing" class="nav-link">Price</a></li>
                        <li class="nav-item"><a href="#contact" class="nav-link">Contact</a></li>
                    </ul>
                </div>
            </nav>
        </div>
    </div>
    <!-- Nav End -->

    <!-- Header Start-->
    <div class="header" id="header">
        <div class="container">
            <h1>Welcome to <span>Atlass Innovations</span></h1>
            <p class="hero-subtitle" >
                Where cutting-edge technology meets <span class="highlight" style="
                color: black;
                font-weight: 600;">human-centric solutions</span>
            </p>
            <a class="btn" href="javascript:viod(0)"><i class="fas fa-link"></i> Read More</a>
        </div>
    </div>
    <!-- Header End-->

    <!-- About Start-->
    <div class="about" id="about">
        <div class="container">
            <div class="section-header">
                <h4>Learn more</h4>
                <h2>About Us</h2>
            </div>
            <div class="row align-items-center">
                <div class="col-md-6">
                    <div class="about-img">
                        <img src="./images/about.jpg" alt="About Image">
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="about-content">
                        <h3>Our Story</h3>
                        <p>
                            Atlass Innovations is more than just an IT company, it's a testament to the power of vision,
                            hard work, and
                            collaboration. From its humble beginnings in Lagos Nigeria, to its global reach.
                            Atlass Innovations is proof that with the right
                            team and mindset, anything is possible. As the company continues to grow and innovate, one
                            thing is certain: the future
                            is bright for Atlass Innovations, and the world is our arena. <br>
                            <br><strong>
                                Innovate.
                                Empower. Transform. That’s the Atlass way.
                            </strong>
                        </p>
                    </div>
                    <div class="about-content">
                        <h3>Our Goal</h3>
                        <p>
                            At Atlass Innovations, our goal is to revolutionize the tech industry by delivering
                            innovative, affordable, and
                            impactful solutions that empower businesses and communities worldwide to thrive in a
                            digital-first era. <br>
                            From our roots in Lagos, Nigeria, we are committed to fostering a culture of innovation,
                            learning, and collaboration. By
                            nurturing young talent through our internship program and leveraging our global reach via
                            platforms like Upwork, we aim
                            to bridge the gap between local expertise and global opportunities.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- About End -->

    <!-- Team Start -->
    <div class="team" id="team">
        <div class="container">
            <div class="section-header text-center">
                <h4>Meet our</h4>
                <h2>Founders</h2>
            </div>

            <div class="row team-container justify-content-center">
                <div class="col-lg-3 col-md-4 col-sm-6 team-item">
                    <div class="team-img" style="position: relative;">
                        <img src="./images/Team/Franklin.png" class="img-fluid mx-auto d-block" alt="Team Image" style="display: block;">
                        <div class="team-link" style="position: absolute; inset: 0; background: rgba(71, 230, 230, 0.95); display: flex; justify-content: center; align-items: center; gap: 15px; opacity: 0; transition: opacity 0.3s ease;">
                            <a href="https://x.com/fishbone_dev" title="Twitter"><i class="fab fa-twitter"></i></a>
                            <a href="javascript:void(0)" title="Facebook"><i class="fab fa-facebook-f"></i></a>
                            <a href="javascript:void(0)" title="Linkedin"><i class="fab fa-linkedin-in"></i></a>
                            <a href="javascript:void(0)" title="Instagram"><i class="fab fa-instagram"></i></a>
                        </div>
                    </div>

                    <div class="team-info text-center">
                        <h4><strong>FRANKLIN NMAJU</strong></h4>
                        <p><strong>CO-FOUNDER/CEO</strong></p>
                    </div>
                </div>

                <div class="col-lg-3 col-md-4 col-sm-6 team-item">
                    <div class="team-img" style="position: relative;">
                        <img src="./images/Team/mama.png" class="img-fluid mx-auto d-block" alt="Team Image" style="display: block;">
                        <div class="team-link" style="position: absolute; inset: 0; background: rgba(71, 230, 230, 0.95); display: flex; justify-content: center; align-items: center; gap: 15px; opacity: 0; transition: opacity 0.3s ease;">
                            <a href="https://x.com/soy_maddiie" title="Twitter"><i class="fab fa-twitter"></i></a>
                            <a href="javascript:void(0)" title="Facebook"><i class="fab fa-facebook-f"></i></a>
                            <a href="javascript:void(0)" title="Linkedin"><i class="fab fa-linkedin-in"></i></a>
                            <a href="javascript:void(0)" title="Instagram"><i class="fab fa-instagram"></i></a>
                        </div>
                    </div>

                    <div class="team-info text-center">
                        <h4><strong>MAGDALENE DIM</strong></h4>
                        <p><strong>CO-FOUNDER/COO</strong></p>
                    </div>
                </div>

                <div class="col-lg-3 col-md-4 col-sm-6 team-item">
                    <div class="team-img" style="position: relative;">
                        <img src="./images/Team/Olamide.png" class="img-fluid mx-auto d-block" alt="Team Image" style="display: block;">
                        <div class="team-link" style="position: absolute; inset: 0; background: rgba(71, 230, 230, 0.95); display: flex; justify-content: center; align-items: center; gap: 15px; opacity: 0; transition: opacity 0.3s ease;">
                            <a href="https://x.com/0xDeemah" title="Twitter"><i class="fab fa-twitter"></i></a>
                            <a href="javascript:void(0)" title="Facebook"><i class="fab fa-facebook-f"></i></a>
                            <a href="javascript:void(0)" title="Linkedin"><i class="fab fa-linkedin-in"></i></a>
                            <a href="javascript:void(0)" title="Instagram"><i class="fab fa-instagram"></i></a>
                            </div>
                        </div>

                        <div class="team-info text-center">
                            <h4><strong>OLAMIDE AHMED</strong></h4>
                            <p><strong>CO-FOUNDER/CTO</strong></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <style>
        .team-img {
            display: inline-block;
            /* Ensures proper sizing */
        }
    
        .team-img:hover .team-link {
            opacity: 1 !important;
        }
    
        .team-img img {
            width: 100%;
            height: auto;
            display: block;
        }
    </style>
    <!-- Team End -->

    <!-- Service Start -->
    <div class="service" id="service">
        <div class="container">
            <div class="section-header">
                <span class="glyphicon glyphicon-asterisk"></span>
                <h4>World class</h4>
                <h2>Services</h2>
            </div>
            <div class="row align-items-center">
                <div class="col-md-6">
                    <div class="service-img">
                        <img src="./images/Service/service-1.jpg" alt="Service Image">
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="service-detail">
                        <h3><i class="fas fa-laptop"></i>Web Development</h3>
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item">Responsive, SEO-friendly websites with CMS integration and fast-loading architecture.</li>
                            <li class="list-group-item">Dynamic apps using React, Node.js, and cloud solutions for scalability and performance.</li>
                            <li class="list-group-item">Seamless third-party connections with RESTful/GraphQL APIs and CRM/ERP systems.</li>
                            <li class="list-group-item">Ongoing security updates, performance tuning, and 24/7 technical assistance.</li>
                            <li class="list-group-item">Agile experts using AI/ML with security-first, high-performance solutions.</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="row align-items-center">
                <div class="col-md-6 d-md-none d-sm-block">
                    <div class="service-img">
                        <img src="./images/Service/service-2.jpg" alt="Service Image">
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="service-detail">
                        <h3><i class="fas fa-mobile-alt"></i>Apps Development</h3>
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item">High-performance iOS & Android apps with intuitive UX and scalable architecture.</li>
                            <li class="list-group-item">Flutter and React Native apps that deliver native-like experiences across all devices.</li>
                            <li class="list-group-item">Seamless connectivity with existing systems, APIs, and cloud services.</li>
                            <li class="list-group-item">Regular performance optimization, security patches, and feature enhancements.</li>
                            <li class="list-group-item">Expert developers using cutting-edge tech to deliver secure, market-ready applications.</li>
                        </ul>
                    </div>
                </div>
                <div class="col-md-6 d-sm-none d-md-block">
                    <div class="service-img">
                        <img src="./images/Service/service-2.jpg" alt="Service Image">
                    </div>
                </div>
            </div>
            <div class="row align-items-center">
                <div class="col-md-6">
                    <div class="service-img">
                        <img src="./images/Service/service-3.jpg" alt="Service Image">
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="service-detail">
                        <h3><i class="fas fa-shield-alt"></i>Online Security</h3>
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item">Provision of end-to-end protection with advanced firewalls, encryption, and threat monitoring.</li>
                            <li class="list-group-item">Comprehensive vulnerability assessments, penetration testing, and real-time threat response.</li>
                            <li class="list-group-item">GDPR, HIPAA & PCI-DSS compliant solutions to safeguard sensitive information.</li>
                            <li class="list-group-item">Proactive detection and mitigation of cyber threats with AI-driven systems.</li>
                            <li class="list-group-item">Certified experts delivering ironclad security tailored to your business needs.</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="row align-items-center">
                <div class="col-md-6 d-md-none d-sm-block">
                    <div class="service-img">
                        <img src="./images/Service/service-4.jpg" alt="Service Image">
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="service-detail">
                        <h3><i class="fas fa-envelope-open-text"></i>Digital Marketing</h3>
                        <ul class="list-group list-group-flush">
                            <li class="list-group-item">Boost visibility with SEO, PPC, and social media strategies that drive conversions.</li>
                            <li class="list-group-item">Engaging campaigns across blogs, videos, and email for maximum audience reach.</li>
                            <li class="list-group-item">Precision-targeted ads using analytics and AI for higher ROI.</li>
                            <li class="list-group-item">Crafting compelling narratives to build trust and loyalty.</li>
                            <li class="list-group-item">Results-focused strategies that scale your business and outperform competitors.</li>
                        </ul>
                    </div>
                </div>
                <div class="col-md-6 d-sm-none d-md-block">
                    <div class="service-img">
                        <img src="./images/Service/service-4.jpg" alt="Service Image">
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Service End -->

    <!-- Call To Action Start -->
    <div class="call-to-action">
        <div class="container text-center">
            <div class="section-header">
                <h4>Call to action</h4>
                <h2>Call us</h2>
            </div>
            <a class="btn" href="javascript:void(0)"><i class="fas fa-phone-alt"></i>Click to Call</a>
        </div>
    </div>
    <!-- Call To Action End -->

    <!-- Portfolio Start -->
    <div class="portfolio" id="portfolio">
        <div class="container">
            <div class="section-header">
                <h4>Creative</h4>
                <h2>Portfolio</h2>
            </div>

            <div class="row portfolio-container">
                <div class="col-lg-4 col-md-6 portfolio-item">
                    <div class="portfolio-img">
                        <img src="./images/Portfolio/kiddies.jpg" class="img-fluid" alt="Portfolio">
                        <div class="portfolio-link">
                            <a href="./images/Portfolio/kiddies.jpg" data-lightbox="portfolio" data-title="An ecommerce website for kids."
                                title="Preview"><i class="fas fa-eye"></i></a>
                            <a href="https://0xolami.github.io/Kiddies-Store/" title="More Details"><i class="fas fa-link"></i></a>
                        </div>
                    </div>

                    <div class="portfolio-info">
                        <h4>Kiddies Store; An ecommerce website for kids.</h4>
                        <h3>Web Design</h3>
                    </div>
                </div>

                <div class="col-lg-4 col-md-6 portfolio-item">
                    <div class="portfolio-img">
                        <img src="./images/Portfolio/Moviesite.jpg" class="img-fluid" alt="Portfolio">
                        <div class="portfolio-link">
                            <a href="./images/Portfolio/Moviesite.jpg" data-lightbox="portfolio"
                                data-title="A movie streaming website." title="Preview"><i class="fas fa-eye"></i></a>
                            <a href="https://gentlefrank.github.io/moviewebsite/index.html" title="More Details"><i class="fas fa-link"></i></a>
                        </div>
                    </div>

                    <div class="portfolio-info">
                        <h4>Ozone HD; A movie streaming website.</h4>
                        <h3>Web Development</h3>
                    </div>
                </div>

                <div class="col-lg-4 col-md-6 portfolio-item">
                    <div class="portfolio-img">
                        <img src="./images/Portfolio/Productdesign 1.jpg" class="img-fluid" alt="Portfolio">
                        <div class="portfolio-link">
                            <a href="./images/Portfolio/Productdesign 1.jpg" data-lightbox="portfolio" data-title="A food delivery app."
                                title="Preview"><i class="fas fa-eye"></i></a>
                            <a href="javascript:void(0)" title="More Details"><i class="fas fa-link"></i></a>
                        </div>
                    </div>

                    <div class="portfolio-info">
                        <h4>Mc Cripsy; A food delivery app.</h4>
                        <h3>App Design</h3>
                    </div>
                </div>

                <div class="col-lg-4 col-md-6 portfolio-item">
                    <div class="portfolio-img">
                        <img src="./images/Portfolio/Productdesign 2.jpg" class="img-fluid" alt="Portfolio">
                        <div class="portfolio-link">
                            <a href="./images/Portfolio/Productdesign 2.jpg" data-lightbox="portfolio" data-title="An ecommerce website for phones."
                                title="Preview"><i class="fas fa-eye"></i></a>
                            <a href="javascript:void(0)" title="More Details"><i class="fas fa-link"></i></a>
                        </div>
                    </div>

                    <div class="portfolio-info">
                        <h4>Store; An ecommerce website for phones.</h4>
                        <h3>Product Design</h3>
                    </div>
                </div>

                <div class="col-lg-4 col-md-6 portfolio-item">
                    <div class="portfolio-img">
                        <img src="./images/Portfolio/Traveland.png" class="img-fluid" alt="Portfolio">
                        <div class="portfolio-link">
                            <a href="./images/Portfolio/Traveland.png" data-lightbox="portfolio"
                                data-title="A travel agency website." title="Preview"><i class="fas fa-eye"></i></a>
                            <a href="https://magdalyndim.github.io/traveLand" title="More Details"><i class="fas fa-link"></i></a>
                        </div>
                    </div>

                    <div class="portfolio-info">
                        <h4>TraveLand; A travel agency website.</h4>
                        <h3>Web Development</h3>
                    </div>
                </div>

                <div class="col-lg-4 col-md-6 portfolio-item">
                    <div class="portfolio-img">
                        <img src="./img/portfolio-6.jpg" class="img-fluid" alt="Portfolio">
                        <div class="portfolio-link">
                            <a href="./img/portfolio-6.jpg" data-lightbox="portfolio" data-title="Phasellus eget dictum"
                                title="Preview"><i class="fas fa-eye"></i></a>
                            <a href="" title="More Details"><i class="fas fa-link"></i></a>
                        </div>
                    </div>

                    <div class="portfolio-info">
                        <h4>Aliquam blandit nisi</h4>
                        <p>SEO</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Portfolio End -->

    <!--Pricing start-->
    <div class="pricing" id="pricing">
        <div class="container">
            <div class="section-header">
                <h4>Creative</h4>
                <h2>Price Table</h2>
            </div>
            <div class="row">
                <div class="col-md-4">
                    <div class="price-content">
                        <div class="price-plan">
                            <h3>Basic</h3>
                            <p>For small company</p>
                            <i class="fas fa-home"></i>
                        </div>
                        <ul class="price-details">
                            <li>Website Development</li>
                            <li>Logo Design</li>
                            <li>Web Apps</li>
                            <li>Custom Banners</li>
                            <li>Maintenance (Quarterly)</li>
                            <li>Domain & Hosting Renewal (Annually)</li>
                        </ul>
                        <a href="javascript:void(0)" class="btn">Contact</a>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="price-content">
                        <div class="price-plan">
                            <h3>Standard</h3>
                            <p>For big company</p>
                            <i class="fas fa-star"></i>
                        </div>
                        <ul class="price-details">
                            <li>Website Development (5 Pages)</li>
                            <li>Product Design</li>
                            <li>Member & Admin Panels</li>
                            <li>Payment Integration</li>
                            <li>Maintenance (Quarterly)</li>
                            <li>Domain & Hosting Renewal (Annually)</li>
                        </ul>
                        <a href="javascript:void(0)" class="btn">Contact</a>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="price-content">
                        <div class="price-plan">
                            <h3>Premium</h3>
                            <p>For Large Organization</p>
                            <i class="fas fa-gift"></i>
                        </div>
                        <ul class="price-details">
                            <li>Website Development (Advanced)</li>
                            <li>Full custom Web Apps</li>
                            <li>Member & Admin Panels</li>
                            <li>Payment Integration</li>
                            <li>Maintenance (Quarterly)</li>
                            <li>Domain & Hosting Renewal (Annually)</li>
                        </ul>
                        <a href="javascript:void(0)" class="btn">Contact</a>
                    </div>
                </div>
            </div>

            <div style="max-width: 800px; margin: 0 auto;">
                <h3 style="text-align: center;">Custom Service Pricing</h3>
                <div style="display: flex; align-items: center; justify-content: space-between; gap: 20px;">
                    <p>Clients should reach out to us today for a tailored quote,  inquiries and custom pricing, highly specialized solutions and other services not listed here.</p>
                    <a href="javascript:void(0)"
                        style="background-color: #61daff; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px; font-weight: bold; white-space: nowrap; transition: background-color 0.3s ease;"
                        onmouseover="this.style.backgroundColor='#65BDC7'" onmouseout="this.style.backgroundColor= '#61daff'">Contact Us</a>
                </div>
            </div>
        </div>
    </div>
    <!--Pricing End-->

    <!-- Contact Start -->
    <div class="contact" id="contact">
        <div class="container">
            <div class="section-header">
                <h4>24/hr Support</h4>
                <h2>Contact</h2>
            </div>

            <div class="row">
                <div class="col-md-12">
                    <div class="contact-form">
                        <form>
                            <div class="form-row">
                                <div class="form-group col-sm-6">
                                    <input type="text" class="form-control" placeholder="Your Name" />
                                </div>
                                <div class="form-group col-sm-6">
                                    <input type="email" class="form-control" placeholder="Your Email" />
                                </div>
                            </div>
                            <div class="form-group">
                                <input type="text" class="form-control" placeholder="Subject" />
                            </div>
                            <div class="form-group">
                                <textarea class="form-control" rows="5" placeholder="Message"></textarea>
                            </div>
                            <div><button class="btn" type="submit" onclick="return false;">Send Message</button></div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <!-- Contact End -->

    <!-- Footer Start -->
    <div class="footer">
        <div class="container">
            <div class="row footer-top">
                <div class="col-md-4">
                    <h2>Get in Touch</h2>
                    <div class="contact-info">
                        <h4>E-mail:</h4>
                        <p>atlassinnovations@gmail.com</p>
                        <h4>Phone:</h4>
                        <p>+234 812 345 6789</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <h2>Stay connected</h2>
                    <div class="social-links">
                        <a href="https://x.com/AtlasInovations"><i class="fab fa-twitter"></i></a>
                        <a href="javascript:void(0)"><i class="fab fa-facebook-f"></i></a>
                        <a href="javascript:void(0)"><i class="fab fa-linkedin-in"></i></a>
                        <a href="javascript:void(0)"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="col-md-4">
                    <h2>Stay updated</h2>
                    <div class="subscribe">
                        <form>
                            <input type="email" class="form-control" placeholder="Your email" />
                            <button class="btn" type="submit" onclick="return false;">Submit</button>
                            <label>Don't worry we don't spam</label>
                        </form>
                    </div>
                </div>
            </div>
            <div class="row footer-bottom">
                <div class="col-md-6 copyright" style="text-align: center; width: 100%; margin: 0 auto; padding: 20px 0;">
                    Copyright &copy; 2025 Atlass Inovations. All Rights Reserved
                </div>
            </div>
        </div>
    </div>
    <!-- Footer End -->

    <a href="javascript:void(0)" class="back-to-top"><i class="fas fa-angle-up"></i></a>

    <!-- Libraries JS -->
    <script src="https://code.jquery.com/jquery-3.4.1.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
    <script src="/Assets/lib/easing/easing.min.js"></script>
    <script src="/Assets/lib/lightbox/js/lightbox.min.js"></script>

    <!-- Main Javascript -->
    <script src="/Assets/js/main.js"></script>

</body>

</html>
