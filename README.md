# Hackaholics

1. First, ensure you have Node.js installed on your computer. You can download it from [https://nodejs.org/](https://nodejs.org/) (version 18 or higher recommended)
2. Install the following tools:


```shellscript
npm install -g pnpm # Faster package manager
```

3. Create a new directory and extract the zip file contents there
4. Install the project dependencies:


```shellscript
pnpm install
```

5. Start the development server:


```shellscript
pnpm dev
```

The project should now be running at [http://localhost:3000](http://localhost:3000)

Key dependencies included:

- Next.js 14
- React 18
- Tailwind CSS
- shadcn/ui components
- TypeScript
- Various UI-related packages (radix-ui, lucide-react, etc.)


The project uses:

- App Router for routing
- Server Components by default
- TypeScript for type safety
- Tailwind CSS for styling
- Environment variables for configuration
