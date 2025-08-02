# SHE_BUILD

# 🌸 AuraRoomie – Frontend

AuraRoomie is a vibrant, voice-powered roommate matching platform made exclusively for women. The frontend is built using **HTML, CSS, and JavaScript**, designed with bright, inclusive aesthetics and voice interaction capabilities to enhance user experience and accessibility.

---

## 🌟 Key Features (Frontend)

### 🧠 1. Omnidimensional User Introduction Form
- Users sign up by entering:
  - Basic info: name, age, location, profession.
  - Personal traits: likes, dislikes, lifestyle habits.
  - Preferences in a roommate.
- The form data is later analyzed using the NLP backend for compatibility scoring.

### 🎙️ 2. Voice-Based Introduction (Google Web Speech API)
- Users can **speak their introduction** instead of typing it.
- Voice input is transcribed and saved as part of the user's roommate profile.
- This helps add a more human, personal touch to matching.

### 🧪 3. Optional Quiz for Personality Assessment
- A short, visual quiz helps the algorithm understand deeper personality traits.
- Results are also factored into compatibility scoring.

### 💬 4. Compatibility Result Page
- After signup, users are shown:
  - A list of **highly compatible roommate matches** (80%+).
  - **Compatibility percentage**.
  - Breakdown of **trait similarities and differences**.
- Includes an option to **initiate a chat** with matched users.

### 🏡 5. Modern Women-Focused UI
- All pages (login, signup, compatibility) use:
  - Soft pinks, purples, and pastel gradients.
  - Rounded cards, big buttons, and friendly typography.
  - Images of real women and inclusive cartoon illustrations.
- Designed to feel **safe, empowering, and modern**.

---

## 📁 Folder Structure

```
AuraRoomie-Frontend/
├── index.html             # Landing Page
├── signup.html            # Signup Form
├── login.html             # Login Page
├── voice-intro.html       # Voice-Based Introduction
├── compatibility.html     # Compatibility Result Page
├── chat.html              # Chat UI (frontend only)
├── styles/
│   ├── index.css
│   ├── signup.css
│   ├── voice.css
│   ├── compatibility.css
│   └── chat.css
└── assets/
    ├── images/            # Women-centric images & illustrations
    └── icons/             # Icons used in buttons and nav
```

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** (Custom + Flexbox/Grid)
- **JavaScript**
- **Google Web Speech API** (Voice input)
- Designed for seamless integration with:
  - Node.js + Express.js Backend
  - MongoDB Database
  - Python Flask NLP Microservice (spaCy)

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/sakkshhiii/SHE_BUILD
   cd AuraRoomie-Frontend
   ```

2. Open `index.html` in your browser.
3. Use the form or voice input to simulate a user flow.
4. Ensure backend is connected to see compatibility results and matches.

---

## 🧩 Next Steps (For Devs)

- Connect to backend APIs for:
  - NLP-based compatibility scoring
  - Real-time chat
  - Auth & session management
- Make responsive for mobile screens (future enhancement)

---

## 🙋‍♀️ Made For
**Women looking for safe, compatible living spaces.**  
Backed by voice AI, smart design, and inclusivity.

---

## 👩‍💻 Developed By
A hackathon project built with ❤️ by Binary-Brains developers passionate about safe co-living solutions for women.
