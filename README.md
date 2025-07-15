# Canvas LLM Science Tools

This GitHub repository contains starter materials for building interactive, standards-aligned web apps for use within the Canvas LMS, powered by Large Language Models (LLMs). The tools and prompts here are designed to help educators without coding experience create engaging learning experiences with AI support.

---

## 🔧 What’s Included (For Now)

- `html-apps/` – A sample embeddable HTML learning tool (e.g., ion randomizer)
- `prompts/` – Two system prompts to use with ChatGPT or local LLM tools:
  - `web_app_generator.txt`
  - `instructional_design_writer.txt`

🗂️ **Note:** Additional instructional design artifacts, lesson plans, and deployment guides are hosted in our [Google Drive folder](#) (link to be added when ready).

---

## 🧱 Prompt 1: Web App Generator

**Use this prompt to instruct an LLM to generate simple, embeddable HTML/JS learning tools.** These tools can be uploaded into Canvas directly, no plugins or external dependencies required.

Steps:
1. Copy the text from `prompts/web_app_generator.txt`
2. Paste it into the **system prompt field** in ChatGPT (or LM Studio)
3. Provide a classroom concept (e.g., "Create an app that randomizes cations and anions for ionic bonding practice.")
4. Save the HTML output and test it locally or upload it to Canvas.

---

## 📘 Prompt 2: Instructional Design Writer

**Use this prompt to create a full standards-aligned instructional summary** based on a learning activity or app.

Steps:
1. Copy the text from `prompts/instructional_design_writer.txt`
2. Paste it as the system prompt
3. Provide a short description of the activity or app (e.g., "Students use a tool that generates cations and anions and write compound names.")
4. The LLM will return:
   - GSE alignment
   - Learning target
   - Success criteria
   - UDL, SEP, CCC, DCI integration

---

## 🌐 Sample App

See `html-apps/ion_randomizer.html` for an example web-based tool created using Prompt 1. This can be embedded into a Canvas LMS module to allow students to interact with randomized ion data.

---

## 📄 License

All prompts and HTML tools in this repository are shared under the [Creative Commons Attribution 4.0 License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You are free to:
- Share and adapt
- Use commercially or non-commercially
As long as you **provide attribution**.

---

## 📎 More Resources

Lesson plans, deployment guides, and UDL-aligned instructional designs will be added to this GitHub repo in the future. For now, visit our shared [Google Drive workspace](#) (link coming soon).

---

## 🙌 Maintainer

Created and maintained by **Derikson Rivera** for district instructional technology initiatives. For questions, collaboration, or PD requests, reach out via your district email or team drive.
