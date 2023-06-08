# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 2.0.0 (2023-06-08)


### ⚠ BREAKING CHANGES

* use `ref` instead of id in DOM as container, makes it more "vue-way"

### Features

* add cors ([e9c4a10](https://github.com/jetthai/vue-lazyload/commit/e9c4a10314d27d9d5e914756853aa4f36d9a95ca))
* split lazy config & import on demand ([dad9f41](https://github.com/jetthai/vue-lazyload/commit/dad9f415de11b2028f5b12fe837cfd82f4b6305f))


### Bug Fixes

* [#348](https://github.com/jetthai/vue-lazyload/issues/348) ([cd8df3d](https://github.com/jetthai/vue-lazyload/commit/cd8df3db0be77f4a3719cb01ffe66d49f73362fd))
* 348 prevent to get null 404 (Not Found) ([f270672](https://github.com/jetthai/vue-lazyload/commit/f2706721188d89d543f93274bbde6d8a31d8a61a))
* babel configuration not work ([#505](https://github.com/jetthai/vue-lazyload/issues/505)) ([e379b31](https://github.com/jetthai/vue-lazyload/commit/e379b3183f379566455cc22fbc1111d11d88f4e0))
* banner missing ([8c098b6](https://github.com/jetthai/vue-lazyload/commit/8c098b671f2eb871b66cf26b6d93f9ba5d20fe41))
* check IntersectionObserver wrong ([5688afa](https://github.com/jetthai/vue-lazyload/commit/5688afa3f8c683aae75ea311bf207d41eae15065))
* error img url load limit ([50888b7](https://github.com/jetthai/vue-lazyload/commit/50888b7669853b9a00d639b63569188fdcad5283))
* error load repeat ([6dc016d](https://github.com/jetthai/vue-lazyload/commit/6dc016d996af8fc7a704ce4d76a7f57aacf279be))
* error symbol in docs ([ca1c6c4](https://github.com/jetthai/vue-lazyload/commit/ca1c6c48bad4e4995b5238e15f0dcd5e92e9bced))
* issue[#112](https://github.com/jetthai/vue-lazyload/issues/112) ([8b2e16c](https://github.com/jetthai/vue-lazyload/commit/8b2e16c52abe1a72f279963b376d7bfb53e12a8b))
* issue[#128](https://github.com/jetthai/vue-lazyload/issues/128) ([459be0a](https://github.com/jetthai/vue-lazyload/commit/459be0a18af002c32385b95f31dfd7207a720c41))
* issue[#130](https://github.com/jetthai/vue-lazyload/issues/130) ([c431e73](https://github.com/jetthai/vue-lazyload/commit/c431e7327e872ed9bced8acbf296b29ae870dd98))
* issue[#133](https://github.com/jetthai/vue-lazyload/issues/133) ([cd1032e](https://github.com/jetthai/vue-lazyload/commit/cd1032ec08fa974d877fb1865f6060664f3c0aa5))
* issue[#133](https://github.com/jetthai/vue-lazyload/issues/133) ([3b0eab9](https://github.com/jetthai/vue-lazyload/commit/3b0eab91a146af2c62e4104102ad3df29bce2407))
* issue[#150](https://github.com/jetthai/vue-lazyload/issues/150) ([15349db](https://github.com/jetthai/vue-lazyload/commit/15349db75ceb7ddde6a946280ecce7556058a0bd))
* issue[#236](https://github.com/jetthai/vue-lazyload/issues/236) fixed [#236](https://github.com/jetthai/vue-lazyload/issues/236), fixed [#218](https://github.com/jetthai/vue-lazyload/issues/218) ([bb6528e](https://github.com/jetthai/vue-lazyload/commit/bb6528e14d4112f937e7e7d20eb27b4f65374735))
* issue[#25](https://github.com/jetthai/vue-lazyload/issues/25) ([4b92c8e](https://github.com/jetthai/vue-lazyload/commit/4b92c8e3da469aea1c495ce3fb581f858b868041))
* issue[#26](https://github.com/jetthai/vue-lazyload/issues/26) ([e19f9b2](https://github.com/jetthai/vue-lazyload/commit/e19f9b2418ee70ee92d991d4f12a9bdbf939cdb4))
* issue[#269](https://github.com/jetthai/vue-lazyload/issues/269) ([cbf4ecc](https://github.com/jetthai/vue-lazyload/commit/cbf4ecc5bf5db4b383842d1036328ac1971fdca6))
* issue[#35](https://github.com/jetthai/vue-lazyload/issues/35) ([b6a3c6b](https://github.com/jetthai/vue-lazyload/commit/b6a3c6b965ea2d498434341dc60fa90336123574))
* issue[#36](https://github.com/jetthai/vue-lazyload/issues/36) ([761bfbe](https://github.com/jetthai/vue-lazyload/commit/761bfbe1859a5c423d701b9dbcef456a1caf2f3f))
* issue[#373](https://github.com/jetthai/vue-lazyload/issues/373) [#372](https://github.com/jetthai/vue-lazyload/issues/372) ([6c8d883](https://github.com/jetthai/vue-lazyload/commit/6c8d8837f4d4f11f7b57fb8dc4733398607e83c4))
* issue[#380](https://github.com/jetthai/vue-lazyload/issues/380) ([fe7db4a](https://github.com/jetthai/vue-lazyload/commit/fe7db4afe5e3f46ead290a25ce98d502a89aebdb))
* issue[#380](https://github.com/jetthai/vue-lazyload/issues/380) ([6f42af9](https://github.com/jetthai/vue-lazyload/commit/6f42af902509caad844298c84c36bdd465f094b4))
* issue[#65](https://github.com/jetthai/vue-lazyload/issues/65) ([480a79b](https://github.com/jetthai/vue-lazyload/commit/480a79bd09e7c215127a0fd600a7b4c0669950d7))
* issue[#72](https://github.com/jetthai/vue-lazyload/issues/72) && add webp support ([d39c28e](https://github.com/jetthai/vue-lazyload/commit/d39c28eb1f88fad798244e1a98ce252bd106b757))
* issue[#89](https://github.com/jetthai/vue-lazyload/issues/89) ([cb99bd7](https://github.com/jetthai/vue-lazyload/commit/cb99bd701943c9923480e136799f33acfcf81613))
* lazy-component destroy bug ([3cffccd](https://github.com/jetthai/vue-lazyload/commit/3cffccd9d2067168ee944d98c4b44cead190b356))
* lint error ([995ca81](https://github.com/jetthai/vue-lazyload/commit/995ca8162a9575a4c7867604d383c1daa463c02f))
* lint error ([196190c](https://github.com/jetthai/vue-lazyload/commit/196190cc334b1ff1dd6d67b357bbefc90f6bb7e8))
* listener load miss callback ([e8d35cf](https://github.com/jetthai/vue-lazyload/commit/e8d35cf64ba5399e0ca665f49be4920a7788613b))
* low version browser not support for of ([70b23b8](https://github.com/jetthai/vue-lazyload/commit/70b23b83280401648ada689017aeeac9a8b6667a))
* miss DEFAULT_PRE ([a8769da](https://github.com/jetthai/vue-lazyload/commit/a8769da3e70c16e6a3f533780284f3b9c8bed5d3))
* miss DEFAULT_PRE ([f27cb68](https://github.com/jetthai/vue-lazyload/commit/f27cb6818d652520c65c04ae964e2417ed862e7e))
* miss promiss at es5 ([c8c4e7a](https://github.com/jetthai/vue-lazyload/commit/c8c4e7acf36dbf6601d4721e93a083439d31660b))
* mode switch between event and observer ([8803615](https://github.com/jetthai/vue-lazyload/commit/880361532ee6bfed5e02b2abb71ee437e527a336))
* server side render miss window ([d03ff50](https://github.com/jetthai/vue-lazyload/commit/d03ff5020d876667f770436d25a75fc482729657))
* silent config not work bug ([c0397e1](https://github.com/jetthai/vue-lazyload/commit/c0397e1e926f2e388faadad437b97e0bbf047fb5))
* src update with data-srcset ([af49b4f](https://github.com/jetthai/vue-lazyload/commit/af49b4f4f60eab1187444b6c6d092e0a443289ed))
* ssr support ([fc238d2](https://github.com/jetthai/vue-lazyload/commit/fc238d292286713b3517f00e868572851435e45a))
* stop working with vue2.2.0 ([69b0870](https://github.com/jetthai/vue-lazyload/commit/69b08701fb65b9b2ce8a5c6250984a6b01db15fb))
* update data  bind ([f06faf2](https://github.com/jetthai/vue-lazyload/commit/f06faf2b9958b2a5f540940ea26f1f99bc9118af))
* Update dependent software ([807eee3](https://github.com/jetthai/vue-lazyload/commit/807eee37b1592112d218ae9ffa9f1e0a777d66d1))
* window is not defined in SSR ([acf6a91](https://github.com/jetthai/vue-lazyload/commit/acf6a91d41122d814d544e11859cdbe45209f7e7))
* with :style ([166a23f](https://github.com/jetthai/vue-lazyload/commit/166a23fe7ea9a823201636757cf7fd35f04de3f1))


* optimization, do not add $remove to Array.prototype, simplify code with array function (some, find) ([ca3db9e](https://github.com/jetthai/vue-lazyload/commit/ca3db9e5e3a10f78b4f630ee2cacce135108e499))
