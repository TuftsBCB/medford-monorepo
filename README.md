# MEDFORD Monorepo

We will initially attempt to use NX minimally. Primarily because it is a polygot monorepo, creates dependency graphs, and supports semantic versioning, among other reasons. :)

https://nx.dev/

### What's in here?
- parser [python]
- language server [python]
- vs code extension [python, minimal typescript]
- medford-in-a-box (web-based editor) [typescript, svelte]

### What's are the requirements

Top-level directory and subdirectories for each programs/apps.

Top-level directory and subdirectories for each shared code per language or implementation. (i.e., python code for loading files)

UNIT Tests across multiple programs/apps.

Semantic Versioning for builds.
