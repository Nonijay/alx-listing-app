# Alx Listing App

## Overview of the project
The ALX Listing App project aims to scaffold and lay the foundational structure for a modern Airbnb clone. This initial milestone focuses on setting up a well-organized and scalable codebase using Next.js, TypeScript, TailwindCSS, and ESLint. By establishing a clean folder structure, reusable components, and adhering to best practices, the project ensures a solid starting point for building a dynamic, responsive, and user-friendly property listing page.

## Learning Objectives
This milestone is designed for professional developers to strengthen their expertise in modern web application development. By completing this milestone, learners will:
    - Gain hands-on experience scaffolding a Next.js project tailored for production readiness.
    - Implement TypeScript for type safety and reusable interfaces to enhance code maintainability and robustness.
    - Configure TailwindCSS for building responsive, accessible, and visually appealing UI components.
    - Structure a Next.js project following industry-standard best practices, ensuring scalability and readability.
    - Create foundational reusable components and organize assets effectively for real-world applications.

## Requirements
To successfully complete this milestone, learners must meet the following prerequisites:
    - Basic knowledge of Next.js, React, and TypeScript.
    - Familiarity with TailwindCSS and modern styling techniques.
    - Understanding of ESLint and its role in maintaining code quality.
    - Proficiency in organizing and structuring projects for scalability.

## Technical Requirements
    - Next.js version 13+.
    - Node.js version 16+ installed locally.
    - Text editor (e.g., VS Code) with TypeScript and TailwindCSS extensions installed.

## Key Highlights
    1. project setup
        - Scaffold a Next.js application named alx-listing-app with TypeScript, ESLint, and TailwindCSS enabled.
        - Configure TailwindCSS using a minimal and clean configuration (tailwind.config.js and globals.css).
    
    2. Folder Structure and Reusability
        - Establish a clean folder structure, including directories for components/, interfaces/, constants/, and public/assets/.
        - Create reusable components such as Card and Button for modularity and scalability.
    
    3. TypeScript Integration
        - Define TypeScript interfaces (CardProps, ButtonProps, etc.) in interfaces/index.ts to ensure type safety and code consistency.

    4. Asset Management
        - Organize assets, including images and SVGs, under public/assets/ for easy access and maintenance.
        - From this Figma Mockup

    5. Documentation and Run Instructions
        - Create a comprehensive README.md file with details about the project, its goals, folder structure, and steps to run the project locally.
        - Verify the project setup by running it locally and ensuring all configurations work seamlessly.


## Getting Started on a NextJs Project

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/pages/building-your-application/routing/api-routes) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/pages/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn-pages-router) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/pages/building-your-application/deploying) for more details.
