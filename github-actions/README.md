# GitHub Actions

This directory contains some shared [GitHub Actions][docs] used on CIs managed
by the Rust Infrastructure team. There are no stability guarantees for these
actions, since they're supposed to only be used in infra managed by us.

* [**cancel-outdated-builds**](cancel-outdated-buildsd): cancel the build if a
  new commit is pushed.
* [**static-websites**](static-websites): deploy a directory to GitHub Pages.

[docs]: https://help.github.com/en/articles/about-actions
