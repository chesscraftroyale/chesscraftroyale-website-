# chesscraftroyale-website-
<!DOCTYPE html>
<html>
<head>
    <title>ChessCraft Royale</title>
</head>
<body>
    <h1>Welcome to ChessCraft Royale!</h1>
    <p>This is our website.</p>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ChessCraft Royale - Legal Documents</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #111;
      color: #fff;
      padding: 15px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #222;
    }
    nav button {
      background: none;
      border: none;
      color: #fff;
      padding: 14px 20px;
      cursor: pointer;
      font-size: 16px;
    }
    nav button.active {
      background: #444;
    }
    section {
      padding: 20px;
      display: none;
    }
    section.active {
      display: block;
    }
    h2 {
      color: #111;
      margin-top: 20px;
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #111;
      color: #fff;
      font-size: 14px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>ChessCraft Royale - Legal Documents</h1>
  </header>

  <nav>
    <button class="active" onclick="showSection('terms')">Terms of Use</button>
    <button onclick="showSection('privacy')">Privacy Policy</button>
  </nav>

  <!-- Terms Section -->
  <section id="terms" class="active">
    <h2>Terms of Use</h2>
    <p>Welcome to <b>ChessCraft Royale</b>. By using this app, you agree to follow the rules and conditions stated below. Please read carefully.</p>
    <h3>1. Acceptance</h3>
    <p>By accessing or using ChessCraft Royale, you accept these Terms fully. If you disagree, please stop using the app.</p>
    <h3>2. Usage</h3>
    <p>You agree not to misuse the app, cheat, or violate fair play. Any abuse may result in account suspension.</p>
    <h3>3. Ads and Rewards</h3>
    <p>The app is free to play and monetized through ads and in-game coins. There is no premium membership.</p>
    <h3>4. Tournaments</h3>
    <p>Weekly, Monthly, and Grandmaster tournaments follow fair-play rules. Winners and runners-up automatically qualify for the next tier.</p>
    <h3>5. Intellectual Property</h3>
    <p>All designs, features, and logos belong to Team ChessCraft Royale.</p>
    <h3>6. Termination</h3>
    <p>We may suspend or terminate accounts that break these rules.</p>
    <h3>7. Governing Law</h3>
    <p>These Terms are governed by Indian law.</p>
  </section>

  <!-- Privacy Section -->
  <section id="privacy">
    <h2>Privacy Policy</h2>
    <p>Your privacy is important to us. This Privacy Policy explains how we handle your data.</p>
    <h3>1. Information We Collect</h3>
    <p>We collect limited information such as login via Google/Facebook, and in-game progress data. We do not sell personal data.</p>
    <h3>2. Usage of Data</h3>
    <p>Data is used to provide gameplay, save progress, improve features, and ensure fair tournaments.</p>
    <h3>3. Third-Party Services</h3>
    <p>The app uses third-party services (like ads) that may collect anonymous data.</p>
    <h3>4. Delete My Account</h3>
    <p>Players have the right to request account deletion. The app includes a "Delete My Account" button. Once used, your account and related data will be removed.</p>
    <h3>5. Children</h3>
    <p>Child mode is available optionally with ChessCraft Academy AI. Parents/guardians should guide children in use.</p>
    <h3>6. Updates</h3>
    <p>We may update this policy from time to time. Any major updates will be shown inside the app.</p>
  </section>

  <footer>
    &copy; 2025 Team ChessCraft Royale. All Rights Reserved.
  </footer>

  <script>
    function showSection(id) {
      document.querySelectorAll("section").forEach(sec => sec.classList.remove("active"));
      document.querySelectorAll("nav button").forEach(btn => btn.classList.remove("active"));
      document.getElementById(id).classList.add("active");
      event.target.classList.add("active");
    }
  </script>
</body>
</html>
