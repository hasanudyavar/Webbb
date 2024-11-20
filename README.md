<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Makeup Paradise</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            background-color: #ffe6f2;
            font-family: 'Raleway', sans-serif;
        }

        h1, h2, h3, h4 {
            font-family: 'Playfair Display', serif;
        }

        a:hover, button:hover {
            color: #fff;
            background-color: #ff0000;
            transition: all 0.3s ease;
        }

        .hero-section {
            position: relative;
            background: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTrqN2GBS6XkpiWP6Nk6pX-pBQBHT3_9UungA&usqp=CAU') center/cover no-repeat;
            height: 100vh;
            color: #fff;
        }

        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.5);
            z-index: 1;
        }

        .hero-content {
            position: relative;
            z-index: 2;
            text-align: center;
            top: 50%;
            transform: translateY(-50%);
        }

        .about-us, .photos, .testimonials, .blog, .contact {
            padding: 50px 15px;
        }

        .parallax {
            background: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTxBFMSy6vaBj15eWNakkzH2gnefuCunNraqw&usqp=CAU') center/cover no-repeat;
            height: 300px;
            color: #fff;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .testimonial {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            margin-bottom: 20px;
        }

        .card:hover {
            transform: scale(1.05);
            transition: 0.3s;
        }

        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        footer .social-icons a {
            color: #fff;
            margin: 0 10px;
            font-size: 20px;
        }

        footer .social-icons a:hover {
            color: #ff0000;
        }
    </style>
</head>

<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Makeup Paradise</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#hero">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="#about">About Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="#photos">Photos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#testimonials">Testimonials</a></li>
                    <li class="nav-item"><a class="nav-link" href="#blog">Blog</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="hero" class="hero-section">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <h1>Welcome to Makeup Paradise</h1>
            <p>Your beauty, our passion.</p>
            <button class="btn btn-outline-light">Shop Now</button>
        </div>
    </section>

    <!-- About Us -->
    <section id="about" class="about-us text-center">
        <div class="container">
            <h2>About Us</h2>
            <p>We provide top-quality makeup products tailored to your beauty needs. Our mission is to empower everyone to feel confident and radiant.</p>
        </div>
    </section>

    <!-- Parallax -->
    <div class="parallax">
        <h2>Enhance Your Beauty</h2>
    </div>

    <!-- Gallery -->
    <section id="photos" class="photos">
        <div class="container">
            <h2 class="text-center">Our Gallery</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRfYZLjOCZy4j9f1tnBMso5-2a57PdjRfbUg&usqp=CAU" class="card-img-top" alt="Makeup Item">
                        <div class="card-body">
                            <p class="card-text">Beautiful lipsticks for every occasion.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://cdn.fynd.com/v2/falling-surf-7c8bb8/fyprod/wrkr/products/pictures/item/free/original/000000000494274146/A1fynYwKkG-000000000494274146_1.png" class="card-img-top" alt="Makeup Item">
                        <div class="card-body">
                            <p class="card-text">Luxurious foundations for flawless skin.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://images-cdn.ubuy.co.in/633e71fbb51000174d530de3-rare-beauty-discovery-eyeshadow-palette.jpg" class="card-img-top" alt="Makeup Item">
                        <div class="card-body">
                            <p class="card-text">Vibrant eyeshadow palettes for every look.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="testimonials bg-light text-center">
        <div class="container">
            <h2>What Our Customers Say</h2>
            <div class="row">
                <div class="col-md-6">
                    <div class="testimonial">
                        <p>"Amazing quality! Highly recommend. My skin feels amazing with their foundation!"</p>
                        <strong>- Jane Doe</strong>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="testimonial">
                        <p>"I loved their lipsticks! They are so smooth and long-lasting. A must-have in my makeup bag!"</p>
                        <strong>- Sarah Smith</strong>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Blog -->
    <section id="blog" class="blog text-center">
        <div class="container">
            <h2>Latest from Our Blog</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQW3z-9yHV36741zv7EYIYpKy1crngkfLXTkQ&usqp=CAU" class="card-img-top" alt="Blog">
                        <div class="card-body">
                            <h5 class="card-title">5 Tips for Long-Lasting Makeup</h5>
                            <p class="card-text">Learn how to keep your makeup fresh all day long.</p>
                            <a href="#" class="btn btn-primary">Read More</a>
                        </div>
                    </div>
                </div>
                <!-- Add more blog posts as needed -->
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact bg-light text-center">
        <div class="container">
            <h2>Contact Us</h2>
            <form>
                <input type="text" class="form-control" placeholder="Name" required>
                <input type="email" class="form-control" placeholder="Email" required>
                <textarea class="form-control" placeholder="Message" rows="4" required></textarea>
                <button type="submit" class="btn btn-dark">Submit</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Makeup Paradise. All rights reserved.</p>
        <div class="social-icons">
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
