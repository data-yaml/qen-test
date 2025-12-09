# test-1765244183-91cb725e-wrapper-test

## Project Metadata

- **Created:** 2025-12-09
- **Branch:** 251208-test-1765244183-91cb725e-wrapper-test

## Overview

*Briefly describe the purpose and goals of this project.*

## Repositories

This project includes repositories defined in the `pyproject.toml` file. Current repositories:

- See `pyproject.toml` for the most up-to-date list

## Getting Started

### Using the Project Wrapper

This project includes a `./qen` executable that automatically runs qen commands in this project's context:

```bash
# From within the project directory, use the wrapper:
./qen status      # Check project status
./qen add <repo>  # Add a repository
./qen pull        # Update repos
./qen pr status   # Check PR status
./qen --help      # More commands

# The wrapper ensures you're always working with this project,
# even if you have multiple qen projects configured.
```

### Using Global qen

Alternatively, you can use the global `qen` command with the `--proj` flag:

```bash
uvx qen --proj test-1765244183-91cb725e-wrapper-test status
uvx qen --proj test-1765244183-91cb725e-wrapper-test add <repo>
```

## Next Steps

- [ ] Update project overview
- [ ] Add more detailed documentation
- [ ] Configure repositories in `pyproject.toml`
