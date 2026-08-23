# 🌅 Romantic "Good Morning" Digital Gift ❤️

A luxury, romantic "Good Morning" single-page website created with love for your girlfriend. Designed with soft blush gradients, frosted glassmorphism, animated floating particles (hearts, petals, sparkles), responsive mobile-first typography, and an interactive surprise love letter.

---

## ✨ Features

- **Soft Romantic Aesthetics**: Curated color palette with blush pink, rose quartz, warm champagne gold, and delicate ambient light glows.
- **Glassmorphism Central Card**: Backdrop blur, subtle shimmer sweep animation, and soft ambient drop shadows.
- **Ambient Animated Particles**: High-performance canvas simulation of drifting hearts, falling sakura/rose petals, and twinkling stars.
- **Interactive Surprise Note**: A smooth 3D unfolding love letter triggered by the *"Tap for a little surprise ❤️"* button, accompanied by a confetti burst and gentle synthesized chime.
- **Synthesized Romantic Audio**: Built-in chime & tone effects using the native Web Audio API (zero external audio files needed, works offline and instantaneously).
- **Interactive Touch & Cursor Trail**: Anywhere she taps or moves on screen, mini floating hearts and stardust blossom.
- **Bonus Whispers & Love Counter**:
  - 3 Morning affirmation/whisper pills (*Smile First*, *Warm Hug*, *Always Loved*)
  - *"Tap to send love back"* counter that floats kisses to your heart!
- **100% Standalone & Lightweight**: Single `index.html` file using pure HTML5, CSS3, and vanilla JavaScript. Zero build steps, zero external npm dependencies.

---

## 💌 How to Personalize

You have two easy ways to personalize the message:

### Option 1: Using URL Parameters (Instant & No Code Editing)
You can directly send her a personalized link by adding parameters at the end of the URL:

```text
https://yourusername.github.io/PrivateThinks/?name=jaan&from=Pradeep
```

Supported URL parameters:
- `?name=` or `?her=` : Her name or pet name (e.g. `Priya`, `jaan`, `Angel`, `My Love`)
- `?from=` or `?me=` : Your name (e.g. `Pradeep`, `Yours Forever`)
- `?title=` : Custom main heading
- `?subtitle=` : Custom subtitle
- `?msg=` : Custom romantic paragraph
- `?quote=` : Custom highlighted quote line
- `?surprise=` : Custom secret reveal message

### Option 2: Editing `index.html` Directly
Open `index.html` and look for the `CONFIG` block inside the `<script>` tag near line 510:

```javascript
const CONFIG = {
  // Girlfriend's name / pet name
  girlfriendName: "jaan",
  
  // Your name / signoff
  senderName: "Yours Always",
  
  // Main Section Texts
  mainHeading: "Good Morning, My Love ❤️",
  mainSubtitle: "To the most beautiful person in my world ✨",
  
  // Heartfelt paragraph
  romanticMessage: "As the gentle morning sun paints the world with light...",
  
  // Highlighted Quote Line
  highlightQuote: "“You are my favourite thought every morning. ❤️”",
  
  // Surprise Message inside the secret note
  surpriseMessage: "If I could choose one place to be this morning,\nit would be right beside you. 🥰",
  surpriseSignoff: "Have the most amazing day, {name}. ❤️",
  
  // Sound Enabled by default
  soundEnabled: true
};
```

---

## 🚀 How to Host on GitHub Pages (2 Minutes)

1. Push this repository to GitHub:
   ```bash
   git add .
   git commit -m "Add romantic good morning website"
   git push origin main
   ```
2. Go to your repository on GitHub.
3. Click **Settings** (gear icon) > **Pages** (on the left menu).
4. Under **Branch**, select `main` and folder `/ (root)`, then click **Save**.
5. In ~1 minute, GitHub will give you a live URL like:
   `https://<your-username>.github.io/<repo-name>/`
6. Send the link to your girlfriend in the morning! 💌

---

## 📱 Mobile & Desktop Friendly
Designed mobile-first to look flawless when opened directly from WhatsApp, Telegram, iMessage, Instagram DM, or browser on iPhone and Android.
