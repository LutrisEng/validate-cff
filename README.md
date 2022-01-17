<!-- SPDX-FileCopyrightText: 2021 Lutris Engineering, Inc -->
<!-- SPDX-License-Identifier: CC0-1.0 -->
<!-- SPDX-FileContributor: Piper McCorkle <piper@lutris.engineering> -->

# validate-cff

Example:

```yaml
on:
  push:
    branches:
      - main
  pull_request:

jobs:
  validate_citation:
    name: Validate CITATION.cff
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - uses: LutrisEng/validate-cff@v1.0.0
```
