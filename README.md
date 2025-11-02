<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Borden | Personal Brand</title>
    <style>
        /* Reset and Base Styles - Minimalist foundation */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Playfiar Display', Arial, sans-serif;
            background: linear-gradient(to bottom, #571717, #000000); /* Black top to dark grey bottom */
            color: #000;
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 40px 20px;
            overflow-x: hidden;
        }
        .container {
            max-width: 800px;
            width: 100%;
            background: rgba(255, 255, 255, 0.1); /* Subtle overlay to keep content readable on dark background */
            padding: 60px 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3); /* Deeper shadow for contrast on dark */
            text-align: center;
            position: relative;
            overflow: hidden;
            backdrop-filter: blur(5px); /* Optional frosted-glass effect for modern feel */
        }
        /* Artful Creativity: Subtle particle-like dots in background (lightened for visibility on dark) */
        .container::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: radial-gradient(circle, rgba(200, 200, 200, 0.15) 1px, transparent 1px);
            background-size: 20px 20px;
            opacity: 0.4;
            z-index: -1;
            animation: float 20s infinite linear;
        }
        @keyframes float {
            0% { transform: translateY(0); }
            100% { transform: translateY(-20px); }
        }
        /* Header */
        header h1 {
            font-size: 3.5rem;
            font-weight: 300;
            margin-bottom: 10px;
            letter-spacing: 2px;
            color: #b8860b; /* Deep gold (darker shade of gold for elegance and readability) */
        }
        header p.subtitle {
            font-size: 1.2rem;
            color: #851111; /* Lighter ruby tone for secondary headline */
            margin-bottom: 40px;
            font-style: italic;
        }
        /* Profile Image - Placeholder for your photo */
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin: 0 auto 30px;
            border: 4px solid #919191; /* Darker border to blend with background */
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease;
        }
        .profile-img:hover {
            transform: scale(1.05);
        }
        /* Sections */
        section {
            margin: 40px 0;
            padding: 20px;
            background: rgba(50, 50, 50, 0.5); /* Darker semi-transparent for section cards */
            border-radius: 15px;
            transition: background 0.3s ease;
        }
        section:hover {
            background: rgba(70, 70, 70, 0.7);
        }
        section h2 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #701124; /* Ruby for secondary headlines (section titles) */
            position: relative;
        }
        section h2::after {
            content: '';
            position: absolute;
            bottom: -8px;
            left: 50%;
            transform: translateX(-50%);
            width: 50px;
            height: 2px;
            background: #b8860b; /* Deep gold accent underline */
        }
        section p, section ul {
            font-size: 1.1rem;
            text-align: left;
            max-width: 600px;
            margin: 0 auto;
            color: #c0c0c0; /* Silver for main text */
        }
        section ul {
            list-style: none;
        }
        section ul li {
            margin: 10px 0;
            padding-left: 20px;
            position: relative;
        }
        section ul li::before {
            content: '•';
            position: absolute;
            left: 0;
            color: #b8860b; /* Deep gold bullets */
            font-weight: bold;
        }
        section ul li strong {
            color: #dc143c; /* Ruby for bolded terms in lists */
        }
        /* Connect Button */
        .connect-btn {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 30px;
            background: #b8860b; /* Deep gold button */
            color: #000;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 4px 10px rgba(184, 134, 11, 0.4);
        }
        .connect-btn:hover {
            background: #dc143c; /* Ruby on hover */
            color: #fff;
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(220, 20, 60, 0.5);
        }
        /* Footer */
        footer {
            margin-top: 50px;
            font-size: 0.9rem;
            color: #a0a0a0; /* Muted silver for footer */
        }
        /* Responsive Adjustments */
        @media (max-width: 600px) {
            header h1 { font-size: 2.5rem; }
            .container { padding: 40px 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Your Name</h1>
            <p class="subtitle">Building Connections | Embracing Growth | Grounded in Humanity</p>
        </header>
       
        <!-- Replace src with your photo URL or local file, e.g., 'your-photo.jpg' -->
        <img src="https://via.placeholder.com/150" alt="Your Profile Photo" class="profile-img">
       
        <section id="about">
            <h2>About Me</h2>
            <p>I'm a lifelong learner dedicated to personal growth, forging meaningful networks, and maintaining a humanist perspective in everything I do. With a focus on self-improvement, I strive to balance ambition with empathy, turning ideas into impactful connections.</p>
        </section>
       
        <section id="ideals">
            <h2>My Ideals</h2>
            <ul>
                <li><strong>Continuous Improvement:</strong> Embracing challenges as opportunities to evolve.</li>
                <li><strong>Authentic Networking:</strong> Building relationships based on trust and mutual growth.</li>
                <li><strong>Humanist Approach:</strong> Prioritizing empathy, ethics, and real-world impact over pure efficiency.</li>
                <li><strong>Grounded Ambition:</strong> Pursuing goals with humility and a focus on long-term fulfillment.</li>
            </ul>
        </section>
       
        <section id="goals">
            <h2>My Goals</h2>
            <ul>
                <li>Expand my professional network by collaborating on innovative projects.</li>
                <li>Achieve mastery in [your field/skill, e.g., coding, design].</li>
                <li>Contribute to communities that value personal development and humanism.</li>
                <li>Inspire others through sharing my journey and lessons learned.</li>
            </ul>
        </section>
       
        <a href="mailto:bordash@xichor.org" class="connect-btn">Let's Connect</a>
       
        <footer>
            &copy; 2025 Built with Xichor.
        </footer>
    </div>
</body>
</html>
