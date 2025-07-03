# Yvyrupa Code

Yvyrupa Code is a repository that gathers various implementations of classic algorithms and problems in multiple programming languages, focusing on comparing concurrent and parallel programming interfaces. The goal is to explore the efficiency, efficacy, and effectiveness of the concurrency models and native constructs available in modern languages.

## Objectives

This repository serves as a practical foundation for:

- Empirical study of the expressiveness and overhead of concurrency abstractions.
- Comparisons between models based on threads, channels, processes, and asynchronous tasks.
- Assessment of code readability, actual parallelism, and development effort.
- Investigation of the adoption of OpenMP directives in open-source codebases.

## Contents

The repository is organized by language, including implementations in:

- Rust
- Go
- OpenMP
- GQM: This directory contains the raw data collected by the application of the model developed using the GQM method.

Each implementation addresses a classic problem (e.g., producer/consumer, Fibonacci calculation, Game of Life) to highlight different aspects of the concurrent and parallel programming models supported by each language.

## Citation

If you find this repository useful for your research or teaching, please cite the following references:

```bibtex
@inproceedings{YvyrupaCodeSSCAD2024,
  author    = {Lucas Braatz Araújo, Daniel Di Domenico, André Rauber Du Bois, Gerson Geraldo H. Cavalheiro},
  title     = {Revisitando Clássicos da Concorrência:\Implementação e Avaliação em OpenMP, Rust e Golang},
  booktitle = {Anais do XXVI Simpósio em Sistemas Computacionais de Alto Desempenho},
  location  = {Bonito/MS},
  year      = {2025},
  publisher = {SBC},
  address   = {Porto Alegre, RS, Brasil},
  pages     = {xxx--xxx},
  issn      = {0000-0000},
  doi       = {xxxxx},
  url       = {https://somewhereovertherainbow}
}
```

Outras informações podem ser encontradas em:

```bibtex
@incollection{CursoJAI2025,
  author    = {Gerson Cavalheiro and Alexandro Baldassin and André R. Du Bois},
  title     = {Programação Multithread: Modelos e Abstrações em Linguagens Contemporâneas},
  booktitle = {XLIV Jornadas de Atualização em Informática (JAI 2025)},
  location  = {Maceió/AL},
  year      = {2025},
  publisher = {SBC},
  address   = {Porto Alegre, RS, Brasil},
  pages     = {xxx--xxx},
  issn      = {0000-0000},
  doi       = {xxxxx},
  url       = {https://somewhereovertherainbow}
}
```

## About the name

The name Yvyrupa Code refers to the Guarani concept of Yvyrupa — the world as a shared, borderless land — symbolizing the coexistence of multiple programming languages within a unified analytical and practical space.

##  How to contribute

Contributions are welcome!

If you want to improve this repository — by adding new implementations, fixing issues, or enhancing documentation — please follow these steps:

1. Fork the repository
2. Create a new branch for your contribution:
   ```bash
   git checkout -b your-feature-name
   ```
3. Make your changes and commit them with a meaningful message.
4. Push your branch to your fork:
   ```bash
   git push origin your-feature-name
   ```
5. Open a Pull Request on the main repository, clearly describing your changes and rationale.

When submitting new implementations, please:

- Include a short README or comment header explaining the approach.
- Follow the existing file structure and naming conventions.
- Prefer idiomatic and efficient use of the language's concurrency model.

 For detailed contribution guidelines, see:\
👉 [CONTRIBUTING.md](CONTRIBUTING.md)

Thank you for helping make Yvyrupa Code a better resource for the community!
