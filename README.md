# starengine

An autonomous, no-LLM trading engine for the SpaceTraders API (v2).

Status: planning. The build plan for an implementing agent is in [`docs/plan/`](docs/plan/README.md)
(nine files: scaffolding, architecture, API client and request budget, decision engine, milestones,
tests, shadow comparison, go-live and safety). Start with `docs/plan/README.md`, then
`docs/plan/05-milestones-and-build-order.md`.

Operator answers recorded in the plan README (2026-11-14): separate source IP via proxy, same box as the
live fleet but its own user/process/database, go straight to trading, live from the 2026-11-15 reset.

Secrets (the SpaceTraders token, proxy credentials) are environment variables on the host only.
Never commit them.
