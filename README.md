
# One Notebook 📝

A modern, full-stack document management application inspired by Notion. Built with Next.js 14, Convex, and Clerk authentication.

![One Notebook](https://img.shields.io/badge/Next.js-14-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-blue?style=flat-square&logo=typescript)
![Convex](https://img.shields.io/badge/Convex-Backend-orange?style=flat-square)
![Clerk](https://img.shields.io/badge/Clerk-Auth-blue?style=flat-square)

## ✨ Features

- 📄 **Infinite Document Nesting** - Create unlimited hierarchical document structures
- 🎨 **Rich Text Editor** - BlockNote-powered editor with image upload support
- 🔄 **Real-time Updates** - Instant synchronization across all devices
- 🗑️ **Soft Delete & Restore** - Trash can with recovery functionality
- 🌐 **Publish to Web** - Share documents via public URLs
- 🎭 **Custom Icons & Covers** - Personalize documents with emojis and images
- 🌓 **Dark/Light Mode** - Seamless theme switching
- ⌨️ **Keyboard Shortcuts** - Cmd/Ctrl+K for quick search
- 📱 **Mobile Responsive** - Fully functional on all devices
- 🔐 **Secure Authentication** - OAuth integration via Clerk

## 🚀 Tech Stack

- **Frontend**: Next.js 14 (App Router), React, TypeScript, Tailwind CSS
- **Backend**: Convex (Real-time Database)
- **Authentication**: Clerk
- **File Storage**: EdgeStore (CDN)
- **Editor**: BlockNote
- **UI Components**: Shadcn/ui, Radix UI
- **State Management**: Zustand
- **Styling**: Tailwind CSS with dark mode support

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/Chiragj2003/One-Notebook.git

# Navigate to project directory
cd One-Notebook

# Install dependencies
npm install

# Set up environment variables
# Create .env.local file with:
# CONVEX_DEPLOYMENT=
# CLERK_SECRET_KEY=
# EDGE_STORE_ACCESS_KEY=
# EDGE_STORE_SECRET_KEY=
# NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
# NEXT_PUBLIC_CONVEX_URL=
# NEXT_PUBLIC_SITE_URL=

# Run Convex backend
npx convex dev

# In another terminal, start the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the application.

## 🏗️ Project Structure

```
├── app/                    # Next.js App Router
│   ├── (main)/            # Main application routes
│   ├── (public)/          # Public document preview
│   └── (root)/            # Landing page
├── components/            # Reusable React components
├── convex/               # Convex backend (queries, mutations, schema)
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
└── providers/            # React context providers
```

## 🎯 Key Features Implementation

### Real-time Synchronization
Powered by Convex, all document changes are synchronized in real-time across all connected clients without manual polling or WebSocket configuration.

### Hierarchical Documents
Documents can be nested infinitely, creating a tree structure perfect for organizing complex projects and knowledge bases.

### Rich Text Editing
BlockNote editor provides a modern, block-based editing experience with support for:
- Text formatting (bold, italic, code, etc.)
- Headings and lists
- Images with drag-and-drop upload
- Code blocks

### Authentication
Clerk provides secure authentication with support for:
- Email/Password
- OAuth providers (Google, GitHub, etc.)
- Session management
- User profiles

## 🔒 Security

- All API routes are protected with authentication
- User data isolation at the database level
- Environment variables for sensitive keys
- Secure file uploads with EdgeStore

## 📈 Performance

- Server Components for reduced JavaScript bundle
- Automatic code splitting and lazy loading
- Image optimization via Next.js
- CDN-based file storage for global delivery
- Database indexing for fast queries

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/)
- [Convex](https://www.convex.dev/)
- [Clerk](https://clerk.com/)
- [BlockNote](https://www.blocknotejs.org/)
- [Shadcn/ui](https://ui.shadcn.com/)

## 📧 Contact

**Chirag J** - [@Chiragj2003](https://github.com/Chiragj2003)

Project Link: [https://github.com/Chiragj2003/One-Notebook](https://github.com/Chiragj2003/One-Notebook)

---

⭐ Star this repo if you find it helpful!



