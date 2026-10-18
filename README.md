# LumaForge Studio

A polished React + Vite visual website-builder demo with animated design details, responsive canvas, editable sections, template starters, local saving, undo/redo, and standalone HTML export.

## Requirements
- Node.js 18 or newer
- npm

## Run locally
```bash
npm install
npm run dev
```

## Production build
```bash
npm run build
npm run preview
```

Vite outputs the production site to `dist/`.

## Deploy on Vercel
- Import this repository.
- Framework preset: Vite
- Root directory: `./`
- Build command: `npm run build`
- Output directory: `dist`
- Install command: `npm install`

## What works
- Template selection and searchable template picker
- Add, select, reorder, edit and delete page sections
- Editable headlines, supporting copy, button labels and colours
- Desktop/mobile canvas preview
- Undo/redo for section and settings changes
- Local browser saving and recent project list
- Export current draft as a standalone HTML file
- Responsive layout and reduced-motion support

## Honest limitations
The “Start with an idea” tool creates a local starter concept from the user's prompt. It is not connected to an external AI model. Saving uses this browser's local storage; it is not cloud sync or user-account storage. Publish/hosting is handled separately by Vercel.
