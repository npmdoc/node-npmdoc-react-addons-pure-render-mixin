# api documentation for  [react-addons-pure-render-mixin (v15.4.2)](https://github.com/facebook/react#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-addons-pure-render-mixin.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-addons-pure-render-mixin) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-addons-pure-render-mixin.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-addons-pure-render-mixin)
#### This package provides the React PureRenderMixin add-on.

[![NPM](https://nodei.co/npm/react-addons-pure-render-mixin.png?downloads=true)](https://www.npmjs.com/package/react-addons-pure-render-mixin)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-addons-pure-render-mixin/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-react-addons-pure-render-mixin_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-addons-pure-render-mixin/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-addons-pure-render-mixin/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-addons-pure-render-mixin/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/facebook/react/issues"
    },
    "dependencies": {
        "fbjs": "^0.8.4",
        "object-assign": "^4.1.0"
    },
    "description": "This package provides the React PureRenderMixin add-on.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "a8433c71c45e2368503721921dc47bdaf1fbabcd",
        "tarball": "https://registry.npmjs.org/react-addons-pure-render-mixin/-/react-addons-pure-render-mixin-15.4.2.tgz"
    },
    "files": [
        "LICENSE",
        "PATENTS",
        "README.md",
        "index.js"
    ],
    "homepage": "https://github.com/facebook/react#readme",
    "keywords": [
        "react",
        "react-addon"
    ],
    "license": "BSD-3-Clause",
    "main": "index.js",
    "maintainers": [
        {
            "name": "fb",
            "email": "opensource+npm@fb.com"
        },
        {
            "name": "gaearon",
            "email": "dan.abramov@gmail.com"
        },
        {
            "name": "graue",
            "email": "scott@oceanbase.org"
        },
        {
            "name": "sebmarkbage",
            "email": "sebastian@calyptus.eu"
        },
        {
            "name": "spicyj",
            "email": "ben@benalpert.com"
        },
        {
            "name": "tomocchino",
            "email": "tomocchino@gmail.com"
        },
        {
            "name": "zpao",
            "email": "paul@oshannessy.com"
        }
    ],
    "name": "react-addons-pure-render-mixin",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.4.2"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/facebook/react.git"
    },
    "scripts": {},
    "version": "15.4.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-addons-pure-render-mixin](#apidoc.module.react-addons-pure-render-mixin)
1.  [function <span class="apidocSignatureSpan">react-addons-pure-render-mixin.</span>shouldComponentUpdate (nextProps, nextState)](#apidoc.element.react-addons-pure-render-mixin.shouldComponentUpdate)



# <a name="apidoc.module.react-addons-pure-render-mixin"></a>[module react-addons-pure-render-mixin](#apidoc.module.react-addons-pure-render-mixin)

#### <a name="apidoc.element.react-addons-pure-render-mixin.shouldComponentUpdate"></a>[function <span class="apidocSignatureSpan">react-addons-pure-render-mixin.</span>shouldComponentUpdate (nextProps, nextState)](#apidoc.element.react-addons-pure-render-mixin.shouldComponentUpdate)
- description and source-code
```javascript
shouldComponentUpdate = function (nextProps, nextState) {
  return shallowCompare(this, nextProps, nextState);
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
