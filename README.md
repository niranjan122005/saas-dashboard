# Base – SaaS Dashboard (React + TypeScript + Tailwind)

Implementation of the *SAAS Dashboard (figmamarket.com)* Figma file.

## Run
```bash
npm install
npm run dev      # http://localhost:5173
npm test         # vitest + Testing Library
npm run build
```
Any email + a 6+ character password logs in (demo auth, stored in localStorage).

## Structure
- `src/layout` – responsive shell (fixed sidebar ≥ lg, slide-in drawer below)
- `src/components/ui` – Button, Modal, Badge, Checkbox, Toggle, Tabs, ActionMenu, Icon (Iconly PNGs tinted via CSS mask)
- `src/components/charts` – hand-written SVG charts (line, donut, sparkline, bars)
- `src/pages` – Auth (Login / Sign Up / Recover / Confirm), Dashboard, Analytics (Product + Customer), Invoice, Schedule (Task Preview board/list/timeline at /schedule, Schedule List at /schedule/list), Calendar (Day/Week/Month/Year), Messages, Notification, Settings (profile, password, preferences)
- `src/lib` – auth, store, toast, prefs contexts
- `public/images`, `public/icons` – assets cropped/copied from the supplied PNGs and Iconly folder

