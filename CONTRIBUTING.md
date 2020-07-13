# Contributing

Interested in contributing to KERNEL? Want to request a new feature?
Before you do, please read the following guidelines.

## Getting Started

**Dependencies**:

1. Python 2. I currently run version `2.7.17`
2. [Mkdocs](https://www.mkdocs.org/). I currently run version `1.0.4`

_There can be some confusion setting up your environment given the mess that is Python 2 and 3. I have both installed on my machine and simply use `python` for Python 2 and `python3` for Python 3._

![Kernel env setup](docs/assets/images/kernel-env.png)

**Steps to run locally**:

1. `git clone https://github.com/andytudhope/kernel.git`
2. `cd kernel`
3. `mkdocs serve`

You can run run `mkdocs build` to build the production site, but that shouldn't be necessary for contributions as you can simply use `serve` to check that your changes work before submitting a PR.

### Missing a feature?

You can request a new feature by submitting an issue to our GitHub Repository.
If you would like to implement a new feature, please submit an issue with a
proposal for your work first, to be sure that it is of use for everyone, as
KERNEL is highly curated. Please consider what kind of
change it is:

* For a **major feature**, first open an issue and outline your proposal so
  that it can be discussed. This will also allow us to better coordinate our
  efforts, prevent duplication of work, and help you to craft the change so
  that it is successfully accepted into the project.

* **Small features and bugs** can be crafted and directly submitted as a Pull
  Request. However, there is no guarantee that your feature will make it into
  the `master`, as it's always a matter of opinion whether if benefits the
  overall functionality of the project.

## Submission guidelines

### Submitting an issue

Before you submit an issue, please search the issue tracker, maybe an issue for
your problem already exists and the discussion might inform you of workarounds
readily available.

We want to fix all the issues as soon as possible, but before fixing a bug we
need to reproduce and confirm it. In order to reproduce bugs we will
systematically ask you to provide a minimal reproduction scenario using the
custom issue template. Please stick to the issue template.

Unfortunately we are not able to investigate / fix bugs without a minimal
reproduction scenario, so if we don't hear back from you we may close the issue.

### Submitting a Pull Request (PR)

Search GitHub for an open or closed PR that relates to your submission. You
don't want to duplicate effort. If you do not find a related issue or PR,
go ahead.

1. **Test locally**: Fork the project, set up your local development environment,
  make your changes in a separate git branch and add descriptive messages to
  your commits.

2. **Pull Request**: After building the theme, commit the compiled output, push
  your branch to GitHub and send a PR to `kernel:master`. If we
  suggest changes, make the required updates, rebase your branch and push the
  changes to your GitHub repository, which will automatically update your PR.

After your PR is merged, you can safely delete your branch and pull the changes
from the main (upstream) repository.
