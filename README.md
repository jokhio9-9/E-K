<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>EduPK - Learn From Home</title>
    <link href="https://fonts.googleapis.com/css2?family=Segoe+UI:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: #f4f7f9;
        }
        /* Topbar */
        
        .topbar {
            background-color: #0b0d26;
            color: white;
            padding: 8px 40px;
            font-size: 14px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .topbar a {
            color: white;
            margin-left: 10px;
            text-decoration: none;
        }
        /* Navbar */
        
        .navbar {
            background-color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        .logo {
            font-size: 24px;
            font-weight: 700;
            color: #004aad;
        }
        
        .navbar-links a {
            margin: 0 15px;
            color: #000;
            text-decoration: none;
            font-weight: 500;
        }
        
        .navbar-links a:hover {
            color: #00bcd4;
        }
        
        .join-btn {
            padding: 10px 20px;
            background-color: #0066ff;
            color: white;
            border: none;
            border-radius: 4px;
            text-decoration: none;
            font-weight: bold;
        }
        /* Hero Section */
        
        .hero {
            background: linear-gradient(to bottom, rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('Edukate.webp');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 40px;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }
        
        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
        }
        
        .search-bar {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            display: flex;
            max-width: 600px;
            margin: auto;
        }
        
        .search-bar select,
        .search-bar input {
            border: none;
            padding: 15px;
            font-size: 16px;
            flex: 1;
        }
        
        .search-bar button {
            background-color: #f04d4e;
            border: none;
            color: white;
            padding: 15px 30px;
            font-size: 16px;
            cursor: pointer;
        }
        
        .section {
            padding: 60px 40px;
            text-align: center;
        }
        
        .section h2 {
            color: #1c2c38;
            font-size: 32px;
            margin-bottom: 20px;
        }
        
        .section p {
            color: #555;
            max-width: 700px;
            margin: auto;
        }
        /* Slider */
        
        .slider-container {
            overflow: hidden;
            position: relative;
            max-width: 100%;
            background-color: #f4f7f9;
            padding: 40px 0;
        }
        
        .slider-track {
            display: flex;
            animation: scrollSlider 12s linear infinite;
            width: calc(300px * 6);
        }
        
        .slider-card {
            background: #fff;
            width: 300px;
            margin: 0 15px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            flex-shrink: 0;
            text-align: center;
        }
        
        .slider-card img {
            width: 60px;
            height: 60px;
            margin-bottom: 15px;
        }
        
        .slider-card h3 {
            color: #2b3e50;
            margin: 10px 0;
        }
        
        .slider-card p {
            font-size: 14px;
            color: #555;
        }
        
        @keyframes scrollSlider {
            0% {
                transform: translateX(0);
            }
            100% {
                transform: translateX(-50%);
            }
        }
        
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                align-items: flex-start;
            }
            .navbar-links {
                display: flex;
                flex-direction: column;
                width: 100%;
            }
            .navbar-links a {
                margin: 10px 0;
            }
            .hero h1 {
                font-size: 32px;
            }
            .hero p {
                font-size: 16px;
            }
            .search-bar {
                flex-direction: column;
            }
            .search-bar button {
                width: 100%;
            }
            .slider-track {
                animation-duration: 18s;
            }
            .slider-card {
                width: 250px;
            }
            .slider-card img {
                width: 50px;
                height: 50px;
            }
        }
    </style>
</head>

<body>

    <!-- TOPBAR with social links -->
    <div class="topbar">
        <div>📞 +012 345 6789 | ✉️ info@example.com</div>
        <div>
            <a href="https://www.facebook.com/YourPage" target="_blank">🌐 Facebook</a>
            <a href="https://twitter.com/YourProfile" target="_blank">🐦 Twitter</a>
            <a href="https://www.instagram.com/YourProfile" target="_blank">📸 Instagram</a>
            <a href="https://www.tiktok.com/@YourProfile" target="_blank">🎵 TikTok</a>
            <a href="https://www.linkedin.com/in/YourProfile" target="_blank">💼 LinkedIn</a>
            <a href="https://www.youtube.com/@YourChannel" target="_blank">▶️ YouTube</a>
        </div>
    </div>

    <!-- NAVBAR -->
    <div class="navbar">
        <div class="logo">EᗪᑌᑭK</div>
        <div class="navbar-links">
            <a href="Home.html">Home</a>
            <a href="Courses.html">Courses</a>
            <a href="subjects.html">Subjects</a>
            <a href="classes.html">Online Classes</a>
            <a href="tutorials.html">Tutorials</a>
            <a href="quizzes.html">Quizzes</a>
            <a href="assignments.html">Assignments</a>
            <a href="blog.html">Blog</a>
            <a href="contact.html">Contact</a>
            <a href="about.html">About</a>
            <a href="login.html">Login</a>
        </div>
        <a href="#" class="join-btn">Join Us</a>
    </div>

    <!-- HERO SECTION -->
    <section class="hero">
        <p>Learn From Home</p>
        <h1>Education Courses</h1>
        <div class="search-bar">
            <select>
                <option value="">Courses</option>
                <option value="english">English</option>
                <option value="ms-office">MS Office</option>
                <option value="graphic-design">Graphic Design</option>
            </select>
            <input type="text" placeholder="Keyword">
            <button>Search</button>
        </div>
    </section>

    <!-- SECTION -->
    <section class="section">
        <h2>First Choice For Online Education Anywhere</h2>
        <p>Join EduPK and discover flexible, affordable, and trusted online learning. Thousands of learners are already succeeding through our expert-led courses.</p>
    </section>

    <!-- SLIDER SECTION -->
    <section class="slider-container">
        <div class="slider-track">
            <div class="slider-card">
                <img src="https://cdn-icons-png.flaticon.com/512/3135/3135768.png" alt="Courses Icon">
                <h3>Courses</h3>
                <p>Basic English Grammar | Spoken English | Business English |English for Kids | IELTS Preparation</p>
            </div>
            <div class="slider-card">
                <img src="https://cdn-icons-png.flaticon.com/512/2942/2942921.png" alt="Online Classes Icon">
                <h3>Online Classes</h3>
                <p>Attend live or recorded sessions by expert teachers with easy access.</p>
            </div>
            <div class="slider-card">
                <img src="https://cdn-icons-png.flaticon.com/512/3898/3898150.png" alt="Quizzes Icon">
                <h3>Quizzes</h3>
                <p>Practice MCQs, test knowledge, and receive instant feedback on your progress.</p>
            </div>
            <div class="slider-card">
                <img src="https://cdn-icons-png.flaticon.com/512/3135/3135768.png" alt="Courses Icon">
                <h3>Courses</h3>
                <p>MS Word | MS Excel (Basic to Advanced) | MS PowerPoint |MS Outlook | Office Productivity Tools</p>
            </div>
            <div class="slider-card">
                <img src="https://cdn-icons-png.flaticon.com/512/2942/2942921.png" alt="Online Classes Icon">
                <h3>Online Classes</h3>
                <p>Attend live or recorded sessions by expert teachers with easy access.</p>
            </div>
            <div class="slider-card">
                <img src="https://cdn-icons-png.flaticon.com/512/3898/3898150.png" alt="Quizzes Icon">
                <h3>Quizzes</h3>
                <p>Practice MCQs, test knowledge, and receive instant feedback on your progress.</p>
            </div>
        </div>
    </section>

</body>

</html>



<br><br>
<style>
    .slider-container {
        overflow: hidden;
        position: relative;
        max-width: 100%;
        background-color: #f4f7f9;
        padding: 40px 0;
    }
    
    .slider-track {
        display: flex;
        animation: scrollSlider 12s linear infinite;
        width: calc(300px * 6);
        /* 6 cards (looped) */
    }
    
    .slider-card {
        background: #fff;
        width: 300px;
        margin: 0 15px;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        padding: 20px;
        flex-shrink: 0;
        text-align: center;
    }
    
    .slider-card img {
        width: 60px;
        height: 60px;
        margin-bottom: 15px;
    }
    
    .slider-card h3 {
        color: #2b3e50;
        margin: 10px 0;
    }
    
    .slider-card p {
        font-size: 14px;
        color: #555;
    }
    
    @keyframes scrollSlider {
        0% {
            transform: translateX(0);
        }
        100% {
            transform: translateX(-50%);
        }
    }
    
    @media (max-width: 768px) {
        .slider-track {
            animation-duration: 18s;
        }
        .slider-card {
            width: 250px;
        }
        .slider-card img {
            width: 50px;
            height: 50px;
        }
    }
</style>

<section class="slider-container">
    <div class="slider-track">
        <!-- Repeat to enable infinite scrolling effect -->
        <div class="slider-card">
            <img src="https://cdn-icons-png.flaticon.com/512/3135/3135768.png" alt="Courses Icon">
            <h3>Courses</h3>
            <p>Basic English Grammar | Spoken English | Business English |English for Kids | IELTS Preparation</p>
        </div>
        <div class="slider-card">
            <img src="https://cdn-icons-png.flaticon.com/512/2942/2942921.png" alt="Online Classes Icon">
            <h3>Online Classes</h3>
            <p>Attend live or recorded sessions by expert teachers with easy access.</p>
        </div>
        <div class="slider-card">
            <img src="https://cdn-icons-png.flaticon.com/512/3898/3898150.png" alt="Quizzes Icon">
            <h3>Quizzes</h3>
            <p>Practice MCQs, test knowledge, and receive instant feedback on your progress.</p>
        </div>

        <!-- Repeat same cards for smooth infinite scroll -->
        <div class="slider-card">
            <img src="https://cdn-icons-png.flaticon.com/512/3135/3135768.png" alt="Courses Icon">
            <h3>Courses</h3>
            <p>MS Word | MS Excel (Basic to Advanced) | MS PowerPoint |MS Outlook | Office Productivity Tools</p>
        </div>
        <div class="slider-card">
            <img src="https://cdn-icons-png.flaticon.com/512/2942/2942921.png" alt="Online Classes Icon">
            <h3>Online Classes</h3>
            <p>Attend live or recorded sessions by expert teachers with easy access.</p>
        </div>
        <div class="slider-card">
            <img src="https://cdn-icons-png.flaticon.com/512/3898/3898150.png" alt="Quizzes Icon">
            <h3>Quizzes</h3>
            <p>Practice MCQs, test knowledge, and receive instant feedback on your progress.</p>
        </div>
    </div>
</section>


</body>

</html>
