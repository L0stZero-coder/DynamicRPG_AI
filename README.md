# 🧠 DynamicRPG_AI — AI-Driven Narrative Role-Playing Engine

DynamicRPG_AI is a C++-based interactive storytelling engine that generates and adapts branching RPG narratives in real-time based on player choices. It maintains a memory of past decisions to deliver more immersive, personalized storylines — forming the foundation for future AI-enhanced role-playing systems.

---

## 🎮 Key Features

- 🧭 **Branching Story Engine** – State-driven narrative progression
- 🧠 **Memory-Based Choices** – Tracks past decisions and reflects them in future events
- 🗂️ **Modular Structure** – Easy to expand with more story states or advanced logic
- 🔗 **JSON-Compatible** – Potential for dynamic loading and external story integration
- ⚡ **CMake Build System** – Fast compilation and portability across platforms
- 🔮 **Python NLP Stub** – Future-ready integration with LLMs like GPT or BERT

---

## 📁 Folder Structure

```
DynamicRPG_AI/
├── include/            # C++ header files
├── src/                # Core source code
├── data/               # Optional JSON story structure
├── scripts/            # Python NLP generator stub
├── assets/             # Placeholder for game audio/visual content
├── CMakeLists.txt      # Build configuration
└── README.md           # Project documentation
```

---

## 🛠️ Build Instructions

### 🔧 Prerequisites

- C++17 compatible compiler (GCC, Clang, or MSVC)
- CMake ≥ 3.10

### 🚀 Steps to Build & Run

```bash
git clone https://github.com/L0stZero-coder/DynamicRPG_AI.git
cd DynamicRPG_AI
mkdir build && cd build
cmake ..
make
./DynamicRPG_AI
```

---

## 🧩 Dependencies

Currently lightweight and dependency-free for the C++ side.

**Optional (Python NLP integration):**
- Python 3.8+
- `transformers` (for GPT-like model)
- `openai` SDK (if using OpenAI API)

---

## 🌱 Future Improvements

> The goal is to evolve this into a true AI storyteller.

Here’s what’s coming or recommended:

- 🗣️ **Natural Language Understanding (NLP):** Integrate GPT or LLM APIs to dynamically generate dialogue and story branches.
- 💾 **Save/Load System:** Allow story and memory persistence across sessions.
- 🧠 **Memory-Driven Consequences:** Let past decisions influence future paths, NPC behavior, and emotional arcs.
- 🎭 **Character Personalities:** Add emotional depth and unique NPCs with distinct behaviors.
- 🌍 **World State Engine:** Develop a global state machine to track factions, time, reputation, etc.
- 🌐 **Multilingual Support:** Localize prompts and stories using external JSON or gettext.

---

## 🤝 Contributing

Want to help shape the future of dynamic AI-powered storytelling? Contributions are welcome — from new story branches to AI model integrations.

---

## 📜 License

MIT License — feel free to use, modify, and distribute.

---

## 👨‍💻 Author

**L0stZero-code** — Computer Science.  
Project: *BoardMasterAI | Narrative Module: DynamicRPG_AI*

---

> “A story is a living thing — the more choices you make, the deeper it breathes.”
