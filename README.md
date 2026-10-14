# GrowthHouse — Security Awareness Training

Public staff Security Awareness Training site for **GrowthHouse**. Derived from
the private template `abdula-dan/CoPilotCode` (wired as the `upstream` remote).

- Live site: `docs/index.html` — self-contained, no build step.
- Branding: `const CUSTOMER = "GrowthHouse";` near the top of `docs/index.html`.

## Publish (GitHub Pages)

Settings → Pages → Build and deployment → Source: **Deploy from a branch**,
Branch: **main** / **/docs**. The link will be:

`https://abdula-dan.github.io/growthhouse-security-awareness/`

## Pull template improvements later

```sh
git fetch upstream
git merge upstream/main   # keep the CUSTOMER = "GrowthHouse" line if it conflicts
git push origin main
```

## Reporting

Staff complete the topics and click **View my results → Copy summary**; the
summary is plain text (name, organisation = GrowthHouse, date, per-topic
pass/score) to paste into an email or ticket for management.
