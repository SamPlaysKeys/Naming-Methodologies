# Homelab Naming Methodology

This repo holds a talk + slide deck about one oddly important topic: what you name your homelab boxes and services.

Yes, it’s “just names.” Also: bad names are how you end up with `server2_final_rebuild` three years later and no idea what it does.

---

## What this is

- A PPTX that walks through different naming styles:
  - Default (`Sam's iPhone`)
  - Hardware‑based (`RPi1`, `ThinkStation4`)
  - Purpose‑based (`backup01`, `docker-host3`)
  - Fully themed / silly (`Odin`, `Canary`, etc.)
- Some light psychology on why naming things makes you more likely to maintain them.
- A gentle reminder that enterprise naming schemes are great… for enterprises, not necessarily your one‑rack closet or collection or raspberry pis.

---

## What I learned

- Names are **anchors**: once you name something, you care a bit more about it and are more likely to keep it alive.
- Enterprise naming is **brilliant for teams and auditors**, but feels like overkill when it’s just you and three nodes pretending to be a data center.
- Fun/themed names are great, you need to document what they actually do.
- Splitting it into:
  - **Device name** (fun / personal)
  - **Service name** (boring, descriptive DNS)
  seems to be the sweet spot.

---

## The actual conclusion

There is no **One True Naming Scheme**.

The best option is whatever:
- You’ll **actually stick with**, and
- Won’t make you swear at yourself six months from now when you’re remoting into something at 1 AM.

---

## Files

- `Homelab-Naming-Ideology.pptx` – the slides.
- `resources.md` – articles, forum threads, and references that fed into this.

## Attribution
If you steal any of this for your own lab or your own talk, that’s a feature, not a bug. Just give me some credit and we're good.

## License <-- Legal Stuff
<a href="https://example.com">Naming Methodologies</a> © 2026 by <a href="https://example.com">Sam Fleming</a> is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a>
