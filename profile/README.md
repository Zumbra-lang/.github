<p align="center">
  <img src="./assets/logo.png" width="200" alt="logo">
</p>
# ZUMBRA Programming Language

> ⚙️ *ZUMBRA is a simple, fun, and expressive programming language made for learning, experimenting, and enjoying the beauty of code.*

---

## ✨ What is ZUMBRA?

ZUMBRA is a custom programming language built with its own parser, compiler, and virtual machine. It supports function definitions, scoped variables, custom operators, and more — all with a minimalist syntax and a playful soul.

Not your typical cup of J..., try a shot of ZUMBRA.

---

## 📦 Features

- 🧠 **User-defined functions** with `fct`
- 📦 **Global and local variables** with `var`
- 🧮 Arithmetic and logical operations: `+ - * / % = <= >=`
- 🔁 Conditional logic: `if`, `else`, `return`
- 🔧 Custom assignment operator: `<<`
- 📚 Built-in functions:
  - `sizeOf`
  - `addToArray`
  - `removeFromArray`
  - `first`, `last`, `allButFirst`
  - `show`
  - `input`
- 🧠 **Don't forget the ";"**

---

## 🛠 Code examples

```zumbra
show("Whats your name ?");
var name << input();

show("My name is " + name);
```

```zumbra
var sum << fct(a, b){
    return a + b;
};

var sub << fct(a,b){
    return a - b;
};

show(sum(1, 2));
show(sub(2, 5));
```

---

## 📥 How to Run

You can execute `.zum` code using the compiled ZUMBRA binary on different platforms.

### **Windows** 🖥️

1. Download the `zumbra.exe` file for Windows from the [GitHub Release](https://github.com/Zumbra-lang/Zumbra-lang/releases/download/v0.0.1/zumbra-release-win.zip).
2. Open a command prompt or PowerShell window and run the following command:

   ```bash
   zumbra.exe myscript.zum
   ```

### **Linux** 🐧

1. Download the `zumbra-linux` file for Linux from the [GitHub Release](https://github.com/Zumbra-lang/Zumbra-lang/releases/download/linuxv0.0.1/zumbra-linux).
2. Make the file executable by running:

   ```bash
   chmod +x zumbra-linux
   ```

3. Run the script with the following command in your terminal:

   ```bash
   ./zumbra-linux myscript.zum
   ```

---

### ⚡ Additional Notes:
- Make sure the ZUMBRA binary file (`zumbra-linux`, `zumbra.exe`) has execution permissions on your system.
- For **Windows**, just run the command without additional configuration.
- For **Linux**, use the `chmod` command to make the file executable.

---

## Meet the Mascot

ZUMBRA is proudly represented by its friendly mascot: **Zumbrita**, the coding gambazin!

<p align="center">
    <img src="./assets/mascot.png" width="200" alt="Zumbrita">
</p>

Feel free to include Zumbrita in your projects or documentation! He loves code and caffeine ☕.

---

## 💻 Developing ZUMBRA

ZUMBRA is written in Go and includes a custom-built:

- Lexer
- Parser (Pratt-style)
- Bytecode Compiler
- Virtual Machine (Stack-based)

### Compile it:

```bash
go build -o zumbra
```

---

## 📎 VS Code Integration

We provide a [ZUMBRA VS Code Extension](https://marketplace.visualstudio.com/items/?itemName=joselucasapp.zum-lang-support) for syntax highlighting and `.zum` file support.

> Includes keyword coloring, strings, and built-in function recognition.

---

## 📄 License

MIT License. See `LICENSE` for details.

---

### 👨‍💻 Creator

---

## Joselucasapp
Bringing ZUMBRA to life with love, logic, and a hint of rebellion.
