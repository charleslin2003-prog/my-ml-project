# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project state

This repository is currently an empty scaffold. It contains no source code, no package/module structure, no tests, and no build or CI configuration. The only tracked files are `README.md` (a one-line title stub) and `.gitignore` (GitHub's standard Python template).

There are no commands to document yet (no build, lint, test, or run steps exist because there is nothing to build, lint, test, or run). Update this file once real code, a dependency/build tool, and tests are added.

## `requirements.txt`

The `requirements.txt` in the repo root is untracked and is **not** a valid project dependency list — it is a UTF-16 encoded dump of ~440 packages that matches a full Anaconda `base` environment (e.g. `anaconda-navigator`, `jupyterlab`, `conda-build`, `spyder`-adjacent packages), not dependencies of this project. Do not treat it as authoritative for what this project needs, and do not `pip install -r requirements.txt` from it as-is. When real dependencies are introduced, replace this file with a proper UTF-8, project-scoped requirements file (or a `pyproject.toml`).
