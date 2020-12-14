# JavaScript Oldies for Visual Studio Code

[<img src=https://raw.githubusercontent.com/prantlf/vscode-javascript-oldies/master/logo.png height=20 alt=Logo>][from the marketplace]
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE)
[![Build Status](https://github.com/prantlf/vscode-javascript-oldies/workflows/Test/badge.svg)](https://github.com/prantlf/vscode-javascript-oldies/actions)

> Collects extensions for [Visual Studio Code] to help maintaining JavaScript projects written with old frameworks and tools.

Do you have to code with old technologies like AMD, Grunt, JSHint or Karma? Do you have to document with JSDoc? Don't despair, you will still be able to use the modern VS Code efficiently :-) Check out the great extensions below:

* [Debugger for Chrome](#debugger-for-chrome)
* [Document This](#document-this)
* [Fold on Open](#fold-on-open)
* [JSDoc Live Preview](#jsdoc-live-preview)
* [JSHint](#jshint)
* [Karma Problem Matchers](#karma-problem-matchers)
* [Require Module Support](#require-module-support)
* [Task Explorer](#task-explorer)
* [TODO Tree](#todo-tree)

## Installation

Install this extension to your Visual Studio Code [from the marketplace], or download a specific version of a [released package] and install it from the file.

## Debugger for Chrome

Debug an application or [Karma tests](https://github.com/prantlf/vscode-karma-problem-matchers#debug) that run in the browser. Just add a launcher, place breakpoints and hit F5. It will not work right away - you will need to reload the debugging session by clicking on the green circling arrow once the test finish, so that the breakpoints get hit. Enable just the tests that you want to debug (by using `fdescribe`, for example) to be more efficient.

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome).

## Document This

Place the cursor on the name of a class or function and hit `Ctrl+Alt+D` twice. (Yes, hit the `D` twice.) Continue writing the documentation comment. If you want describe an object member, place the cursor on the right side of the colon in the member declaration.

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=oouo-diogo-perdigao.docthis).

## Fold on Open

Be rid of the endless scrolling over the "green lines", when you want to inspect the code. [Collapse all block comments automatically](https://github.com/prantlf/vscode-fold-on-open#fold-on-open), when you open a source file.

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=prantlf.fold-on-open).

## JSDoc Live Preview

If you bind the keys `Shift+Alt+V` the command "JSDoc: Show Preview" command, you will be able to open the preview panel quickly like with `Shift+Cmd+V` for Markdown.

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=Perkovec.jsdoc-live-preview).

## JSHint

Make sure that you install `jshint` to `node_modules` in your project and configure it in the `.jshintrc` file.

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=dbaeumer.jshint).

## Karma Problem Matchers

Observe the failed tests in the Problems window. [Select the problem matcher](https://github.com/prantlf/vscode-karma-problem-matchers#configuration) for your test framework, reporter and browser in your [task running Karma](https://github.com/prantlf/vscode-karma-problem-matchers#run).

Also, if breakpoints do not get hit during debugging, make sure that you selected the proper problem matcher. If you see an animation waiting for the pre-launch task to finish, the expected text pattern in the terminal was not detected.

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=prantlf.karma-problem-matchers).

## Require Module Support

Jump to the module where the selected class or function is declared. [Configure](https://github.com/anacierdem/vscode-requirejs#settings) the `baseURL` path to your module sources and optionally the RequireJS config file. Then enjoy the jump by hitting F12 and F4. (The "Go To Declaration" command will offer you the place where the imported argument is declared too.)

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=lici.require-js).

## TODO Tree

If you still hope that the management will care about fixing the lots of `TODO` and `FIXME` comments... At least you can inspect them in a list or tree in a sidebar opened from the action toolbar.

See also the [marketplace page](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree).

## License

Copyright (c) 2020 Ferdinand Prantl

Licensed under the MIT license.

The logo was based on an [original icon](https://www.iconfinder.com/icons/998217/announcement_audio_loud_mic_microphone_radio_studio_icon) published by [Chamestudio Pvt Ltd](https://www.iconfinder.com/chamedesign) under the [Creative Commons Attribution 3.0 Unported (CC BY 3.0)](https://creativecommons.org/licenses/by/3.0/) license. Thank you!

[Visual Studio Code]: https://code.visualstudio.com/
[from the marketplace]: https://marketplace.visualstudio.com/items?itemName=prantlf.javascript-oldies
[released package]: https://github.com/prantlf/vscode-javascript-oldies/releases
