---
layout: layout.pug
navigationTitle:  dcos node
title: dcos node
menuWeight: 11
excerpt: Displaying DC/OS node information

enterprise: false
---


# Description
View DC/OS node information.

# Usage

```bash
dcos node [OPTION]
```

# Options

| Name, shorthand | Default | Description |
|---------|-------------|-------------|
| `--help, h`   |             |  Print usage. |
| `--info`   |             |  Print a short description of this subcommand. |
| `--json`   |             |  Print JSON-formatted data. |
| `--version, v`   |             | Print version information. |

# Child commands

| Command | Description |
|---------|-------------|
| [dcos node diagnostics](/1.12/cli/command-reference/dcos-node/dcos-node-diagnostics/)   | View the details of diagnostics bundles. |
| [dcos node diagnostics create](/1.12/cli/command-reference/dcos-node/dcos-node-diagnostics-create/)   | Create a diagnostics bundle.|
| [dcos node diagnostics delete](/1.12/cli/command-reference/dcos-node/dcos-node-diagnostics-delete/)   | Delete a diagnostics bundle.|
| [dcos node diagnostics download](/1.12/cli/command-reference/dcos-node/dcos-node-diagnostics-download/)   | Download a diagnostics bundle.|
| [dcos node list components](/1.12/cli/command-reference/dcos-node/dcos-node-list-components/)   | Print a list of available DC/OS components on specified node. |
| [dcos node log](/1.12/cli/command-reference/dcos-node/dcos-node-log/)   | Print the Mesos logs for the leading master node, agent nodes, or both. |
| [dcos node ssh](/1.12/cli/command-reference/dcos-node/dcos-node-ssh/)   | Establish an SSH connection to the master or agent nodes of your DC/OS cluster. |
