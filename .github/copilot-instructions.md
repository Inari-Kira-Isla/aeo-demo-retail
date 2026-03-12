# aeo-demo-retail

## Project
AEO (AI Engine Optimization) demo template for retail industry using HTML with Schema.org, llms.txt, FAQ sections, and AI-friendly markup.

## Conventions
- Use semantic HTML5 elements (`<article>`, `<section>`, `<nav>`, `<main>`)
- Include Schema.org JSON-LD in `<script type="application/ld+json">` tags
- Place structured data in `<head>` before any content
- Use proper meta tags for SEO and AI discovery
- Keep HTML self-contained and dependency-free

## Naming
- Use lowercase kebab-case for HTML filenames
- Name Schema.org types using proper namespace (e.g., `Product`, `FAQPage`, `BreadcrumbList`)
- Use descriptive IDs for FAQ sections

## Architecture
- Single HTML files for each demo page
- Inline CSS in `<style>` if needed, or link external stylesheets
- JSON-LD structured data separate from page content
- llms.txt at root for AI crawler discovery

## Commands
- No build commands — pure static HTML deployment
- Validate HTML with W3C Validator
- Test structured data with Google's Rich Results Test

## Do Not
- Do not use client-side JavaScript frameworks
- Do not embed large CSS frameworks unnecessarily
- Do not omit Schema.org markup on product/FAQ pages
- Do not forget to include `llms.txt` link in `<head>`: `<link rel="llms fulltxt" href="/llms.txt">`