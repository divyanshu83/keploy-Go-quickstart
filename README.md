# Testing Go APIs with Keploy — Echo + Postgres

This repository contains a **single-page, beginner-friendly documentation site** that explains how to test Go APIs using **Keploy’s automatic test generation**.

The tutorial walks through recording real API traffic from a Go Echo application backed by Postgres and replaying it as deterministic tests—without manually writing test cases.

🔗 **Live Demo:** https://keploy-go-quickstart.vercel.app

---

## What the tutorial covers

* What Keploy is and how it works
* Setting up Keploy with a Go Echo + Postgres application
* Recording real API interactions as test cases
* Replaying recorded interactions as deterministic tests
* Understanding Keploy’s value for Go developers

The content is written for developers who have **never used Keploy before**.

---

## Tech stack

* **Next.js 14** (App Router)
* **MDX** for documentation content
* **Tailwind CSS** for styling

The setup is intentionally minimal to keep the focus on the tutorial itself.

---

## Running locally

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## Build

Create a production build:

```bash
npm run build
npm start
```

---

## Project structure

```text
├── app/
│   ├── layout.tsx          # Root layout and metadata
│   ├── page.mdx            # Main tutorial content
│   └── globals.css         # Global styles
├── components/
│   ├── Callout.tsx         # Info / warning / success callouts
│   ├── CodeBlock.tsx       # Code block with copy-to-clipboard
│   └── ThemeToggle.tsx     # Light / dark mode toggle
├── mdx-components.tsx      # MDX component mapping
├── next.config.mjs         # Next.js + MDX configuration
└── tailwind.config.ts      # Tailwind configuration
```

---


## About the documentation

This tutorial is structured as a **documentation-style guide**.

It prioritizes:

* Step-by-step explanations
* Real commands and outputs
* Practical developer workflows

The goal is to help developers understand Keploy by actually *using* it, rather than reading abstract descriptions.

---

## License

This project is licensed under the **MIT License**.
