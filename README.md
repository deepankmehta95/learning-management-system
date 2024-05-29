This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First crate a new .env file by copying .env.example file.

Second, you need to sign up on all the 3rd party platforms which are used in this repo and update the .env file with required API keys.

Third, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 3rd Party Platforms Used

Various types of 3rd party platforms used are:

- [Clerk](https://clerk.com) - For authentication.
- [Uploadthing](https://uploadthing.com) - For uploading of images and asset files.
- [Stripe](https://stripe.com) - For course purchases.
- [Mux](https://www.mux.com) - For managing video information.

## Note

This is not a full fledged platform like Udemy or Coursera. This is a simple platform where, there can only be one admin and he/she can manage their courses. To be an admin you have to update your user id in `NEXT_PUBLIC_TEACHER_ID` in .env file.
