# 🚀 Ignite Call - Next 🚀

Ignite call is a scheduling app, where the user can register on the website, connect with their Google account and provide a scheduling link to their clients and/or friends. 

Those who receive the link can choose an available day and time from the registered user's calendar.

Automatically, when making a schedule, information with date, time, name, email and notes are added to the Google calendar of the user who provided the access link to their schedule screen. The available days and times are defined when registering.

### 👉 Links: 
- Web: [here](https://ignite-call-degui1s-projects.vercel.app/)

## ▶ How to start project

```shell
  npm i

  # Dev mode
  npm run dev

  # Prod mode
  npm run build
  npm run preview 
```

## ⚙ Config Section
```bash
# Prisma - both URLs are used to connect to the database
DATABASE_URL="url"
DATABASE_DIRECT_URL="url"

# Google oAuth - These keys are provided by Google so that the website can use OAuth2.0
GOOGLE_CLIENT_ID=id
GOOGLE_CLIENT_SECRET=secret

# NextAuth - NextAuthSecret is required to use NextAuth. You can create a random string.
NEXTAUTH_SECRET=secret

```

### 🛠 Tools:
 - React 
 - TypeScript
 - Stitches
 - Next
 - Next Auth
 - googleapis
 - Radix UI
 - Next SEO
 - Zod
 - Prisma
 - React Query
 - React hook forms
 
### ✔ You can:
- Connect your Google Calendar
- Provide a scheduling link to your clients and/or friends
- Automatically add appointments to your calendar
