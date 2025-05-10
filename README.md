# RSA-Chat-Simulator-web-application
A sleek, interactive RSA cryptography project that simulates encrypted chat between users. Built with pure HTML, CSS, and JavaScript, this tool demonstrates RSA key generation, encryption, decryption, and secure message exchange — all in a beautiful web UI.

<!-- Add a screenshot file in your repo named 'screenshot.png' -->

🌟 Features
🔑 RSA Key Generation – Generates public and private keys using random primes.

🔒 Message Encryption & Decryption – Type a message and see it encrypted with RSA.

💬 Chat Simulation – Switch between two users ("adam" and "eve") and send encrypted messages.

🌙 Dark/Light Mode Toggle – Easily switch between light and dark themes.

📜 Step-by-step RSA Explanation – Visual breakdown of the RSA key generation process.

🎨 Responsive UI & Animations – Modern, mobile-friendly design with smooth transitions.

📁 File Structure
bash
Copy
Edit
├── index.html        # Main HTML file with embedded CSS & JavaScript
├── myphoto.jpeg      # Your profile image for the footer (optional)
├── screenshot.png    # (Recommended) Screenshot of the app for preview
└── README.md         # This file
🚀 Getting Started
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/rsa-chat-simulator.git
cd rsa-chat-simulator
Open index.html in your browser:

bash
Copy
Edit
start index.html   # Windows
open index.html    # macOS
xdg-open index.html # Linux
🧪 How It Works
Key Generation: Generates random primes p and q, computes n, ϕ(n), and selects e and d.

Encryption: Each character's Unicode value is encrypted using the public key (e, n).

Decryption: Encrypted integers are decrypted back to characters using the private key (d, n).

Chat: Simulates chat by showing both encrypted and decrypted versions of each message.

🖼 UI Highlights
Chat bubbles show:

Original message

Encrypted form

Decrypted result

Footer with author profile and links

Animations for RSA explanation and messages

👤 Author
Harsh Kholwar
📷 Instagram
💬 WhatsApp
💻 GitHub <!-- Update with your actual GitHub profile URL -->

