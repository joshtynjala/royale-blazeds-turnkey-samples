# BlazeDS Turnkey testdrive-datapush sample

## Requirements

- [Apache Royale](https://royale.apache.org/)
- [BlazeDS Turnkey Bundle](https://github.com/joshtynjala/blazeds-turnkey-archive).

## Usage

1. Compile the project using [vscode-as3mxml](https://marketplace.visualstudio.com/items?itemName=bowlerhatllc.vscode-as3mxml) or [asconfigc](https://npmjs.com/package/asconfigc).

2. In the directory where you extracted the BlazeDS Turnkey Bundle, delete everything except _startfeed.jsp_ and _stopfeed.jsp_ in the _webapps/samples/testdrive-datapush_ subdirectory.

3. Copy the compiled files from this project's _bin/js-debug_ directory into _webapps/samples/testdrive-datapush_.

4. Open a web browser and load _http://localhost:8080/samples/testdrive-datapush/startfeed.jsp_ to start the feed.

5. Then, load _http://localhost:8080/samples/testdrive-datapush_ to see the sample.

6. Finally, load _http://localhost:8080/samples/testdrive-datapush/stopfeed.jsp_ to stop the feed.
