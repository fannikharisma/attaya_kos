# Attaya Kos Website (`attayakos.my.id`)

The official landing page for **Attaya Kos** housing business. This website is built as a fast, clean, and responsive static web application, hosted seamlessly using **GitHub Pages** with a custom domain.

---

## 🌐 Live URL
* **Website:** [https://attayakos.my.id](https://attayakos.my.id)
* **Hosting Platform:** GitHub Pages

## 🚀 Key Features
* **Responsive Design:** Optimized for mobile (Android/iOS) and desktop viewing.
* **Photo Gallery:** Showcases room conditions, facilities, and the surrounding environment.
* **Facilities Detail:** Up-to-date room specifications (e.g., AC, private bathroom, etc.).
* **Direct Contact Integration:** Instant "Click to Chat" WhatsApp integration for prospective tenants to schedule site visits or ask questions.

## 🛠️ Tech Stack
* HTML5 & CSS3 (for semantic structure and layout styling)

## 💻 Local Development Setup (WSL Linux)

To make content updates or test design modifications locally within your WSL environment before deploying them to GitHub:

1. Navigate to the project directory in your WSL terminal:
   cd ~/projects/personal/attaya-kos
2. Run a local development server:
    Using VS Code Live Server Extension: Open index.html and click the "Go Live" button in the bottom status bar.
    Using Python Built-in Server: Alternatively, spin up a quick Python server via your terminal:
    python3 -m http.server 8080
    Then, open your Windows browser and go to `localhost:8080`.

## 📝 Important Maintenance Notes
* **Line Endings:** Ensure all text file line endings are configured to use **LF** format (Linux standard) instead of CRLF.
* **Custom Domain Lock:** Never delete or alter the **`CNAME`** file in the root directory. Doing so will disconnect the custom domain from GitHub Pages.