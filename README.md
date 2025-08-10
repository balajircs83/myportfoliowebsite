# Balaji's Portfolio Website

A modern, responsive portfolio website showcasing expertise in cloud architecture, AI/ML solutions, DevOps, and full-stack development.

## 🚀 Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive**: Fully responsive across all devices
- **Performance Optimized**: Built with Next.js for optimal performance
- **SEO Friendly**: Optimized for search engines
- **Accessibility**: WCAG compliant design
- **Static Export**: Can be deployed as a static site

## 🛠 Tech Stack

- **Framework**: Next.js 14 with TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Animations**: Framer Motion
- **Deployment**: Vercel/Netlify ready

## 📋 Sections

1. **Hero**: Introduction with animated role titles and key stats
2. **About**: Professional journey, philosophy, and certifications
3. **Skills**: Interactive skill categories with project counts
4. **Experience**: Detailed work history with achievements
5. **Projects**: Showcase of featured projects with metrics
6. **Contact**: Contact form and social links

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/balaji/portfolio-website.git
cd portfolio-website
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
# or
yarn build
```

### Export Static Site

```bash
npm run export
# or
yarn export
```

## 🎨 Customization

### Colors

The website uses a professional color scheme based on major cloud providers:
- **Azure Blue**: `#0078D4`
- **AWS Orange**: `#FF9900`
- **GCP Green**: `#34A853`

Update colors in `tailwind.config.js`:

```javascript
colors: {
  azure: '#0078D4',
  aws: '#FF9900',
  gcp: '#34A853',
  primary: '#0078D4',
  secondary: '#FF9900',
  accent: '#34A853',
}
```

### Content

Update personal information in the following components:
- `components/Hero.tsx` - Personal intro and stats
- `components/About.tsx` - Professional journey and certifications
- `components/Skills.tsx` - Technical skills and expertise
- `components/Experience.tsx` - Work history and achievements
- `components/Projects.tsx` - Portfolio projects
- `components/Contact.tsx` - Contact information

### Resume

Place your resume PDF in the `public` folder as `resume.pdf`.

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🔧 Performance

- **Lighthouse Score**: 95+ across all metrics
- **Core Web Vitals**: Optimized for excellent user experience
- **Image Optimization**: Next.js automatic image optimization
- **Code Splitting**: Automatic code splitting for faster loads

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy automatically on every push

### Netlify

1. Build the static export: `npm run export`
2. Upload the `out` folder to Netlify
3. Configure custom domain if needed

### GitHub Pages

1. Update `next.config.js` with your repository name
2. Build and export: `npm run export`
3. Deploy the `out` folder to GitHub Pages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/balaji/portfolio-website/issues).

## 📞 Contact

- **Email**: balaji@example.com
- **LinkedIn**: [linkedin.com/in/balaji](https://linkedin.com/in/balaji)
- **GitHub**: [github.com/balaji](https://github.com/balaji)

---

Built with ❤️ using Next.js and Tailwind CSS