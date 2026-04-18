# Asterisk

> Monkey interpreters across languages.

---

## ✨ About

**Asterisk** is a collection of **Monkey interpreters** implemented in different programming languages.

Instead of building different languages, this project focuses on implementing the **same language (Monkey)** multiple times to better understand how design decisions change across ecosystems.

The name comes from the symbol `*` (asterisk):

* In automata theory, it represents **zero or more repetitions** (Kleene star)
* It reflects how interpreters repeatedly process tokens, expressions, and evaluation steps
* It symbolizes **iteration, patterns, and scalability** in language design

---

## 🧠 Why Monkey?

Monkey (from Crafting Interpreters) is small but powerful:

* Simple enough to implement from scratch
* Complex enough to cover real interpreter concepts
* Perfect for comparing implementations across languages

---

## 🧩 Features (Monkey Language)

* Variables and bindings (`let`)
* Functions and closures
* Integers and booleans
* Conditionals (`if / else`)
* Return statements
* Basic operators (`+`, `-`, `*`, `/`, `==`, `!=`)

---

## ⚙️ Interpreter Pipeline

```id="o3hzzc"
Source Code → Tokens → AST → Evaluation → Output
```

Each interpreter implements:

1. **Lexer** → Converts source code into tokens
2. **Parser** → Builds the Abstract Syntax Tree (AST)
3. **Evaluator** → Executes the AST
4. **Environment** → Stores variables and scope

---

## 🎯 Goals

* Understand interpreters deeply by repetition (**build it multiple times**)
* Compare language-specific patterns (Go vs Rust vs C#)
* Explore tradeoffs in memory, performance, and design
* Build a strong foundation for compilers and virtual machines

---

## 🧪 Future Plans

* Add bytecode compiler for Monkey
* Build a virtual machine (VM)
* Benchmark implementations across languages
* Extend Monkey with new features

---

## 🤝 Contributing

If you're also learning interpreters, feel free to explore, fork, and experiment.

---

## 🧩 Philosophy

`*` means repetition.

And repetition is how mastery is built.

This project is about writing the same interpreter again and again—
until the concepts become second nature.
