# My Contributions to the Fedimint Organization

Contributions span two repositories under the `fedimint` org: **fedimint-sdk** and **fedimint-sdk-ffi**.

---

## Repo: `fedimint/fedimint-sdk`

### Pull Requests

**Merged**
- [#429](https://github.com/fedimint/fedimint-sdk/pull/429) - Added an error message shown when wallet status is checked before joining a federation.
- [#428](https://github.com/fedimint/fedimint-sdk/pull/428) - Replaced the generic guardian timeout with a dedicated wait timeout specifically for the scanner.
- [#395](https://github.com/fedimint/fedimint-sdk/pull/395) - Wired up devimint integration tests to run as part of the mapped CI workflow.
- [#389](https://github.com/fedimint/fedimint-sdk/pull/389) - Implemented storage for federation metadata along with a facade for consensus projection.
- [#357](https://github.com/fedimint/fedimint-sdk/pull/357) - Implemented a proper end-to-end onboarding flow for the SDK.
- [#328](https://github.com/fedimint/fedimint-sdk/pull/328) - Added a missing `blurred` CSS class so the mnemonic is properly hidden/obscured in the UI.
- [#327](https://github.com/fedimint/fedimint-sdk/pull/327) - Fixed errors from `MnemonicManager` that were being silently swallowed, mapping them to clear, user-friendly messages in the Vite demo.
- [#324](https://github.com/fedimint/fedimint-sdk/pull/324) - Fixed checksum verification in the Expo plugin by using a cross-platform crypto approach instead of a platform-specific one.
- [#321](https://github.com/fedimint/fedimint-sdk/pull/321) - Added SHA-256 checksum verification for binaries downloaded by the SDK, to ensure integrity/security.
- [#309](https://github.com/fedimint/fedimint-sdk/pull/309) - Updated CI so that React Native builds are triggered whenever the `core/types` package changes, fixing a gap where such changes weren't being tested.


### Issues Created

- [#380](https://github.com/fedimint/fedimint-sdk/issues/380) - T4 FFI Shape Spike.
- [#326](https://github.com/fedimint/fedimint-sdk/issues/326) - Reported that in the Vite example app, all SDK validation errors were swallowed and surfaced only as a generic "Operation failed".
- [#325](https://github.com/fedimint/fedimint-sdk/issues/325) - Reported a bug where the mnemonic eye (show/hide) button does not blur the text.
- [#322](https://github.com/fedimint/fedimint-sdk/issues/322) - Reported that checksum verification in the Expo plugin fails on Windows because it relies on Unix-only tools (`shasum`/`cut`).
- [#311](https://github.com/fedimint/fedimint-sdk/issues/311) - Proposed optimizing and consolidating PR workflows using dynamic path filtering.
- [#307](https://github.com/fedimint/fedimint-sdk/issues/307) - Reported that changes to the `packages/core` package weren't triggering React Native CI checks on PRs (later fixed via PR #309).

---

## Repo: `fedimint/fedimint-sdk-ffi`

### Pull Requests

**Merged**
- [#14](https://github.com/fedimint/fedimint-sdk-ffi/pull/14) — Fixed an issue with the SDK path during host compilation and added a new CI workflow (Nic).
- [#13](https://github.com/fedimint/fedimint-sdk-ffi/pull/13) — Fixed linker errors that were occurring in the CI build pipeline.
