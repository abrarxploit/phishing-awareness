# Phishing Awareness Campaign

This project is a static phishing simulation built to educate users on online scams. It safely mimics a real-world phishing scenario and redirects users to an awareness page — no data is collected.

---

## 🎯 Objective

- Help users recognize and avoid phishing links.
- Simulate a real-world social engineering trap.
- Educate visitors immediately after interaction.

---

## 🛠 Tools & Technologies Used

- HTML, CSS & JavaScript (Frontend only)
- Firebase Hosting (Free, secure static site hosting)
- Docker + Firebase CLI (Deployment environment)
- Bitly / TinyURL (Short, realistic link)

---

## 📁 Project Structure

```
Phishing-awareness-campaign/
├── public/
│   ├── index.html       # Final deployed phishing simulation
│   └── thanks.html      # Awareness page shown after redirect
├── source-code/
│   ├── index.html       # Editable source code
│   └── thanks.html      # Editable source code
├── README.md
```

---

## 🚀 Deployment Instructions

Follow these exact steps to deploy this simulation:

### 1. Clone the repository
```bash
git clone https://github.com/abrarxploit/phishing-awareness.git
cd phishing-awareness
```

### 2. Set up Firebase
```bash
npm install -g firebase-tools
firebase login --no-localhost
```

### 3. Initialize Firebase Hosting
```bash
firebase init hosting
# - Choose existing or create new Firebase project
# - Set `public` as public directory
# - Set as a single-page app (rewrite to index.html)
```

### 4. Copy your deployment-ready files
```bash
cp source-code/index.html public/index.html
cp source-code/thanks.html public/thanks.html
```

### 5. Deploy your project
```bash
firebase deploy
```

---

## 🔗 Demo

Test link:

https://tinyurl.com/gulistan-news-jk


---

## ⚠️ Disclaimer

This is a cybersecurity awareness tool meant only for educational and demonstrative purposes. Do not misuse this project for unethical activities or data collection.

---

## 👤 Author

**Abrar**  
🔗 [LinkedIn](https://www.linkedin.com/in/abrardar)

