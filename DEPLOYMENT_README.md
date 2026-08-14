# Arogga Homeo — Deployment Package

This is the Arena.ai-generated Next.js e-commerce storefront for Arogga Homeo.

## Important
The storefront uses PostgreSQL for products, reviews and orders. A public deployment therefore needs a PostgreSQL database and a `DATABASE_URL` environment variable.

## Deployment
1. Create a PostgreSQL database with a hosted provider.
2. Import this project into a Git repository or connect the ZIP contents to a Next.js host such as Vercel.
3. Add `DATABASE_URL` to the deployment's environment variables.
4. Run the database migration/seed commands from the project's existing Drizzle setup.
5. Deploy.

## Local commands
```bash
npm install
npm run dev
```

## Brand
Arogga Homeo
Phone: 01923885555
