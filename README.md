# api documentation for  [jasmine-node (v1.14.5)](https://github.com/mhevery/jasmine-node)  [![npm package](https://img.shields.io/npm/v/npmdoc-jasmine-node.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-jasmine-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-jasmine-node.svg)](https://travis-ci.org/npmdoc/node-npmdoc-jasmine-node)
#### DOM-less simple JavaScript BDD testing framework for Node

[![NPM](https://nodei.co/npm/jasmine-node.png?downloads=true)](https://www.npmjs.com/package/jasmine-node)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jasmine-node/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-jasmine-node_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jasmine-node/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-jasmine-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-jasmine-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Misko Hevery",
        "email": "misko@hevery.com"
    },
    "bin": {
        "jasmine-node": "bin/jasmine-node"
    },
    "bugs": {
        "url": "https://github.com/mhevery/jasmine-node/issues"
    },
    "contributors": [
        {
            "name": "Chris Moultrie",
            "email": "chris@moultrie.org"
        }
    ],
    "dependencies": {
        "coffee-script": ">=1.0.1",
        "gaze": "~0.3.2",
        "jasmine-growl-reporter": "~0.0.2",
        "jasmine-reporters": "~1.0.0",
        "mkdirp": "~0.3.5",
        "requirejs": ">=0.27.1",
        "underscore": ">= 1.3.1",
        "walkdir": ">= 0.0.1"
    },
    "description": "DOM-less simple JavaScript BDD testing framework for Node",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "18e8397b856924ee77003666c3731b5aea50c39d",
        "tarball": "https://registry.npmjs.org/jasmine-node/-/jasmine-node-1.14.5.tgz"
    },
    "homepage": "https://github.com/mhevery/jasmine-node",
    "keywords": [
        "testing",
        "bdd"
    ],
    "licenses": [
        "MIT"
    ],
    "main": "lib/jasmine-node",
    "maintainers": [
        {
            "name": "mhevery",
            "email": "misko@hevery.com"
        },
        {
            "name": "tebriel",
            "email": "chris@moultrie.org"
        }
    ],
    "name": "jasmine-node",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mhevery/jasmine-node.git"
    },
    "scripts": {
        "test": "node lib/jasmine-node/cli.js spec"
    },
    "version": "1.14.5"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module jasmine-node](#apidoc.module.jasmine-node)
1.  boolean <span class="apidocSignatureSpan">jasmine-node.</span>CATCH_EXCEPTIONS
1.  boolean <span class="apidocSignatureSpan">jasmine-node.</span>VERBOSE
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Block (env, func, spec)](#apidoc.element.jasmine-node.Block)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>ConsoleReporter ()](#apidoc.element.jasmine-node.ConsoleReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Env ()](#apidoc.element.jasmine-node.Env)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>ExpectationResult (params)](#apidoc.element.jasmine-node.ExpectationResult)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>FakeTimer ()](#apidoc.element.jasmine-node.FakeTimer)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>GrowlReporter ()](#apidoc.element.jasmine-node.GrowlReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>JUnitXmlReporter (savePath, consolidate, useDotNotation, filePrefix, consolidateAll)](#apidoc.element.jasmine-node.JUnitXmlReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>JsApiReporter ()](#apidoc.element.jasmine-node.JsApiReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers (env, actual, spec, opt_isNot)](#apidoc.element.jasmine-node.Matchers)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers.Any (expectedClass)](#apidoc.element.jasmine-node.Matchers.Any)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers.ObjectContaining (sample)](#apidoc.element.jasmine-node.Matchers.ObjectContaining)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>MessageResult (values)](#apidoc.element.jasmine-node.MessageResult)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>MultiReporter ()](#apidoc.element.jasmine-node.MultiReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>NUnitXmlReporter (options)](#apidoc.element.jasmine-node.NUnitXmlReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>NestedResults ()](#apidoc.element.jasmine-node.NestedResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>PrettyPrinter ()](#apidoc.element.jasmine-node.PrettyPrinter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Queue (env)](#apidoc.element.jasmine-node.Queue)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Reporter ()](#apidoc.element.jasmine-node.Reporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Runner (env)](#apidoc.element.jasmine-node.Runner)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Spec (env, suite, description)](#apidoc.element.jasmine-node.Spec)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Spy (name)](#apidoc.element.jasmine-node.Spy)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>StringPrettyPrinter ()](#apidoc.element.jasmine-node.StringPrettyPrinter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Suite (env, description, specDefinitions, parentSuite)](#apidoc.element.jasmine-node.Suite)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>TapReporter ()](#apidoc.element.jasmine-node.TapReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>TeamcityReporter (config)](#apidoc.element.jasmine-node.TeamcityReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalReporter (config)](#apidoc.element.jasmine-node.TerminalReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalVerboseReporter (config)](#apidoc.element.jasmine-node.TerminalVerboseReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsBlock (env, timeout, spec)](#apidoc.element.jasmine-node.WaitsBlock)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsForBlock (env, timeout, latchFunction, message, spec)](#apidoc.element.jasmine-node.WaitsForBlock)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>XmlHttpRequest ()](#apidoc.element.jasmine-node.XmlHttpRequest)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>any (clazz)](#apidoc.element.jasmine-node.any)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>asyncSpecDone ()](#apidoc.element.jasmine-node.asyncSpecDone)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>asyncSpecWait ()](#apidoc.element.jasmine-node.asyncSpecWait)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>bindOriginal_ (base, name)](#apidoc.element.jasmine-node.bindOriginal_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>clearInterval ()](#apidoc.element.jasmine-node.clearInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>clearTimeout ()](#apidoc.element.jasmine-node.clearTimeout)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>createSpy (name)](#apidoc.element.jasmine-node.createSpy)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>createSpyObj (baseName, methodNames)](#apidoc.element.jasmine-node.createSpyObj)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>executeSpecsInFolder (options)](#apidoc.element.jasmine-node.executeSpecsInFolder)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>getEnv ()](#apidoc.element.jasmine-node.getEnv)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>getGlobal ()](#apidoc.element.jasmine-node.getGlobal)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>isA_ (typeName, value)](#apidoc.element.jasmine-node.isA_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>isArray_ (value)](#apidoc.element.jasmine-node.isArray_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>isDomNode (obj)](#apidoc.element.jasmine-node.isDomNode)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>isNumber_ (value)](#apidoc.element.jasmine-node.isNumber_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>isSpy (putativeSpy)](#apidoc.element.jasmine-node.isSpy)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>isString_ (value)](#apidoc.element.jasmine-node.isString_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>loadHelpersInFolder (folder, matcher)](#apidoc.element.jasmine-node.loadHelpersInFolder)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>log ()](#apidoc.element.jasmine-node.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>objectContaining (sample)](#apidoc.element.jasmine-node.objectContaining)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>pp (value)](#apidoc.element.jasmine-node.pp)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>setInterval ()](#apidoc.element.jasmine-node.setInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>setTimeout ()](#apidoc.element.jasmine-node.setTimeout)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>unimplementedMethod_ ()](#apidoc.element.jasmine-node.unimplementedMethod_)
1.  number <span class="apidocSignatureSpan">jasmine-node.</span>DEFAULT_TIMEOUT_INTERVAL
1.  number <span class="apidocSignatureSpan">jasmine-node.</span>DEFAULT_UPDATE_INTERVAL
1.  number <span class="apidocSignatureSpan">jasmine-node.</span>MAX_PRETTY_PRINT_DEPTH
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Block.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Clock
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Clock.defaultFakeTimer
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Clock.real
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>ConsoleReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Env.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>ExpectationResult.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>FakeTimer.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>GrowlReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>JUnitXmlReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>JsApiReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Matchers.Any.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Matchers.ObjectContaining.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Matchers.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>MessageResult.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>MultiReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>NUnitXmlReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>NestedResults.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>PrettyPrinter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Queue.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Reporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Runner.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Spec.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Spy.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>StringPrettyPrinter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>Suite.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>TapReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>TerminalReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>TerminalReporter.prototype.ANSIColors
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>TerminalReporter.prototype.NoColors
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>TerminalVerboseReporter.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>WaitsBlock.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>WaitsForBlock.prototype
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>util
1.  object <span class="apidocSignatureSpan">jasmine-node.</span>version_

#### [module jasmine-node.Block](#apidoc.module.jasmine-node.Block)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Block (env, func, spec)](#apidoc.element.jasmine-node.Block.Block)

#### [module jasmine-node.Block.prototype](#apidoc.module.jasmine-node.Block.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Block.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.Block.prototype.execute)

#### [module jasmine-node.Clock](#apidoc.module.jasmine-node.Clock)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>assertInstalled ()](#apidoc.element.jasmine-node.Clock.assertInstalled)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>installMock ()](#apidoc.element.jasmine-node.Clock.installMock)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>isInstalled ()](#apidoc.element.jasmine-node.Clock.isInstalled)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>reset ()](#apidoc.element.jasmine-node.Clock.reset)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>runFunctionsWithinRange (oldMillis, nowMillis)](#apidoc.element.jasmine-node.Clock.runFunctionsWithinRange)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>scheduleFunction (timeoutKey, funcToCall, millis, recurring)](#apidoc.element.jasmine-node.Clock.scheduleFunction)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>tick (millis)](#apidoc.element.jasmine-node.Clock.tick)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>uninstallMock ()](#apidoc.element.jasmine-node.Clock.uninstallMock)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>useMock ()](#apidoc.element.jasmine-node.Clock.useMock)
1.  object <span class="apidocSignatureSpan">jasmine-node.Clock.</span>defaultFakeTimer
1.  object <span class="apidocSignatureSpan">jasmine-node.Clock.</span>installed
1.  object <span class="apidocSignatureSpan">jasmine-node.Clock.</span>real

#### [module jasmine-node.Clock.defaultFakeTimer](#apidoc.module.jasmine-node.Clock.defaultFakeTimer)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>clearInterval (timeoutKey)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.clearInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>clearTimeout (timeoutKey)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.clearTimeout)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>setInterval (funcToCall, millis)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.setInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>setTimeout (funcToCall, millis)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.setTimeout)
1.  number <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>nowMillis
1.  number <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>timeoutsMade
1.  object <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>scheduledFunctions

#### [module jasmine-node.Clock.real](#apidoc.module.jasmine-node.Clock.real)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>clearInterval (timer)](#apidoc.element.jasmine-node.Clock.real.clearInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>clearTimeout (timer)](#apidoc.element.jasmine-node.Clock.real.clearTimeout)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>setInterval (callback, repeat, arg1, arg2, arg3)](#apidoc.element.jasmine-node.Clock.real.setInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>setTimeout (callback, after, arg1, arg2, arg3)](#apidoc.element.jasmine-node.Clock.real.setTimeout)

#### [module jasmine-node.ConsoleReporter](#apidoc.module.jasmine-node.ConsoleReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>ConsoleReporter ()](#apidoc.element.jasmine-node.ConsoleReporter.ConsoleReporter)

#### [module jasmine-node.ConsoleReporter.prototype](#apidoc.module.jasmine-node.ConsoleReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>hasGroupedConsole ()](#apidoc.element.jasmine-node.ConsoleReporter.prototype.hasGroupedConsole)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSpecStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSuiteResults)

#### [module jasmine-node.Env](#apidoc.module.jasmine-node.Env)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Env ()](#apidoc.element.jasmine-node.Env.Env)

#### [module jasmine-node.Env.prototype](#apidoc.module.jasmine-node.Env.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>addEqualityTester (equalityTester)](#apidoc.element.jasmine-node.Env.prototype.addEqualityTester)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>addReporter (reporter)](#apidoc.element.jasmine-node.Env.prototype.addReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>afterEach ()](#apidoc.element.jasmine-node.Env.prototype.afterEach)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>beforeEach ()](#apidoc.element.jasmine-node.Env.prototype.beforeEach)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>clearInterval ()](#apidoc.element.jasmine-node.Env.prototype.clearInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>clearTimeout ()](#apidoc.element.jasmine-node.Env.prototype.clearTimeout)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>compareObjects_ (a, b, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Env.prototype.compareObjects_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>compareRegExps_ (a, b, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Env.prototype.compareRegExps_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>contains_ (haystack, needle)](#apidoc.element.jasmine-node.Env.prototype.contains_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>currentRunner ()](#apidoc.element.jasmine-node.Env.prototype.currentRunner)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>ddescribe (description, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.ddescribe)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>describe (description, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.describe)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>describe_ (suite, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.describe_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>equals_ (a, b, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Env.prototype.equals_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>execute ()](#apidoc.element.jasmine-node.Env.prototype.execute)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>iit (description, func)](#apidoc.element.jasmine-node.Env.prototype.iit)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>it ()](#apidoc.element.jasmine-node.Env.prototype.it)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>nextSpecId ()](#apidoc.element.jasmine-node.Env.prototype.nextSpecId)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>nextSuiteId ()](#apidoc.element.jasmine-node.Env.prototype.nextSuiteId)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>setInterval ()](#apidoc.element.jasmine-node.Env.prototype.setInterval)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>setTimeout ()](#apidoc.element.jasmine-node.Env.prototype.setTimeout)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>version ()](#apidoc.element.jasmine-node.Env.prototype.version)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>versionString ()](#apidoc.element.jasmine-node.Env.prototype.versionString)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>xdescribe (desc, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.xdescribe)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>xit (desc, func)](#apidoc.element.jasmine-node.Env.prototype.xit)

#### [module jasmine-node.ExpectationResult](#apidoc.module.jasmine-node.ExpectationResult)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>ExpectationResult (params)](#apidoc.element.jasmine-node.ExpectationResult.ExpectationResult)

#### [module jasmine-node.ExpectationResult.prototype](#apidoc.module.jasmine-node.ExpectationResult.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ExpectationResult.prototype.</span>passed ()](#apidoc.element.jasmine-node.ExpectationResult.prototype.passed)
1.  [function <span class="apidocSignatureSpan">jasmine-node.ExpectationResult.prototype.</span>toString ()](#apidoc.element.jasmine-node.ExpectationResult.prototype.toString)

#### [module jasmine-node.FakeTimer](#apidoc.module.jasmine-node.FakeTimer)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>FakeTimer ()](#apidoc.element.jasmine-node.FakeTimer.FakeTimer)

#### [module jasmine-node.FakeTimer.prototype](#apidoc.module.jasmine-node.FakeTimer.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>reset ()](#apidoc.element.jasmine-node.FakeTimer.prototype.reset)
1.  [function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>runFunctionsWithinRange (oldMillis, nowMillis)](#apidoc.element.jasmine-node.FakeTimer.prototype.runFunctionsWithinRange)
1.  [function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>scheduleFunction (timeoutKey, funcToCall, millis, recurring)](#apidoc.element.jasmine-node.FakeTimer.prototype.scheduleFunction)
1.  [function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>tick (millis)](#apidoc.element.jasmine-node.FakeTimer.prototype.tick)

#### [module jasmine-node.GrowlReporter](#apidoc.module.jasmine-node.GrowlReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>GrowlReporter ()](#apidoc.element.jasmine-node.GrowlReporter.GrowlReporter)

#### [module jasmine-node.GrowlReporter.prototype](#apidoc.module.jasmine-node.GrowlReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportRunnerResults ()](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportRunnerStarting ()](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportSpecStarting ()](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportSpecStarting)

#### [module jasmine-node.JUnitXmlReporter](#apidoc.module.jasmine-node.JUnitXmlReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>JUnitXmlReporter (savePath, consolidate, useDotNotation, filePrefix, consolidateAll)](#apidoc.element.jasmine-node.JUnitXmlReporter.JUnitXmlReporter)
1.  object <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.</span>finished_at
1.  object <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.</span>started_at

#### [module jasmine-node.JUnitXmlReporter.prototype](#apidoc.module.jasmine-node.JUnitXmlReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>getFullName (suite, isFilename)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.getFullName)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>getNestedOutput (suite)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.getNestedOutput)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportRunnerStarting ()](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSpecStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSuiteResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>writeFile (path, filename, text)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.writeFile)

#### [module jasmine-node.JsApiReporter](#apidoc.module.jasmine-node.JsApiReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>JsApiReporter ()](#apidoc.element.jasmine-node.JsApiReporter.JsApiReporter)

#### [module jasmine-node.JsApiReporter.prototype](#apidoc.module.jasmine-node.JsApiReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.JsApiReporter.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportSuiteResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>results ()](#apidoc.element.jasmine-node.JsApiReporter.prototype.results)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>resultsForSpec (specId)](#apidoc.element.jasmine-node.JsApiReporter.prototype.resultsForSpec)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>resultsForSpecs (specIds)](#apidoc.element.jasmine-node.JsApiReporter.prototype.resultsForSpecs)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>suites ()](#apidoc.element.jasmine-node.JsApiReporter.prototype.suites)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>summarizeResult_ (result)](#apidoc.element.jasmine-node.JsApiReporter.prototype.summarizeResult_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>summarize_ (suiteOrSpec)](#apidoc.element.jasmine-node.JsApiReporter.prototype.summarize_)

#### [module jasmine-node.Matchers](#apidoc.module.jasmine-node.Matchers)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers (env, actual, spec, opt_isNot)](#apidoc.element.jasmine-node.Matchers.Matchers)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>Any (expectedClass)](#apidoc.element.jasmine-node.Matchers.Any)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>ObjectContaining (sample)](#apidoc.element.jasmine-node.Matchers.ObjectContaining)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>matcherFn_ (matcherName, matcherFunction)](#apidoc.element.jasmine-node.Matchers.matcherFn_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>pp (str)](#apidoc.element.jasmine-node.Matchers.pp)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>wrapInto_ (prototype, matchersClass)](#apidoc.element.jasmine-node.Matchers.wrapInto_)

#### [module jasmine-node.Matchers.Any](#apidoc.module.jasmine-node.Matchers.Any)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>Any (expectedClass)](#apidoc.element.jasmine-node.Matchers.Any.Any)

#### [module jasmine-node.Matchers.Any.prototype](#apidoc.module.jasmine-node.Matchers.Any.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.Any.prototype.</span>jasmineMatches (other)](#apidoc.element.jasmine-node.Matchers.Any.prototype.jasmineMatches)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.Any.prototype.</span>jasmineToString ()](#apidoc.element.jasmine-node.Matchers.Any.prototype.jasmineToString)

#### [module jasmine-node.Matchers.ObjectContaining](#apidoc.module.jasmine-node.Matchers.ObjectContaining)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>ObjectContaining (sample)](#apidoc.element.jasmine-node.Matchers.ObjectContaining.ObjectContaining)

#### [module jasmine-node.Matchers.ObjectContaining.prototype](#apidoc.module.jasmine-node.Matchers.ObjectContaining.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.ObjectContaining.prototype.</span>jasmineMatches (other, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Matchers.ObjectContaining.prototype.jasmineMatches)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.ObjectContaining.prototype.</span>jasmineToString ()](#apidoc.element.jasmine-node.Matchers.ObjectContaining.prototype.jasmineToString)

#### [module jasmine-node.Matchers.prototype](#apidoc.module.jasmine-node.Matchers.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>report (result, failing_message, details)](#apidoc.element.jasmine-node.Matchers.prototype.report)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBe (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toBe)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeCloseTo (expected, precision)](#apidoc.element.jasmine-node.Matchers.prototype.toBeCloseTo)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeDefined ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeDefined)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeFalsy ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeFalsy)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeGreaterThan (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toBeGreaterThan)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeLessThan (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toBeLessThan)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeNaN ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeNaN)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeNull ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeNull)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeTruthy ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeTruthy)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeUndefined ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeUndefined)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toContain (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toContain)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toEqual (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toEqual)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toHaveBeenCalled ()](#apidoc.element.jasmine-node.Matchers.prototype.toHaveBeenCalled)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toHaveBeenCalledWith ()](#apidoc.element.jasmine-node.Matchers.prototype.toHaveBeenCalledWith)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toHaveProperty (prop)](#apidoc.element.jasmine-node.Matchers.prototype.toHaveProperty)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toMatch (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toMatch)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotBe (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotBe)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotContain (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotContain)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotEqual (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotEqual)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotMatch (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotMatch)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toThrow (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toThrow)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasCalled ()](#apidoc.element.jasmine-node.Matchers.prototype.wasCalled)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasCalledWith ()](#apidoc.element.jasmine-node.Matchers.prototype.wasCalledWith)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasNotCalled ()](#apidoc.element.jasmine-node.Matchers.prototype.wasNotCalled)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasNotCalledWith ()](#apidoc.element.jasmine-node.Matchers.prototype.wasNotCalledWith)

#### [module jasmine-node.MessageResult](#apidoc.module.jasmine-node.MessageResult)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>MessageResult (values)](#apidoc.element.jasmine-node.MessageResult.MessageResult)

#### [module jasmine-node.MessageResult.prototype](#apidoc.module.jasmine-node.MessageResult.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MessageResult.prototype.</span>toString ()](#apidoc.element.jasmine-node.MessageResult.prototype.toString)

#### [module jasmine-node.MultiReporter](#apidoc.module.jasmine-node.MultiReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>MultiReporter ()](#apidoc.element.jasmine-node.MultiReporter.MultiReporter)

#### [module jasmine-node.MultiReporter.prototype](#apidoc.module.jasmine-node.MultiReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>addReporter (reporter)](#apidoc.element.jasmine-node.MultiReporter.prototype.addReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>log ()](#apidoc.element.jasmine-node.MultiReporter.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportRunnerResults ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportRunnerStarting ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportSpecResults ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportSpecStarting ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportSpecStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportSuiteResults ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportSuiteResults)

#### [module jasmine-node.NUnitXmlReporter](#apidoc.module.jasmine-node.NUnitXmlReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>NUnitXmlReporter (options)](#apidoc.element.jasmine-node.NUnitXmlReporter.NUnitXmlReporter)

#### [module jasmine-node.NUnitXmlReporter.prototype](#apidoc.module.jasmine-node.NUnitXmlReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSpecStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSuiteResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>writeFile (text)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.writeFile)

#### [module jasmine-node.NestedResults](#apidoc.module.jasmine-node.NestedResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>NestedResults ()](#apidoc.element.jasmine-node.NestedResults.NestedResults)

#### [module jasmine-node.NestedResults.prototype](#apidoc.module.jasmine-node.NestedResults.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>addResult (result)](#apidoc.element.jasmine-node.NestedResults.prototype.addResult)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>getItems ()](#apidoc.element.jasmine-node.NestedResults.prototype.getItems)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>log (values)](#apidoc.element.jasmine-node.NestedResults.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>passed ()](#apidoc.element.jasmine-node.NestedResults.prototype.passed)
1.  [function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>rollupCounts (result)](#apidoc.element.jasmine-node.NestedResults.prototype.rollupCounts)

#### [module jasmine-node.PrettyPrinter](#apidoc.module.jasmine-node.PrettyPrinter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>PrettyPrinter ()](#apidoc.element.jasmine-node.PrettyPrinter.PrettyPrinter)

#### [module jasmine-node.PrettyPrinter.prototype](#apidoc.module.jasmine-node.PrettyPrinter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitArray ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitArray)
1.  [function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitObject ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitObject)
1.  [function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitScalar ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitScalar)
1.  [function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitString ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitString)
1.  [function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>format (value)](#apidoc.element.jasmine-node.PrettyPrinter.prototype.format)
1.  [function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>iterateObject (obj, fn)](#apidoc.element.jasmine-node.PrettyPrinter.prototype.iterateObject)

#### [module jasmine-node.Queue](#apidoc.module.jasmine-node.Queue)
1.  boolean <span class="apidocSignatureSpan">jasmine-node.Queue.</span>LOOP_DONT_RECURSE
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Queue (env)](#apidoc.element.jasmine-node.Queue.Queue)

#### [module jasmine-node.Queue.prototype](#apidoc.module.jasmine-node.Queue.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>add (block, ensure)](#apidoc.element.jasmine-node.Queue.prototype.add)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>addBefore (block, ensure)](#apidoc.element.jasmine-node.Queue.prototype.addBefore)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>insertNext (block, ensure)](#apidoc.element.jasmine-node.Queue.prototype.insertNext)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>isRunning ()](#apidoc.element.jasmine-node.Queue.prototype.isRunning)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>next_ ()](#apidoc.element.jasmine-node.Queue.prototype.next_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>results ()](#apidoc.element.jasmine-node.Queue.prototype.results)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>start (onComplete)](#apidoc.element.jasmine-node.Queue.prototype.start)

#### [module jasmine-node.Reporter](#apidoc.module.jasmine-node.Reporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Reporter ()](#apidoc.element.jasmine-node.Reporter.Reporter)

#### [module jasmine-node.Reporter.prototype](#apidoc.module.jasmine-node.Reporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.Reporter.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.Reporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.Reporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.Reporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.Reporter.prototype.reportSpecStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.Reporter.prototype.reportSuiteResults)

#### [module jasmine-node.Runner](#apidoc.module.jasmine-node.Runner)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Runner (env)](#apidoc.element.jasmine-node.Runner.Runner)

#### [module jasmine-node.Runner.prototype](#apidoc.module.jasmine-node.Runner.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>add (block)](#apidoc.element.jasmine-node.Runner.prototype.add)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>addSuite (suite)](#apidoc.element.jasmine-node.Runner.prototype.addSuite)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>afterEach (afterEachFunction)](#apidoc.element.jasmine-node.Runner.prototype.afterEach)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>beforeEach (beforeEachFunction)](#apidoc.element.jasmine-node.Runner.prototype.beforeEach)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>execute ()](#apidoc.element.jasmine-node.Runner.prototype.execute)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>finishCallback ()](#apidoc.element.jasmine-node.Runner.prototype.finishCallback)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>results ()](#apidoc.element.jasmine-node.Runner.prototype.results)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>specs ()](#apidoc.element.jasmine-node.Runner.prototype.specs)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>suites ()](#apidoc.element.jasmine-node.Runner.prototype.suites)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>topLevelSuites ()](#apidoc.element.jasmine-node.Runner.prototype.topLevelSuites)

#### [module jasmine-node.Spec](#apidoc.module.jasmine-node.Spec)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Spec (env, suite, description)](#apidoc.element.jasmine-node.Spec.Spec)

#### [module jasmine-node.Spec.prototype](#apidoc.module.jasmine-node.Spec.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addBeforesAndAftersToQueue ()](#apidoc.element.jasmine-node.Spec.prototype.addBeforesAndAftersToQueue)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addMatcherResult (result)](#apidoc.element.jasmine-node.Spec.prototype.addMatcherResult)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addMatchers (matchersPrototype)](#apidoc.element.jasmine-node.Spec.prototype.addMatchers)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addToQueue (block)](#apidoc.element.jasmine-node.Spec.prototype.addToQueue)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>after (doAfter)](#apidoc.element.jasmine-node.Spec.prototype.after)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.Spec.prototype.execute)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>expect (actual)](#apidoc.element.jasmine-node.Spec.prototype.expect)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>explodes ()](#apidoc.element.jasmine-node.Spec.prototype.explodes)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>fail (e)](#apidoc.element.jasmine-node.Spec.prototype.fail)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>finish (onComplete)](#apidoc.element.jasmine-node.Spec.prototype.finish)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>finishCallback ()](#apidoc.element.jasmine-node.Spec.prototype.finishCallback)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>getFullName ()](#apidoc.element.jasmine-node.Spec.prototype.getFullName)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>getMatchersClass_ ()](#apidoc.element.jasmine-node.Spec.prototype.getMatchersClass_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>log ()](#apidoc.element.jasmine-node.Spec.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>removeAllSpies ()](#apidoc.element.jasmine-node.Spec.prototype.removeAllSpies)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>results ()](#apidoc.element.jasmine-node.Spec.prototype.results)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>runs (func)](#apidoc.element.jasmine-node.Spec.prototype.runs)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>spyOn (obj, methodName, ignoreMethodDoesntExist)](#apidoc.element.jasmine-node.Spec.prototype.spyOn)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>waits (timeout)](#apidoc.element.jasmine-node.Spec.prototype.waits)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>waitsFor (latchFunction, optional_timeoutMessage, optional_timeout)](#apidoc.element.jasmine-node.Spec.prototype.waitsFor)

#### [module jasmine-node.Spy](#apidoc.module.jasmine-node.Spy)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Spy (name)](#apidoc.element.jasmine-node.Spy.Spy)

#### [module jasmine-node.Spy.prototype](#apidoc.module.jasmine-node.Spy.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andCallFake (fakeFunc)](#apidoc.element.jasmine-node.Spy.prototype.andCallFake)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andCallThrough ()](#apidoc.element.jasmine-node.Spy.prototype.andCallThrough)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andReturn (value)](#apidoc.element.jasmine-node.Spy.prototype.andReturn)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andThrow (exceptionMsg)](#apidoc.element.jasmine-node.Spy.prototype.andThrow)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>reset ()](#apidoc.element.jasmine-node.Spy.prototype.reset)

#### [module jasmine-node.StringPrettyPrinter](#apidoc.module.jasmine-node.StringPrettyPrinter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>StringPrettyPrinter ()](#apidoc.element.jasmine-node.StringPrettyPrinter.StringPrettyPrinter)

#### [module jasmine-node.StringPrettyPrinter.prototype](#apidoc.module.jasmine-node.StringPrettyPrinter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>append (value)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.append)
1.  [function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitArray (array)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitArray)
1.  [function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitObject (obj)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitObject)
1.  [function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitScalar (value)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitScalar)
1.  [function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitString (value)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitString)

#### [module jasmine-node.Suite](#apidoc.module.jasmine-node.Suite)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>Suite (env, description, specDefinitions, parentSuite)](#apidoc.element.jasmine-node.Suite.Suite)

#### [module jasmine-node.Suite.prototype](#apidoc.module.jasmine-node.Suite.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>add (suiteOrSpec)](#apidoc.element.jasmine-node.Suite.prototype.add)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>afterEach (afterEachFunction)](#apidoc.element.jasmine-node.Suite.prototype.afterEach)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>beforeEach (beforeEachFunction)](#apidoc.element.jasmine-node.Suite.prototype.beforeEach)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>children ()](#apidoc.element.jasmine-node.Suite.prototype.children)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.Suite.prototype.execute)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>finish (onComplete)](#apidoc.element.jasmine-node.Suite.prototype.finish)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>getFullName ()](#apidoc.element.jasmine-node.Suite.prototype.getFullName)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>results ()](#apidoc.element.jasmine-node.Suite.prototype.results)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>specs ()](#apidoc.element.jasmine-node.Suite.prototype.specs)
1.  [function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>suites ()](#apidoc.element.jasmine-node.Suite.prototype.suites)

#### [module jasmine-node.TapReporter](#apidoc.module.jasmine-node.TapReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>TapReporter ()](#apidoc.element.jasmine-node.TapReporter.TapReporter)

#### [module jasmine-node.TapReporter.prototype](#apidoc.module.jasmine-node.TapReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.TapReporter.prototype.log)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.TapReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.TapReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.TapReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.TapReporter.prototype.reportSpecStarting)

#### [module jasmine-node.TerminalReporter](#apidoc.module.jasmine-node.TerminalReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalReporter (config)](#apidoc.element.jasmine-node.TerminalReporter.TerminalReporter)

#### [module jasmine-node.TerminalReporter.prototype](#apidoc.module.jasmine-node.TerminalReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>addFailureToFailures_ (spec)](#apidoc.element.jasmine-node.TerminalReporter.prototype.addFailureToFailures_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>printLine_ (stringValue)](#apidoc.element.jasmine-node.TerminalReporter.prototype.printLine_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>printRunnerResults_ (runner)](#apidoc.element.jasmine-node.TerminalReporter.prototype.printRunnerResults_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportFailures_ ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportFailures_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportRunnerStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportSuiteResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>stringWithColor_ (stringValue, color)](#apidoc.element.jasmine-node.TerminalReporter.prototype.stringWithColor_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>summarize_ (suiteOrSpec)](#apidoc.element.jasmine-node.TerminalReporter.prototype.summarize_)
1.  object <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>ANSIColors
1.  object <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>NoColors

#### [module jasmine-node.TerminalReporter.prototype.ANSIColors](#apidoc.module.jasmine-node.TerminalReporter.prototype.ANSIColors)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>fail ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.fail)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>ignore ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.ignore)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>neutral ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.neutral)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>pass ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.pass)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>specTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.specTiming)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>suiteTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.suiteTiming)

#### [module jasmine-node.TerminalReporter.prototype.NoColors](#apidoc.module.jasmine-node.TerminalReporter.prototype.NoColors)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>fail ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.fail)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>ignore ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.ignore)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>neutral ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.neutral)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>pass ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.pass)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>specTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.specTiming)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>suiteTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.suiteTiming)

#### [module jasmine-node.TerminalVerboseReporter](#apidoc.module.jasmine-node.TerminalVerboseReporter)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalVerboseReporter (config)](#apidoc.element.jasmine-node.TerminalVerboseReporter.TerminalVerboseReporter)

#### [module jasmine-node.TerminalVerboseReporter.prototype](#apidoc.module.jasmine-node.TerminalVerboseReporter.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>buildMessagesFromResults_ (messages, results, depth)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.buildMessagesFromResults_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>indentMessage_ (message, indentCount)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.indentMessage_)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportRunnerResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSpecResults)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSpecStarting)
1.  [function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSuiteResults)

#### [module jasmine-node.WaitsBlock](#apidoc.module.jasmine-node.WaitsBlock)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsBlock (env, timeout, spec)](#apidoc.element.jasmine-node.WaitsBlock.WaitsBlock)

#### [module jasmine-node.WaitsBlock.prototype](#apidoc.module.jasmine-node.WaitsBlock.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.WaitsBlock.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.WaitsBlock.prototype.execute)

#### [module jasmine-node.WaitsForBlock](#apidoc.module.jasmine-node.WaitsForBlock)
1.  [function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsForBlock (env, timeout, latchFunction, message, spec)](#apidoc.element.jasmine-node.WaitsForBlock.WaitsForBlock)
1.  number <span class="apidocSignatureSpan">jasmine-node.WaitsForBlock.</span>TIMEOUT_INCREMENT

#### [module jasmine-node.WaitsForBlock.prototype](#apidoc.module.jasmine-node.WaitsForBlock.prototype)
1.  [function <span class="apidocSignatureSpan">jasmine-node.WaitsForBlock.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.WaitsForBlock.prototype.execute)

#### [module jasmine-node.util](#apidoc.module.jasmine-node.util)
1.  [function <span class="apidocSignatureSpan">jasmine-node.util.</span>argsToArray (args)](#apidoc.element.jasmine-node.util.argsToArray)
1.  [function <span class="apidocSignatureSpan">jasmine-node.util.</span>extend (destination, source)](#apidoc.element.jasmine-node.util.extend)
1.  [function <span class="apidocSignatureSpan">jasmine-node.util.</span>formatException (e)](#apidoc.element.jasmine-node.util.formatException)
1.  [function <span class="apidocSignatureSpan">jasmine-node.util.</span>htmlEscape (str)](#apidoc.element.jasmine-node.util.htmlEscape)
1.  [function <span class="apidocSignatureSpan">jasmine-node.util.</span>inherit (childClass, parentClass)](#apidoc.element.jasmine-node.util.inherit)



# <a name="apidoc.module.jasmine-node"></a>[module jasmine-node](#apidoc.module.jasmine-node)

#### <a name="apidoc.element.jasmine-node.Block"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Block (env, func, spec)](#apidoc.element.jasmine-node.Block)
- description and source-code
```javascript
Block = function (env, func, spec) {
  this.env = env;
  this.func = func;
  this.spec = spec;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.ConsoleReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>ConsoleReporter ()](#apidoc.element.jasmine-node.ConsoleReporter)
- description and source-code
```javascript
ConsoleReporter = function () {
    this.started = false;
    this.finished = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Env ()](#apidoc.element.jasmine-node.Env)
- description and source-code
```javascript
Env = function () {
  this.currentSpec = null;
  this.currentSuite = null;
  this.currentRunner_ = new jasmine.Runner(this);

  this.reporter = new jasmine.MultiReporter();

  this.updateInterval = jasmine.DEFAULT_UPDATE_INTERVAL;
  this.defaultTimeoutInterval = jasmine.DEFAULT_TIMEOUT_INTERVAL;
  this.lastUpdate = 0;
  this.specFilter = function(spec) {
    return this.exclusive_ <= spec.exclusive_;
  };

  this.nextSpecId_ = 0;
  this.nextSuiteId_ = 0;
  this.equalityTesters_ = [];

  // 0 - normal
  // 1 - contains some ddescribe
  // 2 - contains some iit
  this.exclusive_ = 0;

  // wrap matchers
  this.matchersClass = function() {
    jasmine.Matchers.apply(this, arguments);
  };
  jasmine.util.inherit(this.matchersClass, jasmine.Matchers);

  jasmine.Matchers.wrapInto_(jasmine.Matchers.prototype, this.matchersClass);
}
```
- example usage
```shell
...




describe('async-callback', function() {
  var env;
  beforeEach(function() {
env = new jasmine.Env();
  });

  describe('it', function() {

it("should time out if callback is not called", function() {
  env.describe("it", function() {
    env.it("doesn't wait", function(done) {
...
```

#### <a name="apidoc.element.jasmine-node.ExpectationResult"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>ExpectationResult (params)](#apidoc.element.jasmine-node.ExpectationResult)
- description and source-code
```javascript
ExpectationResult = function (params) {
  this.type = 'expect';
  this.matcherName = params.matcherName;
  this.passed_ = params.passed;
  this.expected = params.expected;
  this.actual = params.actual;
  this.message = this.passed_ ? 'Passed.' : params.message;

  var trace = (params.trace || new Error(this.message));
  this.trace = this.passed_ ? '' : trace;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.FakeTimer"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>FakeTimer ()](#apidoc.element.jasmine-node.FakeTimer)
- description and source-code
```javascript
FakeTimer = function () {
  this.reset();

  var self = this;
  self.setTimeout = function(funcToCall, millis) {
    self.timeoutsMade++;
    self.scheduleFunction(self.timeoutsMade, funcToCall, millis, false);
    return self.timeoutsMade;
  };

  self.setInterval = function(funcToCall, millis) {
    self.timeoutsMade++;
    self.scheduleFunction(self.timeoutsMade, funcToCall, millis, true);
    return self.timeoutsMade;
  };

  self.clearTimeout = function(timeoutKey) {
    self.scheduledFunctions[timeoutKey] = jasmine.undefined;
  };

  self.clearInterval = function(timeoutKey) {
    self.scheduledFunctions[timeoutKey] = jasmine.undefined;
  };

}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.GrowlReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>GrowlReporter ()](#apidoc.element.jasmine-node.GrowlReporter)
- description and source-code
```javascript
GrowlReporter = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>JUnitXmlReporter (savePath, consolidate, useDotNotation, filePrefix, consolidateAll)](#apidoc.element.jasmine-node.JUnitXmlReporter)
- description and source-code
```javascript
JUnitXmlReporter = function (savePath, consolidate, useDotNotation, filePrefix, consolidateAll) {
    this.savePath = savePath || '';
    this.consolidate = consolidate === jasmine.undefined ? true : consolidate;
    this.consolidateAll = consolidateAll === jasmine.undefined ? false : consolidateAll;
    this.useDotNotation = useDotNotation === jasmine.undefined ? true : useDotNotation;
    this.filePrefix = filePrefix || (this.consolidateAll ? 'junitresults' : 'TEST-');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>JsApiReporter ()](#apidoc.element.jasmine-node.JsApiReporter)
- description and source-code
```javascript
JsApiReporter = function () {
  this.started = false;
  this.finished = false;
  this.suites_ = [];
  this.results_ = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers (env, actual, spec, opt_isNot)](#apidoc.element.jasmine-node.Matchers)
- description and source-code
```javascript
Matchers = function (env, actual, spec, opt_isNot) {
  this.env = env;
  this.actual = actual;
  this.spec = spec;
  this.isNot = opt_isNot || false;
  this.reportWasCalled_ = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.Any"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers.Any (expectedClass)](#apidoc.element.jasmine-node.Matchers.Any)
- description and source-code
```javascript
Matchers.Any = function (expectedClass) {
  this.expectedClass = expectedClass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.ObjectContaining"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers.ObjectContaining (sample)](#apidoc.element.jasmine-node.Matchers.ObjectContaining)
- description and source-code
```javascript
Matchers.ObjectContaining = function (sample) {
  this.sample = sample;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.MessageResult"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>MessageResult (values)](#apidoc.element.jasmine-node.MessageResult)
- description and source-code
```javascript
MessageResult = function (values) {
  this.type = 'log';
  this.values = values;
  this.trace = new Error(); // todo: test better
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.MultiReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>MultiReporter ()](#apidoc.element.jasmine-node.MultiReporter)
- description and source-code
```javascript
MultiReporter = function () {
  this.subReporters_ = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>NUnitXmlReporter (options)](#apidoc.element.jasmine-node.NUnitXmlReporter)
- description and source-code
```javascript
NUnitXmlReporter = function (options) {
    options = options || {};
    this.savePath = options.savePath || '';
    this.filename = options.filename || 'nunit-results.xml';
    this.reportName = options.reportName || 'Jasmine Results';
    this.testSuites = {};
    this.testSpecs = {};
    this.testRun = {
        suites: []
    };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.NestedResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>NestedResults ()](#apidoc.element.jasmine-node.NestedResults)
- description and source-code
```javascript
NestedResults = function () {
<span class="apidocCodeCommentSpan">  /**
   * The total count of results
   */
</span>  this.totalCount = 0;
  /**
   * Number of passed results
   */
  this.passedCount = 0;
  /**
   * Number of failed results
   */
  this.failedCount = 0;
  /**
   * Was this suite/spec skipped?
   */
  this.skipped = false;
  /**
   * @ignore
   */
  this.items_ = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.PrettyPrinter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>PrettyPrinter ()](#apidoc.element.jasmine-node.PrettyPrinter)
- description and source-code
```javascript
PrettyPrinter = function () {
  this.ppNestLevel_ = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Queue"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Queue (env)](#apidoc.element.jasmine-node.Queue)
- description and source-code
```javascript
Queue = function (env) {
  this.env = env;

  // parallel to blocks. each true value in this array means the block will
  // get executed even if we abort
  this.ensured = [];
  this.blocks = [];
  this.running = false;
  this.index = 0;
  this.offset = 0;
  this.abort = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Reporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Reporter ()](#apidoc.element.jasmine-node.Reporter)
- description and source-code
```javascript
Reporter = function () {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Runner"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Runner (env)](#apidoc.element.jasmine-node.Runner)
- description and source-code
```javascript
Runner = function (env) {
  var self = this;
  self.env = env;
  self.queue = new jasmine.Queue(env);
  self.before_ = [];
  self.after_ = [];
  self.suites_ = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Spec (env, suite, description)](#apidoc.element.jasmine-node.Spec)
- description and source-code
```javascript
Spec = function (env, suite, description) {
  if (!env) {
    throw new Error('jasmine.Env() required');
  }
  if (!suite) {
    throw new Error('jasmine.Suite() required');
  }
  var spec = this;
  spec.id = env.nextSpecId ? env.nextSpecId() : null;
  spec.env = env;
  spec.suite = suite;
  spec.description = description;
  spec.queue = new jasmine.Queue(env);

  spec.afterCallbacks = [];
  spec.spies_ = [];

  spec.results_ = new jasmine.NestedResults();
  spec.results_.description = description;
  spec.matchersClass = null;
  spec.exclusive_ = suite.exclusive_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spy"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Spy (name)](#apidoc.element.jasmine-node.Spy)
- description and source-code
```javascript
Spy = function (name) {
<span class="apidocCodeCommentSpan">  /**
   * The name of the spy, if provided.
   */
</span>  this.identity = name || 'unknown';
  /**
   *  Is this Object a spy?
   */
  this.isSpy = true;
  /**
   * The actual function this spy stubs.
   */
  this.plan = function() {
  };
  /**
   * Tracking of the most recent call to the spy.
   * @example
   * var mySpy = jasmine.createSpy('foo');
   * mySpy(1, 2);
   * mySpy.mostRecentCall.args = [1, 2];
   */
  this.mostRecentCall = {};

  /**
   * Holds arguments for each call to the spy, indexed by call count
   * @example
   * var mySpy = jasmine.createSpy('foo');
   * mySpy(1, 2);
   * mySpy(7, 8);
   * mySpy.mostRecentCall.args = [7, 8];
   * mySpy.argsForCall[0] = [1, 2];
   * mySpy.argsForCall[1] = [7, 8];
   */
  this.argsForCall = [];
  this.calls = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.StringPrettyPrinter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>StringPrettyPrinter ()](#apidoc.element.jasmine-node.StringPrettyPrinter)
- description and source-code
```javascript
StringPrettyPrinter = function () {
  jasmine.PrettyPrinter.call(this);

  this.string = '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Suite"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Suite (env, description, specDefinitions, parentSuite)](#apidoc.element.jasmine-node.Suite)
- description and source-code
```javascript
Suite = function (env, description, specDefinitions, parentSuite) {
  var self = this;
  self.id = env.nextSuiteId ? env.nextSuiteId() : null;
  self.description = description;
  self.queue = new jasmine.Queue(env);
  self.parentSuite = parentSuite;
  self.env = env;
  self.before_ = [];
  self.after_ = [];
  self.children_ = [];
  self.suites_ = [];
  self.specs_ = [];
  self.exclusive_ = parentSuite && parentSuite.exclusive_ || 0;
}
```
- example usage
```shell
...
expect(result.name).toEqual('the spec');
expect(result.type).toEqual('spec');
expect(result.children.length).toEqual(0);
    });

    it('creates a summary object from suite with 1 spec', function() {
var env = { nextSuiteId: false }
var suite = new jasmine.Suite(env, 'suite name', undefined, undefined);
suite.description = 'the suite';
suite.parentSuite = null;
suite.children_.push(this.spec);

var result = this.reporter.summarize_(suite);
expect(result.name).toEqual('the suite');
expect(result.type).toEqual('suite');
...
```

#### <a name="apidoc.element.jasmine-node.TapReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>TapReporter ()](#apidoc.element.jasmine-node.TapReporter)
- description and source-code
```javascript
TapReporter = function () {
    this.started = false;
    this.finished = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TeamcityReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>TeamcityReporter (config)](#apidoc.element.jasmine-node.TeamcityReporter)
- description and source-code
```javascript
TeamcityReporter = function (config) {
  var callback_ = config.onComplete || false;

  (function(superFn) {
    jasmineNode.TeamcityReporter.prototype.reportRunnerResults = function(runner) {
      superFn.call(this, runner);
      if (callback_) {callback_(runner)}
    }
  }(jasmine.TeamcityReporter.prototype.reportRunnerResults));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalReporter (config)](#apidoc.element.jasmine-node.TerminalReporter)
- description and source-code
```javascript
TerminalReporter = function (config) {
  this.print_ = config.print || function (str) { process.stdout.write(util.format(str)); };
  this.color_ = config.color ? this.ANSIColors : this.NoColors;

  this.started_ = false;
  this.finished_ = false;

  this.callback_ = config.onComplete || false

  this.suites_ = [];
  this.specResults_ = {};
  this.failures_ = [];
  this.includeStackTrace_ = config.includeStackTrace === false ? false : true;
  this.stackFilter_ = config.stackFilter || function(t) { return t; };
}
```
- example usage
```shell
...


var jasmineNode = require(__dirname + "/../lib/jasmine-node/reporter").jasmineNode;

describe('TerminalReporter', function() {
beforeEach(function() {
  var config = {}
  this.reporter = new jasmineNode.TerminalReporter(config);
});

describe("initialize", function() {
  it('initializes print_ from config', function() {
    var config = { print: true };
    this.reporter = new jasmineNode.TerminalReporter(config);
    expect(this.reporter.print_).toBeTruthy();
...
```

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalVerboseReporter (config)](#apidoc.element.jasmine-node.TerminalVerboseReporter)
- description and source-code
```javascript
TerminalVerboseReporter = function (config) {
  jasmineNode.TerminalReporter.call(this, config);
  // The extra field in this object
  this.indent_ = 0;
  this.specTimes_ = {};
  this.suiteTimes_ = {};
  this.suiteResults_ = {};
}
```
- example usage
```shell
...
  });
});
});

describe('TerminalVerboseReporter', function() {
beforeEach(function() {
  var config = {}
  this.verboseReporter = new jasmineNode.TerminalVerboseReporter(config);
  this.addFailureToFailuresSpy = spyOn(this.verboseReporter, 'addFailureToFailures_');
  this.spec = {
    id: 23,
    results: function() {
      return {
        failedCount: 1,
        getItems: function() {
...
```

#### <a name="apidoc.element.jasmine-node.WaitsBlock"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsBlock (env, timeout, spec)](#apidoc.element.jasmine-node.WaitsBlock)
- description and source-code
```javascript
WaitsBlock = function (env, timeout, spec) {
  this.timeout = timeout;
  jasmine.Block.call(this, env, null, spec);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.WaitsForBlock"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsForBlock (env, timeout, latchFunction, message, spec)](#apidoc.element.jasmine-node.WaitsForBlock)
- description and source-code
```javascript
WaitsForBlock = function (env, timeout, latchFunction, message, spec) {
  this.timeout = timeout || env.defaultTimeoutInterval;
  this.latchFunction = latchFunction;
  this.message = message;
  this.totalTimeSpentWaitingForLatch = 0;
  jasmine.Block.call(this, env, null, spec);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.XmlHttpRequest"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>XmlHttpRequest ()](#apidoc.element.jasmine-node.XmlHttpRequest)
- description and source-code
```javascript
XmlHttpRequest = function () {
  function tryIt(f) {
    try {
      return f();
    } catch(e) {
    }
    return null;
  }

  var xhr = tryIt(function() {
    return new ActiveXObject("Msxml2.XMLHTTP.6.0");
  }) ||
    tryIt(function() {
      return new ActiveXObject("Msxml2.XMLHTTP.3.0");
    }) ||
    tryIt(function() {
      return new ActiveXObject("Msxml2.XMLHTTP");
    }) ||
    tryIt(function() {
      return new ActiveXObject("Microsoft.XMLHTTP");
    });

  if (!xhr) throw new Error("This browser does not support XMLHttpRequest.");

  return xhr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.any"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>any (clazz)](#apidoc.element.jasmine-node.any)
- description and source-code
```javascript
any = function (clazz) {
  return new jasmine.Matchers.Any(clazz);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.asyncSpecDone"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>asyncSpecDone ()](#apidoc.element.jasmine-node.asyncSpecDone)
- description and source-code
```javascript
asyncSpecDone = function (){
  jasmine.asyncSpecWait.done = true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.asyncSpecWait"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>asyncSpecWait ()](#apidoc.element.jasmine-node.asyncSpecWait)
- description and source-code
```javascript
asyncSpecWait = function (){
  var wait = jasmine.asyncSpecWait;
  wait.start = now();
  wait.done = false;
  (function innerWait(){
    waits(10);
    runs(function() {
      if (wait.start + wait.timeout < now()) {
        expect('timeout waiting for spec').toBeNull();
      } else if (wait.done) {
        wait.done = false;
      } else {
        innerWait();
      }
    });
  })();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.bindOriginal_"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>bindOriginal_ (base, name)](#apidoc.element.jasmine-node.bindOriginal_)
- description and source-code
```javascript
bindOriginal_ = function (base, name) {
  var original = base[name];
  if (original.apply) {
    return function() {
      return original.apply(base, arguments);
    };
  } else {
    // IE support
    return jasmine.getGlobal()[name];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.clearInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>clearInterval ()](#apidoc.element.jasmine-node.clearInterval)
- description and source-code
```javascript
clearInterval = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.clearTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>clearTimeout ()](#apidoc.element.jasmine-node.clearTimeout)
- description and source-code
```javascript
clearTimeout = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.createSpy"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>createSpy (name)](#apidoc.element.jasmine-node.createSpy)
- description and source-code
```javascript
createSpy = function (name) {

  var spyObj = function() {
    spyObj.wasCalled = true;
    spyObj.callCount++;
    var args = jasmine.util.argsToArray(arguments);
    spyObj.mostRecentCall.object = this;
    spyObj.mostRecentCall.args = args;
    spyObj.argsForCall.push(args);
    spyObj.calls.push({object: this, args: args});
    return spyObj.plan.apply(this, arguments);
  };

  var spy = new jasmine.Spy(name);

  for (var prop in spy) {
    spyObj[prop] = spy[prop];
  }

  spyObj.reset();

  return spyObj;
}
```
- example usage
```shell
...



describe("Manually ticking the Jasmine Mock Clock", function() {
  var timerCallback;

  beforeEach(function() {
timerCallback = jasmine.createSpy('timerCallback');
jasmine.Clock.useMock();
  });

  it("causes a timeout to be called synchronously", function() {
setTimeout(timerCallback, 100);

expect(timerCallback).not.toHaveBeenCalled();
...
```

#### <a name="apidoc.element.jasmine-node.createSpyObj"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>createSpyObj (baseName, methodNames)](#apidoc.element.jasmine-node.createSpyObj)
- description and source-code
```javascript
createSpyObj = function (baseName, methodNames) {
  if (!jasmine.isArray_(methodNames) || methodNames.length === 0) {
    throw new Error('createSpyObj requires a non-empty array of method names to create spies for');
  }
  var obj = {};
  for (var i = 0; i < methodNames.length; i++) {
    obj[methodNames[i]] = jasmine.createSpy(baseName + '.' + methodNames[i]);
  }
  return obj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.executeSpecsInFolder"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>executeSpecsInFolder (options)](#apidoc.element.jasmine-node.executeSpecsInFolder)
- description and source-code
```javascript
executeSpecsInFolder = function (options){
  var folders =      options['specFolders'];
  var done   =       options['onComplete'];
  var isVerbose =    options['isVerbose'];
  var showColors =   options['showColors'];
  var teamcity =     options['teamcity'];
  var useRequireJs = options['useRequireJs'];
  var matcher =      options['regExpSpec'];
  var junitreport = options['junitreport'];
  var includeStackTrace = options['includeStackTrace'];
  var growl = options['growl'];

  // Overwriting it allows us to handle custom async specs
  it = function(desc, func, timeout) {
      return jasmine.getEnv().it(desc, func, timeout);
  }
  beforeEach = function(func, timeout) {
      return jasmine.getEnv().beforeEach(func, timeout);
  }
  afterEach = function(func, timeout) {
      return jasmine.getEnv().afterEach(func, timeout);
  }
  var fileMatcher = matcher || new RegExp(".(js)$", "i"),
      colors = showColors || false,
      specs = require('./spec-collection'),
      jasmineEnv = jasmine.getEnv();

  specs.load(folders, fileMatcher);

  if(junitreport && junitreport.report) {
    var existsSync = fs.existsSync || path.existsSync;
    if(!existsSync(junitreport.savePath)) {
      util.puts('creating junit xml report save path: ' + junitreport.savePath);
      mkdirp.sync(junitreport.savePath, "0755");
    }
    jasmineEnv.addReporter(new jasmine.JUnitXmlReporter(junitreport.savePath,
                                                        junitreport.consolidate,
                                                        junitreport.useDotNotation));
  }

  if(teamcity){
    jasmineEnv.addReporter(new jasmine.TeamcityReporter({onComplete: done}));
  } else if(isVerbose) {
    jasmineEnv.addReporter(new jasmine.TerminalVerboseReporter({ print: print,
                                                         color:       showColors,
                                                         onComplete:  done,
                                                         stackFilter: removeJasmineFrames}));
  } else {
    jasmineEnv.addReporter(new jasmine.TerminalReporter({print: print,
                                                color: showColors,
                                                includeStackTrace: includeStackTrace,
                                                onComplete:  done,
                                                stackFilter: removeJasmineFrames}));
  }

  if (growl) {
    jasmineEnv.addReporter(new jasmine.GrowlReporter());
  }

  if (useRequireJs) {
    require('./requirejs-runner').executeJsRunner(
      specs,
      done,
      jasmineEnv,
      typeof useRequireJs === 'string' ? useRequireJs : null
    );
  } else {
    var specsList = specs.getSpecs();

    for (var i = 0, len = specsList.length; i < len; ++i) {
      var filename = specsList[i];
      delete require.cache[filename.path()];
      // Catch exceptions in loading the spec
      try {
        require(filename.path().replace(/\.\w+$/, ""));
      } catch (e) {
        console.log("Exception loading: " + filename.path());
        console.log(e);
        throw e;
      }
    }

    jasmineEnv.execute();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.getEnv"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>getEnv ()](#apidoc.element.jasmine-node.getEnv)
- description and source-code
```javascript
getEnv = function () {
  var env = jasmine.currentEnv_ = jasmine.currentEnv_ || new jasmine.Env();
  return env;
}
```
- example usage
```shell
...
  expect(body).toEqual("hello world");
  done();
});
});
'''

An asynchronous test will fail after '5000' ms if 'done()' is not called. This timeout
can be changed by setting 'jasmine.getEnv().defaultTimeoutInterval' or by passing a timeout
interval in the specification.

'''javascript
var request = require('request');

it("should respond with hello world", function(done) {
request("http://localhost:3000/hello", function(error, response, body){
...
```

#### <a name="apidoc.element.jasmine-node.getGlobal"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>getGlobal ()](#apidoc.element.jasmine-node.getGlobal)
- description and source-code
```javascript
getGlobal = function () {
  function getGlobal() {
    return this;
  }

  return getGlobal();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.isA_"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>isA_ (typeName, value)](#apidoc.element.jasmine-node.isA_)
- description and source-code
```javascript
isA_ = function (typeName, value) {
  return Object.prototype.toString.apply(value) === '[object ' + typeName + ']';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.isArray_"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>isArray_ (value)](#apidoc.element.jasmine-node.isArray_)
- description and source-code
```javascript
isArray_ = function (value) {
  return jasmine.isA_("Array", value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.isDomNode"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>isDomNode (obj)](#apidoc.element.jasmine-node.isDomNode)
- description and source-code
```javascript
isDomNode = function (obj) {
  return obj.nodeType > 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.isNumber_"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>isNumber_ (value)](#apidoc.element.jasmine-node.isNumber_)
- description and source-code
```javascript
isNumber_ = function (value) {
  return jasmine.isA_("Number", value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.isSpy"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>isSpy (putativeSpy)](#apidoc.element.jasmine-node.isSpy)
- description and source-code
```javascript
isSpy = function (putativeSpy) {
  return putativeSpy && putativeSpy.isSpy;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.isString_"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>isString_ (value)](#apidoc.element.jasmine-node.isString_)
- description and source-code
```javascript
isString_ = function (value) {
  return jasmine.isA_("String", value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.loadHelpersInFolder"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>loadHelpersInFolder (folder, matcher)](#apidoc.element.jasmine-node.loadHelpersInFolder)
- description and source-code
```javascript
loadHelpersInFolder = function (folder, matcher) {
  // Check to see if the folder is actually a file, if so, back up to the
  // parent directory and find some helpers
  folderStats = fs.statSync(folder);
  if (folderStats.isFile()) {
    folder = path.dirname(folder);
  }

  var helpers = [],
      helperCollection = require('./spec-collection');

  helperCollection.load([folder], matcher);
  helpers = helperCollection.getSpecs();

  for (var i = 0, len = helpers.length; i < len; ++i) {
    var file = helpers[i].path();

    try {
      var helper = require(file.replace(/\.*$/, ""));
    } catch (e) {
      console.log("Exception loading helper: " + file)
      console.log(e);
      throw e; // If any of the helpers fail to load, fail everything
    }

    for (var key in helper) {
      global[key]= helper[key];
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>log ()](#apidoc.element.jasmine-node.log)
- description and source-code
```javascript
log = function () {
  var spec = jasmine.getEnv().currentSpec;
  spec.log.apply(spec, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.objectContaining"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>objectContaining (sample)](#apidoc.element.jasmine-node.objectContaining)
- description and source-code
```javascript
objectContaining = function (sample) {
    return new jasmine.Matchers.ObjectContaining(sample);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.pp"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>pp (value)](#apidoc.element.jasmine-node.pp)
- description and source-code
```javascript
pp = function (value) {
  var stringPrettyPrinter = new jasmine.StringPrettyPrinter();
  stringPrettyPrinter.format(value);
  return stringPrettyPrinter.string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.setInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>setInterval ()](#apidoc.element.jasmine-node.setInterval)
- description and source-code
```javascript
setInterval = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.setTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>setTimeout ()](#apidoc.element.jasmine-node.setTimeout)
- description and source-code
```javascript
setTimeout = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.unimplementedMethod_"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>unimplementedMethod_ ()](#apidoc.element.jasmine-node.unimplementedMethod_)
- description and source-code
```javascript
unimplementedMethod_ = function () {
  throw new Error("unimplemented method");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Block"></a>[module jasmine-node.Block](#apidoc.module.jasmine-node.Block)

#### <a name="apidoc.element.jasmine-node.Block.Block"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Block (env, func, spec)](#apidoc.element.jasmine-node.Block.Block)
- description and source-code
```javascript
Block = function (env, func, spec) {
  this.env = env;
  this.func = func;
  this.spec = spec;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Block.prototype"></a>[module jasmine-node.Block.prototype](#apidoc.module.jasmine-node.Block.prototype)

#### <a name="apidoc.element.jasmine-node.Block.prototype.execute"></a>[function <span class="apidocSignatureSpan">jasmine-node.Block.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.Block.prototype.execute)
- description and source-code
```javascript
execute = function (onComplete) {
  if (!jasmine.CATCH_EXCEPTIONS) {
    this.func.apply(this.spec);
  }
  else {
    try {
      this.func.apply(this.spec);
    } catch (e) {
      this.spec.fail(e);
    }
  }
  onComplete();
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```



# <a name="apidoc.module.jasmine-node.Clock"></a>[module jasmine-node.Clock](#apidoc.module.jasmine-node.Clock)

#### <a name="apidoc.element.jasmine-node.Clock.assertInstalled"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>assertInstalled ()](#apidoc.element.jasmine-node.Clock.assertInstalled)
- description and source-code
```javascript
assertInstalled = function () {
  if (!jasmine.Clock.isInstalled()) {
    throw new Error("Mock clock is not installed, use jasmine.Clock.useMock()");
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.installMock"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>installMock ()](#apidoc.element.jasmine-node.Clock.installMock)
- description and source-code
```javascript
installMock = function () {
  jasmine.Clock.installed = jasmine.Clock.defaultFakeTimer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.isInstalled"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>isInstalled ()](#apidoc.element.jasmine-node.Clock.isInstalled)
- description and source-code
```javascript
isInstalled = function () {
  return jasmine.Clock.installed == jasmine.Clock.defaultFakeTimer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.reset"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>reset ()](#apidoc.element.jasmine-node.Clock.reset)
- description and source-code
```javascript
reset = function () {
  jasmine.Clock.assertInstalled();
  jasmine.Clock.defaultFakeTimer.reset();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.runFunctionsWithinRange"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>runFunctionsWithinRange (oldMillis, nowMillis)](#apidoc.element.jasmine-node.Clock.runFunctionsWithinRange)
- description and source-code
```javascript
runFunctionsWithinRange = function (oldMillis, nowMillis) {
  jasmine.Clock.defaultFakeTimer.runFunctionsWithinRange(oldMillis, nowMillis);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.scheduleFunction"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>scheduleFunction (timeoutKey, funcToCall, millis, recurring)](#apidoc.element.jasmine-node.Clock.scheduleFunction)
- description and source-code
```javascript
scheduleFunction = function (timeoutKey, funcToCall, millis, recurring) {
  jasmine.Clock.defaultFakeTimer.scheduleFunction(timeoutKey, funcToCall, millis, recurring);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.tick"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>tick (millis)](#apidoc.element.jasmine-node.Clock.tick)
- description and source-code
```javascript
tick = function (millis) {
  jasmine.Clock.assertInstalled();
  jasmine.Clock.defaultFakeTimer.tick(millis);
}
```
- example usage
```shell
...
});

it("causes a timeout to be called synchronously", function() {
  setTimeout(timerCallback, 100);

  expect(timerCallback).not.toHaveBeenCalled();

  jasmine.Clock.tick(101);

  expect(timerCallback).toHaveBeenCalled();
});

it("causes an interval to be called synchronously", function() {
  setInterval(timerCallback, 100);
...
```

#### <a name="apidoc.element.jasmine-node.Clock.uninstallMock"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>uninstallMock ()](#apidoc.element.jasmine-node.Clock.uninstallMock)
- description and source-code
```javascript
uninstallMock = function () {
  jasmine.Clock.assertInstalled();
  jasmine.Clock.installed = jasmine.Clock.real;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.useMock"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.</span>useMock ()](#apidoc.element.jasmine-node.Clock.useMock)
- description and source-code
```javascript
useMock = function () {
  if (!jasmine.Clock.isInstalled()) {
    var spec = jasmine.getEnv().currentSpec;
    spec.after(jasmine.Clock.uninstallMock);

    jasmine.Clock.installMock();
  }
}
```
- example usage
```shell
...


describe("Manually ticking the Jasmine Mock Clock", function() {
  var timerCallback;

  beforeEach(function() {
timerCallback = jasmine.createSpy('timerCallback');
jasmine.Clock.useMock();
  });

  it("causes a timeout to be called synchronously", function() {
setTimeout(timerCallback, 100);

expect(timerCallback).not.toHaveBeenCalled();
...
```



# <a name="apidoc.module.jasmine-node.Clock.defaultFakeTimer"></a>[module jasmine-node.Clock.defaultFakeTimer](#apidoc.module.jasmine-node.Clock.defaultFakeTimer)

#### <a name="apidoc.element.jasmine-node.Clock.defaultFakeTimer.clearInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>clearInterval (timeoutKey)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.clearInterval)
- description and source-code
```javascript
clearInterval = function (timeoutKey) {
  self.scheduledFunctions[timeoutKey] = jasmine.undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.defaultFakeTimer.clearTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>clearTimeout (timeoutKey)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.clearTimeout)
- description and source-code
```javascript
clearTimeout = function (timeoutKey) {
  self.scheduledFunctions[timeoutKey] = jasmine.undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.defaultFakeTimer.setInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>setInterval (funcToCall, millis)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.setInterval)
- description and source-code
```javascript
setInterval = function (funcToCall, millis) {
  self.timeoutsMade++;
  self.scheduleFunction(self.timeoutsMade, funcToCall, millis, true);
  return self.timeoutsMade;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.defaultFakeTimer.setTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.defaultFakeTimer.</span>setTimeout (funcToCall, millis)](#apidoc.element.jasmine-node.Clock.defaultFakeTimer.setTimeout)
- description and source-code
```javascript
setTimeout = function (funcToCall, millis) {
  self.timeoutsMade++;
  self.scheduleFunction(self.timeoutsMade, funcToCall, millis, false);
  return self.timeoutsMade;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Clock.real"></a>[module jasmine-node.Clock.real](#apidoc.module.jasmine-node.Clock.real)

#### <a name="apidoc.element.jasmine-node.Clock.real.clearInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>clearInterval (timer)](#apidoc.element.jasmine-node.Clock.real.clearInterval)
- description and source-code
```javascript
clearInterval = function (timer) {
  if (timer && timer._repeat) {
    timer._repeat = null;
    clearTimeout(timer);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.real.clearTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>clearTimeout (timer)](#apidoc.element.jasmine-node.Clock.real.clearTimeout)
- description and source-code
```javascript
clearTimeout = function (timer) {
  if (timer && (timer[kOnTimeout] || timer._onTimeout)) {
    timer[kOnTimeout] = timer._onTimeout = null;
    if (timer instanceof Timeout) {
      timer.close(); // for after === 0
    } else {
      unenroll(timer);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.real.setInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>setInterval (callback, repeat, arg1, arg2, arg3)](#apidoc.element.jasmine-node.Clock.real.setInterval)
- description and source-code
```javascript
setInterval = function (callback, repeat, arg1, arg2, arg3) {
  if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  var len = arguments.length;
  var args;
  if (len === 3) {
    args = [arg1];
  } else if (len === 4) {
    args = [arg1, arg2];
  } else if (len > 4) {
    args = [arg1, arg2, arg3];
    for (var i = 5; i < len; i++)
      // extend array dynamically, makes .apply run much faster in v6.0.0
      args[i - 2] = arguments[i];
  }

  return createRepeatTimeout(callback, repeat, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Clock.real.setTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.Clock.real.</span>setTimeout (callback, after, arg1, arg2, arg3)](#apidoc.element.jasmine-node.Clock.real.setTimeout)
- description and source-code
```javascript
setTimeout = function (callback, after, arg1, arg2, arg3) {
  if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  var len = arguments.length;
  var args;
  if (len === 3) {
    args = [arg1];
  } else if (len === 4) {
    args = [arg1, arg2];
  } else if (len > 4) {
    args = [arg1, arg2, arg3];
    for (var i = 5; i < len; i++)
      // extend array dynamically, makes .apply run much faster in v6.0.0
      args[i - 2] = arguments[i];
  }

  return createSingleTimeout(callback, after, args);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.ConsoleReporter"></a>[module jasmine-node.ConsoleReporter](#apidoc.module.jasmine-node.ConsoleReporter)

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.ConsoleReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>ConsoleReporter ()](#apidoc.element.jasmine-node.ConsoleReporter.ConsoleReporter)
- description and source-code
```javascript
ConsoleReporter = function () {
    this.started = false;
    this.finished = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.ConsoleReporter.prototype"></a>[module jasmine-node.ConsoleReporter.prototype](#apidoc.module.jasmine-node.ConsoleReporter.prototype)

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.prototype.hasGroupedConsole"></a>[function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>hasGroupedConsole ()](#apidoc.element.jasmine-node.ConsoleReporter.prototype.hasGroupedConsole)
- description and source-code
```javascript
hasGroupedConsole = function () {
    var console = jasmine.getGlobal().console;
    return console && console.info && console.warn && console.group && console.groupEnd && console.groupCollapsed;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.log)
- description and source-code
```javascript
log = function (str) {
    var console = jasmine.getGlobal().console;
    if (console && console.log) {
        console.log(str);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
    if (this.hasGroupedConsole()) {
        var suites = runner.suites();
        startGroup(runner.results(), 'tests');
        for (var i=0; i<suites.length; i++) {
            if (!suites[i].parentSuite) {
                suiteResults(suites[i]);
            }
        }
        console.groupEnd();
    }
    else {
        var dur = (new Date()).getTime() - this.start_time;
        var failed = this.executed_specs - this.passed_specs;
        var spec_str = this.executed_specs + (this.executed_specs === 1 ? " spec, " : " specs, ");
        var fail_str = failed + (failed === 1 ? " failure in " : " failures in ");

        this.log("Runner Finished.");
        this.log(spec_str + fail_str + (dur/1000) + "s.");
    }
    this.finished = true;
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function (runner) {
    this.started = true;
    if (!this.hasGroupedConsole()) {
        this.start_time = (new Date()).getTime();
        this.executed_specs = 0;
        this.passed_specs = 0;
        this.log("Runner Started.");
    }
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
    if (!this.hasGroupedConsole()) {
        var resultText = "Failed.";

        if (spec.results().skipped ) {
            resultText = 'Skipped.';
        } else if (spec.results().passed()) {
            this.passed_specs++;
            resultText = "Passed.";
        }

        this.log(resultText);
    }
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function (spec) {
    if (!this.hasGroupedConsole()) {
        this.executed_specs++;
        this.log(spec.suite.description + ' : ' + spec.description + ' ... ');
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.ConsoleReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.ConsoleReporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function (suite) {
    if (!this.hasGroupedConsole()) {
        var results = suite.results();
        this.log(suite.description + ": " + results.passedCount + " of " + results.totalCount + " passed.");
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Env"></a>[module jasmine-node.Env](#apidoc.module.jasmine-node.Env)

#### <a name="apidoc.element.jasmine-node.Env.Env"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Env ()](#apidoc.element.jasmine-node.Env.Env)
- description and source-code
```javascript
Env = function () {
  this.currentSpec = null;
  this.currentSuite = null;
  this.currentRunner_ = new jasmine.Runner(this);

  this.reporter = new jasmine.MultiReporter();

  this.updateInterval = jasmine.DEFAULT_UPDATE_INTERVAL;
  this.defaultTimeoutInterval = jasmine.DEFAULT_TIMEOUT_INTERVAL;
  this.lastUpdate = 0;
  this.specFilter = function(spec) {
    return this.exclusive_ <= spec.exclusive_;
  };

  this.nextSpecId_ = 0;
  this.nextSuiteId_ = 0;
  this.equalityTesters_ = [];

  // 0 - normal
  // 1 - contains some ddescribe
  // 2 - contains some iit
  this.exclusive_ = 0;

  // wrap matchers
  this.matchersClass = function() {
    jasmine.Matchers.apply(this, arguments);
  };
  jasmine.util.inherit(this.matchersClass, jasmine.Matchers);

  jasmine.Matchers.wrapInto_(jasmine.Matchers.prototype, this.matchersClass);
}
```
- example usage
```shell
...




describe('async-callback', function() {
  var env;
  beforeEach(function() {
env = new jasmine.Env();
  });

  describe('it', function() {

it("should time out if callback is not called", function() {
  env.describe("it", function() {
    env.it("doesn't wait", function(done) {
...
```



# <a name="apidoc.module.jasmine-node.Env.prototype"></a>[module jasmine-node.Env.prototype](#apidoc.module.jasmine-node.Env.prototype)

#### <a name="apidoc.element.jasmine-node.Env.prototype.addEqualityTester"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>addEqualityTester (equalityTester)](#apidoc.element.jasmine-node.Env.prototype.addEqualityTester)
- description and source-code
```javascript
addEqualityTester = function (equalityTester) {
  this.equalityTesters_.push(equalityTester);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.addReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>addReporter (reporter)](#apidoc.element.jasmine-node.Env.prototype.addReporter)
- description and source-code
```javascript
addReporter = function (reporter) {
  this.reporter.addReporter(reporter);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.afterEach"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>afterEach ()](#apidoc.element.jasmine-node.Env.prototype.afterEach)
- description and source-code
```javascript
afterEach = function () {
    var args = Array.prototype.slice.call(arguments, 0);
    var timeout = null;
    if (isLastArgumentATimeout(args)) {
        timeout = args.pop();
        // The changes to the jasmine test runner causes undef to be passed when
        // calling all it()'s now. If the last argument isn't a timeout and the
        // last argument IS undefined, let's just pop it off. Since out of bounds
        // items are undefined anyways, *hopefully* removing an undef item won't
        // hurt.
    } else if (args[args.length-1] == undefined) {
        args.pop();
    }
    if (isLastArgumentAnAsyncSpecFunction(args))
    {
        var specFunction = args.pop();
        args.push(function() {
            return asyncSpec(specFunction, this, timeout);
        });
    }
    return withoutAsync[jasmineFunction].apply(this, args);
}
```
- example usage
```shell
...
    });
});

describe("afterEach", function() {
  it("should be passed async callback", function() {
    var completed = false;
    env.describe("afterEach", function() {
      env.afterEach(function(done) {
        process.nextTick(function() {
          done('Failed in afterEach');
          completed = true;
        });
      });
      env.it("should pass", function() {
        this.expect(1+2).toEqual(3);
...
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.beforeEach"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>beforeEach ()](#apidoc.element.jasmine-node.Env.prototype.beforeEach)
- description and source-code
```javascript
beforeEach = function () {
    var args = Array.prototype.slice.call(arguments, 0);
    var timeout = null;
    if (isLastArgumentATimeout(args)) {
        timeout = args.pop();
        // The changes to the jasmine test runner causes undef to be passed when
        // calling all it()'s now. If the last argument isn't a timeout and the
        // last argument IS undefined, let's just pop it off. Since out of bounds
        // items are undefined anyways, *hopefully* removing an undef item won't
        // hurt.
    } else if (args[args.length-1] == undefined) {
        args.pop();
    }
    if (isLastArgumentAnAsyncSpecFunction(args))
    {
        var specFunction = args.pop();
        args.push(function() {
            return asyncSpec(specFunction, this, timeout);
        });
    }
    return withoutAsync[jasmineFunction].apply(this, args);
}
```
- example usage
```shell
...

});

describe("beforeEach", function() {
  it("should wait for callback", function() {
    env.describe("beforeEach", function() {
      var waited = false;
      env.beforeEach(function(done) {
        process.nextTick(function() {
          waited = true;
          done();
        });
      });
      env.it("waited", function() {
        env.currentSpec.expect(waited).toBeTruthy();
...
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.clearInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>clearInterval ()](#apidoc.element.jasmine-node.Env.prototype.clearInterval)
- description and source-code
```javascript
clearInterval = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.clearTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>clearTimeout ()](#apidoc.element.jasmine-node.Env.prototype.clearTimeout)
- description and source-code
```javascript
clearTimeout = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.compareObjects_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>compareObjects_ (a, b, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Env.prototype.compareObjects_)
- description and source-code
```javascript
compareObjects_ = function (a, b, mismatchKeys, mismatchValues) {
  if (a.__Jasmine_been_here_before__ === b && b.__Jasmine_been_here_before__ === a) {
    return true;
  }

  a.__Jasmine_been_here_before__ = b;
  b.__Jasmine_been_here_before__ = a;

  var hasKey = function(obj, keyName) {
    return obj !== null && obj[keyName] !== jasmine.undefined;
  };

  for (var property in b) {
    if (!hasKey(a, property) && hasKey(b, property)) {
      mismatchKeys.push("expected has key '" + property + "', but missing from actual.");
    }
  }
  for (property in a) {
    if (!hasKey(b, property) && hasKey(a, property)) {
      mismatchKeys.push("expected missing key '" + property + "', but present in actual.");
    }
  }
  for (property in b) {
    if (property == '__Jasmine_been_here_before__') continue;
    if (!this.equals_(a[property], b[property], mismatchKeys, mismatchValues)) {
      mismatchValues.push("'" + property + "' was '" + (b[property] ? jasmine.util.htmlEscape(b[property].toString()) : b[property
]) + "' in expected, but was '" + (a[property] ? jasmine.util.htmlEscape(a[property].toString()) : a[property]) + "' in actual.");
    }
  }

  if (jasmine.isArray_(a) && jasmine.isArray_(b) && a.length != b.length) {
    mismatchValues.push("arrays were not the same length");
  }

  delete a.__Jasmine_been_here_before__;
  delete b.__Jasmine_been_here_before__;
  return (mismatchKeys.length === 0 && mismatchValues.length === 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.compareRegExps_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>compareRegExps_ (a, b, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Env.prototype.compareRegExps_)
- description and source-code
```javascript
compareRegExps_ = function (a, b, mismatchKeys, mismatchValues) {
  if (a.source != b.source)
    mismatchValues.push("expected pattern /" + b.source + "/ is not equal to the pattern /" + a.source + "/");

  if (a.ignoreCase != b.ignoreCase)
    mismatchValues.push("expected modifier i was" + (b.ignoreCase ? " " : " not ") + "set and does not equal the origin modifier
");

  if (a.global != b.global)
    mismatchValues.push("expected modifier g was" + (b.global ? " " : " not ") + "set and does not equal the origin modifier");

  if (a.multiline != b.multiline)
    mismatchValues.push("expected modifier m was" + (b.multiline ? " " : " not ") + "set and does not equal the origin modifier");

  if (a.sticky != b.sticky)
    mismatchValues.push("expected modifier y was" + (b.sticky ? " " : " not ") + "set and does not equal the origin modifier");

  return (mismatchValues.length === 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.contains_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>contains_ (haystack, needle)](#apidoc.element.jasmine-node.Env.prototype.contains_)
- description and source-code
```javascript
contains_ = function (haystack, needle) {
  if (jasmine.isArray_(haystack)) {
    for (var i = 0; i < haystack.length; i++) {
      if (this.equals_(haystack[i], needle)) return true;
    }
    return false;
  }
  return haystack.indexOf(needle) >= 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.currentRunner"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>currentRunner ()](#apidoc.element.jasmine-node.Env.prototype.currentRunner)
- description and source-code
```javascript
currentRunner = function () {
  return this.currentRunner_;
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.ddescribe"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>ddescribe (description, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.ddescribe)
- description and source-code
```javascript
ddescribe = function (description, specDefinitions) {
  var suite = new jasmine.Suite(this, description, null, this.currentSuite);
  suite.exclusive_ = 1;
  this.exclusive_ = Math.max(this.exclusive_, 1);

  return this.describe_(suite, specDefinitions);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.describe"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>describe (description, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.describe)
- description and source-code
```javascript
describe = function (description, specDefinitions) {
  var suite = new jasmine.Suite(this, description, null, this.currentSuite);
  return this.describe_(suite, specDefinitions);
}
```
- example usage
```shell
...
  beforeEach(function() {
    env = new jasmine.Env();
  });

  describe('it', function() {

    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();
...
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.describe_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>describe_ (suite, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.describe_)
- description and source-code
```javascript
describe_ = function (suite, specDefinitions) {
  var parentSuite = this.currentSuite;
  if (parentSuite) {
    parentSuite.add(suite);
  } else {
    this.currentRunner_.add(suite);
  }

  this.currentSuite = suite;

  var declarationError = null;
  try {
    specDefinitions.call(suite);
  } catch(e) {
    declarationError = e;
  }

  if (declarationError) {
    this.it("encountered a declaration exception", function() {
      throw declarationError;
    });
  }

  this.currentSuite = parentSuite;

  return suite;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.equals_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>equals_ (a, b, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Env.prototype.equals_)
- description and source-code
```javascript
equals_ = function (a, b, mismatchKeys, mismatchValues) {
  mismatchKeys = mismatchKeys || [];
  mismatchValues = mismatchValues || [];

  for (var i = 0; i < this.equalityTesters_.length; i++) {
    var equalityTester = this.equalityTesters_[i];
    var result = equalityTester(a, b, this, mismatchKeys, mismatchValues);
    if (result !== jasmine.undefined) return result;
  }

  if (a === b) return true;

  if (a === jasmine.undefined || a === null || b === jasmine.undefined || b === null) {
    return (a == jasmine.undefined && b == jasmine.undefined);
  }

  if (jasmine.isDomNode(a) && jasmine.isDomNode(b)) {
    return a === b;
  }

  if (a instanceof Date && b instanceof Date) {
    return a.getTime() == b.getTime();
  }

  if (a.jasmineMatches) {
    return a.jasmineMatches(b);
  }

  if (b.jasmineMatches) {
    return b.jasmineMatches(a);
  }

  if (a instanceof jasmine.Matchers.ObjectContaining) {
    return a.matches(b);
  }

  if (b instanceof jasmine.Matchers.ObjectContaining) {
    return b.matches(a);
  }

  if (jasmine.isString_(a) && jasmine.isString_(b)) {
    return (a == b);
  }

  if (jasmine.isNumber_(a) && jasmine.isNumber_(b)) {
    return (a == b);
  }

  if (a instanceof RegExp && b instanceof RegExp) {
    return this.compareRegExps_(a, b, mismatchKeys, mismatchValues);
  }

  if (typeof a === "object" && typeof b === "object") {
    return this.compareObjects_(a, b, mismatchKeys, mismatchValues);
  }

  //Straight check
  return (a === b);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.execute"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>execute ()](#apidoc.element.jasmine-node.Env.prototype.execute)
- description and source-code
```javascript
execute = function () {
  this.currentRunner_.execute();
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.iit"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>iit (description, func)](#apidoc.element.jasmine-node.Env.prototype.iit)
- description and source-code
```javascript
iit = function (description, func) {
  var spec = this.it(description, func);
  spec.exclusive_ = 2;
  this.exclusive_ = 2;

  return spec;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.it"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>it ()](#apidoc.element.jasmine-node.Env.prototype.it)
- description and source-code
```javascript
it = function () {
    var args = Array.prototype.slice.call(arguments, 0);
    var timeout = null;
    if (isLastArgumentATimeout(args)) {
        timeout = args.pop();
        // The changes to the jasmine test runner causes undef to be passed when
        // calling all it()'s now. If the last argument isn't a timeout and the
        // last argument IS undefined, let's just pop it off. Since out of bounds
        // items are undefined anyways, *hopefully* removing an undef item won't
        // hurt.
    } else if (args[args.length-1] == undefined) {
        args.pop();
    }
    if (isLastArgumentAnAsyncSpecFunction(args))
    {
        var specFunction = args.pop();
        args.push(function() {
            return asyncSpec(specFunction, this, timeout);
        });
    }
    return withoutAsync[jasmineFunction].apply(this, args);
}
```
- example usage
```shell
...
    env = new jasmine.Env();
  });

  describe('it', function() {

    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
...
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.nextSpecId"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>nextSpecId ()](#apidoc.element.jasmine-node.Env.prototype.nextSpecId)
- description and source-code
```javascript
nextSpecId = function () {
  return this.nextSpecId_++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.nextSuiteId"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>nextSuiteId ()](#apidoc.element.jasmine-node.Env.prototype.nextSuiteId)
- description and source-code
```javascript
nextSuiteId = function () {
  return this.nextSuiteId_++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.setInterval"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>setInterval ()](#apidoc.element.jasmine-node.Env.prototype.setInterval)
- description and source-code
```javascript
setInterval = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.setTimeout"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>setTimeout ()](#apidoc.element.jasmine-node.Env.prototype.setTimeout)
- description and source-code
```javascript
setTimeout = function () {
  return original.apply(base, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.version"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>version ()](#apidoc.element.jasmine-node.Env.prototype.version)
- description and source-code
```javascript
version = function () {
  if (jasmine.version_) {
    return jasmine.version_;
  } else {
    throw new Error('Version not set');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.versionString"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>versionString ()](#apidoc.element.jasmine-node.Env.prototype.versionString)
- description and source-code
```javascript
versionString = function () {
  if (!jasmine.version_) {
    return "version unknown";
  }

  var version = this.version();
  var versionString = version.major + "." + version.minor + "." + version.build;
  if (version.release_candidate) {
    versionString += ".rc" + version.release_candidate;
  }
  versionString += " revision " + version.revision;
  return versionString;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.xdescribe"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>xdescribe (desc, specDefinitions)](#apidoc.element.jasmine-node.Env.prototype.xdescribe)
- description and source-code
```javascript
xdescribe = function (desc, specDefinitions) {
  return {
    execute: function() {
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Env.prototype.xit"></a>[function <span class="apidocSignatureSpan">jasmine-node.Env.prototype.</span>xit (desc, func)](#apidoc.element.jasmine-node.Env.prototype.xit)
- description and source-code
```javascript
xit = function (desc, func) {
  return {
    id: this.nextSpecId(),
    runs: function() {
    }
  };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.ExpectationResult"></a>[module jasmine-node.ExpectationResult](#apidoc.module.jasmine-node.ExpectationResult)

#### <a name="apidoc.element.jasmine-node.ExpectationResult.ExpectationResult"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>ExpectationResult (params)](#apidoc.element.jasmine-node.ExpectationResult.ExpectationResult)
- description and source-code
```javascript
ExpectationResult = function (params) {
  this.type = 'expect';
  this.matcherName = params.matcherName;
  this.passed_ = params.passed;
  this.expected = params.expected;
  this.actual = params.actual;
  this.message = this.passed_ ? 'Passed.' : params.message;

  var trace = (params.trace || new Error(this.message));
  this.trace = this.passed_ ? '' : trace;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.ExpectationResult.prototype"></a>[module jasmine-node.ExpectationResult.prototype](#apidoc.module.jasmine-node.ExpectationResult.prototype)

#### <a name="apidoc.element.jasmine-node.ExpectationResult.prototype.passed"></a>[function <span class="apidocSignatureSpan">jasmine-node.ExpectationResult.prototype.</span>passed ()](#apidoc.element.jasmine-node.ExpectationResult.prototype.passed)
- description and source-code
```javascript
passed = function () {
  return this.passed_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.ExpectationResult.prototype.toString"></a>[function <span class="apidocSignatureSpan">jasmine-node.ExpectationResult.prototype.</span>toString ()](#apidoc.element.jasmine-node.ExpectationResult.prototype.toString)
- description and source-code
```javascript
toString = function () {
  return this.message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.FakeTimer"></a>[module jasmine-node.FakeTimer](#apidoc.module.jasmine-node.FakeTimer)

#### <a name="apidoc.element.jasmine-node.FakeTimer.FakeTimer"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>FakeTimer ()](#apidoc.element.jasmine-node.FakeTimer.FakeTimer)
- description and source-code
```javascript
FakeTimer = function () {
  this.reset();

  var self = this;
  self.setTimeout = function(funcToCall, millis) {
    self.timeoutsMade++;
    self.scheduleFunction(self.timeoutsMade, funcToCall, millis, false);
    return self.timeoutsMade;
  };

  self.setInterval = function(funcToCall, millis) {
    self.timeoutsMade++;
    self.scheduleFunction(self.timeoutsMade, funcToCall, millis, true);
    return self.timeoutsMade;
  };

  self.clearTimeout = function(timeoutKey) {
    self.scheduledFunctions[timeoutKey] = jasmine.undefined;
  };

  self.clearInterval = function(timeoutKey) {
    self.scheduledFunctions[timeoutKey] = jasmine.undefined;
  };

}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.FakeTimer.prototype"></a>[module jasmine-node.FakeTimer.prototype](#apidoc.module.jasmine-node.FakeTimer.prototype)

#### <a name="apidoc.element.jasmine-node.FakeTimer.prototype.reset"></a>[function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>reset ()](#apidoc.element.jasmine-node.FakeTimer.prototype.reset)
- description and source-code
```javascript
reset = function () {
  this.timeoutsMade = 0;
  this.scheduledFunctions = {};
  this.nowMillis = 0;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.FakeTimer.prototype.runFunctionsWithinRange"></a>[function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>runFunctionsWithinRange (oldMillis, nowMillis)](#apidoc.element.jasmine-node.FakeTimer.prototype.runFunctionsWithinRange)
- description and source-code
```javascript
runFunctionsWithinRange = function (oldMillis, nowMillis) {
  var scheduledFunc;
  var funcsToRun = [];
  for (var timeoutKey in this.scheduledFunctions) {
    scheduledFunc = this.scheduledFunctions[timeoutKey];
    if (scheduledFunc != jasmine.undefined &&
        scheduledFunc.runAtMillis >= oldMillis &&
        scheduledFunc.runAtMillis <= nowMillis) {
      funcsToRun.push(scheduledFunc);
      this.scheduledFunctions[timeoutKey] = jasmine.undefined;
    }
  }

  if (funcsToRun.length > 0) {
    funcsToRun.sort(function(a, b) {
      return a.runAtMillis - b.runAtMillis;
    });
    for (var i = 0; i < funcsToRun.length; ++i) {
      try {
        var funcToRun = funcsToRun[i];
        this.nowMillis = funcToRun.runAtMillis;
        funcToRun.funcToCall();
        if (funcToRun.recurring) {
          this.scheduleFunction(funcToRun.timeoutKey,
              funcToRun.funcToCall,
              funcToRun.millis,
              true);
        }
      } catch(e) {
      }
    }
    this.runFunctionsWithinRange(oldMillis, nowMillis);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.FakeTimer.prototype.scheduleFunction"></a>[function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>scheduleFunction (timeoutKey, funcToCall, millis, recurring)](#apidoc.element.jasmine-node.FakeTimer.prototype.scheduleFunction)
- description and source-code
```javascript
scheduleFunction = function (timeoutKey, funcToCall, millis, recurring) {
  this.scheduledFunctions[timeoutKey] = {
    runAtMillis: this.nowMillis + millis,
    funcToCall: funcToCall,
    recurring: recurring,
    timeoutKey: timeoutKey,
    millis: millis
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.FakeTimer.prototype.tick"></a>[function <span class="apidocSignatureSpan">jasmine-node.FakeTimer.prototype.</span>tick (millis)](#apidoc.element.jasmine-node.FakeTimer.prototype.tick)
- description and source-code
```javascript
tick = function (millis) {
  var oldMillis = this.nowMillis;
  var newMillis = oldMillis + millis;
  this.runFunctionsWithinRange(oldMillis, newMillis);
  this.nowMillis = newMillis;
}
```
- example usage
```shell
...
});

it("causes a timeout to be called synchronously", function() {
  setTimeout(timerCallback, 100);

  expect(timerCallback).not.toHaveBeenCalled();

  jasmine.Clock.tick(101);

  expect(timerCallback).toHaveBeenCalled();
});

it("causes an interval to be called synchronously", function() {
  setInterval(timerCallback, 100);
...
```



# <a name="apidoc.module.jasmine-node.GrowlReporter"></a>[module jasmine-node.GrowlReporter](#apidoc.module.jasmine-node.GrowlReporter)

#### <a name="apidoc.element.jasmine-node.GrowlReporter.GrowlReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>GrowlReporter ()](#apidoc.element.jasmine-node.GrowlReporter.GrowlReporter)
- description and source-code
```javascript
GrowlReporter = function () {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.GrowlReporter.prototype"></a>[module jasmine-node.GrowlReporter.prototype](#apidoc.module.jasmine-node.GrowlReporter.prototype)

#### <a name="apidoc.element.jasmine-node.GrowlReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportRunnerResults ()](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function () {

  growl(growlMessage(this.passedSpecs, this.totalSpecs), {
    name: growlName,
    title: growlTitle(this.passedSpecs, this.totalSpecs, this.startedAt),
    image: growlImage(this.passedSpecs, this.totalSpecs)
  });
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.GrowlReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportRunnerStarting ()](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function () {
  this.startedAt = new Date();
  this.passedSpecs = 0;
  this.totalSpecs = 0;
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.GrowlReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
  if (spec.results().passed()) {
    this.passedSpecs++;
  }
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.GrowlReporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.GrowlReporter.prototype.</span>reportSpecStarting ()](#apidoc.element.jasmine-node.GrowlReporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function () {
  this.totalSpecs++;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.JUnitXmlReporter"></a>[module jasmine-node.JUnitXmlReporter](#apidoc.module.jasmine-node.JUnitXmlReporter)

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.JUnitXmlReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>JUnitXmlReporter (savePath, consolidate, useDotNotation, filePrefix, consolidateAll)](#apidoc.element.jasmine-node.JUnitXmlReporter.JUnitXmlReporter)
- description and source-code
```javascript
JUnitXmlReporter = function (savePath, consolidate, useDotNotation, filePrefix, consolidateAll) {
    this.savePath = savePath || '';
    this.consolidate = consolidate === jasmine.undefined ? true : consolidate;
    this.consolidateAll = consolidateAll === jasmine.undefined ? false : consolidateAll;
    this.useDotNotation = useDotNotation === jasmine.undefined ? true : useDotNotation;
    this.filePrefix = filePrefix || (this.consolidateAll ? 'junitresults' : 'TEST-');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.JUnitXmlReporter.prototype"></a>[module jasmine-node.JUnitXmlReporter.prototype](#apidoc.module.jasmine-node.JUnitXmlReporter.prototype)

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.getFullName"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>getFullName (suite, isFilename)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.getFullName)
- description and source-code
```javascript
getFullName = function (suite, isFilename) {
    var fullName;
    if (this.useDotNotation) {
        fullName = suite.description;
        for (var parentSuite = suite.parentSuite; parentSuite; parentSuite = parentSuite.parentSuite) {
            fullName = parentSuite.description + '.' + fullName;
        }
    }
    else {
        fullName = suite.getFullName();
    }

    // Either remove or escape invalid XML characters
    if (isFilename) {
        return fullName.replace(/[^\w]/g, "");
    }
    return escapeInvalidXmlChars(fullName);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.getNestedOutput"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>getNestedOutput (suite)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.getNestedOutput)
- description and source-code
```javascript
getNestedOutput = function (suite) {
    var output = suite.output;
    for (var i = 0; i < suite.suites().length; i++) {
        output += this.getNestedOutput(suite.suites()[i]);
    }
    return output;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.log)
- description and source-code
```javascript
log = function (str) {
    var console = jasmine.getGlobal().console;

    if (console && console.log) {
        console.log(str);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
    var fileName;
    if (this.consolidateAll) {
        fileName = this.filePrefix + '.xml';
        var output = '<?xml version="1.0" encoding="UTF-8" ?>';
        output += "\n<testsuites>";
    }
    var suites = runner.suites();
    for (var i = 0; i < suites.length; i++) {
        var suite = suites[i];
        fileName = this.consolidateAll ? fileName : this.filePrefix + this.getFullName(suite, true) + '.xml';
        if (!this.consolidateAll) {
            var output = '<?xml version="1.0" encoding="UTF-8" ?>';
        }
        // if we are consolidating, only write out top-level suites
        if ((this.consolidate || this.consolidateAll) && suite.parentSuite) {
            continue;
        }
        else if (this.consolidate || this.consolidateAll) {
            if (!this.consolidateAll) {
                output += "\n<testsuites>";
            }
            output += this.getNestedOutput(suite);
            if (!this.consolidateAll) {
                output += "\n</testsuites>";
                this.writeFile(this.savePath, fileName, output);
            }
        }
        else {
            output += suite.output;
            this.writeFile(this.savePath, fileName, output);
        }
    }
    if (this.consolidateAll) {
        output += "\n</testsuites>";
        this.writeFile(this.savePath, fileName, output);
    }
    // When all done, make it known on JUnitXmlReporter
    JUnitXmlReporter.finished_at = (new Date()).getTime();
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportRunnerStarting ()](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function () {
    // When run test, make it known on JUnitXmlReporter
    JUnitXmlReporter.started_at = (new Date()).getTime();
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
    var results = spec.results();
    spec.didFail = !results.passed();
    spec.duration = elapsed(spec.startTime, new Date());
    spec.output = '<testcase classname="' + this.getFullName(spec.suite) +
        '" name="' + escapeInvalidXmlChars(spec.description) + '" time="' + spec.duration + '">';
    if(results.skipped) {
      spec.output = spec.output + "<skipped />";
    }

    var failure = "";
    var failures = 0;
    var resultItems = results.getItems();
    for (var i = 0; i < resultItems.length; i++) {
        var result = resultItems[i];

        if (result.type == 'expect' && result.passed && !result.passed()) {
            failures += 1;
            failure += '<failure type="' + result.type + '" message="' + trim(escapeInvalidXmlChars(result.message)) + '">';
            failure += escapeInvalidXmlChars(result.trace.stack || result.message);
            failure += "</failure>";
        }
    }
    if (failure) {
        spec.output += failure;
    }
    spec.output += "</testcase>";
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function (spec) {
    spec.startTime = new Date();

    if (!spec.suite.startTime) {
        spec.suite.startTime = spec.startTime;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function (suite) {
    var results = suite.results();
    var specs = suite.specs();
    var specOutput = "";
    // for JUnit results, let's only include directly failed tests (not nested suites')
    var failedCount = 0;

    suite.status = results.passed() ? 'Passed.' : 'Failed.';
    if (results.totalCount === 0) { // todo: change this to check results.skipped
        suite.status = 'Skipped.';
    }

    // if a suite has no (active?) specs, reportSpecStarting is never called
    // and thus the suite has no startTime -- account for that here
    suite.startTime = suite.startTime || new Date();
    suite.duration = elapsed(suite.startTime, new Date());

    for (var i = 0; i < specs.length; i++) {
        failedCount += specs[i].didFail ? 1 : 0;
        specOutput += "\n  " + specs[i].output;
    }
    suite.output = '\n<testsuite name="' + this.getFullName(suite) +
        '" errors="0" tests="' + specs.length + '" failures="' + failedCount +
        '" time="' + suite.duration + '" timestamp="' + ISODateString(suite.startTime) + '">';
    suite.output += specOutput;
    suite.output += "\n</testsuite>";
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JUnitXmlReporter.prototype.writeFile"></a>[function <span class="apidocSignatureSpan">jasmine-node.JUnitXmlReporter.prototype.</span>writeFile (path, filename, text)](#apidoc.element.jasmine-node.JUnitXmlReporter.prototype.writeFile)
- description and source-code
```javascript
writeFile = function (path, filename, text) {
    var errors = [];

    function getQualifiedFilename(separator) {
        if (separator && path && path.substr(-1) !== separator && filename.substr(0) !== separator) {
            return path + separator + filename;
        }
        return path + filename;
    }

    function rhinoWrite(path, filename, text) {
        if (path) {
            // turn filename into a qualified path
            filename = getQualifiedFilename(java.lang.System.getProperty("file.separator"));
            // create parent dir and ancestors if necessary
            var file = java.io.File(filename);
            var parentDir = file.getParentFile();
            if (!parentDir.exists()) {
                parentDir.mkdirs();
            }
        }
        // finally write the file
        var out = new java.io.BufferedWriter(new java.io.FileWriter(filename));
        out.write(text);
        out.close();
    }

    function phantomWrite(path, filename, text) {
        // turn filename into a qualified path
        filename = getQualifiedFilename(window.fs_path_separator);
        // write via a method injected by phantomjs-testrunner.js
        __phantom_writeFile(filename, text);
    }

    function nodeWrite(path, filename, text) {
        var fs = require("fs");
        var nodejs_path = require("path");
        require("mkdirp").sync(path); // make sure the path exists
        var filepath = nodejs_path.join(path, filename);
        var xmlfile = fs.openSync(filepath, "w");
        fs.writeSync(xmlfile, text, 0);
        fs.closeSync(xmlfile);
    }


    // Attempt writing with each possible environment.
    // Track errors in case no write succeeds
    try {
        rhinoWrite(path, filename, text);
        return;
    } catch (e) {
        errors.push('  Rhino attempt: ' + e.message);
    }

    try {
        phantomWrite(path, filename, text);
        return;
    } catch (f) {
        errors.push('  PhantomJs attempt: ' + f.message);
    }

    try {
        nodeWrite(path, filename, text);
        return;
    } catch (g) {
        errors.push('  NodeJS attempt: ' + g.message);
    }

    // If made it here, no write succeeded.  Let user know.
    this.log("Warning: writing junit report failed for '" + path + "', '" +
             filename + "'. Reasons:\n" +
             errors.join("\n"));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.JsApiReporter"></a>[module jasmine-node.JsApiReporter](#apidoc.module.jasmine-node.JsApiReporter)

#### <a name="apidoc.element.jasmine-node.JsApiReporter.JsApiReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>JsApiReporter ()](#apidoc.element.jasmine-node.JsApiReporter.JsApiReporter)
- description and source-code
```javascript
JsApiReporter = function () {
  this.started = false;
  this.finished = false;
  this.suites_ = [];
  this.results_ = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.JsApiReporter.prototype"></a>[module jasmine-node.JsApiReporter.prototype](#apidoc.module.jasmine-node.JsApiReporter.prototype)

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.JsApiReporter.prototype.log)
- description and source-code
```javascript
log = function (str) {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
  this.finished = true;
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function (runner) {
  this.started = true;
  var suites = runner.topLevelSuites();
  for (var i = 0; i < suites.length; i++) {
    var suite = suites[i];
    this.suites_.push(this.summarize_(suite));
  }
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
  this.results_[spec.id] = {
    messages: spec.results().getItems(),
    result: spec.results().failedCount > 0 ? "failed" : "passed"
  };
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.JsApiReporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function (suite) {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.results"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>results ()](#apidoc.element.jasmine-node.JsApiReporter.prototype.results)
- description and source-code
```javascript
results = function () {
  return this.results_;
}
```
- example usage
```shell
...
      expect(1+2).toEqual(3);
    });
  });

  env.currentRunner().execute();

  waitsFor(function() {
    return env.currentRunner().results().totalCount > 0;
  }, 6000);

  runs(function() {
    expect(env.currentRunner().results().failedCount).toEqual(1);
    expect(firstResult(env.currentRunner()).message).toMatch(/timeout/);;
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.resultsForSpec"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>resultsForSpec (specId)](#apidoc.element.jasmine-node.JsApiReporter.prototype.resultsForSpec)
- description and source-code
```javascript
resultsForSpec = function (specId) {
  return this.results_[specId];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.resultsForSpecs"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>resultsForSpecs (specIds)](#apidoc.element.jasmine-node.JsApiReporter.prototype.resultsForSpecs)
- description and source-code
```javascript
resultsForSpecs = function (specIds){
  var results = {};
  for (var i = 0; i < specIds.length; i++) {
    var specId = specIds[i];
    results[specId] = this.summarizeResult_(this.results_[specId]);
  }
  return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.suites"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>suites ()](#apidoc.element.jasmine-node.JsApiReporter.prototype.suites)
- description and source-code
```javascript
suites = function () {
  return this.suites_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.summarizeResult_"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>summarizeResult_ (result)](#apidoc.element.jasmine-node.JsApiReporter.prototype.summarizeResult_)
- description and source-code
```javascript
summarizeResult_ = function (result){
  var summaryMessages = [];
  var messagesLength = result.messages.length;
  for (var messageIndex = 0; messageIndex < messagesLength; messageIndex++) {
    var resultMessage = result.messages[messageIndex];
    summaryMessages.push({
      text: resultMessage.type == 'log' ? resultMessage.toString() : jasmine.undefined,
      passed: resultMessage.passed ? resultMessage.passed() : true,
      type: resultMessage.type,
      message: resultMessage.message,
      trace: {
        stack: resultMessage.passed && !resultMessage.passed() ? resultMessage.trace.stack : jasmine.undefined
      }
    });
  }

  return {
    result : result.result,
    messages : summaryMessages
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.JsApiReporter.prototype.summarize_"></a>[function <span class="apidocSignatureSpan">jasmine-node.JsApiReporter.prototype.</span>summarize_ (suiteOrSpec)](#apidoc.element.jasmine-node.JsApiReporter.prototype.summarize_)
- description and source-code
```javascript
summarize_ = function (suiteOrSpec) {
  var isSuite = suiteOrSpec instanceof jasmine.Suite;
  var summary = {
    id: suiteOrSpec.id,
    name: suiteOrSpec.description,
    type: isSuite ? 'suite' : 'spec',
    children: []
  };

  if (isSuite) {
    var children = suiteOrSpec.children();
    for (var i = 0; i < children.length; i++) {
      summary.children.push(this.summarize_(children[i]));
    }
  }
  return summary;
}
```
- example usage
```shell
...
    id: 1,
    description: 'the spec',
    isSuite: false
  }
});

it('creates a summary object from spec', function() {
  var result = this.reporter.summarize_(this.spec);

  expect(result.id).toEqual(1);
  expect(result.name).toEqual('the spec');
  expect(result.type).toEqual('spec');
  expect(result.children.length).toEqual(0);
});
...
```



# <a name="apidoc.module.jasmine-node.Matchers"></a>[module jasmine-node.Matchers](#apidoc.module.jasmine-node.Matchers)

#### <a name="apidoc.element.jasmine-node.Matchers.Matchers"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Matchers (env, actual, spec, opt_isNot)](#apidoc.element.jasmine-node.Matchers.Matchers)
- description and source-code
```javascript
Matchers = function (env, actual, spec, opt_isNot) {
  this.env = env;
  this.actual = actual;
  this.spec = spec;
  this.isNot = opt_isNot || false;
  this.reportWasCalled_ = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.Any"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>Any (expectedClass)](#apidoc.element.jasmine-node.Matchers.Any)
- description and source-code
```javascript
Any = function (expectedClass) {
  this.expectedClass = expectedClass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.ObjectContaining"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>ObjectContaining (sample)](#apidoc.element.jasmine-node.Matchers.ObjectContaining)
- description and source-code
```javascript
ObjectContaining = function (sample) {
  this.sample = sample;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.matcherFn_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>matcherFn_ (matcherName, matcherFunction)](#apidoc.element.jasmine-node.Matchers.matcherFn_)
- description and source-code
```javascript
matcherFn_ = function (matcherName, matcherFunction) {
  return function() {
    var matcherArgs = jasmine.util.argsToArray(arguments);
    var result = matcherFunction.apply(this, arguments);

    if (this.isNot) {
      result = !result;
    }

    if (this.reportWasCalled_) return result;

    var message;
    if (!result) {
      if (this.message) {
        message = this.message.apply(this, arguments);
        if (jasmine.isArray_(message)) {
          message = message[this.isNot ? 1 : 0];
        }
      } else {
        var englishyPredicate = matcherName.replace(/[A-Z]/g, function(s) { return ' ' + s.toLowerCase(); });
        message = "Expected " + jasmine.pp(this.actual) + (this.isNot ? " not " : " ") + englishyPredicate;
        if (matcherArgs.length > 0) {
          for (var i = 0; i < matcherArgs.length; i++) {
            if (i > 0) message += ",";
            message += " " + jasmine.pp(matcherArgs[i]);
          }
        }
        message += ".";
      }
    }
    var expectationResult = new jasmine.ExpectationResult({
      matcherName: matcherName,
      passed: result,
      expected: matcherArgs.length > 1 ? matcherArgs : matcherArgs[0],
      actual: this.actual,
      message: message
    });
    this.spec.addMatcherResult(expectationResult);
    return jasmine.undefined;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.pp"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>pp (str)](#apidoc.element.jasmine-node.Matchers.pp)
- description and source-code
```javascript
pp = function (str) {
  throw new Error("jasmine.Matchers.pp() is no longer supported, please use jasmine.pp() instead!");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.wrapInto_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>wrapInto_ (prototype, matchersClass)](#apidoc.element.jasmine-node.Matchers.wrapInto_)
- description and source-code
```javascript
wrapInto_ = function (prototype, matchersClass) {
  for (var methodName in prototype) {
    if (methodName == 'report') continue;
    var orig = prototype[methodName];
    matchersClass.prototype[methodName] = jasmine.Matchers.matcherFn_(methodName, orig);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Matchers.Any"></a>[module jasmine-node.Matchers.Any](#apidoc.module.jasmine-node.Matchers.Any)

#### <a name="apidoc.element.jasmine-node.Matchers.Any.Any"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>Any (expectedClass)](#apidoc.element.jasmine-node.Matchers.Any.Any)
- description and source-code
```javascript
Any = function (expectedClass) {
  this.expectedClass = expectedClass;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Matchers.Any.prototype"></a>[module jasmine-node.Matchers.Any.prototype](#apidoc.module.jasmine-node.Matchers.Any.prototype)

#### <a name="apidoc.element.jasmine-node.Matchers.Any.prototype.jasmineMatches"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.Any.prototype.</span>jasmineMatches (other)](#apidoc.element.jasmine-node.Matchers.Any.prototype.jasmineMatches)
- description and source-code
```javascript
jasmineMatches = function (other) {
  if (this.expectedClass == String) {
    return typeof other == 'string' || other instanceof String;
  }

  if (this.expectedClass == Number) {
    return typeof other == 'number' || other instanceof Number;
  }

  if (this.expectedClass == Function) {
    return typeof other == 'function' || other instanceof Function;
  }

  if (this.expectedClass == Object) {
    return typeof other == 'object';
  }

  return other instanceof this.expectedClass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.Any.prototype.jasmineToString"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.Any.prototype.</span>jasmineToString ()](#apidoc.element.jasmine-node.Matchers.Any.prototype.jasmineToString)
- description and source-code
```javascript
jasmineToString = function () {
  return '<jasmine.any(' + this.expectedClass + ')>';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Matchers.ObjectContaining"></a>[module jasmine-node.Matchers.ObjectContaining](#apidoc.module.jasmine-node.Matchers.ObjectContaining)

#### <a name="apidoc.element.jasmine-node.Matchers.ObjectContaining.ObjectContaining"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.</span>ObjectContaining (sample)](#apidoc.element.jasmine-node.Matchers.ObjectContaining.ObjectContaining)
- description and source-code
```javascript
ObjectContaining = function (sample) {
  this.sample = sample;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Matchers.ObjectContaining.prototype"></a>[module jasmine-node.Matchers.ObjectContaining.prototype](#apidoc.module.jasmine-node.Matchers.ObjectContaining.prototype)

#### <a name="apidoc.element.jasmine-node.Matchers.ObjectContaining.prototype.jasmineMatches"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.ObjectContaining.prototype.</span>jasmineMatches (other, mismatchKeys, mismatchValues)](#apidoc.element.jasmine-node.Matchers.ObjectContaining.prototype.jasmineMatches)
- description and source-code
```javascript
jasmineMatches = function (other, mismatchKeys, mismatchValues) {
  mismatchKeys = mismatchKeys || [];
  mismatchValues = mismatchValues || [];

  var env = jasmine.getEnv();

  var hasKey = function(obj, keyName) {
    return obj != null && obj[keyName] !== jasmine.undefined;
  };

  for (var property in this.sample) {
    if (!hasKey(other, property) && hasKey(this.sample, property)) {
      mismatchKeys.push("expected has key '" + property + "', but missing from actual.");
    }
    else if (!env.equals_(this.sample[property], other[property], mismatchKeys, mismatchValues)) {
      mismatchValues.push("'" + property + "' was '" + (other[property] ? jasmine.util.htmlEscape(other[property].toString()) :
other[property]) + "' in expected, but was '" + (this.sample[property] ? jasmine.util.htmlEscape(this.sample[property].toString()) :
this.sample[property]) + "' in actual.");
    }
  }

  return (mismatchKeys.length === 0 && mismatchValues.length === 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.ObjectContaining.prototype.jasmineToString"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.ObjectContaining.prototype.</span>jasmineToString ()](#apidoc.element.jasmine-node.Matchers.ObjectContaining.prototype.jasmineToString)
- description and source-code
```javascript
jasmineToString = function () {
  return "<jasmine.objectContaining(" + jasmine.pp(this.sample) + ")>";
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Matchers.prototype"></a>[module jasmine-node.Matchers.prototype](#apidoc.module.jasmine-node.Matchers.prototype)

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.report"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>report (result, failing_message, details)](#apidoc.element.jasmine-node.Matchers.prototype.report)
- description and source-code
```javascript
report = function (result, failing_message, details) {
  throw new Error("As of jasmine 0.11, custom matchers must be implemented differently -- please see jasmine docs");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBe"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBe (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toBe)
- description and source-code
```javascript
toBe = function (expected) {
  return this.actual === expected;
}
```
- example usage
```shell
...

describe("Top level describe block", function() {
  it("first it block in top level describe", function() {
    expect(true).toEqual(true);
  });
  describe("Second level describe block", function() {
    it("first it block in second level describe", function() {
      expect(true).toBe(true);
    });
  });
  it("second it block in top level describe", function() {
    expect(true).toEqual(true);
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeCloseTo"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeCloseTo (expected, precision)](#apidoc.element.jasmine-node.Matchers.prototype.toBeCloseTo)
- description and source-code
```javascript
toBeCloseTo = function (expected, precision) {
  if (!(precision === 0)) {
    precision = precision || 2;
  }
  return Math.abs(expected - this.actual) < (Math.pow(10, -precision) / 2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeDefined"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeDefined ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeDefined)
- description and source-code
```javascript
toBeDefined = function () {
  return (this.actual !== jasmine.undefined);
}
```
- example usage
```shell
...
  this.reporter = new jasmineNode.TerminalReporter(config);
  expect(this.reporter.suites_.length).toEqual(0);
});

it('initializes the specResults_ to an Object', function() {
  var config = {}
  this.reporter = new jasmineNode.TerminalReporter(config);
  expect(this.reporter.specResults_).toBeDefined();
});

it('initializes the failures_ array', function() {
  var config = {}
  this.reporter = new jasmineNode.TerminalReporter(config);
  expect(this.reporter.failures_.length).toEqual(0);
});
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeFalsy"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeFalsy ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeFalsy)
- description and source-code
```javascript
toBeFalsy = function () {
  return !this.actual;
}
```
- example usage
```shell
...
    this.reporter = new jasmineNode.TerminalReporter(config);
    expect(this.reporter.includeStackTrace_).toBeTruthy();
});

it('sets the started_ flag to false', function() {
  var config = {}
  this.reporter = new jasmineNode.TerminalReporter(config);
  expect(this.reporter.started_).toBeFalsy();
});

it('sets the finished_ flag to false', function() {
  var config = {}
  this.reporter = new jasmineNode.TerminalReporter(config);
  expect(this.reporter.finished_).toBeFalsy();
});
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeGreaterThan"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeGreaterThan (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toBeGreaterThan)
- description and source-code
```javascript
toBeGreaterThan = function (expected) {
  return this.actual > expected;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeLessThan"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeLessThan (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toBeLessThan)
- description and source-code
```javascript
toBeLessThan = function (expected) {
  return this.actual < expected;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeNaN"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeNaN ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeNaN)
- description and source-code
```javascript
toBeNaN = function () {
  this.message = function() {
    return [ "Expected " + jasmine.pp(this.actual) + " to be NaN." ];
  };

  return (this.actual !== this.actual);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeNull"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeNull ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeNull)
- description and source-code
```javascript
toBeNull = function () {
  return (this.actual === null);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeTruthy"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeTruthy ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeTruthy)
- description and source-code
```javascript
toBeTruthy = function () {
  return !!this.actual;
}
```
- example usage
```shell
...
      runs(function() {
          1+1;
      });
      waitsFor(function() {
          return true === false;
      }, "the impossible", 1000);
      runs(function() {
          expect(true).toBeTruthy();
      });
  });
});

describe('root', function () {

describe('nested', function () {
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toBeUndefined"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toBeUndefined ()](#apidoc.element.jasmine-node.Matchers.prototype.toBeUndefined)
- description and source-code
```javascript
toBeUndefined = function () {
  return (this.actual === jasmine.undefined);
}
```
- example usage
```shell
...
               [ '     the message' ] ];

      expect(this.printLineSpy).toHaveBeenCalled();
      expect(this.printLineSpy.argsForCall).toEqual(generatedOutput);

      expect(this.printSpy).toHaveBeenCalled();
      expect(this.printSpy.argsForCall[0]).toEqual(['Failures:']);
      expect(this.printSpy.argsForCall[1]).toBeUndefined();
  });
});
});

describe('TerminalVerboseReporter', function() {
beforeEach(function() {
  var config = {}
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toContain"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toContain (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toContain)
- description and source-code
```javascript
toContain = function (expected) {
  return this.env.contains_(this.actual, expected);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toEqual"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toEqual (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toEqual)
- description and source-code
```javascript
toEqual = function (expected) {
  return this.env.equals_(this.actual, expected);
}
```
- example usage
```shell
...
asynchronously waiting until the 'done()' callback is called.

'''javascript
var request = require('request');

it("should respond with hello world", function(done) {
  request("http://localhost:3000/hello", function(error, response, body){
    expect(body).toEqual("hello world");
    done();
  });
});
'''

An asynchronous test will fail after '5000' ms if 'done()' is not called. This timeout
can be changed by setting 'jasmine.getEnv().defaultTimeoutInterval' or by passing a timeout
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toHaveBeenCalled"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toHaveBeenCalled ()](#apidoc.element.jasmine-node.Matchers.prototype.toHaveBeenCalled)
- description and source-code
```javascript
toHaveBeenCalled = function () {
  if (arguments.length > 0) {
    throw new Error('toHaveBeenCalled does not take arguments, use toHaveBeenCalledWith');
  }

  if (!jasmine.isSpy(this.actual)) {
    throw new Error('Expected a spy, but got ' + jasmine.pp(this.actual) + '.');
  }

  this.message = function() {
    return [
      "Expected spy " + this.actual.identity + " to have been called.",
      "Expected spy " + this.actual.identity + " not to have been called."
    ];
  };

  return this.actual.wasCalled;
}
```
- example usage
```shell
...
  timerCallback = jasmine.createSpy('timerCallback');
  jasmine.Clock.useMock();
});

it("causes a timeout to be called synchronously", function() {
  setTimeout(timerCallback, 100);

  expect(timerCallback).not.toHaveBeenCalled();

  jasmine.Clock.tick(101);

  expect(timerCallback).toHaveBeenCalled();
});

it("causes an interval to be called synchronously", function() {
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toHaveBeenCalledWith"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toHaveBeenCalledWith ()](#apidoc.element.jasmine-node.Matchers.prototype.toHaveBeenCalledWith)
- description and source-code
```javascript
toHaveBeenCalledWith = function () {
  var expectedArgs = jasmine.util.argsToArray(arguments);
  if (!jasmine.isSpy(this.actual)) {
    throw new Error('Expected a spy, but got ' + jasmine.pp(this.actual) + '.');
  }
  this.message = function() {
    var invertedMessage = "Expected spy " + this.actual.identity + " not to have been called with " + jasmine.pp(expectedArgs) + "
but it was.";
    var positiveMessage = "";
    if (this.actual.callCount === 0) {
      positiveMessage = "Expected spy " + this.actual.identity + " to have been called with " + jasmine.pp(expectedArgs) + " but
 it was never called.";
    } else {
      positiveMessage = "Expected spy " + this.actual.identity + " to have been called with " + jasmine.pp(expectedArgs) + " but
 actual calls were " + jasmine.pp(this.actual.argsForCall).replace(/^\[ | \]$/g, '')
    }
    return [positiveMessage, invertedMessage];
  };

  return this.env.contains_(this.actual.argsForCall, expectedArgs);
}
```
- example usage
```shell
...
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
      passed: function() { return false; }
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toHaveProperty"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toHaveProperty (prop)](#apidoc.element.jasmine-node.Matchers.prototype.toHaveProperty)
- description and source-code
```javascript
toHaveProperty = function (prop) {
    try {
      return prop in this.actual;
    }
    catch (e) {
      return false;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toMatch"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toMatch (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toMatch)
- description and source-code
```javascript
toMatch = function (expected) {
  return new RegExp(expected).test(this.actual);
}
```
- example usage
```shell
...

  waitsFor(function() {
    return env.currentRunner().results().totalCount > 0;
  }, 6000);

  runs(function() {
    expect(env.currentRunner().results().failedCount).toEqual(1);
    expect(firstResult(env.currentRunner()).message).toMatch(/timeout/);;
  });
});

it("should accept timeout for individual spec", function() {
  env.describe("it", function() {
    env.it("doesn't wait", function(done) {
      expect(1+2).toEqual(3);
...
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toNotBe"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotBe (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotBe)
- description and source-code
```javascript
toNotBe = function (expected) {
  return this.actual !== expected;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toNotContain"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotContain (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotContain)
- description and source-code
```javascript
toNotContain = function (expected) {
  return !this.env.contains_(this.actual, expected);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toNotEqual"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotEqual (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotEqual)
- description and source-code
```javascript
toNotEqual = function (expected) {
  return !this.env.equals_(this.actual, expected);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toNotMatch"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toNotMatch (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toNotMatch)
- description and source-code
```javascript
toNotMatch = function (expected) {
  return !(new RegExp(expected).test(this.actual));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.toThrow"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>toThrow (expected)](#apidoc.element.jasmine-node.Matchers.prototype.toThrow)
- description and source-code
```javascript
toThrow = function (expected) {
  var result = false;
  var exception;
  if (typeof this.actual != 'function') {
    throw new Error('Actual is not a function');
  }
  try {
    this.actual();
  } catch (e) {
    exception = e;
  }
  if (exception) {
    result = (expected === jasmine.undefined || this.env.equals_(exception.message || exception, expected.message || expected));
  }

  var not = this.isNot ? "not " : "";

  this.message = function() {
    if (exception && (expected === jasmine.undefined || !this.env.equals_(exception.message || exception, expected.message || expected
))) {
      return ["Expected function " + not + "to throw", expected ? expected.message || expected : "an exception", ", but it threw
", exception.message || exception].join(' ');
    } else {
      return "Expected function to throw an exception.";
    }
  };

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.wasCalled"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasCalled ()](#apidoc.element.jasmine-node.Matchers.prototype.wasCalled)
- description and source-code
```javascript
wasCalled = function () {
  if (arguments.length > 0) {
    throw new Error('toHaveBeenCalled does not take arguments, use toHaveBeenCalledWith');
  }

  if (!jasmine.isSpy(this.actual)) {
    throw new Error('Expected a spy, but got ' + jasmine.pp(this.actual) + '.');
  }

  this.message = function() {
    return [
      "Expected spy " + this.actual.identity + " to have been called.",
      "Expected spy " + this.actual.identity + " not to have been called."
    ];
  };

  return this.actual.wasCalled;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.wasCalledWith"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasCalledWith ()](#apidoc.element.jasmine-node.Matchers.prototype.wasCalledWith)
- description and source-code
```javascript
wasCalledWith = function () {
  var expectedArgs = jasmine.util.argsToArray(arguments);
  if (!jasmine.isSpy(this.actual)) {
    throw new Error('Expected a spy, but got ' + jasmine.pp(this.actual) + '.');
  }
  this.message = function() {
    var invertedMessage = "Expected spy " + this.actual.identity + " not to have been called with " + jasmine.pp(expectedArgs) + "
but it was.";
    var positiveMessage = "";
    if (this.actual.callCount === 0) {
      positiveMessage = "Expected spy " + this.actual.identity + " to have been called with " + jasmine.pp(expectedArgs) + " but
 it was never called.";
    } else {
      positiveMessage = "Expected spy " + this.actual.identity + " to have been called with " + jasmine.pp(expectedArgs) + " but
 actual calls were " + jasmine.pp(this.actual.argsForCall).replace(/^\[ | \]$/g, '')
    }
    return [positiveMessage, invertedMessage];
  };

  return this.env.contains_(this.actual.argsForCall, expectedArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.wasNotCalled"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasNotCalled ()](#apidoc.element.jasmine-node.Matchers.prototype.wasNotCalled)
- description and source-code
```javascript
wasNotCalled = function () {
  if (arguments.length > 0) {
    throw new Error('wasNotCalled does not take arguments');
  }

  if (!jasmine.isSpy(this.actual)) {
    throw new Error('Expected a spy, but got ' + jasmine.pp(this.actual) + '.');
  }

  this.message = function() {
    return [
      "Expected spy " + this.actual.identity + " to not have been called.",
      "Expected spy " + this.actual.identity + " to have been called."
    ];
  };

  return !this.actual.wasCalled;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Matchers.prototype.wasNotCalledWith"></a>[function <span class="apidocSignatureSpan">jasmine-node.Matchers.prototype.</span>wasNotCalledWith ()](#apidoc.element.jasmine-node.Matchers.prototype.wasNotCalledWith)
- description and source-code
```javascript
wasNotCalledWith = function () {
  var expectedArgs = jasmine.util.argsToArray(arguments);
  if (!jasmine.isSpy(this.actual)) {
    throw new Error('Expected a spy, but got ' + jasmine.pp(this.actual) + '.');
  }

  this.message = function() {
    return [
      "Expected spy not to have been called with " + jasmine.pp(expectedArgs) + " but it was",
      "Expected spy to have been called with " + jasmine.pp(expectedArgs) + " but it was"
    ];
  };

  return !this.env.contains_(this.actual.argsForCall, expectedArgs);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.MessageResult"></a>[module jasmine-node.MessageResult](#apidoc.module.jasmine-node.MessageResult)

#### <a name="apidoc.element.jasmine-node.MessageResult.MessageResult"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>MessageResult (values)](#apidoc.element.jasmine-node.MessageResult.MessageResult)
- description and source-code
```javascript
MessageResult = function (values) {
  this.type = 'log';
  this.values = values;
  this.trace = new Error(); // todo: test better
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.MessageResult.prototype"></a>[module jasmine-node.MessageResult.prototype](#apidoc.module.jasmine-node.MessageResult.prototype)

#### <a name="apidoc.element.jasmine-node.MessageResult.prototype.toString"></a>[function <span class="apidocSignatureSpan">jasmine-node.MessageResult.prototype.</span>toString ()](#apidoc.element.jasmine-node.MessageResult.prototype.toString)
- description and source-code
```javascript
toString = function () {
  var text = "";
  for (var i = 0; i < this.values.length; i++) {
    if (i > 0) text += " ";
    if (jasmine.isString_(this.values[i])) {
      text += this.values[i];
    } else {
      text += jasmine.pp(this.values[i]);
    }
  }
  return text;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.MultiReporter"></a>[module jasmine-node.MultiReporter](#apidoc.module.jasmine-node.MultiReporter)

#### <a name="apidoc.element.jasmine-node.MultiReporter.MultiReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>MultiReporter ()](#apidoc.element.jasmine-node.MultiReporter.MultiReporter)
- description and source-code
```javascript
MultiReporter = function () {
  this.subReporters_ = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.MultiReporter.prototype"></a>[module jasmine-node.MultiReporter.prototype](#apidoc.module.jasmine-node.MultiReporter.prototype)

#### <a name="apidoc.element.jasmine-node.MultiReporter.prototype.addReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>addReporter (reporter)](#apidoc.element.jasmine-node.MultiReporter.prototype.addReporter)
- description and source-code
```javascript
addReporter = function (reporter) {
  this.subReporters_.push(reporter);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.MultiReporter.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>log ()](#apidoc.element.jasmine-node.MultiReporter.prototype.log)
- description and source-code
```javascript
log = function () {
  for (var j = 0; j < this.subReporters_.length; j++) {
    var subReporter = this.subReporters_[j];
    if (subReporter[functionName]) {
      subReporter[functionName].apply(subReporter, arguments);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.MultiReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportRunnerResults ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function () {
  for (var j = 0; j < this.subReporters_.length; j++) {
    var subReporter = this.subReporters_[j];
    if (subReporter[functionName]) {
      subReporter[functionName].apply(subReporter, arguments);
    }
  }
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.MultiReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportRunnerStarting ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function () {
  for (var j = 0; j < this.subReporters_.length; j++) {
    var subReporter = this.subReporters_[j];
    if (subReporter[functionName]) {
      subReporter[functionName].apply(subReporter, arguments);
    }
  }
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.MultiReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportSpecResults ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function () {
  for (var j = 0; j < this.subReporters_.length; j++) {
    var subReporter = this.subReporters_[j];
    if (subReporter[functionName]) {
      subReporter[functionName].apply(subReporter, arguments);
    }
  }
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.MultiReporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportSpecStarting ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function () {
  for (var j = 0; j < this.subReporters_.length; j++) {
    var subReporter = this.subReporters_[j];
    if (subReporter[functionName]) {
      subReporter[functionName].apply(subReporter, arguments);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.MultiReporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.MultiReporter.prototype.</span>reportSuiteResults ()](#apidoc.element.jasmine-node.MultiReporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function () {
  for (var j = 0; j < this.subReporters_.length; j++) {
    var subReporter = this.subReporters_[j];
    if (subReporter[functionName]) {
      subReporter[functionName].apply(subReporter, arguments);
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.NUnitXmlReporter"></a>[module jasmine-node.NUnitXmlReporter](#apidoc.module.jasmine-node.NUnitXmlReporter)

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter.NUnitXmlReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>NUnitXmlReporter (options)](#apidoc.element.jasmine-node.NUnitXmlReporter.NUnitXmlReporter)
- description and source-code
```javascript
NUnitXmlReporter = function (options) {
    options = options || {};
    this.savePath = options.savePath || '';
    this.filename = options.filename || 'nunit-results.xml';
    this.reportName = options.reportName || 'Jasmine Results';
    this.testSuites = {};
    this.testSpecs = {};
    this.testRun = {
        suites: []
    };
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.NUnitXmlReporter.prototype"></a>[module jasmine-node.NUnitXmlReporter.prototype](#apidoc.module.jasmine-node.NUnitXmlReporter.prototype)

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
    var output = printTestResults(runner, this);
    this.writeFile(output);
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function (runner) {
    var suites = runner.suites();

    for (var i = 0; i < suites.length; i++) {
        var currentSuite = suites[i];

        var suite = {
            elapsed: 0,
            executed: false,
            id: currentSuite.id,
            name: currentSuite.description,
            specs: [],
            success: false,
            suites: []
        };

        this.testSuites[currentSuite.id] = suite;

        var parent = this.testRun.suites;
        if (currentSuite.parentSuite) {
            parent = this.testSuites[currentSuite.parentSuite.id].suites;
        }

        parent.push(suite);
    }
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
    var elapsed = spec.startTime ? (new Date() - spec.startTime) / 1000 : 0;
    var results = spec.results();
    var skipped = !!results.skipped;
    var id = spec.id;
    var suite = spec.suite;
    var testSuite = this.testSuites[suite.id];
    var testSpec = {
        elapsed: elapsed,
        executed: !skipped,
        failures: [],
        id: spec.id,
        name: spec.description,
        success: results.passed()
    };
    this.testSpecs[spec.id] = testSpec;
    testSuite.specs.push(testSpec);

    if (!testSpec.success) {
        var items = results.getItems();

        for (var i = 0; i < items.length; i++) {
            var result = items[i];
            if (result.passed && !result.passed()) {
                var failure = {
                    message: result.toString(),
                    stack: result.trace.stack ? result.trace.stack : ""
                };
                testSpec.failures.push(failure);
            }
        }
    }

    while (suite) {
        testSuite = this.testSuites[suite.id];
        testSuite.elapsed = testSuite.elapsed ? (testSuite.elapsed + elapsed) : elapsed;
        suite = suite.parentSuite;
    }
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function (spec) {
    spec.startTime = new Date();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function (suite) {
    var id = suite.id;

    var results = suite.results();

    var testSuite = this.testSuites[id];
    testSuite.executed = true;
    testSuite.success = results.passed();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.NUnitXmlReporter.prototype.writeFile"></a>[function <span class="apidocSignatureSpan">jasmine-node.NUnitXmlReporter.prototype.</span>writeFile (text)](#apidoc.element.jasmine-node.NUnitXmlReporter.prototype.writeFile)
- description and source-code
```javascript
writeFile = function (text) {
    var errors = [];
    var path = this.savePath;
    var filename = this.filename;
    function getQualifiedFilename(separator) {
        if (path && path.substr(-1) !== separator && filename.substr(0) !== separator) {
            path += separator;
        }
        return path + filename;
    }

    function rhinoWrite(path, filename, text) {
        if (path) {
            // turn filename into a qualified path
            filename = getQualifiedFilename(java.lang.System.getProperty("file.separator"));
            // create parent dir and ancestors if necessary
            var file = java.io.File(filename);
            var parentDir = file.getParentFile();
            if (!parentDir.exists()) {
                parentDir.mkdirs();
            }
        }
        // finally write the file
        var out = new java.io.BufferedWriter(new java.io.FileWriter(filename));
        out.write(text);
        out.close();
    }

    function phantomWrite(path, filename, text) {
        // turn filename into a qualified path
        filename = getQualifiedFilename(window.fs_path_separator);
        // write via a method injected by phantomjs-testrunner.js
        __phantom_writeFile(filename, text);
    }

    function nodeWrite(path, filename, text) {
        var fs = require("fs");
        var nodejs_path = require("path");
        require("mkdirp").sync(path); // make sure the path exists
        var filepath = nodejs_path.join(path, filename);
        var xmlfile = fs.openSync(filepath, "w");
        fs.writeSync(xmlfile, text, 0);
        fs.closeSync(xmlfile);
    }

    // Attempt writing with each possible environment.
    // Track errors in case no write succeeds
    try {
        rhinoWrite(path, filename, text);
        return;
    } catch (e) {
        errors.push('  Rhino attempt: ' + e.message);
    }

    try {
        phantomWrite(path, filename, text);
        return;
    } catch (f) {
        errors.push('  PhantomJs attempt: ' + f.message);
    }

    try {
        nodeWrite(path, filename, text);
        return;
    } catch (g) {
        errors.push('  NodeJS attempt: ' + g.message);
    }

    // If made it here, no write succeeded.  Let user know.
    console.log("Warning: writing junit report failed for '" + path + "', '" +
        filename + "'. Reasons:\n" +
        errors.join("\n")
    );
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.NestedResults"></a>[module jasmine-node.NestedResults](#apidoc.module.jasmine-node.NestedResults)

#### <a name="apidoc.element.jasmine-node.NestedResults.NestedResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>NestedResults ()](#apidoc.element.jasmine-node.NestedResults.NestedResults)
- description and source-code
```javascript
NestedResults = function () {
<span class="apidocCodeCommentSpan">  /**
   * The total count of results
   */
</span>  this.totalCount = 0;
  /**
   * Number of passed results
   */
  this.passedCount = 0;
  /**
   * Number of failed results
   */
  this.failedCount = 0;
  /**
   * Was this suite/spec skipped?
   */
  this.skipped = false;
  /**
   * @ignore
   */
  this.items_ = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.NestedResults.prototype"></a>[module jasmine-node.NestedResults.prototype](#apidoc.module.jasmine-node.NestedResults.prototype)

#### <a name="apidoc.element.jasmine-node.NestedResults.prototype.addResult"></a>[function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>addResult (result)](#apidoc.element.jasmine-node.NestedResults.prototype.addResult)
- description and source-code
```javascript
addResult = function (result) {
  if (result.type != 'log') {
    if (result.items_) {
      this.rollupCounts(result);
    } else {
      this.totalCount++;
      if (result.passed()) {
        this.passedCount++;
      } else {
        this.failedCount++;
      }
    }
  }
  this.items_.push(result);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.NestedResults.prototype.getItems"></a>[function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>getItems ()](#apidoc.element.jasmine-node.NestedResults.prototype.getItems)
- description and source-code
```javascript
getItems = function () {
  return this.items_;
}
```
- example usage
```shell
...
        expect(env.currentRunner().results().failedCount).toEqual(1);
      });
    });
  });
});

function firstResult(runner) {
  return runner.results().getItems()[0].getItems()[0].getItems()[0];
}
...
```

#### <a name="apidoc.element.jasmine-node.NestedResults.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>log (values)](#apidoc.element.jasmine-node.NestedResults.prototype.log)
- description and source-code
```javascript
log = function (values) {
  this.items_.push(new jasmine.MessageResult(values));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.NestedResults.prototype.passed"></a>[function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>passed ()](#apidoc.element.jasmine-node.NestedResults.prototype.passed)
- description and source-code
```javascript
passed = function () {
  return this.passedCount === this.totalCount;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.NestedResults.prototype.rollupCounts"></a>[function <span class="apidocSignatureSpan">jasmine-node.NestedResults.prototype.</span>rollupCounts (result)](#apidoc.element.jasmine-node.NestedResults.prototype.rollupCounts)
- description and source-code
```javascript
rollupCounts = function (result) {
  this.totalCount += result.totalCount;
  this.passedCount += result.passedCount;
  this.failedCount += result.failedCount;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.PrettyPrinter"></a>[module jasmine-node.PrettyPrinter](#apidoc.module.jasmine-node.PrettyPrinter)

#### <a name="apidoc.element.jasmine-node.PrettyPrinter.PrettyPrinter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>PrettyPrinter ()](#apidoc.element.jasmine-node.PrettyPrinter.PrettyPrinter)
- description and source-code
```javascript
PrettyPrinter = function () {
  this.ppNestLevel_ = 0;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.PrettyPrinter.prototype"></a>[module jasmine-node.PrettyPrinter.prototype](#apidoc.module.jasmine-node.PrettyPrinter.prototype)

#### <a name="apidoc.element.jasmine-node.PrettyPrinter.prototype.emitArray"></a>[function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitArray ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitArray)
- description and source-code
```javascript
emitArray = function () {
  throw new Error("unimplemented method");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.PrettyPrinter.prototype.emitObject"></a>[function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitObject ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitObject)
- description and source-code
```javascript
emitObject = function () {
  throw new Error("unimplemented method");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.PrettyPrinter.prototype.emitScalar"></a>[function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitScalar ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitScalar)
- description and source-code
```javascript
emitScalar = function () {
  throw new Error("unimplemented method");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.PrettyPrinter.prototype.emitString"></a>[function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>emitString ()](#apidoc.element.jasmine-node.PrettyPrinter.prototype.emitString)
- description and source-code
```javascript
emitString = function () {
  throw new Error("unimplemented method");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.PrettyPrinter.prototype.format"></a>[function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>format (value)](#apidoc.element.jasmine-node.PrettyPrinter.prototype.format)
- description and source-code
```javascript
format = function (value) {
  this.ppNestLevel_++;
  try {
    if (value === jasmine.undefined) {
      this.emitScalar('undefined');
    } else if (value === null) {
      this.emitScalar('null');
    } else if (value === jasmine.getGlobal()) {
      this.emitScalar('<global>');
    } else if (value.jasmineToString) {
      this.emitScalar(value.jasmineToString());
    } else if (typeof value === 'string') {
      this.emitString(value);
    } else if (jasmine.isSpy(value)) {
      this.emitScalar("spy on " + value.identity);
    } else if (value instanceof RegExp) {
      this.emitScalar(value.toString());
    } else if (typeof value === 'function') {
      this.emitScalar('Function');
    } else if (typeof value.nodeType === 'number') {
      this.emitScalar('HTMLNode');
    } else if (value instanceof Date) {
      this.emitScalar('Date(' + value + ')');
    } else if (value.__Jasmine_been_here_before__) {
      this.emitScalar('<circular reference: ' + (jasmine.isArray_(value) ? 'Array' : 'Object') + '>');
    } else if (jasmine.isArray_(value) || typeof value == 'object') {
      value.__Jasmine_been_here_before__ = true;
      if (jasmine.isArray_(value)) {
        this.emitArray(value);
      } else {
        this.emitObject(value);
      }
      delete value.__Jasmine_been_here_before__;
    } else {
      this.emitScalar(value.toString());
    }
  } finally {
    this.ppNestLevel_--;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.PrettyPrinter.prototype.iterateObject"></a>[function <span class="apidocSignatureSpan">jasmine-node.PrettyPrinter.prototype.</span>iterateObject (obj, fn)](#apidoc.element.jasmine-node.PrettyPrinter.prototype.iterateObject)
- description and source-code
```javascript
iterateObject = function (obj, fn) {
  for (var property in obj) {
    if (!obj.hasOwnProperty(property)) continue;
    if (property == '__Jasmine_been_here_before__') continue;
    fn(property, obj.__lookupGetter__ ? (obj.__lookupGetter__(property) !== jasmine.undefined &&
                                         obj.__lookupGetter__(property) !== null) : false);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Queue"></a>[module jasmine-node.Queue](#apidoc.module.jasmine-node.Queue)

#### <a name="apidoc.element.jasmine-node.Queue.Queue"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Queue (env)](#apidoc.element.jasmine-node.Queue.Queue)
- description and source-code
```javascript
Queue = function (env) {
  this.env = env;

  // parallel to blocks. each true value in this array means the block will
  // get executed even if we abort
  this.ensured = [];
  this.blocks = [];
  this.running = false;
  this.index = 0;
  this.offset = 0;
  this.abort = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Queue.prototype"></a>[module jasmine-node.Queue.prototype](#apidoc.module.jasmine-node.Queue.prototype)

#### <a name="apidoc.element.jasmine-node.Queue.prototype.add"></a>[function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>add (block, ensure)](#apidoc.element.jasmine-node.Queue.prototype.add)
- description and source-code
```javascript
add = function (block, ensure) {
  if (ensure === jasmine.undefined) {
    ensure = false;
  }

  this.blocks.push(block);
  this.ensured.push(ensure);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Queue.prototype.addBefore"></a>[function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>addBefore (block, ensure)](#apidoc.element.jasmine-node.Queue.prototype.addBefore)
- description and source-code
```javascript
addBefore = function (block, ensure) {
  if (ensure === jasmine.undefined) {
    ensure = false;
  }

  this.blocks.unshift(block);
  this.ensured.unshift(ensure);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Queue.prototype.insertNext"></a>[function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>insertNext (block, ensure)](#apidoc.element.jasmine-node.Queue.prototype.insertNext)
- description and source-code
```javascript
insertNext = function (block, ensure) {
  if (ensure === jasmine.undefined) {
    ensure = false;
  }

  this.ensured.splice((this.index + this.offset + 1), 0, ensure);
  this.blocks.splice((this.index + this.offset + 1), 0, block);
  this.offset++;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Queue.prototype.isRunning"></a>[function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>isRunning ()](#apidoc.element.jasmine-node.Queue.prototype.isRunning)
- description and source-code
```javascript
isRunning = function () {
  return this.running;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Queue.prototype.next_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>next_ ()](#apidoc.element.jasmine-node.Queue.prototype.next_)
- description and source-code
```javascript
next_ = function () {
  var self = this;
  var goAgain = true;

  while (goAgain) {
    goAgain = false;

    if (self.index < self.blocks.length && !(this.abort && !this.ensured[self.index])) {
      var calledSynchronously = true;
      var completedSynchronously = false;

      var onComplete = function () {
        if (jasmine.Queue.LOOP_DONT_RECURSE && calledSynchronously) {
          completedSynchronously = true;
          return;
        }

        if (self.blocks[self.index].abort) {
          self.abort = true;
        }

        self.offset = 0;
        self.index++;

        var now = new Date().getTime();
        if (self.env.updateInterval && now - self.env.lastUpdate > self.env.updateInterval) {
          self.env.lastUpdate = now;
          self.env.setTimeout(function() {
            self.next_();
          }, 0);
        } else {
          if (jasmine.Queue.LOOP_DONT_RECURSE && completedSynchronously) {
            goAgain = true;
          } else {
            self.next_();
          }
        }
      };
      self.blocks[self.index].execute(onComplete);

      calledSynchronously = false;
      if (completedSynchronously) {
        onComplete();
      }

    } else {
      self.running = false;
      if (self.onComplete) {
        self.onComplete();
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Queue.prototype.results"></a>[function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>results ()](#apidoc.element.jasmine-node.Queue.prototype.results)
- description and source-code
```javascript
results = function () {
  var results = new jasmine.NestedResults();
  for (var i = 0; i < this.blocks.length; i++) {
    if (this.blocks[i].results) {
      results.addResult(this.blocks[i].results());
    }
  }
  return results;
}
```
- example usage
```shell
...
      expect(1+2).toEqual(3);
    });
  });

  env.currentRunner().execute();

  waitsFor(function() {
    return env.currentRunner().results().totalCount > 0;
  }, 6000);

  runs(function() {
    expect(env.currentRunner().results().failedCount).toEqual(1);
    expect(firstResult(env.currentRunner()).message).toMatch(/timeout/);;
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.Queue.prototype.start"></a>[function <span class="apidocSignatureSpan">jasmine-node.Queue.prototype.</span>start (onComplete)](#apidoc.element.jasmine-node.Queue.prototype.start)
- description and source-code
```javascript
start = function (onComplete) {
  this.running = true;
  this.onComplete = onComplete;
  this.next_();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Reporter"></a>[module jasmine-node.Reporter](#apidoc.module.jasmine-node.Reporter)

#### <a name="apidoc.element.jasmine-node.Reporter.Reporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Reporter ()](#apidoc.element.jasmine-node.Reporter.Reporter)
- description and source-code
```javascript
Reporter = function () {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Reporter.prototype"></a>[module jasmine-node.Reporter.prototype](#apidoc.module.jasmine-node.Reporter.prototype)

#### <a name="apidoc.element.jasmine-node.Reporter.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.Reporter.prototype.log)
- description and source-code
```javascript
log = function (str) {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Reporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.Reporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.Reporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.Reporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function (runner) {
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.Reporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.Reporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.Reporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.Reporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function (spec) {
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Reporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.Reporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.Reporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function (suite) {
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Runner"></a>[module jasmine-node.Runner](#apidoc.module.jasmine-node.Runner)

#### <a name="apidoc.element.jasmine-node.Runner.Runner"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Runner (env)](#apidoc.element.jasmine-node.Runner.Runner)
- description and source-code
```javascript
Runner = function (env) {
  var self = this;
  self.env = env;
  self.queue = new jasmine.Queue(env);
  self.before_ = [];
  self.after_ = [];
  self.suites_ = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Runner.prototype"></a>[module jasmine-node.Runner.prototype](#apidoc.module.jasmine-node.Runner.prototype)

#### <a name="apidoc.element.jasmine-node.Runner.prototype.add"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>add (block)](#apidoc.element.jasmine-node.Runner.prototype.add)
- description and source-code
```javascript
add = function (block) {
  if (block instanceof jasmine.Suite) {
    this.addSuite(block);
  }
  this.queue.add(block);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.addSuite"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>addSuite (suite)](#apidoc.element.jasmine-node.Runner.prototype.addSuite)
- description and source-code
```javascript
addSuite = function (suite) {
  this.suites_.push(suite);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.afterEach"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>afterEach (afterEachFunction)](#apidoc.element.jasmine-node.Runner.prototype.afterEach)
- description and source-code
```javascript
afterEach = function (afterEachFunction) {
  afterEachFunction.typeName = 'afterEach';
  this.after_.splice(0,0,afterEachFunction);
}
```
- example usage
```shell
...
    });
});

describe("afterEach", function() {
  it("should be passed async callback", function() {
    var completed = false;
    env.describe("afterEach", function() {
      env.afterEach(function(done) {
        process.nextTick(function() {
          done('Failed in afterEach');
          completed = true;
        });
      });
      env.it("should pass", function() {
        this.expect(1+2).toEqual(3);
...
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.beforeEach"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>beforeEach (beforeEachFunction)](#apidoc.element.jasmine-node.Runner.prototype.beforeEach)
- description and source-code
```javascript
beforeEach = function (beforeEachFunction) {
  beforeEachFunction.typeName = 'beforeEach';
  this.before_.splice(0,0,beforeEachFunction);
}
```
- example usage
```shell
...

});

describe("beforeEach", function() {
  it("should wait for callback", function() {
    env.describe("beforeEach", function() {
      var waited = false;
      env.beforeEach(function(done) {
        process.nextTick(function() {
          waited = true;
          done();
        });
      });
      env.it("waited", function() {
        env.currentSpec.expect(waited).toBeTruthy();
...
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.execute"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>execute ()](#apidoc.element.jasmine-node.Runner.prototype.execute)
- description and source-code
```javascript
execute = function () {
  var self = this;
  if (self.env.reporter.reportRunnerStarting) {
    self.env.reporter.reportRunnerStarting(this);
  }
  self.queue.start(function () {
    self.finishCallback();
  });
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.finishCallback"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>finishCallback ()](#apidoc.element.jasmine-node.Runner.prototype.finishCallback)
- description and source-code
```javascript
finishCallback = function () {
  this.env.reporter.reportRunnerResults(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.results"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>results ()](#apidoc.element.jasmine-node.Runner.prototype.results)
- description and source-code
```javascript
results = function () {
  return this.queue.results();
}
```
- example usage
```shell
...
      expect(1+2).toEqual(3);
    });
  });

  env.currentRunner().execute();

  waitsFor(function() {
    return env.currentRunner().results().totalCount > 0;
  }, 6000);

  runs(function() {
    expect(env.currentRunner().results().failedCount).toEqual(1);
    expect(firstResult(env.currentRunner()).message).toMatch(/timeout/);;
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.specs"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>specs ()](#apidoc.element.jasmine-node.Runner.prototype.specs)
- description and source-code
```javascript
specs = function () {
  var suites = this.suites();
  var specs = [];
  for (var i = 0; i < suites.length; i++) {
    specs = specs.concat(suites[i].specs());
  }
  return specs;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.suites"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>suites ()](#apidoc.element.jasmine-node.Runner.prototype.suites)
- description and source-code
```javascript
suites = function () {
  return this.suites_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Runner.prototype.topLevelSuites"></a>[function <span class="apidocSignatureSpan">jasmine-node.Runner.prototype.</span>topLevelSuites ()](#apidoc.element.jasmine-node.Runner.prototype.topLevelSuites)
- description and source-code
```javascript
topLevelSuites = function () {
  var topLevelSuites = [];
  for (var i = 0; i < this.suites_.length; i++) {
    if (!this.suites_[i].parentSuite) {
      topLevelSuites.push(this.suites_[i]);
    }
  }
  return topLevelSuites;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Spec"></a>[module jasmine-node.Spec](#apidoc.module.jasmine-node.Spec)

#### <a name="apidoc.element.jasmine-node.Spec.Spec"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Spec (env, suite, description)](#apidoc.element.jasmine-node.Spec.Spec)
- description and source-code
```javascript
Spec = function (env, suite, description) {
  if (!env) {
    throw new Error('jasmine.Env() required');
  }
  if (!suite) {
    throw new Error('jasmine.Suite() required');
  }
  var spec = this;
  spec.id = env.nextSpecId ? env.nextSpecId() : null;
  spec.env = env;
  spec.suite = suite;
  spec.description = description;
  spec.queue = new jasmine.Queue(env);

  spec.afterCallbacks = [];
  spec.spies_ = [];

  spec.results_ = new jasmine.NestedResults();
  spec.results_.description = description;
  spec.matchersClass = null;
  spec.exclusive_ = suite.exclusive_;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Spec.prototype"></a>[module jasmine-node.Spec.prototype](#apidoc.module.jasmine-node.Spec.prototype)

#### <a name="apidoc.element.jasmine-node.Spec.prototype.addBeforesAndAftersToQueue"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addBeforesAndAftersToQueue ()](#apidoc.element.jasmine-node.Spec.prototype.addBeforesAndAftersToQueue)
- description and source-code
```javascript
addBeforesAndAftersToQueue = function () {
  var runner = this.env.currentRunner();
  var i;

  for (var suite = this.suite; suite; suite = suite.parentSuite) {
    for (i = 0; i < suite.before_.length; i++) {
      this.queue.addBefore(new jasmine.Block(this.env, suite.before_[i], this));
    }
  }
  for (i = 0; i < runner.before_.length; i++) {
    this.queue.addBefore(new jasmine.Block(this.env, runner.before_[i], this));
  }
  for (i = 0; i < this.afterCallbacks.length; i++) {
    this.queue.add(new jasmine.Block(this.env, this.afterCallbacks[i], this), true);
  }
  for (suite = this.suite; suite; suite = suite.parentSuite) {
    for (i = 0; i < suite.after_.length; i++) {
      this.queue.add(new jasmine.Block(this.env, suite.after_[i], this), true);
    }
  }
  for (i = 0; i < runner.after_.length; i++) {
    this.queue.add(new jasmine.Block(this.env, runner.after_[i], this), true);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.addMatcherResult"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addMatcherResult (result)](#apidoc.element.jasmine-node.Spec.prototype.addMatcherResult)
- description and source-code
```javascript
addMatcherResult = function (result) {
  this.results_.addResult(result);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.addMatchers"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addMatchers (matchersPrototype)](#apidoc.element.jasmine-node.Spec.prototype.addMatchers)
- description and source-code
```javascript
addMatchers = function (matchersPrototype) {
  var parent = this.getMatchersClass_();
  var newMatchersClass = function() {
    parent.apply(this, arguments);
  };
  jasmine.util.inherit(newMatchersClass, parent);
  jasmine.Matchers.wrapInto_(matchersPrototype, newMatchersClass);
  this.matchersClass = newMatchersClass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.addToQueue"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>addToQueue (block)](#apidoc.element.jasmine-node.Spec.prototype.addToQueue)
- description and source-code
```javascript
addToQueue = function (block) {
  if (this.queue.isRunning()) {
    this.queue.insertNext(block);
  } else {
    this.queue.add(block);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.after"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>after (doAfter)](#apidoc.element.jasmine-node.Spec.prototype.after)
- description and source-code
```javascript
after = function (doAfter) {
  if (this.queue.isRunning()) {
    this.queue.add(new jasmine.Block(this.env, doAfter, this), true);
  } else {
    this.afterCallbacks.unshift(doAfter);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.execute"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.Spec.prototype.execute)
- description and source-code
```javascript
execute = function (onComplete) {
  var spec = this;
  if (!spec.env.specFilter(spec)) {
    spec.results_.skipped = true;
    spec.finish(onComplete);
    return;
  }

  this.env.reporter.reportSpecStarting(this);

  spec.env.currentSpec = spec;

  spec.addBeforesAndAftersToQueue();

  spec.queue.start(function () {
    spec.finish(onComplete);
  });
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.expect"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>expect (actual)](#apidoc.element.jasmine-node.Spec.prototype.expect)
- description and source-code
```javascript
expect = function (actual) {
  var positive = new (this.getMatchersClass_())(this.env, actual, this);
  positive.not = new (this.getMatchersClass_())(this.env, actual, this, true);
  return positive;
}
```
- example usage
```shell
...
    });


    it("should finish after callback is called", function() {
env.describe("it", function() {
  env.it("waits", function(done) {
    process.nextTick(function() {
      env.currentSpec.expect(1+2).toEqual(3);
      done();
    });
  });
});

env.currentRunner().execute();
...
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.explodes"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>explodes ()](#apidoc.element.jasmine-node.Spec.prototype.explodes)
- description and source-code
```javascript
explodes = function () {
  throw 'explodes function should not have been called';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.fail"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>fail (e)](#apidoc.element.jasmine-node.Spec.prototype.fail)
- description and source-code
```javascript
fail = function (e) {
  var expectationResult = new jasmine.ExpectationResult({
    passed: false,
    message: e ? jasmine.util.formatException(e) : 'Exception',
    trace: { stack: e.stack }
  });
  this.results_.addResult(expectationResult);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.finish"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>finish (onComplete)](#apidoc.element.jasmine-node.Spec.prototype.finish)
- description and source-code
```javascript
finish = function (onComplete) {
  this.removeAllSpies();
  this.finishCallback();
  if (onComplete) {
    onComplete();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.finishCallback"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>finishCallback ()](#apidoc.element.jasmine-node.Spec.prototype.finishCallback)
- description and source-code
```javascript
finishCallback = function () {
  this.env.reporter.reportSpecResults(this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.getFullName"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>getFullName ()](#apidoc.element.jasmine-node.Spec.prototype.getFullName)
- description and source-code
```javascript
getFullName = function () {
  return this.suite.getFullName() + ' ' + this.description + '.';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.getMatchersClass_"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>getMatchersClass_ ()](#apidoc.element.jasmine-node.Spec.prototype.getMatchersClass_)
- description and source-code
```javascript
getMatchersClass_ = function () {
  return this.matchersClass || this.env.matchersClass;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>log ()](#apidoc.element.jasmine-node.Spec.prototype.log)
- description and source-code
```javascript
log = function () {
  return this.results_.log(arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.removeAllSpies"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>removeAllSpies ()](#apidoc.element.jasmine-node.Spec.prototype.removeAllSpies)
- description and source-code
```javascript
removeAllSpies = function () {
  for (var i = 0; i < this.spies_.length; i++) {
    var spy = this.spies_[i];
    spy.baseObj[spy.methodName] = spy.originalValue;
  }
  this.spies_ = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.results"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>results ()](#apidoc.element.jasmine-node.Spec.prototype.results)
- description and source-code
```javascript
results = function () {
  return this.results_;
}
```
- example usage
```shell
...
      expect(1+2).toEqual(3);
    });
  });

  env.currentRunner().execute();

  waitsFor(function() {
    return env.currentRunner().results().totalCount > 0;
  }, 6000);

  runs(function() {
    expect(env.currentRunner().results().failedCount).toEqual(1);
    expect(firstResult(env.currentRunner()).message).toMatch(/timeout/);;
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.runs"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>runs (func)](#apidoc.element.jasmine-node.Spec.prototype.runs)
- description and source-code
```javascript
runs = function (func) {
  var block = new jasmine.Block(this.env, func, this);
  this.addToQueue(block);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.spyOn"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>spyOn (obj, methodName, ignoreMethodDoesntExist)](#apidoc.element.jasmine-node.Spec.prototype.spyOn)
- description and source-code
```javascript
spyOn = function (obj, methodName, ignoreMethodDoesntExist) {
  if (obj == jasmine.undefined) {
    throw "spyOn could not find an object to spy upon for " + methodName + "()";
  }

  if (!ignoreMethodDoesntExist && obj[methodName] === jasmine.undefined) {
    throw methodName + '() method does not exist';
  }

  if (!ignoreMethodDoesntExist && obj[methodName] && obj[methodName].isSpy) {
    throw new Error(methodName + ' has already been spied upon');
  }

  var spyObj = jasmine.createSpy(methodName);

  this.spies_.push(spyObj);
  spyObj.baseObj = obj;
  spyObj.methodName = methodName;
  spyObj.originalValue = obj[methodName];

  obj[methodName] = spyObj;

  return spyObj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.waits"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>waits (timeout)](#apidoc.element.jasmine-node.Spec.prototype.waits)
- description and source-code
```javascript
waits = function (timeout) {
  var waitsFunc = new jasmine.WaitsBlock(this.env, timeout, this);
  this.addToQueue(waitsFunc);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spec.prototype.waitsFor"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spec.prototype.</span>waitsFor (latchFunction, optional_timeoutMessage, optional_timeout)](#apidoc.element.jasmine-node.Spec.prototype.waitsFor)
- description and source-code
```javascript
waitsFor = function (latchFunction, optional_timeoutMessage, optional_timeout) {
  var latchFunction_ = null;
  var optional_timeoutMessage_ = null;
  var optional_timeout_ = null;

  for (var i = 0; i < arguments.length; i++) {
    var arg = arguments[i];
    switch (typeof arg) {
      case 'function':
        latchFunction_ = arg;
        break;
      case 'string':
        optional_timeoutMessage_ = arg;
        break;
      case 'number':
        optional_timeout_ = arg;
        break;
    }
  }

  var waitsForFunc = new jasmine.WaitsForBlock(this.env, optional_timeout_, latchFunction_, optional_timeoutMessage_, this);
  this.addToQueue(waitsForFunc);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Spy"></a>[module jasmine-node.Spy](#apidoc.module.jasmine-node.Spy)

#### <a name="apidoc.element.jasmine-node.Spy.Spy"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Spy (name)](#apidoc.element.jasmine-node.Spy.Spy)
- description and source-code
```javascript
Spy = function (name) {
<span class="apidocCodeCommentSpan">  /**
   * The name of the spy, if provided.
   */
</span>  this.identity = name || 'unknown';
  /**
   *  Is this Object a spy?
   */
  this.isSpy = true;
  /**
   * The actual function this spy stubs.
   */
  this.plan = function() {
  };
  /**
   * Tracking of the most recent call to the spy.
   * @example
   * var mySpy = jasmine.createSpy('foo');
   * mySpy(1, 2);
   * mySpy.mostRecentCall.args = [1, 2];
   */
  this.mostRecentCall = {};

  /**
   * Holds arguments for each call to the spy, indexed by call count
   * @example
   * var mySpy = jasmine.createSpy('foo');
   * mySpy(1, 2);
   * mySpy(7, 8);
   * mySpy.mostRecentCall.args = [7, 8];
   * mySpy.argsForCall[0] = [1, 2];
   * mySpy.argsForCall[1] = [7, 8];
   */
  this.argsForCall = [];
  this.calls = [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Spy.prototype"></a>[module jasmine-node.Spy.prototype](#apidoc.module.jasmine-node.Spy.prototype)

#### <a name="apidoc.element.jasmine-node.Spy.prototype.andCallFake"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andCallFake (fakeFunc)](#apidoc.element.jasmine-node.Spy.prototype.andCallFake)
- description and source-code
```javascript
andCallFake = function (fakeFunc) {
  this.plan = fakeFunc;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spy.prototype.andCallThrough"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andCallThrough ()](#apidoc.element.jasmine-node.Spy.prototype.andCallThrough)
- description and source-code
```javascript
andCallThrough = function () {
  this.plan = this.originalValue;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spy.prototype.andReturn"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andReturn (value)](#apidoc.element.jasmine-node.Spy.prototype.andReturn)
- description and source-code
```javascript
andReturn = function (value) {
  this.plan = function() {
    return value;
  };
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spy.prototype.andThrow"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>andThrow (exceptionMsg)](#apidoc.element.jasmine-node.Spy.prototype.andThrow)
- description and source-code
```javascript
andThrow = function (exceptionMsg) {
  this.plan = function() {
    throw exceptionMsg;
  };
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Spy.prototype.reset"></a>[function <span class="apidocSignatureSpan">jasmine-node.Spy.prototype.</span>reset ()](#apidoc.element.jasmine-node.Spy.prototype.reset)
- description and source-code
```javascript
reset = function () {
  this.wasCalled = false;
  this.callCount = 0;
  this.argsForCall = [];
  this.calls = [];
  this.mostRecentCall = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.StringPrettyPrinter"></a>[module jasmine-node.StringPrettyPrinter](#apidoc.module.jasmine-node.StringPrettyPrinter)

#### <a name="apidoc.element.jasmine-node.StringPrettyPrinter.StringPrettyPrinter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>StringPrettyPrinter ()](#apidoc.element.jasmine-node.StringPrettyPrinter.StringPrettyPrinter)
- description and source-code
```javascript
StringPrettyPrinter = function () {
  jasmine.PrettyPrinter.call(this);

  this.string = '';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.StringPrettyPrinter.prototype"></a>[module jasmine-node.StringPrettyPrinter.prototype](#apidoc.module.jasmine-node.StringPrettyPrinter.prototype)

#### <a name="apidoc.element.jasmine-node.StringPrettyPrinter.prototype.append"></a>[function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>append (value)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.append)
- description and source-code
```javascript
append = function (value) {
  this.string += value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitArray"></a>[function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitArray (array)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitArray)
- description and source-code
```javascript
emitArray = function (array) {
  if (this.ppNestLevel_ > jasmine.MAX_PRETTY_PRINT_DEPTH) {
    this.append("Array");
    return;
  }

  this.append('[ ');
  for (var i = 0; i < array.length; i++) {
    if (i > 0) {
      this.append(', ');
    }
    this.format(array[i]);
  }
  this.append(' ]');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitObject"></a>[function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitObject (obj)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitObject)
- description and source-code
```javascript
emitObject = function (obj) {
  if (this.ppNestLevel_ > jasmine.MAX_PRETTY_PRINT_DEPTH) {
    this.append("Object");
    return;
  }

  var self = this;
  this.append('{ ');
  var first = true;

  this.iterateObject(obj, function(property, isGetter) {
    if (first) {
      first = false;
    } else {
      self.append(', ');
    }

    self.append(property);
    self.append(' : ');
    if (isGetter) {
      self.append('<getter>');
    } else {
      self.format(obj[property]);
    }
  });

  this.append(' }');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitScalar"></a>[function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitScalar (value)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitScalar)
- description and source-code
```javascript
emitScalar = function (value) {
  this.append(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitString"></a>[function <span class="apidocSignatureSpan">jasmine-node.StringPrettyPrinter.prototype.</span>emitString (value)](#apidoc.element.jasmine-node.StringPrettyPrinter.prototype.emitString)
- description and source-code
```javascript
emitString = function (value) {
  this.append("'" + value + "'");
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.Suite"></a>[module jasmine-node.Suite](#apidoc.module.jasmine-node.Suite)

#### <a name="apidoc.element.jasmine-node.Suite.Suite"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>Suite (env, description, specDefinitions, parentSuite)](#apidoc.element.jasmine-node.Suite.Suite)
- description and source-code
```javascript
Suite = function (env, description, specDefinitions, parentSuite) {
  var self = this;
  self.id = env.nextSuiteId ? env.nextSuiteId() : null;
  self.description = description;
  self.queue = new jasmine.Queue(env);
  self.parentSuite = parentSuite;
  self.env = env;
  self.before_ = [];
  self.after_ = [];
  self.children_ = [];
  self.suites_ = [];
  self.specs_ = [];
  self.exclusive_ = parentSuite && parentSuite.exclusive_ || 0;
}
```
- example usage
```shell
...
expect(result.name).toEqual('the spec');
expect(result.type).toEqual('spec');
expect(result.children.length).toEqual(0);
    });

    it('creates a summary object from suite with 1 spec', function() {
var env = { nextSuiteId: false }
var suite = new jasmine.Suite(env, 'suite name', undefined, undefined);
suite.description = 'the suite';
suite.parentSuite = null;
suite.children_.push(this.spec);

var result = this.reporter.summarize_(suite);
expect(result.name).toEqual('the suite');
expect(result.type).toEqual('suite');
...
```



# <a name="apidoc.module.jasmine-node.Suite.prototype"></a>[module jasmine-node.Suite.prototype](#apidoc.module.jasmine-node.Suite.prototype)

#### <a name="apidoc.element.jasmine-node.Suite.prototype.add"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>add (suiteOrSpec)](#apidoc.element.jasmine-node.Suite.prototype.add)
- description and source-code
```javascript
add = function (suiteOrSpec) {
  this.children_.push(suiteOrSpec);
  if (suiteOrSpec instanceof jasmine.Suite) {
    this.suites_.push(suiteOrSpec);
    this.env.currentRunner().addSuite(suiteOrSpec);
  } else {
    this.specs_.push(suiteOrSpec);
  }
  this.queue.add(suiteOrSpec);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.afterEach"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>afterEach (afterEachFunction)](#apidoc.element.jasmine-node.Suite.prototype.afterEach)
- description and source-code
```javascript
afterEach = function (afterEachFunction) {
  afterEachFunction.typeName = 'afterEach';
  this.after_.unshift(afterEachFunction);
}
```
- example usage
```shell
...
    });
});

describe("afterEach", function() {
  it("should be passed async callback", function() {
    var completed = false;
    env.describe("afterEach", function() {
      env.afterEach(function(done) {
        process.nextTick(function() {
          done('Failed in afterEach');
          completed = true;
        });
      });
      env.it("should pass", function() {
        this.expect(1+2).toEqual(3);
...
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.beforeEach"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>beforeEach (beforeEachFunction)](#apidoc.element.jasmine-node.Suite.prototype.beforeEach)
- description and source-code
```javascript
beforeEach = function (beforeEachFunction) {
  beforeEachFunction.typeName = 'beforeEach';
  this.before_.unshift(beforeEachFunction);
}
```
- example usage
```shell
...

});

describe("beforeEach", function() {
  it("should wait for callback", function() {
    env.describe("beforeEach", function() {
      var waited = false;
      env.beforeEach(function(done) {
        process.nextTick(function() {
          waited = true;
          done();
        });
      });
      env.it("waited", function() {
        env.currentSpec.expect(waited).toBeTruthy();
...
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.children"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>children ()](#apidoc.element.jasmine-node.Suite.prototype.children)
- description and source-code
```javascript
children = function () {
  return this.children_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.execute"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.Suite.prototype.execute)
- description and source-code
```javascript
execute = function (onComplete) {
  var self = this;
  this.queue.start(function () {
    self.finish(onComplete);
  });
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.finish"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>finish (onComplete)](#apidoc.element.jasmine-node.Suite.prototype.finish)
- description and source-code
```javascript
finish = function (onComplete) {
  this.env.reporter.reportSuiteResults(this);
  this.finished = true;
  if (typeof(onComplete) == 'function') {
    onComplete();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.getFullName"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>getFullName ()](#apidoc.element.jasmine-node.Suite.prototype.getFullName)
- description and source-code
```javascript
getFullName = function () {
  var fullName = this.description;
  for (var parentSuite = this.parentSuite; parentSuite; parentSuite = parentSuite.parentSuite) {
    fullName = parentSuite.description + ' ' + fullName;
  }
  return fullName;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.results"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>results ()](#apidoc.element.jasmine-node.Suite.prototype.results)
- description and source-code
```javascript
results = function () {
  return this.queue.results();
}
```
- example usage
```shell
...
      expect(1+2).toEqual(3);
    });
  });

  env.currentRunner().execute();

  waitsFor(function() {
    return env.currentRunner().results().totalCount > 0;
  }, 6000);

  runs(function() {
    expect(env.currentRunner().results().failedCount).toEqual(1);
    expect(firstResult(env.currentRunner()).message).toMatch(/timeout/);;
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.specs"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>specs ()](#apidoc.element.jasmine-node.Suite.prototype.specs)
- description and source-code
```javascript
specs = function () {
  return this.specs_;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.Suite.prototype.suites"></a>[function <span class="apidocSignatureSpan">jasmine-node.Suite.prototype.</span>suites ()](#apidoc.element.jasmine-node.Suite.prototype.suites)
- description and source-code
```javascript
suites = function () {
  return this.suites_;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.TapReporter"></a>[module jasmine-node.TapReporter](#apidoc.module.jasmine-node.TapReporter)

#### <a name="apidoc.element.jasmine-node.TapReporter.TapReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>TapReporter ()](#apidoc.element.jasmine-node.TapReporter.TapReporter)
- description and source-code
```javascript
TapReporter = function () {
    this.started = false;
    this.finished = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.TapReporter.prototype"></a>[module jasmine-node.TapReporter.prototype](#apidoc.module.jasmine-node.TapReporter.prototype)

#### <a name="apidoc.element.jasmine-node.TapReporter.prototype.log"></a>[function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>log (str)](#apidoc.element.jasmine-node.TapReporter.prototype.log)
- description and source-code
```javascript
log = function (str) {
    var console = jasmine.getGlobal().console;
    if (console && console.log) {
        console.log(str);
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TapReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.TapReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
    var dur = (new Date()).getTime() - this.start_time;
    var failed = this.executed_specs - this.passed_specs;
    var spec_str = this.executed_specs + (this.executed_specs === 1 ? " spec, " : " specs, ");
    var fail_str = failed + (failed === 1 ? " failure in " : " failures in ");
    var assert_str = this.executed_asserts + (this.executed_asserts === 1 ? " assertion, " : " assertions, ");

    if (this.executed_asserts) {
        this.log("# "+ spec_str + assert_str + fail_str + (dur/1000) + "s.");
    } else {
        this.log('not ok 1 - no asserts run.');
    }
    this.finished = true;
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.TapReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.TapReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function (runner) {
    this.started = true;
    this.start_time = (new Date()).getTime();
    this.executed_specs = 0;
    this.passed_specs = 0;
    this.executed_asserts = 0;
    this.passed_asserts = 0;
    // should have at least 1 spec, otherwise it's considered a failure
    this.log('1..'+ Math.max(runner.specs().length, 1));
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.TapReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.TapReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
    var resultText = "not ok";
    var errorMessage = '';

    var results = spec.results();
    if (results.skipped) {
        return;
    }
    var passed = results.passed();

    this.passed_asserts += results.passedCount;
    this.executed_asserts += results.totalCount;

    if (passed) {
        this.passed_specs++;
        resultText = "ok";
    } else {
        var items = results.getItems();
        var i = 0;
        var expectationResult, stackMessage;
        while (expectationResult = items[i++]) {
            if (expectationResult.trace) {
                stackMessage = expectationResult.trace.stack? expectationResult.trace.stack : expectationResult.message;
                errorMessage += '\n  '+ stackMessage;
            }
        }
    }

    this.log(resultText +" "+ (spec.id + 1) +" - "+ spec.suite.description +" : "+ spec.description + errorMessage);
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.TapReporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.TapReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.TapReporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function (spec) {
    this.executed_specs++;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.TerminalReporter"></a>[module jasmine-node.TerminalReporter](#apidoc.module.jasmine-node.TerminalReporter)

#### <a name="apidoc.element.jasmine-node.TerminalReporter.TerminalReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalReporter (config)](#apidoc.element.jasmine-node.TerminalReporter.TerminalReporter)
- description and source-code
```javascript
TerminalReporter = function (config) {
  this.print_ = config.print || function (str) { process.stdout.write(util.format(str)); };
  this.color_ = config.color ? this.ANSIColors : this.NoColors;

  this.started_ = false;
  this.finished_ = false;

  this.callback_ = config.onComplete || false

  this.suites_ = [];
  this.specResults_ = {};
  this.failures_ = [];
  this.includeStackTrace_ = config.includeStackTrace === false ? false : true;
  this.stackFilter_ = config.stackFilter || function(t) { return t; };
}
```
- example usage
```shell
...


var jasmineNode = require(__dirname + "/../lib/jasmine-node/reporter").jasmineNode;

describe('TerminalReporter', function() {
beforeEach(function() {
  var config = {}
  this.reporter = new jasmineNode.TerminalReporter(config);
});

describe("initialize", function() {
  it('initializes print_ from config', function() {
    var config = { print: true };
    this.reporter = new jasmineNode.TerminalReporter(config);
    expect(this.reporter.print_).toBeTruthy();
...
```



# <a name="apidoc.module.jasmine-node.TerminalReporter.prototype"></a>[module jasmine-node.TerminalReporter.prototype](#apidoc.module.jasmine-node.TerminalReporter.prototype)

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.addFailureToFailures_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>addFailureToFailures_ (spec)](#apidoc.element.jasmine-node.TerminalReporter.prototype.addFailureToFailures_)
- description and source-code
```javascript
addFailureToFailures_ = function (spec) {
  var result = spec.results();
  var failureItem = null;

  var items_length = result.items_.length;
  for (var i = 0; i < items_length; i++) {
    if (result.items_[i].passed_ === false) {
      failureItem = result.items_[i];

      var failure = {
        spec: spec.suite.getFullName() + " " + spec.description,
        message: failureItem.message,
        stackTrace: failureItem.trace.stack
      }

      this.failures_.push(failure);
    }
  }
}
```
- example usage
```shell
...
        return theItems;
      }.call()
    };
    return result;
  }
};

this.reporter.addFailureToFailures_(spec);

var failures = this.reporter.failures_;
expect(failures.length).toEqual(1);
var failure = failures[0];
expect(failure.spec).toEqual('Suite name the spec');
expect(failure.message).toEqual('the message');
expect(failure.stackTrace).toEqual('the stack');
...
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.printLine_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>printLine_ (stringValue)](#apidoc.element.jasmine-node.TerminalReporter.prototype.printLine_)
- description and source-code
```javascript
printLine_ = function (stringValue) {
  this.print_(stringValue);
  this.print_('\n');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.printRunnerResults_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>printRunnerResults_ (runner)](#apidoc.element.jasmine-node.TerminalReporter.prototype.printRunnerResults_)
- description and source-code
```javascript
printRunnerResults_ = function (runner){
  var results = runner.results();
  var specs = runner.specs();
  var msg = '';
  var skippedCount = 0;
  specs.forEach(function(spec) {
    if (spec.results().skipped) {
      skippedCount++;
    }
  });
  var passedCount = specs.length - skippedCount;
  msg += passedCount + ' test' + ((passedCount === 1) ? '' : 's') + ', ';
  msg += results.totalCount + ' assertion' + ((results.totalCount === 1) ? '' : 's') + ', ';
  msg += results.failedCount + ' failure' + ((results.failedCount === 1) ? '' : 's') + ', ';
  msg += skippedCount + ' skipped' + '\n';
  return msg;
}
```
- example usage
```shell
...
        _specs.push(spec);
        return _specs;
      }
    };
  });

  it('uses the specs\'s length, totalCount and failedCount', function() {
    var message = this.reporter.printRunnerResults_(this.runner);
    expect(message).toEqual('1 test, 23 assertions, 52 failures, 0 skipped\n');
  });
});

describe('reports failures', function() {
  beforeEach(function() {
    this.printSpy = spyOn(this.reporter, 'print_');
...
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.reportFailures_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportFailures_ ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportFailures_)
- description and source-code
```javascript
reportFailures_ = function () {
  if (this.failures_.length === 0) {
    return;
  }

  var indent = '  ', failure;
  this.printLine_('\n');

  this.print_('Failures:');

  for (var i = 0; i < this.failures_.length; i++) {
    failure = this.failures_[i];
    this.printLine_('\n');
    this.printLine_('  ' + (i + 1) + ') ' + failure.spec);
    this.printLine_('   Message:');
    this.printLine_('     ' + this.stringWithColor_(failure.message, this.color_.fail()));
    if (this.includeStackTrace_) {
        this.printLine_('   Stacktrace:');
        this.print_('     ' + this.stackFilter_(failure.stackTrace));
    }
  }
}
```
- example usage
```shell
...
  this.printSpy = spyOn(this.reporter, 'print_');
  this.printLineSpy = spyOn(this.reporter, 'printLine_');
});

it('does not report anything when there are no failures', function() {
  this.reporter.failures_ = new Array();

  this.reporter.reportFailures_();

  expect(this.printLineSpy).not.toHaveBeenCalled();
});

it('prints the failures', function() {
  var failure = {
    spec: 'the spec',
...
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
  this.reportFailures_();

  var results = runner.results();
  var resultColor = (results.failedCount > 0) ? this.color_.fail() : this.color_.pass();

  var specs = runner.specs();
  var specCount = specs.length;

  var message = "\n\nFinished in " + ((new Date().getTime() - this.startedAt.getTime()) / 1000) + " seconds";
  this.printLine_(message);

  // This is what jasmine-html.js has
  //message = "" + specCount + " spec" + ( specCount === 1 ? "" : "s" ) + ", " + results.failedCount + " failure" + ((results.failedCount
 === 1) ? "" : "s");

  this.printLine_(this.stringWithColor_(this.printRunnerResults_(runner), resultColor));

  this.finished_ = true;
  if(this.callback_) { this.callback_(runner); }
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.reportRunnerStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportRunnerStarting (runner)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportRunnerStarting)
- description and source-code
```javascript
reportRunnerStarting = function (runner) {
  this.started_ = true;
  this.startedAt = new Date();
  var suites = runner.topLevelSuites();
  for (var i = 0; i < suites.length; i++) {
    var suite = suites[i];
    this.suites_.push(this.summarize_(suite));
  }
}
```
- example usage
```shell
...
    topLevelSuites: function() {
      var suites = [];
      var suite = { id: 25 };
      suites.push(suite);
      return suites;
    }
  };
  this.reporter.reportRunnerStarting(runner);
});

it('sets the started_ field to true', function() {
  expect(this.reporter.started_).toBeTruthy();
});

it('sets the startedAt field', function() {
...
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
  var result = spec.results();
  var msg = '';
  if (result.skipped) {
    msg = this.stringWithColor_('-', this.color_.ignore());
  } else if (result.passed()) {
    msg = this.stringWithColor_('.', this.color_.pass());
  } else {
    msg = this.stringWithColor_('F', this.color_.fail());
    this.addFailureToFailures_(spec);
  }
  this.spec_results += msg;
  this.print_(msg);
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.TerminalReporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function (suite) {
  // Not used in this context
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.stringWithColor_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>stringWithColor_ (stringValue, color)](#apidoc.element.jasmine-node.TerminalReporter.prototype.stringWithColor_)
- description and source-code
```javascript
stringWithColor_ = function (stringValue, color) {
  return (color || this.color_.neutral()) + stringValue + this.color_.neutral();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.summarize_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.</span>summarize_ (suiteOrSpec)](#apidoc.element.jasmine-node.TerminalReporter.prototype.summarize_)
- description and source-code
```javascript
summarize_ = function (suiteOrSpec) {
  var isSuite = suiteOrSpec instanceof jasmine.Suite;

  // We could use a separate object for suite and spec
  var summary = {
    id: suiteOrSpec.id,
    name: suiteOrSpec.description,
    type: isSuite? 'suite' : 'spec',
    suiteNestingLevel: 0,
    children: []
  };

  if (isSuite) {
    var calculateNestingLevel = function(examinedSuite) {
      var nestingLevel = 0;
      while (examinedSuite.parentSuite !== null) {
        nestingLevel += 1;
        examinedSuite = examinedSuite.parentSuite;
      }
      return nestingLevel;
    };

    summary.suiteNestingLevel = calculateNestingLevel(suiteOrSpec);

    var children = suiteOrSpec.children();
    for (var i = 0; i < children.length; i++) {
      summary.children.push(this.summarize_(children[i]));
    }
  }

  return summary;
}
```
- example usage
```shell
...
    id: 1,
    description: 'the spec',
    isSuite: false
  }
});

it('creates a summary object from spec', function() {
  var result = this.reporter.summarize_(this.spec);

  expect(result.id).toEqual(1);
  expect(result.name).toEqual('the spec');
  expect(result.type).toEqual('spec');
  expect(result.children.length).toEqual(0);
});
...
```



# <a name="apidoc.module.jasmine-node.TerminalReporter.prototype.ANSIColors"></a>[module jasmine-node.TerminalReporter.prototype.ANSIColors](#apidoc.module.jasmine-node.TerminalReporter.prototype.ANSIColors)

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.fail"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>fail ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.fail)
- description and source-code
```javascript
fail = function () { return '\033[31m'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.ignore"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>ignore ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.ignore)
- description and source-code
```javascript
ignore = function () { return '\033[37m'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.neutral"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>neutral ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.neutral)
- description and source-code
```javascript
neutral = function () { return '\033[0m';  }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.pass"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>pass ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.pass)
- description and source-code
```javascript
pass = function () { return '\033[32m'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.specTiming"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>specTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.specTiming)
- description and source-code
```javascript
specTiming = function ()  { return '\033[34m'; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.suiteTiming"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.ANSIColors.</span>suiteTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.ANSIColors.suiteTiming)
- description and source-code
```javascript
suiteTiming = function () { return '\033[33m'; }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.TerminalReporter.prototype.NoColors"></a>[module jasmine-node.TerminalReporter.prototype.NoColors](#apidoc.module.jasmine-node.TerminalReporter.prototype.NoColors)

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.fail"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>fail ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.fail)
- description and source-code
```javascript
fail = function () { return ''; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.ignore"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>ignore ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.ignore)
- description and source-code
```javascript
ignore = function () { return ''; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.neutral"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>neutral ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.neutral)
- description and source-code
```javascript
neutral = function () { return ''; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.pass"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>pass ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.pass)
- description and source-code
```javascript
pass = function () { return ''; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.specTiming"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>specTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.specTiming)
- description and source-code
```javascript
specTiming = function () { return ''; }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.suiteTiming"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalReporter.prototype.NoColors.</span>suiteTiming ()](#apidoc.element.jasmine-node.TerminalReporter.prototype.NoColors.suiteTiming)
- description and source-code
```javascript
suiteTiming = function () { return ''; }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.TerminalVerboseReporter"></a>[module jasmine-node.TerminalVerboseReporter](#apidoc.module.jasmine-node.TerminalVerboseReporter)

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter.TerminalVerboseReporter"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>TerminalVerboseReporter (config)](#apidoc.element.jasmine-node.TerminalVerboseReporter.TerminalVerboseReporter)
- description and source-code
```javascript
TerminalVerboseReporter = function (config) {
  jasmineNode.TerminalReporter.call(this, config);
  // The extra field in this object
  this.indent_ = 0;
  this.specTimes_ = {};
  this.suiteTimes_ = {};
  this.suiteResults_ = {};
}
```
- example usage
```shell
...
  });
});
});

describe('TerminalVerboseReporter', function() {
beforeEach(function() {
  var config = {}
  this.verboseReporter = new jasmineNode.TerminalVerboseReporter(config);
  this.addFailureToFailuresSpy = spyOn(this.verboseReporter, 'addFailureToFailures_');
  this.spec = {
    id: 23,
    results: function() {
      return {
        failedCount: 1,
        getItems: function() {
...
```



# <a name="apidoc.module.jasmine-node.TerminalVerboseReporter.prototype"></a>[module jasmine-node.TerminalVerboseReporter.prototype](#apidoc.module.jasmine-node.TerminalVerboseReporter.prototype)

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.buildMessagesFromResults_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>buildMessagesFromResults_ (messages, results, depth)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.buildMessagesFromResults_)
- description and source-code
```javascript
buildMessagesFromResults_ = function (messages, results, depth) {
  var element, specResult, specIndentSpaces, msg = '';
  depth = (depth === undefined) ? 0 : depth;

  var results_length = results.length;
  for (var i = 0; i < results_length; i++) {
    element = results[i];

    if (element.type === 'spec') {
      specResult = this.specResults_[element.id.toString()];

      if (specResult.result === 'passed') {
        msg = this.stringWithColor_(this.indentMessage_(element.name, depth), this.color_.pass());
      } else {
        msg = this.stringWithColor_(this.indentMessage_(element.name, depth), this.color_.fail());
      }
      msg += this.stringWithColor_(" - " + specResult.runtime + " ms",
                                   this.color_.specTiming());

      messages.push(msg);
    } else {
      messages.push('');
      msg = this.indentMessage_(element.name, depth)
      if (element.id != null) {
          suiteResult = this.suiteResults_[element.id.toString()];
          if (suiteResult) {
              msg += this.stringWithColor_(" - " + suiteResult.runtime + " ms", this.color_.suiteTiming());
          }
      }
      messages.push(msg);
    }

    this.buildMessagesFromResults_(messages, element.children, depth + 2);
  }
}
```
- example usage
```shell
...

});

it('does not build anything when the results collection is empty', function() {
  var results = [],
      messages = [];

  this.verboseReporter.buildMessagesFromResults_(messages, results);

  expect(messages.length).toEqual(0);
});

it('adds a single suite to the messages', function() {
  var results = [],
      messages = [];
...
```

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.indentMessage_"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>indentMessage_ (message, indentCount)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.indentMessage_)
- description and source-code
```javascript
indentMessage_ = function (message, indentCount) {
  var _indent = '';
  for (var i = 0; i < indentCount; i++) {
    _indent += '  ';
  }
  return (_indent + message);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportRunnerResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportRunnerResults (runner)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportRunnerResults)
- description and source-code
```javascript
reportRunnerResults = function (runner) {
  var messages = new Array();
  this.buildMessagesFromResults_(messages, this.suites_);

  var messages_length = messages.length;
  for (var i = 0; i < messages_length-1; i++) {
    this.printLine_(messages[i]);
  }

  this.print_(messages[messages_length-1]);

  // Call the parent object's method
  jasmineNode.TerminalReporter.prototype.reportRunnerResults.call(this, runner);
}
```
- example usage
```shell
...
        var result = { failedCount: 0 };
        return result;
      },
      specs: function() { return []; }
    };
    this.reporter.startedAt = new Date();

    this.reporter.reportRunnerResults(runner);

    expect(failuresSpy).toHaveBeenCalled();
    expect(this.printLineSpy).toHaveBeenCalled();
    expect(callbackSpy).toHaveBeenCalled();
  });
});
...
```

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSpecResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportSpecResults (spec)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSpecResults)
- description and source-code
```javascript
reportSpecResults = function (spec) {
  var elapsed = new Date().getTime() - this.specTimes_[spec.id];

  if (spec.results().failedCount > 0) {
    this.addFailureToFailures_(spec);
  }

  this.specResults_[spec.id] = {
    messages: spec.results().getItems(),
    result: spec.results().failedCount > 0 ? 'failed' : 'passed',
    runtime: elapsed
  };
}
```
- example usage
```shell
...
      }
      return result;
    }
  }
});

it('prints a \'.\' for pass', function() {
  this.reporter.reportSpecResults(this.spec);
  expect(this.printSpy).toHaveBeenCalledWith('.');
});

it('prints an \'F\' for failure', function() {
  var addFailureToFailuresSpy = spyOn(this.reporter, 'addFailureToFailures_');
  var results = function() {
    var result = {
...
```

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSpecStarting"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportSpecStarting (spec)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSpecStarting)
- description and source-code
```javascript
reportSpecStarting = function (spec) {
    now = new Date().getTime();
    this.specTimes_[spec.id] = now;
    var suite = spec.suite;
    while (suite) {
        if (!this.suiteTimes_[suite.id]) {
            this.suiteTimes_[suite.id] = now;
        }
        suite = suite.parentSuite;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSuiteResults"></a>[function <span class="apidocSignatureSpan">jasmine-node.TerminalVerboseReporter.prototype.</span>reportSuiteResults (suite)](#apidoc.element.jasmine-node.TerminalVerboseReporter.prototype.reportSuiteResults)
- description and source-code
```javascript
reportSuiteResults = function (suite) {
    var startTime = this.suiteTimes_[suite.id];
    if (startTime) {
        var elapsed = new Date().getTime() - startTime;
        this.suiteResults_[suite.id] = {
            runtime: elapsed
        };
    }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.WaitsBlock"></a>[module jasmine-node.WaitsBlock](#apidoc.module.jasmine-node.WaitsBlock)

#### <a name="apidoc.element.jasmine-node.WaitsBlock.WaitsBlock"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsBlock (env, timeout, spec)](#apidoc.element.jasmine-node.WaitsBlock.WaitsBlock)
- description and source-code
```javascript
WaitsBlock = function (env, timeout, spec) {
  this.timeout = timeout;
  jasmine.Block.call(this, env, null, spec);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.WaitsBlock.prototype"></a>[module jasmine-node.WaitsBlock.prototype](#apidoc.module.jasmine-node.WaitsBlock.prototype)

#### <a name="apidoc.element.jasmine-node.WaitsBlock.prototype.execute"></a>[function <span class="apidocSignatureSpan">jasmine-node.WaitsBlock.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.WaitsBlock.prototype.execute)
- description and source-code
```javascript
execute = function (onComplete) {
  if (jasmine.VERBOSE) {
    this.env.reporter.log('>> Jasmine waiting for ' + this.timeout + ' ms...');
  }
  this.env.setTimeout(function () {
    onComplete();
  }, this.timeout);
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```



# <a name="apidoc.module.jasmine-node.WaitsForBlock"></a>[module jasmine-node.WaitsForBlock](#apidoc.module.jasmine-node.WaitsForBlock)

#### <a name="apidoc.element.jasmine-node.WaitsForBlock.WaitsForBlock"></a>[function <span class="apidocSignatureSpan">jasmine-node.</span>WaitsForBlock (env, timeout, latchFunction, message, spec)](#apidoc.element.jasmine-node.WaitsForBlock.WaitsForBlock)
- description and source-code
```javascript
WaitsForBlock = function (env, timeout, latchFunction, message, spec) {
  this.timeout = timeout || env.defaultTimeoutInterval;
  this.latchFunction = latchFunction;
  this.message = message;
  this.totalTimeSpentWaitingForLatch = 0;
  jasmine.Block.call(this, env, null, spec);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.jasmine-node.WaitsForBlock.prototype"></a>[module jasmine-node.WaitsForBlock.prototype](#apidoc.module.jasmine-node.WaitsForBlock.prototype)

#### <a name="apidoc.element.jasmine-node.WaitsForBlock.prototype.execute"></a>[function <span class="apidocSignatureSpan">jasmine-node.WaitsForBlock.prototype.</span>execute (onComplete)](#apidoc.element.jasmine-node.WaitsForBlock.prototype.execute)
- description and source-code
```javascript
execute = function (onComplete) {
  if (jasmine.VERBOSE) {
    this.env.reporter.log('>> Jasmine waiting for ' + (this.message || 'something to happen'));
  }
  var latchFunctionResult;
  try {
    latchFunctionResult = this.latchFunction.apply(this.spec);
  } catch (e) {
    this.spec.fail(e);
    onComplete();
    return;
  }

  if (latchFunctionResult) {
    onComplete();
  } else if (this.totalTimeSpentWaitingForLatch >= this.timeout) {
    var message = 'timed out after ' + this.timeout + ' msec waiting for ' + (this.message || 'something to happen');
    this.spec.fail({
      name: 'timeout',
      message: message
    });

    this.abort = true;
    onComplete();
  } else {
    this.totalTimeSpentWaitingForLatch += jasmine.WaitsForBlock.TIMEOUT_INCREMENT;
    var self = this;
    this.env.setTimeout(function() {
      self.execute(onComplete);
    }, jasmine.WaitsForBlock.TIMEOUT_INCREMENT);
  }
}
```
- example usage
```shell
...
    it("should time out if callback is not called", function() {
env.describe("it", function() {
  env.it("doesn't wait", function(done) {
    expect(1+2).toEqual(3);
  });
});

env.currentRunner().execute();

waitsFor(function() {
  return env.currentRunner().results().totalCount > 0;
}, 6000);

runs(function() {
  expect(env.currentRunner().results().failedCount).toEqual(1);
...
```



# <a name="apidoc.module.jasmine-node.util"></a>[module jasmine-node.util](#apidoc.module.jasmine-node.util)

#### <a name="apidoc.element.jasmine-node.util.argsToArray"></a>[function <span class="apidocSignatureSpan">jasmine-node.util.</span>argsToArray (args)](#apidoc.element.jasmine-node.util.argsToArray)
- description and source-code
```javascript
argsToArray = function (args) {
  var arrayOfArgs = [];
  for (var i = 0; i < args.length; i++) arrayOfArgs.push(args[i]);
  return arrayOfArgs;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.util.extend"></a>[function <span class="apidocSignatureSpan">jasmine-node.util.</span>extend (destination, source)](#apidoc.element.jasmine-node.util.extend)
- description and source-code
```javascript
extend = function (destination, source) {
  for (var property in source) destination[property] = source[property];
  return destination;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.util.formatException"></a>[function <span class="apidocSignatureSpan">jasmine-node.util.</span>formatException (e)](#apidoc.element.jasmine-node.util.formatException)
- description and source-code
```javascript
formatException = function (e) {
  var lineNumber;
  if (e.line) {
    lineNumber = e.line;
  }
  else if (e.lineNumber) {
    lineNumber = e.lineNumber;
  }

  var file;

  if (e.sourceURL) {
    file = e.sourceURL;
  }
  else if (e.fileName) {
    file = e.fileName;
  }

  var message = (e.name && e.message) ? (e.name + ': ' + e.message) : e.toString();

  if (file && lineNumber) {
    message += ' in ' + file + ' (line ' + lineNumber + ')';
  }

  return message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.util.htmlEscape"></a>[function <span class="apidocSignatureSpan">jasmine-node.util.</span>htmlEscape (str)](#apidoc.element.jasmine-node.util.htmlEscape)
- description and source-code
```javascript
htmlEscape = function (str) {
  if (!str) return str;
  return str.replace(/&/g, '&amp;')
    .replace(/</g, '&lt;')
    .replace(/>/g, '&gt;');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.jasmine-node.util.inherit"></a>[function <span class="apidocSignatureSpan">jasmine-node.util.</span>inherit (childClass, parentClass)](#apidoc.element.jasmine-node.util.inherit)
- description and source-code
```javascript
inherit = function (childClass, parentClass) {
<span class="apidocCodeCommentSpan">  /**
   * @private
   */
</span>  var subclass = function() {
  };
  subclass.prototype = parentClass.prototype;
  childClass.prototype = new subclass();
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
