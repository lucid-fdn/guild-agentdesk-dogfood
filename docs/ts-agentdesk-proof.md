# TypeScript AgentDesk Dogfood Proof

This file is the intentionally small work product for issue #3.

It proves the TypeScript-first AgentDesk loop can run from a clean external repo:

- create an `agent:ready` GitHub issue
- sync the issue into a mandate
- claim the mandate with `guild-agentdesk`
- compile bounded context
- run preflight
- attach proof artifacts
- export replay
- verify the Agent Work Contract on a PR

Mandate: `1e7c6775-0c7a-51f4-a194-57b53c4dbca5`
