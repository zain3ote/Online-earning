# Online-earning
Online earn platform 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EarnOnline - Make Money From Home</title>
    <link rel="stylesheet" href="/css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <nav>
                <div class="logo">
                    <h1>Earn<span>Online</span></h1>
                    <p>Make money from home</p>
                </div>
                <ul class="nav-links">
                    <li><a href="/">Home</a></li>
                    <li><a href="#how-it-works">How It Works</a></li>
                    <li><a href="#features">Features</a></li>
                    <% if (user) { %>
                        <li><a href="/dashboard" class="btn">Dashboard</a></li>
                    <% } else { %>
                        <li><a href="/login" class="btn">Login</a></li>
                        <li><a href="/signup" class="btn btn-primary">Sign Up</a></li>
                    <% } %>
                </ul>
            </nav>
            
            <div class="hero">
                <div class="hero-content">
                    <h1>Start Earning Money Online Today!</h1>
                    <p>Complete simple tasks, surveys and get paid directly to your JazzCash account</p>
                    <div class="hero-buttons">
                        <a href="<%= user ? '/dashboard' : '/signup' %>" class="btn btn-primary btn-large">Get Started</a>
                        <a href="#how-it-works" class="btn btn-outline">Learn More</a>
                    </div>
                </div>
                <div class="hero-image">
                    <img src="/images/earning.png" alt="Online Earning">
                </div>
            </div>
        </div>
    </header>

    <section class="stats">
        <div class="container">
            <div class="stat-item">
                <h3>500K+</h3>
                <p>Users Earning</p>
            </div>
            <div class="stat-item">
                <h3>10M+</h3>
                <p>PKR Paid Out</p>
            </div>
            <div class="stat-item">
                <h3>50+</h3>
                <p>Daily Surveys</p>
            </div>
            <div class="stat-item">
                <h3>24/7</h3>
                <p>Support</p>
            </div>
        </div>
    </section>

    <section id="how-it-works" class="how-it-works">
        <div class="container">
            <h2>How It Works</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-icon">1</div>
                    <h3>Sign Up</h3>
                    <p>Create your free account in just 30 seconds</p>
                </div>
                <div class="step">
                    <div class="step-icon">2</div>
                    <h3>Complete Tasks</h3>
                    <p>Take surveys, watch videos or complete offers</p>
                </div>
                <div class="step">
                    <div class="step-icon">3</div>
                    <h3>Earn Money</h3>
                    <p>Get paid for each completed task</p>
                </div>
                <div class="step">
                    <div class="step-icon">4</div>
                    <h3>Withdraw</h3>
                    <p>Cash out to your JazzCash anytime</p>
                </div>
            </div>
        </div>
    </section>

    <section id="features" class="features">
        <div class="container">
            <h2>Why Choose EarnOnline?</h2>
            <div class="feature-grid">
                <div class="feature-card">
                    <i class="fas fa-wallet"></i>
                    <h3>Instant Withdrawals</h3>
                    <p>Get your money in your JazzCash account within minutes</p>
                </div>
                <div class="feature-card">
                    <i class="fas fa-users"></i>
                    <h3>Referral Program</h3>
                    <p>Earn 10% of your referrals' earnings for life</p>
                </div>
                <div class="feature-card">
                    <i class="fas fa-tasks"></i>
                    <h3>Daily Tasks</h3>
                    <p>New earning opportunities added every day</p>
                </div>
                <div class="feature-card">
                    <i class="fas fa-headset"></i>
                    <h3>24/7 Support</h3>
                    <p>Our team is always ready to help you</p>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-about">
                    <h3>EarnOnline</h3>
                    <p>The easiest way to make money online in Pakistan. Join thousands of users earning daily.</p>
                </div>
                <div class="footer-links">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="/">Home</a></li>
                        <li><a href="/dashboard">Dashboard</a></li>
                        <li><a href="/withdraw">Withdraw</a></li>
                        <li><a href="/surveys">Surveys</a></li>
                    </ul>
                </div>
                <div class="footer-contact">
                    <h3>Contact Us</h3>
                    <p><i class="fas fa-envelope"></i> support@earnonline.com</p>
                    <p><i class="fas fa-phone"></i> +92 300 1234567</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 EarnOnline. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script src="/js/main.js"></script>
</body>
</html>
