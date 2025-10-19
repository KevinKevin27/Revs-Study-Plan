## Inspiration
For what we based our project off, we were heavily inspired by various Quizlet games that utilized that information from the study sets. Additionally, we were also inspired by Google's 'Doodle Champion Island Games' doodle. Unfortunately, as Quizlet became more and more paid, access to educational entertainment experiences that were specific to what needed to be learned was severely limited. This is what inspired us to make this program.
## What it does
The user has the capability to search up any topic or subject they'd like. Utilizing a web-scraping API, the program dynamically searches the Knowt website and uses its export feature to gather all of the flashcard data as plain text. Processing this text, the program uses these flashcards as the basis for various mini-games such as Skate Invaders.
## How we built it
We created a Python script that does the web-scraping through an API. Additionally, we used the Phaser game engine to write the games. We then implemented the games into a website utilizing React, NextJS, NodeJS, and TypeScript where the games are ran on the website with the information provided from the web-scraping Python script.
## Challenges we ran into
There was initial difficulty scraping the Knowt website to gather the data required for the postcards as it took a while to commit to a API for gathering, although the processing was much simpler once the text was acquired. More difficulties were had with the various games, since we had to merge the Phaser game engine with the other website frameworks which created instability and a learning-curve on implementation. We definitely wanted to produce more games but ultimately only had time to design, create, and implement just one.
## Accomplishments that we're proud of
We are proud of the web-scraping mechanic, as it is very dynamic and adjusts to things such as alternative webpages from the Knowt website. Additionally, we are proud of the first-hand knowledge gained regarding React and various other frameworks, as this was one of our first times utilizing these. Finally, we are also proud of the art produced for the project, as all of it is hand-made and has a coquette pixel art-style.
## What we learned
As previously mentioned, we learned a lot about React and other frameworks such as NextJS and NodeJS. Additionally we gained knowledge of API's and the syntax and formatting required to use one. Most importantly, we learned the importance of teamwork and collaborating. Collaboration!
## What's next for Rev's Study Plan
If possible, we would love to more games to the website, and even add systems between games such as currency with a shop, navigation, or more graphics.

This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
