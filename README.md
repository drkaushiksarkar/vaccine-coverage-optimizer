# Vaccine Coverage Optimizer

Vaccine coverage optimization and equity analysis platform using WUENIC estimates, administrative records, and coverage survey data.

## Architecture

```
vaccine-coverage-optimizer/
  src/           # Core modules
  tests/         # Unit and integration tests
  config/        # Configuration files
  docs/          # Documentation
```

## Modules

- **coverage_estimator**: Core coverage estimator functionality
- **equity_scorer**: Core equity scorer functionality
- **schedule_optimizer**: Core schedule optimizer functionality
- **dropout_analyzer**: Core dropout analyzer functionality
- **demand_forecaster**: Core demand forecaster functionality

## Quick Start

```bash
pip install -r requirements.txt
python -m vaccine_coverage_optimizer.main
```

## Testing

```bash
pytest tests/ -v
```

## License

MIT License - see LICENSE for details.
