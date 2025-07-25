<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Charity: Water - Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: 'Avenir', 'Proxima Nova', sans-serif;
      background-color: #fffbe6;
      color: #333;
    }

    .hero {
      background: url('https://via.placeholder.com/1600x600?text=Clean+Water+for+All') center/cover no-repeat;
      color: black;
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 1rem;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.3rem;
      max-width: 600px;
    }

    .story {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      padding: 3rem 1rem;
      background-color: #ffffff;
      max-width: 1000px;
      margin: 0 auto;
    }

    .story img {
      width: 100%;
      max-width: 500px;
      border-radius: 8px;
      margin: 1rem;
    }

    .story-text {
      flex: 1;
      padding: 1rem;
    }

    .story-text h2 {
      color: #2E9DF7;
      font-size: 2rem;
    }

    .story-text p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    .donate-section {
      text-align: center;
      background-color: #FFC907;
      padding: 3rem 1rem;
    }

    .donate-section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #000;
    }

    .cta-button {
      display: inline-block;
      margin-top: 1rem;
      padding: 1rem 2rem;
      background-color: #2E9DF7;
      color: white;
      font-size: 1.1rem;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      transition: background 0.3s ease;
    }

    .cta-button:hover {
      background-color: #1d7fcf;
    }

    footer {
      background-color: #f5f5f5;
      padding: 1rem;
      text-align: center;
      font-size: 0.9rem;
      color: #888;
    }

    /* Media Queries for Mobile Responsiveness */
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }

      .story {
        flex-direction: column;
        padding: 2rem 1rem;
      }

      .story-text {
        padding: 0;
      }
    }
  </style>
</head>
<body>
  <section class="hero">
    <h1>Clean Water Changes Everything</h1>
    <p>100% of your donation brings clean water to communities in need. Help us make a lasting impact today.</p>
  </section>

  <section class="story">
    <img src="https://via.placeholder.com/500x300?text=Impact+Story+Image" alt="Impact Story">
    <div class="story-text">
      <h2>Meet Amina</h2>
      <p>Amina used to walk 4 hours a day to fetch unsafe water for her family. Now, thanks to donations like yours, clean water is just steps from her home. Your support transforms lives.</p>
    </div>
  </section>

  <section class="donate-section">
    <h2>Ready to make a difference?</h2>
    <a href="#" class="cta-button">Donate Now</a>
  </section>

  <footer>
    &copy; 2025 Charity: Water | Designed by Keller Leet
  </footer>
</body>
</html># Landing-page
