# C.O.C.E.

**Talk messy, let AI organise it.**

I never write a perfectly structured prompt. I open a voice note, talk the way it is in my head, and let the AI organise it into four parts before any work starts:

| | |
|---|---|
| **C**ontext | The situation, who you are in it, what already exists |
| **O**bjective | What you actually want to happen |
| **C**riteria | What can and can't happen, including what you don't want |
| **E**xamples | References, screenshots, things you like |

You check the result, say "ok", and get one clean request to paste into a new chat.

## Quick start: any AI chat

Copy the prompt and paste it at the start of a conversation, then send your voice note transcript or messy text:

- 🇦🇺 English: [prompt-en.md](prompt-en.md)
- 🇧🇷 Português: [prompt-pt-br.md](prompt-pt-br.md)

## Save it once, use it every time

So you don't have to paste it in every chat, save it inside your AI:

| AI | Where it goes | How |
|---|---|---|
| **Claude** | Skill | Download [`coce.zip`](coce.zip). Go to **Customize › Skills**, click **+**, then **Create skill › Upload a skill**, and choose the zip. Needs **Code execution and file creation** on in **Settings › Capabilities**. |
| **Gemini** | Skill | Download [`coce.zip`](coce.zip). In gemini.google.com, go to **Customize › Skills**, click **Create › Upload** and choose the zip (or the `SKILL.md` file). |
| **ChatGPT** | Project | Create a **New project** (e.g. "C.O.C.E."). Open the project's **••• › Project settings** and paste the prompt from [prompt-en.md](prompt-en.md) into the instructions. Start your chats inside that project. |
| **Copilot** | Agent | In the Microsoft Copilot app, under **Agents**, select **New agent**, choose **Configure**, and paste the prompt from [prompt-en.md](prompt-en.md) into **Instructions**. |

The same `SKILL.md` works as a skill in Claude and Gemini. For ChatGPT and Copilot, use the copy-paste prompt.

## Example

> "I want an app to help people lose weight, it has to be in British English, not American, and I like the look of a couple of apps I'll send you..."

becomes:

- **Context:** starting a new app project
- **Objective:** a weight-loss app
- **Criteria:** British English, not American
- **Examples:** screenshots of apps I like (mentioned, not shared)

---

Made by Bianca Vasques · [@biancavasques.ai](https://instagram.com/biancavasques.ai)
