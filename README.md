# Python-Grundlagen

Eine kurze Einführung in Python für das Seminar. Sie ist die Voraussetzung für den Data-Mining-Teil (Repository `intro-data-mining-de`) und den darauf aufbauenden Text-Mining-Teil (Repository `intro-text-mining-de`).

| # | Skript | Inhalte | Daten | Pakete |
|---|---|---|---|---|
| 01 | [Python-Grundlagen](01-python-basics.ipynb) | Zahlen, Vergleiche, Text und Listen in Python, Grafiken mit `matplotlib` | Penn World Table 10.0 (`pwt100.xlsx`) | pandas, matplotlib, openpyxl |

## Ausführen

Das Skript läuft in jeder Python-Umgebung mit Jupyter. Benötigt werden folgende Pakete:

```bash
python -m pip install matplotlib openpyxl pandas jupyterlab
```

Das Notebook ist **mit Ausgaben** gespeichert, sodass es sich auch ohne Ausführen lesen lässt.

## Daten

- `pwt100.xlsx` - Penn World Table 10.0 (https://www.rug.nl/ggdc/productivity/pwt/).
