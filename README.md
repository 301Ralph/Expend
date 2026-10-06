# Expend

A responsive personal budget tracker with an original anime-inspired dark fantasy interface. Built with JavaScript and Vite. No paid APIs or backend required.

## Features

- Income and daily expense records with categories, dates and notes
- Monthly bill and utang records, with paid/unpaid controls
- Monthly dashboard and spending budget
- Search, edit and delete transactions
- PHP by default, with selectable currency formatting
- JSON backups for transferring records between browsers
- Responsive phone, tablet and desktop layouts

Records stay in localStorage in the current browser. No account or automatic synchronization is provided. Export backups regularly: clearing browser data will delete records. Use a trusted personal device. Available balance means this month's recorded income minus expenses and paid bills; it is not a bank balance. Debts represent money you owe and are shown separately; marking a debt paid does not create an expense. Add that expense separately if you want it included in spending. Monthly bills are individual records; create one for each billing month.

## Development

Use Node.js 22.12+ (or 20.19+).

```sh
npm ci
npm run dev
```

```sh
npm run build
npm run preview
```

## Deploy on Netlify

1. Push this project to your GitHub repository.
2. In Netlify, import the repository and select your branch.
3. Build command: `npm run build`. Publish directory: `dist`. These settings are included in `netlify.toml`.
4. Deploy. No environment variables or secrets are required.

Alternatively, run `npm run build` and drag the `dist` folder into Netlify's manual deploy interface. Deploy the built folder, not the source folder.

Google Fonts enhances the typography; system fonts work when it is unavailable. The interface uses original CSS artwork and does not include copyrighted anime artwork.
