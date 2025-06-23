# Apnaa-Astrologer
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Apna Astrologer</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Apna Astrologer</h1>
    <p>Your guide to Tarot, Astrology, Vastu & Numerology</p>
    <nav>
      <a href="#about">About</a>
      <a href="#courses">Courses</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about" class="section">
    <h2>About Us</h2>
    <div class="bio">
      <div>
        <h3>Arunnima</h3>
        <p>A certified tarot and astrology expert, Arunnima has guided hundreds of people on their spiritual journeys with clarity and compassion.</p>
      </div>
      <div>
        <h3>Mr. [Your Husband's Name]</h3>
        <p>An experienced Vastu and Numerology expert, he brings traditional wisdom with practical insights to help bring balance and harmony.</p>
      </div>
    </div>
  </section>

  <section id="courses" class="section">
    <h2>Our Courses</h2>
    <div class="courses">
      <div class="course">
        <h3>Tarot Reading Course</h3>
        <p>Learn intuitive tarot reading, card meanings, spreads, and client connection techniques. Includes practice sessions.</p>
      </div>
      <div class="course">
        <h3>Astrology Course</h3>
        <p>Understand birth charts, planets, houses, and predictive techniques in both Vedic and Western styles.</p>
      </div>
      <div class="course">
        <h3>Vastu Shastra Course</h3>
        <p>Study directional energies, remedies, and traditional placement for home and office harmony.</p>
      </div>
      <div class="course">
        <h3>Numerology Course</h3>
        <p>Explore the power of numbers in names, dates, and life paths using ancient systems.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: contact@apnaastrologer.com</p>
    <p>WhatsApp: +91-XXXXXXXXXX</p>
  </section>
  body {
  font-family: 'Poppins', sans-serif;
  margin: 0;
  background-color: #fff8dc;
  color: #333;
  scroll-behavior: smooth;
}

header {
  background-color: #ff9933;
  color: white;
  text-align: center;
  padding: 40px 20px;
}

header h1 {
  margin: 0;
  font-size: 2.5em;
}

header p {
  font-size: 1.2em;
  margin: 10px 0 20px;
}

nav a {
  margin: 0 15px;
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.section {
  padding: 40px 20px;
  opacity: 0;
  transform: translateY(30px);
  animation: fadeSlide 1s ease-out forwards;
}

.section:nth-of-type(even) {
  animation-delay: 0.2s;
}

h2 {
  color: #ff9933;
  text-align: center;
}

.bio {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  margin-top: 20px;
}

.bio div {
  max-width: 400px;
  margin: 20px;
  background: #fffdf2;
  padding: 20px;
  border: 2px solid #ffcc66;
  border-radius: 10px;
  text-align: center;
}

.profile-img {
  width: 100%;
  max-width: 150px;
  border-radius: 50%;
  margin-bottom: 10px;
}

.courses {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.course {
  background: #fff7e6;
  padding: 20px;
  border: 2px solid #ffcc66;
  border-radius: 10px;
  text-align: center;
}

.course img {
  width: 100%;
  max-width: 200px;
  border-radius: 8px;
  margin-bottom: 10px;
}

footer {
  background-color: #ff9933;
  color: white;
  text-align: center;
  padding: 20px;
  font-size: 0.9em;
}

@keyframes fadeSlide {
  to {
    opacity: 1;
    transform: translateY(0);
  }
}


  <footer>
    <p>© 2025 Apna Astrologer. All rights reserved.</p>
  </footer>
</body>
</html>
