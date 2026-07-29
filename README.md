# envelope

Integrity envelope for untrusted content — delimiter escaping, constant-time MAC, closed source classes (K3 kernel, couche 3).

Born from the hub dismantling ([ADR-0020](https://github.com/libre-ai/governance/blob/main/docs/adr/0020-general-activation-and-hub-dismantling.md)): history carried by `git filter-repo` from `libre-ai/libre-ai`, which remains the clonable archive. Consumed as a sha-pinned GitHub git-dep.

## Verify

```sh
bun install --frozen-lockfile
bun run check
```
