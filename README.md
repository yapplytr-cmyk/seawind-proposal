# Nautico × Seawind — Pitch Demo

A single-file animated pitch site, built for Seawind Europe.

## Preview locally

Option 1 — just open it:
```
open index.html
```

Option 2 — run a tiny local server (nicer, no CORS weirdness):
```
python3 -m http.server 4173
# → http://localhost:4173
```

## Deploy to Vercel (once approved)

1. `git init && git add . && git commit -m "Seawind pitch demo"`
2. Push to a new GitHub repo
3. Import into Vercel — it's already configured via `vercel.json`
4. No build step, static deploy
