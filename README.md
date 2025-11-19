# 🌌 Solar System Animation — HTML & CSS

A beautiful and interactive **Solar System animation** built entirely using **HTML** and **CSS**.  
This project demonstrates the power of CSS animations, transforms, and keyframes to create smooth orbital motion without using JavaScript.

---

## 🚀 Features

- 🌞 Glowing Sun at the center  
- 🪐 Smooth orbit animations for all planets  
- 🌍 Each planet has unique colors and orbit speeds  
- 🔄 Pure CSS Keyframe animation (No JavaScript!)  
- 🎨 Clean and minimal space-themed UI  
- 📱 Responsive design for all screen sizes  

---

## 📸 Preview

*(Insert your screenshot here)*  
Example:  
```
assets/solar-system-preview.png
```

---

## 🛠️ Technologies Used

- **HTML5**
- **CSS3**
  - Keyframe animations  
  - Transform properties  
  - Circular orbits with border-radius  
  - Animation delays for realistic motion  

---

## 📂 Project Structure

```
Solar-System-Animation/
│── index.html
│── style.css
│── README.md
└── assets/
      └── (optional images or media)
```

---

## ⚙️ How It Works

- Each planet is a `<div>` with a specific size and color.
- Orbits are created using CSS circles.
- CSS `@keyframes` is used to rotate each planet around the Sun.
- Different **animation durations** simulate planet speeds.

Example animation logic:

```css
@keyframes orbit {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
```

Each planet is given:
- A custom orbit size  
- A rotation speed  
- A color  

---

## ▶️ How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/solar-system-animation.git
   ```

2. **Navigate to the folder:**
   ```bash
   cd solar-system-animation
   ```

3. **Open in browser:**
   Simply double-click the `index.html` file.

No installations or dependencies required.

---

## 🌐 Live Demo

If hosted on GitHub Pages, add link here:

🔗 **Live Demo:** Coming Soon…

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is released under the **MIT License**.

---

## 👤 Author

**Your Name**  
- GitHub: [your-username](https://github.com/your-username)  
- LinkedIn: [your-linkedin](https://linkedin.com/in/your-link)  

---

⭐ *If you found this project helpful, please give it a star!*  
