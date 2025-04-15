<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elshaddai Skill Centre</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background: linear-gradient(135deg, #8B4513 0%, #A0522D 100%);
            color: white;
            text-align: center;
            padding: 30px 20px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        header p {
            font-size: 1.5em;
            color: #FFD700;
            margin: 10px 0;
            font-style: italic;
        }
        nav {
            background-color: #333;
            text-align: center;
            padding: 15px 0;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 12px 25px;
            display: inline-block;
            font-weight: bold;
            transition: background-color 0.3s, transform 0.2s;
        }
        nav a:hover {
            background-color: #555;
            transform: scale(1.05);
        }
        marquee {
            background-color: #ff6f61;
            color: white;
            padding: 10px;
            font-weight: bold;
        }
        main {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }
        section {
            margin-bottom: 50px;
        }
        .course, .service {
            border: 1px solid #ddd;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            background-color: #fff;
            transition: all 0.3s ease;
        }
        .course:hover, .service:hover {
            box-shadow: 0 6px 12px rgba(0,0,0,0.15);
            transform: translateY(-5px);
        }
        h1, h2 {
            color: #c71585;
        }
        h3 {
            color: #8B4513;
            display: flex;
            align-items: center;
        }
        h3 i {
            margin-right: 10px;
            color: #ff6f61;
        }
        a {
            color: #ff69b4;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
            color: #c71585;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
        }
        .contact-item {
            margin: 12px 0;
            display: flex;
            align-items: center;
        }
        .contact-item i {
            margin-right: 12px;
            color: #ff6f61;
        }
        .btn {
            display: inline-block;
            padding: 12px 25px;
            background-color: #ff6f61;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #e55a50;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="Elshaddai Skill Centre Logo" width="120">
        <h1>Elshaddai Skill Centre</h1>
        <p>LEARN & GROW</p>
    </header>
    <nav>
        <a href="#home"><i class="fas fa-home"></i> Home</a>
        <a href="#courses"><i class="fas fa-book"></i> Courses</a>
        <a href="#support"><i class="fas fa-tools"></i> Support Services</a>
        <a href="#contact"><i class="fas fa-envelope"></i> Contact Us</a>
    </nav>
    <marquee behavior="scroll" direction="left">MS-Office Class Starts Today at 4:45pm</marquee>
    <main>
        <section id="home">
            <h2>Welcome to Elshaddai Skill Centre</h2>
            <p><i class="fas fa-map-marker-alt"></i> Located at: 7/3, 8th street, Sundaram Nagar, M C Road, Thanjavur-613004</p>
            <p><i class="fas fa-clock"></i> Active Hours: Monday, Tuesday, Thursday, and Friday</p>
            <ul>
                <li>Morning Session: 9:00 am - 12:30 pm</li>
                <li>Evening Session: 6:00 pm to 9:00 pm</li>
            </ul>
            <p><i class="fas fa-calendar-check"></i> Appointment needed in prior</p>
            <p><i class="fas fa-map"></i> <a href="https://maps.app.goo.gl/E6GKSsGycKJ3qeR6A" target="_blank">View Location</a></p>
            <div class="cta">
                <a href="#contact" class="btn">Join Our Journey Now!</a>
            </div>
        </section>
        <section id="courses">
            <h2>Courses Offered</h2>
            <div class="course">
                <h3><i class="fas fa-graduation-cap"></i> 11th & 12th CS & CA Tuition Classes</h3>
                <p>Discover your tech brilliance with our tailored tuition for 11th and 12th graders. In just 16 one-hour sessions, spark your future in Computer Science for only Rs 2000!</p>
            </div>
            <div class="course">
                <h3><i class="fab fa-python"></i> Python For Beginners – 30-Day Foundation Course</h3>
                <p>Embark on a coding adventure with Python! Our beginner-friendly course empowers you to create magic in 45 sessions, online or offline, for just Rs 4500.</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-code"></i> Learn C for Beginners – 30 Days</h3>
                <p>Unleash your programming potential with C. Join our flexible 30-session course, online or offline, and innovate for only Rs 3000!</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-code"></i> Master C++ Fundamentals – 30 Days</h3>
                <p>Step into C++ and shape your tech future. Master the basics in 30 sessions, online or offline, for Rs 3000!</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-code"></i> Combo Class: Learn C & C++ – 45 Days</h3>
                <p>Double your skills with our C and C++ combo course. Conquer both in 30 sessions for just Rs 3000, online or offline!</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-laptop-code"></i> Web Designing: HTML, CSS & JavaScript – 30 Days</h3>
                <p>Unleash your inner artist and craft stunning websites! Master HTML, CSS, and JavaScript in 30 sessions to create digital masterpieces. Join now for Rs 6000 and shine online!</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-desktop"></i> Ms-Office Automation – 30 Days</h3>
                <p>Transform your productivity with Word, Excel, and PowerPoint expertise. Become a workplace star in 30 sessions for Rs 4500!</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-database"></i> Learn PHP & MySQL – 30 Days</h3>
                <p>Build dynamic websites with PHP and MySQL. Our 30-session course, online or offline, sets you up for success at Rs 6000!</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-lightbulb"></i> 7 Days to a New You – Quantum Methods</h3>
                <p>Reimagine your future with powerful mindset techniques. Transform in just 5 sessions for only Rs 500!</p>
            </div>
            <div class="course">
                <h3><i class="fas fa-comment"></i> Speak English Confidently – 30 Days</h3>
                <p>Shine bright with fluent English! Our 45-session course for all ages helps you speak with confidence, opening new doors. Join today for Rs 4500!</p>
            </div>
        </section>
        <section id="support">
            <h2>Support Services</h2>
            <div class="service">
                <h3><i class="fas fa-file-alt"></i> College Research Paper Preparation</h3>
                <p>Excel academically with expert guidance on research papers. Seamless support for Rs 100 per hour!</p>
            </div>
            <div class="service">
                <h3><i class="fas fa-project-diagram"></i> CS & CA Mini & Major Projects</h3>
                <p>Turn your CS projects into portfolio gems. Perfect for students ready to stand out!</p>
            </div>
            <div class="service">
                <h3><i class="fas fa-check-circle"></i> EPF Claims & KYC Updating</h3>
                <p>Simplify your EPFO needs with our hassle-free service for just Rs 200!</p>
            </div>
            <div class="service">
                <h3><i class="fas fa-cogs"></i> OS Installation & Software Services</h3>
                <p>Boost your device's performance with our expert PC and laptop solutions!</p>
            </div>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <div class="contact-item"><i class="fas fa-user"></i> Owner/Tutor/Trainer: Jason Paul S</div>
            <div class="contact-item"><i class="fas fa-building"></i> Company: Elshaddai Skill Centre</div>
            <div class="contact-item"><i class="fas fa-map-marker-alt"></i> Address: 7/3, 8th street, Sundaram Nagar, M C Road, Thanjavur-613004</div>
            <div class="contact-item"><i class="fas fa-phone"></i> Mobile: +91 8870211980</div>
            <div class="contact-item"><i class="fas fa-envelope"></i> Email: <a href="mailto:elshaddaiskillcentre@gmail.com">elshaddaiskillcentre@gmail.com</a></div>
            <div class="contact-item"><i class="fas fa-chalkboard-teacher"></i> Classes: Online / Offline</div>
            <div class="contact-item"><i class="fab fa-whatsapp"></i> <a href="https://wa.me/918870211980" target="_blank">WhatsApp</a></div>
            <div class="contact-item"><i class="fab fa-instagram"></i> <a href="https://www.instagram.com/elsh.addaiskillcentre" target="_blank">Instagram</a></div>
            <div class="contact-item"><i class="fab fa-youtube"></i> <a href="https://www.youtube.com/@elshaddaiskillcentre" target="_blank">YouTube</a></div>
        </section>
    </main>
    <footer>
        <p>© 2025 Elshaddai Skill Centre. All rights reserved.</p>
    </footer>
</body>
</html>
