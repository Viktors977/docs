---
id: ory-update-opl
title: ory update opl
description: ory update opl Update the Ory Permission Language file in Ory Cloud
---

<!--
This file is auto-generated.

To improve this file please make your change against the appropriate "./cmd/*.go" file.
-->
## ory update opl

Update the Ory Permission Language file in Ory Cloud

### Synopsis

Update the Ory Permission Language file in Ory Cloud. Legacy namespace definitions will be overwritten.

```
ory update opl <project-id> [flags]
```

### Examples

```
$ {{ .CommandPath }} ecaaa3cb-0730-4ee8-a6df-9553cdfeef89 \
	--file /path/to/namespace_config.ts

class Example implements Namespace {}

```

### Options

```
  -f, --file string      Configuration file (file://namespace_config.ts, https://example.org/namespace_config.ts, ...) to update the Ory Permission Language config
      --format string    Set the output format. One of table, json, yaml, and json-pretty. (default "default")
  -h, --help             help for opl
      --project string   The project to use
```

### Options inherited from parent commands

```
  -c, --config string   Path to the Ory Cloud configuration file.
  -q, --quiet           Be quiet with output printing.
  -y, --yes             Confirm all dialogs with yes.
```

### SEE ALSO

* [ory update](ory-update)	 - Update resources
