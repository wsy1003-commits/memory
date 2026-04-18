# P-Reinforce Classification Policy

This document tracks the reinforcement learning policy weights and rules for categorizing wiki notes.

## Current Weights
- w1 (Categorization Accuracy): 0.4
- w2 (Graph Connectivity): 0.3
- w3 (User Satisfaction): 0.3

## Boundary Shifts
*(Records of user corrections that update boundaries between categories)*
- (Example) "Wait, this is AI, not just Tech." -> Adjusted vector boundary for `Topics/AI`.

## Auto-Refactoring Rules
- Split folders when file count exceeds 12.
