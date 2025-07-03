# Contributing to Yvyrupa-Code

Thank you for your interest in contributing to the Yvyrupa-Code project! This repository explores parallel and concurrent programming by implementing classic problems in multiple programming languages with diverse concurrency models. Below are ways you can contribute to the project.

##  Contribution Activities

### 1. Implement in New Languages
- Add idiomatic implementations of the existing problems in new languages such as **Java**, **Elixir**, **Julia**, **Kotlin**, **Erlang**, or **Swift**.
- Prefer native or canonical concurrency features of each language (e.g., actors in Elixir, coroutines in Kotlin).

### 2. Extend Existing Case Studies
- Add alternative implementations using **different concurrency paradigms** in the same language.
- Examples:
  - C++: `std::jthread`, `OpenMP`, `TBB`, `std::async`
  - Rust: `async/.await` with `tokio`, or data-parallelism with `rayon`
  - Go: worker pools, multiple channels
  - Python: `multiprocessing`, `asyncio`, `threading` + `Queue`
- This helps evaluate the trade-offs between different idioms within the same language.

### 3. Automate Detection of Concurrency Features
- Create a **tool or script** that analyzes source code to extract:
  - Concurrency primitives used (e.g., `thread::spawn`, `go`, `Task`, `channel`)
  - Programming model (shared memory, CSP, process-based)
  - Language and abstraction type
- Output should be in JSON, CSV, or Markdown format.

### 4. Benchmark and Automation
- Implement a benchmarking suite to execute implementations with fixed input.
- Collect performance metrics: **execution time**, **CPU**, **memory**.
- Export results in tabular formats (CSV, LaTeX, Markdown).

### 5. Documentation and Multilingual Support
- Help us translate the README and documentation into **English**, **Portuguese**, and **Spanish**.
- Write usage tutorials or Jupyter-style notebooks.

### 6. Concurrency Safety Analysis
- Use static and dynamic analysis tools to detect **data races**, **deadlocks**, or **starvation**.
- Examples:
  - Rust: `Miri`, `cargo clippy`
  - C/C++: `ThreadSanitizer`, `Helgrind`
  - Go: race detector (`go run -race`)

### 7. Formal Modeling and Verification
- Choose one or more problems and formally specify them using:
  - **TLA+**, **Promela/SPIN**, or **Alloy**
- Verify properties like safety (mutual exclusion) and liveness (eventual response).

### 8. Interactive Visualization
- Build a small interactive visualization for the execution behavior:
  - Thread schedules
  - Message passing timelines
  - Lock contention events
- Can be implemented using Python + `streamlit` or JavaScript-based dashboards.

##  Guidelines
- Follow idiomatic code style for each language.
- Keep implementations minimal but clear.
- Always document:
  - The concurrency model used
  - Key primitives or libraries
  - Assumptions or limitations

##  Submitting Contributions
1. Fork the repository.
2. Create a new branch (`feature/my-feature`).
3. Add your changes and commit.
4. Open a Pull Request with a clear description.

Let us know if you need help choosing an issue or getting started. Contributions of all levels are welcome!
