# Python-Grundlagen

Eine kurze Einführung in Python für das Seminar. Sie ist die Voraussetzung für den Data-Mining-Teil (Repository `intro-data-mining-de`) und den darauf aufbauenden Text-Mining-Teil (Repository `intro-text-mining-de`).

| # | Skript | Inhalte | Daten | Pakete |
|---|---|---|---|---|
| 00 | [Vorbereitungen für alle Repositories](00-setup-all-repos.ipynb) | Installation aller Pakete der drei Seminar-Repositories, spaCy-Modelle, NLTK-Stoppwörter, Sentence-Transformer-Modell, Kaggle-Datensätze, Text-Mining-Korpus und API-Schlüssel | lädt die Daten von Data Mining und Text Mining herunter | pip |
| 01 | [Python-Grundlagen](01-python-basics.ipynb) | Zahlen, Vergleiche, Text und Listen in Python, Grafiken mit `matplotlib` | Penn World Table 10.0 (`pwt100.xlsx`) | pandas, matplotlib, openpyxl |

## Ausführen

Das Skript läuft in jeder Python-Umgebung mit Jupyter. Benötigt werden folgende Pakete:

```bash
python -m pip install matplotlib openpyxl pandas jupyterlab
```

Das Notebook `01-python-basics.ipynb` ist **mit Ausgaben** gespeichert, sodass es sich auch ohne Ausführen lesen lässt.

Wer alle drei Teile des Seminars in einer Umgebung einrichten möchte, führt einmal [`00-setup-all-repos.ipynb`](00-setup-all-repos.ipynb) aus. Es erwartet `intro-data-mining-de` und `intro-text-mining-de` im selben übergeordneten Ordner wie dieses Repository, braucht Python 3.10 oder neuer und lädt insgesamt rund 3 GB herunter. Das Notebook ist **ohne Ausgaben** gespeichert.

## Daten

- `pwt100.xlsx` - Penn World Table 10.0 (https://www.rug.nl/ggdc/productivity/pwt/).
