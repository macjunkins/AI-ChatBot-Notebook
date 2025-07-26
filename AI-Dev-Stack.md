# AI Dev Stack

## Let’s walk through a **minimal, focused dev stack** that covers:

* ✅ **Coding & implementation**
* ✅ **Issue coordination**
* ✅ **Contextual AI support in IDE**
* ✅ **Light GitHub integration (CLI preferred)**
* 💸 **Low/controlled cost**
* 🧠 **Maximize context and productivity**

---

## 🧰 Dev Stack Components (Coding-Only)

| Category                     | Recommendation                           | Notes                                                                  |
| ---------------------------- | ---------------------------------------- | ---------------------------------------------------------------------- |
| **IDE**                      | Zed or VS Code                           | Zed: Lightweight, Rust-native, collaborative. VS Code: plugin-rich.    |
| **AI Coding Assistant**      | **Cursor**, **Continue**, or **Codeium** | All have local context in-editor. No memory beyond file/project.       |
| **LLM Backend**              | LM Studio or Ollama                      | Run open models like Codestral, DeepSeek, etc.                         |
| **Project Agent (optional)** | Devika / GPT-Engineer / OpenDevin        | For multi-file reasoning, task planning. Good for greenfield projects. |
| **Version Control**          | Git + GitHub CLI                         | You’ve got this handled.                                               |
| **Issue Coordination**       | Use Linear CLI (or JSON files)           | We'll sync this lightly with PM side via milestone/issue IDs.          |

---

## 🧠 Key Decision Points

### 1. **IDE + AI Pairing**

#### Option A: **Cursor**

* Built on VS Code, optimized for AI pair programming.
* Context window based on file and project structure.
* GitHub-aware, but doesn’t require login.
* Works great with local models **or** OpenAI.
* 💸 **Free** (some limits), **\$20/mo Pro** — but you can use LM Studio backend.

#### Option B: **Continue + VS Code**

* Plugin that adds AI pane to VS Code.
* Open-source, can be configured with **LM Studio**, **Ollama**, or OpenAI.
* Full control over context, tokens, models.
* 📦 Ideal for DIY workflows.

---

### 2. **Coding Assistant vs Agent**

| Tool                      | Best Use                   | Local Model? | Project Context              |
| ------------------------- | -------------------------- | ------------ | ---------------------------- |
| **Cursor**                | Inline suggestions & edits | ✅            | ✅ File + project awareness   |
| **Continue**              | On-demand chat + code nav  | ✅            | ✅ Excellent in-VS Code agent |
| **Codeium**               | Fast autocomplete          | ❌ Cloud      | ❌                            |
| **Devika / GPT-Engineer** | Project generation         | ✅            | ✅ Full project plans, edits  |

---

### 3. **GitHub Integration**

Since you use the **GitHub CLI**, you don’t need anything baked-in. But:

* Cursor & Continue can "read" Git diffs, help with commit messages, etc.
* Zed supports built-in Git lens if needed.
* Project agents (Devika, GPT-Eng) can commit code and write commit messages.

---

## 🚀 Stack Suggestion for You (Coding Side)

Here’s a stack with **cost control**, **long context**, and **good separation** from ChatGPT:

| Component          | Tool                                                 |
| ------------------ | ---------------------------------------------------- |
| **IDE**            | Zed (for Rust) or VS Code                            |
| **AI Pairing**     | Continue (VS Code) or Cursor                         |
| **Model Runtime**  | LM Studio or Ollama                                  |
| **Optional Agent** | Devika (if you want an AI "co-dev")                  |
| **GitHub**         | gh CLI + commit hooks or AI-assisted commit messages |

---

## 🧪 Bonus: Local Models for Dev Work

Some local models you can run via LM Studio or Ollama:

| Model              | Type               | Context | Good For               |
| ------------------ | ------------------ | ------- | ---------------------- |
| **Codestral**      | Coding             | 32K+    | Autocomplete, code-gen |
| **DeepSeek Coder** | Coding + reasoning | 32K–64K | Explanations, edits    |
| **LLaMA 3 70B**    | General + code     | 8K–16K  | Good fallback          |
| **StarCoder2**     | Code-specialized   | 16K–32K | VS Code pairing        |

Use Q4\_K\_M or Q5\_1 versions for better performance in LM Studio.

---

## ✅ Next Steps

Would you like to:

* Compare **Cursor vs Continue** for your workflow?
* See a **model + tool compatibility chart** for your machine specs?
* Set up an initial **dev environment bootstrap** with project folder layout + tools?

Let’s build out your dev side as lean and powerful as your PM setup.
