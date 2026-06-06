# Lema Markdown

Personal fork of [MarkText](https://github.com/marktext/marktext), an open-source, markdown editor focused on speed and usability.

This project is based on the original MarkText source code (MIT license) and is maintained as an independent codebase for experimentation and personal development.

## Origin

- **Original project:** [marktext/marktext](https://github.com/marktext/marktext)
- **Original authors:** [Jocs](https://github.com/Jocs), [Felix Häusler](https://github.com/fxha), [Tkaixiang](https://github.com/Tkaixiang), and contributors.
- **Original license:** MIT

## Status

In development. Minimal changes from upstream for now.

## Getting Started

Requirements:
- Node.js >= 20.19.0
- pnpm >= 10

```bash
pnpm install
pnpm dev
```

**Windows users:** `ced` and `keytar` are optional native dependencies. If you do not have Visual Studio Build Tools with the "Desktop development with C++" workload installed, `pnpm install` will skip their compilation and the app will use fallbacks (UTF-8 for encoding detection and electron-store for password storage). This is sufficient for UI development.

## Attribution

- **App icon:** "Hp Notepad Pencil" from [Harmonia Pastelis Icons](https://www.iconarchive.com/show/harmonia-pastelis-icons-by-raindropmemory.html) by [Teekatas Suwannakrua](http://raindropmemory.deviantart.com/) (Raindropmemory). Licensed as [free for non-commercial use](https://www.iconarchive.com/show/harmonia-pastelis-icons-by-raindropmemory.html).

## License

[MIT](LICENSE).
