# Changelog

All notable changes to this project will be documented in this file. See [Convential Commits](https://www.conventionalcommits.org/en/v1.0.0/#specification) for commit guidelines.

## [6.3.1](http://superfly.tv/compare/v6.3.0...v6.3.1) (Thu May 22 2025)


### Fixes

* fix lint [67c93d99](http://superfly.tv/commit/67c93d99e1b11112837cc955208691ffb0083b0b)
* in cgAdd: make cgLayer be optional [3066ee35](http://superfly.tv/commit/3066ee355e1bfa628602e3707ec980ad616b2502)

## [6.3.0](http://superfly.tv/compare/v6.2.1...v6.3.0) (Tue Jul 30 2024)


### Features

* add custom commands [9763f84f](http://superfly.tv/commit/9763f84fcbd7288f9b6933d55d53cd90e4b6d7c9)

## [6.2.1](http://superfly.tv/compare/v6.2.0...v6.2.1) (Thu Feb 01 2024)


### Fixes

* mixer tween parameters #199 (#200) [cd573113](http://superfly.tv/commit/cd573113ac9286ef1fc4b7a1c02f2c2c1ecc2eaf)

## [6.2.0](http://superfly.tv/compare/v6.1.1...v6.2.0) (Tue Jan 02 2024)


### Fixes

* info format should be string [2fe75295](http://superfly.tv/commit/2fe752958a0e7352d7b3f1d9b500fea308736815)

### Features

* add discard [d531a7d3](http://superfly.tv/commit/d531a7d34141ae86cd815b50a4661a5d846610b7)
* add ping, begin and commit [29a72688](http://superfly.tv/commit/29a726881aeb0ffa4e605dc49ca346e0e0503d5c)

## [6.1.1](http://superfly.tv/compare/v6.1.0...v6.1.1) (Tue Oct 17 2023)


### Fixes

* bug fix in INFO CHANNEL deserializer [985417bd](http://superfly.tv/commit/985417bd91d6b699a8d677b97a4bec105a6738f5)

## [6.1.0](http://superfly.tv/compare/v6.0.6...v6.1.0) (Mon Oct 16 2023)


### Features

* add INFO Config deserializer [9af33b11](http://superfly.tv/commit/9af33b11b7234a52dd4bdca61e2dce6938443332)
* add separate commands for INFO, INFO channel and INFO channel-layer, and handle return data properly [19997ce9](http://superfly.tv/commit/19997ce97c3781ca7defb407ac04bc8c260d6ae0)
* Add strict types for the deserialized return-data of some of the commands [f1c67b4d](http://superfly.tv/commit/f1c67b4d63e2465f1751e4134aa0a4c4e35d88f2)

### Fixes

* set all default return-data to be unknown instead of undefined [7622c142](http://superfly.tv/commit/7622c142cbfe8c988e39a2eb634e4d68cdfd5f94)

## [6.0.6](http://superfly.tv/compare/v6.0.5...v6.0.6) (Thu Oct 05 2023)


### Fixes

* aFilter and vFilter serialized incorrectly SOFIE-2706 [0765fed5](http://superfly.tv/commit/0765fed57d649c76af101ea364f9a7b8a196f471)

## [6.0.5](http://superfly.tv/compare/v6.0.4...v6.0.5) (Tue Oct 03 2023)


## [6.0.4](http://superfly.tv/compare/v6.0.3...v6.0.4) (Tue Oct 03 2023)


### Fixes

* receiving fragmented message gets stuck SOFIE-2680 (#188) [15739ae7](http://superfly.tv/commit/15739ae7bf50ff2f67f4778afc7dc73d0674433d)
* allow lenght of 0 [02d082da](http://superfly.tv/commit/02d082da9e992364398cf241faa57a9c0fae9f50)

## [6.0.3](http://superfly.tv/compare/v6.0.2...v6.0.3) (Wed May 03 2023)


### Fixes

* cgAdd didn't serialize data properly [60790958](http://superfly.tv/commit/60790958d3109a23e7121ebc81192a2eae2417d3)
* make some parameters optional [23d3de2d](http://superfly.tv/commit/23d3de2da5bd3a401882a6ef9c8be81097f92fb3)

## [6.0.2](http://superfly.tv/compare/v6.0.1...v6.0.2) (Wed Mar 22 2023)


### Fixes

* playOnLoad serialisation [fa661a38](http://superfly.tv/commit/fa661a38be986e8e43b357efaa4b236474eb716f)

## [6.0.1](http://superfly.tv/compare/v6.0.0...v6.0.1) (Thu Feb 16 2023)


### Fixes

* multi-token PLAY/LOADBG commands serialize incorrectly [2b1bc0cb](http://superfly.tv/commit/2b1bc0cb816ae827f8f877cd321f54a1d81248af)

## [6.0.0](http://superfly.tv/compare/5.1.0...v6.0.0) (Fri Nov 11 2022)

## Breaking changes

### Features

* **!** rewrite library [8d23d0d3](http://superfly.tv/commit/8d23d0d32677f86f5e63bf706c9c5967aef80638)

### Fixes

* decklink format should be optional [21bc530e](http://superfly.tv/commit/21bc530e2a8a203aa1f6cfe461a1e2eb047c1974)
* rework sending API [01c13f68](http://superfly.tv/commit/01c13f6893e869b9c27c2ab4d076ee55a41b741d)
* disconnect flow closes requests [7e8ec251](http://superfly.tv/commit/7e8ec251ff9b027e1b327a26dc9466bc120d2c58)
* do not swallow error [e4767c1e](http://superfly.tv/commit/e4767c1ebd88aacb72dec477678158b7b40f400d)
* add typed events to the basic api [d4613dcf](http://superfly.tv/commit/d4613dcfee624c3b00acc0fd7cdc2d4529677b7b)
* add some missing params [35beca66](http://superfly.tv/commit/35beca6618d603b8577380e205025e1ab090faa7)
* improve socket connection handling [a29f690f](http://superfly.tv/commit/a29f690f5ae7b007af01e24c944ac0286bb6bb85)

### Features

* multi version support [6d18b5ca](http://superfly.tv/commit/6d18b5ca4c4dfec6d1741a5890df2775c1bde51f)
* add disconnect flow [8bc9b7db](http://superfly.tv/commit/8bc9b7dbc2cfebd62f371a057f2bbd369267c9d4)
* command timeouts [1e28632c](http://superfly.tv/commit/1e28632c844e17880e0c7a93735b2eff6af7a9ea)
* add xml parsing of responses [f8a83470](http://superfly.tv/commit/f8a83470976fb8506ee7a5ff68405e53088e2809)

## [5.1.0](https://github.com/SuperFlyTV/casparcg-connection/compare/5.0.1...5.1.0) (2020-11-16)


### Features

* add ffmpeg filter options ([1b81653](https://github.com/SuperFlyTV/casparcg-connection/commit/1b81653cf9f5f898fcc62f21d4844377076b3134))

### [5.0.1](https://github.com/SuperFlyTV/casparcg-connection/compare/5.0.0...5.0.1) (2020-09-29)

## [5.0.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.9.0...5.0.0) (2020-09-29)


### ⚠ BREAKING CHANGES

* drop node 8 support

### Features

* drop node 8 support ([44f6dae](https://github.com/SuperFlyTV/casparcg-connection/commit/44f6dae5102ba54163bb81385a06157530027d37))
* **ci:** use prerelease flow & optionally skip audit [skip ci] ([bd32ef1](https://github.com/SuperFlyTV/casparcg-connection/commit/bd32ef1f2b1b43053bb82a009f01143b45c5a9f8))
* update ci to run for node 8,10,12 ([8e1de30](https://github.com/SuperFlyTV/casparcg-connection/commit/8e1de3093dbee2a979eb0c9736515449d965dc47))

# [4.9.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.8.1...4.9.0) (2019-11-18)


### Features

* clear_on_404 parameter for PLAY/LOAD/LOADBG ([b8f0bd6](https://github.com/SuperFlyTV/casparcg-connection/commit/b8f0bd6c519fe15d0aa36f461b18383467fd8755))
* FRAMES_DELAY parameter for PLAY/LOAD/LOADBG route ([bceabce](https://github.com/SuperFlyTV/casparcg-connection/commit/bceabce321466fcfdd28dc4dd6c41c93ede162c3))



## [4.8.1](https://github.com/SuperFlyTV/casparcg-connection/compare/4.8.0...4.8.1) (2019-11-07)



# [4.8.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.7.0...4.8.0) (2019-11-07)


### Bug Fixes

* remove unnecessary overloads ([5a2ca12](https://github.com/SuperFlyTV/casparcg-connection/commit/5a2ca1213585d6fbb669a4341b28cad28e628ad8))
* sting transition property names ([6b45644](https://github.com/SuperFlyTV/casparcg-connection/commit/6b4564470cd66d41a35a51e211836430987e9dc8))
* update dependencies ([b481590](https://github.com/SuperFlyTV/casparcg-connection/commit/b48159035c1f27b29736556c6a1d5a015de83057))
* update docs ([50f3fb0](https://github.com/SuperFlyTV/casparcg-connection/commit/50f3fb02199367587d510db91d44e04f1a84ba3e))


### Features

* **call:** Adds SEEK support to call ([bad75ae](https://github.com/SuperFlyTV/casparcg-connection/commit/bad75ae625d0a3aaf7e2140447f5624ccda8c598)), closes [#5](https://github.com/SuperFlyTV/casparcg-connection/issues/5)
* sting audio fade parameters ([9c64a9e](https://github.com/SuperFlyTV/casparcg-connection/commit/9c64a9ea6e61078e567927600c6e6d1d6c0c8b61))



# [4.7.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.6.1...4.7.0) (2019-04-11)


### Bug Fixes

* **Validator:** refactor of PositiveNumberValidatorBetween ([1d6f41e](https://github.com/SuperFlyTV/casparcg-connection/commit/1d6f41e))


### Features

* **call:** adds all ffmpeg producer calls ([2edbe9d](https://github.com/SuperFlyTV/casparcg-connection/commit/2edbe9d))
* **call:** Adds SEEK support to call ([1704912](https://github.com/SuperFlyTV/casparcg-connection/commit/1704912)), closes [#5](https://github.com/SuperFlyTV/casparcg-connection/issues/5)
* add support for IN property in PLAY command ([9e059be](https://github.com/SuperFlyTV/casparcg-connection/commit/9e059be))



<a name="4.6.1"></a>
## [4.6.1](https://github.com/SuperFlyTV/casparcg-connection/compare/4.6.0...4.6.1) (2019-01-15)



<a name="4.6.0"></a>
# [4.6.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.5.3...4.6.0) (2018-12-12)


### Bug Fixes

* add back overloads for play methods ([40b12b4](https://github.com/SuperFlyTV/casparcg-connection/commit/40b12b4))


### Features

* channel_layout property ([c66fcfb](https://github.com/SuperFlyTV/casparcg-connection/commit/c66fcfb))



<a name="4.5.3"></a>
## [4.5.3](https://github.com/SuperFlyTV/casparcg-connection/compare/4.5.2...4.5.3) (2018-10-03)


### Bug Fixes

* **sting:** stingOverlayFilename can be the empty string ([afe1143](https://github.com/SuperFlyTV/casparcg-connection/commit/afe1143))



<a name="4.5.2"></a>
## [4.5.2](https://github.com/SuperFlyTV/casparcg-connection/compare/4.5.1...4.5.2) (2018-09-24)



<a name="4.5.1"></a>
## [4.5.1](https://github.com/SuperFlyTV/casparcg-connection/compare/4.5.0...4.5.1) (2018-09-11)


### Bug Fixes

* validation of transition paramters ([d128f98](https://github.com/SuperFlyTV/casparcg-connection/commit/d128f98))



<a name="4.5.0"></a>
# [4.5.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.4.0...4.5.0) (2018-08-14)


### Features

* route command ([43bdf63](https://github.com/SuperFlyTV/casparcg-connection/commit/43bdf63))



<a name="4.4.0"></a>
# [4.4.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.3.1...4.4.0) (2018-08-07)


### Bug Fixes

* **Commands:** Rejects promise on invalid command ([8632c79](https://github.com/SuperFlyTV/casparcg-connection/commit/8632c79))


### Features

* **Commands:** Better promise handling with fallback to empty promises instead of mixing promise and null handling ([8400194](https://github.com/SuperFlyTV/casparcg-connection/commit/8400194))



<a name="4.3.1"></a>
## [4.3.1](https://github.com/SuperFlyTV/casparcg-connection/compare/4.3.0...4.3.1) (2018-08-02)


### Bug Fixes

* Time command takes timecode parameter ([858e2a4](https://github.com/SuperFlyTV/casparcg-connection/commit/858e2a4))



<a name="4.3.0"></a>
# [4.3.0](https://github.com/SuperFlyTV/casparcg-connection/compare/4.2.2...4.3.0) (2018-08-02)


### Features

* sting transition type ([538a4d0](https://github.com/SuperFlyTV/casparcg-connection/commit/538a4d0))



<a name="4.2.2"></a>
## [4.2.2](https://github.com/SuperFlyTV/casparcg-connection/compare/4.2.1...4.2.2) (2018-07-02)


### Bug Fixes

* use 'new' keyword instead of Object.create ([27c6055](https://github.com/SuperFlyTV/casparcg-connection/commit/27c6055))



<a name="4.2.1"></a>
## [4.2.1](https://github.com/SuperFlyTV/casparcg-connection/compare/4.2.0...4.2.1) (2018-07-02)



<a name="4.2.0"></a>
# [4.2.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v4.1.1...v4.2.0) (2018-06-28)


### Bug Fixes

* refactor package.json, add circleCI badge and correct ssh fingerprint ([37c5377](https://github.com/SuperFlyTV/casparcg-connection/commit/37c5377))
* ts lint errors ([84e830c](https://github.com/SuperFlyTV/casparcg-connection/commit/84e830c))
* typescrit imrovements ([3b8634e](https://github.com/SuperFlyTV/casparcg-connection/commit/3b8634e))


### Features

* initial convert to circleci ([842de38](https://github.com/SuperFlyTV/casparcg-connection/commit/842de38))



<a name="4.1.1"></a>
## [4.1.1](https://github.com/SuperFlyTV/casparcg-connection/compare/v4.1.0...v4.1.1) (2018-06-27)


### Bug Fixes

* don't set queueMode on uninitialized socket ([c6a8b06](https://github.com/SuperFlyTV/casparcg-connection/commit/c6a8b06))



<a name="4.1.0"></a>
# [4.1.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v4.0.3...v4.1.0) (2018-05-22)



<a name="4.0.3"></a>
## [4.0.3](https://github.com/SuperFlyTV/casparcg-connection/compare/v4.0.2...v4.0.3) (2018-05-07)



<a name="4.0.2"></a>
## [4.0.2](https://github.com/SuperFlyTV/casparcg-connection/compare/v4.0.1...v4.0.2) (2018-05-04)



<a name="4.0.1"></a>
## [4.0.1](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.1...v4.0.1) (2018-04-29)


### Bug Fixes

* **TemplateData):** PR from Craig Sweaton escaping \r\n from template data. Prevents breaking the AMCP communication. 


<a name="4.0.0"></a>
# [4.0.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.1.0...v4.0.0) (2018-04-10)


### Features

* **Asynchronous commands:** refactor the internal command execution ([7b10d43](https://github.com/SuperFlyTV/casparcg-connection/commit/7b10d43))
* **QueueMode:** allow runtime configuration ([f39f7ea](https://github.com/SuperFlyTV/casparcg-connection/commit/f39f7ea))
* **Scheduled Commands:** keep sequential mode for compatibility ([48a760f](https://github.com/SuperFlyTV/casparcg-connection/commit/48a760f))
* **Scheduled Commands:** schedule and resolve scheduled commands ([5a9f0fb](https://github.com/SuperFlyTV/casparcg-connection/commit/5a9f0fb))


* . ([7a8d4c6](https://github.com/SuperFlyTV/casparcg-connection/commit/7a8d4c6))


### BREAKING CHANGES

* set default queue mode to SALVO, making the library fully asynchronous.



<a name="3.1.0"></a>
# [3.1.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.2...v3.1.0) (2018-03-28)


### Features

* **Add/Remove Commands:** Merge branch 'Besedin86/master' into develop ([ca772e6](https://github.com/SuperFlyTV/casparcg-connection/commit/ca772e6))



<a name="3.0.2"></a>
## [3.0.2](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.1...v3.0.2) (2018-03-27)


### Bug Fixes

* **CGAddCommand:** playOnLoad is required ([3fc9300](https://github.com/SuperFlyTV/casparcg-connection/commit/3fc9300)), closes [#93](https://github.com/SuperFlyTV/casparcg-connection/issues/93)



<a name="3.0.1"></a>
## [3.0.1](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.0...v3.0.1) (2017-10-22)


### Bug Fixes

* **MixerCommands:** Corrected copy/paste errors for several mixer commands, related to transitions. ([29bc5a5](https://github.com/SuperFlyTV/casparcg-connection/commit/29bc5a5)), closes [#89](https://github.com/SuperFlyTV/casparcg-connection/issues/89)



<a name="3.0.0"></a>
# [3.0.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.0-next.4...v3.0.0) (2017-10-16)


### Bug Fixes

* **TemplateData:** Correct double escaping of quotes xml strings ([5bda229](https://github.com/SuperFlyTV/casparcg-connection/commit/5bda229))



<a name="3.0.0-next.4"></a>
# [3.0.0-next.4](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.0-next.3...v3.0.0-next.4) (2017-10-03)


### Bug Fixes

* **Config:** Correct cross-version-import between configVOs ([bdcedfd](https://github.com/SuperFlyTV/casparcg-connection/commit/bdcedfd))
* **onConnection:** Bug with promise resolve and queue conducting on initial connection ([4504cb9](https://github.com/SuperFlyTV/casparcg-connection/commit/4504cb9))



<a name="3.0.0-next.3"></a>
# [3.0.0-next.3](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.0-next.2...v3.0.0-next.3) (2017-07-31)


### Bug Fixes

* **Socket:** Fixed bug with disposing socket clients before they are created ([7a0a510](https://github.com/SuperFlyTV/casparcg-connection/commit/7a0a510))



<a name="3.0.0-next.2"></a>
# [3.0.0-next.2](https://github.com/SuperFlyTV/casparcg-connection/compare/3.0.0-next.1...v3.0.0-next.2) (2017-07-24)



<a name="3.0.0-next.1"></a>
# [3.0.0-next.1](https://github.com/SuperFlyTV/casparcg-connection/compare/v3.0.0-next.0...v3.0.0-next.1) (2017-07-20)


### Features

* **VirginServer:** Report server's virgin-state on connected events ([a8f3b61](https://github.com/SuperFlyTV/casparcg-connection/commit/a8f3b61))



<a name="3.0.0-next.0"></a>
# [3.0.0-next.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v2.1.0...v3.0.0-next.0) (2017-07-20)


### Bug Fixes

* **Command:** Critical error with command timeouts ([6caeacb](https://github.com/SuperFlyTV/casparcg-connection/commit/6caeacb))
* **Config:** Bugfix with manual operations parsing config XML ([e80117b](https://github.com/SuperFlyTV/casparcg-connection/commit/e80117b))
* **Events:** Critical bug introduced in v1.0.0 ([7dcd9fe](https://github.com/SuperFlyTV/casparcg-connection/commit/7dcd9fe))
* **Logging:** Better handling of errors ([d80c794](https://github.com/SuperFlyTV/casparcg-connection/commit/d80c794))
* **Socket:** Prevents timeout of extremely long responses ([613c629](https://github.com/SuperFlyTV/casparcg-connection/commit/613c629))
* **Socket:** Removed unused internal event ([5eb343c](https://github.com/SuperFlyTV/casparcg-connection/commit/5eb343c))
* **Version:** bugfix for setting manuel ServerVersion ([8362a22](https://github.com/SuperFlyTV/casparcg-connection/commit/8362a22))


### Code Refactoring

* **Enum:** Changed the public enum ServerVersion ([b7aadea](https://github.com/SuperFlyTV/casparcg-connection/commit/b7aadea))


### Features

* **Command:** Planned for better timeout retry strategy ([b0b5f19](https://github.com/SuperFlyTV/casparcg-connection/commit/b0b5f19))
* **Config:** Added members "vo" and "xml" as aliases to "VO" and "XML" on Config objects ([65dffde](https://github.com/SuperFlyTV/casparcg-connection/commit/65dffde))
* **Queue:** Added prioritized queues ([929e4ad](https://github.com/SuperFlyTV/casparcg-connection/commit/929e4ad)), closes [#15](https://github.com/SuperFlyTV/casparcg-connection/issues/15)
* **Version:** Added version promise to CasparCG ([554ea41](https://github.com/SuperFlyTV/casparcg-connection/commit/554ea41)), closes [#73](https://github.com/SuperFlyTV/casparcg-connection/issues/73)


### BREAKING CHANGES

* **Enum:** enum ServerVersion is now CasparCGVersion, for consistency.



<a name="2.1.0"></a>
# [2.1.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v2.0.3...v2.1.0) (2017-07-18)


### Bug Fixes

* CasparCG Connection events ([a825a18](https://github.com/SuperFlyTV/casparcg-connection/commit/a825a18))


### Features

* **Commands:** Better command timeout strategy ([bd51c31](https://github.com/SuperFlyTV/casparcg-connection/commit/bd51c31))
* **Socket:** (Re)connection strategy ([3d04e5f](https://github.com/SuperFlyTV/casparcg-connection/commit/3d04e5f)), closes [#66](https://github.com/SuperFlyTV/casparcg-connection/issues/66)
* **Socket:** Reconnection ([90ca334](https://github.com/SuperFlyTV/casparcg-connection/commit/90ca334))



<a name="2.0.3"></a>
## [2.0.3](https://github.com/SuperFlyTV/casparcg-connection/compare/v2.0.2...v2.0.3) (2017-07-12)


### Bug Fixes

* events ([1288f34](https://github.com/SuperFlyTV/casparcg-connection/commit/1288f34))



<a name="2.0.2"></a>
## [2.0.2](https://github.com/SuperFlyTV/casparcg-connection/compare/v2.0.1...v2.0.2) (2017-07-12)



<a name="2.0.1"></a>
## [2.0.1](https://github.com/SuperFlyTV/casparcg-connection/compare/v2.0.0...v2.0.1) (2017-07-12)



<a name="2.0.0"></a>
# [2.0.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v1.0.0...v2.0.0) (2017-07-12)


### Bug Fixes

* ES5 target ([f41b04f](https://github.com/SuperFlyTV/casparcg-connection/commit/f41b04f))


### BREAKING CHANGES

* Reverted ES6 target back to ES5 due to Meteor compability



<a name="1.0.0"></a>
# [1.0.0](https://github.com/SuperFlyTV/casparcg-connection/compare/v0.17.2...v1.0.0) (2017-07-12)


### build

* ES6 target ([41b1292](https://github.com/SuperFlyTV/casparcg-connection/commit/41b1292))


### Features

* SocketState changed ([e1fdd5b](https://github.com/SuperFlyTV/casparcg-connection/commit/e1fdd5b))


### BREAKING CHANGES

* build target ES2015 (ES6). This required Node.js version 6.4.0 or higher to fully function.



<a name="0.17.2"></a>
## [0.17.2](https://github.com/SuperFlyTV/casparcg-connection/compare/v0.17.1...v0.17.2) (2017-06-18)


### Bug Fixes

* typo ([5214ead](https://github.com/SuperFlyTV/casparcg-connection/commit/5214ead))
