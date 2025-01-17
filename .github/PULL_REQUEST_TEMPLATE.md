* **Kind:** bugfix / enhancement / feature

<!-- For a bug fix, make sure the bug was already reported in an issue. -->

* Close #…

### Description

<!-- Please recap the motivation and/or implementation choices for this change. -->

### Checklist

<!-- You can remove all the check-boxes that are not applicable. -->

* [ ] Read the [CONTRIBUTING.md](https://github.com/ocaml-sf/learn-ocaml/blob/master/CONTRIBUTING.md) guide and:
  * [ ] Use [Atomic Commits](https://github.com/ocaml-sf/learn-ocaml/blob/master/CONTRIBUTING.md#atomic-commits) so each commit gathers a single logical change
  * [ ] Use [Conventional Commits](https://github.com/ocaml-sf/learn-ocaml/blob/master/CONTRIBUTING.md#conventional-commits) regarding commit messages (needed by our release toolchain)
* [ ] Add/update [tests](https://github.com/ocaml-sf/learn-ocaml/tree/master/tests#readme)
  <!-- if the change impacts the grading feature. -->
* [ ] Add/update [documentation](https://github.com/ocaml-sf/learn-ocaml/tree/master/docs)
  <!-- if there are some user-facing changes. -->
* [ ] …
  <!-- you can add more items to summarize what remains to do. -->

<!-- You can leave this note below as a reminder for maintainers: -->
### Note to maintainers

* Read [this wiki page](https://github.com/ocaml-sf/learn-ocaml/wiki/Checklist-for-testing-and-merging-a-PR).
* Make sure the PR has a **milestone**.
* ***Assign*** yourself before merging.
* Either do a regular **merge**:
  * for PRs containing *several commits* following [conventional-commits](https://github.com/ocaml-sf/learn-ocaml/blob/master/CONTRIBUTING.md#conventional-commits),
  * or for PRs containing 1 commit shared with a later PR (to preserve the SHA1)
* Or do a **squash-merge**:
  * for PRs containing *only 1 commit* (not shared with a later PR),
  * or for PRs containing several commits that need not be kept in the history;
  * → ***Update the commit message header*** with a [conventional-commit type](https://github.com/ocaml-sf/learn-ocaml/blob/master/CONTRIBUTING.md#conventional-commits-examples),
  * → ***Add a footer*** `Close #…` if a related issue exists.
