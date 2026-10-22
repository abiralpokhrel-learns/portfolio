# 🗞️ The Daily Abiral — Portfolio Edition

**Dateline: Butwal, Nepal** — Local data engineer prints his entire career on one page, refuses to use a framework, gets away with it.

Welcome to the source code of **[abhiralpokharel.com.np](https://abhiralpokharel.com.np)** — my personal portfolio, styled like an old-school broadsheet newspaper. Dense type, justified columns, drop caps, zero frameworks. Just hand-written HTML, CSS and vanilla JavaScript holding the presses together.

---

## 🔴 LIVE EDITION

👉 **[abhiralpokharel.com.np](https://abhiralpokharel.com.np)** — fresh off the press, updated every push.

---

## 📰 Inside today's paper

- **A living dateline** — the edition label (Morning / Afternoon / Evening / Night) follows *your* clock, not mine, and the date reprints itself daily.
- **The ticker** — Python, SQL, dbt, AWS, Spark, Airflow… all the tools, scrolling past like a stock tape.
- **Animated counters & scroll reveals** — because even newspapers deserve a little drama.
- **⭐ The Mascot** — the tiny 3D chap in the corner. He used to roam the page randomly (chaotic, annoying, fired from that job). Now he has a proper beat: **he only stands on headlines.** Scroll down and he Mario-hops down to the next heading; scroll up and he hops back up. Click him and he does a backflip and says something mildly unhinged. Staff favourite.

## 🛠️ The printing press (tech)

| Layer | Choice |
|---|---|
| Markup | One honest `index.html` |
| Styling | Hand-rolled CSS, Georgia serif, black on white — no other colours, editor's orders |
| Behaviour | Vanilla JavaScript — typing effect, dateline, counters, ticker, and one very disciplined mascot |
| Hosting | Cloudflare Pages — every push to `main` is a new edition |
| Mascot | `mascot.png` — must always travel with `index.html`, he gets lost otherwise |

## 🚀 Run it locally

No build step. No dependencies. No 400 MB of `node_modules` to apologise for.

```bash
git clone https://github.com/abiralpokhrel-learns/portfolio.git
cd portfolio
# open index.html in a browser — that's the whole tutorial
```

## ✍️ Colophon

Set in Georgia. Printed on 100% recycled pixels. No frameworks were harmed.

*— Abiral Pokhrel, Data Engineer (ETL wrangler, lakehouse enjoyer, professional bug fixer)*
