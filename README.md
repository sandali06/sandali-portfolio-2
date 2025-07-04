# sandali-portfolio-2
This simple, responsive portfolio website showcases Sandali’s graphic design work. It includes Home, About, and Contact pages with a clean layout and easy navigation. Visitors can learn about Sandali’s skills and reach out via the contact form. Ideal for a beginner’s web development project. 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>WordPress Website Development Assignment - Sandali</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
    }
    header {
      background: #333;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      margin-top: 0.5rem;
    }
    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
    }
    section {
      padding: 2rem;
      background: white;
      margin: 1rem;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }
    iframe {
      max-width: 100%;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    img {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 1rem 0;
    }
    form input, form textarea, form button {
      width: 100%;
      padding: 0.5rem;
      margin: 0.5rem 0;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #333;
      color: white;
    }
  </style>
</head>
<body>

  <header>
    <h1>WordPress Simple Website Development</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#theme">Theme</a>
      <a href="#sitemap">Sitemap/UI</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home">
    <h2>Assignment Summary</h2>
    <p>This assignment involves designing and developing a 3-page WordPress website using free tools. The steps include selecting a theme, designing the sitemap and wireframes in Figma, developing the pages in WordPress, and hosting or submitting the website. It helps build essential skills in web development, UI planning, and deployment.</p>
  </section>

  <section id="about">
    <h2>Objective</h2>
    <p>The goal is to plan, design, and build a simple website using WordPress and Figma. Students will apply hands-on skills to create a functional and visually consistent site.</p>
  </section>

  <section id="theme">
    <h2>Theme Selection and Scenario</h2>
    <p><strong>Chosen Theme:</strong> Astra</p>
    <p>I chose the <strong>Astra</strong> theme for its lightweight structure, fast loading speed, and ease of customization. It integrates perfectly with Elementor and other page builders. Astra’s minimal design and responsive layout make it ideal for a personal portfolio website, which is the scenario I selected. This setup allows me to display my skills and contact information professionally and clearly across devices.</p>
  </section>

  <section id="sitemap">
    <h2>Sitemap & UI Sketches</h2>

    <h3>Sitemap</h3>
    <!-- Replace below with actual Figma embed or PNG -->
    <img src="sitemap-sample.png" alt="Sitemap Design">

    <!-- OR embed from Figma -->
    <!--
    <iframe width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=YOUR_FIGMA_URL" allowfullscreen></iframe>
    -->

    <h3>UI Wireframes</h3>
    <p>These low-fidelity wireframes were created in Figma to plan the structure of each page.</p>
    <img src="ui-home.png" alt="Home Page Wireframe">
    <img src="ui-about.png" alt="About Page Wireframe">
    <img src="ui-contact.png" alt="Contact Page Wireframe">
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>If you have any questions regarding this assignment, feel free to reach out.</p>
    <form>
      <label>Name:</label><br>
      <input type="text" name="name" required><br>
      <label>Email:</label><br>
      <input type="email" name="email" required><br>
      <label>Message:</label><br>
      <textarea name="message" rows="4" required></textarea><br>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Sandali Perera. All rights reserved.
  </footer>

</body>
</html>
