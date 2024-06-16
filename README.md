# GitHub Step Summarizer

![Continuous Integration](https://img.shields.io/github/actions/workflow/status/bitwizeshift/github-step-summarizer/.github%2Fworkflows%2Fpostsubmit.yaml?logo=github)
[![GitHub Release](https://img.shields.io/github/v/release/bitwizeshift/github-step-summarizer?include_prereleases)][github-releases]
[![readthedocs](https://img.shields.io/badge/docs-readthedocs-blue?logo=readthedocs&logoColor=white)][docs]
[![Godocs](https://img.shields.io/badge/docs-godocs-blue?logo=go&logoColor=white)][go-docs]

This is a small utility that lets you easily template summaries for your
GitHub Actions Step Summary. It's a simple command-line tool that reads a
template file, and will automatically output to `${GITHUB_STEP_SUMMARY}`.

[docs]: https://bitwizeshift.github.io/github-step-summarizer/
[go-docs]: https://pkg.go.dev/github.com/bitwizeshift/github-step-summarizer
[github-releases]: https://github.com/bitwizeshift/github-step-summarizer/releases
