# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## 11.0.0 (2026-07-13)


### ⚠ BREAKING CHANGES

* move to krakenjs scope (#395)

### Features

* add events on prerender start and finish ([#403](https://github.com/gigaphoton/zoid/issues/403)) ([c603048](https://github.com/gigaphoton/zoid/commit/c6030488dcbb4bb182b630acf722b6a8bbafc5dd))
* **bridge:** allow bridgeUrl to be a function ([#314](https://github.com/gigaphoton/zoid/issues/314)) ([554c6de](https://github.com/gigaphoton/zoid/commit/554c6de3a19960dc9e71188787da720d1cbd166b))
* **sourcemap:** Add Source maps ([#55](https://github.com/gigaphoton/zoid/issues/55)) ([9a30424](https://github.com/gigaphoton/zoid/commit/9a3042441b1232b18b280ab447f6d5426987e075))
* upgrade to grumbler scripts 8 ([#414](https://github.com/gigaphoton/zoid/issues/414)) ([b857e89](https://github.com/gigaphoton/zoid/commit/b857e8930e76ebae77d755f5e9e0f5ac432a5790))
* **validate-call-onerror:** Calling `onError` prop, if it exists, if prop validation throws an error ([#189](https://github.com/gigaphoton/zoid/issues/189)) ([f707e15](https://github.com/gigaphoton/zoid/commit/f707e15a5535fbf83d4f51a0d82aa1c4dd5d0f37))
* **venmo:** allow trusted domains ([#439](https://github.com/gigaphoton/zoid/issues/439)) ([5f3bf00](https://github.com/gigaphoton/zoid/commit/5f3bf00a08715154ff110023f0a1b862d560670e))


### Bug Fixes

* avoid throwing errors if container is no longer in page ([#424](https://github.com/gigaphoton/zoid/issues/424)) ([e2825bb](https://github.com/gigaphoton/zoid/commit/e2825bb5e08eadde14e8fc7b6b76d9069c5a3daf))
* **ci:** bump flow-typed to ^4.1.1 to fix cold-cache libdef parse failure ([b45d8d5](https://github.com/gigaphoton/zoid/commit/b45d8d5b4b9d23c922b92b5f7c528fef3f8bf106))
* **ci:** use babel 7 commonjs plugin and declare it explicitly ([a84a29a](https://github.com/gigaphoton/zoid/commit/a84a29ae9544d97f8701e8d12ece1c6cf9d883d3))
* **getter:** Log on execute ([#56](https://github.com/gigaphoton/zoid/issues/56)) ([1d81fb2](https://github.com/gigaphoton/zoid/commit/1d81fb2d959ecaa1ff88da54b377f8dc02a62348))
* only throw errors for major version changes ([#425](https://github.com/gigaphoton/zoid/issues/425)) ([57e8989](https://github.com/gigaphoton/zoid/commit/57e8989fedf94ea1e1084827acc21fedfad6e267))
* **prop:** trusted domain ([#440](https://github.com/gigaphoton/zoid/issues/440)) ([081d0d5](https://github.com/gigaphoton/zoid/commit/081d0d5a77bbd496284ef9e138f353a4386b6ee8))
* reduce frequency of "Detected iframe close" error ([#426](https://github.com/gigaphoton/zoid/issues/426)) ([5343277](https://github.com/gigaphoton/zoid/commit/53432775742a56aad8377c84258ec8d7a17d0450))
* specify dimensions in iframe demo ([#375](https://github.com/gigaphoton/zoid/issues/375)) ([a4c1564](https://github.com/gigaphoton/zoid/commit/a4c1564249dd76102276a77e936164816eb7563a))


* add tests related to zoid prop usage in the wild ([#379](https://github.com/gigaphoton/zoid/issues/379)) ([88e972d](https://github.com/gigaphoton/zoid/commit/88e972d211978f97f016262afccf44de3fc85488))
* **docs:** update github actions badge url ([#419](https://github.com/gigaphoton/zoid/issues/419)) ([31d59fb](https://github.com/gigaphoton/zoid/commit/31d59fbd1c89697e3773a5f043a506c95ee009a5))
* **docs:** update npm badge ([#437](https://github.com/gigaphoton/zoid/issues/437)) ([2ef6fdb](https://github.com/gigaphoton/zoid/commit/2ef6fdb4efeeecdbbe446623cf45650499d598fa))
* drop unpinned third-party action from publish workflow ([570b68b](https://github.com/gigaphoton/zoid/commit/570b68bd118153648694757897976c7b83fbb416))
* fix build badge ([eb8677a](https://github.com/gigaphoton/zoid/commit/eb8677a3c41f8ad52158ad946573d0df9a47538d))
* fix snippet syntax error ([#231](https://github.com/gigaphoton/zoid/issues/231)) ([7b0c9e1](https://github.com/gigaphoton/zoid/commit/7b0c9e1d8db1659db1b8887d35370c82b3448a59))
* fix typos in parent-props and xprops docs ([#408](https://github.com/gigaphoton/zoid/issues/408)) ([2fe2858](https://github.com/gigaphoton/zoid/commit/2fe28584d75f9f740ec7a6d162b8d775c9cf39a0))
* move devDependencies to [@krakenjs](https://github.com/krakenjs) scope ([#400](https://github.com/gigaphoton/zoid/issues/400)) ([a085f40](https://github.com/gigaphoton/zoid/commit/a085f408ff4f20d95f22ab5b44acb490038c33d7))
* move to krakenjs scope ([#395](https://github.com/gigaphoton/zoid/issues/395)) ([c10ac41](https://github.com/gigaphoton/zoid/commit/c10ac415ce6a2174c7ef08f2451da95bb9795888))
* **package:** Adding belter as a direct dependency ([#214](https://github.com/gigaphoton/zoid/issues/214)) ([e4de508](https://github.com/gigaphoton/zoid/commit/e4de508f7a162e65f099b79f79b6451c22807d6d))
* publish to GitHub Packages under [@gigaphoton](https://github.com/gigaphoton) scope ([8e4c73c](https://github.com/gigaphoton/zoid/commit/8e4c73c1b19c23e02bc5fb57b0459626e8627063))
* **release:** 10.0.0 ([25c3629](https://github.com/gigaphoton/zoid/commit/25c36292cc46bceb3a9e713c81c8f9e313a25431))
* **release:** 10.1.0 ([2f1ea97](https://github.com/gigaphoton/zoid/commit/2f1ea97635fe1741747f9136b1cb2d908116b6da))
* **release:** 10.2.0 ([a2b12c8](https://github.com/gigaphoton/zoid/commit/a2b12c80f31fe2942726e42b96761b82387fb839))
* **release:** 10.2.1 ([ed6e6dc](https://github.com/gigaphoton/zoid/commit/ed6e6dc8cddfde815b4c4dd8805a3b96e2a830f6))
* **release:** 10.2.2 ([16318c7](https://github.com/gigaphoton/zoid/commit/16318c785a501048c4fe0ff77042e0b6d6ebf81d))
* **release:** 10.2.3 ([ad49c72](https://github.com/gigaphoton/zoid/commit/ad49c727d2c2e047fde41ad2e38ed30ec02e2002))
* **release:** 10.2.4 ([8e0a48b](https://github.com/gigaphoton/zoid/commit/8e0a48b1e69d403f1e96091eee8bf24f97cd214a))
* **release:** 10.3.0 ([004c8f5](https://github.com/gigaphoton/zoid/commit/004c8f53df97c3b4a929ea722781e639588c3aba))
* **release:** 10.3.1 ([3b6f24b](https://github.com/gigaphoton/zoid/commit/3b6f24b4051e3fdb1de9a0ab2fdd3e78e0b1a72a))
* remove token from publish action ([#422](https://github.com/gigaphoton/zoid/issues/422)) ([3c6fa18](https://github.com/gigaphoton/zoid/commit/3c6fa180c564b248d0e1b2ed66a2eaef8e2527e6))
* standardize configs ([7504244](https://github.com/gigaphoton/zoid/commit/7504244fe9c856a74e210008ed5fac00d2bf114d))
* update babel config ([#418](https://github.com/gigaphoton/zoid/issues/418)) ([2657252](https://github.com/gigaphoton/zoid/commit/2657252085d401d64740fc3c8b372f085705bbf6))
* use prettier ([#401](https://github.com/gigaphoton/zoid/issues/401)) ([3974c52](https://github.com/gigaphoton/zoid/commit/3974c52a880e8b7a72201c9ad205b576611e7c65))

### [10.3.1](https://github.com/krakenjs/zoid/compare/v10.3.0...v10.3.1) (2023-06-13)


### Bug Fixes

* **prop:** trusted domain ([#440](https://github.com/krakenjs/zoid/issues/440)) ([081d0d5](https://github.com/krakenjs/zoid/commit/081d0d5a77bbd496284ef9e138f353a4386b6ee8))

## [10.3.0](https://github.com/krakenjs/zoid/compare/v10.2.4...v10.3.0) (2023-06-12)


### Features

* **venmo:** allow trusted domains ([#439](https://github.com/krakenjs/zoid/issues/439)) ([5f3bf00](https://github.com/krakenjs/zoid/commit/5f3bf00a08715154ff110023f0a1b862d560670e))


* **docs:** update npm badge ([#437](https://github.com/krakenjs/zoid/issues/437)) ([2ef6fdb](https://github.com/krakenjs/zoid/commit/2ef6fdb4efeeecdbbe446623cf45650499d598fa))

### [10.2.4](https://github.com/krakenjs/zoid/compare/v10.2.3...v10.2.4) (2023-05-22)

### [10.2.3](https://github.com/krakenjs/zoid/compare/v10.2.2...v10.2.3) (2023-05-03)

### [10.2.2](https://github.com/krakenjs/zoid/compare/v10.2.1...v10.2.2) (2023-05-01)


### Bug Fixes

* reduce frequency of "Detected iframe close" error ([#426](https://github.com/krakenjs/zoid/issues/426)) ([5343277](https://github.com/krakenjs/zoid/commit/53432775742a56aad8377c84258ec8d7a17d0450))

### [10.2.1](https://github.com/krakenjs/zoid/compare/v10.2.0...v10.2.1) (2023-04-25)


### Bug Fixes

* only throw errors for major version changes ([#425](https://github.com/krakenjs/zoid/issues/425)) ([57e8989](https://github.com/krakenjs/zoid/commit/57e8989fedf94ea1e1084827acc21fedfad6e267))

## [10.2.0](https://github.com/krakenjs/zoid/compare/v10.1.0...v10.2.0) (2023-04-24)


### Features

* upgrade to grumbler scripts 8 ([#414](https://github.com/krakenjs/zoid/issues/414)) ([b857e89](https://github.com/krakenjs/zoid/commit/b857e8930e76ebae77d755f5e9e0f5ac432a5790))


### Bug Fixes

* avoid throwing errors if container is no longer in page ([#424](https://github.com/krakenjs/zoid/issues/424)) ([e2825bb](https://github.com/krakenjs/zoid/commit/e2825bb5e08eadde14e8fc7b6b76d9069c5a3daf))


* **docs:** update github actions badge url ([#419](https://github.com/krakenjs/zoid/issues/419)) ([31d59fb](https://github.com/krakenjs/zoid/commit/31d59fbd1c89697e3773a5f043a506c95ee009a5))
* fix typos in parent-props and xprops docs ([#408](https://github.com/krakenjs/zoid/issues/408)) ([2fe2858](https://github.com/krakenjs/zoid/commit/2fe28584d75f9f740ec7a6d162b8d775c9cf39a0))
* remove token from publish action ([#422](https://github.com/krakenjs/zoid/issues/422)) ([3c6fa18](https://github.com/krakenjs/zoid/commit/3c6fa180c564b248d0e1b2ed66a2eaef8e2527e6))
* update babel config ([#418](https://github.com/krakenjs/zoid/issues/418)) ([2657252](https://github.com/krakenjs/zoid/commit/2657252085d401d64740fc3c8b372f085705bbf6))
* use prettier ([#401](https://github.com/krakenjs/zoid/issues/401)) ([3974c52](https://github.com/krakenjs/zoid/commit/3974c52a880e8b7a72201c9ad205b576611e7c65))

## [10.1.0](https://github.com/krakenjs/zoid/compare/v10.0.0...v10.1.0) (2022-05-03)


### Features

* add events on prerender start and finish ([#403](https://github.com/krakenjs/zoid/issues/403)) ([c603048](https://github.com/krakenjs/zoid/commit/c6030488dcbb4bb182b630acf722b6a8bbafc5dd))


* move devDependencies to [@krakenjs](https://github.com/krakenjs) scope ([#400](https://github.com/krakenjs/zoid/issues/400)) ([a085f40](https://github.com/krakenjs/zoid/commit/a085f408ff4f20d95f22ab5b44acb490038c33d7))

## [10.0.0](https://github.com/krakenjs/zoid/compare/v9.0.87...v10.0.0) (2022-03-01)


### ⚠ BREAKING CHANGES

* move to krakenjs scope (#395)

* fix build badge ([eb8677a](https://github.com/krakenjs/zoid/commit/eb8677a3c41f8ad52158ad946573d0df9a47538d))
* move to krakenjs scope ([#395](https://github.com/krakenjs/zoid/issues/395)) ([c10ac41](https://github.com/krakenjs/zoid/commit/c10ac415ce6a2174c7ef08f2451da95bb9795888))
* standardize configs ([7504244](https://github.com/krakenjs/zoid/commit/7504244fe9c856a74e210008ed5fac00d2bf114d))
