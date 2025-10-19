

# Chapter 2 — Installation & Setup

> *“Simplicity is the first sign of clarity. The easier it is to begin, the more people you empower.”*  
> — **Nirajan Ghimire**

---

## ⚙️ Introduction

Installing **Sathi Language** is more than just setting up a tool — it’s the beginning of a creative relationship with your computer.

Every programmer remembers the first moment their terminal replied back. That instant of *interaction* — when you say something and the machine listens — is magical.  

I wanted that first moment in Sathi to feel warm, human, and welcoming.  
No complex build tools, no compiler errors — just a friendly “Sathi!” to greet you.

Sathi runs anywhere Python runs: Windows, macOS, Linux — even Raspberry Pi.  
Because friendship shouldn’t have boundaries.

---

## 🪜 Step 1: Installation via PyPI

The simplest way to get started is by using **pip**, Python’s package manager.

```bash
pip install sathi-lang
```

After installation, you can verify that Sathi is working by typing:

```bash
sathi --version
```

If the version number appears, you’re ready to start your journey.

---

### 💬 Why PyPI?

I chose PyPI because accessibility matters.  
Many learners don’t have admin access to install compilers or configure environments.  
But Python — it’s everywhere.  

By making Sathi a **PyPI package**, I ensured that anyone, anywhere, can start coding with culture in less than a minute.  
No barriers, no dependencies — just curiosity and creativity.

---

## 📁 Step 2: Create Your First Sathi Program

Now, let’s create your first `.sathi` file.  
Open your favorite text editor and type the following:

```sathi
sathi bhanna "Sathi!"
```

Save it as `hello.sathi` and run:

```bash
sathi hello.sathi
```

✅ **Output:**
```
Sathi!
```

Your computer just greeted you back — in your language.  
That simple interaction is the essence of Sathi.

> “When the machine speaks your word, you realize — you were never just coding, you were communicating.”

---

## 🧩 Step 3: Explore Sathi from Source

If you prefer working directly with the source code:

```bash
git clone https://github.com/nirajang20/Sathi-Language.git
cd Sathi-Language
python3 sathi.py examples/hello.sathi
```

This allows you to experiment, modify, and extend the language however you like.  
After all, a true friend doesn’t hide secrets — it invites you to explore.

---

## 💻 Step 4: Using the VS Code Extension

For those who love clean syntax highlighting and snippets, Sathi’s **VS Code extension** provides an elegant experience.

### 🧭 Installation

1. Open **VS Code**.  
2. Go to **Extensions → Install from VSIX...**  
3. Select the file `sathi-lang.vsix`.  
4. Open a `.sathi` file — highlighting and auto-suggestions will activate instantly.

### 💡 Included Snippets

| Shortcut | Expands To |
|-----------|------------|
| `bhanna` | `sathi bhanna "..."` |
| `yedi` | Template for if-else block |
| `dohoryau` | Template for repeat loop |
| `kamgar` | Template for function definition |

---

## 🌐 Step 5: Run Anywhere

Once installed, Sathi works seamlessly across operating systems.  
You can even use it on **Raspberry Pi** to blend hardware with cultural software.

```bash
python3 sathi.py yourfile.sathi
```

Or on macOS:

```bash
sathi yourfile.sathi
```

> “The more universal the tool, the more personal the creation becomes.”

---

## 🧠 Troubleshooting Tips

If you face an issue during installation, don’t worry — Sathi listens and helps.

| Problem | Possible Cause | Solution |
|----------|----------------|-----------|
| `ModuleNotFoundError` | Python environment issue | Reinstall using `pip install sathi-lang` |
| `Permission Denied` | Missing admin rights | Use `--user` flag in pip command |
| `sathi command not found` | PATH not updated | Run via `python -m sathi` directly |

For deeper help, visit:  
[https://github.com/nirajang20/Sathi-Language/issues](https://github.com/nirajang20/Sathi-Language/issues)

---

## 🪶 Summary

Installing Sathi isn’t about setup — it’s about *starting a dialogue*.  
When your computer replies *“Sathi!”*, that’s the first spark of creativity — the beginning of friendship between you and technology.

So, open your terminal.  
Say hello.  
And let your journey begin — with **Sathi**.

> “Every friendship starts with a hello — this one begins with a line of code.”