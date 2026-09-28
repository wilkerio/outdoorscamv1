<div align="center">

# OUTDOORSCAN

### Product engineering · React · TypeScript · Modern UI

<p>
  <img src="https://img.shields.io/badge/React-19-111827?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-5-111827?style=for-the-badge&logo=typescript&logoColor=3178C6" />
  <img src="https://img.shields.io/badge/Vite-Frontend-111827?style=for-the-badge&logo=vite&logoColor=646CFF" />
  <img src="https://img.shields.io/badge/Tailwind-CSS-111827?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4" />
</p>

**A product-oriented web application experiment built around a modern, component-driven frontend stack.**

</div>

---

## ✦ Project

OutdoorScan is a technical exploration of product engineering on the web.

The repository combines:

- React + TypeScript
- modern Vite tooling
- Tailwind CSS
- reusable UI primitives
- application data handling
- forms and validation
- charts and reporting
- document/export tooling

---

## 🧱 Frontend architecture

~~~text
┌──────────────────────┐
│     Product UI       │
└──────────┬───────────┘
           │
┌──────────▼───────────┐
│   React Components   │
│     + Radix UI       │
└──────────┬───────────┘
           │
┌──────────▼───────────┐
│ State / Data / Forms │
│     Query + Zod      │
└──────────┬───────────┘
           │
┌──────────▼───────────┐
│ Reporting / Exports  │
│ Charts / PDF / XLSX  │
└──────────────────────┘
~~~

---

## ✨ Engineering characteristics

### Component-driven UI

Radix UI primitives cover interaction patterns such as:

**Dialog · Menu · Tabs · Accordion · Popover · Select · Navigation**

### Data & state

The stack includes **TanStack Query** for application data handling.

### Forms & validation

**React Hook Form + Zod** provide the form and validation layer.

### Reporting & exports

The dependency stack includes:

- Recharts
- ExcelJS
- XLSX
- jsPDF
- html2canvas

---

## 🛠️ Stack

| Category | Technologies |
|---|---|
| UI | React 19 · Radix UI · Tailwind CSS |
| Language | TypeScript |
| Build | Vite |
| Data | TanStack Query · Supabase JS |
| Forms | React Hook Form · Zod |
| Routing | React Router |
| Charts | Recharts |
| Export | ExcelJS · XLSX · jsPDF |

---

## 🚀 Development

~~~bash
npm install
npm run dev
~~~

### Production build

~~~bash
npm run build
~~~

### Lint

~~~bash
npm run lint
~~~

---

## 🧠 Engineering model

~~~text
PRODUCT INTERFACE
       ↓
COMPONENT SYSTEM
       ↓
APPLICATION STATE
       ↓
DATA + VALIDATION
       ↓
REPORTING / EXPORTS
~~~

<div align="center">

**Design the interface. Structure the system. Ship the product.**

</div>

> OutdoorScan is presented as a public product-engineering exploration, not as a claim of a finished commercial platform.
