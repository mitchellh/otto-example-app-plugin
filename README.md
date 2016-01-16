# Otto Example App Plugin

This repository contains an example app type plugin for
[Otto](https://www.ottoproject.io). App types enable Otto to detect and
work with new types of applications.

## Building the Plugin

To build the plugin, compile it like a normal go executable:

```
$ go get
$ go build -o otto-plugin-example
```

The output name of "otto-plugin-example" is important. Otto looks for
the pattern `otto-plugin-*` to find plugins.
