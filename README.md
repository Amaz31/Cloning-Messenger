This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

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

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

### Prerequisites

Node Version 14.x

### Setup .env file

```bash
DATABASE_URL= (mongoDB : https://www.mongodb.com/fr-fr/cloud/atlas/lp/try4)
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY= (See https://cloudinary.com/ and copy paste pusher_app key)
PUSHER_APP_ID= (See https://cloudinary.com/ and copy paste app_id key)
PUSHER_SECRET= (See https://cloudinary.com/ and copy paste secret key)

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME= (See https://cloudinary.com/ and copy paste cloud name)

GITHUB_ID= (See https://github.com and copy paste ID key)
GITHUB_SECRET= (See https://github.com and copy paste secret key)

GOOGLE_CLIENT_ID= (See https://google.com/ and copy paste client ID)
GOOGLE_CLIENT_SECRET= (See https://google.com/ and copy paste client secret)
```

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Key Features

Key Features:

- Real-time messaging using Pusher  
- Message notifications and alerts  
- Tailwind design for sleek UI  
- Tailwind animations and transition effects  
- Full responsiveness for all devices  
- Credential authentication with NextAuth  
- Google authentication integration  
- Github authentication integration  
- File and image upload using Cloudinary CDN  
- Client form validation and handling using react-hook-form  
- Server error handling with react-toast  
- Message read receipts  
- Online/offline user status  
- Group chats and one-on-one messaging  
- Message attachments and file sharing  
- User profile customization and settings    
