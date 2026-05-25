# Chapter 29: Creating Variation 2: Mutation Over Generations

## Core Idea
Make one duplicate, change it, then duplicate the change, and so on. Each generation is a mutation of the previous generation — creating an evolutionary chain.

## Frameworks Introduced
- **Mutation over generations**: Make one duplicate, change it, then duplicate the change, and so on. Each generation is a mutation of the previous generation, not the original.
- **Evolutionary chain**: Each step is a small mutation of the previous step — the chain can drift far from the original.
- **Generational distance**: The more generations, the more distant from the original — use this to control variation distance.

## Key Concepts
- **Small steps**: Each mutation should be small enough to maintain recognizability
- **Drift**: Over many generations, the idea can drift far from the original — this is a feature, not a bug
- **Chain of custody**: Keep track of which generation is which — you need to know the lineage
- **Selection**: At each step, decide which version to mutate next — selection is creative

## Mental Models
- Use mutation over generations when you want gradual evolution from a single idea
- Think of it as "natural selection" applied to musical ideas
- Each generation is a small step — the cumulative effect is large

## Anti-patterns
- **Large jumps**: Making big changes at each step loses the evolutionary connection
- **No selection**: Randomly choosing which version to mutate next
- **Too many generations**: Eventually the connection to the original is lost entirely

## Key Takeaways
1. Make one duplicate, change it, then duplicate the change, and so on
2. Each generation is a mutation of the previous generation, not the original
3. Keep mutations small to maintain recognizability
4. Selection at each step is a creative decision
5. The chain can drift far from the original — this is a feature, not a bug

## Connects To
- **ch28**: Mutation of Clones — the parallel version of this technique
- **ch30**: Note Transformations — specific types of mutations
- **ch55**: Repetition and Insistence — gradual variation prevents monotony
- **ch61**: Dramatic Arc — evolutionary chains can create dramatic arcs
