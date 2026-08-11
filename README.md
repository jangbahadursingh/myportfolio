# 🎓 Student Resume | Intro

A modern, responsive **Student Resume / Portfolio website** built with **HTML, CSS, and JavaScript**.

## 🌟 Live Preview

🚀 **Live Demo:** Add your deployed website URL here.

## 📌 About The Project

This project is a responsive student resume website designed to present a student's introduction, profile, current learning areas, projects, education, skills, certifications, interests, and social links.

The supplied `index.html` is a self-contained front-end project with embedded CSS and JavaScript. It includes responsive layouts for desktop, tablet, and mobile devices.

## ✨ Features

- 🧑‍🎓 Student profile and qualification section
- 🖼️ Profile photo support using `profile.jpg`
- 🧭 Responsive desktop navigation
- 📱 Hamburger menu for mobile devices
- ⌨️ Animated **Now Learning** typing section
- 🚀 Projects showcase with technology chips
- 🎓 Education timeline
- 📂 Expandable Details / accordion sections
- 🍃 Animated falling-leaves background
- 🎨 Gradient dark UI with animations
- ♿ ARIA labels and keyboard-friendly controls
- 📴 Reduced-motion support
- 📱 Responsive desktop, tablet, and mobile layouts

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure |
| **CSS3** | Styling, responsive layout and animations |
| **JavaScript** | Mobile menu and typing animation |
| **Google Fonts – Poppins** | Typography |
| **SVG** | Icons and visual elements |

## 📁 Project Structure

```text
student-resume/
│
├── index.html
├── profile.jpg
└── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Example:

```bash
git clone https://github.com/YOUR_USERNAME/student-resume.git
```

### 2. Open the Project

```bash
cd student-resume
```

### 3. Add Your Profile Photo

Place your photo beside `index.html`:

```text
student-resume/
├── index.html
├── profile.jpg
└── README.md
```

The header uses:

```html
<img src="profile.jpg" alt="Student profile photo">
```

### 4. Run the Website

No package installation is required for this static project.

Simply open `index.html` in a browser, or use **VS Code Live Server**.

## ⌨️ Customize the “Now Learning” Section

The current JavaScript contains:

```javascript
const roles = [
    'Web Development',
    'UI/UX Design',
    'Front-End Engineering',
    'JavaScript & Animations'
];
```

For a Python/Flask-focused profile, you can change it to:

```javascript
const roles = [
    'Python',
    'Flask',
    'Web Development',
    'HTML & CSS',
    'JavaScript',
    'MySQL',
    'Git & GitHub'
];
```

## ✏️ Customize Your Resume

Update the following sections in `index.html`:

### Student Name

```html
<div class="profile-name">JANG BAHADUR SINGH</div>
```

### Qualification / Role

```html
<div class="profile-title">MCA(INTEGRATED) • Front-End Developer</div>
```

### Projects

The Projects section currently contains:

- Resume Builder
- Student Dashboard
- Portfolio Landing

Replace these with your actual projects and add GitHub/Live Demo links.

### Education

Replace the sample education timeline with your actual:

- Degree
- Institution
- Department
- Study period

### Skills

Update the Details → Skills section with your real technologies, such as:

```text
Python
Flask
HTML
CSS
JavaScript
MySQL
Git
GitHub
```

### Social Links

Replace the placeholder `href="#"` values with your actual GitHub, LinkedIn, and email links.

Example:

```html
<a href="YOUR_GITHUB_URL" aria-label="GitHub">
```

```html
<a href="YOUR_LINKEDIN_URL" aria-label="LinkedIn">
```

```html
<a href="mailto:YOUR_EMAIL@example.com" aria-label="Email">
```

## 📱 Responsive Behavior

### Desktop
Full navigation links are displayed.

### Mobile
Navigation links are replaced by a hamburger menu.

The JavaScript supports:

- Open menu
- Close menu
- Close after selecting a link
- Close when switching back to desktop
- Close using the **Escape** key

## 🌐 Deploy with GitHub Pages

This static project can be hosted free using GitHub Pages.

1. Create a GitHub repository.
2. Upload `index.html`.
3. Upload `profile.jpg`.
4. Upload `README.md`.
5. Open **Settings → Pages**.
6. Select the `main` branch and repository root.
7. Save.
8. Open the generated GitHub Pages URL.

Example:

```text
https://YOUR_USERNAME.github.io/REPOSITORY_NAME/
```

## 📤 Push Updates to GitHub

```bash
git status
git add .
git commit -m "Update student resume website"
git push origin main
```

## 🎯 Project Purpose

This project can be used as:

- Student resume
- Personal portfolio
- Fresher developer profile
- Academic project showcase
- GitHub Pages website
- Front-end development practice project

## 🔮 Future Improvements

Possible additions include:

- 📄 Download Resume button
- 🌐 Live project links
- 💻 GitHub repository buttons
- 📧 Contact form
- 🐍 Python / Flask backend
- 🗄️ Database integration
- 🌓 Light/Dark mode
- 📊 GitHub statistics
- 🏆 Certificate links
- 🖼️ Project screenshots
- 🔗 LinkedIn and portfolio integration

## 👨‍💻 Developer

**JANG BAHADUR SINGH**

🎓 MCA (Integrated)  
💻 Student / Developer  
🌐 Web Development  
🚀 Learning and Building Projects

## 🔗 Connect

- **GitHub:** Add your GitHub profile URL
- **LinkedIn:** Add your LinkedIn profile URL
- **Portfolio:** Add your portfolio URL
- **Email:** Add your email address

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ **Star**.

<p align="center">

**Built with HTML + CSS + JavaScript ❤️**

</p>