# Computational Models of Memory and Forgetting

A Python project exploring how memories can be represented, strengthened, forgotten, interfered with, and retrieved using simple computational models.

The goal of this project is to build increasingly sophisticated models of memory while developing an intuitive understanding of the mathematics and computational principles behind learning and forgetting.

## Models

### Model 1 — Passive Memory Decay

Introduces a numerical representation of memory strength over time using exponential decay.

### Model 2 — Memory Reinforcement

Models how repeated reinforcement can strengthen a memory and keep it above a retrieval threshold.

### Model 3 — Spaced Repetition

Models how periodically reinforcing a memory can preserve its retrievability over longer periods of time.

### Model 4 — Memory Consolidation

Builds upon spaced repetition by allowing the decay rate to decrease as a memory is repeatedly reinforced, representing increasing resistance to forgetting.

### Model 5 — Memory Interference

Models how the formation of a new memory can interfere with and weaken the retrievability of an existing memory.

### Model 6 — Competitive Retrieval

Models retrieval as competition between memories, where a stronger competing memory can prevent another memory from being successfully retrieved.

### Model 7 — Hebbian Learning

Introduces Hebbian learning, where the strength of a connection increases based on the simultaneous activity of presynaptic and postsynaptic neurons.

This allows memory strength to emerge from simulated neural activity rather than being manually assigned.

### Model 8 — Bounded Hebbian Learning

Extends the Hebbian learning model by introducing diminishing strengthening as a connection approaches its maximum strength.

This prevents connection strength from increasing indefinitely and causes repeatedly activated connections to converge toward an upper bound.

### Model 9 — Hebbian Learning with Rehearsal and Decay

Combines Hebbian strengthening with exponential decay.

At each event, a memory may be rehearsed, causing its neural connection to strengthen, or remain inactive, causing the connection to decay.

The model also compares several rehearsal probabilities to explore how rehearsal frequency affects long-term connection strength. More frequent rehearsal produces stronger and more persistent connections, while infrequent rehearsal allows decay to dominate.

## Tools

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Current Direction

The next stage of the project will use Monte Carlo simulation to run the rehearsal-and-decay model many times for each rehearsal probability.

This will make it possible to examine average long-term connection strength, variability between simulations, and whether there is a rehearsal frequency at which Hebbian strengthening begins to consistently outweigh decay.

Future experiments may also vary parameters including:

- Presynaptic activity
- Postsynaptic activity
- Initial connection strength
- Learning rate
- Decay rate

These experiments can help explore how different learning and forgetting mechanisms interact within the model.

Longer-term models may combine learning, decay, consolidation, interference, and competitive retrieval into a more complete computational memory system.

## Motivation

Memory is not simply a matter of storing or deleting information. Memories can weaken over time, become strengthened through repetition, interfere with one another, and compete during retrieval.

At the neural level, learning can also be understood as changes in the strength of connections between neurons.

This project explores how these processes can emerge from relatively simple mathematical rules and computational mechanisms, while developing an understanding of the intersection between mathematics, neuroscience, and cognitive science.