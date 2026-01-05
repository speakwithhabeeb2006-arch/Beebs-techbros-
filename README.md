
        }

        .hero::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, rgba(0,255,255,0.1), rgba(255,0,255,0.1));
            opacity: 0.5;
        }

        .hero h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: clamp(3rem, 8vw, 6rem);
            margin-bottom: 1rem;
            color: var(--primary);
            text-shadow: 0 0 20px var(--primary), 0 0 40px var(--primary);
        }

        .hero p {
            font-size: 1.5rem;
            max-width: 800px;
            margin-bottom: 2rem;
            opacity: 0.9;
        }

        .btn {
            padding: 1rem 2.5rem;
            background: var(--glass);
            border: 1px solid var(--primary);
            border-radius: 50px;
            color: var(--primary);
            text-decoration: none;
            font-weight: 500;
            backdrop-filter: blur(10px);
            box-shadow: 0 0 15px rgba(0,255,255,0.3);
            transition: all 0.4s;
        }

        .btn:hover {
            background: rgba(0,255,255,0.1);
            box-shadow: 0 0 30px rgba(0,255,255,0.6);
            transform: translateY(-5px);
        }

        section {
            padding: 8rem 5%;
            max-width: 1200px;
            margin: 0 auto;
        }

        h2 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3rem;
            text-align: center;
            margin-bottom: 4rem;
            color: var(--primary);
            text-shadow: 0 0 15px var(--primary);
        }

        .glass-card {
            background: var(--glass);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border-radius: 20px;
            border: 1px solid rgba(255,255,255,0.1);
            padding: 2rem;
            margin: 2rem 0;
            box-shadow: 0 8px 32px rgba(0,0,0,0.3);
            transition: transform 0.4s;
        }

        .glass-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 0 40px rgba(0,255,255,0.2);
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        footer {
            text-align: center;
            padding: 3rem;
            background: rgba(0,0,0,0.5);
            border-top: 1px solid rgba(0,255,255,0.2);
        }

        @media (max-width: 768px) {
            nav {
                display: none;
            }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Beebs Techbros</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#services">Services</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Beebs Techbros</h1>
        <p>Innovating the future of tech – one bold idea at a time. Join the techbros revolution.</p>
        <a href="#about" class="btn">Explore More</a>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <div class="glass-card">
            <p>Beebs Techbros is a futuristic tech community and collective dedicated to pushing boundaries in software development, AI, web3, and cutting-edge innovation. We're a group of passionate developers, designers, and thinkers building tomorrow's solutions today.</p>
        </div>
        <div class="grid">
            <div class="glass-card">
                <h3>Our Mission</h3>
                <p>Empower creators with futuristic tools and knowledge to shape the digital world.</p>
            </div>
            <div class="glass-card">
                <h3>Our Vision</h3>
                <p>A world where technology seamlessly enhances human potential.</p>
            </div>
            <div class="glass-card">
                <h3>Our Values</h3>
                <p>Innovation • Collaboration • Boldness • Excellence</p>
            </div>
        </div>
    </section>

    <section id="services">
        <h2>Services & Expertise</h2>
        <div class="grid">
            <div class="glass-card">
                <h3>Web Development</h3>
                <p>Modern, responsive websites with futuristic designs.</p>
            </div>
            <div class="glass-card">
                <h3>AI & Machine Learning</h3>
                <p>Building intelligent systems for the next era.</p>
            </div>
            <div class="glass-card">
                <h3>Blockchain & Web3</h3>
                <p>Decentralized apps and smart contracts.</p>
            </div>
            <div class="glass-card">
                <h3>Consulting</h3>
                <p>Strategic tech advice for startups and enterprises.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Get in Touch</h2>
        <div class="glass-card" style="max-width: 600px; margin: 0 auto;">
            <p>Email: hello@beebstechbros.com</p>
            <p>Twitter/X: @beebstechbros</p>
            <p>Discord: Join our community</p>
            <a href="mailto:hello@beebstechbros.com" class="btn" style="display: inline-block; margin-top: 1rem;">Contact Us</a>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Beebs Techbros. All rights reserved. Built with futuristic vibes.</p>
    </footer>

</body>
</html>
