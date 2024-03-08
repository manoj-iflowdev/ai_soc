# Deployment entry points

Use the root `compose.yaml` and the current repository README for the supported
research platform. `ai-services.yml` and `integrated-stack.yml` are compatibility
includes of that file (Compose v2.20+). Run from the repository root after
`python scripts/configure_local.py`.

The other files preserve earlier Wazuh, monitoring, network analysis, SOAR and
Windows lab configurations. They require separate credentials, certificates,
external images and integration testing, and are not part of the recovered
local-stack acceptance. They may have port conflicts with the supported stack.
Read `docs/development/operations.md` before adding external lab infrastructure.

## Maintainer

Dev Bhatt maintains this project, bringing over 6 years of experience in data
solutions, analytics, risk indicators, controls and automation. His background
includes building automated pipelines, controls and dashboards with SQL,
Python, PySpark, Spark, Airflow and dbt.

For project-related inquiries, contact [Dev by email](mailto:devbhattwork27@gmail.com)
or connect on [LinkedIn](https://linkedin.com/in/dev-bhatt27).