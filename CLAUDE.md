# Stream Pick

A Next.js 15 application built with TypeScript, React 19, and Tailwind CSS. This project appears to be in early development stages and includes shadcn/ui components setup.

## Project Overview

- **Framework**: Next.js 15 with App Router and Turbopack
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4 with shadcn/ui components
- **UI Components**: Lucide React icons, class-variance-authority for styling
- **Font**: Geist Sans and Geist Mono

## Development Commands

```bash
# Start development server with Turbopack
npm run dev

# Build for production with Turbopack
npm run build

# Start production server
npm run start

# Run ESLint
npm run lint
```

## Project Structure

```
stream-pick/
├── app/                 # Next.js App Router pages
│   ├── globals.css     # Global CSS with Tailwind
│   ├── layout.tsx      # Root layout component
│   └── page.tsx        # Home page component
├── lib/                # Utility functions
│   └── utils.ts        # Shared utilities
├── components.json     # shadcn/ui configuration
├── package.json        # Dependencies and scripts
└── next.config.ts      # Next.js configuration
```

## Key Dependencies

- **Next.js 15** - React framework with App Router
- **React 19** - Latest React with concurrent features
- **Tailwind CSS 4** - Utility-first CSS framework
- **shadcn/ui** - Component library setup (New York style)
- **TypeScript** - Type safety and development experience
- **Lucide React** - Icon library

## Development Notes

- Uses Turbopack for faster builds and development
- shadcn/ui is configured with New York style and Lucide icons
- Component aliases are set up for clean imports (`@/components`, `@/lib`, etc.)
- CSS variables are enabled for theming support