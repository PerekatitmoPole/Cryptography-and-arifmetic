# Cryptography and Arithmetic

Конспекты и материалы по курсу **«Криптография и арифметика»**;

---

### Конспекты (PDF)
- Лекция 1 — [PDF](out/lecture-01.pdf) · [TeX](Tex/lecture-01.tex)
- Лекция 2 — [PDF](out/lecture-02.pdf) · [TeX](Tex/lecture-02.tex)
- Лекция 3 — [PDF](out/lecture-03.pdf) · [TeX](Tex/lecture-03.tex)

### Исходники (рукописные)
- Лекция 1 — [PDF](Исходники/lecture-01/)
- Лекция 2 — [PDF](Исходники/lecture-02/)
- Лекция 3 — [PDF](Исходники/lecture-03/)

### Материалы курса
- [Темы для докладов](Материалы%20курса/Темы%20для%20докладов.pdf)
- [Курс алгебры, Винберг](Материалы%20курса/Курс%20Алгебры%20Винберг.pdf)
- [Group theory, Milne](Материалы%20курса/Group%20theory.pdf)

---

## Сборка (LaTeX)

Сборка через `pdflatex`:

```bash
 pdflatex -interaction=nonstopmode -halt-on-error -file-line-error -output-directory=out "Tex\lecture-0*.tex"