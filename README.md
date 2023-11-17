## Overview

Many application projects often share similar config, leading to duplication across projects. This library aims to solve this problem by providing a set of config that allow projects to inherit and reuse common config easily.

## Usage

You can include this library as a package in pb_project.yaml of your application project

```
packages:
  - name: corelib
    url: "https://github.com/rudderlabs/rudderstack-profiles-corelib/tag/schema_{{best_schema_version}}"
