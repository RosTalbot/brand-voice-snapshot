# 🧠 Vibe Agent 02: Brand Voice Snapshot

**Brand Voice Snapshot** is a lightweight, AI-powered tone analysis tool that helps founders and marketers quickly understand the unique writing style behind their brand. By pasting in a short content sample, users receive an instant summary of tone, sentence structure, formatting patterns, and “vibe tags” to guide brand consistency or train GPTs.

> 🛠️ Built for async teams, creative ops, and solo creators who want fast brand clarity—without hiring a strategist.

---

## 🚀 How It Works

**Input:**  
A short writing sample (e.g., website copy, email, social post)

**Output:**  
A Markdown-style breakdown of:
- 🌟 Tone Descriptors (e.g. confident, friendly, irreverent)
- ✍️ Sentence Style (short, punchy, or complex)
- 🎨 Formatting Patterns (emojis, lists, line breaks, etc.)
- 🔖 Vibe Tags (quirky, polished, rebellious, etc.)
- 💡 Emotional Impact (how the tone *feels*)
- 🧹 Bonus: GPT-ready prompt snippet to replicate the voice

---

## 📥 Example Input

```
We believe creative freedom isn’t optional—it’s the whole point.
Our tools are here to simplify, clarify, and get the hell out of your way.
```

---

## 📤 Example Output

```markdown
**Tone:** Bold, direct, empowering  
**Sentence Style:** Short, punchy  
**Formatting Patterns:** Em dash, emphatic punctuation, no emojis  
**Vibe Tags:** rebellious, modern, no-nonsense  
**Audience Feeling:** Energized, unfiltered, motivated  
**Prompt to Replicate This Style:**  
Write in a bold, irreverent tone with short, declarative sentences. Avoid emojis. Emphasize personal freedom and cut through fluff.
```

---

## 🧪 Use Cases

- ✍️ Founders documenting brand voice for the first time  
- 🧠 AI trainers building tone-aligned GPTs or Claude bots  
- 🧑‍🎨 Creative teams needing tone audits for client copy  
- 📢 Marketers improving consistency across platforms

---

## 🛠 Tech Stack

| Layer        | Tool       |
|--------------|------------|
| LLM          | GPT-4 (ChatGPT, Claude optional) |
| Interface    | Replit, Notion form, or n8n (optional) |
| Output       | Markdown / JSON / text |
| Hosting      | Local or cloud-based (optional) |

---

## 🧹 Prompt Template

```text
You are a brand voice analyst.  
Analyze the following writing sample and return a structured summary with:
- Tone descriptors (max 3)  
- Sentence structure (short, medium, long)  
- Formatting patterns (e.g., lists, emojis, line breaks)  
- Vibe tags (quirky, bold, calm, etc.)  
- A sentence about how this voice might feel to a reader  
- Bonus: A GPT/Claude-ready prompt to mimic this style

[Insert writing sample here]
```

---

## 🏗 Status: MVP v1  
This is the first iteration of **Vibe Agent 02** in the [Micro Vibe Projects Series](https://github.com/RosTalbot).  

Planned improvements:
- Custom input form (Notion or Replit)
- Export to Markdown
- Voice training toggle (fine-tune-ready JSON format)

---

## 👤 Creator  
Built by [Ros Talbot](https://github.com/RosTalbot)  
Part of the AI Agent Bootcamp, 2025

---
