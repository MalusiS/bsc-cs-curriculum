# Y01 · CS50x — Introduction to Computer Science

## Course metadata

| | |
|---|---|
| Institution / platform | Harvard University (edX), free audit |
| Credits | 4 (Core Programming) |
| Term | Y1 · Term 1 (primary track) |
| Start date | 2026-09-14 |
| Planned end | 2026-12-13 (final exam) — buffer week to 2026-12-20 |
| Total hours invested | _update weekly from daily log_ |
| Certificate / completion evidence | _link or screenshot on completion_ |
| Final grade (self-graded) | _pending_ |

## Grading

| Component | Weight | Date | Score |
|---|---|---|---|
| Coursework (problem sets, labs, final project) | 30% | ongoing | — |
| Midterm (closed-book, 2h, written + code) | 30% | Sat 31 Oct 2026, 14:00–16:00 | — |
| Final (closed-book, 3h, written + code) | 40% | Sat 12 Dec 2026, 14:00–17:00 | — |

Programming-course exam format: 50% live/handwritten code · 30% debugging and analysis · 20% design and architecture. Score < 70% → review and retake within one week.

## 14-week plan

| Week | Topic | Work |
|---|---|---|
| 1 | Scratch | Lecture 0, Scratch project, K&R Ch. 1, README, 3 binary questions |
| 2 | C | Syntax, hello, Mario, cash, credit, K&R Ch. 2 |
| 3 | Arrays | Strings, arrays, readability, Caesar, substitution, K&R Ch. 3 |
| 4 | Algorithms | Search, sorting, Big O, recursion, plurality, runoff, Tideman |
| 5 | Memory | Hex, pointers, malloc, Valgrind, filter, recover, K&R Ch. 5 |
| 6 | Data structures | Structs, linked lists, hash tables, tries, Speller, midterm prep |
| 7 | Midterm + Python | Midterm 31 Oct; Python, DNA, Sentimental |
| 8 | SQL | SQLite, joins, Movies, Fiftyville, SVG SQL export |
| 9 | Web | HTML, CSS, JavaScript, DOM, Homepage, SVG web preview |
| 10 | Flask | Flask MVC, AJAX, Finance, final-project prep |
| 11 | Final project P1 | Architecture and scaffold; no new lectures |
| 12 | Final project P2 | Build, test, synthesize exam question bank |
| 13 | Final + polish | Final 12 Dec; documentation and polish |
| 14 | Buffer | Catch-up, backup ritual, *Code* Ch. 11–15 |

## Repository structure

```
Y01-CS50x/
├── week0-scratch/
├── week1-c/
├── week2-arrays/
├── week3-algorithms/
├── week4-memory/
├── week5-data-structures/
├── week6-python/
├── week7-sql/
├── week8-web/
├── week9-flask/
├── midterm-exam/
├── final-exam/
├── final-project/
└── README.md
```

## Key concepts mastered
_Fill in at completion — what can I now do independently?_
- [ ] C syntax, compilation, and debugging with gdb/valgrind
- [ ] Pointers, stack vs heap, malloc/free
- [ ] Arrays, strings, and memory layout
- [ ] Sorting/searching, Big O, recursion
- [ ] Linked lists, hash tables, tries
- [ ] Python, SQL, HTML/CSS/JS, Flask basics

## Notable work
_Links to specific problem sets, labs, and the final project (add as completed)._

| Week | Problem set | Link | check50 / style50 |
|---|---|---|---|
| | | | |

## Honest reflection
_What was hard? What did I get wrong? What would I do differently?_

## Exam scores
| Exam | Date | Score | Post-mortem |
|---|---|---|---|
| Midterm | 2026-10-31 | — | `_exams/Y01/cs50x-midterm-postmortem.md` |
| Final | 2026-12-12 | — | `_exams/Y01/cs50x-final-postmortem.md` |

Sample questions to prepare for: implement `swap(int *a, int *b)` and explain why the by-value version fails; trace the stack frames of `factorial(4)`; compare bubble sort vs merge sort complexity and when to choose each.

## Books read
- *The C Programming Language* (K&R) — Chapters 1–5 in Weeks 1–5; exercises committed to `kr-exercises/`. See [`_reading-list/Y01-books.md`](../_reading-list/Y01-books.md).

## Papers reviewed
None (no Research Seminar in Year 1).

## Definition of Done (per problem set)
- [ ] Compiles and runs without errors
- [ ] Committed with a conventional message
- [ ] README/inline comment explains the "why"
- [ ] check50 and style50 pass
- [ ] Screenshot/log captured for milestones
- [ ] 2-minute Obsidian reflection written
- [ ] Study hours logged

## Completion ritual
1. Self-grade · 2. Update `transcript.json` and GPA · 3. Capture certificate/screenshot · 4. `git tag -a cs50-complete -m "Completed CS50x, 2026"` · 5. Publish 500–1000 word retrospective · 6. Update portfolio tracker · 7. Archive Obsidian notes · 8. Log completion.
