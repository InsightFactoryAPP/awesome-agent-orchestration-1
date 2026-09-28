## Anti-patterns

- Building a private “shared agent infra” monorepo when Paperclip or Conductor already cover tickets, runs, adapters, and governance.
- Treating dual ticket/run state machines as a reason to own the whole stack — extract a library only after two or more real consumers need the same code.
- Fork-only control planes that never ship a usable CLI/UI and accumulate permanence through backlog documents.

## Contributing

PRs welcome for tools that are open source (or clearly documented hosted products), actively maintained, and that map cleanly to a row in the problem map. Prefer describing what the tool does, not its marketing.

To the extent possible under law, Angel Hermon has waived all copyright and related or neighboring rights to this work. CC0 1.0, 2026.
