Shapetal

Let me first look at what's already in your workspace.

The workspace is empty — a blank canvas! "A new number system" is a wide-open concept, so let me ask a couple of
questions to narrow down what you're imagining.

Fun — I'll design something genuinely original. Here's my proposal:

---

# 🔷 **Shapetal** — A Geometric Base-6 Number System

## Core Idea

Each digit is a **geometric shape** whose number of sides *is* its value. This makes the number system visually
self-documenting.

| Decimal Digit | Shapetal Symbol | Why                   |
|---------------|-----------------|-----------------------|
| 0             | `○`             | Circle — zero corners |
| 1             | `│`             | Line — one stroke     |
| 2             | `∠`             | Angle — two rays      |
| 3             | `△`             | Triangle — 3 sides    |
| 4             | `□`             | Square — 4 sides      |
| 5             | `⬠`             | Pentagon — 5 sides    |

## Examples

| Decimal | Base-6 | Shapetal |
|---------|--------|----------|
| 0       | 0      | `○`      |
| 5       | 5      | `⬠`      |
| 6       | 10     | `│○`     |
| 13      | 21     | `∠│`     |
| 36      | 100    | `│○○`    |
| 42      | 110    | `││○`    |
| 255     | 1103   | `││○△`   |

## Why Base-6?

- **Cleaner fractions**: 1/2 = `○.△`, 1/3 = `○.∠`, 1/6 = `○.│`
- **Countable on one hand** (0–5 per digit)
- Factors of 2 and 3 built in — divides evenly into many natural groupings

## What I'd Build

A Python package (`shapetal/`) with:

- **`ShapetalNumber` class** — full arithmetic (`+`, `-`, `*`, `/`, [//](cci:9://file:///:0:0-0:0), `%`, `**`),
  comparisons, and conversions to/from decimal, binary, hex
- **Fractional support** — seximal decimals with the geometric symbols
- **Interactive CLI calculator** — type expressions, see results in both Shapetal and decimal
- **Unit tests** for correctness

```
anewnumbersystem/
├── README.md
├── shapetal/
│   ├── __init__.py
│   ├── core.py        # ShapetalNumber class + arithmetic
│   ├── symbols.py     # Symbol definitions & mappings
│   └── cli.py         # Interactive calculator
└── tests/
    └── test_shapetal.py
```

---

Want me to build this? If so, **switch to Code mode** using the mode selector in the input box and I'll implement the
whole thing.