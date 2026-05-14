# Artificial Intelligence Lecture Summary

Comprehensive LaTeX-based lecture summary for a university-level
Artificial Intelligence course covering intelligent agents,
search algorithms, heuristics, optimization, adversarial search,
and core AI methodologies.

The project focuses on structured technical documentation,
problem-solving strategies, rational agents, informed search,
and modern artificial intelligence concepts.

---

## Topics Covered

- Introduction to Artificial Intelligence
- Turing Test & Chinese Room Argument
- Rational Agents
- AI Environments
- Agent Architectures
- Reflex & Model-Based Agents
- Goal-Based & Utility-Based Agents
- Learning Agents
- Search Problems
- State Space Representation
- Tree Search Algorithms
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Uniform-Cost Search (UCS)
- Iterative Deepening Search (IDS)
- Heuristics
- Greedy Best-First Search
- A* Search
- Admissible & Consistent Heuristics
- Graph Search
- Optimization Problems
- Local Search Algorithms
- Hill Climbing
- Beam Search
- Simulated Annealing
- Adversarial Search
- Minimax Algorithm
- Alpha-Beta Pruning
- Constraint Satisfaction Problems (CSPs)

---

## Build Instructions

Requirements:
- A LaTeX installation (e.g. MikTeX or TeX Live)
- Installation of the [TU Template](https://github.com/tudace/tuda_latex_templates) and the required plugins
- Installation of Pygments (for code blocks), e.g. via `pip install Pygments`

First, the folder structure must of course be downloaded, for example using `git clone`.  
Afterwards, the summary/document must be compiled with the `--shell-escape` flag.  

If you are using VS Code with LaTeX Workshop, you can modify the `settings.json` by appending the following:

```jsonc
"latex-workshop.latex.tools": [
    {
        "name": "latexmk",
        "command": "latexmk",
        "args": [
            "--shell-escape",
            "-synctex=1",
            "-interaction=nonstopmode",
            "-file-line-error",
            "-lualatex", // alternatively: "-pdf", etc.
            "-outdir=%OUTDIR%",
            "%DOC%"
        ]
    },
],
```

---

## Goals of the Project

- Create a structured and maintainable AI reference
- Summarize classical artificial intelligence concepts
- Document search and optimization algorithms
- Explain heuristics and rational decision-making
- Improve technical documentation and LaTeX workflow skills

---

## Disclaimer

This document was independently written for educational purposes.
It is intended as a personal lecture summary and study reference.

Some topics may be based on university lecture material and publicly
known artificial intelligence concepts. All rights to original course
content remain with their respective owners.

---

## License

This repository is licensed under the MIT License.
