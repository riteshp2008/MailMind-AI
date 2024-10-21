Here's an updated **GitHub README** file with the new name **MailMind-AI**:

---

# 📧 MailMind-AI

MailMind-AI is an advanced AI-powered email client built with **Next.js 14**, designed to enhance your email management with intelligent features. This fully-featured application includes a premium subscription model, allowing users to unlock additional capabilities. Payments are securely managed via Stripe, with webhooks facilitating real-time event handling. The application is optimized for performance and scalability using modern web technologies.

## 🛠️ Features

- **AI-Generated Emails**: Compose emails effortlessly with AI, powered by OpenAI API.
- **Premium Subscription**: Unlock premium features through Stripe payment integration.
- **User Authentication**: Secure user authentication and management via Clerk.
- **Real-Time Event Handling**: Stripe webhooks for payment and subscription management.
- **Scalable Backend**: Efficient database management using Prisma ORM and PostgreSQL.
- **Responsive UI**: Fully responsive, modern UI using Tailwind CSS, clsx, and tailwind-merge.
- **Advanced Search**: Intelligent search functionality powered by Pinecone vector search.
- **Deployed on Vercel**: Scalable serverless architecture with Vercel deployment.

## 🖥️ Tech Stack

- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS, clsx, tailwind-merge
- **Backend**: Node.js, Prisma ORM, PostgreSQL, Neon Database Serverless
- **AI Integration**: OpenAI API, OpenAI Edge, Pinecone
- **Payments & Subscription**: Stripe, Webhooks
- **Authentication**: Clerk
- **Cloud & Deployment**: AWS SDK, Vercel
- **API Handling**: Axios, @tanstack/react-query

## 🚀 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/mailmind-ai.git
   cd mailmind-ai
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Create a `.env.local` file in the root directory and add the following environment variables:

   ```bash
   NEXT_PUBLIC_CLERK_FRONTEND_API=<Your Clerk Frontend API>
   CLERK_API_KEY=<Your Clerk API Key>
   DATABASE_URL=<Your PostgreSQL Database URL>
   STRIPE_SECRET_KEY=<Your Stripe Secret Key>
   OPENAI_API_KEY=<Your OpenAI API Key>
   PINECONE_API_KEY=<Your Pinecone API Key>
   ```

4. Set up the Prisma database:

   ```bash
   npx prisma migrate dev
   ```

5. Run the development server:

   ```bash
   npm run dev
   ```

   The app should now be running on [http://localhost:3000](http://localhost:3000).

## 🧪 Testing

Run the following command to execute tests:

```bash
npm run test
```

## 📦 Deployment

Deploy your project easily to Vercel:

1. Install the Vercel CLI:

   ```bash
   npm i -g vercel
   ```

2. Link your project:

   ```bash
   vercel link
   ```

3. Deploy your app:

   ```bash
   vercel --prod
   ```

---

❤️🔥
