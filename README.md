# Genuary-Art-Gallery-Website
Gallery website created to display all p5.js generative art designed for Genuary 2025.

Author: Timothy Johnson <br>
Date: January 2025


### 🔗 Live Demo

[Genuary 2025 Generative Art Gallery](https://mrtimmyj-art.netlify.app/)

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;A visually immersive, browser-based gallery to showcase all 31 days of the Genuary 2025 generative art challenge.
Each artwork is created using p5.js, then embedded into a modern, responsive HTML/CSS/JavaScript website with a canvas-first presentation.

&nbsp;&nbsp;&nbsp;&nbsp;This project is a canvas-driven gallery designed to display 31 generative art pieces made during Genuary 2025, a month-long creative coding challenge.
Each piece was built using p5.js, and the website acts as both an art showcase and a technical artifact of the creative journey.

This digital exhibition not only reflects a month of creative exploration in generative design, but also serves as a personal milestone in learning creative coding and frontend web technologies.

🧩 Features

    🖼️ Grid-Based Art Display: CSS Grid powers a responsive, interactive gallery layout

    🌙 Dark Mode Toggle: User-friendly night mode with JavaScript toggle

    🎨 Canvas-Based Artwork: Each art piece is embedded in a dedicated HTML page using p5.js

    🖱️ Interactive Thumbnails: Clickable art previews link directly to full canvas experiences

    📁 Organized by Day: Clear structure following Genuary's day-by-day format

    🧹 Minimalist Aesthetic: Emphasizes artwork with a clean, gallery-style interface

🔄 User Workflow

    Open the homepage (index.html)

    Browse through the art thumbnails displayed in the grid

    Click any piece to open a full canvas view in its own page

    Toggle dark/light mode as desired

    Explore all 31 days of generative art

📁 Code Structure

.<br>
genuary-2025-gallery/<br>
├── index.html &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Main grid gallery page<br>
├── about.html &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Info/about page<br>
├── gallery.html &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Gallery list view of projects<br>
├── res/
│   ├── style.css &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Core gallery styles<br>
│   ├── images/ &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Art thumbnails used in the grid<br>
│   ├── src/<br>
│   │   └── dark-mode.js &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Dark mode logic<br>
│   │   └── nav-menu.js &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Navigational menu logic<br>
│   │   │   ├── day1/<br>
│   │   │   └── day1-art.js &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Navigational menu logic<br>
│   │   │   ├── day2/<br>
│   │   │   └── ...<br>
├── art/<br><br>
│   ├── day1/<br>
│   │   └── art1.html &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Full canvas p5.js sketch<br>
│   ├── day2/<br>
│   │   └── art1.html<br>
│   └── ...<br>
├── 

⚙️ How It Works

🧱 Gallery Grid

    Uses display: grid to layout art pieces in a stylized mosaic

    Each grid item is a clickable <div> with a background-image and JS onclick handler

🖼️ Full Artwork Pages

    Each day's sketch lives in a dedicated art/dayX/art1.html

    p5.js runs the sketch on a full-viewport canvas

    Files are grouped per day for clarity and scalability

🌙 Dark Mode

    Simple JavaScript toggle linked to a CSS class

    Button click toggles the dark-mode class across the entire site

🖼️ Screenshots / Visuals

![genuarybannertrans](https://github.com/user-attachments/assets/05f55569-fb9e-427c-9c90-c5f069d484d3)

🧰 Technologies Used

    🎨 HTML/CSS	Core structure and layout
    
    🖼️ p5.js	Generative art rendering framework
    
    🧪 JavaScript	Dark mode toggle, grid click handlers
    
    📸 Canvas API	Embedded in each artX.html using p5.js

🚀 Getting Started

    To clone and run this project locally:

      git clone https://github.com/MrTimmyJ/Genuary-Art-Gallery-Website
      cd Genuary-Art-Gallery-Website/index.html

🪪 License

This open-source project is available under the [MIT License](https://opensource.org/license/mit).
