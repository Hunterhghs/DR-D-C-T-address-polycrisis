# The Polycrisis Is a Diffusion Problem — Digital Report

A one-page digital report by **Hunter Hughes**, published by **H Heuristics**, on how diffusion of innovations, economic convergence, and the clean transition unwind the coupled global polycrisis of pollution, warming, and poverty.

- **Live:** https://pdp.hheuristics.com/
- **Repository:** https://github.com/Hunterhghs/DR-D-C-T-address-polycrisis
- **Format:** Single self-contained `index.html` (inline CSS + JS, Chart.js via CDN)
- **Engine:** Built with the Veles pipeline (Fable-5 × DeepSeek hybrid)
- **Custom domain:** `CNAME` → `pdp.hheuristics.com`

## Contents

1. Executive summary
2. The polycrisis is one system, not a portfolio of crises
3. Diffusion does the heavy lifting
4. Convergence is the poverty exit ramp
5. The clean transition is the coupling mechanism
6. The DR-D-C-T loop compounds
7. The honest counter-case
8. Implications
9. Sources & notes

The page embeds five Chart.js figures (coupled polycrisis dashboard, clean-tech cost deflation, S-curves in motion, convergence scatter, clean-vs-fossil investment), a four-node DR-D-C-T loop diagram, two data tables, and a binding-term close.

## Deploy via GitHub Pages

The `CNAME` file maps this repository to `pdp.hheuristics.com`. Ensure the DNS record for `pdp` points to GitHub Pages (a `CNAME` to `Hunterhghs.github.io`).

1. Push this repository to GitHub (default branch `main`).
2. On GitHub: **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**, select branch `main`, folder `/ (root)`.
4. Save. GitHub will detect the `CNAME` file and serve the site at:
   `https://pdp.hheuristics.com/`
5. Optionally enable **Enforce HTTPS** under Settings → Pages.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

---

© 2026 Hunter Hughes · H Heuristics — Research & Advisory
