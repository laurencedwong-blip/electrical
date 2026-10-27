# CircuitBench

Repository for CircuitBench electrical-symbol work.

## Current status

This repository contains only an initial scaffold. The current CircuitBench
application source has not been imported, so there is no runnable application,
build command, or test suite here yet.

## Add the current project

1. Obtain a source export or snapshot of the current CircuitBench project.
2. Create a branch from `main`, such as `import/circuitbench-source`.
3. Add the source at the repository root, preserving its existing layout,
   assets, dependency manifests, and lockfiles. Review any README or ignore
   rules from the export alongside these scaffold files.
4. Check for credentials and private data before committing. Keep secrets out
   of Git; add a sanitized `.env.example` if the application needs configuration.
5. Use the imported project's actual setup and verification commands, then
   document them here and open a pull request.

Choose framework-specific folders, dependencies, tooling, and automation after
inspecting the source. No application architecture is established by this scaffold.

## Reversibility

The scaffold consists only of `README.md` and `.gitignore`. Both can be revised
or removed when importing the application; no application files have been replaced.
