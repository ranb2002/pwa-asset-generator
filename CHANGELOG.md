# Changelog

All notable changes to this project will be documented in this file. See
[Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [3.2.1](https://github.com/onderceylan/pwa-asset-generator/compare/v3.2.0...v3.2.1) (2020-08-31)


### Bug Fixes

* **main:** fix xhtml option having no effect on module usage ([4dfa9c4](https://github.com/onderceylan/pwa-asset-generator/commit/4dfa9c4c61826c392a735099b456efb4ec3da070)), closes [#351](https://github.com/onderceylan/pwa-asset-generator/issues/351)

# [3.2.0](https://github.com/onderceylan/pwa-asset-generator/compare/v3.1.3...v3.2.0) (2020-08-30)


### Features

* **main:** enable parallel execution ([98f0464](https://github.com/onderceylan/pwa-asset-generator/commit/98f046441a7930d0393610af7ec6b8156e076542)), closes [#357](https://github.com/onderceylan/pwa-asset-generator/issues/357)

## [3.1.3](https://github.com/onderceylan/pwa-asset-generator/compare/v3.1.2...v3.1.3) (2020-07-30)


### Bug Fixes

* **main:** constraint default type to png for manifest icons ([bf6f87c](https://github.com/onderceylan/pwa-asset-generator/commit/bf6f87cf7125796fcba090a98b503111b835cbda)), closes [#337](https://github.com/onderceylan/pwa-asset-generator/issues/337)

## [3.1.2](https://github.com/onderceylan/pwa-asset-generator/compare/v3.1.1...v3.1.2) (2020-07-30)


### Bug Fixes

* **puppets:** updated scraper for latest specs and improve fallback handling ([6506952](https://github.com/onderceylan/pwa-asset-generator/commit/6506952133df437ab191400533fd57585c81d7ff)), closes [#355](https://github.com/onderceylan/pwa-asset-generator/issues/355)

## [3.1.1](https://github.com/onderceylan/pwa-asset-generator/compare/v3.1.0...v3.1.1) (2020-06-03)


### Bug Fixes

* **docs:** fix BLM example image URL ([2cb0e76](https://github.com/onderceylan/pwa-asset-generator/commit/2cb0e76173f8516e7a8bcf005bbf8e02c322f8a9)), closes [#303](https://github.com/onderceylan/pwa-asset-generator/issues/303)

# [3.1.0](https://github.com/onderceylan/pwa-asset-generator/compare/v3.0.0...v3.1.0) (2020-06-03)


### Features

* **cli:** display help when no arg is provided ([0641bd9](https://github.com/onderceylan/pwa-asset-generator/commit/0641bd9fb3da650ac06abff3f90e8007567804a6)), closes [#302](https://github.com/onderceylan/pwa-asset-generator/issues/302)
* **main:** add BLM branding #blacklifematters ([d572c5d](https://github.com/onderceylan/pwa-asset-generator/commit/d572c5da436fb4dec59eb1bfd0609e5b05b6d4b9)), closes [#301](https://github.com/onderceylan/pwa-asset-generator/issues/301)

# [3.0.0](https://github.com/onderceylan/pwa-asset-generator/compare/v2.3.0...v3.0.0) (2020-05-15)


### Bug Fixes

* **cli:** fixed conflicting -h option ([3d4f04c](https://github.com/onderceylan/pwa-asset-generator/commit/3d4f04c8bb9d784e73e1b0a398e909432e8d7887)), closes [#263](https://github.com/onderceylan/pwa-asset-generator/issues/263)


### Features

* **main:** added dark mode media query support for html inputs ([c5d2e0d](https://github.com/onderceylan/pwa-asset-generator/commit/c5d2e0d2b729d130b759cd39755280b8cee8c4c3)), closes [#227](https://github.com/onderceylan/pwa-asset-generator/issues/227)
* **main:** added stricter chrome launch args set ([bdfbef4](https://github.com/onderceylan/pwa-asset-generator/commit/bdfbef4021567f9b055a614f574c58863a9ee3a3)), closes [#229](https://github.com/onderceylan/pwa-asset-generator/issues/229)
* **main:** exported appleDeviceSpecsForLaunchImages from module API ([dac56d4](https://github.com/onderceylan/pwa-asset-generator/commit/dac56d4cadcff35e95188d7a684f0b882683c679)), closes [#248](https://github.com/onderceylan/pwa-asset-generator/issues/248)
* **main:** switched to JPG as default output type ([bb5cfec](https://github.com/onderceylan/pwa-asset-generator/commit/bb5cfec59daf9087f9415831788453b32254d1f6)), closes [#278](https://github.com/onderceylan/pwa-asset-generator/issues/278)
* **meta:** added xhtml option to introduce self-closing meta tags ([0dea81a](https://github.com/onderceylan/pwa-asset-generator/commit/0dea81a764e5f1d3f2d1069c31aae2722aec37cd)), closes [#192](https://github.com/onderceylan/pwa-asset-generator/issues/192)
* **node:** drop node 8 support due to its EOL ([030569b](https://github.com/onderceylan/pwa-asset-generator/commit/030569b1afbb908ba39f85d2e64c18f7981852ad)), closes [#231](https://github.com/onderceylan/pwa-asset-generator/issues/231)


### BREAKING CHANGES

* **main:** Due to the large carbon footprint that PNG assets create, switched over using JPG
output with compression by default.
* **cli:** -h path override usage is dropped. It's replaced with -v shorthand.
* **node:** Users with node v8 will not be actively supported.

# [2.3.0](https://github.com/onderceylan/pwa-asset-generator/compare/v2.2.2...v2.3.0) (2020-03-08)


### Features

* **main:** added maskable purpose as default declaration in manifest ([006d73c](https://github.com/onderceylan/pwa-asset-generator/commit/006d73cf3712fdadb6686e48a6169c33eb5dc641)), closes [#38](https://github.com/onderceylan/pwa-asset-generator/issues/38)
* **main:** added maskable purpose as default declaration in manifest ([84dcc67](https://github.com/onderceylan/pwa-asset-generator/commit/84dcc6714f7251b6d1df83e4d51ffcb6e5ff07ad)), closes [#38](https://github.com/onderceylan/pwa-asset-generator/issues/38)
* **main:** added pathOverride option to allow path optimisation on href ([7ff2e07](https://github.com/onderceylan/pwa-asset-generator/commit/7ff2e071ddd011412b2aa3fae8865270069bf565)), closes [#148](https://github.com/onderceylan/pwa-asset-generator/issues/148)
* **main:** added pathOverride option to allow path optimisation on href ([2d89cba](https://github.com/onderceylan/pwa-asset-generator/commit/2d89cba433e6ac3e7c359f0228750e092e1ccd08)), closes [#148](https://github.com/onderceylan/pwa-asset-generator/issues/148)

## [2.2.2](https://github.com/onderceylan/pwa-asset-generator/compare/v2.2.1...v2.2.2) (2020-02-24)


### Bug Fixes

* **puppets:** fixed failing scrape of Apple splash screen specs ([cff635b](https://github.com/onderceylan/pwa-asset-generator/commit/cff635b940ef6ae6233224fcdff297b068985d54)), closes [#168](https://github.com/onderceylan/pwa-asset-generator/issues/168)

## [2.2.1](https://github.com/onderceylan/pwa-asset-generator/compare/v2.2.0...v2.2.1) (2020-01-21)


### Bug Fixes

* **puppets:** added wait until networkidle opt for remote html input ([9aa86eb](https://github.com/onderceylan/pwa-asset-generator/commit/9aa86eb8a783f66cd0608f7684271cfe93c3a686)), closes [#125](https://github.com/onderceylan/pwa-asset-generator/issues/125)

# [2.2.0](https://github.com/onderceylan/pwa-asset-generator/compare/v2.1.3...v2.2.0) (2020-01-16)


### Features

* **main:** added jpg extension as an output type ([e1f2221](https://github.com/onderceylan/pwa-asset-generator/commit/e1f222146517e350c536026c5ac8c4bb1a50a252)), closes [#116](https://github.com/onderceylan/pwa-asset-generator/issues/116)

## [2.1.3](https://github.com/onderceylan/pwa-asset-generator/compare/v2.1.2...v2.1.3) (2019-12-19)


### Bug Fixes

* **file:** fixed an issue while creating a non-existent output dir ([b691b6f](https://github.com/onderceylan/pwa-asset-generator/commit/b691b6f8085c3fb4d384364a55bcfeb12ae10305)), closes [#77](https://github.com/onderceylan/pwa-asset-generator/issues/77)

## [2.1.2](https://github.com/onderceylan/pwa-asset-generator/compare/v2.1.1...v2.1.2) (2019-11-08)


### Bug Fixes

* **cli:** updated docs to clarify transparency option ([a4bcaff](https://github.com/onderceylan/pwa-asset-generator/commit/a4bcaffc0b91621b25fd65084eb09ef008bb60b0)), closes [#68](https://github.com/onderceylan/pwa-asset-generator/issues/68)

## [2.1.1](https://github.com/onderceylan/pwa-asset-generator/compare/v2.1.0...v2.1.1) (2019-11-01)


### Bug Fixes

* **puppets:** added error handling for failing chrome kill attempt ([6cc65fd](https://github.com/onderceylan/pwa-asset-generator/commit/6cc65fd1fdce6b70ffb6383ac452aba207f1d1b1)), closes [#65](https://github.com/onderceylan/pwa-asset-generator/issues/65)

# [2.1.0](https://github.com/onderceylan/pwa-asset-generator/compare/v2.0.2...v2.1.0) (2019-11-01)


### Bug Fixes

* **browser:** added a method to kill premature chrome instances ([ad69854](https://github.com/onderceylan/pwa-asset-generator/commit/ad69854c45af27d767319095aaae2706eb404f05)), closes [#58](https://github.com/onderceylan/pwa-asset-generator/issues/58)
* **file:** replaced backslash in path output of generate images API res ([6563977](https://github.com/onderceylan/pwa-asset-generator/commit/656397727017ad93290bd781c7dffb1874fbae51)), closes [#64](https://github.com/onderceylan/pwa-asset-generator/issues/64)


### Features

* **main:** upgraded to pptr v2 and optimized chrome launcher ([a14e8e6](https://github.com/onderceylan/pwa-asset-generator/commit/a14e8e630fc3542bf353fe88f5d398b409bb0c53)), closes [#62](https://github.com/onderceylan/pwa-asset-generator/issues/62) [#58](https://github.com/onderceylan/pwa-asset-generator/issues/58)

## [2.0.2](https://github.com/onderceylan/pwa-asset-generator/compare/v2.0.1...v2.0.2) (2019-10-30)


### Bug Fixes

* **meta:** added disable decoding entities option to cheerio ([1e984eb](https://github.com/onderceylan/pwa-asset-generator/commit/1e984ebd976f080130f8d6209602f86cd904e5bb)), closes [#60](https://github.com/onderceylan/pwa-asset-generator/issues/60)

## [2.0.1](https://github.com/onderceylan/pwa-asset-generator/compare/v2.0.0...v2.0.1) (2019-10-27)


### Bug Fixes

* **browser:** avoid SPOF for chrome launcher ([f5ca991](https://github.com/onderceylan/pwa-asset-generator/commit/f5ca9917ae965c6508e15e52e7efcf9dae1f402a)), closes [#56](https://github.com/onderceylan/pwa-asset-generator/issues/56)

# [2.0.0](https://github.com/onderceylan/pwa-asset-generator/compare/v1.3.1...v2.0.0) (2019-10-25)


### Bug Fixes

* **browser:** added error handling for chrome-launcher ([c6ed23a](https://github.com/onderceylan/pwa-asset-generator/commit/c6ed23a06e6e9cdbeeb8aba4837fa28f138c7bee)), closes [#50](https://github.com/onderceylan/pwa-asset-generator/issues/50)
* **package:** suppressed security warning by changing pkg v strategy ([9987e39](https://github.com/onderceylan/pwa-asset-generator/commit/9987e395888260e245c06a5f1c1f2d7a736854d5)), closes [#53](https://github.com/onderceylan/pwa-asset-generator/issues/53)


### Features

* **file:** avoided saving a shell html file ([b96d545](https://github.com/onderceylan/pwa-asset-generator/commit/b96d5453cbcaa950f21864f3b1cd494726f3cbc9)), closes [#52](https://github.com/onderceylan/pwa-asset-generator/issues/52)
* **icon:** added optional favicon generation ([699686a](https://github.com/onderceylan/pwa-asset-generator/commit/699686a39df2502a8ebd18ecc4d8b6b96a199196)), closes [#47](https://github.com/onderceylan/pwa-asset-generator/issues/47)
* **main:** added dark mode support for iOS ([f4aca1c](https://github.com/onderceylan/pwa-asset-generator/commit/f4aca1c3ec9768596b97e405485b2c446e89c40d)), closes [#51](https://github.com/onderceylan/pwa-asset-generator/issues/51)
* **pptr:** switched over puppeteer-core to avoid chromium install ([05edb2e](https://github.com/onderceylan/pwa-asset-generator/commit/05edb2ee19c68b700963c513766c10deff11334c)), closes [#50](https://github.com/onderceylan/pwa-asset-generator/issues/50)
* **pwa:** added single quotes option for generated HTML tags ([351a3cc](https://github.com/onderceylan/pwa-asset-generator/commit/351a3cc92d292d9ec5215fae1d120933e4357808)), closes [#49](https://github.com/onderceylan/pwa-asset-generator/issues/49)


### BREAKING CHANGES

* **main:** generateImages method from the module API now returns HTMLMeta object with the
chunks of HTML content, instead of one big HTML string

## [1.3.1](https://github.com/onderceylan/pwa-asset-generator/compare/v1.3.0...v1.3.1) (2019-09-26)


### Bug Fixes

* **file:** fixed relative path to input file that is not resolving ([19cc7c4](https://github.com/onderceylan/pwa-asset-generator/commit/19cc7c4)), closes [#45](https://github.com/onderceylan/pwa-asset-generator/issues/45)

# [1.3.0](https://github.com/onderceylan/pwa-asset-generator/compare/v1.2.0...v1.3.0) (2019-09-25)


### Features

* **core:** migrated to TypeScript and reduced node dep to 6.4.0 ([cfc1657](https://github.com/onderceylan/pwa-asset-generator/commit/cfc1657)), closes [#6](https://github.com/onderceylan/pwa-asset-generator/issues/6)

# [1.2.0](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.7...v1.2.0) (2019-09-12)


### Features

* **main:** added option to provide path prefix to generated href links ([268c671](https://github.com/onderceylan/pwa-asset-generator/commit/268c671)), closes [#31](https://github.com/onderceylan/pwa-asset-generator/issues/31)
* **main:** added option to provide path prefix to generated href links ([1e18466](https://github.com/onderceylan/pwa-asset-generator/commit/1e18466)), closes [#31](https://github.com/onderceylan/pwa-asset-generator/issues/31)
* **main:** exposed private API via main.js ([afce4af](https://github.com/onderceylan/pwa-asset-generator/commit/afce4af)), closes [#5](https://github.com/onderceylan/pwa-asset-generator/issues/5)
* **main:** exposed private API via main.js ([d3367ad](https://github.com/onderceylan/pwa-asset-generator/commit/d3367ad)), closes [#5](https://github.com/onderceylan/pwa-asset-generator/issues/5)
* **main:** refactored main and added index.d.ts ([72a7fe4](https://github.com/onderceylan/pwa-asset-generator/commit/72a7fe4)), closes [#5](https://github.com/onderceylan/pwa-asset-generator/issues/5)
* **main:** refactored main and added index.d.ts ([1ab1c3e](https://github.com/onderceylan/pwa-asset-generator/commit/1ab1c3e)), closes [#5](https://github.com/onderceylan/pwa-asset-generator/issues/5)

## [1.1.7](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.6...v1.1.7) (2019-08-30)


### Bug Fixes

* **file.js, pwa.js, package.json:** fix Windows backslash paths being added to icon and html content ([24fef99](https://github.com/onderceylan/pwa-asset-generator/commit/24fef99)), closes [#36](https://github.com/onderceylan/pwa-asset-generator/issues/36)

## [1.1.6](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.5...v1.1.6) (2019-08-29)


### Bug Fixes

* **cli:** add icon code output for ios icons ([c768fb6](https://github.com/onderceylan/pwa-asset-generator/commit/c768fb6)), closes [#26](https://github.com/onderceylan/pwa-asset-generator/issues/26)
* **puppets:** increased timeout for generating images ([3191560](https://github.com/onderceylan/pwa-asset-generator/commit/3191560)), closes [#28](https://github.com/onderceylan/pwa-asset-generator/issues/28)

## [1.1.5](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.4...v1.1.5) (2019-08-22)


### Bug Fixes

* **cli:** calculated relative path of generated content to the reference output file ([b76e9d2](https://github.com/onderceylan/pwa-asset-generator/commit/b76e9d2)), closes [#21](https://github.com/onderceylan/pwa-asset-generator/issues/21)
* **cli:** use relative path when output is not provided ([ec991ec](https://github.com/onderceylan/pwa-asset-generator/commit/ec991ec)), closes [#20](https://github.com/onderceylan/pwa-asset-generator/issues/20)

## [1.1.4](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.3...v1.1.4) (2019-08-19)


### Bug Fixes

* **cli:** fixed wrong url on help text ([6cc6e22](https://github.com/onderceylan/pwa-asset-generator/commit/6cc6e22)), closes [#11](https://github.com/onderceylan/pwa-asset-generator/issues/11)
* fixed iPad 12.9" specs being stripped out and added orientation key to the media queries ([59a891a](https://github.com/onderceylan/pwa-asset-generator/commit/59a891a)), closes [#18](https://github.com/onderceylan/pwa-asset-generator/issues/18)
* **puppets:** fixed the check where scraping result is evaluated ([b584be0](https://github.com/onderceylan/pwa-asset-generator/commit/b584be0))

## [1.1.3](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.2...v1.1.3) (2019-08-18)


### Bug Fixes

* **cli:** fixed wrong url on help text ([03775bf](https://github.com/onderceylan/pwa-asset-generator/commit/03775bf)), closes [#11](https://github.com/onderceylan/pwa-asset-generator/issues/11)

## [1.1.2](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.1...v1.1.2) (2019-08-16)


### Bug Fixes

* **readme:** fixed wrong link on examples ([35152f3](https://github.com/onderceylan/pwa-asset-generator/commit/35152f3))

## [1.1.1](https://github.com/onderceylan/pwa-asset-generator/compare/v1.1.0...v1.1.1) (2019-08-16)


### Bug Fixes

* **readme:** fixed broken link on readme ([5d6e0b4](https://github.com/onderceylan/pwa-asset-generator/commit/5d6e0b4))

# [1.1.0](https://github.com/onderceylan/pwa-asset-generator/compare/v1.0.2...v1.1.0) (2019-08-15)


### Features

* **cli:** added --portrait-only and --landscape-only flags ([1fb1ecb](https://github.com/onderceylan/pwa-asset-generator/commit/1fb1ecb)), closes [#4](https://github.com/onderceylan/pwa-asset-generator/issues/4)
* **cli:** added --splash-only and --icon-only flags ([20f39e0](https://github.com/onderceylan/pwa-asset-generator/commit/20f39e0)), closes [#3](https://github.com/onderceylan/pwa-asset-generator/issues/3)
* **cli:** added --type and --quality flags ([c0c1565](https://github.com/onderceylan/pwa-asset-generator/commit/c0c1565)), closes [#2](https://github.com/onderceylan/pwa-asset-generator/issues/2)
* **cli:** create output folder if it doesn't exist ([4eebf34](https://github.com/onderceylan/pwa-asset-generator/commit/4eebf34)), closes [#9](https://github.com/onderceylan/pwa-asset-generator/issues/9)

## [1.0.2](https://github.com/onderceylan/pwa-asset-generator/compare/v1.0.1...v1.0.2) (2019-08-14)


### Bug Fixes

* **npm:** ignored static files to keep the tarball clean ([6de2a39](https://github.com/onderceylan/pwa-asset-generator/commit/6de2a39))

## [1.0.1](https://github.com/onderceylan/pwa-asset-generator/compare/v1.0.0...v1.0.1) (2019-08-14)


### Bug Fixes

* **cli:** fixed the issue when output is not provided ([b7102e7](https://github.com/onderceylan/pwa-asset-generator/commit/b7102e7)), closes [#1](https://github.com/onderceylan/pwa-asset-generator/issues/1)
