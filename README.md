## Getting Started

First, run the next development server:

```bash
npm run dev:next
```

Then open another terminal to generate prisma client and run the prisma server:

```bash
npm run dev:prisma
```

In order to deploy database schema locally and populate with seed data run:

```bash
npm run prisma:initital-setup
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

Open [http://localhost:4466/prisma/local/\_admin](http://localhost:4466/prisma/local/_admin) to access prisma admin(local database).
Run `npm run prisma:token` to generate a secret token for prisma admin. Copy and paste it in the project settings on the right top side of the prisma admin.
