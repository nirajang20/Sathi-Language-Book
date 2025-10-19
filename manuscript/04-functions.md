


# Chapter 4 — Functions & Logic: Building Bonds Through Behavior

> *“A function is not a command — it’s a conversation.”*  
> — **Nirajan Ghimire**

---

## 🌱 Introduction

Every program, at its heart, is a dialogue.  
When we define a function, we’re not giving orders to the machine — we’re teaching it *how to respond*.

In Sathi, functions are written with warmth and intention.  
They represent not hierarchy, but **collaboration**.  
When you write `sathi kam gar`, you’re not saying *“do this.”*  
You’re saying *“let’s do this together.”*

That’s the philosophy behind Sathi’s logic system — where computation is grounded in communication.

---

## 🧩 Understanding Functions in Sathi

A **function** is a reusable block of code that performs a specific task.  
But in Sathi, it’s more than that — it’s an *act of cooperation* between you and your digital friend.

### 🌸 Basic Syntax

```sathi
sathi kam gar joda(a, b)
    sathi farki a + b
sathi sakkyo
```

Call the function:
```sathi
sathi bhanna "Sum: " + str(joda(5, 10))
```

✅ Output:
```
Sum: 15
```

**Meaning:**
- `kam gar` → do work, define behavior  
- `farki` → return the result  
- `sakkyo` → close the conversation (end block)

> 🪶 *“Every function ends not because the work stops, but because understanding is complete.”*

---

## 🪶 The Language of Collaboration

The word *“kam gar”* literally means “do work.”  
It’s something you’d say to a teammate, not a subordinate.  
It embodies **mutual respect** — the essence of Sathi’s conversational tone.

Unlike traditional languages where functions “execute,” Sathi’s functions **participate**.

When we write:

```sathi
sathi kam gar swagat(naam)
    sathi bhanna "Namaste, " + naam + "!"
sathi sakkyo
```

We’re not just instructing — we’re inviting collaboration.

---

## 🧠 Function Parameters: Sharing Understanding

Just like in conversation, Sathi functions can accept *arguments* — pieces of information that shape the discussion.

```sathi
sathi kam gar parichaya(naam, umra)
    sathi bhanna "Namaste, " + naam + "! Tapaiko umra " + str(umra) + " ho."
sathi sakkyo
```

Call it:
```sathi
sathi gara parichaya("Nirajan", 22)
```

✅ Output:
```
Namaste, Nirajan! Tapaiko umra 22 ho.
```

> In everyday Nepali, when we introduce someone, we don’t just say their name — we describe who they are.  
> That same pattern is embedded in Sathi’s logic — clarity through context.

---

## 🧭 Function Calls — `sathi gara`

To call or invoke a function, we use **`sathi gara`**, meaning *“call your friend.”*

```sathi
sathi gara swagat("Sathi")
```

This is more than execution — it’s **connection**.

It reinforces Sathi’s design goal:  
> Code that reads like a conversation, not a command line.

---

## 💫 Returning Values — `sathi farki`

Every function in Sathi can return something meaningful using **`sathi farki`**, meaning *“return back.”*

```sathi
sathi kam gar guna(a, b)
    sathi farki a * b
sathi sakkyo

sathi yo ho result = guna(4, 5)
sathi bhanna "Result: " + str(result)
```

✅ Output:
```
Result: 20
```

Here, `farki` symbolizes reciprocity — giving something back after effort.  
It completes the cycle of friendship between logic and output.

---

## 🧩 Nested Functions — Conversations Within Conversations

Sathi supports nested logic — one function can call another, creating a layered flow.

```sathi
sathi kam gar multiply(a, b)
    sathi farki a * b
sathi sakkyo

sathi kam gar square(num)
    sathi farki multiply(num, num)
sathi sakkyo

sathi bhanna "Square: " + str(square(7))
```

✅ Output:
```
Square: 49
```

This demonstrates that **collaboration breeds creativity.**  
Each function contributes meaning to the larger dialogue.

---

## ⚙️ Logical Expressions and Decisions

Logic in Sathi uses the same conversational approach as its syntax.  
When you combine `sathi bhane` and functions, you create reasoning that feels natural.

```sathi
sathi kam gar check_age(umra)
    sathi yedi umra >= 18 bhane
        sathi farki "Adult"
    sathi natra
        sathi farki "Minor"
    sathi sakkyo
sathi sakkyo

sathi bhanna "You are an " + check_age(20)
```

✅ Output:
```
You are an Adult
```

> In Sathi, decision-making reads like empathy — a friend who listens and responds.

---

## 🧮 Function Composition — Building Meaning Layer by Layer

Sathi encourages combining smaller, meaningful functions into bigger ideas.  
This is called **function composition**, and it mirrors teamwork.

```sathi
sathi kam gar add(a, b)
    sathi farki a + b
sathi sakkyo

sathi kam gar square(x)
    sathi farki x * x
sathi sakkyo

sathi kam gar compute(a, b)
    sathi farki square(add(a, b))
sathi sakkyo

sathi bhanna "Result: " + str(compute(3, 4))
```

✅ Output:
```
Result: 49
```

Here, three functions work together like teammates, each doing their part.

> “Collaboration is not complexity — it’s harmony in logic.”  
> — *Nirajan Ghimire*

---

## 🪄 Advanced Example: Greeting System

Let’s build something more expressive — a small Sathi “friendship bot.”

```sathi
sathi kam gar greet(naam, samay)
    sathi yedi samay == "bihana" bhane
        sathi farki "Subha bihana, " + naam + "!"
    sathi yedi samay == "beluka" bhane
        sathi farki "Subha beluka, " + naam + "!"
    sathi natra
        sathi farki "Namaste, " + naam + "!"
    sathi sakkyo
sathi sakkyo

sathi bhanna greet("Nirajan", "beluka")
```

✅ Output:
```
Subha beluka, Nirajan!
```

Each branch feels alive — expressive, localized, friendly.  
It’s not just functional; it’s *personal*.

---

## 🔁 Recursive Thinking: When Logic Reflects Nature

Recursion — a function calling itself — feels natural in Sathi because repetition is part of Nepali storytelling.

```sathi
sathi kam gar countdown(n)
    sathi yedi n <= 0 bhane
        sathi bhanna "Done!"
    sathi natra
        sathi bhanna str(n)
        sathi gara countdown(n - 1)
    sathi sakkyo
sathi sakkyo

sathi gara countdown(5)
```

Output:
```
5
4
3
2
1
Done!
```

Like the verses of a **Dohori song**, the function repeats until closure — an echo of traditional narrative structure.

---

## 💬 Human Analogy: Teaching by Example

When you teach someone to do something, you don’t just tell them once.  
You explain, demonstrate, and guide until they understand.

That’s how Sathi treats functions.  
Every function is a lesson, every call a practice, every return an acknowledgment.

> “Programming is teaching — and functions are your students.”  
> — *Nirajan Ghimire*

---

## 🧭 Error Handling in Logic

Even friends misunderstand sometimes.  
In future versions, Sathi will support **error dialogue**, allowing you to handle mistakes gracefully.

Example concept (planned feature):

```sathi
sathi kosis gar
    sathi bhanna 5 / 0
sathi samasya bhaye
    sathi bhanna "Error ayo, tara Sathi samjhana garchha."
sathi sakkyo
```

> *“Error handling is empathy in code.”*

---

## 🪶 Summary

Functions in Sathi aren’t cold abstractions — they’re **relationships**.  
Each one carries the warmth of communication and the clarity of cooperation.

When you define a function in Sathi, you’re not just writing logic —  
you’re **building trust** between human and machine.

> “A friend helps you do the work — that’s why we call it ‘sathi kam gar.’”  
> — *Nirajan Ghimire*