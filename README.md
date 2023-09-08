# MiniBlog

## Introduction

MiniBlog is a text-based social sharing web application inspired by Threads. 

## Features

- Create threads
- Comment on threads
- Search thread creators
- Community management
- Activity tracking

## Getting Started

To set up MiniBlog locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/IrisWRX/MiniBlog.git
   ```

2. Change into the project directory:

   ```bash
   cd MiniBlog
   ```

3. Install the dependencies using npm:

   ```bash
   npm i
   ```

4. Create a Clerk account and set up a project named "MiniBlog".

5. Select Next.js and obtain your API key.

6. Create a .env file in the project root and add the following necessary environment variables:
   ```
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=
   NEXT_CLERK_WEBHOOK_SECRET=
   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
   NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
   NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

   MONGODB_URL=

   UPLOADTHING_SECRET=
   UPLOADTHING_APP_ID=
   ```

7. After you have installed the dependencies, you can start the development server:
   ```bash
   npm run dev
   ```
   This will launch the development server, and you can access the application by visiting http://localhost:3000 in your web browser.
