# Genies

This project uses Ollama, running in a Docker container, to manage self-hosted open source AI models like DeepSeek-V3/R1, Llama 3.3, and Qwen.

Ollama provides a convenient platform for running AI models locally, giving users privacy over the data they feed into the models, and allowing customization of models for specific use cases.

> [!IMPORTANT]
> **This repository is archived and is no longer maintained.**
> This was an experiment to see if running Ollama in a container would work well for interactive applications like GitHub Chat. It turned out to be too slow for that use case, so I switched to running Ollama natively on the host machine instead, which is much faster for interactive workloads.

## Documentation

* [Requirements](./docs/requirements.adoc)
* [Usage](./docs/usage.adoc)
* [Models](./docs/models.adoc)

---

Copyright © 2026-present Kieran Potts, [MIT license](./LICENSE.txt)
