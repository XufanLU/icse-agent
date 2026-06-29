# Agent Interruption and Recovery

This repository contains supporting material for the paper on agent interruption
and recovery. The materials are organized around the prototype evaluation and
the SMS study process used in the paper.

- `ab_test/`
  - Contains the prototype used to evaluate checkpoint-based interruption and recovery.
  - Includes the checkpointing A/B tests, the local first-shell agent prototype, fixture-backed CIF/XAS pairs, and the workflow helpers needed by the test harness.
  - See `ab_test/README.md` for setup and run instructions.

- `multiagent_debug_flow/`
  - Contains a lightweight multi-agent software-engineering debugging workflow.
  - Compares restart-from-zero against checkpoint resume after reviewer feedback in a developer/reviewer patch-and-test loop.
  - Includes deterministic dry-run agents and an opt-in OpenAI Agents SDK mode.
  - Records wall-clock time, token usage, test runs, file mutations, review rounds, and repeated work.
  - See `multiagent_debug_flow/README.md` for setup and run instructions.

- `SMS_mapping_material/`
  - Records the process used for the SMS mapping study.
  - `mapping_result.xlsx` stores the mapping results and related study material.


## License

Third-party dependencies retain their respective licenses. See
[`LICENSES.md`](LICENSES.md) for a package summary table and detailed notices.
