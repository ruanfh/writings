---
title: Reality structure
author: Ruan Hanthequeste
copyright: © 2026 Ruan Hanthequeste. All rights reserved.
version: 0.1.1
created: 2026-10-18
updated: 2026-10-21
layout: default
---


# Reality structure

## Simplified model

```mermaid
flowchart TB
	A[Archetypes]
	U[Universe]
	S[Sentience]
	A --Instantiation--> U
	A --Discovery--> S
	U --Sensation--> S
	S --Action--> U
```

## Disks and processes
Imagine the whole reality is a computer.
It would require three kinds of disk:

| Disk type  | Permissions |
| ---------- | ----------- |
| Archetypal | Read-only   |
| Sentient   | Append-only |
| Universal  | Read-write  |

The Universal-disk is updated by the Universal-process.

Each sentient being is its own process.
Each sentient being would own a partition of the Sentient-disk, which would be private.

The Archetypal-disk, from here on called the Archetypes, has all instructions.
All the mathematical constants, all the physical constants and all the psychological constants.

The Archetypes have all the required instructions for the Universal-process and the Sentient-processes.

### Instantiation

The Universal-process reads from the Universal-disk, then reads the instructions in the Archetypes, then apply the transformation and finally writes the result on the Universal-disk.

```mermaid
flowchart TB
	subgraph U[Universe]
		S[Universal-disk]
		C[Universal-process]
		end
	S --Feeds--> C
	C ~~~ A[Archetypes]
    A -.Instructions.-> C
	C --Instantiates--> S 
```

### Discovery

Given the current state of a sentient being, the Archetypes contain the instructions to the next possible states.
Free will is the pointer that chooses the set of instructions to apply.

```mermaid
flowchart TB
    subgraph S[Sentient being]
        D[Sentient-disk-partition]
        P[Sentient-process]
        end
	D --Feeds--> P
	P ~~~ A[Archetypes]
    A -.Instructions.-> P
	P --Discovery--> D 
```

### Body, Sentience and the Universe

The Body, being part of the Universe, is the interface through which sentience both receives sensation from and acts upon the Universe.

```mermaid
flowchart TB
    subgraph S[Sentient being]
        D[Sentient-disk]
        P[Sentient-process]
        end
    subgraph U[Universe]
        B[Body]
        E[Environment]
        end
    D --Action--> P
    B --Sensation--> P
    P --Add--> D
    P --Update--> B
    B <-.Interact.-> E
```

### Communication between sentient beings

Given what was established so far, communication works the following way:

```mermaid
flowchart TB
	P1[Sentient being 1]
	P2[Sentient being 2]
	U[Universe]
	P1 --Action--> U
	P2 --Action--> U
	P1 <-.Communication.-> P2
	U --Sensation--> P1
	U --Sensation--> P2
```

## Notes

### Note on Antoine Lavoisier
Lavoisier said:
> "Nothing is lost, nothing is created, everything is transformed."

This may apply to the Universal-disk.
But it does not apply to the Sentient-disk, which is in constant creation.
Nor does it apply to the Archetypes which are never transformed.

### Note on Roger Penrose
I developed this model independently, then later encountered Roger Penrose's account of the mathematical, physical, and mental worlds.
Although there are similarities, his account differs substantially from my view of reality.

### Note on Edward Fredkin
Edward Fredkin's digital physics treats physical processes as computational.
By contrast, I use computation only as a symbol for describing reality.
