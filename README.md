# Jackie Oliver

Software engineer working on infrastructure, data pipelines, and capture systems for robot learning.

- **RentAHuman:** payout ledgers and payment integrations with Stripe Connect and Whop.
- **Haptica (founder):** haptic gloves, multi-camera capture, and hand-tracking pipelines for robot training data. Selected capture code is available below.
- **KBRA:** data engineering with Airflow, Kafka, Databricks, and SQL Server ingestion.

## Selected projects

| Project | Engineering focus |
| --- | --- |
| [Capture & hand tracking](https://github.com/jackieoliver/hand-tracking-pipeline) | Camera control, recording sessions, telemetry, and hand-pose processing. **Python, Swift, GoPro, Apple Vision.** |
| [Agent Sync](https://github.com/jackieoliver/agent-sync) | Synchronize coding-assistant state across Mac and Linux with conflict detection, checksum verification, and backups. **Python, SSH/rsync, systemd.** |
| [pnp-js](https://github.com/jackieoliver/pnp-js) | Estimate camera pose from 2D–3D correspondences using DLT initialization and Levenberg–Marquardt refinement. **JavaScript, no runtime dependencies.** |
| [French Weave](https://github.com/jackieoliver/french-weave-extension) | Language learning across browser reading and coding assistants: constrained substitutions plus a documented Claude Code/Codex shared-state integration. **JavaScript, Python.** |
| [Audio Clock Sync](https://github.com/jackieoliver/audio-clock-sync) | Estimate recording-device clock offsets from shared audio, with confidence scoring and candidate-offset comparison. **Python, NumPy, SciPy.** |
| [Claude for Codex](https://github.com/jackieoliver/codex-claude-fable-plugin) | A CLI bridge with model selection and persistent project conversations. **JavaScript, Node.js.** |

Start with **Capture & hand tracking** for a larger system, **Agent Sync** for reliability decisions, or **pnp-js** for a focused algorithm and runnable tests. Each repository explains its scope and setup; capture/model tooling requires additional hardware or assets for the full workflow.

Most production work lives in private repositories. I'm happy to walk through the architecture and engineering decisions.

[LinkedIn](https://www.linkedin.com/in/jacqueline-r-oliver/) · [3D tree site](https://jackieoliver.github.io/jackieoliver/)
