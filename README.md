# Autonomous Intelligent Systems — Companion Code

Runnable Jupyter notebooks accompanying the book *Autonomous Intelligent Systems: From Kalman Filtering to Hybrid AI in Practice* by Jacek Szymonik and Michał Nietopiel.

The notebooks for each chapter are in `chapter_N/source_code/`. Figures produced by the notebooks are written to `chapter_N/figures/`.

## Contents

| Chapter | Topic | Notebooks (`chapter_N/source_code/`) |
|---|---|---|
| 5 | Planning: classical algorithms, reinforcement learning, LLM planners | `state_space`, `dijkstra_algorithm`, `rrt_algorithm`, `reinforcement_learning`, `vehicle_routing`, `uav_mission_planning`, `ambitious_task_ollama_solution` |

## Getting started

Requires Python 3.11 or newer.

```bash
git clone https://github.com/szymonik-jacek/autonomous-intelligent-systems-code.git
cd autonomous-intelligent-systems-code
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

`chapter_5/source_code/ambitious_task_ollama_solution.ipynb` additionally needs a local [Ollama](https://ollama.com) server running at `http://localhost:11434` with the `phi3` model installed (`ollama pull phi3`).

## Note

This repository is generated automatically from the book's manuscript repository. Please report problems through Issues rather than pull requests, since direct changes here are overwritten on the next update.
