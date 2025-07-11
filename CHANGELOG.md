# Changelog

## [0.7.1](https://github.com/jakepage91/hello-distr/compare/0.7.0...0.7.1) (2025-07-08)


### Bug Fixes

* replace invalid ENTRYPOINT with proper CMD in Dockerfiles ([8f1c49f](https://github.com/jakepage91/hello-distr/commit/8f1c49fa07cf94adf004dbf3a697fd6bc918fe5b))

## [0.7.0](https://github.com/jakepage91/hello-distr/compare/0.6.0...0.7.0) (2025-07-08)


### Features

* update container configurations and deployment manifests ([ec67837](https://github.com/jakepage91/hello-distr/commit/ec6783710501e299632710b14202740b1e32bd8e))

## [0.6.0](https://github.com/jakepage91/hello-distr/compare/0.5.2...0.6.0) (2025-07-07)


### Features

* add health check endpoint for production monitoring ([a695541](https://github.com/jakepage91/hello-distr/commit/a695541e63d099ab0d3173225e58469c70d095f5))

## [0.5.2](https://github.com/jakepage91/hello-distr/compare/0.5.1...0.5.2) (2025-07-07)


### Bug Fixes

* ensure Docker images are built on every release tag ([23abc86](https://github.com/jakepage91/hello-distr/commit/23abc865fb1f2255eee304dd444d95c89f7c2e15))

## [0.5.1](https://github.com/jakepage91/hello-distr/compare/0.5.0...0.5.1) (2025-07-07)


### Bug Fixes

* add missing DB environment variables to shared-env section ([4709e63](https://github.com/jakepage91/hello-distr/commit/4709e631802a80cfacd43d062a15bd56d83fcd14))
* correct Dockerfile entrypoints and backend database configuration ([d791d34](https://github.com/jakepage91/hello-distr/commit/d791d34cb2500432536349fb5eac04a330f41358))
* trigger a new release ([c148e8c](https://github.com/jakepage91/hello-distr/commit/c148e8c4543383c4c04525453a3d3759b292518d))

## [0.5.0](https://github.com/jakepage91/hello-distr/compare/0.4.0...0.5.0) (2025-07-07)


### Features

* trigger release-please for new version ([4c4aaf7](https://github.com/jakepage91/hello-distr/commit/4c4aaf79862fd540648734afd087d293925c9f85))

## [0.4.0](https://github.com/jakepage91/hello-distr/compare/0.3.1...0.4.0) (2025-07-02)


### Features

* introduce database connection error for demo ([fd6347d](https://github.com/jakepage91/hello-distr/commit/fd6347dacc1f8ad17f0709f0443d4dd163e9af62))

## [0.3.1](https://github.com/jakepage91/hello-distr/compare/0.3.0...0.3.1) (2025-07-01)


### Bug Fixes

* remove matrix strategy from push-distr workflow ([0f8d65e](https://github.com/jakepage91/hello-distr/commit/0f8d65eeb3be01074b3a778d45c6f220fb877cf7))


### Docs

* add setup completion note ([b1692d9](https://github.com/jakepage91/hello-distr/commit/b1692d92c96e2eb03886d84447dff5f079131e88))

## [0.3.0](https://github.com/jakepage91/hello-distr/compare/0.2.2...0.3.0) (2025-07-01)


### Features

* update Docker registry paths and revert push-distr workflow ([d498e53](https://github.com/jakepage91/hello-distr/commit/d498e5323c736e78a50dee929cd3c0482fccce44))
* update docker-compose to use jakepage91 registry ([ab237dd](https://github.com/jakepage91/hello-distr/commit/ab237dd65bb061db34a49f503be817654a62e3ed))


### Bug Fixes

* simplify push-distr workflow to resolve variable reference issue ([7f6c78e](https://github.com/jakepage91/hello-distr/commit/7f6c78e0d20744666cba51929c320a1a61c4231b))

## [0.2.2](https://github.com/jakepage91/hello-distr/compare/0.2.1...0.2.2) (2025-07-01)


### Bug Fixes

* remove duplicate matrix entry in push-distr workflow ([fceb657](https://github.com/jakepage91/hello-distr/commit/fceb6573573d1fbc3d0a1b1d440b7fd106bee52c))

## [0.2.1](https://github.com/jakepage91/hello-distr/compare/0.2.0...0.2.1) (2025-07-01)


### Docs

* update README to reflect production distr API usage ([35ea64b](https://github.com/jakepage91/hello-distr/commit/35ea64bb70b94ff1aa9caec019354c6707ef32a6))

## [0.2.0](https://github.com/jakepage91/hello-distr/compare/0.1.10...0.2.0) (2025-07-01)


### Features

* add backend and proxy for prod deployment ([#12](https://github.com/jakepage91/hello-distr/issues/12)) ([22b9f3f](https://github.com/jakepage91/hello-distr/commit/22b9f3fb53043a6388a4b63867f018265778a53f))
* add frontend ([#1](https://github.com/jakepage91/hello-distr/issues/1)) ([5f7d78d](https://github.com/jakepage91/hello-distr/commit/5f7d78dbb2b1bde3befdfbb881de56d3db049f0a))


### Bug Fixes

* **ci:** deploy compose file name ([#26](https://github.com/jakepage91/hello-distr/issues/26)) ([70544ac](https://github.com/jakepage91/hello-distr/commit/70544ac499394831fa269893c018442879e67667))
* **ci:** deploy compose file name in release please config ([#28](https://github.com/jakepage91/hello-distr/issues/28)) ([7007944](https://github.com/jakepage91/hello-distr/commit/70079445c218c26792b45b29d1bc6275ac7c9c7e))
* **deps:** update dependency @heroui/button to v2.2.15 ([#55](https://github.com/jakepage91/hello-distr/issues/55)) ([6cbac86](https://github.com/jakepage91/hello-distr/commit/6cbac86d4940759d53ed11a5626780f6ffbb334f))
* **deps:** update dependency @heroui/button to v2.2.16 ([#83](https://github.com/jakepage91/hello-distr/issues/83)) ([04cc1f4](https://github.com/jakepage91/hello-distr/commit/04cc1f4352481235c7d27895f33937f56ed512eb))
* **deps:** update dependency @heroui/button to v2.2.17 ([#132](https://github.com/jakepage91/hello-distr/issues/132)) ([8c3d09c](https://github.com/jakepage91/hello-distr/commit/8c3d09c5741d40770bd0c2ea0ceeaeb389dc30a3))
* **deps:** update dependency @heroui/button to v2.2.19 ([#171](https://github.com/jakepage91/hello-distr/issues/171)) ([91c4e92](https://github.com/jakepage91/hello-distr/commit/91c4e92131351d6baa5d6bf24a3ad07357c9aaa7))
* **deps:** update dependency @heroui/button to v2.2.20 ([#231](https://github.com/jakepage91/hello-distr/issues/231)) ([a711403](https://github.com/jakepage91/hello-distr/commit/a71140312a88c556202022ee8bbc86f20866cc3d))
* **deps:** update dependency @heroui/button to v2.2.21 ([#248](https://github.com/jakepage91/hello-distr/issues/248)) ([bc78156](https://github.com/jakepage91/hello-distr/commit/bc7815627988933b7a9309c3cd246d74f23fefea))
* **deps:** update dependency @heroui/button to v2.2.22 ([#277](https://github.com/jakepage91/hello-distr/issues/277)) ([cbe04b3](https://github.com/jakepage91/hello-distr/commit/cbe04b3e8f7bbbb70cc991154b37a72475b96016))
* **deps:** update dependency @heroui/code to v2.2.11 ([#56](https://github.com/jakepage91/hello-distr/issues/56)) ([76d7183](https://github.com/jakepage91/hello-distr/commit/76d7183e952345770e8a331bfd7ea9d86affd285))
* **deps:** update dependency @heroui/code to v2.2.12 ([#84](https://github.com/jakepage91/hello-distr/issues/84)) ([9a54727](https://github.com/jakepage91/hello-distr/commit/9a54727d2aa3c6038f0102c93efa6d84d6ff1b8c))
* **deps:** update dependency @heroui/code to v2.2.14 ([#172](https://github.com/jakepage91/hello-distr/issues/172)) ([272cb54](https://github.com/jakepage91/hello-distr/commit/272cb540fe05adc4ce2118e9135fe62daeee6121))
* **deps:** update dependency @heroui/code to v2.2.15 ([#232](https://github.com/jakepage91/hello-distr/issues/232)) ([0b0a9bd](https://github.com/jakepage91/hello-distr/commit/0b0a9bd92f779d1a4c760fe479ce52e28956653b))
* **deps:** update dependency @heroui/code to v2.2.16 ([#249](https://github.com/jakepage91/hello-distr/issues/249)) ([96570e4](https://github.com/jakepage91/hello-distr/commit/96570e4255ba91260c1577d28a537ad365b26649))
* **deps:** update dependency @heroui/input to v2.4.15 ([#57](https://github.com/jakepage91/hello-distr/issues/57)) ([390a3c2](https://github.com/jakepage91/hello-distr/commit/390a3c2b57a547c7e825f52aac5c69a79d4e80d0))
* **deps:** update dependency @heroui/input to v2.4.16 ([#85](https://github.com/jakepage91/hello-distr/issues/85)) ([2d00276](https://github.com/jakepage91/hello-distr/commit/2d002768f142c1009e6a49e0d556ef95cfc041bb))
* **deps:** update dependency @heroui/input to v2.4.17 ([#133](https://github.com/jakepage91/hello-distr/issues/133)) ([389a515](https://github.com/jakepage91/hello-distr/commit/389a51577dcad8cf0294fbcad91531b44ebcbcbe))
* **deps:** update dependency @heroui/input to v2.4.19 ([#173](https://github.com/jakepage91/hello-distr/issues/173)) ([45f97fe](https://github.com/jakepage91/hello-distr/commit/45f97fe8a842a82d9c129bed317dfdab8db4c116))
* **deps:** update dependency @heroui/input to v2.4.20 ([#233](https://github.com/jakepage91/hello-distr/issues/233)) ([3906a58](https://github.com/jakepage91/hello-distr/commit/3906a58ada60d286e1887c82326f2a04ee7cdcf1))
* **deps:** update dependency @heroui/input to v2.4.21 ([#251](https://github.com/jakepage91/hello-distr/issues/251)) ([bba7845](https://github.com/jakepage91/hello-distr/commit/bba7845068ead9babd3fbbf32367ac5c398640d1))
* **deps:** update dependency @heroui/input to v2.4.22 ([#278](https://github.com/jakepage91/hello-distr/issues/278)) ([5b54562](https://github.com/jakepage91/hello-distr/commit/5b54562e6d78d017dc5e016f2b85176ea1aabccb))
* **deps:** update dependency @heroui/kbd to v2.2.11 ([#58](https://github.com/jakepage91/hello-distr/issues/58)) ([a0353bb](https://github.com/jakepage91/hello-distr/commit/a0353bb0e1495da0b0f49f85f3c03fd15ff8c21f))
* **deps:** update dependency @heroui/kbd to v2.2.12 ([#86](https://github.com/jakepage91/hello-distr/issues/86)) ([895ca17](https://github.com/jakepage91/hello-distr/commit/895ca177caac049ea1d9285ab207f2ce87e662a1))
* **deps:** update dependency @heroui/kbd to v2.2.13 ([#134](https://github.com/jakepage91/hello-distr/issues/134)) ([b3415dd](https://github.com/jakepage91/hello-distr/commit/b3415dd93d299721c4ee570a81c6a34ab081f25a))
* **deps:** update dependency @heroui/kbd to v2.2.15 ([#174](https://github.com/jakepage91/hello-distr/issues/174)) ([d682891](https://github.com/jakepage91/hello-distr/commit/d682891dfa1d6cb7bc7831b9649c6f419391ae7d))
* **deps:** update dependency @heroui/kbd to v2.2.16 ([#234](https://github.com/jakepage91/hello-distr/issues/234)) ([1265c1e](https://github.com/jakepage91/hello-distr/commit/1265c1ec763eedfb94fbc4cbeb2717839898699f))
* **deps:** update dependency @heroui/kbd to v2.2.17 ([#253](https://github.com/jakepage91/hello-distr/issues/253)) ([b72904f](https://github.com/jakepage91/hello-distr/commit/b72904fb187e9bc2be1d74264d830a77b0495b24))
* **deps:** update dependency @heroui/link to v2.2.12 ([#59](https://github.com/jakepage91/hello-distr/issues/59)) ([e76577c](https://github.com/jakepage91/hello-distr/commit/e76577cb21e30df5174c34e550e7c113d0226f2a))
* **deps:** update dependency @heroui/link to v2.2.13 ([#87](https://github.com/jakepage91/hello-distr/issues/87)) ([7f3bb25](https://github.com/jakepage91/hello-distr/commit/7f3bb256d4e069a49e715089dc0a49a1c2862068))
* **deps:** update dependency @heroui/link to v2.2.14 ([#135](https://github.com/jakepage91/hello-distr/issues/135)) ([76371fa](https://github.com/jakepage91/hello-distr/commit/76371fa659ead54adee78ceac482e187aa45f44c))
* **deps:** update dependency @heroui/link to v2.2.16 ([#175](https://github.com/jakepage91/hello-distr/issues/175)) ([cb7e366](https://github.com/jakepage91/hello-distr/commit/cb7e366f9e59e0aa44817c9637b396d6abfc28b2))
* **deps:** update dependency @heroui/link to v2.2.17 ([#235](https://github.com/jakepage91/hello-distr/issues/235)) ([97cf4df](https://github.com/jakepage91/hello-distr/commit/97cf4df8275d142ed691143f96841de89b2d7ba9))
* **deps:** update dependency @heroui/link to v2.2.18 ([#254](https://github.com/jakepage91/hello-distr/issues/254)) ([46c96dc](https://github.com/jakepage91/hello-distr/commit/46c96dcb1c1ac80121927b3fc5c23dea6ff1d886))
* **deps:** update dependency @heroui/link to v2.2.19 ([#279](https://github.com/jakepage91/hello-distr/issues/279)) ([f5719c7](https://github.com/jakepage91/hello-distr/commit/f5719c7e325fb4b86e2e0b46b0fb7b9ba4b4d281))
* **deps:** update dependency @heroui/listbox to v2.3.14 ([#60](https://github.com/jakepage91/hello-distr/issues/60)) ([3e161d7](https://github.com/jakepage91/hello-distr/commit/3e161d7b56cf29fc1a3319adcbae4580844bcc39))
* **deps:** update dependency @heroui/listbox to v2.3.15 ([#88](https://github.com/jakepage91/hello-distr/issues/88)) ([45eb8f6](https://github.com/jakepage91/hello-distr/commit/45eb8f688a6e02c5a684db41de0c2c25771dc562))
* **deps:** update dependency @heroui/listbox to v2.3.16 ([#136](https://github.com/jakepage91/hello-distr/issues/136)) ([fd6c1f0](https://github.com/jakepage91/hello-distr/commit/fd6c1f04ac5fba5b5d3bd77c39247ddc69928482))
* **deps:** update dependency @heroui/listbox to v2.3.18 ([#176](https://github.com/jakepage91/hello-distr/issues/176)) ([7abe446](https://github.com/jakepage91/hello-distr/commit/7abe446376f9e66cf8aa7623262d933bbc2b460b))
* **deps:** update dependency @heroui/listbox to v2.3.19 ([#236](https://github.com/jakepage91/hello-distr/issues/236)) ([539e8fc](https://github.com/jakepage91/hello-distr/commit/539e8fc1decedcf0bc67cd4e01d669521f090c73))
* **deps:** update dependency @heroui/listbox to v2.3.20 ([#255](https://github.com/jakepage91/hello-distr/issues/255)) ([164609f](https://github.com/jakepage91/hello-distr/commit/164609ff96c38745f9d80f883b8e13f30d555c52))
* **deps:** update dependency @heroui/listbox to v2.3.21 ([#280](https://github.com/jakepage91/hello-distr/issues/280)) ([4302aad](https://github.com/jakepage91/hello-distr/commit/4302aad9d953dded9223f07044beb9c930c25c39))
* **deps:** update dependency @heroui/navbar to v2.2.13 ([#61](https://github.com/jakepage91/hello-distr/issues/61)) ([f949c71](https://github.com/jakepage91/hello-distr/commit/f949c711e497b4f7cea13c0e5ae1782a7dedc316))
* **deps:** update dependency @heroui/navbar to v2.2.14 ([#89](https://github.com/jakepage91/hello-distr/issues/89)) ([dfba164](https://github.com/jakepage91/hello-distr/commit/dfba16463cb0513804de8962052f52ba44584388))
* **deps:** update dependency @heroui/navbar to v2.2.15 ([#137](https://github.com/jakepage91/hello-distr/issues/137)) ([727256c](https://github.com/jakepage91/hello-distr/commit/727256c22bfd4713473beb1de597bf6873b8fd53))
* **deps:** update dependency @heroui/navbar to v2.2.17 ([#177](https://github.com/jakepage91/hello-distr/issues/177)) ([9588bac](https://github.com/jakepage91/hello-distr/commit/9588bac90d578fe35895e0ff2c46123c104e22c6))
* **deps:** update dependency @heroui/navbar to v2.2.18 ([#237](https://github.com/jakepage91/hello-distr/issues/237)) ([c9994ca](https://github.com/jakepage91/hello-distr/commit/c9994ca2fa0e933060e26a126f8e70c628976495))
* **deps:** update dependency @heroui/navbar to v2.2.19 ([#256](https://github.com/jakepage91/hello-distr/issues/256)) ([01ab23e](https://github.com/jakepage91/hello-distr/commit/01ab23ed8149d9ab092cc828c9a6c16c8d43c11a))
* **deps:** update dependency @heroui/navbar to v2.2.20 ([#281](https://github.com/jakepage91/hello-distr/issues/281)) ([c39a7b7](https://github.com/jakepage91/hello-distr/commit/c39a7b721033e8614b7f45f8e7dbaf23a525535f))
* **deps:** update dependency @heroui/snippet to v2.2.16 ([#62](https://github.com/jakepage91/hello-distr/issues/62)) ([0bbc68d](https://github.com/jakepage91/hello-distr/commit/0bbc68d145fd9c5c897a7db893cefede79604f3a))
* **deps:** update dependency @heroui/snippet to v2.2.17 ([#90](https://github.com/jakepage91/hello-distr/issues/90)) ([0516690](https://github.com/jakepage91/hello-distr/commit/0516690b7eabb6dc41634bf5e6fac9d1f789e358))
* **deps:** update dependency @heroui/snippet to v2.2.18 ([#138](https://github.com/jakepage91/hello-distr/issues/138)) ([8ec068f](https://github.com/jakepage91/hello-distr/commit/8ec068f95fc76704d4bbaffe5ae7455106045cf6))
* **deps:** update dependency @heroui/snippet to v2.2.20 ([#178](https://github.com/jakepage91/hello-distr/issues/178)) ([3a502fb](https://github.com/jakepage91/hello-distr/commit/3a502fb436013c931158420a486e95657707e978))
* **deps:** update dependency @heroui/snippet to v2.2.21 ([#238](https://github.com/jakepage91/hello-distr/issues/238)) ([03d8563](https://github.com/jakepage91/hello-distr/commit/03d85632ce2e20f3b81f83203246a96ee4674f93))
* **deps:** update dependency @heroui/snippet to v2.2.22 ([#257](https://github.com/jakepage91/hello-distr/issues/257)) ([ba2ec50](https://github.com/jakepage91/hello-distr/commit/ba2ec50701ac3d3b698a8573c0d40131ace25906))
* **deps:** update dependency @heroui/snippet to v2.2.23 ([#282](https://github.com/jakepage91/hello-distr/issues/282)) ([2e38156](https://github.com/jakepage91/hello-distr/commit/2e38156fa52d471ec04bd13883a3f2ba8a8d858f))
* **deps:** update dependency @heroui/switch to v2.2.13 ([#64](https://github.com/jakepage91/hello-distr/issues/64)) ([9b97939](https://github.com/jakepage91/hello-distr/commit/9b979391dc7f11b8104a6675f2fa2151e7fd95af))
* **deps:** update dependency @heroui/switch to v2.2.14 ([#91](https://github.com/jakepage91/hello-distr/issues/91)) ([25525fa](https://github.com/jakepage91/hello-distr/commit/25525faef2a346884da5ff1bcfcbc9727b8969c7))
* **deps:** update dependency @heroui/switch to v2.2.15 ([#139](https://github.com/jakepage91/hello-distr/issues/139)) ([d73e55c](https://github.com/jakepage91/hello-distr/commit/d73e55c9b687e188551554c487687c175564f0bf))
* **deps:** update dependency @heroui/switch to v2.2.17 ([#179](https://github.com/jakepage91/hello-distr/issues/179)) ([ab96d1c](https://github.com/jakepage91/hello-distr/commit/ab96d1c095dfa989254dce21c4165b0240318200))
* **deps:** update dependency @heroui/switch to v2.2.18 ([#239](https://github.com/jakepage91/hello-distr/issues/239)) ([b4dc925](https://github.com/jakepage91/hello-distr/commit/b4dc92577ca7cd99be5d606df2fbd477f6127561))
* **deps:** update dependency @heroui/switch to v2.2.19 ([#258](https://github.com/jakepage91/hello-distr/issues/258)) ([8db0d6a](https://github.com/jakepage91/hello-distr/commit/8db0d6a9911147d53ead2281f7b5ceafb5ae9b85))
* **deps:** update dependency @heroui/switch to v2.2.20 ([#283](https://github.com/jakepage91/hello-distr/issues/283)) ([54beb11](https://github.com/jakepage91/hello-distr/commit/54beb119344f37046ab406967d81eadd7ab61f7f))
* **deps:** update dependency @heroui/system to v2.4.11 ([#65](https://github.com/jakepage91/hello-distr/issues/65)) ([cd64328](https://github.com/jakepage91/hello-distr/commit/cd643283f6b326e54e866bfb41e98cdfbc15ad16))
* **deps:** update dependency @heroui/system to v2.4.12 ([#92](https://github.com/jakepage91/hello-distr/issues/92)) ([a299044](https://github.com/jakepage91/hello-distr/commit/a299044a2f6ae8a857c0f995620de4f3ed02b5ee))
* **deps:** update dependency @heroui/system to v2.4.13 ([#140](https://github.com/jakepage91/hello-distr/issues/140)) ([22c5b37](https://github.com/jakepage91/hello-distr/commit/22c5b37d4d30aa561fe59983033f874802acba10))
* **deps:** update dependency @heroui/system to v2.4.15 ([#180](https://github.com/jakepage91/hello-distr/issues/180)) ([5033d4d](https://github.com/jakepage91/hello-distr/commit/5033d4d3fef18031dfe23faf259f53f1ea54ca5e))
* **deps:** update dependency @heroui/system to v2.4.16 ([#240](https://github.com/jakepage91/hello-distr/issues/240)) ([92d29f7](https://github.com/jakepage91/hello-distr/commit/92d29f7d5eb2067d60c43a8638b96d761c63eb2e))
* **deps:** update dependency @heroui/system to v2.4.17 ([#259](https://github.com/jakepage91/hello-distr/issues/259)) ([f9e88ef](https://github.com/jakepage91/hello-distr/commit/f9e88efe611a1e77a9597ebf723088082d93187a))
* **deps:** update dependency @heroui/system to v2.4.18 ([#284](https://github.com/jakepage91/hello-distr/issues/284)) ([dea2d4c](https://github.com/jakepage91/hello-distr/commit/dea2d4cd53783693311f2828da28f1af2154f753))
* **deps:** update dependency @heroui/theme to v2.4.11 ([#67](https://github.com/jakepage91/hello-distr/issues/67)) ([3c9dcd7](https://github.com/jakepage91/hello-distr/commit/3c9dcd7c20473f4f8ea7edb77a5c7acb6f8e1540))
* **deps:** update dependency @heroui/theme to v2.4.12 ([#94](https://github.com/jakepage91/hello-distr/issues/94)) ([cb8cb78](https://github.com/jakepage91/hello-distr/commit/cb8cb783b715658dfb8fec1c236085ba43a2c116))
* **deps:** update dependency @heroui/theme to v2.4.13 ([#141](https://github.com/jakepage91/hello-distr/issues/141)) ([27539d0](https://github.com/jakepage91/hello-distr/commit/27539d0a556e1ecce9b16311ffea2d9eb151ba25))
* **deps:** update dependency @heroui/theme to v2.4.15 ([#181](https://github.com/jakepage91/hello-distr/issues/181)) ([35152ec](https://github.com/jakepage91/hello-distr/commit/35152ecca20578849b3b1b682fd138bc6818f49a))
* **deps:** update dependency @heroui/theme to v2.4.16 ([#242](https://github.com/jakepage91/hello-distr/issues/242)) ([30a815a](https://github.com/jakepage91/hello-distr/commit/30a815a2ea95dc15bb9841dc45c405c98cf11ab3))
* **deps:** update dependency @heroui/theme to v2.4.17 ([#260](https://github.com/jakepage91/hello-distr/issues/260)) ([f1a131f](https://github.com/jakepage91/hello-distr/commit/f1a131fbbdd1da9f27464b90356b7a7e7e41f656))
* **deps:** update dependency @react-aria/visually-hidden to v3.8.21 ([#100](https://github.com/jakepage91/hello-distr/issues/100)) ([034f101](https://github.com/jakepage91/hello-distr/commit/034f101265d4cb0372be1b72c2baa453c7bd2abc))
* **deps:** update dependency @react-aria/visually-hidden to v3.8.25 ([#261](https://github.com/jakepage91/hello-distr/issues/261)) ([8ede201](https://github.com/jakepage91/hello-distr/commit/8ede20173a7d1f0e476af80c750c2729f62d4566))
* **deps:** update dependency framer-motion to v12 ([#45](https://github.com/jakepage91/hello-distr/issues/45)) ([0c36c2b](https://github.com/jakepage91/hello-distr/commit/0c36c2b5a7d8448d74121ba3d4a898f8ca65bbac))
* **deps:** update dependency framer-motion to v12.10.0 ([#191](https://github.com/jakepage91/hello-distr/issues/191)) ([7e74525](https://github.com/jakepage91/hello-distr/commit/7e74525e31cb8ea018df9ef06f70154ba3d3ed49))
* **deps:** update dependency framer-motion to v12.10.1 ([#196](https://github.com/jakepage91/hello-distr/issues/196)) ([96fc7f8](https://github.com/jakepage91/hello-distr/commit/96fc7f8c1c05af638cef95b64f4eb43f907549f0))
* **deps:** update dependency framer-motion to v12.10.5 ([#198](https://github.com/jakepage91/hello-distr/issues/198)) ([ad395e1](https://github.com/jakepage91/hello-distr/commit/ad395e17f6c1a31adb63bf1230ee770adc3bbb9c))
* **deps:** update dependency framer-motion to v12.11.0 ([#203](https://github.com/jakepage91/hello-distr/issues/203)) ([6490785](https://github.com/jakepage91/hello-distr/commit/64907859b50fed11d57ad00e63802a4a0b808091))
* **deps:** update dependency framer-motion to v12.11.3 ([#208](https://github.com/jakepage91/hello-distr/issues/208)) ([40f07df](https://github.com/jakepage91/hello-distr/commit/40f07dfcaecde6fb398ee0ad092ebc285fc8b9e6))
* **deps:** update dependency framer-motion to v12.11.4 ([#209](https://github.com/jakepage91/hello-distr/issues/209)) ([3c9dac3](https://github.com/jakepage91/hello-distr/commit/3c9dac31a46f9472271209815a858be9c1b75eea))
* **deps:** update dependency framer-motion to v12.12.1 ([#211](https://github.com/jakepage91/hello-distr/issues/211)) ([aa4a28d](https://github.com/jakepage91/hello-distr/commit/aa4a28d504dedecad9ccb8029300bfbffb6bc9f2))
* **deps:** update dependency framer-motion to v12.12.2 ([#217](https://github.com/jakepage91/hello-distr/issues/217)) ([833af2d](https://github.com/jakepage91/hello-distr/commit/833af2ddb3cb69907fce78758b6ebfd49c9453ba))
* **deps:** update dependency framer-motion to v12.14.0 ([#218](https://github.com/jakepage91/hello-distr/issues/218)) ([c224bab](https://github.com/jakepage91/hello-distr/commit/c224babe9cd83a3b5883b2380e10e7c7c315e77b))
* **deps:** update dependency framer-motion to v12.15.0 ([#220](https://github.com/jakepage91/hello-distr/issues/220)) ([8c2d3c1](https://github.com/jakepage91/hello-distr/commit/8c2d3c159de804674c03b9c3912c7582f8e152a6))
* **deps:** update dependency framer-motion to v12.16.0 ([#244](https://github.com/jakepage91/hello-distr/issues/244)) ([cc69a8b](https://github.com/jakepage91/hello-distr/commit/cc69a8bf4bc8ec4d9fbeb652adbbe69e21a02da5))
* **deps:** update dependency framer-motion to v12.18.1 ([#263](https://github.com/jakepage91/hello-distr/issues/263)) ([86cbd79](https://github.com/jakepage91/hello-distr/commit/86cbd79c3c343ae039090153fa0220c4548cd76e))
* **deps:** update dependency framer-motion to v12.19.1 ([#288](https://github.com/jakepage91/hello-distr/issues/288)) ([bdef2da](https://github.com/jakepage91/hello-distr/commit/bdef2da8fad7da6fb28f13edefaeeb1439eafe9d))
* **deps:** update dependency framer-motion to v12.19.2 ([#293](https://github.com/jakepage91/hello-distr/issues/293)) ([925e35b](https://github.com/jakepage91/hello-distr/commit/925e35bea4ff43fbbc17636893f48c85fbbfc195))
* **deps:** update dependency framer-motion to v12.20.1 ([#296](https://github.com/jakepage91/hello-distr/issues/296)) ([18f4b31](https://github.com/jakepage91/hello-distr/commit/18f4b31eeca8b87d630e9c92beb805e0d71553ac))
* **deps:** update dependency framer-motion to v12.4.10 ([#70](https://github.com/jakepage91/hello-distr/issues/70)) ([f2d817f](https://github.com/jakepage91/hello-distr/commit/f2d817f4231b34f1adbf57c2bf1d59c7f10d05fa))
* **deps:** update dependency framer-motion to v12.4.11 ([#97](https://github.com/jakepage91/hello-distr/issues/97)) ([d40dc7f](https://github.com/jakepage91/hello-distr/commit/d40dc7f6d9d4d12fb2cf8e1ae72b1ccbf6faed50))
* **deps:** update dependency framer-motion to v12.5.0 ([#102](https://github.com/jakepage91/hello-distr/issues/102)) ([60ba856](https://github.com/jakepage91/hello-distr/commit/60ba856107fba18b1a8810a6b65e7c1460c2fb01))
* **deps:** update dependency framer-motion to v12.6.0 ([#118](https://github.com/jakepage91/hello-distr/issues/118)) ([53e47a5](https://github.com/jakepage91/hello-distr/commit/53e47a5c5272c809a584f4d216b0cc478640da80))
* **deps:** update dependency framer-motion to v12.6.2 ([#120](https://github.com/jakepage91/hello-distr/issues/120)) ([c5a6785](https://github.com/jakepage91/hello-distr/commit/c5a6785661637739b9347350a799bb40ccd50729))
* **deps:** update dependency framer-motion to v12.6.3 ([#125](https://github.com/jakepage91/hello-distr/issues/125)) ([01326cf](https://github.com/jakepage91/hello-distr/commit/01326cf79d813734dbacefd9a6cbaead26b5cd79))
* **deps:** update dependency framer-motion to v12.6.5 ([#147](https://github.com/jakepage91/hello-distr/issues/147)) ([1e4af0c](https://github.com/jakepage91/hello-distr/commit/1e4af0c473975a1eb9a930ec85a48ae8dcedd341))
* **deps:** update dependency framer-motion to v12.7.2 ([#151](https://github.com/jakepage91/hello-distr/issues/151)) ([42520ec](https://github.com/jakepage91/hello-distr/commit/42520ecacb2c160681996086e8ce0d6061d9bacc))
* **deps:** update dependency framer-motion to v12.7.3 ([#154](https://github.com/jakepage91/hello-distr/issues/154)) ([0ac090a](https://github.com/jakepage91/hello-distr/commit/0ac090afe0a6f3f762f0bb1a36ef6305172324e9))
* **deps:** update dependency framer-motion to v12.7.4 ([#155](https://github.com/jakepage91/hello-distr/issues/155)) ([891aed1](https://github.com/jakepage91/hello-distr/commit/891aed1c8e02148d586773785685181c1f8036e6))
* **deps:** update dependency framer-motion to v12.8.0 ([#162](https://github.com/jakepage91/hello-distr/issues/162)) ([e6c83a5](https://github.com/jakepage91/hello-distr/commit/e6c83a5db963be4b8101919a5f7280a45d734547))
* **deps:** update dependency framer-motion to v12.9.1 ([#163](https://github.com/jakepage91/hello-distr/issues/163)) ([53444df](https://github.com/jakepage91/hello-distr/commit/53444dfff3ae4210a5d6b7dd487e32be271c631c))
* **deps:** update dependency framer-motion to v12.9.2 ([#168](https://github.com/jakepage91/hello-distr/issues/168)) ([e90770f](https://github.com/jakepage91/hello-distr/commit/e90770f029f280dc0edb3ff68d2abf3f45e8a53c))
* **deps:** update dependency framer-motion to v12.9.4 ([#183](https://github.com/jakepage91/hello-distr/issues/183)) ([4180f7c](https://github.com/jakepage91/hello-distr/commit/4180f7ce454c939f07cb1dd65d029dfd7ec21ce5))
* **deps:** update dependency framer-motion to v12.9.7 ([#187](https://github.com/jakepage91/hello-distr/issues/187)) ([6c2681e](https://github.com/jakepage91/hello-distr/commit/6c2681e41660b2c591eb2dc0d3c4329ffadb2a1a))
* **deps:** update dependency intl-messageformat to v10.7.16 ([#112](https://github.com/jakepage91/hello-distr/issues/112)) ([e635201](https://github.com/jakepage91/hello-distr/commit/e63520104f24ae6c28effcea520e96dcbcfc6e77))
* **deps:** update dependency next to v15.1.2 [security] ([#4](https://github.com/jakepage91/hello-distr/issues/4)) ([c23e4b6](https://github.com/jakepage91/hello-distr/commit/c23e4b6438b9f8f45bb3e4b180e8c0bfe663e674))
* **deps:** update dependency next-themes to v0.4.5 ([#96](https://github.com/jakepage91/hello-distr/issues/96)) ([fd97715](https://github.com/jakepage91/hello-distr/commit/fd97715fbf513d05cd933e6a36f81bc5633737cc))
* **deps:** update dependency next-themes to v0.4.6 ([#103](https://github.com/jakepage91/hello-distr/issues/103)) ([76ce99e](https://github.com/jakepage91/hello-distr/commit/76ce99ea400757d7153f324653d2b944a9cca89e))
* **deps:** update nextjs monorepo to v15.2.0 ([#40](https://github.com/jakepage91/hello-distr/issues/40)) ([d56ea7a](https://github.com/jakepage91/hello-distr/commit/d56ea7a6d9b782691e90d7de16e01c503d852c50))
* **deps:** update nextjs monorepo to v15.2.1 ([#73](https://github.com/jakepage91/hello-distr/issues/73)) ([b4f3745](https://github.com/jakepage91/hello-distr/commit/b4f37454e1641685cbddf20dd38bbe3c9b894f5f))
* **deps:** update nextjs monorepo to v15.2.2 ([#101](https://github.com/jakepage91/hello-distr/issues/101)) ([a2056c3](https://github.com/jakepage91/hello-distr/commit/a2056c3325334099301ee4110fcb07562566ee4d))
* **deps:** update nextjs monorepo to v15.2.3 ([#107](https://github.com/jakepage91/hello-distr/issues/107)) ([ec6da4d](https://github.com/jakepage91/hello-distr/commit/ec6da4df0d8100d3a629479897eaf26bd1308a25))
* **deps:** update nextjs monorepo to v15.2.4 ([#116](https://github.com/jakepage91/hello-distr/issues/116)) ([f070d2d](https://github.com/jakepage91/hello-distr/commit/f070d2dca0691b4193de1e4692159bd1164fc898))
* **deps:** update nextjs monorepo to v15.2.5 ([#143](https://github.com/jakepage91/hello-distr/issues/143)) ([4595c59](https://github.com/jakepage91/hello-distr/commit/4595c59aed54df4885ce68b1ceb4b1e130b4a9ab))
* **deps:** update nextjs monorepo to v15.3.0 ([#145](https://github.com/jakepage91/hello-distr/issues/145)) ([5edd7ed](https://github.com/jakepage91/hello-distr/commit/5edd7ed02719bb678f22547de993e7203e642ba5))
* **deps:** update nextjs monorepo to v15.3.1 ([#156](https://github.com/jakepage91/hello-distr/issues/156)) ([30bbc8c](https://github.com/jakepage91/hello-distr/commit/30bbc8cdbb188bfc6ef68fb2fe046b73e0d26b09))
* **deps:** update nextjs monorepo to v15.3.2 ([#193](https://github.com/jakepage91/hello-distr/issues/193)) ([b350841](https://github.com/jakepage91/hello-distr/commit/b35084164d52b1860ef81159d76caa59ce4fbfec))
* **deps:** update nextjs monorepo to v15.3.3 ([#226](https://github.com/jakepage91/hello-distr/issues/226)) ([ff500dd](https://github.com/jakepage91/hello-distr/commit/ff500ddb6bac32f71399bfc70deae3e18e4cb622))
* **deps:** update nextjs monorepo to v15.3.4 ([#276](https://github.com/jakepage91/hello-distr/issues/276)) ([dba09f0](https://github.com/jakepage91/hello-distr/commit/dba09f0c7df8886a5c9a6673543e133189dba8a7))
* **deps:** update react monorepo (major) ([#46](https://github.com/jakepage91/hello-distr/issues/46)) ([74f3d0e](https://github.com/jakepage91/hello-distr/commit/74f3d0e9d740f888a68ca38f5e81db08b5f58049))
* **deps:** update react monorepo to v19.1.0 ([#122](https://github.com/jakepage91/hello-distr/issues/122)) ([57be632](https://github.com/jakepage91/hello-distr/commit/57be632f855efa02985e1acb5fb452737f18806e))
* **deps:** update react-spectrum monorepo ([#149](https://github.com/jakepage91/hello-distr/issues/149)) ([e0a74e8](https://github.com/jakepage91/hello-distr/commit/e0a74e80175c2595bfb5740864c1cecd7628f156))
* **deps:** update react-spectrum monorepo ([#214](https://github.com/jakepage91/hello-distr/issues/214)) ([619079c](https://github.com/jakepage91/hello-distr/commit/619079c58192831af0bea4e48464c9bb3fb97738))
* **deps:** update react-spectrum monorepo ([#247](https://github.com/jakepage91/hello-distr/issues/247)) ([5406f81](https://github.com/jakepage91/hello-distr/commit/5406f81e465979b9f955dfc3b8b0c8e77f5b914a))
* **deps:** update react-spectrum monorepo ([#77](https://github.com/jakepage91/hello-distr/issues/77)) ([0afdbce](https://github.com/jakepage91/hello-distr/commit/0afdbcee11fd50b7a7417f0812813cb0d84779e8))
* extra hosts for frontend container ([#47](https://github.com/jakepage91/hello-distr/issues/47)) ([04f6bb1](https://github.com/jakepage91/hello-distr/commit/04f6bb198c6480836a45f360ef7f8247df378249))
* postgres healthcheck parameters ([#34](https://github.com/jakepage91/hello-distr/issues/34)) ([683f9e4](https://github.com/jakepage91/hello-distr/commit/683f9e4cf478d93e999358def8db237d467d0ad0))


### Other

* add second push distr action, small docs updates ([#38](https://github.com/jakepage91/hello-distr/issues/38)) ([70b2f0e](https://github.com/jakepage91/hello-distr/commit/70b2f0e2bc111341960f714e030808043c4b1031))
* Configure Renovate ([#2](https://github.com/jakepage91/hello-distr/issues/2)) ([5a40e07](https://github.com/jakepage91/hello-distr/commit/5a40e07a9c13ae421da73afc230e9707e22da17b))
* **deps:** bump @babel/runtime from 7.26.9 to 7.26.10 in /frontend ([#104](https://github.com/jakepage91/hello-distr/issues/104)) ([d42b30b](https://github.com/jakepage91/hello-distr/commit/d42b30b11cdfcc2905771512de4e8ef3b24c90f3))
* **deps:** replace dependency eslint-plugin-node with eslint-plugin-n ^14.0.0 ([#5](https://github.com/jakepage91/hello-distr/issues/5)) ([6d9ffb3](https://github.com/jakepage91/hello-distr/commit/6d9ffb328a9b889fffd37f06b2d7e5cbc890fca0))
* **deps:** update caddy docker tag to v2.10.0 ([#160](https://github.com/jakepage91/hello-distr/issues/160)) ([05a117a](https://github.com/jakepage91/hello-distr/commit/05a117a23a567d51e5100c6b7ca7d84a26e8d80a))
* **deps:** update dependency @react-types/shared to v3.27.0 ([#13](https://github.com/jakepage91/hello-distr/issues/13)) ([3acc53e](https://github.com/jakepage91/hello-distr/commit/3acc53e10a3f723ce9304d5853af7c05408e68e9))
* **deps:** update dependency @types/node to v20.17.19 ([#14](https://github.com/jakepage91/hello-distr/issues/14)) ([b991628](https://github.com/jakepage91/hello-distr/commit/b9916287cf70e580697a50bbada43f5e4ff1d1e2))
* **deps:** update dependency @types/node to v20.17.21 ([#63](https://github.com/jakepage91/hello-distr/issues/63)) ([8ff5989](https://github.com/jakepage91/hello-distr/commit/8ff5989d6d6be075275492b716fcdf0247771ecd))
* **deps:** update dependency @types/node to v20.17.22 ([#66](https://github.com/jakepage91/hello-distr/issues/66)) ([7594aca](https://github.com/jakepage91/hello-distr/commit/7594aca07cb16206e359f0b88bd2dd7c85a111d5))
* **deps:** update dependency @types/node to v22 ([#41](https://github.com/jakepage91/hello-distr/issues/41)) ([2c654f9](https://github.com/jakepage91/hello-distr/commit/2c654f9fbb230957d9617b537f6f3549508647a1))
* **deps:** update dependency @types/node to v22.13.10 ([#82](https://github.com/jakepage91/hello-distr/issues/82)) ([31cae12](https://github.com/jakepage91/hello-distr/commit/31cae125c55642713e96b6ff2ea46c0ee92e938b))
* **deps:** update dependency @types/node to v22.13.11 ([#110](https://github.com/jakepage91/hello-distr/issues/110)) ([e3b86ca](https://github.com/jakepage91/hello-distr/commit/e3b86ca45e3bac93d33c988a8643d9347041033e))
* **deps:** update dependency @types/node to v22.13.13 ([#114](https://github.com/jakepage91/hello-distr/issues/114)) ([dc80494](https://github.com/jakepage91/hello-distr/commit/dc804942af0c412bea3e9df62e7654cfc35891ca))
* **deps:** update dependency @types/node to v22.13.14 ([#121](https://github.com/jakepage91/hello-distr/issues/121)) ([453623b](https://github.com/jakepage91/hello-distr/commit/453623b526269d748bb0967d25f826af6b9203a4))
* **deps:** update dependency @types/node to v22.13.17 ([#124](https://github.com/jakepage91/hello-distr/issues/124)) ([d9487f4](https://github.com/jakepage91/hello-distr/commit/d9487f473d7df6504960cd62a86aad0a91491dd1))
* **deps:** update dependency @types/node to v22.13.9 ([#72](https://github.com/jakepage91/hello-distr/issues/72)) ([403c01b](https://github.com/jakepage91/hello-distr/commit/403c01bd50ee712b86f5ed1e31938a014b975455))
* **deps:** update dependency @types/node to v22.14.0 ([#128](https://github.com/jakepage91/hello-distr/issues/128)) ([a954118](https://github.com/jakepage91/hello-distr/commit/a95411890ebe95c953fda088d016b763901c0e59))
* **deps:** update dependency @types/node to v22.14.1 ([#150](https://github.com/jakepage91/hello-distr/issues/150)) ([72fd9e8](https://github.com/jakepage91/hello-distr/commit/72fd9e82d33b4e202afb8cc41b07ce4f53c128e2))
* **deps:** update dependency @types/node to v22.15.0 ([#166](https://github.com/jakepage91/hello-distr/issues/166)) ([6c53d01](https://github.com/jakepage91/hello-distr/commit/6c53d0122d8569523b10362b50e4b541038e1034))
* **deps:** update dependency @types/node to v22.15.12 ([#188](https://github.com/jakepage91/hello-distr/issues/188)) ([3fc8603](https://github.com/jakepage91/hello-distr/commit/3fc8603c44078882cdb8e229d57d456e173a5736))
* **deps:** update dependency @types/node to v22.15.14 ([#192](https://github.com/jakepage91/hello-distr/issues/192)) ([68673c8](https://github.com/jakepage91/hello-distr/commit/68673c888657ae805edfc42101ff41e19ae6a9bc))
* **deps:** update dependency @types/node to v22.15.15 ([#195](https://github.com/jakepage91/hello-distr/issues/195)) ([003dc4d](https://github.com/jakepage91/hello-distr/commit/003dc4dd89c0745982dee6d3a8e0e6aa50b29bd4))
* **deps:** update dependency @types/node to v22.15.16 ([#197](https://github.com/jakepage91/hello-distr/issues/197)) ([6c3e539](https://github.com/jakepage91/hello-distr/commit/6c3e5396cc50b7f2a8371e8502f3769e6a8dfcae))
* **deps:** update dependency @types/node to v22.15.17 ([#199](https://github.com/jakepage91/hello-distr/issues/199)) ([d291894](https://github.com/jakepage91/hello-distr/commit/d2918944bedfdd244b90b0b879a79c1c4f07a7bf))
* **deps:** update dependency @types/node to v22.15.18 ([#207](https://github.com/jakepage91/hello-distr/issues/207)) ([fbbe1a2](https://github.com/jakepage91/hello-distr/commit/fbbe1a226726b5acd0cfc1073e56d32b8e783ad1))
* **deps:** update dependency @types/node to v22.15.19 ([#213](https://github.com/jakepage91/hello-distr/issues/213)) ([8ae4335](https://github.com/jakepage91/hello-distr/commit/8ae4335e6e4250abb72c0df104119f9e70b58648))
* **deps:** update dependency @types/node to v22.15.2 ([#167](https://github.com/jakepage91/hello-distr/issues/167)) ([b772dd1](https://github.com/jakepage91/hello-distr/commit/b772dd1e23b0cc33a8b030230c685840a9d5b2aa))
* **deps:** update dependency @types/node to v22.15.21 ([#215](https://github.com/jakepage91/hello-distr/issues/215)) ([a5964b8](https://github.com/jakepage91/hello-distr/commit/a5964b8b3568373f4490c43d9d038cba37e6b14b))
* **deps:** update dependency @types/node to v22.15.23 ([#223](https://github.com/jakepage91/hello-distr/issues/223)) ([a531b6c](https://github.com/jakepage91/hello-distr/commit/a531b6c5f33069fc8e8bf1b69ca37f8e70532192))
* **deps:** update dependency @types/node to v22.15.24 ([#224](https://github.com/jakepage91/hello-distr/issues/224)) ([7409954](https://github.com/jakepage91/hello-distr/commit/7409954a2db4382369cdf02bc9e55cf079c352af))
* **deps:** update dependency @types/node to v22.15.26 ([#227](https://github.com/jakepage91/hello-distr/issues/227)) ([a9c948e](https://github.com/jakepage91/hello-distr/commit/a9c948e0471d29f58332453b2b2fc3101606ff79))
* **deps:** update dependency @types/node to v22.15.29 ([#229](https://github.com/jakepage91/hello-distr/issues/229)) ([302f82c](https://github.com/jakepage91/hello-distr/commit/302f82c8ae4bd79484734c0860e17621629ed6c9))
* **deps:** update dependency @types/node to v22.15.3 ([#169](https://github.com/jakepage91/hello-distr/issues/169)) ([f284b86](https://github.com/jakepage91/hello-distr/commit/f284b86f9e6821c38a4b97e87f13b6b436e85681))
* **deps:** update dependency @types/node to v22.15.30 ([#246](https://github.com/jakepage91/hello-distr/issues/246)) ([6ce6e33](https://github.com/jakepage91/hello-distr/commit/6ce6e336552c169a76891e2cd5d9acdbcaa0f092))
* **deps:** update dependency @types/node to v22.15.31 ([#252](https://github.com/jakepage91/hello-distr/issues/252)) ([fbc6058](https://github.com/jakepage91/hello-distr/commit/fbc6058df1f9a65062f4298bcdb19dfc66d4e44c))
* **deps:** update dependency @types/node to v22.15.32 ([#269](https://github.com/jakepage91/hello-distr/issues/269)) ([738f521](https://github.com/jakepage91/hello-distr/commit/738f5212d96c7359b7687ea8caaa2e9e58d71df4))
* **deps:** update dependency @types/node to v22.15.33 ([#289](https://github.com/jakepage91/hello-distr/issues/289)) ([64e8d52](https://github.com/jakepage91/hello-distr/commit/64e8d527b1ff73a5fec29cc06beced875f3a0407))
* **deps:** update dependency @types/node to v22.15.34 ([#295](https://github.com/jakepage91/hello-distr/issues/295)) ([28d2cc5](https://github.com/jakepage91/hello-distr/commit/28d2cc5d007cdebb5acd7d6aa2fc73c0aefdff4f))
* **deps:** update dependency @types/react to v19.0.11 ([#106](https://github.com/jakepage91/hello-distr/issues/106)) ([10e7db5](https://github.com/jakepage91/hello-distr/commit/10e7db585c03d7a71a97643d27324bd06b6d1ca8))
* **deps:** update dependency @types/react to v19.0.12 ([#108](https://github.com/jakepage91/hello-distr/issues/108)) ([eb729b7](https://github.com/jakepage91/hello-distr/commit/eb729b708f9cae894d692421fbd4c34cf786692b))
* **deps:** update dependency @types/react to v19.1.1 ([#148](https://github.com/jakepage91/hello-distr/issues/148)) ([a722779](https://github.com/jakepage91/hello-distr/commit/a72277954d25c54574627095d21df4fba1cfc206))
* **deps:** update dependency @types/react to v19.1.2 ([#152](https://github.com/jakepage91/hello-distr/issues/152)) ([e794a1c](https://github.com/jakepage91/hello-distr/commit/e794a1cf4424711c009f96990820a878c782fc3d))
* **deps:** update dependency @types/react to v19.1.3 ([#190](https://github.com/jakepage91/hello-distr/issues/190)) ([acf14e2](https://github.com/jakepage91/hello-distr/commit/acf14e23796e6566e2d64209951f7f0317ada7e7))
* **deps:** update dependency @types/react to v19.1.5 ([#216](https://github.com/jakepage91/hello-distr/issues/216)) ([98480fa](https://github.com/jakepage91/hello-distr/commit/98480fa57360067df6aab45586673475d7468ed5))
* **deps:** update dependency @types/react to v19.1.6 ([#219](https://github.com/jakepage91/hello-distr/issues/219)) ([766a937](https://github.com/jakepage91/hello-distr/commit/766a937f1bfd8ff3bfbebf5c5beba189675354ae))
* **deps:** update dependency @types/react to v19.1.7 ([#250](https://github.com/jakepage91/hello-distr/issues/250)) ([22b93e6](https://github.com/jakepage91/hello-distr/commit/22b93e66c93d88e3454f4f4623fe65f62226e1d6))
* **deps:** update dependency @types/react to v19.1.8 ([#264](https://github.com/jakepage91/hello-distr/issues/264)) ([a561864](https://github.com/jakepage91/hello-distr/commit/a56186487d7d7070a1fc05ac38f387133000f29e))
* **deps:** update dependency @types/react-dom to v19.1.2 ([#144](https://github.com/jakepage91/hello-distr/issues/144)) ([b6aed91](https://github.com/jakepage91/hello-distr/commit/b6aed91bc63afd348f7432ea4564f73d07d32644))
* **deps:** update dependency @types/react-dom to v19.1.3 ([#182](https://github.com/jakepage91/hello-distr/issues/182)) ([53e7dd3](https://github.com/jakepage91/hello-distr/commit/53e7dd3966ea9babf55d77295e29f372c4983e90))
* **deps:** update dependency @types/react-dom to v19.1.5 ([#206](https://github.com/jakepage91/hello-distr/issues/206)) ([0a5b286](https://github.com/jakepage91/hello-distr/commit/0a5b2867ecd75441bab5f7843676c1772bc15992))
* **deps:** update dependency @types/react-dom to v19.1.6 ([#245](https://github.com/jakepage91/hello-distr/issues/245)) ([be392b5](https://github.com/jakepage91/hello-distr/commit/be392b5ab5345d4c83d7a01cec5101039552f59f))
* **deps:** update dependency autoprefixer to v10.4.20 ([#7](https://github.com/jakepage91/hello-distr/issues/7)) ([e3dec4a](https://github.com/jakepage91/hello-distr/commit/e3dec4a6824da52299d665993864397f0797f2ae))
* **deps:** update dependency autoprefixer to v10.4.21 ([#93](https://github.com/jakepage91/hello-distr/issues/93)) ([648882a](https://github.com/jakepage91/hello-distr/commit/648882a1c8db82fc7ea73e03cd65296bbb239fe6))
* **deps:** update dependency eslint to v9 ([#42](https://github.com/jakepage91/hello-distr/issues/42)) ([0b9086b](https://github.com/jakepage91/hello-distr/commit/0b9086b864905f5edf45bfb44f234794ab4bac08))
* **deps:** update dependency eslint to v9.22.0 ([#80](https://github.com/jakepage91/hello-distr/issues/80)) ([eceb238](https://github.com/jakepage91/hello-distr/commit/eceb23876aaf3dfbb8a0a0b7ba3638af71d8f0cc))
* **deps:** update dependency eslint to v9.23.0 ([#111](https://github.com/jakepage91/hello-distr/issues/111)) ([30b91b7](https://github.com/jakepage91/hello-distr/commit/30b91b7a2df48fb335654fc6d9117afaf2a7ddfb))
* **deps:** update dependency eslint to v9.24.0 ([#130](https://github.com/jakepage91/hello-distr/issues/130)) ([7d4feb1](https://github.com/jakepage91/hello-distr/commit/7d4feb11b9f0dca596114d6d48b997f5b09fbe32))
* **deps:** update dependency eslint to v9.25.0 ([#157](https://github.com/jakepage91/hello-distr/issues/157)) ([bfe03f3](https://github.com/jakepage91/hello-distr/commit/bfe03f38cf9d68c6aa82fb1eb099fffa7eba73b2))
* **deps:** update dependency eslint to v9.25.1 ([#158](https://github.com/jakepage91/hello-distr/issues/158)) ([f483362](https://github.com/jakepage91/hello-distr/commit/f48336234d699799407bcb017942351a64cc620b))
* **deps:** update dependency eslint to v9.26.0 ([#184](https://github.com/jakepage91/hello-distr/issues/184)) ([9d10f7d](https://github.com/jakepage91/hello-distr/commit/9d10f7d05836a815c413056e2ca2aa6b7d3097b2))
* **deps:** update dependency eslint to v9.27.0 ([#212](https://github.com/jakepage91/hello-distr/issues/212)) ([8fc6b7c](https://github.com/jakepage91/hello-distr/commit/8fc6b7c3ae22793f70173a3299804e48711f7022))
* **deps:** update dependency eslint to v9.28.0 ([#230](https://github.com/jakepage91/hello-distr/issues/230)) ([de86eef](https://github.com/jakepage91/hello-distr/commit/de86eef1aa012b6583e036e2f6966e6ae945e2f0))
* **deps:** update dependency eslint to v9.29.0 ([#268](https://github.com/jakepage91/hello-distr/issues/268)) ([8f9f58c](https://github.com/jakepage91/hello-distr/commit/8f9f58c469b0fd0aa0b19a8858a535bef08f2d79))
* **deps:** update dependency eslint to v9.30.0 ([#294](https://github.com/jakepage91/hello-distr/issues/294)) ([5da228c](https://github.com/jakepage91/hello-distr/commit/5da228c416e1efc38376c566ebd63dda2cdff0d3))
* **deps:** update dependency eslint-config-prettier to v10 ([#43](https://github.com/jakepage91/hello-distr/issues/43)) ([d3204da](https://github.com/jakepage91/hello-distr/commit/d3204da05b411809d1b6a00602860ff3a63d7cde))
* **deps:** update dependency eslint-config-prettier to v10.1.1 ([#79](https://github.com/jakepage91/hello-distr/issues/79)) ([baaae94](https://github.com/jakepage91/hello-distr/commit/baaae9440e96d56bf5e07ac5f0a8822d20138e62))
* **deps:** update dependency eslint-config-prettier to v10.1.2 ([#146](https://github.com/jakepage91/hello-distr/issues/146)) ([25eb9c7](https://github.com/jakepage91/hello-distr/commit/25eb9c7e338372bf1246d13f858b20253d686e89))
* **deps:** update dependency eslint-config-prettier to v10.1.3 ([#194](https://github.com/jakepage91/hello-distr/issues/194)) ([074a69b](https://github.com/jakepage91/hello-distr/commit/074a69b81ba0a2edea58bc9314824ca6a91bd30e))
* **deps:** update dependency eslint-config-prettier to v10.1.5 ([#201](https://github.com/jakepage91/hello-distr/issues/201)) ([8c77ca4](https://github.com/jakepage91/hello-distr/commit/8c77ca42483fa2160c510dbcf02f8788b4d5dc1f))
* **deps:** update dependency eslint-plugin-import to v2.32.0 ([#285](https://github.com/jakepage91/hello-distr/issues/285)) ([3f4ed71](https://github.com/jakepage91/hello-distr/commit/3f4ed71a375aebbc41da68ecf47311f07ca712cc))
* **deps:** update dependency eslint-plugin-n to v17 ([#53](https://github.com/jakepage91/hello-distr/issues/53)) ([5c5e25c](https://github.com/jakepage91/hello-distr/commit/5c5e25c2c351e5bb71dcf3b1d431bb621d26159d))
* **deps:** update dependency eslint-plugin-n to v17.16.2 ([#74](https://github.com/jakepage91/hello-distr/issues/74)) ([fc188e5](https://github.com/jakepage91/hello-distr/commit/fc188e5e40d326d6c659b2e4b53c312204a09119))
* **deps:** update dependency eslint-plugin-n to v17.17.0 ([#119](https://github.com/jakepage91/hello-distr/issues/119)) ([4eff84b](https://github.com/jakepage91/hello-distr/commit/4eff84bdf9a880d8f21a036d0ae97e5d9177d8f5))
* **deps:** update dependency eslint-plugin-n to v17.18.0 ([#202](https://github.com/jakepage91/hello-distr/issues/202)) ([b620565](https://github.com/jakepage91/hello-distr/commit/b620565b410072b3a2781ed59772c06901cb24f8))
* **deps:** update dependency eslint-plugin-n to v17.19.0 ([#243](https://github.com/jakepage91/hello-distr/issues/243)) ([198fa46](https://github.com/jakepage91/hello-distr/commit/198fa465a60d07ba77d73aa50dd90bb05bad2f75))
* **deps:** update dependency eslint-plugin-n to v17.20.0 ([#267](https://github.com/jakepage91/hello-distr/issues/267)) ([1489b8c](https://github.com/jakepage91/hello-distr/commit/1489b8cb4aa8cfa05335d904feb72d8ca28e761d))
* **deps:** update dependency eslint-plugin-prettier to v5.2.3 ([#8](https://github.com/jakepage91/hello-distr/issues/8)) ([dceefdd](https://github.com/jakepage91/hello-distr/commit/dceefdd0a178f7038861fc2b48addfd6ab9707c8))
* **deps:** update dependency eslint-plugin-prettier to v5.2.4 ([#113](https://github.com/jakepage91/hello-distr/issues/113)) ([02adaa2](https://github.com/jakepage91/hello-distr/commit/02adaa2bfcbf4a4a017748082d40cc297c855d4e))
* **deps:** update dependency eslint-plugin-prettier to v5.2.5 ([#117](https://github.com/jakepage91/hello-distr/issues/117)) ([e13be0a](https://github.com/jakepage91/hello-distr/commit/e13be0af131dec56a494ff867459ccb3f11f9391))
* **deps:** update dependency eslint-plugin-prettier to v5.2.6 ([#127](https://github.com/jakepage91/hello-distr/issues/127)) ([a16c8cc](https://github.com/jakepage91/hello-distr/commit/a16c8cc19285d133cd05ab3f8f9238f69c268fc2))
* **deps:** update dependency eslint-plugin-prettier to v5.3.1 ([#185](https://github.com/jakepage91/hello-distr/issues/185)) ([7e76fe6](https://github.com/jakepage91/hello-distr/commit/7e76fe6a0bcf10e2b382fa356e2132c279b84d00))
* **deps:** update dependency eslint-plugin-prettier to v5.4.0 ([#186](https://github.com/jakepage91/hello-distr/issues/186)) ([ccf4f73](https://github.com/jakepage91/hello-distr/commit/ccf4f73a7bd1d00e3a006cc5886cc231b4011269))
* **deps:** update dependency eslint-plugin-prettier to v5.4.1 ([#228](https://github.com/jakepage91/hello-distr/issues/228)) ([559d373](https://github.com/jakepage91/hello-distr/commit/559d3738a28c01bd31b143083ac09ed3faf55da8))
* **deps:** update dependency eslint-plugin-prettier to v5.5.0 ([#273](https://github.com/jakepage91/hello-distr/issues/273)) ([a818ef2](https://github.com/jakepage91/hello-distr/commit/a818ef22f0afb26f22446232878adc46651f2843))
* **deps:** update dependency eslint-plugin-prettier to v5.5.1 ([#291](https://github.com/jakepage91/hello-distr/issues/291)) ([7b1a030](https://github.com/jakepage91/hello-distr/commit/7b1a03013c0f3bd8d18c8b95691f6dd0ce672194))
* **deps:** update dependency eslint-plugin-react to v7.37.5 ([#129](https://github.com/jakepage91/hello-distr/issues/129)) ([d4d61d4](https://github.com/jakepage91/hello-distr/commit/d4d61d41982f358a6ffa7c5d8b2bb4e04b8602d2))
* **deps:** update dependency postcss to v8.5.3 ([#15](https://github.com/jakepage91/hello-distr/issues/15)) ([827f6f0](https://github.com/jakepage91/hello-distr/commit/827f6f0d7ffc92aac4266afe434405da4cee9a83))
* **deps:** update dependency postcss to v8.5.4 ([#225](https://github.com/jakepage91/hello-distr/issues/225)) ([49d1ef7](https://github.com/jakepage91/hello-distr/commit/49d1ef74607ed9ce3f4362d34a9461def5f896a8))
* **deps:** update dependency postcss to v8.5.5 ([#265](https://github.com/jakepage91/hello-distr/issues/265)) ([710ab55](https://github.com/jakepage91/hello-distr/commit/710ab55fa1d2f0db265cf90beae4fa4bf5fa5920))
* **deps:** update dependency postcss to v8.5.6 ([#270](https://github.com/jakepage91/hello-distr/issues/270)) ([9012f8a](https://github.com/jakepage91/hello-distr/commit/9012f8aeb46ba2c80e2b2bfe4d0bccba3b7f58fe))
* **deps:** update dependency prettier to v3.5.2 ([#16](https://github.com/jakepage91/hello-distr/issues/16)) ([da9a80a](https://github.com/jakepage91/hello-distr/commit/da9a80a01ac6b6a00a20ad9a13f2fcc731d102a9))
* **deps:** update dependency prettier to v3.5.3 ([#69](https://github.com/jakepage91/hello-distr/issues/69)) ([c6ad5e1](https://github.com/jakepage91/hello-distr/commit/c6ad5e1e5e47d45cb0819bd5ecd0609455824cba))
* **deps:** update dependency prettier to v3.6.0 ([#286](https://github.com/jakepage91/hello-distr/issues/286)) ([296cb48](https://github.com/jakepage91/hello-distr/commit/296cb4801331267f1be068d215955b24b36a9a8e))
* **deps:** update dependency prettier to v3.6.1 ([#290](https://github.com/jakepage91/hello-distr/issues/290)) ([5e12ad9](https://github.com/jakepage91/hello-distr/commit/5e12ad9aa21603e8f60c3d7d0b2d35feda8296d8))
* **deps:** update dependency prettier to v3.6.2 ([#292](https://github.com/jakepage91/hello-distr/issues/292)) ([218df39](https://github.com/jakepage91/hello-distr/commit/218df39e3deca4a4c7ed3e6d29e6703cdfab3c52))
* **deps:** update dependency tailwind-variants to v0.3.1 ([#9](https://github.com/jakepage91/hello-distr/issues/9)) ([6fd60cc](https://github.com/jakepage91/hello-distr/commit/6fd60ccce739d648f73ab4fa874308b69d2ba118))
* **deps:** update dependency tailwind-variants to v1 ([#95](https://github.com/jakepage91/hello-distr/issues/95)) ([6d33595](https://github.com/jakepage91/hello-distr/commit/6d3359534e110d58f22e40afd42e8652be1c6c73))
* **deps:** update dependency tailwindcss to v3.4.17 ([#10](https://github.com/jakepage91/hello-distr/issues/10)) ([baa64e6](https://github.com/jakepage91/hello-distr/commit/baa64e67851fefd1462d64f9d831d08913c00d58))
* **deps:** update dependency typescript to v5.7.3 ([#17](https://github.com/jakepage91/hello-distr/issues/17)) ([a62c139](https://github.com/jakepage91/hello-distr/commit/a62c1398f8a90fefa1a05f7fa32587aec4d6941b))
* **deps:** update dependency typescript to v5.8.2 ([#68](https://github.com/jakepage91/hello-distr/issues/68)) ([40b1c83](https://github.com/jakepage91/hello-distr/commit/40b1c83d0f1df60d155258593a68bb8c1af0d8ad))
* **deps:** update dependency typescript to v5.8.3 ([#131](https://github.com/jakepage91/hello-distr/issues/131)) ([66717c4](https://github.com/jakepage91/hello-distr/commit/66717c43e6a56912b049bdec9e1b8d1abd213c92))
* **deps:** update docker/build-push-action action to v6.14.0 ([#24](https://github.com/jakepage91/hello-distr/issues/24)) ([90f1921](https://github.com/jakepage91/hello-distr/commit/90f192165556657c6ad6a779e75cdf904ce5ea72))
* **deps:** update docker/build-push-action action to v6.15.0 ([#50](https://github.com/jakepage91/hello-distr/issues/50)) ([68620fa](https://github.com/jakepage91/hello-distr/commit/68620fae555be9f22440c93af5cac17ea686a0c6))
* **deps:** update docker/build-push-action action to v6.16.0 ([#164](https://github.com/jakepage91/hello-distr/issues/164)) ([8f042d6](https://github.com/jakepage91/hello-distr/commit/8f042d6535a2e12a19558d2e425d60b2ef758d41))
* **deps:** update docker/build-push-action action to v6.17.0 ([#210](https://github.com/jakepage91/hello-distr/issues/210)) ([8383ce1](https://github.com/jakepage91/hello-distr/commit/8383ce1570dc1775038891b84f1ef82607123fac))
* **deps:** update docker/build-push-action action to v6.18.0 ([#221](https://github.com/jakepage91/hello-distr/issues/221)) ([7d736b4](https://github.com/jakepage91/hello-distr/commit/7d736b412c151e65a8f39174c518ca5ab279f6a1))
* **deps:** update docker/login-action action to v3.4.0 ([#105](https://github.com/jakepage91/hello-distr/issues/105)) ([9b3696d](https://github.com/jakepage91/hello-distr/commit/9b3696df11263f2b1298cb2237e36a4c13333eee))
* **deps:** update docker/metadata-action action to v5.7.0 ([#51](https://github.com/jakepage91/hello-distr/issues/51)) ([2c84dd9](https://github.com/jakepage91/hello-distr/commit/2c84dd9ecccb485b7b5588653b420e31a7dc7d13))
* **deps:** update docker/setup-buildx-action action to v3.10.0 ([#52](https://github.com/jakepage91/hello-distr/issues/52)) ([cdd684c](https://github.com/jakepage91/hello-distr/commit/cdd684cd203943f0f3f7a9ad045d5378e5fc9388))
* **deps:** update docker/setup-buildx-action action to v3.11.0 ([#271](https://github.com/jakepage91/hello-distr/issues/271)) ([1cabde9](https://github.com/jakepage91/hello-distr/commit/1cabde91cb16c43c3fbac0e56ffda3e0c0ed164c))
* **deps:** update docker/setup-buildx-action action to v3.11.1 ([#275](https://github.com/jakepage91/hello-distr/issues/275)) ([64b05a2](https://github.com/jakepage91/hello-distr/commit/64b05a2acc374c21c06e12b9dba99bad59f62f13))
* **deps:** update docker/setup-buildx-action action to v3.9.0 ([#32](https://github.com/jakepage91/hello-distr/issues/32)) ([1e5a8ec](https://github.com/jakepage91/hello-distr/commit/1e5a8ec8aec7c4f974bb38e1487fa855fe95cff6))
* **deps:** update googleapis/release-please-action action to v4.1.4 ([#54](https://github.com/jakepage91/hello-distr/issues/54)) ([92ef7c4](https://github.com/jakepage91/hello-distr/commit/92ef7c42933a6cb0e17a88674226a7ebfb2054d5))
* **deps:** update googleapis/release-please-action action to v4.1.5 ([#76](https://github.com/jakepage91/hello-distr/issues/76)) ([692bc0f](https://github.com/jakepage91/hello-distr/commit/692bc0fd75e12e28623285d5ec227ebfb8fa789c))
* **deps:** update googleapis/release-please-action action to v4.2.0 ([#81](https://github.com/jakepage91/hello-distr/issues/81)) ([464a475](https://github.com/jakepage91/hello-distr/commit/464a475cb8edb5b014f7c6f6a8d3b2dca23321fe))
* **deps:** update postgres docker tag to v17.4 ([#18](https://github.com/jakepage91/hello-distr/issues/18)) ([855e3b0](https://github.com/jakepage91/hello-distr/commit/855e3b00fa83ae6ae97f80b09a2db15b240b1505))
* **deps:** update python docker tag to v3.13 ([#20](https://github.com/jakepage91/hello-distr/issues/20)) ([f8e3fda](https://github.com/jakepage91/hello-distr/commit/f8e3fda8b927e7a04cd43fab66c9e0fe681f5309))
* **deps:** update react monorepo ([#11](https://github.com/jakepage91/hello-distr/issues/11)) ([d194191](https://github.com/jakepage91/hello-distr/commit/d194191b2400137a20f29efef9987d783f1d77f4))
* **deps:** update react monorepo ([#126](https://github.com/jakepage91/hello-distr/issues/126)) ([ae4df02](https://github.com/jakepage91/hello-distr/commit/ae4df029420a0f1d8f0a96859276c09c94c2ad1d))
* **deps:** update react monorepo to v19.1.4 ([#204](https://github.com/jakepage91/hello-distr/issues/204)) ([db09432](https://github.com/jakepage91/hello-distr/commit/db09432d56952b439e6d7756d93d1838b7301e7b))
* **deps:** update typescript-eslint monorepo to v8.25.0 ([#21](https://github.com/jakepage91/hello-distr/issues/21)) ([986dfde](https://github.com/jakepage91/hello-distr/commit/986dfde5bf7b40e74dc556b4906a27c29fda6402))
* **deps:** update typescript-eslint monorepo to v8.26.0 ([#71](https://github.com/jakepage91/hello-distr/issues/71)) ([243de4c](https://github.com/jakepage91/hello-distr/commit/243de4c795fea35126b15b4c2b3e0fc85d7b3a45))
* **deps:** update typescript-eslint monorepo to v8.26.1 ([#98](https://github.com/jakepage91/hello-distr/issues/98)) ([8376166](https://github.com/jakepage91/hello-distr/commit/83761663c8a757f9c0bd9674c4161b14a354084d))
* **deps:** update typescript-eslint monorepo to v8.27.0 ([#109](https://github.com/jakepage91/hello-distr/issues/109)) ([f120f89](https://github.com/jakepage91/hello-distr/commit/f120f89c42856009a4c206b21ca09a331f748a16))
* **deps:** update typescript-eslint monorepo to v8.28.0 ([#115](https://github.com/jakepage91/hello-distr/issues/115)) ([7c669ea](https://github.com/jakepage91/hello-distr/commit/7c669eaa8f711a4d5ba97ec6cb9a6efdee9ead6b))
* **deps:** update typescript-eslint monorepo to v8.29.0 ([#123](https://github.com/jakepage91/hello-distr/issues/123)) ([d884495](https://github.com/jakepage91/hello-distr/commit/d884495d3cd2b1c8861a64428f6fc97f2fdf6bb6))
* **deps:** update typescript-eslint monorepo to v8.29.1 ([#142](https://github.com/jakepage91/hello-distr/issues/142)) ([e969543](https://github.com/jakepage91/hello-distr/commit/e96954340298e3dc976627633d542d2fc3dd12e6))
* **deps:** update typescript-eslint monorepo to v8.30.1 ([#153](https://github.com/jakepage91/hello-distr/issues/153)) ([e8c4463](https://github.com/jakepage91/hello-distr/commit/e8c4463cdf4144e710768f83109931a8ede8ce59))
* **deps:** update typescript-eslint monorepo to v8.31.0 ([#159](https://github.com/jakepage91/hello-distr/issues/159)) ([b5b7ba4](https://github.com/jakepage91/hello-distr/commit/b5b7ba4cb0edbec7275f3397de1dd1ad07b4b00e))
* **deps:** update typescript-eslint monorepo to v8.31.1 ([#170](https://github.com/jakepage91/hello-distr/issues/170)) ([33a050d](https://github.com/jakepage91/hello-distr/commit/33a050dacd0f3f7d1fa92028098e0087f5c3f2db))
* **deps:** update typescript-eslint monorepo to v8.32.0 ([#189](https://github.com/jakepage91/hello-distr/issues/189)) ([4f3b244](https://github.com/jakepage91/hello-distr/commit/4f3b24450172b9d590598a574b0cf54079cc8a8c))
* **deps:** update typescript-eslint monorepo to v8.32.1 ([#205](https://github.com/jakepage91/hello-distr/issues/205)) ([47f7262](https://github.com/jakepage91/hello-distr/commit/47f72625b7c305ddf16ac96c24f7a7295fb70b87))
* **deps:** update typescript-eslint monorepo to v8.33.0 ([#222](https://github.com/jakepage91/hello-distr/issues/222)) ([0baffa8](https://github.com/jakepage91/hello-distr/commit/0baffa8b73b56cbf8c86129d5eaae96825655cb3))
* **deps:** update typescript-eslint monorepo to v8.33.1 ([#241](https://github.com/jakepage91/hello-distr/issues/241)) ([45a50c7](https://github.com/jakepage91/hello-distr/commit/45a50c7c173f019c1d813e3ba98c4652fd6161e0))
* **deps:** update typescript-eslint monorepo to v8.34.0 ([#262](https://github.com/jakepage91/hello-distr/issues/262)) ([b37d414](https://github.com/jakepage91/hello-distr/commit/b37d414debb42aee53faebc6ba5a4e5dd291cc40))
* **deps:** update typescript-eslint monorepo to v8.34.1 ([#272](https://github.com/jakepage91/hello-distr/issues/272)) ([8366cde](https://github.com/jakepage91/hello-distr/commit/8366cde0199e02e3a291b22aced550a2304cb8b8))
* **deps:** update typescript-eslint monorepo to v8.35.0 ([#287](https://github.com/jakepage91/hello-distr/issues/287)) ([b413b26](https://github.com/jakepage91/hello-distr/commit/b413b26d975bed9a5a6ed5c14b76c1657d80b8e9))
* **deps:** update typescript-eslint monorepo to v8.35.1 ([#297](https://github.com/jakepage91/hello-distr/issues/297)) ([cae4d95](https://github.com/jakepage91/hello-distr/commit/cae4d958d11f17c88740ae50016c71c162fc58f6))
* downgrade current version ([#23](https://github.com/jakepage91/hello-distr/issues/23)) ([4e53176](https://github.com/jakepage91/hello-distr/commit/4e531767c38496e890403ab5285201cb638eb619))
* initial commit ([d0ef3d9](https://github.com/jakepage91/hello-distr/commit/d0ef3d908894299e4f08e5d4966ad806f06aa95e))
* **main:** release 0.1.0 ([#22](https://github.com/jakepage91/hello-distr/issues/22)) ([e1fe24c](https://github.com/jakepage91/hello-distr/commit/e1fe24cb6dc822ef7cba14805d487e8c55af0785))
* **main:** release 0.1.1 ([#27](https://github.com/jakepage91/hello-distr/issues/27)) ([eb76bf9](https://github.com/jakepage91/hello-distr/commit/eb76bf9004d94ef0d05e972a2f9a8e262547304e))
* **main:** release 0.1.10 ([#99](https://github.com/jakepage91/hello-distr/issues/99)) ([a9c0170](https://github.com/jakepage91/hello-distr/commit/a9c017028979c6be5157528153ff3ec39ad0e189))
* **main:** release 0.1.2 ([#29](https://github.com/jakepage91/hello-distr/issues/29)) ([b658cbc](https://github.com/jakepage91/hello-distr/commit/b658cbc35abddd45f6c350bfcc5297d5195e370b))
* **main:** release 0.1.3 ([#31](https://github.com/jakepage91/hello-distr/issues/31)) ([cf3c1d8](https://github.com/jakepage91/hello-distr/commit/cf3c1d82cbba16be81c90a731d4dc06aac08f95c))
* **main:** release 0.1.4 ([#35](https://github.com/jakepage91/hello-distr/issues/35)) ([50b2f6e](https://github.com/jakepage91/hello-distr/commit/50b2f6e0bbe250e5791a90adf5a734e332db4587))
* **main:** release 0.1.5 ([#37](https://github.com/jakepage91/hello-distr/issues/37)) ([24bd80c](https://github.com/jakepage91/hello-distr/commit/24bd80cad92f8235279db3ccff3ea7069e449f2b))
* **main:** release 0.1.6 ([#48](https://github.com/jakepage91/hello-distr/issues/48)) ([f0af6ab](https://github.com/jakepage91/hello-distr/commit/f0af6abf2f60658575154324ea62eabeb5cb039a))
* **main:** release 0.1.7 ([#49](https://github.com/jakepage91/hello-distr/issues/49)) ([9aaa253](https://github.com/jakepage91/hello-distr/commit/9aaa253924f62cf4aad1d7f2f61e5c421e6e2596))
* **main:** release 0.1.8 ([#75](https://github.com/jakepage91/hello-distr/issues/75)) ([6d21051](https://github.com/jakepage91/hello-distr/commit/6d2105162a51308abde25fe3ffa2cb9bc1f4766b))
* **main:** release 0.1.9 ([#78](https://github.com/jakepage91/hello-distr/issues/78)) ([b03cfee](https://github.com/jakepage91/hello-distr/commit/b03cfee0aa4b4b12f5b33129771adcffa8ab2114))
* push to demo distr ([#25](https://github.com/jakepage91/hello-distr/issues/25)) ([2864d8e](https://github.com/jakepage91/hello-distr/commit/2864d8e906805bc42629945b5edd0b5de37d1df5))
* update docs ([#36](https://github.com/jakepage91/hello-distr/issues/36)) ([8130357](https://github.com/jakepage91/hello-distr/commit/81303576be658c2182b0b7fd23a49525108ecf31))

## [0.1.10](https://github.com/glasskube/hello-distr/compare/0.1.9...0.1.10) (2025-04-23)


### Bug Fixes

* **deps:** update dependency @heroui/button to v2.2.17 ([#132](https://github.com/glasskube/hello-distr/issues/132)) ([8c3d09c](https://github.com/glasskube/hello-distr/commit/8c3d09c5741d40770bd0c2ea0ceeaeb389dc30a3))
* **deps:** update dependency @heroui/input to v2.4.17 ([#133](https://github.com/glasskube/hello-distr/issues/133)) ([389a515](https://github.com/glasskube/hello-distr/commit/389a51577dcad8cf0294fbcad91531b44ebcbcbe))
* **deps:** update dependency @heroui/kbd to v2.2.13 ([#134](https://github.com/glasskube/hello-distr/issues/134)) ([b3415dd](https://github.com/glasskube/hello-distr/commit/b3415dd93d299721c4ee570a81c6a34ab081f25a))
* **deps:** update dependency @heroui/link to v2.2.14 ([#135](https://github.com/glasskube/hello-distr/issues/135)) ([76371fa](https://github.com/glasskube/hello-distr/commit/76371fa659ead54adee78ceac482e187aa45f44c))
* **deps:** update dependency @heroui/listbox to v2.3.16 ([#136](https://github.com/glasskube/hello-distr/issues/136)) ([fd6c1f0](https://github.com/glasskube/hello-distr/commit/fd6c1f04ac5fba5b5d3bd77c39247ddc69928482))
* **deps:** update dependency @heroui/navbar to v2.2.15 ([#137](https://github.com/glasskube/hello-distr/issues/137)) ([727256c](https://github.com/glasskube/hello-distr/commit/727256c22bfd4713473beb1de597bf6873b8fd53))
* **deps:** update dependency @heroui/snippet to v2.2.18 ([#138](https://github.com/glasskube/hello-distr/issues/138)) ([8ec068f](https://github.com/glasskube/hello-distr/commit/8ec068f95fc76704d4bbaffe5ae7455106045cf6))
* **deps:** update dependency @heroui/switch to v2.2.15 ([#139](https://github.com/glasskube/hello-distr/issues/139)) ([d73e55c](https://github.com/glasskube/hello-distr/commit/d73e55c9b687e188551554c487687c175564f0bf))
* **deps:** update dependency @heroui/system to v2.4.13 ([#140](https://github.com/glasskube/hello-distr/issues/140)) ([22c5b37](https://github.com/glasskube/hello-distr/commit/22c5b37d4d30aa561fe59983033f874802acba10))
* **deps:** update dependency @heroui/theme to v2.4.12 ([#94](https://github.com/glasskube/hello-distr/issues/94)) ([cb8cb78](https://github.com/glasskube/hello-distr/commit/cb8cb783b715658dfb8fec1c236085ba43a2c116))
* **deps:** update dependency @heroui/theme to v2.4.13 ([#141](https://github.com/glasskube/hello-distr/issues/141)) ([27539d0](https://github.com/glasskube/hello-distr/commit/27539d0a556e1ecce9b16311ffea2d9eb151ba25))
* **deps:** update dependency @react-aria/visually-hidden to v3.8.21 ([#100](https://github.com/glasskube/hello-distr/issues/100)) ([034f101](https://github.com/glasskube/hello-distr/commit/034f101265d4cb0372be1b72c2baa453c7bd2abc))
* **deps:** update dependency framer-motion to v12.4.11 ([#97](https://github.com/glasskube/hello-distr/issues/97)) ([d40dc7f](https://github.com/glasskube/hello-distr/commit/d40dc7f6d9d4d12fb2cf8e1ae72b1ccbf6faed50))
* **deps:** update dependency framer-motion to v12.5.0 ([#102](https://github.com/glasskube/hello-distr/issues/102)) ([60ba856](https://github.com/glasskube/hello-distr/commit/60ba856107fba18b1a8810a6b65e7c1460c2fb01))
* **deps:** update dependency framer-motion to v12.6.0 ([#118](https://github.com/glasskube/hello-distr/issues/118)) ([53e47a5](https://github.com/glasskube/hello-distr/commit/53e47a5c5272c809a584f4d216b0cc478640da80))
* **deps:** update dependency framer-motion to v12.6.2 ([#120](https://github.com/glasskube/hello-distr/issues/120)) ([c5a6785](https://github.com/glasskube/hello-distr/commit/c5a6785661637739b9347350a799bb40ccd50729))
* **deps:** update dependency framer-motion to v12.6.3 ([#125](https://github.com/glasskube/hello-distr/issues/125)) ([01326cf](https://github.com/glasskube/hello-distr/commit/01326cf79d813734dbacefd9a6cbaead26b5cd79))
* **deps:** update dependency framer-motion to v12.6.5 ([#147](https://github.com/glasskube/hello-distr/issues/147)) ([1e4af0c](https://github.com/glasskube/hello-distr/commit/1e4af0c473975a1eb9a930ec85a48ae8dcedd341))
* **deps:** update dependency framer-motion to v12.7.2 ([#151](https://github.com/glasskube/hello-distr/issues/151)) ([42520ec](https://github.com/glasskube/hello-distr/commit/42520ecacb2c160681996086e8ce0d6061d9bacc))
* **deps:** update dependency framer-motion to v12.7.3 ([#154](https://github.com/glasskube/hello-distr/issues/154)) ([0ac090a](https://github.com/glasskube/hello-distr/commit/0ac090afe0a6f3f762f0bb1a36ef6305172324e9))
* **deps:** update dependency framer-motion to v12.7.4 ([#155](https://github.com/glasskube/hello-distr/issues/155)) ([891aed1](https://github.com/glasskube/hello-distr/commit/891aed1c8e02148d586773785685181c1f8036e6))
* **deps:** update dependency framer-motion to v12.8.0 ([#162](https://github.com/glasskube/hello-distr/issues/162)) ([e6c83a5](https://github.com/glasskube/hello-distr/commit/e6c83a5db963be4b8101919a5f7280a45d734547))
* **deps:** update dependency intl-messageformat to v10.7.16 ([#112](https://github.com/glasskube/hello-distr/issues/112)) ([e635201](https://github.com/glasskube/hello-distr/commit/e63520104f24ae6c28effcea520e96dcbcfc6e77))
* **deps:** update dependency next-themes to v0.4.5 ([#96](https://github.com/glasskube/hello-distr/issues/96)) ([fd97715](https://github.com/glasskube/hello-distr/commit/fd97715fbf513d05cd933e6a36f81bc5633737cc))
* **deps:** update dependency next-themes to v0.4.6 ([#103](https://github.com/glasskube/hello-distr/issues/103)) ([76ce99e](https://github.com/glasskube/hello-distr/commit/76ce99ea400757d7153f324653d2b944a9cca89e))
* **deps:** update nextjs monorepo to v15.2.2 ([#101](https://github.com/glasskube/hello-distr/issues/101)) ([a2056c3](https://github.com/glasskube/hello-distr/commit/a2056c3325334099301ee4110fcb07562566ee4d))
* **deps:** update nextjs monorepo to v15.2.3 ([#107](https://github.com/glasskube/hello-distr/issues/107)) ([ec6da4d](https://github.com/glasskube/hello-distr/commit/ec6da4df0d8100d3a629479897eaf26bd1308a25))
* **deps:** update nextjs monorepo to v15.2.4 ([#116](https://github.com/glasskube/hello-distr/issues/116)) ([f070d2d](https://github.com/glasskube/hello-distr/commit/f070d2dca0691b4193de1e4692159bd1164fc898))
* **deps:** update nextjs monorepo to v15.2.5 ([#143](https://github.com/glasskube/hello-distr/issues/143)) ([4595c59](https://github.com/glasskube/hello-distr/commit/4595c59aed54df4885ce68b1ceb4b1e130b4a9ab))
* **deps:** update nextjs monorepo to v15.3.0 ([#145](https://github.com/glasskube/hello-distr/issues/145)) ([5edd7ed](https://github.com/glasskube/hello-distr/commit/5edd7ed02719bb678f22547de993e7203e642ba5))
* **deps:** update nextjs monorepo to v15.3.1 ([#156](https://github.com/glasskube/hello-distr/issues/156)) ([30bbc8c](https://github.com/glasskube/hello-distr/commit/30bbc8cdbb188bfc6ef68fb2fe046b73e0d26b09))
* **deps:** update react monorepo to v19.1.0 ([#122](https://github.com/glasskube/hello-distr/issues/122)) ([57be632](https://github.com/glasskube/hello-distr/commit/57be632f855efa02985e1acb5fb452737f18806e))
* **deps:** update react-spectrum monorepo ([#149](https://github.com/glasskube/hello-distr/issues/149)) ([e0a74e8](https://github.com/glasskube/hello-distr/commit/e0a74e80175c2595bfb5740864c1cecd7628f156))


### Other

* **deps:** bump @babel/runtime from 7.26.9 to 7.26.10 in /frontend ([#104](https://github.com/glasskube/hello-distr/issues/104)) ([d42b30b](https://github.com/glasskube/hello-distr/commit/d42b30b11cdfcc2905771512de4e8ef3b24c90f3))
* **deps:** update caddy docker tag to v2.10.0 ([#160](https://github.com/glasskube/hello-distr/issues/160)) ([05a117a](https://github.com/glasskube/hello-distr/commit/05a117a23a567d51e5100c6b7ca7d84a26e8d80a))
* **deps:** update dependency @types/node to v22.13.11 ([#110](https://github.com/glasskube/hello-distr/issues/110)) ([e3b86ca](https://github.com/glasskube/hello-distr/commit/e3b86ca45e3bac93d33c988a8643d9347041033e))
* **deps:** update dependency @types/node to v22.13.13 ([#114](https://github.com/glasskube/hello-distr/issues/114)) ([dc80494](https://github.com/glasskube/hello-distr/commit/dc804942af0c412bea3e9df62e7654cfc35891ca))
* **deps:** update dependency @types/node to v22.13.14 ([#121](https://github.com/glasskube/hello-distr/issues/121)) ([453623b](https://github.com/glasskube/hello-distr/commit/453623b526269d748bb0967d25f826af6b9203a4))
* **deps:** update dependency @types/node to v22.13.17 ([#124](https://github.com/glasskube/hello-distr/issues/124)) ([d9487f4](https://github.com/glasskube/hello-distr/commit/d9487f473d7df6504960cd62a86aad0a91491dd1))
* **deps:** update dependency @types/node to v22.14.0 ([#128](https://github.com/glasskube/hello-distr/issues/128)) ([a954118](https://github.com/glasskube/hello-distr/commit/a95411890ebe95c953fda088d016b763901c0e59))
* **deps:** update dependency @types/node to v22.14.1 ([#150](https://github.com/glasskube/hello-distr/issues/150)) ([72fd9e8](https://github.com/glasskube/hello-distr/commit/72fd9e82d33b4e202afb8cc41b07ce4f53c128e2))
* **deps:** update dependency @types/react to v19.0.11 ([#106](https://github.com/glasskube/hello-distr/issues/106)) ([10e7db5](https://github.com/glasskube/hello-distr/commit/10e7db585c03d7a71a97643d27324bd06b6d1ca8))
* **deps:** update dependency @types/react to v19.0.12 ([#108](https://github.com/glasskube/hello-distr/issues/108)) ([eb729b7](https://github.com/glasskube/hello-distr/commit/eb729b708f9cae894d692421fbd4c34cf786692b))
* **deps:** update dependency @types/react to v19.1.1 ([#148](https://github.com/glasskube/hello-distr/issues/148)) ([a722779](https://github.com/glasskube/hello-distr/commit/a72277954d25c54574627095d21df4fba1cfc206))
* **deps:** update dependency @types/react to v19.1.2 ([#152](https://github.com/glasskube/hello-distr/issues/152)) ([e794a1c](https://github.com/glasskube/hello-distr/commit/e794a1cf4424711c009f96990820a878c782fc3d))
* **deps:** update dependency @types/react-dom to v19.1.2 ([#144](https://github.com/glasskube/hello-distr/issues/144)) ([b6aed91](https://github.com/glasskube/hello-distr/commit/b6aed91bc63afd348f7432ea4564f73d07d32644))
* **deps:** update dependency eslint to v9.23.0 ([#111](https://github.com/glasskube/hello-distr/issues/111)) ([30b91b7](https://github.com/glasskube/hello-distr/commit/30b91b7a2df48fb335654fc6d9117afaf2a7ddfb))
* **deps:** update dependency eslint to v9.24.0 ([#130](https://github.com/glasskube/hello-distr/issues/130)) ([7d4feb1](https://github.com/glasskube/hello-distr/commit/7d4feb11b9f0dca596114d6d48b997f5b09fbe32))
* **deps:** update dependency eslint to v9.25.0 ([#157](https://github.com/glasskube/hello-distr/issues/157)) ([bfe03f3](https://github.com/glasskube/hello-distr/commit/bfe03f38cf9d68c6aa82fb1eb099fffa7eba73b2))
* **deps:** update dependency eslint to v9.25.1 ([#158](https://github.com/glasskube/hello-distr/issues/158)) ([f483362](https://github.com/glasskube/hello-distr/commit/f48336234d699799407bcb017942351a64cc620b))
* **deps:** update dependency eslint-config-prettier to v10.1.2 ([#146](https://github.com/glasskube/hello-distr/issues/146)) ([25eb9c7](https://github.com/glasskube/hello-distr/commit/25eb9c7e338372bf1246d13f858b20253d686e89))
* **deps:** update dependency eslint-plugin-n to v17.17.0 ([#119](https://github.com/glasskube/hello-distr/issues/119)) ([4eff84b](https://github.com/glasskube/hello-distr/commit/4eff84bdf9a880d8f21a036d0ae97e5d9177d8f5))
* **deps:** update dependency eslint-plugin-prettier to v5.2.4 ([#113](https://github.com/glasskube/hello-distr/issues/113)) ([02adaa2](https://github.com/glasskube/hello-distr/commit/02adaa2bfcbf4a4a017748082d40cc297c855d4e))
* **deps:** update dependency eslint-plugin-prettier to v5.2.5 ([#117](https://github.com/glasskube/hello-distr/issues/117)) ([e13be0a](https://github.com/glasskube/hello-distr/commit/e13be0af131dec56a494ff867459ccb3f11f9391))
* **deps:** update dependency eslint-plugin-prettier to v5.2.6 ([#127](https://github.com/glasskube/hello-distr/issues/127)) ([a16c8cc](https://github.com/glasskube/hello-distr/commit/a16c8cc19285d133cd05ab3f8f9238f69c268fc2))
* **deps:** update dependency eslint-plugin-react to v7.37.5 ([#129](https://github.com/glasskube/hello-distr/issues/129)) ([d4d61d4](https://github.com/glasskube/hello-distr/commit/d4d61d41982f358a6ffa7c5d8b2bb4e04b8602d2))
* **deps:** update dependency tailwind-variants to v1 ([#95](https://github.com/glasskube/hello-distr/issues/95)) ([6d33595](https://github.com/glasskube/hello-distr/commit/6d3359534e110d58f22e40afd42e8652be1c6c73))
* **deps:** update dependency typescript to v5.8.3 ([#131](https://github.com/glasskube/hello-distr/issues/131)) ([66717c4](https://github.com/glasskube/hello-distr/commit/66717c43e6a56912b049bdec9e1b8d1abd213c92))
* **deps:** update docker/login-action action to v3.4.0 ([#105](https://github.com/glasskube/hello-distr/issues/105)) ([9b3696d](https://github.com/glasskube/hello-distr/commit/9b3696df11263f2b1298cb2237e36a4c13333eee))
* **deps:** update react monorepo ([#126](https://github.com/glasskube/hello-distr/issues/126)) ([ae4df02](https://github.com/glasskube/hello-distr/commit/ae4df029420a0f1d8f0a96859276c09c94c2ad1d))
* **deps:** update typescript-eslint monorepo to v8.26.1 ([#98](https://github.com/glasskube/hello-distr/issues/98)) ([8376166](https://github.com/glasskube/hello-distr/commit/83761663c8a757f9c0bd9674c4161b14a354084d))
* **deps:** update typescript-eslint monorepo to v8.27.0 ([#109](https://github.com/glasskube/hello-distr/issues/109)) ([f120f89](https://github.com/glasskube/hello-distr/commit/f120f89c42856009a4c206b21ca09a331f748a16))
* **deps:** update typescript-eslint monorepo to v8.28.0 ([#115](https://github.com/glasskube/hello-distr/issues/115)) ([7c669ea](https://github.com/glasskube/hello-distr/commit/7c669eaa8f711a4d5ba97ec6cb9a6efdee9ead6b))
* **deps:** update typescript-eslint monorepo to v8.29.0 ([#123](https://github.com/glasskube/hello-distr/issues/123)) ([d884495](https://github.com/glasskube/hello-distr/commit/d884495d3cd2b1c8861a64428f6fc97f2fdf6bb6))
* **deps:** update typescript-eslint monorepo to v8.29.1 ([#142](https://github.com/glasskube/hello-distr/issues/142)) ([e969543](https://github.com/glasskube/hello-distr/commit/e96954340298e3dc976627633d542d2fc3dd12e6))
* **deps:** update typescript-eslint monorepo to v8.30.1 ([#153](https://github.com/glasskube/hello-distr/issues/153)) ([e8c4463](https://github.com/glasskube/hello-distr/commit/e8c4463cdf4144e710768f83109931a8ede8ce59))
* **deps:** update typescript-eslint monorepo to v8.31.0 ([#159](https://github.com/glasskube/hello-distr/issues/159)) ([b5b7ba4](https://github.com/glasskube/hello-distr/commit/b5b7ba4cb0edbec7275f3397de1dd1ad07b4b00e))

## [0.1.9](https://github.com/glasskube/hello-distr/compare/0.1.8...0.1.9) (2025-03-10)


### Bug Fixes

* **deps:** update dependency @heroui/button to v2.2.16 ([#83](https://github.com/glasskube/hello-distr/issues/83)) ([04cc1f4](https://github.com/glasskube/hello-distr/commit/04cc1f4352481235c7d27895f33937f56ed512eb))
* **deps:** update dependency @heroui/code to v2.2.12 ([#84](https://github.com/glasskube/hello-distr/issues/84)) ([9a54727](https://github.com/glasskube/hello-distr/commit/9a54727d2aa3c6038f0102c93efa6d84d6ff1b8c))
* **deps:** update dependency @heroui/input to v2.4.16 ([#85](https://github.com/glasskube/hello-distr/issues/85)) ([2d00276](https://github.com/glasskube/hello-distr/commit/2d002768f142c1009e6a49e0d556ef95cfc041bb))
* **deps:** update dependency @heroui/kbd to v2.2.12 ([#86](https://github.com/glasskube/hello-distr/issues/86)) ([895ca17](https://github.com/glasskube/hello-distr/commit/895ca177caac049ea1d9285ab207f2ce87e662a1))
* **deps:** update dependency @heroui/link to v2.2.13 ([#87](https://github.com/glasskube/hello-distr/issues/87)) ([7f3bb25](https://github.com/glasskube/hello-distr/commit/7f3bb256d4e069a49e715089dc0a49a1c2862068))
* **deps:** update dependency @heroui/listbox to v2.3.15 ([#88](https://github.com/glasskube/hello-distr/issues/88)) ([45eb8f6](https://github.com/glasskube/hello-distr/commit/45eb8f688a6e02c5a684db41de0c2c25771dc562))
* **deps:** update dependency @heroui/navbar to v2.2.14 ([#89](https://github.com/glasskube/hello-distr/issues/89)) ([dfba164](https://github.com/glasskube/hello-distr/commit/dfba16463cb0513804de8962052f52ba44584388))
* **deps:** update dependency @heroui/snippet to v2.2.17 ([#90](https://github.com/glasskube/hello-distr/issues/90)) ([0516690](https://github.com/glasskube/hello-distr/commit/0516690b7eabb6dc41634bf5e6fac9d1f789e358))
* **deps:** update dependency @heroui/switch to v2.2.14 ([#91](https://github.com/glasskube/hello-distr/issues/91)) ([25525fa](https://github.com/glasskube/hello-distr/commit/25525faef2a346884da5ff1bcfcbc9727b8969c7))
* **deps:** update dependency @heroui/system to v2.4.12 ([#92](https://github.com/glasskube/hello-distr/issues/92)) ([a299044](https://github.com/glasskube/hello-distr/commit/a299044a2f6ae8a857c0f995620de4f3ed02b5ee))
* **deps:** update react-spectrum monorepo ([#77](https://github.com/glasskube/hello-distr/issues/77)) ([0afdbce](https://github.com/glasskube/hello-distr/commit/0afdbcee11fd50b7a7417f0812813cb0d84779e8))


### Other

* **deps:** update dependency @types/node to v22.13.10 ([#82](https://github.com/glasskube/hello-distr/issues/82)) ([31cae12](https://github.com/glasskube/hello-distr/commit/31cae125c55642713e96b6ff2ea46c0ee92e938b))
* **deps:** update dependency autoprefixer to v10.4.21 ([#93](https://github.com/glasskube/hello-distr/issues/93)) ([648882a](https://github.com/glasskube/hello-distr/commit/648882a1c8db82fc7ea73e03cd65296bbb239fe6))
* **deps:** update dependency eslint to v9.22.0 ([#80](https://github.com/glasskube/hello-distr/issues/80)) ([eceb238](https://github.com/glasskube/hello-distr/commit/eceb23876aaf3dfbb8a0a0b7ba3638af71d8f0cc))
* **deps:** update dependency eslint-config-prettier to v10.1.1 ([#79](https://github.com/glasskube/hello-distr/issues/79)) ([baaae94](https://github.com/glasskube/hello-distr/commit/baaae9440e96d56bf5e07ac5f0a8822d20138e62))
* **deps:** update googleapis/release-please-action action to v4.2.0 ([#81](https://github.com/glasskube/hello-distr/issues/81)) ([464a475](https://github.com/glasskube/hello-distr/commit/464a475cb8edb5b014f7c6f6a8d3b2dca23321fe))

## [0.1.8](https://github.com/glasskube/hello-distr/compare/0.1.7...0.1.8) (2025-03-06)


### Other

* **deps:** update dependency eslint-plugin-n to v17.16.2 ([#74](https://github.com/glasskube/hello-distr/issues/74)) ([fc188e5](https://github.com/glasskube/hello-distr/commit/fc188e5e40d326d6c659b2e4b53c312204a09119))
* **deps:** update googleapis/release-please-action action to v4.1.5 ([#76](https://github.com/glasskube/hello-distr/issues/76)) ([692bc0f](https://github.com/glasskube/hello-distr/commit/692bc0fd75e12e28623285d5ec227ebfb8fa789c))

## [0.1.7](https://github.com/glasskube/hello-distr/compare/0.1.6...0.1.7) (2025-03-04)


### Bug Fixes

* **deps:** update dependency @heroui/button to v2.2.15 ([#55](https://github.com/glasskube/hello-distr/issues/55)) ([6cbac86](https://github.com/glasskube/hello-distr/commit/6cbac86d4940759d53ed11a5626780f6ffbb334f))
* **deps:** update dependency @heroui/code to v2.2.11 ([#56](https://github.com/glasskube/hello-distr/issues/56)) ([76d7183](https://github.com/glasskube/hello-distr/commit/76d7183e952345770e8a331bfd7ea9d86affd285))
* **deps:** update dependency @heroui/input to v2.4.15 ([#57](https://github.com/glasskube/hello-distr/issues/57)) ([390a3c2](https://github.com/glasskube/hello-distr/commit/390a3c2b57a547c7e825f52aac5c69a79d4e80d0))
* **deps:** update dependency @heroui/kbd to v2.2.11 ([#58](https://github.com/glasskube/hello-distr/issues/58)) ([a0353bb](https://github.com/glasskube/hello-distr/commit/a0353bb0e1495da0b0f49f85f3c03fd15ff8c21f))
* **deps:** update dependency @heroui/link to v2.2.12 ([#59](https://github.com/glasskube/hello-distr/issues/59)) ([e76577c](https://github.com/glasskube/hello-distr/commit/e76577cb21e30df5174c34e550e7c113d0226f2a))
* **deps:** update dependency @heroui/listbox to v2.3.14 ([#60](https://github.com/glasskube/hello-distr/issues/60)) ([3e161d7](https://github.com/glasskube/hello-distr/commit/3e161d7b56cf29fc1a3319adcbae4580844bcc39))
* **deps:** update dependency @heroui/navbar to v2.2.13 ([#61](https://github.com/glasskube/hello-distr/issues/61)) ([f949c71](https://github.com/glasskube/hello-distr/commit/f949c711e497b4f7cea13c0e5ae1782a7dedc316))
* **deps:** update dependency @heroui/snippet to v2.2.16 ([#62](https://github.com/glasskube/hello-distr/issues/62)) ([0bbc68d](https://github.com/glasskube/hello-distr/commit/0bbc68d145fd9c5c897a7db893cefede79604f3a))
* **deps:** update dependency @heroui/switch to v2.2.13 ([#64](https://github.com/glasskube/hello-distr/issues/64)) ([9b97939](https://github.com/glasskube/hello-distr/commit/9b979391dc7f11b8104a6675f2fa2151e7fd95af))
* **deps:** update dependency @heroui/system to v2.4.11 ([#65](https://github.com/glasskube/hello-distr/issues/65)) ([cd64328](https://github.com/glasskube/hello-distr/commit/cd643283f6b326e54e866bfb41e98cdfbc15ad16))
* **deps:** update dependency @heroui/theme to v2.4.11 ([#67](https://github.com/glasskube/hello-distr/issues/67)) ([3c9dcd7](https://github.com/glasskube/hello-distr/commit/3c9dcd7c20473f4f8ea7edb77a5c7acb6f8e1540))
* **deps:** update dependency framer-motion to v12.4.10 ([#70](https://github.com/glasskube/hello-distr/issues/70)) ([f2d817f](https://github.com/glasskube/hello-distr/commit/f2d817f4231b34f1adbf57c2bf1d59c7f10d05fa))
* **deps:** update nextjs monorepo to v15.2.0 ([#40](https://github.com/glasskube/hello-distr/issues/40)) ([d56ea7a](https://github.com/glasskube/hello-distr/commit/d56ea7a6d9b782691e90d7de16e01c503d852c50))
* **deps:** update nextjs monorepo to v15.2.1 ([#73](https://github.com/glasskube/hello-distr/issues/73)) ([b4f3745](https://github.com/glasskube/hello-distr/commit/b4f37454e1641685cbddf20dd38bbe3c9b894f5f))
* **deps:** update react monorepo (major) ([#46](https://github.com/glasskube/hello-distr/issues/46)) ([74f3d0e](https://github.com/glasskube/hello-distr/commit/74f3d0e9d740f888a68ca38f5e81db08b5f58049))


### Other

* **deps:** update dependency @react-types/shared to v3.27.0 ([#13](https://github.com/glasskube/hello-distr/issues/13)) ([3acc53e](https://github.com/glasskube/hello-distr/commit/3acc53e10a3f723ce9304d5853af7c05408e68e9))
* **deps:** update dependency @types/node to v20.17.21 ([#63](https://github.com/glasskube/hello-distr/issues/63)) ([8ff5989](https://github.com/glasskube/hello-distr/commit/8ff5989d6d6be075275492b716fcdf0247771ecd))
* **deps:** update dependency @types/node to v20.17.22 ([#66](https://github.com/glasskube/hello-distr/issues/66)) ([7594aca](https://github.com/glasskube/hello-distr/commit/7594aca07cb16206e359f0b88bd2dd7c85a111d5))
* **deps:** update dependency @types/node to v22 ([#41](https://github.com/glasskube/hello-distr/issues/41)) ([2c654f9](https://github.com/glasskube/hello-distr/commit/2c654f9fbb230957d9617b537f6f3549508647a1))
* **deps:** update dependency @types/node to v22.13.9 ([#72](https://github.com/glasskube/hello-distr/issues/72)) ([403c01b](https://github.com/glasskube/hello-distr/commit/403c01bd50ee712b86f5ed1e31938a014b975455))
* **deps:** update dependency autoprefixer to v10.4.20 ([#7](https://github.com/glasskube/hello-distr/issues/7)) ([e3dec4a](https://github.com/glasskube/hello-distr/commit/e3dec4a6824da52299d665993864397f0797f2ae))
* **deps:** update dependency eslint to v9 ([#42](https://github.com/glasskube/hello-distr/issues/42)) ([0b9086b](https://github.com/glasskube/hello-distr/commit/0b9086b864905f5edf45bfb44f234794ab4bac08))
* **deps:** update dependency eslint-plugin-n to v17 ([#53](https://github.com/glasskube/hello-distr/issues/53)) ([5c5e25c](https://github.com/glasskube/hello-distr/commit/5c5e25c2c351e5bb71dcf3b1d431bb621d26159d))
* **deps:** update dependency postcss to v8.5.3 ([#15](https://github.com/glasskube/hello-distr/issues/15)) ([827f6f0](https://github.com/glasskube/hello-distr/commit/827f6f0d7ffc92aac4266afe434405da4cee9a83))
* **deps:** update dependency prettier to v3.5.3 ([#69](https://github.com/glasskube/hello-distr/issues/69)) ([c6ad5e1](https://github.com/glasskube/hello-distr/commit/c6ad5e1e5e47d45cb0819bd5ecd0609455824cba))
* **deps:** update dependency typescript to v5.7.3 ([#17](https://github.com/glasskube/hello-distr/issues/17)) ([a62c139](https://github.com/glasskube/hello-distr/commit/a62c1398f8a90fefa1a05f7fa32587aec4d6941b))
* **deps:** update dependency typescript to v5.8.2 ([#68](https://github.com/glasskube/hello-distr/issues/68)) ([40b1c83](https://github.com/glasskube/hello-distr/commit/40b1c83d0f1df60d155258593a68bb8c1af0d8ad))
* **deps:** update docker/build-push-action action to v6.15.0 ([#50](https://github.com/glasskube/hello-distr/issues/50)) ([68620fa](https://github.com/glasskube/hello-distr/commit/68620fae555be9f22440c93af5cac17ea686a0c6))
* **deps:** update docker/metadata-action action to v5.7.0 ([#51](https://github.com/glasskube/hello-distr/issues/51)) ([2c84dd9](https://github.com/glasskube/hello-distr/commit/2c84dd9ecccb485b7b5588653b420e31a7dc7d13))
* **deps:** update docker/setup-buildx-action action to v3.10.0 ([#52](https://github.com/glasskube/hello-distr/issues/52)) ([cdd684c](https://github.com/glasskube/hello-distr/commit/cdd684cd203943f0f3f7a9ad045d5378e5fc9388))
* **deps:** update googleapis/release-please-action action to v4.1.4 ([#54](https://github.com/glasskube/hello-distr/issues/54)) ([92ef7c4](https://github.com/glasskube/hello-distr/commit/92ef7c42933a6cb0e17a88674226a7ebfb2054d5))
* **deps:** update react monorepo ([#11](https://github.com/glasskube/hello-distr/issues/11)) ([d194191](https://github.com/glasskube/hello-distr/commit/d194191b2400137a20f29efef9987d783f1d77f4))
* **deps:** update typescript-eslint monorepo to v8.25.0 ([#21](https://github.com/glasskube/hello-distr/issues/21)) ([986dfde](https://github.com/glasskube/hello-distr/commit/986dfde5bf7b40e74dc556b4906a27c29fda6402))
* **deps:** update typescript-eslint monorepo to v8.26.0 ([#71](https://github.com/glasskube/hello-distr/issues/71)) ([243de4c](https://github.com/glasskube/hello-distr/commit/243de4c795fea35126b15b4c2b3e0fc85d7b3a45))

## [0.1.6](https://github.com/glasskube/hello-distr/compare/0.1.5...0.1.6) (2025-02-26)


### Bug Fixes

* **deps:** update dependency framer-motion to v12 ([#45](https://github.com/glasskube/hello-distr/issues/45)) ([0c36c2b](https://github.com/glasskube/hello-distr/commit/0c36c2b5a7d8448d74121ba3d4a898f8ca65bbac))
* extra hosts for frontend container ([#47](https://github.com/glasskube/hello-distr/issues/47)) ([04f6bb1](https://github.com/glasskube/hello-distr/commit/04f6bb198c6480836a45f360ef7f8247df378249))


### Other

* **deps:** replace dependency eslint-plugin-node with eslint-plugin-n ^14.0.0 ([#5](https://github.com/glasskube/hello-distr/issues/5)) ([6d9ffb3](https://github.com/glasskube/hello-distr/commit/6d9ffb328a9b889fffd37f06b2d7e5cbc890fca0))
* **deps:** update dependency eslint-config-prettier to v10 ([#43](https://github.com/glasskube/hello-distr/issues/43)) ([d3204da](https://github.com/glasskube/hello-distr/commit/d3204da05b411809d1b6a00602860ff3a63d7cde))
* **deps:** update dependency tailwind-variants to v0.3.1 ([#9](https://github.com/glasskube/hello-distr/issues/9)) ([6fd60cc](https://github.com/glasskube/hello-distr/commit/6fd60ccce739d648f73ab4fa874308b69d2ba118))
* **deps:** update docker/setup-buildx-action action to v3.9.0 ([#32](https://github.com/glasskube/hello-distr/issues/32)) ([1e5a8ec](https://github.com/glasskube/hello-distr/commit/1e5a8ec8aec7c4f974bb38e1487fa855fe95cff6))

## [0.1.5](https://github.com/glasskube/hello-distr/compare/0.1.4...0.1.5) (2025-02-26)


### Other

* add second push distr action, small docs updates ([#38](https://github.com/glasskube/hello-distr/issues/38)) ([70b2f0e](https://github.com/glasskube/hello-distr/commit/70b2f0e2bc111341960f714e030808043c4b1031))
* update docs ([#36](https://github.com/glasskube/hello-distr/issues/36)) ([8130357](https://github.com/glasskube/hello-distr/commit/81303576be658c2182b0b7fd23a49525108ecf31))

## [0.1.4](https://github.com/glasskube/hello-distr/compare/0.1.3...0.1.4) (2025-02-25)


### Bug Fixes

* postgres healthcheck parameters ([#34](https://github.com/glasskube/hello-distr/issues/34)) ([683f9e4](https://github.com/glasskube/hello-distr/commit/683f9e4cf478d93e999358def8db237d467d0ad0))

## [0.1.3](https://github.com/glasskube/hello-distr/compare/0.1.2...0.1.3) (2025-02-25)


### Other

* **deps:** update docker/build-push-action action to v6.14.0 ([#24](https://github.com/glasskube/hello-distr/issues/24)) ([90f1921](https://github.com/glasskube/hello-distr/commit/90f192165556657c6ad6a779e75cdf904ce5ea72))
* **deps:** update postgres docker tag to v17.4 ([#18](https://github.com/glasskube/hello-distr/issues/18)) ([855e3b0](https://github.com/glasskube/hello-distr/commit/855e3b00fa83ae6ae97f80b09a2db15b240b1505))

## [0.1.2](https://github.com/glasskube/hello-distr/compare/0.1.1...0.1.2) (2025-02-25)


### Bug Fixes

* **ci:** deploy compose file name in release please config ([#28](https://github.com/glasskube/hello-distr/issues/28)) ([7007944](https://github.com/glasskube/hello-distr/commit/70079445c218c26792b45b29d1bc6275ac7c9c7e))

## [0.1.1](https://github.com/glasskube/hello-distr/compare/0.1.0...0.1.1) (2025-02-25)


### Bug Fixes

* **ci:** deploy compose file name ([#26](https://github.com/glasskube/hello-distr/issues/26)) ([70544ac](https://github.com/glasskube/hello-distr/commit/70544ac499394831fa269893c018442879e67667))

## [0.1.0](https://github.com/glasskube/hello-distr/compare/v0.0.1...0.1.0) (2025-02-25)


### Features

* add backend and proxy for prod deployment ([#12](https://github.com/glasskube/hello-distr/issues/12)) ([22b9f3f](https://github.com/glasskube/hello-distr/commit/22b9f3fb53043a6388a4b63867f018265778a53f))
* add frontend ([#1](https://github.com/glasskube/hello-distr/issues/1)) ([5f7d78d](https://github.com/glasskube/hello-distr/commit/5f7d78dbb2b1bde3befdfbb881de56d3db049f0a))


### Bug Fixes

* **deps:** update dependency next to v15.1.2 [security] ([#4](https://github.com/glasskube/hello-distr/issues/4)) ([c23e4b6](https://github.com/glasskube/hello-distr/commit/c23e4b6438b9f8f45bb3e4b180e8c0bfe663e674))


### Other

* Configure Renovate ([#2](https://github.com/glasskube/hello-distr/issues/2)) ([5a40e07](https://github.com/glasskube/hello-distr/commit/5a40e07a9c13ae421da73afc230e9707e22da17b))
* **deps:** update dependency @types/node to v20.17.19 ([#14](https://github.com/glasskube/hello-distr/issues/14)) ([b991628](https://github.com/glasskube/hello-distr/commit/b9916287cf70e580697a50bbada43f5e4ff1d1e2))
* **deps:** update dependency eslint-plugin-prettier to v5.2.3 ([#8](https://github.com/glasskube/hello-distr/issues/8)) ([dceefdd](https://github.com/glasskube/hello-distr/commit/dceefdd0a178f7038861fc2b48addfd6ab9707c8))
* **deps:** update dependency prettier to v3.5.2 ([#16](https://github.com/glasskube/hello-distr/issues/16)) ([da9a80a](https://github.com/glasskube/hello-distr/commit/da9a80a01ac6b6a00a20ad9a13f2fcc731d102a9))
* **deps:** update dependency tailwindcss to v3.4.17 ([#10](https://github.com/glasskube/hello-distr/issues/10)) ([baa64e6](https://github.com/glasskube/hello-distr/commit/baa64e67851fefd1462d64f9d831d08913c00d58))
* **deps:** update python docker tag to v3.13 ([#20](https://github.com/glasskube/hello-distr/issues/20)) ([f8e3fda](https://github.com/glasskube/hello-distr/commit/f8e3fda8b927e7a04cd43fab66c9e0fe681f5309))
* downgrade current version ([#23](https://github.com/glasskube/hello-distr/issues/23)) ([4e53176](https://github.com/glasskube/hello-distr/commit/4e531767c38496e890403ab5285201cb638eb619))
* initial commit ([d0ef3d9](https://github.com/glasskube/hello-distr/commit/d0ef3d908894299e4f08e5d4966ad806f06aa95e))
* push to demo distr ([#25](https://github.com/glasskube/hello-distr/issues/25)) ([2864d8e](https://github.com/glasskube/hello-distr/commit/2864d8e906805bc42629945b5edd0b5de37d1df5))
