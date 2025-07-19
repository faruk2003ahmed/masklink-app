
# 🕵️‍♂️ MaskLink - Stay Hidden, Stay Connected

MaskLink হল একটি আধুনিক মেসেজিং এবং কলিং ওয়েব অ্যাপ, যেখানে আপনি নিজের পরিচয় গোপন রেখে নিরাপদে চ্যাট ও ভিডিও কল করতে পারবেন — শুধুমাত্র একটি Mask ID দিয়েই!

## 📱 Features

✅ Real-Time Chat (Firebase Realtime Database)  
✅ Secure Video Calling (WebRTC)  
✅ Friend Request System via Mask ID  
✅ Firebase Authentication & Security Rules  
✅ Dark Mode Friendly UI  
✅ Mobile Responsive Design

---

## 🚀 Live Preview

🚧 Coming Soon...

---

## 🔧 Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Firebase Realtime Database, Authentication  
- **Video Call**: WebRTC  
- **Security**: Firebase Rules

---

## 🛠️ Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/masklink.git
   cd masklink

2. Create a Firebase project and enable:

Authentication (Email/Password or Anonymous)

Realtime Database

Hosting (optional)



3. Copy your Firebase config from the console and replace in index.html:

const firebaseConfig = {
  apiKey: "YOUR-KEY",
  authDomain: "YOUR-DOMAIN",
  projectId: "YOUR-ID",
  storageBucket: "YOUR-BUCKET",
  messagingSenderId: "YOUR-ID",
  appId: "YOUR-APP-ID"
};


4. Deploy or run locally by opening index.html in your browser.




---

🔐 Firebase Security Rules (Example)

{
  "rules": {
    ".read": "auth != null",
    ".write": "auth != null"
  }
}


---

📸 Screenshots

> Screenshots coming soon...




---

📄 License

This project is licensed under the MIT License.
Feel free to fork, clone, and contribute!


---

🤝 Contribute

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.


---

🧠 Inspired By

Apps like Telegram Secret Chat, WhatsApp Call — but with Mask Identity!


---

🙏 Disclaimer

MaskLink is built for educational and ethical use only.
Any misuse for illegal activity will be solely the user's responsibility.
We collect no personal data. Privacy is your right, use it responsibly.


---

🌐 Stay Connected

📬 For queries, support, or collaboration: farukahmed20apr2003@gmail.com 
📢 Official Telegram Channel: https://t.me/MuskLinkBD
