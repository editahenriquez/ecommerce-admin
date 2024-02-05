# Full Stack E-Commerce + Dashboard & CMS - E-Commerce
 
It's built using Next.js, React, Prisma, MySQL, Shadcn and Tailwind CSS

## Features

- Dashboard as both CMS, Admin and API!
- Control multiple stores
- CRUD of billboards, categories, products, colors, sizes (API for all these cases)
- Feature products to show on the homepage
- Order creation
- Stripe checkout
- Stripe webhooks
- See orders, graph of revenues
- Clerck authentication

![Ecommerce](Ecommerce.png?raw=true "Ecommerce ")

### <a href="https://ecommerce-admin-projectm.vercel.app/">LIVE DEMO</a>

## 1. Clone the repository

Firstly, you will need to run the following command in the Terminal to clone the repository onto your machine.

```git clone https://github.com/editahenriquez/ecommerce-admin.git```

## 2. Usage

Open your web browser and visit `http://localhost:3000`

## 3. Setup .env file

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/
DATABASE_URL=
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
STRIPE_API_KEY=
FRONTEND_STORE_URL=http://localhost:3001
STRIPE_WEBHOOK_SECRET=

## Credits

##### Inspiration from

<a href="https://github.com/AntonioErdeljac">AntonioErdeljac</a>