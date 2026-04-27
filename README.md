# 📝 Blog Web Application

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/EJS-B4CA65?style=for-the-badge&logo=ejs&logoColor=white" alt="EJS" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/License-ISC-blue?style=for-the-badge" alt="License" />
</p>

<p align="center">
  A clean, elegant, and fully functional Blog Web Application built with <strong>Node.js</strong>, <strong>Express</strong>, and <strong>EJS</strong>.
  <br />
  Create, read, update, and delete your thoughts with a beautiful, responsive UI.
</p>
<img width="947" height="407" alt="image" src="https://github.com/user-attachments/assets/77cc9fc7-c47b-43a0-9e81-a24130427dba" />


---

## ✨ Features

- 🏠 **Home Page** — View all your blog posts in a sleek card-based layout
- ➕ **Create Posts** — Write and publish new blog posts with a title and content
- ✏️ **Edit Posts** — Modify existing posts seamlessly
- 🗑️ **Delete Posts** — Remove posts with a confirmation dialog
- 🎨 **Modern UI** — Clean, minimal design with smooth animations and hover effects
- 📱 **Responsive Design** — Looks great on all screen sizes
- ⚡ **Smooth Transitions** — Page fade-in animations for a premium feel
- 🧩 **Reusable Components** — Partial templates for header and footer

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Node.js** | JavaScript runtime environment |
| **Express.js** | Fast, minimalist web framework |
| **EJS** | Embedded JavaScript templating engine |
| **Body-Parser** | Parse incoming request bodies |
| **CSS3** | Modern styling with animations & transitions |

---

## 📁 Project Structure

```
Blog-Web_Application-Project/
├── index.js                 # Main server & route handlers
├── package.json             # Project metadata & dependencies
├── package-lock.json        # Dependency lock file
├── public/
│   └── styles.css           # Global stylesheet with animations
└── views/
    ├── index.ejs            # Home page — list all posts
    ├── create.ejs           # Create new post form
    ├── edit.ejs             # Edit existing post form
    └── partials/
        ├── header.ejs       # HTML head, meta tags, CSS links
        └── footer.ejs       # Scripts, fade-in effects, closing tags
```

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine (v14 or higher recommended)
- A code editor like [VS Code](https://code.visualstudio.com/)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/razazaheer12/Blog-Web_Application-Project.git
   cd Blog-Web_Application-Project
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the application**
   ```bash
   node index.js
   ```

4. **Open in browser**
   ```
   http://localhost:3000
   ```

---

## 🌐 Application Routes

| Method | Route | Description |
|--------|-------|-------------|
| `GET` | `/` | Home page — displays all blog posts |
| `GET` | `/create` | Render form to create a new post |
| `POST` | `/create` | Submit and save a new post |
| `GET` | `/edit/:id` | Render form to edit a specific post |
| `POST` | `/edit/:id` | Update the selected post |
| `POST` | `/delete/:id` | Delete the selected post |

---

## 🎯 Key Highlights

- **In-Memory Storage**: Posts are stored in a simple array for lightweight, zero-config operation
- **Form Validation**: HTML5 `required` attributes ensure no empty submissions
- **Delete Confirmation**: JavaScript `confirm()` dialog prevents accidental deletions
- **Premium Styling**:
  - CSS reset for consistent cross-browser rendering
  - `Inter` font from Google Fonts for a modern, readable look
  - Card hover effects with subtle elevation and shadows
  - `@keyframes fadeIn` animation for post cards
  - Smooth opacity transition on page load
- **Modular Templating**: EJS partials keep code DRY and maintainable

---

## 📸 Screenshots

> _Add your own screenshots here to showcase the UI!_
><img width="947" height="410" alt="image" src="https://github.com/user-attachments/assets/43b92f27-9ca4-47f2-9d27-06e128f9506c" />

> 1. Home page with post listings
> <img width="949" height="407" alt="image" src="https://github.com/user-attachments/assets/2b35673e-b58b-431f-b0e2-f9fbb37161de" />
> 2. Create post form
> <img width="950" height="411" alt="image" src="https://github.com/user-attachments/assets/7acb7bc2-fd05-485d-aaf5-f36a6c223b64" />
> 3. Edit post form
<img width="950" height="412" alt="image" src="https://github.com/user-attachments/assets/7cfd79df-239b-40c1-8686-6b9279198c46" />

---

## 🔮 Future Enhancements

- [ ] Persist data using MongoDB or a JSON file
- [ ] Add user authentication & sessions
- [ ] Implement post categories and tags
- [ ] Add a rich-text editor (e.g., Quill or TinyMCE)
- [ ] Deploy to Render / Vercel / Railway
- [ ] Add pagination for large post collections
- [ ] Dark mode toggle

---

## 🤝 Contributing

Contributions are always welcome! If you have ideas for improvements or find any issues, feel free to:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **ISC License**. See the [package.json](package.json) for more details.

---

## 👨‍💻 Author

Built with ❤️ by **Raza**  
📧 GitHub: [@razazaheer12](https://github.com/razazaheer12)

---

<p align="center">
  ⭐ Star this repo if you found it helpful!
</p>

