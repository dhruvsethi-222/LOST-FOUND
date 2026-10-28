# The Solution Lost and Found

A web-based lost and found system for the university: students and staff report what they have lost or found, and the campus security office verifies every claim before an item is handed back.

DBT 1305 Web Application Development · team project · Group A · team **The Solution**

| Member | Admission number | GitHub | Role |
| --- | --- | --- | --- |
| Dhruv Sethi | 227034 | dhruvsethi-222 | Member 1 — shared stylesheet blocks, first push |
| Jerry Mudola | 226695 | Sixthenexus0 | Member 2 |

## The public pages

Every page answers one question, and every page has the same header, nav, aside and footer.

| Page | The question it answers | Owner |
| --- | --- | --- |
| `index.html` | What is this, and is it for me? | Dhruv Sethi |
| `about.html` | Who is behind it, and can I trust them? | Dhruv Sethi |
| `contact.html` | How do I reach a person? | Dhruv Sethi |
| `how-it-works.html` | What happens after I report, and what do I bring to collect? | Dhruv Sethi |
| `found-items.html` | Has anyone handed in my item? | Jerry Mudola |
| `report-lost.html` | How do I report something I lost? | Jerry Mudola |
| `report-found.html` | I found something. What do I do? | Jerry Mudola |
| `register.html` | How do I get an account? | Jerry Mudola |

The forms use `action="#"` until the server arrives, so they do not send anything yet.

## The private side (not built here)

These pages show one person's own data, so they are not public and are left for later: logging in and the verification email; *My reports and claims* and claim status for students and staff; the claim form; match alerts; and the security office's pages for pending claims, ranked matches, verifying a claim, recording a hand-over, disposing of expired items, managing accounts and reports. Passwords are left out of `register.html` for the same reason: logins and passwords are the next unit's work.

## House style

| Role | Colour | Used for |
| --- | --- | --- |
| main | `#14532D` deep green | header, buttons, links, headings |
| ground | `#F7FAF8` green-white | the page behind it all |
| ink | `#1F2A24` near-black | body text, the nav |
| accent | `#E07A5F` terracotta | borders and highlights only |

Headings: Merriweather, serif. Body: Open Sans, sans-serif.

## The stylesheet

One file, `css/style.css`, linked from every page, cut into five blocks with one owner each:

1. house style — Dhruv Sethi
2. layout: the grid, the nav row, the cards — Dhruv Sethi
3. `index`, `about`, `contact`, `how-it-works` — Dhruv Sethi
4. `found-items`, `report-lost`, `report-found`, `register` — Jerry Mudola
5. phone, the one media query — Dhruv Sethi — **keep this last**

Every sitting: `git pull` before you type, edit your own block only, `git commit -m "a sentence"`, `git push`.
