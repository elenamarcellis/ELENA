# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elena Marcellis | Web Design & SEO</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Space+Mono&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <nav>
        <div class="container">
            <a href="#" class="logo">EM</a>
            <div class="nav-links">
                <a href="#work">Work</a>
                <a href="#services">Services</a>
                <a href="#contact">Contact</a>
            </div>
        </div>
    </nav>

    <section class="hero">
        <div class="container">
            <h1 class="hero-title">
                <span class="line">DESIGN</span>
                <span class="line">DEVELOP</span>
                <span class="line accent">DOMINATE.</span>
            </h1>
            <p class="hero-sub">Full‑cycle web solutions — from logo to SEO to ongoing care. Based in Chicago, serving worldwide.</p>
            <a href="#contact" class="btn">GET YOUR FREE SITE AUDIT →</a>
        </div>
    </section>

    <section id="services" class="services">
        <div class="container">
            <h2 class="section-title">WHAT I DO</h2>
            <div class="services-grid">
                <div class="service-card">
                    <i class="fas fa-palette"></i>
                    <h3>Logo & Brand Identity</h3>
                    <p>Distinct visual identities that communicate your essence.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-code"></i>
                    <h3>Web Design & Dev</h3>
                    <p>Custom, responsive websites built for performance and beauty.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-chart-line"></i>
                    <h3>SEO That Ranks</h3>
                    <p>On‑page, technical, and content SEO to increase visibility.</p>
                </div>
                <div class="service-card">
                    <i class="fas fa-sync-alt"></i>
                    <h3>Ongoing Management</h3>
                    <p>Updates, backups, security — so you can focus on your business.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="work" class="work">
        <div class="container">
            <h2 class="section-title">SELECTED WORK</h2>
            <div class="work-grid">
                <div class="work-card">
                    <div class="work-img"></div>
                    <h3>Project Alpha</h3>
                    <p>Brand + website for a tech startup.</p>
                    <span class="tag">+200% Organic Traffic</span>
                </div>
                <div class="work-card">
                    <div class="work-img"></div>
                    <h3>Project Beta</h3>
                    <p>E‑commerce redesign with SEO overhaul.</p>
                    <span class="tag">+40% Conversions</span>
                </div>
                <div class="work-card">
                    <div class="work-img"></div>
                    <h3>Project Gamma</h3>
                    <p>Full‑stack web app with custom backend.</p>
                    <span class="tag">Load Time ‑60%</span>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">LET'S BUILD SOMETHING CRAZY</h2>
            <p class="contact-sub">Ready to turn your website into a growth engine?</p>
            <div class="contact-info">
                <p><i class="fas fa-map-marker-alt"></i> Chicago, IL 60607</p>
                <p><i class="fas fa-envelope"></i> elenamarcellis001@gmail.com</p>
                <p><i class="fas fa-clock"></i> Response time: < 24 hours</p>
            </div>
            <form class="contact-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <textarea placeholder="Tell me about your project..." rows="4" required></textarea>
                <button type="submit" class="btn">SEND MESSAGE</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 Elena Marcellis. All rights reserved.</p>
            <p>Hand‑coded with rage and passion.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
