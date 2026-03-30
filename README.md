# Cryptography and Arithmetic

Конспекты и материалы по курсу **«Криптография и арифметика»**;

---

### Конспекты (PDF)
- Лекция 1 — [PDF](out/lecture-01.pdf) · [TeX](Tex/lecture-01.tex)
- Лекция 2 — [PDF](out/lecture-02.pdf) · [TeX](Tex/lecture-02.tex)
- Лекция 3 — [PDF](out/lecture-03.pdf) · [TeX](Tex/lecture-03.tex)
- Лекция 4 — В разработке.
- Лекция 5 — В разработке.
- Лекция 6 — В разработке.

### Исходники (рукописные)
- Лекция 1 — [PDF](Исходники/lecture-01.pdf)
- Лекция 2 — [PDF](Исходники/lecture-02.pdf)
- Лекция 3 — [PDF](Исходники/lecture-03.pdf)
- Лекция 4 — [PDF](Исходники/lecture-04.pdf)
- Лекция 5 — [PDF](Исходники/lecture-05.pdf)
- Лекция 6 — [PDF](Исходники/lecture-06.pdf)

### Материалы курса
- [Темы для докладов](Материалы%20курса/Темы%20для%20докладов.pdf)
- [Курс алгебры, Винберг](Материалы%20курса/Курс%20Алгебры%20Винберг.pdf)
- [Group theory, Milne](Материалы%20курса/Group%20theory.pdf)
- [Курс арифметики](Материалы%20курса/Курс_арифметики.pdf)
- [Алгебраическая геометрия](Материалы%20курса/Алгебраическая_геометрия.pdf)

---

## Сборка (LaTeX)

Сборка через `pdflatex`:

```bash
 pdflatex -interaction=nonstopmode -halt-on-error -file-line-error -output-directory=out "Tex\lecture-0*.tex"