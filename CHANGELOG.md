## [1.0.0] - 2026-06-25

### 🚀 Features

- Add git-cliff configuration and integrate changelog generation into release script

### 🐛 Bug Fixes

- *(data_process.py)* Refactor spatial data processing to use geopandas and remove unnecessary code

### 🚜 Refactor

- Migrate pre-commit config to git-hooks.nix and update environment setup
- *(data_process.py)* Fix indentation of `county_geom` method definition
- *(data_process.py)* Refactor data processing logic to use parquet files and improve performance by caching intermediate results

### ⚙️ Miscellaneous Tasks

- *(devenv.nix)* Update OCO_MODEL to qwen2.5-coder:3b for improved reliability and compatibility
