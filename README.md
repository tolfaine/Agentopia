# 🏡 Agentopia

A living village where some of the villagers are your real AI agents at work. 🤖🌾

## 🌱 Intention

Agentopia is a sandbox village simulation that runs around the clock on one computer. 🌙☀️

- 🎮 **A game in its own right.** Villagers have needs, jobs and a small economy, and live their lives whether or not anything is connected. Their decisions use utility AI, and an inspector shows why each villager chose what it did.
- 🧑‍🌾 **A body for real AI agents.** A villager can embody a coding agent session (Claude Code first, Codex and others later) that runs elsewhere. The agent does not pilot the villager; its real activity (tools used, errors, waiting on you) shapes what the villager is seen doing.
- 🎛️ **A control surface.** From the world you can start a session, pick its model, read its chat, type into it and approve its permission prompts.

It is a personal project with two goals: a portfolio piece for game AI programming 💼, and an ant farm 🐜 worth leaving on a second monitor that also shows which agent needs you.

## 🚧 Status

Design stage. No code yet. ✏️

## ✨ Planned features

- 🧠 Headless C++ simulation: villagers with hunger and rest, utility AI, deterministic from a seed
- 🔍 Decision inspector: inputs, curve outputs and scores behind every choice
- 🗺️ Browser viewer: god view of the village, click anything to inspect it
- 🔌 Session gateway speaking the Agent Client Protocol, so one adapter covers Claude, Codex and Gemini
- 💬 Agent villagers driven by live session events, with a chat panel per agent
- 🥖 Jobs, about five goods and a small economy, with 20 to 30 villagers
- ⏩ Accelerated game clock with speed controls, saves, and an event log of what happened while you were away
- 🪄 Spawn presets, model picker and permission approval from the viewer
- 👀 Read-only villagers for sessions started in a terminal
- 📱 Phone access over a private network, never a public URL
- 🔮 Later: villagers with their own model-driven minds, an Unreal Engine viewer, fast-forward of missed time
