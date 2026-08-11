# My Contributions to the CNCF Ecosystem 

Contributions span 3 repositories under the CNCF Ecosystem.

---

## Repo: `kubernetes-sigs/node-readiness-controller`

### Pull Requests

- [#381](https://github.com/kubernetes-sigs/node-readiness-controller/pull/381) :- Opened a PR for Clear FailedNodes on successful node reconciliation.Also fixes a state leak in the NodeReconciler.

- [#381](https://github.com/kubernetes-sigs/node-readiness-controller/pull/381) :- [test] add e2e coverage for missing condition handling and finalizer cleanup



### Issues Created

- [#376](https://github.com/kubernetes-sigs/node-readiness-controller/issues/376) :- [Bug] Open NodeReconciler permanently leaks transient errors into Status.FailedNodes

- [#358](https://github.com/kubernetes-sigs/node-readiness-controller/issues/358) :- [FEATURE] Add missing E2E test coverage for Finalizer Cleanup and Missing Conditions

- [#375](https://github.com/kubernetes-sigs/node-readiness-controller/issues/375) :- 
[BUG] Deleting a NodeReadinessRule orphans bootstrap completed annotations on Nodes


### PRs Reviewed

- [#388 - (by tejassinghbhati)](https://github.com/kubernetes-sigs/node-readiness-controller/pull/388) :- Reviewed this PR and left feedback for adding helm upgrade section and requested to add a line for users can supply their own overrides file using `-f custom-values.yaml`
---
