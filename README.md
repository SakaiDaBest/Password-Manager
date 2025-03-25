<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>🔐 Secure Password Manager (C++)</h1>

<p>This is a command-line-based Secure Password Manager written in C++. It allows users to store and retrieve passwords securely using AES encryption and SQLite.</p>

<h2>🚀 Features</h2>
    <ul>
        <li>🔑 Secure password storage using AES-256 encryption</li>
        <li>📄 Master password authentication with SHA3-512 hashing</li>
        <li>📁 SQLite database for storing credentials</li>
        <li>🛠 CRUD operations: Add, View, Update, and Delete passwords</li>
    </ul>

<h2>🛠 Requirements</h2>
    <ul>
        <li>C++ compiler (G++/MSVC/Clang)</li>
        <li>SQLite3 library</li>
        <li>OpenSSL for AES encryption</li>
    </ul>

<h2>📦 Setup Instructions</h2>

<h3>1. Clone this repository</h3>
    <pre><code>git clone https://github.com/yourusername/password-manager.git
cd password-manager</code></pre>

<h3>2. Install dependencies</h3>
    <ul>
        <li>Windows: Use <code>vcpkg</code> to install OpenSSL and SQLite</li>
        <li>Linux/macOS: Install via package manager
            <pre><code>sudo apt install libsqlite3-dev libssl-dev</code></pre>
        </li>
    </ul>

 <h3>3. Compile the project</h3>
    <pre><code>g++ main.cpp -o password_manager -l sqlite3 -lssl -lcrypto</code></pre>

 <h3>4. Run the Password Manager</h3>
    <pre><code>./password_manager</code></pre>

 <h2>✅ Functionality</h2>
    <ol>
        <li>Authenticate with a master password</li>
        <li>Encrypt and store passwords securely</li>
        <li>Retrieve and decrypt stored passwords</li>
        <li>Update and delete credentials</li>
    </ol>

 <h2>🧠 Credits</h2>
    <ul>
        <li>C++ – Core language</li>
        <li>SQLite – Database storage</li>
        <li>OpenSSL – AES encryption</li>
    </ul>

 <h2>⚠️ Legal</h2>
    <p>This tool is for <strong>personal and educational use only</strong>. Ensure you comply with data protection laws.</p>
</body>
</html>
