


# Appendix — Reference, FAQs, and Acknowledgments

> *“Every story ends with gratitude — every language with understanding.”*  
> — **Nirajan Ghimire**

---

## 📘 A. Full Syntax Reference (v1.0)

The following table lists all core Sathi keywords, their meanings, and equivalent Python behavior.

| Sathi Keyword | Meaning (English) | Equivalent (Python) | Example |
|----------------|------------------|---------------------|----------|
| `sathi yo ho` | Declare variable | `=` | `sathi yo ho naam = "Nirajan"` |
| `sathi bhanna` | Print / Say | `print()` | `sathi bhanna "Namaste, Sansar!"` |
| `sathi bhanna sangai` | Print on same line | `print(..., end="")` | `sathi bhanna sangai "Hello"` |
| `sathi bhanna naya` | Print with newline | `print("\\n")` | `sathi bhanna naya "Hi"` |
| `sathi leu` | Take input | `input()` | `sathi leu naam "Tapaiko naam k ho?"` |
| `sathi yedi` | If condition | `if` | `sathi yedi x > y bhane` |
| `sathi bhane` | Then clause | `:` | `sathi yedi x > y bhane` |
| `sathi natra` | Else clause | `else` | `sathi natra` |
| `sathi dohoryau` | Repeat loop | `while/for` | `sathi dohoryau 5 choti` |
| `sathi sakkyo` | End / Close block | `end` | `sathi sakkyo` |
| `sathi kam gar` | Define function | `def` | `sathi kam gar joda(a, b)` |
| `sathi gara` | Call function | Function call | `sathi gara greet("Nirajan")` |
| `sathi farki` | Return value | `return` | `sathi farki a + b` |
| `sathi laga` | Import file | `import` | `sathi laga "math.sathi"` |
| `sathi soch` | Think / Imagine | (Future feature: AI intent) | `sathi soch "Banau ek calculator"` |
| `sathi kosis gar` | Try block | `try:` | `sathi kosis gar` |
| `sathi samasya bhaye` | Handle error | `except:` | `sathi samasya bhaye` |

---

## 🧠 B. Data Types Overview

Sathi supports data types similar to Python, expressed in cultural form.

| Type | Example | Description |
|------|----------|-------------|
| Number | `5`, `3.14` | Integer or floating number |
| String | `"Namaste"` | Sequence of characters |
| Boolean | `sahi`, `galat` | True / False |
| List | `[1, 2, 3]` | Ordered collection |
| Dictionary | `{naam: "Nirajan"}` | Key-value pairs |

---

## 🔣 C. Mathematical Keywords

| Keyword | Meaning | Python Equivalent |
|----------|----------|-------------------|
| `joda` | Add | `+` |
| `ghatau` | Subtract | `-` |
| `guna` | Multiply | `*` |
| `bhaag` | Divide | `/` |

Example:
```sathi
sathi yo ho result = joda(5, 3)
sathi bhanna "Result: " + str(result)
```

---

## ⚙️ D. Installation FAQ

### 1️⃣ How do I install Sathi?
Run:
```bash
pip install sathi-lang
```
Then test:
```bash
sathi --version
```

---

### 2️⃣ How do I run a `.sathi` program?
Use:
```bash
sathi filename.sathi
```
or, directly via Python:
```bash
python3 sathi.py filename.sathi
```

---

### 3️⃣ My `sathi` command isn’t found!
Make sure your Python `Scripts` or `bin` folder is in the system PATH.  
Alternatively, run Sathi manually from the cloned folder.

---

### 4️⃣ Does Sathi work on macOS, Linux, and Windows?
Yes! It’s built entirely in Python, making it compatible across all platforms.

---

### 5️⃣ How can I contribute?
Join the community on GitHub:
> [https://github.com/nirajang20/Sathi-Language](https://github.com/nirajang20/Sathi-Language)

You can submit pull requests, add examples, improve docs, or create your own `.sathi` projects.

---

## 💻 E. Contribution Guide

Sathi thrives on collaboration.  
Follow these simple steps to join the movement:

1. **Fork the repository**
   ```bash
   git clone https://github.com/nirajang20/Sathi-Language.git
   ```
2. **Create a new branch**
   ```bash
   git checkout -b feature-yourname
   ```
3. **Commit your changes**
   ```bash
   git commit -m "Added new feature/example"
   ```
4. **Push and open a Pull Request**
   ```bash
   git push origin feature-yourname
   ```

### 💬 Contribution Principles
- Respect all contributors.
- Document clearly — make learning easier.
- Celebrate creativity — every idea matters.
- Code with culture.

> “Open source is not just about sharing code — it’s about sharing kindness.”  
> — *Nirajan Ghimire*

---

## 🌏 F. Learning Path: From Beginner to Creator

Sathi is designed to grow with you.

| Level | Focus | Practice Idea |
|--------|--------|----------------|
| 🌱 Beginner | Syntax, printing, and loops | Create your first Sathi calculator |
| 🧠 Intermediate | Functions & conditions | Build a Sathi quiz app |
| 💡 Advanced | Interpreter understanding | Contribute to Sathi core on GitHub |
| 🚀 Creator | AI + Web IDE | Build your own cultural coding module |

---

## 🧩 G. Common Errors & Solutions

| Error | Cause | Solution |
|--------|--------|----------|
| `Sathi samjhana sakena` | Syntax error | Check missing `sathi sakkyo` |
| `Variable not found` | Typo in variable name | Verify correct spelling |
| `Input Error` | Missing quotes | Always wrap text in `"` |
| `Import Error` | File not found | Use relative path or same folder |

> “Don’t fear errors — they are messages from your digital friend.”  
> — *Nirajan Ghimire*

---

## 📚 H. Example File Structure

```
Sathi-Language/
├── sathi.py
├── /examples/
│   ├── hello.sathi
│   ├── calculator.sathi
│   └── story.sathi
├── /docs/
│   ├── syntax-list.md
│   └── usage.md
└── /vscode-extension/
    ├── package.json
    ├── snippets/sathi.json
    └── syntaxes/sathi.tmLanguage.json
```

---

## 💞 I. Acknowledgments

Sathi is not just a personal project — it’s a community dream.  
Special thanks to every friend, mentor, and curious learner who helped shape its journey.

### 🙏 Special Mentions
- **Open Source Community** — for teaching collaboration.  
- **SDSU Faculty & Peers** — for encouraging innovation.  
- **Nepalese Student Association at SDSU** — for cultural inspiration.  
- **Every Sathi User** — for proving that language and logic can coexist.

> “Without you, Sathi would just be syntax. With you, it became a story.”

---

## ✍️ J. Epilogue: The Journey Beyond Code

As this book closes, remember — Sathi isn’t only a language you code in.  
It’s a reflection of how we express, understand, and connect through technology.

When you type:
```sathi
sathi bhanna "Sathi!"
```
You’re not commanding a machine.  
You’re **greeting a friend** — one that listens, learns, and grows with you.

> “Every line of code is a sentence in the story of human progress.  
> Sathi simply makes that story easier to tell.”  
> — *Nirajan Ghimire*

---

**Website:** [https://nirajang.com.np/sathi](https://nirajang.com.np/sathi)  
**GitHub:** [https://github.com/nirajang20/Sathi-Language](https://github.com/nirajang20/Sathi-Language)  
**Author:** *Nirajan Ghimire*  
**Tagline:** *Code with culture — build with Sathi.*