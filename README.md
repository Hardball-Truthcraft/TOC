# TOC
<!-- TOC -->
<!-- /TOC -->


name: TOC Generator
on:
  pull_request:
    paths: ["README.md", "docs/**/*.md"]
jobs:
  toc:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: technote-space/toc-generator@v4
