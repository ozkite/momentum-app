``mermaid
 flowchart TD
    Start((Open Momentum)) --> Welcome{First Time?}
    
    Welcome -- Yes --> Boost[Claim 2x Multiplier Welcome Boost]
    Welcome -- No --> Mirror[<b>The Mirror:</b> What are you avoiding?]
    
    Boost --> Mirror
    
    Mirror --> AI[AI Task Shredder: GPT-4o-mini]
    AI --> Steps[5-Minute Micro-Steps Generated]
    
    Steps --> Select[Select Daily Habits: Mind/Body/Spirit]
    
    Select --> Stake{Stake Momentum?}
    Stake -- No --> Browse[Browse Only Mode]
    Stake -- Yes --> Payment[Stripe / ckUSDC Stablecoin Stake]
    
    Payment --> Daily[Daily Check-in Loop]
    
    Daily --> Verify{Goal Met?}
    Verify -- Yes --> Progress[Maintain Streak + Raffle Entry]
    Verify -- No --> Loss[Stake Released to Prize Pool]
    
    Progress --> Weekly[Weekly Caffeine Raffle]
    Weekly --> Monthly[Monthly $20 Streak Prize]
```

```mermaid
flowchart TB
    subgraph Client["Client Layer"]
        A[Next.js 15 App Router]
        B[React Server Components]
        C[Tailwind plus shadcn/ui]
    end
    
    subgraph Edge["Edge Layer"]
        D[Vercel Edge Network]
        E[Middleware/Auth]
    end
    
    subgraph API["API Layer"]
        F[Server Actions]
        G[Stripe Checkout API]
        H[OpenAI Streaming API]
        I[Supabase Client]
    end
    
    subgraph Data["Data Layer"]
        J[Supabase PostgreSQL]
        K[Row Level Security]
        L[Real-time Subscriptions]
    end
    
    subgraph External["External Services"]
        M[Stripe Payments<br/>Fiat to USDC]
        N[OpenAI GPT-4o-mini]
        O[ICP ckUSDC<br/>Future Settlement]
    end
    
    A --> D
    D --> E
    E --> F
    F --> G
    F --> H
    F --> I
    I --> J
    J --> K
    J --> L
    G --> M
    H --> N
    M -.->|Phase 2| O
    
    style Client fill:#e1f5ff
    style API fill:#fff3cd
    style Data fill:#d4edda
    style External fill:#ffe6cc
```
