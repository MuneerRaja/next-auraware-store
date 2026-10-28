
**Muneer** is a modern, fully responsive e-commerce storefront created by **Muneer Raja**. It converts a Figma e-commerce design into production-ready code using **Next.js 14 App Router**, **TypeScript**, **Tailwind CSS**, **Redux Toolkit**, **Framer Motion**, and **ShadCN UI** to deliver a scalable, optimized solution based on industry standards.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Issues](#issues)
- [License](#license)
- [Credits](#credits)
- [Contact](#contact)

## Overview

Muhammad Muneer is a complete online-store front end: homepage with product showcases, shop page with filters, product detail page, and a Redux-powered shopping cart. The project follows best practices for **SEO**, **performance optimization**, and **accessibility**, making it a solid foundation for scalable and maintainable e-commerce front-ends.

## Features

- **Next.js 14**: Server-side rendering (SSR), Static Site Generation (SSG), and optimized routing.
- **TypeScript**: Strongly typed code for better error detection and maintainability.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **Redux Toolkit**: State management for the shopping cart and other global state, persisted with redux-persist.
- **Framer Motion**: Smooth animations and transitions for an enhanced user experience.
- **ShadCN UI**: Beautifully styled, accessible, and customizable UI components.
- **Fully Responsive**: Mobile-first design ensuring the layout adapts across devices.
- **Performance Optimized**: Best practices followed for fast loading and interaction.
- **Accessible**: Built with accessibility standards to provide an inclusive experience.

## Technologies

- **Next.js 14** - React framework with built-in SSR and optimization.
- **TypeScript** - Superset of JavaScript for strong typing and code consistency.
- **Tailwind CSS** - Utility-first CSS framework for fast, responsive design.
- **Redux Toolkit** - State management for the shopping cart and global app state.
- **Framer Motion** - Animations and interactions in React.
- **ShadCN UI** - Accessible, customizable UI components.
- **Figma** - The design tool used as the source of the project's layout.

## Installation

To get started with Muhammad Muneer locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MuneerDevCodes/next-auraware-store.git
   cd 
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Run the development server:**

   ```bash
   npm run dev
   ```

4. **Open in your browser:**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the app.

## Usage

- To explore or modify the code, navigate through the `components`, `features`, and `app` directories.
- The shopping cart logic is managed using **Redux**. You can find the store configuration and cart actions in the `src/lib/features` directory.
- **ShadCN UI** components are used across the app. They can be customized in the `src/components/ui` directory.
- You can easily modify and extend the project to suit your needs, whether for personal use or professional projects.

## Project Structure

```bash
next-auraware-store/
│
├── public/                # Static assets
├── src/
│   ├── app/               # Next.js App Router
│   ├── components/        # Reusable components (including ShadCN UI components)
│   └── lib/
│       ├── features/      # The Redux logics for features (e.g., shopping cart)
│       ├── hooks/         # Custom React hooks
│       ├── store.ts       # Redux store
│       ├── utils.ts       # Utility functions
│   ├── styles/            # Tailwind CSS styles (global, utilities and fonts)
│   ├── types/             # TypeScript types
│
├── components.json         # ShadCN UI configuration
├── next.config.mjs         # Next.js configuration
├── package.json            # Node.js dependencies and scripts
├── postcss.config.mjs      # Post CSS configuration
├── README.md               # Project documentation
├── tailwind.config.ts      # Tailwind CSS configuration
├── tsconfig.json           # TypeScript configuration
```

## Contact

- **Name**: Muneer Raja
- **GitHub**: [https://github.com/MuneerDevCodes](https://github.com/MuneerDevCodes)
