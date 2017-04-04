# api documentation for  [stylelint (v7.10.1)](https://stylelint.io)  [![npm package](https://img.shields.io/npm/v/npmdoc-stylelint.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-stylelint) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-stylelint.svg)](https://travis-ci.org/npmdoc/node-npmdoc-stylelint)
#### A mighty, modern CSS linter.

[![NPM](https://nodei.co/npm/stylelint.png?downloads=true)](https://www.npmjs.com/package/stylelint)

[![apidoc](https://npmdoc.github.io/node-npmdoc-stylelint/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-stylelint_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-stylelint/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-stylelint/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-stylelint/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "David Clark",
        "Maxime Thirouin",
        "Richard Hallows"
    ],
    "bin": {
        "stylelint": "bin/stylelint.js"
    },
    "bugs": {
        "url": "https://github.com/stylelint/stylelint/issues"
    },
    "dependencies": {
        "autoprefixer": "^6.0.0",
        "balanced-match": "^0.4.0",
        "chalk": "^1.1.1",
        "colorguard": "^1.2.0",
        "cosmiconfig": "^2.1.1",
        "debug": "^2.6.0",
        "doiuse": "^2.4.1",
        "execall": "^1.0.0",
        "file-entry-cache": "^2.0.0",
        "get-stdin": "^5.0.0",
        "globby": "^6.0.0",
        "globjoin": "^0.1.4",
        "html-tags": "^1.1.1",
        "ignore": "^3.2.0",
        "imurmurhash": "^0.1.4",
        "known-css-properties": "^0.0.7",
        "lodash": "^4.17.4",
        "log-symbols": "^1.0.2",
        "meow": "^3.3.0",
        "micromatch": "^2.3.11",
        "normalize-selector": "^0.2.0",
        "postcss": "^5.0.20",
        "postcss-less": "^0.14.0",
        "postcss-media-query-parser": "^0.2.0",
        "postcss-reporter": "^3.0.0",
        "postcss-resolve-nested-selector": "^0.1.1",
        "postcss-scss": "^0.4.0",
        "postcss-selector-parser": "^2.1.1",
        "postcss-value-parser": "^3.1.1",
        "resolve-from": "^2.0.0",
        "specificity": "^0.3.0",
        "string-width": "^2.0.0",
        "style-search": "^0.1.0",
        "stylehacks": "^2.3.2",
        "sugarss": "^0.2.0",
        "svg-tags": "^1.0.0",
        "table": "^4.0.1"
    },
    "description": "A mighty, modern CSS linter.",
    "devDependencies": {
        "benchmark": "^2.1.0",
        "common-tags": "^1.3.0",
        "coveralls": "^2.11.16",
        "cp-file": "^4.1.1",
        "d3-queue": "^3.0.3",
        "eslint": "~3.19.0",
        "eslint-config-stylelint": "^6.0.0",
        "file-exists-promise": "^1.0.2",
        "flow-bin": "^0.42.0",
        "fs-promise": "^2.0.0",
        "jest": "^19.0.1",
        "npm-run-all": "^4.0.0",
        "npmpub": "^3.0.1",
        "pify": "^2.3.0",
        "postcss-import": "^9.0.0",
        "postcss-safe-parser": "^2.0.0",
        "remark-cli": "^3.0.0",
        "remark-preset-lint-consistent": "^2.0.0",
        "remark-preset-lint-recommended": "^2.0.0",
        "remark-validate-links": "^6.0.0",
        "request": "^2.69.0",
        "sinon": "^2.0.0",
        "strip-ansi": "^3.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "209a7ce5e781fc2a62489fbb31ec0201ec675db2",
        "tarball": "https://registry.npmjs.org/stylelint/-/stylelint-7.10.1.tgz"
    },
    "engines": {
        "node": ">=4.2.1"
    },
    "eslintConfig": {
        "extends": [
            "stylelint"
        ],
        "globals": {
            "testRule": true
        }
    },
    "files": [
        "bin",
        "CONTRIBUTING.md",
        "decls/*.js",
        "docs",
        "lib",
        "!**/__tests__"
    ],
    "gitHead": "d76c6d1358917fe06f56710f71ddfc32ebd6b759",
    "greenkeeper": {
        "label": "PR: review needed"
    },
    "homepage": "https://stylelint.io",
    "jest": {
        "collectCoverage": false,
        "collectCoverageFrom": [
            "lib/**/*.js"
        ],
        "coverageDirectory": "./.coverage/",
        "coverageReporters": [
            "lcov",
            "text-summary"
        ],
        "coverageThreshold": {
            "global": {
                "branches": 75,
                "functions": 75,
                "lines": 75,
                "statements": 75
            }
        },
        "setupFiles": [
            "./jest-setup.js"
        ],
        "testEnvironment": "node",
        "roots": [
            "lib",
            "system-tests"
        ],
        "testRegex": ".*\\.test\\.js$|rules/.*/__tests__/.*\\.js$"
    },
    "keywords": [
        "css",
        "less",
        "scss",
        "sugarss",
        "lint",
        "linter",
        "stylelint"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "davidtheclark",
            "email": "david.dave.clark@gmail.com"
        },
        {
            "name": "jeddy3",
            "email": "npm@richardhallows.com"
        },
        {
            "name": "moox",
            "email": "m@moox.io"
        }
    ],
    "name": "stylelint",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "remarkConfig": {
        "plugins": [
            "preset-lint-recommended",
            "preset-lint-consistent",
            [
                "validate-links",
                {
                    "repository": "stylelint/stylelint"
                }
            ]
        ]
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/stylelint/stylelint.git"
    },
    "scripts": {
        "benchmark-rule": "node scripts/benchmark-rule.js",
        "flow": "flow",
        "jest": "jest",
        "lint": "npm-run-all --parallel lint:*",
        "lint:js": "eslint . --cache",
        "lint:md": "remark . --quiet --frail",
        "pretest": "npm-run-all --serial lint flow",
        "release": "npmpub",
        "test": "jest --coverage",
        "watch": "jest --watch"
    },
    "version": "7.10.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module stylelint](#apidoc.module.stylelint)
1.  [function <span class="apidocSignatureSpan">stylelint.</span>createLinter (options)](#apidoc.element.stylelint.createLinter)
1.  [function <span class="apidocSignatureSpan">stylelint.</span>createPlugin (ruleName, rule)](#apidoc.element.stylelint.createPlugin)
1.  [function <span class="apidocSignatureSpan">stylelint.</span>createRuleTester (equalityCheck)](#apidoc.element.stylelint.createRuleTester)
1.  [function <span class="apidocSignatureSpan">stylelint.</span>lint (options)](#apidoc.element.stylelint.lint)
1.  [function <span class="apidocSignatureSpan">stylelint.</span>process (root, opts)](#apidoc.element.stylelint.process)
1.  object <span class="apidocSignatureSpan">stylelint.</span>augmentConfig
1.  object <span class="apidocSignatureSpan">stylelint.</span>formatters
1.  object <span class="apidocSignatureSpan">stylelint.</span>rules
1.  object <span class="apidocSignatureSpan">stylelint.</span>utils

#### [module stylelint.augmentConfig](#apidoc.module.stylelint.augmentConfig)
1.  [function <span class="apidocSignatureSpan">stylelint.augmentConfig.</span>augmentConfigExtended ( stylelint, cosmiconfigResultArg )](#apidoc.element.stylelint.augmentConfig.augmentConfigExtended)
1.  [function <span class="apidocSignatureSpan">stylelint.augmentConfig.</span>augmentConfigFull ( stylelint, cosmiconfigResultArg )](#apidoc.element.stylelint.augmentConfig.augmentConfigFull)

#### [module stylelint.formatters](#apidoc.module.stylelint.formatters)
1.  [function <span class="apidocSignatureSpan">stylelint.formatters.</span>json (results)](#apidoc.element.stylelint.formatters.json)
1.  [function <span class="apidocSignatureSpan">stylelint.formatters.</span>string (results)](#apidoc.element.stylelint.formatters.string)
1.  [function <span class="apidocSignatureSpan">stylelint.formatters.</span>verbose (results)](#apidoc.element.stylelint.formatters.verbose)

#### [module stylelint.rules](#apidoc.module.stylelint.rules)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-blacklist (blacklistInput)](#apidoc.element.stylelint.rules.at-rule-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.at-rule-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-name-case (expectation)](#apidoc.element.stylelint.rules.at-rule-name-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-name-newline-after (expectation)](#apidoc.element.stylelint.rules.at-rule-name-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-name-space-after (expectation)](#apidoc.element.stylelint.rules.at-rule-name-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-no-unknown (actual, options)](#apidoc.element.stylelint.rules.at-rule-no-unknown)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.at-rule-no-vendor-prefix)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-semicolon-newline-after (actual)](#apidoc.element.stylelint.rules.at-rule-semicolon-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-semicolon-space-before (expectation)](#apidoc.element.stylelint.rules.at-rule-semicolon-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-whitelist (whitelistInput)](#apidoc.element.stylelint.rules.at-rule-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-empty-line-before (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-newline-after (expectation, options)](#apidoc.element.stylelint.rules.block-closing-brace-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-newline-before (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-newline-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-space-after (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-space-before (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-no-empty (actual)](#apidoc.element.stylelint.rules.block-no-empty)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-no-single-line (actual)](#apidoc.element.stylelint.rules.block-no-single-line)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-newline-after (expectation)](#apidoc.element.stylelint.rules.block-opening-brace-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-newline-before (expectation)](#apidoc.element.stylelint.rules.block-opening-brace-newline-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-space-after (expectation)](#apidoc.element.stylelint.rules.block-opening-brace-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-space-before (expectation, options)](#apidoc.element.stylelint.rules.block-opening-brace-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>color-hex-case (expectation)](#apidoc.element.stylelint.rules.color-hex-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>color-hex-length (expectation)](#apidoc.element.stylelint.rules.color-hex-length)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>color-named (expectation, options)](#apidoc.element.stylelint.rules.color-named)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>color-no-hex (actual)](#apidoc.element.stylelint.rules.color-no-hex)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>color-no-invalid-hex (actual)](#apidoc.element.stylelint.rules.color-no-invalid-hex)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.comment-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-no-empty (actual)](#apidoc.element.stylelint.rules.comment-no-empty)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-whitespace-inside (expectation)](#apidoc.element.stylelint.rules.comment-whitespace-inside)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-word-blacklist (blacklist)](#apidoc.element.stylelint.rules.comment-word-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-media-pattern (pattern)](#apidoc.element.stylelint.rules.custom-media-pattern)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-property-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.custom-property-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-property-no-outside-root (actual)](#apidoc.element.stylelint.rules.custom-property-no-outside-root)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-property-pattern (pattern)](#apidoc.element.stylelint.rules.custom-property-pattern)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-bang-space-after (expectation)](#apidoc.element.stylelint.rules.declaration-bang-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-bang-space-before (expectation)](#apidoc.element.stylelint.rules.declaration-bang-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-duplicate-properties (on, options)](#apidoc.element.stylelint.rules.declaration-block-no-duplicate-properties)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-ignored-properties (actual)](#apidoc.element.stylelint.rules.declaration-block-no-ignored-properties)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-redundant-longhand-properties (actual, options)](#apidoc.element.stylelint.rules.declaration-block-no-redundant-longhand-properties)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-shorthand-property-overrides (actual)](#apidoc.element.stylelint.rules.declaration-block-no-shorthand-property-overrides)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-properties-order (expectation, options)](#apidoc.element.stylelint.rules.declaration-block-properties-order)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-newline-after (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-newline-before (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-newline-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-space-after (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-space-before (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-single-line-max-declarations (quantity)](#apidoc.element.stylelint.rules.declaration-block-single-line-max-declarations)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-trailing-semicolon (expectation)](#apidoc.element.stylelint.rules.declaration-block-trailing-semicolon)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-colon-newline-after (expectation)](#apidoc.element.stylelint.rules.declaration-colon-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-colon-space-after (expectation)](#apidoc.element.stylelint.rules.declaration-colon-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-colon-space-before (expectation)](#apidoc.element.stylelint.rules.declaration-colon-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.declaration-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-no-important (actual)](#apidoc.element.stylelint.rules.declaration-no-important)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-unit-blacklist (blacklist)](#apidoc.element.stylelint.rules.declaration-property-unit-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-unit-whitelist (whitelist)](#apidoc.element.stylelint.rules.declaration-property-unit-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-value-blacklist (blacklist)](#apidoc.element.stylelint.rules.declaration-property-value-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-value-whitelist (whitelist)](#apidoc.element.stylelint.rules.declaration-property-value-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>font-family-name-quotes (expectation)](#apidoc.element.stylelint.rules.font-family-name-quotes)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>font-family-no-duplicate-names (actual, options)](#apidoc.element.stylelint.rules.font-family-no-duplicate-names)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>font-weight-notation (expectation, options)](#apidoc.element.stylelint.rules.font-weight-notation)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-blacklist (blacklist)](#apidoc.element.stylelint.rules.function-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-calc-no-unspaced-operator (actual)](#apidoc.element.stylelint.rules.function-calc-no-unspaced-operator)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.function-comma-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.function-comma-newline-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-space-after (expectation)](#apidoc.element.stylelint.rules.function-comma-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-space-before (expectation)](#apidoc.element.stylelint.rules.function-comma-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-linear-gradient-no-nonstandard-direction (actual)](#apidoc.element.stylelint.rules.function-linear-gradient-no-nonstandard-direction)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-max-empty-lines (max)](#apidoc.element.stylelint.rules.function-max-empty-lines)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-name-case (expectation, options)](#apidoc.element.stylelint.rules.function-name-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-parentheses-newline-inside (expectation)](#apidoc.element.stylelint.rules.function-parentheses-newline-inside)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-parentheses-space-inside (expectation)](#apidoc.element.stylelint.rules.function-parentheses-space-inside)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-data-uris (expectation)](#apidoc.element.stylelint.rules.function-url-data-uris)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-no-scheme-relative (actual)](#apidoc.element.stylelint.rules.function-url-no-scheme-relative)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-quotes (expectation, options)](#apidoc.element.stylelint.rules.function-url-quotes)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-scheme-whitelist (whitelist)](#apidoc.element.stylelint.rules.function-url-scheme-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-whitelist (whitelistInput)](#apidoc.element.stylelint.rules.function-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>function-whitespace-after (expectation)](#apidoc.element.stylelint.rules.function-whitespace-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>indentation (space)](#apidoc.element.stylelint.rules.indentation)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>keyframe-declaration-no-important (actual)](#apidoc.element.stylelint.rules.keyframe-declaration-no-important)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>length-zero-no-unit (actual)](#apidoc.element.stylelint.rules.length-zero-no-unit)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>max-empty-lines (max, options)](#apidoc.element.stylelint.rules.max-empty-lines)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>max-line-length (maxLength, options)](#apidoc.element.stylelint.rules.max-line-length)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>max-nesting-depth (max, options)](#apidoc.element.stylelint.rules.max-nesting-depth)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-colon-space-after (expectation)](#apidoc.element.stylelint.rules.media-feature-colon-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-colon-space-before (expectation)](#apidoc.element.stylelint.rules.media-feature-colon-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-blacklist (blacklist)](#apidoc.element.stylelint.rules.media-feature-name-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-case (expectation)](#apidoc.element.stylelint.rules.media-feature-name-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-no-unknown (actual, options)](#apidoc.element.stylelint.rules.media-feature-name-no-unknown)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.media-feature-name-no-vendor-prefix)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-whitelist (whitelist)](#apidoc.element.stylelint.rules.media-feature-name-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-no-missing-punctuation (actual)](#apidoc.element.stylelint.rules.media-feature-no-missing-punctuation)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-parentheses-space-inside (expectation)](#apidoc.element.stylelint.rules.media-feature-parentheses-space-inside)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-range-operator-space-after (expectation)](#apidoc.element.stylelint.rules.media-feature-range-operator-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-range-operator-space-before (expectation)](#apidoc.element.stylelint.rules.media-feature-range-operator-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-newline-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-space-after (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-space-before (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-browser-hacks (on, options)](#apidoc.element.stylelint.rules.no-browser-hacks)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-descending-specificity (actual)](#apidoc.element.stylelint.rules.no-descending-specificity)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-duplicate-selectors (actual)](#apidoc.element.stylelint.rules.no-duplicate-selectors)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-empty-source (actual)](#apidoc.element.stylelint.rules.no-empty-source)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-eol-whitespace (on, options)](#apidoc.element.stylelint.rules.no-eol-whitespace)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-extra-semicolons (actual)](#apidoc.element.stylelint.rules.no-extra-semicolons)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-indistinguishable-colors (on, options)](#apidoc.element.stylelint.rules.no-indistinguishable-colors)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-invalid-double-slash-comments (actual)](#apidoc.element.stylelint.rules.no-invalid-double-slash-comments)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-missing-end-of-source-newline (actual)](#apidoc.element.stylelint.rules.no-missing-end-of-source-newline)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-unknown-animations (actual)](#apidoc.element.stylelint.rules.no-unknown-animations)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>no-unsupported-browser-features (on, options)](#apidoc.element.stylelint.rules.no-unsupported-browser-features)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>number-leading-zero (expectation)](#apidoc.element.stylelint.rules.number-leading-zero)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>number-max-precision (precision)](#apidoc.element.stylelint.rules.number-max-precision)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>number-no-trailing-zeros (actual)](#apidoc.element.stylelint.rules.number-no-trailing-zeros)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>property-blacklist (blacklist)](#apidoc.element.stylelint.rules.property-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>property-case (expectation)](#apidoc.element.stylelint.rules.property-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>property-no-unknown (actual, options)](#apidoc.element.stylelint.rules.property-no-unknown)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>property-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.property-no-vendor-prefix)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>property-whitelist (whitelist)](#apidoc.element.stylelint.rules.property-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>root-no-standard-properties (actual)](#apidoc.element.stylelint.rules.root-no-standard-properties)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>rule-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.rule-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>rule-nested-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.rule-nested-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>rule-non-nested-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.rule-non-nested-empty-line-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-brackets-space-inside (expectation)](#apidoc.element.stylelint.rules.selector-attribute-brackets-space-inside)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-blacklist (blacklistInput)](#apidoc.element.stylelint.rules.selector-attribute-operator-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-space-after (expectation)](#apidoc.element.stylelint.rules.selector-attribute-operator-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-space-before (expectation)](#apidoc.element.stylelint.rules.selector-attribute-operator-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-whitelist (whitelistInput)](#apidoc.element.stylelint.rules.selector-attribute-operator-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-quotes (expectation)](#apidoc.element.stylelint.rules.selector-attribute-quotes)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-class-pattern (pattern, options)](#apidoc.element.stylelint.rules.selector-class-pattern)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-combinator-space-after (expectation)](#apidoc.element.stylelint.rules.selector-combinator-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-combinator-space-before (expectation)](#apidoc.element.stylelint.rules.selector-combinator-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-descendant-combinator-no-non-space (actual)](#apidoc.element.stylelint.rules.selector-descendant-combinator-no-non-space)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-id-pattern (pattern)](#apidoc.element.stylelint.rules.selector-id-pattern)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-newline-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-space-after (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-space-before (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-max-compound-selectors (max)](#apidoc.element.stylelint.rules.selector-max-compound-selectors)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-max-empty-lines (max)](#apidoc.element.stylelint.rules.selector-max-empty-lines)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-max-specificity (max)](#apidoc.element.stylelint.rules.selector-max-specificity)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-nested-pattern (pattern)](#apidoc.element.stylelint.rules.selector-nested-pattern)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-attribute (actual)](#apidoc.element.stylelint.rules.selector-no-attribute)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-combinator (actual)](#apidoc.element.stylelint.rules.selector-no-combinator)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-empty (actual)](#apidoc.element.stylelint.rules.selector-no-empty)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-id (actual)](#apidoc.element.stylelint.rules.selector-no-id)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-qualifying-type (enabled, options)](#apidoc.element.stylelint.rules.selector-no-qualifying-type)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-type (on, options)](#apidoc.element.stylelint.rules.selector-no-type)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-universal (actual)](#apidoc.element.stylelint.rules.selector-no-universal)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.selector-no-vendor-prefix)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-blacklist (blacklist)](#apidoc.element.stylelint.rules.selector-pseudo-class-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-case (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-class-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-no-unknown (actual, options)](#apidoc.element.stylelint.rules.selector-pseudo-class-no-unknown)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-parentheses-space-inside (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-class-parentheses-space-inside)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-whitelist (whitelist)](#apidoc.element.stylelint.rules.selector-pseudo-class-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-element-case (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-element-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-element-colon-notation (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-element-colon-notation)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-element-no-unknown (actual, options)](#apidoc.element.stylelint.rules.selector-pseudo-element-no-unknown)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-root-no-composition (actual)](#apidoc.element.stylelint.rules.selector-root-no-composition)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-type-case (expectation)](#apidoc.element.stylelint.rules.selector-type-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-type-no-unknown (actual, options)](#apidoc.element.stylelint.rules.selector-type-no-unknown)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>shorthand-property-no-redundant-values (actual)](#apidoc.element.stylelint.rules.shorthand-property-no-redundant-values)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>string-no-newline (actual)](#apidoc.element.stylelint.rules.string-no-newline)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>string-quotes (expectation)](#apidoc.element.stylelint.rules.string-quotes)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>stylelint-disable-reason (expectation)](#apidoc.element.stylelint.rules.stylelint-disable-reason)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>time-min-milliseconds (minimum)](#apidoc.element.stylelint.rules.time-min-milliseconds)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>time-no-imperceptible (actual)](#apidoc.element.stylelint.rules.time-no-imperceptible)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-blacklist (blacklistInput, options)](#apidoc.element.stylelint.rules.unit-blacklist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-case (expectation)](#apidoc.element.stylelint.rules.unit-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-no-unknown (actual, options)](#apidoc.element.stylelint.rules.unit-no-unknown)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-whitelist (whitelistInput, options)](#apidoc.element.stylelint.rules.unit-whitelist)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>value-keyword-case (expectation, options)](#apidoc.element.stylelint.rules.value-keyword-case)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.value-list-comma-newline-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.value-list-comma-newline-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-space-after (expectation)](#apidoc.element.stylelint.rules.value-list-comma-space-after)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-space-before (expectation)](#apidoc.element.stylelint.rules.value-list-comma-space-before)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-max-empty-lines (max)](#apidoc.element.stylelint.rules.value-list-max-empty-lines)
1.  [function <span class="apidocSignatureSpan">stylelint.rules.</span>value-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.value-no-vendor-prefix)

#### [module stylelint.utils](#apidoc.module.stylelint.utils)
1.  [function <span class="apidocSignatureSpan">stylelint.utils.</span>checkAgainstRule ( options, callback )](#apidoc.element.stylelint.utils.checkAgainstRule)
1.  [function <span class="apidocSignatureSpan">stylelint.utils.</span>report (violation)](#apidoc.element.stylelint.utils.report)
1.  [function <span class="apidocSignatureSpan">stylelint.utils.</span>ruleMessages ( ruleName, messages )](#apidoc.element.stylelint.utils.ruleMessages)
1.  [function <span class="apidocSignatureSpan">stylelint.utils.</span>validateOptions ( result, ruleName )](#apidoc.element.stylelint.utils.validateOptions)



# <a name="apidoc.module.stylelint"></a>[module stylelint](#apidoc.module.stylelint)

#### <a name="apidoc.element.stylelint.createLinter"></a>[function <span class="apidocSignatureSpan">stylelint.</span>createLinter (options)](#apidoc.element.stylelint.createLinter)
- description and source-code
```javascript
createLinter = function (options)/*: stylelint$internalApi*/ {
  options = options || {}
  const stylelint/*: Object*/ = { _options: options }

  // Two separate explorers so they can each have their own transform
  // function whose results are cached by cosmiconfig
  stylelint._fullExplorer = cosmiconfig("stylelint", {
    argv: false,
    rcExtensions: true,
    transform: _.partial(augmentConfig.augmentConfigFull, stylelint),
  })
  stylelint._extendExplorer = cosmiconfig(null, {
    argv: false,
    transform: _.partial(augmentConfig.augmentConfigExtended, stylelint),
  })

  stylelint._specifiedConfigCache = new Map()
  stylelint._postcssResultCache = new Map()
  stylelint._createStylelintResult = _.partial(createStylelintResult, stylelint)
  stylelint._getPostcssResult = _.partial(getPostcssResult, stylelint)
  stylelint._lintSource = _.partial(lintSource, stylelint)

  stylelint.getConfigForFile = _.partial(getConfigForFile, stylelint)
  stylelint.isPathIgnored = _.partial(isPathIgnored, stylelint)

  return stylelint
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.createPlugin"></a>[function <span class="apidocSignatureSpan">stylelint.</span>createPlugin (ruleName, rule)](#apidoc.element.stylelint.createPlugin)
- description and source-code
```javascript
createPlugin = function (ruleName, rule) {
  return {
    ruleName,
    rule,
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.createRuleTester"></a>[function <span class="apidocSignatureSpan">stylelint.</span>createRuleTester (equalityCheck)](#apidoc.element.stylelint.createRuleTester)
- description and source-code
```javascript
createRuleTester = function (equalityCheck) {
  return function (rule, schema) {
    const alreadyHadOnlyTest = !!onlyTest
    if (schema.accept) {
      schema.accept.forEach(_.partial(checkCaseForOnly, "accept"))
    }

    if (schema.reject) {
      schema.reject.forEach(_.partial(checkCaseForOnly, "reject"))
    }

    if (onlyTest) {
      schema = _.assign(_.omit(schema, [ "accept", "reject" ]), {
        skipBasicChecks: true,
        [onlyTest.type]: [onlyTest.case],
      })
    }

    if (!alreadyHadOnlyTest) {
      process.nextTick(() => {
        processGroup(rule, schema, equalityCheck)
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.lint"></a>[function <span class="apidocSignatureSpan">stylelint.</span>lint (options)](#apidoc.element.stylelint.lint)
- description and source-code
```javascript
lint = function (options)/*: Promise<stylelint$standaloneReturnValue>*/ {
  const files = options.files
  const code = options.code
  const codeFilename = options.codeFilename
  const config = options.config
  const configFile = options.configFile
  const configBasedir = options.configBasedir
  const configOverrides = options.configOverrides
  const ignoreDisables = options.ignoreDisables
  const ignorePath = options.ignorePath
  const reportNeedlessDisables = options.reportNeedlessDisables
  const formatter = options.formatter
  const syntax = options.syntax
  const customSyntax = options.customSyntax
  const allowEmptyInput = options.allowEmptyInput
  const cacheLocation = options.cacheLocation
  const useCache = options.cache || false
  let fileCache

  const startTime = Date.now()

  const isValidCode = typeof code === "string"
  if (!files && !isValidCode || files && (code || isValidCode)) {
    throw new Error("You must pass stylelint a 'files' glob or a 'code' string, though not both")
  }

  let formatterFunction
  if (typeof formatter === "string") {
    formatterFunction = formatters[formatter]
    if (formatterFunction === undefined) {
      return Promise.reject(new Error("You must use a valid formatter option: 'json', 'string', 'verbose', or a function"))
    }
  } else if (typeof formatter === "function") {
    formatterFunction = formatter
  } else {
    formatterFunction = formatters.json
  }

  const stylelint = createStylelint({
    config,
    configFile,
    configBasedir,
    configOverrides,
    ignoreDisables,
    ignorePath,
    reportNeedlessDisables,
    syntax,
    customSyntax,
  })

  if (!files) {
    const absoluteCodeFilename = (codeFilename !== undefined && !path.isAbsolute(codeFilename))
      ? path.join(process.cwd(), codeFilename)
      : codeFilename
    return stylelint._lintSource({
      code,
      codeFilename: absoluteCodeFilename,
    }).then(postcssResult => {
      return stylelint._createStylelintResult(postcssResult)
    }).catch(handleError).then(stylelintResult => {
      return prepareReturnValue([stylelintResult])
    })
  }

  let fileList = files
  if (typeof fileList === "string") {
    fileList = [fileList]
  }
  fileList = fileList.concat(
    alwaysIgnoredGlobs.map(file => "!" + file)
  )

  if (useCache) {
    const stylelintVersion = pkg.version
    const hashOfConfig = hash('${stylelintVersion}_${JSON.stringify(config)}')
    fileCache = new FileCache(cacheLocation, hashOfConfig)
  } else {
    // No need to calculate hash here, we just want to delete cache file.
    fileCache = new FileCache(cacheLocation)
    // Remove cache file if cache option is disabled
    fileCache.destroy()
  }

  return globby(fileList).then(filePaths => {
    if (!filePaths.length) {
      if (allowEmptyInput === undefined || !allowEmptyInput) {
        const message = (files => {
          if (typeof files === "string") {
            return '${files} does'
          }
          // seperate files into last (last file) and initial) all the others
          const initial = files.slice(0)
          const last = initial.pop()
          // join into a comma seperated string of file names
          const ending = (files.length > 1 ? 'and ${last} do' : '${last} does')
          return '${initial.join(", ")} ${ending}'.trim()
        })(files) + " not match any files"

        const err/*: Object*/ = new Error(message)
        err.code = 80
        throw err
      } else {
        return Promise.all([])
      }
    }

    let absoluteFilePaths = filePaths.map(filePath => {
      const absoluteFilepath = (!path.isAbsolute(filePath))
        ? path.join(process.cwd(), filePath)
        : path.normalize(filePath)
      return absoluteFilepath
    })

    if (useCache) {
      absoluteFilePaths = absoluteFilePaths.filter(fileCache.hasFileChanged.bind(fileCache))
    }

    const getStylelintResults = absoluteFilePaths.map(absoluteFilepath => {
      debug('Processing ${absoluteFilepath}')
      return stylelint._lintSource({
        filePath: absoluteFilepath,
      } ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.process"></a>[function <span class="apidocSignatureSpan">stylelint.</span>process (root, opts)](#apidoc.element.stylelint.process)
- description and source-code
```javascript
process = function (root, opts) {
  return postcss([creator(opts)]).process(root, opts);
}
```
- example usage
```shell
...
    let preProcessedCode = code
    if (options.codeProcessors) {
      options.codeProcessors.forEach(codeProcessor => {
        preProcessedCode = codeProcessor(preProcessedCode, source)
      })
    }

    return postcssProcessor.process(preProcessedCode, postcssOptions)
  }).then(postcssResult => {
    stylelint._postcssResultCache.set(options.filePath, postcssResult)
    return postcssResult
  })
}

function readFile(filePath/*: string*/)/*: Promise<string>*/ {
...
```



# <a name="apidoc.module.stylelint.augmentConfig"></a>[module stylelint.augmentConfig](#apidoc.module.stylelint.augmentConfig)

#### <a name="apidoc.element.stylelint.augmentConfig.augmentConfigExtended"></a>[function <span class="apidocSignatureSpan">stylelint.augmentConfig.</span>augmentConfigExtended ( stylelint, cosmiconfigResultArg )](#apidoc.element.stylelint.augmentConfig.augmentConfigExtended)
- description and source-code
```javascript
function augmentConfigExtended( stylelint, cosmiconfigResultArg )/*: Promise<?{ config: stylelint$config, filepath: string }>*/ {
  const cosmiconfigResult = cosmiconfigResultArg // Lock in for Flow
  if (!cosmiconfigResult) return Promise.resolve(null)

  const configDir = path.dirname(cosmiconfigResult.filepath || "")
  const cleanedConfig = _.omit(cosmiconfigResult.config, "ignoreFiles")
  return augmentConfigBasic(stylelint, cleanedConfig, configDir).then(augmentedConfig => {
    return {
      config: augmentedConfig,
      filepath: cosmiconfigResult.filepath,
    }
  })
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.augmentConfig.augmentConfigFull"></a>[function <span class="apidocSignatureSpan">stylelint.augmentConfig.</span>augmentConfigFull ( stylelint, cosmiconfigResultArg )](#apidoc.element.stylelint.augmentConfig.augmentConfigFull)
- description and source-code
```javascript
function augmentConfigFull( stylelint, cosmiconfigResultArg )/*: Promise<?{ config: stylelint$config, filepath: string }>*/ {
  const cosmiconfigResult = cosmiconfigResultArg // Lock in for Flow
  if (!cosmiconfigResult) return Promise.resolve(null)

  const config = cosmiconfigResult.config,
    filepath = cosmiconfigResult.filepath

  const configDir = stylelint._options.configBasedir || path.dirname(filepath || "")

  return augmentConfigBasic(stylelint, config, configDir, true).then(augmentedConfig => {
    return addIgnorePatterns(stylelint, augmentedConfig)
  }).then(augmentedConfig => {
    return addPluginFunctions(augmentedConfig)
  }).then(augmentedConfig => {
    return addProcessorFunctions(augmentedConfig)
  }).then(augmentedConfig => {
    if (!augmentedConfig.rules) {
      throw configurationError("No rules found within configuration. Have you provided a \"rules\" property?")
    }

    return normalizeAllRuleSettings(augmentedConfig)
  }).then(augmentedConfig => {
    return {
      config: augmentedConfig,
      filepath: cosmiconfigResult.filepath,
    }
  })
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stylelint.formatters"></a>[module stylelint.formatters](#apidoc.module.stylelint.formatters)

#### <a name="apidoc.element.stylelint.formatters.json"></a>[function <span class="apidocSignatureSpan">stylelint.formatters.</span>json (results)](#apidoc.element.stylelint.formatters.json)
- description and source-code
```javascript
json = function (results) {
  const cleanedResults = results.map(result => {
    return _.omitBy(result, (value, key) => key[0] === "_")
  })
  return JSON.stringify(cleanedResults)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.formatters.string"></a>[function <span class="apidocSignatureSpan">stylelint.formatters.</span>string (results)](#apidoc.element.stylelint.formatters.string)
- description and source-code
```javascript
string = function (results) {
  let output = invalidOptionsFormatter(results)
  output += deprecationsFormatter(results)

  output = results.reduce((output, result) => {
    output += formatter(result.warnings, result.source)
    return output
  }, output)

  // Ensure consistent padding
  output = output.trim()

  if (output !== "") {
    output = "\n" + output + "\n\n"
  }

  return output
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.formatters.verbose"></a>[function <span class="apidocSignatureSpan">stylelint.formatters.</span>verbose (results)](#apidoc.element.stylelint.formatters.verbose)
- description and source-code
```javascript
verbose = function (results) {
  let output = stringFormatter(results)

  if (output === "") {
    output = "\n"
  }

  const sourceWord = results.length > 1 ? "sources" : "source"
  const ignoredCount = results.filter(result => result.ignored).length
  const checkedDisplay = ignoredCount ? '${results.length - ignoredCount} of ${results.length}' : results.length
  output += chalk.underline('${checkedDisplay} ${sourceWord} checked\n')
  results.forEach(result => {
    let formatting = "green"
    if (result.errored) {
      formatting = "red"
    } else if (result.warnings.length) {
      formatting = "yellow"
    } else if (result.ignored) {
      formatting = "dim"
    }
    let sourceText = '${result.source}'
    if (result.ignored) {
      sourceText += " (ignored)"
    }
    output += _.get(chalk, formatting)(' ${sourceText}\n')
  })

  const warnings = _.flatten(results.map(r => r.warnings))
  const warningsBySeverity = _.groupBy(warnings, "severity")
  const problemWord = warnings.length === 1 ? "problem" : "problems"

  output += chalk.underline('\n${warnings.length} ${problemWord} found\n')

  _.forOwn(warningsBySeverity, (warningList, severityLevel) => {
    const warningsByRule = _.groupBy(warningList, "rule")
    output += ' severity level "${severityLevel}": ${warningList.length}\n'
    _.forOwn(warningsByRule, (list, rule) => {
      output += chalk.dim('  ${rule}: ${list.length}\n')
    })
  })

  return output + "\n"
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stylelint.rules"></a>[module stylelint.rules](#apidoc.module.stylelint.rules)

#### <a name="apidoc.element.stylelint.rules.at-rule-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-blacklist (blacklistInput)](#apidoc.element.stylelint.rules.at-rule-blacklist)
- description and source-code
```javascript
at-rule-blacklist = function (blacklistInput) {
  // To allow for just a string as a parameter (not only arrays of strings)
  const blacklist = [].concat(blacklistInput)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      const name = atRule.name

      if (blacklist.indexOf(postcss.vendor.unprefixed(name).toLowerCase()) === -1) {
        return
      }

      report({
        message: messages.rejected(name),
        node: atRule,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.at-rule-empty-line-before)
- description and source-code
```javascript
at-rule-empty-line-before = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    }, {
      actual: options,
      possible: {
        except: [
          "after-same-name",
          "all-nested",
          "inside-block",
          "blockless-after-same-name-blockless",
          "blockless-group",
          "blockless-after-blockless",
          "first-nested",
        ],
        ignore: [
          "after-comment",
          "all-nested",
          "inside-block",
          "blockless-after-same-name-blockless",
          "blockless-group",
          "blockless-after-blockless",
        ],
        ignoreAtRules: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    if (
      optionsMatches(options, "ignore", "all-nested")
      || optionsMatches(options, "except", "all-nested")
    ) {
      result.warn((
        "'at-rule-empty-line-before\'s' \"all-nested\" option has been deprecated and in 8.0 will be removed. " +
        "Instead use the \"inside-block\" option."
      ), {
        stylelintType: "deprecation",
        stylelintReference: "https://stylelint.io/user-guide/rules/at-rule-empty-line-before/",
      })
    }

    if (
      optionsMatches(options, "ignore", "blockless-group")
      || optionsMatches(options, "except", "blockless-group")
    ) {
      result.warn((
        "'at-rule-empty-line-before\'s' \"blockless-group\" option has been deprecated and in 8.0 will be removed. " +
        "Instead use the \"blockless-after-blockless\" option."
      ), {
        stylelintType: "deprecation",
        stylelintReference: "https://stylelint.io/user-guide/rules/at-rule-empty-line-before/",
      })
    }

    root.walkAtRules(atRule => {
      // Ignore the first node
      if (atRule === root.first) {
        return
      }

      // Return early if at-rule is to be ignored
      if (optionsMatches(options, "ignoreAtRules", atRule.name)) {
        return
      }

      // Optionally ignore the expectation if the node is blockless
      if (
        optionsMatches(options, "ignore", "blockless-group")
        && !hasBlock(atRule)
        || optionsMatches(options, "ignore", "blockless-after-blockless")
        && !hasBlock(atRule)
      ) {
        return
      }

      const isNested = atRule.parent !== root
      const previousNode = atRule.prev()

      // Optionally ignore the expection if the node is blockless
      // and following another blockless at-rule with the same name
      if (
        optionsMatches(options, "ignore", "blockless-after-same-name-blockless")
        && isBlocklessAfterSameNameBlockless()
      ) {
        return
      }

      // Optionally ignore the expectation if the node is inside a block
      if (
        optionsMatches(options, "ignore", "all-nested")
        && isNested
        || optionsMatches(options, "ignore", "inside-block")
        && isNested
      ) {
        return
      }

      // Optionally ignore the expectation if a comment precedes this node
      if (
        optionsMatches(options, "ignore", "after-comment")
        && isAfterComment()
      ) {
        return
      }

      const hasEmptyLineBefore = hasEmptyLine(atRule.raws.before)
      let expectEmptyLineBefore = expectation === "always"
        ? true
        : false

      // Optionally reverse the expectation if any exceptions apply
      if (
        optionsMatches(options, "except", "after-same-name")
        && isAfterSameName()
        || optionsMatches(options, "except", "all-nested")
        && isNested
        || optionsMatches(options, "except", "inside-block")
        && isNested
        || optionsMatches(options, "except", "first-nested")
        && isFirstNested()
        || optionsMatches(options, "except", "blockless-group")
        && isBlocklessAfterBlockless()
        || optionsMatches(options, "except", "blockless-after-blockless")
        && isBlocklessAfterBlockless()
        || optionsMatches( ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-name-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-name-case (expectation)](#apidoc.element.stylelint.rules.at-rule-name-case)
- description and source-code
```javascript
at-rule-name-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      const name = atRule.name

      const expectedName = expectation === "lower"
        ? name.toLowerCase()
        : name.toUpperCase()

      if (name === expectedName) {
        return
      }

      report({
        message: messages.expected(name, expectedName),
        node: atRule,
        ruleName,
        result,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-name-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-name-newline-after (expectation)](#apidoc.element.stylelint.rules.at-rule-name-newline-after)
- description and source-code
```javascript
at-rule-name-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    atRuleNameSpaceChecker({
      root,
      result,
      locationChecker: checker.afterOneOnly,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-name-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-name-space-after (expectation)](#apidoc.element.stylelint.rules.at-rule-name-space-after)
- description and source-code
```javascript
at-rule-name-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    atRuleNameSpaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-no-unknown"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-no-unknown (actual, options)](#apidoc.element.stylelint.rules.at-rule-no-unknown)
- description and source-code
```javascript
at-rule-no-unknown = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignoreAtRules: [_.isString],
      },
      optional: true,
    })

    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      const name = atRule.name

      // Return early if at-rule is to be ignored
      if (optionsMatches(options, "ignoreAtRules", atRule.name)) {
        return
      }

      if (
        postcss.vendor.prefix(name)
        || keywordSets.atRules.has(name.toLowerCase())
      ) {
        return
      }

      report({
        message: messages.rejected('@${name}'),
        node: atRule,
        ruleName,
        result,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-no-vendor-prefix"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.at-rule-no-vendor-prefix)
- description and source-code
```javascript
at-rule-no-vendor-prefix = function (actual) {
  return function (root, result) {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      if (!isStandardSyntaxAtRule(atRule)) {
        return
      }

      const name = atRule.name

      if (name[0] !== "-") {
        return
      }

      if (!isAutoprefixable.atRuleName(name)) {
        return
      }

      report({
        message: messages.rejected(name),
        node: atRule,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-semicolon-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-semicolon-newline-after (actual)](#apidoc.element.stylelint.rules.at-rule-semicolon-newline-after)
- description and source-code
```javascript
at-rule-semicolon-newline-after = function (actual) {
  const checker = whitespaceChecker("newline", actual, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual,
      possible: ["always"],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      const nextNode = atRule.next()
      if (!nextNode) {
        return
      }
      if (hasBlock(atRule)) {
        return
      }

      // Allow an end-of-line comment
      const nodeToCheck = nextNonCommentNode(nextNode)
      if (!nodeToCheck) {
        return
      }

      checker.afterOneOnly({
        source: rawNodeString(nodeToCheck),
        index: -1,
        err: msg => {
          report({
            message: msg,
            node: atRule,
            index: atRule.toString().length + 1,
            result,
            ruleName,
          })
        },
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-semicolon-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-semicolon-space-before (expectation)](#apidoc.element.stylelint.rules.at-rule-semicolon-space-before)
- description and source-code
```javascript
at-rule-semicolon-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      if (hasBlock(atRule)) {
        return
      }
      const nodeString = rawNodeString(atRule)

      checker.before({
        source: nodeString,
        index: nodeString.length,
        err: m => {
          report({
            message: m,
            node: atRule,
            index: nodeString.length - 1,
            result,
            ruleName,
          })
        },
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.at-rule-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>at-rule-whitelist (whitelistInput)](#apidoc.element.stylelint.rules.at-rule-whitelist)
- description and source-code
```javascript
at-rule-whitelist = function (whitelistInput) {
  // To allow for just a string as a parameter (not only arrays of strings)
  const whitelist = [].concat(whitelistInput)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      const name = atRule.name

      if (whitelist.indexOf(postcss.vendor.unprefixed(name).toLowerCase()) !== -1) {
        return
      }

      report({
        message: messages.rejected(name),
        node: atRule,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-closing-brace-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-empty-line-before (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-empty-line-before)
- description and source-code
```javascript
block-closing-brace-empty-line-before = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always-multi-line",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      // Return early if blockless or has empty block
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }

      // Get whitespace after ""}", ignoring extra semicolon
      const before = (statement.raws.after || "").replace(/;+/, "")
      if (before === undefined) {
        return
      }

      // Calculate index
      const statementString = statement.toString()
      let index = statementString.length - 1
      if (statementString[index - 1] === "\r") {
        index -= 1
      }

      // Set expectation
      const expectEmptyLineBefore = expectation === "always-multi-line"
        && !isSingleLineString(blockString(statement))
          ? true
          : false

      // Check for at least one empty line
      const hasEmptyLineBefore = hasEmptyLine(before)

      // Return if the expectation is met
      if (expectEmptyLineBefore === hasEmptyLineBefore) {
        return
      }

      const message = expectEmptyLineBefore
        ? messages.expected
        : messages.rejected

      report({
        message,
        result,
        ruleName,
        node: statement,
        index,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-closing-brace-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-newline-after (expectation, options)](#apidoc.element.stylelint.rules.block-closing-brace-newline-after)
- description and source-code
```javascript
block-closing-brace-newline-after = function (expectation, options) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-single-line",
        "never-single-line",
        "always-multi-line",
        "never-multi-line",
      ],
    }, {
      actual: options,
      possible: {
        ignoreAtRules: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      if (!hasBlock(statement)) {
        return
      }
      if (optionsMatches(options, "ignoreAtRules", statement.name)) {
        return
      }

      const nextNode = statement.next()
      if (!nextNode) {
        return
      }

      // Allow an end-of-line comment x spaces after the brace
      const nextNodeIsSingleLineComment = nextNode.type === "comment"
        && !/[^ ]/.test((nextNode.raws.before || ""))
        && nextNode.toString().indexOf("\n") === -1

      const nodeToCheck = nextNodeIsSingleLineComment
        ? nextNode.next()
        : nextNode

      if (!nodeToCheck) {
        return
      }

      let reportIndex = statement.toString().length
      let source = rawNodeString(nodeToCheck)

      // Skip a semicolon at the beginning, if any
      if (
        source
        && source[0] === ";"
      ) {
        source = source.slice(1)
        reportIndex++
      }

      // Only check one after, because there might be other
      // spaces handled by the indentation rule
      checker.afterOneOnly({
        source,
        index: -1,
        lineCheckStr: blockString(statement),
        err: msg => {
          report({
            message: msg,
            node: statement,
            index: reportIndex,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-closing-brace-newline-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-newline-before (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-newline-before)
- description and source-code
```javascript
block-closing-brace-newline-before = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      // Return early if blockless or has empty block
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }

      // Ignore extra semicolon
      const after = (statement.raws.after || "").replace(/;+/, "")
      if (after === undefined) {
        return
      }

      const blockIsMultiLine = !isSingleLineString(blockString(statement))
      const statementString = statement.toString()

      let index = statementString.length - 2
      if (statementString[index - 1] === "\r") {
        index -= 1
      }

      // We're really just checking whether a
      // newline *starts* the block's final space -- between
      // the last declaration and the closing brace. We can
      // ignore any other whitespace between them, because that
      // will be checked by the indentation rule.
      if (
        !_.startsWith(after, "\n")
        && !_.startsWith(after, "\r\n")
      ) {
        if (expectation === "always") {
          complain(messages.expectedBefore)
        } else if (
          blockIsMultiLine
          && expectation === "always-multi-line"
        ) {
          complain(messages.expectedBeforeMultiLine)
        }
      }

      if (
        after !== ""
        && blockIsMultiLine
        && expectation === "never-multi-line"
      ) {
        complain(messages.rejectedBeforeMultiLine)
      }

      function complain(message) {
        report({
          message,
          result,
          ruleName,
          node: statement,
          index,
        })
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-closing-brace-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-space-after (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-space-after)
- description and source-code
```javascript
block-closing-brace-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)

  return function (root, result) {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      const nextNode = statement.next()
      if (!nextNode) {
        return
      }
      if (!hasBlock(statement)) {
        return
      }

      let reportIndex = statement.toString().length
      let source = rawNodeString(nextNode)

      // Skip a semicolon at the beginning, if any
      if (
        source
        && source[0] === ";"
      ) {
        source = source.slice(1)
        reportIndex++
      }

      checker.after({
        source,
        index: -1,
        lineCheckStr: blockString(statement),
        err: msg => {
          report({
            message: msg,
            node: statement,
            index: reportIndex,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-closing-brace-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-closing-brace-space-before (expectation)](#apidoc.element.stylelint.rules.block-closing-brace-space-before)
- description and source-code
```javascript
block-closing-brace-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual : expectation,
      possible : [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statement: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      // Return early if blockless or has empty block
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }

      const source = blockString(statement)
      const statementString = statement.toString()

      let index = statementString.length - 2
      if (statementString[index - 1] === "\r") {
        index -= 1
      }

      checker.before({
        source,
        index: source.length - 1,
        err: msg => {
          report({
            message: msg,
            node: statement,
            index,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-no-empty"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-no-empty (actual)](#apidoc.element.stylelint.rules.block-no-empty)
- description and source-code
```javascript
block-no-empty = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      if (!hasEmptyBlock(statement)) {
        return
      }

      let index = beforeBlockString(statement, { noRawBefore: true }).length

      // For empty blocks when using SugarSS parser
      if (statement.raws.between === undefined) {
        index--
      }

      report({
        message: messages.rejected,
        node: statement,
        index,
        result,
        ruleName,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-no-single-line"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-no-single-line (actual)](#apidoc.element.stylelint.rules.block-no-single-line)
- description and source-code
```javascript
block-no-single-line = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    result.warn((
      "'block-no-single-line' has been deprecated and in 8.0 will be removed. " +
      "Instead use 'block-opening-brace-newline-after' and 'block-closing-brace-newline-before' with the \"always\" option."
    ), {
      stylelintType: "deprecation",
      stylelintReference: "https://stylelint.io/user-guide/rules/block-no-single-line/",
    })

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }
      if (!isSingleLineString(blockString(statement))) {
        return
      }

      report({
        message: messages.rejected,
        node: statement,
        index: beforeBlockString(statement, { noRawBefore: true }).length,
        result,
        ruleName,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-opening-brace-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-newline-after (expectation)](#apidoc.element.stylelint.rules.block-opening-brace-newline-after)
- description and source-code
```javascript
block-opening-brace-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statement: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      // Return early if blockless or has an empty block
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }

      // Allow an end-of-line comment
      const nodeToCheck = nextNonCommentNode(statement.first)
      if (!nodeToCheck) {
        return
      }

      checker.afterOneOnly({
        source: rawNodeString(nodeToCheck),
        index: -1,
        lineCheckStr: blockString(statement),
        err: m => {
          report({
            message: m,
            node: statement,
            index: beforeBlockString(statement, { noRawBefore: true }).length + 1,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-opening-brace-newline-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-newline-before (expectation)](#apidoc.element.stylelint.rules.block-opening-brace-newline-before)
- description and source-code
```javascript
block-opening-brace-newline-before = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual : expectation,
      possible : [
        "always",
        "always-single-line",
        "never-single-line",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statement: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      // Return early if blockless or has an empty block
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }

      const source = beforeBlockString(statement)
      const beforeBraceNoRaw = beforeBlockString(statement, { noRawBefore: true })

      let index = beforeBraceNoRaw.length - 1
      if (beforeBraceNoRaw[index - 1] === "\r") {
        index -= 1
      }

      checker.beforeAllowingIndentation({
        lineCheckStr: blockString(statement),
        source,
        index: source.length,
        err: m => {
          report({
            message: m,
            node: statement,
            index,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-opening-brace-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-space-after (expectation)](#apidoc.element.stylelint.rules.block-opening-brace-space-after)
- description and source-code
```javascript
block-opening-brace-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      // Return early if blockless or has an empty block
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }

      checker.after({
        source: blockString(statement),
        index: 0,
        err: m => {
          report({
            message: m,
            node: statement,
            index: beforeBlockString(statement, { noRawBefore: true }).length + 1,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.block-opening-brace-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>block-opening-brace-space-before (expectation, options)](#apidoc.element.stylelint.rules.block-opening-brace-space-before)
- description and source-code
```javascript
block-opening-brace-space-before = function (expectation, options) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
        "always-multi-line",
        "never-multi-line",
      ],
    }, {
      actual: options,
      possible: {
        ignoreAtRules: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    // Check both kinds of statements: rules and at-rules
    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      // Return early if blockless or has an empty block
      if (
        !hasBlock(statement)
        || hasEmptyBlock(statement)
      ) {
        return
      }

      // Return early if at-rule is to be ignored
      if (optionsMatches(options, "ignoreAtRules", statement.name)) {
        return
      }

      const source = beforeBlockString(statement)
      const beforeBraceNoRaw = beforeBlockString(statement, { noRawBefore: true })

      let index = beforeBraceNoRaw.length - 1
      if (beforeBraceNoRaw[index - 1] === "\r") {
        index -= 1
      }

      checker.before({
        source,
        index: source.length,
        lineCheckStr: blockString(statement),
        err: m => {
          report({
            message: m,
            node: statement,
            index,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.color-hex-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>color-hex-case (expectation)](#apidoc.element.stylelint.rules.color-hex-case)
- description and source-code
```javascript
color-hex-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const declString = blurFunctionArguments(decl.toString(), "url")
      styleSearch({ source: declString, target: "#" }, match => {
        const hexMatch = /^#[0-9A-Za-z]+/.exec(declString.substr(match.startIndex))
        if (!hexMatch) {
          return
        }

        const hexValue = hexMatch[0]
        const hexValueLower = hexValue.toLowerCase()
        const hexValueUpper = hexValue.toUpperCase()
        const expectedHex = expectation === "lower"
          ? hexValueLower
          : hexValueUpper

        if (hexValue === expectedHex) {
          return
        }

        report({
          message: messages.expected(hexValue, expectedHex),
          node: decl,
          index: match.startIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.color-hex-length"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>color-hex-length (expectation)](#apidoc.element.stylelint.rules.color-hex-length)
- description and source-code
```javascript
color-hex-length = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "short",
        "long",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const declString = decl.toString()

      styleSearch({ source: declString, target: "#" }, match => {
        const hexMatch = /^#[0-9A-Za-z]+/.exec(declString.substr(match.startIndex))
        if (!hexMatch) {
          return
        }

        const hexValue = hexMatch[0]

        if (
          expectation === "long"
          && hexValue.length !== 4
          && hexValue.length !== 5
        ) {
          return
        }

        if (
          expectation === "short"
          && (
            hexValue.length < 6
            || !canShrink(hexValue)
          )
        ) {
          return
        }

        const variant = expectation === "long"
          ? longer
          : shorter

        report({
          message: messages.expected(hexValue, variant(hexValue)),
          node: decl,
          index: match.startIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.color-named"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>color-named (expectation, options)](#apidoc.element.stylelint.rules.color-named)
- description and source-code
```javascript
color-named = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "never",
        "always-where-possible",
      ],
    }, {
      actual: options,
      possible: {
        ignoreProperties: [_.isString],
        ignore: ["inside-function"],
      },
      optional: true,
    })

    if (!validOptions) {
      return
    }

    const namedColors = Object.keys(namedColorData)

    root.walkDecls(decl => {
      if (propertySets.acceptCustomIdents.has(decl.prop)) {
        return
      }

      // Return early if the property is to be ignored
      if (optionsMatches(options, "ignoreProperties", decl.prop)) {
        return
      }

      valueParser(decl.value).walk(node => {
        const value = node.value,
          type = node.type,
          sourceIndex = node.sourceIndex

        if (
          optionsMatches(options, "ignore", "inside-function")
          && type === "function"
        ) {
          return false
        }

        if (!isStandardSyntaxFunction(node)) {
          return false
        }

        if (!isStandardSyntaxValue(value)) {
          return
        }
        // Return early if neither a word nor a function
        if (NODE_TYPES.indexOf(type) === -1) {
          return
        }

        // Check for named colors for "never" option
        if (
          expectation === "never"
          && type === "word"
          && namedColors.indexOf(value.toLowerCase()) !== -1
        ) {
          complain(messages.rejected(value), decl, declarationValueIndex(decl) + sourceIndex)
          return
        }

        // Check "always-where-possible" option ...
        if (expectation !== "always-where-possible") {
          return
        }

        // First by checking for alternative color function representations ...
        if (
          type === "function"
          && keywordSets.colorFunctionNames.has(value.toLowerCase())
        ) {
          // Remove all spaces to match what's in 'representations'
          const normalizedFunctionString = valueParser.stringify(node).replace(/\s+/g, "")
          let namedColor
          for (let i = 0, l = namedColors.length; i < l; i++) {
            namedColor = namedColors[i]
            if (namedColorData[namedColor].func.indexOf(normalizedFunctionString.toLowerCase()) !== -1) {
              complain(messages.expected(namedColor, normalizedFunctionString), decl, declarationValueIndex(decl) + sourceIndex)
              return // Exit as soon as a problem is found
            }
          }
          return
        }

        // Then by checking for alternative hex representations
        let namedColor
        for (let i = 0, l = namedColors.length; i < l; i++) {
          namedColor = namedColors[i]
          if (namedColorData[namedColor].hex.indexOf(value.toLowerCase()) !== -1) {
            complain(messages.expected(namedColor, value), decl, declarationValueIndex(decl) + sourceIndex)
            return // Exit as soon as a problem is found
          }
        }
      })
    })

    function complain(message, node, index) {
      report({
        result,
        ruleName,
        message,
        node,
        index,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.color-no-hex"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>color-no-hex (actual)](#apidoc.element.stylelint.rules.color-no-hex)
- description and source-code
```javascript
color-no-hex = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const declString = decl.toString()

      styleSearch({ source: declString, target: "#" }, match => {
        // If there's not a colon, comma, or whitespace character before, we'll assume this is
        // not intended to be a hex color, but is instead something like the
        // hash in a url() argument
        if (!/[:,\s]/.test(declString[match.startIndex - 1])) {
          return
        }

        const hexMatch = /^#[0-9A-Za-z]+/.exec(declString.substr(match.startIndex))
        if (!hexMatch) {
          return
        }
        const hexValue = hexMatch[0]

        report({
          message: messages.rejected(hexValue),
          node: decl,
          index: match.startIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.color-no-invalid-hex"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>color-no-invalid-hex (actual)](#apidoc.element.stylelint.rules.color-no-invalid-hex)
- description and source-code
```javascript
color-no-invalid-hex = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const declString = decl.toString()

      styleSearch({ source: declString, target: "#" }, match => {
        // If there's not a colon, comma, or whitespace character before, we'll assume this is
        // not intended to be a hex color, but is instead something like the
        // hash in a url() argument
        if (!/[:,\s]/.test(declString[match.startIndex - 1])) {
          return
        }

        const hexMatch = /^#[0-9A-Za-z]+/.exec(declString.substr(match.startIndex))
        if (!hexMatch) {
          return
        }

        const hexValue = hexMatch[0]
        if (isValidHex(hexValue)) {
          return
        }

        report({
          message: messages.rejected(hexValue),
          node: decl,
          index: match.startIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.comment-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.comment-empty-line-before)
- description and source-code
```javascript
comment-empty-line-before = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    }, {
      actual: options,
      possible: {
        except: ["first-nested"],
        ignore: [
          "stylelint-commands",
          "stylelint-command",
          "between-comments",
          "after-comment",
        ],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    if (
      optionsMatches(options, "ignore", "between-comments")
    ) {
      result.warn((
        "'comment-empty-line-before\'s' \"between-comments\" option has been deprecated and in 8.0 will be removed. " +
        "Instead use the \"after-comment\" option."
      ), {
        stylelintType: "deprecation",
        stylelintReference: "https://stylelint.io/user-guide/rules/comment-empty-line-before/",
      })
    }

    root.walkComments(comment => {
      // Ignore the first node
      if (comment === root.first) {
        return
      }

      // Optionally ignore stylelint commands
      if (
        comment.text.indexOf(stylelintCommandPrefix) === 0
        && optionsMatches(options, "ignore", "stylelint-commands")
      ) {
        return
      }

      // Optionally ignore newlines between comments
      const prev = comment.prev()
      if (
        prev
        && prev.type === "comment"
        && optionsMatches(options, "ignore", "between-comments")
      ) {
        return
      }

      if (
        prev
        && prev.type === "comment"
        && optionsMatches(options, "ignore", "after-comment")
      ) {
        return
      }

      if (
        comment.raws.inline
        || comment.inline
      ) {
        return
      }

      const before = (comment.raws.before || "")

      // Ignore shared-line comments
      if (before.indexOf("\n") === -1) {
        return
      }

      const expectEmptyLineBefore = (() => {
        if (
          optionsMatches(options, "except", "first-nested")
          && comment.parent !== root
          && comment === comment.parent.first
        ) {
          return false
        }
        return expectation === "always"
      })()

      const hasEmptyLineBefore = hasEmptyLine(before)

      // Return if the expectation is met
      if (expectEmptyLineBefore === hasEmptyLineBefore) {
        return
      }

      const message = expectEmptyLineBefore
        ? messages.expected
        : messages.rejected

      report({
        message,
        node: comment,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.comment-no-empty"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-no-empty (actual)](#apidoc.element.stylelint.rules.comment-no-empty)
- description and source-code
```javascript
comment-no-empty = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkComments(comment => {
      // To ignore inline SCSS comments
      if (
        comment.raws.inline
        || comment.inline
      ) {
        return
      }

      // To ignore comments that are not empty
      if (
        comment.text
        && comment.text.length !== 0
      ) {
        return
      }

      report({
        message: messages.rejected,
        node: comment,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.comment-whitespace-inside"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-whitespace-inside (expectation)](#apidoc.element.stylelint.rules.comment-whitespace-inside)
- description and source-code
```javascript
comment-whitespace-inside = function (expectation) {
  return function (root, result) {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkComments(function (comment) {
      if (
        comment.raws.inline
        || comment.inline
      ) {
        return
      }

      const rawComment = comment.toString()
      const firstFourChars = rawComment.substr(0, 4)

      // Return early if sourcemap or copyright comment
      if (/^\/\*[#!]\s/.test(firstFourChars)) {
        return
      }

      const leftMatches = rawComment.match(/(^\/\*+)(\s)?/)
      const rightMatches = rawComment.match(/(\s)?(\*+\/)$/)
      const opener = leftMatches[1]
      const leftSpace = leftMatches[2] || ""
      const rightSpace = rightMatches[1] || ""
      const closer = rightMatches[2]

      if (
        expectation === "never"
        && leftSpace !== ""
      ) {
        complain(messages.rejectedOpening, opener.length)
      }

      if (
        expectation === "always"
        && !isWhitespace(leftSpace)
      ) {
        complain(messages.expectedOpening, opener.length)
      }

      if (
        expectation === "never"
        && rightSpace !== ""
      ) {
        complain(messages.rejectedClosing, comment.toString().length - closer.length - 1)
      }

      if (
        expectation === "always"
        && !isWhitespace(rightSpace)
      ) {
        complain(messages.expectedClosing, comment.toString().length - closer.length - 1)
      }

      function complain(message, index) {
        report({
          message,
          index,
          result,
          ruleName,
          node: comment,
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.comment-word-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>comment-word-blacklist (blacklist)](#apidoc.element.stylelint.rules.comment-word-blacklist)
- description and source-code
```javascript
comment-word-blacklist = function (blacklist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkComments(comment => {
      const text = comment.text
      const rawComment = comment.toString()
      const firstFourChars = rawComment.substr(0, 4)

      // Return early if sourcemap
      if (firstFourChars === "/*# ") {
        return
      }

      const matchesWord = matchesStringOrRegExp(text, blacklist) || containsString(text, blacklist)

      if (!matchesWord) {
        return
      }

      report({
        message: messages.rejected(matchesWord.pattern),
        node: comment,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.custom-media-pattern"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-media-pattern (pattern)](#apidoc.element.stylelint.rules.custom-media-pattern)
- description and source-code
```javascript
custom-media-pattern = function (pattern) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: pattern,
      possible: [
        _.isRegExp,
        _.isString,
      ],
    })
    if (!validOptions) {
      return
    }

    const regexpPattern = _.isString(pattern) ? new RegExp(pattern) : pattern

    root.walkAtRules(atRule => {
      if (atRule.name.toLowerCase() !== "custom-media") {
        return
      }

      const customMediaName = atRule.params.match(/^--(\S+)\b/)[1]

      if (regexpPattern.test(customMediaName)) {
        return
      }

      report({
        message: messages.expected,
        node: atRule,
        index: atRuleParamIndex(atRule),
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.custom-property-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-property-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.custom-property-empty-line-before)
- description and source-code
```javascript
custom-property-empty-line-before = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    }, {
      actual: options,
      possible: {
        except: [
          "first-nested",
          "after-comment",
          "after-custom-property",
        ],
        ignore: [
          "after-comment",
          "inside-single-line-block",
        ],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop,
        parent = decl.parent

      if (!isStandardSyntaxDeclaration(decl)) {
        return
      }
      if (!isCustomProperty(prop)) {
        return
      }

      // Optionally ignore the node if a comment precedes it
      if (
        optionsMatches(options, "ignore", "after-comment")
        && decl.prev()
        && decl.prev().type === "comment"
      ) {
        return
      }

      // Optionally ignore nodes inside single-line blocks
      if (
        optionsMatches(options, "ignore", "inside-single-line-block")
        && isSingleLineString(blockString(parent))
      ) {
        return
      }

      let expectEmptyLineBefore = expectation === "always" ? true : false

      // Optionally reverse the expectation for the first nested node
      if (
        optionsMatches(options, "except", "first-nested")
        && decl === parent.first
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Optionally reverse the expectation if a comment precedes this node
      if (
        optionsMatches(options, "except", "after-comment")
        && decl.prev()
        && decl.prev().type === "comment"
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Optionally reverse the expectation if a custom property precedes this node
      if (
        optionsMatches(options, "except", "after-custom-property")
        && decl.prev()
        && decl.prev().prop
        && isCustomProperty(decl.prev().prop)
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      const hasEmptyLineBefore = hasEmptyLine(decl.raws.before)

      // Return if the expectation is met
      if (expectEmptyLineBefore === hasEmptyLineBefore) {
        return
      }

      const message = expectEmptyLineBefore ? messages.expected : messages.rejected
      report({
        message,
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.custom-property-no-outside-root"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-property-no-outside-root (actual)](#apidoc.element.stylelint.rules.custom-property-no-outside-root)
- description and source-code
```javascript
custom-property-no-outside-root = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed. Instead use the community 'stylelint-suitcss' plugin pack.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    root.walkRules(rule => {
      // Ignore rules whose selector is just ':root'
      if (rule.selector.toLowerCase().trim() === ":root") {
        return
      }

      rule.walkDecls(decl => {
        if (!isCustomProperty(decl.prop)) {
          return
        }
        report({
          message: messages.rejected,
          node: decl,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.custom-property-pattern"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>custom-property-pattern (pattern)](#apidoc.element.stylelint.rules.custom-property-pattern)
- description and source-code
```javascript
custom-property-pattern = function (pattern) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: pattern,
      possible: [
        _.isRegExp,
        _.isString,
      ],
    })
    if (!validOptions) {
      return
    }

    const regexpPattern = _.isString(pattern) ? new RegExp(pattern) : pattern

    root.walkDecls(decl => {
      const prop = decl.prop

      if (!isCustomProperty(prop)) {
        return
      }
      if (regexpPattern.test(prop.slice(2))) {
        return
      }

      report({
        message: messages.expected,
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-bang-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-bang-space-after (expectation)](#apidoc.element.stylelint.rules.declaration-bang-space-after)
- description and source-code
```javascript
declaration-bang-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    declarationBangSpaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-bang-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-bang-space-before (expectation)](#apidoc.element.stylelint.rules.declaration-bang-space-before)
- description and source-code
```javascript
declaration-bang-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    declarationBangSpaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-no-duplicate-properties"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-duplicate-properties (on, options)](#apidoc.element.stylelint.rules.declaration-block-no-duplicate-properties)
- description and source-code
```javascript
declaration-block-no-duplicate-properties = function (on, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual: on }, {
      actual: options,
      possible: {
        ignore: [
          "consecutive-duplicates",
          "consecutive-duplicates-with-different-values",
        ],
        ignoreProperties: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    // In order to accommodate nested blocks (postcss-nested),
    // we need to run a shallow loop (instead of eachDecl() or eachRule(),
    // which loop recursively) and allow each nested block to accumulate
    // its own list of properties -- so that a property in a nested rule
    // does not conflict with the same property in the parent rule
    root.each(node => {
      if (
        node.type === "rule"
        || node.type === "atrule"
      ) {
        checkRulesInNode(node)
      }
    })

    function checkRulesInNode(node) {
      const decls = []
      const values = []

      node.each(child => {
        if (
          child.nodes
          && child.nodes.length
        ) {
          checkRulesInNode(child)
        }

        if (child.type !== "decl") {
          return
        }

        const prop = child.prop
        const value = child.value

        if (!isStandardSyntaxProperty(prop)) {
          return
        }
        if (isCustomProperty(prop)) {
          return
        }

        // Return early if the property is to be ignored
        if (optionsMatches(options, "ignoreProperties", prop)) {
          return
        }

        // Ignore the src property as commonly duplicated in at-fontface
        if (prop.toLowerCase() === "src") {
          return
        }

        const indexDuplicate = decls.indexOf(prop.toLowerCase())

        if (indexDuplicate !== -1) {
          if (optionsMatches(options, "ignore", "consecutive-duplicates-with-different-values")) {
            // if duplicates are not consecutive
            if (indexDuplicate !== decls.length - 1) {
              report({
                message: messages.rejected(prop),
                node: child,
                result,
                ruleName,
              })
              return
            }
            // if values of consecutive duplicates are equal
            if (value === values[indexDuplicate]) {
              report({
                message: messages.rejected(value),
                node: child,
                result,
                ruleName,
              })
              return
            }
            return
          }

          if (
            optionsMatches(options, "ignore", "consecutive-duplicates")
            && indexDuplicate === decls.length - 1
          ) {
            return
          }

          report({
            message: messages.rejected(prop),
            node: child,
            result,
            ruleName,
          })
        }

        decls.push(prop.toLowerCase())
        values.push(value.toLowerCase())
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-no-ignored-properties"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-ignored-properties (actual)](#apidoc.element.stylelint.rules.declaration-block-no-ignored-properties)
- description and source-code
```javascript
declaration-block-no-ignored-properties = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })

    if (!validOptions) {
      return
    }

    result.warn((
      "'declaration-block-no-ignored-properties' has been deprecated and in 8.0 will be removed."
    ), {
      stylelintType: "deprecation",
      stylelintReference: "https://stylelint.io/user-guide/rules/declaration-block-no-ignored-properties/",
    })

    const uniqueDecls = {}
    root.walkDecls(decl => {
      uniqueDecls[decl.prop] = decl
    })

    Object.keys(uniqueDecls).forEach((prop, index) => {
      const decl = uniqueDecls[prop]
      const unprefixedProp = postcss.vendor.unprefixed(prop)
      const unprefixedValue = postcss.vendor.unprefixed(decl.value)

      ignored.forEach(ignore => {
        const matchProperty = matchesStringOrRegExp(unprefixedProp.toLowerCase(), ignore.property)
        const matchValue = matchesStringOrRegExp(unprefixedValue.toLowerCase(), ignore.value)

        if (!matchProperty || !matchValue) {
          return
        }

        const ignoredProperties = ignore.ignoredProperties

        decl.parent.nodes.forEach((node, nodeIndex) => {
          if (!node.prop || ignoredProperties.indexOf(node.prop.toLowerCase()) === -1 || index === nodeIndex) {
            return
          }

          report({
            message: messages.rejected(node.prop, decl.toString()),
            node,
            result,
            ruleName,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-no-redundant-longhand-properties"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-redundant-longhand-properties (actual, options)](#apidoc.element.stylelint.rules.declaration-block-no-redundant-longhand-properties)
- description and source-code
```javascript
declaration-block-no-redundant-longhand-properties = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignoreShorthands: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    const longhandProperties = _.transform(shorthandData, (result, values, key) => {
      if (optionsMatches(options, "ignoreShorthands", key)) {
        return
      }

      values.forEach(value => {
        (result[value] || (result[value] = [])).push(key)
      })
    })

    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      const longhandDeclarations = {}
      // Shallow iteration so nesting doesn't produce
      // false positives
      statement.each(node => {
        if (node.type !== "decl") {
          return
        }

        const prop = node.prop.toLowerCase()

        const shorthandProperties = longhandProperties[prop]

        if (!shorthandProperties) {
          return
        }

        shorthandProperties.forEach(shorthandProperty => {
          (longhandDeclarations[shorthandProperty] || (longhandDeclarations[shorthandProperty] = [])).push(prop)

          if (!_.isEqual(shorthandData[shorthandProperty].sort(), longhandDeclarations[shorthandProperty].sort())) {
            return
          }

          report({
            ruleName,
            result,
            node,
            message: messages.expected(shorthandProperty),
          })
        })
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-no-shorthand-property-overrides"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-no-shorthand-property-overrides (actual)](#apidoc.element.stylelint.rules.declaration-block-no-shorthand-property-overrides)
- description and source-code
```javascript
declaration-block-no-shorthand-property-overrides = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkRules(check)
    root.walkAtRules(check)

    function check(statement) {
      const declarations = {}
      // Shallow iteration so nesting doesn't produce
      // false positives
      statement.each(node => {
        if (node.type !== "decl") {
          return
        }
        const prop = node.prop

        const overrideables = shorthandData[prop.toLowerCase()]
        if (!overrideables) {
          declarations[prop.toLowerCase()] = prop
          return
        }
        overrideables.forEach(longhandProp => {
          if (!declarations.hasOwnProperty(longhandProp)) {
            return
          }
          report({
            ruleName,
            result,
            node,
            message: messages.rejected(prop, declarations[longhandProp]),
          })
        })
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-properties-order"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-properties-order (expectation, options)](#apidoc.element.stylelint.rules.declaration-block-properties-order)
- description and source-code
```javascript
declaration-block-properties-order = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: validatePrimaryOption,
    }, {
      actual: options,
      possible: {
        unspecified: [
          "top",
          "bottom",
          "ignore",
          "bottomAlphabetical",
        ],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    result.warn((
      "'declaration-block-properties-order'has been deprecated and in 8.0 will be removed. " +
      "Instead use the community 'stylelint-order' plugin pack."
    ), {
      stylelintType: "deprecation",
      stylelintReference: "https://stylelint.io/user-guide/rules/declaration-block-properties-order/",
    })

    const alphabetical = expectation === "alphabetical"
    const expectedOrder = alphabetical ? null : createExpectedOrder(expectation)
    // By default, ignore unspecified properties
    const unspecified = _.get(options, ["unspecified"], "ignore")

    // Shallow loop
    root.each(node => {
      if (node.type === "rule" || node.type === "atrule") {
        checkNode(node)
      }
    })

    function checkNode(node) {
      const allPropData = []

      node.each(child => {
        // If the child has nested nodes with child
        // (e.g. a rule nested within a rule), make
        // sure to check the children
        if (child.nodes && child.nodes.length) {
          checkNode(child)
        }

        if (child.type !== "decl") {
          return
        }

        const prop = child.prop

        if (!isStandardSyntaxProperty(prop)) {
          return
        }
        if (isCustomProperty(prop)) {
          return
        }

        let unprefixedPropName = postcss.vendor.unprefixed(prop)

        // Hack to allow -moz-osx-font-smoothing to be understood
        // just like -webkit-font-smoothing
        if (unprefixedPropName.indexOf("osx-") === 0) {
          unprefixedPropName = unprefixedPropName.slice(4)
        }

        const propData = {
          name: prop,
          unprefixedName: unprefixedPropName,
          orderData: alphabetical ? null : getOrderData(expectedOrder, unprefixedPropName),
          before: child.raws.before,
          index: allPropData.length,
          node: child,
        }

        const previousPropData = _.last(allPropData)
        allPropData.push(propData)

        // Skip first decl
        if (!previousPropData) {
          return
        }

        const isCorrectOrder = alphabetical ? checkAlpabeticalOrder(previousPropData, propData) : checkOrder(previousPropData, propData
)

        if (isCorrectOrder) {
          return
        }

        complain({
          message: messages.expected(propData.name, previousPropData.name),
          node: child,
        })
      })

      function checkOrder(firstPropData, secondPropData) {
        // If the unprefixed property names are the same, resort to alphabetical ordering
        if (firstPropData.unprefixedName === secondPropData.unprefixedName) {
          return firstPropData.name <= secondPropData.name
        }

        const firstPropIsUnspecified = !firstPropData.orderData
        const secondPropIsUnspecified = !secondPropData.orderData

        // Now check actual known properties ...
        if (!firstPropIsUnspecified && !secondPropIsUnspecified) {
          return firstPropData.orderData.expectedPosition <= secondPropData.orderData.expectedPosition
        }

        if (firstPropIsUnspecified && !secondPropIsUnspecified) {
          // If first prop is unspecified, look for a specified prop before it to
          // compare to the current prop
          const priorSpecifiedPropData = _.findLast(allPropData.slice(0, -1), d => !!d.orderData)
          if (priorSpecifiedPropData && priorSpecifiedPropData.orderData && priorSpecifiedPropData.orderData.expectedPosition >
secondPropData.orderData.expectedPosition) {
            complain({
              message: messages.expected(secondPropData.name, priorSpecifiedPropData.name),
              node: ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-semicolon-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-newline-after (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-newline-after)
- description and source-code
```javascript
declaration-block-semicolon-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      // Ignore last declaration if there's no trailing semicolon
      const parentRule = decl.parent
      if (
        !parentRule.raws.semicolon
        && parentRule.last === decl
      ) {
        return
      }

      const nextNode = decl.next()
      if (!nextNode) {
        return
      }

      // Allow end-of-line comment
      const nodeToCheck = nextNonCommentNode(nextNode)
      if (!nodeToCheck) {
        return
      }

      checker.afterOneOnly({
        source: rawNodeString(nodeToCheck),
        index: -1,
        lineCheckStr: blockString(parentRule),
        err: m => {
          report({
            message: m,
            node: decl,
            index: decl.toString().length + 1,
            result,
            ruleName,
          })
        },
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-semicolon-newline-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-newline-before (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-newline-before)
- description and source-code
```javascript
declaration-block-semicolon-newline-before = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)

  return function (root, result) {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(function (decl) {
      const parentRule = decl.parent
      if (
        !parentRule.raws.semicolon
        && parentRule.last === decl
      ) {
        return
      }

      const declString = decl.toString()

      checker.beforeAllowingIndentation({
        source: declString,
        index: declString.length,
        lineCheckStr: blockString(parentRule),
        err: m => {
          report({
            message: m,
            node: decl,
            index: decl.toString().length - 1,
            result,
            ruleName,
          })
        },
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-semicolon-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-space-after (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-space-after)
- description and source-code
```javascript
declaration-block-semicolon-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)

  return function (root, result) {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(function (decl) {
      // Ignore last declaration if there's no trailing semicolon
      const parentRule = decl.parent
      if (!parentRule.raws.semicolon && parentRule.last === decl) {
        return
      }

      const nextDecl = decl.next()
      if (!nextDecl) {
        return
      }

      checker.after({
        source: rawNodeString(nextDecl),
        index: -1,
        lineCheckStr: blockString(parentRule),
        err: m => {
          report({
            message: m,
            node: decl,
            index: decl.toString().length + 1,
            result,
            ruleName,
          })
        },
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-semicolon-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-semicolon-space-before (expectation)](#apidoc.element.stylelint.rules.declaration-block-semicolon-space-before)
- description and source-code
```javascript
declaration-block-semicolon-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      // Ignore last declaration if there's no trailing semicolon
      const parentRule = decl.parent
      if (!parentRule.raws.semicolon && parentRule.last === decl) {
        return
      }

      const declString = decl.toString()

      checker.before({
        source: declString,
        index: declString.length,
        lineCheckStr: blockString(parentRule),
        err: m => {
          report({
            message: m,
            node: decl,
            index: decl.toString().length - 1,
            result,
            ruleName,
          })
        },
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-single-line-max-declarations"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-single-line-max-declarations (quantity)](#apidoc.element.stylelint.rules.declaration-block-single-line-max-declarations)
- description and source-code
```javascript
declaration-block-single-line-max-declarations = function (quantity) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: quantity,
      possible: [_.isNumber],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isSingleLineString(blockString(rule))) {
        return
      }
      if (!rule.nodes) {
        return
      }

      const decls = rule.nodes.filter(node => node.type === "decl")

      if (decls.length <= quantity) {
        return
      }

      report({
        message: messages.expected(quantity),
        node: rule,
        index: beforeBlockString(rule, { noRawBefore: true }).length,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-block-trailing-semicolon"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-block-trailing-semicolon (expectation)](#apidoc.element.stylelint.rules.declaration-block-trailing-semicolon)
- description and source-code
```javascript
declaration-block-trailing-semicolon = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      if (atRule.parent === root) {
        return
      }
      if (atRule !== atRule.parent.last) {
        return
      }
      if (hasBlock(atRule)) {
        return
      }
      checkLastNode(atRule)
    })

    root.walkDecls(decl => {
      if (decl !== decl.parent.last) {
        return
      }
      checkLastNode(decl)
    })

    function checkLastNode(node) {
      let message

      if (expectation === "always") {
        if (node.parent.raws.semicolon) {
          return
        }
        message = messages.expected
      }
      if (expectation === "never") {
        if (!node.parent.raws.semicolon) {
          return
        }
        message = messages.rejected
      }

      report({
        message,
        node,
        index: node.toString().trim().length - 1,
        result,
        ruleName,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-colon-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-colon-newline-after (expectation)](#apidoc.element.stylelint.rules.declaration-colon-newline-after)
- description and source-code
```javascript
declaration-colon-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (!isStandardSyntaxDeclaration(decl)) {
        return
      }

      // Get the raw prop, and only the prop
      const endOfPropIndex = declarationValueIndex(decl) + (decl.raws.between || "").length - 1

      // The extra characters tacked onto the end ensure that there is a character to check
      // after the colon. Otherwise, with 'background:pink' the character after the
      const propPlusColon = decl.toString().slice(0, endOfPropIndex) + "xxx"

      for (let i = 0, l = propPlusColon.length; i < l; i++) {
        if (propPlusColon[i] !== ":") {
          continue
        }
        const indexToCheck = propPlusColon.substr(propPlusColon[i], 3) === "/*" ? propPlusColon.indexOf("*/", i) + 1 : i

        checker.afterOneOnly({
          source: propPlusColon,
          index: indexToCheck,
          lineCheckStr: decl.value,
          err: m => {
            report({
              message: m,
              node: decl,
              index: indexToCheck,
              result,
              ruleName,
            })
          },
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-colon-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-colon-space-after (expectation)](#apidoc.element.stylelint.rules.declaration-colon-space-after)
- description and source-code
```javascript
declaration-colon-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    declarationColonSpaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-colon-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-colon-space-before (expectation)](#apidoc.element.stylelint.rules.declaration-colon-space-before)
- description and source-code
```javascript
declaration-colon-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    declarationColonSpaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.declaration-empty-line-before)
- description and source-code
```javascript
declaration-empty-line-before = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    }, {
      actual: options,
      possible: {
        except: [
          "first-nested",
          "after-comment",
          "after-declaration",
        ],
        ignore: [
          "after-comment",
          "after-declaration",
          "inside-single-line-block",
        ],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop,
        parent = decl.parent

      if (!isStandardSyntaxDeclaration(decl)) {
        return
      }
      if (isCustomProperty(prop)) {
        return
      }

      // Optionally ignore the node if a comment precedes it
      if (
        optionsMatches(options, "ignore", "after-comment")
        && decl.prev()
        && decl.prev().type === "comment"
      ) {
        return
      }

      // Optionally ignore the node if a declaration precedes it
      if (
        optionsMatches(options, "ignore", "after-declaration")
        && decl.prev()
        && decl.prev().type === "decl"
      ) {
        return
      }

      // Optionally ignore nodes inside single-line blocks
      if (
        optionsMatches(options, "ignore", "inside-single-line-block")
        && isSingleLineString(blockString(parent))
      ) {
        return
      }

      let expectEmptyLineBefore = expectation === "always"
        ? true
        : false

      // Optionally reverse the expectation for the first nested node
      if (
        optionsMatches(options, "except", "first-nested")
        && decl === parent.first
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Optionally reverse the expectation if a comment precedes this node
      if (
        optionsMatches(options, "except", "after-comment")
        && decl.prev()
        && decl.prev().type === "comment"
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Optionally reverse the expectation if a declaration precedes this node
      if (
        optionsMatches(options, "except", "after-declaration")
        && decl.prev()
        && decl.prev().prop
        && isStandardSyntaxDeclaration(decl.prev())
        && !isCustomProperty(decl.prev().prop)
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Check for at least one empty line
      const hasEmptyLineBefore = hasEmptyLine(decl.raws.before)

      // Return if the expectation is met
      if (expectEmptyLineBefore === hasEmptyLineBefore) {
        return
      }

      const message = expectEmptyLineBefore
        ? messages.expected
        : messages.rejected
      report({ message, node: decl, result, ruleName })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-no-important"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-no-important (actual)](#apidoc.element.stylelint.rules.declaration-no-important)
- description and source-code
```javascript
declaration-no-important = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (!decl.important) {
        return
      }

      report({
        message: messages.rejected,
        node: decl,
        word: "important",
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-property-unit-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-unit-blacklist (blacklist)](#apidoc.element.stylelint.rules.declaration-property-unit-blacklist)
- description and source-code
```javascript
declaration-property-unit-blacklist = function (blacklist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isObject],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop,
        value = decl.value

      const unprefixedProp = postcss.vendor.unprefixed(prop)

      const propBlacklist = _.find(blacklist, (list, propIdentifier) => matchesStringOrRegExp(unprefixedProp, propIdentifier))

      if (!propBlacklist) {
        return
      }

      valueParser(value).walk(function (node) {
        // Ignore wrong units within 'url' function
        if (
          node.type === "function"
          && node.value.toLowerCase() === "url"
        ) {
          return false
        }
        if (node.type === "string") {
          return
        }

        const unit = getUnitFromValueNode(node)

        if (
          !unit
          || unit
          && propBlacklist.indexOf(unit.toLowerCase()) === -1
        ) {
          return
        }

        report({
          message: messages.rejected(prop, unit),
          node: decl,
          index: declarationValueIndex(decl) + node.sourceIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-property-unit-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-unit-whitelist (whitelist)](#apidoc.element.stylelint.rules.declaration-property-unit-whitelist)
- description and source-code
```javascript
declaration-property-unit-whitelist = function (whitelist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isObject],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop,
        value = decl.value

      const unprefixedProp = postcss.vendor.unprefixed(prop)

      const propWhitelist = _.find(whitelist, (list, propIdentifier) => matchesStringOrRegExp(unprefixedProp, propIdentifier))

      if (!propWhitelist) {
        return
      }

      valueParser(value).walk(function (node) {
        // Ignore wrong units within 'url' function
        if (node.type === "function" && node.value.toLowerCase() === "url") {
          return false
        }
        if (node.type === "string") {
          return
        }

        const unit = getUnitFromValueNode(node)

        if (!unit || (unit && propWhitelist.indexOf(unit.toLowerCase())) !== -1) {
          return
        }

        report({
          message: messages.rejected(prop, unit),
          node: decl,
          index: declarationValueIndex(decl) + node.sourceIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-property-value-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-value-blacklist (blacklist)](#apidoc.element.stylelint.rules.declaration-property-value-blacklist)
- description and source-code
```javascript
declaration-property-value-blacklist = function (blacklist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isObject],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop,
        value = decl.value

      const unprefixedProp = postcss.vendor.unprefixed(prop)
      const propBlacklist = _.find(blacklist, (list, propIdentifier) => matchesStringOrRegExp(unprefixedProp, propIdentifier))

      if (_.isEmpty(propBlacklist)) {
        return
      }

      if (!matchesStringOrRegExp(value, propBlacklist)) {
        return
      }

      report({
        message: messages.rejected(prop, value),
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.declaration-property-value-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>declaration-property-value-whitelist (whitelist)](#apidoc.element.stylelint.rules.declaration-property-value-whitelist)
- description and source-code
```javascript
declaration-property-value-whitelist = function (whitelist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isObject],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop,
        value = decl.value

      const unprefixedProp = postcss.vendor.unprefixed(prop)
      const propWhitelist = _.find(whitelist, (list, propIdentifier) => matchesStringOrRegExp(unprefixedProp, propIdentifier))

      if (_.isEmpty(propWhitelist)) {
        return
      }

      if (matchesStringOrRegExp(value, propWhitelist)) {
        return
      }

      report({
        message: messages.rejected(prop, value),
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.font-family-name-quotes"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>font-family-name-quotes (expectation)](#apidoc.element.stylelint.rules.font-family-name-quotes)
- description and source-code
```javascript
font-family-name-quotes = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always-where-required",
        "always-where-recommended",
        "always-unless-keyword",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(/^font(-family)?$/i, decl => {
      const fontFamilies = findFontFamily(decl.value)

      if (fontFamilies.length === 0) {
        return
      }

      fontFamilies.forEach(fontFamilyNode => {
        let rawFamily = fontFamilyNode.value

        if (fontFamilyNode.quote) {
          rawFamily = fontFamilyNode.quote + rawFamily + fontFamilyNode.quote
        }

        checkFamilyName(rawFamily, decl)
      })
    })

    function checkFamilyName(rawFamily, decl) {
      if (!isStandardSyntaxValue(rawFamily)) {
        return
      }
      if (isVariable(rawFamily)) {
        return
      }

      const hasQuotes = rawFamily[0] === "'" || rawFamily[0] === "\""

      // Clean the family of its quotes
      const family = rawFamily.replace(/^['"]|['"]$/g, "")

      // Disallow quotes around (case-insensitive) keywords
      // and system font keywords in all cases
      if (keywordSets.fontFamilyKeywords.has(family.toLowerCase()) || isSystemFontKeyword(family)) {
        if (hasQuotes) {
          return complain(messages.rejected(family), family, decl)
        }
        return
      }

      const required = quotesRequired(family)
      const recommended = quotesRecommended(family)

      switch (expectation) {
        case "always-unless-keyword":
          if (!hasQuotes) {
            return complain(messages.expected(family), family, decl)
          }
          return

        case "always-where-recommended":
          if (!recommended && hasQuotes) {
            return complain(messages.rejected(family), family, decl)
          }
          if (recommended && !hasQuotes) {
            return complain(messages.expected(family), family, decl)
          }
          return

        case "always-where-required":
          if (!required && hasQuotes) {
            return complain(messages.rejected(family), family, decl)
          }
          if (required && !hasQuotes) {
            return complain(messages.expected(family), family, decl)
          }
          return
      }
    }

    function complain(message, family, decl) {
      report({
        result,
        ruleName,
        message,
        node: decl,
        word: family,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.font-family-no-duplicate-names"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>font-family-no-duplicate-names (actual, options)](#apidoc.element.stylelint.rules.font-family-no-duplicate-names)
- description and source-code
```javascript
font-family-no-duplicate-names = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignoreFontFamilyNames: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(/^font(-family)?$/i, decl => {
      const keywords = new Set()
      const familyNames = new Set()

      const fontFamilies = findFontFamily(decl.value)

      if (fontFamilies.length === 0) {
        return
      }

      fontFamilies.forEach(fontFamilyNode => {
        const family = fontFamilyNode.value.trim()

        if (optionsMatches(options, "ignoreFontFamilyNames", fontFamilyNode.value.trim())) {
          return
        }

        if (isFamilyNameKeyword(fontFamilyNode)) {
          if (keywords.has(family.toLowerCase())) {
            complain(messages.rejected(family), declarationValueIndex(decl) + fontFamilyNode.sourceIndex, decl)
            return
          }

          keywords.add(family)
          return
        }

        if (familyNames.has(family)) {
          complain(messages.rejected(family), declarationValueIndex(decl) + fontFamilyNode.sourceIndex, decl)
          return
        }

        familyNames.add(family)
      })
    })

    function complain(message, index, decl) {
      report({
        result,
        ruleName,
        message,
        node: decl,
        index,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.font-weight-notation"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>font-weight-notation (expectation, options)](#apidoc.element.stylelint.rules.font-weight-notation)
- description and source-code
```javascript
font-weight-notation = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "numeric",
        "named-where-possible",
      ],
    }, {
      actual: options,
      possible: {
        ignore: ["relative"],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (decl.prop.toLowerCase() === "font-weight") {
        checkWeight(decl.value, decl)
      }

      if (decl.prop.toLowerCase() === "font") {
        checkFont(decl)
      }
    })

    function checkFont(decl) {
      const valueList = postcss.list.space(decl.value)
      // We do not need to more carefully distinguish font-weight
      // numbers from unitless line-heights because line-heights in
      // 'font' values need to be part of a font-size/line-height pair
      const hasNumericFontWeight = valueList.some(isNumbery)

      for (const value of postcss.list.space(decl.value)) {
        if (value.toLowerCase() === NORMAL_KEYWORD && !hasNumericFontWeight || isNumbery(value) || value.toLowerCase() !== NORMAL_KEYWORD
 && keywordSets.fontWeightKeywords.has(value.toLowerCase())) {
          checkWeight(value, decl)
          return
        }
      }
    }

    function checkWeight(weightValue, decl) {
      if (!isStandardSyntaxValue(weightValue)) {
        return
      }
      if (isVariable(weightValue)) {
        return
      }
      if (weightValue.toLowerCase() === INHERIT_KEYWORD || weightValue.toLowerCase() === INITIAL_KEYWORD) {
        return
      }

      if (optionsMatches(options, "ignore", "relative") && keywordSets.fontWeightRelativeKeywords.has(weightValue.toLowerCase())) {
        return
      }

      const weightValueOffset = decl.value.indexOf(weightValue)

      if (expectation === "numeric") {
        if (!isNumbery(weightValue)) {
          return complain(messages.expected("numeric"))
        }
      }

      if (expectation === "named-where-possible") {
        if (isNumbery(weightValue)) {
          if (_.includes(WEIGHTS_WITH_KEYWORD_EQUIVALENTS, weightValue)) {
            complain(messages.expected("named"))
          }
          return
        }
        if (!keywordSets.fontWeightKeywords.has(weightValue.toLowerCase()) && weightValue.toLowerCase() !== NORMAL_KEYWORD) {
          return complain(messages.invalidNamed(weightValue))
        }
        return
      }

      function complain(message) {
        report({
          ruleName,
          result,
          message,
          node: decl,
          index: declarationValueIndex(decl) + weightValueOffset,
        })
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-blacklist (blacklist)](#apidoc.element.stylelint.rules.function-blacklist)
- description and source-code
```javascript
function-blacklist = function (blacklist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }
    root.walkDecls(decl => {
      const value = decl.value

      valueParser(value).walk(function (node) {
        if (node.type !== "function") {
          return
        }
        if (!isStandardSyntaxFunction(node)) {
          return
        }
        if (!matchesStringOrRegExp(postcss.vendor.unprefixed(node.value).toLowerCase(), blacklist)) {
          return
        }

        report({
          message: messages.rejected(node.value),
          node: decl,
          index: declarationValueIndex(decl) + node.sourceIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-calc-no-unspaced-operator"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-calc-no-unspaced-operator (actual)](#apidoc.element.stylelint.rules.function-calc-no-unspaced-operator)
- description and source-code
```javascript
function-calc-no-unspaced-operator = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    function complain(message, node, index) {
      report({ message, node, index, result, ruleName })
    }

    root.walkDecls(decl => {
      valueParser(decl.value).walk(node => {
        if (node.type !== "function" || node.value.toLowerCase() !== "calc") {
          return
        }

        const parensMatch = balancedMatch("(", ")", valueParser.stringify(node))
        const rawExpression = parensMatch.body
        const expressionIndex = decl.source.start.column + decl.prop.length + (decl.raws.between || "").length + node.sourceIndex
        const expression = blurVariables(rawExpression)

        checkSymbol("+")
        checkSymbol("-")
        checkSymbol("*")
        checkSymbol("/")

        function checkSymbol(symbol) {
          const styleSearchOptions = {
            source: expression,
            target: symbol,
            functionArguments: "skip",
          }

          styleSearch(styleSearchOptions, match => {
            const index = match.startIndex

            // Deal with signs.
            // (@ and $ are considered "digits" here to allow for variable syntaxes
            // that permit signs in front of variables, e.g. '-$number')
            // As is "." to deal with fractional numbers without a leading zero
            if ((symbol === "+" || symbol === "-") && /[\d@\$.]/.test(expression[index + 1])) {
              const expressionBeforeSign = expression.substr(0, index)

              // Ignore signs that directly follow a opening bracket
              if (expressionBeforeSign[expressionBeforeSign.length - 1] === "(") {
                return
              }

              // Ignore signs at the beginning of the expression
              if (/^\s*$/.test(expressionBeforeSign)) {
                return
              }

              // Otherwise, ensure that there is a real operator preceeding them
              if (/[\*/+-]\s*$/.test(expressionBeforeSign)) {
                return
              }

              // And if not, complain
              complain(messages.expectedOperatorBeforeSign(symbol), decl, expressionIndex + index)
              return
            }

            const beforeOk = expression[index - 1] === " " && !isWhitespace(expression[index - 2]) || newlineBefore(expression,
index - 1)
            if (!beforeOk) {
              complain(messages.expectedBefore(symbol), decl, expressionIndex + index)
            }

            const afterOk = expression[index + 1] === " " && !isWhitespace(expression[index + 2]) || expression[index + 1] === "\n" || expression.substr(index + 1, 2) === "\r\n"

            if (!afterOk) {
              complain(messages.expectedAfter(symbol), decl, expressionIndex + index)
            }
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-comma-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.function-comma-newline-after)
- description and source-code
```javascript
function-comma-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    functionCommaSpaceChecker({
      root,
      result,
      locationChecker: checker.afterOneOnly,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-comma-newline-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.function-comma-newline-before)
- description and source-code
```javascript
function-comma-newline-before = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    functionCommaSpaceChecker({
      root,
      result,
      locationChecker: checker.beforeAllowingIndentation,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-comma-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-space-after (expectation)](#apidoc.element.stylelint.rules.function-comma-space-after)
- description and source-code
```javascript
function-comma-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    functionCommaSpaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-comma-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-comma-space-before (expectation)](#apidoc.element.stylelint.rules.function-comma-space-before)
- description and source-code
```javascript
function-comma-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    functionCommaSpaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-linear-gradient-no-nonstandard-direction"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-linear-gradient-no-nonstandard-direction (actual)](#apidoc.element.stylelint.rules.function-linear-gradient-no-nonstandard-direction)
- description and source-code
```javascript
function-linear-gradient-no-nonstandard-direction = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      functionArgumentsSearch(decl.toString().toLowerCase(), "linear-gradient", (expression, expressionIndex) => {
        const firstArg = expression.split(",")[0].trim()

        // If the first character is a number, we can assume the user intends an angle
        if (/[\d\.]/.test(firstArg[0])) {
          if (/^[\d\.]+(?:deg|grad|rad|turn)$/.test(firstArg)) {
            return
          }
          complain()
          return
        }

        // The first argument may not be a direction: it may be an angle,
        // or a color stop (in which case user gets default direction, "to bottom")
        // cf. https://drafts.csswg.org/css-images-3/#linear-gradient-syntax
        if (!/left|right|top|bottom/.test(firstArg)) {
          return
        }

        const withToPrefix = !postcss.vendor.prefix(decl.value)
        if (!isStandardDirection(firstArg, withToPrefix)) {
          complain()
          return
        }

        function complain() {
          report({
            message: messages.rejected,
            node: decl,
            index: expressionIndex,
            result,
            ruleName,
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-max-empty-lines"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-max-empty-lines (max)](#apidoc.element.stylelint.rules.function-max-empty-lines)
- description and source-code
```javascript
function-max-empty-lines = function (max) {
  const maxAdjacentNewlines = max + 1

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: max,
      possible: _.isNumber,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (decl.value.indexOf("(") === -1) {
        return
      }

      const declString = decl.toString()
      const repeatLFNewLines = _.repeat("\n", maxAdjacentNewlines)
      const repeatCRLFNewLines = _.repeat("\r\n", maxAdjacentNewlines)

      styleSearch({
        source: declString,
        target: "\n",
        functionArguments: "only",
      }, match => {
        if (declString.substr(match.startIndex + 1, maxAdjacentNewlines) === repeatLFNewLines || declString.substr(match.startIndex
 + 1, maxAdjacentNewlines * 2) === repeatCRLFNewLines) {
          // Put index at '\r' if it's CRLF, otherwise leave it at '\n'
          let index = match.startIndex
          if (declString[index - 1] === "\r") {
            index -= 1
          }

          report({
            message: messages.expected(max),
            node: decl,
            index,
            result,
            ruleName,
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-name-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-name-case (expectation, options)](#apidoc.element.stylelint.rules.function-name-case)
- description and source-code
```javascript
function-name-case = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    }, {
      actual: options,
      possible: {
        ignoreFunctions: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const value = decl.value

      valueParser(value).walk(function (node) {
        if (node.type !== "function" || !isStandardSyntaxFunction(node)) {
          return
        }

        const functionName = node.value
        const functionNameLowerCase = functionName.toLowerCase()

        const ignoreFunctions = options && options.ignoreFunctions || []

        if (ignoreFunctions.length > 0 && matchesStringOrRegExp(functionName, ignoreFunctions)) {
          return
        }

        let expectedFunctionName = null

        if (expectation === "lower" && mapLowercaseFunctionNamesToCamelCase.has(functionNameLowerCase)) {
          expectedFunctionName = mapLowercaseFunctionNamesToCamelCase.get(functionNameLowerCase)
        } else if (expectation === "lower") {
          expectedFunctionName = functionNameLowerCase
        } else {
          expectedFunctionName = functionName.toUpperCase()
        }

        if (functionName === expectedFunctionName) {
          return
        }

        report({
          message: messages.expected(functionName, expectedFunctionName),
          node: decl,
          index: declarationValueIndex(decl) + node.sourceIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-parentheses-newline-inside"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-parentheses-newline-inside (expectation)](#apidoc.element.stylelint.rules.function-parentheses-newline-inside)
- description and source-code
```javascript
function-parentheses-newline-inside = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (decl.value.indexOf("(") === -1) {
        return
      }

      valueParser(decl.value).walk(valueNode => {
        if (valueNode.type !== "function") {
          return
        }

        if (!isStandardSyntaxFunction(valueNode)) {
          return
        }

        const functionString = valueParser.stringify(valueNode)
        const isMultiLine = !isSingleLineString(functionString)
        function containsNewline(str) {
          return str.indexOf("\n") !== -1
        }

        // Check opening ...

        const openingIndex = valueNode.sourceIndex + valueNode.value.length + 1

        if (expectation === "always" && !containsNewline(valueNode.before)) {
          complain(messages.expectedOpening, openingIndex)
        }

        if (isMultiLine && expectation === "always-multi-line" && !containsNewline(valueNode.before)) {
          complain(messages.expectedOpeningMultiLine, openingIndex)
        }

        if (isMultiLine && expectation === "never-multi-line" && valueNode.before !== "") {
          complain(messages.rejectedOpeningMultiLine, openingIndex)
        }

        // Check closing ...

        const closingIndex = valueNode.sourceIndex + functionString.length - 2

        if (expectation === "always" && !containsNewline(valueNode.after)) {
          complain(messages.expectedClosing, closingIndex)
        }

        if (isMultiLine && expectation === "always-multi-line" && !containsNewline(valueNode.after)) {
          complain(messages.expectedClosingMultiLine, closingIndex)
        }

        if (isMultiLine && expectation === "never-multi-line" && valueNode.after !== "") {
          complain(messages.rejectedClosingMultiLine, closingIndex)
        }
      })

      function complain(message, offset) {
        report({
          ruleName,
          result,
          message,
          node: decl,
          index: declarationValueIndex(decl) + offset,
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-parentheses-space-inside"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-parentheses-space-inside (expectation)](#apidoc.element.stylelint.rules.function-parentheses-space-inside)
- description and source-code
```javascript
function-parentheses-space-inside = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (decl.value.indexOf("(") === -1) {
        return
      }

      valueParser(decl.value).walk(valueNode => {
        if (valueNode.type !== "function") {
          return
        }

        if (!isStandardSyntaxFunction(valueNode)) {
          return
        }

        const functionString = valueParser.stringify(valueNode)
        const isSingleLine = isSingleLineString(functionString)

        // Check opening ...

        const openingIndex = valueNode.sourceIndex + valueNode.value.length + 1

        if (expectation === "always" && valueNode.before !== " ") {
          complain(messages.expectedOpening, openingIndex)
        }

        if (expectation === "never" && valueNode.before !== "") {
          complain(messages.rejectedOpening, openingIndex)
        }

        if (isSingleLine && expectation === "always-single-line" && valueNode.before !== " ") {
          complain(messages.expectedOpeningSingleLine, openingIndex)
        }

        if (isSingleLine && expectation === "never-single-line" && valueNode.before !== "") {
          complain(messages.rejectedOpeningSingleLine, openingIndex)
        }

        // Check closing ...

        const closingIndex = valueNode.sourceIndex + functionString.length - 2

        if (expectation === "always" && valueNode.after !== " ") {
          complain(messages.expectedClosing, closingIndex)
        }

        if (expectation === "never" && valueNode.after !== "") {
          complain(messages.rejectedClosing, closingIndex)
        }

        if (isSingleLine && expectation === "always-single-line" && valueNode.after !== " ") {
          complain(messages.expectedClosingSingleLine, closingIndex)
        }

        if (isSingleLine && expectation === "never-single-line" && valueNode.after !== "") {
          complain(messages.rejectedClosingSingleLine, closingIndex)
        }
      })

      function complain(message, offset) {
        report({
          ruleName,
          result,
          message,
          node: decl,
          index: declarationValueIndex(decl) + offset,
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-url-data-uris"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-data-uris (expectation)](#apidoc.element.stylelint.rules.function-url-data-uris)
- description and source-code
```javascript
function-url-data-uris = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(function (decl) {
      valueParser(decl.value).walk(valueNode => {
        if (valueNode.type !== "function" || valueNode.value.toLowerCase() !== "url" || !valueNode.nodes.length > 0) {
          return
        }

        const urlValueNode = valueNode.nodes[0]

        if (!urlValueNode.value || !isStandardSyntaxValue(urlValueNode.value) || isVariable(urlValueNode.value)) {
          return
        }

        const valueContainDataUris = urlValueNode.value.toLowerCase().indexOf("data:") === 0
        const needUrlDataUris = expectation === "always"

        if (valueContainDataUris && needUrlDataUris || !valueContainDataUris && !needUrlDataUris) {
          return
        }

        const message = needUrlDataUris ? messages.expected : messages.rejected

        report({
          message,
          node: decl,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-url-no-scheme-relative"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-no-scheme-relative (actual)](#apidoc.element.stylelint.rules.function-url-no-scheme-relative)
- description and source-code
```javascript
function-url-no-scheme-relative = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(function (decl) {
      functionArgumentsSearch(decl.toString().toLowerCase(), "url", (args, index) => {
        const url = _.trim(args, " '\"")

        if (!isStandardSyntaxUrl(url) || url.indexOf("//") !== 0) {
          return
        }

        report({
          message: messages.rejected,
          node: decl,
          index,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-url-quotes"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-quotes (expectation, options)](#apidoc.element.stylelint.rules.function-url-quotes)
- description and source-code
```javascript
function-url-quotes = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    }, {
      actual: options,
      possible: {
        except: ["empty"],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(checkStatement)
    root.walkRules(checkStatement)

    function checkStatement(statement) {
      if (statement.type === "atrule") {
        checkAtRuleParams(statement)
      }

      statement.walkDecls(function (decl) {
        functionArgumentsSearch(decl.toString().toLowerCase(), "url", (args, index) => {
          checkArgs(args, decl, index, "url")
        })
      })
    }

    function checkAtRuleParams(atRule) {
      const atRuleParamsLowerCase = atRule.params.toLowerCase()
      functionArgumentsSearch(atRuleParamsLowerCase, "url", (args, index) => {
        checkArgs(args, atRule, index + atRuleParamIndex(atRule), "url")
      })
      functionArgumentsSearch(atRuleParamsLowerCase, "url-prefix", (args, index) => {
        checkArgs(args, atRule, index + atRuleParamIndex(atRule), "url-prefix")
      })
      functionArgumentsSearch(atRuleParamsLowerCase, "domain", (args, index) => {
        checkArgs(args, atRule, index + atRuleParamIndex(atRule), "domain")
      })
    }

    function checkArgs(args, node, index, functionName) {
      let shouldHasQuotes = expectation === "always"

      const leftTrimmedArgs = args.trimLeft()
      if (!isStandardSyntaxUrl(leftTrimmedArgs)) {
        return
      }
      const complaintIndex = index + args.length - leftTrimmedArgs.length
      const hasQuotes = leftTrimmedArgs[0] === "'" || leftTrimmedArgs[0] === "\""

      const trimmedArg = args.trim()
      const isEmptyArgument = _.includes([
        "",
        "''",
        "\"\"",
      ], trimmedArg)
      if (optionsMatches(options, "except", "empty") && isEmptyArgument) {
        shouldHasQuotes = !shouldHasQuotes
      }

      if (shouldHasQuotes) {
        if (hasQuotes) {
          return
        }
        complain(messages.expected(functionName), node, complaintIndex)
      } else {
        if (!hasQuotes) {
          return
        }
        complain(messages.rejected(functionName), node, complaintIndex)
      }
    }

    function complain(message, node, index) {
      report({
        message,
        node,
        index,
        result,
        ruleName,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-url-scheme-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-url-scheme-whitelist (whitelist)](#apidoc.element.stylelint.rules.function-url-scheme-whitelist)
- description and source-code
```javascript
function-url-scheme-whitelist = function (whitelist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(function (decl) {
      functionArgumentsSearch(decl.toString().toLowerCase(), "url", (args, index) => {
        const unspacedUrlString = _.trim(args, " ")
        if (!isStandardSyntaxUrl(unspacedUrlString)) {
          return
        }
        const urlString = _.trim(unspacedUrlString, "'\"")

        const url = parse(urlString)
        if (url.protocol === null) {
          return
        }

        const scheme = url.protocol.toLowerCase().slice(0, -1) // strip trailing ':'

        // The URL spec does not require a scheme to be followed by '//', but checking
        // for it allows this rule to differentiate <scheme>:<hostname> urls from
        // <hostname>:<port> urls. 'data:' scheme urls are an exception to this rule.
        const slashIndex = url.protocol.length
        const expectedSlashes = urlString.slice(slashIndex, slashIndex + 2)
        const isSchemeLessUrl = expectedSlashes !== "//" && scheme !== "data"
        if (isSchemeLessUrl) {
          return
        }

        const whitelistLowerCase = typeof whitelist === "string" ? whitelist.toLowerCase() : whitelist.join("|").toLowerCase().split
("|")

        if (containsString(scheme, whitelistLowerCase)) {
          return
        }

        report({
          message: messages.rejected(scheme),
          node: decl,
          index,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-whitelist (whitelistInput)](#apidoc.element.stylelint.rules.function-whitelist)
- description and source-code
```javascript
function-whitelist = function (whitelistInput) {
  const whitelist = [].concat(whitelistInput)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }
    root.walkDecls(decl => {
      const value = decl.value

      valueParser(value).walk(function (node) {
        if (node.type !== "function") {
          return
        }
        if (!isStandardSyntaxFunction(node)) {
          return
        }
        if (matchesStringOrRegExp(postcss.vendor.unprefixed(node.value).toLowerCase(), whitelist)) {
          return
        }
        report({
          message: messages.rejected(node.value),
          node: decl,
          index: declarationValueIndex(decl) + node.sourceIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.function-whitespace-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>function-whitespace-after (expectation)](#apidoc.element.stylelint.rules.function-whitespace-after)
- description and source-code
```javascript
function-whitespace-after = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const declString = decl.toString()

      styleSearch({
        source: declString,
        target: ")",
        functionArguments: "only",
      }, match => {
        checkClosingParen(declString, match.startIndex, decl)
      })
    })

    function checkClosingParen(source, index, node) {
      const nextChar = source[index + 1]
      if (expectation === "always") {
        // Allow for the next character to be a single empty space,
        // another closing parenthesis, a comma, or the end of the value
        if (nextChar === " ") {
          return
        }
        if (nextChar === "\n") {
          return
        }
        if (source.substr(index + 1, 2) === "\r\n") {
          return
        }
        if (ACCEPTABLE_AFTER_CLOSING_PAREN.has(nextChar)) {
          return
        }
        report({
          message: messages.expected,
          node,
          index: index + 1,
          result,
          ruleName,
        })
      } else if (expectation === "never") {
        if (isWhitespace(nextChar)) {
          report({
            message: messages.rejected,
            node,
            index: index + 1,
            result,
            ruleName,
          })
        }
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.indentation"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>indentation (space)](#apidoc.element.stylelint.rules.indentation)
- description and source-code
```javascript
indentation = function (space) {
  const options = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : {}

  const isTab = space === "tab"
  const indentChar = isTab ? "\t" : _.repeat(" ", space)
  const warningWord = isTab ? "tab" : "space"

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: space,
      possible: [
        _.isNumber,
        "tab",
      ],
    }, {
      actual: options,
      possible: {
        except: [
          "block",
          "value",
          "param",
        ],
        ignore: [
          "value",
          "param",
          "inside-parens",
        ],
        indentInsideParens: [
          "twice",
          "once-at-root-twice-in-block",
        ],
        indentClosingBrace: [_.isBoolean],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    // Cycle through all nodes using walk.
    root.walk(node => {
      const nodeLevel = indentationLevel(node)
      const expectedWhitespace = _.repeat(indentChar, nodeLevel)

      let before = (node.raws.before || "")
      const after = (node.raws.after || "")

      // Only inspect the spaces before the node
      // if this is the first node in root
      // or there is a newline in the 'before' string.
      // (If there is no newline before a node,
      // there is no "indentation" to check.)
      const inspectBefore = root.first === node || before.indexOf("\n") !== -1

      // Cut out any * hacks from 'before'
      before = before[before.length - 1] === "*" || before[before.length - 1] === "_" ? before.slice(0, before.length - 1) : before

      // Inspect whitespace in the 'before' string that is
      // *after* the *last* newline character,
      // because anything besides that is not indentation for this node:
      // it is some other kind of separation, checked by some separate rule
      if (inspectBefore && before.slice(before.lastIndexOf("\n") + 1) !== expectedWhitespace) {
        report({
          message: messages.expected(legibleExpectation(nodeLevel)),
          node,
          result,
          ruleName,
        })
      }

      // Only blocks have the 'after' string to check.
      // Only inspect 'after' strings that start with a newline;
      // otherwise there's no indentation involved.
      // And check 'indentClosingBrace' to see if it should be indented an extra level.
      const closingBraceLevel = options.indentClosingBrace ? nodeLevel + 1 : nodeLevel
      if (hasBlock(node) && after && after.indexOf("\n") !== -1 && after.slice(after.lastIndexOf("\n") + 1) !== _.repeat(indentChar
, closingBraceLevel)) {
        report({
          message: messages.expected(legibleExpectation(closingBraceLevel)),
          node,
          index: node.toString().length - 1,
          result,
          ruleName,
        })
      }

      // If this is a declaration, check the value
      if (node.value) {
        checkValue(node, nodeLevel)
      }

      // If this is a rule, check the selector
      if (node.selector) {
        checkSelector(node, nodeLevel)
      }

      // If this is an at rule, check the params
      if (node.type === "atrule") {
        checkAtRuleParams(node, nodeLevel)
      }
    })

    function indentationLevel(node) {
      const level = arguments.length > 1 && arguments[1] !== undefined ? arguments[1] : 0

      if (node.parent.type === "root") {
        return level
      }

      let calculatedLevel

      // Indentation level equals the ancestor nodes
      // separating this node from root; so recursively
      // run this operation
      calculatedLevel = indentationLevel(node.parent, level + 1)

      // If options.except includes "block",
      // blocks are taken down one from their calculated level
      // (all blocks are the same level as their parents)
      if (optionsMatches(options, "except", "block") && (node.type === "rule" || node.type === "atrule") && hasBlock(node)) {
        calculatedLevel--
      }

      return calculatedLevel
    }

    function checkValue(decl, declLevel) { ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.keyframe-declaration-no-important"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>keyframe-declaration-no-important (actual)](#apidoc.element.stylelint.rules.keyframe-declaration-no-important)
- description and source-code
```javascript
keyframe-declaration-no-important = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^(-(moz|webkit)-)?keyframes$/i, atRuleKeyframes => {
      atRuleKeyframes.walkDecls(decl => {
        if (!decl.important) {
          return
        }
        report({
          message: messages.rejected,
          node: decl,
          word: "important",
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.length-zero-no-unit"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>length-zero-no-unit (actual)](#apidoc.element.stylelint.rules.length-zero-no-unit)
- description and source-code
```javascript
length-zero-no-unit = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      check(blurComments(decl.toString()), decl)
    })

    root.walkAtRules(atRule => {
      const source = hasBlock(atRule) ? beforeBlockString(atRule, { noRawBefore: true }) : atRule.toString()
      check(source, atRule)
    })

    function check(value, node) {
      const ignorableIndexes = new Set()

      styleSearch({ source: value, target: "0" }, match => {
        const index = match.startIndex

        // Given a 0 somewhere in the full property value (not in a string, thanks
        // to styleSearch) we need to isolate the value that contains the zero.
        // To do so, we'll find the last index before the 0 of a character that would
        // divide one value in a list from another, and the next index of such a
        // character; then we build a substring from those indexes, which we can
        // assess.

        // If a single value includes multiple 0's (e.g. 100.01px), we don't want
        // each 0 to be treated as a separate value, possibly resulting in multiple
        // warnings for the same value (e.g. 0.00px).
        //
        // This check prevents that from happening: we build and check against a
        // Set containing all the indexes that are part of a value already validated.
        if (ignorableIndexes.has(index)) {
          return
        }

        const prevValueBreakIndex = _.findLastIndex(value.substr(0, index), char => {
          return [
            " ",
            ",",
            ")",
            "(",
            "#",
          ].indexOf(char) !== -1
        })

        // Ignore hex colors
        if (value[prevValueBreakIndex] === "#") {
          return
        }

        // If no prev break was found, this value starts at 0
        const valueWithZeroStart = prevValueBreakIndex === -1 ? 0 : prevValueBreakIndex + 1

        const nextValueBreakIndex = _.findIndex(value.substr(valueWithZeroStart), char => {
          return [
            " ",
            ",",
            ")",
          ].indexOf(char) !== -1
        })

        // If no next break was found, this value ends at the end of the string
        const valueWithZeroEnd = nextValueBreakIndex === -1 ? value.length : nextValueBreakIndex + valueWithZeroStart

        const valueWithZero = value.slice(valueWithZeroStart, valueWithZeroEnd)
        const parsedValue = valueParser.unit(valueWithZero)

        if (!parsedValue || parsedValue && !parsedValue.unit) {
          return
        }

        // Add the indexes to ignorableIndexes so the same value will not
        // be checked multiple times.
        _.range(valueWithZeroStart, valueWithZeroEnd).forEach(i => ignorableIndexes.add(i))

        // Only pay attention if the value parses to 0
        // and units with lengths
        if (parseFloat(valueWithZero, 10) !== 0 || !keywordSets.lengthUnits.has(parsedValue.unit.toLowerCase())) {
          return
        }

        report({
          message: messages.rejected,
          node,
          index: valueWithZeroEnd - parsedValue.unit.length,
          result,
          ruleName,
        })
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.max-empty-lines"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>max-empty-lines (max, options)](#apidoc.element.stylelint.rules.max-empty-lines)
- description and source-code
```javascript
max-empty-lines = function (max, options) {
  const maxAdjacentNewlines = max + 1

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: max,
      possible: _.isNumber,
    }, {
      actual: options,
      possible: {
        ignore: [
          "comments",
        ],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    const rootString = root.toString()
    const repeatLFNewLines = _.repeat("\n", maxAdjacentNewlines)
    const repeatCRLFNewLines = _.repeat("\r\n", maxAdjacentNewlines)
    const ignoreComments = optionsMatches(options, "ignore", "comments")

    styleSearch({ source: rootString, target: "\n" }, match => {
      checkMatch(rootString, match.endIndex, root)
    })

    // We must check comments separately in order to accommodate stupid
    // '//'-comments from SCSS, which postcss-scss converts to '/* ... */',
    // which adds to extra characters at the end, which messes up our
    // warning position
    if (!ignoreComments) {
      root.walkComments(comment => {
        const source = (comment.raws.left || "") + comment.text + (comment.raws.right || "")
        styleSearch({ source, target: "\n" }, match => {
          checkMatch(source, match.endIndex, comment, 2)
        })
      })
    }

    function checkMatch(source, matchEndIndex, node) {
      const offset = arguments.length > 3 && arguments[3] !== undefined ? arguments[3] : 0

      let violationIndex = false
      if (source.substr(matchEndIndex, maxAdjacentNewlines) === repeatLFNewLines) {
        violationIndex = matchEndIndex + maxAdjacentNewlines
      } else if (source.substr(matchEndIndex, maxAdjacentNewlines * 2) === repeatCRLFNewLines) {
        violationIndex = matchEndIndex + maxAdjacentNewlines * 2
      }

      if (!violationIndex) {
        return
      }

      report({
        message: messages.expected(max),
        node,
        index: violationIndex + offset,
        result,
        ruleName,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.max-line-length"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>max-line-length (maxLength, options)](#apidoc.element.stylelint.rules.max-line-length)
- description and source-code
```javascript
max-line-length = function (maxLength, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: maxLength,
      possible: _.isNumber,
    }, {
      actual: options,
      possible: {
        ignore: [
          "non-comments",
          "comments",
        ],
        ignorePattern: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    const rootString = root.source.input.css

    const ignoreNonComments = optionsMatches(options, "ignore", "non-comments")
    const ignoreComments = optionsMatches(options, "ignore", "comments")

    // Check first line
    checkNewline({ endIndex: 0 })

    // Check subsequent lines
    styleSearch({ source: rootString, target: ["\n"], comments: "check" }, checkNewline)

    function complain(index) {
      report({
        index,
        result,
        ruleName,
        message: messages.expected(maxLength),
        node: root,
      })
    }

    function checkNewline(match) {
      let nextNewlineIndex = rootString.indexOf("\n", match.endIndex)
      if (rootString[nextNewlineIndex - 1] === "\r") {
        nextNewlineIndex -= 1
      }

      // Accommodate last line
      if (nextNewlineIndex === -1) {
        nextNewlineIndex = rootString.length
      }

      const rawLineLength = nextNewlineIndex - match.endIndex
      const lineText = rootString.slice(match.endIndex, nextNewlineIndex)

      if (optionsMatches(options, "ignorePattern", lineText)) {
        return
      }

      const urlArgumentsLength = execall(/url\((.*)\)/ig, lineText).reduce((result, match) => {
        return result + _.get(match, "sub[0].length", 0)
      }, 0)

      const importUrlsLength = execall(/\@import\s+(['"].*['"])/ig, lineText).reduce((result, match) => {
        return result + _.get(match, "sub[0].length", 0)
      }, 0)

      // If the line's length is less than or equal to the specified
      // max, ignore it ... So anything below is liable to be complained about.
      // **Note that the length of any url arguments or import urls
      // are excluded from the calculation.**
      if (rawLineLength - urlArgumentsLength - importUrlsLength <= maxLength) {
        return
      }

      const complaintIndex = nextNewlineIndex - 1

      if (ignoreComments) {
        if (match.insideComment) {
          return
        }

        // This trimming business is to notice when the line starts a
        // comment but that comment is indented, e.g.
        //<span class="apidocCodeCommentSpan">       /* something here */
</span>        const nextTwoChars = rootString.slice(match.endIndex).trim().slice(0, 2)
        if (nextTwoChars === "/*" || nextTwoChars === "//") {
          return
        }
      }

      if (ignoreNonComments) {
        if (match.insideComment) {
          return complain(complaintIndex)
        }

        // This trimming business is to notice when the line starts a
        // comment but that comment is indented, e.g.
        //       /* something here */
        const nextTwoChars = rootString.slice(match.endIndex).trim().slice(0, 2)
        if (nextTwoChars !== "/*" && nextTwoChars !== "//") {
          return
        }
        return complain(complaintIndex)
      }

      // If there are no spaces besides initial (indent) spaces, ignore it
      const lineString = rootString.slice(match.endIndex, nextNewlineIndex)
      if (lineString.replace(/^\s+/, "").indexOf(" ") === -1) {
        return
      }

      return complain(complaintIndex)
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.max-nesting-depth"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>max-nesting-depth (max, options)](#apidoc.element.stylelint.rules.max-nesting-depth)
- description and source-code
```javascript
max-nesting-depth = function (max, options) {
  const ignoreAtRulesWithoutDeclarationBlocks = optionsMatches(options, "ignore", "at-rules-without-declaration-blocks") || optionsMatches
(options, "ignore", "blockless-at-rules")
  const isIgnoreAtRule = node => node.type === "atrule" && optionsMatches(options, "ignoreAtRules", node.name)

  return (root, result) => {
    validateOptions(result, ruleName, {
      actual: max,
      possible: [_.isNumber],
    }, {
      optional: true,
      actual: options,
      possible: {
        ignore: [
          "at-rules-without-declaration-blocks",
          "blockless-at-rules",
        ],
        ignoreAtRules: [_.isString],
      },
    })

    if (optionsMatches(options, "ignore", "at-rules-without-declaration-blocks")) {
      result.warn((
        "'max-nesting-depth\'s' \"at-rules-without-declaration-blocks\" option has been deprecated and in 8.0 will be removed. Instead
 use the\"blockless-at-rules\" option."
      ), {
        stylelintType: "deprecation",
        stylelintReference: "https://stylelint.io/user-guide/rules/max-nesting-depth/",
      })
    }

    root.walkRules(checkStatement)
    root.walkAtRules(checkStatement)

    function checkStatement(statement) {
      if (isIgnoreAtRule(statement)) {
        return
      }
      if (!hasBlock(statement)) {
        return
      }
      const depth = nestingDepth(statement)
      if (depth > max) {
        report({
          ruleName,
          result,
          node: statement,
          message: messages.expected(max),
        })
      }
    }
  }

  function nestingDepth(node, level) {
    level = level || 0
    const parent = node.parent

    if (isIgnoreAtRule(parent)) {
      return 0
    }

    // The nesting depth level's computation has finished
    // when this function, recursively called, receives
    // a node that is not nested -- a direct child of the
    // root node
    if (parent.type === "root" || parent.type === "atrule" && parent.parent.type === "root") {
      return level
    }

    if (ignoreAtRulesWithoutDeclarationBlocks && node.type === "atrule" && node.every(child => child.type !== "decl")) {
      return nestingDepth(parent, level)
    }

    // Unless any of the conditions above apply, we want to
    // add 1 to the nesting depth level and then check the parent,
    // continuing to add and move up the hierarchy
    // until we hit the root node
    return nestingDepth(parent, level + 1)
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-colon-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-colon-space-after (expectation)](#apidoc.element.stylelint.rules.media-feature-colon-space-after)
- description and source-code
```javascript
media-feature-colon-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    mediaFeatureColonSpaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-colon-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-colon-space-before (expectation)](#apidoc.element.stylelint.rules.media-feature-colon-space-before)
- description and source-code
```javascript
media-feature-colon-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    mediaFeatureColonSpaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-name-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-blacklist (blacklist)](#apidoc.element.stylelint.rules.media-feature-name-blacklist)
- description and source-code
```javascript
media-feature-name-blacklist = function (blacklist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      mediaParser(atRule.params).walk(/^media-feature$/i, mediaFeatureNode => {
        const parent = mediaFeatureNode.parent,
          sourceIndex = mediaFeatureNode.sourceIndex,
          value = mediaFeatureNode.value

        if (isRangeContextMediaFeature(parent.value) || !isStandardSyntaxMediaFeatureName(value) || isCustomMediaQuery(value)) {
          return
        }

        if (!matchesStringOrRegExp(value.toLowerCase(), blacklist)) {
          return
        }

        report({
          index: atRuleParamIndex(atRule) + sourceIndex,
          message: messages.rejected(value),
          node: atRule,
          ruleName,
          result,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-name-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-case (expectation)](#apidoc.element.stylelint.rules.media-feature-name-case)
- description and source-code
```javascript
media-feature-name-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      mediaParser(atRule.params).walk(/^media-feature$/i, mediaFeatureNode => {
        const parent = mediaFeatureNode.parent,
          sourceIndex = mediaFeatureNode.sourceIndex,
          value = mediaFeatureNode.value

        if (isRangeContextMediaFeature(parent.value) || !isStandardSyntaxMediaFeatureName(value) || isCustomMediaQuery(value)) {
          return
        }

        const expectedFeatureName = expectation === "lower" ? value.toLowerCase() : value.toUpperCase()

        if (value === expectedFeatureName) {
          return
        }

        report({
          index: atRuleParamIndex(atRule) + sourceIndex,
          message: messages.expected(value, expectedFeatureName),
          node: atRule,
          ruleName,
          result,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-name-no-unknown"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-no-unknown (actual, options)](#apidoc.element.stylelint.rules.media-feature-name-no-unknown)
- description and source-code
```javascript
media-feature-name-no-unknown = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignoreMediaFeatureNames: [_.isString],
      },
      optional: true,
    })

    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      mediaParser(atRule.params).walk(/^media-feature$/i, mediaFeatureNode => {
        const parent = mediaFeatureNode.parent,
          sourceIndex = mediaFeatureNode.sourceIndex,
          value = mediaFeatureNode.value

        if (isRangeContextMediaFeature(parent.value) || !isStandardSyntaxMediaFeatureName(value) || isCustomMediaQuery(value)) {
          return
        }

        if (optionsMatches(options, "ignoreMediaFeatureNames", value)) {
          return
        }

        if (postcss.vendor.prefix(value) || keywordSets.mediaFeatureNames.has(value.toLowerCase())) {
          return
        }

        report({
          index: atRuleParamIndex(atRule) + sourceIndex,
          message: messages.rejected(value),
          node: atRule,
          ruleName,
          result,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-name-no-vendor-prefix"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.media-feature-name-no-vendor-prefix)
- description and source-code
```javascript
media-feature-name-no-vendor-prefix = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      const params = atRule.params

      if (!isAutoprefixable.mediaFeatureName(params)) {
        return
      }
      const matches = atRule.toString().match(/[a-z-]+device-pixel-ratio/ig)

      if (!matches) { return }

      matches.forEach(match => {
        report({
          message: messages.rejected,
          node: atRule,
          word: match,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-name-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-name-whitelist (whitelist)](#apidoc.element.stylelint.rules.media-feature-name-whitelist)
- description and source-code
```javascript
media-feature-name-whitelist = function (whitelist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      mediaParser(atRule.params).walk(/^media-feature$/i, mediaFeatureNode => {
        const parent = mediaFeatureNode.parent,
          sourceIndex = mediaFeatureNode.sourceIndex,
          value = mediaFeatureNode.value

        if (isRangeContextMediaFeature(parent.value) || !isStandardSyntaxMediaFeatureName(value) || isCustomMediaQuery(value)) {
          return
        }

        if (matchesStringOrRegExp(value.toLowerCase(), whitelist)) {
          return
        }

        report({
          index: atRuleParamIndex(atRule) + sourceIndex,
          message: messages.rejected(value),
          node: atRule,
          ruleName,
          result,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-no-missing-punctuation"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-no-missing-punctuation (actual)](#apidoc.element.stylelint.rules.media-feature-no-missing-punctuation)
- description and source-code
```javascript
media-feature-no-missing-punctuation = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    result.warn((
      "'media-feature-no-missing-punctuation' has been deprecated and in 8.0 will be removed."
    ), {
      stylelintType: "deprecation",
      stylelintReference: "https://stylelint.io/user-guide/rules/media-feature-no-missing-punctuation/",
    })

    root.walkAtRules(/^media$/i, atRule => {
      execall(/\((.*?)\)/g, atRule.params).forEach(mediaFeatureMatch => {
        if (!isStandardSyntaxMediaFeature(mediaFeatureMatch.match)) {
          return
        }

        const splitMediaFeature = mediaFeatureMatch.sub[0].trim().split(/\s+/)
        if (splitMediaFeature.length === 1) {
          return
        }

        // Ignore the last one
        for (let i = 0, l = splitMediaFeature.length - 1; i < l; i++) {
          const mediaFeaturePart = splitMediaFeature[i]

          // This part is valid if it is punctuation,
          // it ends with punctuation,
          // the next part is punctuation,
          // or the next part begins with punctuation
          if (isPunctuation(mediaFeaturePart)) {
            continue
          }
          if (endsWithPunctuation(mediaFeaturePart)) {
            continue
          }
          const nextPart = splitMediaFeature[i + 1]
          if (isPunctuation(nextPart)) {
            continue
          }
          if (startsWithPunctuation(nextPart)) {
            continue
          }

          return report({
            result,
            ruleName,
            message: messages.rejected,
            node: atRule,
            index: atRuleParamIndex(atRule) + mediaFeatureMatch.index,
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-parentheses-space-inside"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-parentheses-space-inside (expectation)](#apidoc.element.stylelint.rules.media-feature-parentheses-space-inside)
- description and source-code
```javascript
media-feature-parentheses-space-inside = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      // If there are comments in the params, the complete string
      // will be at atRule.raws.params.raw
      const params = _.get(atRule, "raws.params.raw", atRule.params)
      const indexBoost = atRuleParamIndex(atRule)

      styleSearch({ source: params, target: "(" }, match => {
        const nextCharIsSpace = params[match.startIndex + 1] === " "
        if (nextCharIsSpace && expectation === "never") {
          report({
            message: messages.rejectedOpening,
            node: atRule,
            index: match.startIndex + 1 + indexBoost,
            result,
            ruleName,
          })
        }
        if (!nextCharIsSpace && expectation === "always") {
          report({
            message: messages.expectedOpening,
            node: atRule,
            index: match.startIndex + 1 + indexBoost,
            result,
            ruleName,
          })
        }
      })

      styleSearch({ source: params, target: ")" }, match => {
        const prevCharIsSpace = params[match.startIndex - 1] === " "
        if (prevCharIsSpace && expectation === "never") {
          report({
            message: messages.rejectedClosing,
            node: atRule,
            index: match.startIndex - 1 + indexBoost,
            result,
            ruleName,
          })
        }
        if (!prevCharIsSpace && expectation === "always") {
          report({
            message: messages.expectedClosing,
            node: atRule,
            index: match.startIndex - 1 + indexBoost,
            result,
            ruleName,
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-range-operator-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-range-operator-space-after (expectation)](#apidoc.element.stylelint.rules.media-feature-range-operator-space-after)
- description and source-code
```javascript
media-feature-range-operator-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      findMediaOperator(atRule, checkAfterOperator)
    })

    function checkAfterOperator(match, params, node) {
      const endIndex = match.index + match[1].length

      checker.after({
        source: params,
        index: endIndex,
        err: m => {
          report({
            message: m,
            node,
            index: endIndex + atRuleParamIndex(node) + 1,
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-feature-range-operator-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-feature-range-operator-space-before (expectation)](#apidoc.element.stylelint.rules.media-feature-range-operator-space-before)
- description and source-code
```javascript
media-feature-range-operator-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(/^media$/i, atRule => {
      findMediaOperator(atRule, checkBeforeOperator)
    })

    function checkBeforeOperator(match, params, node) {
      // The extra '+ 1' is because the match itself contains
      // the character before the operator
      checker.before({
        source: params,
        index: match.index + 1,
        err: m => {
          report({
            message: m,
            node,
            index: match.index + atRuleParamIndex(node),
            result,
            ruleName,
          })
        },
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-query-list-comma-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-newline-after)
- description and source-code
```javascript
media-query-list-comma-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    // Only check for the newline after the comma, while allowing
    // arbitrary indentation after the newline
    mediaQueryListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.afterOneOnly,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-query-list-comma-newline-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-newline-before)
- description and source-code
```javascript
media-query-list-comma-newline-before = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }
    mediaQueryListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.beforeAllowingIndentation,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-query-list-comma-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-space-after (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-space-after)
- description and source-code
```javascript
media-query-list-comma-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }
    mediaQueryListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.media-query-list-comma-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>media-query-list-comma-space-before (expectation)](#apidoc.element.stylelint.rules.media-query-list-comma-space-before)
- description and source-code
```javascript
media-query-list-comma-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    mediaQueryListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-browser-hacks"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-browser-hacks (on, options)](#apidoc.element.stylelint.rules.no-browser-hacks)
- description and source-code
```javascript
no-browser-hacks = function (on, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual: on }, {
      optional: true,
      actual: options,
      possible: {
        browsers: [_.isString],
      },
    })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed. Use 'stylelint-no-browser-hacks' plugin instead.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    const stylehacksOptions = { lint: true }
    if (options && options.browsers) {
      stylehacksOptions.browsers = options.browsers
    }

    const stylehacksResult = new Result()
    stylehacks(stylehacksOptions)(root, stylehacksResult)
    stylehacksResult.warnings().forEach(stylehacksWarning => {
      const message = messages.rejected(stylehacksWarning.identifier, stylehacksWarning.hack)
      report({
        ruleName,
        result,
        message,
        node: stylehacksWarning.node,
        line: stylehacksWarning.line,
        column: stylehacksWarning.column,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-descending-specificity"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-descending-specificity (actual)](#apidoc.element.stylelint.rules.no-descending-specificity)
- description and source-code
```javascript
no-descending-specificity = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    const selectorContextLookup = nodeContextLookup()

    root.walkRules(rule => {
      // Ignore custom property set '--foo: {};'
      if (isCustomPropertySet(rule)) {
        return
      }

      const comparisonContext = selectorContextLookup.getContext(rule, findAtRuleContext(rule))

      rule.selectors.forEach(selector => {
        const trimSelector = selector.trim()
        // Ignore '.selector, { }'
        if (trimSelector === "") {
          return
        }

        // The edge-case of duplicate selectors will act acceptably
        const index = rule.selector.indexOf(trimSelector)
        // Resolve any nested selectors before checking
        resolvedNestedSelector(selector, rule).forEach(resolvedSelector => {
          parseSelector(resolvedSelector, result, rule, s => checkSelector(s, rule, index, comparisonContext))
        })
      })
    })

    function checkSelector(selectorNode, rule, sourceIndex, comparisonContext) {
      const selector = selectorNode.toString()
      const referenceSelectorNode = lastCompoundSelectorWithoutPseudoClasses(selectorNode)
      const selectorSpecificity = specificity.calculate(selector)[0].specificityArray
      const entry = { selector, specificity: selectorSpecificity }

      if (!comparisonContext.has(referenceSelectorNode)) {
        comparisonContext.set(referenceSelectorNode, [entry])
        return
      }

      const priorComparableSelectors = comparisonContext.get(referenceSelectorNode)

      priorComparableSelectors.forEach(priorEntry => {
        if (specificity.compare(selectorSpecificity, priorEntry.specificity) === -1) {
          report({
            ruleName,
            result,
            node: rule,
            message: messages.rejected(selector, priorEntry.selector),
            index: sourceIndex,
          })
        }
      })

      priorComparableSelectors.push(entry)
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-duplicate-selectors"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-duplicate-selectors (actual)](#apidoc.element.stylelint.rules.no-duplicate-selectors)
- description and source-code
```javascript
no-duplicate-selectors = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    // The top level of this map will be rule sources.
    // Each source maps to another map, which maps rule parents to a set of selectors.
    // This ensures that selectors are only checked against selectors
    // from other rules that share the same parent and the same source.
    const selectorContextLookup = nodeContextLookup()

    root.walkRules(rule => {
      if (isKeyframeRule(rule)) {
        return
      }

      const contextSelectorSet = selectorContextLookup.getContext(rule, findAtRuleContext(rule))
      const resolvedSelectors = rule.selectors.reduce((result, selector) => {
        return _.union(result, resolvedNestedSelector(selector, rule))
      }, [])
      const normalizedSelectorList = resolvedSelectors.map(normalizeSelector)
      const selectorLine = rule.source.start.line

      // Complain if the same selector list occurs twice

      // Sort the selectors list so that the order of the constituents
      // doesn't matter
      const sortedSelectorList = normalizedSelectorList.slice().sort().join(",")
      if (contextSelectorSet.has(sortedSelectorList)) {
        // If the selector isn't nested we can use its raw value; otherwise,
        // we have to approximate something for the message -- which is close enough
        const isNestedSelector = resolvedSelectors.join(",") !== rule.selectors.join(",")
        const selectorForMessage = isNestedSelector ? resolvedSelectors.join(", ") : rule.selector
        const previousDuplicatePosition = contextSelectorSet.get(sortedSelectorList)

        return report({
          result,
          ruleName,
          node: rule,
          message: messages.rejected(selectorForMessage, previousDuplicatePosition),
        })
      }

      contextSelectorSet.set(sortedSelectorList, selectorLine)

      // Or complain if one selector list contains the same selector more than one
      rule.selectors.forEach((selector, i) => {
        if (_.includes(normalizedSelectorList.slice(0, i), normalizeSelector(selector))) {
          report({
            result,
            ruleName,
            node: rule,
            message: messages.rejected(selector, selectorLine),
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-empty-source"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-empty-source (actual)](#apidoc.element.stylelint.rules.no-empty-source)
- description and source-code
```javascript
no-empty-source = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    if (!/^\s*$/.test(root.toString())) {
      return
    }

    report({
      message: messages.rejected,
      node: root,
      result,
      ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-eol-whitespace"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-eol-whitespace (on, options)](#apidoc.element.stylelint.rules.no-eol-whitespace)
- description and source-code
```javascript
no-eol-whitespace = function (on, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: on,
    }, {
      optional: true,
      actual: options,
      possible: {
        ignore: ["empty-lines"],
      },
    })
    if (!validOptions) {
      return
    }

    const rootString = root.toString()
    styleSearch({
      source: rootString,
      target: [
        "\n",
        "\r",
      ],
      comments: "check",
    }, match => {
      // If the character before newline is not whitespace, ignore
      if (!whitespacesToReject.has(rootString[match.startIndex - 1])) {
        return
      }

      if (optionsMatches(options, "ignore", "empty-lines")) {
        // If there is only whitespace between the previous newline and
        // this newline, ignore
        const lineBefore = rootString.substring(match.startIndex + 1, rootString.lastIndexOf("\n", match.startIndex - 1))
        if (isOnlyWhitespace(lineBefore)) {
          return
        }
      }

      report({
        message: messages.rejected,
        node: root,
        index: match.startIndex - 1,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-extra-semicolons"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-extra-semicolons (actual)](#apidoc.element.stylelint.rules.no-extra-semicolons)
- description and source-code
```javascript
no-extra-semicolons = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    const rawAfterRoot = root.raws.after

    if (rawAfterRoot && rawAfterRoot.trim().length !== 0) {
      styleSearch({ source: rawAfterRoot, target: ";" }, match => {
        complain(root.toString().length - rawAfterRoot.length + match.startIndex)
      })
    }

    root.walk(node => {
      let rawBeforeNode = node.raws.before

      if (rawBeforeNode && rawBeforeNode.trim().length !== 0) {
        let allowedSemi = 0

        // Forbid semicolon before first custom properties sets
        if (isCustomPropertySet(node) && node.parent.index(node) > 0) {
          allowedSemi = 1
        }

        const next = node.next()

        // Ignore semicolon before comment if next node is custom properties sets or comment
        if (node.type === "comment" && next
          && (isCustomPropertySet(next) && node.parent.index(next) > 0 || next.type === "comment")
        ) {
          allowedSemi = 1
        }

        const prev = node.prev()

        // Adding previous node string to custom properties set if previous node is comment
        if (isCustomPropertySet(node) && node.parent.index(node) > 0 && prev && prev.type === "comment") {
          rawBeforeNode = prev.toString() + rawBeforeNode
          allowedSemi = 0
        }

        styleSearch({ source: rawBeforeNode, target: ";" }, (match, count) => {
          if (count === allowedSemi) {
            return
          }

          complain(getOffsetByNode(node) - rawBeforeNode.length + match.startIndex)
        })
      }

      const rawAfterNode = node.raws.after

      if (rawAfterNode && rawAfterNode.trim().length !== 0) {
        let allowedSemi = 0

        if (!hasEmptyBlock(node) && isCustomPropertySet(node.nodes[node.nodes.length - 1])) {
          allowedSemi = 1
        }

        styleSearch({ source: rawAfterNode, target: ";" }, (match, count) => {
          if (count === allowedSemi) {
            return
          }

          const index = getOffsetByNode(node) + node.toString().length - 1 - rawAfterNode.length + match.startIndex
          complain(index)
        })
      }
    })

    function complain(index) {
      report({
        message: messages.rejected,
        node: root,
        index,
        result,
        ruleName,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-indistinguishable-colors"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-indistinguishable-colors (on, options)](#apidoc.element.stylelint.rules.no-indistinguishable-colors)
- description and source-code
```javascript
no-indistinguishable-colors = function (on, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual: on }, {
      optional: true,
      actual: options,
      possible: {
        ignore: isValidHex,
        threshold: x => _.isNumber(x) && x >= 0 && x <= 100,
        whitelist: x => _.isArray(x) && x.every(isValidHex),
      },
    })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    const colorguardResult = new Result()
    colorguard(options)(root, colorguardResult)
    colorguardResult.warnings().forEach(colorguardWarning => {
      const message = messages.rejected(colorguardWarning.secondColor, colorguardWarning.firstColor)
      report({
        ruleName,
        result,
        message,
        node: colorguardWarning.node,
        index: colorguardWarning.node.toString().indexOf(colorguardWarning.secondColor),
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-invalid-double-slash-comments"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-invalid-double-slash-comments (actual)](#apidoc.element.stylelint.rules.no-invalid-double-slash-comments)
- description and source-code
```javascript
no-invalid-double-slash-comments = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (decl.prop.indexOf("//") === 0) {
        report({
          message: messages.rejected,
          node: decl,
          result,
          ruleName,
        })
      }
    })
    root.walkRules(rule => {
      rule.selectors.forEach(selector => {
        if (selector.indexOf("//") === 0) {
          report({
            message: messages.rejected,
            node: rule,
            result,
            ruleName,
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-missing-end-of-source-newline"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-missing-end-of-source-newline (actual)](#apidoc.element.stylelint.rules.no-missing-end-of-source-newline)
- description and source-code
```javascript
no-missing-end-of-source-newline = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    const sourceCss = root.source.input.css
    if (sourceCss === "" || sourceCss.slice(-1) === "\n") {
      return
    }

    report({
      message: messages.rejected,
      node: root,
      index: sourceCss.length - 1,
      result,
      ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-unknown-animations"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-unknown-animations (actual)](#apidoc.element.stylelint.rules.no-unknown-animations)
- description and source-code
```javascript
no-unknown-animations = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    const declaredAnimations = new Set()
    root.walkAtRules(/(-(moz|webkit)-)?keyframes/i, atRule => {
      declaredAnimations.add(atRule.params)
    })

    root.walkDecls(decl => {
      if (decl.prop.toLowerCase() === "animation" || decl.prop.toLowerCase() === "animation-name") {
        const animationNames = findAnimationName(decl.value)

        if (animationNames.length === 0) {
          return
        }

        animationNames.forEach(animationNameNode => {
          if (keywordSets.animationNameKeywords.has(animationNameNode.value.toLowerCase())) {
            return
          }
          if (declaredAnimations.has(animationNameNode.value)) {
            return
          }

          report({
            result,
            ruleName,
            message: messages.rejected(animationNameNode.value),
            node: decl,
            index: declarationValueIndex(decl) + animationNameNode.sourceIndex,
          })
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.no-unsupported-browser-features"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>no-unsupported-browser-features (on, options)](#apidoc.element.stylelint.rules.no-unsupported-browser-features)
- description and source-code
```javascript
no-unsupported-browser-features = function (on, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual: on }, {
      optional: true,
      actual: options,
      possible: {
        browsers: [_.isString],
        ignore: [_.isString],
      },
    })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    const doiuseOptions = {}

    if (options && options.browsers) {
      doiuseOptions.browsers = options.browsers
    }

    if (options && options.ignore) {
      doiuseOptions.ignore = options.ignore
    }

    const doiuseResult = new Result()
    doiuse(doiuseOptions).postcss(root, doiuseResult)
    doiuseResult.warnings().forEach(doiuseWarning => {
      report({
        ruleName,
        result,
        message: messages.rejected(cleanDoiuseWarningText(doiuseWarning.text)),
        node: doiuseWarning.node,
        line: doiuseWarning.line,
        column: doiuseWarning.column,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.number-leading-zero"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>number-leading-zero (expectation)](#apidoc.element.stylelint.rules.number-leading-zero)
- description and source-code
```javascript
number-leading-zero = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      if (atRule.name.toLowerCase() === "import") {
        return
      }

      check(atRule, atRule.params, atRuleParamIndex)
    })

    root.walkDecls(decl => check(decl, decl.value, declarationValueIndex))

    function check(node, value, getIndex) {
      // Get out quickly if there are no periods
      if (value.indexOf(".") === -1) {
        return
      }

      valueParser(value).walk(valueNode => {
        // Ignore 'url' function
        if (valueNode.type === "function" && valueNode.value.toLowerCase() === "url") {
          return false
        }

        // Ignore strings, comments, etc
        if (valueNode.type !== "word") {
          return
        }

        // Check leading zero
        if (expectation === "always") {
          const match = /(?:\D|^)(\.\d+)/.exec(valueNode.value)

          if (match === null) {
            return
          }

          // The regexp above consists of 2 capturing groups (or capturing parentheses).
          // We need the index of the second group. This makes sanse when we have "-.5" as an input
          // for regex. And we need the index of ".5".
          const capturingGroupIndex = match[0].length - match[1].length
          complain(messages.expected, node, getIndex(node) + valueNode.sourceIndex + match.index + capturingGroupIndex)
        }

        if (expectation === "never") {
          const match = /(?:\D|^)(0+\.\d+)/.exec(valueNode.value)

          if (match === null) {
            return
          }

          const capturingGroupIndex = match[0].length - match[1].length
          complain(messages.rejected, node, getIndex(node) + valueNode.sourceIndex + match.index + capturingGroupIndex)
        }
      })
    }

    function complain(message, node, index) {
      report({
        result,
        ruleName,
        message,
        node,
        index,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.number-max-precision"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>number-max-precision (precision)](#apidoc.element.stylelint.rules.number-max-precision)
- description and source-code
```javascript
number-max-precision = function (precision) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: precision,
      possible: [_.isNumber],
    })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      if (atRule.name.toLowerCase() === "import") {
        return
      }

      check(atRule, atRule.params, atRuleParamIndex)
    })

    root.walkDecls(decl => check(decl, decl.value, declarationValueIndex))

    function check(node, value, getIndex) {
      // Get out quickly if there are no periods
      if (value.indexOf(".") === -1) {
        return
      }

      valueParser(value).walk(valueNode => {
        // Ignore 'url' function
        if (valueNode.type === "function" && valueNode.value.toLowerCase() === "url") {
          return false
        }

        // Ignore strings, comments, etc
        if (valueNode.type !== "word") {
          return
        }

        const match = /\d*\.(\d+)/.exec(valueNode.value)

        if (match === null) {
          return
        }

        if (match[1].length <= precision) {
          return
        }

        report({
          result,
          ruleName,
          node,
          index: getIndex(node) + valueNode.sourceIndex + match.index,
          message: messages.expected(parseFloat(match[0]), precision),
        })
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.number-no-trailing-zeros"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>number-no-trailing-zeros (actual)](#apidoc.element.stylelint.rules.number-no-trailing-zeros)
- description and source-code
```javascript
number-no-trailing-zeros = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkAtRules(atRule => {
      if (atRule.name.toLowerCase() === "import") {
        return
      }

      check(atRule, atRule.params, atRuleParamIndex)
    })

    root.walkDecls(decl => check(decl, decl.value, declarationValueIndex))

    function check(node, value, getIndex) {
      // Get out quickly if there are no periods
      if (value.indexOf(".") === -1) {
        return
      }

      valueParser(value).walk(valueNode => {
        // Ignore 'url' function
        if (valueNode.type === "function" && valueNode.value.toLowerCase() === "url") {
          return false
        }

        // Ignore strings, comments, etc
        if (valueNode.type !== "word") {
          return
        }

        const match = /(\.\d*)0+(?:\D|$)/.exec(valueNode.value)

        if (match === null) {
          return
        }

        report({
          message: messages.rejected,
          node,
          index: getIndex(node) + valueNode.sourceIndex + match.index + match[1].length,
          result,
          ruleName,
        })
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.property-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>property-blacklist (blacklist)](#apidoc.element.stylelint.rules.property-blacklist)
- description and source-code
```javascript
property-blacklist = function (blacklist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop

      if (!isStandardSyntaxProperty(prop)) {
        return
      }
      if (isCustomProperty(prop)) {
        return
      }
      if (!matchesStringOrRegExp(postcss.vendor.unprefixed(prop), blacklist)) {
        return
      }

      report({
        message: messages.rejected(prop),
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.property-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>property-case (expectation)](#apidoc.element.stylelint.rules.property-case)
- description and source-code
```javascript
property-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop

      if (!isStandardSyntaxProperty(prop)) {
        return
      }
      if (isCustomProperty(prop)) {
        return
      }

      const expectedProp = expectation === "lower" ? prop.toLowerCase() : prop.toUpperCase()
      if (prop === expectedProp) {
        return
      }

      report({
        message: messages.expected(prop, expectedProp),
        node: decl,
        ruleName,
        result,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.property-no-unknown"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>property-no-unknown (actual, options)](#apidoc.element.stylelint.rules.property-no-unknown)
- description and source-code
```javascript
property-no-unknown = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignoreProperties: [_.isString],
        checkPrefixed: _.isBoolean,
      },
      optional: true,
    })

    if (!validOptions) {
      return
    }

    const shouldCheckPrefixed = _.get(options, "checkPrefixed")

    root.walkDecls(decl => {
      const prop = decl.prop

      if (!isStandardSyntaxProperty(prop)) {
        return
      }
      if (!isStandardSyntaxDeclaration(decl)) {
        return
      }
      if (isCustomProperty(prop)) {
        return
      }

      if (!shouldCheckPrefixed && postcss.vendor.prefix(prop)) {
        return
      }

      if (optionsMatches(options, "ignoreProperties", prop)) {
        return
      }

      if (properties.indexOf(prop.toLowerCase()) !== -1) {
        return
      }

      report({
        message: messages.rejected(prop),
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.property-no-vendor-prefix"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>property-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.property-no-vendor-prefix)
- description and source-code
```javascript
property-no-vendor-prefix = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop

      // Make sure there's a vendor prefix,
      // but this isn't a custom property

      if (prop[0] !== "-" || prop[1] === "-") {
        return
      }

      if (!isAutoprefixable.property(prop)) {
        return
      }
      report({
        message: messages.rejected(prop),
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.property-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>property-whitelist (whitelist)](#apidoc.element.stylelint.rules.property-whitelist)
- description and source-code
```javascript
property-whitelist = function (whitelist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop

      if (!isStandardSyntaxProperty(prop)) {
        return
      }
      if (isCustomProperty(prop)) {
        return
      }
      if (matchesStringOrRegExp(postcss.vendor.unprefixed(prop), whitelist)) {
        return
      }

      report({
        message: messages.rejected(prop),
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.root-no-standard-properties"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>root-no-standard-properties (actual)](#apidoc.element.stylelint.rules.root-no-standard-properties)
- description and source-code
```javascript
root-no-standard-properties = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed. Instead use the community 'stylelint-suitcss' plugin pack.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    root.walkRules(rule => {
      if (rule.selector.toLowerCase().indexOf(":root") === -1) {
        return
      }
      parseSelector(rule.selector, result, rule, checkSelector)

      function checkSelector(selectorAST) {
        if (ignoreRule(selectorAST)) {
          return
        }

        rule.each(function (node) {
          if (node.type !== "decl") {
            return
          }

          const prop = node.prop

          if (!isStandardSyntaxProperty(prop)) {
            return
          }
          if (isCustomProperty(prop)) {
            return
          }

          report({
            message: messages.rejected(prop),
            node,
            result,
            ruleName,
          })
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.rule-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>rule-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.rule-empty-line-before)
- description and source-code
```javascript
rule-empty-line-before = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-multi-line",
        "never-multi-line",
      ],
    }, {
      actual: options,
      possible: {
        ignore: [
          "after-comment",
          "inside-block",
        ],
        except: [
          "after-rule",
          "after-single-line-comment",
          "first-nested",
          "inside-block-and-after-rule",
        ],
      },
      optional: true,
    })

    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }

      // Ignore the first node
      if (rule === root.first) {
        return
      }

      let expectEmptyLineBefore = expectation.indexOf("always") !== -1 ? true : false

      // Optionally ignore the expectation if a comment precedes this node
      if (
        optionsMatches(options, "ignore", "after-comment")
        && rule.prev()
        && rule.prev().type === "comment"
      ) {
        return
      }

      // Optionally ignore the expectation if inside a block
      if (
        optionsMatches(options, "ignore", "inside-block")
        && rule.parent !== root
      ) {
        return
      }

      // Ignore if the expectation is for multiple and the rule is single-line
      if (
        expectation.indexOf("multi-line") !== -1
        && isSingleLineString(rule.toString())
      ) {
        return
      }

      // Optionally reverse the expectation for the first nested node
      if (
        optionsMatches(options, "except", "first-nested")
        && rule === rule.parent.first
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Optionally reverse the expectation if a rule precedes this node
      if (
        optionsMatches(options, "except", "after-rule")
        && rule.prev()
        && rule.prev().type === "rule"
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Optionally reverse the expectation if a rule precedes this node and is inside a block
      if (
        optionsMatches(options, "except", "inside-block-and-after-rule")
        && rule.prev()
        && rule.prev().type === "rule"
        && rule.parent !== root
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      // Optionally reverse the expectation for single line comments
      if (
        optionsMatches(options, "except", "after-single-line-comment")
        && rule.prev()
        && rule.prev().type === "comment"
        && isSingleLineString(rule.prev().toString())
      ) {
        expectEmptyLineBefore = !expectEmptyLineBefore
      }

      const hasEmptyLineBefore = hasEmptyLine(rule.raws.before)

      // Return if the expectation is met
      if (expectEmptyLineBefore === hasEmptyLineBefore) {
        return
      }

      const message = expectEmptyLineBefore ? messages.expected : messages.rejected

      report({
        message,
        node: rule,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.rule-nested-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>rule-nested-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.rule-nested-empty-line-before)
- description and source-code
```javascript
rule-nested-empty-line-before = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-multi-line",
        "never-multi-line",
      ],
    }, {
      actual: options,
      possible: {
        ignore: ["after-comment"],
        except: [
          "first-nested",
          "after-comment",
          "after-rule",
        ],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed. Instead use 'rule-empty-line-before'.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }

      // Only attend to nested rule sets
      if (rule.parent === root) {
        return
      }

      checkRuleEmptyLineBefore({ rule, expectation, options, result, messages, checkedRuleName: ruleName })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.rule-non-nested-empty-line-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>rule-non-nested-empty-line-before (expectation, options)](#apidoc.element.stylelint.rules.rule-non-nested-empty-line-before)
- description and source-code
```javascript
rule-non-nested-empty-line-before = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-multi-line",
        "never-multi-line",
      ],
    }, {
      actual: options,
      possible: {
        ignore: ["after-comment"],
        except: ["after-single-line-comment"],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed. Instead use 'rule-empty-line-before'.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }

      // Ignore nested rule sets
      if (rule.parent !== root) {
        return
      }

      // Ignore the first node
      if (rule === root.first) {
        return
      }

      checkRuleEmptyLineBefore({ rule, expectation, options, result, messages, checkedRuleName: ruleName })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-attribute-brackets-space-inside"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-brackets-space-inside (expectation)](#apidoc.element.stylelint.rules.selector-attribute-brackets-space-inside)
- description and source-code
```javascript
selector-attribute-brackets-space-inside = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (rule.selector.indexOf("[") === -1) {
        return
      }

      parseSelector(rule.selector, result, rule, selectorTree => {
        selectorTree.walkAttributes(attributeNode => {
          const attributeSelectorString = attributeNode.toString()

          styleSearch({ source: attributeSelectorString, target: "[" }, match => {
            const nextCharIsSpace = attributeSelectorString[match.startIndex + 1] === " "
            const index = attributeNode.sourceIndex + match.startIndex + 1
            if (nextCharIsSpace && expectation === "never") {
              complain(messages.rejectedOpening, index)
            }
            if (!nextCharIsSpace && expectation === "always") {
              complain(messages.expectedOpening, index)
            }
          })

          styleSearch({ source: attributeSelectorString, target: "]" }, match => {
            const prevCharIsSpace = attributeSelectorString[match.startIndex - 1] === " "
            const index = attributeNode.sourceIndex + match.startIndex - 1
            if (prevCharIsSpace && expectation === "never") {
              complain(messages.rejectedClosing, index)
            }
            if (!prevCharIsSpace && expectation === "always") {
              complain(messages.expectedClosing, index)
            }
          })
        })
      })

      function complain(message, index) {
        report({
          message,
          index,
          result,
          ruleName,
          node: rule,
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-attribute-operator-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-blacklist (blacklistInput)](#apidoc.element.stylelint.rules.selector-attribute-operator-blacklist)
- description and source-code
```javascript
selector-attribute-operator-blacklist = function (blacklistInput) {
  const blacklist = [].concat(blacklistInput)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (rule.selector.indexOf("[") === -1 || rule.selector.indexOf("=") === -1) {
        return
      }

      parseSelector(rule.selector, result, rule, selectorTree => {
        selectorTree.walkAttributes(attributeNode => {
          const operator = attributeNode.operator

          if (!operator || operator && blacklist.indexOf(operator) === -1) {
            return
          }

          report({
            message: messages.rejected(operator),
            node: rule,
            index: attributeNode.attribute.length + 1,
            result,
            ruleName,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-attribute-operator-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-space-after (expectation)](#apidoc.element.stylelint.rules.selector-attribute-operator-space-after)
- description and source-code
```javascript
selector-attribute-operator-space-after = function (expectation) {
  return (root, result) => {
    const checker = whitespaceChecker("space", expectation, messages)
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    selectorAttributeOperatorSpaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
      checkBeforeOperator: false,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-attribute-operator-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-space-before (expectation)](#apidoc.element.stylelint.rules.selector-attribute-operator-space-before)
- description and source-code
```javascript
selector-attribute-operator-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    selectorAttributeOperatorSpaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
      checkBeforeOperator: true,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-attribute-operator-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-operator-whitelist (whitelistInput)](#apidoc.element.stylelint.rules.selector-attribute-operator-whitelist)
- description and source-code
```javascript
selector-attribute-operator-whitelist = function (whitelistInput) {
  const whitelist = [].concat(whitelistInput)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (rule.selector.indexOf("[") === -1 || rule.selector.indexOf("=") === -1) {
        return
      }

      parseSelector(rule.selector, result, rule, selectorTree => {
        selectorTree.walkAttributes(attributeNode => {
          const operator = attributeNode.operator

          if (!operator || operator && whitelist.indexOf(operator) !== -1) {
            return
          }

          report({
            message: messages.rejected(operator),
            node: rule,
            index: attributeNode.attribute.length + 1,
            result,
            ruleName,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-attribute-quotes"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-attribute-quotes (expectation)](#apidoc.element.stylelint.rules.selector-attribute-quotes)
- description and source-code
```javascript
selector-attribute-quotes = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (rule.selector.indexOf("[") === -1 || rule.selector.indexOf("=") === -1) {
        return
      }

      parseSelector(rule.selector, result, rule, selectorTree => {
        selectorTree.walkAttributes(attributeNode => {
          if (!attributeNode.operator) {
            return
          }

          const attributeSelectorString = attributeNode.toString()

          if (!attributeNode.quoted && expectation === "always") {
            complain(messages.expected(attributeNode.raws.unquoted), attributeNode.sourceIndex + attributeSelectorString.indexOf
(attributeNode.value))
          }

          if (attributeNode.quoted && expectation === "never") {
            complain(messages.rejected(attributeNode.raws.unquoted), attributeNode.sourceIndex + attributeSelectorString.indexOf
(attributeNode.value))
          }
        })
      })

      function complain(message, index) {
        report({
          message,
          index,
          result,
          ruleName,
          node: rule,
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-class-pattern"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-class-pattern (pattern, options)](#apidoc.element.stylelint.rules.selector-class-pattern)
- description and source-code
```javascript
selector-class-pattern = function (pattern, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: pattern,
      possible: [
        _.isRegExp,
        _.isString,
      ],
    }, {
      actual: options,
      possible: {
        resolveNestedSelectors: _.isBoolean,
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    const shouldResolveNestedSelectors = _.get(options, "resolveNestedSelectors")
    const normalizedPattern = _.isString(pattern) ? new RegExp(pattern) : pattern

    root.walkRules(rule => {
      const selector = rule.selector,
        selectors = rule.selectors

      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      if (selectors.some(s => isKeyframeSelector(s))) {
        return
      }

      // Only bother resolving selectors that have an interpolating &
      if (shouldResolveNestedSelectors && hasInterpolatingAmpersand(selector)) {
        resolveNestedSelector(selector, rule).forEach(selector => {
          if (!isStandardSyntaxSelector(selector)) {
            return
          }

          parseSelector(selector, result, rule, s => checkSelector(s, rule))
        })
      } else {
        parseSelector(selector, result, rule, s => checkSelector(s, rule))
      }
    })

    function checkSelector(fullSelector, rule) {
      fullSelector.walkClasses(classNode => {
        const value = classNode.value,
          sourceIndex = classNode.sourceIndex

        if (normalizedPattern.test(value)) {
          return
        }
        report({
          result,
          ruleName,
          message: messages.expected(value),
          node: rule,
          index: sourceIndex,
        })
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-combinator-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-combinator-space-after (expectation)](#apidoc.element.stylelint.rules.selector-combinator-space-after)
- description and source-code
```javascript
selector-combinator-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    selectorCombinatorSpaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-combinator-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-combinator-space-before (expectation)](#apidoc.element.stylelint.rules.selector-combinator-space-before)
- description and source-code
```javascript
selector-combinator-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    selectorCombinatorSpaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-descendant-combinator-no-non-space"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-descendant-combinator-no-non-space (actual)](#apidoc.element.stylelint.rules.selector-descendant-combinator-no-non-space)
- description and source-code
```javascript
selector-descendant-combinator-no-non-space = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }

      const selector = rule.selector

      parseSelector(selector, result, rule, fullSelector => {
        fullSelector.walkCombinators(combinatorNode => {
          const value = combinatorNode.value

          if (punctuationSets.nonSpaceCombinators.has(value)) {
            return
          }
          if (value === " ") {
            return
          }

          report({
            result,
            ruleName,
            message: messages.rejected(value),
            node: rule,
            index: combinatorNode.sourceIndex,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-id-pattern"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-id-pattern (pattern)](#apidoc.element.stylelint.rules.selector-id-pattern)
- description and source-code
```javascript
selector-id-pattern = function (pattern) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: pattern,
      possible: [
        _.isRegExp,
        _.isString,
      ],
    })
    if (!validOptions) {
      return
    }

    const normalizedPattern = _.isString(pattern) ? new RegExp(pattern) : pattern

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }

      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }

      parseSelector(selector, result, rule, fullSelector => {
        fullSelector.walk(selectorNode => {
          if (selectorNode.type !== "id") {
            return
          }
          const value = selectorNode.value,
            sourceIndex = selectorNode.sourceIndex

          if (normalizedPattern.test(value)) {
            return
          }

          report({
            result,
            ruleName,
            message: messages.expected(value),
            node: rule,
            index: sourceIndex,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-list-comma-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-newline-after)
- description and source-code
```javascript
selector-list-comma-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      // Get raw selector so we can allow end-of-line comments, e.g.
      // a,<span class="apidocCodeCommentSpan"> /* comment */
</span>      // b {}
      const selector = rule.raws.selector ? rule.raws.selector.raw : rule.selector
      styleSearch({
        source: selector,
        target: ",",
        functionArguments: "skip",
      }, match => {
        const nextThreeChars = selector.substr(match.endIndex, 3)

        // If there's a // comment, that means there has to be a newline
        // ending the comment so we're fine
        if (nextThreeChars === " //") {
          return
        }

        // If there is a space and then a comment begins, look for the newline
        // after that comment
        const indextoCheckAfter = nextThreeChars === " /*" ? selector.indexOf("*/", match.endIndex) + 1 : match.startIndex
        checker.afterOneOnly({
          source: selector,
          index: indextoCheckAfter,
          err: m => report({
            message: m,
            node: rule,
            index: match.startIndex,
            result,
            ruleName,
          }),
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-list-comma-newline-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-newline-before)
- description and source-code
```javascript
selector-list-comma-newline-before = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    selectorListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.beforeAllowingIndentation,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-list-comma-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-space-after (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-space-after)
- description and source-code
```javascript
selector-list-comma-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    selectorListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-list-comma-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-list-comma-space-before (expectation)](#apidoc.element.stylelint.rules.selector-list-comma-space-before)
- description and source-code
```javascript
selector-list-comma-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    selectorListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-max-compound-selectors"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-max-compound-selectors (max)](#apidoc.element.stylelint.rules.selector-max-compound-selectors)
- description and source-code
```javascript
selector-max-compound-selectors = function (max) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: max,
      possible: [
        function (max) {
          return typeof max === "number" && max > 0
        },
      ],
    })
    if (!validOptions) {
      return
    }

    // Finds actual selectors in selectorNode object and checks them
    function checkSelector(selectorNode, rule) {
      let compoundCount = 1

      selectorNode.each(childNode => {
        // Only traverse inside actual selectors and :not()
        if (childNode.type === "selector" || childNode.value === ":not") {
          checkSelector(childNode, rule)
        }

        // Compound selectors are separated by combinators, so increase count when meeting one
        if (childNode.type === "combinator") {
          compoundCount++
        }
      })

      if (selectorNode.type !== "root" && selectorNode.type !== "pseudo" && compoundCount > max) {
        report({
          ruleName,
          result,
          node: rule,
          message: messages.expected(selectorNode, max),
          word: selectorNode,
        })
      }
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (!isStandardSyntaxSelector(rule.selector)) {
        return
      }

      // Nested selectors are processed in steps, as nesting levels are resolved.
      // Here we skip processing the intermediate parts of selectors (to process only fully resolved selectors)
      if (rule.nodes.some(node => node.type === "rule" || node.type === "atrule")) {
        return
      }

      // Using 'rule.selectors' gets us each selector if there is a comma separated set
      rule.selectors.forEach(selector => {
        resolvedNestedSelector(selector, rule).forEach(resolvedSelector => {
          // Process each resolved selector with 'checkSelector' via postcss-selector-parser
          selectorParser(s => checkSelector(s, rule)).process(resolvedSelector)
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-max-empty-lines"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-max-empty-lines (max)](#apidoc.element.stylelint.rules.selector-max-empty-lines)
- description and source-code
```javascript
selector-max-empty-lines = function (max) {
  const maxAdjacentNewlines = max + 1

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: max,
      possible: _.isNumber,
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      const selector = rule.raws.selector ? rule.raws.selector.raw : rule.selector
      const repeatLFNewLines = _.repeat("\n", maxAdjacentNewlines)
      const repeatCRLFNewLines = _.repeat("\r\n", maxAdjacentNewlines)

      styleSearch({ source: selector, target: "\n" }, match => {
        if (selector.substr(match.startIndex + 1, maxAdjacentNewlines) === repeatLFNewLines || selector.substr(match.startIndex +
1, maxAdjacentNewlines * 2) === repeatCRLFNewLines) {
          // Put index at '\r' if it's CRLF, otherwise leave it at '\n'
          let index = match.startIndex
          if (selector[index - 1] === "\r") {
            index -= 1
          }

          report({
            message: messages.expected(max),
            node: rule,
            index,
            result,
            ruleName,
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-max-specificity"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-max-specificity (max)](#apidoc.element.stylelint.rules.selector-max-specificity)
- description and source-code
```javascript
selector-max-specificity = function (max) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: max,
      possible: [
        function (max) {
        // Check that the max specificity is in the form "a,b,c"
          const pattern = new RegExp("^\\d+,\\d+,\\d+$")
          return pattern.test(max)
        },
      ],
    })
    if (!validOptions) {
      return
    }

    const maxSpecificityArray = ("0," + max).split(",").map(parseFloat)
    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (!isStandardSyntaxSelector(rule.selector)) {
        return
      }
      // Using rule.selectors gets us each selector in the eventuality we have a comma separated set
      rule.selectors.forEach(selector => {
        resolvedNestedSelector(selector, rule).forEach(resolvedSelector => {
          // Return early if selector contains a not pseudo-class
          if (selector.indexOf(":not(") !== -1) {
            return
          }
          // Return early if selector contains a matches
          if (selector.indexOf(":matches(") !== -1) {
            return
          }
          // Check if the selector specificity exceeds the allowed maximum
          try {
            if (specificity.compare(resolvedSelector, maxSpecificityArray) === 1) {
              report({
                ruleName,
                result,
                node: rule,
                message: messages.expected(resolvedSelector, max),
                word: selector,
              })
            }
          } catch (e) {
            result.warn("Cannot parse selector", { node: rule })
          }
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-nested-pattern"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-nested-pattern (pattern)](#apidoc.element.stylelint.rules.selector-nested-pattern)
- description and source-code
```javascript
selector-nested-pattern = function (pattern) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: pattern,
      possible: [
        _.isRegExp,
        _.isString,
      ],
    })
    if (!validOptions) {
      return
    }

    const normalizedPattern = _.isString(pattern) ? new RegExp(pattern) : pattern

    root.walkRules(rule => {
      if (rule.parent.type !== "rule") {
        return
      }
      if (!isStandardSyntaxRule(rule)) {
        return
      }

      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }

      if (normalizedPattern.test(selector)) {
        return
      }

      report({
        result,
        ruleName,
        message: messages.expected(selector),
        node: rule,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-attribute"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-attribute (actual)](#apidoc.element.stylelint.rules.selector-no-attribute)
- description and source-code
```javascript
selector-no-attribute = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      parseSelector(selector, result, rule, selectorAST => {
        selectorAST.walkAttributes(attribute => {
          report({
            message: messages.rejected,
            node: rule,
            index: attribute.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-combinator"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-combinator (actual)](#apidoc.element.stylelint.rules.selector-no-combinator)
- description and source-code
```javascript
selector-no-combinator = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      parseSelector(selector, result, rule, selectorAST => {
        selectorAST.walkCombinators(combinator => {
          report({
            message: messages.rejected,
            node: rule,
            index: combinator.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-empty"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-empty (actual)](#apidoc.element.stylelint.rules.selector-no-empty)
- description and source-code
```javascript
selector-no-empty = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    result.warn((
      "'selector-no-empty' has been deprecated and in 8.0 will be removed."
    ), {
      stylelintType: "deprecation",
      stylelintReference: "https://stylelint.io/user-guide/rules/selector-no-empty/",
    })

    root.walkRules(rule => {
      let index = 0

      rule.selector.split(",").forEach(item => {
        index += item.length + 1

        if (item.trim() !== "") {
          return
        }

        report({
          message: messages.rejected,
          node: rule,
          index: index - 1,
          ruleName,
          result,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-id"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-id (actual)](#apidoc.element.stylelint.rules.selector-no-id)
- description and source-code
```javascript
selector-no-id = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (isKeyframeRule(rule)) {
        return
      }
      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      parseSelector(selector, result, rule, selectorAST => {
        selectorAST.walkIds(idNode => {
          if (idNode.parent.parent.type === "pseudo") {
            return
          }

          report({
            message: messages.rejected,
            node: rule,
            index: idNode.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-qualifying-type"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-qualifying-type (enabled, options)](#apidoc.element.stylelint.rules.selector-no-qualifying-type)
- description and source-code
```javascript
selector-no-qualifying-type = function (enabled, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: enabled,
      possible: [
        true,
        false,
      ],
    }, {
      actual: options,
      possible: {
        ignore: [
          "attribute",
          "class",
          "id",
        ],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (isKeyframeRule(rule)) {
        return
      }
      // Increasing performance
      if (!isStandardSyntaxSelector(rule.selector)) {
        return
      }
      if (!isSelectorCharacters(rule.selector)) {
        return
      }

      function checkSelector(selectorAST) {
        selectorAST.walkTags(selector => {
          const selectorParent = selector.parent

          if (selectorParent.nodes.length === 1) {
            return
          }

          const selectorNodes = getRightNodes(selector)
          const index = selector.sourceIndex

          selectorNodes.forEach(selectorNode => {
            if (selectorNode.type === "id" && !optionsMatches(options, "ignore", "id")) {
              complain(index)
            }

            if (selectorNode.type === "class" && !optionsMatches(options, "ignore", "class")) {
              complain(index)
            }

            if (selectorNode.type === "attribute" && !optionsMatches(options, "ignore", "attribute")) {
              complain(index)
            }
          })
        })
      }

      resolvedNestedSelector(rule.selector, rule).forEach(resolvedSelector => {
        if (!isStandardSyntaxSelector(resolvedSelector)) {
          return
        }

        parseSelector(resolvedSelector, result, rule, checkSelector)
      })

      function complain(index) {
        report({
          ruleName,
          result,
          node: rule,
          message: messages.rejected,
          index,
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-type"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-type (on, options)](#apidoc.element.stylelint.rules.selector-no-type)
- description and source-code
```javascript
selector-no-type = function (on, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual: on }, {
      actual: options,
      possible: {
        ignore: [
          "descendant",
          "compounded",
        ],
        ignoreTypes: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    const ignoreDescendant = optionsMatches(options, "ignore", "descendant")
    const ignoreCompounded = optionsMatches(options, "ignore", "compounded")

    root.walkRules(rule => {
      const selector = rule.selector,
        selectors = rule.selectors

      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      if (selectors.some(s => isKeyframeSelector(s))) {
        return
      }

      if (ignoreDescendant) {
        // Resolve each selector within the list before checking
        selectors.forEach(selector => {
          resolveNestedSelector(selector, rule).forEach(selector => {
            checkSelector(selector, rule)
          })
        })
      } else {
        checkSelector(selector, rule)
      }
    })

    function checkSelector(selector, rule) {
      parseSelector(selector, result, rule, selectorAST => {
        selectorAST.walkTags(tag => {
          if (!isStandardSyntaxTypeSelector(tag)) {
            return
          }

          if (optionsMatches(options, "ignoreTypes", tag.value)) {
            return
          }

          if (ignoreDescendant && hasCombinatorBefore(tag)) {
            return
          }

          if (ignoreCompounded && isCompounded(tag)) {
            return
          }

          report({
            message: messages.rejected,
            node: rule,
            index: tag.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-universal"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-universal (actual)](#apidoc.element.stylelint.rules.selector-no-universal)
- description and source-code
```javascript
selector-no-universal = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      parseSelector(selector, result, rule, selectorAST => {
        selectorAST.walkUniversals(universal => {
          report({
            message: messages.rejected,
            node: rule,
            index: universal.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-no-vendor-prefix"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.selector-no-vendor-prefix)
- description and source-code
```javascript
selector-no-vendor-prefix = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          if (isAutoprefixable.selector(pseudoNode.value)) {
            report({
              result,
              ruleName,
              message: messages.rejected(pseudoNode.value),
              node: rule,
              index: (rule.raws.before || "").length + pseudoNode.sourceIndex,
            })
          }
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-class-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-blacklist (blacklist)](#apidoc.element.stylelint.rules.selector-pseudo-class-blacklist)
- description and source-code
```javascript
selector-pseudo-class-blacklist = function (blacklist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      if (selector.indexOf(":") === -1) {
        return
      }

      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          const value = pseudoNode.value

          // Ignore pseudo-elements

          if (value.slice(0, 2) === "::") {
            return
          }

          const name = value.slice(1)

          if (!matchesStringOrRegExp(postcss.vendor.unprefixed(name).toLowerCase(), blacklist)) {
            return
          }

          report({
            index: pseudoNode.sourceIndex,
            message: messages.rejected(name),
            node: rule,
            result,
            ruleName,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-class-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-case (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-class-case)
- description and source-code
```javascript
selector-pseudo-class-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector
      const startIndexPseudo = selector.indexOf(":")

      if (startIndexPseudo === -1) {
        return
      }

      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          const pseudo = pseudoNode.value

          if (!isStandardSyntaxSelector(pseudo)) {
            return
          }

          if (pseudo.indexOf("::") !== -1 || keywordSets.levelOneAndTwoPseudoElements.has(pseudo.toLowerCase().slice(1))) {
            return
          }

          const expectedPseudo = expectation === "lower" ? pseudo.toLowerCase() : pseudo.toUpperCase()

          if (pseudo === expectedPseudo) {
            return
          }

          report({
            message: messages.expected(pseudo, expectedPseudo),
            node: rule,
            index: pseudoNode.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-class-no-unknown"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-no-unknown (actual, options)](#apidoc.element.stylelint.rules.selector-pseudo-class-no-unknown)
- description and source-code
```javascript
selector-pseudo-class-no-unknown = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignorePseudoClasses: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector

      // Return early before parse if no pseudos for performance

      if (selector.indexOf(":") === -1) {
        return
      }

      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          const value = pseudoNode.value

          if (!isStandardSyntaxSelector(value)) {
            return
          }

          if (isCustomSelector(value)) {
            return
          }

          // Ignore pseudo-elements
          if (value.slice(0, 2) === "::") {
            return
          }

          if (optionsMatches(options, "ignorePseudoClasses", pseudoNode.value.slice(1))) {
            return
          }

          const name = value.slice(1)

          if (postcss.vendor.prefix(name)
            || keywordSets.pseudoClasses.has(name.toLowerCase())
            || keywordSets.pseudoElements.has(name.toLowerCase())
          ) {
            return
          }

          if (pseudoNode.prev()) {
            const prevPseudoNodeValue = postcss.vendor.unprefixed(pseudoNode.prev().value.toLowerCase().slice(2))

            if (keywordSets.webkitProprietaryPseudoElements.has(prevPseudoNodeValue)
              && keywordSets.webkitProprietaryPseudoClasses.has(name.toLowerCase())
            ) {
              return
            }
          }

          report({
            message: messages.rejected(value),
            node: rule,
            index: pseudoNode.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-class-parentheses-space-inside"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-parentheses-space-inside (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-class-parentheses-space-inside)
- description and source-code
```javascript
selector-pseudo-class-parentheses-space-inside = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (rule.selector.indexOf("(") === -1) {
        return
      }

      parseSelector(rule.selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          if (_.get(pseudoNode, "parent.parent.type") === "pseudo") {
            return
          }

          const pseudoSelectorString = pseudoNode.toString()

          styleSearch({ source: pseudoSelectorString, target: "(" }, match => {
            const nextCharIsSpace = pseudoSelectorString[match.startIndex + 1] === " "
            const index = pseudoNode.sourceIndex + match.startIndex + 1
            if (nextCharIsSpace && expectation === "never") {
              complain(messages.rejectedOpening, index)
            }
            if (!nextCharIsSpace && expectation === "always") {
              complain(messages.expectedOpening, index)
            }
          })

          styleSearch({ source: pseudoSelectorString, target: ")" }, match => {
            const prevCharIsSpace = pseudoSelectorString[match.startIndex - 1] === " "
            const index = pseudoNode.sourceIndex + match.startIndex - 1
            if (prevCharIsSpace && expectation === "never") {
              complain(messages.rejectedClosing, index)
            }
            if (!prevCharIsSpace && expectation === "always") {
              complain(messages.expectedClosing, index)
            }
          })
        })
      })

      function complain(message, index) {
        report({
          message,
          index,
          result,
          ruleName,
          node: rule,
        })
      }
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-class-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-class-whitelist (whitelist)](#apidoc.element.stylelint.rules.selector-pseudo-class-whitelist)
- description and source-code
```javascript
selector-pseudo-class-whitelist = function (whitelist) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      const selector = rule.selector

      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      if (selector.indexOf(":") === -1) {
        return
      }

      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          const value = pseudoNode.value

          // Ignore pseudo-elements

          if (value.slice(0, 2) === "::") {
            return
          }

          const name = value.slice(1)

          if (matchesStringOrRegExp(postcss.vendor.unprefixed(name).toLowerCase(), whitelist)) {
            return
          }

          report({
            index: pseudoNode.sourceIndex,
            message: messages.rejected(name),
            node: rule,
            result,
            ruleName,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-element-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-element-case (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-element-case)
- description and source-code
```javascript
selector-pseudo-element-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector
      const startIndexPseudoElement = selector.indexOf(":")

      if (startIndexPseudoElement === -1) {
        return
      }

      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          const pseudoElement = pseudoNode.value

          if (!isStandardSyntaxSelector(pseudoElement)) {
            return
          }

          if (pseudoElement.indexOf("::") === -1 && !keywordSets.levelOneAndTwoPseudoElements.has(pseudoElement.toLowerCase().slice
(1))) {
            return
          }

          const expectedPseudoElement = expectation === "lower" ? pseudoElement.toLowerCase() : pseudoElement.toUpperCase()

          if (pseudoElement === expectedPseudoElement) {
            return
          }

          report({
            message: messages.expected(pseudoElement, expectedPseudoElement),
            node: rule,
            index: pseudoNode.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-element-colon-notation"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-element-colon-notation (expectation)](#apidoc.element.stylelint.rules.selector-pseudo-element-colon-notation)
- description and source-code
```javascript
selector-pseudo-element-colon-notation = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "single",
        "double",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector

      // get out early if no pseudo elements or classes
      if (selector.indexOf(":") === -1) {
        return
      }

      // match only level 1 and 2 pseudo elements
      const pseudoElementsWithColons = _.toArray(keywordSets.levelOneAndTwoPseudoElements).map(x => ':${x}')
      styleSearch({ source: selector.toLowerCase(), target: pseudoElementsWithColons }, match => {
        const prevCharIsColon = selector[match.startIndex - 1] === ":"

        if (expectation === "single" && !prevCharIsColon) {
          return
        }
        if (expectation === "double" && prevCharIsColon) {
          return
        }

        report({
          message: messages.expected(expectation),
          node: rule,
          index: match.startIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-pseudo-element-no-unknown"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-pseudo-element-no-unknown (actual, options)](#apidoc.element.stylelint.rules.selector-pseudo-element-no-unknown)
- description and source-code
```javascript
selector-pseudo-element-no-unknown = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignorePseudoElements: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      if (!isStandardSyntaxRule(rule)) {
        return
      }
      const selector = rule.selector

      // Return early before parse if no pseudos for performance

      if (selector.indexOf(":") === -1) {
        return
      }

      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkPseudos(pseudoNode => {
          const value = pseudoNode.value

          if (!isStandardSyntaxSelector(value)) {
            return
          }

          // Ignore pseudo-classes
          if (value.slice(0, 2) !== "::") {
            return
          }

          if (optionsMatches(options, "ignorePseudoElements", pseudoNode.value.slice(2))) {
            return
          }

          const name = value.slice(2)

          if (postcss.vendor.prefix(name) || keywordSets.pseudoElements.has(name.toLowerCase())) {
            return
          }

          report({
            message: messages.rejected(value),
            node: rule,
            index: pseudoNode.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-root-no-composition"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-root-no-composition (actual)](#apidoc.element.stylelint.rules.selector-root-no-composition)
- description and source-code
```javascript
selector-root-no-composition = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed. Instead use the community 'stylelint-suitcss' plugin pack.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    root.walkRules(rule => {
      if (rule.selector.toLowerCase().indexOf(":root") === -1 || rule.selector.toLowerCase().trim() === ":root") {
        return
      }

      report({
        message: messages.rejected,
        node: rule,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-type-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-type-case (expectation)](#apidoc.element.stylelint.rules.selector-type-case)
- description and source-code
```javascript
selector-type-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      const selector = rule.selector,
        selectors = rule.selectors

      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      if (selectors.some(s => isKeyframeSelector(s))) {
        return
      }

      parseSelector(selector, result, rule, selectorAST => {
        selectorAST.walkTags(tag => {
          if (!isStandardSyntaxTypeSelector(tag)) {
            return
          }

          const sourceIndex = tag.sourceIndex,
            value = tag.value

          const expectedValue = expectation === "lower" ? value.toLowerCase() : value.toUpperCase()

          if (value === expectedValue) {
            return
          }

          report({
            message: messages.expected(value, expectedValue),
            node: rule,
            index: sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.selector-type-no-unknown"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>selector-type-no-unknown (actual, options)](#apidoc.element.stylelint.rules.selector-type-no-unknown)
- description and source-code
```javascript
selector-type-no-unknown = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignore: [
          "default-namespace",
        ],
        ignoreNamespaces: [_.isString],
        ignoreTypes: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkRules(rule => {
      const selector = rule.selector,
        selectors = rule.selectors

      if (!isStandardSyntaxRule(rule)) {
        return
      }
      if (!isStandardSyntaxSelector(selector)) {
        return
      }
      if (selectors.some(s => isKeyframeSelector(s))) {
        return
      }

      parseSelector(selector, result, rule, selectorTree => {
        selectorTree.walkTags(tagNode => {
          if (!isStandardSyntaxTypeSelector(tagNode)) {
            return
          }

          if (
            optionsMatches(options, "ignore", "default-namespace")
            && !tagNode.hasOwnProperty("namespace")
          ) {
            return
          }

          if (optionsMatches(options, "ignoreNamespaces", tagNode.namespace)) {
            return
          }

          if (optionsMatches(options, "ignoreTypes", tagNode.value)) {
            return
          }

          const tagName = tagNode.value
          const tagNameLowerCase = tagName.toLowerCase()

          if (htmlTags.indexOf(tagNameLowerCase) !== -1 || svgTags.indexOf(tagNameLowerCase) !== -1 || nonStandardHtmlTags.has(tagNameLowerCase
)) {
            return
          }

          report({
            message: messages.rejected(tagName),
            node: rule,
            index: tagNode.sourceIndex,
            ruleName,
            result,
          })
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.shorthand-property-no-redundant-values"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>shorthand-property-no-redundant-values (actual)](#apidoc.element.stylelint.rules.shorthand-property-no-redundant-values)
- description and source-code
```javascript
shorthand-property-no-redundant-values = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (!isStandardSyntaxDeclaration(decl) || !isStandardSyntaxProperty(decl.prop)) {
        return
      }

      const prop = decl.prop,
        value = decl.value

      const normalizedProp = postcss.vendor.unprefixed(prop.toLowerCase())

      // Ignore not shorthandable properties, and math operations
      if (isIgnoredCharacters(value) || !shorthandableProperties.has(normalizedProp) || ignoredShorthandProperties.has(normalizedProp
)) {
        return
      }

      const valuesToShorthand = []

      valueParser(value).walk(valueNode => {
        if (valueNode.type !== "word") {
          return
        }

        valuesToShorthand.push(valueParser.stringify(valueNode))
      })

      if (valuesToShorthand.length <= 1 || valuesToShorthand.length > 4) {
        return
      }

      const shortestForm = canCondense.apply(undefined, valuesToShorthand)
      const shortestFormString = shortestForm.filter(value => {
        return value
      }).join(" ")
      const valuesFormString = valuesToShorthand.join(" ")

      if (shortestFormString.toLowerCase() === valuesFormString.toLowerCase()) {
        return
      }

      report({
        message: messages.rejected(value, shortestFormString),
        node: decl,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.string-no-newline"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>string-no-newline (actual)](#apidoc.element.stylelint.rules.string-no-newline)
- description and source-code
```javascript
string-no-newline = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    const cssString = root.toString()
    styleSearch({
      source: cssString,
      target: "\n",
      strings: "only",
    }, match => {
      const charBefore = cssString[match.startIndex - 1]
      let index = match.startIndex
      if (charBefore === "\\") {
        return
      }
      if (charBefore === "\r") index -= 1
      report({
        message: messages.rejected,
        node: root,
        index,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.string-quotes"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>string-quotes (expectation)](#apidoc.element.stylelint.rules.string-quotes)
- description and source-code
```javascript
string-quotes = function (expectation) {
  const erroneousQuote = expectation === "single" ? "\"" : "'"

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "single",
        "double",
      ],
    })
    if (!validOptions) {
      return
    }

    const cssString = root.toString()
    styleSearch({ source: cssString, target: erroneousQuote }, match => {
      report({
        message: messages.expected(expectation),
        node: root,
        index: match.startIndex,
        result,
        ruleName,
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.stylelint-disable-reason"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>stylelint-disable-reason (expectation)](#apidoc.element.stylelint.rules.stylelint-disable-reason)
- description and source-code
```javascript
stylelint-disable-reason = function (expectation) {
  return function (root, result) {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always-before",
        "always-after",
      ],
    })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    root.walkComments(function (comment) {
      if (comment.text.indexOf(stylelintDisableCommand) !== 0) {
        return
      }

      if (expectation === "always-before") {
        const prev = comment.prev()
        const prevIsCommentAndValid = prev && prev.type === "comment" && !isDisableCommand(prev.text)

        let prevDisableLineIsCommentAndValid = false

        if (comment.text.indexOf(stylelintDisableLineCommand) === 0 && !prevIsCommentAndValid && prev) {
          const friendlyPrev = prev.prev()

          prevDisableLineIsCommentAndValid = friendlyPrev && friendlyPrev.type === "comment" && !isDisableCommand(friendlyPrev.text
)
        }

        if (!prevIsCommentAndValid && !prevDisableLineIsCommentAndValid) {
          const disabledRanges = result.stylelint.disabledRanges
          result.stylelint.disabledRanges = false

          report({
            message: messages.expectedBefore,
            node: comment,
            result,
            ruleName,
          })
          result.stylelint.disabledRanges = disabledRanges
        }
      } else if (expectation === "always-after") {
        const next = comment.next()
        const nextIsCommentAndValid = next && next.type === "comment" && !isDisableCommand(next.text)

        if (!nextIsCommentAndValid) {
          const disabledRanges = result.stylelint.disabledRanges
          result.stylelint.disabledRanges = false

          report({
            message: messages.expectedAfter,
            node: comment,
            result,
            ruleName,
          })
          result.stylelint.disabledRanges = disabledRanges
        }
      }
    })

    function isDisableCommand(text) {
      return text.indexOf(stylelintDisableCommand) === 0
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.time-min-milliseconds"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>time-min-milliseconds (minimum)](#apidoc.element.stylelint.rules.time-min-milliseconds)
- description and source-code
```javascript
time-min-milliseconds = function (minimum) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: minimum,
      possible: _.isNumber,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const propertyName = postcss.vendor.unprefixed(decl.prop.toLowerCase())

      if (
        keywordSets.longhandTimeProperties.has(propertyName)
        && !isAcceptableTime(decl.value)
      ) {
        complain(decl)
      }

      if (keywordSets.shorthandTimeProperties.has(propertyName)) {
        const valueList = postcss.list.space(decl.value)

        for (const value of valueList) {
          if (!isAcceptableTime(value)) {
            complain(decl, decl.value.indexOf(value))
          }
        }
      }
    })

    function isAcceptableTime(time) {
      const parsedTime = valueParser.unit(time)

      if (!parsedTime) return true

      if (parsedTime.number <= 0) {
        return true
      }

      if (parsedTime.unit.toLowerCase() === "ms" && parsedTime.number < minimum) {
        return false
      }

      if (parsedTime.unit.toLowerCase() === "s" && parsedTime.number * 1000 < minimum) {
        return false
      }

      return true
    }

    function complain(decl, offset) {
      offset = offset || 0

      report({
        result,
        ruleName,
        message: messages.expected(minimum),
        index: declarationValueIndex(decl) + offset,
        node: decl,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.time-no-imperceptible"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>time-no-imperceptible (actual)](#apidoc.element.stylelint.rules.time-no-imperceptible)
- description and source-code
```javascript
time-no-imperceptible = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    result.warn((
      ''${ruleName}' has been deprecated and in 8.0 will be removed. Instead use 'time-min-milliseconds' with '100' as its primary
 option.'
    ), {
      stylelintType: "deprecation",
      stylelintReference: 'https://stylelint.io/user-guide/rules/${ruleName}/',
    })

    root.walkDecls(decl => {
      if (keywordSets.longhandTimeProperties.has(postcss.vendor.unprefixed(decl.prop.toLowerCase()))) {
        if (isImperceptibleTime(decl.value)) {
          complain(messages.rejected(decl.value), decl)
        }
      }

      if (keywordSets.shorthandTimeProperties.has(postcss.vendor.unprefixed(decl.prop.toLowerCase()))) {
        const valueList = postcss.list.space(decl.value)
        for (const value of valueList) {
          if (isImperceptibleTime(value)) {
            complain(messages.rejected(value), decl, decl.value.indexOf(value))
          }
        }
      }
    })

    function isImperceptibleTime(time) {
      const parsedTime = valueParser.unit(time)
      if (!parsedTime) return false
      const absoluteTime = Math.abs(parsedTime.number)
      if (parsedTime.unit.toLowerCase() === "ms" && absoluteTime <= MINIMUM_MILLISECONDS) {
        return true
      }
      if (parsedTime.unit.toLowerCase() === "s" && absoluteTime * 1000 <= MINIMUM_MILLISECONDS) {
        return true
      }
      return false
    }

    function complain(message, decl) {
      const offset = arguments.length > 2 && arguments[2] !== undefined ? arguments[2] : 0

      report({
        result,
        ruleName,
        message,
        index: declarationValueIndex(decl) + offset,
        node: decl,
      })
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.unit-blacklist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-blacklist (blacklistInput, options)](#apidoc.element.stylelint.rules.unit-blacklist)
- description and source-code
```javascript
unit-blacklist = function (blacklistInput, options) {
  const blacklist = [].concat(blacklistInput)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: blacklist,
      possible: [_.isString],
    }, {
      optional: true,
      actual: options,
      possible: {
        ignoreProperties: validateObjectWithStringArrayProps,
      },
    })
    if (!validOptions) {
      return
    }

    function check(node, value, getIndex) {
      valueParser(value).walk(function (valueNode) {
        // Ignore wrong units within 'url' function
        if (valueNode.type === "function" && valueNode.value.toLowerCase() === "url") {
          return false
        }

        const unit = getUnitFromValueNode(valueNode)

        if (!unit || unit && blacklist.indexOf(unit.toLowerCase()) === -1) {
          return
        }

        if (options && optionsMatches(options.ignoreProperties, unit.toLowerCase(), node.prop)) {
          return
        }

        report({
          index: getIndex(node) + valueNode.sourceIndex,
          message: messages.rejected(unit),
          node,
          result,
          ruleName,
        })
      })
    }

    root.walkAtRules(/^media$/i, atRule => check(atRule, atRule.params, atRuleParamIndex))
    root.walkDecls(decl => check(decl, decl.value, declarationValueIndex))
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.unit-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-case (expectation)](#apidoc.element.stylelint.rules.unit-case)
- description and source-code
```javascript
unit-case = function (expectation) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    })
    if (!validOptions) {
      return
    }

    function check(node, value, getIndex) {
      valueParser(value).walk(valueNode => {
        // Ignore wrong units within 'url' function
        if (valueNode.type === "function" && valueNode.value.toLowerCase() === "url") {
          return false
        }

        const unit = getUnitFromValueNode(valueNode)

        if (!unit) {
          return
        }

        const expectedUnit = expectation === "lower" ? unit.toLowerCase() : unit.toUpperCase()

        if (unit === expectedUnit) {
          return
        }

        report({
          index: getIndex(node) + valueNode.sourceIndex,
          message: messages.expected(unit, expectedUnit),
          node,
          result,
          ruleName,
        })
      })
    }

    root.walkAtRules(/^media$/i, atRule => check(atRule, atRule.params, atRuleParamIndex))
    root.walkDecls(decl => check(decl, decl.value, declarationValueIndex))
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.unit-no-unknown"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-no-unknown (actual, options)](#apidoc.element.stylelint.rules.unit-no-unknown)
- description and source-code
```javascript
unit-no-unknown = function (actual, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual }, {
      actual: options,
      possible: {
        ignoreUnits: [_.isString],
      },
      optional: true,
    })

    if (!validOptions) {
      return
    }

    function check(node, value, getIndex) {
      valueParser(value).walk(function (valueNode) {
        // Ignore wrong units within 'url' function
        if (valueNode.type === "function" && valueNode.value.toLowerCase() === "url") {
          return false
        }

        const unit = getUnitFromValueNode(valueNode)
        if (!unit) {
          return
        }

        if (optionsMatches(options, "ignoreUnits", unit)) {
          return
        }

        if (keywordSets.units.has(unit.toLowerCase())) {
          return
        }

        report({
          index: getIndex(node) + valueNode.sourceIndex,
          message: messages.rejected(unit),
          node,
          result,
          ruleName,
        })
      })
    }

    root.walkAtRules(/^media$/i, atRule => check(atRule, atRule.params, atRuleParamIndex))
    root.walkDecls(decl => check(decl, decl.value, declarationValueIndex))
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.unit-whitelist"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>unit-whitelist (whitelistInput, options)](#apidoc.element.stylelint.rules.unit-whitelist)
- description and source-code
```javascript
unit-whitelist = function (whitelistInput, options) {
  const whitelist = [].concat(whitelistInput)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: whitelist,
      possible: [_.isString],
    }, {
      optional: true,
      actual: options,
      possible: {
        ignoreProperties: validateObjectWithStringArrayProps,
      },
    })
    if (!validOptions) {
      return
    }

    function check(node, value, getIndex) {
      valueParser(value).walk(function (valueNode) {
        // Ignore wrong units within 'url' function
        if (valueNode.type === "function" && valueNode.value.toLowerCase() === "url") {
          return false
        }

        const unit = getUnitFromValueNode(valueNode)

        if (!unit || unit && whitelist.indexOf(unit.toLowerCase()) !== -1) {
          return
        }

        if (options && optionsMatches(options["ignoreProperties"], unit.toLowerCase(), node.prop)) {
          return
        }

        report({
          index: getIndex(node) + valueNode.sourceIndex,
          message: messages.rejected(unit),
          node,
          result,
          ruleName,
        })
      })
    }

    root.walkAtRules(/^media$/i, atRule => check(atRule, atRule.params, atRuleParamIndex))
    root.walkDecls(decl => check(decl, decl.value, declarationValueIndex))
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.value-keyword-case"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>value-keyword-case (expectation, options)](#apidoc.element.stylelint.rules.value-keyword-case)
- description and source-code
```javascript
value-keyword-case = function (expectation, options) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "lower",
        "upper",
      ],
    }, {
      actual: options,
      possible: {
        ignoreKeywords: [_.isString],
      },
      optional: true,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const prop = decl.prop,
        value = decl.value

      valueParser(value).walk(node => {
        const valueLowerCase = node.value.toLowerCase()

        // Ignore system colors
        if (keywordSets.systemColors.has(valueLowerCase)) {
          return
        }

        // Ignore keywords within 'url' and 'var' function
        if (node.type === "function" && (valueLowerCase === "url" || valueLowerCase === "var" || valueLowerCase === "counter" ||
valueLowerCase === "counters" || valueLowerCase === "attr")) {
          return false
        }

        const keyword = node.value

        // Ignore css variables, and hex values, and math operators, and sass interpolation
        if (node.type !== "word" || !isStandardSyntaxValue(node.value) || value.indexOf("#") !== -1 || ignoredCharacters.has(keyword
) || getUnitFromValueNode(node)) {
          return
        }

        if (prop === "animation" && !keywordSets.animationShorthandKeywords.has(valueLowerCase) && !keywordSets.animationNameKeywords
.has(valueLowerCase)) {
          return
        }
        if (prop === "animation-name" && !keywordSets.animationNameKeywords.has(valueLowerCase)) {
          return
        }
        if (prop === "font" && !keywordSets.fontShorthandKeywords.has(valueLowerCase) && !keywordSets.fontFamilyKeywords.has(valueLowerCase
)) {
          return
        }
        if (prop === "font-family" && !keywordSets.fontFamilyKeywords.has(valueLowerCase)) {
          return
        }
        if (prop === "counter-increment" && isCounterIncrementCustomIdentValue(valueLowerCase)) {
          return
        }
        if (prop === "counter-reset" && isCounterResetCustomIdentValue(valueLowerCase)) {
          return
        }
        if (prop === "grid-row" && !keywordSets.gridRowKeywords.has(valueLowerCase)) {
          return
        }
        if (prop === "grid-column" && !keywordSets.gridColumnKeywords.has(valueLowerCase)) {
          return
        }
        if (prop === "grid-area" && !keywordSets.gridAreaKeywords.has(valueLowerCase)) {
          return
        }
        if (prop === "list-style" && !keywordSets.listStyleShorthandKeywords.has(valueLowerCase) && !keywordSets.listStyleTypeKeywords
.has(valueLowerCase)) {
          return
        }
        if (prop === "list-style-type" && !keywordSets.listStyleTypeKeywords.has(valueLowerCase)) {
          return
        }

        const ignoreKeywords = options && options.ignoreKeywords || []

        if (ignoreKeywords.length > 0 && matchesStringOrRegExp(keyword, ignoreKeywords)) {
          return
        }

        const keywordLowerCase = keyword.toLocaleLowerCase()
        let expectedKeyword = null

        if (expectation === "lower" && mapLowercaseKeywordsToCamelCase.has(keywordLowerCase)) {
          expectedKeyword = mapLowercaseKeywordsToCamelCase.get(keywordLowerCase)
        } else if (expectation === "lower") {
          expectedKeyword = keyword.toLowerCase()
        } else {
          expectedKeyword = keyword.toUpperCase()
        }

        if (keyword === expectedKeyword) {
          return
        }

        report({
          message: messages.expected(keyword, expectedKeyword),
          node: decl,
          index: declarationValueIndex(decl) + node.sourceIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.value-list-comma-newline-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-newline-after (expectation)](#apidoc.element.stylelint.rules.value-list-comma-newline-after)
- description and source-code
```javascript
value-list-comma-newline-after = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    valueListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.afterOneOnly,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.value-list-comma-newline-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-newline-before (expectation)](#apidoc.element.stylelint.rules.value-list-comma-newline-before)
- description and source-code
```javascript
value-list-comma-newline-before = function (expectation) {
  const checker = whitespaceChecker("newline", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "always-multi-line",
        "never-multi-line",
      ],
    })
    if (!validOptions) {
      return
    }

    valueListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.beforeAllowingIndentation,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.value-list-comma-space-after"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-space-after (expectation)](#apidoc.element.stylelint.rules.value-list-comma-space-after)
- description and source-code
```javascript
value-list-comma-space-after = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    valueListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.after,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.value-list-comma-space-before"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-comma-space-before (expectation)](#apidoc.element.stylelint.rules.value-list-comma-space-before)
- description and source-code
```javascript
value-list-comma-space-before = function (expectation) {
  const checker = whitespaceChecker("space", expectation, messages)
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: expectation,
      possible: [
        "always",
        "never",
        "always-single-line",
        "never-single-line",
      ],
    })
    if (!validOptions) {
      return
    }

    valueListCommaWhitespaceChecker({
      root,
      result,
      locationChecker: checker.before,
      checkedRuleName: ruleName,
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.value-list-max-empty-lines"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>value-list-max-empty-lines (max)](#apidoc.element.stylelint.rules.value-list-max-empty-lines)
- description and source-code
```javascript
value-list-max-empty-lines = function (max) {
  const maxAdjacentNewlines = max + 1

  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, {
      actual: max,
      possible: _.isNumber,
    })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      const value = decl.value
      const repeatLFNewLines = _.repeat("\n", maxAdjacentNewlines)
      const repeatCRLFNewLines = _.repeat("\r\n", maxAdjacentNewlines)

      styleSearch({ source: value, target: "\n" }, match => {
        if (value.substr(match.startIndex + 1, maxAdjacentNewlines) === repeatLFNewLines || value.substr(match.startIndex + 1, maxAdjacentNewlines
 * 2) === repeatCRLFNewLines) {
          // Put index at '\r' if it's CRLF, otherwise leave it at '\n'
          let index = match.startIndex
          if (value[index - 1] === "\r") {
            index -= 1
          }

          report({
            message: messages.expected(max),
            node: decl,
            index,
            result,
            ruleName,
          })
        }
      })
    })
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.rules.value-no-vendor-prefix"></a>[function <span class="apidocSignatureSpan">stylelint.rules.</span>value-no-vendor-prefix (actual)](#apidoc.element.stylelint.rules.value-no-vendor-prefix)
- description and source-code
```javascript
value-no-vendor-prefix = function (actual) {
  return (root, result) => {
    const validOptions = validateOptions(result, ruleName, { actual })
    if (!validOptions) {
      return
    }

    root.walkDecls(decl => {
      if (!isStandardSyntaxDeclaration(decl) || !isStandardSyntaxProperty(decl.prop) || decl.value[0] !== "-") {
        return
      }

      const prop = decl.prop,
        value = decl.value

      // Search the full declaration in order to get an accurate index

      styleSearch({ source: value.toLowerCase(), target: valuePrefixes }, match => {
        const fullIdentifier = /^(-[a-z-]+)\b/i.exec(value.slice(match.startIndex))[1]
        if (!isAutoprefixable.propertyValue(prop, fullIdentifier)) {
          return
        }

        report({
          message: messages.rejected(fullIdentifier),
          node: decl,
          index: prop.length + (decl.raws.between || "").length + match.startIndex,
          result,
          ruleName,
        })
      })
    })
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.stylelint.utils"></a>[module stylelint.utils](#apidoc.module.stylelint.utils)

#### <a name="apidoc.element.stylelint.utils.checkAgainstRule"></a>[function <span class="apidocSignatureSpan">stylelint.utils.</span>checkAgainstRule ( options, callback )](#apidoc.element.stylelint.utils.checkAgainstRule)
- description and source-code
```javascript
checkAgainstRule = function ( options, callback ) {
  if (!options) throw new Error("checkAgainstRule requires an options object with 'ruleName', 'ruleSettings', and 'root' properties
")
  if (!callback) throw new Error("checkAgainstRule requires a callback")
  if (!options.ruleName) throw new Error("checkAgainstRule requires a 'ruleName' option")
  if (!rules[options.ruleName]) throw new Error('Rule '${options.ruleName}' does not exist')
  if (!options.ruleSettings) throw new Error("checkAgainstRule requires a 'ruleSettings' option")
  if (!options.root) throw new Error("checkAgainstRule requires a 'root' option")

  const settings = normalizeRuleSettings(options.ruleSettings, options.ruleName)
  if (!settings) { return }

  const tmpPostcssResult = new Result()
  rules[options.ruleName](settings[0], settings[1])(options.root, tmpPostcssResult)
  tmpPostcssResult.warnings().forEach(callback)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.utils.report"></a>[function <span class="apidocSignatureSpan">stylelint.utils.</span>report (violation)](#apidoc.element.stylelint.utils.report)
- description and source-code
```javascript
report = function (violation) {
  const ruleName = violation.ruleName
  const result = violation.result
  const message = violation.message
  const line = violation.line
  const node = violation.node
  const index = violation.index
  const word = violation.word

  result.stylelint = result.stylelint || {}

  // In quiet mode, mere warnings are ignored
  if (result.stylelint.quiet && result.stylelint.ruleSeverities[ruleName] !== "error") {
    return
  }

  // If a line is not passed, use the node.positionBy method to get the
  // line number that the complaint pertains to
  const startLine = line || node.positionBy({ index }).line

  if (result.stylelint.disabledRanges && !result.stylelint.ignoreDisables) {
    const ranges = result.stylelint.disabledRanges[ruleName] || result.stylelint.disabledRanges.all
    for (const range of ranges) {
      if (
      // If the violation is within a disabledRange,
      // and that disabledRange's rules include this one,
      // do not register a warning
      range.start <= startLine && (range.end >= startLine || range.end === undefined) && (!range.rules || range.rules.indexOf(ruleName
) !== -1)) {
        return
      }
    }
  }

  const severity = _.get(result.stylelint, [ "ruleSeverities", ruleName ], "ignore")

  if (!result.stylelint.stylelintError && severity === "error") {
    result.stylelint.stylelintError = true
  }

  const warningProperties/*: Object*/ = {
    severity,
    rule: ruleName,
  }
  if (node) {
    warningProperties.node = node
  }
  if (index) {
    warningProperties.index = index
  }
  if (word) {
    warningProperties.word = word
  }

  const warningMessage = _.get(result.stylelint, [ "customMessages", ruleName ], message)
  result.warn(warningMessage, warningProperties)
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.utils.ruleMessages"></a>[function <span class="apidocSignatureSpan">stylelint.utils.</span>ruleMessages ( ruleName, messages )](#apidoc.element.stylelint.utils.ruleMessages)
- description and source-code
```javascript
ruleMessages = function ( ruleName, messages )/*: Object*/ {
  return Object.keys(messages).reduce((newMessages, messageId) => {
    const messageText = messages[messageId]
    if (typeof messageText === "string") {
      newMessages[messageId] = '${messageText} (${ruleName})'
    } else {
      newMessages[messageId] = function () {
        return '${messageText.apply(null, arguments)} (${ruleName})'
      }
    }
    return newMessages
  }, {})
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.stylelint.utils.validateOptions"></a>[function <span class="apidocSignatureSpan">stylelint.utils.</span>validateOptions ( result, ruleName )](#apidoc.element.stylelint.utils.validateOptions)
- description and source-code
```javascript
validateOptions = function ( result, ruleName )/*: boolean*/ {
  let noErrors = true

  const optionDescriptions = Array.from(arguments).slice(2)

  optionDescriptions.forEach(optionDescription => {
    validate(optionDescription, ruleName, complain)
  })

  function complain(message) {
    noErrors = false
    result.warn(message, {
      stylelintType: "invalidOption",
    })
    _.set(result, "stylelint.stylelintError", true)
  }

  return noErrors
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
