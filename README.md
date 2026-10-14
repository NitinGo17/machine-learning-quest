# Machine Learning Quest

An interactive, gamified, **offline** website that teaches machine learning — built entirely from two lecture decks by **Payal Gupta**: *The Basics of Artificial Intelligence and Machine Learning* and *Machine Learning*.

## Live site

https://nitingo17.github.io/machine-learning-quest/

## What's inside

- **10 topic levels + a Boss Level**, unlocking in order: AI/ML/Deep Learning · ML vs Traditional Programming · Types of Learning · Data & Model Vocabulary · Model Evaluation · The ML Pipeline · Regression · Classification · Unsupervised Learning & Clustering · Neural Networks & Deep Learning · Boss quiz.
- **A clickable, colour-coded SVG flowchart for every level** — including the full model-development pipeline and the model-selection tree.
- **Hand-drawn SVG diagrams** (no external images): the ML family tree, traditional statistics vs ML, supervised vs unsupervised vs semi-supervised, underfit/good/overfit, clustering vs association, and an artificial neural network.
- **4 live canvas demos**: linear regression (drag points), K-means clustering (change K, step the loop), a KNN decision boundary (drop points), and underfitting vs overfitting (complexity slider).
- **Per level**: explanation, analogies, key terms, flashcards, a drag-and-drop challenge and a 4–6 question quiz (multiple choice, true/false, fill-in-the-blank) with instant feedback.
- **Gamification**: XP, player levels, hearts, a daily streak, 12 badges and a progress dashboard (XP over time, accuracy per topic, weak topics).
- **Light/dark mode**, mobile-friendly layout, and progress saved in the browser via `localStorage`.

## Running it

It is a single self-contained HTML file. Just open `index.html` in a browser — no build step, no server, no network needed.

## Editing the content

All lessons, quizzes, flashcards and flowcharts live in a commented `LEVELS` array inside the `<script>` of `index.html`. Change the values there and the engine picks them up.

## Sourcing

Every fact, definition, flowchart and diagram on the page is drawn from the two decks above; nothing was added from outside them. The two decks do not cover gradient descent, backpropagation or learning rates, so those are deliberately absent.

## License

MIT
