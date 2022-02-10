# Spiral Heatmap - Northern hemisphere sea ice extent 1978 to 2017

https://observablehq.com/@tomshanley/spiral-heatmap-northern-hemisphere-sea-ice-extent-1978-to-2@205

View this notebook in your browser by running a web server in this folder. For
example:

~~~sh
npx http-server
~~~

Or, use the [Observable Runtime](https://github.com/observablehq/runtime) to
import this module directly into your application. To npm install:

~~~sh
npm install @observablehq/runtime@4
npm install https://api.observablehq.com/@tomshanley/spiral-heatmap-northern-hemisphere-sea-ice-extent-1978-to-2@205.tgz?v=3
~~~

Then, import your notebook and the runtime as:

~~~js
import {Runtime, Inspector} from "@observablehq/runtime";
import define from "@tomshanley/spiral-heatmap-northern-hemisphere-sea-ice-extent-1978-to-2";
~~~

To log the value of the cell named “foo”:

~~~js
const runtime = new Runtime();
const main = runtime.module(define);
main.value("foo").then(value => console.log(value));
~~~
