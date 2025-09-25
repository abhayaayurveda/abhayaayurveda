
<head>  
  <meta charset="utf-8" />  
  <meta name="viewport" content="width=device-width,initial-scale=1" />  
  <title>Abhaya Ayurveda Hospital — Ennakkad</title>  
  <meta name="description" content="Abhaya Ayurveda Hospital, Ennakkad — Authentic Ayurvedic treatments, Panchakarma, chronic care and wellness programs." />  
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">  
  <style>  
    body{margin:0;font-family:'Inter',sans-serif;line-height:1.6;background:#f7faf7;color:#0a1b12}  
    header{background:#0f5132;color:#fff;padding:20px}  
    .container{max-width:1100px;margin:auto;padding:20px}  
    nav a{color:white;text-decoration:none;margin:0 10px;font-weight:600}  
    .hero{padding:60px 20px;text-align:center}  
    .hero h1{font-size:34px;margin:0}  
    .hero p{max-width:600px;margin:10px auto}  
    .btn{background:#1e7a53;color:#fff;padding:12px 20px;border-radius:6px;text-decoration:none;display:inline-block;margin-top:15px}  
    section{padding:40px 20px}  
    h2{text-align:center;margin-bottom:20px}  
    .grid{display:grid;gap:20px}  
    .services{grid-template-columns:repeat(auto-fit,minmax(220px,1fr))}  
    .card{background:#fff;border-radius:10px;padding:20px;box-shadow:0 2px 6px rgba(0,0,0,0.08)}  
    footer{background:#07200f;color:#cfe9d9;text-align:center;padding:20px}  
    form label{display:block;margin-top:10px;font-weight:600}  
    input,textarea,select{width:100%;padding:10px;border-radius:6px;border:1px solid #ccc}  
    button{background:#1e7a53;color:#fff;padding:12px 18px;border:none;border-radius:6px;margin-top:15px;cursor:pointer}  
  </style>  
</head>  
<body>  
  <header>  
    <div class="container" style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap">  
      <div>  
        <h1 style="margin:0;font-size:22px">Abhaya Ayurveda Hospital</h1>  
        <small>Ennakkad</small>  
      </div>  
      <nav>  
        <a href="#services">Services</a>  
        <a href="#treatments">Treatments</a>  
        <a href="#doctors">Doctors</a>  
        <a href="#contact">Contact</a>  
      </nav>  
    </div>  
  </header>  
  
  <section class="hero">  
    <h1>Welcome to Abhaya Ayurveda Hospital</h1>  
    <p>Authentic Ayurvedic care in Ennakkad — Panchakarma, chronic care, herbal therapies, and wellness programs guided by experienced Vaidyas.</p>  
    <a href="#contact" class="btn">Book an Appointment</a>  
  </section>  
  
  <section id="services">  
    <h2>Our Services</h2>  
    <div class="container grid services">  
      <div class="card"><h3>Panchakarma</h3><p>Detoxification & rejuvenation with classical Ayurveda methods.</p></div>  
      <div class="card"><h3>Chronic Care</h3><p>Management for arthritis, back pain, diabetes, and lifestyle diseases.</p></div>  
      <div class="card"><h3>Wellness Programs</h3><p>Residential healing, yoga, meditation and balanced Ayurvedic diet.</p></div>  
      <div class="card"><h3>Herbal Therapies</h3><p>Customized medicines and oils prepared under expert supervision.</p></div>  
    </div>  
  </section>  
  
  <section id="treatments" style="background:#eef6f0">  
    <h2>Popular Treatments</h2>  
    <div class="container grid services">  
      <div class="card"><h3>Joint & Arthritis Care</h3><p>Relief through medicated oils, therapies, and lifestyle support.</p></div>  
      <div class="card"><h3>Diabetes Management</h3><p>Herbal formulations and diet modifications for better control.</p></div>  
      <div class="card"><h3>Stress & Sleep Therapy</h3><p>Shirodhara, Abhyanga and meditation programs for mental balance.</p></div>  
    </div>  
  </section>  
  
  <section id="doctors">  
    <h2>Our Team</h2>  
    <div class="container grid services">  
      <div class="card"><h3>Dr. R. Sharma, BAMS</h3><p>Chief Vaidya — Panchakarma & chronic care specialist</p></div>  
      <div class="card"><h3>Dr. K. Menon, BAMS</h3><p>Expert in Ayurvedic medicines & lifestyle disorders</p></div>  
      <div class="card"><h3>Therapist Team</h3><p>Experienced Panchakarma & massage therapists</p></div>  
    </div>  
  </section>  
  
  <section id="contact" style="background:#eef6f0">  
    <h2>Book Appointment / Contact</h2>  
    <div class="container" style="display:grid;grid-template-columns:1fr 1fr;gap:20px">  
      <form onsubmit="return sendMail(event)">  
        <label>Name</label>  
        <input type="text" name="name" required>  
        <label>Phone</label>  
        <input type="text" name="phone" required>  
        <label>Service</label>  
        <select name="service">  
          <option>Panchakarma</option>  
          <option>Consultation</option>  
          <option>Wellness Program</option>  
        </select>  
        <label>Message</label>  
        <textarea name="message"></textarea>  
        <button type="submit">Send Request</button>  
      </form>  
      <div>  
        <h3>Abhaya Ayurveda Hospital</h3>  
        <p>Ennakkad</p>  
        <p><strong>Phone:</strong> +91-9447486814</p>  
        <p><strong>Email:</strong> info@abhayaayurveda.org</p>  
        <p><strong>Hours:</strong> Mon–Sat 8:00 am – 6:00 pm</p>  
      </div>  
    </div>  
  </section>  
  
  <footer>  
    © <span id="year"></span> Abhaya Ayurveda Hospital, Ennakkad  
  </footer>  
  
  <script>  
    document.getElementById("year").textContent=new Date().getFullYear();  
    function sendMail(e){  
      e.preventDefault();  
      alert("Your request has been recorded. We will contact you shortly.");  
      return false;  
    }  
  </script>  
</body>  
</html>  
