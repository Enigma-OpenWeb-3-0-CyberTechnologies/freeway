# Changelog

## [1.6.2](https://github.com/web3-storage/freeway/compare/v1.6.1...v1.6.2) (2023-03-29)


### Bug Fixes

* update max shards values ([#29](https://github.com/web3-storage/freeway/issues/29)) ([5001b73](https://github.com/web3-storage/freeway/commit/5001b737f4da360629153a308a7b0f96123a8d44))

## [1.6.1](https://github.com/web3-storage/freeway/compare/v1.6.0...v1.6.1) (2023-03-16)


### Bug Fixes

* allow hash character in directory listings ([#27](https://github.com/web3-storage/freeway/issues/27)) ([64a678f](https://github.com/web3-storage/freeway/commit/64a678f420d9b56c0a67b78748d2915be647145f))

## [1.6.0](https://github.com/web3-storage/freeway/compare/v1.5.3...v1.6.0) (2023-03-02)


### Features

* set max number of car cids to resolve ([#24](https://github.com/web3-storage/freeway/issues/24)) ([94e65ea](https://github.com/web3-storage/freeway/commit/94e65eac9bc2375802e85ac1f1a807510c07ce7c))

## [1.5.3](https://github.com/web3-storage/freeway/compare/v1.5.2...v1.5.3) (2022-11-11)


### Bug Fixes

* better svg content type detection ([1e216bf](https://github.com/web3-storage/freeway/commit/1e216bfd6df4cbfec40235309fdcf42ae5d2fda6))

## [1.5.2](https://github.com/web3-storage/freeway/compare/v1.5.1...v1.5.2) (2022-10-21)


### Bug Fixes

* update gateway-lib to fix uri encoded paths ([a8ebe47](https://github.com/web3-storage/freeway/commit/a8ebe47d4e2711bd57170d0999bb030a74f3e421))

## [1.5.1](https://github.com/web3-storage/freeway/compare/v1.5.0...v1.5.1) (2022-10-21)


### Bug Fixes

* remove max Content-Length middleware ([#16](https://github.com/web3-storage/freeway/issues/16)) ([bf11d0c](https://github.com/web3-storage/freeway/commit/bf11d0c99f41efaf11a3869b836287fdeee28b60))

## [1.5.0](https://github.com/web3-storage/freeway/compare/v1.4.0...v1.5.0) (2022-10-20)


### Features

* use package.json version number ([4567807](https://github.com/web3-storage/freeway/commit/4567807a9ef214725606aa0a53385cd2f9fc517b))


### Bug Fixes

* content length header ([9fa30c1](https://github.com/web3-storage/freeway/commit/9fa30c1cb030e93065f3f859df3dfe4757c11fee))
* fewer log lines ([6afcb27](https://github.com/web3-storage/freeway/commit/6afcb27feab508d58d498f03c51c2918a824ba01))
* temporarily limit the size of the response until memory leak is resolved ([#15](https://github.com/web3-storage/freeway/issues/15)) ([1b04a19](https://github.com/web3-storage/freeway/commit/1b04a19846c8efa2ffe191cd7806c0775df07b19))

## [1.4.0](https://github.com/web3-storage/freeway/compare/v1.3.0...v1.4.0) (2022-10-19)


### Features

* add version header ([fcbf1ac](https://github.com/web3-storage/freeway/commit/fcbf1ac4ac2d6d4ba4351d28007d97aca11909a1))

## [1.3.0](https://github.com/web3-storage/freeway/compare/v1.2.0...v1.3.0) (2022-10-19)


### Features

* add memory budgeting ([979b13b](https://github.com/web3-storage/freeway/commit/979b13b7318ee097a3a358a055847e1c3dacd3c9))


### Bug Fixes

* cancel after releaseLock throws INVALID_STATE error ([#10](https://github.com/web3-storage/freeway/issues/10)) ([af62fe6](https://github.com/web3-storage/freeway/commit/af62fe68be5a65d8d743624e109c71fba4114c71))
* delete ref to block after resolve ([56baf25](https://github.com/web3-storage/freeway/commit/56baf25ff0d4b27acdb324f852ec217930e1e7b7))
* do not sort offsets in batch ([bbf8df5](https://github.com/web3-storage/freeway/commit/bbf8df56ad2e38d93efffda22e9655a0d80aee84))
* process one batch at a time ([d4eea8f](https://github.com/web3-storage/freeway/commit/d4eea8f5b068120c9587e06bc466dbcb067d77b5))

## [1.2.0](https://github.com/web3-storage/freeway/compare/v1.1.3...v1.2.0) (2022-10-18)


### Features

* add CDN cache ([#8](https://github.com/web3-storage/freeway/issues/8)) ([9ddf0fa](https://github.com/web3-storage/freeway/commit/9ddf0fa11dabdb174c827b95cfbf06c594529da0))

## [1.1.3](https://github.com/web3-storage/freeway/compare/v1.1.2...v1.1.3) (2022-10-17)


### Bug Fixes

* add 501 error not implemented for range requests ([#6](https://github.com/web3-storage/freeway/issues/6)) ([c13f15c](https://github.com/web3-storage/freeway/commit/c13f15c31462e29a725ec872f741eec5fc884cb1))

## [1.1.2](https://github.com/web3-storage/freeway/compare/v1.1.1...v1.1.2) (2022-10-17)


### Bug Fixes

* pass data bucket and index bucket to blockstore ([ead11a3](https://github.com/web3-storage/freeway/commit/ead11a37233963c941d08782df340de1901ac06c))
* resolve batch when missing response ([cb91670](https://github.com/web3-storage/freeway/commit/cb916708bef975bfe7dc46aabe7fb34a3d28b1d9))

## [1.1.1](https://github.com/web3-storage/freeway/compare/v1.1.0...v1.1.1) (2022-10-17)


### Bug Fixes

* only create batching blockstore if not reading whole CAR into memory ([b748b6a](https://github.com/web3-storage/freeway/commit/b748b6a87b22fecb14787ed8bb1734875676e503))

## [1.1.0](https://github.com/web3-storage/freeway/compare/v1.0.0...v1.1.0) (2022-10-17)


### Features

* use DUDEWHERE bucket ([a291852](https://github.com/web3-storage/freeway/commit/a2918521856e450e14dbb7b4ee3491c7aa37d73c))
* use satnav bucket ([10ea5cc](https://github.com/web3-storage/freeway/commit/10ea5ccbb43330af602a90d89286644f9e064bdf))

## 1.0.0 (2022-10-13)


### Features

* add handlers for CAR and block ([2d24706](https://github.com/web3-storage/freeway/commit/2d2470600e9b188876c2d9efc221382ba681be83))
* add sharded directories support ([b0fecc4](https://github.com/web3-storage/freeway/commit/b0fecc44a500e6e037ecbbe1ec48806e301fc610))
* block batching ([#1](https://github.com/web3-storage/freeway/issues/1)) ([c0a35e4](https://github.com/web3-storage/freeway/commit/c0a35e4e26f7e9c8e9846b6190463ce6bbbc9745))
* detection for text content (when no filename) ([f8b9d1a](https://github.com/web3-storage/freeway/commit/f8b9d1a0b9b8b3a89e553b4852f4708c9cdd8671))
* initial commit ([f3e5147](https://github.com/web3-storage/freeway/commit/f3e5147384142ee972c394eae094ee920c3862b4))


### Bug Fixes

* bump down max bytes in memory ([17d7fef](https://github.com/web3-storage/freeway/commit/17d7fefa3d68143d037e6c7a7cedf5e14c6ef93e))
* handle error building index ([e2c1ca2](https://github.com/web3-storage/freeway/commit/e2c1ca2e09f2f61de6d337fa3ee0507dae8e255e))
* propogate index build error ([fd6135b](https://github.com/web3-storage/freeway/commit/fd6135b7e07513b1c680467c6b7fcf34267e7fbf))
