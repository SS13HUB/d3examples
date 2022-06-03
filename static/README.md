
### Static cache

---

This folder contains static cache.

Some of it - it's local development, some of it - copy of polupar libraries, just in case *plus* for independent CPU and connection performance.

Below you can learn about what was cached.

---

##### Cached files list:

Note: Symbol "." stands for root directory of git project, not current directory.

| File | Source |
|:-|:-|
| **> [./static/bootstrap/3.3.6/css/](./bootstrap/3.3.6/css/)** |
| [bootstrap.min.css](./bootstrap/3.3.6/css/bootstrap.min.css) | http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css |
| [bootstrap.min.css.map](./bootstrap/3.3.6/css/bootstrap.min.css.map) | http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css.map |
| **> [./static/js/d3/](./d3/)** |
| [d3.v1.js](./d3/d3.v1.js) | https://d3js.org/d3.v1.js |
| [d3.v2.js](./d3/d3.v2.js) | https://d3js.org/d3.v2.js |
| [d3.v3.js](./d3/d3.v3.js) | https://d3js.org/d3.v3.js |
| [d3.v4.js](./d3/d3.v4.js) | https://d3js.org/d3.v4.js |
| [d3.v5.js](./d3/d3.v5.js) | https://d3js.org/d3.v5.js |
| [d3.v6.js](./d3/d3.v6.js) | https://d3js.org/d3.v6.js |
| [d3.v7.js](./d3/d3.v7.js) | https://d3js.org/d3.v7.js |
| **> [./static/js/d3/min/](./d3/min)** |
| [d3.v4-2-2.min.js](./d3/min/d3.v4-2-2.min.js) | https://cdnjs.cloudflare.com/ajax/libs/d3/4.2.2/d3.min.js |
| [d3.v4-9-1.min.js](./d3/min/d3.v4-9-1.min.js) | https://cdnjs.cloudflare.com/ajax/libs/d3/4.9.1/d3.min.js |
| **> [./static/data/](./data/)** |
| [africa.json](./data/africa.json) | [https://gist.github.com/d3indepth/3ccd770923a61f26f55156657e2f51e8/#file-africa-json](https://gist.githubusercontent.com/d3indepth/3ccd770923a61f26f55156657e2f51e8/raw/9a33b25b8d6cfece3bc7ea5379c733709b00fbe1/africa.json) |
| [ireland.json](./data/ireland.json) | https://gist.github.com/2183412 |
| [ne_110m_land.json](./data/ne_110m_land.json) | [https://gist.github.com/d3indepth/f28e1c3a99ea6d84986f35ac8646fac7#file-ne_110m_land-json](https://gist.githubusercontent.com/d3indepth/f28e1c3a99ea6d84986f35ac8646fac7/raw/c58cede8dab4673c91a3db702d50f7447b373d98/ne_110m_land.json) |


---

<!--
/// Node.js code for generating D3 lib files' names for different versions, for table above: ///

for (let i = 1; i < 8; i++) {
	console.log("| [d3.v" + i + ".js](./d3/d3.v" + i + ".js) | https://d3js.org/d3.v" + i + ".js |");
}
-->
