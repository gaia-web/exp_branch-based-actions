# exp_branching-actions

This is an experimental repo.

When pushing a branch that has name starts with `a_`, the GitHub Action `a` would be triggered to run. When pushing a branch that has name starts with `a-utils`, the GitHub Action `a-utils` would be triggered to run. Otherwise, no GitHub Action would be triggered.
When a PR related to "a_" and "a-utils_" is created or updated, the action would be triggered and the result would be shown on the PR. If it fails to run, it could potentially be set to prevent the PR to be merged. Usually, the actual action could be a build script or unit tests.
