These are test cases for the dep importers

* Untagged revision that isn't HEAD (v1.0.0-2-gabc123).
* Non-semver tag (beta1).
* Semver branch (v2) with multiple commits.
* Semver tag on the non-default branch, not HEAD.
* Multiple semver tags that match a caret constraint
  (v1.0.1, v1.0.2).
* Subpackages (`./subpkgA`, `./subpkgB`).
* External dependencies (`./subpkgA` -> `github.com/sdboyer/deptest`).
