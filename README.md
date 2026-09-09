# Computational Models of Memory and Forgetting

A Python project exploring how memories can be represented, strengthened, forgotten, interfered with, and retrieved using simple computational models.

The goal of this project is to build increasingly sophisticated models of memory while developing an intuitive understanding of the mathematics and computational principles behind learning and forgetting.

## Models
### Model 1 — Passive Memory Decay

Introduces a simple numerical representation of memory strength over time. Follows a simple exponential decay function.

### Model 2 - Memory Reinforcement

Models how memories can be reinforced, keeping them above the retrieval threshold.

### Model 3 - Spaced Repetition

Models spaced repetition, keeping the memory above the retrieval threshold.

### Model 4 - Memory Consolidation

Builds upon Model 3 to model how with spaced repetition, the decay rate slows.

### Model 5 - Memory Interference

Models the strength of an old memory versus the strength of an interfering memory.

### Model 6 — Competitive Retrieval

Models retrieval as competition between memories, where stronger competing memories can prevent an older memory from being retrieved.

## Tools
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## Current Direction

The next stage of the project will introduce learning mechanisms, beginning with Hebbian learning. This will allow memory strengths to emerge from simulated experience rather than being manually assigned.

Future models may combine learning, decay, interference, and competitive retrieval into a more complete computational memory system.

## Motivation

Memory is not simply a matter of storing or deleting information. Memories can weaken over time, become difficult to retrieve, or compete with other information.

This project explores how these processes can emerge from relatively simple mathematical rules and computational mechanisms, delving into the intersection of mathematics and cognitive science.
