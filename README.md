<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TJ Roofing LLC | Premium Roofing in Thurston County</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --bg-black: #0a0a0a;
            --card-gray: #161616;
            --gold: #d4af37;
            --gold-hover: #f1c40f;
            --text-white: #ffffff;
            --text-muted: #a0a0a0;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Inter', sans-serif; background-color: var(--bg-black); color: var(--text-white); line-height: 1.6; overflow-x: hidden; }

      
        nav { padding: 2rem 5%; display: flex; justify-content: space-between; align-items: center; position: absolute; width: 100%; z-index: 10; }
        .logo { font-weight: 700; font-size: 1.5rem; letter-spacing: 1px; color: var(--gold); }

       
        .hero { height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; padding: 0 10%; background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1632759162353-066f1fc910b8?auto=format&fit=crop&q=80&w=2000') no-repeat center center/cover; }
        .hero h1 { font-size: clamp(2.5rem, 6vw, 4.5rem); margin-bottom: 1rem; line-height: 1.1; }
        .hero p { font-size: 1.2rem; color: var(--text-muted); margin-bottom: 2rem; max-width: 600px; }
        .cta-btns { display: flex; gap: 1rem; flex-wrap: wrap; justify-content: center; }

     
        .btn { padding: 1rem 2rem; border-radius: 50px; text-decoration: none; font-weight: 700; transition: 0.3s; cursor: pointer; }
        .btn-gold { background: var(--gold); color: black; border: none; }
        .btn-gold:hover { background: var(--gold-hover); transform: translateY(-3px); }
        .btn-outline { border: 1px solid var(--text-white); color: var(--text-white); }
        .btn-outline:hover { background: var(--text-white); color: black; }


        .trust-bar { background: var(--card-gray); padding: 1.5rem; text-align: center; border-bottom: 1px solid #333; }
        .trust-content { display: flex; justify-content: center; gap: 3rem; flex-wrap: wrap; opacity: 0.8; }

       
        .section { padding: 6rem 10%; }
        .section-title { text-align: center; margin-bottom: 4rem; }
        .section-title h2 { font-size: 2.5rem; margin-bottom: 10px; }
        .section-title span { color: var(--gold); text-transform: uppercase; letter-spacing: 2px; font-size: 0.9rem; }

        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; }
        .card { background: var(--card-gray); padding: 2.5rem; border-radius: 20px; border: 1px solid #222; transition: 0.4s; }
        .card:hover { border-color: var(--gold); transform: translateY(-10px); box-shadow: 0 10px 30px rgba(0,0,0,0.5); }
        .card h3 { color: var(--gold); margin-bottom: 1rem; }

      
        .testimonial-card { font-style: italic; border-left: 3px solid var(--gold); padding-left: 1.5rem; }

        .contact-container { max-width: 800px; margin: 0 auto; background: var(--card-gray); padding: 3rem; border-radius: 20px; }
        input, select, textarea { width: 100%; padding: 1rem; margin-bottom: 1rem; background: #222; border: 1px solid #333; color: white; border-radius: 8px; }
        
        footer { text-align: center; padding: 3rem; border-top: 1px solid #222; font-size: 0.9rem; color: var(--text-muted); }

        @media (max-width: 768px) {
            .hero { padding: 0 5%; }
            .trust-content { gap: 1rem; font-size: 0.8rem; }
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo">TJ ROOFING LLC</div>
        <div class="phone">📞 (360) 555-0123</div>
    </nav>

    <section class="hero">
        <span>ESTABLISHED & LOCALLY TRUSTED</span>
        <h1>Premium Roofing.<br>Honest Pricing.<br>Built to Last.</h1>
        <p>Expert craftsmanship meets transparent communication. Serving Thurston County with 4.8-star excellence.</p>
        <div class="cta-btns">
            <a href="#contact" class="btn btn-gold">Get Free Estimate</a>
            <a href="tel:3605550123" class="btn btn-outline">Call Now</a>
        </div>
    </section>

    <div class="trust-bar">
        <div class="trust-content">
            <span>⭐️ 4.8 Rating (25+ Reviews)</span>
            <span>🛡️ Fully Licensed & Insured</span>
            <span>📍 Thurston County Local</span>
        </div>
    </div>

    <section class="section">
        <div class="section-title">
            <span>Our Services</span>
            <h2>Master-Level Solutions</h2>
        </div>
        <div class="grid">
            <div class="card"><h3>Roof Replacement</h3><p>High-end architectural shingles and premium installation for long-term protection.</p></div>
            <div class="card"><h3>Roof Repair</h3><p>Fast, reliable leak detection and structural fixes to save your home from water damage.</p></div>
            <div class="card"><h3>TPO & Flat Roofing</h3><p>Modern solutions for flat-roofed homes and commercial spaces with heat-welded durability.</p></div>
            <div class="card"><h3>Moss Removal</h3><p>Professional treatment that cleans and preserves your roof without damaging the shingles.</p></div>
            <div class="card"><h3>Roof Cleaning</h3><p>Maintain your curb appeal and extend your roof's life with our gentle wash system.</p></div>
            <div class="card"><h3>Emergency Service</h3><p>Immediate response for storm damage or sudden leaks when you need it most.</p></div>
        </div>
    </section>

    <section class="section" style="background: #0f0f0f;">
        <div class="section-title">
            <span>Reviews</span>
            <h2>What Your Neighbors Say</h2>
        </div>
        <div class="grid">
            <div class="card testimonial-card">"Professional, affordable, and on time. They fixed what another company messed up."<br><br><strong>- Michael S., Olympia</strong></div>
            <div class="card testimonial-card">"High-quality work and very responsive. The crew was polite and left the site spotless."<br><br><strong>- Sarah L., Lacey</strong></div>
            <div class="card testimonial-card">"Fast, efficient, and exceeded expectations. Best roofing experience I've ever had."<br><br><strong>- David K., Tumwater</strong></div>
        </div>
    </section>

    <section id="contact" class="section">
        <div class="section-title">
            <span>Free Quote</span>
            <h2>Secure Your Estimate</h2>
        </div>
        <div class="contact-container">
            <form>
                <input type="text" placeholder="Full Name" required>
                <input type="tel" placeholder="Phone Number" required>
                <input type="text" placeholder="Property Address" required>
                <select>
                    <option>Select Project Type</option>
                    <option>New Roof</option>
                    <option>Repair</option>
                    <option>Cleaning/Moss Removal</option>
                </select>
                <textarea rows="4" placeholder="Tell us about your roof..."></textarea>
                <button type="submit" class="btn btn-gold" style="width: 100%;">Submit Request</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 TJ Roofing LLC. Licensed, Bonded & Insured. Serving Thurston County, WA.</p>
    </footer>

</body>
</html>
