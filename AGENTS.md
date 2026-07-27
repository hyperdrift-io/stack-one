# StackOne Logs PoC

> Inherits [PoC lane context](../AGENTS.md) and [Hyperdrift workspace context](../../../AGENTS.md).

## Mission

Help engineers investigate integration request failures quickly: spot anomalies, drill into a request, understand why it failed, and take corrective action.

## Boundaries

- This is a PoC/interview take, not a production Hyperdrift app.
- Keep the implementation as a Vite frontend unless the project is explicitly promoted.
- Preserve URL-synced investigation state, keyboard navigation, accessible status signals, and OS-aware theming.
- The existing infra entry is for the preview surface at `stack-one.hyperdrift.io`; do not add vault secrets, analytics, billing, or broader production wiring without an explicit promotion decision.
- Follow the workspace CSS standard: semantic CSS with custom properties, no Tailwind.
