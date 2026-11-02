# MotoX prototype (retired)

> **Retired on 2026-10-31.** This was the first prototype of MotoX. It is kept
> here, read-only, as a record of what was learned. The second version is at
> [Benko-E/MotoXv2](https://github.com/Benko-E/MotoXv2), and the current one, the
> third, at [Benko-E/MotoX](https://github.com/Benko-E/MotoX) and
> https://benko-e.github.io/MotoX/.

A browser motocross game in the spirit of Motocross Madness 1 and 2.
Milestone 1 is a free-ride sandbox about one thing: making the bike feel good.

**Play the prototype:** https://benko-e.github.io/MotoX-prototype/

## Run it on your own computer

```
npm install
npm run dev     # opens on http://localhost:5174
npm test        # headless checks
npm run build   # builds the site into docs/, which GitHub Pages serves
```

All feel values live in [`src/config.ts`](src/config.ts). The plan and build
order are in [`plans/`](plans/).
