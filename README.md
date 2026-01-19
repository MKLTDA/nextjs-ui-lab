# nextjs-ui-lab
{
  "name": "nextjs-ui-lab",
  "private": true,
  "version": "0.1.0",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "14.1.0",
    "react": "^18.2.0",
    "react-dom": "^18.2.0"
  }
}
/** @type {import('next').NextConfig} */
const nextConfig = {
  reactStrictMode: true,
};

module.exports = nextConfig;
export const metadata = {
  title: "Frontend UI Lab",
  description: "Educational frontend layout and deployment experiments",
};

export default function RootLayout({
  children,
}: {
  children: React.ReactNode;
}) {
  return (
    <html lang="en">
      <body style={{ margin: 0, fontFamily: "Arial, sans-serif" }}>
        {children}
      </body>
    </html>
  );
}
export default function Home() {
  return (
    <main style={{ padding: "40px" }}>
      <h1>Frontend UI Lab</h1>
      <p>
        This project is used exclusively for educational and technical testing
        with Next.js.
      </p>

      <section style={{ marginTop: "24px" }}>
        <h2>Project Goals</h2>
        <ul>
          <li>Frontend layout experiments</li>
          <li>Component structure testing</li>
          <li>Deployment and build workflow validation</li>
        </ul>
      </section>
    </main>
  );
}
# Frontend UI Lab

This repository contains a simple Next.js project created strictly for
**educational and technical experimentation**.

## Purpose
- Frontend layout and UI structure testing
- Routing and rendering experiments with Next.js
- Deployment and build workflow validation

## Non-commercial use
This project:
- Is not intended for commercial use
- Is not affiliated with any company or brand
- Does not replicate, impersonate, or compete with any real platform

All content and UI elements are generic and created solely for learning purposes.

## Tech Stack
- Next.js
- React
- TypeScript

## Status
Active for personal learning and technical experimentation only.
<p style={{ marginTop: "16px", fontSize: "14px", opacity: 0.7 }}>
  No real users, data collection, or monetization involved.
</p>
