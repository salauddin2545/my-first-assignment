<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles/portfolio.css">
</head>
<body>
    <header class="main-header">
        <div class="header-logo">LOGO</div>
        <button class="menu-button">Menu</button>
    </header>
    <section class="hero-section">
        <h1 class="hero-title">Cool Dark UI Template for Webflow Agencies!</h1>
        <p class="hero-subtitle">This template instantly leveled up our presence." – Studio Vertex</p>
        <button class="primary-button">Get Started Free</button>
    </section>
    <section class="action-section">
        <div class="action-content">
            <div class="action-text-area">
                <h2 class="action-title">See it in Action</h2>
                <p class="action-description">This template instantly leveled up our presence." – Studio Vertex</p>
                <button class="primary-button">Explore More</button>
            </div>
            <div class="action-image-area">
                <img src="images/wc-mini.png" alt="Product Demo Mockup" class="action-mockup-image">
            </div>
        </div>
    </section>

    <section class="stats-section">
        <h2 class="stats-title">Joined Thousands of Productive Users</h2>
        <div class="stats-grid">
            <div class="stat-item">
                <p class="stat-number">50K</p>
                <p class="stat-label">Active Users</p>
            </div>
            <div class="stat-item">
                <p class="stat-number">2M+</p>
                <p class="stat-label">Focus Sessions</p>
            </div>
            <div class="stat-item">
                <p class="stat-number">95%</p>
                <p class="stat-label">Satisfaction Rate</p>
            </div>
        </div>
    </section>

    <section class="reviews-section">
        <h2 class="section-title">What our users say</h2>
        <div class="reviews-grid">
            <div class="review-card">
                <div class="star-rating">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
                <h3 class="review-title">Loved by Designers</h3>
                <p class="review-quote">"This template instantly leveled up our presence."</p>
                <p class="review-source">~ Studio Vertex</p>
                <div class="reviewer-info">
                    <img src="images/avatar.png" alt="Reviewer Avatar" class="reviewer-avatar">
                    <div class="reviewer-details">
                        <p class="reviewer-name">Reviewer name</p>
                        <p class="review-date">Date</p>
                    </div>
                </div>
            </div>

            <div class="review-card">
                <div class="star-rating">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
                <h3 class="review-title">Loved by Designers</h3>
                <p class="review-quote">"This template instantly leveled up our presence."</p>
                <p class="review-source">~ Studio Vertex</p>
                <div class="reviewer-info">
                    <img src="images/avatar.png" alt="Reviewer Avatar" class="reviewer-avatar">
                    <div class="reviewer-details">
                        <p class="reviewer-name">Reviewer name</p>
                        <p class="review-date">Date</p>
                    </div>
                </div>
            </div>

            <div class="review-card">
                <div class="star-rating">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                </div>
                <h3 class="review-title">Loved by Designers</h3>
                <p class="review-quote">"This template instantly leveled up our presence."</p>
                <p class="review-source">~ Studio Vertex</p>
                <div class="reviewer-info">
                    <img src="images/avatar.png" alt="Reviewer Avatar" class="reviewer-avatar">
                    <div class="reviewer-details">
                        <p class="reviewer-name">Reviewer name</p>
                        <p class="review-date">Date</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="focus-section">
        <h2 class="section-heading">Ready to focus better</h2>
        <p class="section-subtext">This template instantly leveled up our presence." – Studio Vertex</p>
        <button class="primary-button">Get Started Free</button>

        <div class="image-mockup">
            <img src="images/wc-big.png" alt="Webflow Conf 2022 Screenshot">
        </div>
    </section>

    <section class="contact-section">
        <div class="left-side">
            <h1 class="main-heading">Let's Get in Touch</h1>
        </div>
        <div class="right-side">
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="email">Email</label>
                    <input type="email" id="email" name="email" placeholder="example@email.com" required>
                </div>
                <div class="form-group">
                    <label for="name">Name</label>
                    <input type="text" id="name" name="name" placeholder="full name" required>
                </div>
                <div class="form-group">
                    <label for="message">Message</label>
                    <textarea id="message" name="message" rows="5" placeholder="write your message...."
                        required></textarea>
                </div>
                <button type="submit" class="submit-button">Get in Touch</button>
            </form>
        </div>
    </section>

    <footer class="main-footer">
        <div class="footer-content">
            <div class="footer-logo">LOGO</div>
            <p class="footer-description">
                Ready to elevate your online presence? Contact us today to discuss
                your project and discover how we can bring your vision to life.
            </p>
            <nav class="footer-nav">
                <ul>
                    <li><a href="#">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">How it Works</a></li>
                    <li><a href="#">Services</a></li>
                </ul>
            </nav>
        </div>
    </footer>
</body>
</html>
