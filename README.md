# BlazeDS Turnkey Apache Royale Samples

The [Adobe BlazeDS Turnkey bundle](https://github.com/joshtynjala/blazeds-turnkey-archive) includes a number of sample frontend applications created with [Apache Flex](https://flex.apache.org/), and meant to run on Adobe Flash Player. The samples contained in this repository are designed to replace the original Flex apps with new versions built with [Apache Royale](https://royale.apache.org/) instead.

Each sample can be compiled using [vscode-as3mxml](https://marketplace.visualstudio.com/items?itemName=bowlerhatllc.vscode-as3mxml) or [asconfigc](https://npmjs.com/package/asconfigc). Then, the generated files may be copied from _bin/js-debug_ into the appropriate subdirectory inside the BlazeDS Turnkey bundle's _webapps/samples/_ subdirectory. For instance, if you build the **testdrive-101** sample, you'd copy the contents of _testdrive-101/bin/js-debug_ into _webapps/samples/testdrive-101_.

Some samples in the BlazeDS Turnkey bundle contain _.jsp_ files used by the server. You must keep those files for the samples to work.