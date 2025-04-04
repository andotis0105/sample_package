# sample_package

Instructional_Content_Package/
│
├── README.md
│   → This file! It explains how to use the contents of this package.
│
├── drag-and-drops/
│   └── fruit-match/
│       ├── index.html           → The main drag-and-drop activity.
│       ├── style.css            → The styling (colors, fonts, layout).
│       ├── script.js            → The interactive functionality.
│       ├── instructions.md      → Instructions for how to embed or use this activity.
│       └── preview.png          → Screenshot of what the activity looks like.
│
├── quizzes/
│   └── module1-quiz/
│       ├── index.html           → Quiz HTML file (can be embedded).
│       ├── questions.json       → The actual quiz questions/data.
│       ├── style.css            → Quiz styling.
│       └── instructions.md      → How to use and/or edit the quiz.
│
└── media-assets/
    ├── images/                  → Any image files used in the activities.
    └── audio/                   → Any audio files used (instructions, cues, etc).


# 🍎 Instructions: Fruit Match Drag-and-Drop Activity

This folder contains a simple drag-and-drop activity where students match fruit names to images. Here's how to preview it, customize it, and embed it into Canvas or your LMS.

---

## ✅ What's in this folder:
- `index.html` → The activity page. This is the file you’ll use to embed.
- `style.css` → Styling for colors, fonts, layout. Optional to edit.
- `script.js` → The JavaScript that makes the drag-and-drop work.
- `preview.png` → A screenshot of the finished activity.
- This `instructions.md` file!

---

## 👀 How to Preview the Activity
You can preview it in two ways:

### Option A: Double-click `index.html`
If you’ve downloaded the folder to your computer, just double-click `index.html` to open it in your browser.

### Option B: Use an Online Code Editor (like CodePen or GitHub Pages)
Upload the HTML, CSS, and JS to a web editor to see it live online.

---

## 🔗 How to Embed in Canvas

### Option 1: Embed Using an Iframe (Recommended)
1. Upload the folder to a **hosting platform** (e.g., your school’s file server, GitHub Pages, or another web host).
2. Copy the **URL** of the live `index.html` file.
3. In Canvas:
    - Go to your course and edit a **Page**.
    - Switch to **HTML Editor** view (click `</>` or "HTML" tab).
    - Paste this code, replacing the `src` with your own URL:
      ```html
      <iframe src="https://yourhost.com/path/to/fruit-match/index.html" width="100%" height="500px"></iframe>
      ```
4. Save the page. Done!

### Option 2: Upload as a File
Canvas sometimes supports uploading HTML files directly, but **functionality can be limited** if JS is involved. Ask your LMS admin if unsure.

---

## 🛠️ Customization Tips

- Want to change the fruit names or images? Edit `index.html` directly.
- Want to adjust fonts/colors? Modify `style.css`.
- Be careful editing `script.js` unless you're comfortable with JavaScript.

---

## 💬 Need Help?
Contact the instructional design team or your friendly neighborhood tech-savvy sidekick (probably someone named K 😎).

---

