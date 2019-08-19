# 1.0.0 (2019-08-19)


* Expressify Openwhisk and use probot's router #34 (#35) ([6b27d3e](https://github.com/adobe/openwhisk-probot-builder/commit/6b27d3e)), closes [#34](https://github.com/adobe/openwhisk-probot-builder/issues/34) [#35](https://github.com/adobe/openwhisk-probot-builder/issues/35) [#34](https://github.com/adobe/openwhisk-probot-builder/issues/34)


### Bug Fixes

* **config:** make semantic release update package.json ([ce312ee](https://github.com/adobe/openwhisk-probot-builder/commit/ce312ee))
* **config:** use correct action builder ([9ecad08](https://github.com/adobe/openwhisk-probot-builder/commit/9ecad08))
* **deploy:** switch to default nodejs10 container ([ea3a1ab](https://github.com/adobe/openwhisk-probot-builder/commit/ea3a1ab)), closes [#42](https://github.com/adobe/openwhisk-probot-builder/issues/42)
* **deploy:** switch to default nodejs10 container ([72866b1](https://github.com/adobe/openwhisk-probot-builder/commit/72866b1))
* **index:** remove development server from index due to webpack problems ([#94](https://github.com/adobe/openwhisk-probot-builder/issues/94)) ([f0dd76e](https://github.com/adobe/openwhisk-probot-builder/commit/f0dd76e))
* **initial:** trigger release ([7ef6854](https://github.com/adobe/openwhisk-probot-builder/commit/7ef6854))
* **log:** add action params to log ([#41](https://github.com/adobe/openwhisk-probot-builder/issues/41)) ([518cfa7](https://github.com/adobe/openwhisk-probot-builder/commit/518cfa7)), closes [#40](https://github.com/adobe/openwhisk-probot-builder/issues/40)
* **package:** update @adobe/openwhisk-action-builder to version 0.7.0 ([26adc44](https://github.com/adobe/openwhisk-probot-builder/commit/26adc44)), closes [#62](https://github.com/adobe/openwhisk-probot-builder/issues/62) [#63](https://github.com/adobe/openwhisk-probot-builder/issues/63)
* **package:** update @adobe/openwhisk-action-builder to version 1.0.0 ([a75d2e8](https://github.com/adobe/openwhisk-probot-builder/commit/a75d2e8)), closes [#72](https://github.com/adobe/openwhisk-probot-builder/issues/72)
* **package:** update dependencies ([88b5dff](https://github.com/adobe/openwhisk-probot-builder/commit/88b5dff))
* **package:** update dependencies ([5430d73](https://github.com/adobe/openwhisk-probot-builder/commit/5430d73))
* **package:** update dependencies ([#92](https://github.com/adobe/openwhisk-probot-builder/issues/92)) ([b1db928](https://github.com/adobe/openwhisk-probot-builder/commit/b1db928))
* **package:** update dotenv to version 8.0.0 ([fa30761](https://github.com/adobe/openwhisk-probot-builder/commit/fa30761))
* **package:** update openwhisk-action-builder to version 0.5.2 ([f03043c](https://github.com/adobe/openwhisk-probot-builder/commit/f03043c))
* **package:** update probot to version 9.2.11 ([31ac239](https://github.com/adobe/openwhisk-probot-builder/commit/31ac239))
* **package:** update probot to version 9.2.12 ([7790017](https://github.com/adobe/openwhisk-probot-builder/commit/7790017))
* **package:** update probot to version 9.2.13 ([bd09c13](https://github.com/adobe/openwhisk-probot-builder/commit/bd09c13))
* **package:** update probot to version 9.2.19 ([b90cd12](https://github.com/adobe/openwhisk-probot-builder/commit/b90cd12)), closes [#89](https://github.com/adobe/openwhisk-probot-builder/issues/89)
* **package:** update probot to version 9.2.4 ([2405a48](https://github.com/adobe/openwhisk-probot-builder/commit/2405a48)), closes [#56](https://github.com/adobe/openwhisk-probot-builder/issues/56)
* **package:** update probot to version 9.2.5 ([d239309](https://github.com/adobe/openwhisk-probot-builder/commit/d239309))
* **package:** update probot to version 9.2.6 ([309acf2](https://github.com/adobe/openwhisk-probot-builder/commit/309acf2))
* **package:** update probot to version 9.2.7 ([5755cd4](https://github.com/adobe/openwhisk-probot-builder/commit/5755cd4))
* **package:** update probot to version 9.2.8 ([1b13993](https://github.com/adobe/openwhisk-probot-builder/commit/1b13993))
* **package:** update probot to version 9.2.9 ([2f5fb0a](https://github.com/adobe/openwhisk-probot-builder/commit/2f5fb0a))
* **package:** update to @adobe/openwhisk-action-builder@1.2.1 ([62efa4c](https://github.com/adobe/openwhisk-probot-builder/commit/62efa4c))
* **probot:** Avoid sticky errors ([#49](https://github.com/adobe/openwhisk-probot-builder/issues/49)) ([dbbabe0](https://github.com/adobe/openwhisk-probot-builder/commit/dbbabe0))
* **test:** ensure latest mocha works ([f8a1982](https://github.com/adobe/openwhisk-probot-builder/commit/f8a1982))
* **wrapper:** adjust to new __ow_body behaviour of expressify ([9a36502](https://github.com/adobe/openwhisk-probot-builder/commit/9a36502))


### Features

* **action:** allow githup app private key to be specified via action params ([#65](https://github.com/adobe/openwhisk-probot-builder/issues/65)) ([8fdf044](https://github.com/adobe/openwhisk-probot-builder/commit/8fdf044)), closes [#64](https://github.com/adobe/openwhisk-probot-builder/issues/64)
* **dev:** extract dev tools ([e670e8a](https://github.com/adobe/openwhisk-probot-builder/commit/e670e8a))
* **development:** Add simple way to run development server. ([7a684d0](https://github.com/adobe/openwhisk-probot-builder/commit/7a684d0)), closes [#51](https://github.com/adobe/openwhisk-probot-builder/issues/51)
* **express:** Use serverless-http (via new action builder) ([1f12c6c](https://github.com/adobe/openwhisk-probot-builder/commit/1f12c6c)), closes [#44](https://github.com/adobe/openwhisk-probot-builder/issues/44)
* **init:** pass probot options ([#59](https://github.com/adobe/openwhisk-probot-builder/issues/59)) ([6ae62d0](https://github.com/adobe/openwhisk-probot-builder/commit/6ae62d0)), closes [#58](https://github.com/adobe/openwhisk-probot-builder/issues/58)
* **logging:** Removed Logger from exports in favour and use action builder ([f664ee8](https://github.com/adobe/openwhisk-probot-builder/commit/f664ee8))


### BREAKING CHANGES

* **action:** The GH_WEBHOOK_SECRET param in now called GH_APP_WEBHOOK_SECRET.
* **action:** the secret and appId can no longer be loaded from env.APP_ID and env.WEBHOOK_SECRET
* **logging:** Logger no longer exported.
* - API of OpenWhiskWrapper has changed to reflect express semantics.

# [3.1.0](https://github.com/adobe/openwhisk-probot-builder/compare/v3.0.8...v3.1.0) (2019-06-19)


### Features

* **development:** Add simple way to run development server. ([7a684d0](https://github.com/adobe/openwhisk-probot-builder/commit/7a684d0)), closes [#51](https://github.com/adobe/openwhisk-probot-builder/issues/51)
