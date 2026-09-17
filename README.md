# Orixa — Landing Page Ecommerce in Revenue Share

Landing page per un business model di creazione e gestione ecommerce a **revenue share**:
nessun costo di setup, nessun canone, compenso calcolato come percentuale sulle vendite online.

Basata sul tema Astro VIIO, con contenuti, sezioni e metadati completamente riscritti.

## Getting Started

Edit the following files to customize links, content, and layout details:

- `src/pages/index.astro` — contenuti e sezioni della landing
- `src/layouts/Layout.astro` — header, footer, link di navigazione e metadati
- `src/components/RevenueCalculator.astro` — simulatore revenue share (aliquote e soglie)
- `src/components/ContactCta.astro` — sezione contatti (email e link call)
- `src/i18n/ui.ts` — stringhe tradotte

## Installation

Install dependencies:

```bash
npm install
````

Run the development server:

```bash
npm run dev
```

Build the production site (output to `./dist/`):

```bash
npm run build
```

## Sezioni della landing

1. Hero con proposta di valore e CTA
2. Introduzione al modello revenue share
3. Come funziona (timeline in 4 step)
4. Gallery con punti di forza del negozio
5. Statements (rischio zero, interessi allineati, crescita misurabile)
6. Calcolatore revenue share interattivo
7. Modelli di collaborazione (Launch 15%, Scale 8%)
8. FAQ contrattuali e operative
9. Logo marquee
10. Contatti

## Personalizzazione

Sostituire `hello@orixa.studio` in `src/pages/index.astro` con l'indirizzo reale,
e aggiornare le aliquote nel componente `RevenueCalculator.astro` e nella sezione
`Plans` di `index.astro`.

## License

Il tema originale e i componenti inclusi sono utilizzabili **solo per scopi non commerciali**.
Verificare i termini della licenza prima di pubblicare questa pagina per un'attività commerciale.
