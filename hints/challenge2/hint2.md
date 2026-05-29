Order matters here.

The safe flow is:
AI response (Markdown)
→ marked (HTML)
→ DOMPurify (sanitized HTML)
→ DOM

If you sanitize before converting Markdown,
you're sanitizing the wrong thing.
