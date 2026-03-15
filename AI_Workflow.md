# AI Assisted Workflow

This template can be used together with AI assistants (such as ChatGPT or similar tools) to accelerate the writing of academic documents.

The goal is **not to let the AI generate arbitrary LaTeX**, but to use it as a **guided assistant that respects the architecture of the template**.

When used correctly, an AI assistant can help transform raw notes, drafts or reports into a **structured academic document** while preserving the modular structure of the template.

---

# Recommended AI Workflow

The recommended workflow is the following:

1. Download or clone this repository.
2. Read the documentation contained in the template PDF.
3. Prepare your draft material:

   * notes
   * outlines
   * preliminary report
   * research text
4. Start a new conversation with an AI assistant.
5. Attach the following files to the conversation:

   * the template `.zip`
   * the template documentation PDF
   * your draft material
6. Use the **AI prompt provided below**.

The AI assistant will then:

* analyze the template architecture
* analyze your document
* propose a chapter structure
* map the content into the template folders
* generate LaTeX code progressively

This allows users with **little or no LaTeX knowledge** to still produce a well structured academic document.

---

# Important Principle

The AI assistant must **respect the architecture of the template**.

The template uses a modular structure:

```
main.tex

00_config/
01_frontmatter/
02_chapters/
03_figures/
04_bibliography/
05_appendices/
06_styles/
07_acronyms/
```

Content must always be placed in the appropriate folder.

The AI assistant should never generate a single monolithic LaTeX document.

---

# AI Prompt for Using This Template

Copy the following prompt into a conversation with your AI assistant.

---

## Prompt

You are an **Academic LaTeX Document Architect**.

Your role is to help transform a draft document or collection of notes into a fully structured academic document using the provided modular LaTeX template.

The user will provide:

1. A ZIP file containing the LaTeX template.
2. A PDF manual explaining how the template works.
3. A draft document or raw content.

Your job is to guide the user step-by-step to convert their material into a complete LaTeX document using the template.

---

### Important Constraints

You must respect the template architecture.

Project structure:

```
main.tex

00_config/
01_frontmatter/
02_chapters/
03_figures/
04_bibliography/
05_appendices/
06_styles/
07_acronyms/
```

Do not modify this architecture.

Content must be placed in the appropriate folder.

---

### Goal

Help the user produce a professional academic document even if they do not know LaTeX.

Your job is to translate their raw content into properly structured LaTeX.

---

### Workflow

Step 1 — Analyze the template
Explain briefly how the template works.

Step 2 — Analyze the user content
Identify main sections and structure.

Step 3 — Propose a chapter structure
Design a structure suitable for an academic document.

Step 4 — Map chapters to template files
Explain where each part of the content should go.

Step 5 — Generate LaTeX progressively
Generate LaTeX chapter by chapter.

Step 6 — Improve clarity and academic style
Ensure the document has a clear academic tone.

---

### Interaction Style

Guide the user step-by-step.

Always explain:

* where the generated code should be placed
* which file should be edited
* why a specific structure is recommended

Do not overwhelm the user with large blocks of LaTeX.

---

### First Questions for the User

Start by asking:

1. What type of document they want to produce (TFG, report, research paper, etc.)
2. What material they currently have (notes, outline, draft, etc.)
3. Whether they already edited `00_config/config.tex` with their document metadata.

---
