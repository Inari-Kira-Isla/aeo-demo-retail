# aeo-demo-retail

## Overview
A retail industry demo template demonstrating AEO (AI Engine Optimization). It provides a foundation for implementing Schema.org, `llms.txt` for AI agent instructions, and FAQ markup to make retail content easily indexable by LLMs and AI search engines.

## Tech Stack
- **HTML5**: Core markup.
- **JSON-LD**: For Schema.org structured data (Product, Organization).
- **CSS**: Basic styling for presentation.
- **Vanilla JS**: Minimal interaction if needed.

## Architecture
- `index.html`: Main entry point containing semantic HTML and embedded Schema.org markup.
- `llms.txt`: A text file providing instructions or sitemaps specifically for AI agents (LLMs).
- FAQ Section: Structured Q&A blocks optimized for AI parsing.

## Commands
- **Preview**: Open `index.html` in any browser.
- **Validation**: Use [Google Rich Results Test](https://search.google.com/test/rich-results) or [Schema Markup Validator](https://validator.schema.org/) to verify the JSON-LD output.

## Coding Style
- Use semantic HTML5 tags (`<main>`, `<article>`, `<section>`).
- Ensure JSON-LD is valid and contextually matches the visible content.
- Prioritize readability and structure for AI agents over complex visual layouts.

## Important Rules
- **Strict Schema**: Broken or mismatched Schema.org data can lead to penalties. Always validate.
- **AI Access**: Ensure `llms.txt` is accessible and not blocked by `robots.txt`.
- **Maintain Semantics**: Do not strip semantic tags; they are crucial for AEO.