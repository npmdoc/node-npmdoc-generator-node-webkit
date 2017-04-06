# api documentation for  [generator-node-webkit (v1.0.4)](https://github.com/Dica-Developer/generator-node-webkit)  [![npm package](https://img.shields.io/npm/v/npmdoc-generator-node-webkit.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-generator-node-webkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-generator-node-webkit.svg)](https://travis-ci.org/npmdoc/node-npmdoc-generator-node-webkit)
#### A generator for node-webkit

[![NPM](https://nodei.co/npm/generator-node-webkit.png?downloads=true)](https://www.npmjs.com/package/generator-node-webkit)

[![apidoc](https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-generator-node-webkit_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-generator-node-webkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Dica-Developer",
        "url": "https://github.com/Dica-Developer"
    },
    "bugs": {
        "url": "https://github.com/Dica-Developer/generator-node-webkit/issues"
    },
    "dependencies": {
        "decompress-zip": "^0.1.0",
        "follow-redirects": "^0.0.3",
        "fs-extra": "^0.16.3",
        "github": "^0.2.3",
        "html-wiring": "^1.1.0",
        "lodash": "^3.8.0",
        "request": "^2.53.0",
        "tar-fs": "^1.4.2",
        "temp": ">=0.8.1",
        "when": "^3.7.2",
        "yeoman-generator": "^0.18.7"
    },
    "description": "A generator for node-webkit",
    "devDependencies": {
        "chai": "^1.10.0",
        "coveralls": ">=2.11.2",
        "mocha": "^2.1.0",
        "mocha-lcov-reporter": ">=0.0.1",
        "temp": ">=0.8.1"
    },
    "directories": {},
    "dist": {
        "shasum": "97b5d8620fba87379a87c8789e92b8676000652e",
        "tarball": "https://registry.npmjs.org/generator-node-webkit/-/generator-node-webkit-1.0.4.tgz"
    },
    "engines": {
        "node": ">=0.10.0",
        "npm": ">=1.2.10"
    },
    "gitHead": "be9b3c9b3fb16c9ae516f88f1a6da67ee13bd6fc",
    "homepage": "https://github.com/Dica-Developer/generator-node-webkit",
    "keywords": [
        "yeoman-generator",
        "node-webkit"
    ],
    "license": "MIT",
    "main": "app/index.js",
    "maintainers": [
        {
            "name": "dica-developer",
            "email": "dica-developer@mascha.me"
        }
    ],
    "name": "generator-node-webkit",
    "optionalDependencies": {},
    "peerDependencies": {
        "yo": ">=1.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/Dica-Developer/generator-node-webkit.git"
    },
    "scripts": {
        "test": "mocha test -R mocha-lcov-reporter | coveralls"
    },
    "version": "1.0.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module generator-node-webkit](#apidoc.module.generator-node-webkit)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.</span>super_ (args, options)](#apidoc.element.generator-node-webkit.super_)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.</span>super_.prototype._ (value)](#apidoc.element.generator-node-webkit.super_.prototype._)
1.  object <span class="apidocSignatureSpan">generator-node-webkit.</span>super_.prototype
1.  object <span class="apidocSignatureSpan">generator-node-webkit.</span>super_.prototype._.prototype

#### [module generator-node-webkit.super_](#apidoc.module.generator-node-webkit.super_)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.</span>super_ ()](#apidoc.element.generator-node-webkit.super_.super_)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.</span>extend (protoProps, staticProps)](#apidoc.element.generator-node-webkit.super_.extend)

#### [module generator-node-webkit.super_.prototype](#apidoc.module.generator-node-webkit.super_.prototype)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_ (value)](#apidoc.element.generator-node-webkit.super_.prototype._)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_directory (source, destination, process, bulk)](#apidoc.element.generator-node-webkit.super_.prototype._directory)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_getGlobalStorage ()](#apidoc.element.generator-node-webkit.super_.prototype._getGlobalStorage)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_getStorage ()](#apidoc.element.generator-node-webkit.super_.prototype._getStorage)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_prepCopy (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype._prepCopy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_writeFiles (done)](#apidoc.element.generator-node-webkit.super_.prototype._writeFiles)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>append (html, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.append)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendFiles (htmlOrOptions, fileType, optimizedPath, sourceFileList, attrs, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.appendFiles)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendScripts (html, optimizedPath, sourceFileList, attrs, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.appendScripts)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendScriptsDir (html, optimizedPath, sourceScriptDir, attrs)](#apidoc.element.generator-node-webkit.super_.prototype.appendScriptsDir)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendStyles (html, optimizedPath, sourceFileList, attrs, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.appendStyles)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendStylesDir (html, optimizedPath, sourceStyleDir, attrs)](#apidoc.element.generator-node-webkit.super_.prototype.appendStylesDir)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendToFile (path, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.appendToFile)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>argument (name, config)](#apidoc.element.generator-node-webkit.super_.prototype.argument)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>argumentsHelp ()](#apidoc.element.generator-node-webkit.super_.prototype.argumentsHelp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>attributes (attrs)](#apidoc.element.generator-node-webkit.super_.prototype.attributes)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>bowerInstall (cmpnt, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.bowerInstall)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>bulkCopy (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.bulkCopy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>bulkDirectory (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.bulkDirectory)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>cacheRoot ()](#apidoc.element.generator-node-webkit.super_.prototype.cacheRoot)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>checkRequiredArgs ()](#apidoc.element.generator-node-webkit.super_.prototype.checkRequiredArgs)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>composeWith (namespace, options, settings)](#apidoc.element.generator-node-webkit.super_.prototype.composeWith)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>copy (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.copy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>defaultFor (name)](#apidoc.element.generator-node-webkit.super_.prototype.defaultFor)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>desc (description)](#apidoc.element.generator-node-webkit.super_.prototype.desc)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>destinationPath ()](#apidoc.element.generator-node-webkit.super_.prototype.destinationPath)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>destinationRoot (rootPath)](#apidoc.element.generator-node-webkit.super_.prototype.destinationRoot)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>determineAppname ()](#apidoc.element.generator-node-webkit.super_.prototype.determineAppname)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>directory (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.directory)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>domUpdate (html, tagName, content, mode)](#apidoc.element.generator-node-webkit.super_.prototype.domUpdate)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>engine (body, data, options)](#apidoc.element.generator-node-webkit.super_.prototype.engine)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>expand (pattern, options)](#apidoc.element.generator-node-webkit.super_.prototype.expand)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>expandFiles (pattern, options)](#apidoc.element.generator-node-webkit.super_.prototype.expandFiles)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>extract (archive, destination, opts, cb)](#apidoc.element.generator-node-webkit.super_.prototype.extract)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>fetch (url, destination, cb)](#apidoc.element.generator-node-webkit.super_.prototype.fetch)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>generateBlock (blockType, optimizedPath, filesBlock, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.generateBlock)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>getCollisionFilter ()](#apidoc.element.generator-node-webkit.super_.prototype.getCollisionFilter)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>help ()](#apidoc.element.generator-node-webkit.super_.prototype.help)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>hookFor (name, config)](#apidoc.element.generator-node-webkit.super_.prototype.hookFor)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>installDependencies (options)](#apidoc.element.generator-node-webkit.super_.prototype.installDependencies)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>invoke (namespace, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.invoke)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>isPathAbsolute ()](#apidoc.element.generator-node-webkit.super_.prototype.isPathAbsolute)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>mkdir ()](#apidoc.element.generator-node-webkit.super_.prototype.mkdir)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>npmInstall (pkgs, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.npmInstall)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>option (name, config)](#apidoc.element.generator-node-webkit.super_.prototype.option)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>optionsHelp ()](#apidoc.element.generator-node-webkit.super_.prototype.optionsHelp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>parseOptions ()](#apidoc.element.generator-node-webkit.super_.prototype.parseOptions)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>prepend (html, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.prepend)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>prependToFile (path, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.prependToFile)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>prompt (questions, callback)](#apidoc.element.generator-node-webkit.super_.prototype.prompt)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>read (filepath, encoding)](#apidoc.element.generator-node-webkit.super_.prototype.read)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>readFileAsString (filePath)](#apidoc.element.generator-node-webkit.super_.prototype.readFileAsString)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>registerTransformStream (stream)](#apidoc.element.generator-node-webkit.super_.prototype.registerTransformStream)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>remote ()](#apidoc.element.generator-node-webkit.super_.prototype.remote)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>remoteDir (cache, cb)](#apidoc.element.generator-node-webkit.super_.prototype.remoteDir)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>removeScript (html, scriptPath)](#apidoc.element.generator-node-webkit.super_.prototype.removeScript)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>removeStyle (html, path)](#apidoc.element.generator-node-webkit.super_.prototype.removeStyle)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>rootGeneratorName ()](#apidoc.element.generator-node-webkit.super_.prototype.rootGeneratorName)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>rootGeneratorVersion ()](#apidoc.element.generator-node-webkit.super_.prototype.rootGeneratorVersion)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>run (cb)](#apidoc.element.generator-node-webkit.super_.prototype.run)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>runHooks (cb)](#apidoc.element.generator-node-webkit.super_.prototype.runHooks)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>runInstall (installer, paths, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.runInstall)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>sourceRoot (rootPath)](#apidoc.element.generator-node-webkit.super_.prototype.sourceRoot)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>spawnCommand (command, args, opt)](#apidoc.element.generator-node-webkit.super_.prototype.spawnCommand)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>tarball (archive, destination, opts, cb)](#apidoc.element.generator-node-webkit.super_.prototype.tarball)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>template (source, destination, data, options)](#apidoc.element.generator-node-webkit.super_.prototype.template)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>templatePath ()](#apidoc.element.generator-node-webkit.super_.prototype.templatePath)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>usage ()](#apidoc.element.generator-node-webkit.super_.prototype.usage)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>write (filepath, content, writeFile)](#apidoc.element.generator-node-webkit.super_.prototype.write)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>writeFileFromString (html, filePath)](#apidoc.element.generator-node-webkit.super_.prototype.writeFileFromString)
1.  object <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>user
1.  string <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>welcome

#### [module generator-node-webkit.super_.prototype._](#apidoc.module.generator-node-webkit.super_.prototype._)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_ (value)](#apidoc.element.generator-node-webkit.super_.prototype._._)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>after (n, func)](#apidoc.element.generator-node-webkit.super_.prototype._.after)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>all (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.all)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>any (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.any)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>assign (object, source, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.assign)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>at (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.at)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>bind (func, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.bind)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>bindAll (object)](#apidoc.element.generator-node-webkit.super_.prototype._.bindAll)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>bindKey (object, key)](#apidoc.element.generator-node-webkit.super_.prototype._.bindKey)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>camelize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.camelize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>capitalize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.capitalize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>center (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.center)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>chain (value)](#apidoc.element.generator-node-webkit.super_.prototype._.chain)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>chars (str)](#apidoc.element.generator-node-webkit.super_.prototype._.chars)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>chop (str, step)](#apidoc.element.generator-node-webkit.super_.prototype._.chop)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>classify (str)](#apidoc.element.generator-node-webkit.super_.prototype._.classify)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>clean (str)](#apidoc.element.generator-node-webkit.super_.prototype._.clean)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>clone (value, isDeep, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.clone)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>cloneDeep (value, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.cloneDeep)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>collect (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.collect)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>compact (array)](#apidoc.element.generator-node-webkit.super_.prototype._.compact)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>compose ()](#apidoc.element.generator-node-webkit.super_.prototype._.compose)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>constant (value)](#apidoc.element.generator-node-webkit.super_.prototype._.constant)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>contains (collection, target, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.contains)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>count (str, substr)](#apidoc.element.generator-node-webkit.super_.prototype._.count)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>countBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.countBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>create (prototype, properties)](#apidoc.element.generator-node-webkit.super_.prototype._.create)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>createCallback (func, thisArg, argCount)](#apidoc.element.generator-node-webkit.super_.prototype._.createCallback)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>curry (func, arity)](#apidoc.element.generator-node-webkit.super_.prototype._.curry)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>dasherize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.dasherize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>debounce (func, wait, options)](#apidoc.element.generator-node-webkit.super_.prototype._.debounce)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>defaults (object, source, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.defaults)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>defer (func)](#apidoc.element.generator-node-webkit.super_.prototype._.defer)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>delay (func, wait)](#apidoc.element.generator-node-webkit.super_.prototype._.delay)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>detect (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.detect)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>difference (array)](#apidoc.element.generator-node-webkit.super_.prototype._.difference)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>drop (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.drop)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>each (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.each)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>eachRight (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.eachRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>endsWith (str, ends)](#apidoc.element.generator-node-webkit.super_.prototype._.endsWith)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>escape (string)](#apidoc.element.generator-node-webkit.super_.prototype._.escape)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>escapeHTML (str)](#apidoc.element.generator-node-webkit.super_.prototype._.escapeHTML)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>escapeRegExp (str)](#apidoc.element.generator-node-webkit.super_.prototype._.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>every (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.every)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>exports ()](#apidoc.element.generator-node-webkit.super_.prototype._.exports)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>extend (object, source, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.extend)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>filter (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.filter)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>find (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.find)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findIndex (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findIndex)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findKey (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findKey)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findLast (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findLast)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findLastIndex (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findLastIndex)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findLastKey (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findLastKey)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findWhere (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findWhere)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>first (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.first)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>flatten (array, isShallow, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.flatten)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>foldl (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.foldl)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>foldr (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.foldr)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forEach (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forEach)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forEachRight (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forEachRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forIn (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forIn)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forInRight (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forInRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forOwn (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forOwn)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forOwnRight (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forOwnRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>functions (object)](#apidoc.element.generator-node-webkit.super_.prototype._.functions)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>groupBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.groupBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>has (object, key)](#apidoc.element.generator-node-webkit.super_.prototype._.has)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>head (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.head)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>humanize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.humanize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>identity (value)](#apidoc.element.generator-node-webkit.super_.prototype._.identity)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>include (collection, target, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.include)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>indexBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.indexBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>indexOf (array, value, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.indexOf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>initial (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.initial)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>inject (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.inject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>insert (str, i, substr)](#apidoc.element.generator-node-webkit.super_.prototype._.insert)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>intersection ()](#apidoc.element.generator-node-webkit.super_.prototype._.intersection)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>invert (object)](#apidoc.element.generator-node-webkit.super_.prototype._.invert)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>invoke (collection, methodName)](#apidoc.element.generator-node-webkit.super_.prototype._.invoke)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isArguments (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isArguments)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isArray ()](#apidoc.element.generator-node-webkit.super_.prototype._.isArray)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isBlank (str)](#apidoc.element.generator-node-webkit.super_.prototype._.isBlank)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isBoolean (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isBoolean)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isDate (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isDate)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isElement (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isElement)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isEmpty (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isEmpty)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isEqual (a, b, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.isEqual)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isFinite (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isFinite)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isFunction (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isFunction)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isNaN (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isNaN)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isNull (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isNull)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isNumber (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isNumber)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isObject (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isObject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isPlainObject (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isPlainObject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isRegExp (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isRegExp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isString (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isString)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isUndefined (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isUndefined)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>join ()](#apidoc.element.generator-node-webkit.super_.prototype._.join)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>keys (object)](#apidoc.element.generator-node-webkit.super_.prototype._.keys)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>last (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.last)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>levenshtein (str1, str2)](#apidoc.element.generator-node-webkit.super_.prototype._.levenshtein)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lines (str)](#apidoc.element.generator-node-webkit.super_.prototype._.lines)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>ljust (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.ljust)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lpad (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.lpad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lrpad (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.lrpad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lstrip (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.lstrip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>ltrim (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.ltrim)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>map (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.map)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>mapValues (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.mapValues)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>max (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.max)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>memoize (func, resolver)](#apidoc.element.generator-node-webkit.super_.prototype._.memoize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>merge (object)](#apidoc.element.generator-node-webkit.super_.prototype._.merge)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>methods (object)](#apidoc.element.generator-node-webkit.super_.prototype._.methods)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>min (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.min)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>mixin (object, source, options)](#apidoc.element.generator-node-webkit.super_.prototype._.mixin)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>naturalCmp (str1, str2)](#apidoc.element.generator-node-webkit.super_.prototype._.naturalCmp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>noConflict ()](#apidoc.element.generator-node-webkit.super_.prototype._.noConflict)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>noop ()](#apidoc.element.generator-node-webkit.super_.prototype._.noop)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>now ()](#apidoc.element.generator-node-webkit.super_.prototype._.now)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>numberFormat (number, dec, dsep, tsep)](#apidoc.element.generator-node-webkit.super_.prototype._.numberFormat)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>object (keys, values)](#apidoc.element.generator-node-webkit.super_.prototype._.object)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>omit (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.omit)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>once (func)](#apidoc.element.generator-node-webkit.super_.prototype._.once)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pad (str, length, padStr, type)](#apidoc.element.generator-node-webkit.super_.prototype._.pad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pairs (object)](#apidoc.element.generator-node-webkit.super_.prototype._.pairs)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>parseInt ()](#apidoc.element.generator-node-webkit.super_.prototype._.parseInt)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>partial (func)](#apidoc.element.generator-node-webkit.super_.prototype._.partial)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>partialRight (func)](#apidoc.element.generator-node-webkit.super_.prototype._.partialRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pick (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.pick)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pluck (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.pluck)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>property (key)](#apidoc.element.generator-node-webkit.super_.prototype._.property)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>prune (str, length, pruneStr)](#apidoc.element.generator-node-webkit.super_.prototype._.prune)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pull (array)](#apidoc.element.generator-node-webkit.super_.prototype._.pull)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>q (str, quoteChar)](#apidoc.element.generator-node-webkit.super_.prototype._.q)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>quote (str, quoteChar)](#apidoc.element.generator-node-webkit.super_.prototype._.quote)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>random (min, max, floating)](#apidoc.element.generator-node-webkit.super_.prototype._.random)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>range (start, end, step)](#apidoc.element.generator-node-webkit.super_.prototype._.range)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>reduce (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.reduce)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>reduceRight (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.reduceRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>reject (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.reject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>remove (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.remove)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>repeat (str, qty, separator)](#apidoc.element.generator-node-webkit.super_.prototype._.repeat)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rest (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.rest)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>result (object, key)](#apidoc.element.generator-node-webkit.super_.prototype._.result)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rjust (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.rjust)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rpad (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.rpad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rstrip (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.rstrip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rtrim (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.rtrim)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>runInContext (context)](#apidoc.element.generator-node-webkit.super_.prototype._.runInContext)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sample (collection, n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.sample)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>select (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.select)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>shuffle (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.shuffle)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>size (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.size)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>slugify (str)](#apidoc.element.generator-node-webkit.super_.prototype._.slugify)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>some (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.some)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sortBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.sortBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sortedIndex (array, value, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.sortedIndex)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>splice (str, i, howmany, substr)](#apidoc.element.generator-node-webkit.super_.prototype._.splice)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sprintf ()](#apidoc.element.generator-node-webkit.super_.prototype._.sprintf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>startsWith (str, starts)](#apidoc.element.generator-node-webkit.super_.prototype._.startsWith)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strLeft (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strLeft)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strLeftBack (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strLeftBack)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strRight (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strRightBack (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strRightBack)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strip (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.strip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>stripTags (str)](#apidoc.element.generator-node-webkit.super_.prototype._.stripTags)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>succ (str)](#apidoc.element.generator-node-webkit.super_.prototype._.succ)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>surround (str, wrapper)](#apidoc.element.generator-node-webkit.super_.prototype._.surround)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>swapCase (str)](#apidoc.element.generator-node-webkit.super_.prototype._.swapCase)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>tail (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.tail)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>take (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.take)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>tap (value, interceptor)](#apidoc.element.generator-node-webkit.super_.prototype._.tap)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>template (text, data, options)](#apidoc.element.generator-node-webkit.super_.prototype._.template)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>throttle (func, wait, options)](#apidoc.element.generator-node-webkit.super_.prototype._.throttle)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>times (n, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.times)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>titleize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.titleize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toArray (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.toArray)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toBool (str, trueValues, falseValues)](#apidoc.element.generator-node-webkit.super_.prototype._.toBool)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toBoolean (str, trueValues, falseValues)](#apidoc.element.generator-node-webkit.super_.prototype._.toBoolean)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toNumber (str, decimals)](#apidoc.element.generator-node-webkit.super_.prototype._.toNumber)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toSentence (array, separator, lastSeparator, serial)](#apidoc.element.generator-node-webkit.super_.prototype._.toSentence)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toSentenceSerial ()](#apidoc.element.generator-node-webkit.super_.prototype._.toSentenceSerial)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>transform (object, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.transform)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>trim (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.trim)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>truncate (str, length, truncateStr)](#apidoc.element.generator-node-webkit.super_.prototype._.truncate)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>underscored (str)](#apidoc.element.generator-node-webkit.super_.prototype._.underscored)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unescape (string)](#apidoc.element.generator-node-webkit.super_.prototype._.unescape)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unescapeHTML (str)](#apidoc.element.generator-node-webkit.super_.prototype._.unescapeHTML)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>union ()](#apidoc.element.generator-node-webkit.super_.prototype._.union)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>uniq (array, isSorted, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.uniq)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unique (array, isSorted, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.unique)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>uniqueId (prefix)](#apidoc.element.generator-node-webkit.super_.prototype._.uniqueId)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unquote (str, quoteChar)](#apidoc.element.generator-node-webkit.super_.prototype._.unquote)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unzip ()](#apidoc.element.generator-node-webkit.super_.prototype._.unzip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>values (object)](#apidoc.element.generator-node-webkit.super_.prototype._.values)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>vsprintf (fmt, argv)](#apidoc.element.generator-node-webkit.super_.prototype._.vsprintf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>where (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.where)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>without (array)](#apidoc.element.generator-node-webkit.super_.prototype._.without)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>words (str, delimiter)](#apidoc.element.generator-node-webkit.super_.prototype._.words)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>wrap (value, wrapper)](#apidoc.element.generator-node-webkit.super_.prototype._.wrap)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>xor ()](#apidoc.element.generator-node-webkit.super_.prototype._.xor)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>zip ()](#apidoc.element.generator-node-webkit.super_.prototype._.zip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>zipObject (keys, values)](#apidoc.element.generator-node-webkit.super_.prototype._.zipObject)
1.  object <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>str
1.  object <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>support
1.  object <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>templateSettings
1.  string <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>VERSION

#### [module generator-node-webkit.super_.prototype._.prototype](#apidoc.module.generator-node-webkit.super_.prototype._.prototype)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>after ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.after)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>all ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.all)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>any ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.any)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>assign ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.assign)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>at ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.at)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>bind ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.bind)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>bindAll ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.bindAll)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>bindKey ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.bindKey)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>camelize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.camelize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>capitalize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.capitalize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>center ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.center)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>chain ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.chain)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>chars ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.chars)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>chop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.chop)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>classify ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.classify)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>clean ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.clean)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>clone ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.clone)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>cloneDeep ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.cloneDeep)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>collect ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.collect)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>compact ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.compact)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>compose ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.compose)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>concat ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.concat)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>constant ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.constant)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>contains ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.contains)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>count ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.count)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>countBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.countBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>create ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.create)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>createCallback ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.createCallback)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>curry ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.curry)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>dasherize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.dasherize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>debounce ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.debounce)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>defaults ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.defaults)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>defer ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.defer)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>delay ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.delay)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>detect ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.detect)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>difference ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.difference)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>drop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.drop)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>each ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.each)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>eachRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.eachRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>endsWith ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.endsWith)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>escape ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.escape)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>escapeHTML ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.escapeHTML)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>escapeRegExp ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>every ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.every)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>exports ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.exports)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>extend ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.extend)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>filter ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.filter)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>find ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.find)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findIndex ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findIndex)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findKey ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findKey)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findLast ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLast)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findLastIndex ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLastIndex)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findLastKey ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLastKey)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findWhere ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findWhere)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>first (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.first)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>flatten ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.flatten)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>foldl ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.foldl)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>foldr ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.foldr)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forEach ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forEach)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forEachRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forEachRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forIn ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forIn)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forInRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forInRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forOwn ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forOwn)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forOwnRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forOwnRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>functions ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.functions)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>groupBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.groupBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>has ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.has)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>head (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.head)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>humanize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.humanize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>identity ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.identity)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>include ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.include)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>indexBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.indexBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>indexOf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.indexOf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>initial ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.initial)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>inject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.inject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>insert ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.insert)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>intersection ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.intersection)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>invert ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.invert)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>invoke ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.invoke)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isArguments ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isArguments)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isArray ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isArray)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isBlank ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isBlank)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isBoolean ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isBoolean)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isDate ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isDate)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isElement ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isElement)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isEmpty ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isEmpty)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isEqual ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isEqual)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isFinite ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isFinite)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isFunction ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isFunction)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isNaN ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNaN)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isNull ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNull)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isNumber ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNumber)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isObject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isObject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isPlainObject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isPlainObject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isRegExp ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isRegExp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isString ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isString)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isUndefined ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isUndefined)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>join ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.join)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>keys ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.keys)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>last (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.last)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lastIndexOf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>levenshtein ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.levenshtein)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lines ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lines)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>ljust ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.ljust)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lpad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lpad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lrpad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lrpad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lstrip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lstrip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>ltrim ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.ltrim)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>map ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.map)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>mapValues ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.mapValues)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>max ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.max)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>memoize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.memoize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>merge ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.merge)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>methods ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.methods)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>min ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.min)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>mixin ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.mixin)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>naturalCmp ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.naturalCmp)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>noConflict ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.noConflict)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>noop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.noop)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>now ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.now)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>numberFormat ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.numberFormat)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>object ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.object)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>omit ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.omit)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>once ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.once)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pairs ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pairs)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>parseInt ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.parseInt)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>partial ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.partial)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>partialRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.partialRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pick ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pick)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pluck ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pluck)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pop)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>property ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.property)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>prune ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.prune)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pull ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pull)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>push ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.push)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>q ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.q)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>quote ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.quote)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>random ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.random)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>range ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.range)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reduce ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reduce)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reduceRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reduceRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reject)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>remove ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.remove)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>repeat ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.repeat)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rest ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rest)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>result ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.result)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reverse ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reverse)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rjust ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rjust)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rpad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rpad)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rstrip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rstrip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rtrim ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rtrim)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>runInContext ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.runInContext)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sample (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sample)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>select ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.select)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>shift ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.shift)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>shuffle ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.shuffle)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>size ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.size)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>slice ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.slice)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>slugify ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.slugify)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>some ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.some)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sort ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sort)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sortBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sortBy)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sortedIndex ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sortedIndex)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>splice ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.splice)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sprintf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sprintf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>startsWith ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.startsWith)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strLeft ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strLeft)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strLeftBack ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strLeftBack)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strRight)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strRightBack ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strRightBack)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>stripTags ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.stripTags)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>succ ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.succ)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>support (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.support)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>surround ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.surround)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>swapCase ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.swapCase)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>tail ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.tail)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>take (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.take)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>tap ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.tap)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>template ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.template)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>templateSettings (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.templateSettings)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>throttle ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.throttle)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>times ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.times)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>titleize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.titleize)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toArray ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toArray)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toBool ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toBool)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toBoolean ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toBoolean)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toNumber ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toNumber)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toSentence ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toSentence)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toSentenceSerial ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toSentenceSerial)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toString ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toString)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>transform ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.transform)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>trim ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.trim)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>truncate ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.truncate)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>underscored ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.underscored)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unescape ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unescape)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unescapeHTML ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unescapeHTML)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>union ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.union)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>uniq ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.uniq)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unique ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unique)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>uniqueId ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.uniqueId)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unquote ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unquote)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unshift ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unshift)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unzip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unzip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>value ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.value)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>valueOf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.valueOf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>values ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.values)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>vsprintf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.vsprintf)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>where ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.where)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>without ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.without)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>words ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.words)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>wrap ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.wrap)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>xor ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.xor)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>zip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.zip)
1.  [function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>zipObject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.zipObject)



# <a name="apidoc.module.generator-node-webkit"></a>[module generator-node-webkit](#apidoc.module.generator-node-webkit)

#### <a name="apidoc.element.generator-node-webkit.super_"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.</span>super_ (args, options)](#apidoc.element.generator-node-webkit.super_)
- description and source-code
```javascript
function Base(args, options) {
  events.EventEmitter.call(this);

  if (!Array.isArray(args)) {
    options = args;
    args = [];
  }

  this.options = options || {};
  this._args = args || [];
  this._options = {};
  this._arguments = [];
  this._hooks = [];
  this._composedWith = [];
  this._transformStreams = [];

  this.option('help', {
    alias: 'h',
    desc: 'Print the generator\'s options and usage'
  });

  this.option('skip-cache', {
    type: Boolean,
    desc: 'Do not remember prompt answers',
    defaults: false
  });

  // checks required paramaters
  assert(this.options.env, 'You must provide the environment object. Use env#create() to create a new generator.');
  assert(this.options.resolved, 'You must provide the resolved path value. Use env#create() to create a new generator.');
  this.env = this.options.env;
  this.resolved = this.options.resolved;

  // Ensure the environment support features this yeoman-generator version require.
  require('yeoman-environment').enforceUpdate(this.env);

  this.description = this.description || '';

  this.async = function () {
    return function () {};
  };

  this.conflicter = new Conflicter(this.env.adapter, this.options.force);

  // Mirror the adapter log method on the generator.
  //
  // example:
  // this.log('foo');
  // this.log.error('bar');
  this.log = this.env.adapter.log;

  // determine the app root
  var rootPath = findup('.yo-rc.json');
  rootPath = rootPath ? path.dirname(rootPath) : process.cwd();
  if (rootPath !== process.cwd()) {
    this.log(
      '\n' +
      'Just found a '.yo-rc.json' in a parent directory.\n' +
      'Setting the project root at: ' + rootPath + '\n'
    );
    process.chdir(rootPath);
  }

  // Set the file-utils environments
  // Set logger as a noop as logging is handled by the yeoman conflicter
  this.src = file.createEnv({
    base: this.sourceRoot.bind(this),
    dest: this.destinationRoot.bind(this),
    logger: fileLogger
  });
  this.dest = file.createEnv({
    base: this.destinationRoot.bind(this),
    dest: this.sourceRoot.bind(this),
    logger: fileLogger
  });
  this.fs = FileEditor.create(this.env.sharedFs);

  // Register collision filters which return true if the file can be written to
  this.dest.registerValidationFilter('collision', this.getCollisionFilter());
  this.src.registerValidationFilter('collision', this.getCollisionFilter());

  this.appname = this.determineAppname();
  this.config = this._getStorage();
  this._globalConfig = this._getGlobalStorage();

  // ensure source/destination path, can be configured from subclasses
  this.sourceRoot(path.join(path.dirname(this.resolved), 'templates'));

  // Only instantiate the Gruntfile API when requested
  Object.defineProperty(this, 'gruntfile', {
    get: function () {
      if (!this.env.gruntfile) {
        var gruntfile = this.fs.read(this.destinationPath('Gruntfile.js'), {
          defaults: ''
        });
        this.env.gruntfile = new GruntfileEditor(gruntfile);
      }

      // Schedule the creation/update of the Gruntfile
      this.env.runLoop.add('writing', function (done) {
        this.fs.write(
          this.destinationPath('Gruntfile.js'),
          this.env.gruntfile.toString()
        );
        done();
      }.bind(this), { once: 'gruntfile:write' });

      return this.env.gruntfile;
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.</span>super_.prototype._ (value)](#apidoc.element.generator-node-webkit.super_.prototype._)
- description and source-code
```javascript
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
  return (value && typeof value == 'object' && !isArray(value) && hasOwnProperty.call(value, '__wrapped__'))
   ? value
   : new lodashWrapper(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.generator-node-webkit.super_"></a>[module generator-node-webkit.super_](#apidoc.module.generator-node-webkit.super_)

#### <a name="apidoc.element.generator-node-webkit.super_.super_"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.</span>super_ ()](#apidoc.element.generator-node-webkit.super_.super_)
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

#### <a name="apidoc.element.generator-node-webkit.super_.extend"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.</span>extend (protoProps, staticProps)](#apidoc.element.generator-node-webkit.super_.extend)
- description and source-code
```javascript
function extend(protoProps, staticProps) {
  var parent = this;
  var child;

  // The constructor function for the new subclass is either defined by you
  // (the "constructor" property in your 'extend' definition), or defaulted
  // by us to simply call the parent's constructor.
  if (protoProps && hasOwnProp.call(protoProps, 'constructor')) {
    child = protoProps.constructor;
  } else {
    child = function () { return parent.apply(this, arguments); };
  }

  // Add static properties to the constructor function, if supplied.
  objectAssign(child, parent, staticProps);

  // Set the prototype chain to inherit from 'parent'
  child.prototype = Object.create(parent.prototype, {
    constructor: {
      value: child,
      enumerable: false,
      writable: true,
      configurable: true
    }
  });

  // Add prototype properties (instance properties) to the subclass,
  // if supplied.
  if (protoProps) objectAssign(child.prototype, protoProps);

  // Set a convenience property in case the parent's prototype is needed
  // later.
  child.__super__ = parent.prototype;

  return child;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.generator-node-webkit.super_.prototype"></a>[module generator-node-webkit.super_.prototype](#apidoc.module.generator-node-webkit.super_.prototype)

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_ (value)](#apidoc.element.generator-node-webkit.super_.prototype._)
- description and source-code
```javascript
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
  return (value && typeof value == 'object' && !isArray(value) && hasOwnProperty.call(value, '__wrapped__'))
   ? value
   : new lodashWrapper(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._directory"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_directory (source, destination, process, bulk)](#apidoc.element.generator-node-webkit.super_.prototype._directory)
- description and source-code
```javascript
function _directory(source, destination, process, bulk) {
  // Only add sourceRoot if the path is not absolute
  var root = this.isPathAbsolute(source) ? source : path.join(this.sourceRoot(), source);
  var files = this.expandFiles('**', { dot: true, cwd: root });

  destination = destination || source;

  if (typeof destination === 'function') {
    process = destination;
    destination = source;
  }

  var cp = this.copy;
  if (bulk) {
    cp = this.bulkCopy;
  }

  // get the path relative to the template root, and copy to the relative destination
  for (var i in files) {
    var dest = path.join(destination, files[i]);
    cp.call(this, path.join(root, files[i]), dest, process);
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._getGlobalStorage"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_getGlobalStorage ()](#apidoc.element.generator-node-webkit.super_.prototype._getGlobalStorage)
- description and source-code
```javascript
_getGlobalStorage = function () {
  var storePath = path.join(userHome, '.yo-rc-global.json');
  var storeName = util.format('%s:%s', this.rootGeneratorName(), this.rootGeneratorVersion());
  return new Storage(storeName, this.fs, storePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._getStorage"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_getStorage ()](#apidoc.element.generator-node-webkit.super_.prototype._getStorage)
- description and source-code
```javascript
_getStorage = function () {
  var storePath = path.join(this.destinationRoot(), '.yo-rc.json');
  return new Storage(this.rootGeneratorName(), this.fs, storePath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._prepCopy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_prepCopy (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype._prepCopy)
- description and source-code
```javascript
function _prepCopy(source, destination, process) {
  destination = destination || source;

  if (typeof destination === 'function') {
    process = destination;
    destination = source;
  }

  source = this.isPathAbsolute(source) ? source : path.join(this.sourceRoot(), source);
  destination = this.isPathAbsolute(destination) ? destination : path.join(this.destinationRoot(), destination);

  var encoding = null;
  var body = fs.readFileSync(source);

  var isText = istextorbinary.isTextSync(undefined, body);

  if (isText) {
    body = body.toString();

    if (typeof process === 'function') {
      body = process(body, source, destination, {
        encoding: encoding
      });
    }
  }

  return {
    body: body,
    encoding: encoding,
    destination: destination,
    source: source
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._writeFiles"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_writeFiles (done)](#apidoc.element.generator-node-webkit.super_.prototype._writeFiles)
- description and source-code
```javascript
_writeFiles = function (done) {
  var self = this;

  var conflictChecker = through.obj(function (file, enc, cb) {
    var stream = this;

    // Config file should not be processed by the conflicter. Just pass through
    var filename = path.basename(file.path);
    if (filename === '.yo-rc.json' || filename === '.yo-rc-global.json') {
      this.push(file);
      return cb();
    }

    self.conflicter.checkForCollision(file.path, file.contents, function (err, status) {
      if (err) return cb(err);
      if (status !== 'skip') {
        stream.push(file);
      }
      cb();
    });
    self.conflicter.resolve();
  });

  var transformStreams = this._transformStreams.concat([conflictChecker]);
  this.fs.commit(transformStreams, function () {
    done();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.append"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>append (html, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.append)
- description and source-code
```javascript
function append(html, tagName, content) {
  return this.domUpdate(html, tagName, content, 'a');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.appendFiles"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendFiles (htmlOrOptions, fileType, optimizedPath, sourceFileList, attrs, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.appendFiles)
- description and source-code
```javascript
function appendFiles(htmlOrOptions, fileType, optimizedPath, sourceFileList, attrs, searchPath) {
  var blocks;
  var updatedContent;
  var html = htmlOrOptions;
  var files = '';

  if (typeof htmlOrOptions === 'object') {
    html = htmlOrOptions.html;
    fileType = htmlOrOptions.fileType;
    optimizedPath = htmlOrOptions.optimizedPath;
    sourceFileList = htmlOrOptions.sourceFileList;
    attrs = htmlOrOptions.attrs;
    searchPath = htmlOrOptions.searchPath;
  }

  attrs = this.attributes(attrs);

  if (fileType === 'js') {
    sourceFileList.forEach(function (el) {
      files += '        <script ' + attrs + ' src="' + el + '"></script>\n';
    });
    blocks = this.generateBlock('js', optimizedPath, files, searchPath);
    updatedContent = this.append(html, 'body', blocks);
  } else if (fileType === 'css') {
    sourceFileList.forEach(function (el) {
      files += '        <link ' + attrs + ' rel="stylesheet" href="' + el + '">\n';
    });
    blocks = this.generateBlock('css', optimizedPath, files, searchPath);
    updatedContent = this.append(html, 'head', blocks);
  }

  // cleanup trailing whitespace
  return updatedContent.replace(/[\t ]+$/gm, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.appendScripts"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendScripts (html, optimizedPath, sourceFileList, attrs, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.appendScripts)
- description and source-code
```javascript
function appendScripts(html, optimizedPath, sourceFileList, attrs, searchPath) {
  return this.appendFiles(html, 'js', optimizedPath, sourceFileList, attrs, searchPath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.appendScriptsDir"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendScriptsDir (html, optimizedPath, sourceScriptDir, attrs)](#apidoc.element.generator-node-webkit.super_.prototype.appendScriptsDir)
- description and source-code
```javascript
function appendScriptsDir(html, optimizedPath, sourceScriptDir, attrs) {
  var sourceScriptList = fs.readdirSync(path.resolve(sourceScriptDir));
  return this.appendFiles(html, 'js', optimizedPath, sourceScriptList, attrs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.appendStyles"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendStyles (html, optimizedPath, sourceFileList, attrs, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.appendStyles)
- description and source-code
```javascript
function appendStyles(html, optimizedPath, sourceFileList, attrs, searchPath) {
  return this.appendFiles(html, 'css', optimizedPath, sourceFileList, attrs, searchPath);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.appendStylesDir"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendStylesDir (html, optimizedPath, sourceStyleDir, attrs)](#apidoc.element.generator-node-webkit.super_.prototype.appendStylesDir)
- description and source-code
```javascript
function appendStylesDir(html, optimizedPath, sourceStyleDir, attrs) {
  var sourceStyleList = fs.readdirSync(path.resolve(sourceStyleDir));
  return this.appendFiles(html, 'css', optimizedPath, sourceStyleList, attrs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.appendToFile"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>appendToFile (path, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.appendToFile)
- description and source-code
```javascript
function appendToFile(path, tagName, content) {
  var html = this.readFileAsString(path);
  var updatedContent = this.append(html, tagName, content);
  this.writeFileFromString(updatedContent, path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.argument"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>argument (name, config)](#apidoc.element.generator-node-webkit.super_.prototype.argument)
- description and source-code
```javascript
function argument(name, config) {
  config = config || {};
  _.defaults(config, {
    name: name,
    required: config.defaults == null,
    type: String
  });

  var position = this._arguments.length;
  this._arguments.push({
    name: name,
    config: config
  });

  Object.defineProperty(this, name, {
    configurable: true,
    enumerable: true,
    get: function () {
      // a bit of coercion and type handling, to be improved
      // just dealing with Array/String, default is assumed to be String
      var value = config.type === Array ? this.args.slice(position) : this.args[position];
      return position >= this.args.length ? config.defaults : value;
    },
    set: function (value) {
      this.args[position] = value;
    }
  });

  this.checkRequiredArgs();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.argumentsHelp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>argumentsHelp ()](#apidoc.element.generator-node-webkit.super_.prototype.argumentsHelp)
- description and source-code
```javascript
function argumentsHelp() {
  var rows = this._arguments.map(function (arg) {
    var config = arg.config;
    return [
      '',
      arg.name ? arg.name : '',
      config.desc ? '# ' + config.desc : '',
      config.type ? 'Type: ' + config.type.name : '',
      'Required: ' + config.required
    ];
  });

  return table(rows);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.attributes"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>attributes (attrs)](#apidoc.element.generator-node-webkit.super_.prototype.attributes)
- description and source-code
```javascript
function attributes(attrs) {
  return Object.keys(attrs || {}).map(function (key) {
    return key + '="' + attrs[key] + '"';
  }).join(' ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.bowerInstall"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>bowerInstall (cmpnt, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.bowerInstall)
- description and source-code
```javascript
function install(cmpnt, options, cb) {
  return this.runInstall('bower', cmpnt, options, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.bulkCopy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>bulkCopy (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.bulkCopy)
- description and source-code
```javascript
function bulkCopy(source, destination, process) {

  var file = this._prepCopy(source, destination, process);

  mkdirp.sync(path.dirname(file.destination));
  fs.writeFileSync(file.destination, file.body);

  // synchronize stats and modification times from the original file.
  var stats = fs.statSync(file.source);
  try {
    fs.chmodSync(file.destination, stats.mode);
    fs.utimesSync(file.destination, stats.atime, stats.mtime);
  } catch (err) {
    this.log.error('Error setting permissions of "' + chalk.bold(file.destination) + '" file: ' + err);
  }

  this.log.create(file.destination);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.bulkDirectory"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>bulkDirectory (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.bulkDirectory)
- description and source-code
```javascript
function directory(source, destination, process) {
  // Join the source here because the conflicter will not run
  // until next tick, which resets the source root on remote
  // bulkCopy operations
  source = path.join(this.sourceRoot(), source);
  this.conflicter.checkForCollision(destination, null, function (err, status) {
    // create or force means file write, identical or skip prevent the
    // actual write.
    if (/force|create/.test(status)) {
      this._directory(source, destination, process, true);
    }

  }.bind(this));
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.cacheRoot"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>cacheRoot ()](#apidoc.element.generator-node-webkit.super_.prototype.cacheRoot)
- description and source-code
```javascript
function cacheRoot() {
  return path.join(xdgBasedir.cache, 'yeoman');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.checkRequiredArgs"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>checkRequiredArgs ()](#apidoc.element.generator-node-webkit.super_.prototype.checkRequiredArgs)
- description and source-code
```javascript
checkRequiredArgs = function () {
  // If the help option was provided, we don't want to check for required
  // arguments, since we're only going to print the help message anyway.
  if (this.options.help) return;

  // Bail early if it's not possible to have a missing required arg
  if (this.args.length > this._arguments.length) return;

  this._arguments.forEach(function (arg, position) {
    // If the help option was not provided, check whether the argument was
    // required, and whether a value was provided.
    if (arg.config.required && position >= this.args.length) {
      return this.emit('error', new Error('Did not provide required argument ' + chalk.bold(arg.name) + '!'));
    }
  }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.composeWith"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>composeWith (namespace, options, settings)](#apidoc.element.generator-node-webkit.super_.prototype.composeWith)
- description and source-code
```javascript
function composeWith(namespace, options, settings) {
  settings = settings || {};
  var generator;
  if (settings.local) {
    var Generator = require(settings.local);
    Generator.resolved = require.resolve(settings.local);
    Generator.namespace = namespace;
    generator = this.env.instantiate(Generator, options);
  } else {
    generator = this.env.create(namespace, options);
  }

  if (this._running) {
    generator.run();
  } else {
    this._composedWith.push(generator);
  }
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.copy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>copy (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.copy)
- description and source-code
```javascript
function copy(source, destination, process) {
  var file = this._prepCopy(source, destination, process);
  try {
    file.body = this.engine(file.body, this);
  } catch (err) {
    // this happens in some cases when trying to copy a JS file like lodash/underscore
    // (conflicting the templating engine)
  }

  this.fs.copy(file.source, file.destination, {
    process: function () {
      return file.body;
    }
  });

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.defaultFor"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>defaultFor (name)](#apidoc.element.generator-node-webkit.super_.prototype.defaultFor)
- description and source-code
```javascript
function defaultFor(name) {
  return this.options[name] || name;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.desc"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>desc (description)](#apidoc.element.generator-node-webkit.super_.prototype.desc)
- description and source-code
```javascript
function desc(description) {
  this.description = description || '';
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.destinationPath"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>destinationPath ()](#apidoc.element.generator-node-webkit.super_.prototype.destinationPath)
- description and source-code
```javascript
destinationPath = function () {
  var args = [this.destinationRoot()].concat(_.toArray(arguments));
  return path.join.apply(path, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.destinationRoot"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>destinationRoot (rootPath)](#apidoc.element.generator-node-webkit.super_.prototype.destinationRoot)
- description and source-code
```javascript
destinationRoot = function (rootPath) {
  if (_.isString(rootPath)) {
    this._destinationRoot = path.resolve(rootPath);

    if (!fs.existsSync(rootPath)) {
      this.mkdir(rootPath);
    }

    process.chdir(rootPath);

    // Reset the storage
    this.config = this._getStorage();
  }

  return this._destinationRoot || process.cwd();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.determineAppname"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>determineAppname ()](#apidoc.element.generator-node-webkit.super_.prototype.determineAppname)
- description and source-code
```javascript
determineAppname = function () {
  var appname = this.fs.readJSON(this.destinationPath('bower.json'), {}).name;

  if (!appname) {
    appname = this.fs.readJSON(this.destinationPath('package.json'), {}).name;
  }

  if (!appname) {
    appname = path.basename(this.destinationRoot());
  }

  return appname.replace(/[^\w\s]+?/g, ' ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.directory"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>directory (source, destination, process)](#apidoc.element.generator-node-webkit.super_.prototype.directory)
- description and source-code
```javascript
function directory(source, destination, process) {
  return this._directory(source, destination, process);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.domUpdate"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>domUpdate (html, tagName, content, mode)](#apidoc.element.generator-node-webkit.super_.prototype.domUpdate)
- description and source-code
```javascript
function domUpdate(html, tagName, content, mode) {
  var $ = cheerio.load(html, { decodeEntities: false });

  if (content !== undefined) {
    if (mode === 'a') {
      $(tagName).append(content);
    } else if (mode === 'p') {
      $(tagName).prepend(content);
    } else if (mode === 'r') {
      $(tagName).html(content);
    } else if (mode === 'd') {
      $(tagName).remove();
    }
    return $.html();
  } else {
    console.error('Please supply valid content to be updated.');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.engine"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>engine (body, data, options)](#apidoc.element.generator-node-webkit.super_.prototype.engine)
- description and source-code
```javascript
engine = function (body, data, options) {
  return engine.detect(body) ? engine(body, data, options) : body;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.expand"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>expand (pattern, options)](#apidoc.element.generator-node-webkit.super_.prototype.expand)
- description and source-code
```javascript
function expand(pattern, options) {
  return glob.sync(pattern, options);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.expandFiles"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>expandFiles (pattern, options)](#apidoc.element.generator-node-webkit.super_.prototype.expandFiles)
- description and source-code
```javascript
function expandFiles(pattern, options) {
  options = options || {};
  var cwd = options.cwd || process.cwd();
  return this.expand(pattern, options).filter(function (filepath) {
    return fs.statSync(path.join(cwd, filepath)).isFile();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.extract"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>extract (archive, destination, opts, cb)](#apidoc.element.generator-node-webkit.super_.prototype.extract)
- description and source-code
```javascript
function _extract(archive, destination, opts, cb) {
  if (_.isFunction(opts) && !cb) {
    cb = opts;
    opts = { extract: true };
  }

  opts = _.assign({ extract: true }, opts);

  var log = this.log.write()
    .info('... Fetching %s ...', archive)
    .info(chalk.yellow('This might take a few moments'));

  var download = new Download(opts)
    .get(archive)
    .dest(destination)
    .use(function (res) {
      res.on('data', function () {
        log.write('.');
      });
    });

  download.run(function (err) {
    if (err) return cb(err);

    log.write().ok('Done in ' + destination).write();
    cb();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.fetch"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>fetch (url, destination, cb)](#apidoc.element.generator-node-webkit.super_.prototype.fetch)
- description and source-code
```javascript
function _fetch(url, destination, cb) {
  var log = this.log('... Fetching %s ...', url);
  var download = new Download()
    .get(url)
    .dest(destination)
    .use(function (res) {
      res.on('data', function () {
        log.write('.');
      });
    });

  download.run(function (err) {
    if (err) return cb(err);

    log.ok('Done in ' + destination).write();
    cb();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.generateBlock"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>generateBlock (blockType, optimizedPath, filesBlock, searchPath)](#apidoc.element.generator-node-webkit.super_.prototype.generateBlock)
- description and source-code
```javascript
function generateBlock(blockType, optimizedPath, filesBlock, searchPath) {
  var blockStart;
  var blockEnd;
  var blockSearchPath = '';

  if (searchPath !== undefined) {
    if (util.isArray(searchPath)) {
      searchPath = '{' + searchPath.join(',') + '}';
    }
    blockSearchPath = '(' + searchPath + ')';
  }

  blockStart = '\n        <!-- build:' + blockType + blockSearchPath + ' ' + optimizedPath + ' -->\n';
  blockEnd = '        <!-- endbuild -->\n';
  return blockStart + filesBlock + blockEnd;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.getCollisionFilter"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>getCollisionFilter ()](#apidoc.element.generator-node-webkit.super_.prototype.getCollisionFilter)
- description and source-code
```javascript
getCollisionFilter = function () {
  var self = this;
  return function checkForCollisionFilter(output) {
    var done = this.async();

    self.conflicter.checkForCollision(output.path, output.contents, function (err, status) {
      if (err) {
        done(false);
        return self.emit('error', err);
      }

      if (!/force|create/.test(status)) {
        return done('Skip modifications to ' + output.path);
      }

      return done(true);
    });
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.help"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>help ()](#apidoc.element.generator-node-webkit.super_.prototype.help)
- description and source-code
```javascript
function help() {
  var filepath = path.join(this.sourceRoot(), '../USAGE');
  var exists = fs.existsSync(filepath);

  var out = [
    'Usage:',
    '  ' + this.usage(),
    ''
  ];

  // build options
  if (Object.keys(this._options).length) {
    out = out.concat([
      'Options:',
      this.optionsHelp(),
      ''
    ]);
  }

  // build arguments
  if (this._arguments.length) {
    out = out.concat([
      'Arguments:',
      this.argumentsHelp(),
      ''
    ]);
  }

  // append USAGE file is any
  if (exists) {
    out.push(fs.readFileSync(filepath, 'utf8'));
  }

  return out.join('\n');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.hookFor"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>hookFor (name, config)](#apidoc.element.generator-node-webkit.super_.prototype.hookFor)
- description and source-code
```javascript
function hookFor(name, config) {
  config = config || {};

  // enforce use of hookFor during instantiation
  assert(!this._running, 'hookFor can only be used inside the constructor function');

  // add the corresponding option to this class, so that we output these hooks
  // in help
  this.option(name, {
    desc: _s.humanize(name) + ' to be invoked',
    defaults: this.options[name] || ''
  });

  this._hooks.push(_.defaults(config, {
    name: name
  }));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.installDependencies"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>installDependencies (options)](#apidoc.element.generator-node-webkit.super_.prototype.installDependencies)
- description and source-code
```javascript
installDependencies = function (options) {
  var msg = {
    commands: [],
    template: _.template('\n\nI\'m all done. ' +
    '<%= skipInstall ? "Just run" : "Running" %> <%= commands %> ' +
    '<%= skipInstall ? "" : "for you " %>to install the required dependencies.' +
    '<% if (!skipInstall) { %> If this fails, try running the command yourself.<% } %>\n\n')
  };

  var commands = [];

  if (_.isFunction(options)) {
    options = {
      callback: options
    };
  }

  options = _.defaults(options || {}, {
    bower: true,
    npm: true,
    skipInstall: false,
    skipMessage: false,
    callback: function () {}
  });

  if (options.npm) {
    msg.commands.push('npm install');
    commands.push(function (cb) {
      this.npmInstall(null, null, cb);
    }.bind(this));
  }

  if (options.bower) {
    msg.commands.push('bower install');
    commands.push(function (cb) {
      this.bowerInstall(null, null, cb);
    }.bind(this));
  }

  assert(msg.commands.length, 'installDependencies needs at least one of 'npm' or 'bower' to run.');

  if (!options.skipMessage) {
    this.env.adapter.log(msg.template(_.extend(options, {
      commands: chalk.yellow.bold(msg.commands.join(' & '))
    })));
  }

  if (options.skipInstall) {
    return options.callback();
  }

  async.parallel(commands, options.callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.invoke"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>invoke (namespace, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.invoke)
- description and source-code
```javascript
function invoke(namespace, options, cb) {
  cb = cb || function () {};
  options = options || {};
  options.args = options.args || [];

  // Hack: create a clone of the environment because we don't want to share
  // the runLoop
  var env = require('yeoman-environment').util.duplicateEnv(this.env);
  var generator = env.create(namespace, options);

  this.log.emit('up');
  this.log.invoke(namespace);
  this.log.emit('up');

  generator.once('end', function () {
    this.log.emit('down');
    this.log.emit('down');
  }.bind(this));

  return generator.run(cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.isPathAbsolute"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>isPathAbsolute ()](#apidoc.element.generator-node-webkit.super_.prototype.isPathAbsolute)
- description and source-code
```javascript
isPathAbsolute = function () {
  var filepath = path.join.apply(path, arguments);
  return path.resolve(filepath) === filepath;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.mkdir"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>mkdir ()](#apidoc.element.generator-node-webkit.super_.prototype.mkdir)
- description and source-code
```javascript
mkdir = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.npmInstall"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>npmInstall (pkgs, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.npmInstall)
- description and source-code
```javascript
function install(pkgs, options, cb) {
  return this.runInstall('npm', pkgs, options, cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.option"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>option (name, config)](#apidoc.element.generator-node-webkit.super_.prototype.option)
- description and source-code
```javascript
function option(name, config) {
  config = config || {};
  _.defaults(config, {
    name: name,
    desc: 'Description for ' + name,
    type: Boolean,
    defaults: undefined,
    hide: false
  });

  if (this._options[name] == null) {
    this._options[name] = config;
  }

  if (this.options[name] == null) {
    this.options[name] = config.defaults;
  }

  this.parseOptions();

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.optionsHelp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>optionsHelp ()](#apidoc.element.generator-node-webkit.super_.prototype.optionsHelp)
- description and source-code
```javascript
function optionsHelp() {
  var options = _.reject(this._options, function (el) {
    return el.hide;
  });

  var hookOpts = this._hooks.map(function (hook) {
    return hook.generator && hook.generator._options;
  }).reduce(function (a, b) {
    a = a.concat(b);
    return a;
  }, []).filter(function (opts) {
    return opts && opts.name !== 'help';
  });

  var rows = options.concat(hookOpts).map(function (opt) {
    var defaults = opt.defaults;
    return [
      '',
      opt.alias ? '-' + opt.alias + ', ' : '',
      '--' + opt.name,
      opt.desc ? '# ' + opt.desc : '',
      defaults == null || defaults === '' ? '' : 'Default: ' + defaults
    ];
  });

  return table(rows);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.parseOptions"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>parseOptions ()](#apidoc.element.generator-node-webkit.super_.prototype.parseOptions)
- description and source-code
```javascript
parseOptions = function () {
  var opts = {};
  var shortOpts = {};
  _.each(this._options, function (option) {
    opts[option.name] = option.type;
    if (option.alias) {
      shortOpts[option.alias] = '--' + option.name;
    }
  });
  opts = nopt(opts, shortOpts, this._args, 0);

  _.extend(this.options, opts);

  this.args = this.arguments = opts.argv.remain;
  this.checkRequiredArgs();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.prepend"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>prepend (html, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.prepend)
- description and source-code
```javascript
function prepend(html, tagName, content) {
  return this.domUpdate(html, tagName, content, 'p');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.prependToFile"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>prependToFile (path, tagName, content)](#apidoc.element.generator-node-webkit.super_.prototype.prependToFile)
- description and source-code
```javascript
function prependToFile(path, tagName, content) {
  var html = this.readFileAsString(path);
  var updatedContent = this.prepend(html, tagName, content);
  this.writeFileFromString(updatedContent, path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.prompt"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>prompt (questions, callback)](#apidoc.element.generator-node-webkit.super_.prototype.prompt)
- description and source-code
```javascript
prompt = function (questions, callback) {
  questions = promptSuggestion.prefillQuestions(this._globalConfig, questions);

  this.env.adapter.prompt(questions, function (answers) {
    if (!this.options['skip-cache']) {
      promptSuggestion.storeAnswers(this._globalConfig, questions, answers);
    }

    if (_.isFunction(callback)) {
      callback(answers);
    }
  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.read"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>read (filepath, encoding)](#apidoc.element.generator-node-webkit.super_.prototype.read)
- description and source-code
```javascript
function read(filepath, encoding) {
  if (!this.isPathAbsolute(filepath)) {
    filepath = path.join(this.sourceRoot(), filepath);
  }

  var contents = this.fs.read(filepath, { raw: true });
  return contents.toString(encoding || 'utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.readFileAsString"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>readFileAsString (filePath)](#apidoc.element.generator-node-webkit.super_.prototype.readFileAsString)
- description and source-code
```javascript
function readFileAsString(filePath) {
  return fs.readFileSync(path.resolve(filePath), 'utf8');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.registerTransformStream"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>registerTransformStream (stream)](#apidoc.element.generator-node-webkit.super_.prototype.registerTransformStream)
- description and source-code
```javascript
registerTransformStream = function (stream) {
  assert(stream, 'expected to receive a transform stream as parameter');
  this._transformStreams.push(stream);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.remote"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>remote ()](#apidoc.element.generator-node-webkit.super_.prototype.remote)
- description and source-code
```javascript
remote = function () {
  var username;
  var repo;
  var branch;
  var cb;
  var refresh;
  var url;
  var cache;

  if (arguments.length <= 3 && typeof arguments[2] !== 'function') {
    url = arguments[0];
    cb = arguments[1];
    refresh = arguments[2];
    cache = path.join(this.cacheRoot(), _.slugify(url));
  } else {
    username = arguments[0];
    repo = arguments[1];
    branch = arguments[2];
    cb = arguments[3];
    refresh = arguments[4];

    if (!cb) {
      cb = branch;
      branch = 'master';
    }

    cache = path.join(this.cacheRoot(), username, repo, branch);
    url = 'https://github.com/' + [username, repo, 'archive', branch].join('/') + '.tar.gz';
  }

  var done = function (err) {
    if (err) return cb(err);
    this.remoteDir(cache, cb);
  }.bind(this);

  fs.stat(cache, function (err) {
    // already cached
    if (err) {
      return this.extract(url, cache, { strip: 1 }, done);
    }

    // no refresh, so we can use this cache
    if (!refresh) return done();

    // otherwise, we need to remove it, to fetch it again
    rimraf(cache, function (err) {
      if (err) return cb(err);
      this.extract(url, cache, { strip: 1 }, done);
    }.bind(this));

  }.bind(this));

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.remoteDir"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>remoteDir (cache, cb)](#apidoc.element.generator-node-webkit.super_.prototype.remoteDir)
- description and source-code
```javascript
remoteDir = function (cache, cb) {
  var self = this;
  var files = this.expandFiles('**', { cwd: cache, dot: true });

  var remoteFs = {};
  remoteFs.cachePath = cache;

  // simple proxy to '.copy(source, destination)'
  remoteFs.copy = function copy(source, destination) {
    source = path.join(cache, source);
    self.copy(source, destination);
    return this;
  };

  // simple proxy to '.bulkCopy(source, destination)'
  remoteFs.bulkCopy = function copy(source, destination) {
    source = path.join(cache, source);
    self.bulkCopy(source, destination);
    return this;
  };

  // same as '.template(source, destination, data)'
  remoteFs.template = function template(source, destination, data) {
    data = data || self;
    destination = destination || source;
    source = path.join(cache, source);

    var body = self.engine(self.read(source), data);
    self.write(destination, body);
  };

  // same as '.template(source, destination)'
  remoteFs.directory = function directory(source, destination) {
    var root = self.sourceRoot();
    self.sourceRoot(cache);
    self.directory(source, destination);
    self.sourceRoot(root);
  };

  // simple proxy to '.bulkDirectory(source, destination)'
  remoteFs.bulkDirectory = function directory(source, destination) {
    var root = self.sourceRoot();
    self.sourceRoot(cache);
    self.bulkDirectory(source, destination);
    self.sourceRoot(root);
  };

  var fileLogger = { write: _.noop, warn: _.noop };

  // Set the file-utils environments
  // Set logger as a noop as logging is handled by the yeoman conflicter
  remoteFs.src = fileUtils.createEnv({
    base: cache,
    dest: this.destinationRoot(),
    logger: fileLogger
  });
  remoteFs.dest = fileUtils.createEnv({
    base: this.destinationRoot(),
    dest: cache,
    logger: fileLogger
  });

  remoteFs.dest.registerValidationFilter('collision', this.getCollisionFilter());
  remoteFs.src.registerValidationFilter('collision', this.getCollisionFilter());

  cb(null, remoteFs, files);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.removeScript"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>removeScript (html, scriptPath)](#apidoc.element.generator-node-webkit.super_.prototype.removeScript)
- description and source-code
```javascript
function removeScript(html, scriptPath) {
  return this.domUpdate(html, 'script[src$="' + scriptPath + '"]', '', 'd');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.removeStyle"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>removeStyle (html, path)](#apidoc.element.generator-node-webkit.super_.prototype.removeStyle)
- description and source-code
```javascript
function removeStyle(html, path) {
  return this.domUpdate(html, 'link[href$="' + path + '"]', '', 'd');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.rootGeneratorName"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>rootGeneratorName ()](#apidoc.element.generator-node-webkit.super_.prototype.rootGeneratorName)
- description and source-code
```javascript
rootGeneratorName = function () {
  var filepath = findup('package.json', { cwd: this.resolved });
  return filepath ? this.fs.readJSON(filepath).name : '*';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.rootGeneratorVersion"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>rootGeneratorVersion ()](#apidoc.element.generator-node-webkit.super_.prototype.rootGeneratorVersion)
- description and source-code
```javascript
rootGeneratorVersion = function () {
  var filepath = findup('package.json', { cwd: this.resolved });
  return filepath ? this.fs.readJSON(filepath).version : '0.0.0';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.run"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>run (cb)](#apidoc.element.generator-node-webkit.super_.prototype.run)
- description and source-code
```javascript
function run(cb) {
  cb = cb || function () {};

  var self = this;
  this._running = true;
  this.emit('run');

  var methods = Object.getOwnPropertyNames(Object.getPrototypeOf(this));
  var validMethods = methods.filter(methodIsValid);
  assert(validMethods.length, 'This Generator is empty. Add at least one method for it to run.');

  this.env.runLoop.once('end', function () {
    this.emit('end');
    cb();
  }.bind(this));

  // Ensure a prototype method is a candidate run by default
  function methodIsValid(name) {
    return name.charAt(0) !== '_' && name !== 'constructor';
  }

  function addMethod(method, methodName, queueName) {
    queueName = queueName || 'default';
    debug('Queueing ' + methodName + ' in ' + queueName);
    self.env.runLoop.add(queueName, function (completed) {
      debug('Running ' + methodName);
      var done = function (err) {
        if (err) self.emit('error', err);
        completed();
      };

      var running = false;
      self.async = function () {
        running = true;
        return done;
      };

      self.emit('method:' + methodName);
      try {
        method.apply(self, self.args);
        if (!running) return done();
      } catch (err) {
        debug('An error occured while running ' + methodName, err);
        self.emit('error', err);
      }
    });
  }

  function addInQueue(name) {
    var item = Object.getPrototypeOf(self)[name];
    var queueName = self.env.runLoop.queueNames.indexOf(name) >= 0 ? name : null;

    // Name points to a function; run it!
    if (_.isFunction(item)) {
      return addMethod(item, name, queueName);
    }

    // Not a queue hash; stop
    if (!queueName) return;

    // Run each queue items
    _.each(item, function (method, methodName) {
      if (!_.isFunction(method) || !methodIsValid(methodName)) return;
      addMethod(method, methodName, queueName);
    });
  }

  validMethods.forEach(addInQueue);

  var writeFiles = function () {
    this.env.runLoop.add('conflicts', this._writeFiles.bind(this), {
      once: 'write memory fs to disk'
    });
  }.bind(this);

  this.env.sharedFs.on('change', writeFiles);
  writeFiles();

  // Add the default conflicts handling
  this.env.runLoop.add('conflicts', function (done) {
    this.conflicter.resolve(function (err) {
      if (err) this.emit('error', err);
      done();
    }.bind(this));
  }.bind(this));

  this.on('end', function () {
    debug('Running the hooked generators');
    this.runHooks();
  });

  _.invoke(this._composedWith, 'run');

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.runHooks"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>runHooks (cb)](#apidoc.element.generator-node-webkit.super_.prototype.runHooks)
- description and source-code
```javascript
function runHooks(cb) {
  cb = _.isFunction(cb) ? cb : function () {};

  var setupInvoke = function (hook) {
    var resolved = this.defaultFor(hook.name);
    var options = _.clone(hook.options || this.options);
    options.args = _.clone(hook.args || this.args);

    return function (next) {
      this.invoke(resolved + (hook.as ? ':' + hook.as : ''), options, next);
    }.bind(this);
  }.bind(this);

  async.series(this._hooks.map(setupInvoke), cb);

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.runInstall"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>runInstall (installer, paths, options, cb)](#apidoc.element.generator-node-webkit.super_.prototype.runInstall)
- description and source-code
```javascript
runInstall = function (installer, paths, options, cb) {
  if (!cb && _.isFunction(options)) {
    cb = options;
    options = {};
  }

  options = options || {};
  cb = cb || function () {};
  paths = Array.isArray(paths) ? paths : (paths && paths.split(' ') || []);

  var args = ['install'].concat(paths).concat(dargs(options));

  this.env.runLoop.add('install', function (done) {
    this.emit(installer + 'Install', paths);
    this.spawnCommand(installer, args, options)
      .on('error', cb)
      .on('exit', function (err) {
        if (err === 127) {
          this.log.error(
            'Could not find ' + installer + '. Please install with ' +
            ''npm install -g ' + installer + ''.'
          );
        }
        this.emit(installer + 'Install:end', paths);
        cb(err);
        done();
      }.bind(this));
  }.bind(this), { once: installer + ' ' + args.join(' '), run: false });

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.sourceRoot"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>sourceRoot (rootPath)](#apidoc.element.generator-node-webkit.super_.prototype.sourceRoot)
- description and source-code
```javascript
sourceRoot = function (rootPath) {
  if (_.isString(rootPath)) {
    this._sourceRoot = path.resolve(rootPath);
  }

  return this._sourceRoot;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.spawnCommand"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>spawnCommand (command, args, opt)](#apidoc.element.generator-node-webkit.super_.prototype.spawnCommand)
- description and source-code
```javascript
function spawnCommand(command, args, opt) {
  opt = opt || {};
  return spawn(command, args, _.defaults(opt, { stdio: 'inherit' }));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.tarball"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>tarball (archive, destination, opts, cb)](#apidoc.element.generator-node-webkit.super_.prototype.tarball)
- description and source-code
```javascript
function _extract(archive, destination, opts, cb) {
  if (_.isFunction(opts) && !cb) {
    cb = opts;
    opts = { extract: true };
  }

  opts = _.assign({ extract: true }, opts);

  var log = this.log.write()
    .info('... Fetching %s ...', archive)
    .info(chalk.yellow('This might take a few moments'));

  var download = new Download(opts)
    .get(archive)
    .dest(destination)
    .use(function (res) {
      res.on('data', function () {
        log.write('.');
      });
    });

  download.run(function (err) {
    if (err) return cb(err);

    log.write().ok('Done in ' + destination).write();
    cb();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.template"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>template (source, destination, data, options)](#apidoc.element.generator-node-webkit.super_.prototype.template)
- description and source-code
```javascript
function template(source, destination, data, options) {
  if (!destination || !this.isPathAbsolute(destination)) {
    destination = path.join(
      this.destinationRoot(),
      this.engine(destination || source, data || this, options)
    );
  }

  if (!this.isPathAbsolute(source)) {
    source = path.join(
      this.sourceRoot(),
      this.engine(source, data || this, options)
    );
  }

  var body = this.engine(this.fs.read(source), data || this, options);

  // Using copy to keep the file mode of the previous file
  this.fs.copy(source, destination, {
    process: function () {
      return body;
    }
  });
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.templatePath"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>templatePath ()](#apidoc.element.generator-node-webkit.super_.prototype.templatePath)
- description and source-code
```javascript
templatePath = function () {
  var args = [this.sourceRoot()].concat(_.toArray(arguments));
  return path.join.apply(path, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.usage"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>usage ()](#apidoc.element.generator-node-webkit.super_.prototype.usage)
- description and source-code
```javascript
function usage() {
  var options = Object.keys(this._options).length ? '[options]' : '';
  var name = ' ' + this.options.namespace;
  var args = '';

  if (this._arguments.length) {
    args = this._arguments.map(formatArg).join(' ');
  }

  name = name.replace(/^yeoman:/, '');

  var out = 'yo' + name + ' ' + options + ' ' + args;

  if (this.description) {
    out += '\n\n' + this.description;
  }

  return out;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.write"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>write (filepath, content, writeFile)](#apidoc.element.generator-node-webkit.super_.prototype.write)
- description and source-code
```javascript
function write(filepath, content, writeFile) {
  this.fs.write(filepath, content);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype.writeFileFromString"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>writeFileFromString (html, filePath)](#apidoc.element.generator-node-webkit.super_.prototype.writeFileFromString)
- description and source-code
```javascript
function writeFileFromString(html, filePath) {
  fs.writeFileSync(path.resolve(filePath), html, 'utf8');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.generator-node-webkit.super_.prototype._"></a>[module generator-node-webkit.super_.prototype._](#apidoc.module.generator-node-webkit.super_.prototype._)

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._._"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype.</span>_ (value)](#apidoc.element.generator-node-webkit.super_.prototype._._)
- description and source-code
```javascript
function lodash(value) {
  // don't wrap if already wrapped, even if wrapped by a different 'lodash' constructor
  return (value && typeof value == 'object' && !isArray(value) && hasOwnProperty.call(value, '__wrapped__'))
   ? value
   : new lodashWrapper(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.after"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>after (n, func)](#apidoc.element.generator-node-webkit.super_.prototype._.after)
- description and source-code
```javascript
function after(n, func) {
  if (!isFunction(func)) {
    throw new TypeError;
  }
  return function() {
    if (--n < 1) {
      return func.apply(this, arguments);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.all"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>all (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.all)
- description and source-code
```javascript
function every(collection, callback, thisArg) {
  var result = true;
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      if (!(result = !!callback(collection[index], index, collection))) {
        break;
      }
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      return (result = !!callback(value, index, collection));
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.any"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>any (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.any)
- description and source-code
```javascript
function some(collection, callback, thisArg) {
  var result;
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      if ((result = callback(collection[index], index, collection))) {
        break;
      }
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      return !(result = callback(value, index, collection));
    });
  }
  return !!result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.assign"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>assign (object, source, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.assign)
- description and source-code
```javascript
assign = function (object, source, guard) {
  var index, iterable = object, result = iterable;
  if (!iterable) return result;
  var args = arguments,
      argsIndex = 0,
      argsLength = typeof guard == 'number' ? 2 : args.length;
  if (argsLength > 3 && typeof args[argsLength - 2] == 'function') {
    var callback = baseCreateCallback(args[--argsLength - 1], args[argsLength--], 2);
  } else if (argsLength > 2 && typeof args[argsLength - 1] == 'function') {
    callback = args[--argsLength];
  }
  while (++argsIndex < argsLength) {
    iterable = args[argsIndex];
    if (iterable && objectTypes[typeof iterable]) {
    var ownIndex = -1,
        ownProps = objectTypes[typeof iterable] && keys(iterable),
        length = ownProps ? ownProps.length : 0;

    while (++ownIndex < length) {
      index = ownProps[ownIndex];
      result[index] = callback ? callback(result[index], iterable[index]) : iterable[index];
    }
    }
  }
  return result
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.at"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>at (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.at)
- description and source-code
```javascript
function at(collection) {
  var args = arguments,
      index = -1,
      props = baseFlatten(args, true, false, 1),
      length = (args[2] && args[2][args[1]] === collection) ? 1 : props.length,
      result = Array(length);

  while(++index < length) {
    result[index] = collection[props[index]];
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.bind"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>bind (func, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.bind)
- description and source-code
```javascript
function bind(func, thisArg) {
  return arguments.length > 2
    ? createWrapper(func, 17, slice(arguments, 2), null, thisArg)
    : createWrapper(func, 1, null, null, thisArg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.bindAll"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>bindAll (object)](#apidoc.element.generator-node-webkit.super_.prototype._.bindAll)
- description and source-code
```javascript
function bindAll(object) {
  var funcs = arguments.length > 1 ? baseFlatten(arguments, true, false, 1) : functions(object),
      index = -1,
      length = funcs.length;

  while (++index < length) {
    var key = funcs[index];
    object[key] = createWrapper(object[key], 1, null, null, object);
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.bindKey"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>bindKey (object, key)](#apidoc.element.generator-node-webkit.super_.prototype._.bindKey)
- description and source-code
```javascript
function bindKey(object, key) {
  return arguments.length > 2
    ? createWrapper(key, 19, slice(arguments, 2), null, object)
    : createWrapper(key, 3, null, null, object);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.camelize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>camelize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.camelize)
- description and source-code
```javascript
camelize = function (str){
  return _s.trim(str).replace(/[-_\s]+(.)?/g, function(match, c){ return c ? c.toUpperCase() : ""; });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.capitalize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>capitalize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.capitalize)
- description and source-code
```javascript
capitalize = function (str){
  str = str == null ? '' : String(str);
  return str.charAt(0).toUpperCase() + str.slice(1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.center"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>center (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.center)
- description and source-code
```javascript
center = function (str, length, padStr) {
  return _s.pad(str, length, padStr, 'both');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.chain"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>chain (value)](#apidoc.element.generator-node-webkit.super_.prototype._.chain)
- description and source-code
```javascript
function chain(value) {
  value = new lodashWrapper(value);
  value.__chain__ = true;
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.chars"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>chars (str)](#apidoc.element.generator-node-webkit.super_.prototype._.chars)
- description and source-code
```javascript
chars = function (str) {
  if (str == null) return [];
  return String(str).split('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.chop"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>chop (str, step)](#apidoc.element.generator-node-webkit.super_.prototype._.chop)
- description and source-code
```javascript
chop = function (str, step){
  if (str == null) return [];
  str = String(str);
  step = ~~step;
  return step > 0 ? str.match(new RegExp('.{1,' + step + '}', 'g')) : [str];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.classify"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>classify (str)](#apidoc.element.generator-node-webkit.super_.prototype._.classify)
- description and source-code
```javascript
classify = function (str){
  return _s.capitalize(_s.camelize(String(str).replace(/[\W_]/g, ' ')).replace(/\s/g, ''));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.clean"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>clean (str)](#apidoc.element.generator-node-webkit.super_.prototype._.clean)
- description and source-code
```javascript
clean = function (str){
  return _s.strip(str).replace(/\s+/g, ' ');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.clone"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>clone (value, isDeep, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.clone)
- description and source-code
```javascript
function clone(value, isDeep, callback, thisArg) {
  // allows working with "Collections" methods without using their 'index'
  // and 'collection' arguments for 'isDeep' and 'callback'
  if (typeof isDeep != 'boolean' && isDeep != null) {
    thisArg = callback;
    callback = isDeep;
    isDeep = false;
  }
  return baseClone(value, isDeep, typeof callback == 'function' && baseCreateCallback(callback, thisArg, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.cloneDeep"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>cloneDeep (value, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.cloneDeep)
- description and source-code
```javascript
function cloneDeep(value, callback, thisArg) {
  return baseClone(value, true, typeof callback == 'function' && baseCreateCallback(callback, thisArg, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.collect"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>collect (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.collect)
- description and source-code
```javascript
function map(collection, callback, thisArg) {
  var index = -1,
      length = collection ? collection.length : 0;

  callback = lodash.createCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    var result = Array(length);
    while (++index < length) {
      result[index] = callback(collection[index], index, collection);
    }
  } else {
    result = [];
    forOwn(collection, function(value, key, collection) {
      result[++index] = callback(value, key, collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.compact"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>compact (array)](#apidoc.element.generator-node-webkit.super_.prototype._.compact)
- description and source-code
```javascript
function compact(array) {
  var index = -1,
      length = array ? array.length : 0,
      result = [];

  while (++index < length) {
    var value = array[index];
    if (value) {
      result.push(value);
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.compose"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>compose ()](#apidoc.element.generator-node-webkit.super_.prototype._.compose)
- description and source-code
```javascript
function compose() {
  var funcs = arguments,
      length = funcs.length;

  while (length--) {
    if (!isFunction(funcs[length])) {
      throw new TypeError;
    }
  }
  return function() {
    var args = arguments,
        length = funcs.length;

    while (length--) {
      args = [funcs[length].apply(this, args)];
    }
    return args[0];
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.constant"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>constant (value)](#apidoc.element.generator-node-webkit.super_.prototype._.constant)
- description and source-code
```javascript
function constant(value) {
  return function() {
    return value;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.contains"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>contains (collection, target, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.contains)
- description and source-code
```javascript
function contains(collection, target, fromIndex) {
  var index = -1,
      indexOf = getIndexOf(),
      length = collection ? collection.length : 0,
      result = false;

  fromIndex = (fromIndex < 0 ? nativeMax(0, length + fromIndex) : fromIndex) || 0;
  if (isArray(collection)) {
    result = indexOf(collection, target, fromIndex) > -1;
  } else if (typeof length == 'number') {
    result = (isString(collection) ? collection.indexOf(target, fromIndex) : indexOf(collection, target, fromIndex)) > -1;
  } else {
    forOwn(collection, function(value) {
      if (++index >= fromIndex) {
        return !(result = value === target);
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.count"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>count (str, substr)](#apidoc.element.generator-node-webkit.super_.prototype._.count)
- description and source-code
```javascript
count = function (str, substr){
  if (str == null || substr == null) return 0;

  str = String(str);
  substr = String(substr);

  var count = 0,
    pos = 0,
    length = substr.length;

  while (true) {
    pos = str.indexOf(substr, pos);
    if (pos === -1) break;
    count++;
    pos += length;
  }

  return count;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.countBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>countBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.countBy)
- description and source-code
```javascript
countBy = function (collection, callback, thisArg) {
  var result = {};
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      setter(result, value, callback(value, index, collection), collection);
    }
  } else {
    forOwn(collection, function(value, key, collection) {
      setter(result, value, callback(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.create"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>create (prototype, properties)](#apidoc.element.generator-node-webkit.super_.prototype._.create)
- description and source-code
```javascript
function create(prototype, properties) {
  var result = baseCreate(prototype);
  return properties ? assign(result, properties) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.createCallback"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>createCallback (func, thisArg, argCount)](#apidoc.element.generator-node-webkit.super_.prototype._.createCallback)
- description and source-code
```javascript
function createCallback(func, thisArg, argCount) {
  var type = typeof func;
  if (func == null || type == 'function') {
    return baseCreateCallback(func, thisArg, argCount);
  }
  // handle "_.pluck" style callback shorthands
  if (type != 'object') {
    return property(func);
  }
  var props = keys(func),
      key = props[0],
      a = func[key];

  // handle "_.where" style callback shorthands
  if (props.length == 1 && a === a && !isObject(a)) {
    // fast path the common case of providing an object with a single
    // property containing a primitive value
    return function(object) {
      var b = object[key];
      return a === b && (a !== 0 || (1 / a == 1 / b));
    };
  }
  return function(object) {
    var length = props.length,
        result = false;

    while (length--) {
      if (!(result = baseIsEqual(object[props[length]], func[props[length]], null, true))) {
        break;
      }
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.curry"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>curry (func, arity)](#apidoc.element.generator-node-webkit.super_.prototype._.curry)
- description and source-code
```javascript
function curry(func, arity) {
  arity = typeof arity == 'number' ? arity : (+arity || func.length);
  return createWrapper(func, 4, null, null, null, arity);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.dasherize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>dasherize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.dasherize)
- description and source-code
```javascript
dasherize = function (str){
  return _s.trim(str).replace(/([A-Z])/g, '-$1').replace(/[-_\s]+/g, '-').toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.debounce"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>debounce (func, wait, options)](#apidoc.element.generator-node-webkit.super_.prototype._.debounce)
- description and source-code
```javascript
function debounce(func, wait, options) {
  var args,
      maxTimeoutId,
      result,
      stamp,
      thisArg,
      timeoutId,
      trailingCall,
      lastCalled = 0,
      maxWait = false,
      trailing = true;

  if (!isFunction(func)) {
    throw new TypeError;
  }
  wait = nativeMax(0, wait) || 0;
  if (options === true) {
    var leading = true;
    trailing = false;
  } else if (isObject(options)) {
    leading = options.leading;
    maxWait = 'maxWait' in options && (nativeMax(wait, options.maxWait) || 0);
    trailing = 'trailing' in options ? options.trailing : trailing;
  }
  var delayed = function() {
    var remaining = wait - (now() - stamp);
    if (remaining <= 0) {
      if (maxTimeoutId) {
        clearTimeout(maxTimeoutId);
      }
      var isCalled = trailingCall;
      maxTimeoutId = timeoutId = trailingCall = undefined;
      if (isCalled) {
        lastCalled = now();
        result = func.apply(thisArg, args);
        if (!timeoutId && !maxTimeoutId) {
          args = thisArg = null;
        }
      }
    } else {
      timeoutId = setTimeout(delayed, remaining);
    }
  };

  var maxDelayed = function() {
    if (timeoutId) {
      clearTimeout(timeoutId);
    }
    maxTimeoutId = timeoutId = trailingCall = undefined;
    if (trailing || (maxWait !== wait)) {
      lastCalled = now();
      result = func.apply(thisArg, args);
      if (!timeoutId && !maxTimeoutId) {
        args = thisArg = null;
      }
    }
  };

  return function() {
    args = arguments;
    stamp = now();
    thisArg = this;
    trailingCall = trailing && (timeoutId || !leading);

    if (maxWait === false) {
      var leadingCall = leading && !timeoutId;
    } else {
      if (!maxTimeoutId && !leading) {
        lastCalled = stamp;
      }
      var remaining = maxWait - (stamp - lastCalled),
          isCalled = remaining <= 0;

      if (isCalled) {
        if (maxTimeoutId) {
          maxTimeoutId = clearTimeout(maxTimeoutId);
        }
        lastCalled = stamp;
        result = func.apply(thisArg, args);
      }
      else if (!maxTimeoutId) {
        maxTimeoutId = setTimeout(maxDelayed, remaining);
      }
    }
    if (isCalled && timeoutId) {
      timeoutId = clearTimeout(timeoutId);
    }
    else if (!timeoutId && wait !== maxWait) {
      timeoutId = setTimeout(delayed, wait);
    }
    if (leadingCall) {
      isCalled = true;
      result = func.apply(thisArg, args);
    }
    if (isCalled && !timeoutId && !maxTimeoutId) {
      args = thisArg = null;
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.defaults"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>defaults (object, source, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.defaults)
- description and source-code
```javascript
defaults = function (object, source, guard) {
  var index, iterable = object, result = iterable;
  if (!iterable) return result;
  var args = arguments,
      argsIndex = 0,
      argsLength = typeof guard == 'number' ? 2 : args.length;
  while (++argsIndex < argsLength) {
    iterable = args[argsIndex];
    if (iterable && objectTypes[typeof iterable]) {
    var ownIndex = -1,
        ownProps = objectTypes[typeof iterable] && keys(iterable),
        length = ownProps ? ownProps.length : 0;

    while (++ownIndex < length) {
      index = ownProps[ownIndex];
      if (typeof result[index] == 'undefined') result[index] = iterable[index];
    }
    }
  }
  return result
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.defer"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>defer (func)](#apidoc.element.generator-node-webkit.super_.prototype._.defer)
- description and source-code
```javascript
function defer(func) {
  if (!isFunction(func)) {
    throw new TypeError;
  }
  var args = slice(arguments, 1);
  return setTimeout(function() { func.apply(undefined, args); }, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.delay"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>delay (func, wait)](#apidoc.element.generator-node-webkit.super_.prototype._.delay)
- description and source-code
```javascript
function delay(func, wait) {
  if (!isFunction(func)) {
    throw new TypeError;
  }
  var args = slice(arguments, 2);
  return setTimeout(function() { func.apply(undefined, args); }, wait);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.detect"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>detect (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.detect)
- description and source-code
```javascript
function find(collection, callback, thisArg) {
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      if (callback(value, index, collection)) {
        return value;
      }
    }
  } else {
    var result;
    forOwn(collection, function(value, index, collection) {
      if (callback(value, index, collection)) {
        result = value;
        return false;
      }
    });
    return result;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.difference"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>difference (array)](#apidoc.element.generator-node-webkit.super_.prototype._.difference)
- description and source-code
```javascript
function difference(array) {
  return baseDifference(array, baseFlatten(arguments, true, true, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.drop"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>drop (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.drop)
- description and source-code
```javascript
function rest(array, callback, thisArg) {
  if (typeof callback != 'number' && callback != null) {
    var n = 0,
        index = -1,
        length = array ? array.length : 0;

    callback = lodash.createCallback(callback, thisArg, 3);
    while (++index < length && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = (callback == null || thisArg) ? 1 : nativeMax(0, callback);
  }
  return slice(array, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.each"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>each (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.each)
- description and source-code
```javascript
function forEach(collection, callback, thisArg) {
  var index = -1,
      length = collection ? collection.length : 0;

  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    while (++index < length) {
      if (callback(collection[index], index, collection) === false) {
        break;
      }
    }
  } else {
    forOwn(collection, callback);
  }
  return collection;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.eachRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>eachRight (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.eachRight)
- description and source-code
```javascript
function forEachRight(collection, callback, thisArg) {
  var length = collection ? collection.length : 0;
  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    while (length--) {
      if (callback(collection[length], length, collection) === false) {
        break;
      }
    }
  } else {
    var props = keys(collection);
    length = props.length;
    forOwn(collection, function(value, key, collection) {
      key = props ? props[--length] : --length;
      return callback(collection[key], key, collection);
    });
  }
  return collection;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.endsWith"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>endsWith (str, ends)](#apidoc.element.generator-node-webkit.super_.prototype._.endsWith)
- description and source-code
```javascript
endsWith = function (str, ends){
  if (ends === '') return true;
  if (str == null || ends == null) return false;
  str = String(str); ends = String(ends);
  return str.length >= ends.length && str.slice(str.length - ends.length) === ends;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.escape"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>escape (string)](#apidoc.element.generator-node-webkit.super_.prototype._.escape)
- description and source-code
```javascript
function escape(string) {
  return string == null ? '' : String(string).replace(reUnescapedHtml, escapeHtmlChar);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.escapeHTML"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>escapeHTML (str)](#apidoc.element.generator-node-webkit.super_.prototype._.escapeHTML)
- description and source-code
```javascript
escapeHTML = function (str) {
  if (str == null) return '';
  return String(str).replace(/[&<>"']/g, function(m){ return '&' + reversedEscapeChars[m] + ';'; });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.escapeRegExp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>escapeRegExp (str)](#apidoc.element.generator-node-webkit.super_.prototype._.escapeRegExp)
- description and source-code
```javascript
escapeRegExp = function (str){
  if (str == null) return '';
  return String(str).replace(/([.*+?^=!:${}()|[\]\/\\])/g, '\\$1');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.every"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>every (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.every)
- description and source-code
```javascript
function every(collection, callback, thisArg) {
  var result = true;
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      if (!(result = !!callback(collection[index], index, collection))) {
        break;
      }
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      return (result = !!callback(value, index, collection));
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.exports"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>exports ()](#apidoc.element.generator-node-webkit.super_.prototype._.exports)
- description and source-code
```javascript
exports = function () {
  var result = {};

  for (var prop in this) {
    if (!this.hasOwnProperty(prop) || prop.match(/^(?:include|contains|reverse)$/)) continue;
    result[prop] = this[prop];
  }

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.extend"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>extend (object, source, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.extend)
- description and source-code
```javascript
extend = function (object, source, guard) {
  var index, iterable = object, result = iterable;
  if (!iterable) return result;
  var args = arguments,
      argsIndex = 0,
      argsLength = typeof guard == 'number' ? 2 : args.length;
  if (argsLength > 3 && typeof args[argsLength - 2] == 'function') {
    var callback = baseCreateCallback(args[--argsLength - 1], args[argsLength--], 2);
  } else if (argsLength > 2 && typeof args[argsLength - 1] == 'function') {
    callback = args[--argsLength];
  }
  while (++argsIndex < argsLength) {
    iterable = args[argsIndex];
    if (iterable && objectTypes[typeof iterable]) {
    var ownIndex = -1,
        ownProps = objectTypes[typeof iterable] && keys(iterable),
        length = ownProps ? ownProps.length : 0;

    while (++ownIndex < length) {
      index = ownProps[ownIndex];
      result[index] = callback ? callback(result[index], iterable[index]) : iterable[index];
    }
    }
  }
  return result
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.filter"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>filter (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.filter)
- description and source-code
```javascript
function filter(collection, callback, thisArg) {
  var result = [];
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      if (callback(value, index, collection)) {
        result.push(value);
      }
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      if (callback(value, index, collection)) {
        result.push(value);
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.find"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>find (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.find)
- description and source-code
```javascript
function find(collection, callback, thisArg) {
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      if (callback(value, index, collection)) {
        return value;
      }
    }
  } else {
    var result;
    forOwn(collection, function(value, index, collection) {
      if (callback(value, index, collection)) {
        result = value;
        return false;
      }
    });
    return result;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.findIndex"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findIndex (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findIndex)
- description and source-code
```javascript
function findIndex(array, callback, thisArg) {
  var index = -1,
      length = array ? array.length : 0;

  callback = lodash.createCallback(callback, thisArg, 3);
  while (++index < length) {
    if (callback(array[index], index, array)) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.findKey"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findKey (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findKey)
- description and source-code
```javascript
function findKey(object, callback, thisArg) {
  var result;
  callback = lodash.createCallback(callback, thisArg, 3);
  forOwn(object, function(value, key, object) {
    if (callback(value, key, object)) {
      result = key;
      return false;
    }
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.findLast"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findLast (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findLast)
- description and source-code
```javascript
function findLast(collection, callback, thisArg) {
  var result;
  callback = lodash.createCallback(callback, thisArg, 3);
  forEachRight(collection, function(value, index, collection) {
    if (callback(value, index, collection)) {
      result = value;
      return false;
    }
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.findLastIndex"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findLastIndex (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findLastIndex)
- description and source-code
```javascript
function findLastIndex(array, callback, thisArg) {
  var length = array ? array.length : 0;
  callback = lodash.createCallback(callback, thisArg, 3);
  while (length--) {
    if (callback(array[length], length, array)) {
      return length;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.findLastKey"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findLastKey (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findLastKey)
- description and source-code
```javascript
function findLastKey(object, callback, thisArg) {
  var result;
  callback = lodash.createCallback(callback, thisArg, 3);
  forOwnRight(object, function(value, key, object) {
    if (callback(value, key, object)) {
      result = key;
      return false;
    }
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.findWhere"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>findWhere (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.findWhere)
- description and source-code
```javascript
function find(collection, callback, thisArg) {
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      if (callback(value, index, collection)) {
        return value;
      }
    }
  } else {
    var result;
    forOwn(collection, function(value, index, collection) {
      if (callback(value, index, collection)) {
        result = value;
        return false;
      }
    });
    return result;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.first"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>first (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.first)
- description and source-code
```javascript
function first(array, callback, thisArg) {
  var n = 0,
      length = array ? array.length : 0;

  if (typeof callback != 'number' && callback != null) {
    var index = -1;
    callback = lodash.createCallback(callback, thisArg, 3);
    while (++index < length && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = callback;
    if (n == null || thisArg) {
      return array ? array[0] : undefined;
    }
  }
  return slice(array, 0, nativeMin(nativeMax(0, n), length));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.flatten"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>flatten (array, isShallow, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.flatten)
- description and source-code
```javascript
function flatten(array, isShallow, callback, thisArg) {
  // juggle arguments
  if (typeof isShallow != 'boolean' && isShallow != null) {
    thisArg = callback;
    callback = (typeof isShallow != 'function' && thisArg && thisArg[isShallow] === array) ? null : isShallow;
    isShallow = false;
  }
  if (callback != null) {
    array = map(array, callback, thisArg);
  }
  return baseFlatten(array, isShallow);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.foldl"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>foldl (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.foldl)
- description and source-code
```javascript
function reduce(collection, callback, accumulator, thisArg) {
  if (!collection) return accumulator;
  var noaccum = arguments.length < 3;
  callback = lodash.createCallback(callback, thisArg, 4);

  var index = -1,
      length = collection.length;

  if (typeof length == 'number') {
    if (noaccum) {
      accumulator = collection[++index];
    }
    while (++index < length) {
      accumulator = callback(accumulator, collection[index], index, collection);
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      accumulator = noaccum
        ? (noaccum = false, value)
        : callback(accumulator, value, index, collection)
    });
  }
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.foldr"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>foldr (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.foldr)
- description and source-code
```javascript
function reduceRight(collection, callback, accumulator, thisArg) {
  var noaccum = arguments.length < 3;
  callback = lodash.createCallback(callback, thisArg, 4);
  forEachRight(collection, function(value, index, collection) {
    accumulator = noaccum
      ? (noaccum = false, value)
      : callback(accumulator, value, index, collection);
  });
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.forEach"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forEach (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forEach)
- description and source-code
```javascript
function forEach(collection, callback, thisArg) {
  var index = -1,
      length = collection ? collection.length : 0;

  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    while (++index < length) {
      if (callback(collection[index], index, collection) === false) {
        break;
      }
    }
  } else {
    forOwn(collection, callback);
  }
  return collection;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.forEachRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forEachRight (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forEachRight)
- description and source-code
```javascript
function forEachRight(collection, callback, thisArg) {
  var length = collection ? collection.length : 0;
  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    while (length--) {
      if (callback(collection[length], length, collection) === false) {
        break;
      }
    }
  } else {
    var props = keys(collection);
    length = props.length;
    forOwn(collection, function(value, key, collection) {
      key = props ? props[--length] : --length;
      return callback(collection[key], key, collection);
    });
  }
  return collection;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.forIn"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forIn (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forIn)
- description and source-code
```javascript
forIn = function (collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
  if (!objectTypes[typeof iterable]) return result;
  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
    for (index in iterable) {
      if (callback(iterable[index], index, collection) === false) return result;
    }
  return result
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.forInRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forInRight (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forInRight)
- description and source-code
```javascript
function forInRight(object, callback, thisArg) {
  var pairs = [];

  forIn(object, function(value, key) {
    pairs.push(key, value);
  });

  var length = pairs.length;
  callback = baseCreateCallback(callback, thisArg, 3);
  while (length--) {
    if (callback(pairs[length--], pairs[length], object) === false) {
      break;
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.forOwn"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forOwn (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forOwn)
- description and source-code
```javascript
forOwn = function (collection, callback, thisArg) {
  var index, iterable = collection, result = iterable;
  if (!iterable) return result;
  if (!objectTypes[typeof iterable]) return result;
  callback = callback && typeof thisArg == 'undefined' ? callback : baseCreateCallback(callback, thisArg, 3);
    var ownIndex = -1,
        ownProps = objectTypes[typeof iterable] && keys(iterable),
        length = ownProps ? ownProps.length : 0;

    while (++ownIndex < length) {
      index = ownProps[ownIndex];
      if (callback(iterable[index], index, collection) === false) return result;
    }
  return result
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.forOwnRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>forOwnRight (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.forOwnRight)
- description and source-code
```javascript
function forOwnRight(object, callback, thisArg) {
  var props = keys(object),
      length = props.length;

  callback = baseCreateCallback(callback, thisArg, 3);
  while (length--) {
    var key = props[length];
    if (callback(object[key], key, object) === false) {
      break;
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.functions"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>functions (object)](#apidoc.element.generator-node-webkit.super_.prototype._.functions)
- description and source-code
```javascript
function functions(object) {
  var result = [];
  forIn(object, function(value, key) {
    if (isFunction(value)) {
      result.push(key);
    }
  });
  return result.sort();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.groupBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>groupBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.groupBy)
- description and source-code
```javascript
groupBy = function (collection, callback, thisArg) {
  var result = {};
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      setter(result, value, callback(value, index, collection), collection);
    }
  } else {
    forOwn(collection, function(value, key, collection) {
      setter(result, value, callback(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.has"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>has (object, key)](#apidoc.element.generator-node-webkit.super_.prototype._.has)
- description and source-code
```javascript
function has(object, key) {
  return object ? hasOwnProperty.call(object, key) : false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.head"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>head (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.head)
- description and source-code
```javascript
function first(array, callback, thisArg) {
  var n = 0,
      length = array ? array.length : 0;

  if (typeof callback != 'number' && callback != null) {
    var index = -1;
    callback = lodash.createCallback(callback, thisArg, 3);
    while (++index < length && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = callback;
    if (n == null || thisArg) {
      return array ? array[0] : undefined;
    }
  }
  return slice(array, 0, nativeMin(nativeMax(0, n), length));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.humanize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>humanize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.humanize)
- description and source-code
```javascript
humanize = function (str){
  return _s.capitalize(_s.underscored(str).replace(/_id$/,'').replace(/_/g, ' '));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.identity"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>identity (value)](#apidoc.element.generator-node-webkit.super_.prototype._.identity)
- description and source-code
```javascript
function identity(value) {
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.include"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>include (collection, target, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.include)
- description and source-code
```javascript
function contains(collection, target, fromIndex) {
  var index = -1,
      indexOf = getIndexOf(),
      length = collection ? collection.length : 0,
      result = false;

  fromIndex = (fromIndex < 0 ? nativeMax(0, length + fromIndex) : fromIndex) || 0;
  if (isArray(collection)) {
    result = indexOf(collection, target, fromIndex) > -1;
  } else if (typeof length == 'number') {
    result = (isString(collection) ? collection.indexOf(target, fromIndex) : indexOf(collection, target, fromIndex)) > -1;
  } else {
    forOwn(collection, function(value) {
      if (++index >= fromIndex) {
        return !(result = value === target);
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.indexBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>indexBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.indexBy)
- description and source-code
```javascript
indexBy = function (collection, callback, thisArg) {
  var result = {};
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      setter(result, value, callback(value, index, collection), collection);
    }
  } else {
    forOwn(collection, function(value, key, collection) {
      setter(result, value, callback(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.indexOf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>indexOf (array, value, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.indexOf)
- description and source-code
```javascript
function indexOf(array, value, fromIndex) {
  if (typeof fromIndex == 'number') {
    var length = array ? array.length : 0;
    fromIndex = (fromIndex < 0 ? nativeMax(0, length + fromIndex) : fromIndex || 0);
  } else if (fromIndex) {
    var index = sortedIndex(array, value);
    return array[index] === value ? index : -1;
  }
  return baseIndexOf(array, value, fromIndex);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.initial"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>initial (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.initial)
- description and source-code
```javascript
function initial(array, callback, thisArg) {
  var n = 0,
      length = array ? array.length : 0;

  if (typeof callback != 'number' && callback != null) {
    var index = length;
    callback = lodash.createCallback(callback, thisArg, 3);
    while (index-- && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = (callback == null || thisArg) ? 1 : callback || n;
  }
  return slice(array, 0, nativeMin(nativeMax(0, length - n), length));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.inject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>inject (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.inject)
- description and source-code
```javascript
function reduce(collection, callback, accumulator, thisArg) {
  if (!collection) return accumulator;
  var noaccum = arguments.length < 3;
  callback = lodash.createCallback(callback, thisArg, 4);

  var index = -1,
      length = collection.length;

  if (typeof length == 'number') {
    if (noaccum) {
      accumulator = collection[++index];
    }
    while (++index < length) {
      accumulator = callback(accumulator, collection[index], index, collection);
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      accumulator = noaccum
        ? (noaccum = false, value)
        : callback(accumulator, value, index, collection)
    });
  }
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.insert"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>insert (str, i, substr)](#apidoc.element.generator-node-webkit.super_.prototype._.insert)
- description and source-code
```javascript
insert = function (str, i, substr){
  return _s.splice(str, i, 0, substr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.intersection"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>intersection ()](#apidoc.element.generator-node-webkit.super_.prototype._.intersection)
- description and source-code
```javascript
function intersection() {
  var args = [],
      argsIndex = -1,
      argsLength = arguments.length,
      caches = getArray(),
      indexOf = getIndexOf(),
      trustIndexOf = indexOf === baseIndexOf,
      seen = getArray();

  while (++argsIndex < argsLength) {
    var value = arguments[argsIndex];
    if (isArray(value) || isArguments(value)) {
      args.push(value);
      caches.push(trustIndexOf && value.length >= largeArraySize &&
        createCache(argsIndex ? args[argsIndex] : seen));
    }
  }
  var array = args[0],
      index = -1,
      length = array ? array.length : 0,
      result = [];

  outer:
  while (++index < length) {
    var cache = caches[0];
    value = array[index];

    if ((cache ? cacheIndexOf(cache, value) : indexOf(seen, value)) < 0) {
      argsIndex = argsLength;
      (cache || seen).push(value);
      while (--argsIndex) {
        cache = caches[argsIndex];
        if ((cache ? cacheIndexOf(cache, value) : indexOf(args[argsIndex], value)) < 0) {
          continue outer;
        }
      }
      result.push(value);
    }
  }
  while (argsLength--) {
    cache = caches[argsLength];
    if (cache) {
      releaseObject(cache);
    }
  }
  releaseArray(caches);
  releaseArray(seen);
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.invert"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>invert (object)](#apidoc.element.generator-node-webkit.super_.prototype._.invert)
- description and source-code
```javascript
function invert(object) {
  var index = -1,
      props = keys(object),
      length = props.length,
      result = {};

  while (++index < length) {
    var key = props[index];
    result[object[key]] = key;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.invoke"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>invoke (collection, methodName)](#apidoc.element.generator-node-webkit.super_.prototype._.invoke)
- description and source-code
```javascript
function invoke(collection, methodName) {
  var args = slice(arguments, 2),
      index = -1,
      isFunc = typeof methodName == 'function',
      length = collection ? collection.length : 0,
      result = Array(typeof length == 'number' ? length : 0);

  forEach(collection, function(value) {
    result[++index] = (isFunc ? methodName : value[methodName]).apply(value, args);
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isArguments"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isArguments (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isArguments)
- description and source-code
```javascript
function isArguments(value) {
  return value && typeof value == 'object' && typeof value.length == 'number' &&
    toString.call(value) == argsClass || false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isArray"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isArray ()](#apidoc.element.generator-node-webkit.super_.prototype._.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isBlank"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isBlank (str)](#apidoc.element.generator-node-webkit.super_.prototype._.isBlank)
- description and source-code
```javascript
isBlank = function (str){
  if (str == null) str = '';
  return (/^\s*$/).test(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isBoolean"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isBoolean (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isBoolean)
- description and source-code
```javascript
function isBoolean(value) {
  return value === true || value === false ||
    value && typeof value == 'object' && toString.call(value) == boolClass || false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isDate"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isDate (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isDate)
- description and source-code
```javascript
function isDate(value) {
  return value && typeof value == 'object' && toString.call(value) == dateClass || false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isElement"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isElement (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isElement)
- description and source-code
```javascript
function isElement(value) {
  return value && value.nodeType === 1 || false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isEmpty"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isEmpty (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isEmpty)
- description and source-code
```javascript
function isEmpty(value) {
  var result = true;
  if (!value) {
    return result;
  }
  var className = toString.call(value),
      length = value.length;

  if ((className == arrayClass || className == stringClass || className == argsClass ) ||
      (className == objectClass && typeof length == 'number' && isFunction(value.splice))) {
    return !length;
  }
  forOwn(value, function() {
    return (result = false);
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isEqual"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isEqual (a, b, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.isEqual)
- description and source-code
```javascript
function isEqual(a, b, callback, thisArg) {
  return baseIsEqual(a, b, typeof callback == 'function' && baseCreateCallback(callback, thisArg, 2));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isFinite"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isFinite (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isFinite)
- description and source-code
```javascript
function isFinite(value) {
  return nativeIsFinite(value) && !nativeIsNaN(parseFloat(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isFunction"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isFunction (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  return typeof value == 'function';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isNaN"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isNaN (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isNaN)
- description and source-code
```javascript
function isNaN(value) {
  // 'NaN' as a primitive is the only value that is not equal to itself
  // (perform the [[Class]] check first to avoid errors with some host objects in IE)
  return isNumber(value) && value != +value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isNull"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isNull (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isNull)
- description and source-code
```javascript
function isNull(value) {
  return value === null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isNumber"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isNumber (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isNumber)
- description and source-code
```javascript
function isNumber(value) {
  return typeof value == 'number' ||
    value && typeof value == 'object' && toString.call(value) == numberClass || false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isObject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isObject (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isObject)
- description and source-code
```javascript
function isObject(value) {
  // check if the value is the ECMAScript language type of Object
  // http://es5.github.io/#x8
  // and avoid a V8 bug
  // http://code.google.com/p/v8/issues/detail?id=2291
  return !!(value && objectTypes[typeof value]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isPlainObject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isPlainObject (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isPlainObject)
- description and source-code
```javascript
isPlainObject = function (value) {
  if (!(value && toString.call(value) == objectClass)) {
    return false;
  }
  var valueOf = value.valueOf,
      objProto = isNative(valueOf) && (objProto = getPrototypeOf(valueOf)) && getPrototypeOf(objProto);

  return objProto
    ? (value == objProto || getPrototypeOf(value) == objProto)
    : shimIsPlainObject(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isRegExp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isRegExp (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isRegExp)
- description and source-code
```javascript
function isRegExp(value) {
  return value && typeof value == 'object' && toString.call(value) == regexpClass || false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isString"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isString (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isString)
- description and source-code
```javascript
function isString(value) {
  return typeof value == 'string' ||
    value && typeof value == 'object' && toString.call(value) == stringClass || false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.isUndefined"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>isUndefined (value)](#apidoc.element.generator-node-webkit.super_.prototype._.isUndefined)
- description and source-code
```javascript
function isUndefined(value) {
  return typeof value == 'undefined';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.join"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>join ()](#apidoc.element.generator-node-webkit.super_.prototype._.join)
- description and source-code
```javascript
join = function () {
  var args = slice.call(arguments),
    separator = args.shift();

  if (separator == null) separator = '';

  return args.join(separator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.keys"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>keys (object)](#apidoc.element.generator-node-webkit.super_.prototype._.keys)
- description and source-code
```javascript
keys = function (object) {
  if (!isObject(object)) {
    return [];
  }
  return nativeKeys(object);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.last"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>last (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.last)
- description and source-code
```javascript
function last(array, callback, thisArg) {
  var n = 0,
      length = array ? array.length : 0;

  if (typeof callback != 'number' && callback != null) {
    var index = length;
    callback = lodash.createCallback(callback, thisArg, 3);
    while (index-- && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = callback;
    if (n == null || thisArg) {
      return array ? array[length - 1] : undefined;
    }
  }
  return slice(array, nativeMax(0, length - n));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.lastIndexOf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.generator-node-webkit.super_.prototype._.lastIndexOf)
- description and source-code
```javascript
function lastIndexOf(array, value, fromIndex) {
  var index = array ? array.length : 0;
  if (typeof fromIndex == 'number') {
    index = (fromIndex < 0 ? nativeMax(0, index + fromIndex) : nativeMin(fromIndex, index - 1)) + 1;
  }
  while (index--) {
    if (array[index] === value) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.levenshtein"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>levenshtein (str1, str2)](#apidoc.element.generator-node-webkit.super_.prototype._.levenshtein)
- description and source-code
```javascript
levenshtein = function (str1, str2) {
  if (str1 == null && str2 == null) return 0;
  if (str1 == null) return String(str2).length;
  if (str2 == null) return String(str1).length;

  str1 = String(str1); str2 = String(str2);

  var current = [], prev, value;

  for (var i = 0; i <= str2.length; i++)
    for (var j = 0; j <= str1.length; j++) {
      if (i && j)
        if (str1.charAt(j - 1) === str2.charAt(i - 1))
          value = prev;
        else
          value = Math.min(current[j], current[j - 1], prev) + 1;
      else
        value = i + j;

      prev = current[j];
      current[j] = value;
    }

  return current.pop();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.lines"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lines (str)](#apidoc.element.generator-node-webkit.super_.prototype._.lines)
- description and source-code
```javascript
lines = function (str) {
  if (str == null) return [];
  return String(str).split("\n");
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.ljust"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>ljust (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.ljust)
- description and source-code
```javascript
ljust = function (str, length, padStr) {
  return _s.pad(str, length, padStr, 'right');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.lpad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lpad (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.lpad)
- description and source-code
```javascript
lpad = function (str, length, padStr) {
  return _s.pad(str, length, padStr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.lrpad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lrpad (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.lrpad)
- description and source-code
```javascript
lrpad = function (str, length, padStr) {
  return _s.pad(str, length, padStr, 'both');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.lstrip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>lstrip (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.lstrip)
- description and source-code
```javascript
lstrip = function (str, characters){
  if (str == null) return '';
  if (!characters && nativeTrimLeft) return nativeTrimLeft.call(str);
  characters = defaultToWhiteSpace(characters);
  return String(str).replace(new RegExp('^' + characters + '+'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.ltrim"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>ltrim (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.ltrim)
- description and source-code
```javascript
ltrim = function (str, characters){
  if (str == null) return '';
  if (!characters && nativeTrimLeft) return nativeTrimLeft.call(str);
  characters = defaultToWhiteSpace(characters);
  return String(str).replace(new RegExp('^' + characters + '+'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.map"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>map (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.map)
- description and source-code
```javascript
function map(collection, callback, thisArg) {
  var index = -1,
      length = collection ? collection.length : 0;

  callback = lodash.createCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    var result = Array(length);
    while (++index < length) {
      result[index] = callback(collection[index], index, collection);
    }
  } else {
    result = [];
    forOwn(collection, function(value, key, collection) {
      result[++index] = callback(value, key, collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.mapValues"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>mapValues (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.mapValues)
- description and source-code
```javascript
function mapValues(object, callback, thisArg) {
  var result = {};
  callback = lodash.createCallback(callback, thisArg, 3);

  forOwn(object, function(value, key, object) {
    result[key] = callback(value, key, object);
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.max"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>max (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.max)
- description and source-code
```javascript
function max(collection, callback, thisArg) {
  var computed = -Infinity,
      result = computed;

  // allows working with functions like '_.map' without using
  // their 'index' argument as a callback
  if (typeof callback != 'function' && thisArg && thisArg[callback] === collection) {
    callback = null;
  }
  if (callback == null && isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      if (value > result) {
        result = value;
      }
    }
  } else {
    callback = (callback == null && isString(collection))
      ? charAtCallback
      : lodash.createCallback(callback, thisArg, 3);

    forEach(collection, function(value, index, collection) {
      var current = callback(value, index, collection);
      if (current > computed) {
        computed = current;
        result = value;
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.memoize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>memoize (func, resolver)](#apidoc.element.generator-node-webkit.super_.prototype._.memoize)
- description and source-code
```javascript
function memoize(func, resolver) {
  if (!isFunction(func)) {
    throw new TypeError;
  }
  var memoized = function() {
    var cache = memoized.cache,
        key = resolver ? resolver.apply(this, arguments) : keyPrefix + arguments[0];

    return hasOwnProperty.call(cache, key)
      ? cache[key]
      : (cache[key] = func.apply(this, arguments));
  }
  memoized.cache = {};
  return memoized;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.merge"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>merge (object)](#apidoc.element.generator-node-webkit.super_.prototype._.merge)
- description and source-code
```javascript
function merge(object) {
  var args = arguments,
      length = 2;

  if (!isObject(object)) {
    return object;
  }
  // allows working with '_.reduce' and '_.reduceRight' without using
  // their 'index' and 'collection' arguments
  if (typeof args[2] != 'number') {
    length = args.length;
  }
  if (length > 3 && typeof args[length - 2] == 'function') {
    var callback = baseCreateCallback(args[--length - 1], args[length--], 2);
  } else if (length > 2 && typeof args[length - 1] == 'function') {
    callback = args[--length];
  }
  var sources = slice(arguments, 1, length),
      index = -1,
      stackA = getArray(),
      stackB = getArray();

  while (++index < length) {
    baseMerge(object, sources[index], callback, stackA, stackB);
  }
  releaseArray(stackA);
  releaseArray(stackB);
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.methods"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>methods (object)](#apidoc.element.generator-node-webkit.super_.prototype._.methods)
- description and source-code
```javascript
function functions(object) {
  var result = [];
  forIn(object, function(value, key) {
    if (isFunction(value)) {
      result.push(key);
    }
  });
  return result.sort();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.min"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>min (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.min)
- description and source-code
```javascript
function min(collection, callback, thisArg) {
  var computed = Infinity,
      result = computed;

  // allows working with functions like '_.map' without using
  // their 'index' argument as a callback
  if (typeof callback != 'function' && thisArg && thisArg[callback] === collection) {
    callback = null;
  }
  if (callback == null && isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      if (value < result) {
        result = value;
      }
    }
  } else {
    callback = (callback == null && isString(collection))
      ? charAtCallback
      : lodash.createCallback(callback, thisArg, 3);

    forEach(collection, function(value, index, collection) {
      var current = callback(value, index, collection);
      if (current < computed) {
        computed = current;
        result = value;
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.mixin"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>mixin (object, source, options)](#apidoc.element.generator-node-webkit.super_.prototype._.mixin)
- description and source-code
```javascript
function mixin(object, source, options) {
  var chain = true,
      methodNames = source && functions(source);

  if (!source || (!options && !methodNames.length)) {
    if (options == null) {
      options = source;
    }
    ctor = lodashWrapper;
    source = object;
    object = lodash;
    methodNames = functions(source);
  }
  if (options === false) {
    chain = false;
  } else if (isObject(options) && 'chain' in options) {
    chain = options.chain;
  }
  var ctor = object,
      isFunc = isFunction(ctor);

  forEach(methodNames, function(methodName) {
    var func = object[methodName] = source[methodName];
    if (isFunc) {
      ctor.prototype[methodName] = function() {
        var chainAll = this.__chain__,
            value = this.__wrapped__,
            args = [value];

        push.apply(args, arguments);
        var result = func.apply(object, args);
        if (chain || chainAll) {
          if (value === result && isObject(result)) {
            return this;
          }
          result = new ctor(result);
          result.__chain__ = chainAll;
        }
        return result;
      };
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.naturalCmp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>naturalCmp (str1, str2)](#apidoc.element.generator-node-webkit.super_.prototype._.naturalCmp)
- description and source-code
```javascript
naturalCmp = function (str1, str2){
  if (str1 == str2) return 0;
  if (!str1) return -1;
  if (!str2) return 1;

  var cmpRegex = /(\.\d+)|(\d+)|(\D+)/g,
    tokens1 = String(str1).toLowerCase().match(cmpRegex),
    tokens2 = String(str2).toLowerCase().match(cmpRegex),
    count = Math.min(tokens1.length, tokens2.length);

  for(var i = 0; i < count; i++) {
    var a = tokens1[i], b = tokens2[i];

    if (a !== b){
      var num1 = parseInt(a, 10);
      if (!isNaN(num1)){
        var num2 = parseInt(b, 10);
        if (!isNaN(num2) && num1 - num2)
          return num1 - num2;
      }
      return a < b ? -1 : 1;
    }
  }

  if (tokens1.length === tokens2.length)
    return tokens1.length - tokens2.length;

  return str1 < str2 ? -1 : 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.noConflict"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>noConflict ()](#apidoc.element.generator-node-webkit.super_.prototype._.noConflict)
- description and source-code
```javascript
function noConflict() {
  context._ = oldDash;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.noop"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>noop ()](#apidoc.element.generator-node-webkit.super_.prototype._.noop)
- description and source-code
```javascript
function noop() {
  // no operation performed
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.now"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>now ()](#apidoc.element.generator-node-webkit.super_.prototype._.now)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.numberFormat"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>numberFormat (number, dec, dsep, tsep)](#apidoc.element.generator-node-webkit.super_.prototype._.numberFormat)
- description and source-code
```javascript
numberFormat = function (number, dec, dsep, tsep) {
  if (isNaN(number) || number == null) return '';

  number = number.toFixed(~~dec);
  tsep = typeof tsep == 'string' ? tsep : ',';

  var parts = number.split('.'), fnums = parts[0],
    decimals = parts[1] ? (dsep || '.') + parts[1] : '';

  return fnums.replace(/(\d)(?=(?:\d{3})+$)/g, '$1' + tsep) + decimals;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.object"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>object (keys, values)](#apidoc.element.generator-node-webkit.super_.prototype._.object)
- description and source-code
```javascript
function zipObject(keys, values) {
  var index = -1,
      length = keys ? keys.length : 0,
      result = {};

  if (!values && length && !isArray(keys[0])) {
    values = [];
  }
  while (++index < length) {
    var key = keys[index];
    if (values) {
      result[key] = values[index];
    } else if (key) {
      result[key[0]] = key[1];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.omit"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>omit (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.omit)
- description and source-code
```javascript
function omit(object, callback, thisArg) {
  var result = {};
  if (typeof callback != 'function') {
    var props = [];
    forIn(object, function(value, key) {
      props.push(key);
    });
    props = baseDifference(props, baseFlatten(arguments, true, false, 1));

    var index = -1,
        length = props.length;

    while (++index < length) {
      var key = props[index];
      result[key] = object[key];
    }
  } else {
    callback = lodash.createCallback(callback, thisArg, 3);
    forIn(object, function(value, key, object) {
      if (!callback(value, key, object)) {
        result[key] = value;
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.once"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>once (func)](#apidoc.element.generator-node-webkit.super_.prototype._.once)
- description and source-code
```javascript
function once(func) {
  var ran,
      result;

  if (!isFunction(func)) {
    throw new TypeError;
  }
  return function() {
    if (ran) {
      return result;
    }
    ran = true;
    result = func.apply(this, arguments);

    // clear the 'func' variable so the function may be garbage collected
    func = null;
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.pad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pad (str, length, padStr, type)](#apidoc.element.generator-node-webkit.super_.prototype._.pad)
- description and source-code
```javascript
pad = function (str, length, padStr, type) {
  str = str == null ? '' : String(str);
  length = ~~length;

  var padlen  = 0;

  if (!padStr)
    padStr = ' ';
  else if (padStr.length > 1)
    padStr = padStr.charAt(0);

  switch(type) {
    case 'right':
      padlen = length - str.length;
      return str + strRepeat(padStr, padlen);
    case 'both':
      padlen = length - str.length;
      return strRepeat(padStr, Math.ceil(padlen/2)) + str
              + strRepeat(padStr, Math.floor(padlen/2));
    default: // 'left'
      padlen = length - str.length;
      return strRepeat(padStr, padlen) + str;
    }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.pairs"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pairs (object)](#apidoc.element.generator-node-webkit.super_.prototype._.pairs)
- description and source-code
```javascript
function pairs(object) {
  var index = -1,
      props = keys(object),
      length = props.length,
      result = Array(length);

  while (++index < length) {
    var key = props[index];
    result[index] = [key, object[key]];
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.parseInt"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>parseInt ()](#apidoc.element.generator-node-webkit.super_.prototype._.parseInt)
- description and source-code
```javascript
function parseInt() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.partial"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>partial (func)](#apidoc.element.generator-node-webkit.super_.prototype._.partial)
- description and source-code
```javascript
function partial(func) {
  return createWrapper(func, 16, slice(arguments, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.partialRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>partialRight (func)](#apidoc.element.generator-node-webkit.super_.prototype._.partialRight)
- description and source-code
```javascript
function partialRight(func) {
  return createWrapper(func, 32, null, slice(arguments, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.pick"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pick (object, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.pick)
- description and source-code
```javascript
function pick(object, callback, thisArg) {
  var result = {};
  if (typeof callback != 'function') {
    var index = -1,
        props = baseFlatten(arguments, true, false, 1),
        length = isObject(object) ? props.length : 0;

    while (++index < length) {
      var key = props[index];
      if (key in object) {
        result[key] = object[key];
      }
    }
  } else {
    callback = lodash.createCallback(callback, thisArg, 3);
    forIn(object, function(value, key, object) {
      if (callback(value, key, object)) {
        result[key] = value;
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.pluck"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pluck (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.pluck)
- description and source-code
```javascript
function map(collection, callback, thisArg) {
  var index = -1,
      length = collection ? collection.length : 0;

  callback = lodash.createCallback(callback, thisArg, 3);
  if (typeof length == 'number') {
    var result = Array(length);
    while (++index < length) {
      result[index] = callback(collection[index], index, collection);
    }
  } else {
    result = [];
    forOwn(collection, function(value, key, collection) {
      result[++index] = callback(value, key, collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.property"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>property (key)](#apidoc.element.generator-node-webkit.super_.prototype._.property)
- description and source-code
```javascript
function property(key) {
  return function(object) {
    return object[key];
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prune"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>prune (str, length, pruneStr)](#apidoc.element.generator-node-webkit.super_.prototype._.prune)
- description and source-code
```javascript
prune = function (str, length, pruneStr){
  if (str == null) return '';

  str = String(str); length = ~~length;
  pruneStr = pruneStr != null ? String(pruneStr) : '...';

  if (str.length <= length) return str;

  var tmpl = function(c){ return c.toUpperCase() !== c.toLowerCase() ? 'A' : ' '; },
    template = str.slice(0, length+1).replace(/.(?=\W*\w*$)/g, tmpl); // 'Hello, world' -> 'HellAA AAAAA'

  if (template.slice(template.length-2).match(/\w\w/))
    template = template.replace(/\s*\S+$/, '');
  else
    template = _s.rtrim(template.slice(0, template.length-1));

  return (template+pruneStr).length > str.length ? str : str.slice(0, template.length)+pruneStr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.pull"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>pull (array)](#apidoc.element.generator-node-webkit.super_.prototype._.pull)
- description and source-code
```javascript
function pull(array) {
  var args = arguments,
      argsIndex = 0,
      argsLength = args.length,
      length = array ? array.length : 0;

  while (++argsIndex < argsLength) {
    var index = -1,
        value = args[argsIndex];
    while (++index < length) {
      if (array[index] === value) {
        splice.call(array, index--, 1);
        length--;
      }
    }
  }
  return array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.q"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>q (str, quoteChar)](#apidoc.element.generator-node-webkit.super_.prototype._.q)
- description and source-code
```javascript
q = function (str, quoteChar) {
  return _s.surround(str, quoteChar || '"');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.quote"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>quote (str, quoteChar)](#apidoc.element.generator-node-webkit.super_.prototype._.quote)
- description and source-code
```javascript
quote = function (str, quoteChar) {
  return _s.surround(str, quoteChar || '"');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.random"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>random (min, max, floating)](#apidoc.element.generator-node-webkit.super_.prototype._.random)
- description and source-code
```javascript
function random(min, max, floating) {
  var noMin = min == null,
      noMax = max == null;

  if (floating == null) {
    if (typeof min == 'boolean' && noMax) {
      floating = min;
      min = 1;
    }
    else if (!noMax && typeof max == 'boolean') {
      floating = max;
      noMax = true;
    }
  }
  if (noMin && noMax) {
    max = 1;
  }
  min = +min || 0;
  if (noMax) {
    max = min;
    min = 0;
  } else {
    max = +max || 0;
  }
  if (floating || min % 1 || max % 1) {
    var rand = nativeRandom();
    return nativeMin(min + (rand * (max - min + parseFloat('1e-' + ((rand +'').length - 1)))), max);
  }
  return baseRandom(min, max);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.range"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>range (start, end, step)](#apidoc.element.generator-node-webkit.super_.prototype._.range)
- description and source-code
```javascript
function range(start, end, step) {
  start = +start || 0;
  step = typeof step == 'number' ? step : (+step || 1);

  if (end == null) {
    end = start;
    start = 0;
  }
  // use 'Array(length)' so engines like Chakra and V8 avoid slower modes
  // http://youtu.be/XAqIpGU8ZZk#t=17m25s
  var index = -1,
      length = nativeMax(0, ceil((end - start) / (step || 1))),
      result = Array(length);

  while (++index < length) {
    result[index] = start;
    start += step;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.reduce"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>reduce (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.reduce)
- description and source-code
```javascript
function reduce(collection, callback, accumulator, thisArg) {
  if (!collection) return accumulator;
  var noaccum = arguments.length < 3;
  callback = lodash.createCallback(callback, thisArg, 4);

  var index = -1,
      length = collection.length;

  if (typeof length == 'number') {
    if (noaccum) {
      accumulator = collection[++index];
    }
    while (++index < length) {
      accumulator = callback(accumulator, collection[index], index, collection);
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      accumulator = noaccum
        ? (noaccum = false, value)
        : callback(accumulator, value, index, collection)
    });
  }
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.reduceRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>reduceRight (collection, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.reduceRight)
- description and source-code
```javascript
function reduceRight(collection, callback, accumulator, thisArg) {
  var noaccum = arguments.length < 3;
  callback = lodash.createCallback(callback, thisArg, 4);
  forEachRight(collection, function(value, index, collection) {
    accumulator = noaccum
      ? (noaccum = false, value)
      : callback(accumulator, value, index, collection);
  });
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.reject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>reject (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.reject)
- description and source-code
```javascript
function reject(collection, callback, thisArg) {
  callback = lodash.createCallback(callback, thisArg, 3);
  return filter(collection, function(value, index, collection) {
    return !callback(value, index, collection);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.remove"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>remove (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.remove)
- description and source-code
```javascript
function remove(array, callback, thisArg) {
  var index = -1,
      length = array ? array.length : 0,
      result = [];

  callback = lodash.createCallback(callback, thisArg, 3);
  while (++index < length) {
    var value = array[index];
    if (callback(value, index, array)) {
      result.push(value);
      splice.call(array, index--, 1);
      length--;
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.repeat"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>repeat (str, qty, separator)](#apidoc.element.generator-node-webkit.super_.prototype._.repeat)
- description and source-code
```javascript
repeat = function (str, qty, separator){
  if (str == null) return '';

  qty = ~~qty;

  // using faster implementation if separator is not needed;
  if (separator == null) return strRepeat(String(str), qty);

  // this one is about 300x slower in Google Chrome
  for (var repeat = []; qty > 0; repeat[--qty] = str) {}
  return repeat.join(separator);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.rest"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rest (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.rest)
- description and source-code
```javascript
function rest(array, callback, thisArg) {
  if (typeof callback != 'number' && callback != null) {
    var n = 0,
        index = -1,
        length = array ? array.length : 0;

    callback = lodash.createCallback(callback, thisArg, 3);
    while (++index < length && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = (callback == null || thisArg) ? 1 : nativeMax(0, callback);
  }
  return slice(array, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.result"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>result (object, key)](#apidoc.element.generator-node-webkit.super_.prototype._.result)
- description and source-code
```javascript
function result(object, key) {
  if (object) {
    var value = object[key];
    return isFunction(value) ? object[key]() : value;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.rjust"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rjust (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.rjust)
- description and source-code
```javascript
rjust = function (str, length, padStr) {
  return _s.pad(str, length, padStr);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.rpad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rpad (str, length, padStr)](#apidoc.element.generator-node-webkit.super_.prototype._.rpad)
- description and source-code
```javascript
rpad = function (str, length, padStr) {
  return _s.pad(str, length, padStr, 'right');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.rstrip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rstrip (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.rstrip)
- description and source-code
```javascript
rstrip = function (str, characters){
  if (str == null) return '';
  if (!characters && nativeTrimRight) return nativeTrimRight.call(str);
  characters = defaultToWhiteSpace(characters);
  return String(str).replace(new RegExp(characters + '+$'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.rtrim"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>rtrim (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.rtrim)
- description and source-code
```javascript
rtrim = function (str, characters){
  if (str == null) return '';
  if (!characters && nativeTrimRight) return nativeTrimRight.call(str);
  characters = defaultToWhiteSpace(characters);
  return String(str).replace(new RegExp(characters + '+$'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.runInContext"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>runInContext (context)](#apidoc.element.generator-node-webkit.super_.prototype._.runInContext)
- description and source-code
```javascript
function runInContext(context) {
  // Avoid issues with some ES3 environments that attempt to use values, named
  // after built-in constructors like 'Object', for the creation of literals.
  // ES5 clears this up by stating that literals must use built-in constructors.
  // See http://es5.github.io/#x11.1.5.
  context = context ? _.defaults(root.Object(), context, _.pick(root, contextProps)) : root;

<span class="apidocCodeCommentSpan">  /** Native constructor references */
</span>  var Array = context.Array,
      Boolean = context.Boolean,
      Date = context.Date,
      Function = context.Function,
      Math = context.Math,
      Number = context.Number,
      Object = context.Object,
      RegExp = context.RegExp,
      String = context.String,
      TypeError = context.TypeError;

  /**
   * Used for 'Array' method references.
   *
   * Normally 'Array.prototype' would suffice, however, using an array literal
   * avoids issues in Narwhal.
   */
  var arrayRef = [];

  /** Used for native method references */
  var objectProto = Object.prototype;

  /** Used to restore the original '_' reference in 'noConflict' */
  var oldDash = context._;

  /** Used to resolve the internal [[Class]] of values */
  var toString = objectProto.toString;

  /** Used to detect if a method is native */
  var reNative = RegExp('^' +
    String(toString)
      .replace(/[.*+?^${}()|[\]\\]/g, '\\$&')
      .replace(/toString| for [^\]]+/g, '.*?') + '$'
  );

  /** Native method shortcuts */
  var ceil = Math.ceil,
      clearTimeout = context.clearTimeout,
      floor = Math.floor,
      fnToString = Function.prototype.toString,
      getPrototypeOf = isNative(getPrototypeOf = Object.getPrototypeOf) && getPrototypeOf,
      hasOwnProperty = objectProto.hasOwnProperty,
      push = arrayRef.push,
      setTimeout = context.setTimeout,
      splice = arrayRef.splice,
      unshift = arrayRef.unshift;

  /** Used to set meta data on functions */
  var defineProperty = (function() {
    // IE 8 only accepts DOM elements
    try {
      var o = {},
          func = isNative(func = Object.defineProperty) && func,
          result = func(o, o, o) && func;
    } catch(e) { }
    return result;
  }());

  /* Native method shortcuts for methods with the same name as other 'lodash' methods */
  var nativeCreate = isNative(nativeCreate = Object.create) && nativeCreate,
      nativeIsArray = isNative(nativeIsArray = Array.isArray) && nativeIsArray,
      nativeIsFinite = context.isFinite,
      nativeIsNaN = context.isNaN,
      nativeKeys = isNative(nativeKeys = Object.keys) && nativeKeys,
      nativeMax = Math.max,
      nativeMin = Math.min,
      nativeParseInt = context.parseInt,
      nativeRandom = Math.random;

  /** Used to lookup a built-in constructor by [[Class]] */
  var ctorByClass = {};
  ctorByClass[arrayClass] = Array;
  ctorByClass[boolClass] = Boolean;
  ctorByClass[dateClass] = Date;
  ctorByClass[funcClass] = Function;
  ctorByClass[objectClass] = Object;
  ctorByClass[numberClass] = Number;
  ctorByClass[regexpClass] = RegExp;
  ctorByClass[stringClass] = String;

  /*--------------------------------------------------------------------------*/

  /**
   * Creates a 'lodash' object which wraps the given value to enable intuitive
   * method chaining.
   *
   * In addition to Lo-Dash methods, wrappers also have the following 'Array' methods:
   * 'concat', 'join', 'pop', 'push', 'reverse', 'shift', 'slice', 'sort', 'splice',
   * and 'unshift'
   *
   * Chaining is supported in custom builds as long as the 'value' method is
   * implicitly or explicitly included in the build.
   *
   * The chainable wrapper functions are:
   * 'after', 'assign', 'bind', 'bindAll', 'bindKey', 'chain', 'compact',
   * 'compose', 'concat', 'countBy', 'create', 'createCallback', 'curry',
   * 'debounce', 'defaults', 'defer', 'delay', 'difference', 'filter', 'flatten',
   * 'forEach', 'forEachRight', 'forIn', 'forInRight', 'forOwn', 'forOwnRight',
   * 'functions', 'groupBy', 'indexBy', 'initial', 'intersection', 'invert',
   * 'invoke', 'keys', 'map', 'max', 'memoize', 'merge', 'min', 'obje ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.sample"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sample (collection, n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.sample)
- description and source-code
```javascript
function sample(collection, n, guard) {
  if (collection && typeof collection.length != 'number') {
    collection = values(collection);
  }
  if (n == null || guard) {
    return collection ? collection[baseRandom(0, collection.length - 1)] : undefined;
  }
  var result = shuffle(collection);
  result.length = nativeMin(nativeMax(0, n), result.length);
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.select"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>select (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.select)
- description and source-code
```javascript
function filter(collection, callback, thisArg) {
  var result = [];
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      if (callback(value, index, collection)) {
        result.push(value);
      }
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      if (callback(value, index, collection)) {
        result.push(value);
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.shuffle"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>shuffle (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.shuffle)
- description and source-code
```javascript
function shuffle(collection) {
  var index = -1,
      length = collection ? collection.length : 0,
      result = Array(typeof length == 'number' ? length : 0);

  forEach(collection, function(value) {
    var rand = baseRandom(0, ++index);
    result[index] = result[rand];
    result[rand] = value;
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.size"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>size (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.size)
- description and source-code
```javascript
function size(collection) {
  var length = collection ? collection.length : 0;
  return typeof length == 'number' ? length : keys(collection).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.slugify"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>slugify (str)](#apidoc.element.generator-node-webkit.super_.prototype._.slugify)
- description and source-code
```javascript
slugify = function (str) {
  if (str == null) return '';

  var from  = "ąàáäâãåæăćęèéëêìíïîłńòóöôõøśșțùúüûñçżź",
      to    = "aaaaaaaaaceeeeeiiiilnoooooosstuuuunczz",
      regex = new RegExp(defaultToWhiteSpace(from), 'g');

  str = String(str).toLowerCase().replace(regex, function(c){
    var index = from.indexOf(c);
    return to.charAt(index) || '-';
  });

  return _s.dasherize(str.replace(/[^\w\s-]/g, ''));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.some"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>some (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.some)
- description and source-code
```javascript
function some(collection, callback, thisArg) {
  var result;
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      if ((result = callback(collection[index], index, collection))) {
        break;
      }
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      return !(result = callback(value, index, collection));
    });
  }
  return !!result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.sortBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sortBy (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.sortBy)
- description and source-code
```javascript
function sortBy(collection, callback, thisArg) {
  var index = -1,
      isArr = isArray(callback),
      length = collection ? collection.length : 0,
      result = Array(typeof length == 'number' ? length : 0);

  if (!isArr) {
    callback = lodash.createCallback(callback, thisArg, 3);
  }
  forEach(collection, function(value, key, collection) {
    var object = result[++index] = getObject();
    if (isArr) {
      object.criteria = map(callback, function(key) { return value[key]; });
    } else {
      (object.criteria = getArray())[0] = callback(value, key, collection);
    }
    object.index = index;
    object.value = value;
  });

  length = result.length;
  result.sort(compareAscending);
  while (length--) {
    var object = result[length];
    result[length] = object.value;
    if (!isArr) {
      releaseArray(object.criteria);
    }
    releaseObject(object);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.sortedIndex"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sortedIndex (array, value, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.sortedIndex)
- description and source-code
```javascript
function sortedIndex(array, value, callback, thisArg) {
  var low = 0,
      high = array ? array.length : low;

  // explicitly reference 'identity' for better inlining in Firefox
  callback = callback ? lodash.createCallback(callback, thisArg, 1) : identity;
  value = callback(value);

  while (low < high) {
    var mid = (low + high) >>> 1;
    (callback(array[mid]) < value)
      ? low = mid + 1
      : high = mid;
  }
  return low;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.splice"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>splice (str, i, howmany, substr)](#apidoc.element.generator-node-webkit.super_.prototype._.splice)
- description and source-code
```javascript
splice = function (str, i, howmany, substr){
  var arr = _s.chars(str);
  arr.splice(~~i, ~~howmany, substr);
  return arr.join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.sprintf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>sprintf ()](#apidoc.element.generator-node-webkit.super_.prototype._.sprintf)
- description and source-code
```javascript
sprintf = function () {
  if (!str_format.cache.hasOwnProperty(arguments[0])) {
    str_format.cache[arguments[0]] = str_format.parse(arguments[0]);
  }
  return str_format.format.call(null, str_format.cache[arguments[0]], arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.startsWith"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>startsWith (str, starts)](#apidoc.element.generator-node-webkit.super_.prototype._.startsWith)
- description and source-code
```javascript
startsWith = function (str, starts){
  if (starts === '') return true;
  if (str == null || starts == null) return false;
  str = String(str); starts = String(starts);
  return str.length >= starts.length && str.slice(0, starts.length) === starts;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.strLeft"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strLeft (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strLeft)
- description and source-code
```javascript
strLeft = function (str, sep){
  if (str == null) return '';
  str = String(str); sep = sep != null ? String(sep) : sep;
  var pos = !sep ? -1 : str.indexOf(sep);
  return ~pos ? str.slice(0, pos) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.strLeftBack"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strLeftBack (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strLeftBack)
- description and source-code
```javascript
strLeftBack = function (str, sep){
  if (str == null) return '';
  str += ''; sep = sep != null ? ''+sep : sep;
  var pos = str.lastIndexOf(sep);
  return ~pos ? str.slice(0, pos) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.strRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strRight (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strRight)
- description and source-code
```javascript
strRight = function (str, sep){
  if (str == null) return '';
  str = String(str); sep = sep != null ? String(sep) : sep;
  var pos = !sep ? -1 : str.indexOf(sep);
  return ~pos ? str.slice(pos+sep.length, str.length) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.strRightBack"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strRightBack (str, sep)](#apidoc.element.generator-node-webkit.super_.prototype._.strRightBack)
- description and source-code
```javascript
strRightBack = function (str, sep){
  if (str == null) return '';
  str = String(str); sep = sep != null ? String(sep) : sep;
  var pos = !sep ? -1 : str.lastIndexOf(sep);
  return ~pos ? str.slice(pos+sep.length, str.length) : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.strip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>strip (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.strip)
- description and source-code
```javascript
strip = function (str, characters){
  if (str == null) return '';
  if (!characters && nativeTrim) return nativeTrim.call(str);
  characters = defaultToWhiteSpace(characters);
  return String(str).replace(new RegExp('^' + characters + '+|' + characters + '+$', 'g'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.stripTags"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>stripTags (str)](#apidoc.element.generator-node-webkit.super_.prototype._.stripTags)
- description and source-code
```javascript
stripTags = function (str){
  if (str == null) return '';
  return String(str).replace(/<\/?[^>]+>/g, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.succ"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>succ (str)](#apidoc.element.generator-node-webkit.super_.prototype._.succ)
- description and source-code
```javascript
succ = function (str){
  if (str == null) return '';
  str = String(str);
  return str.slice(0, -1) + String.fromCharCode(str.charCodeAt(str.length-1) + 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.surround"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>surround (str, wrapper)](#apidoc.element.generator-node-webkit.super_.prototype._.surround)
- description and source-code
```javascript
surround = function (str, wrapper) {
  return [wrapper, str, wrapper].join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.swapCase"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>swapCase (str)](#apidoc.element.generator-node-webkit.super_.prototype._.swapCase)
- description and source-code
```javascript
swapCase = function (str) {
  if (str == null) return '';
  return String(str).replace(/\S/g, function(c){
    return c === c.toUpperCase() ? c.toLowerCase() : c.toUpperCase();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.tail"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>tail (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.tail)
- description and source-code
```javascript
function rest(array, callback, thisArg) {
  if (typeof callback != 'number' && callback != null) {
    var n = 0,
        index = -1,
        length = array ? array.length : 0;

    callback = lodash.createCallback(callback, thisArg, 3);
    while (++index < length && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = (callback == null || thisArg) ? 1 : nativeMax(0, callback);
  }
  return slice(array, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.take"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>take (array, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.take)
- description and source-code
```javascript
function first(array, callback, thisArg) {
  var n = 0,
      length = array ? array.length : 0;

  if (typeof callback != 'number' && callback != null) {
    var index = -1;
    callback = lodash.createCallback(callback, thisArg, 3);
    while (++index < length && callback(array[index], index, array)) {
      n++;
    }
  } else {
    n = callback;
    if (n == null || thisArg) {
      return array ? array[0] : undefined;
    }
  }
  return slice(array, 0, nativeMin(nativeMax(0, n), length));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.tap"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>tap (value, interceptor)](#apidoc.element.generator-node-webkit.super_.prototype._.tap)
- description and source-code
```javascript
function tap(value, interceptor) {
  interceptor(value);
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.template"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>template (text, data, options)](#apidoc.element.generator-node-webkit.super_.prototype._.template)
- description and source-code
```javascript
function template(text, data, options) {
  // based on John Resig's 'tmpl' implementation
  // http://ejohn.org/blog/javascript-micro-templating/
  // and Laura Doktorova's doT.js
  // https://github.com/olado/doT
  var settings = lodash.templateSettings;
  text = String(text || '');

  // avoid missing dependencies when 'iteratorTemplate' is not defined
  options = defaults({}, options, settings);

  var imports = defaults({}, options.imports, settings.imports),
      importsKeys = keys(imports),
      importsValues = values(imports);

  var isEvaluating,
      index = 0,
      interpolate = options.interpolate || reNoMatch,
      source = "__p += '";

  // compile the regexp to match each delimiter
  var reDelimiters = RegExp(
    (options.escape || reNoMatch).source + '|' +
    interpolate.source + '|' +
    (interpolate === reInterpolate ? reEsTemplate : reNoMatch).source + '|' +
    (options.evaluate || reNoMatch).source + '|$'
  , 'g');

  text.replace(reDelimiters, function(match, escapeValue, interpolateValue, esTemplateValue, evaluateValue, offset) {
    interpolateValue || (interpolateValue = esTemplateValue);

    // escape characters that cannot be included in string literals
    source += text.slice(index, offset).replace(reUnescapedString, escapeStringChar);

    // replace delimiters with snippets
    if (escapeValue) {
      source += "' +\n__e(" + escapeValue + ") +\n'";
    }
    if (evaluateValue) {
      isEvaluating = true;
      source += "';\n" + evaluateValue + ";\n__p += '";
    }
    if (interpolateValue) {
      source += "' +\n((__t = (" + interpolateValue + ")) == null ? '' : __t) +\n'";
    }
    index = offset + match.length;

    // the JS engine embedded in Adobe products requires returning the 'match'
    // string in order to produce the correct 'offset' value
    return match;
  });

  source += "';\n";

  // if 'variable' is not specified, wrap a with-statement around the generated
  // code to add the data object to the top of the scope chain
  var variable = options.variable,
      hasVariable = variable;

  if (!hasVariable) {
    variable = 'obj';
    source = 'with (' + variable + ') {\n' + source + '\n}\n';
  }
  // cleanup code by stripping empty strings
  source = (isEvaluating ? source.replace(reEmptyStringLeading, '') : source)
    .replace(reEmptyStringMiddle, '$1')
    .replace(reEmptyStringTrailing, '$1;');

  // frame code as the function body
  source = 'function(' + variable + ') {\n' +
    (hasVariable ? '' : variable + ' || (' + variable + ' = {});\n') +
    "var __t, __p = '', __e = _.escape" +
    (isEvaluating
      ? ', __j = Array.prototype.join;\n' +
        "function print() { __p += __j.call(arguments, '') }\n"
      : ';\n'
    ) +
    source +
    'return __p\n}';

  // Use a sourceURL for easier debugging.
  // http://www.html5rocks.com/en/tutorials/developertools/sourcemaps/#toc-sourceurl
  var sourceURL = '\n/*\n//# sourceURL=' + (options.sourceURL || '/lodash/template/source[' + (templateCounter++) + ']') + '\n*/';

  try {
    var result = Function(importsKeys, 'return ' + source + sourceURL).apply(undefined, importsValues);
  } catch(e) {
    e.source = source;
    throw e;
  }
  if (data) {
    return result(data);
  }
  // provide the compiled function's source by its 'toString' method, in
  // supported environments, or the 'source' property as a convenience for
  // inlining compiled templates during the build process
  result.source = source;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.throttle"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>throttle (func, wait, options)](#apidoc.element.generator-node-webkit.super_.prototype._.throttle)
- description and source-code
```javascript
function throttle(func, wait, options) {
  var leading = true,
      trailing = true;

  if (!isFunction(func)) {
    throw new TypeError;
  }
  if (options === false) {
    leading = false;
  } else if (isObject(options)) {
    leading = 'leading' in options ? options.leading : leading;
    trailing = 'trailing' in options ? options.trailing : trailing;
  }
  debounceOptions.leading = leading;
  debounceOptions.maxWait = wait;
  debounceOptions.trailing = trailing;

  return debounce(func, wait, debounceOptions);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.times"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>times (n, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.times)
- description and source-code
```javascript
function times(n, callback, thisArg) {
  n = (n = +n) > -1 ? n : 0;
  var index = -1,
      result = Array(n);

  callback = baseCreateCallback(callback, thisArg, 1);
  while (++index < n) {
    result[index] = callback(index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.titleize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>titleize (str)](#apidoc.element.generator-node-webkit.super_.prototype._.titleize)
- description and source-code
```javascript
titleize = function (str){
  if (str == null) return '';
  str  = String(str).toLowerCase();
  return str.replace(/(?:^|\s|-)\S/g, function(c){ return c.toUpperCase(); });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.toArray"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toArray (collection)](#apidoc.element.generator-node-webkit.super_.prototype._.toArray)
- description and source-code
```javascript
function toArray(collection) {
  if (collection && typeof collection.length == 'number') {
    return slice(collection);
  }
  return values(collection);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.toBool"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toBool (str, trueValues, falseValues)](#apidoc.element.generator-node-webkit.super_.prototype._.toBool)
- description and source-code
```javascript
toBool = function (str, trueValues, falseValues) {
  if (typeof str === "number") str = "" + str;
  if (typeof str !== "string") return !!str;
  str = _s.trim(str);
  if (boolMatch(str, trueValues || ["true", "1"])) return true;
  if (boolMatch(str, falseValues || ["false", "0"])) return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.toBoolean"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toBoolean (str, trueValues, falseValues)](#apidoc.element.generator-node-webkit.super_.prototype._.toBoolean)
- description and source-code
```javascript
toBoolean = function (str, trueValues, falseValues) {
  if (typeof str === "number") str = "" + str;
  if (typeof str !== "string") return !!str;
  str = _s.trim(str);
  if (boolMatch(str, trueValues || ["true", "1"])) return true;
  if (boolMatch(str, falseValues || ["false", "0"])) return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.toNumber"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toNumber (str, decimals)](#apidoc.element.generator-node-webkit.super_.prototype._.toNumber)
- description and source-code
```javascript
toNumber = function (str, decimals) {
  if (!str) return 0;
  str = _s.trim(str);
  if (!str.match(/^-?\d+(?:\.\d+)?$/)) return NaN;
  return parseNumber(parseNumber(str).toFixed(~~decimals));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.toSentence"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toSentence (array, separator, lastSeparator, serial)](#apidoc.element.generator-node-webkit.super_.prototype._.toSentence)
- description and source-code
```javascript
toSentence = function (array, separator, lastSeparator, serial) {
  separator = separator || ', ';
  lastSeparator = lastSeparator || ' and ';
  var a = array.slice(), lastMember = a.pop();

  if (array.length > 2 && serial) lastSeparator = _s.rtrim(separator) + lastSeparator;

  return a.length ? a.join(separator) + lastSeparator + lastMember : lastMember;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.toSentenceSerial"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>toSentenceSerial ()](#apidoc.element.generator-node-webkit.super_.prototype._.toSentenceSerial)
- description and source-code
```javascript
toSentenceSerial = function () {
  var args = slice.call(arguments);
  args[3] = true;
  return _s.toSentence.apply(_s, args);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.transform"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>transform (object, callback, accumulator, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.transform)
- description and source-code
```javascript
function transform(object, callback, accumulator, thisArg) {
  var isArr = isArray(object);
  if (accumulator == null) {
    if (isArr) {
      accumulator = [];
    } else {
      var ctor = object && object.constructor,
          proto = ctor && ctor.prototype;

      accumulator = baseCreate(proto);
    }
  }
  if (callback) {
    callback = lodash.createCallback(callback, thisArg, 4);
    (isArr ? forEach : forOwn)(object, function(value, index, object) {
      return callback(accumulator, value, index, object);
    });
  }
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.trim"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>trim (str, characters)](#apidoc.element.generator-node-webkit.super_.prototype._.trim)
- description and source-code
```javascript
trim = function (str, characters){
  if (str == null) return '';
  if (!characters && nativeTrim) return nativeTrim.call(str);
  characters = defaultToWhiteSpace(characters);
  return String(str).replace(new RegExp('^' + characters + '+|' + characters + '+$', 'g'), '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.truncate"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>truncate (str, length, truncateStr)](#apidoc.element.generator-node-webkit.super_.prototype._.truncate)
- description and source-code
```javascript
truncate = function (str, length, truncateStr){
  if (str == null) return '';
  str = String(str); truncateStr = truncateStr || '...';
  length = ~~length;
  return str.length > length ? str.slice(0, length) + truncateStr : str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.underscored"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>underscored (str)](#apidoc.element.generator-node-webkit.super_.prototype._.underscored)
- description and source-code
```javascript
underscored = function (str){
  return _s.trim(str).replace(/([a-z\d])([A-Z]+)/g, '$1_$2').replace(/[-\s]+/g, '_').toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.unescape"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unescape (string)](#apidoc.element.generator-node-webkit.super_.prototype._.unescape)
- description and source-code
```javascript
function unescape(string) {
  return string == null ? '' : String(string).replace(reEscapedHtml, unescapeHtmlChar);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.unescapeHTML"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unescapeHTML (str)](#apidoc.element.generator-node-webkit.super_.prototype._.unescapeHTML)
- description and source-code
```javascript
unescapeHTML = function (str) {
  if (str == null) return '';
  return String(str).replace(/\&([^;]+);/g, function(entity, entityCode){
    var match;

    if (entityCode in escapeChars) {
      return escapeChars[entityCode];
    } else if (match = entityCode.match(/^#x([\da-fA-F]+)$/)) {
      return String.fromCharCode(parseInt(match[1], 16));
    } else if (match = entityCode.match(/^#(\d+)$/)) {
      return String.fromCharCode(~~match[1]);
    } else {
      return entity;
    }
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.union"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>union ()](#apidoc.element.generator-node-webkit.super_.prototype._.union)
- description and source-code
```javascript
function union() {
  return baseUniq(baseFlatten(arguments, true, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.uniq"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>uniq (array, isSorted, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.uniq)
- description and source-code
```javascript
function uniq(array, isSorted, callback, thisArg) {
  // juggle arguments
  if (typeof isSorted != 'boolean' && isSorted != null) {
    thisArg = callback;
    callback = (typeof isSorted != 'function' && thisArg && thisArg[isSorted] === array) ? null : isSorted;
    isSorted = false;
  }
  if (callback != null) {
    callback = lodash.createCallback(callback, thisArg, 3);
  }
  return baseUniq(array, isSorted, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.unique"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unique (array, isSorted, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.unique)
- description and source-code
```javascript
function uniq(array, isSorted, callback, thisArg) {
  // juggle arguments
  if (typeof isSorted != 'boolean' && isSorted != null) {
    thisArg = callback;
    callback = (typeof isSorted != 'function' && thisArg && thisArg[isSorted] === array) ? null : isSorted;
    isSorted = false;
  }
  if (callback != null) {
    callback = lodash.createCallback(callback, thisArg, 3);
  }
  return baseUniq(array, isSorted, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.uniqueId"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>uniqueId (prefix)](#apidoc.element.generator-node-webkit.super_.prototype._.uniqueId)
- description and source-code
```javascript
function uniqueId(prefix) {
  var id = ++idCounter;
  return String(prefix == null ? '' : prefix) + id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.unquote"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unquote (str, quoteChar)](#apidoc.element.generator-node-webkit.super_.prototype._.unquote)
- description and source-code
```javascript
unquote = function (str, quoteChar) {
  quoteChar = quoteChar || '"';
  if (str[0] === quoteChar && str[str.length-1] === quoteChar)
    return str.slice(1,str.length-1);
  else return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.unzip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>unzip ()](#apidoc.element.generator-node-webkit.super_.prototype._.unzip)
- description and source-code
```javascript
function zip() {
  var array = arguments.length > 1 ? arguments : arguments[0],
      index = -1,
      length = array ? max(pluck(array, 'length')) : 0,
      result = Array(length < 0 ? 0 : length);

  while (++index < length) {
    result[index] = pluck(array, index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.values"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>values (object)](#apidoc.element.generator-node-webkit.super_.prototype._.values)
- description and source-code
```javascript
function values(object) {
  var index = -1,
      props = keys(object),
      length = props.length,
      result = Array(length);

  while (++index < length) {
    result[index] = object[props[index]];
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.vsprintf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>vsprintf (fmt, argv)](#apidoc.element.generator-node-webkit.super_.prototype._.vsprintf)
- description and source-code
```javascript
vsprintf = function (fmt, argv){
  argv.unshift(fmt);
  return sprintf.apply(null, argv);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.where"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>where (collection, callback, thisArg)](#apidoc.element.generator-node-webkit.super_.prototype._.where)
- description and source-code
```javascript
function filter(collection, callback, thisArg) {
  var result = [];
  callback = lodash.createCallback(callback, thisArg, 3);

  var index = -1,
      length = collection ? collection.length : 0;

  if (typeof length == 'number') {
    while (++index < length) {
      var value = collection[index];
      if (callback(value, index, collection)) {
        result.push(value);
      }
    }
  } else {
    forOwn(collection, function(value, index, collection) {
      if (callback(value, index, collection)) {
        result.push(value);
      }
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.without"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>without (array)](#apidoc.element.generator-node-webkit.super_.prototype._.without)
- description and source-code
```javascript
function without(array) {
  return baseDifference(array, slice(arguments, 1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.words"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>words (str, delimiter)](#apidoc.element.generator-node-webkit.super_.prototype._.words)
- description and source-code
```javascript
words = function (str, delimiter) {
  if (_s.isBlank(str)) return [];
  return _s.trim(str, delimiter).split(delimiter || /\s+/);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.wrap"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>wrap (value, wrapper)](#apidoc.element.generator-node-webkit.super_.prototype._.wrap)
- description and source-code
```javascript
function wrap(value, wrapper) {
  return createWrapper(wrapper, 16, [value]);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.xor"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>xor ()](#apidoc.element.generator-node-webkit.super_.prototype._.xor)
- description and source-code
```javascript
function xor() {
  var index = -1,
      length = arguments.length;

  while (++index < length) {
    var array = arguments[index];
    if (isArray(array) || isArguments(array)) {
      var result = result
        ? baseUniq(baseDifference(result, array).concat(baseDifference(array, result)))
        : array;
    }
  }
  return result || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.zip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>zip ()](#apidoc.element.generator-node-webkit.super_.prototype._.zip)
- description and source-code
```javascript
function zip() {
  var array = arguments.length > 1 ? arguments : arguments[0],
      index = -1,
      length = array ? max(pluck(array, 'length')) : 0,
      result = Array(length < 0 ? 0 : length);

  while (++index < length) {
    result[index] = pluck(array, index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.zipObject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.</span>zipObject (keys, values)](#apidoc.element.generator-node-webkit.super_.prototype._.zipObject)
- description and source-code
```javascript
function zipObject(keys, values) {
  var index = -1,
      length = keys ? keys.length : 0,
      result = {};

  if (!values && length && !isArray(keys[0])) {
    values = [];
  }
  while (++index < length) {
    var key = keys[index];
    if (values) {
      result[key] = values[index];
    } else if (key) {
      result[key[0]] = key[1];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.generator-node-webkit.super_.prototype._.prototype"></a>[module generator-node-webkit.super_.prototype._.prototype](#apidoc.module.generator-node-webkit.super_.prototype._.prototype)

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.after"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>after ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.after)
- description and source-code
```javascript
after = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.all"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>all ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.all)
- description and source-code
```javascript
all = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.any"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>any ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.any)
- description and source-code
```javascript
any = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.assign"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>assign ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.assign)
- description and source-code
```javascript
assign = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.at"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>at ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.at)
- description and source-code
```javascript
at = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.bind"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>bind ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.bind)
- description and source-code
```javascript
bind = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.bindAll"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>bindAll ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.bindAll)
- description and source-code
```javascript
bindAll = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.bindKey"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>bindKey ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.bindKey)
- description and source-code
```javascript
bindKey = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.camelize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>camelize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.camelize)
- description and source-code
```javascript
camelize = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.capitalize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>capitalize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.capitalize)
- description and source-code
```javascript
capitalize = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.center"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>center ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.center)
- description and source-code
```javascript
center = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.chain"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>chain ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.chain)
- description and source-code
```javascript
function wrapperChain() {
  this.__chain__ = true;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.chars"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>chars ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.chars)
- description and source-code
```javascript
chars = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.chop"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>chop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.chop)
- description and source-code
```javascript
chop = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.classify"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>classify ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.classify)
- description and source-code
```javascript
classify = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.clean"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>clean ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.clean)
- description and source-code
```javascript
clean = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.clone"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>clone ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.clone)
- description and source-code
```javascript
clone = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.cloneDeep"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>cloneDeep ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.cloneDeep)
- description and source-code
```javascript
cloneDeep = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.collect"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>collect ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.collect)
- description and source-code
```javascript
collect = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.compact"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>compact ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.compact)
- description and source-code
```javascript
compact = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.compose"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>compose ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.compose)
- description and source-code
```javascript
compose = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.concat"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>concat ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.concat)
- description and source-code
```javascript
concat = function () {
  return new lodashWrapper(func.apply(this.__wrapped__, arguments), this.__chain__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.constant"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>constant ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.constant)
- description and source-code
```javascript
constant = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.contains"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>contains ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.contains)
- description and source-code
```javascript
contains = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.count"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>count ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.count)
- description and source-code
```javascript
count = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.countBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>countBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.countBy)
- description and source-code
```javascript
countBy = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.create"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>create ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.create)
- description and source-code
```javascript
create = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.createCallback"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>createCallback ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.createCallback)
- description and source-code
```javascript
createCallback = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.curry"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>curry ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.curry)
- description and source-code
```javascript
curry = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.dasherize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>dasherize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.dasherize)
- description and source-code
```javascript
dasherize = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.debounce"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>debounce ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.debounce)
- description and source-code
```javascript
debounce = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.defaults"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>defaults ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.defaults)
- description and source-code
```javascript
defaults = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.defer"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>defer ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.defer)
- description and source-code
```javascript
defer = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.delay"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>delay ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.delay)
- description and source-code
```javascript
delay = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.detect"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>detect ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.detect)
- description and source-code
```javascript
detect = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.difference"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>difference ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.difference)
- description and source-code
```javascript
difference = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.drop"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>drop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.drop)
- description and source-code
```javascript
drop = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.each"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>each ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.each)
- description and source-code
```javascript
each = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.eachRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>eachRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.eachRight)
- description and source-code
```javascript
eachRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.endsWith"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>endsWith ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.endsWith)
- description and source-code
```javascript
endsWith = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.escape"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>escape ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.escape)
- description and source-code
```javascript
escape = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.escapeHTML"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>escapeHTML ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.escapeHTML)
- description and source-code
```javascript
escapeHTML = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.escapeRegExp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>escapeRegExp ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.escapeRegExp)
- description and source-code
```javascript
escapeRegExp = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.every"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>every ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.every)
- description and source-code
```javascript
every = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.exports"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>exports ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.exports)
- description and source-code
```javascript
exports = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.extend"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>extend ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.extend)
- description and source-code
```javascript
extend = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.filter"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>filter ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.filter)
- description and source-code
```javascript
filter = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.find"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>find ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.find)
- description and source-code
```javascript
find = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.findIndex"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findIndex ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findIndex)
- description and source-code
```javascript
findIndex = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.findKey"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findKey ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findKey)
- description and source-code
```javascript
findKey = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLast"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findLast ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLast)
- description and source-code
```javascript
findLast = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLastIndex"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findLastIndex ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLastIndex)
- description and source-code
```javascript
findLastIndex = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLastKey"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findLastKey ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findLastKey)
- description and source-code
```javascript
findLastKey = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.findWhere"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>findWhere ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.findWhere)
- description and source-code
```javascript
findWhere = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.first"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>first (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.first)
- description and source-code
```javascript
first = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.flatten"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>flatten ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.flatten)
- description and source-code
```javascript
flatten = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.foldl"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>foldl ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.foldl)
- description and source-code
```javascript
foldl = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.foldr"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>foldr ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.foldr)
- description and source-code
```javascript
foldr = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.forEach"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forEach ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forEach)
- description and source-code
```javascript
forEach = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.forEachRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forEachRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forEachRight)
- description and source-code
```javascript
forEachRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.forIn"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forIn ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forIn)
- description and source-code
```javascript
forIn = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.forInRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forInRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forInRight)
- description and source-code
```javascript
forInRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.forOwn"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forOwn ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forOwn)
- description and source-code
```javascript
forOwn = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.forOwnRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>forOwnRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.forOwnRight)
- description and source-code
```javascript
forOwnRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.functions"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>functions ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.functions)
- description and source-code
```javascript
functions = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.groupBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>groupBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.groupBy)
- description and source-code
```javascript
groupBy = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.has"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>has ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.has)
- description and source-code
```javascript
has = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.head"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>head (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.head)
- description and source-code
```javascript
head = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.humanize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>humanize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.humanize)
- description and source-code
```javascript
humanize = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.identity"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>identity ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.identity)
- description and source-code
```javascript
identity = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.include"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>include ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.include)
- description and source-code
```javascript
include = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.indexBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>indexBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.indexBy)
- description and source-code
```javascript
indexBy = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.indexOf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>indexOf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.indexOf)
- description and source-code
```javascript
indexOf = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.initial"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>initial ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.initial)
- description and source-code
```javascript
initial = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.inject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>inject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.inject)
- description and source-code
```javascript
inject = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.insert"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>insert ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.insert)
- description and source-code
```javascript
insert = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.intersection"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>intersection ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.intersection)
- description and source-code
```javascript
intersection = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.invert"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>invert ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.invert)
- description and source-code
```javascript
invert = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.invoke"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>invoke ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.invoke)
- description and source-code
```javascript
invoke = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isArguments"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isArguments ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isArguments)
- description and source-code
```javascript
isArguments = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isArray"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isArray ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isArray)
- description and source-code
```javascript
isArray = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isBlank"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isBlank ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isBlank)
- description and source-code
```javascript
isBlank = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isBoolean"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isBoolean ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isBoolean)
- description and source-code
```javascript
isBoolean = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isDate"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isDate ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isDate)
- description and source-code
```javascript
isDate = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isElement"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isElement ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isElement)
- description and source-code
```javascript
isElement = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isEmpty"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isEmpty ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isEmpty)
- description and source-code
```javascript
isEmpty = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isEqual"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isEqual ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isEqual)
- description and source-code
```javascript
isEqual = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isFinite"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isFinite ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isFinite)
- description and source-code
```javascript
isFinite = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isFunction"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isFunction ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isFunction)
- description and source-code
```javascript
isFunction = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNaN"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isNaN ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNaN)
- description and source-code
```javascript
isNaN = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNull"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isNull ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNull)
- description and source-code
```javascript
isNull = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNumber"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isNumber ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isNumber)
- description and source-code
```javascript
isNumber = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isObject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isObject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isObject)
- description and source-code
```javascript
isObject = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isPlainObject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isPlainObject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isPlainObject)
- description and source-code
```javascript
isPlainObject = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isRegExp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isRegExp ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isRegExp)
- description and source-code
```javascript
isRegExp = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isString"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isString ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isString)
- description and source-code
```javascript
isString = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.isUndefined"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>isUndefined ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.isUndefined)
- description and source-code
```javascript
isUndefined = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.join"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>join ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.join)
- description and source-code
```javascript
join = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.keys"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>keys ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.keys)
- description and source-code
```javascript
keys = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.last"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>last (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.last)
- description and source-code
```javascript
last = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.lastIndexOf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lastIndexOf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lastIndexOf)
- description and source-code
```javascript
lastIndexOf = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.levenshtein"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>levenshtein ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.levenshtein)
- description and source-code
```javascript
levenshtein = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.lines"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lines ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lines)
- description and source-code
```javascript
lines = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.ljust"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>ljust ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.ljust)
- description and source-code
```javascript
ljust = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.lpad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lpad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lpad)
- description and source-code
```javascript
lpad = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.lrpad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lrpad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lrpad)
- description and source-code
```javascript
lrpad = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.lstrip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>lstrip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.lstrip)
- description and source-code
```javascript
lstrip = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.ltrim"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>ltrim ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.ltrim)
- description and source-code
```javascript
ltrim = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.map"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>map ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.map)
- description and source-code
```javascript
map = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.mapValues"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>mapValues ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.mapValues)
- description and source-code
```javascript
mapValues = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.max"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>max ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.max)
- description and source-code
```javascript
max = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.memoize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>memoize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.memoize)
- description and source-code
```javascript
memoize = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.merge"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>merge ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.merge)
- description and source-code
```javascript
merge = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.methods"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>methods ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.methods)
- description and source-code
```javascript
methods = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.min"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>min ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.min)
- description and source-code
```javascript
min = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.mixin"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>mixin ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.mixin)
- description and source-code
```javascript
mixin = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.naturalCmp"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>naturalCmp ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.naturalCmp)
- description and source-code
```javascript
naturalCmp = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.noConflict"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>noConflict ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.noConflict)
- description and source-code
```javascript
noConflict = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.noop"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>noop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.noop)
- description and source-code
```javascript
noop = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.now"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>now ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.now)
- description and source-code
```javascript
now = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.numberFormat"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>numberFormat ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.numberFormat)
- description and source-code
```javascript
numberFormat = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.object"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>object ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.object)
- description and source-code
```javascript
object = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.omit"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>omit ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.omit)
- description and source-code
```javascript
omit = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.once"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>once ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.once)
- description and source-code
```javascript
once = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.pad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pad)
- description and source-code
```javascript
pad = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.pairs"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pairs ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pairs)
- description and source-code
```javascript
pairs = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.parseInt"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>parseInt ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.parseInt)
- description and source-code
```javascript
parseInt = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.partial"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>partial ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.partial)
- description and source-code
```javascript
partial = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.partialRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>partialRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.partialRight)
- description and source-code
```javascript
partialRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.pick"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pick ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pick)
- description and source-code
```javascript
pick = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.pluck"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pluck ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pluck)
- description and source-code
```javascript
pluck = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.pop"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pop ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pop)
- description and source-code
```javascript
pop = function () {
  var chainAll = this.__chain__,
      result = func.apply(this.__wrapped__, arguments);

  return chainAll
    ? new lodashWrapper(result, chainAll)
    : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.property"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>property ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.property)
- description and source-code
```javascript
property = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.prune"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>prune ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.prune)
- description and source-code
```javascript
prune = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.pull"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>pull ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.pull)
- description and source-code
```javascript
pull = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.push"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>push ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.push)
- description and source-code
```javascript
push = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.q"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>q ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.q)
- description and source-code
```javascript
q = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.quote"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>quote ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.quote)
- description and source-code
```javascript
quote = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.random"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>random ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.random)
- description and source-code
```javascript
random = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.range"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>range ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.range)
- description and source-code
```javascript
range = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.reduce"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reduce ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reduce)
- description and source-code
```javascript
reduce = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.reduceRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reduceRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reduceRight)
- description and source-code
```javascript
reduceRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.reject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reject)
- description and source-code
```javascript
reject = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.remove"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>remove ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.remove)
- description and source-code
```javascript
remove = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.repeat"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>repeat ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.repeat)
- description and source-code
```javascript
repeat = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.rest"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rest ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rest)
- description and source-code
```javascript
rest = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.result"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>result ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.result)
- description and source-code
```javascript
result = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.reverse"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>reverse ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.reverse)
- description and source-code
```javascript
reverse = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.rjust"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rjust ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rjust)
- description and source-code
```javascript
rjust = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.rpad"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rpad ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rpad)
- description and source-code
```javascript
rpad = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.rstrip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rstrip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rstrip)
- description and source-code
```javascript
rstrip = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.rtrim"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>rtrim ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.rtrim)
- description and source-code
```javascript
rtrim = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.runInContext"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>runInContext ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.runInContext)
- description and source-code
```javascript
runInContext = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.sample"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sample (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sample)
- description and source-code
```javascript
sample = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.select"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>select ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.select)
- description and source-code
```javascript
select = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.shift"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>shift ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.shift)
- description and source-code
```javascript
shift = function () {
  var chainAll = this.__chain__,
      result = func.apply(this.__wrapped__, arguments);

  return chainAll
    ? new lodashWrapper(result, chainAll)
    : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.shuffle"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>shuffle ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.shuffle)
- description and source-code
```javascript
shuffle = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.size"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>size ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.size)
- description and source-code
```javascript
size = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.slice"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>slice ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.slice)
- description and source-code
```javascript
slice = function () {
  return new lodashWrapper(func.apply(this.__wrapped__, arguments), this.__chain__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.slugify"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>slugify ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.slugify)
- description and source-code
```javascript
slugify = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.some"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>some ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.some)
- description and source-code
```javascript
some = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.sort"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sort ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sort)
- description and source-code
```javascript
sort = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.sortBy"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sortBy ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sortBy)
- description and source-code
```javascript
sortBy = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.sortedIndex"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sortedIndex ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sortedIndex)
- description and source-code
```javascript
sortedIndex = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.splice"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>splice ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.splice)
- description and source-code
```javascript
splice = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.sprintf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>sprintf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.sprintf)
- description and source-code
```javascript
sprintf = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.startsWith"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>startsWith ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.startsWith)
- description and source-code
```javascript
startsWith = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.strLeft"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strLeft ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strLeft)
- description and source-code
```javascript
strLeft = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.strLeftBack"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strLeftBack ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strLeftBack)
- description and source-code
```javascript
strLeftBack = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.strRight"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strRight ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strRight)
- description and source-code
```javascript
strRight = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.strRightBack"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strRightBack ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strRightBack)
- description and source-code
```javascript
strRightBack = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.strip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>strip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.strip)
- description and source-code
```javascript
strip = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.stripTags"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>stripTags ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.stripTags)
- description and source-code
```javascript
stripTags = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.succ"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>succ ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.succ)
- description and source-code
```javascript
succ = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.support"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>support (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.support)
- description and source-code
```javascript
support = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.surround"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>surround ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.surround)
- description and source-code
```javascript
surround = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.swapCase"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>swapCase ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.swapCase)
- description and source-code
```javascript
swapCase = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.tail"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>tail ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.tail)
- description and source-code
```javascript
tail = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.take"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>take (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.take)
- description and source-code
```javascript
take = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.tap"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>tap ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.tap)
- description and source-code
```javascript
tap = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.template"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>template ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.template)
- description and source-code
```javascript
template = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.templateSettings"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>templateSettings (n, guard)](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.templateSettings)
- description and source-code
```javascript
templateSettings = function (n, guard) {
  var chainAll = this.__chain__,
      result = func(this.__wrapped__, n, guard);

  return !chainAll && (n == null || (guard && !(callbackable && typeof n == 'function')))
    ? result
    : new lodashWrapper(result, chainAll);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.throttle"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>throttle ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.throttle)
- description and source-code
```javascript
throttle = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.times"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>times ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.times)
- description and source-code
```javascript
times = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.titleize"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>titleize ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.titleize)
- description and source-code
```javascript
titleize = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.toArray"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toArray ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toArray)
- description and source-code
```javascript
toArray = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.toBool"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toBool ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toBool)
- description and source-code
```javascript
toBool = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.toBoolean"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toBoolean ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toBoolean)
- description and source-code
```javascript
toBoolean = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.toNumber"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toNumber ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toNumber)
- description and source-code
```javascript
toNumber = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.toSentence"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toSentence ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toSentence)
- description and source-code
```javascript
toSentence = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.toSentenceSerial"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toSentenceSerial ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toSentenceSerial)
- description and source-code
```javascript
toSentenceSerial = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.toString"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>toString ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.toString)
- description and source-code
```javascript
function wrapperToString() {
  return String(this.__wrapped__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.transform"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>transform ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.transform)
- description and source-code
```javascript
transform = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.trim"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>trim ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.trim)
- description and source-code
```javascript
trim = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.truncate"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>truncate ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.truncate)
- description and source-code
```javascript
truncate = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.underscored"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>underscored ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.underscored)
- description and source-code
```javascript
underscored = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.unescape"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unescape ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unescape)
- description and source-code
```javascript
unescape = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.unescapeHTML"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unescapeHTML ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unescapeHTML)
- description and source-code
```javascript
unescapeHTML = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.union"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>union ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.union)
- description and source-code
```javascript
union = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.uniq"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>uniq ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.uniq)
- description and source-code
```javascript
uniq = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.unique"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unique ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unique)
- description and source-code
```javascript
unique = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.uniqueId"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>uniqueId ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.uniqueId)
- description and source-code
```javascript
uniqueId = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.unquote"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unquote ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unquote)
- description and source-code
```javascript
unquote = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.unshift"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unshift ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unshift)
- description and source-code
```javascript
unshift = function () {
  func.apply(this.__wrapped__, arguments);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.unzip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>unzip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.unzip)
- description and source-code
```javascript
unzip = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.value"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>value ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.value)
- description and source-code
```javascript
function wrapperValueOf() {
  return this.__wrapped__;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.valueOf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>valueOf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.valueOf)
- description and source-code
```javascript
function wrapperValueOf() {
  return this.__wrapped__;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.values"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>values ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.values)
- description and source-code
```javascript
values = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.vsprintf"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>vsprintf ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.vsprintf)
- description and source-code
```javascript
vsprintf = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.where"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>where ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.where)
- description and source-code
```javascript
where = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.without"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>without ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.without)
- description and source-code
```javascript
without = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.words"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>words ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.words)
- description and source-code
```javascript
words = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.wrap"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>wrap ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.wrap)
- description and source-code
```javascript
wrap = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.xor"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>xor ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.xor)
- description and source-code
```javascript
xor = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.zip"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>zip ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.zip)
- description and source-code
```javascript
zip = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.generator-node-webkit.super_.prototype._.prototype.zipObject"></a>[function <span class="apidocSignatureSpan">generator-node-webkit.super_.prototype._.prototype.</span>zipObject ()](#apidoc.element.generator-node-webkit.super_.prototype._.prototype.zipObject)
- description and source-code
```javascript
zipObject = function () {
  var chainAll = this.__chain__,
      value = this.__wrapped__,
      args = [value];

  push.apply(args, arguments);
  var result = func.apply(object, args);
  if (chain || chainAll) {
    if (value === result && isObject(result)) {
      return this;
    }
    result = new ctor(result);
    result.__chain__ = chainAll;
  }
  return result;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
