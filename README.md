# Resume

Two resume tools I built, each for a different audience. Each folder is a self-contained project with its own README and setup steps.

## Projects

### [`Claude_Resume_kit/`](./Claude_Resume_kit)

A Claude Code skill kit for tailoring resumes, CVs, and cover letters to a specific job description. You extract your source material (papers, code, reports, past resumes) into a knowledge base once, and every new application draws from it. The tool doesn't rewrite a pasted resume.

- Anti-fabrication rules: provenance flags on every achievement and verb-discipline rules that stop overclaiming
- Skills for `/make-resume`, `/make-cl`, `/critique`, and `/edit-resume`
- Builds `.docx` and `.pdf` output locally through a JSON-spec pipeline

My working copy of the open-source [claude-resume-kit](https://github.com/ARPeeketi/claude-resume-kit) by Akhil Reddy Peeketi (MIT License).

### [`ChatGPT_Resume_Marshallese_Assistance/`](./ChatGPT_Resume_Marshallese_Assistance)

A free, bilingual (English/Marshallese) resume builder for the Arizona Marshallese Community. You fill out a step-by-step form, can get ChatGPT help with the writing, and download a polished one-page PDF. No sign-up is needed, and it all runs in the browser.

- Toggle the interface between English and Marshallese
- Generates ChatGPT prompts for job bullets, skills, and the professional statement
- Keeps the resume to one page and exports a PDF client-side
- Vanilla HTML/CSS/JS, plus an optional Express analytics backend

## Repository layout

```
Resume/
├── Claude_Resume_kit/                       Claude Code resume-tailoring skill kit
└── ChatGPT_Resume_Marshallese_Assistance/   Bilingual browser-based resume builder
```

## History

Both projects were moved here from their original standalone repositories with their full commit history kept.
