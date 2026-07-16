# Hi, I'm Samet

**Full Stack Developer | Real-Time Interfaces for Physical Hardware | Robotics & IoT**

Computer Engineering graduate with 4+ years building production web, mobile and desktop software. TEKNOFEST winner — first place, Autonomous Robots in Industry. Open to new opportunities.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samet-yilmaz-fd-nd/)

## Professional Experience

### Dost Tarım Teknolojileri — Full Stack Developer | Jul 2025 – Present

_Agricultural robotics & farm management_

- Built the **touchscreen UI for an autonomous milking robot** — Next.js 14 + Zustand, with real-time **Socket.IO** sensor and alarm telemetry across a 30-module API layer.
- Developed the **farm-management web platform** end to end — a 216-file **Next.js/TypeScript** app with Turkish/English **i18n**, Excel/CSV reporting, and a full Figma-based UI rebuild.
- Shipped a **React Native + Expo** herd-management app with offline-first **TanStack Query** caching and live GPS collar tracking.
- Wrote a **Tauri 2 desktop launcher in Rust** — automatic farm-LAN → remote failover, health probing, system-tray status; packaged for Windows, Linux and macOS.
- Built **MQTT-driven** greenhouse locomotive and rail control interfaces — UWB positioning, RFID management, charging control.
- Led a **structural modernization** of the farm app: `src/` layout, Zustand state, next-intl localization, and API-layer decomposition.

### KEND (Poliark) — Full Stack Developer | Sep 2023 – Jun 2025

_Browser-based 3D building & interior design platform_

- **Sole full-stack engineer** on a four-person team (UI designer, AI developer, project manager) — owned **architecture, development and deployment** end to end.
- Built a **browser-based 3D building and room designer** in **Three.js** and **WebGL** — direct-manipulation editing at **CAD-level detail**, modelling windows with frames, doors with knobs, and elevators in both **3D and 2D**.
- Integrated an **AI chat that designs rooms and buildings conversationally** and generates **context-aware renders**, cutting manual design time.
- Built **map-based lot selection** that pulls **parcel polygons** from map data to seed building footprints.
- Developed **14+ backend microservices** with a scalable, service-oriented architecture.
- Designed a subscription-based payment system with **Stripe**.
- Managed service deployments on **Google Cloud Run** and **AWS**.

### WeeScooter (WES Advanced Technologies) — Full Stack Developer | Apr 2022 – Aug 2023

_E-scooter rental platform, 40,000+ users_

- Implemented a secure **mobile wallet and payment system** with **Iyzico**, serving **40,000+ users**.
- Built **identity verification against official government APIs** — validating Turkish citizens, resident immigrants and visiting tourists before rental.
- Developed a **monolith backend** for **real-time hardware communication** with **200+ devices**.
- Contributed to hardware and software installation of e-scooter devices in the field.
- Wallet integration with automatic balance actions.

### TRADENS University Team — Frontend Developer | Jan 2022 – Dec 2024

_TEKNOFEST autonomous industrial robot_

- Built the **web and mobile control apps** (React, React Native) for an autonomous robot that **lifts heavy loads in factories**.
- **The only team in the competition to drive the robot from an app** — every other team mounted a touchscreen on the robot body.
- Implemented **path selection and live factory mapping** — operators send the robot along chosen routes and watch the mapped floor in real time.
- Designed the UI components for both apps.
- **Multiple-time TEKNOFEST winner** with the team.
- Mentored **7 junior (student)** frontend developers.

## Projects

### JSON Sort — Zed Editor Extension

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/sametYILMAZ97/zed-ext-JSON-sort) [![Rust](https://img.shields.io/badge/Rust-000000?logo=rust&logoColor=white)](https://github.com/sametYILMAZ97/zed-ext-JSON-sort)

> VS Code-like **Sort JSON** for [Zed](https://zed.dev) — keys recursively, arrays alphabetically, from the command palette.

- Built in **Rust** against the `zed_extension_api`.
- Supports **JSON**, **JSONC** (comments and trailing commas preserved), and **JSON5**.
- Schema-aware key priority, format / minify, and region-only sorting.
- Exposed as editor **code actions** (`Cmd+.` / right-click).

---

### VSCode Theme Generator — npm CLI

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/sametYILMAZ97/vscode-theme-generator) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/sametYILMAZ97/vscode-theme-generator/blob/main/LICENSE)

> Generate custom VS Code themes from colors using colour-harmony algorithms (Fibonacci ratios).

- Generate themes from a single colour or a palette with harmonious colour algorithms.
- Support for **dark**, **light**, or **both** theme variants.
- Syntax highlighting for **9 languages** (JS, TS, Go, Python, Rust, C, Java, PHP, Ruby).
- Output as JSON theme files or **auto-install** as a VS Code extension.

```bash
npm install -g vscode-theme-generator
vscode-theme-generator generate -l js,python -c "#00ff00" -t dark -s -n "My Theme"
```

---

### Snap It Like It's Hot — Chrome Extension

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/sametYILMAZ97/snap-it-like-its-hot)

> A Vivaldi-inspired screenshot extension for Chrome and Chromium browsers.

- **Capture Element** — auto-detect and highlight elements, with keyboard navigation.
- **Capture Area** — drag-and-drop custom rectangular selection.
- **Capture Full Page** — auto-scroll and stitch into a single high-quality image.
- Handles sticky elements and overflow content via scroll-and-stitch.
- One-click **copy to clipboard** or **save as PNG**.

---

### Google Drive Video Downloader — Chrome Extension

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/sametYILMAZ97/chrome-drive-video-downloader)

> Retrieve private and shared Google Drive videos the built-in player marks as non-downloadable.

- Download **private and shared videos** from Google Drive.
- Works on videos where Drive's own player offers no download option.

---

### Windows 11 Context Menu Manager — Desktop App

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/sametYILMAZ97/windows-11-context-menu-manager)

> Electron desktop app for managing Windows 11 context menu entries.

- Visual interface with a live registry view.
- Safe, fully reversible operations using the standard `LegacyDisable` flag.
- Flexible filtering by target (files, folders, background, drive).
- Backup and restore context menu configurations.
- Ships both a **GUI application** and a **PowerShell CLI**.

---

### Everforest Theme — VS Code & Zed

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/sametYILMAZ97/everforest-theme)

> A comfortable, pleasant theme based on the Everforest colour palette.

- Two variants: dark and light.
- Colours drawn from the official Everforest scheme.
- Complete coverage: editor, UI, terminal and syntax highlighting.

---

### LinkedIn Job Search URL Builder — Web App

[![Repo](https://img.shields.io/badge/GitHub-Repository-181717?logo=github)](https://github.com/sametYILMAZ97/linkedin_job_searcher_nuxt) [![Live Demo](https://img.shields.io/badge/Live-Demo-00DC82?logo=vercel)](https://linkedin-job-searcher-nuxt.vercel.app/)

> Nuxt 3 web app for generating optimized LinkedIn job search URLs.

- Built with **Nuxt 3**, **TypeScript**, **Pinia** and **Tailwind CSS**.
- **Vercel Analytics** and Speed Insights integration.
- Deployed on **Vercel** with a CI/CD pipeline.

## Tech Stack

**Languages & Core**

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=flat&logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=flat&logo=vuedotjs&logoColor=%234FC08D) ![Next JS](https://img.shields.io/badge/Next-black?style=flat&logo=next.js&logoColor=white) ![Nuxt JS](https://img.shields.io/badge/Nuxt-002E3B?style=flat&logo=nuxtdotjs&logoColor=#00DC82) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![Expo](https://img.shields.io/badge/expo-1C1E24?style=flat&logo=expo&logoColor=#D04A37) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white) ![Radix UI](https://img.shields.io/badge/radix%20ui-161618?style=flat&logo=radixui&logoColor=white) ![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=flat&logo=mui&logoColor=white)

**3D & Visualization**

![Three js](https://img.shields.io/badge/threejs-black?style=flat&logo=three.js&logoColor=white) ![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white&style=flat) ![D3](https://img.shields.io/badge/D3-F9A03C?style=flat&logo=d3.js&logoColor=white) ![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat&logo=chart.js&logoColor=white) ![Konva](https://img.shields.io/badge/Konva-0D83CD?style=flat&logoColor=white)

**Real-Time & Hardware**

![Socket.io](https://img.shields.io/badge/Socket.io-black?style=flat&logo=socket.io&badgeColor=010101) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=mqtt&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat&logo=socketdotio&logoColor=white)

**Desktop & Extensions**

![Tauri](https://img.shields.io/badge/tauri-%2324C8DB.svg?style=flat&logo=tauri&logoColor=%23FFFFFF) ![Electron.js](https://img.shields.io/badge/Electron-191970?style=flat&logo=Electron&logoColor=white) ![Chrome](https://img.shields.io/badge/Chrome%20Extensions-4285F4?style=flat&logo=googlechrome&logoColor=white)

**Backend & APIs**

![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=flat&logo=express&logoColor=%2361DAFB) ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=flat&logo=nestjs&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=flat&logo=JSON%20web%20tokens) ![Zod](https://img.shields.io/badge/zod-%233068b7.svg?style=flat&logo=zod&logoColor=white)

**Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=flat&logo=amazon-aws&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=flat&logo=google-cloud&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=flat&logo=vercel&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)

**Database & Storage**

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=flat&logo=Firebase&logoColor=white) ![mongoose](https://img.shields.io/badge/mongoose-%2300DC82.svg?style=flat&logo=mongoose&logoColor=white)

**State Management & Data**

![zustand](https://img.shields.io/badge/zustand-%234A5568.svg?style=flat&logo=zustand&logoColor=white) ![React Query](https://img.shields.io/badge/-TanStack%20Query-FF4154?style=flat&logo=react%20query&logoColor=white) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=flat&logo=redux&logoColor=white) ![Pinia](https://img.shields.io/badge/pinia-FFD859?style=flat&logo=pinia&logoColor=white) ![Framer](https://img.shields.io/badge/Framer-black?style=flat&logo=framer&logoColor=blue)

**Tools & Utilities**

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=flat&logo=vite&logoColor=white) ![Jest](https://img.shields.io/badge/-jest-%23C21325?style=flat&logo=jest&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=flat&logo=eslint&logoColor=white) ![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=flat&logo=prettier&logoColor=F7BA3E) ![Biome](https://img.shields.io/badge/biome-60a5fa?style=flat&logo=biome&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=flat&logo=npm&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=flat&logo=figma&logoColor=white)

## Key Achievements

- **TEKNOFEST Success Certificate** — first place, Autonomous Robots in Industry.
- **Only team at TEKNOFEST to control the competition robot from a web and mobile app** — every other team bolted a touchscreen to the robot.
- **Autonomous milking robot UI** shipped to production touchscreens, driven by live sensor telemetry.
- **CAD-level 3D building designer** with conversational AI and map-based parcel selection.
- **40,000+ active users** on the e-scooter rental platform's monolith service.
- **14+ microservices** architected, coded and deployed — as the sole engineer on the team.
- **Government-API identity verification** for citizens, immigrants and tourists in a regulated rental flow.
- **Secure payment systems** handling thousands of transactions across wallet and subscription flows.
- **Cross-platform desktop app in Rust** with automatic network failover — Windows, Linux and macOS.
- **Code review and mentoring** for interns and junior developers.
- **15 public repositories** — developer tools, editor extensions and browser extensions.
