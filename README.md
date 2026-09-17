## Hi, I'm Igor 👋

Full-stack developer. I build web products end to end — typed React / Next.js front
ends on top of Node and NestJS APIs, with real databases, payments, queues and deploys.

### Projects

| Project | What it is |
| --- | --- |
| [**quizway-web**](https://github.com/igstX4/quizway-web) | Quiz platform as one fullstack Next.js 15 app — App Router and Server Actions, Drizzle ORM over SQLite so it starts with no database server to install, quizzes with single choice, multiple choice, true/false and short-text questions. Supabase auth and Stripe billing are wired but optional. |
| [**quizway-api**](https://github.com/igstX4/quizway-api) | The same domain rebuilt as gRPC microservices: a NestJS gateway plus auth, quiz and worker services behind typed protobuf contracts, Prisma for persistence and a queue that runs in memory by default or on Redis (`QUEUE_DRIVER`). Docker Compose and Kong configs included. |
| [**N-Note**](https://github.com/igstX4/N-Note) | Notes you can share with a single link. React client, NestJS + MongoDB API, JWT access tokens with refresh rotation in `httpOnly` cookies and e-mail confirmation on sign-up. |
| [**check-client**](https://github.com/igstX4/check-client) | Operations platform front end: a back office for applications, checks, clients, companies and sellers, plus a key-based portal where a client tracks their own requests. React + TypeScript + Vite, Redux Toolkit for client state and TanStack Query for server state. |
| [**joy_client**](https://github.com/igstX4/joy_client) | PlayStation digital store delivered as a Telegram Mini App — catalogue, cart, balance top-up, purchase history and an admin panel, with the session established by the Telegram WebApp SDK instead of a login form. |
| [**clay**](https://github.com/igstX4/clay) | Landing page for a pottery studio: workshop tariffs, portfolio, reviews and a booking flow, with a hand-written weekly date picker and GSAP-driven section scrolling. |

### Toolbox

**Front end** — React 18/19 · Next.js · TypeScript · Redux Toolkit · TanStack Query · Tailwind CSS · MUI · Ant Design · SCSS modules · Framer Motion

**Back end** — NestJS · Express · gRPC · Prisma · Drizzle ORM · PostgreSQL · MongoDB · Redis · SQLite · Stripe · Supabase

**Tooling** — Docker · GitHub Actions · Vercel · Jest · Vitest · Playwright · ESLint · Prettier

---

📫 The fastest way to reach me is here on GitHub — issues and pull requests are welcome.
