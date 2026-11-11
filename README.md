<div align="center">

# C / Bounded Telemetry Ring Buffer

**Bounded telemetry buffering in low-level C.**

`C11` · Educational implementation · Source available

[Concept](#concept) • [Run](#run) • [Source tour](#source-tour) • [Caveats](#caveats)

</div>

---

## Concept

Fixed-size allocation and O(1) overwriting ingestion; reports exact overflow/drop count, logical event ordering, error status frequency and average latency. No heap allocation after initialization.

## Run

```bash
make
```
Review the included `Makefile` for specific targets.

## Source tour

| In this repository | Role |
|:--|:--|
| [`Makefile`](./Makefile) | Build targets |
| [`README.md`](./README.md) | Technical context |
| [`ring.c`](./ring.c) | C implementation |

## Caveats

Treat this as a reproducible educational project. Simulation outputs depend on the project assumptions; use synthetic inputs, inspect edge cases and review the source before applying any approach to a production system.

<details>
<summary>Original documentation and implementation notes</summary>

# C / Bounded Telemetry Ring Buffer

Fixed-size allocation and O(1) overwriting ingestion; reports exact overflow/drop count, logical event ordering, error status frequency and average latency. No heap allocation after initialization.

```bash
make
```

</details>

---

<sub>Code and commentary in the [Sharanya Pal project index](https://github.com/sharanyapal?tab=repositories).</sub>
