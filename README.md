<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PixelCut | Premium Video Editing</title>
    <link rel="stylesheet" href="styles/main.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&family=Orbitron:wght@500&display=swap" rel="stylesheet">
</head>
<body>
    <div class="cursor-trail"></div>
    
    <header>
        <div class="container">
            <a href="#" class="logo">
                <img src="images/logo.svg" alt="PixelCut Logo">
                <span>PixelCut</span>
            </a>
            
            <nav>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#portfolio">Portfolio</a></li>
                    <li><a href="#pricing">Pricing</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact" class="cta-button">Get Started</a></li>
                </ul>
            </nav>
            
            <div class="mobile-menu-toggle">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </header>
    
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <h1>Transform Your <span class="highlight">Vision</span> Into Stunning Videos</h1>
                <p>Professional video editing services that elevate your content with cinematic quality and creative flair.</p>
                <a href="#contact" class="cta-button pulse">Start Your Project</a>
            </div>
            
            <div class="hero-media">
                <div class="video-player-3d">
                    <div class="screen"></div>
                    <div class="base"></div>
                </div>
            </div>
        </div>
        
        <div class="floating-3d-elements">
            <div class="cube"></div>
            <div class="pyramid"></div>
            <div class="sphere"></div>
        </div>
    </section>
    
    <section id="services" class="services">
        <div class="container">
            <h2>Our <span class="highlight">Services</span></h2>
            
            <div class="services-grid">
                <div class="service-card">
                    <div class="icon-3d">
                        <div class="film-reel"></div>
                    </div>
                    <h3>Basic Editing</h3>
                    <p>Clean cuts, transitions, and audio balancing for polished content.</p>
                </div>
                
                <div class="service-card">
                    <div class="icon-3d">
                        <div class="color-wheel"></div>
                    </div>
                    <h3>Color Grading</h3>
                    <p>Cinematic color correction to set the perfect mood and tone.</p>
                </div>
                
                <div class="service-card">
                    <div class="icon-3d">
                        <div class="motion-graphic"></div>
                    </div>
                    <h3>Motion Graphics</h3>
                    <p>Animated titles, lower thirds, and dynamic elements.</p>
                </div>
                
                <div class="service-card">
                    <div class="icon-3d">
                        <div class="vfx"></div>
                    </div>
                    <h3>Visual Effects</h3>
                    <p>Green screen compositing and special effects integration.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section id="portfolio" class="portfolio">
        <div class="container">
            <h2>Recent <span class="highlight">Projects</span></h2>
            
            <div class="portfolio-grid">
                <!-- Portfolio items would be added here -->
            </div>
        </div>
    </section>
    
    <section id="contact" class="contact">
        <div class="container">
            <h2>Ready to <span class="highlight">Elevate</span> Your Content?</h2>
            
            <form class="contact-form">
                <div class="form-group">
                    <input type="text" placeholder="Your Name" required>
                </div>
                <div class="form-group">
                    <input type="email" placeholder="Your Email" required>
                </div>
                <div class="form-group">
                    <textarea placeholder="Tell us about your project" required></textarea>
                </div>
                <button type="submit" class="cta-button">Send Request</button>
            </form>
        </div>
    </section>
    
    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-col">
                    <h3>PixelCut</h3>
                    <p>Transforming visions into visual masterpieces through expert video editing.</p>
                </div>
                
                <div class="footer-col">
                    <h4>Quick Links</h4>
                    <ul>
                        <li><a href="#services">Services</a></li>
                        <li><a href="#portfolio">Portfolio</a></li>
                        <li><a href="#pricing">Pricing</a></li>
                        <li><a href="#about">About</a></li>
                    </ul>
                </div>
                
                <div class="footer-col">
                    <h4>Connect</h4>
                    <ul class="social-links">
                        <li><a href="#">Instagram</a></li>
                        <li><a href="#">YouTube</a></li>
                        <li><a href="#">Twitter</a></li>
                        <li><a href="#">LinkedIn</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="footer-bottom">
                <p>&copy; 2023 PixelCut Video Editing. All rights reserved.</p>
            </div>
        </div>
    </footer>
    
    <script src="js/main.js"></script>
</body>
</html>