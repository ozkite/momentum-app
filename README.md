# 🌊 Momentum: The Anti-Procrastination Mirror

**Stop Avoiding. Start Flowing.** Momentum is a high-stakes habit formation app built for the "New You." Unlike traditional trackers, Momentum targets the **friction of starting** by breaking down avoided tasks with AI and utilizing **Loss Aversion** through stablecoin staking.

&gt; Destroy procrastination. Stake on yourself. Win by doing.

Momentum is an anti-procrastination accountability platform that combines behavioral psychology (loss aversion) with micro-task generation to help users overcome starting friction on avoided tasks while building positive habits.

## 🎯 The Problem
Traditional to-do lists create anxiety. Habit trackers feel like chores. **Starting is the hardest part.**

## The Solution
1. **The Mirror**: Ask "What are you avoiding right now?" → AI breaks it into 5-minute micro-steps
2. **The Stake**: Bet $1+ weekly on yourself (higher stakes = more raffle tickets)
3. **The Raffle**: Complete goals → enter weekly raffles (coffee credits, cash prizes)
4. **The Loop**: Avoid bad habits (doom scrolling) by filling void with 20+ micro-achievements

## 🚀 The Core Loop
1. **The Mirror:** Tell the AI what you are avoiding. It gives you 5 micro-steps.
2. **The Micro-Habits:** Complete "Mind, Body, Spirit" tasks (Touch grass, breathe, stretch).
3. **Skin in the Game:** Stake $1+ per week. Complete your goals to enter the monthly $100+ Caffeine Raffle.

## 🛠 Tech Stack
- **Caffeine.ai** 
- **Framework:** Next.js 15 (App Router)
- **USDT**, **USDC** Stablecoin smart ocntract addresses
- **Styling:** Tailwind CSS + Shadcn UI
- **Backend/Auth:** Supabase
- **AI:** OpenAI GPT-4o-mini (Task Decomposition)
- **Payments:** Stripe (Fiat-to-Staked Credit)
- - **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS + shadcn/ui
- **Database**: Supabase (PostgreSQL + Auth)
- **Payments**: Stripe (Stablecoin/USDC support)
- **AI**: Vercel AI SDK (OpenAI GPT-4o-mini for micro-task generation)
- ICP Canisters
- USDT or USDC on ICP, ckUSD or ckUSDT
- Fiat onramper
- Login component
-     Frontend: Next.js with TypeScript
    Backend: Next.js API Routes
    Database: SQLite with Prisma ORM
    Authentication: NextAuth.js
    Payments: Stripe for card processing and stablecoin conversion
    Styling: Tailwind CSS
    UI Components: Radix UI
  

## 📦 Features
- **AI Task Shredder:** Turns big fears into 5-minute wins.
- **The Avoidance List:** 30+ habits to quit (Doomscrolling, Snoozing, etc.).
- **Weekly Raffles:** Gamified financial incentives.
- **Group Pulses:** Anonymous 3-5 person accountability pods.
- [x] AI Task Decomposition (5-min micro-steps)
- [x] USDC Staking with Weekly Lockups
- [x] Weighted Raffle System (more tasks + higher stake = better odds)
- [x] 30-Free-Habit Library (Mind/Body/Spirit)
- [x] Welcome Boost (2x Multiplier for first week)


┌─────────────────────────────────────────────────────────────┐
│                     NEXT.JS 15 (App Router)                  │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐       │
│  │   Dashboard  │  │  AI Decomp.  │  │   Checkout   │       │
│  │   (RSC)      │  │   (Route)    │  │   (Route)    │       │
│  └──────────────┘  └──────────────┘  └──────────────┘       │
└─────────────────────────────────────────────────────────────┘
│
┌───────────────────┼───────────────────┐
▼                   ▼                   ▼
┌──────────────┐   ┌──────────────┐   ┌──────────────────┐
│   Supabase   │   │   OpenAI     │   │     Stripe       │
│  (Auth/DB)   │   │ (GPT-4o-mini)│   │ (USDC Checkout)  │
└──────────────┘   └──────────────┘   └──────────────────┘

