# Llama2-Chat

A proof-of-concept of a ChatGPT-like chat frontend for Llama2.

## Technical Components

- Vercel AI SDK;
- Replicate and the Replicate TypeScript SDK;
- Vercel;
- `llama-2-70b-chat`, hosted on Replicate: https://replicate.com/meta/llama-2-70b-chat

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Resources

- https://sdk.vercel.ai/docs/guides/providers/replicate
- https://vercel.com/docs/integrations/ai/replicate

# Next Steps

- Incorporate chat history, rate limiting, session storage, etc w/ Vercel KV, as explained here: https://vercel.com/templates/Next.js/nextjs-ai-chatbot
- Record past chat histories
- “Red flag” a chat
    - Denote that something in there constitutes an exploit
    - Categorize exploit (hate, bias, etc.) (finite list)

## Getting Started

First, run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.