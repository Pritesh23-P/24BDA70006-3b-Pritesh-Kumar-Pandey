# 📚 Library Management System

A modern, interactive library management application built with **Next.js 15**, **React 19**, **TypeScript**, and **Tailwind CSS**. This application provides a beautiful and intuitive interface for managing your book collection with advanced features like borrowing/returning, status tracking, categories, and real-time search.

![Next.js](https://img.shields.io/badge/Next.js-15.5-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-19-blue?style=flat-square&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=flat-square&logo=typescript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38bdf8?style=flat-square&logo=tailwind-css)

---

## ✨ Features

### 📖 Core Functionality
- **Add Books**: Quickly add books with title, author, and category
- **Edit Books**: Modify book details inline with a smooth editing experience
- **Remove Books**: Delete books from your collection
- **Real-time Search**: Search books by title or author with instant results

### 🔄 Advanced Features
- **Borrow/Return System**: Track borrowed books with automatic due date calculation (14 days)
- **Status Tracking**: Visual indicators for Available/Borrowed status
- **Category Management**: Organize books into 7 predefined categories:
  - Fiction
  - Non-Fiction
  - Sci-Fi
  - Mystery
  - Biography
  - History
  - Technology
- **Advanced Filtering**: Filter books by status (All, Available, Borrowed)
- **Statistics Dashboard**: Real-time counters showing:
  - Total books in collection
  - Available books
  - Borrowed books

### 🎨 UI/UX Highlights
- **Modern Design**: Beautiful gradient backgrounds with glassmorphism effects
- **Responsive Layout**: Adapts seamlessly from mobile to desktop (1-3 column grid)
- **Smooth Animations**: Hover effects, transitions, and micro-interactions
- **Icon Integration**: Lucide React icons for enhanced visual appeal
- **Color-coded Status**: Green for available, amber for borrowed
- **Accessible**: Semantic HTML and ARIA labels for screen readers

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:
- **Node.js** 18+ 
- **pnpm** (recommended) or npm/yarn

### Installation

1. **Clone the repository** (or navigate to the project directory):
   ```bash
   cd 24BDA70006-3b-Pritesh-Kumar-Pandey
   ```

2. **Install dependencies**:
   ```bash
   pnpm install
   ```

3. **Approve build scripts** (if prompted):
   ```bash
   pnpm approve-builds
   # Select 'sharp' when prompted
   ```

### Running the Application

Start the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

### Building for Production

```bash
pnpm build
pnpm start
```

---

## 📁 Project Structure

```
24BDA70006-3b-Pritesh-Kumar-Pandey/
├── app/
│   ├── globals.css          # Global styles and Tailwind directives
│   ├── layout.tsx            # Root layout component
│   └── page.tsx              # Main library management page
├── components/
│   ├── ui/                   # shadcn/ui components
│   │   ├── button.tsx        # Button component
│   │   ├── card.tsx          # Card component
│   │   └── input.tsx         # Input component
│   └── library-button.tsx    # Custom library button variants
├── lib/
│   └── utils.ts              # Utility functions (cn helper)
├── public/                   # Static assets
├── components.json           # shadcn/ui configuration
├── package.json              # Dependencies and scripts
├── pnpm-lock.yaml            # Lockfile
├── pnpm-workspace.yaml       # Workspace configuration
├── postcss.config.mjs        # PostCSS configuration
├── tailwind.config.ts        # Tailwind CSS configuration
├── tsconfig.json             # TypeScript configuration
├── next.config.ts            # Next.js configuration
└── README.md                 # This file
```

---

## 🛠️ Technologies Used

| Technology | Version | Purpose |
|------------|---------|---------|
| **Next.js** | 15.5+ | React framework with App Router |
| **React** | 19+ | UI library |
| **TypeScript** | 5+ | Type safety and developer experience |
| **Tailwind CSS** | 3.4+ | Utility-first CSS framework |
| **shadcn/ui** | Latest | Accessible component library |
| **Lucide React** | 0.453+ | Beautiful icon library |
| **Radix UI** | Latest | Headless UI primitives |
| **pnpm** | 10.28+ | Fast, disk space efficient package manager |

---

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start development server at http://localhost:3000 |
| `pnpm build` | Build the application for production |
| `pnpm start` | Start the production server |
| `pnpm lint` | Run ESLint to check code quality |

---

## 🎯 Usage Guide

### Adding a Book
1. Fill in the **Title**, **Author**, and select a **Category**
2. Click the **Add Book** button
3. The book will appear in the collection with "Available" status

### Borrowing a Book
1. Find the book you want to borrow
2. Click the **Borrow** button on the book card
3. The status changes to "Borrowed" with a due date (14 days from now)

### Returning a Book
1. Find the borrowed book
2. Click the **Return** button
3. The status changes back to "Available" and the due date is cleared

### Editing a Book
1. Click the **Edit** icon (pencil) on any book card
2. Modify the title, author, or category
3. Click **Save** to confirm or **Cancel** to discard changes

### Searching & Filtering
- Use the **search bar** to find books by title or author
- Use the **status filter** dropdown to show only Available or Borrowed books
- Filters work together for precise results

---

## 🎨 Design Philosophy

This application follows modern web design principles:

- **Visual Excellence**: Premium aesthetics with gradients, glassmorphism, and smooth animations
- **User-Centric**: Intuitive interface with clear visual feedback
- **Responsive First**: Mobile-friendly design that scales beautifully
- **Performance**: Optimized React components with efficient state management
- **Accessibility**: Semantic HTML and proper ARIA labels

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is created for educational purposes as part of the **24BDA70006** course assignment.

**Student**: Pritesh Kumar Pandey  
**Course**: 24BDA70006-3b

---

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React Framework
- [shadcn/ui](https://ui.shadcn.com/) - Beautiful component library
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Lucide Icons](https://lucide.dev/) - Icon library
- [Radix UI](https://www.radix-ui.com/) - Headless UI primitives

---

## 📞 Support

If you encounter any issues or have questions:
- Check the [Next.js Documentation](https://nextjs.org/docs)
- Review the [React Documentation](https://react.dev)
- Explore [Tailwind CSS Docs](https://tailwindcss.com/docs)

---

**Made with ❤️ using Next.js and React**
