# dep importers testdata
This repo contains testdata for the dep importers:

* Untagged revision that isn't HEAD: `v1.0.3-1-g6ac5f8e (6ac5f8ea1b2a2f06306a2c9ca57cc3e0504b6d27)`
* Non-semver tag: `beta1 (7913ab26988c6fb1e16225f845a178e8849dd254)`
* Semver branch with non-HEAD commits: `v2`
* Semver tag on the non-default branch, not HEAD: `v2.0.0-alpha1 (347760b50204948ea63e531dd6560e56a9adde8f)`
* Multiple semver tags that match a caret constraint: `v1.0.2 (788963efe22e3e6e24c776a11a57468bb2fcd780)`, `v1.0.3 (f637de64b98a0c6dd2d8ea70c6c7dc75f24af952)`
* Untagged revision, not HEAD: `dbb4d971f45d414b34a230426d90e30ba7a92dcc`
* Revision with multiple tags: `v1.0.4 stable (34cf993cc346f65601fe4356dd68bd54d20a1bfe)`
* Subpackages (`./subpkgA`, `./subpkgB`).
* External dependencies (`./subpkgA` -> `github.com/sdboyer/deptest`).
