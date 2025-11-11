<!doctype html>
<html>
<head>
  <meta charset="utf-8" />
  <title>Voices of the Land — Home</title>
  <meta name="viewport" content="width=device-width,initial-scale:1" />
  <style>
    :root {
      --bg:#f5efe6;
      --card:#fff9f2;
      --accent:#8a4b2a;
      --accent-2:#b33a2a;
      --muted:#6b5847;
    }
    body {
      font-family: Inter, Arial, sans-serif;
      background-color: var(--bg);
      color: var(--muted);
      padding: 22px;
      margin: 0;
      /* Medicine Wheel Flower Background */
      background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='60' height='60' viewBox='0 0 60 60'%3E%3Cpath d='M30 10 C20 10 20 20 30 30 C40 20 40 10 30 10' fill='%23FFFFFF' fill-opacity='0.7'/%3E%3Cpath d='M30 50 C20 50 20 40 30 30 C40 40 40 50 30 50' fill='%23B33A2A' fill-opacity='0.5'/%3E%3Cpath d='M10 30 C10 20 20 20 30 30 C20 40 10 40 10 30' fill='%23333333' fill-opacity='0.5'/%3E%3Cpath d='M50 30 C50 20 40 20 30 30 C40 40 50 40 50 30' fill='%23FFD700' fill-opacity='0.5'/%3E%3C/svg%3E");
    }
    .wrap {
      max-width: 720px;
      margin: 0 auto;
      background: rgba(255, 249, 242, 0.98); /* 98% opacity */
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.06);
    }
    h1 {
      color: var(--accent);
      margin: 0 0 10px;
      font-size: 24px;
    }
    h3 { color: var(--accent); }
    p { line-height: 1.6; }

    /* --- Navigation styling --- */
    .main-nav {
      background-color: var(--accent);
      border-radius: 8px;
      margin-bottom: 20px;
      overflow: hidden;
    }
    .main-nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .main-nav a {
      display: block;
      padding: 12px 18px;
      text-decoration: none;
      color: white;
      font-weight: 600;
      font-size: 15px;
    }
    .main-nav a:hover {
      background-color: var(--accent-2);
    }

    .cta-buttons {
      margin-top: 20px;
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
    }
    .cta-buttons a {
      display: inline-block;
      padding: 12px 18px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: 600;
    }
    .cta-primary {
      background-color: var(--accent);
      color: white;
    }
    .cta-secondary {
      background-color: transparent;
      color: var(--accent);
      border: 1px solid var(--accent);
    }
  </style>
</head>
<body>
  <div class="wrap">
    <nav class="main-nav">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="submit.html">Submit a Word</a></li>
        <li><a href="dictionary.html">Public Dictionary</a></li>
        <li><a href="translator.html">Translator</a></li>
        <li><a href="admin.html">Admin Review</a></li>
      </ul>
    </nav>

    <h1>Welcome to Voices of the Land</h1>
    <p>This digital tool is a community-driven project dedicated to the preservation and revitalization of the Cree language. It was created as part of a Design Thinking project to address the real-world need for accessible, community-led language preservation.</p>

    <h3>How This Site Works</h3>
    <p>This tool is built on a "community-first" model. All information is sourced from and verified by the community.</p>

    <ul>
      <li><strong>Submit a Word:</strong> Community members can submit Cree words (Roman and Syllabics), translations, and pronunciation guides.</li>
      <li><strong>Elder Verification:</strong> Submissions are reviewed privately by community Elders for accuracy and appropriateness.</li>
      <li><strong>Public Dictionary:</strong> Verified words become part of the public Cree dictionary for all learners.</li>
      <li><strong>Translator:</strong> A tool to search and map all available translations for a single word.</li>
    </ul>

    <div class="cta-buttons">
      <a href="submit.html" class="cta-primary">Submit a Word</a>
      <a href="dictionary.html" class="cta-secondary">View the Dictionary</a>
    </div>
  </div>
</body>
</html>
