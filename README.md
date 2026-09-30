# azvote-locations

Public civic voting-location data for [azvote.org](https://azvote.org).

This repository hosts a **stable** `locations.json` that the azvote.org Where-to-Vote finder fetches. Voting Locations overwrites `locations.json` on a twice-daily cadence (about **11:00am** and **5:30pm** America/Phoenix) so the site can keep a fixed raw URL without editing Wix Studio.

## Stable raw URL

After this repo is public under `ezazorg`:

```
https://raw.githubusercontent.com/ezazorg/azvote-locations/main/locations.json
```

(If the repo name ends up as `azvote-org-locations`, substitute that name.)

## Contents

- `locations.json` — Arizona early-voting / election-day locations (JSON). Includes `generated_at` / `last_checked` timestamps when present.
- No secrets. Do not commit tokens, Wix credentials, or private keys.

## License

Public domain / CC0 — see `LICENSE`.
