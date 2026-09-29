# SVG Graphics Engine

Year 1 Integrated Project · **2 credits** · Standalone project inside `bsc-cs-curriculum`.

A CLI tool written in **C** that calculates and generates complex SVG vector geometries. It will be used to automate programmatic generation of **WorkCentrik brand assets** and **PeppiVerse character mascots**.

## Status
In progress — Term 1 (14 Sep – 20 Dec 2026). Target: **v1.0 release in Week 12**, polish in Week 13.

## Planned features
- Primitives: circle, rectangle, line, with SVG attributes
- Complex geometry: polygon, path, Bézier, ellipse
- Path rendering via recursive descent for `M`, `L`, `C`, `Z`
- Input from stdin or file, with validation and clear errors
- Storage with linked list and dynamic array
- Export: CSV, JSON, metadata; HTML web preview embedding the SVG

## Usage (target interface)
```bash
make
./svgengine --help
./svgengine circle --cx 50 --cy 50 --r 40 > out.svg
./svgengine render shapes.txt -o out.svg
```
_Update this section as the CLI stabilises._

## Architecture
```
Y01-SVGGraphicsEngine/
├── src/          # C sources (point/shape structs, parser, renderer)
├── include/
├── tests/
├── examples/     # generated SVGs, brand-asset samples
├── docs/adr/     # architecture decision records
├── Makefile
└── README.md
```
Core data types: `Point`, `Shape`. I/O specification is defined in Week 2.

## Milestones

| Week | Milestone | Definition of Done | Done |
|---|---|---|---|
| 1 | Environment and specification | README, architecture, Makefile, Git initialized | ☐ |
| 2 | Planning | Point and Shape structs; I/O specification | ☐ |
| 3 | Skeleton CLI | argc/argv, help, error handling | ☐ |
| 4 | Input parsing | Parse stdin/file and validate input | ☐ |
| 5 | Primitives | Circle, rectangle, line, SVG attributes | ☐ |
| 6 | Memory | Paired malloc/free, zero Valgrind leaks | ☐ |
| 7 | Complex geometry | Polygon, path, Bézier, ellipse | ☐ |
| 8 | Storage | Linked list and dynamic array | ☐ |
| 9 | Path rendering | Recursive descent for M, L, C, Z | ☐ |
| 10 | SQL export | CSV, JSON, metadata | ☐ |
| 11 | Web preview | HTML page embedding SVG | ☐ |
| 12 | v1.0 release | Tests, documentation, demo video | ☐ |
| 13 | Polish | Code review, README, blog post | ☐ |

Work is done mainly in the Sunday project sprint (with Thursday buffer).

## Quality checklist ("Would this pass at MIT/CMU?")
- [ ] Edge cases and invalid input handled
- [ ] Test suite with coverage figure
- [ ] Documentation readable in 30 minutes
- [ ] Performance and memory measured (Valgrind clean)
- [ ] Style enforced (`clang-format`)
- [ ] Threat-modelled input parsing (buffer sizes, malformed input)

## Evidence
- Blog post: *From SVG Primitives to Brand Assets: Building a Programmatic Graphics Engine in C* (Y1 Q1)
- Demo video: _link_
- Sample generated brand assets: `examples/`

## Honest reflection
_What was hard? What would I do differently?_
