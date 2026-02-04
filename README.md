
``` mermaid
flowchart TD
    A[User opens app] --> B{First time?}
    B -->|Yes| C[Claim Welcome Boost 2x]
    B -->|No| D[Morning Check-in]
    
    C --> D
    
    D --> E[What are you avoiding?]
    E --> F[AI generates 5 micro-steps]
    F --> G[Select 3+ habits<br/>Mind/Body/Spirit]
    
    G --> H{Staked this week?}
    H -->|No| I[Stake $1+ USDC<br/>via Stripe]
    H -->|Yes| J[Daily Dashboard]
    I --> J
    
    J --> K[Complete micro-steps<br/>and habits throughout day]
    K --> L{Week end?}
    L -->|No| J
    L -->|Yes| M{Goals met?}
    
    M -->|Yes| N[Refund stake<br/>plus Raffle tickets<br/>equals habits times stake times multiplier]
    M -->|No| O[Forfeit to prize pool]
    
    N --> P[Weekly Raffle<br/>Win Caffeine Credits<br/>or Cash]
    O --> Q[Try again next week<br/>Streak reset]
    
    P --> R[New Week<br/>Streak bonus plus 10%]
    Q --> R
    R --> D
    
    style A fill:#e1f5ff
    style N fill:#d4edda
    style O fill:#f8d7da
    style P fill:#fff3cd
```
