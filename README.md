# AIChatBot

A Next.js AI chat application built with the AI SDK, featuring OpenAI integration.

Ref from AI SDK: https://ai-sdk.dev/docs/getting-started/nextjs-app-router

## Getting Started

First, set up your environment variables:

1. Create a `.env.local` file in the root directory
2. Add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

Then, run the development server:

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

## Features

- Real-time chat with OpenAI GPT-4o
- Streaming responses
- Error handling and validation
- Modern UI with Tailwind CSS

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.
- [AI SDK Documentation](https://ai-sdk.dev/docs/getting-started/nextjs-app-router) - learn about AI SDK integration.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
