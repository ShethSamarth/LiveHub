# LiveHub (Twitch Clone)

This is a repository for Fullstack Twitch Clone: Next.js 14, Livestreaming, React, Server Actions, TailwindCSS, ShadCN UI.

Key Features:

- Streaming using RTMP / WHIP protocols
- Generating ingress
- Connecting Next.js app to OBS / Other streaming software
- Thumbnail upload
- Live viewer count
- Live channel statuses
- Real-time chat using sockets
- Unique color for each viewer in chat
- Following & Blocking system
- Kicking participants from a stream in real-time
- Streamer / Creator Dashboard
- Slow chat mode
- Followers only chat mode
- Enable / Disable chat
- Collapsible layout (hide sidebars, chat, theatre mode etc.)
- Sidebar following & recommendations tab
- Syncing user information to our DB using Webhooks
- Syncing live status information to our DB using Webhooks
- Community tab
- Clerk Authentication
- MySQL Database
- Prisma ORM
- ShadcnUI & TailwindCSS
- Full mobile responsiveness

# Final Version

To visit the website, [click here.](https://livehub-ss.vercel.app/)

### Cloning the repository

```shell
git clone https://github.com/ShethSamarth/livehub.git
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=

LIVEKIT_API_URL=
LIVEKIT_API_KEY=
LIVEKIT_API_SECRET=
NEXT_PUBLIC_LIVEKIT_WS_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

### Install packages

```shell
npm install
```

### Setup prisma

```shell
npx prisma db push
```

### Start the app

```shell
npm run dev
```
