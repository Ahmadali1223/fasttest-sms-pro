
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FastTest SMS Pro</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0b1020;
      color: white;
    }
    header {
      background: #151d35;
      padding: 22px;
      text-align: center;
    }
    h1 { color: #57e3b0; }
    main {
      max-width: 600px;
      margin: 35px auto;
      padding: 20px;
    }
    .card {
      background: #18233d;
      border-radius: 14px;
      padding: 22px;
      margin-bottom: 20px;
    }
    input, textarea, button {
      box-sizing: border-box;
      width: 100%;
      padding: 13px;
      margin-top: 12px;
      border-radius: 8px;
      border: 1px solid #40506c;
      font-size: 16px;
    }
    button {
      background: #28c995;
      color: #08151b;
      border: 0;
      font-weight: bold;
    }
    footer {
      text-align: center;
      color: #aab5cb;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>FastTest SMS Pro</h1>
    <p>Bulk SMS Reseller Platform</p>
  </header>
  <main>
    <section class="card">
      <h2>Welcome</h2>
      <p>Manage your SMS business from one dashboard.</p>
      <p>Pakistan & International Messaging</p>
    </section>
    <section class="card">
      <h2>SMS Dashboard Preview</h2>
      <label for="phone">Test recipient number</label>
      <input id="phone" type="tel" placeholder="+923XXXXXXXXX">
      <label for="message">Message</label>
      <textarea id="message" rows="4"
        placeholder="Type your message"></textarea>
      <button onclick="alert('Demo only. SMS provider API is not connected yet.')">
        Test Dashboard
      </button>
      <p>This is a demo. No SMS will be sent.</p>
    </section>
  </main>
  <footer>FastTest SMS Pro &copy; 2026</footer>
</body>
</html>
