# envelope Canonical Agent Rules

Integrity envelope for untrusted content (K3 kernel, couche 3). Born from the hub dismantling (ADR-0020): history carried by git
filter-repo from packages/envelope; the hub remains the clonable archive.
The governance gate template is consumed as pinned reusable workflows and
a pinned tooling git-dep — never duplicated. Consumers install this
package as a sha-pinned GitHub git-dep.

Run `bun run check` before pushing; never hide a red test. Stage files
before tree-walking gates. Security > quality > performance > completeness.
