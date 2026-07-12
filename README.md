Rae-Medye-Official/
├── index.html
├── about.html
├── music.html
├── videos.html
├── gallery.html
├── contact.html
├── style.css
├── script.js
├── netlify.toml
├── README.md
│
├── images/
│   ├── logo.png
│   ├── hero.jpg
│   ├── rae-medye.jpg
│   └── background.jpg
│
├── music/
│   ├── peace-be-unto-you.mp3
│   ├── peace-of-mind.mp3
│   ├── seasons-and-times.mp3
│   ├── boost-me-up.mp3
│   ├── made-for-me.mp3
│   └── feelings.mp3
│
└── assets/
    ├── icons/
    └── font/
        [build]
publish = "."

[[redirects]]
from = "/*"
to = "/index.html"
status = 200
