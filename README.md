# Notes BA4

LaTeX notes for the BA4 semester.

---

## Build

Compile all subjects and sync PDFs to `_overview/`:

```bash
python build.py
```

Compile specific subjects:

```bash
python build.py algo
python build.py algo iml sigproc
```

---

## Exam Instructions

| Subject | Allowed |
|---|---|
| Computer Systems | 4 double-sided A4 sheets, any format |
| Signal Processing | 2 double-sided A4 sheets, handwritten only |
| Algorithms I | 1 double-sided A4 sheet, any format |

---

## Subjects

### Computer Systems — `compsys/`
- [Cheat sheet](_overview/compsys/cheatsheet.pdf)

### Signal Processing — `sigproc/`
- [Cheat sheet](_overview/sigproc/cheatsheet.pdf)

### Algorithms I — `algo/`
- [Cheat sheet](_overview/algo/cheatsheet.pdf)
- [Course notes](_overview/algo/course.pdf)
- [Condensed algos](_overview/algo/algos_condensed.pdf)

### Intro to Machine Learning — `iml/`
- [Cheat sheet](_overview/iml/cheatsheet.pdf)
- [Course notes](_overview/iml/course.pdf)
- [Python notes](_overview/iml/python_raw_notes.pdf)

---

## Setup

[LaTeX environment setup tutorial](https://www.youtube.com/watch?v=4lyHIQl4VM8)

---

## Structure

```
notes_ba4/
├── _overview/      # Compiled PDFs, one folder per subject
├── _shared/        # Shared LaTeX style files
├── algo/
├── iml/
├── sigproc/
└── compsys/
```

Each subject folder contains `.tex` sources; run `build.py` to recompile.

---

## Authors

**Salim Chaoui El Faiz** — [GitHub](https://github.com/SalimThePokemonMaster)

**Sami Kabbaj** — [GitHub](https://github.com/SamiPro206)
