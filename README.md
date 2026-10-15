# AudioFlow

A lightweight, browser-based project tracker, manual voice quality-control checklist and invoice builder for freelance audio engineers.

## Live demo

Once GitHub Pages is enabled, visit `https://YOUR-USERNAME.github.io/audioflow/`.

## Features

- Dashboard showing active projects, logged hours and estimated unbilled work
- Project records with client, status, hours, hourly rate and delivery notes
- Printable invoices (use the browser's **Print → Save as PDF** option)
- Per-project manual voice QC checklist covering clipping, noise, naturalness, artifacts, loudness and delivery format
- Browser-local storage; no account, backend or network connection required

## Run locally

Download the three files (`index.html`, `style.css`, `script.js`) into the same folder and open `index.html` in a browser.

## Technical notes

Built using vanilla HTML, CSS and JavaScript. Data is stored in browser `localStorage` and is not synced between devices. Sample projects are illustrative. QC results are human-entered, not automatically measured. Invoice totals do not include VAT or other tax calculations. Not intended as production accounting software.

## AI-assisted development

This project was created with AI assistance to explore practical workflows for freelance audio production. It should be presented transparently as an AI-assisted demonstration rather than evidence of independently written software.
