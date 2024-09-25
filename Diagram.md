# Choose Your Own Adventure - Flowchart

```mermaid
flowchart TD
    Start[Start Your Adventure] --> Choice1{Take the Path?}
    
    Choice1 -->|Yes| PathA[You take the path]
    Choice1 -->|No| StayPut[You stay where you are]

    PathA --> Choice2{You encounter a river. Swim across?}
    StayPut --> Rest[You rest under a tree]
    
    Choice2 -->|Yes| Swim[You swim across safely]
    Choice2 -->|No| BackTrack[You turn back]
    
    Swim --> End1[You find treasure!]
    BackTrack --> PathB[You discover another path]

    PathB --> End2[You encounter a friendly traveler]
    Rest --> End3[You enjoy a peaceful afternoon]
