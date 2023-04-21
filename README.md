# Next.js 13 and Server Components Experiment

## Project Overview:

This open-source project, created by Shadcn, is one of the most exciting projects I've worked on. It explores the potential of Next.js 13 and server components in building a modern app with advanced features such as authentication, subscriptions, API routes, and static pages. By pushing the boundaries of cutting-edge technologies, this experiment serves as a valuable learning experience and demonstrates the power of these tools in creating innovative applications.

> **Warning**
> This app is a work in progress.

## Design Process:

to build on this project you need to utilized a range of tools and libraries :

- Next.js 13 (canary release) and
- React 18
- NextAuth.js for authentication
- Prisma as an ORM
- PlanetScale for database management
- Radix UI for UI components
- MDX and Contentlayer for documentation and blog content
- Stripe for subscriptions
- Tailwind CSS for styling
- Zod for validations
- TypeScript for better type safety and developer experience

I'll be posting updates and issues here.

A few people have asked me to turn this into a starter. I think we could do that once the new features are out of beta.

## Note on Performance

## Key Features:

- New /app directory
- Routing, Layouts, Nested Layouts, and Layout Groups
- Data Fetching, Caching, and Mutation
- Loading UI
- Server and Client Components
- API Routes and Middlewares
- Authentication using NextAuth.js
- ORM using Prisma
- Database on PlanetScale
- UI Components built using Radix UI
- Documentation and blog using MDX and Contentlayer
- Subscriptions using Stripe
- Styled using Tailwind CSS
- Validations using Zod
- Written in TypeScript

**follow these steps:**

1. ~GitHub authentication (use email)~
2. ~[Prisma: Error: ENOENT: no such file or directory, open '/var/task/.next/server/chunks/schema.prisma'](https://github.com/prisma/prisma/issues/16117)~
3. ~[Next.js 13: Client side navigation does not update head](https://github.com/vercel/next.js/issues/42414)~

## Running Locally

1. Install dependencies using pnpm:

```sh
pnpm install
```

2. Copy `.env.example` to `.env.local` and update the variables.

```sh
cp .env.example .env.local
```

3. Start the development server:

```sh
pnpm dev
```

## License

Licensed under the [MIT license](https://github.com/shadcn/taxonomy/blob/main/LICENSE.md).
