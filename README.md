# Quant Finance Notebooks

Small, self-contained studies on real market data. Each project asks one question, sources and cleans the data, tests its own assumptions, and states its limitations.

| Project | Question | Key result |
|---|---|---|
| [**TED Spread After LIBOR**](ted-spread/) | Can the TED spread — a classic banking-stress gauge — be rebuilt after LIBOR's discontinuation? | 40-year spread rebuilt by splicing AMERIBOR onto reconstructed LIBOR; substitute validated on overlap (corr 0.92, mean gap −1 bp) and still flags the 2023 SVB failure (+58 bp) |

## Structure

Each project lives in its own folder:

```
<project>/
├── README.md        question, findings, method, limitations
├── <project>.ipynb  full analysis, executed with outputs
├── images/          charts used in the README
└── data/            not committed — see data/README.md for sources
```

## Setup

```bash
pip install -r requirements.txt
jupyter notebook
```
