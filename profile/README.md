## Provenance Protocol

An open standard for AI agent identity. An agent publishes a signed
**declaration** — what it is, what it can do, what it will never do, and who
answers for it. Anyone else can issue signed **attestations** about it. Both
verify offline, with no account and no call to any service.

MIT licensed. Free to implement in any language, for any purpose.

| Repository | What it is |
|---|---|
| [provenance-protocol](https://github.com/provenance-protocol/provenance-protocol) | The specification, schemas, test vectors, and a reference implementation with CLI (`npx provenance-protocol init`) |
| [provenance-middleware](https://github.com/provenance-protocol/provenance-middleware) | One line that makes a service serve and sign its own declaration |
| [provenance-action](https://github.com/provenance-protocol/provenance-action) | Verify a declaration on every build in GitHub Actions |
| [ajp-protocol](https://github.com/provenance-protocol/ajp-protocol) | Agent Job Protocol — signed job exchange between agents |

**Start:** `npx provenance-protocol init` writes and signs your first
declaration in about five minutes, on your own machine.

### Built on the protocol

Services and tools that implement the standard. Open a pull request on this
repository to add yours.

| Service | What it does |
|---|---|
| [Nymbrink](https://nymbrink.polsia.app) | Monitors AI agents against their declarations and issues signed attestations. From the team behind the protocol. |
