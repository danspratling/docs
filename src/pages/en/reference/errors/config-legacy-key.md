---
# NOTE: This file is auto-generated from 'scripts/error-docgen.mjs'
# Do not make edits to it directly, they will be overwritten.
# Instead, change this file: https://github.com/withastro/astro/blob/main/packages/astro/src/core/errors/errors-data.ts
# Translators, please remove this note and the <DontEditWarning/> component.

layout: ~/layouts/MainLayout.astro
title: Legacy configuration detected.
i18nReady: true
githubURL: https://github.com/withastro/astro/blob/main/packages/astro/src/core/errors/errors-data.ts
setup: |
  import DontEditWarning from '../../../../components/DontEditWarning.astro';
---

<DontEditWarning />


> **ConfigLegacyKey**: Legacy configuration detected: `LEGACY_CONFIG_KEY`. (E07002)

## What went wrong?
Astro detected a legacy configuration option in your configuration file.

**See Also:**
-  [Configuration reference](/en/reference/configuration-reference/)
-  [Migration guide](/en/migrate/)


