# ECMAScript Wiki

This is a collection of information and links intended to be useful to developers of ECMAScript engines and tooling. Pull requests are most welcome! :^)

## Engines

| Name | Website | Source code | Implementation Language | License | Supported ES version |
|------|---------|-------------|-------------------------|---------|----------------------|
| Boa | https://boajs.dev | https://github.com/boa-dev/boa | Rust | MIT | |
| ChakraCore | | https://github.com/chakra-core/ChakraCore | C++ | MIT | |
| engine262 | https://engine262.js.org | https://github.com/engine262/engine262 | JavaScript | MIT | ESNext |
| goja | | https://github.com/dop251/goja | Go | MIT | ES5.1 |
| GraalJS (GraalVM JavaScript) | https://www.graalvm.org/dev/reference-manual/js/ | https://github.com/oracle/graaljs | Java | UPL-1.0 | ESNext |
| Hermes | https://hermesengine.dev | https://github.com/facebook/hermes | C++ | MIT | [ES6 with some exceptions](https://hermesengine.dev/docs/language-features) |
| JavaScriptCore | https://trac.webkit.org/wiki/JavaScriptCore | https://github.com/WebKit/WebKit/tree/main/Source/JavaScriptCore | C++, JavaScript | LGPL-2.1 | ESNext |
| LibJS | https://libjs.dev | https://github.com/SerenityOS/serenity/tree/master/Userland/Libraries/LibJS | C++ | BSD-2-Clause | ESNext |
| QuickJS | https://bellard.org/quickjs/ | https://github.com/bellard/quickjs | C | MIT | ES2020 |
| Spidermonkey | https://spidermonkey.dev | https://searchfox.org/mozilla-central/source/js | C++, Rust, JavaScript | MPL 2.0 | ESNext |
| V8 | https://v8.dev | https://source.chromium.org/chromium/chromium/src/+/main:v8/ | C++, JavaScript | BSD | ESNext |
| XS (Moddable SDK) | https://www.moddable.com | https://github.com/Moddable-OpenSource/moddable | C | LGPL-3 | ES2021 |

> **Note**
> _ESNext_ indicates that the engine generally targets the latest ECMAScript standard without major exceptions.

## Specifications

- [ECMA-262](https://tc39.es/ecma262) (ECMAScript Language Specification)
- [ECMA-402](https://tc39.es/ecma402) (ECMAScript Internationalization API Specification)

## Testing

### Test Suites

- [test262](https://github.com/tc39/test262) - Official ECMAScript Conformance Test Suite

### Test Results

- [test262.fyi](https://test262.fyi) - Daily runner of test262 for many engines
- [test262.report](https://test262.report) - test262 results for various engines (defunct as of 2022-09)
- [libjs.dev/test262](https://libjs.dev/test262) - test262 results for LibJS (AST, bytecode, parser tests)

### Test Runners

- [linusg/libjs-test262](https://github.com/linusg/libjs-test262) - test262 runner for LibJS

## Transpilers

TODO: Babel, Sucrase, SWC

## Websites

- [ECMAScript proposals](https://github.com/tc39/proposals)
- [TC39](https://tc39.es)
- [WinterCG](https://wintercg.org)
