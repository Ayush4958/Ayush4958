# My Contributions to the CNCF Ecosystem 

Contributions span 3 repositories under the CNCF Ecosystem.

---

## Repo: `kubernetes-sigs/node-readiness-controller`

### Pull Requests

- [#381](https://github.com/kubernetes-sigs/node-readiness-controller/pull/381) :- Opened a PR for Clear FailedNodes on successful node reconciliation. Also fixes a state leak in the NodeReconciler.
- [#359](https://github.com/kubernetes-sigs/node-readiness-controller/pull/359) :- [test] add e2e coverage for missing condition handling and finalizer cleanup.
- [#437](https://github.com/kubernetes-sigs/node-readiness-controller/pull/437) :- feat(chart): Added topologySpreadConstraints support for multi-zone high availability.
- [#456](https://github.com/kubernetes-sigs/node-readiness-controller/pull/456) :- feat(chart): Adding Prometheus ServiceMonitor support (open).
  
### Issues Created

- [#376](https://github.com/kubernetes-sigs/node-readiness-controller/issues/376) :- [Bug] Open NodeReconciler permanently leaks transient errors into Status.FailedNodes
- [#358](https://github.com/kubernetes-sigs/node-readiness-controller/issues/358) :- [FEATURE] Add missing E2E test coverage for Finalizer Cleanup and Missing Conditions
- [#375](https://github.com/kubernetes-sigs/node-readiness-controller/issues/375) :- [BUG] Deleting a NodeReadinessRule orphans bootstrap completed annotations on Nodes

### PRs Reviewed

- [#388 - (by tejassinghbhati)](https://github.com/kubernetes-sigs/node-readiness-controller/pull/388) :- Reviewed this PR and left feedback for adding a helm upgrade section, and requested a line noting users can supply their own overrides file using `-f custom-values.yaml`.
- [#411 - (by vishnukothakapu)](https://github.com/kubernetes-sigs/node-readiness-controller/pull/411) :- Reviewed this PR adding a PodDisruptionBudget for high availability, suggest them to improve the test case and pointing out the condition which is being silently dropped.
- [#406 - (by rawadhossain)](https://github.com/kubernetes-sigs/node-readiness-controller/pull/406) :- Reviewed this PR adding a `node_readiness_build_info` metric.

---

## Repo: `velero-io/velero`
 
### Pull Requests

- [#10253](https://github.com/velero-io/velero/pull/10253) :- Opened a refactor PR to remove legacy hardcoding of `resticrepositories` from the restore controller.
- [#10248](https://github.com/velero-io/velero/pull/10248) :- Opened a refactor PR to remove deprecated `BackupVolumeInfo` logic from the restore loop.

### Issues Created

- [#10246](https://github.com/velero-io/velero/issues/10246) :- [Feature Request] Proposed native Client-Side Encryption (CSE) support for backup payloads to mitigate risks from storage misconfigurations.

### PRs Reviewed

- [#10252 - (by Ralthos)](https://github.com/velero-io/velero/pull/10252) :- Reviewed the PR & Requested changes that returning `nil` on no artifacts would hang the CLI for 1 min (it only polls `DownloadURL`, ignoring phase) and suggested checking phase in the CLI before creating the `DownloadRequest`. Also flagged a hardcoded 13 phase test array as a false safety net that won't catch new API phases.
---

 ## Repo: `headlamp-k8s/plugins`

 ### Pull Requests
 
 - [#1088](https://github.com/headlamp-k8s/plugins/pull/1088) :- fix(app-catalog): resolve memory leaks in release detail view- #1088

### Issues Created 

- [#1085](https://github.com/headlamp-k8s/plugins/issues/1085) :- [Bug] app-catalog: Releases Detail.tsx lacks fetch cancellation & leaks recursive timeout
