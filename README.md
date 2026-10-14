# chnaumankamboh.github.io

Portfolio of **Nauman Saleem**, AI/ML engineer: https://chnaumankamboh.github.io

The whole site is one static page, presented as a model training run:

- a diffusion-style sampler draws the name out of noise
- a toy attention head over the bio
- a latent-space map of the projects, each with a model card
- a small neural network that trains live in the browser (plain JavaScript, Adam)
- "Ask my model": keyword retrieval over short notes about my work
- the CV as a PDF download

Projects: [DocuChat](https://github.com/chnaumankamboh/docuchat-local-rag) ·
[Jarvis](https://github.com/chnaumankamboh/jarvis-voice-assistant) ·
[UniAttend](https://github.com/chnaumankamboh/uniattend-face-attendance)

## Editing

All text, projects and links live in the `DATA` object at the top of the script in
`index.html`. The CV is `Nauman-Saleem-CV.pdf`; `og-image.png` is the link-preview card.
No build step: push to `main` and GitHub Pages serves it.
