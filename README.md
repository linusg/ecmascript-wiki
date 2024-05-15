# ECMAScript Wiki

This is a collection of information and links intended to be useful to developers of ECMAScript engines and tooling. Pull requests are most welcome! :^)

## Engines

| Logo | Name | Website | Source code | Implementation Language | License | Supported ES version |
|------|------|---------|-------------|-------------------------|---------|----------------------|
| <img width="32" src="https://boajs.dev/img/new_logo_yellow.svg"> | Boa | https://boajs.dev | https://github.com/boa-dev/boa | Rust | MIT | |
| | ChakraCore | | https://github.com/chakra-core/ChakraCore | C++ | MIT | |
| | Duktape | | https://github.com/svaarala/duktape | C | MIT | ES5.1, [ES6/7 (partial)](https://wiki.duktape.org/postes5features) |
| | Elk | | https://github.com/cesanta/elk | C | AGPL-3 | subset of ES6 | 
| <img width="32" src="https://avatars.githubusercontent.com/u/51185628"> | engine262 | https://engine262.js.org | https://github.com/engine262/engine262 | JavaScript | MIT | ESNext |
| | Escargot | | https://github.com/Samsung/escargot | C++ | LGPL-2.1 | ES2020 |
| | Flathead | | https://github.com/ndreynolds/flathead | C | MIT | |
| | goja | | https://github.com/dop251/goja | Go | MIT | ES5.1 |
| | GraalJS (GraalVM JavaScript) | https://www.graalvm.org/dev/reference-manual/js/ | https://github.com/oracle/graaljs | Java | UPL-1.0 | ESNext |
| <img width="32" src="https://raw.githubusercontent.com/facebook/hermes/main/doc/img/logo.svg"> | Hermes | | https://github.com/facebook/hermes | C++ | MIT | [ES6 with some exceptions](https://github.com/facebook/hermes/blob/main/doc/Features.md) |
| | JavaScriptCore | https://trac.webkit.org/wiki/JavaScriptCore | https://github.com/WebKit/WebKit/tree/main/Source/JavaScriptCore | C++, JavaScript | LGPL-2.1 | ESNext |
| <img width="32" src="https://github.com/jerryscript-project/jerryscript/blob/master/LOGO.png"> | JerryScript | https://jerryscript.net | https://github.com/jerryscript-project/jerryscript | C | Apache-2.0 | ES5.1 |
| | Jint | | https://github.com/sebastienros/jint | C# | BSD-2-Clause | ESNext |
| <img width="32" src="https://files.kiesel.dev/img/kiesel-bg.png"> | Kiesel | https://kiesel.dev | https://codeberg.org/kiesel-js/kiesel | Zig | MIT | |
| <img width="32" src="https://lh5.googleusercontent.com/J4azFveGFjfodaKPscuiL6AmtEp4TPYlmYwV1Rp09NrqH6KJZR73fmD_8XoH4uQpape7P8HxsmoRTOkAGNnSm0hFCWU_VyDydDgZ03rU0kMdySovQPoICI0beqfNlkC3NWNLv_A-zbvpPBVhyjljakhAww=s2048"> | LibJS | https://libjs.dev | https://github.com/SerenityOS/serenity/tree/master/Userland/Libraries/LibJS | C++ | BSD-2-Clause | ESNext |
| | mJS | https://mongoose-os.com | https://github.com/cesanta/mjs | C | GPL-2 | subset of ES6 |
| | Nashorn | https://openjdk.org/projects/nashorn | https://github.com/openjdk/nashorn | Java | GPL-2.0 | subset of ES6 |
| <img width="32" src="https://avatars.githubusercontent.com/u/108045716?s=32"> | Nova | | https://github.com/trynova/nova | Rust | | |
| <img width="32" src="https://raw.githubusercontent.com/CanadaHonk/porffor/main/logo.png"> | Porffor | https://porffor.goose.icu | https://github.com/CanadaHonk/porffor | JavaScript | MIT | |
| | QtJsEngine/Qv4 | https://doc.qt.io/qt-6/qjsengine.html | https://code.qt.io/cgit/qt/qtdeclarative.git/tree/src/qml | C++ | LGPL | |
| | QtScript | https://doc.qt.io/qt-5/qtscript-index.html | https://code.qt.io/cgit/qt/qtscript.git | C++ | LGPL | |
| | QuickJS | https://bellard.org/quickjs/ | https://github.com/bellard/quickjs | C | MIT | ES2020 |
| | Rhino | https://mozilla.github.io/rhino | https://github.com/mozilla/rhino | Java | MPL-2.0 | subset of ES6 |
| <img width="32" src="https://raw.githubusercontent.com/mozilla-spidermonkey/spidermonkey.dev/production/assets/img/spidermonkey-small.svg"> | Spidermonkey | https://spidermonkey.dev | https://searchfox.org/mozilla-central/source/js | C++, Rust, JavaScript | MPL-2.0 | ESNext |
| | Starlight | https://teletype.in/@starlight-js | https://github.com/Starlight-JS/starlight | Rust | MPL-2.0 | |
| ![image](https://v8.dev/_img/v8-outline.svg) | V8 | https://v8.dev | https://source.chromium.org/chromium/chromium/src/+/main:v8/ | C++, JavaScript | BSD | ESNext |
| | XS (Moddable SDK) | https://www.moddable.com | https://github.com/Moddable-OpenSource/moddable | C | LGPL-3 | ES2021 |

> **Note**
> _ESNext_ indicates that the engine generally targets the latest ECMAScript standard without major exceptions.

### Installers

- [esvu](https://github.com/devsnek/esvu) - esvu is your one-stop shop for all implementations of ECMAScript
- [jsvu](https://github.com/GoogleChromeLabs/jsvu) - JavaScript (engine) Version Updater

### Wrappers

- [eshost](https://github.com/bterlson/eshost) - A uniform wrapper around a multitude of ECMAScript hosts
- [eshost-cli](https://github.com/bterlson/eshost-cli) - Run ECMAScript code uniformly across any ECMAScript host

## Specifications

- [ECMA-262](https://tc39.es/ecma262) - ECMAScript Language Specification
- [ECMA-402](https://tc39.es/ecma402) - ECMAScript Internationalization API Specification

## Testing

### Test Suites

- [test262](https://github.com/tc39/test262) - Official ECMAScript Conformance Test Suite
- [LibJS tests](https://github.com/SerenityOS/serenity/tree/master/Userland/Libraries/LibJS/Tests) - Tests developed for LibJS with a Jest-like framework

### Test Results

- [test262.fyi](https://test262.fyi) - Daily runner of test262 for many engines
- [test262.report](https://test262.report) - test262 results for various engines (defunct as of 2022-09)
- [boajs.dev/boa/test262](https://boajs.dev/boa/test262) - test262 results for Boa
- [libjs.dev/test262](https://libjs.dev/test262) - test262 results for LibJS (AST, bytecode, parser tests)

### Test Runners

- [bterlson/test262-harness](https://github.com/bterlson/test262-harness) - Experimental harness for test262, uses eshost
- [linusg/libjs-test262](https://github.com/linusg/libjs-test262) - test262 runner for LibJS
- [LibJS `test-js`](https://github.com/SerenityOS/serenity/blob/master/Tests/LibJS/test-js.cpp) - Custom test runner for the LibJS tests

## Transpilers

TODO: Babel, Sucrase, SWC

## Websites

- [ECMAScript proposals](https://github.com/tc39/proposals)
- [TC39](https://tc39.es) - Ecma TC39 committee standardizing ECMAScript
- [WinterCG](https://wintercg.org) - Web-interoperable Runtimes Community Group
