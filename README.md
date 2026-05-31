# 🎓 STEM Assistant Application

An accessible learning platform designed to empower visually impaired students with enhanced STEM education through innovative audio processing and interactive learning experiences.

## 🌟 Features

- **Accessible Design**: Built with WCAG compliance and screen reader optimization
- **Audio Processing**: Advanced audio stem separation for enhanced learning
- **Interactive UI**: Modern, responsive interface with dark/light theme support
- **User Authentication**: Secure login and signup with Supabase
- **Download Management**: Track and manage educational resources
- **Admin Dashboard**: Comprehensive analytics and user management
- **Offline Support**: Local data storage with automatic sync when online

## 🚀 Tech Stack

- **Frontend**: React 18 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + Radix UI Components
- **Routing**: React Router v7
- **State Management**: TanStack Query (React Query)
- **Backend**: Supabase (Authentication & Database)
- **Forms**: React Hook Form + Zod validation
- **Animations**: Spline 3D animations
- **Charts**: Recharts for data visualization

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/R-Jashwanth/STEM-assistant-application.git
   cd STEM-assistant-application
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   VITE_SUPABASE_URL=your_supabase_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:5173`

## 📦 Build for Production

```bash
npm run build
```

The build output will be in the `dist` directory.

## 🎯 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 📁 Project Structure

```
STEM-assistant-application/
├── src/
│   ├── components/       # Reusable UI components
│   │   ├── admin/       # Admin-specific components
│   │   ├── analytics/   # Analytics components
│   │   ├── layout/      # Layout components (Header, Footer)
│   │   └── ui/          # Radix UI components
│   ├── pages/           # Page components
│   ├── lib/             # Utility functions and services
│   ├── hooks/           # Custom React hooks
│   ├── integrations/    # Third-party integrations (Supabase)
│   ├── App.tsx          # Main application component
│   └── main.tsx         # Application entry point
├── public/              # Static assets
├── supabase/            # Supabase configuration and migrations
└── package.json         # Project dependencies
```

## 🎨 Key Features Breakdown

### Accessibility
- Screen reader optimized
- Keyboard navigation support
- High contrast themes
- ARIA labels and semantic HTML

### User Management
- Secure authentication with Supabase
- User profile management
- Activity tracking
- Download history

### Admin Features
- User analytics dashboard
- Download tracking
- APK version management
- System monitoring

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For support or inquiries:
- Email: jashwanthr975@gmail.com
- GitHub: [R-Jashwanth/STEM-assistant-application](https://github.com/R-Jashwanth/STEM-assistant-application)

## 📄 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- Built for Hackathon 2025
- Designed to make STEM education accessible for all
- Special thanks to all contributors and supporters

---

Made with ❤️ for accessible education

