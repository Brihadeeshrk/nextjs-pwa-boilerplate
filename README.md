# Next.js PWA Template

This is a [Next.js](https://nextjs.org) Progressive Web Application (PWA) project that follows the official [Next.js PWA documentation](https://nextjs.org/docs/app/building-your-application/configuring/progressive-web-apps). It uses the latest Next.js version with TypeScript, Tailwind CSS, and Turbopack.

## Prerequisites

Before getting started, you'll need to:

1. Install web-push and its TypeScript types globally:

```bash
npm install -g web-push
npm install --save-dev @types/web-push
```

2. Generate VAPID keys:

```bash
web-push generate-vapid-keys
```

3. Create a `.env` file in the root directory and add your VAPID keys:

```env
NEXT_PUBLIC_VAPID_PUBLIC_KEY=your_public_key_here
VAPID_PRIVATE_KEY=your_private_key_here
```

## Getting Started

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js and PWAs, take a look at the following resources:

- [Next.js PWA Documentation](https://nextjs.org/docs/app/building-your-application/configuring/progressive-web-apps) - learn about PWA features in Next.js
- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
