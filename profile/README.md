<div align="center">
  <a href="https://www.reactylon.com/docs">
     <img width="960" alt="reactylon-hero" src="https://github.com/user-attachments/assets/1d3484d2-c180-41e3-8737-10c366ad32f8" />
  </a>
<br/><br/>
  <p>
    <strong>XR-first React ecosystem built on Babylon.js for production-ready WebXR and 3D experiences.</strong>
  </p>

  <p>
    Build real 3D & XR products with React, not just tech demos.
  </p>
</div>

---

## 🌍 Vision

Reactylon aims to be the place where:

- **XR-first React architectures** are explored, refined, and shared.  
- **Real product patterns** are extracted from real-world 3D/XR apps, not just playgrounds.  
- Tooling for **tree-shakable, type-safe, cross-platform** 3D experiences keeps evolving.  

If you’re building or planning serious **WebXR and 3D applications with React and Babylon.js**, Reactylon is the ecosystem you can grow in, not just experiment with.

---

## 🧬 What’s inside the Reactylon ecosystem?

### 1. Core framework — [`reactylon`](https://github.com/simonedevit/reactylon)

The **brain** of the ecosystem.

- Declarative syntax for Babylon.js in JSX  
- Deep React integration (state, hooks, composition)  
- Automatic scene injection and object management  
- Cross-platform: desktop & mobile browsers, PWAs, XR/VR/AR headsets

> You stay in React. Reactylon drives Babylon.js across web, mobile, and XR headsets.

---

### 2. Build-time magic — [`babel-plugin-reactylon`](https://github.com/simonedevit/babel-plugin-reactylon)

The **compiler sidekick**.

- Statically analyzes Reactylon JSX elements  
- Generates deep, tree-shakable ES modules from `@babylonjs/core` and `@babylonjs/gui`  
- Automatically injects required side-effect imports

> You write clean JSX. The plugin makes the bundle smart and lean.

---

### 3. Zero-config starter — [`create-reactylon-app`](https://github.com/simonedevit/create-reactylon-app)

The **fast lane** into Reactylon.

- Bootstraps a **React 19** project with Webpack and Reactylon prewired  
- Configures Babylon.js engine, physics, and a starter scene  
- Gives you a runnable project in one command: `npx create-reactylon-app my-app`

> You run one command. It scaffolds a Reactylon boilerplate app for you.

---

### 4. Starter templates

Clone-and-go starter templates for popular React stacks:

- **Vite** - [`reactylon-vite-starter`](https://github.com/simonedevit/reactylon-vite-starter)  
  Minimal SPA setup with Vite + React + TypeScript, ideal for iterating quickly on 3D/XR scenes.

- **Next.js (App Router)** - [`reactylon-nextjs-starter`](https://github.com/simonedevit/reactylon-nextjs-starter)  
  Production-ready shell with routing, SSR, and SEO, while keeping Reactylon logic in client components.

- **Astro** - [`reactylon-astro-starter`](https://github.com/simonedevit/reactylon-astro-starter)  
  Integration starter that shows how to mount a Reactylon React app inside an Astro project via `client:only="react"`.

> Pick the stack you already use, clone a starter, and focus on your scenes instead of wiring configs.
