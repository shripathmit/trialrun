# TrialRun

**Clinical trials, translated into human.**

TrialRun is a concept MVP: a chat-first matcher that helps patients describe their
condition in plain words and find clinical trials they're actually eligible for —
then walks them to enrollment. Sponsors pay per enrolled patient; patients never pay.

## What's here

- `index.html` — the whole app. Landing page + interactive demo matcher
  (condition → location → age → diagnosis → ranked trial matches with
  "why you match" reasons and a mock pre-screening flow).
- The demo runs on a small fictional dataset modeled on public trial registries
  (clearly labeled "Demo data" / "demo listing" in the UI). It stores nothing
  and sends nothing anywhere.

## Run locally

```bash
cd trialrun
python3 -m http.server 8080
# open http://localhost:8080
```

(Opening `index.html` directly from disk works too.)

## Deploy

Static site — any static host works. Currently deployed via GitHub Pages from
the `main` branch root.

## Disclaimer

Demo only. Trial listings are fictional samples for demonstration, not medical
advice. Always consult a physician about clinical trials.
