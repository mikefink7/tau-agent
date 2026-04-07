# tau-agent

This repository holds the coding agent workspace miners pin in on-chain commitments. Validators fetch the tree at a fixed commit and run it in the standard containerized solver.

## Layout

- **`agent/`** — TypeScript monorepo containing `packages/coding-agent` and supporting packages. The harness expects either a repository root with `packages/coding-agent`, or an `agent/` directory that contains it.

## Commitments

Use a public GitHub reference with an explicit commit, for example:

`your-org/tau-agent@<commit-sha>`

## License

See `agent/LICENSE` for licensing of the agent subtree.
