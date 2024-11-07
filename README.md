<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miracle Morning Club</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Helvetica, Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #000;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
        }

        .logo {
            text-align: center;
            font-size: 3em;
            margin: 20px 0;
        }

        .hero {
            text-align: center;
            padding: 40px 20px;
            background: #fff;
            border: 1px solid #000;
            border-radius: 2px;
            margin-bottom: 40px;
        }

        .hero h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
            font-weight: bold;
            letter-spacing: -0.5px;
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 40px 0;
        }

        .feature-box {
            background: #fff;
            padding: 30px;
            border: 1px solid #000;
            border-radius: 2px;
        }

        .feature-box h3 {
            font-weight: bold;
            margin-bottom: 15px;
            letter-spacing: -0.5px;
        }

        .examples {
            background: #fff;
            padding: 20px;
            border: 1px solid #000;
            border-radius: 2px;
            margin: 20px 0;
        }

        .examples h2 {
            font-weight: bold;
            letter-spacing: -0.5px;
        }

        .cta-button {
            display: inline-block;
            background: #000;
            color: #fff;
            padding: 12px 24px;
            border-radius: 2px;
            text-decoration: none;
            font-weight: bold;
            margin: 20px 0;
            transition: all 0.2s ease;
        }

        .cta-button:hover {
            background: #333;
        }

        .faq {
            margin: 40px 0;
        }

        .faq-item {
            margin-bottom: 10px;
        }

        .faq-question {
            background: #fff;
            padding: 15px;
            cursor: pointer;
            border: 1px solid #000;
            border-radius: 2px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: bold;
        }

        .faq-question:hover {
            background: #f8f8f8;
        }

        .faq-answer {
            display: none;
            padding: 15px;
            background: #fff;
            border: 1px solid #000;
            border-top: none;
            margin-top: -1px;
            border-radius: 0 0 2px 2px;
        }

        .testimonials {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 40px 0;
        }

        .testimonial {
            background: #fff;
            padding: 20px;
            border: 1px solid #000;
            border-radius: 2px;
        }

        .nav-menu {
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 20px 0;
            margin-bottom: 40px;
            border-bottom: 1px solid #000;
        }

        .nav-menu a {
            color: #000;
            text-decoration: none;
            font-weight: bold;
            text-transform: uppercase;
            font-size: 14px;
            letter-spacing: 1px;
        }

        .nav-menu a:hover {
            text-decoration: underline;
        }

        h2 {
            font-weight: bold;
            letter-spacing: -0.5px;
            margin-bottom: 20px;
        }

        ul {
            list-style-type: none;
        }

        ul li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }

        ul li:before {
            content: "–";
            position: absolute;
            left: 0;
        }
    </style>
</head>
<body>
    <div class="logo">
        ☀️
    </div>

    <nav class="nav-menu">
        <a href="#about">About</a>
        <a href="#gatherings">Gatherings</a>
        <a href="#community">Community</a>
        <a href="#apply">Apply</a>
    </nav>

    <div class="hero">
        <h1>our goal is to help you rise and shine ✨</h1>
        <p>Join a community of early risers who are committed to personal growth and success</p>
        <a href="#apply" class="cta-button">Apply to join (takes less than 5 minutes)</a>
    </div>

    <div class="examples">
        <h2>Examples of people in Miracle Morning Club:</h2>
        <ul>
            <li>Olympic athletes sharing their morning routines and mental preparation techniques</li>
            <li>Tech founders discussing how early morning focus shapes their innovation process</li>
            <li>Creative professionals explaining how dawn hours fuel their artistic inspiration</li>
            <li>+ many others from companies like Nike, Tesla, Pixar, Broadway, Michelin-starred restaurants, and more.</li>
        </ul>
    </div>

    <div class="feature-grid">
        <div class="feature-box">
            <h3>Breakfast Gatherings</h3>
            <p>Join curated morning meetups with exceptional achievers from various fields. Share inspiration over breakfast in cities like NYC, SF, London, Paris, Tokyo, and more.</p>
        </div>

        <div class="feature-box">
            <h3>Morning Routines</h3>
            <p>Get exclusive insights into the morning routines of world-class performers. Learn how they start their day and apply their practices to your life.</p>
        </div>

        <div class="feature-box">
            <h3>Networking</h3>
            <p>Connect with like-minded early risers who are committed to personal growth and achievement in their respective fields.</p>
        </div>
    </div>

    <div class="faq">
        <h2>Frequently Asked Questions</h2>
        <div class="faq-item">
            <div class="faq-question">
                Who's behind this? <span>+</span>
            </div>
            <div class="faq-answer">
                A community of passionate individuals inspired by Hal Elrod's Miracle Morning, committed to helping others achieve their full potential through morning routines and networking.
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-question">
                Who hosts the breakfast gatherings? <span>+</span>
            </div>
            <div class="faq-answer">
                Local community leaders and notable achievers in various fields host our morning gatherings, creating intimate spaces for meaningful connections.
            </div>
        </div>

        <div class="faq-item">
            <div class="faq-question">
                How can I host a gathering in my city? <span>+</span>
            </div>
            <div class="faq-answer">
                Reach out to us through the application form, and we'll connect with you about hosting opportunities in your area.
            </div>
        </div>
    </div>

    <div class="testimonials">
        <div class="testimonial">
            <p>"The Miracle Morning Club has transformed not just my mornings, but my entire approach to success. The community is incredible!"</p>
            <p><strong>- Sarah Chen, Olympic Athlete</strong></p>
        </div>
        <div class="testimonial">
            <p>"Meeting other driven individuals at sunrise has been game-changing for my creative process. The energy is unmatched."</p>
            <p><strong>- Michael Rivera, Tech Founder</strong></p>
        </div>
    </div>

    <script>
        document.querySelectorAll('.faq-question').forEach(question => {
            question.addEventListener('click', () => {
                const answer = question.nextElementSibling;
                const isOpen = answer.style.display === 'block';
                answer.style.display = isOpen ? 'none' : 'block';
                question.querySelector('span').textContent = isOpen ? '+' : '-';
            });
        });
    </script>
</body>
</html>
