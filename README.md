# comportexviz-nupic

This uses a [temporary fork](https://github.com/mrcslws/comportexviz/tree/nupic-hack) of ComportexViz. Specifically, the "nupic-hack" branch.

Install dependencies. (TODO)

Host the "public" folder on a local webserver.

~~~
cd public
python -m SimpleHTTPServer 8000
~~~

Run the websocket.

~~~
python server.py
~~~

Navigate to http://localhost:8000
