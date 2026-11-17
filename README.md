# nevarch

A multi-agent workflow toolkit, starting from an unmodified copy of
[pstack](https://github.com/cursor/plugins/tree/main/pstack) by Lauren Tan.

## Layout

- `pstack/` — the pstack Cursor plugin (skills, agents, playbooks, docs), copied as-is.
- `harness/pstack/` — the generated Claude Code adapter for pstack, copied as-is.
- `pstack/skills/{deslop,control-ui,control-cli}` — bundled from [cursor-team-kit](https://github.com/cursor/plugins/tree/main/cursor-team-kit) so pstack has no external plugin dependency.

## Provenance

Imported from [`cursor/plugins`](https://github.com/cursor/plugins) at commit
`e1cc03121a0e71129a4fb730d7c5528a0a3e43c8` (pstack v0.15.43).
See [NOTICE](NOTICE).

## License

MIT — see [LICENSE](LICENSE).
