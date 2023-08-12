# Spotify Clone with Next 13 : React, PostgreSQL, Stripe, Tailwind, Supabase.

For DEMO, use [Stripe Testing Cards](https://stripe.com/docs/testing)

Features:

- Song upload
- File and image upload using Supabase storage
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Stripe integration
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with Supabase
- Handling relations between Server and Child components in a real-time environment
- Cancelling Stripe subscriptions
- Github authentication integration
- Stripe recurring payment integration
- Play song audio
- Favorites system
- Playlists / Liked songs system
- Advanced Player component

### Prerequisites

**Node version 14.x**

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

### Add SQL Tables
Use `database.sql` file, create songs and liked_songs table (there is a video tutorial)

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
