
  <meta charset="utf-8" />

  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <style>
    :root{--bg:#f5efe6;--card:#fff9f2;--accent:#8a4b2a;--accent-2:#b33a2a;--muted:#6b5847;}
    body{font-family:Inter, Arial, sans-serif;background:var(--bg);color:var(--muted);padding:22px;margin:0;}
    .wrap{max-width:720px;margin:0 auto;background:var(--card);padding:20px;border-radius:12px;box-shadow:0 6px 20px rgba(0,0,0,0.06);}
    h1{color:var(--accent);margin:0 0 10px;font-size:24px;}
    p{line-height:1.6;}
    .main-nav{background-color:var(--accent);border-radius:8px;margin-bottom:20px;overflow:hidden;}
    .main-nav ul{list-style:none;margin:0;padding:0;display:flex;flex-wrap:wrap;justify-content:center;}
    .main-nav a{display:block;padding:12px 18px;text-decoration:none;color:white;font-weight:600;font-size:15px;}
    .main-nav a:hover{background-color:var(--accent-2);}
    .cta-buttons{margin-top:20px;display:flex;gap:12px;}
    .cta-buttons a{display:inline-block;padding:12px 18px;border-radius:8px;text-decoration:none;font-weight:600;}
    .cta-primary{background-color:var(--accent);color:white;}
    .cta-secondary{background-color:transparent;color:var(--accent);border:1px solid var(--accent);}
  </style>
  <div class="wrap">
    <nav class="main-nav">
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="submit.html">Submit a Word</a></li>
        <li><a href="dictionary.html">Public Dictionary</a></li>
        <li><a href="admin.html">Admin Review</a></li>
      </ul>
    </nav>
    
    <h1>Welcome to Voices of the Land</h1>
    <p>This digital tool is a community-driven project dedicated to the preservation and revitalization of the Cree language. It was created as part of a Design Thinking project to address the real-world need for accessible, community-led language preservation.</p>
    
    <h3>How This Site Works</h3>
    <p>This tool is built on a "community-first" model. All information is sourced from and verified by the community.</p>
    <ul>
      <li><strong>Submit a Word:</strong> Community members can submit Cree words, translations, notes, and audio recordings.</li>
      <li><strong>Elder Verification:</strong> Submissions are sent to a private queue. Community Elders review each entry for accuracy and appropriateness.</li>
      <li><strong>Public Dictionary:</strong> Once verified, the entry is published to the Public Dictionary for all learners to access.</li>
    </ul>

    <div class="cta-buttons">
      <a href="submit.html" class="cta-primary">Submit a Word</a>
      <a href="dictionary.html" class.="cta-secondary">View the Dictionary</a>
    </div>

  </div>

