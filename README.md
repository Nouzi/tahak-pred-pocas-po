# Ťahák · Pred · Počas · Po

Ťahák k workshopu o práci s AI agentmi (Týždeň učenia, FPV UCM, 12. 10. 2026).
Tri vety na kopírovanie, odovzdávka v troch krokoch, subagenti a príkazy pre skills.

## Súbory

- `index.html` — celá stránka (jeden súbor, bez build kroku)
- `tahak-a4.pdf` — verzia na tlač
- `.nojekyll` — GitHub Pages súbory nespracúva cez Jekyll

## Zverejnenie cez GitHub Pages

```bash
cd tahak-pred-pocas-po
git init
git add .
git commit -m "Ťahák Pred · Počas · Po"
gh repo create tahak-pred-pocas-po --public --source=. --push
```

Potom na GitHube: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main`, priečinok `/ (root)` → Save.**

Stránka bude o 1–2 minúty na adrese `https://<váš-github-účet>.github.io/tahak-pred-pocas-po/`.

## Zmena odkazu na formulár

V `index.html` sú dve miesta: atribút `href` pri `id="feedback-link"` a premenná `FEEDBACK_URL` v skripte na konci súboru.

## Zdroje

Obsah vychádza z [aihero.dev](https://www.aihero.dev/) (Matt Pocock) a knižnice [mattpocock/skills](https://github.com/mattpocock/skills).
