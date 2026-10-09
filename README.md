# Artur Istratov · Projects

I build Python applications and work with graph algorithms. These pages describe two of my projects, what works so far, and what I plan to develop next. The source repositories are private.

## Golf Caddy AI

A Python application that suggests golf clubs based on shot conditions and records rounds and practice sessions in SQLite. The current version runs in the terminal and uses fixed rules.

I plan to add recommendations that learn from a player's shot history, a Streamlit interface, and swing feedback from video. Those features are still on the roadmap.

Built with Python and SQLite. Planned additions include XGBoost and MediaPipe Pose.

[Read about Golf Caddy AI](projects/golf-club-recommender.md)

## Comparing program structure with graph edit distance

For my final-year Computer Science project, I investigated whether control-flow graphs could identify obfuscated versions of a Python function. I compared A* and Dijkstra search under uniform and weighted edit costs.

The experiment classified 9 of 11 baseline comparisons correctly. A* explored up to 86.6% fewer search states, though its heuristic sometimes made it slower than Dijkstra. These results come from a small synthetic dataset; the project page explains where the approach failed.

Built with Python, NetworkX, NumPy, SciPy, and Matplotlib.

[Read about the research](projects/cfg-ged-analysis.md)

[GitHub profile](https://github.com/ar2urr)
