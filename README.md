# YUMMY

Yummy is an online food ordering application built with T3 Stack including Next.js, Typescript, tRPC, NextAuth.js, Stripe, Next-intl, React Query, Prisma, Tailwind CSS, Chadcn UI, Zustand, Framer Motion, Neon DB and a variety of modern web technologies.
It allows users to easily browse menus, place and checkout orders, and manage their accounts.
The application supports both Arabic and English languages.
Yummy integrates a robust admin panel dashboard to manage users easily, orders, categories, and products.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Environment Variables](#environment-variables)
- [Technologies Used](#technologies-used)

## Features

- User authentication and authorization: Secure login system for users and admins.
- Menu browsing and food item selection: Users can browse through a variety of menu options and select their desired food items.
- Order placement and management: Users can place orders for food items, and admins can manage these orders.
- Responsive design for mobile and desktop: The application is designed to be accessible and usable on both mobile devices and desktop computers.
- Real-time order updates: Users receive real-time updates on the status of their orders.
- Secure payment processing with Stripe: Integration with Stripe for secure payment processing.
- Multi-language support: The application supports both Arabic and English languages.
- Admin dashboard: An administrative interface where admins can manage users, orders, categories, and products. This includes functionalities such as:
  - User management: Admins can view, create, edit, and delete user accounts.
  - Order management: Admins can view and update the status of orders, such as marking them as fulfilled or canceled.
  - Category management: Admins can manage categories of food items, including creating, editing, and deleting categories.
  - Product management: Admins can manage individual food products, including adding new products, updating existing ones, and removing products from the menu.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Maahmoud-Elsayed/online-food-ordering.git
   cd online-food-ordering

   ```

2. Install dependencies:

```bash
npm install

```

3. Set up the environment variables:

Create a .env file in the root of the project and add the necessary environment variables as described in the Environment Variables section.

4. Run the development server:

```bash
npm run dev

```

Open your browser and navigate to http://localhost:3000.

## Usage

To start the application in development mode, use:

```bash
npm run dev
```

To build the application for production, use:

```bash
npm run build
```

To start the application in production mode, use:

```bash
npm start
```

## Environment Variables

The application requires several environment variables to be set. Create a .env file in the root of your project and add the following variables:

```bash
DATABASE_URL=your_database_url
NEXTAUTH_SECRET=your_nextauth_secret
GITHUB_ID=your_github_id
GITHUB_SECRET=your_github_secret
GOOGLE_ID=your_google_id
GOOGLE_SECRET=your_google_secret
NEXTAUTH_URL=http://localhost:3000
RESEND_API_KEY=your_resend_api_key
UPLOADTHING_SECRET=your_uploadthing_secret
UPLOADTHING_APP_ID=your_uploadthing_app_id
STRIPE_PUBLIC_KEY=your_stripe_public_key
STRIPE_SECRET_KEY=your_stripe_secret_key
STRIPE_WEBHOOK_KEY=your_stripe_webhook_key
UPSTASH_REDIS_REST_URL=your_upstash_redis_rest_url
UPSTASH_REDIS_REST_TOKEN=your_upstash_redis_rest_token
NEXT_PUBLIC_ADMIN_PASSWORD=your_test_admin_account_password
```

Replace `your_*` with the appropriate values for your setup.

### Technologies Used

- Next.js: React framework for server-side rendering and static site generation
- NextAuth.js: Authentication for Next.js
- TypeScript: Superset of JavaScript for static typing
- Prisma: ORM for database management
- TRPC: Typesafe APIs using TypeScript
- Chadcn UI: Accessible UI components
- Tailwind CSS: Utility-first CSS framework
- Zustand: State management library
- Stripe: Payment processing
- Framer Motion: Animations
- React Hook Form: Forms and validation
- Zod: TypeScript-first schema declaration and validation
- Uploadthing: to upload files
- Upstash: Redis database service for rate limiting
- React Email: Email components and management
- Neon DB: Serverless Postgres database
- React Query: Data fetching and synchronization
- Next-intl: Internationalization for Next.js applications
