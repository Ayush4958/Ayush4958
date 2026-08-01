# My Contributions to the Fedimint Organization

Contributions span two repositories under the `fedimint` org: **fedimint-sdk** and **fedimint-sdk-ffi**.

---

## Repo: `fedimint/fedimint-sdk`

### Pull Requests

**Open**
- [#324 - fix: use cross platform crypto for checksum verification in expo plugin](https://github.com/fedimint/fedimint-sdk/pull/324) — Open PR fixing checksum verification in the Expo plugin by using a cross-platform crypto approach instead of a platform-specific one.
- [#314 - ci: unify PR workflows with dynamic path filtering](https://github.com/fedimint/fedimint-sdk/pull/314) — Open PR consolidating multiple PR/CI workflows into a unified one that uses dynamic path filtering to decide what runs.

**Merged**
- [#321 - fix: implement SHA-256 checksum verification for downloaded binaries](https://github.com/fedimint/fedimint-sdk/pull/321) — Added SHA-256 checksum verification for binaries downloaded by the SDK, to ensure integrity/security.
- [#309 - ci: trigger react native builds on 'core/types' package changes](https://github.com/fedimint/fedimint-sdk/pull/309) — Updated CI so that React Native builds are triggered whenever the `core/types` package changes, fixing a gap where such changes weren't being tested.

### Issues Created

**Open**
- [#322 - Expo plugin checksum verification fails on Windows due to shasum/cut dependency](https://github.com/fedimint/fedimint-sdk/issues/322) — Reported that checksum verification in the Expo plugin fails on Windows because it relies on Unix-only tools (`shasum`/`cut`).
- [#311 - Prop: Optimize and unify PR workflows using dynamic path filtering](https://github.com/fedimint/fedimint-sdk/issues/311) — Proposed optimizing and consolidating PR workflows using dynamic path filtering (later addressed via PR #314).

**Closed**
- [#307 - CI: Changes to packages/core do not trigger React Native checks on PR](https://github.com/fedimint/fedimint-sdk/issues/307) — Reported that changes to the `packages/core` package weren't triggering React Native CI checks on PRs (later fixed via PR #309).

---

## Repo: `fedimint/fedimint-sdk-ffi`

### Pull Requests

**Merged**
- [#14 - Fix host compilation SDK Path & Added Nic CI workflow](https://github.com/fedimint/fedimint-sdk-ffi/pull/14) — Fixed an issue with the SDK path during host compilation and added a new CI workflow (Nic).
- [#13 - Fix the CI Linker Errors](https://github.com/fedimint/fedimint-sdk-ffi/pull/13) — Fixed linker errors that were occurring in the CI build pipeline.
