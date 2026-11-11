# Fieldglass Ops

Research operations desk: fact-vs-allegation split-track, controlled relationship graph, Drive ingestion manifest summary, license triage heuristics.

## Live deploy (Vercel via GitHub — no Grok popup)

1. Open https://vercel.com/new while logged in with **GitHub**
2. Import `cantgetalonggta-png/fieldglass-ops`
3. Framework preset: **Other** (static)
4. Deploy

Optional GitHub Pages: Settings → Pages → Deploy from branch `main` / root.

## Local

```bash
npx serve -l 8080 .
```

## Policy

- Allegations stay labeled until a primary or audited secondary record supports the exact statement
- Promotion requires `DIRECT_PRIMARY_RECORD` or `SECONDARY_REPORTING` + non-empty pinpoint locator
- `security-reference-excluded` topics are filename-only and are not operationalized as attack tooling
- Demo data is fictional

Drive folder ingested (catalog only): `1YjyZIolmhISxjag_0SJgeDCpIZSoGAt_` (220 unique files).
