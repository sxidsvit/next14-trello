## Fullstack Trello Clone

### Next.js 14, Server Actions, React, Prisma, Stripe, Tailwind, MySQL

[Visit site](https://next14-trello-sxidsvit.vercel.app/)

Key Features:
- Auth 
- Organizations / Workspaces
- Board creation
- Unsplash API for random beautiful cover images
- Activity log for entire organization
- Board rename and delete
- List creation
- List rename, delete, drag & drop reorder and copy
- Card creation
- Card description, rename, delete, drag & drop reorder and copy
- Card activity log
- Board limit for every organization
- Stripe subscription for each organization to unlock unlimited boards
- Landing page
- MySQL DB
- Prisma ORM
- shadcnUI & TailwindCSS

### Prerequisites

**Node version 18.x.x**



##### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_SIGN_UP_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=

DATABASE_URL=

NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

NEXT_PUBLIC_APP_URL=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=
```

### Setup Prisma

Add MySQL Database (I used PlanetScale)

```shell
npx prisma generate
npx prisma db push

```

### Start the app

```shell
npm run dev
```
---

##### Contact with me: 
[<img alt="webDev | LinkedIn" src="https://img.shields.io/badge/linkedin-0077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />][linkedin]

[linkedin]: https://www.linkedin.com/in/sergiy-antonyuk/

##### I can't express how much I have learned from [you](https://www.youtube.com/@codewithantonio) ! <br> Thanks for the hard and smart work.


![](demo.gif)