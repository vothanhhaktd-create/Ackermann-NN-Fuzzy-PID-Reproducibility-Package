# Tables and Python Source Code for Reproducibility

This package contains:

```text
results/tables/
├── overall_metrics.csv
├── overall_metrics.xlsx
└── scenario_metrics.csv

src/
└── ackermann_control/
    ├── __init__.py
    ├── parameters.py
    ├── vehicle_model.py
    ├── fuzzy_rules.py
    ├── controllers.py
    ├── mpc_benchmark.py
    ├── scenarios.py
    ├── simulation.py
    ├── metrics.py
    └── plotting.py

scripts/
├── run_all.py
├── generate_figures.py
└── export_tables.py
```

## How to rerun the simulations

```bash
pip install -r requirements.txt
python scripts/run_all.py
```

## Table files

- `overall_metrics.csv`: full metric table for all controllers and scenarios.
- `overall_metrics.xlsx`: Excel version of the full metric table.
- `scenario_metrics.csv`: compact per-scenario summary showing best controllers and proposed-controller metrics.

