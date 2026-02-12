<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>charity: water — Landing Page</title>
    <style>
        /* ---------- Global Styles ---------- */
        :root{
            --navy: #003366;
            --yellow: #ffc907;
            --cream: #fff7e1;
            --bg: #fed8c1;
            --hero: #77a8bb;
            --text: #003366;
        }

        html,body{height:100%;}
        body {
            margin: 0;
            font-family: "Proxima Nova", Arial, sans-serif;
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
            -webkit-font-smoothing:antialiased;
            -moz-osx-font-smoothing:grayscale;
        }

        h1, h2 {margin: 0 0 0.75rem 0;}

        a {text-decoration: none;}

        /* ---------- Header / Logo ---------- */
        header.logo{
            display:flex;
            align-items:center;
            justify-content:center;
            padding:20px;
            background-color:var(--navy);
        }

        .logo-img{
            height:50px;
            width:auto;
            display:block;
            margin-right:12px;
        }

        .logo-text{
            font-size:1.25rem;
            font-weight:700;
            color:var(--cream);
        }

        /* ---------- Hero Section ---------- */
        .hero{
            background-color:var(--hero);
            padding:64px 20px;
            text-align:center;
        }

        .hero .hero-img{
            width:100%;
            max-width:900px;
            border-radius:8px;
            margin:0 auto 30px;
            display:block;
        }

        .hero h1{
            font-size:clamp(1.6rem, 3.5vw, 2.5rem);
            color:var(--cream);
            margin-top:0;
        }

        .hero p{font-size:1.05rem; color:var(--text); max-width:900px; margin:10px auto 0}

        .cta-btn{
            display:inline-block;
            margin-top:24px;
            padding:12px 26px;
            background-color:var(--yellow);
            color:var(--navy);
            font-weight:700;
            border-radius:6px;
            border:0;
        }

        .cta-btn:focus,
        .cta-btn:hover{opacity:0.95; outline:3px solid rgba(0,0,0,0.08)}

        /* ---------- Story Section ---------- */
        .story{padding:48px 20px; max-width:900px; margin:0 auto}

        .story .story-img{width:100%; border-radius:8px; margin-top:20px; display:block}

        /* ---------- CTA Section ---------- */
        .cta-section{background-color:var(--navy); padding:48px 20px; text-align:center}

        .cta-section h2{font-size:clamp(1.25rem, 2.5vw, 2rem); color:var(--cream)}

        .cta-section a{display:inline-block; margin-top:16px; padding:12px 22px; background-color:var(--yellow); color:#111; border-radius:6px}

        /* ---------- Responsive tweaks ---------- */
        @media (min-width:900px){
            .logo-text{font-size:1.5rem}
            .hero{padding:80px 20px}
        }
    </style>
</head>
<body>

    <header class="logo" role="banner">
        <img src="assets/logo.png" alt="charity: water logo" class="logo-img" loading="lazy">
        <span class="logo-text">charity: water</span>
    </header>

    <main>
        <section class="hero" aria-label="Hero: Make an impact">
            <img src="assets/hero-photo.jpg" alt="Community accessing clean water" class="hero-img" loading="lazy">
            <h1>Your Voice Can Bring Clean Water</h1>
            <p>When you take action with charity: water, you're supporting sustainable solutions and seeing how your commitment transform lives.</p>
            <a href="#donate" class="cta-btn" role="button">Make Your Impact</a>
        </section>

        <section class="story" aria-labelledby="story-heading">
            <h2 id="story-heading">Why Your Action Matters</h2>
            <p>
                Clean water changes everything. It restores health, opens doors to education, and strengthens entire communities.
                Your support fuels proven, transparent solutions that create lasting impact.
            </p>
            <img src="Story-photo.jpg" alt="A family benefiting from clean water" class="story-img" loading="lazy">
            <img src="assets/story-photo.jpg" alt="A family benefiting from clean water" class="story-img" loading="lazy">
        </section>

        <section class="cta-section" aria-labelledby="cta-heading">
            <h2 id="cta-heading">Ready to Create Change?</h2>
            <a href="#join">Join the Movement</a>
        </section>
    </main>

</body>
</html>

- Optimize images and add `srcset` for the hero image.
- Add simple CI or preview deployment (GitHub Pages or Netlify).

## License

Add a license file if this project will be shared publicly.
