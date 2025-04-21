<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sajib Rayhan - Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #0066cc;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header img {
      border-radius: 50%;
      width: 150px;
      height: 150px;
      object-fit: cover;
      border: 4px solid white;
      margin-top: 1rem;
    }
    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    h2 {
      color: #0066cc;
    }
    .contact a {
      display: inline-block;
      margin-right: 10px;
      text-decoration: none;
      color: #0066cc;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #eee;
      margin-top: 2rem;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input, textarea {
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 1rem;
    }
    button {
      background-color: #0066cc;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #004999;
    }
  </style>
</head>
<body>
  <header>
    <h1>Sajib Rayhan</h1>
    <p>Student | Graphics Designer | Trader</p>
    <img src="profile.jpg" alt="Sajib Rayhan's Photo" />
  </header>  <section>
    <h2>About Me</h2>
    <p>I am Sajib Rayhan, currently studying Law at Sheikh Fazilatunnesa Mujib University. I am skilled in computer operations, graphics design, and trading.</p>
  </section>  <section>
    <h2>Skills</h2>
    <ul>
      <li>Graphics Design</li>
      <li>Trading</li>
      <li>Basic Computer Operations</li>
    </ul>
  </section>  <section>
    <h2>Projects</h2>
    <ul>
      <li><strong>Facebook Cover Design:</strong> Designed multiple eye-catching Facebook cover pages for businesses and personal brands.</li>
      <li><strong>Trading Analysis & Reports:</strong> Created detailed trading analysis using chart patterns and market insights.</li>
    </ul>
  </section>  <section>
    <h2>Contact</h2>
    <div class="contact">
      <p>Email: <a href="mailto:ibrahimislamsojib3@gmail.com">ibrahimislamsojib3@gmail.com</a></p>
      <p>Phone: <a href="tel:01571502854">01571502854</a></p>
      <p>Facebook: <a href="https://www.facebook.com/ibrahimislamsojib3" target="_blank">Visit My Facebook</a></p>
    </div>
    <form action="https://formspree.io/f/moqgqjzv" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>  <footer>
    <p>&copy; 2025 Sajib Rayhan</p>
  </footer>
</body>
</html>