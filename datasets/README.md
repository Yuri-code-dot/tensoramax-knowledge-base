# TensoraMax Knowledge Base: Datasets

This directory contains various JSONL (JSON Lines) datasets intended for training and fine-tuning small language models (SLMs) within the TensoraMax AI ecosystem. These datasets cover a range of topics relevant to web development, UI/UX design, and AI assistant interactions, providing a foundational corpus for TXB's learning.

## Dataset Format

Each file is in JSON Lines format, where each line is a valid JSON object. Typically, each object contains a `"prompt"` field and a `"response"` field, representing a question-answer pair or an instruction-completion pair.

## Contents

*   `coding.jsonl`: General coding questions and answers, covering various programming concepts.
*   `html.jsonl`: Prompts and responses specifically related to HTML structure, tags, and best practices.
*   `css.jsonl`: Prompts and responses focusing on CSS styling, layout, and responsive design.
*   `javascript.jsonl`: Prompts and responses for JavaScript programming, including syntax, concepts, and common tasks.
*   `uiux.jsonl`: Questions and answers related to UI/UX design principles, patterns, and accessibility.
*   `txb_knowledge.jsonl`: Data specifically about TXB, TensoraMax Studio, its modules, vision, and roadmap.
*   `conversations.jsonl`: Example conversational turns between a user and TXB, demonstrating natural language interaction.

These datasets are designed to be expanded and refined as the TensoraMax Studio and TXB evolve, serving as a critical resource for improving TXB's intelligence and contextual understanding.
