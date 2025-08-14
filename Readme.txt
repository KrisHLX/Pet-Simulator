 Virtual Pet Simulation Game 

Hey there!  
This is my web development project for creating a **Virtual Pet Simulator** using HTML, CSS, and JavaScript.  
The idea was to build an interactive pet (mine is a cat 🐱) that users can take care of by feeding it, exercising it, and putting it to sleep.

---

## 🎯 Features Implemented

- ✅ Virtual pet character (a cute animated cat!)
- ✅ Hunger, Happiness, and Energy stats
- ✅ Real-time progress bars that update as the pet's state changes
- ✅ Buttons to interact: **Eat**, **Exercise**, and **Sleep**
- ✅ Custom backgrounds for each action (feeding, walking, sleeping)
- ✅ Animations using Phaser.js (idle, walk, fall, hurt)
- ✅ Automatic stat decay over time
- ✅ Pet reactions + messages (e.g., when hungry or tired)
- ✅ Special message when sleeping: `"I'm sleeping now, don't disturb me 💤"`
- ✅ Sleep lasts until user clicks another action (like feeding or exercise)

---

## 📁 How to Run

1. Unzip the project folder.
2. Open `index.html` in any modern browser (preferably Chrome).
3. No installations required—everything works in the browser!

---

## 🧠 Tech Used

- HTML5 + CSS3
- JavaScript (vanilla)
- [Phaser 3](https://phaser.io/) for animations
- Cute pixel assets for the cat animations and background scenes

---

## 💡 How It Works

- Hunger, happiness, and energy decrease slowly over time.
- Feed the cat to refill hunger.
- Exercise to boost happiness.
- Let it sleep to restore energy.
- If any stat drops too low, the cat plays a sad/hurt animation.
- Once all stats are okay, it goes back to idle automatically.

---

## 👩‍💻 Folder Structure

project-folder/  
│  
├── assets/  
│   ├── Fall/  
│   ├── hurt/  
│   ├── idle/  
│   ├── walk/  
│   ├── foodbowl.png  
│   ├── table.png  
│   ├── kitchenbg.jpg  
│   ├── walkbg.jpg  
│   └── sleepbg.jpg  
│  
├── index.html  
└── README.md  

---

## 🙌 Final Notes

This was a super fun project and I’ve tried to cover all requirements in the brief.  
Let me know what you think! ✨