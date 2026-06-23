# AI Solutions Studio — Builder Stories (Concept Prototype)

A working sketch of how the **California Community Colleges AI Solutions Studio** could present its apps — not as a static inventory, but as stories, the way they're meant to be read:

> **Person → Story → App (root) → Lineage → Collection**

It's a single, self-contained, scrolling editorial page: five real Super-Trainer builders, each in their own voice, with an interactive **"apply across contexts"** panel that shows what stays (the *root* / base-sauce) and what you'd swap to adapt it for your college. It closes on the bigger picture — how individual apps ladder up to system change.

- **Ryan Hitch** — Chaffey College — *UDL Assessment Bot*
- **My-Linh Nguyen** — Cuyamaca College — *Major / Pathway Generator* (a real remix of Cleve Barton's SMC app)
- **Khrystyn Pamintuan** — Cuyamaca College — *Ask CeCe* (with My-Linh, a counseling collection forming at one college)
- **Sally Baldwin** — Foothill College — *Responsible-AI Ecosystem* (a preview of V2 collections)
- **Jacob Jun** — Hartnell College — *OscarBot* (a student "front door")

No build step, no dependencies.

---

## View it locally

Open `index.html` in any browser.

---

## Headshots

All five headshots are in **`assets/`**, optimized for the web:

| Builder | File |
|---|---|
| Ryan Hitch | `assets/ryan-hitch.jpg` |
| My-Linh Nguyen | `assets/my-linh-nguyen.jpg` |
| Khrystyn Pamintuan | `assets/khrystyn-pamintuan.jpg` |
| Sally Baldwin | `assets/sally-baldwin.png` |
| Jacob Jun | `assets/jacob-jun.jpg` |

To swap a photo, replace the file with the same name and refresh. (If a file is ever missing, its frame just stays empty — the page still renders.)

---

## Publish to GitHub Pages (for cohort reactions)

1. Create a new repository on GitHub (e.g. `ai-solutions-studio-prototype`).
2. Upload everything in this folder (`index.html`, `README.md`, the `assets/` folder).
3. In the repo: **Settings → Pages → Source: Deploy from a branch**, pick `main` and `/ (root)`, **Save**.
4. After ~1 minute your live link is `https://<your-username>.github.io/ai-solutions-studio-prototype/`.
5. Share it with the cohort.

> Command line, from this folder:
> ```sh
> git init && git add . && git commit -m "AI Solutions Studio prototype"
> git branch -M main
> git remote add origin https://github.com/<your-username>/ai-solutions-studio-prototype.git
> git push -u origin main
> ```

---

## Notes

- **Design:** a story-led editorial layout (inspired by long-form editorial sites), with a sticky contents nav and one interactive moment per story.
- **Brand:** Playlab v2.0 — cream paper, ink, one yellow highlighter (the selected context chip). Instrument Sans / Spline Sans Mono / EB Garamond.
- **Content** is drawn from the builders' own story bios; app buttons link to live Playlab projects.
- A concept prototype for internal reaction, not a production product.
