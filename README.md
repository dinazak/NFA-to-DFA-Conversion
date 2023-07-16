# NFA to DFA Conversion and String Generation

This repository contains code for converting a Non-Deterministic Finite Automaton (NFA) to a Deterministic Finite Automaton (DFA) using the subset construction technique. It also includes functionality to generate a string that passes through all the states of the DFA.

## Problem Description

The problem is to detect all the strings from 0s and 1s such that the 4th symbol from the end is 1.

The notebook contains the following components:

1. `NFA_To_DFA` function: Implements the conversion of an NFA to a DFA using the subset construction technique.
2. `draw_dfa` function: Draws the DFA transition diagram using NetworkX and Matplotlib.
3. String input generation: Generates a string that passes through all the states of the DFA.
