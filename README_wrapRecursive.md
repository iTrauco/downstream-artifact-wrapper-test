# 🧩 wrapRecursive.js

Wraps all nested Markdown headings (`##`, `###`, `####`, etc.) in collapsible `<details>` blocks recursively.

## Usage

```bash
node wrapRecursive.js your_file.md
```

This will output a new file:

```
your_file_recursive_collapsed.md
```

## Requirements

- Node.js

## Notes

- Each heading level is wrapped inside the previous level.
- Useful for implementation guides, docs, and technical specs.
