# Sir Raja Shafqat Hayat · Mathematics website

A multi-page site for Sir Raja Shafqat Hayat: Cambridge O Level Mathematics 4024, Additional Mathematics 4037 and AS & A Level Mathematics 9709, Karachi and online. Every page is one self-contained HTML file in one flat folder: styles, scripts and graphics are inside each page. No admin panel, no database.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: live graph board (turning points, tangent, area), where he teaches, the 9709 route builder, a worked answer that marks itself with M/A/B marks, online classes, enrol band |
| `courses.html` | 4024, 4037 and 9709 paper by paper, how a topic is worked through |
| `syllabus.html` | Every topic for 4024, 4037 and each 9709 paper, with a progress tracker and a filter |
| `past-papers.html` | Every session 2018–2026 for all three courses (PastPapers.co + PapaCambridge), score log with chart, exam timer with focus mode |
| `study-room.html` | Function plotter (pan, zoom, read points), quadratic workbench with full working, formula cards, sixty-second drill |
| `about.html` | His background and where he teaches |
| `contact.html` | Enrolment form that opens a ready-written WhatsApp message, FAQ |
| `404.html` | Not-found page |
| `raja-shafqat.png` | Share image for WhatsApp and social previews (1200 × 630) |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

Every page also has light and dark themes, a `/` or Ctrl K search over pages, topics and tools, an “Ask the desk” helper that answers common questions and hands the rest to WhatsApp, smooth scrolling and view transitions.

## Confirm with Sir Raja before launch

1. **WhatsApp 0339 2255800 and 0300 2029592.** Both are from his YouTube channel. To change, find and replace `923392255800` / `0339 2255800` (and the second number) across all HTML files.
2. **Where he teaches.** Titan College (A Level faculty, announced Oct 2026), Highbrow College, Heuser College, earlier Credo College, from public college posts and his Facebook profile. Confirm the list and wording.
3. **University of Karachi.** From his Facebook profile.
4. **Photo.** The studio portrait (cleaned up from his poster) is on the home hero, the about page and the share image.
5. **“How classes run”** on the courses page describes a general teaching sequence. Adjust if he works differently.
6. **Fees and timings** are never shown; every such question goes to WhatsApp.
7. **Domain.** Canonical links, sitemap and robots use `https://raja-shafqat.nexlyr.solutions`. Find and replace if you use another domain.

## Content notes

- Paper lengths and marks follow the current Cambridge 4024 (two 2-hour, 100-mark papers, Paper 1 non-calculator), 4037 and 9709 syllabuses. Topic summaries, the worked example and the drill were written for this site.
- Visitor progress (tracker, scores, drill best, theme) stays in the visitor’s browser only.

## Deploy

Upload every file to the root of a GitHub repo and import it on Vercel (Framework preset: Other, no build command). `vercel.json` turns on clean URLs, so `/courses` serves `courses.html`.

Website by Nexlyr Solutions.
