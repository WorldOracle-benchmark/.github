# WorldOracle

**Benchmarking Action-Conditioned World Models against Real-World Executions**

[Website](https://worldoracle-benchmark.github.io/) · [Paper](https://arxiv.org/abs/2610.18826) · [Code](https://github.com/WorldOracle-benchmark/WorldOracle) · [Datasets](https://huggingface.co/WorldOracle) · [Leaderboard](https://worldoracle-benchmark.github.io/leaderboard.html)

WorldOracle evaluates whether action-conditioned world models predict what happens in the real world. Given the same initial observation and low-level action trajectory, it compares predicted rollouts with paired real-world executions, including physical outcomes and task-state transitions.

## What we evaluate

- **Across embodiments:** AgiBot G2, YAM, and human-hand interactions, including both successful and failed executions.
- **Across action distributions and time horizons:** Human-operated and policy-rollout trajectories, with long, multi-segment episodes and synchronized multi-view observations.
- **Across four complementary dimensions:** Physical State Correctness, Interaction Spatial Alignment, Key Interaction Area Fidelity, and Multi-View Action Coherence.

## Get involved

Explore the [datasets](https://huggingface.co/WorldOracle), evaluate your model with the [evaluation code](https://github.com/WorldOracle-benchmark/WorldOracle), and visit the [leaderboard](https://worldoracle-benchmark.github.io/leaderboard.html) for results and submission instructions.

Questions, feedback, and contributions are welcome through [GitHub Issues](https://github.com/WorldOracle-benchmark/WorldOracle/issues).
