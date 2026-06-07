# CodeFlex AI - Premium Next.js Starter Template

A modern, high-performance starter boilerplate for Next.js, React 19, Tailwind CSS v4, and shadcn/ui. Pre-configured with developer-friendly tooling, theme system (dark mode), and a clean structure optimized for rapid web application development.

---

## 🚀 Key Features

*   **Next.js 16 & React 19** – App Router, Server Actions, and rendering optimizations.
*   **Tailwind CSS v4** – Built with the latest Tailwind compiler for blazing-fast build times.
*   **shadcn/ui Integration** – Accessible, customizable UI components ready to use.
*   **Theme Management** – Fully integrated dark/light mode toggle with `next-themes`.
*   **TypeScript Ready** – Strongly typed layout, page, and component templates.
*   **Code Quality Suite** – Pre-configured ESLint, Prettier, and TypeScript checks.

---

## 🛠️ Tech Stack

*   **Framework:** [Next.js](https://nextjs.org/) (App Router)
*   **UI Components:** [shadcn/ui](https://ui.shadcn.com/)
*   **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
*   **Icons:** [Lucide React](https://lucide.dev/)
*   **Themes:** [Next Themes](https://github.com/pacocoursey/next-themes)

---

## 📦 Getting Started

### Prerequisites

Ensure you have Node.js (v18.x or later) and npm installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/codeflex-ai.git
   cd codeflex-ai/next-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result!

---

## 🧩 Adding & Using Components

This template uses **shadcn/ui**. To add new components to your project, use:

```bash
npx shadcn@latest add [component-name]
```

For example, to add a Dialog:
```bash
npx shadcn@latest add dialog
```

### Importing Components
Once added, you can import and use them anywhere in your application:

```tsx
import { Button } from "@/components/ui/button";

export default function Home() {
  return <Button>Click me</Button>;
}
```

---

## 📂 Project Structure

```text
next-app/
├── app/                  # Next.js App Router (pages, layouts, globals)
│   ├── globals.css       # Tailwind stylesheet
│   ├── layout.tsx        # Main application layout with ThemeProvider
│   └── page.tsx          # Home/landing page
├── components/           # Custom React components
│   ├── ui/               # shadcn/ui component library
│   └── theme-provider.tsx# Theme support wrapper
├── hooks/                # Custom React hooks
├── lib/                  # Shared utilities and helper functions
├── public/               # Static assets (images, icons)
├── package.json          # Dependency and script manager
└── tsconfig.json         # TypeScript configuration
```

---

## 🧹 Code Formatting & Linting

Keep the codebase clean and consistent with the built-in commands:

*   **Linting:** `npm run lint`
*   **Formatting:** `npm run format`
*   **Type Checking:** `npm run typecheck`
