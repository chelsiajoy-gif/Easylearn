# EasyLearn CAPM Playground

A bright, interactive visual lesson explaining the Capital Asset Pricing Model (CAPM) through a roller-coaster metaphor. Learners can adjust the risk-free rate, expected market return, and beta, then see the formula, return estimate, and animated ride respond in real time. A one-tap quiz checks the core idea.

## Deploy to Netlify

Import `chelsiajoy-gif/Easylearn` from GitHub. This is a static site with no dependencies or build step:

- **Build command:** leave blank
- **Publish directory:** `.`

The included `netlify.toml` sets the publish directory. The complete experience is in `index.html` and uses inline SVG, CSS, and JavaScript.

## Learning note

CAPM is introduced as a simplified expected/required-return model: `E(R) = Rf + β × (Rm − Rf)`. The interface explains that CAPM is an estimate, not a guaranteed return or investment recommendation, and that beta measures market sensitivity rather than every type of risk.
