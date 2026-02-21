# Cryptography and Arithmetic

Конспекты и материалы по курсу **«Криптография и арифметика»**;

---

### Конспекты (PDF)
- Лекция 1 — [PDF](out/lecture-01.pdf) · [TeX](Tex/lecture-01.tex)
- Лекция 2 — [PDF](out/lecture-02.pdf) · [TeX](Tex/lecture-02.tex)

### Исходники (рукописные)
- Лекция 1 — [PDF](Исходники/lecture-01/)
- Лекция 2 — [PDF](Исходники/lecture-02/)

### Темы для докладов
- [Темы для докладов (PDF)](Темы%20для%20докладов.pdf)

---

## Сборка (LaTeX)

Сборка через `latexmk`:

```bash
latexmk -pdf -interaction=nonstopmode -outdir=out Tex/main.tex