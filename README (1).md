# 9702 Physics Notes

A free, interactive revision website for **Cambridge International AS & A Level Physics (9702)**. It covers every topic in the syllabus with clear notes, the key equations, worked examples, simulations you can play with, and exam-style questions with mark schemes.

The whole site is a single HTML file. There is nothing to install and no build step: open it in a browser, or host it on GitHub Pages.

---

## Features

- **All 25 syllabus topics** in two tabs: AS Level (topics 1–11) and A Level (topics 12–25).
- **108 key equations**, each tagged **"On formulae page"** (printed on the exam paper) or **"Learn it"** (must be memorised), checked against the official 9702 Data and Formulae list.
- **47 multiple-choice questions** in the style of Paper 1. They mark themselves instantly and explain the answer.
- **62 structured questions** in the style of Papers 2 and 4. Each has a lined answer box and a mark scheme written with the codes Cambridge examiners use (**B1, M1, A1, C1**).
- **Worked examples** for every calculation-based topic.
- **8 interactive simulations:**
  | Simulation | Topic |
  |---|---|
  | Projectile motion | 2. Kinematics |
  | Stationary waves (strings, closed pipes, open pipes) | 8. Superposition |
  | Diffraction grating | 8. Superposition |
  | Potential divider with an LDR or thermistor | 10. D.C. circuits |
  | Oscillations with light, critical and heavy damping | 17. Oscillations |
  | Capacitor charging and discharging | 19. Capacitance |
  | Photoelectric effect | 22. Quantum physics |
  | Random radioactive decay | 23. Nuclear physics |
- **Search** across every topic and section.
- **Progress tracking**: mark topics as revised (saved in your browser only).
- **Light and dark themes**, a layout that works on phones, and keyboard navigation.
- **Data page**: the physical constants printed on the exam papers, and an explanation of how the marks work.

## Syllabus coverage

The content follows the Cambridge 9702 syllabus for **2025–2027**. The **2028–2030** syllabus keeps the same 25 topics with no significant changes to teaching, so the site applies to both.

| AS Level | A Level |
|---|---|
| 1. Physical quantities and units | 12. Motion in a circle |
| 2. Kinematics | 13. Gravitational fields |
| 3. Dynamics | 14. Temperature |
| 4. Forces, density and pressure | 15. Ideal gases |
| 5. Work, energy and power | 16. Thermodynamics |
| 6. Deformation of solids | 17. Oscillations |
| 7. Waves | 18. Electric fields |
| 8. Superposition | 19. Capacitance |
| 9. Electricity | 20. Magnetic fields |
| 10. D.C. circuits | 21. Alternating currents |
| 11. Particle physics | 22. Quantum physics |
| | 23. Nuclear physics |
| | 24. Medical physics |
| | 25. Astronomy and cosmology |

## Getting started

### Open it locally

Download `index.html` and double-click it. It opens in any modern browser (Chrome, Edge, Firefox, Safari).

### Host it on GitHub Pages

1. Create a new repository and upload `index.html` (rename `physics-9702.html` to `index.html` if needed) and this `README.md`.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and the `/ (root)` folder, then **Save**.
4. After a minute or two, the site is live at `https://<your-username>.github.io/<repository-name>/`.

### Linking to a topic

Every topic and section has its own link, so you can send students straight to it:

```
https://<your-username>.github.io/<repository-name>/#as-6     → AS topic 6, Deformation of solids
https://<your-username>.github.io/<repository-name>/#a-22     → A Level topic 22, Quantum physics
```

`as-0` and `a-0` are the overview pages for each level.

## How it works

- Everything (content, styles and scripts) is in one self-contained HTML file with no frameworks or libraries.
- Equations are rendered as plain HTML and CSS, so they display instantly and work offline.
- Simulations are drawn with the HTML Canvas API and follow the light or dark theme.
- Fonts (Figtree and STIX Two Text) load from Google Fonts. Offline, the page falls back to system fonts and still works.
- Progress, the last topic visited and the theme choice are stored in the browser's `localStorage`. Nothing is sent to a server.

## Accuracy

Every numerical answer in the worked examples and mark schemes was recomputed independently in code before release. If you spot an error in the physics, an answer or a mark scheme, please [open an issue](../../issues) with the topic and question number.

## Contributing

Contributions are welcome, especially new questions, corrections and translations.

1. Fork the repository and create a branch.
2. Make your change in `index.html`. Each topic is an `<article>` with an id such as `as-7` or `a-19`.
3. Open a pull request describing what you changed and why.

## Disclaimer

This is an independent revision resource. It is **not affiliated with, endorsed by or produced by Cambridge University Press & Assessment**. "Cambridge International" and the syllabus code 9702 are used only to identify the course the notes cover.

The questions are original, written in the style of 9702 examination papers. They are **not** copies of past papers. For official past papers, mark schemes and the current syllabus, use the [Cambridge International website](https://www.cambridgeinternational.org/programmes-and-qualifications/cambridge-international-as-and-a-level-physics-9702/) or ask your teacher.

## License

No license has been chosen yet. Until one is added, all rights are reserved by the repository owner. To let others reuse and adapt the material, add a `LICENSE` file; for example, [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) suits educational content.
