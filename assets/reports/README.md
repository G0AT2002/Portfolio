# Put your PDF reports in this folder.

Then point at them from `data.js`:

    files: [
      { label: { en: "Report", fr: "Rapport" }, path: "assets/reports/your-file.pdf" }
    ]

Every PDF in here is now a real deliverable — the `*-PLACEHOLDER.pdf` stubs are gone.

Naming: lowercase, dashes, no spaces or accents — e.g. `splunk-detection-lab.pdf`.

Redact before committing: a public repo means public PDFs.
