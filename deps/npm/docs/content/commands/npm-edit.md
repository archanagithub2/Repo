---
title: npm-edit
section: 1
description: Edit an installed package
---

### Synopsis

<!-- AUTOGENERATED USAGE DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/commands/edit.js -->

```bash
npm edit <pkg>[/<subpkg>...]
```

<!-- automatically generated, do not edit manually -->
<!-- see lib/commands/edit.js -->

<!-- AUTOGENERATED USAGE DESCRIPTIONS END -->

Note: This command is unaware of workspaces.

### Description

Selects a dependency in the current project and opens the package folder in
the default editor (or whatever you've configured as the npm `editor`
config -- see [`npm-config`](npm-config).)

After it has been edited, the package is rebuilt so as to pick up any
changes in compiled packages.

For instance, you can do `npm install connect` to install connect
into your package, and then `npm edit connect` to make a few
changes to your locally installed copy.

### Configuration

<!-- AUTOGENERATED CONFIG DESCRIPTIONS START -->
<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->
#### `editor`

* Default: The EDITOR or VISUAL environment variables, or 'notepad.exe' on
  Windows, or 'vim' on Unix systems
* Type: String

The command to run for `npm edit` and `npm config edit`.

<!-- automatically generated, do not edit manually -->
<!-- see lib/utils/config/definitions.js -->

<!-- AUTOGENERATED CONFIG DESCRIPTIONS END -->

### See Also

* [npm folders](/configuring-npm/folders)
* [npm explore](/commands/npm-explore)
* [npm install](/commands/npm-install)
* [npm config](/commands/npm-config)
* [npmrc](/configuring-npm/npmrc)
