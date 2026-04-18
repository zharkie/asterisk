<p align="center">
  <img src="assets/logo.svg" alt="Asterisk Logo" width="120"/>
</p>

<h1 align="center">Asterisk</h1>

<p align="center">
  <em>Monkey interpreters across languages</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/language-Monkey-22c55e?style=for-the-badge" />
  <img src="https://img.shields.io/badge/focus-Interpreters-16a34a?style=for-the-badge" />
  <img src="https://img.shields.io/badge/status-In%20Progress-4ade80?style=for-the-badge" />
</p>

---

## ✨ About

**Asterisk** is a collection of **Monkey interpreters** built across multiple programming languages.

Rather than creating different languages, this project focuses on implementing the **same language repeatedly** to gain a deeper understanding of how interpreters work and how design decisions vary across ecosystems.

The name **Asterisk (`*`)** is intentional:

* In automata theory, it represents **zero or more repetitions** (Kleene star)
* It mirrors how interpreters repeatedly process tokens and expressions
* It reflects the idea of mastering concepts through repetition

---

## 🧠 Why Monkey?

Monkey (from Crafting Interpreters) is a minimal but expressive language:

* Small enough to build from scratch
* Rich enough to cover real interpreter concepts
* Ideal for comparing implementations across languages

---

## 🧩 Language Features

The Monkey language includes:

* Variable bindings (`let`)
* Functions and closures
* Integers and booleans
* Conditional expressions (`if / else`)
* Return statements
* Basic operators (`+`, `-`, `*`, `/`, `==`, `!=`)

---

## ⚙️ Interpreter Pipeline

```
Source Code → Tokens → AST → Evaluation → Output
```

Each implementation follows the same core pipeline:

1. **Lexer** → Converts source code into tokens
2. **Parser** → Builds the Abstract Syntax Tree (AST)
3. **Evaluator** → Walks the AST and executes it
4. **Environment** → Stores variables and manages scope

---

## 🎯 Goals

* Build interpreters from scratch multiple times (**learn by repetition**)
* Compare implementation patterns across languages
* Understand parsing, evaluation, and runtime behavior deeply
* Build a strong foundation for compilers and virtual machines

---

## 🧪 Future Plans

* Add a bytecode compiler for Monkey
* Build a virtual machine (VM)
* Benchmark implementations across languages
* Extend the language with new features

---

## 🤝 Contributing

Contributions, experiments, and discussions are welcome.
If you're learning interpreters too, feel free to explore and build alongside this project.

---

## 🧩 Philosophy

`*` means repetition.

And repetition leads to mastery.

This project is about writing the same interpreter again and again—
until the abstractions become intuition.
