# AI Edge Newsletter

## Setup

1. Install dependencies:
```
npm install -g pnpm
pnpm install
```

2. Copy `.env.example` to `.env` and fill in your values:
```
cp .env.example .env
```

3. Build the app:
```
pnpm run build
```

4. Start the server:
```
pnpm run start
```

## Deploy to Railway

1. Push this folder to GitHub
2. Go to railway.app → New Project → Deploy from GitHub
3. Add environment variables from .env
4. Done!

## Environment Variables

- `BEEHIIV_API_KEY` - Get from beehiiv.com dashboard
- `DATABASE_URL` - MySQL connection string
- `PORT` - Port to run on (Railway sets this automatically)
