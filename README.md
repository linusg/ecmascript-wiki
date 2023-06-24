# ECMAScript Wiki

This is a collection of information and links intended to be useful to developers of ECMAScript engines and tooling. Pull requests are most welcome! :^)

## Engines

| Logo | Name | Website | Source code | Implementation Language | License | Supported ES version |
|------|------|---------|-------------|-------------------------|---------|----------------------|
| <img width="32" src="https://boajs.dev/images/logo.png"> | Boa | https://boajs.dev | https://github.com/boa-dev/boa | Rust | MIT | |
| | ChakraCore | | https://github.com/chakra-core/ChakraCore | C++ | MIT | |
| <img width="32" src="https://avatars.githubusercontent.com/u/51185628"> | engine262 | https://engine262.js.org | https://github.com/engine262/engine262 | JavaScript | MIT | ESNext |
| | goja | | https://github.com/dop251/goja | Go | MIT | ES5.1 |
| | GraalJS (GraalVM JavaScript) | https://www.graalvm.org/dev/reference-manual/js/ | https://github.com/oracle/graaljs | Java | UPL-1.0 | ESNext |
| <img width="32" src="https://hermesengine.dev/img/logo.svg"> | Hermes | https://hermesengine.dev | https://github.com/facebook/hermes | C++ | MIT | [ES6 with some exceptions](https://hermesengine.dev/docs/language-features) |
| | JavaScriptCore | https://trac.webkit.org/wiki/JavaScriptCore | https://github.com/WebKit/WebKit/tree/main/Source/JavaScriptCore | C++, JavaScript | LGPL-2.1 | ESNext |
| <img width="32" src="https://lh5.googleusercontent.com/J4azFveGFjfodaKPscuiL6AmtEp4TPYlmYwV1Rp09NrqH6KJZR73fmD_8XoH4uQpape7P8HxsmoRTOkAGNnSm0hFCWU_VyDydDgZ03rU0kMdySovQPoICI0beqfNlkC3NWNLv_A-zbvpPBVhyjljakhAww=s2048"> | LibJS | https://libjs.dev | https://github.com/SerenityOS/serenity/tree/master/Userland/Libraries/LibJS | C++ | BSD-2-Clause | ESNext |
| | QuickJS | https://bellard.org/quickjs/ | https://github.com/bellard/quickjs | C | MIT | ES2020 |
| <img width="32" src="https://raw.githubusercontent.com/mozilla-spidermonkey/spidermonkey.dev/production/assets/img/spidermonkey-small.svg"> | Spidermonkey | https://spidermonkey.dev | https://searchfox.org/mozilla-central/source/js | C++, Rust, JavaScript | MPL 2.0 | ESNext |
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

- [linusg/libjs-test262](https://github.com/linusg/libjs-test262) - test262 runner for LibJS
- [LibJS `test-js`](https://github.com/SerenityOS/serenity/blob/master/Tests/LibJS/test-js.cpp) - Custom test runner for the LibJS tests

## Transpilers

TODO: Babel, Sucrase, SWC

## Websites

- [ECMAScript proposals](https://github.com/tc39/proposals)
- [TC39](https://tc39.es) - Ecma TC39 committee standardizing ECMAScript
- [WinterCG](https://wintercg.org) - Web-interoperable Runtimes Community Group
