# NEM electricity-price deep-learning papers, explained

- `index.html` — the directory of NEM spot-price deep-learning papers (Tan 2023 → Sinclair 2026) with every concept explained visually and with live worked examples.
- `rnn_explainer.html` — companion: LSTM, GRU and TCN worked numerically.
- `src/` — the report is built by concatenating `src/01_head.html` … `src/07_scripts.html` in order into `index.html`. Edit a part, then rebuild:

```
cat src/01_head.html src/02_foundations.html src/03_blocks.html src/04_attention.html src/05_beyond.html src/06_papers.html src/07_scripts.html > index.html
```

Both pages are self-contained (no external scripts or assets).
