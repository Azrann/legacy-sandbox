**Languages:** [English](README.md) · [Español](README.es.md)

# legacy-sandbox

Small historical test files.

<!-- BEGIN project-context -->

## Historical dates and evidence

**Reference year for this version: 2016.** This uses the most recent source or configuration file with a recoverable historical date; the exact creation date could not be confirmed.

- Most recent datable file: **2016-07-09**, [`testa/miArchivo.txt`](testa/miArchivo.txt); date of the commit modifying the file, recovered from local Git history.
- Earliest record among the original Git repositories included: **2016-07-09**. This may be an import and does not establish when the code was first written.

October 2026 copy timestamps and documents generated during this review were excluded. Recoverable dates do not guarantee that there are no later, undated changes.

Reference years by component (most recent datable file):

| Component | Year |
| --- | --- |
| [`testa`](testa/) | 2016 |
| [`testb`](testb/) | 2016 |

## Why this is worth exploring

Preserves two minimal repository experiments with text files. Their value is archival and educational for Git; there is no application with its own logic to highlight.

Code entry points:

- [`testa/miArchivo.txt`](testa/miArchivo.txt)
- [`testb/miArchivo.txt`](testb/miArchivo.txt)

<!-- END project-context -->

## Contents

| Directory | Function |
| --- | --- |
| [`testa/`](testa/) | Minimal test repository containing only miArchivo.txt, with no application code or build manifests. |
| [`testb/`](testb/) | Minimal test repository containing only miArchivo.txt, with no application code or build manifests. |



## Requirements and setup

Text files; no executable application.

This is a historical copy. Consult each component's project files and README for versions and dependencies. Restore NuGet/npm from the appropriate folder; internal libraries may need rebuilding. Prepare databases and external services using your own accounts.

## Configuration and security

Original secrets have been removed or replaced with `REPLACE_WITH_YOUR_VALUE`. Search for this marker before running and provide values through local configuration or environment variables. Sessions, private keys, signing certificates, databases, logs, deployment profiles, and binary packages are not published. The `.gitignore` protects these local files.

A fresh history is published: old commits remain only in the original local copy. Example values cannot connect to the original services.

## Validation status

A static review and secret scan were performed before publication. Applications, trading operations, deployments, and tests contacting external services were not run. Building with current tools is not guaranteed. Some projects need historical dependencies and assets that are not included.

## Licenses and provenance

Third-party licenses and attributions present in the code are retained. No blanket license is added to components that lacked one. This import preserves local sources and does not claim to be a current version of the original project.
