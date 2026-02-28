<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luwined Fairline Agency | Real Estate & Property Management</title>

<style>
    * { margin:0; padding:0; box-sizing:border-box; font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
    body { background:#f5f7fa; color:#333; line-height:1.6; }
    
    header { 
        position: relative;
        background: url('hero-property.jpg') no-repeat center center/cover;
        color: white; 
        height: 400px;
        display:flex;
        flex-direction:column;
        justify-content:center;
        align-items:center;
        text-align:center;
    }
    header h1 { font-size:48px; margin-bottom:10px; text-shadow: 2px 2px 5px rgba(0,0,0,0.5);}
    header p { font-size:20px; text-shadow: 1px 1px 4px rgba(0,0,0,0.5); }

    nav { background:#111827; padding:15px; text-align:center; position: sticky; top:0; z-index:1000; }
    nav a { color:white; text-decoration:none; margin:0 15px; font-weight:500; transition:0.3s; }
    nav a:hover { color:#3b82f6; }

    section { padding:60px 20px; max-width:1200px; margin:auto; }
    h2 { text-align:center; margin-bottom:40px; color:#1f2937; font-size:32px; }

    .card { background:white; padding:25px; margin-bottom:20px; border-radius:10px; box-shadow:0 5px 15px rgba(0,0,0,0.08); }
    .services ul { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); list-style:none; gap:15px; }
    .services li { background:#e5e7eb; padding:15px; border-radius:8px; text-align:center; font-weight:500; }

    .portfolio { display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:20px; }
    .portfolio img { width:100%; border-radius:8px; }

    .testimonials { display:grid; grid-template-columns:repeat(auto-fit,minmax(300px,1fr)); gap:20px; }
    .testimonial { background:#e5e7eb; padding:20px; border-radius:10px; font-style:italic; }

    .btn { display:inline-block; background:#2563eb; color:white; padding:12px 20px; border-radius:6px; text-decoration:none; margin-top:15px; transition:0.3s; }
    .btn:hover { background:#1e40af; }

    footer { background:#111827; color:#9ca3af; text-align:center; padding:20px; margin-top:40px; }

    @media(max-width:600px){
        header h1 { font-size:32px; }
        header p { font-size:16px; }
    }
</style>
</head>

<body>

<header>
    <h1>Luwined Fairline Agency</h1>
    <p>Connecting Buyers & Sellers | Property Management | Construction & Renovations</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Us</h2>
    <div class="card">
        <p>
            Luwined Fairline Agency is your trusted partner for real estate solutions, property management, 
            renovations, construction, and waste management. We handle buying, selling, leasing, 
            document processing, market analysis, and connecting buyers and sellers for seamless transactions.
        </p>
    </div>
</section>

<section id="services">
    <h2>Our Services</h2>
    <div class="card services">
        <ul>
            <li>Property Buying & Selling</li>
            <li>Property Renting & Leasing</li>
            <li>Property Management</li>
            <li>Administrative & Document Processing</li>
            <li>Market Analysis</li>
            <li>Renovations & Construction</li>
            <li>Waste Management</li>
            <li>Connecting Buyers & Sellers</li>
        </ul>
    </div>
</section>

<section id="portfolio">
    <h2>Our Portfolio</h2>
    <div class="portfolio">
        <img src="property1.jpg" alt="Property 1">
        <img src="property2.jpg" alt="Property 2">
        <img src="property3.jpg" alt="Property 3">
        <img src="property4.jpg" alt="Property 4">
    </div>
</section>

<section id="testimonials">
    <h2>What Our Clients Say</h2>
    <div class="testimonials">
        <div class="testimonial">"Luwined Fairline Agency made buying my first home smooth and stress-free!" – John D.</div>
        <div class="testimonial">"Professional, trustworthy, and highly responsive. Highly recommend!" – Sarah K.</div>
        <div class="testimonial">"Their renovation and property management services are top-notch." – Ahmed M.</div>
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <div class="card">
        <p>Email: <a href="mailto:info@luwinedfairline.com">info@luwinedfairline.com</a></p>
        <p>Phone: +XXX-XXX-XXXX</p>
        <p>Address: Your Office Address Here</p>
        <a href="mailto:info@luwinedfairline.com" class="btn">Send Inquiry</a>
    </div>
</section>

<footer>
    <p>© 2026 Luwined Fairline Agency. All Rights Reserved.</p>
</footer>

</body>
</html>
