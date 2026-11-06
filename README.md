# CV Reviewer & ATS Check

A browser-based resume reviewer that scores a CV against **16 hiring standards**,
estimates how an **applicant tracking system** will parse it, and returns specific,
actionable fixes rather than generic advice.

Single self-contained HTML file. No build step, no backend — **your resume never leaves
your browser.**

Built by **Tosin Aina**.

---

## What it does

- Scores the resume against 16 standards covering structure, impact statements,
  quantification, keyword coverage, formatting and length
- Produces an **ATS parse score** — flagging the formatting choices that cause
  tracking systems to drop or mangle content
- Returns **specific rewrites**, not "add more detail"
- Remembers the resume between sessions in local browser storage

## Running it

Open `index.html` in a browser. That's the install.

```
git clone https://github.com/Tozino22/cv-reviewer.git
cd cv-reviewer
start index.html     # Windows
open  index.html     # macOS
```

Or use the hosted version via GitHub Pages.

## Privacy

Everything runs client-side. The resume text is held in the page and in your browser's
own local storage. Nothing is uploaded, logged or transmitted.

## Licence

MIT.
