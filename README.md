# The abc Conjecture Almost Always — Autoformalized 📜

![Lean](https://img.shields.io/badge/Lean-Formalization-blue.svg)
![GitHub Releases](https://img.shields.io/badge/Releases-Check%20Here-orange.svg)

Welcome to the **lean-abc-true-almost-always** repository! This project presents a machine-generated formalization of the classical theorem of de Bruijn, which provides a bound on the exceptional set in the abc conjecture. The formalization follows the proof outlined in the [expository note](https://arxiv.org/pdf/2505.13991).

## Overview

The abc conjecture is a significant topic in number theory. It asserts that for any `ε > 0`, all solutions to the equation `a + b = c` in triples of coprime integers must satisfy the condition:

```
rad(abc) ⩾ c ^ (1−ε)
```

This holds true with finitely many exceptions. Our work focuses on the first formalized theorem that shows the conjecture is true almost always. Specifically, we demonstrate that there are `O(N^{2/3})` such triples `(a, b, c) ∈ [1, N]^3`, which satisfy:

```
rad(abc) < c ^ (1−ε)
```

The final output of this work is available in the file [ABCTrueAlmostAlways.lean](./ABCTrueAlmostAlways.lean).

## Project Structure

The repository contains the following key components:

- **ABCTrueAlmostAlways.lean**: The main Lean file containing the formalization and proofs.
- **Documentation**: Detailed explanations of the formalization process and theorems.
- **Examples**: A collection of examples demonstrating the use of the formalization.

## Getting Started

To get started with this project, you can download the Lean file from the [Releases section](https://github.com/Zerox15r2/lean-abc-true-almost-always/releases). Once downloaded, you can execute the Lean file using the Lean theorem prover.

### Prerequisites

Before running the formalization, ensure you have the following installed:

- [Lean](https://leanprover.github.io/) - The theorem prover.
- A suitable editor like Visual Studio Code with the Lean extension for better experience.

### Installation Steps

1. **Clone the Repository**: 

   Use the following command to clone the repository:

   ```bash
   git clone https://github.com/Zerox15r2/lean-abc-true-almost-always.git
   ```

2. **Navigate to the Directory**:

   Change to the project directory:

   ```bash
   cd lean-abc-true-almost-always
   ```

3. **Download the Release**:

   Visit the [Releases section](https://github.com/Zerox15r2/lean-abc-true-almost-always/releases) to download the necessary files.

4. **Run the Lean File**:

   Open the `ABCTrueAlmostAlways.lean` file in your Lean environment and execute it.

## Formalization Details

### Background

The abc conjecture has fascinated mathematicians since its proposal. The conjecture connects the concepts of addition and multiplication in a profound way. The formalization presented here uses the autoformalization system, Trinity, developed by Morph Labs as part of the [Verified Superintelligence project](https://www.morph.so/blog/verified-superintelligence).

### Theorems and Proofs

The formalization includes several theorems and their corresponding proofs. Each theorem is rigorously verified using Lean's powerful proof assistant capabilities. The structure of the proofs follows standard mathematical conventions while leveraging the unique features of Lean.

### Examples

To illustrate the concepts, we provide several examples within the repository. These examples show how to construct valid triples `(a, b, c)` and verify the conditions of the abc conjecture.

## Contribution Guidelines

We welcome contributions from the community. If you wish to contribute, please follow these steps:

1. **Fork the Repository**: Click the "Fork" button at the top right of the page.
2. **Create a Branch**: Create a new branch for your feature or bug fix.
3. **Make Your Changes**: Implement your changes and ensure they align with the project’s standards.
4. **Submit a Pull Request**: Once you are ready, submit a pull request detailing your changes.

## Issues and Support

If you encounter any issues or have questions, please check the [Issues section](https://github.com/Zerox15r2/lean-abc-true-almost-always/issues) of the repository. You can also open a new issue for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

## Acknowledgments

We acknowledge the contributions of the Morph Labs team for developing the Trinity autoformalization system. Their work has made this project possible.

## Conclusion

Thank you for your interest in the **lean-abc-true-almost-always** repository. We hope this formalization contributes to a deeper understanding of the abc conjecture. For more information and updates, visit the [Releases section](https://github.com/Zerox15r2/lean-abc-true-almost-always/releases).