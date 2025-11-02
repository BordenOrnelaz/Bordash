<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Personal Brand</title>
    <style>
        /* Reset and Base Styles - Minimalist foundation */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Times New Roman', arial, sans-serif;
            background: linear-gradient(to bottom, #000000, #1f1f1f); /* Subtle gradient for depth */
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
            background: rgba(fff, 300, 123, 0.85); /* Semi-transparent for airy feel */
            padding: 60px 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(100, 100, 0, 0.1); /* Soft shadow for elevation */
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        /* Artful Creativity: Subtle particle-like dots in background */
        .container::before {
            content: '';
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: radial-gradient(circle, rgba(100, 150, 200, 0.1) 1px, transparent 1px);
            background-size: 20px 20px;
            opacity: 0.3;
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
            font-weight: 1000;
            margin-bottom: 10px;
            letter-spacing: 2px;
            color: #bf8d00;
        }
        header p.subtitle {
            font-size: 1.2rem;
            color: #64748b;
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
            border: 4px solid #D6981E;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.15);
            transition: transform 0.3s ease;
        }
        .profile-img:hover {
            transform: scale(1.05);
        }
        /* Sections */
        section {
            margin: 40px 0;
            padding: 20px;
            background: rgba(240, 244, 248, 0.5);
            border-radius: 15px;
            transition: background 0.3s ease;
        }
        section:hover {
            background: rgba(220, 230, 240, 0.7);
        }
        section h2 {
            font-size: 1.8rem;
            margin-bottom: 15px;
            color: #8b2222;
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
            background: #CFA406; /* Artful accent color */
        }
        section p, section ul {
            font-size: 1.1rem;
            text-align: left;
            max-width: 600px;
            margin: 0 auto;
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
            color: #8b0001;
            font-weight: bold;
        }
        /* Connect Button */
        .connect-btn {
            display: inline-block;
            margin-top: 30px;
            padding: 12px 30px;
            background: #CC9223;
            color: #900;
            text-decoration: none;
            border-radius: 2000px;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 10px 100px rgba(900, 000, 000, 0.9);
        }
        .connect-btn:hover {
            background: #ff000;
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(100, 150, 200, 0.4);
        }
        /* Footer */
        footer {
            margin-top: 50px;
            font-size: 0.9rem;
            color: #8c8c8c;
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
            <h1>Borden</h1>
          <p class="subtitle">Born in the forest | Raised by the city.</p><p class="subtitle">Defined by Rock and Roll</p>
        </header>
        
        <!-- Replace src with your photo URL or local file, e.g., 'your-photo.jpg' -->
        <img src="https://pbs.twimg.com/media/FgI55VVVEAAT6Sl?format=jpg&name=medium" alt="Your Profile Photo" class="profile-img">
        
        <section id="about">
            <h2>The Human</h2>
            <p>I'm a wanderer etched in the ink of endless dawns, chasing the ghost of who I was to birth the man I'll become. I weave souls into constellations - raw, electric, unbreakable - holding the thunder of dreams in one hand, the whisper of compassion in the other.
              Ambition? It's the fire in my veins, tempered by the salt of tears shed for strangers. I turn sparks of thought into lightning storms of kinship, where ideas bleed into bonds that outlast the flesh.</p>
        </section>
        
        <section id="ideals">
            <h2>My Ideals</h2>
            <ul>
                <li><strong>Continuous Improvement:</strong> I dive headfirst into the abyss of trials,
rising slick with evolution's sweat, reborn in the wreckage of yesterday.</li>
                <li><strong>Authentic Networking:</strong> No masks, no chains—just veins pulsing with trust, forging empires of mutual ascent where egos dissolve in shared blood.</li>
                <li><strong>Humanist Approach:</strong> Empathy's the blade I wield over cold machinery,
carving ethics into the marrow of progress, where impact echoes louder than the hum of hollow speed.</li>
                <li><strong>Grounded Ambition:</strong> I chase horizons with knees scarred from kneeling,
humility my compass, fulfillment the slow-burn horizon that scorches the soul eternal.</li>
            </ul>
        </section>
        
        <section id="goals">
            <h2>My Goals</h2>
            <ul>
                <li>Explode my web of warriors through collaborations that shatter the ordinary, birthing projects that howl innovation into the void.</li>
                <li>Claw my way to godhood in [your field/skill, e.g., coding, design], fingers bleeding code, eyes wild with mastery’s fever.</li>
                <li>Pour my essence into tribes that worship growth and the human spark, building altars to development where spirits entwine.</li>
                <li>Ignite the lost with tales ripped from my ribs - journeys scarred, lessons forged in fire - screaming inspiration until the world catches flame.</li>
            </ul>
        </section>
        
        <a href="mailto:bordash@xichor.org" class="connect-btn">Send a Raven</a>
        
        <footer>
            &copy; 2025 Flows with Xichor.
        </footer>
    </div>
</body>
</html>
