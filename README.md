<div align="center">

  <img src="https://img.shields.io/badge/✨%20Vibe%20Coded-100%25-8A2BE2?style=for-the-badge" alt="Vibe Coded" />
  <br />
  <br />

  <h1>⚡ SyncPad v11 - Ultimate</h1>
  
  <p>
    <strong>The ultimate serverless pastebin. SyncPad lets you edit, sync, and share code snippets or notes in real-time with anyone, anywhere.</strong>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Security-End--to--End%20Encrypted-success?style=flat-square" alt="Security" />
    <img src="https://img.shields.io/badge/Tech-WebRTC%20%7C%20PeerJS%20%7C%20PrismJS-blue?style=flat-square" alt="Tech Stack" />
    <a href="https://github.com/shubhambelbase/SyncPad/stargazers">
      <img src="https://img.shields.io/github/stars/shubhambelbase/SyncPad?style=social" alt="Stars" />
    </a>
  </p>

  <h3>
    <a href="https://syncnotepad.netlify.app/">🔴 View Live Demo</a>
  </h3>
</div>

## ⚡ The Vibe

This isn't just a notepad; it's a **shared brain with a voice**. Vibe coded to feel sleek and futuristic, SyncPad v11 reinvents the pastebin experience.

Built entirely in the flow state, **v11 (Ultimate)** pushes the limits of client-side technology—handling real-time keystroke synchronization, live code highlighting, and **integrated secure messaging** without a single backend server. It's just you, your notes, and your chat.

## 💡 What It Does

**SyncPad** establishes a secure, direct connection between multiple users (Host & Guests).

* **The Problem:** Traditional pastebins are static (read-only), chat apps ruin code formatting, and sending files back and forth is slow.
* **The Solution:** A browser-based, instant collaboration tool. Open the link, paste your code, and **chat securely** while you edit together. **Privacy by design.**


## ✨ Key Features

| 🛡️ **Security & Communication** | 📝 **Ultimate Paste Control** |
| :--- | :--- |
| **💬 Session Chat:** Built-in, encrypted instant messaging | **Syntax Highlighting:** Auto-detects and colors code |
| **Host Approval:** You decide who connects to your session | **Smart Tab:** Indent code blocks perfectly |
| **Guest Lock:** Host can freeze guest editing instantly | **Auto-Scroll Sync:** Viewports stay aligned automatically |
| **E2E Encryption:** Data & Chat flows directly via WebRTC | **Auto-Save:** Never lose work; caches to local storage |
| **Magic Link:** One-click join via URL parameters | **Vibe Themes:** Toggle between clean Light and deep Dark mode |

## 🛠️ Built With

* **WebRTC (PeerJS):** For low-latency, encrypted P2P text & chat synchronization.
* **PrismJS:** For beautiful, lightweight syntax highlighting.
* **TailwindCSS:** For the glassmorphism UI and responsive design.
* **Vanilla JS:** Zero framework bloat for maximum performance on any device.

## 🚀 How to Run

Because this app uses WebRTC, **it works best via HTTPS** or `localhost`.

### Option 1: GitHub Pages / Netlify (Easiest)
1.  Fork this repo.
2.  Deploy to **GitHub Pages** or **Netlify**.
3.  Open the link on two devices (one as **Host**, one as **Joiner**).

### Option 2: Local Network
1.  **Clone the repo:**
    ```bash
    git clone [https://github.com/shubhambelbase/SyncPad.git](https://github.com/shubhambelbase/SyncPad.git)
    ```
2.  **Navigate to folder:**
    ```bash
    cd SyncPad
    ```
3.  **Run with a live server:**
    (VS Code "Live Server" extension is recommended)
    ```bash
    # Or using Python 3
    python -m http.server 8000
    ```

## 📖 How to Use

1.  **Host Mode (Owner):**
    * Open the app and click **"Start Session"**.
    * Copy the **4-digit Room Code** or the **Magic Link**.
    * (Optional) Use the **Lock** icon to make the note read-only for guests.

2.  **Join Mode (Guest):**
    * Enter the 4-digit code in the "Join" box (or just click the Magic Link).
    * Wait for the Host to **Approve** your connection.
    * Start typing! Your cursor and text sync instantly.
    * **Use the Chat Sidebar** to discuss the code or notes in real-time!

## 🤝 Contributing

Got an idea to make this even more "Vibe Coded"?
1.  Fork it.
2.  Create your Feature Branch (`git checkout -b feature/FileSharing`)
3.  Commit your Changes.
4.  Push to the Branch.
5.  Open a Pull Request.

---

<div align="center">
  <p>Vibe coded with ❤️ by <a href="https://github.com/shubhambelbase">Shubham Belbase</a></p>
</div>
