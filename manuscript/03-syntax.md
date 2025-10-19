


# Chapter 3 — Syntax & Semantics: The Language of Friendship

> *“The closer code feels to conversation, the more powerful it becomes.”*  
> — **Nirajan Ghimire**

---

## 🧠 Introduction

Every programming language has syntax — but not every language has *soul*.  
Sathi’s syntax is designed not only for machines to understand but for *humans to feel*.  
It merges Nepali linguistic rhythm with computational logic, creating an experience where code reads like storytelling.

When I first wrote the keywords `sathi yo ho`, it felt like saying *“this is something”* rather than *“declare variable.”*  
That emotional connection — the ability to express logic in familiar words — is what defines Sathi’s syntax.

---

## 🌱 Design Philosophy

Sathi is built around **three principles of friendly syntax**:

1. **Clarity through familiarity** — It should sound natural and intuitive.  
2. **Emotion in expression** — Words carry tone and empathy.  
3. **Cultural grounding** — Each keyword holds meaning drawn from Nepali communication patterns.

By combining cultural linguistics with structured computation, Sathi transforms code into a readable dialogue.

---

## 🪶 Core Syntax Elements

### 1️⃣ Variables — `sathi yo ho`

In Sathi, declaring a variable feels like *introducing* something rather than assigning memory.

```sathi
sathi yo ho naam = "Nirajan"
sathi yo ho umra = 22
sathi bhanna "Mero naam " + naam + " ho, umra " + str(umra)
```

✅ Output:
```
Mero naam Nirajan ho, umra 22
```

**Meaning:**  
- `sathi` → the friend who executes  
- `yo ho` → “this is” or “it is”  
Together they express ownership and identity — *this is my variable.*

> 💬 Linguistic note: The phrase “yo ho” is uniquely Nepali, often used to introduce someone or something warmly.

---

### 2️⃣ Printing & Output — `sathi bhanna`

To express or print output, Sathi uses `bhanna`, which means *“say”* or *“speak.”*

```sathi
sathi bhanna "Hello, Sathi!"
```

Output:
```
Hello, Sathi!
```

#### 💡 Variants:
- `sathi bhanna` — prints to console.  
- `sathi bhanna naya` — prints with a new line (like `print()` in Python).  
- `sathi bhanna sangai` — prints on the same line (like `print(..., end="")`).

```sathi
sathi bhanna "Mero naam "
sathi bhanna sangai "Nirajan ho."
```

Output:
```
Mero naam Nirajan ho.
```

> 🪶 Philosophy: When we tell computers to “say,” we transform them from silent machines into conversational companions.

---

### 3️⃣ Conditional Logic — `sathi bhane` / `sathi natra`

Conditionals in Sathi are more than logical structures — they are expressions of understanding.

```sathi
sathi yo ho umra = 20

sathi yedi umra >= 18 bhane
    sathi bhanna "Tapaai adult hunuhunchha."
sathi natra
    sathi bhanna "Tapaai teen hunuhunchha."
sathi sakkyo
```

Output:
```
Tapaai adult hunuhunchha.
```

**Keywords:**
| Sathi Keyword | Meaning | Equivalent |
|----------------|----------|-------------|
| `yedi` | if | if |
| `bhane` | then | : (colon in Python) |
| `natra` | else | else |
| `sakkyo` | end block | end, closes logic |

> 💬 In Nepali dialogue, *bhane* connects a condition to a conclusion — it’s the natural “if… then…” structure of conversation.

---

### 4️⃣ Loops — `sathi dohoryau`

Sathi’s loop syntax comes from the Nepali word **“Dohori”**, meaning *repetition in a musical dialogue.*  
Each repetition is not just mechanical — it’s rhythmic, intentional, poetic.

#### 🔁 Repeat by count:
```sathi
sathi dohoryau 3 choti
    sathi bhanna "Yo code teen patak chalchha."
sathi sakkyo
```

Output:
```
Yo code teen patak chalchha.
Yo code teen patak chalchha.
Yo code teen patak chalchha.
```

#### 🔁 Repeat with condition:
```sathi
sathi yo ho x = 0

sathi dohoryau jaba x < 5
    sathi bhanna "x ko maan: " + str(x)
    x = x + 1
sathi sakkyo
```

Output:
```
x ko maan: 0
x ko maan: 1
x ko maan: 2
x ko maan: 3
x ko maan: 4
```

> 🧭 Every loop in Sathi mirrors the rhythm of folk exchange — dialogue through iteration.

---

### 5️⃣ Functions — `sathi kam gar` / `sathi farki`

Functions in Sathi are written as **friendly instructions**, not abstract declarations.  
They represent *collaboration*, not command.

```sathi
sathi kam gar joda(a, b)
    sathi farki a + b
sathi sakkyo

sathi bhanna "Sum: " + str(joda(10, 15))
```

Output:
```
Sum: 25
```

**Explanation:**
| Keyword | Meaning | English Equivalent |
|----------|----------|--------------------|
| `kam gar` | do work | define function |
| `farki` | return | return value |
| `sakkyo` | finished | end block |

> 💬 The tone of “kam gar” — “do work” — reflects humility.  
> It’s a phrase used in collaboration, not authority. Sathi treats functions as shared effort, not orders.

---

### 6️⃣ Comments — `#`

Sathi uses the same symbol as Python for comments.

```sathi
# Yo comment ho — computer le ignore garchha
sathi bhanna "Sathi!"
```

Output:
```
Sathi!
```

Comments are where humans talk to other humans inside code — a reflection of Sathi’s friendship philosophy.

---

### 7️⃣ Input — `sathi leu`

To take user input:

```sathi
sathi leu naam "Tapaiko naam k ho? "
sathi bhanna "Namaste, " + naam
```

Output:
```
Tapaiko naam k ho? Nirajan
Namaste, Nirajan
```

| Keyword | Meaning |
|----------|----------|
| `leu` | take (input) |
| `bhanna` | say (output) |

> 🪶 Together, they create a dialogue loop — human asks, machine responds.

---

### 8️⃣ Imports — `sathi laga`

For modularity and reusability, Sathi supports imports:

```sathi
sathi laga "math.sathi"
```

This is equivalent to `import math` in Python.

The word *laga* means *“bring”* or *“attach”* — symbolizing connection and inclusion.

---

## 🧩 Syntax Overview Table

| Concept | Keyword | Meaning | Example |
|----------|----------|----------|----------|
| Variable | `sathi yo ho` | declare variable | `sathi yo ho naam = "Sathi"` |
| Print | `sathi bhanna` | display text | `sathi bhanna "Hello"` |
| Input | `sathi leu` | take input | `sathi leu naam "What is your name?"` |
| If | `sathi bhane` | conditional branch | `sathi yedi x > y bhane ...` |
| Else | `sathi natra` | alternative branch | `sathi natra ...` |
| Loop | `sathi dohoryau` | repeat block | `sathi dohoryau 5 choti ...` |
| Function | `sathi kam gar` | define function | `sathi kam gar add(a,b)` |
| Return | `sathi farki` | return value | `sathi farki a + b` |
| End block | `sathi sakkyo` | end statement | `sathi sakkyo` |
| Import | `sathi laga` | include file | `sathi laga "math.sathi"` |

---

## 🔤 Data Types in Sathi

Sathi mirrors Python’s simplicity in handling data types:

| Type | Example | Description |
|------|----------|--------------|
| Number | `5`, `3.14` | Integer or float |
| String | `"Hello"` | Text data |
| Boolean | `sahi`, `galat` | true / false |
| List | `[1, 2, 3]` | Ordered collection |
| Dictionary | `{naam: "Sathi"}` | Key-value pairs |

> 🧠 The words *sahi* and *galat* literally mean *right* and *wrong* — a poetic reflection of boolean truth.

---

## 🪞 Semantics: The Heart of Understanding

Semantics define *how* Sathi interprets meaning.  
When you write `sathi bhanna`, the interpreter translates not just a command — it translates *intent*.

The Sathi interpreter tokenizes each word, understands context, and executes Python-equivalent logic, while preserving the friendliness of the syntax.  

> 🧩 Example Mapping:
> - `sathi bhanna` → `print()`
> - `sathi yo ho` → variable declaration
> - `sathi kam gar` → `def`
> - `sathi sakkyo` → block closure

Behind every execution is a **translation layer** that listens — not just parses.

---

## 🌸 The Beauty of Expression

What makes Sathi special isn’t its simplicity — it’s its **expressiveness**.  
You can *feel* the warmth in each line. You can *see* the culture embedded in logic.

```sathi
sathi yo ho mitra = "Sathi"
sathi bhanna "Tapai ko code, tapai ko mitra!"
```

Output:
```
Tapai ko code, tapai ko mitra!
```

> “In Sathi, code doesn’t just run — it relates.”  
> — *Nirajan Ghimire*

---

## 🪶 Summary

The syntax of Sathi is more than just a set of rules.  
It’s a cultural framework — a bridge between people and programs.  
By combining linguistic familiarity with logical precision, it transforms coding into communication.

When you code in Sathi, you’re not just telling a machine what to do —  
you’re teaching it *how to understand you.*

> “Syntax is structure. Semantics is soul. Together, they form friendship.”  
> — *Nirajan Ghimire*