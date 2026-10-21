# 🌀 Quelang (The Kadeksan Programming Language)

<div align="center">
  <img width="250" height="250" alt="Quelang Logo" src="https://github.com/user-attachments/assets/a0122457-87a4-487c-afa3-495d1c2eb05c" />
</div>

**Quelang** is a lightweight, interpreted programming language created by Czar Pedro. It was designed to be simple, fun, and highly extensible, featuring native mathematical functions and a unique syntax inspired by the Kadeksan empire.

## ✨ Features
- **Native Fibonacci:** You don't need loops to calculate Fibonacci. Just type `fib(5)` or `fib(1..5)`.
- **Clean Syntax:** Uses `put()` for printing and `fn main()` for the main function.
- **Variables:** Use `var` for mutable variables and `con` for constants.
- **Extensible:** Easy to add new built-in functions.

## 🚀 Hello, World!

```quelang
fn main() {
    put("Hello, World!\n")
}
```

## 🧮 Fibonacci Magic
Quelang has Fibonacci built directly into the core:

```quelang
fn main() {
    put("The 6th number is: " + fib(6) + "\n")
    put("Sequence from 1 to 5: " + fib(1..5) + "\n")
}
```

## 📦 Variables & Math
```quelang
fn main() {
    var x = 10
    con pi = 3.14
    var sum = x + 5
    
    put("X + 5 = " + sum + "\n")
    put("Pi = " + pi + "\n")
}
```

## 💻 How to run it
Currently, Quelang can be run directly in your browser using our Official Web Playground: 
👉 **[Click here to open the Quelang Playground](https://czarofkadeksan.github.io/Quelang-compiler/)**

## 👑 Author
Created by **NeuroSpice (Czar Pedro)**.
