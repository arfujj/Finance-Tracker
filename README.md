<a name="readme-top"></a>

# Personal Finance Tracker
## By Arfaan Jeddy


steps to run

1. Make sure **Git** and **NodeJS** is installed.
3. Create `.env.local` file in **root** directory.
4. Contents of `.env.local`:
5. 'npm install' and then 'npm run dev'

```env
# .env.local

NEXT_TELEMETRY_DISABLED=1

NEXT_PUBLIC_APP_URL=http://localhost:3000

# clerk auth keys
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_d2VsY29tZS1hbnRlYXRlci03NC5jbGVyay5hY2NvdW50cy5kZXYk
CLERK_PUBLISHABLE_KEY=pk_test_d2VsY29tZS1hbnRlYXRlci03NC5jbGVyay5hY2NvdW50cy5kZXYk
CLERK_SECRET_KEY=sk_test_5VcVaLkxEm2HqfazL75vzJyAMbOmGWK90HLuE14ArE

# clerk redirect url
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# neon db url
DATABASE_URL=postgresql://neondb_owner:etTxlX9NsDA0@ep-holy-star-a5f3z4m5.us-east-2.aws.neon.tech/neondb?sslmode=require

# app base url
NEXT_PUBLIC_APP_URL=http://localhost:3000

```


