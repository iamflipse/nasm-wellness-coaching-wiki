# NASM Wellness Coaching — Wiki

Personal study notes on NASM's **Principles of Wellness Coaching** video course (73 lessons), condensed into 24 concept pages plus a glossary and a lesson map.

The course is NASM's copyrighted material. This private repo holds summaries in my own words with only short quotes (under about 25 words each). **The lesson transcripts are not reproduced.**

## Contents

- **Foundations of coaching**: wellness coaching and OPSISE, growth mindset, coach's role and relationship
- **Client psychology**: locus of control, negativity bias, self-compassion and shame, self-efficacy, get-to vs have-to, flexibility, upward spirals
- **Movement**, **positive psychology, stress and recovery**, **sleep**, **social wellness**
- **Nutrition**: dietary patterns, eating and emotions, weight-neutral and intuitive eating, supplements
- **Coaching skills**: motivational interviewing (OARS, DARN, CAT), coaching mindset, session structure, cultural awareness, coaching philosophy
- **Wellness plans**: creating, monitoring, changing, derailers
- [Glossary](src/glossary.md) · [Lesson map](src/lesson-map.md) (all 73 lessons → pages)

## Layout

- `src/` — markdown source pages
- `book/` — mdbook-generated static site
- `tools/mdbook` — mdbook v0.4.21 binary (aarch64 Linux)

## Rebuild

```sh
./tools/mdbook build -d book
git add -A && git commit -m "update" && git push origin main
```

Private copy viewable on the tailnet at `https://spark-c848.tail773700.ts.net:8444/out/nasm-wiki/` (copy `book/` to `~/teleprompter/out/nasm-wiki/`).
