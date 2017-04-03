# api documentation for  [seneca (v3.3.0)](http://senecajs.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-seneca.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-seneca) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-seneca.svg)](https://travis-ci.org/npmdoc/node-npmdoc-seneca)
#### A Microservices Framework for Node.js

[![NPM](https://nodei.co/npm/seneca.png?downloads=true)](https://www.npmjs.com/package/seneca)

[![apidoc](https://npmdoc.github.io/node-npmdoc-seneca/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-seneca_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-seneca/build..beta..travis-ci.org/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-seneca/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-seneca/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Richard Rodger",
        "url": "http://richardrodger.com/"
    },
    "bugs": {
        "url": "https://github.com/senecajs/seneca/issues"
    },
    "contributors": [
        {
            "name": "Adrien Becchis",
            "url": "https://github.com/AdrieanKhisbe"
        },
        {
            "name": "Alexandru Mircea",
            "url": "https://github.com/mirceaalexandru"
        },
        {
            "name": "Adrian Rossouw",
            "url": "http://daemon.co.za"
        },
        {
            "name": "Colin Ihrig",
            "url": "https://github.com/cjihrig"
        },
        {
            "name": "Cristian Ianto",
            "url": "https://github.com/iantocristian"
        },
        {
            "name": "Cristian Kiss",
            "url": "https://github.com/ckiss"
        },
        {
            "name": "David Mark Clements",
            "url": "https://github.com/davidmarkclements"
        },
        {
            "name": "Dean McDonnell",
            "url": "https://github.com/mcdonnelldean"
        },
        {
            "name": "Dominic Tarr",
            "url": "https://github.com/dominictarr"
        },
        {
            "name": "Dustin Deus",
            "url": "https://github.com/StarpTech"
        },
        {
            "name": "Glen Keane",
            "url": "https://github.com/thekemkid"
        },
        {
            "name": "Gege Pincin",
            "url": "https://github.com/Georgette"
        },
        {
            "name": "Jake Pruitt",
            "url": "https://github.com/jakepruitt"
        },
        {
            "name": "Maciej Małecki",
            "url": "http://mmalecki.com"
        },
        {
            "name": "Matteo Collina",
            "url": "https://github.com/mcollina"
        },
        {
            "name": "Marian Radulescu",
            "url": "https://github.com/marianr"
        },
        {
            "name": "Marius Ursache",
            "url": "https://github.com/bamse16"
        },
        {
            "name": "Martin Betak",
            "url": "https://github.com/matobet"
        },
        {
            "name": "Maxence Dalmais",
            "url": "https://github.com/maxired"
        },
        {
            "name": "Mihai Dima",
            "url": "https://github.com/mihaidma"
        },
        {
            "name": "Naomi Feehan",
            "url": "https://github.com/naomifeehan"
        },
        {
            "name": "Paolo Chiodi",
            "url": "https://github.com/paolochiodi"
        },
        {
            "name": "Peter Elger",
            "url": "https://github.com/pelger"
        },
        {
            "name": "Reto Inderbitzin",
            "url": "https://github.com/indr"
        },
        {
            "name": "Reid Rankin",
            "url": "https://github.com/reidrankin"
        },
        {
            "name": "Tane Piper",
            "url": "https://github.com/tanepiper"
        },
        {
            "name": "Wyatt Preul",
            "url": "https://github.com/geek"
        },
        {
            "name": "Vald Houbiev",
            "url": "https://github.com/vladgolubev"
        },
        {
            "name": "Vito Tardia",
            "url": "https://github.com/vtardia"
        }
    ],
    "dependencies": {
        "archy": "1.0.0",
        "eraro": "0.4.1",
        "gate-executor": "1.1.1",
        "gex": "0.2.2",
        "json-stringify-safe": "5.0.1",
        "jsonic": "0.2.2",
        "lodash": "4.15.0",
        "lru-cache": "4.0.1",
        "minimist": "1.2.0",
        "nid": "0.3.2",
        "norma": "0.3.0",
        "ordu": "0.1.1",
        "patrun": "0.5.1",
        "rolling-stats": "0.1.1",
        "semver": "5.3.0",
        "seneca-log-filter": "0.1.0",
        "seneca-transport": "2.1.0",
        "use-plugin": "0.3.2"
    },
    "description": "A Microservices Framework for Node.js",
    "devDependencies": {
        "async": "2.0.x",
        "bench": "0.3.x",
        "body-parser": "1.15.x",
        "code": "3.0.x",
        "connect": "3.4.x",
        "connect-query": "0.2.x",
        "coveralls": "2.11.x",
        "docco": "0.7.x",
        "eslint-config-seneca": "3.x.x",
        "eslint-plugin-hapi": "4.x.x",
        "eslint-plugin-standard": "2.x.x",
        "lab": "11.0.x",
        "seneca-entity": "1.3.x",
        "seneca-error-test": "0.2.x"
    },
    "directories": {},
    "dist": {
        "shasum": "b8c07575fa074284e2407d702ddf35c30fa199bc",
        "tarball": "https://registry.npmjs.org/seneca/-/seneca-3.3.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "LICENSE",
        "README.md",
        "CHANGES.md",
        "lib",
        "seneca.js"
    ],
    "gitHead": "38595f6e4909c1ac71f073a49a772a177a1af690",
    "homepage": "http://senecajs.org",
    "keywords": [
        "micro",
        "service",
        "microservice",
        "micro-service",
        "microservices",
        "micro-services",
        "services",
        "micro services",
        "micro service",
        "framework",
        "minimum",
        "viable",
        "product",
        "toolkit",
        "startup"
    ],
    "license": "MIT",
    "main": "seneca.js",
    "maintainers": [
        {
            "name": "matteo.collina",
            "email": "hello@matteocollina.com"
        },
        {
            "name": "mcdonnelldean",
            "email": "mcdonnelldean@outlook.com"
        },
        {
            "name": "naomifeehanmoran",
            "email": "naomi.feehan.moran@gmail.com"
        },
        {
            "name": "rjrodger",
            "email": "richard.rodger@nearform.com"
        },
        {
            "name": "wyatt",
            "email": "wpreul@gmail.com"
        }
    ],
    "name": "seneca",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/senecajs/seneca.git"
    },
    "scripts": {
        "annotate": "docco seneca.js lib/*.js -o docs/annotated",
        "coverage": "lab -v -P test -L -t 80 -r html > docs/coverage.html",
        "coveralls": "lab -s -P test -r lcov | coveralls",
        "smoke": "node test/stubs/launch.js",
        "test": "lab -v -P test -L -t 80"
    },
    "version": "3.3.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module seneca](#apidoc.module.seneca)
1.  [function <span class="apidocSignatureSpan">seneca.</span>Seneca ()](#apidoc.element.seneca.Seneca)
1.  [function <span class="apidocSignatureSpan">seneca.</span>logging (options)](#apidoc.element.seneca.logging)
1.  [function <span class="apidocSignatureSpan">seneca.</span>print (seneca)](#apidoc.element.seneca.print)
1.  [function <span class="apidocSignatureSpan">seneca.</span>test ()](#apidoc.element.seneca.test)
1.  [function <span class="apidocSignatureSpan">seneca.</span>use ()](#apidoc.element.seneca.use)
1.  object <span class="apidocSignatureSpan">seneca.</span>actions
1.  object <span class="apidocSignatureSpan">seneca.</span>common
1.  object <span class="apidocSignatureSpan">seneca.</span>legacy
1.  object <span class="apidocSignatureSpan">seneca.</span>plugins
1.  object <span class="apidocSignatureSpan">seneca.</span>transport
1.  object <span class="apidocSignatureSpan">seneca.</span>util

#### [module seneca.Seneca](#apidoc.module.seneca.Seneca)
1.  [function <span class="apidocSignatureSpan">seneca.</span>Seneca ()](#apidoc.element.seneca.Seneca.Seneca)
1.  [function <span class="apidocSignatureSpan">seneca.Seneca.</span>super_ ()](#apidoc.element.seneca.Seneca.super_)

#### [module seneca.actions](#apidoc.module.seneca.actions)
1.  [function <span class="apidocSignatureSpan">seneca.actions.</span>find (pattern, flags)](#apidoc.element.seneca.actions.find)
1.  [function <span class="apidocSignatureSpan">seneca.actions.</span>has (pattern)](#apidoc.element.seneca.actions.has)
1.  [function <span class="apidocSignatureSpan">seneca.actions.</span>list (pattern)](#apidoc.element.seneca.actions.list)
1.  object <span class="apidocSignatureSpan">seneca.actions.</span>inward
1.  object <span class="apidocSignatureSpan">seneca.actions.</span>outward

#### [module seneca.common](#apidoc.module.seneca.common)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>argprops (defaults, args, fixed, omits)](#apidoc.element.seneca.common.argprops)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>boolify (v)](#apidoc.element.seneca.common.boolify)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>clean (obj)](#apidoc.element.seneca.common.clean)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>console_error ()](#apidoc.element.seneca.common.console_error)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>copydata (obj)](#apidoc.element.seneca.common.copydata)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>deepextend ()](#apidoc.element.seneca.common.deepextend)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>delegate (scope, func)](#apidoc.element.seneca.common.delegate)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>make_standard_act_log_entry (actmeta, msg, origmsg, ctxt)](#apidoc.element.seneca.common.make_standard_act_log_entry)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>make_standard_err_log_entry (err, ctxt)](#apidoc.element.seneca.common.make_standard_err_log_entry)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>makedie (instance, ctxt)](#apidoc.element.seneca.common.makedie)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>nil ()](#apidoc.element.seneca.common.nil)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>parsePattern (instance, args, normaspec, fixed)](#apidoc.element.seneca.common.parsePattern)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>pattern (patobj)](#apidoc.element.seneca.common.pattern)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>pincanon (inpin)](#apidoc.element.seneca.common.pincanon)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>print (err, out)](#apidoc.element.seneca.common.print)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>recurse (list, work, done)](#apidoc.element.seneca.common.recurse)
1.  [function <span class="apidocSignatureSpan">seneca.common.</span>tagnid ()](#apidoc.element.seneca.common.tagnid)

#### [module seneca.legacy](#apidoc.module.seneca.legacy)
1.  [function <span class="apidocSignatureSpan">seneca.legacy.</span>fail (so)](#apidoc.element.seneca.legacy.fail)

#### [module seneca.logging](#apidoc.module.seneca.logging)
1.  [function <span class="apidocSignatureSpan">seneca.</span>logging (options)](#apidoc.element.seneca.logging.logging)
1.  [function <span class="apidocSignatureSpan">seneca.logging.</span>preload ()](#apidoc.element.seneca.logging.preload)

#### [module seneca.plugins](#apidoc.module.seneca.plugins)
1.  [function <span class="apidocSignatureSpan">seneca.plugins.</span>make_delegate (instance, plugin)](#apidoc.element.seneca.plugins.make_delegate)
1.  [function <span class="apidocSignatureSpan">seneca.plugins.</span>register (so, callpoint)](#apidoc.element.seneca.plugins.register)
1.  object <span class="apidocSignatureSpan">seneca.plugins.</span>api_decorations

#### [module seneca.print](#apidoc.module.seneca.print)
1.  [function <span class="apidocSignatureSpan">seneca.</span>print (seneca)](#apidoc.element.seneca.print.print)
1.  [function <span class="apidocSignatureSpan">seneca.print.</span>print_options (options)](#apidoc.element.seneca.print.print_options)

#### [module seneca.transport](#apidoc.module.seneca.transport)
1.  [function <span class="apidocSignatureSpan">seneca.transport.</span>client (callpoint)](#apidoc.element.seneca.transport.client)
1.  [function <span class="apidocSignatureSpan">seneca.transport.</span>listen (callpoint)](#apidoc.element.seneca.transport.listen)

#### [module seneca.util](#apidoc.module.seneca.util)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>argprops (defaults, args, fixed, omits)](#apidoc.element.seneca.util.argprops)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>clean (obj)](#apidoc.element.seneca.util.clean)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>copydata (obj)](#apidoc.element.seneca.util.copydata)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>deepextend ()](#apidoc.element.seneca.util.deepextend)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>nil ()](#apidoc.element.seneca.util.nil)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>parsepattern (instance, args, normaspec, fixed)](#apidoc.element.seneca.util.parsepattern)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>pattern (patobj)](#apidoc.element.seneca.util.pattern)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>pincanon (inpin)](#apidoc.element.seneca.util.pincanon)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>print (err, out)](#apidoc.element.seneca.util.print)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>recurse (list, work, done)](#apidoc.element.seneca.util.recurse)
1.  [function <span class="apidocSignatureSpan">seneca.util.</span>router ()](#apidoc.element.seneca.util.router)



# <a name="apidoc.module.seneca"></a>[module seneca](#apidoc.module.seneca)

#### <a name="apidoc.element.seneca.Seneca"></a>[function <span class="apidocSignatureSpan">seneca.</span>Seneca ()](#apidoc.element.seneca.Seneca)
- description and source-code
```javascript
function Seneca() {
  Events.EventEmitter.call(this)
  this.setMaxListeners(0)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.logging"></a>[function <span class="apidocSignatureSpan">seneca.</span>logging (options)](#apidoc.element.seneca.logging)
- description and source-code
```javascript
function logging(options) {
  // Everything is in preload as logging plugins are
  // a special case that need to be loaded before any calls to seneca.log.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.print"></a>[function <span class="apidocSignatureSpan">seneca.</span>print (seneca)](#apidoc.element.seneca.print)
- description and source-code
```javascript
print = function (seneca) {
  var argv = Minimist(process.argv.slice(2))
  if (!argv || !argv.seneca) {
    return
  }
  var cmdspec = argv.seneca
  if (cmdspec.print) {
    if (cmdspec.print.tree) {
      // Hack! Complex init means non-deterministic or multiple ready calls,
      // so just delay tree print by some number of seconds to capture full tree.
      var delay_seconds = cmdspec.print.tree.all || cmdspec.print.tree
      if (_.isNumber(delay_seconds)) {
        setTimeout(function () {
          print_tree(seneca, cmdspec)
        }, 1000 * delay_seconds)
      }
      else {
        // Print after first ready
        seneca.ready(function () {
          print_tree(this, cmdspec)
        })
      }
    }

    if (cmdspec.print.options) {
      seneca.options({ debug: { print: { options: true } } })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.test"></a>[function <span class="apidocSignatureSpan">seneca.</span>test ()](#apidoc.element.seneca.test)
- description and source-code
```javascript
function top_test() {
  var argsarr = new Array(arguments.length)
  for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

  var instance = module.exports({test: true, log: 'test'})
  instance.test.apply(instance, argsarr)

  return instance
}
```
- example usage
```shell
...
for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

var instance = module.exports()

return instance.use.apply(instance, argsarr)
}

// Makes require('seneca').test() work.
module.exports.test = function top_test () {
var argsarr = new Array(arguments.length)
for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

var instance = module.exports({test: true, log: 'test'})
instance.test.apply(instance, argsarr)
...
```

#### <a name="apidoc.element.seneca.use"></a>[function <span class="apidocSignatureSpan">seneca.</span>use ()](#apidoc.element.seneca.use)
- description and source-code
```javascript
function top_use() {
  var argsarr = new Array(arguments.length)
  for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

  var instance = module.exports()

  return instance.use.apply(instance, argsarr)
}
```
- example usage
```shell
...


// Services can listen for messages using a variety of
// transports. In process and http are included by default.


Seneca()
.use(approver)
.listen({type: 'http', port: '8260', pin: 'cmd:*'})

Seneca()
.use(rejector)
.listen(8270)
...
```



# <a name="apidoc.module.seneca.Seneca"></a>[module seneca.Seneca](#apidoc.module.seneca.Seneca)

#### <a name="apidoc.element.seneca.Seneca.Seneca"></a>[function <span class="apidocSignatureSpan">seneca.</span>Seneca ()](#apidoc.element.seneca.Seneca.Seneca)
- description and source-code
```javascript
function Seneca() {
  Events.EventEmitter.call(this)
  this.setMaxListeners(0)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.Seneca.super_"></a>[function <span class="apidocSignatureSpan">seneca.Seneca.</span>super_ ()](#apidoc.element.seneca.Seneca.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seneca.actions"></a>[module seneca.actions](#apidoc.module.seneca.actions)

#### <a name="apidoc.element.seneca.actions.find"></a>[function <span class="apidocSignatureSpan">seneca.actions.</span>find (pattern, flags)](#apidoc.element.seneca.actions.find)
- description and source-code
```javascript
find = function (pattern, flags) {
  var seneca = this

  var pat = _.isString(pattern) ? Jsonic(pattern) : pattern
  pat = seneca.util.clean(pat)
  pat = pat || {}

  var actmeta = seneca.private$.actrouter.find(pat)

  if (!actmeta && flags && flags.catchall) {
    actmeta = seneca.private$.actrouter.find({})
  }

  return actmeta
}
```
- example usage
```shell
...
      private$.handle_sub = function handle_sub (args, result) {
        args.meta$ = args.meta$ || {}

        if (!args.meta$.prior || !args.meta$.prior.entry) {
return
        }

        var subfuncs = private$.subrouter.find(args)

        if (subfuncs) {
args.meta$.sub = subfuncs.pattern

_.each(subfuncs, function subfunc (subfunc) {
  try {
    subfunc.call(self, args, result)
...
```

#### <a name="apidoc.element.seneca.actions.has"></a>[function <span class="apidocSignatureSpan">seneca.actions.</span>has (pattern)](#apidoc.element.seneca.actions.has)
- description and source-code
```javascript
has = function (pattern) {
  return !!exports.find.call(this, pattern)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.actions.list"></a>[function <span class="apidocSignatureSpan">seneca.actions.</span>list (pattern)](#apidoc.element.seneca.actions.list)
- description and source-code
```javascript
list = function (pattern) {
  var pat = _.isString(pattern) ? Jsonic(pattern) : pattern
  var found = this.private$.actrouter.list(pat)
  found = _.map(found, 'match')
  return found
}
```
- example usage
```shell
...
for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

var pins = []
var patterns = _.flatten(argsarr)

_.each(patterns, function (pattern) {
  pattern = _.isString(pattern) ? Jsonic(pattern) : pattern
  pins = pins.concat(_.map(private$.actrouter.list(pattern),
    function (desc) {
      return desc.match
    }
  ))
})

return pins
...
```



# <a name="apidoc.module.seneca.common"></a>[module seneca.common](#apidoc.module.seneca.common)

#### <a name="apidoc.element.seneca.common.argprops"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>argprops (defaults, args, fixed, omits)](#apidoc.element.seneca.common.argprops)
- description and source-code
```javascript
function argprops(defaults, args, fixed, omits) {
  omits = _.isArray(omits) ? omits
    : _.isObject(omits) ? _.keys(omits)
    : _.isString(omits) ? omits.split(/\s*,\s*/)
    : '' + omits

  // a little pre omit to avoid entities named in omits
  var usedargs = _.omit(args, omits)

  // don't support $ args
  usedargs = clean(usedargs)

  return _.omit(deepextend(defaults, usedargs, fixed), omits)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.common.boolify"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>boolify (v)](#apidoc.element.seneca.common.boolify)
- description and source-code
```javascript
boolify = function (v) {
  try {
    return !!JSON.parse(v)
  }
  catch (e) {
    return !!v
  }
}
```
- example usage
```shell
...
    sourcemap.argv
  )

  // Legacy log settings.
  out.log = out.log || out.logger || out.logging || {}

  // boolean corrections
  out.legacy.logging = Common.boolify(out.legacy.logging)

  return out
}


function parse_command_line (spec, parsedSpec) {
  var logSpec = _.isArray(spec) ? spec[0] : spec
...
```

#### <a name="apidoc.element.seneca.common.clean"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>clean (obj)](#apidoc.element.seneca.common.clean)
- description and source-code
```javascript
function clean(obj) {
  if (obj === null) return obj

  return _.pickBy(obj, function (val, prop) {
    return !_.includes(prop, '$')
  })
}
```
- example usage
```shell
...
  // See ['seneca.add'](#seneca.add)
  function api_add () {
var self = this
var args = Common.parsePattern(self, arguments, 'action:f? actmeta:o?')

var raw_pattern = args.pattern

var pattern = self.util.clean(raw_pattern)

if (!_.keys(pattern)) {
  throw error('add_empty_pattern', {args: Common.clean(args)})
}


var action = args.action || function default_action (msg, done) {
...
```

#### <a name="apidoc.element.seneca.common.console_error"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>console_error ()](#apidoc.element.seneca.common.console_error)
- description and source-code
```javascript
console_error = function () {
  console.error.apply(null, arguments)
}
```
- example usage
```shell
...
    })
  })
}

var handleClose = function () {
  root.close(function (err) {
    if (err) {
      Common.console_error(err)
    }

    process.exit(err ? (err.exit === null ? 1 : err.exit) : 0)
  })
}

// close seneca instance
...
```

#### <a name="apidoc.element.seneca.common.copydata"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>copydata (obj)](#apidoc.element.seneca.common.copydata)
- description and source-code
```javascript
copydata = function (obj) {
  var copy

  // Handle the 3 simple types, and null or undefined
  if (obj === null || typeof obj !== 'object') return obj

  // Handle Date
  if (_.isDate(obj)) {
    copy = new Date()
    copy.setTime(obj.getTime())
    return copy
  }

  // Handle Array
  if (_.isArray(obj)) {
    copy = []
    for (var i = 0, len = obj.length; i < len; ++i) {
      copy[i] = copydata(obj[i])
    }
    return copy
  }

  // Handle Object
  if (_.isObject(obj)) {
    copy = {}
    for (var attr in obj) {
      if (obj.hasOwnProperty(attr)) copy[attr] = copydata(obj[attr])
    }
    return copy
  }

  throw new Error("Unable to copy obj! Its type isn't supported.")
}
```
- example usage
```shell
...
function action_options_get (args, done) {
  var options = private$.optioner.get()

  var base = args.base || null
  var root = base ? (options[base] || {}) : options
  var val = args.key ? root[args.key] : root

  done(null, Common.copydata(val))
}

_.each(so.internal.close_signals, function (active, signal) {
  if (active) {
    process.once(signal, handleClose)
  }
})
...
```

#### <a name="apidoc.element.seneca.common.deepextend"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>deepextend ()](#apidoc.element.seneca.common.deepextend)
- description and source-code
```javascript
function deepextend() {
  var argsarr = new Array(arguments.length)
  for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

  // Lodash uses the reverse order to apply defaults than the deepextend API.
  argsarr = argsarr.reverse()

  // Add an empty object to the front of the args.  Defaults will be written
  // to this empty object.
  argsarr.unshift({})

  return _.defaultsDeep.apply(_, argsarr)
}
```
- example usage
```shell
...
  callpoint: callpoint
})

root.util = seneca_util


// Configure logging
private$.exports = { options: Common.deepextend({}, so) }
private$.decorations = {}

private$.logger = load_logger(root, so.internal.logger)
root.log = make_log(root, default_log_modifier)


// Error events are fatal, unless you're undead.  These are not the
...
```

#### <a name="apidoc.element.seneca.common.delegate"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>delegate (scope, func)](#apidoc.element.seneca.common.delegate)
- description and source-code
```javascript
delegate = function (scope, func) {
  var args = Array.prototype.slice.call(arguments, 2)
  return function () {
    return func.apply(scope, args.concat(Array.prototype.slice.call(arguments)))
  }
}
```
- example usage
```shell
...
var is_sync = _.isFunction(actdone)
var execute_instance = instance
var timedout = false

actdone = actdone || _.noop

if (msg.gate$) {
  execute_instance = instance.delegate()
  execute_instance.private$.ge =
    execute_instance.private$.ge.gate()
}

var execspec = {
  fn: function act_fn (done) {
    try {
...
```

#### <a name="apidoc.element.seneca.common.make_standard_act_log_entry"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>make_standard_act_log_entry (actmeta, msg, origmsg, ctxt)](#apidoc.element.seneca.common.make_standard_act_log_entry)
- description and source-code
```javascript
make_standard_act_log_entry = function (actmeta, msg, origmsg, ctxt) {
  var transport = origmsg.transport$ || {}
  var callmeta = msg.meta$ || {}
  var prior = callmeta.prior || {}
  actmeta = actmeta || {}

  return _.extend({
    actid: callmeta.id,
    msg: msg,
    entry: prior.entry,
    prior: prior.chain,
    gate: origmsg.gate$,
    caller: origmsg.caller$,
    meta: actmeta,

    // these are transitional as need to be updated
    // to standard transport metadata
    client: actmeta.client,
    listen: !!transport.origin,
    transport: transport
  }, ctxt)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.common.make_standard_err_log_entry"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>make_standard_err_log_entry (err, ctxt)](#apidoc.element.seneca.common.make_standard_err_log_entry)
- description and source-code
```javascript
make_standard_err_log_entry = function (err, ctxt) {
  if (!err) return ctxt

  return _.extend({
    notice: err.message,
    code: err.code,
    err: err
  }, ctxt)
}
```
- example usage
```shell
...
  }
}

var err = internals.error.apply(null, argsarr)
err.callpoint = new Error().stack.match(/^.*\n.*\n\s*(.*)/)[1]
err.seneca = { code: err.code, valmap: err.details }

this.log.error(Common.make_standard_err_log_entry(err))
if (so.errhandler) {
  so.errhandler.call(this, err)
}

if (cb) {
  cb.call(this, err)
}
...
```

#### <a name="apidoc.element.seneca.common.makedie"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>makedie (instance, ctxt)](#apidoc.element.seneca.common.makedie)
- description and source-code
```javascript
makedie = function (instance, ctxt) {
  ctxt = _.extend(ctxt, instance.die ? instance.die.context : {})

  var die = function (err) {
    var die_trace = '\n' + (new Error('die trace').stack)
        .match(/^.*?\n.*\n(.*)/)[1]

    try {
      if (!err) {
        err = new Error('unknown')
      }
      else if (!Util.isError(err)) {
        err = new Error(_.isString(err) ? err : Util.inspect(err))
      }

      err.fatal$ = true

      var so = instance.options()

      // undead is only for testing, do not use in production
      var undead = (so.debug && so.debug.undead) || (err && err.undead)

      var logdesc = {
        kind: ctxt.txt,
        plugin: ctxt.plugin,
        tag: ctxt.tag,
        id: ctxt.id,
        code: err.code,
        notice: err.message,
        err: err,
        callpoint: ctxt.callpoint()
      }

      instance.log.fatal.apply(instance, logdesc)

      var stack = err.stack || ''
      stack = stack.replace(/^.*?\n/, '\n')

      var procdesc = '\n  pid=' + process.pid +
        ', arch=' + process.arch +
        ', platform=' + process.platform +
        ',\n  path=' + process.execPath +
        ',\n  argv=' + Util.inspect(process.argv).replace(/\n/g, '') +
        ',\n  env=' + Util.inspect(process.env).replace(/\n/g, '')

      var fatalmodemsg = instance.fixedargs.fatal$
        ? '\n  ALL ERRORS FATAL: action called with argument fatal$:true ' +
        '(probably a plugin init error, or using a plugin seneca instance)' : ''

      var stderrmsg =
      '\n\n' +
        'Seneca Fatal Error\n' +
        '==================\n\n' +
        'Message: ' + err.message + '\n\n' +
        'Code: ' + err.code + '\n\n' +
        'Details: ' + Util.inspect(err.details, {depth: null}) + '\n\n' +
        'Stack: ' + stack + '\n\n' +
        'Instance: ' + instance.toString() + fatalmodemsg + die_trace + '\n\n' +
        'When: ' + new Date().toISOString() + '\n\n' +
        'Log: ' + Jsonic.stringify(logdesc) + '\n\n' +
        'Node:\n  ' + Util.inspect(process.versions).replace(/\s+/g, ' ') +
        ',\n  ' + Util.inspect(process.features).replace(/\s+/g, ' ') +
        ',\n  ' + Util.inspect(process.moduleLoadList).replace(/\s+/g, ' ') + '\n\n' +
        'Process: ' + procdesc + '\n\n'

      if (so.errhandler) {
        so.errhandler.call(instance, err)
      }

      if (instance.closed) {
        return
      }

      if (!undead) {
        instance.act('role:seneca,info:fatal,closing$:true', {err: err})

        instance.close(
          // terminate process, err (if defined) is from seneca.close
          function (err) {
            if (!undead) {
              process.nextTick(function () {
                if (err) {
                  exports.console_error(err)
                }

                exports.console_error(stderrmsg)
                exports.console_error('\n\nSENECA TERMINATED at ' + (new Date().toISOString()) +
                  '. See above for error report.\n\n')
                process.exit(1)
              })
            }
          }
       )
      }

      // make sure we close down within options.deathdelay seconds
      if (!undead) {
        var killtimer = setTimeout(function () {
          exports.console_error(stderrmsg)
          exports.console_error('\n\nSENECA TERMINATED (on timeout) at ' +
            (new Date().toISOString()) + '.\n\n')
          process.exit(2)
        }, so.deathdelay)
        killtimer.unref()
      }
    }
    catch (panic) {
      var msg =
      '\n\n' +
        'Seneca Panic\n' +
        '============\n\n' +
        panic.stack +
        '\n\nOriginal Error:\n' +
        (arguments[0] && arguments[0].stack ? arguments[0].stack : arguments[0])
      exports.console_error(msg)
    }
  }

  die.context = ctxt

  return die
}
```
- example usage
```shell
...
  so.idlen = 2
  root.idgen = Nid({length: so.idlen})
  root.id = root.idgen() + '/' + so.tag
}

root.fullname = 'Seneca/' + root.id

root.die = Common.makedie(root, {
  type: 'sys',
  plugin: 'seneca',
  tag: root.version,
  id: root.id,
  callpoint: callpoint
})
...
```

#### <a name="apidoc.element.seneca.common.nil"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>nil ()](#apidoc.element.seneca.common.nil)
- description and source-code
```javascript
function nil() {
  _.each(arguments, function (arg) {
    if (_.isFunction(arg)) {
      return arg()
    }
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.common.parsePattern"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>parsePattern (instance, args, normaspec, fixed)](#apidoc.element.seneca.common.parsePattern)
- description and source-code
```javascript
function parse_pattern(instance, args, normaspec, fixed) {
  args =
    Norma('{strargs:s? objargs:o? moreobjargs:o? ' + (normaspec || '') + '}', args)

  try {
    return _.extend(
      args,
      { pattern: _.extend(
          {},

          // Precedence of arguments in add,act is left-to-right
          args.moreobjargs ? args.moreobjargs : {},
          args.objargs ? args.objargs : {},
          args.strargs ? Jsonic(args.strargs) : {},

          fixed || {})
      })
  }
  catch (e) {
    var col = (e.line === 1) ? e.column - 1 : e.column
    throw internals.error('add_string_pattern_syntax', {
      argstr: args,
      syntax: e.message,
      line: e.line,
      col: col
    })
  }
}
```
- example usage
```shell
...

return exportval
  }

  function api_sub () {
var self = this

var subargs = Common.parsePattern(self, arguments, 'action:f actmeta:o?')
var pattern = subargs.pattern
if (pattern.in$ == null &&
  pattern.out$ == null &&
  pattern.error$ == null &&
  pattern.cache$ == null &&
  pattern.default$ == null &&
  pattern.client$ == null) {
...
```

#### <a name="apidoc.element.seneca.common.pattern"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>pattern (patobj)](#apidoc.element.seneca.common.pattern)
- description and source-code
```javascript
function pattern(patobj) {
  if (_.isString(patobj)) {
    return patobj
  }

  patobj = patobj || {}
  var sb = []
  _.each(patobj, function (v, k) {
    if (!~k.indexOf('$') && !_.isFunction(v)) {
      sb.push(k + ':' + v)
    }
  })

  sb.sort()

  return sb.join(',')
}
```
- example usage
```shell
...
      handle_sub(args, result)
    }
  }

  var subs = private$.subrouter.find(pattern)
  if (!subs) {
    private$.subrouter.add(pattern, subs = [])
    subs.pattern = Common.pattern(pattern)
  }
  subs.push(subargs.action)

  return self
}
...
```

#### <a name="apidoc.element.seneca.common.pincanon"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>pincanon (inpin)](#apidoc.element.seneca.common.pincanon)
- description and source-code
```javascript
function pincanon(inpin) {
  if (_.isString(inpin)) {
    return pattern(Jsonic(inpin))
  }
  else if (_.isArray(inpin)) {
    var pin = _.map(inpin, pincanon)
    pin.sort()
    return pin.join(';')
  }
  else {
    return pattern(inpin)
  }
}
```
- example usage
```shell
...
})

var opts = self.options(null).transport || {}

var raw_config = internals.parse_config(argsarr)

// pg: pin group
raw_config.pg = Common.pincanon(raw_config.pin || raw_config.pins)

var config = internals.resolveConfig(raw_config, opts)

config.id = config.id || Common.pattern(raw_config)

var pins = config.pins ||
      (_.isArray(config.pin) ? config.pin : [config.pin || ''])
...
```

#### <a name="apidoc.element.seneca.common.print"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>print (err, out)](#apidoc.element.seneca.common.print)
- description and source-code
```javascript
function print(err, out) {
  if (err) { console.log('ERROR: ' + err.message) }
  else { console.log(Util.inspect(out, {depth: null})) }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.common.recurse"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>recurse (list, work, done)](#apidoc.element.seneca.common.recurse)
- description and source-code
```javascript
function recurse(list, work, done) {
  var ctxt = this

  if (_.isNumber(list)) {
    list = _.range(0, list)
  }
  else {
    list = _.clone(list)
  }

  function next (err, out) {
    if (err) return done(err, out)

    var item = list.shift()

    if (void 0 !== item) {
      work.call(ctxt, item, next)
    }
    else {
      done.call(ctxt, err, out)
    }
  }
  next.call(ctxt)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.common.tagnid"></a>[function <span class="apidocSignatureSpan">seneca.common.</span>tagnid ()](#apidoc.element.seneca.common.tagnid)
- description and source-code
```javascript
tagnid = function () {
    return generate(opts)
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seneca.legacy"></a>[module seneca.legacy](#apidoc.module.seneca.legacy)

#### <a name="apidoc.element.seneca.legacy.fail"></a>[function <span class="apidocSignatureSpan">seneca.legacy.</span>fail (so)](#apidoc.element.seneca.legacy.fail)
- description and source-code
```javascript
function make_legacy_fail(so) {
  return function () {
    var argsarr = new Array(arguments.length)
    for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

    var cb = _.isFunction(argsarr[argsarr.length - 1])
      ? argsarr[argsarr.length - 1] : null

    if (cb) {
      argsarr.pop()
    }

    if (_.isObject(argsarr[0])) {
      var code = argsarr[0].code
      if (_.isString(code)) {
        argsarr.unshift(code)
      }
    }

    var err = internals.error.apply(null, argsarr)
    err.callpoint = new Error().stack.match(/^.*\n.*\n\s*(.*)/)[1]
    err.seneca = { code: err.code, valmap: err.details }

    this.log.error(Common.make_standard_err_log_entry(err))
    if (so.errhandler) {
      so.errhandler.call(this, err)
    }

    if (cb) {
      cb.call(this, err)
    }

    return err
  }
}
```
- example usage
```shell
...
root.fix = api_fix
root.delegate = api_delegate

// Legacy API; Deprecated.
root.findact = root.find

// DEPRECATED
root.fail = Legacy.fail(so)

// Identifier generator.
root.idgen = Nid({length: so.idlen})
so.tag = so.tag || option_defaults.tag
so.tag = so.tag === 'undefined' ? option_defaults.tag : so.tag

// Create a unique identifer for this instance.
...
```



# <a name="apidoc.module.seneca.logging"></a>[module seneca.logging](#apidoc.module.seneca.logging)

#### <a name="apidoc.element.seneca.logging.logging"></a>[function <span class="apidocSignatureSpan">seneca.</span>logging (options)](#apidoc.element.seneca.logging.logging)
- description and source-code
```javascript
function logging(options) {
  // Everything is in preload as logging plugins are
  // a special case that need to be loaded before any calls to seneca.log.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.logging.preload"></a>[function <span class="apidocSignatureSpan">seneca.logging.</span>preload ()](#apidoc.element.seneca.logging.preload)
- description and source-code
```javascript
preload = function () {
  var seneca = this
  var so = seneca.options()
  var logspec = so.log.basic || so.log || {}

  var origspec = logspec

  if (_.isString(logspec)) {
    if ('quiet' === logspec) {
      logspec = {level: 'none'}
    }
    else if ('silent' === logspec) {
      logspec = {level: 'none'}
    }
    else if ('any' === logspec) {
      logspec = {level: 'debug+'}
    }
    else if ('all' === logspec) {
      logspec = {level: 'debug+'}
    }
    else if ('print' === logspec) {
      logspec = {level: 'debug+'}
    }
    else if ('standard' === logspec) {
      logspec = {level: 'info+'}
    }
    else if ('test' === logspec) {
      logspec = {level: 'warn+'}
    }
  }

  var logrouter = LogFilter(logspec)

  var logger = function (seneca, data) {
    if (logrouter(data)) {
      console.log(Stringify(data))
    }
  }

  // Test mode prints more readable logs
  if (so.test) {
    logger = function (seneca, data) {
      if (logrouter(data)) {
        try {
          var logstr
          var time = data.when - seneca.start_time

          if ('test' === origspec || 'print' === origspec) {
            var logb = [
              time + '/' + seneca.id.substring(0, 2),
              data.kind + (data.case ? '/' + data.case : '')]

            if ('act' === data.kind) {
              if (data.msg) {
                logb.push(data.msg.meta$.id.split('/').map(function (s) {
                  return s.substring(0, 2)
                }).join('/'))

                logb.push(data.msg.meta$.pattern)
              }

              logb.push(Util.inspect(seneca.util.clean(data.result || data.msg))
                        .replace(/\s+/g, '')
                        .substring(0, 88))

              if (data.notice) {
                logb.push(data.notice)
              }

              if ('ERR' === data.case) {
                logb.push('\n\n' + data.err.stack + '\n' + data.caller + '\n')
              }
            }
            else if ('add' === data.kind) {
              logb.push(data.pattern)
            }
            else if ('plugin' === data.kind) {
              logb.push(data.plugin_name +
                        (data.plugin_tag ? '/' + data.plugin_tag : ''))
            }
            else if ('options' === data.kind) {
            }
            else if ('notice' === data.kind) {
              logb.push(data.notice)
            }
            else {
              logb.push(Util.inspect(data).replace(/\n/g, ' '))
            }

            logstr = logb.join('\t')
          }
          else {
            logstr = Util.inspect(data, {depth: null})
            logstr =
              time + ':\n\t' +
              logstr.replace(/\n/g, '\n\t') +
              '\n------------------------------------------------\n\n'
          }

          console.log(logstr)
        }
        catch (e) {
          console.log(data)
        }
      }
    }
  }

  return {
    extend: {
      logger: logger
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.seneca.plugins"></a>[module seneca.plugins](#apidoc.module.seneca.plugins)

#### <a name="apidoc.element.seneca.plugins.make_delegate"></a>[function <span class="apidocSignatureSpan">seneca.plugins.</span>make_delegate (instance, plugin)](#apidoc.element.seneca.plugins.make_delegate)
- description and source-code
```javascript
function make_delegate(instance, plugin) {
  // Adjust Seneca API to be plugin specific.
  var delegate = instance.delegate({
    plugin$: {
      name: plugin.name,
      tag: plugin.tag
    },

    // Act calls inside the plugin definition function are not gated.
    // ungate$: true,
    fatal$: true
  })

  delegate.plugin_foo = true

  delegate.private$ = Object.create(instance.private$)
  delegate.private$.ge = delegate.private$.ge.gate()

  delegate.log = instance.make_log(
    delegate,
    function plugin_delegate_log_modifier (data) {
      data.plugin_name = plugin.name
      data.plugin_tag = plugin.tag
    })

  delegate.die = Common.makedie(delegate, { type: 'plugin', plugin: plugin.name })

  var actmetalist = []

  delegate.add = function () {
    var argsarr = new Array(arguments.length)
    for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

    var actmeta = argsarr[argsarr.length - 1] || {}

    if (_.isFunction(actmeta)) {
      actmeta = {}
      argsarr.push(actmeta)
    }

    actmeta.plugin_name = plugin.name || '-'
    actmeta.plugin_tag = plugin.tag || '-'
    actmeta.plugin_fullname = plugin.fullname

    // TODO: is this necessary?
    actmeta.log = delegate.log

    actmetalist.push(actmeta)

    instance.add.apply(delegate, argsarr)

    return delegate
  }

  delegate.__update_plugin__ = function (plugin) {
    delegate.context.name = plugin.name || '-'
    delegate.context.tag = plugin.tag || '-'
    delegate.context.full = plugin.fullname || '-'

    _.each(actmetalist, function (actmeta) {
      actmeta.plugin_name = plugin.name || actmeta.plugin_name || '-'
      actmeta.plugin_tag = plugin.tag || actmeta.plugin_tag || '-'
      actmeta.plugin_fullname =
        plugin.fullname || actmeta.plugin_fullname || '-'
    })
  }

  delegate.context.module = plugin.parent || module
  delegate.context.name = plugin.name || '-'
  delegate.context.tag = plugin.tag || '-'
  delegate.context.full = plugin.fullname
  delegate.context.isplugin = true

  return delegate
}
```
- example usage
```shell
...
var pins = config.pins ||
      (_.isArray(config.pin) ? config.pin : [config.pin || ''])

pins = _.map(pins, function (pin) {
  return _.isString(pin) ? Jsonic(pin) : pin
})

var sd = Plugins.make_delegate(self, { name: 'client$', tag: void 0 })

var sendclient


var transport_client = function transport_client (msg, done) {
  if (msg.local$) {
    this.prior(msg, done)
...
```

#### <a name="apidoc.element.seneca.plugins.register"></a>[function <span class="apidocSignatureSpan">seneca.plugins.</span>register (so, callpoint)](#apidoc.element.seneca.plugins.register)
- description and source-code
```javascript
register = function (so, callpoint) {
  var seq = 0

  return function api_register (plugin) {
    var seneca = this

    var preload = plugin.init.preload
    preload = _.isFunction(preload) ? preload : _.noop
    var meta = preload.call(seneca, plugin) || {}

    var fullname = plugin.name + (plugin.tag ? '/' + plugin.tag : '')
    plugin.fullname = fullname

    var delegate = make_delegate(seneca, plugin)

    seq++

    var plugin_define_pattern = {
      role: 'seneca',
      plugin: 'define',
      name: plugin.name,
      seq: seq
    }

    if (plugin.tag !== null) {
      plugin_define_pattern.tag = plugin.tag
    }

    // seneca
    delegate
      .add(plugin_define_pattern, plugin_definition)
      .act({
        role: 'seneca',
        plugin: 'define',
        name: plugin.name,
        tag: plugin.tag,
        seq: seq,
        default$: {},
        // gate$: true,
        fatal$: true,
        local$: true
      })

    // needed for seneca.export to operate for plugins like seneca-web
    var preloadName = meta.name || plugin.name
    var preloadRef = preloadName + (plugin.tag ? '/' + plugin.tag : '')
    seneca.private$.exports[preloadName] = meta.export || plugin

    resolve_plugin_exports(seneca, preloadRef, meta)

    function plugin_definition (msg, plugin_done) {
      var plugin_seneca = this
      var plugin_options = resolve_options(fullname, plugin, seneca)

      // Update plugin options data in Seneca options.
      var seneca_options = {plugin: {}}
      seneca_options.plugin[fullname] = plugin_options
      seneca.options(seneca_options)

      plugin_seneca.log.debug({
        kind: 'plugin',
        case: 'init',
        name: plugin.name,
        tag: plugin.tag,
        options: plugin_options,
        callpoint: callpoint
      })

      try {
        meta = define_plugin(plugin_seneca, plugin, plugin_options)
      }
      catch (e) {
        // TODO: needs wrapping
        return plugin_done(e)
      }

      // legacy api for service function
      if (_.isFunction(meta)) {
        meta = {service: meta}
      }

      plugin.name = meta.name || plugin.name
      plugin.tag =
        meta.tag ||
        plugin.tag ||
        (plugin.options && plugin.options.tag$)

      plugin.fullname = plugin.name + (plugin.tag ? '/' + plugin.tag : '')

      plugin.service = meta.service || plugin.service

      plugin_seneca.__update_plugin__(plugin)

      var pluginref = plugin.name + (plugin.tag ? '/' + plugin.tag : '')
      seneca.private$.plugins[pluginref] = plugin

      seneca.private$.plugin_order.byname.push(plugin.name)
      seneca.private$.plugin_order.byname = _.uniq(seneca.private$.plugin_order.byname)
      seneca.private$.plugin_order.byref.push(pluginref)


      var exports = resolve_plugin_exports(plugin_seneca, pluginref, meta)

      plugin_seneca.log.debug({
        kind: 'plugin',
        case: 'install',
        name: plugin.name,
        tag: plugin.tag,
        exports: exports
      })

      plugin_seneca.act(
        {
          init: plugin.name,
          tag: plugin.tag,
          default$: {},
          fatal$: true,
          local$: true
        },
        function (err, out) {
          if (err) {
            var plugin_err_code = 'plugin_init'

            plugin.plugin_error = err.message

            if (err.code === 'action-timeout') {
              plugin_err_code = 'plugin_init_timeout'
              plugin.timeout = so.timeout
            }

            return plugin_seneca.die(internals.error(err, plugin_err_code, plugin))
          }

          var fullname = plugin.name + (plugin.tag ? '$' + plugin.tag : '')

          if (so.debug.print && so.debug.print.options) {
            console.log('\nSeneca Options (' + seneca.id + '): plugin: ' +
                        fullname + '\n' +
                        '===\n')
            console.log(Util.inspect(plugin_options, { depth: null }))
            console.log('')
          }

          plugin_seneca.log.debug({
            kind: 'plugin',
            case: 'ready',
            name: plugin.name,
            t ...
```
- example usage
```shell
...
root.outward = api_outward // Add a modifier function for responses outward
root.test = api_test // Set test mode.

// Method aliases.
root.hasact = root.has

// Non-API methods.
root.register = Plugins.register(so, callpoint)
root.depends = api_depends
root.act_if = api_act_if
root.wrap = api_wrap
root.seneca = api_seneca
root.fix = api_fix
root.delegate = api_delegate
...
```



# <a name="apidoc.module.seneca.print"></a>[module seneca.print](#apidoc.module.seneca.print)

#### <a name="apidoc.element.seneca.print.print"></a>[function <span class="apidocSignatureSpan">seneca.</span>print (seneca)](#apidoc.element.seneca.print.print)
- description and source-code
```javascript
print = function (seneca) {
  var argv = Minimist(process.argv.slice(2))
  if (!argv || !argv.seneca) {
    return
  }
  var cmdspec = argv.seneca
  if (cmdspec.print) {
    if (cmdspec.print.tree) {
      // Hack! Complex init means non-deterministic or multiple ready calls,
      // so just delay tree print by some number of seconds to capture full tree.
      var delay_seconds = cmdspec.print.tree.all || cmdspec.print.tree
      if (_.isNumber(delay_seconds)) {
        setTimeout(function () {
          print_tree(seneca, cmdspec)
        }, 1000 * delay_seconds)
      }
      else {
        // Print after first ready
        seneca.ready(function () {
          print_tree(this, cmdspec)
        })
      }
    }

    if (cmdspec.print.options) {
      seneca.options({ debug: { print: { options: true } } })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.print.print_options"></a>[function <span class="apidocSignatureSpan">seneca.print.</span>print_options (options)](#apidoc.element.seneca.print.print_options)
- description and source-code
```javascript
function print_options(options) {
  if (options.debug.print.options) {
    console.log('\nSeneca Options (' + root.id + '): before plugins\n' + '===\n')
    console.log(Util.inspect(options, { depth: null }))
    console.log('')
  }
}
```
- example usage
```shell
...
var seneca = make_seneca(initial_options)
var options = seneca.options()

// The 'internal' key of options is reserved for objects and functions
// that provide functionality, and are thus not really printable
seneca.log.debug({kind: 'notice', options: _.omit(options, ['internal'])})

Print.print_options(options)

// TODO: these are core API and should not be decorations
seneca.decorate('hasplugin', Plugins.api_decorations.hasplugin)
seneca.decorate('findplugin', Plugins.api_decorations.findplugin)
seneca.decorate('plugins', Plugins.api_decorations.plugins)

// Register default plugins, unless turned off by options.
...
```



# <a name="apidoc.module.seneca.transport"></a>[module seneca.transport](#apidoc.module.seneca.transport)

#### <a name="apidoc.element.seneca.transport.client"></a>[function <span class="apidocSignatureSpan">seneca.transport.</span>client (callpoint)](#apidoc.element.seneca.transport.client)
- description and source-code
```javascript
client = function (callpoint) {
  return function api_client () {
    var argsarr = new Array(arguments.length)
    for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

    var self = this

    self.log.debug({
      kind: 'client',
      options: argsarr,
      callpoint: callpoint()
    })

    var opts = self.options(null).transport || {}

    var raw_config = internals.parse_config(argsarr)

    // pg: pin group
    raw_config.pg = Common.pincanon(raw_config.pin || raw_config.pins)

    var config = internals.resolveConfig(raw_config, opts)

    config.id = config.id || Common.pattern(raw_config)

    var pins = config.pins ||
          (_.isArray(config.pin) ? config.pin : [config.pin || ''])

    pins = _.map(pins, function (pin) {
      return _.isString(pin) ? Jsonic(pin) : pin
    })

    var sd = Plugins.make_delegate(self, { name: 'client$', tag: void 0 })

    var sendclient


    var transport_client = function transport_client (msg, done) {
      if (msg.local$) {
        this.prior(msg, done)
      }
      else {
        sendclient.send.call(this, msg, done)
      }
    }

    transport_client.id = config.id

    if (config.makehandle) {
      transport_client.handle = config.makehandle(config)
    }

    _.each(pins, function (pin) {
      pin = _.clone(pin)
      pin.client$ = true
      pin.internal$ = {catchall: true}

      sd.add(pin, transport_client)
    })


    // Create client.
    sd.act(
      'role:transport,cmd:client',
      { config: config, gate$: true },
      function (err, liveclient) {
        if (err) {
          return sd.die(internals.error(err, 'transport_client', config))
        }

        if (liveclient === null) {
          return sd.die(internals.error('transport_client_null',
                                        Common.clean(config)))
        }

        sendclient = liveclient
      })

    return self
  }
}
```
- example usage
```shell
...
}

Seneca()
.use(local)
.act('cmd:run', handler)

Seneca()
.client({port: 8270, pin: 'cmd:run'})
.client({port: 8260, pin: 'cmd:run'})
.use(local)
.act('cmd:run', handler)

Seneca()
.client({port: 8260, pin: 'cmd:run'})
.client({port: 8270, pin: 'cmd:run'})
...
```

#### <a name="apidoc.element.seneca.transport.listen"></a>[function <span class="apidocSignatureSpan">seneca.transport.</span>listen (callpoint)](#apidoc.element.seneca.transport.listen)
- description and source-code
```javascript
listen = function (callpoint) {
  return function api_listen () {
    var argsarr = new Array(arguments.length)
    for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

    var self = this
    var lastArg = _.last(argsarr)
    if (typeof lastArg === 'function') {
      argsarr.pop()
    }

    self.log.debug({
      kind: 'listen',
      options: argsarr,
      callpoint: callpoint()
    })

    var opts = self.options().transport || {}
    var config = internals.resolveConfig(internals.parse_config(argsarr), opts)

    self.act(
      'role:transport,cmd:listen',
      { config: config, gate$: true },
      function (err, result) {
        if (err) {
          return self.die(internals.error(err, 'transport_listen', config))
        }

        if (typeof lastArg === 'function') {
          lastArg(null, result)
          lastArg = _.noop
        }
      })

    return self
  }
}
```
- example usage
```shell
...

// Services can listen for messages using a variety of
// transports. In process and http are included by default.


Seneca()
  .use(approver)
  .listen({type: 'http', port: '8260', pin: 'cmd:*'})

Seneca()
  .use(rejector)
  .listen(8270)


// Load order is important, messages can be routed
...
```



# <a name="apidoc.module.seneca.util"></a>[module seneca.util](#apidoc.module.seneca.util)

#### <a name="apidoc.element.seneca.util.argprops"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>argprops (defaults, args, fixed, omits)](#apidoc.element.seneca.util.argprops)
- description and source-code
```javascript
function argprops(defaults, args, fixed, omits) {
  omits = _.isArray(omits) ? omits
    : _.isObject(omits) ? _.keys(omits)
    : _.isString(omits) ? omits.split(/\s*,\s*/)
    : '' + omits

  // a little pre omit to avoid entities named in omits
  var usedargs = _.omit(args, omits)

  // don't support $ args
  usedargs = clean(usedargs)

  return _.omit(deepextend(defaults, usedargs, fixed), omits)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.util.clean"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>clean (obj)](#apidoc.element.seneca.util.clean)
- description and source-code
```javascript
function clean(obj) {
  if (obj === null) return obj

  return _.pickBy(obj, function (val, prop) {
    return !_.includes(prop, '$')
  })
}
```
- example usage
```shell
...
  // See ['seneca.add'](#seneca.add)
  function api_add () {
var self = this
var args = Common.parsePattern(self, arguments, 'action:f? actmeta:o?')

var raw_pattern = args.pattern

var pattern = self.util.clean(raw_pattern)

if (!_.keys(pattern)) {
  throw error('add_empty_pattern', {args: Common.clean(args)})
}


var action = args.action || function default_action (msg, done) {
...
```

#### <a name="apidoc.element.seneca.util.copydata"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>copydata (obj)](#apidoc.element.seneca.util.copydata)
- description and source-code
```javascript
copydata = function (obj) {
  var copy

  // Handle the 3 simple types, and null or undefined
  if (obj === null || typeof obj !== 'object') return obj

  // Handle Date
  if (_.isDate(obj)) {
    copy = new Date()
    copy.setTime(obj.getTime())
    return copy
  }

  // Handle Array
  if (_.isArray(obj)) {
    copy = []
    for (var i = 0, len = obj.length; i < len; ++i) {
      copy[i] = copydata(obj[i])
    }
    return copy
  }

  // Handle Object
  if (_.isObject(obj)) {
    copy = {}
    for (var attr in obj) {
      if (obj.hasOwnProperty(attr)) copy[attr] = copydata(obj[attr])
    }
    return copy
  }

  throw new Error("Unable to copy obj! Its type isn't supported.")
}
```
- example usage
```shell
...
function action_options_get (args, done) {
  var options = private$.optioner.get()

  var base = args.base || null
  var root = base ? (options[base] || {}) : options
  var val = args.key ? root[args.key] : root

  done(null, Common.copydata(val))
}

_.each(so.internal.close_signals, function (active, signal) {
  if (active) {
    process.once(signal, handleClose)
  }
})
...
```

#### <a name="apidoc.element.seneca.util.deepextend"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>deepextend ()](#apidoc.element.seneca.util.deepextend)
- description and source-code
```javascript
function deepextend() {
  var argsarr = new Array(arguments.length)
  for (var l = 0; l < argsarr.length; ++l) { argsarr[l] = arguments[l] }

  // Lodash uses the reverse order to apply defaults than the deepextend API.
  argsarr = argsarr.reverse()

  // Add an empty object to the front of the args.  Defaults will be written
  // to this empty object.
  argsarr.unshift({})

  return _.defaultsDeep.apply(_, argsarr)
}
```
- example usage
```shell
...
  callpoint: callpoint
})

root.util = seneca_util


// Configure logging
private$.exports = { options: Common.deepextend({}, so) }
private$.decorations = {}

private$.logger = load_logger(root, so.internal.logger)
root.log = make_log(root, default_log_modifier)


// Error events are fatal, unless you're undead.  These are not the
...
```

#### <a name="apidoc.element.seneca.util.nil"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>nil ()](#apidoc.element.seneca.util.nil)
- description and source-code
```javascript
function nil() {
  _.each(arguments, function (arg) {
    if (_.isFunction(arg)) {
      return arg()
    }
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.util.parsepattern"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>parsepattern (instance, args, normaspec, fixed)](#apidoc.element.seneca.util.parsepattern)
- description and source-code
```javascript
function parse_pattern(instance, args, normaspec, fixed) {
  args =
    Norma('{strargs:s? objargs:o? moreobjargs:o? ' + (normaspec || '') + '}', args)

  try {
    return _.extend(
      args,
      { pattern: _.extend(
          {},

          // Precedence of arguments in add,act is left-to-right
          args.moreobjargs ? args.moreobjargs : {},
          args.objargs ? args.objargs : {},
          args.strargs ? Jsonic(args.strargs) : {},

          fixed || {})
      })
  }
  catch (e) {
    var col = (e.line === 1) ? e.column - 1 : e.column
    throw internals.error('add_string_pattern_syntax', {
      argstr: args,
      syntax: e.message,
      line: e.line,
      col: col
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.util.pattern"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>pattern (patobj)](#apidoc.element.seneca.util.pattern)
- description and source-code
```javascript
function pattern(patobj) {
  if (_.isString(patobj)) {
    return patobj
  }

  patobj = patobj || {}
  var sb = []
  _.each(patobj, function (v, k) {
    if (!~k.indexOf('$') && !_.isFunction(v)) {
      sb.push(k + ':' + v)
    }
  })

  sb.sort()

  return sb.join(',')
}
```
- example usage
```shell
...
      handle_sub(args, result)
    }
  }

  var subs = private$.subrouter.find(pattern)
  if (!subs) {
    private$.subrouter.add(pattern, subs = [])
    subs.pattern = Common.pattern(pattern)
  }
  subs.push(subargs.action)

  return self
}
...
```

#### <a name="apidoc.element.seneca.util.pincanon"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>pincanon (inpin)](#apidoc.element.seneca.util.pincanon)
- description and source-code
```javascript
function pincanon(inpin) {
  if (_.isString(inpin)) {
    return pattern(Jsonic(inpin))
  }
  else if (_.isArray(inpin)) {
    var pin = _.map(inpin, pincanon)
    pin.sort()
    return pin.join(';')
  }
  else {
    return pattern(inpin)
  }
}
```
- example usage
```shell
...
})

var opts = self.options(null).transport || {}

var raw_config = internals.parse_config(argsarr)

// pg: pin group
raw_config.pg = Common.pincanon(raw_config.pin || raw_config.pins)

var config = internals.resolveConfig(raw_config, opts)

config.id = config.id || Common.pattern(raw_config)

var pins = config.pins ||
      (_.isArray(config.pin) ? config.pin : [config.pin || ''])
...
```

#### <a name="apidoc.element.seneca.util.print"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>print (err, out)](#apidoc.element.seneca.util.print)
- description and source-code
```javascript
function print(err, out) {
  if (err) { console.log('ERROR: ' + err.message) }
  else { console.log(Util.inspect(out, {depth: null})) }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.util.recurse"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>recurse (list, work, done)](#apidoc.element.seneca.util.recurse)
- description and source-code
```javascript
function recurse(list, work, done) {
  var ctxt = this

  if (_.isNumber(list)) {
    list = _.range(0, list)
  }
  else {
    list = _.clone(list)
  }

  function next (err, out) {
    if (err) return done(err, out)

    var item = list.shift()

    if (void 0 !== item) {
      work.call(ctxt, item, next)
    }
    else {
      done.call(ctxt, err, out)
    }
  }
  next.call(ctxt)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.seneca.util.router"></a>[function <span class="apidocSignatureSpan">seneca.util.</span>router ()](#apidoc.element.seneca.util.router)
- description and source-code
```javascript
function router() { return Patrun() }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
