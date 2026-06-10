# Free Pet Pantry

**Take what you need, leave what you can.**

The website for Free Pet Pantry — a free pet food and essentials pantry for pet parents in need, located on the 200 block of Highland Ave, East Pittsburgh, PA. A project of The Fence Hole Group and a first step toward [Vet Van Fleet](https://vetvanfleet.com), a nonprofit initiative bringing free veterinary care to pets everywhere.

## What's here

- `index.html` — the entire site (single file, no build step, no dependencies).

## Run it locally

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

This is a static site, so it works on any static host. For Vercel: import this repo and deploy with default settings (no framework, output = root).

## Mailing list — already wired

The "Stay in the loop" form posts directly to the **Fence Hole Hub** (your own Supabase-backed
mailing list system) tagged `brand=freepetpantry`. No Mailchimp needed. See the `fencehole-hub`
folder's `SETUP.md` for how to send campaigns and finish the one-time Resend setup.

## Before you go live

1. **Donation link** — the Donate button currently opens an email to Team@FenceHole.com. Swap in a real donation/fundraising link when ready.
2. **Contact email** — make sure `Team@FenceHole.com` is set up to receive mail.

## Privacy note

By design, the site never shows the exact street number. It references the **200 block of Highland Ave** and the map link opens the general street/block, not a pin on the door. The exact spot is shared with visitors when they're nearby.

---

© The Fence Hole Group
