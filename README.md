# LLM-inference-time-scaling
This notebook explores different inference scaling techniques for large language models (LLMs) and evaluates their performance on the Math Benchmark dataset. The main goal is to explore how these techniques impact the accuracy and efficiency of LLMs in solving mathematical problems.

Core parts of the notebook:

*   **VLLM Setup:** Setting up a local LLM server using VLLM for accelerated inference.
*   **Helper Functions:** Implementing functions for dataset loading, answer extraction, normalization, and evaluation.
*   **Chain-of-Thought (CoT):** Evaluating the performance of the CoT prompting technique.
*   **Best-of-N Sampling:** Implementing and evaluating the Best-of-N sampling method with both log-probability and LLM-based verification.
*   **Beam Search:** Implementing and evaluating the Beam Search algorithm for exploring reasoning paths.
*   **Self-Refinement:** Implementing and evaluating an iterative self-refinement approach.
*   **Advanced Search Algorithms (Planned):** Outlining the implementation of A*, Monte Carlo Tree Search (MCTS), and Tree of Thoughts (ToT) for future exploration.
