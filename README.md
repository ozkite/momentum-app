
``` mermaid
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
