#Next-React Frontend for Restaurants
in full rendering
 ![restaurants](https://github.com/aasmah/Restaurant-frontend-backend/assets/35153854/9afd7cb1-e4a9-4340-803b-3b3df7bea9d3)
'restaurants.png'>

## use yarn and then yarn dev to run the code

Do NOT do a yarn build
index3.js (Data is hardcoded)
index.js (Get data from Strapi using Apollo and GraphQL)
restaurantList.js is Web Component to render restaurants

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/import?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Running with Docker

Before dockerizing the application and running the restaurantapp with the Dockerfile and docker-compose.yml, you will need to create your own .env file with credentials for strapi and mongodb. An example of what that file could look like is in env.txt file.