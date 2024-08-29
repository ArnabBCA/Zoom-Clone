
# Zoom Clone

A Web video conferencing platform similar to ZOOM.

## Live Demo 🍿
[Zoom Clone](https://zoom-meet-clone.vercel.app/)

## Authors 🧑‍💻

- [@ArnabBCA](https://github.com/ArnabBCA)

## Tech Stack ⚙️

Frontend Technologies : Next.js, Tailwindcss, Shadcn, TypeScript <br /> Authentication : Clerk <br /> Video & Audio SDK : Stream

## Run Locally 💻

Clone the project

```bash
git clone https://github.com/ArnabBCA/Zoom-Clone
```

Go to the project directory

Install dependencies

```bash
npm install
```

To run the `project`, you will need to add the following environment variables to your `.env.local` file

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY='XXXXXXXXXXXXXXXXXX'      # CLERK PUBLISHABLE KEY        
CLERK_SECRET_KEY='XXXXXXXXXXXX'                             # CLERK SECRET KEY

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
                                      
NEXT_PUBLIC_STREAM_API_KEY='XXXXXXXXXXXX'                   # STREAM_API_KEY
STREAM_SECRET_KEY='XXXXXXXXXXXXX'                           # STREAM_SECRET_KEY

NEXT_PUBLIC_BASE_URL=localhost:3000
```
Start the dev server

```bash
npm run dev
```
Your `frontend` should start. Now you can go to the `URL` below 🎉

```bash
http://localhost:3000
```
