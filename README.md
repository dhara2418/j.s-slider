# j.s-slider
🌙 Smart Image Slider

Interactive, stylish, and beginner-friendly Image Slider Project using pure HTML + CSS + JavaScript.

✨ Features

📁 Image Bank using Array + Objects

⏭️ Next / Previous Navigation

🖥️ Dynamic Display using DOM

🔄 Auto-Play Slider (3s interval)

➕ Add Your Own Slide (URL + Caption)

🎨 Modern UI with gradient text & shadows

🚫 No libraries or frameworks — Pure JavaScript

🧩 Project Structure
📁 Smart-Image-Slider
├── index.html
├── README.md
└── (optional) assets/

📚 Code Overview
🔹 1. Slide Data Structure
const slides = [
    { img: "url", caption: "text" },
];

🔹 2. Display Slide
function showSlide(index) {
    slideImage.src = slides[index].img;
}

🔹 3. Navigation Logic
nextSlide();
prevSlide();

🔹 4. Auto-Play
setInterval(() => nextSlide(), 3000);

🔹 5. Add New Slide
slides.push({ img, caption });

📝 Marking Scheme (Total: 10 Marks)
Component	Marks
Array + Object Image Bank	2
Slider Navigation Logic	2
Display Function (DOM)	2
Extra Feature (Auto-Play / Add Input)	2
GitHub Upload + README.md	2
Total	10 Marks
🚀 Getting Started
1️⃣ Step 1 — Clone the repository
git clone https://github.com/your-username/smart-image-slider.git

2️⃣ Step 2 — Open the project

Open index.html in your browser.

3️⃣ Step 3 — Enjoy the slider

Use Prev / Next

Try Auto-play

Add your own image URL + caption

🛠 Technologies Used

HTML5

CSS3

JavaScript (ES6)

👩‍💻 Author
Dhara Parekh

📌 JavaScript | Frontend | UI Projects
<img width="1920" height="1032" alt="Screenshot 2025-11-18 133250" src="https://github.com/user-attachments/assets/2a1e8472-9907-4fa8-9134-682e34d42d96" />
<img width="1920" height="1032" alt="screen-shot" src="https://github.com/user-attachments/assets/4f59bf6a-916a-42c6-b17c-a256951d6aa5" />

