# jenkins-port-allocator-plugin

## Prerequisites

Install maven and java8.

## Build

To build a .hpi file, run:

``` bash
mvn verify
```

To update the plugin, upload the `target/port-allocator.hpi` file in jenkins under the plugins configuration: https://jenkins.4teamwork.ch/pluginManager/advanced
