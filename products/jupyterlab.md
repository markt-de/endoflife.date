---
title: JupyterLab
category: app
tags: app
permalink: /jupyterlab
versionCommand: jupyterlab --version
changelogTemplate: https://github.com/jupyterlab/jupyterlab/releases/tag/v__LATEST__

identifiers:
  - repology: jupyterlab

auto:
  methods:
    - git: https://github.com/jupyterlab/jupyterlab.git

# eol(x) = releaseDate(x+1)
releases:
-   releaseCycle: "4.4"
    releaseDate: 2025-04-03
    eol: false
    latest: "4.4.3"
    latestReleaseDate: 2025-05-26

-   releaseCycle: "4.3"
    releaseDate: 2024-10-30
    eol: 2025-04-03
    latest: "4.3.6"
    latestReleaseDate: 2025-03-14

-   releaseCycle: "4.2"
    releaseDate: 2024-05-06
    eol: 2024-10-30
    latest: "4.2.6"
    latestReleaseDate: 2024-11-16

-   releaseCycle: "4.1"
    releaseDate: 2024-02-05
    eol: 2024-05-06
    latest: "4.1.8"
    latestReleaseDate: 2024-04-26

-   releaseCycle: "4.0"
    releaseDate: 2023-05-15
    eol: 2024-02-05
    latest: "4.0.13"
    latestReleaseDate: 2024-02-26

-   releaseCycle: "3.6"
    releaseDate: 2023-02-02
    eol: 2023-05-15
    latest: "3.6.8"
    latestReleaseDate: 2024-08-26

-   releaseCycle: "3.5"
    releaseDate: 2022-10-24
    eol: 2023-02-02
    latest: "3.5.3"
    latestReleaseDate: 2023-01-23

-   releaseCycle: "3.4"
    releaseDate: 2022-05-03
    eol: 2022-10-24
    latest: "3.4.7"
    latestReleaseDate: 2022-09-13

-   releaseCycle: "3.3"
    releaseDate: 2022-03-02
    eol: 2022-05-03
    latest: "3.3.4"
    latestReleaseDate: 2022-04-15

-   releaseCycle: "3.2"
    releaseDate: 2021-10-14
    eol: 2022-03-02
    latest: "3.2.9"
    latestReleaseDate: 2022-02-04

-   releaseCycle: "3.1"
    releaseDate: 2021-07-27
    eol: 2021-10-14
    latest: "3.1.18"
    latestReleaseDate: 2021-10-07

-   releaseCycle: "3.0"
    releaseDate: no information (https://github.com/jupyterlab/jupyterlab/releases?page=23)
    eol: 2021-07-27
    latest: "3.0.16"
    latestReleaseDate: 2021-05-18

---

> [JupyterLab](https://jupyter.org/) is a highly extensible, feature-rich notebook
> authoring application and editing environment, and is a part of Project Jupyter, a large
> umbrella project centered around the goal of providing tools (and standards) for interactive
> computing with computational notebooks.


JupyterLab does not follow a strictly documented release policy but adheres to semantic
versioning. The latest major version is the only one actively maintained. While patch releases
are typically backward compatible, breaking changes may occasionally occur in minor versions.

