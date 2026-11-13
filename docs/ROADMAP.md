# ForgeLM-4B — Research roadmap

> **Status:** Planned after 1B milestone. All model parameter counts are research targets until verified.

ForgeLM-4B is the proposed follow-on project for training and evaluating an approximately four-billion-parameter language model. It focuses on scaling decisions, distributed training, efficiency and reliability, grounded in evidence from the 1B-scale project.

| Stage | Milestone | Acceptance criterion | Status |
|---|---|---|---|
| 01 | Review ForgeLM-1B evidence | Analyze actual losses, training throughput, bottlenecks and evaluation results | Planned |
| 02 | Build a scaling plan | Parameter/token tradeoffs, context, optimizer, memory and compute budgets | Planned |
| 03 | Validate distributed training | Data or tensor parallelism as needed, checkpoint shards and fault recovery | Planned |
| 04 | Secure data and compute | Provenance, licensing, quality and feasible accelerator access | Planned |
| 05 | Train approximately 4B parameters | Document true parameter count, tokens, hardware, energy and run cost | Planned |
| 06 | Evaluate and optimize inference | Capability, latency, quantization, memory, robustness and model card | Planned |

## Definition of done

A milestone is completed only with reproducible implementation evidence, configuration, verification/test results, and where applicable hardware/data manifests, published artifacts and measured results. A proposed design or a prepared repository is not evidence of a trained model.

## Decision gates

- **Data:** legally usable source, provenance, filtering, leak checks and quality report.
- **Engineering:** independently rerunnable pipeline, numerical tests, checkpoints and monitoring.
- **Compute:** hardware access, throughput benchmark, memory plan and realistic budget.
- **Evaluation:** frozen protocols, explicit baselines, failure cases and reproducible scoring.

## Next action

Analyze actual losses, training throughput, bottlenecks and evaluation results.
