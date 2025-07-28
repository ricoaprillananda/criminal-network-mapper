# criminal-network-mapper
criminal-network-mapper is a data-driven system that maps and visualizes criminal networks, identifies key actors (kingpins, facilitators, brokers), and simulates potential threat pathways through advanced network analysis.

---

## Features

- Load and parse CSV data containing entities and relationships.
- Build an interactive criminal network graph.
- Identify central or highly connected individuals.
- Detect potential clusters or subnetworks.
- Export high-quality network visualizations.

---

## Project Structure

```
criminal-network-mapper/
├── README.md # Project documentation
├── data/ # Source CSV datasets
│ └── example-criminal-network.csv
├── notebooks/ # Jupyter notebooks for exploration
│ └── exploratory-analysis.ipynb
├── src/ # Core source code
│ ├── data_loader.py
│ ├── network_builder.py
│ ├── visualization.py
│ └── detection_engine.py
├── models/ # Placeholder for ML models (if applied)
│ └── ...
├── output/ # Generated visual outputs
│ └── graphs/
│ └── network-map.png
├── requirements.txt # Python dependencies
├── .gitignore # Files/folders to ignore by Git
└── .gitkeep # Keeps empty folders under version control

---

## Requirements

Install the required dependencies using:

```bash
pip install -r requirements.txt
```
Basic packages include:

- pandas
- networkx
- matplotlib
- seaborn
- jupyterlab

---

## Usage

1. Place your structured criminal data inside the data/ directory in CSV format.
2. Run the exploratory notebook located in notebooks/ to understand the structure.
3. Use the scripts in src/ to load, process, and visualize the network.
4. Generated network graphs will be saved in output/graphs/.

---

## Example Use Case

This toolkit can be used by journalists, data scientists, or investigators to analyze suspected criminal activities by mapping communication, financial, or relational ties across individuals or groups.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Disclaimer

This project is for educational and research purposes only. Any resemblance to real persons, living or dead, or actual events is purely coincidental.


