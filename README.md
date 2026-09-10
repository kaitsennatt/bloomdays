# Bloom Days — client packets

Static site. One folder per client packet, each a single self-contained HTML file.

- `bennet/index.html` → https://clients.bloomdays.co/bennet/
- `geiger/index.html` → https://clients.bloomdays.co/geiger/

## Setup, once
1. Push this repo to GitHub (public — see note below).
2. Settings → Pages → Source: Deploy from a branch → `main` / root.
3. `CNAME` in this repo already contains `clients.bloomdays.co`.
4. At your DNS host, add a CNAME record: `clients` → `<your-github-username>.github.io`
5. Back in Settings → Pages, tick **Enforce HTTPS** once the cert is issued (a few minutes).

## To publish a new packet
Drop `<client>/index.html` into the repo and push. Live in about a minute.

## Note on privacy
GitHub Pages sites are public to anyone with the URL, even from a private repo.
These packets contain a client's street address and photographs of their house,
which is the same exposure as a shared link. Fine for sending to the client;
don't put anything in here you would not hand to a stranger who guessed the URL.
