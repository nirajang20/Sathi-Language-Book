


# Chapter 6 — Building Projects with Sathi: From Ideas to Friendship

> *“Code becomes meaningful when it solves, teaches, and connects.”*  
> — **Nirajan Ghimire**

---

## 🌱 Introduction

Up to this point, we’ve explored how Sathi understands — from its friendly syntax to its empathetic interpreter.  
Now it’s time to **build**.  

This chapter isn’t just about writing code — it’s about **bringing ideas to life through simplicity and culture**.  
Each project you’ll see here is designed to demonstrate both the technical power of Sathi and the emotional warmth that defines its philosophy.

Programming, at its heart, is creative expression.  
And Sathi gives you the tools to express — clearly, beautifully, and humanly.

---

## 🧮 Project 1: The Friendly Calculator

> *“Every friendship starts with sharing — and numbers are where sharing begins.”*

Let’s build a small calculator that performs addition, subtraction, multiplication, and division — but in Sathi’s way: conversational and simple.

```sathi
sathi bhanna "👋 Namaste! Ma Sathi Calculator hu."
sathi bhanna "Let's calculate together."

sathi leu x "Enter first number: "
sathi leu y "Enter second number: "
sathi leu kriya "Choose operation (joda/ghatau/guna/bhaag): "

sathi yedi kriya == "joda" bhane
    sathi bhanna "Result: " + str(float(x) + float(y))
sathi yedi kriya == "ghatau" bhane
    sathi bhanna "Result: " + str(float(x) - float(y))
sathi yedi kriya == "guna" bhane
    sathi bhanna "Result: " + str(float(x) * float(y))
sathi yedi kriya == "bhaag" bhane
    sathi bhanna "Result: " + str(float(x) / float(y))
sathi natra
    sathi bhanna "Unknown operation."
sathi sakkyo
```

✅ Example Output:
```
👋 Namaste! Ma Sathi Calculator hu.
Let's calculate together.
Enter first number: 8
Enter second number: 2
Choose operation (joda/ghatau/guna/bhaag): guna
Result: 16.0
```

### 🧭 What it teaches:
- Input and output handling (`sathi leu`, `sathi bhanna`)
- Conditional logic with multiple branches
- User interaction with natural Nepali-inspired flow

---

## 💬 Project 2: Greeting Bot — “Namaste Sathi!”

This bot greets users based on the time of day and remembers their name.

```sathi
sathi bhanna "Namaste! Ma Sathi Bot hu."
sathi leu naam "Tapaiko naam k ho? "
sathi leu samay "Samay enter garnuhos (bihana/dina/beluka): "

sathi yedi samay == "bihana" bhane
    sathi bhanna "Subha bihana, " + naam + "!"
sathi yedi samay == "dina" bhane
    sathi bhanna "Subha din, " + naam + "!"
sathi yedi samay == "beluka" bhane
    sathi bhanna "Subha beluka, " + naam + "!"
sathi natra
    sathi bhanna "Namaste, " + naam + "!"
sathi sakkyo
```

✅ Example Output:
```
Namaste! Ma Sathi Bot hu.
Tapaiko naam k ho? Nirajan
Samay enter garnuhos (bihana/dina/beluka): beluka
Subha beluka, Nirajan!
```

> 💬 *“Greeting someone is the simplest form of kindness — and now, your computer can join in.”*

---

## 📖 Project 3: Storytelling with Sathi

> *“Stories connect code to culture. Each variable becomes a character, each loop a rhythm.”*

Let’s create a storytelling program that interacts with the user and creates a small personalized narrative.

```sathi
sathi bhanna "📖 Let's make a story together!"
sathi leu naam "Tapaiko naam k ho? "
sathi leu sahar "Tapaiko sahar ko naam k ho? "
sathi leu sapana "Tapaiko sapana k ho? "

sathi bhanna "Once upon a time, there was a coder named " + naam + "."
sathi bhanna naam + " lived in the city of " + sahar + "."
sathi bhanna "Every day, " + naam + " dreamed of becoming a " + sapana + "."
sathi bhanna "One day, " + naam + " met Sathi — a friend who believed in them."
sathi bhanna "Together, they turned that dream into code."
```

✅ Example Output:
```
📖 Let's make a story together!
Tapaiko naam k ho? Nirajan
Tapaiko sahar ko naam k ho? Kathmandu
Tapaiko sapana k ho? Engineer
Once upon a time, there was a coder named Nirajan.
Nirajan lived in the city of Kathmandu.
Every day, Nirajan dreamed of becoming a Engineer.
One day, Nirajan met Sathi — a friend who believed in them.
Together, they turned that dream into code.
```

---

## 🎲 Project 4: Number Guessing Game

Games make learning fun, and Sathi loves playfulness!  
Let’s create a guessing game where the computer thinks of a number, and the user guesses.

```sathi
sathi bhanna "🎲 Welcome to the Guessing Game!"
sathi yo ho secret = 5

sathi doherau jaba sahi ho galat
    sathi leu guess "Guess a number between 1 and 10: "
    sathi yedi int(guess) == secret bhane
        sahi ho sahi
        sathi bhanna "🎉 You got it!"
    sathi natra
        sathi bhanna "Try again!"
    sathi sakkyo
sathi sakkyo
```

✅ Example Output:
```
🎲 Welcome to the Guessing Game!
Guess a number between 1 and 10: 3
Try again!
Guess a number between 1 and 10: 5
🎉 You got it!
```

> *“Games teach patience — and patience is the friend of every coder.”*

---

## 🧮 Project 5: Multiplication Table Generator

```sathi
sathi leu n "Enter a number: "
sathi bhanna "Multiplication Table of " + n

sathi yo ho i = 1
sathi doherau jaba i <= 10
    sathi bhanna str(i) + " x " + str(n) + " = " + str(int(i) * int(n))
    i = i + 1
sathi sakkyo
```

✅ Output:
```
Enter a number: 3
Multiplication Table of 3
1 x 3 = 3
2 x 3 = 6
...
10 x 3 = 30
```

> *“Logic becomes rhythm when repetition meets meaning.”*

---

## 💡 Project 6: Friendship Counter (Looping Warmth)

Sathi’s loops can also carry meaning beyond math.  
This small program repeats a friendly message multiple times.

```sathi
sathi leu naam "Tapaiko naam k ho? "
sathi leu patak "Kati patak ma bhanu 'Sathi ho!'? "

sathi doherau int(patak) choti
    sathi bhanna "Sathi ho, " + naam + "!"
sathi sakkyo
```

✅ Output:
```
Tapaiko naam k ho? Nirajan
Kati patak ma bhanu 'Sathi ho!'? 3
Sathi ho, Nirajan!
Sathi ho, Nirajan!
Sathi ho, Nirajan!
```

> *“Friendship grows with repetition — the more you say it, the truer it feels.”*

---

## 🧩 Combining Projects — The “All-in-One Sathi App”

You can combine all these mini-projects into a single, modular application.  
That’s the beauty of Sathi — each component can connect seamlessly.

```sathi
sathi bhanna "👋 Welcome to All-in-One Sathi App!"
sathi bhanna "1. Calculator"
sathi bhanna "2. Greeting Bot"
sathi bhanna "3. Story Maker"
sathi bhanna "4. Exit"

sathi yo ho choice = input("Choose an option (1-4): ")

sathi yedi choice == "1" bhane
    sathi laga "calculator.sathi"
sathi yedi choice == "2" bhane
    sathi laga "greeting.sathi"
sathi yedi choice == "3" bhane
    sathi laga "story.sathi"
sathi natra
    sathi bhanna "Goodbye from Sathi!"
sathi sakkyo
```

✅ Output:
```
👋 Welcome to All-in-One Sathi App!
1. Calculator
2. Greeting Bot
3. Story Maker
4. Exit
Choose an option (1-4): 2
Namaste! Ma Sathi Bot hu.
...
```

This project encourages modular thinking and reusability — the foundation of strong software design.

---

## 💭 Reflection: Why Projects Matter

Projects are not just “applications.”  
They are **conversations between imagination and logic**.

Sathi invites you to:
- Code with confidence  
- Express with emotion  
- Learn by doing  

Every project you create in Sathi is more than an exercise — it’s a story of communication, curiosity, and connection.

> “When code begins to feel like storytelling, that’s when true creativity begins.”  
> — *Nirajan Ghimire*

---

## 🪶 Summary

Sathi’s simplicity doesn’t limit creation — it **amplifies** it.  
By blending logic and language, even simple programs become meaningful.  

From calculators to stories, every Sathi project is an invitation to explore the human side of programming — to code like you talk, to create like you dream.

Next, we’ll explore how these small ideas grow into a full **ecosystem** — where Sathi evolves from a local experiment to a global movement.

> “Build small. Think big. Code with culture.”  
> — *Nirajan Ghimire*