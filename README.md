# Framework Parallel Phases

![Cover](cover.png)

Run multiple phases simultaneously.

## What's Inside

- `procedure.yaml`: defines four phases with a fan-out dependency graph
- `phases/initialize.py`: setup before parallel tests
- `phases/voltage_test.py`: independent voltage measurement
- `phases/current_test.py`: independent current measurement
- `phases/temperature_test.py`: independent temperature measurement
- `pyproject.toml`: uv-managed Python project

## Get Started

1. Sign up for a free TofuPilot account at [tofupilot.app](https://www.tofupilot.app/auth/signup).
2. Open the **New Procedure** flow in the dashboard and clone this template.
3. Follow the dashboard's instructions to set up a station and run the procedure.

For deeper guides, see the [TofuPilot docs](https://www.tofupilot.com/docs/framework).

## Structure

```
.
├── procedure.yaml
├── phases/
│   ├── initialize.py
│   ├── voltage_test.py
│   ├── current_test.py
│   └── temperature_test.py
├── pyproject.toml
└── README.md
```
