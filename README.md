# 🌊 Momentum: The Anti-Procrastination Mirror

**Stop Avoiding. Start Flowing.** *Destroy procrastination. Stake on yourself. Win by doing.*

Momentum is a high-stakes accountability platform that transforms the "anxiety of starting" into micro-wins. Using behavioral psychology (loss aversion) and AI-driven task decomposition, Momentum helps you crush procrastination while building a "New You" through Mind, Body, and Spirit habits.

## 🎯 The Hook
Traditional to-do lists create anxiety. **Momentum** targets the friction of starting by asking one simple question: *"What are you avoiding right now?"*

---

## 🚀 How It Works

1.  **The Mirror:** Tell the AI what you're avoiding. It uses GPT-4o-mini to shred that scary task into **5-minute micro-steps**.
2.  **The Habit Grid:** Select from 30+ free habits (Touch grass, 3-min meditation, no-doomscrolling) to fill your day with positive momentum.
3.  **The Stake:** Put "Skin in the Game." Stake $1+ (via Stripe/USDC) on your weekly success. 
4.  **The Raffle:** Success keeps your money and enters you into the **Weekly Caffeine Raffle** and the **Monthly $20 Streak Prize**.

---

## 🛠 Tech Stack

- **Framework:** Next.js 15 (App Router) + TypeScript
- **Styling:** Tailwind CSS + shadcn/ui
- **Backend/Auth:** Supabase (PostgreSQL + Auth)
- **AI Engine:** Vercel AI SDK + OpenAI GPT-4o-mini
- **Web3/Stablecoin:** ICP Canisters (ckUSDC / ckUSDT) for transparent prize pools.
- **Payments:** Stripe (Fiat-to-Stablecoin onramp)
- **Incentives:** Caffeine.ai integration for reward distribution.

---

## 📦 Core Features

### 🧠 Mind, Body, Spirit Library (30+ Habits)
- **Mind:** 3-min meditation, 5 pages of reading, 4-7-8 breathing.
- **Body:** Stretch arms, 10 squats, splash cold water, drink 500ml water.
- **Spirit:** Hug a tree, touch grass, say good morning to 3 people, gratitude log.

### 🚫 The Avoidance List (The "Anti-Habits")
Track and quit: Snoozing the alarm, excess doomscrolling, caffeine after 3 PM, and more.

### 💸 The Financial Engine
- **Weekly Lockups:** Stake USDT/USDC to prove your commitment.
- **Weighted Raffles:** Higher stakes + more tasks = higher probability of winning.
- **Welcome Boost:** New users claim a **2x Win Multiplier** for their first week.

### 👥 Group Pulses
Anonymous pods of 3-5 people for social accountability without the noise of social media.

---

## 🏗 Project Structure

```text
/momentum
├── app/
│   ├── api/shred/route.ts     # AI Task Decomposition
│   ├── api/webhooks/stripe    # Stablecoin staking logic
│   ├── dashboard/             # Main Checklist & Mirror UI
│   └── raffle/                # Winners & Rankings
├── components/
│   ├── mirror/                # AI Input & Step display
│   ├── habits/                # Checklist & Progress rings
│   └── staking/               # Stripe/ICP Integration
├── lib/
│   ├── supabase/              # DB Clients
│   └── habits-data.ts         # Library of 30+ items
└── supabase/
    └── schema.sql             # Users, Stakes, Logs
