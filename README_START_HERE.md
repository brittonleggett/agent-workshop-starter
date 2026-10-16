# From Chatbot to Coworker: Your First AI Agent

Author: Britton Leggett. Everything in this folder is fictional practice material.

You've used AI that **answers**. This folder lets you try AI that **does the work**: it reads files, builds tools, sorts an inbox, and fixes its own mistakes, all on your own computer.

## Step 1: Unzip this folder (important)
Right-click the zip file → **Extract All** → **Extract**. Work from the extracted folder, not from inside the zip. If you skip this, the AI can't save anything.

## Step 2: Install ONE agent app (both are fine)
**Option 1, free: Codex (by OpenAI)**
1. Go to **chatgpt.com/download** and choose **Download for Windows** (or macOS). Install the app named **ChatGPT**, not "ChatGPT Classic."
2. Sign in. A free account works. You may be asked to verify a phone number.
3. From the **top-left menu**, choose **Codex**, then open this extracted folder. Open the folder itself: not the zip, and not your Downloads folder.
4. If asked about permissions, keep the default, or choose the option that limits it to this folder. Never pick **Full Access**.

**Option 2, if you pay for Claude Pro: Claude Code (by Anthropic)**
1. Install the **Claude desktop app** from claude.com/download.
2. Sign in, open the **Code** tab, and choose this extracted folder.

No terminal, no programming tools, and no admin rights are needed.

## Step 3: Say hello
Paste this as your first message:
> What's in this folder, and what instructions were you given?

If it describes Crawdad Junction Catering and the files below, you're set up correctly. If it says the folder is empty, you opened the wrong folder (see Step 1).

## What's in here
| File | What it is |
|---|---|
| `AGENTS.md` / `CLAUDE.md` | The AI's standing instructions (same text, one for each app). **Read one.** This is how you "program" an agent: in plain English. |
| `business_rules.md` | The company's prices and policies. |
| `inbox/` | 40 customer emails. |
| `data/sales.csv` | 21 months of weekly sales. |
| `tools/deposit_calculator.html` | A tool the "last intern" built. Is it right? |

## Things to try (copy any of these)
1. *"Build a catering quote calculator from business_rules.md that I can open in my browser."*
2. *"Go through every email in the inbox. Sort them into folders by type, draft a reply to each one that follows our rules, flag anything a manager must see, and make a summary spreadsheet."*
3. *"Turn data/sales.csv into a one-page dashboard. What are the three most important things the owner should know?"*
4. *"Check tools/deposit_calculator.html against business_rules.md. Find every mistake, explain each in plain English, and save a fixed version."*
5. *"Make me something useful for this business that I didn't ask for."*

## Three habits of people who use agents well
1. **Read before you approve.** When the agent asks permission to do something, read what it is.
2. **Check one number.** Agents sound confident even when they're wrong. (To open a tool the agent built, double-click the .html file in File Explorer or Finder.)
3. **Never use real data here.** No real customer info, passwords, or company files in practice folders.

Questions? Ask Dr. Leggett.
