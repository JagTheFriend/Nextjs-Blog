This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

A simple blog built with Next.js and Firebase,
where the user could:

- make a new post
- edit posts
- delete posts
- use markdown

It uses Firebase for authentication (google specifically) \
and Firestore as a database

## Getting Started

First, Make a new file called `.env.public`\
Paste this few lines inside of that file:

```.env
NEXT_PUBLIC_FIREBASE_API_KEY = <Put your apiKey>
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN = <Put your authDomain>
NEXT_PUBLIC_FIREBASE_PROJECT_ID = <Put your projectId>
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET = <Put your storageBucket>
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID = <Put your messagingSenderId>
NEXT_PUBLIC_FIREBASE_APP_ID = <Put your appId>
```

Then run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
