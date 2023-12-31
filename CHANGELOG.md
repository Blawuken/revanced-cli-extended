# 1.0.0 (2023-12-28)


### Bug Fixes

* `defaultExclude` unused ([2015c2a](https://github.com/Blawuken/revanced-cli-extended/commit/2015c2a1dcc0290af237e2eb1ab4aaf5fc84d382))
* `Main-Class` attribute pointing to wrong method ([6e82418](https://github.com/Blawuken/revanced-cli-extended/commit/6e824189586bfa4f8aaac4a5f33aed8d59261115))
* `ZipAligner` not correctly calculating the file offset ([2975a47](https://github.com/Blawuken/revanced-cli-extended/commit/2975a47d0f682a92da7b3ed455f5078298b0cbaa))
* add back in: option to specify keystore file path ([c94471f](https://github.com/Blawuken/revanced-cli-extended/commit/c94471f4643e44b2b472ff0d826db0d2743bdc86))
* add callback for addFiles ([87ffaa4](https://github.com/Blawuken/revanced-cli-extended/commit/87ffaa4bdb25cb85c6ba7195f5d3b13b09a5f912))
* add execute permission to `./gradlew` file ([#36](https://github.com/Blawuken/revanced-cli-extended/issues/36)) ([072d9e1](https://github.com/Blawuken/revanced-cli-extended/commit/072d9e15d7e44b1080923f3afeb194eeb4fe4682))
* Add missing punctuation in command description ([8210351](https://github.com/Blawuken/revanced-cli-extended/commit/821035107d7264580275f395e9e3fcef91394afd))
* align every file ([96ec6a0](https://github.com/Blawuken/revanced-cli-extended/commit/96ec6a0384e4c710c36b99ccf88bb14c5addc7af))
* also delete temporary files when uninstalling ([52c3be2](https://github.com/Blawuken/revanced-cli-extended/commit/52c3be23f2915dccaee7f9941413c8f81e14acc8))
* breaking changes by `revanced-patcher` dependency ([51d2504](https://github.com/Blawuken/revanced-cli-extended/commit/51d250491f390695aedc64e7ee71a9dcf99d695c))
* broken control flow of `includeFilter` ([a0644c7](https://github.com/Blawuken/revanced-cli-extended/commit/a0644c7045344e6a6c324392cb8f507a6d9dbfad))
* broken deprecation message ([e3e74ac](https://github.com/Blawuken/revanced-cli-extended/commit/e3e74ac0e9a844f9d717a499bca09e575dd90435))
* broken script `CONTENT_UNMOUNT_SCRIPT` ([be53e64](https://github.com/Blawuken/revanced-cli-extended/commit/be53e649a7a43de70ba2a7227c49b085001066a6))
* bump patcher dependency version ([51c04b7](https://github.com/Blawuken/revanced-cli-extended/commit/51c04b7b162ad2876bbeb248b7ccddd105b5076d))
* check for package compatibility at first ([9fe5a0b](https://github.com/Blawuken/revanced-cli-extended/commit/9fe5a0b6d93304f630436ed0e954723d9a27b0f6))
* check for root even though when not needed ([0d7581a](https://github.com/Blawuken/revanced-cli-extended/commit/0d7581ad750525e59bd6c019d987c640588ead62))
* check if `packageVersion` is compatible with any from `compatiblePackages` ([32589c8](https://github.com/Blawuken/revanced-cli-extended/commit/32589c88e438e0a1375c256e9bb8a93f5a4d319b))
* Check, if mounting is possible ([3e13fb5](https://github.com/Blawuken/revanced-cli-extended/commit/3e13fb5d56eb2a90c2a4a1ddfc05852b1f70add5))
* ClassLoader not working with Java 9+ ([3a11e11](https://github.com/Blawuken/revanced-cli-extended/commit/3a11e1135bd1e8958dd21247622d549440725ead))
* CLI not working ([29105ba](https://github.com/Blawuken/revanced-cli-extended/commit/29105bab3dabd9d16af6b511caef9727f98afd1a))
* correct spelling mistake ([31fb316](https://github.com/Blawuken/revanced-cli-extended/commit/31fb3166d922ae1f568f52e44cbe726dd1c891a4))
* Correct warning message ([ba573f7](https://github.com/Blawuken/revanced-cli-extended/commit/ba573f73d0e310fdeb8be2831fd40a7188473fff))
* correctly word option descriptions ([ac3a8f6](https://github.com/Blawuken/revanced-cli-extended/commit/ac3a8f66f77a7218974465eebbfc78a536b76d51))
* Create options if it does not exist when updating them ([ca809f0](https://github.com/Blawuken/revanced-cli-extended/commit/ca809f0948379e3a825f24d7a49aba8b6b8767d1))
* delete `outputFile` after deploying ([329f8a3](https://github.com/Blawuken/revanced-cli-extended/commit/329f8a383fe52f4c2a66075d893c6599d3550bee))
* Delete temporal files if it exists ([a022feb](https://github.com/Blawuken/revanced-cli-extended/commit/a022febd0c70807ddc3fa9948207a2a70d5191da))
* delete temporary files after root installation ([a3d8705](https://github.com/Blawuken/revanced-cli-extended/commit/a3d8705e89732a0dd4f51de28c405b6af13c8633))
* deploy to `adb` ([f9b987e](https://github.com/Blawuken/revanced-cli-extended/commit/f9b987e858292332a4b99e4e4280647425b8c0b8))
* do not delete output file ([0f3e090](https://github.com/Blawuken/revanced-cli-extended/commit/0f3e090418771e951dfd15e5c193421f72cbe459))
* do not filter explicitly included patches ([a3d8f00](https://github.com/Blawuken/revanced-cli-extended/commit/a3d8f004ec405f696d99d96c74ca41b573ecf425))
* do not list compatible packages if patches do not define them ([31e4a41](https://github.com/Blawuken/revanced-cli-extended/commit/31e4a41dd20f5fa62f840cd8e3b92fe0814eda87))
* Do not sign if mounting ([578e16b](https://github.com/Blawuken/revanced-cli-extended/commit/578e16b099fddfd2bb56accb225d04dfcd409b0c))
* do not use absolute path from custom AAPT2 binary option ([a9c2a5f](https://github.com/Blawuken/revanced-cli-extended/commit/a9c2a5f096627dbbf8ab1b8da26fb14529ce6bc3))
* don't log when package is incompatible and `exclusive` option is used ([ad81a1b](https://github.com/Blawuken/revanced-cli-extended/commit/ad81a1b656586226f8b7b8d1123c52b0f3f2e6f7))
* don't print same patch multiple times ([f4b0469](https://github.com/Blawuken/revanced-cli-extended/commit/f4b04698d8c1717824e86f91da5e01c5021612da))
* dummy publish task (1/2) [skip ci] ([afff4c8](https://github.com/Blawuken/revanced-cli-extended/commit/afff4c8418bd33959440a3ac9e6c46816b3153ad))
* escape quotation mark in string ([6e21d81](https://github.com/Blawuken/revanced-cli-extended/commit/6e21d81964e8160e06ffda7051dd484e4aaaa432))
* exclude patcher dependency from minimizing ([d5794b9](https://github.com/Blawuken/revanced-cli-extended/commit/d5794b94ca19c9287190a3b863c97a089893cc07))
* Filter logs correctly ([43fc20d](https://github.com/Blawuken/revanced-cli-extended/commit/43fc20d90e0a694b231b17bb7d9ecfa22bb5d9a0))
* filtration of patches malfunctioning ([2d5a7fd](https://github.com/Blawuken/revanced-cli-extended/commit/2d5a7fdf1eb2e13f5013a790b03f09851b167fe0))
* fix noSuchMethodError ([00fec25](https://github.com/Blawuken/revanced-cli-extended/commit/00fec2508a3421b7b5a246254e0cb08850eab6ea))
* fix running commands not running ([2c7fcaf](https://github.com/Blawuken/revanced-cli-extended/commit/2c7fcaf4add65a12052afc5bef779dbc73debd69))
* Fix typo ([#300](https://github.com/Blawuken/revanced-cli-extended/issues/300)) ([9d96bb7](https://github.com/Blawuken/revanced-cli-extended/commit/9d96bb7b4cc4538da416db50bd689af1a632fc45))
* format patches input ([bbb1a63](https://github.com/Blawuken/revanced-cli-extended/commit/bbb1a63abd80dcbecdcf362158c0429cf3e6318f))
* **gitignore:** ignore `options.toml` ([#158](https://github.com/Blawuken/revanced-cli-extended/issues/158)) ([7be9af0](https://github.com/Blawuken/revanced-cli-extended/commit/7be9af0942de2a834b9e57403d46263b65f1a422))
* gradle build script ([6ffba3e](https://github.com/Blawuken/revanced-cli-extended/commit/6ffba3ef0a089c01fd31b667a37a27e77186bbbd))
* gradle sync dependencies ([407efdc](https://github.com/Blawuken/revanced-cli-extended/commit/407efdc8df1bd15710a9617462bfb123cfe739fe))
* improper use of mount variable ([31853fe](https://github.com/Blawuken/revanced-cli-extended/commit/31853fe5393af04805857b78a54434e1c51e4c8e))
* invalid code flow when adding patches ([206f202](https://github.com/Blawuken/revanced-cli-extended/commit/206f2029d7498b6474c16a47cbe451c170fdd31f))
* invalid header when writing a `ZipFile` ([#169](https://github.com/Blawuken/revanced-cli-extended/issues/169)) ([6e703eb](https://github.com/Blawuken/revanced-cli-extended/commit/6e703eb8e8d7da0e52266c4965f37bc8aafb409c))
* keystore file not found exception ([#57](https://github.com/Blawuken/revanced-cli-extended/issues/57)) ([5b8537e](https://github.com/Blawuken/revanced-cli-extended/commit/5b8537e6b7922f1b44058c3a4fc2f56cb4e15e89))
* leftover TODOs ([5b1139c](https://github.com/Blawuken/revanced-cli-extended/commit/5b1139ce43df1f5c2c848a8209a9e618857031ce))
* Log correct options command ([#262](https://github.com/Blawuken/revanced-cli-extended/issues/262)) ([96c196d](https://github.com/Blawuken/revanced-cli-extended/commit/96c196dcb14e37ad91b751af61ee8382547c1ca3))
* Log logs with levels over warning to error output stream ([075f6ad](https://github.com/Blawuken/revanced-cli-extended/commit/075f6ad56528a667dca1f0bed704cf7e5381026f))
* Log not showing in CLI  ([#80](https://github.com/Blawuken/revanced-cli-extended/issues/80)) ([d9c5a17](https://github.com/Blawuken/revanced-cli-extended/commit/d9c5a179c529c386f66df4fa63cd321d396836b5)), closes [#79](https://github.com/Blawuken/revanced-cli-extended/issues/79)
* Make clear what the --exclusive command actually does ([a26b0ea](https://github.com/Blawuken/revanced-cli-extended/commit/a26b0ea64dcd0757b5b49c09137959751874d955))
* make cli compatible with breaking changes of the patcher ([555b38f](https://github.com/Blawuken/revanced-cli-extended/commit/555b38f386363661a1433d82b9825dc345855f65))
* make integrations optional ([bea8b82](https://github.com/Blawuken/revanced-cli-extended/commit/bea8b829c701eee3c5b0bd6fe41c2f3f7df48d9b))
* migrate from `PatchLoader.load(...)` to `JarPatchBundle(...).loadPatches()` ([cabd32f](https://github.com/Blawuken/revanced-cli-extended/commit/cabd32fda41d32616a61ae450c60e1ee7c35bc59))
* migrate to changes of patcher ([b30c737](https://github.com/Blawuken/revanced-cli-extended/commit/b30c7375a7ea61184be5dca19062ee74d1f97692))
* migrate to latest patcher api changes ([ace70e4](https://github.com/Blawuken/revanced-cli-extended/commit/ace70e417fdf280c7630a5a89a773879fd240e96))
* missing implementation ([48102c6](https://github.com/Blawuken/revanced-cli-extended/commit/48102c66077c4ae17e3de1076e9da72de5f00366))
* mount bind revanced.apk from magisk's mirror ([372470c](https://github.com/Blawuken/revanced-cli-extended/commit/372470c77b82e8601ca523e87a2cfd44f79d0e31))
* Move file to output even when mounting ([59dfc98](https://github.com/Blawuken/revanced-cli-extended/commit/59dfc988e351374eb718923d19bd9bdd94e8d3c0))
* move the keystore to the output directory ([6ceb449](https://github.com/Blawuken/revanced-cli-extended/commit/6ceb449cf8539a92d89eeba8136fdc686319e2ef))
* null exception when resource patching is disabled ([#85](https://github.com/Blawuken/revanced-cli-extended/issues/85)) ([125fa06](https://github.com/Blawuken/revanced-cli-extended/commit/125fa06ca6bac66f790e4aba66887464189b3a63))
* only accept directories when looking for files in resource patch ([c76da7e](https://github.com/Blawuken/revanced-cli-extended/commit/c76da7e5ffa208860eea008dad358e4e3bb3d735))
* only check once for patch options ([11c3a6c](https://github.com/Blawuken/revanced-cli-extended/commit/11c3a6cfd4fe59ba5d703358634a1853e1cc22a5))
* Only open files for reading and writing if writeable ([3846f72](https://github.com/Blawuken/revanced-cli-extended/commit/3846f721ca015ab39a7e4b8d3f3d61163a6f1650))
* Only set options for filtered patches ([64d9127](https://github.com/Blawuken/revanced-cli-extended/commit/64d9127291ea9a8abe21a0e82721721495094472))
* only upload `-all.jar` asset ([ca8e1ba](https://github.com/Blawuken/revanced-cli-extended/commit/ca8e1ba6af00e275c6981476f773b13b103799d1))
* overwrite output file ([2bfbbc2](https://github.com/Blawuken/revanced-cli-extended/commit/2bfbbc2eb9057e66a362d37973a108baf44edf7a))
* print original instead of kebab cased names ([5eaad33](https://github.com/Blawuken/revanced-cli-extended/commit/5eaad33dc1fbd24c36e1498f04e21d068e85f53e))
* print stack trace when a patch failed ([924c1f8](https://github.com/Blawuken/revanced-cli-extended/commit/924c1f80ec0d17a3bdc07a0fb2015e44c49162e4))
* releases (2/2) ([227d8d9](https://github.com/Blawuken/revanced-cli-extended/commit/227d8d94c89ec24051bd5bc20808049164d92492))
* remove `-e` from `experimental` option ([3829136](https://github.com/Blawuken/revanced-cli-extended/commit/3829136c49ddce1dc6b01eda04ce013540b213c2))
* remove `excludePatches` check ([eb83cab](https://github.com/Blawuken/revanced-cli-extended/commit/eb83cabfff6fbc28dd892f15b8e28278e284caa9))
* remove duplicate options entries. ([d0fc886](https://github.com/Blawuken/revanced-cli-extended/commit/d0fc8864286adc2677f91a319a11a90272c1001d))
* remove logger from Signer.kt ([51e091c](https://github.com/Blawuken/revanced-cli-extended/commit/51e091ce4021418508044029aa5af6aa7d5162a3))
* remove requirement for solution [skip ci] ([#108](https://github.com/Blawuken/revanced-cli-extended/issues/108)) ([0ce680a](https://github.com/Blawuken/revanced-cli-extended/commit/0ce680a6f1de139434edd80876a168ff695c2d79))
* resolve signatures before applying patches ([c9941fe](https://github.com/Blawuken/revanced-cli-extended/commit/c9941fe182e11066c34c3d390352862bb0f95ca2))
* resource patcher ([9da4f70](https://github.com/Blawuken/revanced-cli-extended/commit/9da4f707ac62d11993021871ef39f4f1709ba89d))
* show actual version in CLI ([1dcdbc9](https://github.com/Blawuken/revanced-cli-extended/commit/1dcdbc9fe9e3ad2fe232ad3baa76d186817532a4))
* sign the aligned file instead of the input file ([22d2535](https://github.com/Blawuken/revanced-cli-extended/commit/22d2535af8b3ea8fa58b6beb2938d240afa0a17d))
* specify correct class containing entry-point ([1fcc591](https://github.com/Blawuken/revanced-cli-extended/commit/1fcc591222ab67112f2b78174a8b94106846838c))
* start with uppercase in log message ([ae91b0d](https://github.com/Blawuken/revanced-cli-extended/commit/ae91b0d597b107a152e1b630b8c16a795a7ca3b3))
* **tests:** set order of tests ([2ef48af](https://github.com/Blawuken/revanced-cli-extended/commit/2ef48af1b339ab729a05d69cb0c8c1ee1e3ab486))
* this tiny thing has caused me the worst headache ever in my life ([a37304e](https://github.com/Blawuken/revanced-cli-extended/commit/a37304e032c9bb7d8b76f48c7eeaededb8a32a1e))
* uncomment merging integrations ([f2d9da4](https://github.com/Blawuken/revanced-cli-extended/commit/f2d9da4dca890241f6fc52bc2049b5655bc2b8ae))
* unfinished todo message ([fb068ef](https://github.com/Blawuken/revanced-cli-extended/commit/fb068ef7532fc236086205b41756c26f53489645))
* unmount script `CONTENT_UMOUNT_SCRIPT` ([3a2fa30](https://github.com/Blawuken/revanced-cli-extended/commit/3a2fa30676338518ab4a320e16c4c1fab78e0615))
* update cli for new patcher version ([9fc2f96](https://github.com/Blawuken/revanced-cli-extended/commit/9fc2f9602aa2f134106fa400daf388176957dd57))
* update patcher to 1.2.5 ([055c282](https://github.com/Blawuken/revanced-cli-extended/commit/055c282dd3d147e3600bdfdf4fd6b4bd72cbf379))
* update patcher version ([499ce0a](https://github.com/Blawuken/revanced-cli-extended/commit/499ce0a6fb1993ad48ffdd9c9e8307e8d0c179c6))
* update patcher version ([0df936e](https://github.com/Blawuken/revanced-cli-extended/commit/0df936e99b01358a88a628af63eebb5ac92cae76))
* update patcher version ([80c11fe](https://github.com/Blawuken/revanced-cli-extended/commit/80c11fef734bdba9026e91f95ee0a4a522cbefab))
* update patcher version ([09b9027](https://github.com/Blawuken/revanced-cli-extended/commit/09b9027e5e28f0483e74b711cf65a7876267a339)), closes [#45](https://github.com/Blawuken/revanced-cli-extended/issues/45)
* update patcher version (fix apktool) ([496f821](https://github.com/Blawuken/revanced-cli-extended/commit/496f82121879443609667a792cc1e16441ef5c2f))
* use absolute file path for key store ([d335846](https://github.com/Blawuken/revanced-cli-extended/commit/d335846202b991e130882e9ce0ab268deb2e27ab))
* use correct option name ([f8972ea](https://github.com/Blawuken/revanced-cli-extended/commit/f8972eac3e5ee0a4a186c12cbe711925656d657b))
* use correct prefix in log message ([1a67cd8](https://github.com/Blawuken/revanced-cli-extended/commit/1a67cd81da5ed7f259b6dbaeb66a7eef4a113034))
* use latest version of patches dependency ([029f1ad](https://github.com/Blawuken/revanced-cli-extended/commit/029f1ad72223e5be6664c2c8810ac35e5807d9a8))
* Use punctuation in option descriptions ([da4469f](https://github.com/Blawuken/revanced-cli-extended/commit/da4469f402c26ad95898404236b0acf0202907e2))
* use working JADB dependency version ([#222](https://github.com/Blawuken/revanced-cli-extended/issues/222)) ([da2c918](https://github.com/Blawuken/revanced-cli-extended/commit/da2c91874d5623402febfcc0677ada3d648565e1))
* wrong keystore output path ([20fa179](https://github.com/Blawuken/revanced-cli-extended/commit/20fa17957e3e454b9755bc7b9b473b6c578cc593))
* wrong label in additional items [skip ci] ([cd3ded1](https://github.com/Blawuken/revanced-cli-extended/commit/cd3ded1fbdb0c8eb7485912d5cbd6a2dd7455658))
* wrong separator when using `ZipFileSystemUtils` ([20e15de](https://github.com/Blawuken/revanced-cli-extended/commit/20e15defc2b90aa5e79bad41c097bd0db8d5e12a))
* wrong use of dependency to `revanced-patches` ([351de6c](https://github.com/Blawuken/revanced-cli-extended/commit/351de6cb90aa0f2ec93e8b8f6c10d7d312082079))
* wrong use of variable substitution / typo ([81d53b5](https://github.com/Blawuken/revanced-cli-extended/commit/81d53b5518454e479b7a8f2e9be934bee30702af)), closes [revanced/revanced-cli#12](https://github.com/revanced/revanced-cli/issues/12)
* wrong variable inverted ([f694542](https://github.com/Blawuken/revanced-cli-extended/commit/f694542d64ccb06bfa4d042f26b6b7192d1e912e))


### Code Refactoring

* migrate from `Signature` to `Fingerprint` ([88852a4](https://github.com/Blawuken/revanced-cli-extended/commit/88852a45ac90ad9419c18f0cb3395745e62eadbf))


* refactor!: restructure code ([07da528](https://github.com/Blawuken/revanced-cli-extended/commit/07da528ce2223582f84bf64d2fec69714c647ddc))


### Features

* `--custom-aapt2-binary` option ([#104](https://github.com/Blawuken/revanced-cli-extended/issues/104)) ([d8dbffd](https://github.com/Blawuken/revanced-cli-extended/commit/d8dbffd7a7ebc583476d368d2ae78853cbb40382))
* `--exclusive` switch ([#78](https://github.com/Blawuken/revanced-cli-extended/issues/78)) ([8e91c12](https://github.com/Blawuken/revanced-cli-extended/commit/8e91c12c5e3864c369005ef9fe7d9db668e86701))
* `--include` option ([#76](https://github.com/Blawuken/revanced-cli-extended/issues/76)) ([57a1e7c](https://github.com/Blawuken/revanced-cli-extended/commit/57a1e7c27fb0c4292e08332b88ccd57d69fa02c6))
* `--uninstall` switch ([#84](https://github.com/Blawuken/revanced-cli-extended/issues/84)) ([131100e](https://github.com/Blawuken/revanced-cli-extended/commit/131100ef0043924a9c11eb9886b4f6b0373690d9))
* `frameworkFolderLocation` patcher option ([bc17298](https://github.com/Blawuken/revanced-cli-extended/commit/bc17298a807ce035b8baa1f7c30e1392ca4ee43b))
* Add `list-versions` command ([a974b8e](https://github.com/Blawuken/revanced-cli-extended/commit/a974b8ea80acd85f8dc472a3f93b8fd7bea08007))
* add appreciation message for new contributors ([6962fc2](https://github.com/Blawuken/revanced-cli-extended/commit/6962fc2f4c0f0c96e88a823be64f8ebd1312ee17))
* Add CLI ([6664f49](https://github.com/Blawuken/revanced-cli-extended/commit/6664f49a11d655fe0723ad4846673b39b08fcadd))
* Add function to get the most common compatible version ([77d9173](https://github.com/Blawuken/revanced-cli-extended/commit/77d91735ffbbd6e733f08176f535bfd39ece0c29))
* add install command ([0350b7f](https://github.com/Blawuken/revanced-cli-extended/commit/0350b7f1a276d9dc795b22442ba4f202855ea090))
* add logging back ([4a23cb6](https://github.com/Blawuken/revanced-cli-extended/commit/4a23cb69bc385158d47b6ea8d3da54b0566a242c))
* Add option to filter patches to be listed by package name ([50c0f98](https://github.com/Blawuken/revanced-cli-extended/commit/50c0f98ce5927e07839437a2e550aa85f5a7e62d))
* add option to specify keystore file path ([9331594](https://github.com/Blawuken/revanced-cli-extended/commit/9331594706404df871d170110da753cde5058d02))
* Add option to warn about patches not being found in supplied patch bundles ([e46d855](https://github.com/Blawuken/revanced-cli-extended/commit/e46d85564320f46c6faa54b2d3fa7fca3fa60019))
* add options command ([9edbbf3](https://github.com/Blawuken/revanced-cli-extended/commit/9edbbf31635603f89fc7bc5dcc6c023d4cdbb5a6))
* add path for `cacheDirectory` and enable resource patching by default ([54c0a03](https://github.com/Blawuken/revanced-cli-extended/commit/54c0a03d44c8d1b586bc487ee1ca71859d6f0b57))
* Add progress bar ([8d96ec8](https://github.com/Blawuken/revanced-cli-extended/commit/8d96ec83cb11ac9323ef268884912961a2405435))
* Add ReVanced Library subproject ([#265](https://github.com/Blawuken/revanced-cli-extended/issues/265)) ([157278c](https://github.com/Blawuken/revanced-cli-extended/commit/157278c9ba25f0f786c5fe58e3e23f6890107118))
* add semantic-release ([78d7aa3](https://github.com/Blawuken/revanced-cli-extended/commit/78d7aa361e4079b979fbf31d4fca2a7eec445618))
* Added root-only adb runner (tested on emulator) ([37ecc5e](https://github.com/Blawuken/revanced-cli-extended/commit/37ecc5eaa6f9b6640061400270d192959e3d69b2))
* allow listing patches without other parameters ([#42](https://github.com/Blawuken/revanced-cli-extended/issues/42)) ([b977d70](https://github.com/Blawuken/revanced-cli-extended/commit/b977d7039f877be242823a4eef0fb8df6550dd05))
* Allow selecting first Adb device, if none supplied automatically by updating dependencies ([e7c3d64](https://github.com/Blawuken/revanced-cli-extended/commit/e7c3d64bf15bf84f3853e7ef699511bf72c13767))
* better output for excluded patches ([#77](https://github.com/Blawuken/revanced-cli-extended/issues/77)) ([ac7c7a9](https://github.com/Blawuken/revanced-cli-extended/commit/ac7c7a9a1a5c08322e3b206780d4f31104d8b570))
* chcon on mount ([e1c7d10](https://github.com/Blawuken/revanced-cli-extended/commit/e1c7d1082a6946d1082c8744a1d0118c1a2263ea))
* Check for missing integrations ([c93186f](https://github.com/Blawuken/revanced-cli-extended/commit/c93186fb9700907e65f33442e88073783cc163de))
* check, if input file exists ([b6dff6d](https://github.com/Blawuken/revanced-cli-extended/commit/b6dff6d832de4a513a6d86b0a59b2458eddd23c2))
* connect to first device if given device was not found ([6485e47](https://github.com/Blawuken/revanced-cli-extended/commit/6485e477a10bb89dfb2e40f3596d72b20bf23cc8))
* debugging option ([1b645c6](https://github.com/Blawuken/revanced-cli-extended/commit/1b645c67db58eb4d49b5290fd247507c9b43a9c6))
* Do not format patch names ([80a8d88](https://github.com/Blawuken/revanced-cli-extended/commit/80a8d88406b2b04d13dca4fb0d7d7d62e1910317))
* do not warn on incompatible packages ([39e377b](https://github.com/Blawuken/revanced-cli-extended/commit/39e377bc485e2892422e9712d30e6ff665856ac1))
* Exit application with CLI exit code ([36c6a6a](https://github.com/Blawuken/revanced-cli-extended/commit/36c6a6a5f75f2e770a7941b3f83f430f62de13de))
* Extend signing API ([592dc1c](https://github.com/Blawuken/revanced-cli-extended/commit/592dc1c64ae4078e73bb71eba11380b301c79dea))
* handle unmounting deleted files ([#148](https://github.com/Blawuken/revanced-cli-extended/issues/148)) ([3a733e5](https://github.com/Blawuken/revanced-cli-extended/commit/3a733e513717799ca0e32327e5b8be043680c556))
* Improve command line argument descriptions ([f9cf7d2](https://github.com/Blawuken/revanced-cli-extended/commit/f9cf7d21b7f1c2f11234d604a1047b9d2b165f83))
* improve description of options ([#185](https://github.com/Blawuken/revanced-cli-extended/issues/185)) ([b69e784](https://github.com/Blawuken/revanced-cli-extended/commit/b69e784785f7f262f83b35c4f241c90036169fc7))
* improve logging ([df85fa3](https://github.com/Blawuken/revanced-cli-extended/commit/df85fa37ef067681a027e6fe9212c8a065d4981b))
* improve missing compatibility annotation tracing log ([2c7eb72](https://github.com/Blawuken/revanced-cli-extended/commit/2c7eb7274c713dfbcb53c5f3b6a9205c751914fa))
* Improve option descriptions ([d5ea5a0](https://github.com/Blawuken/revanced-cli-extended/commit/d5ea5a0ab1cc015730063e5be94ee18bd88cc906))
* Include or exclude patches by their index in relation to supplied patch bundles ([b2055ce](https://github.com/Blawuken/revanced-cli-extended/commit/b2055ce07df3ab9a9f3f73ab17d8c2cf02f2ae62))
* integrations merge ([919b34e](https://github.com/Blawuken/revanced-cli-extended/commit/919b34e174e95ee9b6adef50e405b9bbe117803a))
* issue templates [skip ci] ([bac8c67](https://github.com/Blawuken/revanced-cli-extended/commit/bac8c67d6f7bc10a38bb98a2f6e3f5cf6fa2e3e1))
* List patches which are compatible with any app ([#297](https://github.com/Blawuken/revanced-cli-extended/issues/297)) ([0139dfe](https://github.com/Blawuken/revanced-cli-extended/commit/0139dfe0bfa06a13f56dc03e7718aaf644029614))
* load patches dynamically & use kotlinx.cli ([4624384](https://github.com/Blawuken/revanced-cli-extended/commit/4624384f28378efeb5cae54365169905a0ed4de7))
* Log saved patched APK file path ([16109bd](https://github.com/Blawuken/revanced-cli-extended/commit/16109bd8bc6236debf71cbc8db78fe452b2ed00d))
* Log stacktrace in new line ([c67e3c7](https://github.com/Blawuken/revanced-cli-extended/commit/c67e3c70c7eaa514cde1bebe775a2216bc4a6074))
* Make `--out´ option optional ([3765957](https://github.com/Blawuken/revanced-cli-extended/commit/3765957043989fe7a8932a0c548566a78d04fc41))
* migrate logger to `slf4j` ([6c4c192](https://github.com/Blawuken/revanced-cli-extended/commit/6c4c1924ee9ae75af3449749a6a82b7ae5572129))
* more efficient zipalign ([a942a57](https://github.com/Blawuken/revanced-cli-extended/commit/a942a57364777d6ab6fcb11e6171cc4b496c8540))
* Patch Options CLI implementation ([#132](https://github.com/Blawuken/revanced-cli-extended/issues/132)) ([3f5345a](https://github.com/Blawuken/revanced-cli-extended/commit/3f5345af6e45bfb6c91d52fc089ab18d81fdc998))
* properly make use of logging facade ([41898d7](https://github.com/Blawuken/revanced-cli-extended/commit/41898d7547690e3130372414515c5645e5dc2634))
* remove extra zipalign step ([#106](https://github.com/Blawuken/revanced-cli-extended/issues/106)) ([c8e793e](https://github.com/Blawuken/revanced-cli-extended/commit/c8e793efab8eed39b2cb564bee80ef6e0b2a7d03))
* remove option `--with-descriptions` ([07a423b](https://github.com/Blawuken/revanced-cli-extended/commit/07a423b19ec72e9f020aeb0222f4ced571036dbe))
* remove unused option `-r` ([467d838](https://github.com/Blawuken/revanced-cli-extended/commit/467d8387e646c88d24a30406a5b2e84065ef4d54))
* rename `debugging` option to `experimental` ([98bd6f3](https://github.com/Blawuken/revanced-cli-extended/commit/98bd6f3f4b3eb34c445cbd5e3a3196f399f8bb3b))
* rip-lib and unsigned ([daece06](https://github.com/Blawuken/revanced-cli-extended/commit/daece06f49b48b944e1f29937f96c2c70f143b1c))
* rollback the default values of keystore alias and password to CLI v3.0 (compatible with old keystore) ([2d48607](https://github.com/Blawuken/revanced-cli-extended/commit/2d486076f7340b3cd4b76a0ebe440c7493149212))
* run `release.yml` workflow on branch `dev` ([9a64730](https://github.com/Blawuken/revanced-cli-extended/commit/9a6473056b940c6df4860dd09c09d7ac61545f7d))
* section `acknowledgements` for issue templates ([0e3ecc3](https://github.com/Blawuken/revanced-cli-extended/commit/0e3ecc3a51540b71072ae0be0eb94d115a5b1f92))
* separate logger to stdout & stderr ([#63](https://github.com/Blawuken/revanced-cli-extended/issues/63)) ([0ddc2b5](https://github.com/Blawuken/revanced-cli-extended/commit/0ddc2b54b739dae3e8ccc983bab73fc84e72be0a))
* separate options for `--list` ([#60](https://github.com/Blawuken/revanced-cli-extended/issues/60)) ([52b3161](https://github.com/Blawuken/revanced-cli-extended/commit/52b316150de397ebdee979caf51d4cb20961cf70))
* show description when listing patches ([af32572](https://github.com/Blawuken/revanced-cli-extended/commit/af32572f29d0f0a45ee5c3e01ba4cf1f91fe2f10))
* show full package name when listing patches ([#240](https://github.com/Blawuken/revanced-cli-extended/issues/240)) ([7174364](https://github.com/Blawuken/revanced-cli-extended/commit/7174364ef8ef5d6ce8351a8340f9c1a5b58eac3c))
* Simplify command description ([3b3f7c7](https://github.com/Blawuken/revanced-cli-extended/commit/3b3f7c7a7a7b2795e3d1fad776f6b457f2e68c7b))
* simplify log message ([74d73ca](https://github.com/Blawuken/revanced-cli-extended/commit/74d73ca3a7ba2f5da872fe9a241629e1c143cd4e))
* support for `--install` ([d1ceab4](https://github.com/Blawuken/revanced-cli-extended/commit/d1ceab45c89901f79d46c62f03186502021afb26))
* trace logs when compatibility annotation is missing ([#166](https://github.com/Blawuken/revanced-cli-extended/issues/166)) ([c590bf5](https://github.com/Blawuken/revanced-cli-extended/commit/c590bf559c4d2d2667c2af0c0da23d4706fcd4b7))
* unmount all occurrences in `/proc/mounts` ([#131](https://github.com/Blawuken/revanced-cli-extended/issues/131)) ([4f4e1f9](https://github.com/Blawuken/revanced-cli-extended/commit/4f4e1f9834bf28d9be2efd4fd7bae19951b85258))
* use `am` instead of `monkey` to launch the app ([#159](https://github.com/Blawuken/revanced-cli-extended/issues/159)) ([6a35cf7](https://github.com/Blawuken/revanced-cli-extended/commit/6a35cf7ea46a4474120626ce03d28490cc96bf07))
* use `install` mode by default ([1a3db77](https://github.com/Blawuken/revanced-cli-extended/commit/1a3db77c21b5795220fbac1ec36827fc521fface))
* use better logging text ([b0e748d](https://github.com/Blawuken/revanced-cli-extended/commit/b0e748daff527ee7f417b3069882e074896fc131))
* use friendly descriptions ([3dd875d](https://github.com/Blawuken/revanced-cli-extended/commit/3dd875d14cca488ade6d21bbd4cce0d481692134))
* use new patch naming convention ([f6c221d](https://github.com/Blawuken/revanced-cli-extended/commit/f6c221d72dc43ebea00e5eba6bfa02751ae8ad77))
* Use ReVanced Library in ReVanced CLI ([7794327](https://github.com/Blawuken/revanced-cli-extended/commit/7794327a11e8a0e0f28176cd45fad797b924c45f))
* use separate command to list patches ([b74213f](https://github.com/Blawuken/revanced-cli-extended/commit/b74213f66e0d04d3a0ae6197d069631388e06580))
* use separate command to patch ([32da961](https://github.com/Blawuken/revanced-cli-extended/commit/32da961d57537e99b39fd92b625a1c73f8314bc6))
* use separate command to uninstall ([c0cc909](https://github.com/Blawuken/revanced-cli-extended/commit/c0cc90962646cfffd5e2730ae556423271a7990b))
* use simpler log ([ba758f0](https://github.com/Blawuken/revanced-cli-extended/commit/ba758f00f4ce18791439b7e72fe1ad2e7f11f8af))
* Word log message better ([6942b22](https://github.com/Blawuken/revanced-cli-extended/commit/6942b22a68de5e991987ea89882915917aec93a3))


### Performance Improvements

* Do not check, if the options file exists twice ([e3c5550](https://github.com/Blawuken/revanced-cli-extended/commit/e3c55507cf52e697b9ce9d59decc1cbe4cfe5b43))
* Use a `HashSet` to check for included and excluded patches ([616d14f](https://github.com/Blawuken/revanced-cli-extended/commit/616d14f0097c1ee7ba6dc07be417590f6418e8e5))
* Use multiple threads for writing dex files ([28648a1](https://github.com/Blawuken/revanced-cli-extended/commit/28648a1c53520eef8c799504ff61a35947f878b8))


### Reverts

* feat: remove extra zipalign step ([c3d8fec](https://github.com/Blawuken/revanced-cli-extended/commit/c3d8fecad0ed9d583b9f1f79bc271e0535d87be2))


### BREAKING CHANGES

* This changes many signatures of existing APIs and adds new functions for signing
* This changes the log handler signature
* This introduces major changes to how ReVanced CLI is used from the command line.
* Not backwards compatible, since a lot of classes where renamed.
