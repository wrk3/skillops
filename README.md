# 🧠 SkillOps Starter Kit by Work3

**Prototype, share, and evolve Agent Skills** — a lightweight, open framework to make AI workflows repeatable, auditable, and composable.

This repository accompanies the [Work3 article](https://work3.substack.com/) on *Agent Skills and the rise of SkillOps* — exploring how Anthropic’s new **Skills** framework transforms how organizations capture, execute, and scale procedural knowledge.

---

## 🚀 Why It Matters

Most AI work today is messy: one-off prompts, disconnected copilots, scattered experiments.  
**Skills** fix that — they let agents *learn how to do things* through modular, inspectable knowledge packs.  
When combined with a company’s **Enterprise Graph**, they become a living system of capability.

**SkillOps** is the practice of maintaining those Skills like software:
- versioned 🧾  
- governed 🔒  
- continuously improved 🔁  

That’s how organizations start *teaching themselves* through AI.

---

## 🧩 What’s Inside
```/skills-library/
├── registry.json
├── /meeting_summarizer/
│ ├── SKILL.md
│ └── /scripts/summarize.py
└── /finance_report/
├── SKILL.md
└── /scripts/generate_report.py


✅ **Pre-built examples:**  
- “Meeting Summarizer” — transforms raw notes into action items.  
- “Finance Report” — generates structured summaries from data.  

Each Skill contains:
- A `SKILL.md` definition (metadata + logic)  
- Optional scripts / resources  
- Version and ownership info for governance  

---

## ⚙️ How to Use

1. **Clone the repo**
   ```bash
   git clone https://github.com/<your-username>/skillops-starter-kit.git


Open a Skill and review its SKILL.md.

Test it in Claude:
Paste the contents into a chat and say

“You now have access to this Skill. Please use it to summarize this text.”

Create your own Skill by copying one of the examples.

Add it to registry.json to make it discoverable.

That’s your first SkillOps loop — encode, reuse, improve.

🌱 Evolve Your SkillOps Practice

Assign Skill Owners

Add metadata like status: active/deprecated

Track Skill usage and success rate

Link each Skill to your Enterprise Graph (data, team, workflow)

Over time, you’ll build a living capability network — a foundation for true agentic work.

🧩 Related Reading

Anthropic – Equipping Agents for the Real World with Skills

Work3 – From Agents to SkillOps: The New Stack of Work
