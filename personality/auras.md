---
title: Psychic auras
author: Ruan Hanthequeste
copyright: © 2026 Ruan Hanthequeste. All rights reserved.
version: 0.1.0
created: 2026-10-27
updated: 2026-10-27
layout: default
---

# Psychic auras

- What motivates people?
- How different can personal goals be?
- What people do with their free time?
- Given freedom, health and resources, what one focus on?
- Given that a person is functional, what makes them different from others?

## Auras and their symbolic activities

```mermaid
---
config:
  theme: base
  mindmap:
    colorBy: branch
  themeVariables:
    git0: '#5d5d5e'
    gitBranchLabel0: '#ffffff'
    cScale1: '#9b5c5c'
    cScaleLabel1: '#ffffff'
    cScale2: '#526b8a'
    cScaleLabel2: '#ffffff'
    cScale3: '#526f5b'
    cScaleLabel3: '#ffffff'
    cScale4: '#f1e2b8'
    cScaleLabel4: '#493f2c'
---
mindmap
  Person
    Body / Red
      Power and influence
      Reproductive drive
      Pain avoidance
      Survival
      Eat
    Mind / Blue
      Creation and intellectual discovery
      Learning and teaching
      Music composition
      Classification
      Think
    World / Green
      Music production
      Craftsmanship
      Exploration
      Painting
      Walk
    People / Yellow
      Social life and belonging
      Music performance
      Caretaking
      Status
      Talk
```

The activities listed are symbolic, i.e. meant to illustrate. They can be enjoyable for any type of person regardless of their aura type.

## Auras relation

```mermaid
flowchart LR
  subgraph Body
    bm[Mind]
    bw[World]
    bp[People]
  end

  subgraph People
    pm[Mind]
    pw[World]
    pb[Body]
  end

  subgraph World
    wm[Mind]
    wp[People]
    wb[Body]
  end

  subgraph Mind
    mw[World]
    mp[People]
    mb[Body]
  end

  classDef body fill:#9b5c5c,color:#ffffff,stroke:#6f4040
  classDef people fill:#f1e2b8,color:#493f2c,stroke:#c8b77e
  classDef world fill:#526f5b,color:#ffffff,stroke:#3c5143
  classDef mind fill:#526b8a,color:#ffffff,stroke:#3b4e66

  class Body body
  class People people
  class World world
  class Mind mind

  class bp people
  class bw world
  class bm mind

  class pb body
  class pw world
  class pm mind

  class wb body
  class wp people
  class wm mind

  class mb body
  class mp people
  class mw world
```

Every aura contains the others as tools.

## Personality development stack

```mermaid
flowchart BT
  Body --unlocks--> People --unlocks--> World --unlocks--> Mind

  classDef body fill:#9b5c5c,color:#ffffff,stroke:#6f4040
  classDef people fill:#f1e2b8,color:#493f2c,stroke:#c8b77e
  classDef world fill:#526f5b,color:#ffffff,stroke:#3c5143
  classDef mind fill:#526b8a,color:#ffffff,stroke:#3b4e66

  class Body body
  class People people
  class World world
  class Mind mind
```

1. The bare minimum body control unlocks words usage.
2. The bare minimum social interaction unlocks knowledge on traversing the world both outward and inward.
3. The bare minimum first hand experience of the world unlocks abstraction interest, and the possibility of intellectual pursuits.

Access to the world is a condition to the autonomy of thought, otherwise people rely entirely on what they heard other people say. For instance if a scientific result can't be reproduced one must trust the initial data.
