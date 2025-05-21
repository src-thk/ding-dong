# 🔔 Ding Dong - React 19 Template

<div align="center">
  
  ![Ding Dong](https://img.shields.io/badge/Ding%20Dong-v1.0-blue)
  ![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
  ![Rsbuild](https://img.shields.io/badge/Rsbuild-v1.3.15-orange)
  ![Tanstack](https://img.shields.io/badge/Tanstack-Router%20%26%20Query-FF4154?logo=react-query)
  ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-v4-38B2AC?logo=tailwind-css)
  ![TypeScript](https://img.shields.io/badge/TypeScript-5.8.3-3178C6?logo=typescript)
  ![License](https://img.shields.io/badge/License-MIT-green)

  **A lightning-fast, modern React template supercharged with Rsbuild**
  
</div>

Welcome to **Ding Dong**, a cutting-edge React 19 template designed for modern web development. Built with performance, developer experience, and scalability in mind, Ding Dong provides a solid foundation for your next project.

This template leverages the power of **Rsbuild** for lightning-fast builds, **React 19** for the latest React features, **Tanstack Router** for type-safe routing, **Tanstack Query** for efficient data fetching and state management, **ShadCn/ui** for beautifully designed and accessible components, and **Tailwind CSS v4** for a utility-first CSS workflow.

## ✨ Key Features

- **🚀 Blazing Fast Development:** Powered by Rsbuild, experience near-instantaneous hot module replacement (HMR) and optimized production builds.
- **⚛️ React 19:** Utilize the newest features and improvements from the React core team.
- **🚦 Type-Safe Routing & SSR:** Tanstack Router offers a fully type-safe routing solution with built-in server-side rendering capabilities, catching errors at build time and providing excellent autocompletion.
- **🔄 Effortless Data Management:** Tanstack Query simplifies server-state management, offering caching, synchronization, and background updates out-of-the-box.
- **🎨 Stunning UI Components:** Integrated with ShadCn/ui, providing a collection of beautifully crafted, accessible, and customizable React components built on Radix UI and Tailwind CSS.
- **💨 Utility-First Styling:** Tailwind CSS v4 enables rapid UI development with its utility classes, now even more powerful and optimized.
- **📦 PNPM Ready:** Uses pnpm for efficient package management, saving disk space and boosting installation speed.
- **TypeScript First:** Written in TypeScript for enhanced code quality, maintainability, and developer productivity.

## 🛠️ Tech Stack

| Technology | Description |
|------------|-------------|
| **React 19** | Library for building user interfaces with the latest features and improvements (v19.1.0) |
| **Rsbuild** | High-performance build tool delivering lightning-fast build times (v1.3.15) |
| **Tanstack Router** | Type-safe, modern routing library with first-class data loading and server-side rendering support (v1.120.5) |
| **Tanstack Query** | Powerful data synchronization for fetching, caching, and updating asynchronous data (v5.76.1) |
| **Tailwind CSS v4** | Utility-first CSS framework with advanced features and smaller bundle size (v4.1.7) |
| **shadcn/ui** | High-quality, accessible UI components built with Radix UI and Tailwind |
| **TypeScript** | Static typing for safer, more maintainable code (v5.8.3) |
| **pnpm** | Fast, disk space efficient package manager |

## 🚀 Getting Started

Follow these instructions to get your project up and running:

1. **Clone the repository (if applicable) or use this template:**

   ```bash
   # If you've cloned it
   git clone <repository-url>
   cd ding-dong-template
   ```

2. **Install dependencies using pnpm:**

   Make sure you have pnpm installed. If not, you can install it via npm:
   ```bash
   npm install -g pnpm
   ```
   Then, install the project dependencies:
   ```bash
   pnpm install
   ```

3. **Run the development server:**

   This command starts the Rsbuild development server with HMR.
   ```bash
   pnpm run dev
   ```
   Your application should now be running on a local port (Rsbuild will typically open it in your browser automatically due to `--open` flag in `package.json`).

4. **Build for production:**

   This command creates an optimized production build in the `dist` folder.
   ```bash
   pnpm run build
   ```

5. **Preview the production build:**

   This command serves the production build locally.
   ```bash
   pnpm run preview
   ```

## 📜 Available Scripts

In the `package.json` file, you will find the following scripts:

- `pnpm run dev`: Starts the development server with Rsbuild.
- `pnpm run build`: Builds the application for production.
- `pnpm run preview`: Serves the production build locally.

## 📁 Project Structure

```
ding-dong-template/
├── .vscode/           # VS Code configuration
│   └── settings.json  # Editor settings
├── src/
│   ├── components/    # UI components
│   │   └── ui/        # ShadCn UI components
│   ├── lib/           # Utility functions and shared code
│   │   └── utils.ts   # Utility functions
│   ├── routes/        # Tanstack Router route definitions
│   │   ├── __root.tsx # Root route definition
│   │   ├── about.tsx  # About page route
│   │   └── index.tsx  # Home page route
│   ├── styles/        # CSS styles
│   │   └── globals.css # Global styles
│   ├── env.d.ts       # Environment type definitions
│   └── main.tsx       # Application entry point
├── components.json    # ShadCn UI configuration
├── postcss.config.mjs # PostCSS configuration
├── rsbuild.config.ts  # Rsbuild configuration
├── tsconfig.json      # TypeScript configuration
└── package.json       # Dependencies and scripts
```

## 🤔 Why Choose Ding Dong?

- **Modern & Future-Proof:** Built with the latest versions of industry-leading libraries and tools.
- **Developer-Centric:** Focuses on providing a smooth and efficient development experience with type safety and fast feedback loops.
- **Performance Optimized:** Rsbuild ensures your application is fast, both in development and production.
- **Scalable Foundation:** The chosen stack is well-suited for building small to large-scale applications.
- **Beautiful by Default:** With ShadCn/ui and Tailwind CSS, creating visually appealing interfaces is a breeze.
- **Type Safety Throughout:** From routing to data fetching, enjoy comprehensive TypeScript support.
- **Server-Side Rendering:** Take advantage of Tanstack Router's built-in SSR capabilities for improved SEO and initial load performance.
- **Production Ready:** Optimized builds and sensible defaults make deployment straightforward.

Start your next React project with Ding Dong and experience the joy of modern web development!

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues and pull requests.

## 📄 License

This project is licensed under the MIT License.

---

<div align="center">
  
  **⭐ Star this repository if you find it useful! ⭐**
  
  Made with ❤️ for the React community
  
</div>
