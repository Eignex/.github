<p align="center">
  <img src="banner.svg" style="max-width: 100%; width: 22em" />
</p>

Eignex builds high-performance open source software in Kotlin for the JVM ecosystem, centered on backend libraries and optimization tooling. The goal is to offer small, infrastructure-grade components that help teams build faster and operate more efficiently. The long-term vision is a cohesive stack that brings advanced optimization techniques into everyday backend systems through predictable performance, low overhead, and seamless JVM integration.

## Philosophy

* Consistent, predictable runtime behavior.
* Low-allocation, efficient components.
* Clear semantics with minimal dependencies.
* Components designed for distributed and production environments.
* Tools that scale cleanly from experimentation to full deployment.


## Combo (Primary Project)

**combo** is a multi-variate bandit optimization engine. It supports machine-learning–driven optimization for:

* LLM agent flows and prompt strategies,
* UI and UX parameter experiments,
* Feature flags, routing, and backend tuning,
* and anything else you can think of.

combo runs as an on-prem service deployable on k8s, with an HTTP API and SDK for use from any language. It is fully open source but still under active development and not yet publicly released.

A premium hosted version will be available at **eignex.io**, offering managed infrastructure, analytics UI, and operational tooling.


## Contact
info@eignex.com

## Repositories

- **[combo](https://github.com/Eignex/combo)** Multi-variate discrete optimization engine (in development).
- **[kencode](https://github.com/Eignex/kencode)** Binary–text codecs and compact bit-packed serialization for Kotlin.
- **[kpermute](https://github.com/Eignex/kpermute)** Deterministic, reversible integer permutations for sampling, masking, and pseudo-random shuffling.
