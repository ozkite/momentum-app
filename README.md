``` flowchart TD
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

``` flowchart TD
    A[User Signs Up] --> B[The Mirror: Identify Challenge]
    B --> C[AI Breaks Down into 5-Minute Steps]
    C --> D[Select Habits to Build/Avoid]
    D --> E[Stake USDC/USDT on Weekly Goals]
    E --> F[Complete Daily Micro-Habits]
    F --> G[Track Progress & Check Off Tasks]
    G --> H[Complete Weekly Goals]
    H --> I[Enter Raffle with Weighted Odds]
    I --> J[Win Rewards or Try Again]
    J --> B
    
    style A fill:#e1f5fe
    style B fill:#b3e5fc
    style C fill:#81d4fa
    style D fill:#4fc3f7
    style E fill:#29b6f6
    style F fill:#03a9f4
    style G fill:#039be5
    style H fill:#0288d1
    style I fill:#0277bd
    style J fill:#01579b
```
