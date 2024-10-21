
# 📧 AI-Powered Email Client

An advanced AI-powered email client built using **Next.js 14**, designed to streamline email management with intelligent features. This fully-featured application includes a premium subscription model, where users can unlock additional functionality. Payments are securely handled via Stripe, with real-time event processing enabled through webhooks. The app is optimized for performance and scalability, leveraging a wide range of modern web technologies.

## 🛠️ Features

- **AI-Generated Emails**: Compose emails with the help of AI, powered by the OpenAI API.
- **Premium Subscription**: Users can subscribe for premium features, with payments processed by Stripe.
- **User Authentication**: Secure authentication and user management provided by Clerk.
- **Real-Time Event Handling**: Stripe webhooks for payment and subscription management.
- **Scalable Backend**: Prisma ORM and PostgreSQL for efficient database management.
- **Optimized UI**: Fully responsive UI using Tailwind CSS, enhanced with `clsx` and `tailwind-merge`.
- **Vector Search**: Fast, intelligent search functionality powered by Pinecone.
- **Deployed on Vercel**: Easily deployable and scalable serverless architecture.

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
   git clone https://github.com/your-username/ai-email-client.git
   cd ai-email-client
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Create a `.env.local` file in the root directory and add the following environment variables:

   ```bash
    add required api keys
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


---
THANK YOU
