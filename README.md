# 3D-Hovering-Button
A colorful, animated web page featuring 3D-styled social media link cards and a dynamic gradient background. Includes smooth hover effects, custom icons, and background music playback for an engaging, interactive UI. Built with HTML, CSS, and JavaScript for a clean, modern look.

🌈 3D Social Media Links with Animated Background & Music

This project is a fun and visually rich web page that combines smooth UI animations, 3D-styled link cards, and a dynamic multicolor gradient background. It’s designed to give users a stylish way to access popular social platforms—Facebook, Twitter (X), Instagram, and YouTube—while also offering an optional ambient music experience.

The page uses only HTML, CSS, and JavaScript, making it easy to understand, modify, and extend. Whether you're exploring creative UI effects or showcasing a flashy landing page, this mini-project gives you a great starting point.

✨ Features

🎨 Animated Gradient Background: A smooth multi-color animation powered by CSS keyframes.

📦 3D-Style Social Link Cards: Hovering rotates and pushes each card forward with shadows for a 3D illusion.

🎵 Ambient Background Music: A music button lets users play a looping background track.

🎭 Smooth Hover Effects: Icons and backgrounds change color when hovered.

🔗 Direct Social Links: Each card opens the respective social platform in a new tab.

🪶 Lightweight & Responsive: Works on all modern browsers with zero frameworks.

📁 Project Structure
/project-folder
│── index.html
│── style.css
│── facebook.png.svg
│── x.png.svg
│── instagram.png.svg
│── youtube.png.svg
│── ethereal-night-loop-274337.mp3


Note: Icons and audio file names must match exactly.

🚀 How It Works
🟦 1. HTML Structure

The HTML file contains:

A Play Music button

An audio element for background music

A centered list of social media cards, each containing an image and label

The list is positioned using transform: translate(-50%, -50%) to keep it perfectly centered.

🎨 2. CSS Styling & Animation

The CSS brings the page to life:

🔸 Gradient Animation
@keyframes gradientBG {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}


This creates a looping rainbow-like background.

🔸 3D Link Card Effect

Each card uses:

skew + rotate transforms

side panels created using :before and :after

hover transitions that lift the card and change colors

This combination gives the illusion of depth.

🎧 3. JavaScript Interaction
playBtn.addEventListener("click", () => {
  music.play();
  playBtn.style.display = "none";
});


A simple event listener hides the button once music starts playing.

No external libraries are required.

🛠️ Usage Instructions

Download or clone the repository

git clone <repo-url>


Make sure the following files are in the same folder:

index.html

style.css

All SVG icons

Music file (.mp3)

Open index.html in any browser
That’s it! No server setup needed.

Click the Play Music button for background audio.

Hover over the cards and click to open social platforms.

🎯 Customization Tips

Want to modify the project? Here are some ideas:

Change the background colors by editing the gradient.

Replace icons to link your own social accounts.

Add more platforms by duplicating a <li> block.

Swap the audio file for your own custom music.

Adjust the hover animation speed in the CSS.

❤️ Why I Made This

This project is meant to be a simple, creative experiment with 3D UI effects and playful animations. It’s fun, unique, and perfect for anyone wanting to explore CSS transforms and interactive elements in a clean and enjoyable way.
