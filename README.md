# 🔧 TinCa (Concept Stage)

TinCa is an idea for a tiny, simple language for microcontrollers. 

The goal is to get rid of complex C++ syntax, curly brackets, and semicolons. It should be easy to read and write.

---

## 💡 Syntax Idea

```text
hey hardware

pin(13) = 1

repeat 3
    pin(13) = 0
    delay = 500
    pin(13) = 1
    delay = 1000
```

### 📋 How it works:
* `hey` — acts like `import` or `include` to load the required module (e.g., `hey hardware`).
* `1` and `0` — mean `ON` and `OFF` (HIGH / LOW for microcontroller pins).

---

## 🛠 Current Status

This repository is just a notepad for my idea so I don't forget it. There is no working code here yet. 

I am a graphics guy, not a professional developer. My plan is to slowly build a simple Python script that takes this text and converts it into Arduino C++ code.

If you like the syntax or want to help with the parser later, feel free to open an Issue.
