# Daily Usage Guide: AI Engineering from Scratch

Welcome to **AI Engineering from Scratch**. This isn't a traditional video course—it's an AI-native learning journey designed to be used alongside your AI coding agent (like Claude Code, Cursor, etc.). 

By the end of your daily sessions, you won't just have theoretical knowledge; you will have built a reusable "toolkit" consisting of prompts, agent skills, and Model Context Protocol (MCP) servers.

Here is how you should structure your daily study and development routine.

---

## 1. Start Your Day: Pick Your Focus

If you are new here, determine your starting point using the built-in AI assessment.
* In your AI Coding Agent terminal, run:
  ```bash
  /find-your-level
  ```
  *(This 10-question quiz maps your knowledge and provides a personalized path with hour estimates).*

If you already know your phase, pick your next lesson from `ROADMAP.md`. 
* **Location:** `phases/<XX-phase-name>/<NN-lesson-name>/`

## 2. Study the Core Concepts
Before touching any code, understand the *why*.
* Open `docs/en.md` inside your selected lesson's directory.
* Read the **Motto** (the core idea), the **Problem** it solves, and the **Concept** (complete with Mermaid diagrams and intuitions).

## 3. Build It (From Scratch)
This is where the learning happens. You will implement the concept *without* relying on frameworks like PyTorch or Scikit-Learn at first.
* Open the `code/` directory in the lesson.
* Follow the steps to write the logic in pure Python, TypeScript, Rust, or Julia depending on the lesson. 
* *Why?* Building from scratch removes the magic and gives you deep intuition about how the math and algorithms actually behave.

## 4. Use It (With Frameworks)
Once you've built the underlying logic, learn how it's done in production.
* Still in the `code/` folder, implement the same concept using industry-standard libraries (PyTorch, sklearn, etc.).
* Compare the framework implementation with your from-scratch version.

## 5. Check Your Understanding
After completing the lesson or an entire phase, don't just move on. Validate your knowledge.
* Run the built-in Claude Code skill to take a targeted, 8-question quiz:
  ```bash
  /check-understanding <phase-number>
  ```
* Review the specific lessons the AI recommends based on your quiz results.

## 6. Ship It: Expand Your Toolkit
This is the most crucial step of your daily routine. **Every lesson ships a reusable artifact.**
* After finishing the lesson, navigate to the `outputs/` folder inside the lesson directory.
* Extract the tools:
  * `prompts/`: Templates you can paste into standard AI assistants to get expert help on the topic.
  * `skills/`: `SKILL.md` files ready to be installed into coding agents.
  * `agents/`: Autonomous worker definitions.
  * `mcp-servers/`: MCP servers to plug into AI applications.
* Use a tool like [SkillKit](https://github.com/rohitg00/skillkit) to install these into your actual workflow.

## Quick Summary Checklist for a Daily Session:
- [ ] Determine your next lesson (via `/find-your-level` or `ROADMAP.md`).
- [ ] Read the docs (`docs/en.md`).
- [ ] Implement from scratch (`code/`).
- [ ] Implement using a framework (`code/`).
- [ ] Collect the output artifact (`outputs/`) and add it to your AI toolbelt.
- [ ] Run `/check-understanding` when finishing the phase.

Happy building! Let your AI agent help you learn, and build tools to make your AI agent even better.
