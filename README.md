<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Custom Apparel Store Blueprint</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
        }
        h1, h2, h3 {
            border-bottom: 1px solid #d0d7de;
            padding-bottom: 0.3em;
        }
        code {
            font-family: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace;
            background-color: rgba(209, 213, 219, 0.4);
            padding: 0.2em 0.4em;
            margin: 0;
            font-size: 85%;
            border-radius: 6px;
        }
        pre {
            background-color: #f6f8fa;
            border-radius: 6px;
            padding: 16px;
            overflow: auto;
        }
        pre code {
            background-color: transparent;
            padding: 0;
            margin: 0;
            font-size: 100%;
        }
    </style>
</head>
<body class="bg-white text-gray-900">
    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
        <article class="prose lg:prose-xl">
            <h1 class="text-4xl font-bold mb-4">Custom Apparel E-Commerce Store Blueprint</h1>
            <p class="text-lg text-gray-600">This document provides a comprehensive technical blueprint for a full-stack e-commerce platform specializing in custom-printed apparel. It serves as a complete roadmap for the development team, covering everything from the technology stack to deployment.</p>


cd custom-apparel-store</code></pre>
            <h3 class="text-xl font-semibold mt-4 mb-2">2. Install Dependencies</h3>
            <p>Install the necessary packages for both the frontend and backend.</p>
            <pre><code># In the /frontend directory
npm install

# In the /backend directory
npm install</code></pre>
            <h3 class="text-xl font-semibold mt-4 mb-2">3. Set Up Environment Variables</h3>
            <p>Create a <code>.env</code> file in the <code>/backend</code> directory. You will need to add your database connection string and other secret keys.</p>
            <pre><code>DATABASE_URL="postgresql://user:password@localhost:5432/mydb"
JWT_SECRET="your_jwt_secret"
STRIPE_SECRET_KEY="your_stripe_secret_key"</code></pre>
            <h3 class="text-xl font-semibold mt-4 mb-2">4. Run Database Migrations</h3>
            <p>Use Prisma to sync your database schema.</p>
            <pre><code># In the /backend directory
npx prisma migrate dev</code></pre>
            <h3 class="text-xl font-semibold mt-4 mb-2">5. Start the Development Servers</h3>
            <p>Run both the frontend and backend applications concurrently.</p>
            <pre><code># Start the backend API server (from /backend)
npm run dev

# Start the frontend Next.js server (from /frontend)
npm run dev</code></pre>
        </article>
    </main>
</body>
</html>
