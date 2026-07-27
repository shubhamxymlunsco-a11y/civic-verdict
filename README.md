# civic-verdict
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>The Civic Verdict | Independent Truth & Public Trust</title>
  <style>
    /* Traditional Newspaper Styling with Modern Elements */
    :root {
      --paper-bg: #fdfbf7;
      --ink-black: #111111;
      --accent-red: #b22222;
      --verified-green: #2e7d32;
      --border-line: #222222;
    }

    body {
      background-color: var(--paper-bg);
      color: var(--ink-black);
      font-family: 'Georgia', 'Times New Roman', serif;
      margin: 0;
      padding: 0 20px;
    }

    .wrapper {
      max-width: 1100px;
      margin: 0 auto;
    }

    /* Masthead Header */
    header {
      text-align: center;
      border-bottom: 4px double var(--border-line);
      padding: 20px 0 10px;
    }

    .top-meta {
      display: flex;
      justify-content: space-between;
      font-size: 0.85rem;
      text-transform: uppercase;
      letter-spacing: 1px;
      border-bottom: 1px solid var(--border-line);
      padding-bottom: 5px;
      margin-bottom: 15px;
    }

    h1.newspaper-title {
      font-size: 3.5rem;
      font-family: 'Playfair Display', 'Georgia', serif;
      text-transform: uppercase;
      margin: 0;
      letter-spacing: -1px;
    }

    .tagline {
      font-style: italic;
      font-size: 1.1rem;
      margin-top: 5px;
    }

    /* Newspaper Grid */
    .main-grid {
      display: grid;
      grid-template-columns: 2fr 1fr;
      gap: 30px;
      margin-top: 25px;
    }

    /* Article Cards */
    article {
      border-bottom: 1px solid #ccc;
      padding-bottom: 20px;
      margin-bottom: 25px;
    }

    .category-tag {
      background: var(--ink-black);
      color: #fff;
      font-size: 0.7rem;
      text-transform: uppercase;
      padding: 3px 8px;
      font-family: sans-serif;
      letter-spacing: 1px;
    }

    h2.headline {
      font-size: 2rem;
      margin: 10px 0;
      line-height: 1.2;
    }

    .trust-badge {
      display: inline-block;
      color: var(--verified-green);
      font-weight: bold;
      font-family: sans-serif;
      font-size: 0.85rem;
      margin-bottom: 10px;
    }

    p.paragraph {
      font-size: 1.05rem;
      line-height: 1.6;
      text-align: justify;
    }

    /* QR Code Verification Box */
    .qr-verification-box {
      border: 2px dashed var(--border-line);
      padding: 15px;
      text-align: center;
      background: #f4f1ea;
      margin: 20px 0;
    }

    .qr-verification-box img {
      width: 120px;
      height: 120px;
    }

    .qr-caption {
      font-size: 0.8rem;
      font-family: sans-serif;
      margin-top: 8px;
    }

    /* Opinion Poll Widget */
    .poll-sidebar {
      background: #f7f4ed;
      border: 1px solid var(--border-line);
      padding: 20px;
    }

    .poll-sidebar h3 {
      font-size: 1.3rem;
      text-transform: uppercase;
      border-bottom: 2px solid var(--accent-red);
      padding-bottom: 5px;
      margin-top: 0;
    }

    .poll-option {
      margin-bottom: 15px;
    }

    .poll-button {
      width: 100%;
      background: var(--ink-black);
      color: #fff;
      border: none;
      padding: 10px;
      cursor: pointer;
      font-size: 0.9rem;
      text-align: left;
      transition: background 0.2s;
    }

    .poll-button:hover {
      background: var(--accent-red);
    }

    .progress-bar-container {
      background: #e0e0e0;
      height: 12px;
      width: 100%;
      margin-top: 5px;
      display: none;
    }

    .progress-bar {
      background: var(--verified-green);
      height: 100%;
      width: 0%;
      transition: width 0.5s ease-in-out;
    }

    .percentage-label {
      font-size: 0.8rem;
      font-family: sans-serif;
      display: none;
      margin-top: 3px;
    }

    footer {
      border-top: 4px double var(--border-line);
      text-align: center;
      padding: 20px 0;
      margin-top: 40px;
      font-family: sans-serif;
      font-size: 0.85rem;
    }

    @media (max-width: 768px) {
      .main-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>

<div class="wrapper">
  <!-- Header / Masthead -->
  <header>
    <div class="top-meta">
      <span>Edition: Independent & Unfiltered</span>
      <span>Daily Truth Audit</span>
      <span>Price: Public Good (Free)</span>
    </div>
    <h1 class="newspaper-title">The Civic Verdict</h1>
    <div class="tagline">Fact-Checking Propaganda • Empowering Democratic Choice • Correcting Mistakes</div>
  </header>

  <!-- Main Section Grid -->
  <div class="main-grid">
    
    <!-- News Articles -->
    <main>
      <article>
        <span class="category-tag">Fact Check & Truth Audit</span>
        <h2 class="headline">Evaluating Misinformation in Modern Digital Media Campaigns</h2>
        <div class="trust-badge">✓ Verified Source Data (Trust Score: 98/100)</div>
        
        <p class="paragraph">
          Democracy relies on an informed citizenry capable of identifying biased rhetoric from objective fact. When political campaigns or lobby groups release statistics out of context, public perception becomes skewed. Recognizing where societal choices go off-track begins by directly comparing claims against primary data sources.
        </p>

        <!-- QR Code Integration for Public Trust -->
        <div class="qr-verification-box">
          <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://github.com" alt="Trust Verification QR Code">
          <div class="qr-caption">Scan QR code to inspect raw data sources, citation links, and independent audit trails.</div>
        </div>

        <p class="paragraph">
          Independent media platforms serve as a counter-balance to narrative-driven headlines. By making research records publicly available and opening claims to crowd-sourced verification, citizens can correct public misconceptions and make informed decisions at the ballot box.
        </p>
      </article>
    </main>

    <!-- Democratic Opinion Poll Sidebar -->
    <aside>
      <div class="poll-sidebar">
        <h3>Democratic Voice Poll</h3>
        <p style="font-size: 0.9rem;"><strong>Topic:</strong> Should public funding be strictly mandated for independent, non-partisan fact-checking outlets?</p>
        
        <div class="poll-option">
          <button class="poll-button" onclick="castVote('yes')">A. Yes, to protect independent facts</button>
          <div class="progress-bar-container" id="bar-container-yes">
            <div class="progress-bar" id="bar-yes"></div>
          </div>
          <div class="percentage-label" id="label-yes">0% votes</div>
        </div>

        <div class="poll-option">
          <button class="poll-button" onclick="castVote('no')">B. No, keep media funding private</button>
          <div class="progress-bar-container" id="bar-container-no">
            <div class="progress-bar" id="bar-no"></div>
          </div>
          <div class="percentage-label" id="label-no">0% votes</div>
        </div>

        <p style="font-size: 0.75rem; color: #555; margin-top: 15px;">*Votes are updated in real-time to reflect public democratic consensus.</p>
      </div>
    </aside>

  </div>

  <!-- Footer -->
  <footer>
    <p>&copy; 2026 The Civic Verdict. Free & Open-Source Media Project for Public Literacy.</p>
  </footer>
</div>

<!-- Interactive Poll Logic -->
<script>
  let votes = { yes: 142, no: 38 };

  function castVote(option) {
    votes[option]++;
    const totalVotes = votes.yes + votes.no;

    const yesPercentage = Math.round((votes.yes / totalVotes) * 100);
    const noPercentage = Math.round((votes.no / totalVotes) * 100);

    // Render Progress Bars
    document.getElementById('bar-container-yes').style.display = 'block';
    document.getElementById('bar-container-no').style.display = 'block';
    
    document.getElementById('label-yes').style.display = 'block';
    document.getElementById('label-no').style.display = 'block';

    document.getElementById('bar-yes').style.width = yesPercentage + '%';
    document.getElementById('bar-no').style.width = noPercentage + '%';

    document.getElementById('label-yes').innerText = `${yesPercentage}\% (${votes.yes} votes)`;
    document.getElementById('label-no').innerText = `${noPercentage}\% (${votes.no} votes)`;
  }
</script>

</body>
</html>
