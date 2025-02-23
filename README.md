# Schlaganfallrisiko-Vorhersage mit Machine Learning

Dieses Projekt nutzt den **HearthAttack-Datensatz**, um das Risiko eines Schlaganfalls bei Patienten mithilfe von **Machine Learning**-Techniken vorherzusagen. Ziel ist es, präventive Maßnahmen zu ermöglichen und potenzielle Schlaganfallpatienten frühzeitig zu identifizieren.

## Datenquelle

Der **HearthAttack-Datensatz** umfasst eine Vielzahl von medizinischen Merkmalen, die mit dem Risiko eines Schlaganfalls in Zusammenhang stehen. Die Daten enthalten folgende Attribute:

| **Attribut**  | **Beschreibung**                       |
|---------------|----------------------------------------|
| `age`         | Alter des Patienten                    |
| `sex`         | Geschlecht des Patienten (male/female)|
| `cp`          | Brustschmerztyp (0-3)                 |
| `trestbps`    | Ruheblutdruck                         |
| `chol`        | Cholesterinwert                        |
| `fbs`         | Nüchternblutzucker > 120 mg/dl (True/False)|
| `restecg`     | Ruhe-EKG-Ergebnisse (0-2)              |
| `thalach`     | Maximale Herzfrequenz                 |
| `exang`       | Angina pectoris bei Belastung (yes/no)|
| `oldpeak`     | ST-Absenkung (Depression)             |
| `slope`       | Steigung des ST-Segments (0-2)        |
| `ca`          | Anzahl der großen Gefäße (0-3)        |
| `thal`        | Thalassämie (1-3)                     |
| `target`      | Risiko eines Schlaganfalls (high risk) |

## Projektstruktur

- **Data**: Enthält den HearthAttack-Datensatz.
  - `heart.csv`: Der Datensatz mit medizinischen Informationen und Zielwerten.
- **Notebooks**: Jupyter-Notebook zur Analyse und Vorhersage.
  - `Ü - Heart-Attack.ipynb`: Notebook für die explorative Datenanalyse, Datenvorverarbeitung und Modelltraining.

## Technologien

- **Python**: Hauptprogrammiersprache für Datenanalyse und Modellierung.
- **Pandas & Numpy**: Für Datenmanipulation und -analyse.
- **Scikit-learn**: Für Machine Learning-Modelle und -Evaluierung.
- **Matplotlib / Seaborn**: Für die Visualisierung der Daten und Ergebnisse.

## Anmerkung

Dieses Projekt dient als Teil des Studienprogramms im Bereich **Angewandte Künstliche Intelligenz** und zeigt die Anwendung von dem Modul **Machine Learning 1** in der Gesundheitsbranche.
