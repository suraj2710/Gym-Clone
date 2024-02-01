<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Website</title>
    <style class="css"></style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <h1>Gym</h1>
            </div>
            <ul class="menu">
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <div class="container">
                <h2>Welcome to Gym</h2>
                <p>The best place to get fit and healthy</p>
                <a href="#" class="btn">Join Now</a>
            </div>
        </section>
        <section class="features">
            <div class="container">
                <h3>Why Choose Us</h3>
                <div class="grid">
                    <div class="card">
                        <img src="equipment.jpg" alt="Equipment">
                        <h4>Modern Equipment</h4>
                        <p>We have the latest and most advanced equipment to help you achieve your goals.</p>
                    </div>
                    <div class="card">
                        <img src="trainer.jpg" alt="Trainer">
                        <h4>Professional Trainers</h4>
                        <p>Our trainers are certified and experienced in various fitness disciplines.</p>
                    </div>
                    <div class="card">
                        <img src="schedule.jpg" alt="Schedule">
                        <h4>Flexible Schedule</h4>
                        <p>You can choose from a variety of classes and timings that suit your lifestyle.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="testimonials">
            <div class="container">
                <h3>What Our Clients Say</h3>
                <div class="slider">
                    <div class="slide">
                        <img src="client1.jpg" alt="Client 1">
                        <p>"I have been going to Gym for 6 months and I love it. The trainers are very helpful and motivating. I have seen great results in my body and health."</p>
                        <span>- John Doe</span>
                    </div>
                    <div class="slide">
                        <img src="client2.jpg" alt="Client 2">
                        <p>"Gym is the best place to work out. The equipment is top-notch and the classes are fun and challenging. I highly recommend it to anyone who wants to get fit."</p>
                        <span>- Jane Doe</span>
                    </div>
                    <div class="slide">
                        <img src="client3.jpg" alt="Client 3">
                        <p>"I joined Gym a year ago and I never looked back. The trainers are amazing and the atmosphere is friendly and supportive. I feel stronger and happier than ever."</p>
                        <span>- Jack Doe</span>
                    </div>
                </div>
            </div>
        </section>
        <section class="contact">
            <div class="container">
                <h3>Get In Touch</h3>
                <p>If you have any questions or queries, feel free to contact us. We will get back to you as soon as possible.</p>
                <form>
                    <div class="input-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" placeholder="Enter your name" required>
                    </div>
                    <div class="input-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" placeholder="Enter your email" required>
                    </div>
                    <div class="input-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" placeholder="Enter your message" required></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <p>© 2024 Gym. All rights reserved.</p>
            <ul class="social">
                <li><a href="#"><img src="facebook.png" alt="Facebook"></a></li>
                <li><a href="#"><img src="twitter.png" alt="Twitter"></a></li>
                <li><a href="#"><img src="instagram.png" alt="Instagram"></a></li>
            </ul>
        </div>
    </footer>
    <script>
        // Add your JavaScript code here
    </script>
</body>
</html>
