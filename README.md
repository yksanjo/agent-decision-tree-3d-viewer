# Agent Decision Tree 3D Viewer

Visualize agent reasoning and branch outcomes in 3D space.

## Priority Metadata

- ID: 174
- Domain: spatial-3d
- TTE (days): 4
- Exposure score: 9/10
- Wave: 1
- Priority score: 7.80

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
