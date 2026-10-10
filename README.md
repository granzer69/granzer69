<div align="center">

![Ribhu Siripurapu](./assets/hero.svg)

**Backend & AI systems engineer** — concurrent Go/Redis services, FastAPI platforms, and applied ML wired into real APIs.

B.Tech CSE (Data Science) @ MGIT, Hyderabad · Open to AI/ML & backend internships

</div>

---

<div align="center">

![terminal](./assets/terminal.svg)

</div>

---

## Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/granzer69/Ticket-Engine">Ticket-Engine</a></h3>
      <p>High-concurrency booking path: Go API → Redis Lua atomic allocation + Streams → worker → MySQL. Docker Compose local stack and k6 load scripts.</p>
      <p><code>Go</code> · <code>Redis</code> · <code>MySQL</code> · <code>Docker</code> · <code>k6</code></p>
      <p><sub>Engineering signal: Lua-atomic allocation + idempotent retries under concurrent clients.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/granzer69/Range-Apply">Range-Apply</a></h3>
      <p>Job-intelligence / ATS discovery platform — normalize listings, dedup, and provenance. Apply automation still in progress.</p>
      <p><code>Python</code> · <code>FastAPI</code> · <code>SQL</code></p>
      <p><sub>Engineering signal: ATS discovery scaffolding (Greenhouse / Lever / Ashby) with match-engine work ongoing.</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/granzer69/CareerOS">CareerOS</a></h3>
      <p>Resume analysis platform with JWT auth, Postgres + Alembic, and Claude structured scoring. Not autonomous apply.</p>
      <p><code>FastAPI</code> · <code>React</code> · <code>Postgres</code> · <code>Claude</code></p>
      <p><sub>Engineering signal: authenticated scoring pipeline with real schema migrations.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/granzer69/fake-news-analyzer">fake-news-analyzer</a></h3>
      <p>Media-trust pipeline: Hugging Face fake-news classifier, sentiment, and heuristic trust / clickbait scores behind a FastAPI + Next.js UI.</p>
      <p><code>FastAPI</code> · <code>Next.js</code> · <code>HF</code> · <code>TypeScript</code></p>
      <p><sub>Engineering signal: classifier + heuristics composed into a single trust API.</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/granzer69/Stock-Market-Predictor">Stock-Market-Predictor</a></h3>
      <p>Keras sequence model for next-day close prediction, FastAPI inference, and a Next.js dashboard over historical CSV data.</p>
      <p><code>TensorFlow/Keras</code> · <code>FastAPI</code> · <code>Next.js</code></p>
      <p><sub>Engineering signal: training → inference API → dashboard, not a notebook-only demo.</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/granzer69/Plant-Disease-Classification">Plant-Disease-Classification</a></h3>
      <p>CNN leaf-disease classifier (38 classes) with an inference UI. Validation accuracy ~91% from training history on the held-out split.</p>
      <p><code>TensorFlow/Keras</code> · <code>Python</code></p>
      <p><sub>Engineering signal: multi-class CNN with recorded ~91% val accuracy.</sub></p>
    </td>
  </tr>
</table>

---

## Architecture — Ticket Engine

<div align="center">

![Ticket Engine architecture](./assets/arch-ticket.svg)

</div>

- **Redis owns hot allocation** — Lua script does atomic pop + idempotent user book; Streams carry the persist event.
- **Worker persists sold state to MySQL** — eventual consistency by design; durable ownership lives in MySQL.
- **Load path is instrumented** — Docker Compose stack + k6 scripts (benchmark numbers not published yet).

---

## Tech stack

**Languages** · Go · Python · TypeScript · C · Java · SQL

**Backend** · FastAPI · Redis · MySQL · Postgres

**Frontend** · React · Next.js

**AI / ML** · TensorFlow / Keras · scikit-learn · Hugging Face · Claude

**Infra** · Docker · Git · Linux · k6

---

## Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/granzer69/granzer69/output/github-contribution-grid-snake-dark.svg">
  <img alt="Contribution activity graph" src="https://raw.githubusercontent.com/granzer69/granzer69/output/github-contribution-grid-snake.svg">
</picture>

</div>

---

## Contact

- Email: [ribhusiri@gmail.com](mailto:ribhusiri@gmail.com)
- X: [@s_ribhu](https://x.com/s_ribhu)
- GitHub: [granzer69](https://github.com/granzer69)

<details>
<summary>misc</summary>

<br/>

The Earth is flat — funniest thing you'll ever hear. (It's not. I just keep the bit.)

</details>
