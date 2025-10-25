# 🚀 Abhilash Chary Vadla - Portfolio Website

[![Live Demo](https://img.shields.io/badge/Demo-Live-brightgreen)]([https://abhilashchary.github.io](https://abhilashchary.github.io/portfolio/))
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue)](https://pages.github.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> A modern, responsive portfolio website showcasing my journey as a Software Engineer, Competitive Programmer, and Full-Stack Developer.

## 📸 Preview

![Portfolio Preview](assets/preview.png)

## ✨ Features

### 🎯 Core Functionality
- **Responsive Design** - Fully mobile-friendly and adapts to all screen sizes
- **Dynamic Content** - Real-time GitHub repository integration via API
- **Live CP Stats** - Competitive programming statistics from multiple platforms
- **Interactive Charts** - Visual analytics powered by Chart.js
- **Contact Form** - Direct email integration with prefilled templates
- **Smooth Animations** - Engaging scroll effects and hover transitions

### 📊 Data Integration
- ✅ **GitHub API** - Automatically fetches latest 6 repositories
- ✅ **Codeforces API** - Live rating and contest data
- 📌 **LeetCode Stats** - 1718 rating, 128 problems solved, Top 11.71%
- 📌 **CodeChef Stats** - 1476 rating, 50 problems solved
- 📌 **Smart Interviews** - Rank 2041, Score 42,965, Gold Certified

### 🔗 Social Integration
- LinkedIn profile badge with live updates
- Featured LinkedIn posts with direct links
- Instagram, GitHub, LeetCode, CodeChef, Codeforces profiles
- Professional quote showcase

## 🛠️ Tech Stack

| Category | Technologies |
|----------|-------------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Charts** | Chart.js |
| **APIs** | GitHub REST API, Codeforces API, LinkedIn Badges |
| **Icons** | Font Awesome 6.5.1 |
| **Fonts** | Google Fonts (Inter) |
| **Hosting** | GitHub Pages |

## 📂 Project Structure

```
portfolio/
├── index.html              # Main HTML file (single-page application)
├── assets/
│   ├── profile.jpg         # Profile picture
│   ├── logo.jpg            # Code Resol logo
│   └── resume.pdf          # Downloadable resume
├── README.md               # This file
└── LICENSE                 # MIT License
```

## 🚀 Quick Start

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abhilashchary/Abhilashchary.github.io.git
   cd Abhilashchary.github.io
   ```

2. **Add your assets**
   ```bash
   mkdir assets
   # Add profile.jpg, logo.jpg, and resume.pdf to assets/
   ```

3. **Open in browser**
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Or simply open index.html in your browser
   ```

4. **View locally**
   ```
   http://localhost:8000
   ```

### Deploy to GitHub Pages

1. **Create repository** named `your-username.github.io`
2. **Push your code**
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```
3. **Enable GitHub Pages** in repository Settings → Pages → Deploy from main branch
4. **Access your site** at `https://your-username.github.io`

## 🎨 Customization

### Update Personal Information

Edit `index.html` and replace:
- Name, email, phone in contact section
- Social media links (LinkedIn, GitHub, Instagram, etc.)
- Competitive programming usernames
- Project descriptions and experience details

### Change Colors

Modify CSS variables in `:root` section:
```css
:root {
    --color-bg: #0a0a0f;              /* Background color */
    --color-primary: #00e0b0;          /* Primary accent */
    --color-text-primary: #f0f0f5;    /* Text color */
    /* ... other variables ... */
}
```

### Update Stats

- **Live stats** (GitHub, Codeforces) update automatically
- **Static stats** (LeetCode, CodeChef, Smart Interviews) are hardcoded in HTML
- LinkedIn posts: Replace URLs with your actual post links

## 📊 Data Transparency

### Live Data (Auto-Updated)
- **GitHub**: Repositories, stars, forks via API
- **Codeforces**: Rating, contests via API

### Static Data (Manual Updates Required)
- **LeetCode**: Rating, problems solved (no public API)
- **CodeChef**: Rating, problems (limited API)
- **Smart Interviews**: Rank, score, certification
- **LinkedIn**: Post links, profile badge

**Last Updated**: October 2025

## 🔧 API Integrations

### GitHub API
```javascript
fetch('https://api.github.com/users/Abhilashchary/repos?sort=updated&per_page=6')
```
No authentication required for public repos.

### Codeforces API
```javascript
fetch('https://codeforces.com/api/user.info?handles=vadlaabhilashchary3333')
```
Free public API, no key required.

### LinkedIn Badge
```html
<script src="https://platform.linkedin.com/badges/js/profile.js"></script>
```
Uses official LinkedIn badge widget.

## 📱 Responsive Breakpoints

- **Desktop**: 1140px+ (full layout)
- **Tablet**: 768px - 1139px (adjusted grid)
- **Mobile**: < 768px (single column)

## 🎓 Features Breakdown

### 1. Hero Section
- Animated typing effect
- Profile image with hover effect
- Social media icons
- CTA buttons (Contact, Resume)

### 2. Highlights
- Top 6 achievements cards
- Icon animations
- Hover effects

### 3. Projects
- Dynamic GitHub integration
- Repository cards with tech tags
- Star and fork counts
- Live demo links (if available)

### 4. CP Dashboard
- Platform comparison charts
- Problems solved distribution
- Contest performance timeline
- Direct profile links

### 5. Timeline
- Professional journey visualization
- Education and experience
- Awards and certifications

### 6. LinkedIn Showcase
- Official profile badge
- Professional quote
- Featured posts with thumbnails
- Data transparency note

### 7. Contact Form
- Prefilled mailto integration
- Custom message templates
- Direct email client opening

## 🐛 Known Issues

- LinkedIn post embeds not available (platform limitation)
- LeetCode/CodeChef stats require manual updates
- Mobile menu may need JavaScript toggle fix for some browsers

## 🔮 Future Enhancements

- [ ] Add blog section with Markdown support
- [ ] Dark/Light theme toggle
- [ ] Testimonials carousel
- [ ] Project filter by technology
- [ ] Real-time LeetCode API (if available)
- [ ] Visitor analytics dashboard
- [ ] Multi-language support

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

**Abhilash Chary Vadla**

- 📧 Email: vadlaabhilashchary3333@gmail.com
- 💼 LinkedIn: [linkedin.com/in/coderesol](https://www.linkedin.com/in/coderesol/)
- 🐙 GitHub: [@Abhilashchary](https://github.com/Abhilashchary)
- 💻 LeetCode: [coderesol](https://leetcode.com/u/coderesol/)
- 🍴 CodeChef: [abhilashchary](https://www.codechef.com/users/abhilashchary)
- 📊 Codeforces: [vadlaabhilashchary3333](https://codeforces.com/profile/vadlaabhilashchary3333)
- 📸 Instagram: [@abhi___chary](https://www.instagram.com/abhi___chary/)

---

<div align="center">

**Made with ❤️ by Abhilash Chary Vadla**

⭐ Star this repo if you found it helpful!

</div>
