# IBM Quantum Challenge

## Overview
Welcome to the IBM Qiskit Global Summer School 2024! This document provides an overview of the labs you will encounter, focusing on various quantum computing concepts and techniques using Qiskit.

### Lab 0: Introduction to Challenge Notebooks
In this introductory lab, you'll learn how to use the challenge notebooks, grade your work, and manage the overall workflow for setting up, running, and evaluating the results of your quantum code.

- **Prerequisites**: Familiarity with the Python programming language is essential.
- **Structure**: Each lab contains tutorial content, pre-written code blocks, and challenge code blocks that require you to fill in your own Qiskit code.
- **Instructions**: Complete exercises by typing the required code beneath each `## Write your code below here ##` comment. Ensure you run each code cell to keep everything up to date before submission.

---

### Lab 1: Introduction to Qiskit 1.0
This lab introduces you to the new capabilities and functions of Qiskit 1.0. You'll learn how to set up quantum states and implement an optimization algorithm using the Variational Quantum Eigensolver (VQE).

- **Sections**:
  1. Qiskit States: The New and the Old
  2. VQE with Qiskit 1.0

---

### Prologue: What is the Transpiler?
Transpilation is the process of taking a given input circuit and rewriting it to an equivalent circuit suitable for a specific quantum device. This is crucial as different quantum devices may have varying operational protocols.

- **Purpose**: To optimize circuits for execution on real quantum systems while minimizing the effects of noise.
- **Key Aspects**: Transpilation considers a device's basis gate set, chip topology, and timing constraints.

---

### Lab 3: New Features in Qiskit
In this lab, you'll get a sneak peek into exciting new features being developed for the Qiskit stack. This educational challenge is split into separate notebooks, each highlighting unique innovations.

- **Key Innovations**:
  - Circuit Knitting Toolbox: Simplifies complex quantum circuits.
  - Qiskit Serverless: Integrates quantum and classical computing seamlessly.
  - AI-Powered Tools: Includes Qiskit Code Assistant for code generation and optimization with AI-Powered Transpiler Passes.

---

### Lab 4: Testing a Variational Quantum Classifier
In this lab, you'll build and train a simple Variational Quantum Classifier (VQC) on an ideal backend using the Qiskit Patterns workflow.

- **Key Learning Outcomes**:
  - Understand the impact of noise on VQC performance.
  - Learn techniques to reduce VQC depth.
  - Run the resulting circuit on quantum hardware to observe the effects of error suppression and error mitigation techniques.

---

## Getting Started
Let's dive in and explore the fascinating world of quantum computing with Qiskit! Follow the instructions in each
