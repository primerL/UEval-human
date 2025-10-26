# UEval Human Evaluation

This directory contains the GitHub Pages bundle for UEval's single-prompt human evaluation interface.

## 📊 Dataset Overview
- Total samples: **100**
- Domains available: Art, Diagram, Exercise, Life, Paper, Space, Tech, Textbook

## 🔀 Recommended Splits

### 3 Evaluators
- Evaluator 1: 34 samples to evaluate (art(4), diagram(4), exercise(4), life(4), paper(4), space(4), tech(4), textbook(6))
- Evaluator 2: 33 samples to evaluate (art(4), diagram(4), exercise(4), life(4), paper(4), space(3), tech(4), textbook(6))
- Evaluator 3: 33 samples to evaluate (art(4), diagram(4), exercise(4), life(4), paper(4), space(3), tech(4), textbook(6))

### 4 Parts (easy to assign)
- Part 1: 25 samples to evaluate (art(3), diagram(3), exercise(3), life(3), paper(3), space(3), tech(3), textbook(4))
- Part 2: 25 samples to evaluate (art(3), diagram(3), exercise(3), life(3), paper(3), space(3), tech(3), textbook(4))
- Part 3: 25 samples to evaluate (art(3), diagram(3), exercise(3), life(3), paper(3), space(2), tech(3), textbook(5))
- Part 4: 25 samples to evaluate (art(3), diagram(3), exercise(3), life(3), paper(3), space(2), tech(3), textbook(5))

### 5 Evaluators
- Evaluator 1: 20 samples to evaluate (art(3), diagram(2), exercise(3), life(2), paper(2), space(2), tech(2), textbook(4))
- Evaluator 2: 20 samples to evaluate (art(3), diagram(3), exercise(2), life(2), paper(3), space(2), tech(2), textbook(3))
- Evaluator 3: 20 samples to evaluate (art(2), diagram(3), exercise(2), life(3), paper(3), space(2), tech(2), textbook(3))
- Evaluator 4: 20 samples to evaluate (art(2), diagram(2), exercise(2), life(3), paper(2), space(2), tech(3), textbook(4))
- Evaluator 5: 20 samples to evaluate (art(2), diagram(2), exercise(3), life(2), paper(2), space(2), tech(3), textbook(4))

### By Domain
- 🎨 Art Domain: 12 samples
- 📊 Diagram Domain: 12 samples
- 💪 Exercise Domain: 12 samples
- 🌱 Life Domain: 12 samples
- 📄 Paper Domain: 12 samples
- 🚀 Space Domain: 10 samples
- 💻 Tech Domain: 12 samples
- 📚 Textbook Domain: 18 samples

## 🚀 How to Deploy
1. `cd UEval-human-deploy`
2. `git init && git add . && git commit -m "UEval human evaluation portal"`
3. `git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git`
4. `git branch -M main`
5. `git push -u origin main`
6. Enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root)

Your site will be available at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## 📝 Evaluator Workflow
1. Open the portal and pick your assigned part or domain.
2. Review each sample and rate all six criteria (0-5 scale).
3. Provide concise reasoning per criterion.
4. Hit “Download All Evaluations” to export results as JSON.
5. Send the JSON back to the coordinator.

Progress is saved locally in the browser, so you can pause and resume anytime.
