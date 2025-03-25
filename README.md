<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Secure Password Manager</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; }
        h1, h2 { color: #333; }
        code { background: #f4f4f4; padding: 2px 5px; border-radius: 5px; }
        pre { background: #f4f4f4; padding: 10px; border-radius: 5px; overflow-x: auto; }
    </style>
</head>
<body>
    <h1>Secure Password Manager</h1>
    <p>A simple and secure password manager using C++ and SQLite with AES encryption.</p>
    
  <h2>Features</h2>
    <ul>
        <li>Store and retrieve encrypted credentials</li>
        <li>Secure database management using SQLite</li>
        <li>Master password authentication with SHA3-512 hashing</li>
    </ul>

  <h2>Installation</h2>
    <pre><code>git clone https://github.com/yourusername/secure-password-manager.git
cd secure-password-manager
</code></pre>

  <h2>Requirements</h2>
    <pre><code>sqlite3
OpenSSL</code></pre>

  <h2>Usage</h2>
    <p>Run the program using:</p>
    <pre><code>g++ main.cpp -o password_manager -l sqlite3 -lssl -lcrypto
./password_manager</code></pre>

  <h2>Contributing</h2>
    <p>Feel free to contribute by forking the repository and submitting pull requests.</p>
    
  <h2>License</h2>
    <p>MIT License</p>
</body>
</html>
