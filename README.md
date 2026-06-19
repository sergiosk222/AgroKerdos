# AgroKerdos / ΑγροΚέρδος

Accessible PWA profit calculator for farmers, elderly sellers, λαϊκή αγορά vendors, and small agribusinesses in Greece.

## Main idea

AgroKerdos answers one simple question:

> Did I really earn money today?

The app calculates revenue, expenses, net profit, break-even price, unsold kg, and daily market summary.

## Target users

- Elderly farmers
- Sellers at λαϊκή αγορά
- Small family producers
- Young family members helping older relatives
- Small agricultural businesses in Greece

## Accessibility-first UX

- Easy Mode for fast calculation
- Advanced Mode for detailed expenses
- Large Text mode
- Big buttons
- High contrast
- Clear human-readable result
- Status is shown with color + icon + text
- No hidden complex navigation
- Works well on mobile

## Features

- Greek, Russian, English interface
- Live calculations
- Revenue and expense cards
- Profit/loss human summary
- Progress bars
- Today Market Summary
- Best and weakest product of the day
- Local history using localStorage
- Open/delete saved calculations
- CSV export
- PWA manifest
- Offline cache
- GitHub Pages ready

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript
- localStorage
- Service Worker
- Web App Manifest

No backend, no database, no paid APIs, no framework, no npm dependencies.

## Files

```txt
/index.html
/styles.css
/app.js
/manifest.json
/service-worker.js
/icons/icon-192.png
/icons/icon-512.png
/README.md
```

## Local run

```bash
python3 -m http.server 8000
```

Open:

```txt
http://localhost:8000
```

## GitHub Pages

1. Open repository settings.
2. Go to Pages.
3. Select Deploy from a branch.
4. Branch: main.
5. Folder: /root.
6. Save.

## Roadmap

- Accounts
- Cloud sync
- Average market prices
- WhatsApp preorders
- Seller public page
- Supabase backend
- Marketplace for local producers
- Printable daily report
- Voice input for elderly users
- Receipt/photo scanning
