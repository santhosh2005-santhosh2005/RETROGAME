# 🎮 RETRO GAME - Habbo Hotel Style Multiplayer Experience

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/san8951353723-gmailcoms-projects/v0-habbo-hotel-like-multiplayer-ch)
[![Built with Next.js](https://img.shields.io/badge/Built%20with-Next.js-black?style=for-the-badge&logo=next.js)](https://nextjs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/Styled%20with-Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com)

A modern retro-style multiplayer chatroom inspired by Habbo Hotel, built with cutting-edge web technologies.

## 🌟 Features

- **👥 Multiplayer Chat**: Real-time communication with other players
- **🎮 Pixel Art Style**: Nostalgic retro aesthetic with modern implementation
- **🏠 Virtual Rooms**: Interactive isometric room environments
- **👤 Custom Avatars**: Personalize your character experience
- **🔊 Audio Integration**: Immersive sound effects and background music
- **📱 Responsive Design**: Works on desktop and mobile devices
- **🌙 Dark/Light Theme**: Toggle between color schemes
- **🛡️ Profanity Filter**: Built-in content moderation

## 🚀 Live Demo

**[Play the Game →](https://vercel.com/san8951353723-gmailcoms-projects/v0-habbo-hotel-like-multiplayer-ch)**

## 🛠️ Tech Stack

- **Frontend**: [Next.js 15](https://nextjs.org) with React 19
- **Styling**: [Tailwind CSS](https://tailwindcss.com) with custom components
- **UI Components**: [Radix UI](https://www.radix-ui.com) primitives
- **State Management**: React Hooks and Context API
- **Real-time**: WebSocket integration via Supabase
- **Database**: [Supabase](https://supabase.com) for user data and chat
- **Deployment**: [Vercel](https://vercel.com)
- **Development**: TypeScript, ESLint

## 📦 Getting Started

### Prerequisites

- Node.js 18+ installed
- pnpm package manager (recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/santhosh2005-santhosh2005/RETROGAME.git
cd RETROGAME/v0-habbo-hotel-like-multiplayer-ch

# Install dependencies
pnpm install

# Start development server
pnpm dev
```

Visit `http://localhost:3000` to see your retro game in action!

### Available Scripts

```bash
pnpm dev     # Start development server
pnpm build   # Create production build
pnpm start   # Start production server
pnpm lint    # Run ESLint
```

## 🎯 Project Structure

```
app/                 # Next.js app router pages
components/          # Reusable UI components
├── chat-panel.tsx   # Chat interface
├── iso-room.tsx     # Isometric room renderer
├── pixel-hero.tsx   # Character/avatar component
├── pixel-navigation.tsx # Navigation UI
hooks/               # Custom React hooks
├── use-draggable.ts # Drag and drop functionality
├── use-multiplayer.ts # Multiplayer state management
lib/                 # Utility functions and services
├── iso.ts          # Isometric projection utilities
├── palette.ts      # Color palette management
├── pathfinding.ts  # Movement algorithms
├── supabase-client.ts # Database client
styles/              # CSS modules and global styles
```

## 🔧 Environment Variables

Create a `.env.local` file in the project root:

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🎨 Customization

### Theme Colors
Modify the color palette in `lib/palette.ts` to change the retro aesthetic.

### Room Design
Edit room layouts in `components/iso-room.tsx` to create custom environments.

### Character Sprites
Add your own pixel art in the `public/` directory.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Inspired by classic virtual worlds like Habbo Hotel
- Built with [v0.app](https://v0.app) - AI-powered UI generation
- Powered by [Vercel](https://vercel.com) for seamless deployment
- UI components powered by [shadcn/ui](https://ui.shadcn.com)

## 📞 Support

For issues, questions, or suggestions, please [open an issue](https://github.com/santhosh2005-santhosh2005/RETROGAME/issues) on GitHub.

---

*Made with ❤️ for retro gaming enthusiasts*
