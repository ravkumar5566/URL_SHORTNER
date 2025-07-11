# URL Shortener ⚡

A modern, fast URL shortening service built with React and Vite. Create short, memorable links from long URLs with a clean and intuitive interface.

## ✨ Features

- **⚡ Fast & Responsive** - Built with Vite for lightning-fast development and optimized builds
- **🎨 Modern UI** - Clean, user-friendly interface built with React
- **🔍 URL Validation** - Intelligent URL validation and formatting
- **📋 Copy to Clipboard** - One-click copying of shortened URLs
- **📊 Link Analytics** - Track click counts and usage statistics
- **🎯 Custom Short Codes** - Option to create custom short URL endings
- **📱 Mobile Responsive** - Works seamlessly across all devices

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **React 18** | Frontend framework |
| **Vite** | Build tool & dev server |
| **ESLint** | Code linting with custom rules |
| **CSS3/Tailwind** | Styling (customizable) |
| **HMR** | Hot Module Replacement for instant updates |

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/url-shortener.git
   cd url-shortener
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Build & Deploy

### Production Build
```bash
npm run build
```
Build artifacts will be stored in the `dist/` directory.

### Preview Production Build
```bash
npm run preview
```

## 📜 Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint |
| `npm run lint:fix` | Fix ESLint issues automatically |

## 📁 Project Structure

```
url-shortener/
├── public/
│   └── favicon.ico
├── src/
│   ├── components/
│   │   ├── URLShortener.jsx
│   │   ├── URLList.jsx
│   │   └── Analytics.jsx
│   ├── hooks/
│   │   └── useLocalStorage.js
│   ├── utils/
│   │   └── urlValidator.js
│   ├── App.jsx
│   └── main.jsx
├── package.json
├── vite.config.js
└── README.md
```

## ⚙️ Configuration

### Vite Configuration
The project uses Vite with React plugin for optimal development experience:

- **Fast Refresh** - Choose between Babel (`@vitejs/plugin-react`) or SWC (`@vitejs/plugin-react-swc`)
- **Hot Module Replacement** - Instant updates without losing component state
- **Optimized Build** - Tree-shaking and code splitting out of the box

### ESLint Configuration
For production applications, consider:
- Adding TypeScript support
- Enabling type-aware lint rules
- Integrating `typescript-eslint` for enhanced type checking

## 🎯 Usage

1. **Shorten a URL** - Paste your long URL into the input field and click "Shorten"
2. **Copy Short URL** - Click the copy button next to your shortened URL
3. **View Analytics** - Track clicks and usage statistics for your links
4. **Custom Short Codes** - Create memorable custom endings for your URLs

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Issues & Support

If you encounter any issues or have suggestions for improvements, please [open an issue](https://github.com/ravkumar5566/url-shortener/issues).

## 🙏 Acknowledgments

- React team for the amazing framework
- Vite team for the blazing fast build tool
- All contributors who help make this project better

---

⭐ **If you found this project helpful, please consider giving it a star on GitHub!**
