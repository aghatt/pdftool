
# PDF Power Tools

A comprehensive web application for PDF manipulation and AI-powered document generation built with React, TypeScript, and Vite.

## 🚀 Live Demo

**Visit the live application**: [PDF Power Tools](https://aghatt.github.io/pdftool/)

## 📁 Repository Structure

This repository is organized for optimal hosting:

- **`main` branch**: Contains only hosting files (README, LICENSE, redirect page)
- **`source` branch**: Contains the complete source code for development
- **`gh-pages` branch**: Contains the built application (auto-generated)

## 🛠️ Development

To work on the source code:

1. **Switch to the source branch**:
   ```bash
   git checkout source
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run development server**:
   ```bash
   npm run dev
   ```

4. **Build for production**:
   ```bash
   npm run build
   ```

5. **Deploy to GitHub Pages**:
   ```bash
   npm run deploy
   ```

## 🚀 Features

- **PDF Compression**: Reduce PDF file sizes while maintaining quality
- **PDF Merging**: Combine multiple PDF files into one
- **PDF Splitting**: Split PDFs into multiple files
- **PDF to Word**: Convert PDF files to Word documents
- **AI Document Generator**: Generate documents using AI (Groq integration)
- **Home Maintenance Tracker**: Track home maintenance tasks and schedules

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Vite
- **PDF Processing**: pdf-lib, pdfjs-dist
- **AI Integration**: Groq SDK
- **Document Generation**: docx
- **Styling**: Modern CSS with responsive design

## 📦 Installation (Development)

1. **Clone the repository**
   ```bash
   git clone https://github.com/aghatt/pdftool.git
   cd pdftool
   git checkout source
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   Create a `.env.local` file in the root directory:
   ```env
   VITE_GROQ_API_KEY=your_groq_api_key_here
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

## 📁 Project Structure (Source Branch)

```
pdftool/
├── components/          # Reusable React components
├── pages/              # Page components
├── public/             # Static assets
├── types.ts            # TypeScript type definitions
├── constants.tsx       # Application constants
├── App.tsx             # Main application component
└── index.tsx           # Application entry point
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run type-check` - Run TypeScript type checking
- `npm run deploy` - Deploy to GitHub Pages

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch from the `source` branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request against the `source` branch

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [React](https://reactjs.org/)
- PDF processing powered by [pdf-lib](https://pdf-lib.js.org/)
- AI capabilities powered by [Groq](https://groq.com/)
- Icons from [Lucide React](https://lucide.dev/)
