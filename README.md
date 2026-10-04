# Steady TEST preview

TEST copy of Steady (example data, not a real budget), built from `browc814-spec/steady` branch `v5-phase0`
with `npm run build:preview` (VITE_PREVIEW=1, base `/steady-test/`).

- Uses only `steadytest:` localStorage keys; never reads or writes the live app's `steady-*` keys.
- Sync is off (no setup links, no Apps Script requests). No service worker.

Served at https://browc814-spec.github.io/steady-test/
