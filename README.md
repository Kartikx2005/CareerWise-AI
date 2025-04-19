# Full Stack AI Career Coach with Next JS, Neon DB, Tailwind, Prisma, Inngest, Shadcn UI Tutorial 🔥🔥
## https://youtu.be/UbXpRv5ApKA

![sensai](https://github.com/user-attachments/assets/eee79242-4056-4d19-b655-2873788979e1)

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
```

```
ai-career-coach
├─ .eslintrc.json
├─ README.md
├─ actions
│  ├─ cover-letter.js
│  ├─ dashboard.js
│  ├─ interview.js
│  ├─ resume.js
│  └─ user.js
├─ app
│  ├─ (auth)
│  │  ├─ layout.js
│  │  ├─ sign-in
│  │  │  └─ [[...sign-in]]
│  │  │     └─ page.jsx
│  │  └─ sign-up
│  │     └─ [[...sign-up]]
│  │        └─ page.jsx
│  ├─ (main)
│  │  ├─ ai-cover-letter
│  │  │  ├─ [id]
│  │  │  │  └─ page.jsx
│  │  │  ├─ _components
│  │  │  │  ├─ cover-letter-generator.jsx
│  │  │  │  ├─ cover-letter-list.jsx
│  │  │  │  └─ cover-letter-preview.jsx
│  │  │  ├─ new
│  │  │  │  └─ page.jsx
│  │  │  └─ page.jsx
│  │  ├─ dashboard
│  │  │  ├─ _component
│  │  │  │  └─ dashboard-view.jsx
│  │  │  ├─ layout.js
│  │  │  └─ page.jsx
│  │  ├─ interview
│  │  │  ├─ _components
│  │  │  │  ├─ performace-chart.jsx
│  │  │  │  ├─ quiz-list.jsx
│  │  │  │  ├─ quiz-result.jsx
│  │  │  │  ├─ quiz.jsx
│  │  │  │  └─ stats-cards.jsx
│  │  │  ├─ layout.js
│  │  │  ├─ mock
│  │  │  │  └─ page.jsx
│  │  │  └─ page.jsx
│  │  ├─ layout.jsx
│  │  ├─ onboarding
│  │  │  ├─ _components
│  │  │  │  └─ onboarding-form.jsx
│  │  │  └─ page.jsx
│  │  └─ resume
│  │     ├─ _components
│  │     │  ├─ entry-form.jsx
│  │     │  └─ resume-builder.jsx
│  │     └─ page.jsx
│  ├─ api
│  │  └─ inngest
│  │     └─ route.js
│  ├─ favicon.ico
│  ├─ globals.css
│  ├─ layout.js
│  ├─ lib
│  │  ├─ helper.js
│  │  └─ schema.js
│  ├─ not-found.jsx
│  └─ page.js
├─ components
│  ├─ header.jsx
│  ├─ hero.jsx
│  ├─ theme-provider.jsx
│  └─ ui
│     ├─ accordion.jsx
│     ├─ alert-dialog.jsx
│     ├─ badge.jsx
│     ├─ button.jsx
│     ├─ card.jsx
│     ├─ dialog.jsx
│     ├─ dropdown-menu.jsx
│     ├─ input.jsx
│     ├─ label.jsx
│     ├─ progress.jsx
│     ├─ radio-group.jsx
│     ├─ select.jsx
│     ├─ sonner.jsx
│     ├─ tabs.jsx
│     └─ textarea.jsx
├─ components.json
├─ data
│  ├─ faqs.js
│  ├─ features.js
│  ├─ howItWorks.js
│  ├─ industries.js
│  └─ testimonial.js
├─ eslint.config.mjs
├─ hooks
│  └─ use-fetch.js
├─ jsconfig.json
├─ lib
│  ├─ checkUser.js
│  ├─ inngest
│  │  ├─ client.js
│  │  └─ function.js
│  ├─ prisma.js
│  └─ utils.js
├─ middleware.js
├─ next.config.mjs
├─ package-lock.json
├─ package.json
├─ postcss.config.mjs
├─ prisma
│  ├─ migrations
│  │  ├─ 20250114060115_create_models
│  │  │  └─ migration.sql
│  │  ├─ 20250114064152_update_user
│  │  │  └─ migration.sql
│  │  ├─ 20250117091806_update
│  │  │  └─ migration.sql
│  │  ├─ 20250120090020_hh
│  │  │  └─ migration.sql
│  │  ├─ 20250120124732_update
│  │  │  └─ migration.sql
│  │  └─ migration_lock.toml
│  └─ schema.prisma
├─ public
│  ├─ banner.jpeg
│  ├─ banner2.jpeg
│  ├─ banner3.jpeg
│  └─ logo.png
└─ tailwind.config.mjs

```