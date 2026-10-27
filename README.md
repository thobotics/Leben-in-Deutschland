# Leben in Deutschland

A reusable question bank for short, flexible chat practice.

- **310 questions:** 300 general questions and 10 for Baden-Württemberg.
- Four answer choices and one answer key per question.
- **25 cached image files** covering all 13 picture questions in this set.
- Stable IDs: `DE001`–`DE300`, `BW01`–`BW10`.

## Files

- [questions.json](questions.json): German questions, choices, solutions and source metadata.
- [images/](images/): the picture assets referenced by the question bank.

Image paths are relative to the repository root. Answer labels are A, B, C
and D. Every image record includes its SHA-256 and dimensions.

## Chat practice

Say **go** in the tutoring chat to start or resume a short session. An optional
time budget such as "go, 2 minutes" keeps it small. Questions are presented one
at a time, with brief explanations and useful German vocabulary.

Personal answers, mistakes, review dates and learning progress are kept
separately in the private study log, outside this public repository.

## Sources and attribution

The questions and answer key were obtained from
[YehorAltshuler/bamf-lid-dataset](https://github.com/YehorAltshuler/bamf-lid-dataset),
dataset version **2026-10-26.101410**, generated from the
official [BAMF catalogue](https://www.bamf.de/SharedDocs/Anlagen/DE/Integration/Einbuergerung/gesamtfragenkatalog-lebenindeutschland.pdf?__blob=publicationFile)
and [BAMF Online-Testcenter](https://oet.bamf.de/ords/oetut/f?p=534:1:0).
This repository is an independent study copy, not an official BAMF publication.

Twenty-three pictures retain the source extraction bytes. The pictures for
DE070 and DE130 use equivalent smaller study copies from
[abdullahbutt/leben-in-deutschland-test](https://github.com/abdullahbutt/leben-in-deutschland-test),
commit `ebd34bc936d2e548f8869f5ba97266b581839a0d`.
That source states CC BY-NC 4.0 for its content. Original photo credits are
retained in the question text. Source rights and image credits remain with
their respective holders; no blanket licence is asserted over third-party material.

The source PDF hash, dataset version, source paths and image hashes are
recorded in questions.json. This is a saved snapshot; lessons use it without
downloading the original catalogue again.

## Validation

The prepared bank was checked for 310 unique IDs, exactly 300 general and
10 Baden-Württemberg questions, four non-empty options and one valid answer
label per question. Every referenced image was decoded and its dimensions
checked; the 23 original extraction images also match their supplied hashes.
