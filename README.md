# 📝 Keeper App

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

A beautiful and intuitive note-taking application built with React and Vite. Capture your thoughts, ideas, and reminders with ease!

## 🌐 Live Demo

**[🚀 Try it live on Netlify!](https://stupendous-treacle-9f774e.netlify.app)**

## ✨ Features

- 📝 **Create Notes**: Quickly add new notes with title and content
- 🗑️ **Delete Notes**: Remove notes you no longer need with a single click
- 🎨 **Beautiful UI**: Clean, modern interface inspired by Google Keep
- ⚡ **Fast Performance**: Built with Vite for lightning-fast development and builds
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- 🔄 **Real-time Updates**: Instant note management without page refreshes

## ️ Built With

- **[React](https://reactjs.org/)** - Frontend framework for building user interfaces
- **[Vite](https://vitejs.dev/)** - Next generation frontend tooling
- **[Material-UI](https://mui.com/)** - React components for faster development
- **[CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)** - Styling and animations
- **[Netlify](https://netlify.com/)** - Deployment and hosting
- **[pnpm](https://pnpm.io/)** - Fast, disk space efficient package manager

## 📁 Project Structure

```
keeper-app/
├── public/
│   └── styles.css          # Global styles
├── src/
│   ├── components/
│   │   ├── App.jsx         # Main app component
│   │   ├── Header.jsx      # App header
│   │   ├── CreateArea.jsx  # Note creation form
│   │   ├── Note.jsx        # Individual note component
│   │   └── Footer.jsx      # App footer
│   ├── index.jsx           # App entry point
│   └── vite-env.d.ts       # Vite type definitions
├── index.html              # HTML template
├── package.json            # Dependencies and scripts
├── vite.config.ts          # Vite configuration
└── README.md              # You are here!
```

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (version 16 or higher)
- [npm](https://www.npmjs.com/) or [pnpm](https://pnpm.io/) (recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YarikVitovsky/Keeper-App.git
   cd Keeper-App
   ```

2. **Navigate to frontend directory**
   ```bash
   cd frontend
   ```

3. **Install dependencies**
   ```bash
   npm install
   # or
   pnpm install
   ```

4. **Start the development server**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173` to see the app running!

## 🌐 Deployment

This app is automatically deployed to Netlify from the main branch.

### Deployment Configuration

The project includes a `netlify.toml` file with the following settings:
```toml
[build]
  base = "frontend"
  command = "npm run build"
  publish = "dist"

[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200
```

### Manual Deployment

To deploy your own version:

1. **Build the project**
   ```bash
   cd frontend
   npm run build
   ```

2. **Deploy to Netlify**
   - Drag and drop the `dist` folder to [Netlify](https://netlify.com)
   - Or connect your GitHub repository for automatic deployments

## 📜 Available Scripts

In the frontend directory, you can run:

- `npm run dev` - Runs the app in development mode
- `npm run build` - Builds the app for production  
- `npm run preview` - Preview the production build locally

## 🎯 Usage

1. **Adding a Note**: 
   - Enter a title and content in the create area
   - Click the "+" button to add your note

2. **Deleting a Note**: 
   - Click the delete button (🗑️) on any note to remove it

3. **Viewing Notes**: 
   - All your notes are displayed in a clean grid layout
   - Notes automatically adjust to different screen sizes

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Future Enhancements

- [ ] 🔍 Search functionality
- [ ] 🏷️ Tags and categories  
- [ ] 🌙 Dark mode toggle
- [ ] 💾 Database integration for persistent storage
- [ ] 👤 User authentication and accounts
- [ ] 📤 Export notes functionality
- [ ] 🔔 Reminder notifications
- [ ] 🎨 Customizable themes
- [ ] 📱 PWA support
- [ ] 🔄 Real-time sync across devices

## 🚀 Current Status

✅ **Deployed** - Live at https://stupendous-treacle-9f774e.netlify.app  
✅ **Responsive Design** - Works on all devices  
✅ **Fast Performance** - Built with Vite  
⏳ **Database Integration** - Coming soon for persistent notes

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Yarik Vitovsky**

- GitHub: [@YarikVitovsky](https://github.com/YarikVitovsky)
- Repository: [Keeper-App](https://github.com/YarikVitovsky/Keeper-App)

## 🙏 Acknowledgments

- Inspired by Google Keep
- Built with love using React and Vite
- Thanks to the open source community for amazing tools and libraries

---

⭐ Star this repo if you found it helpful!

Made with ❤️ by [Yarik Vitovsky](https://github.com/YarikVitovsky)
