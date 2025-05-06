# Callisto GPT Agent

## Overview

The **Callisto GPT Agent** is a custom AI assistant built on the ChatGPT platform. It is designed to generate awareness posters, maintain brand consistency, and provide reliable information on security topics. Leveraging a structured knowledge base and detailed agent instructions, Callisto helps users create high-quality, on-brand content efficiently.

## Key Features

- **Poster Generation**: Produces security-awareness poster content with predefined templates and style guidelines.
- **Brand Consistency**: Adheres to the Robotti brand color system, poster style guide, and tone primer to ensure all outputs align with company standards.
- **Security Expertise**: References a curated index of security topics and source integrity guidelines to generate accurate and trustworthy content.
- **Flexible Prompts**: Accepts user prompts for various security themes / risks and adapts output to HTML for a clean `Print To PDF` functionality with no margins.

## File Structure

```txt
callisto_gpt_agent/
├── README.md               # This documentation file
├── agent_instructions/      # Core behavior and prompt instructions
│   ├── callisto_instructions_V2025.05.03.txt
│   └── callisto_instructions_V2025.05.05.md  # Latest Version
├── agent_knowledge_documents/  # Structured knowledge for the agent
│   ├── robotti_color_system.md
│   ├── robotti_poster_style.md
│   ├── robotti_poster_template.html
│   ├── robotti_security_topics_index.json
│   └── robotti_tone_primer.md
└── example_awareness_posters/  # Sample outputs for reference / testing
    ├── HELPFUL ADD-ON, HIDDEN RISK.html # Prompt: Let’s do one on browser extensions that look helpful but expose data.
    ├── HELPFUL ADD-ON, HIDDEN RISK.pdf
    ├── TYPING IN TRUST_ THINK BEFORE YOU PROMPT.html # Prompt: Can you make a poster about AI data leaks from public prompt sharing?
    ├── TYPING IN TRUST_ THINK BEFORE YOU PROMPT.pdf
    ├── YOUR PERSONAL DEVICE, OUR COMPANY’S RISK.html # Prompt: Write a poster warning about insecure use of SSO on personal devices.
    └── YOUR PERSONAL DEVICE, OUR COMPANY’S RISK.pdf

```

## Getting Started

1. **Setup**: Upload the documents contained in the `agent_knowledge_documents` folder into the ChatGPT GPT Configuration Knowledge section.
2. **Configure**: In the ChatGPT GPT configuration screen, copy and paste the latest version of `callisto_instructions_V****.**.**.md` into the `Instructions` field.
3. **Deploy**: Give your iteration of `Callisto` a unique name and description. Bonus points if you give us credit.

## Usage

- **Prompt Examples**:
  - `Can you make a poster about AI data leaks from public prompt sharing?`
  - `Let’s do one on browser extensions that look helpful but expose data.`
  - `Write a poster warning about insecure use of SSO on personal devices.`
  - `Can you turn ‘don’t copy sensitive stuff into ChatGPT’ into a security one-pager?`
  - `Make a print-ready flyer about phishing that baits with anger.`
  - `Can you explain MFA fatigue as a poster someone would *actually* read?`
  - `Draft a poster about mobile app permissions in BYOD environments.`
  - `Help me create a security awareness poster using this quote: "I just wanted it to block ads…"`
  - `Turn this risk idea into a metaphor-first awareness poster: Teams messages leaking outside the org.`
  - `What would a Robotti-style one-pager look like for unpatched browser exploits?`

- **Expected Output**: A complete HTML document with inline CSS matching the Robotti color system and poster style, including title, body content, and a footer with source citations.

## Customization

- **Updating Templates**: Modify `robotti_poster_template.html` to change layout or add new placeholders.
- **Adding Topics**: Edit `robotti_security_topics_index.json` to include additional security themes / examples for better corporate messaging alignment.
- **Style Adjustments**: Tweak values in `robotti_color_system.md` or `robotti_poster_style.md` to refine typography, spacing, and color usage.

## Versioning

- **2025.05.05**: Enhanced Markdown instructions with examples, clarifications, and improved process flow instructions.
- **2025.05.03**: Initial instructions (in `.txt` format).


## 📜 License

This work is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License (CC BY-ND 4.0)](https://creativecommons.org/licenses/by-nd/4.0/).

© 2025 Robotti Tech Services LLC. Unauthorized modification or use without attribution is prohibited.

Use at your own risk — we assume no liability for misuse, misconfiguration, or any downstream consequences.

