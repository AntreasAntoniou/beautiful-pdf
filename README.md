# Beautiful PDF

An agent skill for making print-ready PDFs with HTML/CSS, Pandoc, WeasyPrint, and a rendered-page visual review loop.

## Install

```bash
npx skills add AntreasAntoniou/beautiful-pdf
```

The package contains a portable skill, a production-oriented A4 stylesheet, document patterns, and a PDF-to-PNG review helper. Rendering dependencies are intentionally not installed automatically.

## Test

```bash
python3 -m unittest discover -s tests
```

MIT licensed. See [SECURITY.md](SECURITY.md) before processing sensitive documents.
