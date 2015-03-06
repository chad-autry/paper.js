# Paper.js - The Swiss Army Knife of Vector Graphics Scripting

This repository is simply a redistribution of the built source code of paper.js for use with Browserify. The reason being the official npm build has more dependencies than is required for the browser.
For the actual source code of paper.js and support please see:

- Website: <http://paperjs.org/>
- Discussion forum: <http://groups.google.com/group/paperjs>
- Mainline source code: <https://github.com/paperjs/paper.js>
- Twitter: [@paperjs](http://twitter.com/paperjs)
- Daily development builds: <http://paperjs.org/download/>

## Installing Paper.js

Right now the way to install this version of paper.js is straight from github. It may or may not be published to npm in the near future.

## Version

The version published from this repository is

- `paper-core.js` – The core version for the browser, without PaperScript support nor Acorn.js. Use this to shave off some bytes when working with JavaScript directly.

It is expected a browserify based app will run its own minification after browserify


## License

See the file [LICENSE](https://github.com/paperjs/paper.js/blob/master/LICENSE.txt)
