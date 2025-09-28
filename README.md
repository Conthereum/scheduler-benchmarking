# Scheduler Benchmarking

This repository contains implementations of multiple scheduling algorithms for blockchain transaction processing. The goal is to provide a comprehensive comparison of different approaches and demonstrate how the **Greedy Algorithm** outperforms the rest in terms of efficiency and scalability.

## Repositories

The following repositories are included for benchmarking purposes:

1. **[scheduler-genetic-algorithm](https://github.com/Conthereum/scheduler-genetic-algorithm)**: A genetic algorithm-based scheduler for transaction processing.
2. **[scheduler-greedy](https://github.com/Conthereum/scheduler-greedy)**: The best-performing greedy algorithm scheduler for blockchain transaction scheduling.
3. **[scheduler-job-shop-benchmark](https://github.com/Conthereum/scheduler-job-shop-benchmark)**: A benchmarking environment for job-shop scheduling problems applied to blockchain transactions.
4. **[scheduler-optaplanner](https://github.com/Conthereum/scheduler-optaplanner)**: An implementation using OptaPlanner for job-shop scheduling of blockchain transactions.
5. **[scheduler-ortools](https://github.com/Conthereum/scheduler-ortools)**: A scheduling solution based on Google OR-Tools for blockchain transaction optimization.

## Benchmark Results

The **Greedy Algorithm** is shown to consistently outperform the other approaches. For detailed performance analysis and comparisons, please refer to the the papers.

### Papers:

```bibtex
@inproceedings{Conthereum_Zareh_2025,
  author = {Zareh Chahoki, Atefeh and Herlihy, Maurice and Roveri, Marco},
  title = {Conthereum: Concurrent Ethereum Optimized Transaction Scheduling for Multi-Core Execution},
  booktitle={2025 7th Conference on Blockchain Research & Applications for Innovative Networks and Services (BRAINS)}, 
  year = {2025},
  address = {Zurich, Switzerland},
  url = {-},
  doi = {-},
  numpages = {10},
  location = {Zurich, Switzerland},
}
@article{Survey_Zareh_2025,
  author = {Atefeh Zareh Chahoki, Maurice Herlihy, Marco Roveri},
  title = {SoK: Concurrency in Blockchain, A Systematic Literature Review and Unveiling a Misconception},
  journal={arXiv preprint arXiv:2506.01885},
  year={2025}
}
```
