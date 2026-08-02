# React & Next.js App Router Rules

When working in this Next.js repository, follow these rules:

1. **App Router Only:** Strictly use the Next.js App Router (`app/` directory). Do not use the old `pages/` router.
2. **Server Components First:** Default to React Server Components. Only use `"use client"` when state or browser APIs are required at the lowest leaf nodes.
3. **Styling:** Use Tailwind CSS for all styling. Do not write custom CSS or CSS modules unless strictly necessary for complex animations.
4. **Data Fetching:** Use Next.js native `fetch` with appropriate caching strategies (`revalidate`, `cache: 'no-store'`).
5. **Types:** Use TypeScript. Avoid `any`. Define interfaces for all props and API responses.
