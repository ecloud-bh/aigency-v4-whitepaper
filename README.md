# AIGENCY V4 Whitepaper

> **Sovereign, fully independent, multimodal — 128B parameters.**
> Technical whitepaper for AIGENCY V4 by
> [eCloud Yazılım Teknolojileri](https://e-cloud.web.tr) ·
> [aigency.dev](https://aigency.dev)

[![Whitepaper EN](https://img.shields.io/badge/Whitepaper-EN-blue)](AIGENCY-V4-Whitepaper-EN.pdf)
[![Whitepaper TR](https://img.shields.io/badge/Whitepaper-TR-red)](AIGENCY-V4-Whitepaper-TR.pdf)
[![HuggingFace](https://img.shields.io/badge/🤗-Model_card-yellow)](https://huggingface.co/aigencydev/AIGENCY-V4)
[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC_BY--ND_4.0-lightgrey)](LICENSE)

---

## What's in this repo

```
.
├── AIGENCY-V4-Whitepaper-EN.pdf       # 32-page English whitepaper
├── AIGENCY-V4-Whitepaper-TR.pdf       # 32-page Turkish whitepaper
├── AIGENCY-V4-Whitepaper-EN.docx      # Editable English source
├── AIGENCY-V4-Whitepaper-TR.docx      # Editable Turkish source
├── README.md                          # This file
└── LICENSE                            # CC BY-ND 4.0
```

## Headline numbers

> 22 benchmarks · 13,344 real API calls · Wilson 95% CI · seed=42 · 27 April 2026

| Benchmark | AIGENCY V4 | Position |
|---|---|---|
| Belebele-TR (Turkish reading) | **87.33** | #1 globally — frontier does not publish |
| ARC-Challenge | **94.88** | Tied at frontier |
| GSM8K | **94.62** | Tied at frontier |
| HumanEval / MBPP | **84.15 / 84.82** | Upper-mid frontier |
| MMLU | **80.10** | Lower-mid frontier |
| MMLU-Pro / GPQA-D | 50.20 / 37.88 | Development area (V4.1 target) |
| MMMU / DocVQA | 53.33 / 79.17 | First-gen multimodal |

The full breakdown is in the whitepaper, Section 7.

## Quick links

- **🤗 Model card** — [huggingface.co/aigencydev/AIGENCY-V4](https://huggingface.co/aigencydev/AIGENCY-V4)
- **📊 Evaluation dataset** (reproducibility capsule) — [huggingface.co/datasets/aigencydev/aigency-v4-evaluation](https://huggingface.co/datasets/aigencydev/aigency-v4-evaluation)
- **🌐 Live demo Space** — [huggingface.co/spaces/aigencydev/AIGENCY-V4-Demo](https://huggingface.co/spaces/aigencydev/AIGENCY-V4-Demo)
- **🔧 Benchmark code** — [github.com/ecloud-bh/aigency-benchmarks](https://github.com/ecloud-bh/aigency-benchmarks)
- **🔗 Production API** — [aigency.dev](https://aigency.dev)

## One-line positioning

> AIGENCY V4 — a globally competitive, fully sovereign frontier-adjacent AI
> model designed for Turkish: world-leader on Turkish reading comprehension
> and natural-language inference, frontier-level on grade-school math and
> scientific reasoning, KVKK-resident, transparently evaluated.

## Citation

```bibtex
@techreport{aigency-v4-2026,
  title  = {AIGENCY V4: Sovereign, Fully Independent and Multimodal 128B-Parameter AI Architecture},
  author = {{eCloud Yaz{\i}l{\i}m Teknolojileri}},
  year   = {2026},
  month  = apr,
  institution = {eCloud Yaz{\i}l{\i}m Teknolojileri},
  url    = {https://github.com/ecloud-bh/aigency-v4-whitepaper}
}
```

## License

The whitepaper is licensed under **Creative Commons BY-ND 4.0** —
you may share with attribution; no derivative works.

The benchmark runner code (separate repo) is **MIT**.
The model itself is offered **API-only commercial** — see
[aigency.dev/license](https://aigency.dev/license).

## Contact

**info@e-cloud.web.tr · ai@aigency.dev** · [aigency.dev](https://aigency.dev) ·
© 2026 eCloud Yazılım Teknolojileri
