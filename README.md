# Constitutional Bail — Malaysian Law Study Site

A static educational website on the law of bail in Malaysia, built for a constitutional law class project by Group 7, Class B.

live site @ [https://bail-app.vecel.app](https://bail-app.vercel.app/)

## Pages

| Route | Title | Description |
|---|---|---|
| `/` | Home | Introduction, definition of bail, and site overview |
| `/legal-framework` | Legal Framework | CPC provisions and bail categories (bailable, non-bailable, unbailable) |
| `/legal-foundation` | Jurisprudence of Bail | Case law and constitutional principles |
| `/procedure` | Procedure | Step-by-step visual walkthrough of the bail application process |
| `/faq` | FAQ | Frequently asked questions |
| `/game-companion` | Game Companion | Interactive flashcard deck (6 cards) with flip animation + Vimeo video |

## Tech Stack

- **Framework:** [Astro v5](https://astro.build) (static output)
- **Styling:** Plain CSS via `src/styles/global.css`
- **Analytics:** Vercel Analytics + Speed Insights
- **Deployment:** Vercel

## Local Development

```bash
npm install
npm run dev       # dev server at localhost:4321
npm run build     # production build → dist/
npm run preview   # preview the production build
```

## Project Structure

```
src/
  components/     # Nav, Footer
  layouts/        # Layout.astro (shared shell)
  pages/          # One .astro file per route
  styles/         # global.css
public/
  images/         # Static assets (procedure step images, etc.)
```
