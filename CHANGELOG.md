# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [15.0.0](https://github.com/MaTriXy/material-components-web/compare/v5.1.0...v15.0.0) (2025-02-10)


### Bug Fixes

* circular progress no longer cause dialogs to be scrollable ([9290bd3](https://github.com/MaTriXy/material-components-web/commit/9290bd3b0b919a022d6ff0cfd1c27bb66f7fd44b))
* **base:** Fix compiler errors for TS 4.8 upgrade ([c8bdf61](https://github.com/MaTriXy/material-components-web/commit/c8bdf6144912e20bc616a268404e4f6bc9c45ae3))
* **button:** add `pressed-outline-color` key ([ab55c07](https://github.com/MaTriXy/material-components-web/commit/ab55c07d28e2a10b30260021e97f8c337208e937))
* **button:** Add line-height: initial to button progress indicator class ([602fe8e](https://github.com/MaTriXy/material-components-web/commit/602fe8efa3f3c9a41c7f74a7c5717a0abdec0c60))
* **button:** Attribute `hidden` now correctly hides the button. ([88db019](https://github.com/MaTriXy/material-components-web/commit/88db019902ca09811794b202d66ce1f9f2e54aec))
* **button:** fix theme elevation resolver ([2528c1c](https://github.com/MaTriXy/material-components-web/commit/2528c1c3b6b2a9870807df8c03c49ea45db811b7))
* **button:** Refactored HCM focus ring into a base style with display: none so mixins can be applied to both a visible non-HCM ring and the HCM ring without extra specificity to override ripple-theme.focus selectors ([6a61d62](https://github.com/MaTriXy/material-components-web/commit/6a61d62f6b2b1f6b4bcf7477bdad46ba4139e5c8))
* **button:** update HCM shim to use the existing focus-ring ([a657abb](https://github.com/MaTriXy/material-components-web/commit/a657abb61a2c7d23c2bd92c3cbd54ed404d0bafe))
* **card:** Fix card ripple issue - the ripple is a child of the primary action element. ([f43e0ce](https://github.com/MaTriXy/material-components-web/commit/f43e0ceb536056569898c0ffbe084acc2af54a81))
* **checkbox:** Add explicit system color for checkmark in HCM. ([8c4da22](https://github.com/MaTriXy/material-components-web/commit/8c4da223a7d35c4ca0a4f27534ecdb13087d0f1b))
* **checkbox:** Attribute `hidden` now correctly hides the checkbox. ([63d3a14](https://github.com/MaTriXy/material-components-web/commit/63d3a146e4ce16867f742ce41b1760da7233ed66))
* **checkbox:** move forced-colors theme out of static styles ([bbd1126](https://github.com/MaTriXy/material-components-web/commit/bbd11268f0ea4fd45205a642f1d26a4c4ff34e05))
* **checkbox:** Update checkbox theme styles mixin to accept css vars ([c14e977](https://github.com/MaTriXy/material-components-web/commit/c14e977ee36c26074b04dea5ce37e2300e9d3735))
* **chip:** Propagate unhandled keyboard events ([6081d82](https://github.com/MaTriXy/material-components-web/commit/6081d829b081384ff8433a92bf91db364c588e16))
* **chips:** Add missing tokens for leading icon for validation ([4356e05](https://github.com/MaTriXy/material-components-web/commit/4356e05c5e17a58d0a714e9f087db4b5060085bd))
* **chips:** Fix typography selector in GMDC-Wiz chips theming ([43c7d87](https://github.com/MaTriXy/material-components-web/commit/43c7d87dc0c928d74652ceaebebca51c69b6eaaf))
* **chips:** Update elevation resolver function and mixins that apply elevation ([96f4726](https://github.com/MaTriXy/material-components-web/commit/96f472604cd098572f50987262bcab933574f7b2))
* **chips:** Update elevation resolver function and mixins that apply elevation ([a0ae73b](https://github.com/MaTriXy/material-components-web/commit/a0ae73b0e05a584715b2ec2841c033267f914c34))
* **chips:** Update elevation resolver logic and update suggestion chip accordingly ([7c35e50](https://github.com/MaTriXy/material-components-web/commit/7c35e503698c72d1d848d1429cbb3106d555930d))
* **chips:** Update theme mixins to use the new resolver function ([05fb07f](https://github.com/MaTriXy/material-components-web/commit/05fb07f9fd11ebf692b74591bc944360f613108f))
* **datatable:** Add extra class to pagination Select to fix GM3 styles ([ce8b532](https://github.com/MaTriXy/material-components-web/commit/ce8b5326fa2f15bd4e4d0a653a37d0d1a4bbf315))
* **datatable:** Adjust data table last row border-radius to support setting row background-color. ([ba78e87](https://github.com/MaTriXy/material-components-web/commit/ba78e87246af31e1fe7dd03241a7565f2892fd64))
* **datatable:** Don't use top-level `.mdc-data-table` selector in `theme-styles` ([2c1a8f8](https://github.com/MaTriXy/material-components-web/commit/2c1a8f8fdd53fd509bec519c1d92c1171c75b177))
* **datatable:** Remove unsupported token ([a5fe069](https://github.com/MaTriXy/material-components-web/commit/a5fe069d51e80ab17ab26c902401e75fd8968509))
* **datatable:** Update `static-styles` mixin with remaining styles ([bacda48](https://github.com/MaTriXy/material-components-web/commit/bacda4885c1f9e15eb4eba15bef2f56b329ef085))
* **dialog:** Add tabindex=-1 to dialog surface and set its outline to 0 ([4e840d6](https://github.com/MaTriXy/material-components-web/commit/4e840d68533ef04e438c0b10f1047627a1d01e0c))
* **dialog:** fix dialog close button z-index in dark mode ([26bacc3](https://github.com/MaTriXy/material-components-web/commit/26bacc3feee6ea39c95b35b73c99040399b0f530))
* **dialog:** Fix fullscreen scrim z-index during animation ([39f9424](https://github.com/MaTriXy/material-components-web/commit/39f9424b3806fe8d5b45f1f0cc02fb5b4a7a6998))
* **dialog:** Render dividers in Firefox 94 on Windows HCM ([fae6c65](https://github.com/MaTriXy/material-components-web/commit/fae6c652d7debc3e2875ab9049d806513ddc2421))
* **dialog:** Set default z-index for close button in FloatingSheet dialog. ([3366a71](https://github.com/MaTriXy/material-components-web/commit/3366a71d72f48e946a3f3b314b315395fafb3a1f))
* **dom:** transparent-border mixin RTL bugfix ([395f1ce](https://github.com/MaTriXy/material-components-web/commit/395f1ce61c0056590edd1f7b629f17c4d8599115))
* **dom:** transparent-border mixin RTL bugfix ([07acdde](https://github.com/MaTriXy/material-components-web/commit/07acddef343184362c317a57957a483b4c62cac4))
* **fab:** Add focus ring in HCM. ([d57ec74](https://github.com/MaTriXy/material-components-web/commit/d57ec74c7e9afe5db07162202e6f05b28dd581db))
* **fab:** Attribute `hidden` now correctly hides the radio button. ([c501884](https://github.com/MaTriXy/material-components-web/commit/c5018840c89427aeb4be71472992538ef628c868))
* **floating-label:** Generate valid CSS calc ([304a94e](https://github.com/MaTriXy/material-components-web/commit/304a94e8bde786452d9d8c6b80e8e9e0d84bfcc2))
* **floating-label:** replaced incompatible value types in calc statement by compatible ones ([23073a3](https://github.com/MaTriXy/material-components-web/commit/23073a303310f5aad6a0fef0c2e96fd8dd7ab360))
* **focus:** Add z-index to focus ring. ([b0103d1](https://github.com/MaTriXy/material-components-web/commit/b0103d10aca7e6e8272cde283d9d36272702bf87))
* **focus:** focus-ring.theme-styles now ingests custom properties emitted by focus-ring.theme. focus-ring.theme now accepts only one target-shape theme property, and the focus ring will mold around it. ([a69c14e](https://github.com/MaTriXy/material-components-web/commit/a69c14e10f605e54404d8ceac402c4e5d55d818f))
* **focus:** Use validate.theme-styles in focus-ring.theme-styles. ([1f99f3c](https://github.com/MaTriXy/material-components-web/commit/1f99f3c5033b1712a737d04e7b7b40229bcb4134))
* **focus ring:** Using box-shadow instead of border for focus ring as animating on box-shadow is more performant. ([3a705fa](https://github.com/MaTriXy/material-components-web/commit/3a705fa1d18089ae89c481b5bdfdfed2d378742e))
* **focus-ring:** add 2d padding customizability, RTL bugfix ([f81fb1d](https://github.com/MaTriXy/material-components-web/commit/f81fb1d232901c17d5794499c26e746ccab1af19))
* **focus-ring:** box-sizing bugfix to content-box. If box-sizing border-box is inherited the ring spacing will collapse. ([e58552c](https://github.com/MaTriXy/material-components-web/commit/e58552c6efa0442a36f441efe27cd01f3df2a524))
* **focus-ring:** ignore pointer events ([3ef470e](https://github.com/MaTriXy/material-components-web/commit/3ef470efe6f1d213935dca37ad213030cdd30d88))
* **focus-ring:** RTL bugfix ([e00181e](https://github.com/MaTriXy/material-components-web/commit/e00181e59cb1f29f4a8280f48b377a667a3e783b))
* **focusring:** add real color to focus ring ([15b2215](https://github.com/MaTriXy/material-components-web/commit/15b22154036ffb0fcadc7b404125a016e28e2b23))
* **formfield:** Change cursor style on label to `inherit` rather than `auto` to adopt customization. ([4b35cb7](https://github.com/MaTriXy/material-components-web/commit/4b35cb7d05ac0abf313963370ee2f4b20456df45))
* **formfield:** Fix for [#8187](https://github.com/MaTriXy/material-components-web/issues/8187) (rolling back the errant commit) ([2f5b899](https://github.com/MaTriXy/material-components-web/commit/2f5b899bc1a7e6dc4015186eed59d937aeb2d743))
* **iconbutton:** Apply icon-size theme-styles properly for font icons. ([77cf00e](https://github.com/MaTriXy/material-components-web/commit/77cf00e3767e7ae73fd704e55830ceda8b71fdc9))
* **iconbutton:** Extract focus ring display properties into static styles to prevent customization via density mixins from overriding focus ring display conditions ([3c7b844](https://github.com/MaTriXy/material-components-web/commit/3c7b844c2a27c678d9be5e93f9845dd8efda5835))
* **iconbutton:** Fixed max width and height for high contrast mode focus ring on icon buttons. Display only in forced colors mode. ([cf42927](https://github.com/MaTriXy/material-components-web/commit/cf429277817af685fd0b23a21a2e10ddabc4b9ef))
* **iconbutton:** support custom properties as values for an icon button ([68aaed9](https://github.com/MaTriXy/material-components-web/commit/68aaed940081f45cc1730e684c70e132793b6633))
* **linearprogress:** Fix `track-color` in Theming API ([79b1b61](https://github.com/MaTriXy/material-components-web/commit/79b1b612b9ec10a42caf5946efdead14e44e7f7a))
* **linearprogress:** Fix buffer dots animation when track height is increased ([0c53abc](https://github.com/MaTriXy/material-components-web/commit/0c53abc81c05b9afecc127380c700c99fac5d2f8))
* **linearprogress:** Fix missing buffering keyframes ([ea21914](https://github.com/MaTriXy/material-components-web/commit/ea219142617255a2b365823701b6ea43ff9a9611))
* **list:** Allow alt + enter to select index for lists. ([113b1a3](https://github.com/MaTriXy/material-components-web/commit/113b1a38e87337fdd00c7495fda3299df2dbc317))
* **list:** behavior in case of changing focus from -1 to -1 with forceUpdate: true ([ae278a2](https://github.com/MaTriXy/material-components-web/commit/ae278a2fe94fdb8c5d0716fb34cbe84a691d6146))
* **list:** Fix list leading/trailing icon theming ([36a4cba](https://github.com/MaTriXy/material-components-web/commit/36a4cba9944392b391b86d41405ee21fb97f4c22))
* **list:** Fixes how list handles `CTRL-A` keyboard interactions for multi-selection lists when there are disabled list items. ([a911b38](https://github.com/MaTriXy/material-components-web/commit/a911b386b2fded69e3468ef42e7ef25eb33fcd70))
* **list:** Fixing css for calculating `$mdc-list-subheader-margin` param. ([357f2e5](https://github.com/MaTriXy/material-components-web/commit/357f2e5f15f6374c9d93da135a8b070239ba7464))
* **list:** Improve a11y for multi-select lists ([9736ddc](https://github.com/MaTriXy/material-components-web/commit/9736ddce9c12f5485e746984225919568541e88d))
* **list:** Initialize selectedIndex as an array for checkbox list ([0347671](https://github.com/MaTriXy/material-components-web/commit/034767110778aab3e5f0a3240937d8a07c21197e))
* **list:** only set overflow hidden on mdc-list-item--with-leading-image ([033ae08](https://github.com/MaTriXy/material-components-web/commit/033ae083aad9ad4376e64aa328df936c7adb5a32))
* **list:** Remove ripple styles for disabled items in deprecated list. ([f52358d](https://github.com/MaTriXy/material-components-web/commit/f52358dd0796308919bb78deffc573d0d933c7de))
* **list:** Update lastSelectedIndex when toggling a checkbox range ([dcba26f](https://github.com/MaTriXy/material-components-web/commit/dcba26fe1028cf151ebf34c5947082a49cc85f10))
* **menu:** Account for empty map being passed to theme mixin ([0c52ade](https://github.com/MaTriXy/material-components-web/commit/0c52adeab4a46fb942e7ac64a950d094b54716f8))
* **menu:** do not require all for theme-styles ([1fb4b1a](https://github.com/MaTriXy/material-components-web/commit/1fb4b1a063ecaec1ad0d508b3f5ae5aca3e96652))
* **menu:** make require-all a theme-styles param. ([c64a277](https://github.com/MaTriXy/material-components-web/commit/c64a2776efe4f0aaaee5c32f5fb9ef3570483213))
* **menusurface:** Allow for having (non hoisted) menu inside an overflow hiding parent. ([03618ab](https://github.com/MaTriXy/material-components-web/commit/03618ab70c69118c7dda1c301a30aff4e5318458))
* **menusurface:** Calculate available space on left using `anchorMargin.left` when positioning menu. ([13eea1b](https://github.com/MaTriXy/material-components-web/commit/13eea1b2d64cdc79f86cf065afb32e461c3d7b2b))
* **radio:** Attribute `hidden` now correctly hides the radio button. ([cf9f123](https://github.com/MaTriXy/material-components-web/commit/cf9f12371c251063b3ed1553c439a23f69899377))
* **radio:** Fix disabled state in Firefox Windows high contrast mode ([23043ac](https://github.com/MaTriXy/material-components-web/commit/23043acd0e5341729230cc6e1840460977056115))
* **radio:** Modify theme styles Sass mixin validation to validate only keys ([390220e](https://github.com/MaTriXy/material-components-web/commit/390220e422be57e8f38b74e04d8e8aba6082d333))
* **select:** <fix inherited ellipsis color for list items in selects> ([c43b343](https://github.com/MaTriXy/material-components-web/commit/c43b3438b4b7eeb777072525f9ae07c97d27c0bb))
* **select:** Add border to select menu in HCM. ([5d80969](https://github.com/MaTriXy/material-components-web/commit/5d809696c6699bf9563e8faf8f79ff6ebd78febf))
* **select:** add separate touch target element to Select to maintain size even when shrunk ([453a624](https://github.com/MaTriXy/material-components-web/commit/453a6248a0088c8243852fd20f83fa50c71f3a5f))
* `aria label` lint error in strings ([7f224dd](https://github.com/MaTriXy/material-components-web/commit/7f224ddd44f8ee0d2203103dd4ce6b2886dba72c))
* **select:** Attribute `hidden` now correctly hides the select component. ([551b40d](https://github.com/MaTriXy/material-components-web/commit/551b40d180a02c45f0432e5e49c35cfd3fb5c2b0))
* **select:** revert down/up arrow on anchor changing selected index ([43d08ba](https://github.com/MaTriXy/material-components-web/commit/43d08ba77e44dffbca99194ee18dbd202c8684f7))
* **slider:** Fix bug where secondary click moves slider thumb. ([3ab9565](https://github.com/MaTriXy/material-components-web/commit/3ab956515feb5c861498b156e68493e6f7f2a578))
* **slider:** Fix IE11 bug - `unset` is unsupported in IE. ([f460e23](https://github.com/MaTriXy/material-components-web/commit/f460e23dae619c6d09de114cc8c319972b7d1b10))
* **slider:** In updateUI, fix behavior to match jsdoc claim that when thumb param is undefined it updates both thumbs. Input attributes were not being updated at all. ([cc4ed13](https://github.com/MaTriXy/material-components-web/commit/cc4ed13ccda7b44edce0070edd6ee215e98cc792))
* **slider:** Make the slider errors easier to debug by providing all relevant values in the error message. ([8687937](https://github.com/MaTriXy/material-components-web/commit/868793776d9610ab068af706297a4f4599c7f6f1))
* **slider:** resolve Sass deprecation warning ([7971d6a](https://github.com/MaTriXy/material-components-web/commit/7971d6ad5c3a7e771c4a74757b2185edd97443fd))
* **snackbar:** address Trusted Types violation ([cbd9358](https://github.com/MaTriXy/material-components-web/commit/cbd9358a61e7626ebc12af2cdd3dc465e11ce8bf))
* **switch:** Attribute `hidden` now correctly hides the switch. ([6432d8f](https://github.com/MaTriXy/material-components-web/commit/6432d8fd7862fb39258a7970119f8db9eb8fbdb0))
* **switch:** Restore Firefox 94 HCM outlines ([39cf14b](https://github.com/MaTriXy/material-components-web/commit/39cf14bc3b0ef053219328d36faaf2636e0f77f4))
* **tabs:** Add already supported tokens to the theme list ([3a1f46c](https://github.com/MaTriXy/material-components-web/commit/3a1f46c6692c2ee2130de7712722c548928624eb))
* **text-field:** Update textfield icons to allow spacebar keypresses to trigger an interaction ([c0a11ef](https://github.com/MaTriXy/material-components-web/commit/c0a11ef0d000a098fd0c372be8f12d6a99302855))
* **textfield:** Fix breaking tests due to no valid pointerId being associated with pointer events. ([15db4f1](https://github.com/MaTriXy/material-components-web/commit/15db4f1641bd3657ed230afacb41da84fb1077bc))
* **textfield:** Improve textfield character counter for screen reader ([2797ff8](https://github.com/MaTriXy/material-components-web/commit/2797ff8b651ee34900cf38b115dc69193abdb7b8))
* **textfield:** styles that override floating-label font-size take into account that clients can change this font-size. ([ebb636f](https://github.com/MaTriXy/material-components-web/commit/ebb636f3d44e1a194f822d7dfcb5d70feb817520))
* correct behavior of checkboxes/radios in a list. ([f771b09](https://github.com/MaTriXy/material-components-web/commit/f771b091ce1e5b1b97b3a508f1459e4665008a80))
* rollback of cl/491630368 ([168a629](https://github.com/MaTriXy/material-components-web/commit/168a629a45d885cb6d8778c2d3a75ddf1cd2992a))
* The focus ring shouldn't ignore the container-shape value ([7a3942e](https://github.com/MaTriXy/material-components-web/commit/7a3942e7ad206c3754dd34e2da62b88e4a9dc311))
* Use state-layer-size to correctly position the icon inside of an icon button ([0270229](https://github.com/MaTriXy/material-components-web/commit/02702296e31ef8f9e3068017c73b4740eb56b9cf))
* **list:** rolling back update of list styles since this is causing failures. ([eb103d4](https://github.com/MaTriXy/material-components-web/commit/eb103d4b5d33e0d1535ea28ca0089d2c7002fab6))
* **menusurface:** Make "private" `base_` mixin truly private ([da22ca9](https://github.com/MaTriXy/material-components-web/commit/da22ca960bdac2e0a0fc9e67f6dc1e1164fbe73b))
* **menusurface:** reposition menu surface on window resize events ([6023b1c](https://github.com/MaTriXy/material-components-web/commit/6023b1cd3d2c1213d47ac68e053293270e3e371f))
* **select:** apply `text-field-error-label-text-color` tokens. ([01da0ca](https://github.com/MaTriXy/material-components-web/commit/01da0cabb367ea0a250885d9ee35a20913f87549))
* **select:** relax handling of corner radii for filled variant ([b5c13a7](https://github.com/MaTriXy/material-components-web/commit/b5c13a7a88fdf69bb5515df1dcbb8ce655cfe22c))
* **select:** update text field in select to accept dynamic shape and height ([aa5ac7f](https://github.com/MaTriXy/material-components-web/commit/aa5ac7fe52b870752cd578715ad1760731c63aa5))
* **select:** use `text-field-disabled-trailing-icon-color` token ([adcdb7d](https://github.com/MaTriXy/material-components-web/commit/adcdb7db997f3d471346b05f7b8aefec522a96c2))
* **slider:** Move comment to correct location ([d7a2277](https://github.com/MaTriXy/material-components-web/commit/d7a2277dee780757318ff962277c109a7c615e12))
* **slider:** Move opacity target declaration ([e741b5c](https://github.com/MaTriXy/material-components-web/commit/e741b5c82c7752c36745616d9bc407af590be7d4))
* **slider:** Remove support for deprecated `label-label-text-font-size` token ([8a74f7c](https://github.com/MaTriXy/material-components-web/commit/8a74f7c6d4dffc9e066d548e74ebd7ab1c58ac65))
* **slider:** Replace `label-label-text-font-size` token with `label-label-text-size` ([73537ab](https://github.com/MaTriXy/material-components-web/commit/73537ab0fe98dbf2dc4b824c128c4c05da6ff986))
* **slider:** resolve a couple of errors with new theming API ([8d7ae91](https://github.com/MaTriXy/material-components-web/commit/8d7ae912ab32815d2f01e8540bc49751b8fad38d))
* **slider:** resolve more compilation errors ([db414b8](https://github.com/MaTriXy/material-components-web/commit/db414b864f4c248439d916d4ee36cd43316927ea))
* **slider:** Use CSS Variables instead of hardcoded values for track height ([067af7e](https://github.com/MaTriXy/material-components-web/commit/067af7eff1cc5f3de077068184dfbd31c76f5a41))
* **tabs:** Add validation to tab bar theme ([49041a6](https://github.com/MaTriXy/material-components-web/commit/49041a6c3c713973d289f7a7f3ffa4a991304620))
* **tabs:** adjust rippple area according to container shape ([8c0786d](https://github.com/MaTriXy/material-components-web/commit/8c0786d6f0dca33f9666912598386a04ca153d97))
* **tabs:** Attribute hidden now correctly hides tabs. ([110fafa](https://github.com/MaTriXy/material-components-web/commit/110fafa17ac0756adf377e50b51d8551aab8eb54))
* **tabs:** rolling back style changes due to screenshot breakages. ([5e5c2af](https://github.com/MaTriXy/material-components-web/commit/5e5c2afc06d26a4d091570baf223d8abd79a2f06))
* **tabs:** rolling back style changes due to screenshot breakages. ([2155064](https://github.com/MaTriXy/material-components-web/commit/215506426df0e309e27ce46898c9e5ea6c51da90))
* **textfield:** Add coverage for suffix and prefix text within the font size mixin. ([19bb36a](https://github.com/MaTriXy/material-components-web/commit/19bb36a46b51e79d8bf08948ab5b7d8e9358c2d8))
* **textfield:** Add support for `focus-active-indicator-height` token. ([8c56759](https://github.com/MaTriXy/material-components-web/commit/8c56759428e34766e263008470390487417f00c4))
* **textfield:** add support for placeholder color in theme api ([b994146](https://github.com/MaTriXy/material-components-web/commit/b994146f6d849bd80f280c147d64adae5b930a3c))
* **textfield:** Fix bugs and compilation errors due to custom properties in the theme map ([1dc797e](https://github.com/MaTriXy/material-components-web/commit/1dc797e7f4efe9010be7097b040c0fcb1902ca8c))
* **textfield:** Fix several tokens in theming API ([d3344c1](https://github.com/MaTriXy/material-components-web/commit/d3344c16fd9c006059174e1c3b6d90d2302e8134))
* **textfield:** Fix several tokens in theming API ([9f17ff2](https://github.com/MaTriXy/material-components-web/commit/9f17ff2cb20cb503cedcadbc473b09bc77c6a93e))
* **textfield:** Fix several tokens in theming API ([271aedc](https://github.com/MaTriXy/material-components-web/commit/271aedc306a6adc6acc1f2fe2bb460604c7c3a75))
* **textfield:** initializes 'valid' property from the DOM. ([b836b98](https://github.com/MaTriXy/material-components-web/commit/b836b989225a6259220a98dd23fd2a4b99014031))
* **textfield:** Make it possible to customise leading and trailing icon in disabled states separately ([00d8de0](https://github.com/MaTriXy/material-components-web/commit/00d8de0aadef3f3caffc1ca2a13cf932057dcdbe))
* **theme:** account for null being passed into .theme-styles ([2a9697d](https://github.com/MaTriXy/material-components-web/commit/2a9697dc53e9c7b5b89cc479df9f97a46c095a43))
* **tooltip:** Adjusts logic in `validateTooltipWithCaretDistances` method. ([3e30054](https://github.com/MaTriXy/material-components-web/commit/3e30054fb92c75b85d2f6186f4656d36ea05d6a1))
* **tooltip:** Fix incorrect measurements of rich tooltip widths on subsequent renders. ([7ab3cd3](https://github.com/MaTriXy/material-components-web/commit/7ab3cd3c82b92e741be2e67ead5c44a0ceabe794))
* **tooltip:** Fixes rich tooltip's theme-styles mixin. ([d584104](https://github.com/MaTriXy/material-components-web/commit/d584104537cafcb624ea14f6b8b9ff6ea937d49a))
* **tooltip:** Fixes rich tooltip's theme-styles mixin. ([697fbde](https://github.com/MaTriXy/material-components-web/commit/697fbdebd4bfaa85e0901855d11c8e7febc9c991))
* **tooltip:** Fixing tooltip's z-index mixin. ([a40e3c7](https://github.com/MaTriXy/material-components-web/commit/a40e3c7684ea43f4a75f6afc75a0b8a34f49b674))
* **tooltip:** Stop keydown event propogation when ESC key is pressed. ([8d2d8d3](https://github.com/MaTriXy/material-components-web/commit/8d2d8d3c4dbe6c2a17a5de099d59f7503101999f))
* **tooltip:** Stop re-calculating the tooltip position if the anchor is scrolled out of view. ([684e33d](https://github.com/MaTriXy/material-components-web/commit/684e33d250337e53e46fec26c97b382ba85f60d0))
* **tooltip:** Uses single quotes when retrieving key value from sass map. ([953e689](https://github.com/MaTriXy/material-components-web/commit/953e689f3bad9b0a2b3c384470fc82a2d4b8df92))
* **touch-target:** touch-target mixin now works as expected also when the arguments are custom property strings. ([0e89aab](https://github.com/MaTriXy/material-components-web/commit/0e89aab6b1651c9a22e6caa3c9a9f4b023ff61c3))
* Makes material component to depend on https://github.com/google/safevalues and be Trusted Type compatible. ([a44241e](https://github.com/MaTriXy/material-components-web/commit/a44241e5428e7f83733b2bd8ab7acc851fc2fb85))
* use case-insensitive comparison for the tabindex attribute ([fd95ca7](https://github.com/MaTriXy/material-components-web/commit/fd95ca7ef8eb8479cf9eedceae6a80da4503595b))
* **typography:** Fixes typography `theme-styles` mixin... the value being retreived from the `$theme` map and css property name was swapped. The mixin would request `font-size`/`font-weight`/`letter-spacing` from the `$theme` map (which expects `size`/`weight`/`tracking`)... so these values would always be `null`. ([32b3913](https://github.com/MaTriXy/material-components-web/commit/32b391398aa70f2fbb917cd4649b84d87876cd8e))
* Remove /** [@override](https://github.com/override) */ tags from TypeScript code. ([c3cdff0](https://github.com/MaTriXy/material-components-web/commit/c3cdff07b59adb0f44b40dbbca2cf05868138528))
* Simplify MDCAttachable interface to be any object (Function) that has `attachTo`. ([05db65e](https://github.com/MaTriXy/material-components-web/commit/05db65ec07db5a230e2ba1144000046b09d4c44b))
* Snackbar action button ripple color is applied to the ripple element. ([4e66fb2](https://github.com/MaTriXy/material-components-web/commit/4e66fb2e181b35ac47ae3a6863c101d3ff4f885e))
* **banner:** Adjusting theme api selectors to use `mdc-button`. ([15981e9](https://github.com/MaTriXy/material-components-web/commit/15981e9d95097895247fbcbd6ad9ad14c46be20e))
* **banner:** Correcting incorrect theme values passed through to button's `theme-mixin`. ([0de2f2e](https://github.com/MaTriXy/material-components-web/commit/0de2f2edcb53e05a97ae79c7f5fc181033fbb0cc))
* **banner:** exclude source from npm package ([#7381](https://github.com/MaTriXy/material-components-web/issues/7381)) ([d48a017](https://github.com/MaTriXy/material-components-web/commit/d48a01771a5c5b080179ac34e4ef34146de5e209)), closes [#7360](https://github.com/MaTriXy/material-components-web/issues/7360)
* **banner:** Removing `action-<state>-label-text-color` values from MDC `light-theme` map. ([d97f8f1](https://github.com/MaTriXy/material-components-web/commit/d97f8f133c7d59bbddc49fe39dd9c714bcbb01d4))
* **button:** cleanup outlined button theme keys ([28d0d75](https://github.com/MaTriXy/material-components-web/commit/28d0d75bb554be14171de19f50d082f837125f37))
* **button:** fix touch target reset in context of link buttons ([3b8d442](https://github.com/MaTriXy/material-components-web/commit/3b8d4429e3373661fef202613389e4f2f00b33ad))
* **button:** remove negative padding around icons ([d470693](https://github.com/MaTriXy/material-components-web/commit/d4706933f473925ec3a1ce6f7152208b31664538))
* **button:** stack ripple behind content ([e1e69fd](https://github.com/MaTriXy/material-components-web/commit/e1e69fd8e5fb5624173bc3836f92e6824596ad04))
* **density:** typo in variable exports ([6df682e](https://github.com/MaTriXy/material-components-web/commit/6df682e746d1c417fe00376ba6ec33bd72159757))
* **dom:** Support providing an owner document for announcer messages. ([6236f35](https://github.com/MaTriXy/material-components-web/commit/6236f3576a7f39f452175206f96c08b08315444b))
* **elevation:** reduce warnings when not providing elevation tokens ([adb9f1a](https://github.com/MaTriXy/material-components-web/commit/adb9f1ad8c85e016bbe714d9b8f2d7d28e610f91))
* **iconbutton:** Fix icon button theme keys/light theme values based on updated tokens. ([42d175e](https://github.com/MaTriXy/material-components-web/commit/42d175efc20e9b36eb86a843b23a60626d36e065))
* **iconbutton:** Set icon button ripple z-index to -1. ([586e740](https://github.com/MaTriXy/material-components-web/commit/586e740ddcaa674c409d68ab5faf9ee8c61e2d91))
* **list:** Remove conflicting validation for checkbox list in setEnabled ([353ca7e](https://github.com/MaTriXy/material-components-web/commit/353ca7e9f21b3589a17d25d8892198cba811dd13))
* **list:** Reset selectedIndex to UNSET_INDEX if #setSingleSelection(true) is called and there are no selected list items. ([4eecdea](https://github.com/MaTriXy/material-components-web/commit/4eecdeaf09ed0429aa685ee35ea2ce7970af89cc))
* **menusurface:** Add a getOwnerDocument() method to MDCMenuSurfaceAdapter to provide a reference to the document that owns the menu surface DOM element. ([3486659](https://github.com/MaTriXy/material-components-web/commit/348665978ce73694ad4518626dd70cdf5b984113))
* Fix missing $ripple-target param for ripple mixin ([1340ee9](https://github.com/MaTriXy/material-components-web/commit/1340ee9f7507e6653537d081c53826b5c25b3e22))
* **menu:** apply elevation overlay to new lists ([0ad12ed](https://github.com/MaTriXy/material-components-web/commit/0ad12ed3cffe78a27c7005e2ed9b83643ebb5114))
* **menu-surface:** slightly delay focus restoration to prevent lost focus on mobile devices ([9f68a93](https://github.com/MaTriXy/material-components-web/commit/9f68a932e9d4168da10d8b9c3bb9191afcc3c68f))
* **sass:** Wrap templated calc expressions in strings ([818f4ee](https://github.com/MaTriXy/material-components-web/commit/818f4ee93de968dfaa9d64929b3edf2d9f8dbe01)), closes [#7391](https://github.com/MaTriXy/material-components-web/issues/7391)
* **slider:** Replace `innerHTML` with `firstChild` ([37d4db8](https://github.com/MaTriXy/material-components-web/commit/37d4db86667c967ba173e318a124b72109cc1bb5))
* Fix compilation issues with TypeScript 4.4 ([7246447](https://github.com/MaTriXy/material-components-web/commit/72464476cea3755fbcbb64df832e9933ea7b1170))
* **button:** remove rem/em transformers from typography theme-styles ([a395972](https://github.com/MaTriXy/material-components-web/commit/a395972cfaf2260da9f50875a8fe772cc3c69d83))
* **chips:** Hide HCM focus indicator for presentational actions ([8c7d994](https://github.com/MaTriXy/material-components-web/commit/8c7d994ae1699fd9e51ea80a073554d12959de3f))
* **list:** Use more descriptive foundation method comments ([08d791f](https://github.com/MaTriXy/material-components-web/commit/08d791f37a159f24686e97df983637947e2a1e87))
* **menu:** correct menu opening delay ([a618380](https://github.com/MaTriXy/material-components-web/commit/a6183801a07f109eff3ee209f42631340fbbe4b3)), closes [#5682](https://github.com/MaTriXy/material-components-web/issues/5682) [#4411](https://github.com/MaTriXy/material-components-web/issues/4411)
* **slider:** Reorder such that dragstart event is emitted before any other events when handling drag start. ([877e3fb](https://github.com/MaTriXy/material-components-web/commit/877e3fb0dbdaf06cf3a9b4fb0fa731df2093901c))
* **switch:** add pointer cursor ([12f5622](https://github.com/MaTriXy/material-components-web/commit/12f5622e14b68c12542cb2bf7236c5a1f5492add))
* **switch:** distribute correct css ([#7292](https://github.com/MaTriXy/material-components-web/issues/7292)) ([7b6bcb8](https://github.com/MaTriXy/material-components-web/commit/7b6bcb85874e81f33956d1ec544aedcdc882ffed))
* **switch:** elevation theme custom properties not working ([2865629](https://github.com/MaTriXy/material-components-web/commit/28656298a9c01bd585fdb995be7aa96d3c3395e7))
* **switch:** misaligned handle when inside some flex containers ([ea1e1b8](https://github.com/MaTriXy/material-components-web/commit/ea1e1b850795bd2b6ab7369a9c1e61d4b0d85f2e))
* **switch:** move ripple behind handle ([3e4c6dc](https://github.com/MaTriXy/material-components-web/commit/3e4c6dca1921caa57e1097c03135a7ddf614f003))
* **switch:** prevent collapsing in flex containers ([22f390c](https://github.com/MaTriXy/material-components-web/commit/22f390c4364f0fc407106933154d68ae9e1ed950))
* **switch:** track colors can have opacity and not bleed through ([d923db7](https://github.com/MaTriXy/material-components-web/commit/d923db73aa8db14c0d573208877d8cb6f4a57002))
* **switch:** use correct colors for icons in all HCM themes ([d86fb6f](https://github.com/MaTriXy/material-components-web/commit/d86fb6facd014e2c0c1a88108ddbb59595dea5ac))
* **text-field:** remove disabled white patch in high contrast mode for Firefox 89+ ([17553e9](https://github.com/MaTriXy/material-components-web/commit/17553e9f806551fba7d7b4d5c3b6de5df96db1af))
* **text-field:** show filled textarea label in Firefox 89+ high contrast ([90e08fc](https://github.com/MaTriXy/material-components-web/commit/90e08fc6b82c805ab74d35b75b2e0c8fc72d6405))
* **textfield:** announce error message again if user blurs already invalid field ([75900a5](https://github.com/MaTriXy/material-components-web/commit/75900a5a916249aa307626f7f6b441086146e1c0))
* **theme:** ensure state selectors negate properly ([7249a30](https://github.com/MaTriXy/material-components-web/commit/7249a3060c6b15eef338b44b77065b47e0b26d52))
* **tooltip:** Add a getActiveElement() method to MDCTooltipAdapter to delegate getting the active element from the correct document. ([e334676](https://github.com/MaTriXy/material-components-web/commit/e3346766f22b23b6c1e04cb2821565d388d57054))
* **tooltip:** Adding missing `return` statement into `MDCTooltipComponent#isShown` method. ([4d95812](https://github.com/MaTriXy/material-components-web/commit/4d95812f95ea60665fdab32a1ef8ff4d4e36a8b0))
* **tooltip:** Adjust tooltip `focusout` handler. Ensures that interactive tooltips remain open when ChromeVox uses linear navigation to read non-focusable content inside the tooltip. ([7c96e6b](https://github.com/MaTriXy/material-components-web/commit/7c96e6b98a25839d249e1d56478e919564b5ff07))
* **tooltip:** non-persistent tooltips disappear on scroll ([1f9259b](https://github.com/MaTriXy/material-components-web/commit/1f9259b9d7821181d8655537cf80e95b9856dd7c))
* update combined mdc package to use new switch CSS ([077dcfc](https://github.com/MaTriXy/material-components-web/commit/077dcfcfe483b8631f51cc16a89557d056b4db58)), closes [#7304](https://github.com/MaTriXy/material-components-web/issues/7304)
* Work around bug in Sass ([037285f](https://github.com/MaTriXy/material-components-web/commit/037285f9bda55dfb2e011f7d58338b29bfa37b6b)), closes [sass/sass#3259](https://github.com/sass/sass/issues/3259)
* **tooltip:** allow the Mac zoom service to access plain tooltip contents ([510cf90](https://github.com/MaTriXy/material-components-web/commit/510cf90f289177cf148b2d72cdb773047410731b))
* **tooltip:** Fixing logic for determining whether or not the user intends a tooltip to be hidden from the screenreader or not. ([cf5b9eb](https://github.com/MaTriXy/material-components-web/commit/cf5b9eb86b764859ed8228377d4dd6dc7d2193c6))
* **tooltip:** Only sends notification of a tooltip being hidden if `showTimeout` is not set (indicating that this tooltip is about to be re-shown). ([6ca8b8f](https://github.com/MaTriXy/material-components-web/commit/6ca8b8f858f0d508a56cf09bcb4b11221f901acb))
* prepare for [#7183](https://github.com/MaTriXy/material-components-web/issues/7183) ([#7188](https://github.com/MaTriXy/material-components-web/issues/7188)) ([77b94e8](https://github.com/MaTriXy/material-components-web/commit/77b94e826c6c8c932bc5974855c645f7316f73af))
* Remove lint check from test actions ([#7185](https://github.com/MaTriXy/material-components-web/issues/7185)) ([1ee1fbf](https://github.com/MaTriXy/material-components-web/commit/1ee1fbf01550f9ea19a72671e6fe360722d66385))
* **banner:** Use role alertdialog. ([a07b6d4](https://github.com/MaTriXy/material-components-web/commit/a07b6d486a7852a2089c9c13d5cf80d4ab65a425))
* **base:** observer now listens to superclass properties ([88a33cd](https://github.com/MaTriXy/material-components-web/commit/88a33cd70c0e87fcfb9e2ff58967f911ad71ace7))
* **button:** add missing feature-targeting import ([71fe9a0](https://github.com/MaTriXy/material-components-web/commit/71fe9a067878c810fe6a7d01b8e839764d7a802c))
* **button:** allow Mac zoom service to access button label ([29ac6ec](https://github.com/MaTriXy/material-components-web/commit/29ac6ec1ef7316ecf03dc93ac0d63a3c09250052))
* **button:** Fix non-text buttons with icons to have reduced horizontal padding on the side with the icon. ([197f64f](https://github.com/MaTriXy/material-components-web/commit/197f64fa2a4b78907261e820c5e1e8724777c92c))
* **button:** Fixed button's icon size scaling on browser zoom ([bc104ba](https://github.com/MaTriXy/material-components-web/commit/bc104bae7c4e1bbcbedb085e6079432f06865cbf))
* **chips:** Add documentation for action ([3db4d16](https://github.com/MaTriXy/material-components-web/commit/3db4d1680bb4135c44042ac77521c8ff18032d14))
* **chips:** Add documentation for chip; update action docs ([22b83ad](https://github.com/MaTriXy/material-components-web/commit/22b83adadc55d1d2ccf150bc4a4dc28432f1f453))
* **chips:** Add stubbed component methods along with tests ([06930c9](https://github.com/MaTriXy/material-components-web/commit/06930c96b8a27ec886fc7873d7c0d0a4bec0761a))
* **chips:** Document chip set; add root readme ([5b6a460](https://github.com/MaTriXy/material-components-web/commit/5b6a460167986caea058dd3f42c11c1edd761596))
* **chips:** Expose deprecated resources in top-level TypeScript file ([67d780c](https://github.com/MaTriXy/material-components-web/commit/67d780c795e2a61772f5d1639c202ced3fbc4dc4))
* **chips:** Fix incorrect references between deprecated and non-deprecated resources ([f8579b7](https://github.com/MaTriXy/material-components-web/commit/f8579b7eaa22bf9da04ea5e4ec27418e001a0813))
* **chips:** Make chips wrap by default ([24255c4](https://github.com/MaTriXy/material-components-web/commit/24255c408518dff48ed59c2529ee3d0496d6b40c))
* **chips:** Remove obsolete chips resources now in chips/deprecated/* ([87ac2fd](https://github.com/MaTriXy/material-components-web/commit/87ac2fd5ca4ec7814216d16a0b0ef6a4474d7e92))
* **chips:** Remove obsolete resources ([40dd242](https://github.com/MaTriXy/material-components-web/commit/40dd242d5ce4586002a8e5cb59ce2711572f1cf3))
* **chips:** rename deprecated trailing action classes ([48f4b67](https://github.com/MaTriXy/material-components-web/commit/48f4b67fbd0d43377670673e56cb5868b3a11e1d))
* **chips:** Un-remove obsolete chips resources now in chips/deprecated/* ([7cf6782](https://github.com/MaTriXy/material-components-web/commit/7cf67823ec45a93f5b458060b2ec632479d813c9))
* **chips:** Update chip set links ([4a7939c](https://github.com/MaTriXy/material-components-web/commit/4a7939c9c3f3ec54bc486ee22567f9ca4e8f18bb))
* **chips:** Use deprecated chips in autoinit ([d2a39d3](https://github.com/MaTriXy/material-components-web/commit/d2a39d300e3b9dee6c0d58d34522075f62b261c3))
* **circular-progress:** add annotation ([06dead2](https://github.com/MaTriXy/material-components-web/commit/06dead2d69d09dfde582d0d9fb1473a61358a5f6))
* **circular-progress:** set explicit line-height to prevent inheritance ([e8e39ad](https://github.com/MaTriXy/material-components-web/commit/e8e39ad19d9fae1ddbf065c9047905753ccd5754)), closes [#7118](https://github.com/MaTriXy/material-components-web/issues/7118)
* **data-table:** fix style ordering wrt select & use new variable-width mixin ([afb6889](https://github.com/MaTriXy/material-components-web/commit/afb68894e63c9ed4bb3b3d523cbb4072480117a6)), closes [#6599](https://github.com/MaTriXy/material-components-web/issues/6599)
* **dialog:** add property to customize suppressDefaultPressSelector ([772cc10](https://github.com/MaTriXy/material-components-web/commit/772cc10686cc8994033a556ab70f4be106e902ee))
* **dialog:** Add transparent border to dialog surface for HCM support. ([b2fa996](https://github.com/MaTriXy/material-components-web/commit/b2fa996a1faa513fae691920cb339091d65b6c9b))
* **dialog:** prevent programmatic click on disabled default button ([e0c3462](https://github.com/MaTriXy/material-components-web/commit/e0c346286a9656819302f04b0cf3f7b948429f74))
* **dialog:** Remove the unnecessary border on the dialog title when not needed, this adds an extra line in the UI on high contrast mode. With margins it is possible to keep the previous spacing and only add the border when needed. ([3344d12](https://github.com/MaTriXy/material-components-web/commit/3344d12ad2eb74cfc4ef270290bcc0322ebe8566))
* **dom:** do not cache focusable elements in focus-trap ([7899e0f](https://github.com/MaTriXy/material-components-web/commit/7899e0fe0a87cb255a5216333054207ef2687933))
* **fab:** add alternate decorator only when necessary ([0fd56a8](https://github.com/MaTriXy/material-components-web/commit/0fd56a86b30846de63d7d1520dcecc4d5ece2347))
* **fab:** Apply extended shape radius in Extended FAB's theme mixin ([81911b7](https://github.com/MaTriXy/material-components-web/commit/81911b7077801590c0f47bf17743f3b2b320b863))
* **fab:** Fixed Fab ripple ([84f3db9](https://github.com/MaTriXy/material-components-web/commit/84f3db9ed03fc414f347bfd88be384fe50646bd8)), closes [#7053](https://github.com/MaTriXy/material-components-web/issues/7053)
* **icon-button:** prevent icon shift on press in IE11 ([8fc2927](https://github.com/MaTriXy/material-components-web/commit/8fc29273c49f5bf5006f4df715bee85fbace9cb8))
* **linear-progress:** allow parent visibility prop to propagate to bar ([e543628](https://github.com/MaTriXy/material-components-web/commit/e543628c3924a47ba63f5b7d58a2a931a260d1d3))
* **linear-progress:** fix RTL rendering ([c7c5da2](https://github.com/MaTriXy/material-components-web/commit/c7c5da28f2cd2c1b54dd201d3797e112288fa86c))
* **list:** Add core-styles mixin. ([fc7c4e5](https://github.com/MaTriXy/material-components-web/commit/fc7c4e5ce2451ecd76f7ea3860b18a16e5f31bac))
* **list:** add support for density scaling. ([419e035](https://github.com/MaTriXy/material-components-web/commit/419e035729c1ca1ee2b572ae4b1937e2d8cf04bc))
* **list:** Correcting the selector mapping for CHILD_ELEMENTS_TO_TOGGLE_TABINDEX and FOCUSABLE_CHILD_ELEMENTS. ([8943b99](https://github.com/MaTriXy/material-components-web/commit/8943b991fd04caab88ae543bad16ba9b47bc7634)), closes [#6829](https://github.com/MaTriXy/material-components-web/issues/6829) [#6829](https://github.com/MaTriXy/material-components-web/issues/6829)
* **list:** density configuration mixins do not account for leading avatars ([3674c62](https://github.com/MaTriXy/material-components-web/commit/3674c6282db170dcf8331f93d779055c3852076b))
* **list:** do not activate typeahead on certain modifier keys ([f1b1fd5](https://github.com/MaTriXy/material-components-web/commit/f1b1fd5d3fa72c0a5dab305e3d7e782ff1421d7e))
* **list:** ensure divider appears in IE high contrast mode. ([eff7b46](https://github.com/MaTriXy/material-components-web/commit/eff7b46ac916d2eb130f7d826eee047c5f19e6f2))
* **list:** Ensure trailing-only variants have leading padding in RTL contexts. ([81e2d4f](https://github.com/MaTriXy/material-components-web/commit/81e2d4ff36518c586972aad4512b43d2bb0cd2d2))
* **list:** Fixed the selected + focused state of list item in HCM ([8ba3e29](https://github.com/MaTriXy/material-components-web/commit/8ba3e298ca18cf8e7e11f07559e27287e74efeb8))
* **list:** Selection lists without a selection focus first item. ([03f525f](https://github.com/MaTriXy/material-components-web/commit/03f525f9ff880f27a43f2e50851a5dc6cd6b022c))
* **mdc-list:** invalid syntax in generated .d.ts bundle ([ce82846](https://github.com/MaTriXy/material-components-web/commit/ce828464cdab59cac79add950fcac4f0310ce624))
* **menu:** Remove anchorSize height from calculations when anchored to bottom ([1631198](https://github.com/MaTriXy/material-components-web/commit/16311983787cf46ccd22eaa4d6a076254cb32eea))
* **notched-outline:** fix notched outline no-label style ([99cfb6b](https://github.com/MaTriXy/material-components-web/commit/99cfb6bd53f72240fe76852d0fdaa0b82e7dca39))
* **progress-indicators:** hide from screenreaders on close ([d3a6862](https://github.com/MaTriXy/material-components-web/commit/d3a6862af3ff4f0e157ebe95bd5f54a47fc14c48))
* **ripple:** ensure custom properties are always emitted ([caa73ae](https://github.com/MaTriXy/material-components-web/commit/caa73aeeea780ff65d4434fe1f38cec9396209c4))
* **ripple:** Update states-selector() to use `:active:active` to match active specificity styles. ([faa7d32](https://github.com/MaTriXy/material-components-web/commit/faa7d3226edbb15bdfca69e5ae98b2d7afdd861a))
* **rtl:** do not emit if a left/right value or replacement is null ([ec4ac52](https://github.com/MaTriXy/material-components-web/commit/ec4ac5234c31df882a85a90af4d53b6797c8eb49))
* **rtl:** mixins work with pseudo elements ([f5b6110](https://github.com/MaTriXy/material-components-web/commit/f5b6110d6a3c5ef1253165f5575ed3980748e19c))
* **select:** debounce click on anchor ([b39094d](https://github.com/MaTriXy/material-components-web/commit/b39094d145f9b96c1c75e2b5fcce7b76c9b31bf1))
* **select:** do not conduct anchor typeahead when modifier keys pressed ([6f678a9](https://github.com/MaTriXy/material-components-web/commit/6f678a91a400ac3408e06523d18a134cf3513f6b))
* **select:** set aria-expanded false earlier when menu closes ([df00c2b](https://github.com/MaTriXy/material-components-web/commit/df00c2b30342877eba7d1e21e8a57141739155a5))
* **select:** set hidden input value before firing change event ([2d6ba2c](https://github.com/MaTriXy/material-components-web/commit/2d6ba2c239dfc7d4c2516507b11a32537c163852)), closes [#6904](https://github.com/MaTriXy/material-components-web/issues/6904)
* **shape:** duplication bug with nested custom properties ([f77a4dd](https://github.com/MaTriXy/material-components-web/commit/f77a4dd1a3eb4f6af2b5a7695081408de41211b7))
* **slider:** Add aria-hidden to value indicator container, to avoid duplicate value announcements for screenreader users. ([9687353](https://github.com/MaTriXy/material-components-web/commit/96873535640a2e9141ff8e17e64fcb5e28d90f53))
* **slider:** Adjust hidden input dimensions to take slider dimensions, such that screenreader focus indicators show a highlight around the entire slider. ([fd22355](https://github.com/MaTriXy/material-components-web/commit/fd22355f72ab304aec043f53ced92fa9adfef457))
* **slider:** Fire custom `input` event on input change (i.e. value change via keyboard), mirroring the native `input` event behavior for range inputs. ([ec8f846](https://github.com/MaTriXy/material-components-web/commit/ec8f8465f40bd13f61e2ad26c52314fc27fd5420))
* **slider:** Fire custom change event on input change. ([07deaec](https://github.com/MaTriXy/material-components-web/commit/07deaec27a6f92b9a00c7698c49d3e1a93e504ea))
* **slider:** Fix #quantize to use min value as the baseline. ([0f358dd](https://github.com/MaTriXy/material-components-web/commit/0f358ddae37a8703b8b6f0b8e4de846a196d443a))
* **slider:** Fix bug where value indicator container took space and could be hovered over / clicked when hidden. ([832668d](https://github.com/MaTriXy/material-components-web/commit/832668d33389a0b6194d3d8ef53aa8c252aa8f5d))
* **slider:** Fix JS floating point rounding errors by rounding values to a set number of decimal places based on the step size. ([6072ed6](https://github.com/MaTriXy/material-components-web/commit/6072ed6040e1f65e099b876a4065fbb07378c186))
* **slider:** Fix track height. ([67eb0df](https://github.com/MaTriXy/material-components-web/commit/67eb0df80920a53e04fc151b3ab065959e3e84dc))
* **slider:** Improve HCM borders, add missing [@noflip](https://github.com/noflip) annotations. ([e7202cb](https://github.com/MaTriXy/material-components-web/commit/e7202cb576ff762664a3636ec01cebfa5a61be49))
* **slider:** Mark ripple event handler as passive. Fixes [#6746](https://github.com/MaTriXy/material-components-web/issues/6746) ([abdd100](https://github.com/MaTriXy/material-components-web/commit/abdd10065367738148866c165b339a3e3b9b1fc3))
* **slider:** Modify behavior such that for range sliders, presses in the middle of the range change the value (of the closest thumb). This provides a single-pointer alternative option to an otherwise gesture-based interaction. ([0b8cff7](https://github.com/MaTriXy/material-components-web/commit/0b8cff73421489a5322dd39b8504c16ba0f26120))
* **slider:** Remove big step options. Now that we're using a native range input, big step is not customizable - we follow browser defaults for big step. ([ae27b44](https://github.com/MaTriXy/material-components-web/commit/ae27b44b078ebdad3669b03abc9f28ed184db803))
* **slider:** Throttle slider UI updates. ([7d6a4bb](https://github.com/MaTriXy/material-components-web/commit/7d6a4bb72f210c94161568f964e33cd8b06a8315))
* **slider:** Throw error for invalid initial values based on the step. ([3955d8d](https://github.com/MaTriXy/material-components-web/commit/3955d8d3d2ba2766b59338f0ed7ae640388ce926))
* **slider:** Update both thumbs' value indicator UI's if layout is invoked with undefined `thumb`. ([489d4c2](https://github.com/MaTriXy/material-components-web/commit/489d4c219d1747a8e5de3f210f00898c18201b24))
* **slider:** Use `pointer-events: none` instead of `visibility: hidden` to hide the value indicator container. Adding `visibility: hidden` removes the exit animation since the value indicator is immediately hidden. ([a94bd8d](https://github.com/MaTriXy/material-components-web/commit/a94bd8deb879b0321e8227d26f338789ef3ffb90))
* **slider:** Use mouse/touch events on iOS, to work around pointer events bug. ([671d72d](https://github.com/MaTriXy/material-components-web/commit/671d72d9544d3d1630966ec4e78b5705700defe7)), closes [#6715](https://github.com/MaTriXy/material-components-web/issues/6715)
* **switch:** export temporary deprecated version ([bd68539](https://github.com/MaTriXy/material-components-web/commit/bd685395b652f448e889c123cda97efd77c85fcd))
* **switch:** overlay colors not showing and support -5 density ([33579e0](https://github.com/MaTriXy/material-components-web/commit/33579e00bea179170016031fc3f24b70f57d74d2))
* **tab:** Update ripple adapter to reflect sass ripple-target. ([97c4d40](https://github.com/MaTriXy/material-components-web/commit/97c4d40356fcc89d9eb854ecf322ec7474aa597c))
* **tabs:** Expose min width mixin and set to 90px per spec. ([c4ab987](https://github.com/MaTriXy/material-components-web/commit/c4ab987221d5a3b9ab588321bb0347f5d665505a))
* **tabscroller:** remove trailing underscore ([105b15b](https://github.com/MaTriXy/material-components-web/commit/105b15b965e41bfaafedfb43e278cd5cb9d22195))
* **theme:** do not emit when theme.property() replacements are null ([aa0aaf0](https://github.com/MaTriXy/material-components-web/commit/aa0aaf026aae13532b3e3790992e9cc06397aa91))
* **theme:** ensure either() works with false values ([8e66dbf](https://github.com/MaTriXy/material-components-web/commit/8e66dbfeebe3d5fec438c69093d7f9941c0fbf10))
* **theme:** parsing error when [@import-ing](https://github.com/import-ing) mdc-theme ([b62b126](https://github.com/MaTriXy/material-components-web/commit/b62b1266d66734fcd9d60c7893ea048f83883f8f))
* **theme:** replace works for multiple replacements ([95322b1](https://github.com/MaTriXy/material-components-web/commit/95322b11e3b0c938d9b4de56a1ba80d1ff42596b))
* **tooltip:** Adds "will-change" into CSS to prevent the tooltip from "jittering" when animating in. ([7a003ac](https://github.com/MaTriXy/material-components-web/commit/7a003acf09345920d917cb4ab7c298a66e4fe184))
* **tooltip:** Change foundation to check for "dialog" on the anchor element's aria-haspopup attribute instead of checking for "true". ([b8a1a58](https://github.com/MaTriXy/material-components-web/commit/b8a1a58e4ebb49a73725d2e7ae8aef09c07db09d))
* **tooltip:** Clear hideTimeout in handleAnchorMouseEnter so that the tooltip will not be hidden if the user rapidly moves the mouse in and out of the anchor element. ([365c693](https://github.com/MaTriXy/material-components-web/commit/365c69360230540a67dd141f6bec999b2541a7e8))
* **tooltip:** Fix rich tooltip tests to not use aria-describedby to associate rich tooltips with their anchor elements. This is because interactive rich tooltips should not be used with aria-describedby per a11y guidance. ([251ac04](https://github.com/MaTriXy/material-components-web/commit/251ac04c0a976d48a6be33cc7fcd76f6e2700aac))
* **tooltip:** Fixing component definition of MDCTooltipAdatper#deregisterAnchorEventHandler. ([d928692](https://github.com/MaTriXy/material-components-web/commit/d928692b52157c91c46c9addf66f93ebdff09145))
* **tooltip:** flip precedence of data-tooltip-id and aria-describedby when finding TT id ([b2d22df](https://github.com/MaTriXy/material-components-web/commit/b2d22df5b62003247fa5ca60a23b2ce8b6a17b33))
* **touch-target:** incorrect position in rtl when width is set ([bd1b4e9](https://github.com/MaTriXy/material-components-web/commit/bd1b4e9d857f0b8fb7b5b9de9b8d5d78823f386d))
* **typography:** do not emit styles when setting null from global variable ([f5f1b61](https://github.com/MaTriXy/material-components-web/commit/f5f1b613ce5c0dda39f617adbcfd2bb3f1862a74))
* Adding tests. ([240c5f7](https://github.com/MaTriXy/material-components-web/commit/240c5f74f381967ede9eb1fa13754d2f0282da9e))
* adjust meta baseline and update color mixins. ([07f3e01](https://github.com/MaTriXy/material-components-web/commit/07f3e01b75306a7481c7077cd3ed12a87399958e))
* Document stylelint exceptions ([f89d8b8](https://github.com/MaTriXy/material-components-web/commit/f89d8b8f295c80c7b7e691ec712a30de8a0b26d5))
* **banner:** Update image to graphic and support material icons ([346069c](https://github.com/MaTriXy/material-components-web/commit/346069ccb2a831b37df62bf71135acad92fd69c3))
* **base:** Add EDITING and EDITABLE states to the chip. ([cf3b664](https://github.com/MaTriXy/material-components-web/commit/cf3b664ab1f12b17ea827ad1e2870977b9836e5b))
* **base:** Causes internal text in a chip to not overflow and instead be truncated by ellipsis. ([b83d720](https://github.com/MaTriXy/material-components-web/commit/b83d720ee41acb13e3e6ca69431f718c7887c1de))
* **base:** Make the root property public ([51d4535](https://github.com/MaTriXy/material-components-web/commit/51d4535fe39a2448fbba1ec995bb9980357545fa))
* **base:** Remove "foundation_" from MDCComponent ([8c6d7e0](https://github.com/MaTriXy/material-components-web/commit/8c6d7e0766d8958a8d4ffea35acee9d6841dafd4))
* **base:** Remove trailing underscore "adapter_" ([5b5f62f](https://github.com/MaTriXy/material-components-web/commit/5b5f62f9397100a9dd97c257b930e686837c4ceb))
* **button:** Move theme-baseline() into base Sass. ([080965f](https://github.com/MaTriXy/material-components-web/commit/080965f3952b32105419558c0167873554234dd0))
* **card:** ensure border-adjacent content renders correctly. ([790ca85](https://github.com/MaTriXy/material-components-web/commit/790ca85fd643229e95f2d1c08811c8e0e5513805))
* **chip-set:** crash when only item is removed ([a653b68](https://github.com/MaTriXy/material-components-web/commit/a653b68118e823ae30b1f47f87a4a8e5e69d9186))
* **circular-progress:** Default all variables ([430fd02](https://github.com/MaTriXy/material-components-web/commit/430fd025b07b3e15dd699620fbbfca75f74632a3))
* **circular-progress:** display properly inside button ([000d648](https://github.com/MaTriXy/material-components-web/commit/000d6481570c361cf4c66b55c287eea434b6d11e)), closes [#6388](https://github.com/MaTriXy/material-components-web/issues/6388)
* **circular-progress:** display properly inside button ([2bd09a7](https://github.com/MaTriXy/material-components-web/commit/2bd09a706efb991fd71e171db8994f0282a1f02e))
* **circular-progress:** use theme.property() for color mixins ([7bd5075](https://github.com/MaTriXy/material-components-web/commit/7bd5075de978f8499f4cdc3b8359005184fa5192))
* **data-table:** Add noflip annotation to header cell text align ([843f636](https://github.com/MaTriXy/material-components-web/commit/843f636c047b5371cd31b9ae4af76a7ec494b446))
* **data-table:** Check if data table has checkboxes on destroy ([164c073](https://github.com/MaTriXy/material-components-web/commit/164c07365ef405a14e4375db71fbc55931aa9262))
* **data-table:** Fix icon misalignment in sort icon button when sorted down ([610c26c](https://github.com/MaTriXy/material-components-web/commit/610c26c4a1c7928fec0e8d63be3bd76cb7ff76a0))
* **data-table:** Fix JS error in IE11 when setting multiple styles ([d548d7a](https://github.com/MaTriXy/material-components-web/commit/d548d7a923393f4be11a7919542fa07f5a224d29))
* **data-table:** Fix row checkbox cell's leading padding to match spec ([38ef450](https://github.com/MaTriXy/material-components-web/commit/38ef4501f630351b32efd31ea2b870e0ed1b1b1d))
* **data-table:** Make row checkbox table cell fixed even when table is wide ([a6ac8f6](https://github.com/MaTriXy/material-components-web/commit/a6ac8f629b45e46d598b4b531fed8300fb5a8eef))
* **data-table:** not inverting text alignment in rtl ([bd8d1aa](https://github.com/MaTriXy/material-components-web/commit/bd8d1aafab5c6da614135702f5814447de5ea448))
* **data-table:** partial rollback of [#6390](https://github.com/MaTriXy/material-components-web/issues/6390) ([da72839](https://github.com/MaTriXy/material-components-web/commit/da72839f40a432c529bb24e5bc4514842627d3bf))
* **data-table:** Set progress indicator height to table body offset height ([c678a9d](https://github.com/MaTriXy/material-components-web/commit/c678a9d34a3f694511f292c7a62e68749721b63c))
* **datatable:** Fix updating the header checkbox when there are no rows in a datatable ([2ccf996](https://github.com/MaTriXy/material-components-web/commit/2ccf996cc417b888d7ac4ceebdfa4160464a0bb1))
* **dialog:** Change scale(1) to `transform:none` ([9ea5207](https://github.com/MaTriXy/material-components-web/commit/9ea52070f4f9693266a20311cce15700e84696c3))
* **dialog:** Use superclass properties without trailing underscores ([b4e2fe9](https://github.com/MaTriXy/material-components-web/commit/b4e2fe9f4bf690968d0ac47da0ca4a64ee8d7a88))
* **dom:** Make dom selectors in dom/announce tests scoped ([fc65fd0](https://github.com/MaTriXy/material-components-web/commit/fc65fd00b91d388d0ad15e50a13567a8e1d425c0))
* **elevation:** Use relative path when importing theme Sass file. ([405a29a](https://github.com/MaTriXy/material-components-web/commit/405a29a2016565f8cb269915c5f6c0d4df133c6d))
* **linear-progress:** disable animations when closed ([a831d47](https://github.com/MaTriXy/material-components-web/commit/a831d4799b281729a932f0690b62b6bce1874799))
* **linear-progress:** performance for indeterminate animations in modern browsers ([fc0eb50](https://github.com/MaTriXy/material-components-web/commit/fc0eb5013603a4d5cb4dbc0a999e94df64cc5005))
* **linear-progress:** Use superclass properties without trailing underscores ([8e17857](https://github.com/MaTriXy/material-components-web/commit/8e17857d0a8d301f54fac64cc83804928ec1ff83))
* **list:** add support for non-interactive list roles. ([fc8b045](https://github.com/MaTriXy/material-components-web/commit/fc8b045f1127709c5929a3cd1c9c7d622db8ed42))
* **list:** Preserve aspect ratio of the original image when using it as the icon or avatar for a list. ([be4a19f](https://github.com/MaTriXy/material-components-web/commit/be4a19f9f0668e4fc303d2e60e81473ac11d68be))
* **mdc-dialog:** second dialog `data-mdc-dialog-initial-focus` doesn't work ([a0ec7e2](https://github.com/MaTriXy/material-components-web/commit/a0ec7e25d0ba26c2e85d5576e6af5e5d65b301a3))
* **menu:** Do not set selectedIndex for menu items that have a negative recomputedIndex. ([ef3a095](https://github.com/MaTriXy/material-components-web/commit/ef3a095336a205fa9473a8c6e4940c3f9cccf5ea))
* **menu:** Use superclass properties without trailing underscores ([0008c8a](https://github.com/MaTriXy/material-components-web/commit/0008c8a91a4da2c0c95fe092395cc575cbf23769))
* **menu-surface:** Use superclass properties without trailing underscores ([62abbc8](https://github.com/MaTriXy/material-components-web/commit/62abbc8d762c6c903d4a13817a0b71555764e0df))
* **menusurface:** Fixing bug where body click listener is not being properly deregistered. ([5511c52](https://github.com/MaTriXy/material-components-web/commit/5511c5254476c817b51bb2ae884f56d328348bd0)), closes [#6557](https://github.com/MaTriXy/material-components-web/issues/6557)
* **notched-outline:** Use superclass properties without trailing underscores ([49bf31d](https://github.com/MaTriXy/material-components-web/commit/49bf31d5c9c3ee34e9a51ce3b254a9101c578045))
* **radio:** disabled state in IE high contrast mode ([774dcfc](https://github.com/MaTriXy/material-components-web/commit/774dcfc8eb31e766afd0194c54edfe71a7ff7c3e))
* **radio:** Use superclass properties without trailing underscores ([541638f](https://github.com/MaTriXy/material-components-web/commit/541638fa2ba3410ca1055c5ae563face06fd20be))
* **ripple:** Use superclass properties without trailing underscores ([6167cd0](https://github.com/MaTriXy/material-components-web/commit/6167cd0756a623502f7f84750dcda25226a59794))
* **segmented-button:** Fixed unit test in IE11 ([#6271](https://github.com/MaTriXy/material-components-web/issues/6271)) ([b96fbfc](https://github.com/MaTriXy/material-components-web/commit/b96fbfc7a9b75d7d58ecc53919c26b1cdd05d9ed))
* **segmented-button:** Move include statements to avoid nested classes ([#6380](https://github.com/MaTriXy/material-components-web/issues/6380)) ([bcc5829](https://github.com/MaTriXy/material-components-web/commit/bcc58290a7ac7bbbe191d00be003785017f94d29))
* **segmented-button:** Use empty clientRect in default adapter ([#6343](https://github.com/MaTriXy/material-components-web/issues/6343)) ([9f9aac8](https://github.com/MaTriXy/material-components-web/commit/9f9aac82595ec6eb117e101dc5e0ee0a22e81eee))
* **select:** Also set font size for icon ([c113fc9](https://github.com/MaTriXy/material-components-web/commit/c113fc942a88e2c53b2c36229b2ddff84e6d0eb5))
* **select:** clean up helper text interactions ([654934d](https://github.com/MaTriXy/material-components-web/commit/654934dfaff71dae2b56bd2d4bb04303f5439c3e))
* **select:** Close menu on anchor click when menu is open ([8fa22aa](https://github.com/MaTriXy/material-components-web/commit/8fa22aaccafa3b1ae09164b228d8e1b203337221))
* **select:** do not emit change event when same value selected twice ([e07a708](https://github.com/MaTriXy/material-components-web/commit/e07a7084134b6bbfb1d31a00e410b9d133f28863))
* **select:** ensure enough space for label when outlined menu opening above ([66b8ed7](https://github.com/MaTriXy/material-components-web/commit/66b8ed7e62881b1b22b3b5a32730eac43d563cb7))
* **select:** fix screenreader click interactions ([8904f3c](https://github.com/MaTriXy/material-components-web/commit/8904f3cbe922c5b64f5b7297f23c49861ee13f07))
* **select:** float label on hidden-input initial value ([744bfe5](https://github.com/MaTriXy/material-components-web/commit/744bfe5d8438b49d995ac5e2760d776a1df9838a))
* **select:** fully separate density mixins for filled variants ([d66d22b](https://github.com/MaTriXy/material-components-web/commit/d66d22bf9b9f221ff8b2d713b1e2fc9288f490df))
* **select:** Make compatible with rich list-items ([0a7895f](https://github.com/MaTriXy/material-components-web/commit/0a7895f4d4c22296ad23b2d8a7e1a4dbe231b941))
* **select:** move label before selected text for screenreader a11y ([e139d62](https://github.com/MaTriXy/material-components-web/commit/e139d626eefc941415b876597787753520a45ab1))
* **select:** prevent dropdown icon focus on IE ([b9dff0a](https://github.com/MaTriXy/material-components-web/commit/b9dff0a19ee53e492ef9b06538dfe863214b5fc2)), closes [#6323](https://github.com/MaTriXy/material-components-web/issues/6323)
* **select:** prevent helper text from announcing when hidden ([e056052](https://github.com/MaTriXy/material-components-web/commit/e0560522fc2e390ee25a1968fdde3fde0cab6041))
* **select:** remove gap when outlined opened above with no label ([2fe7012](https://github.com/MaTriXy/material-components-web/commit/2fe70126ae51043d1e733e6d4ec11452e7ed9bc4))
* **select:** remove min-width & dynamic width resizing ([d4cd83a](https://github.com/MaTriXy/material-components-web/commit/d4cd83a857fdf072f547dc597db1f8b30d33a102))
* **select:** remove unnecessary bottom line focus selector ([32fb314](https://github.com/MaTriXy/material-components-web/commit/32fb314cd0cc74f37f0d567a739c115daa96be95))
* **select:** revert 2fed2c1 that delegates to list for single selection logic ([38197b4](https://github.com/MaTriXy/material-components-web/commit/38197b4434959cc8b47124233003c14d9c4a0fbf))
* **select:** Use key constants from DOM package ([388b042](https://github.com/MaTriXy/material-components-web/commit/388b042c7193f78874a8854664742fc7285f1386))
* **select:** Use superclass properties without trailing underscores ([c472bbb](https://github.com/MaTriXy/material-components-web/commit/c472bbbd1aa5e362c227a1c5204601362444d22f))
* **shape:** remove deprecated functions ([e2ea4a9](https://github.com/MaTriXy/material-components-web/commit/e2ea4a99e1930ac4981f22a2b919bdbd31e75a95))
* **slider:** Fix bugs with setting slider position before component initialization: ([9110147](https://github.com/MaTriXy/material-components-web/commit/9110147118180dc1de5c7d727fb3ecbe2507882f))
* **slider:** Move inactive track before active track, so active track consistently overlaps inactive track. ([0b7ac96](https://github.com/MaTriXy/material-components-web/commit/0b7ac9609470218d4ed6229c7a624ed5f3984aa8))
* **slider:** Remove `width: 100%` to account for margin around slider track. ([16c563e](https://github.com/MaTriXy/material-components-web/commit/16c563ef71555da9f02707b9f00abb4c5fc3df79))
* **snackbar:** remove use of [@at-root](https://github.com/at-root) ([98d0296](https://github.com/MaTriXy/material-components-web/commit/98d02962b5f1edd9f541f19198dc3d1992720ea3))
* **snackbar:** Update a11y structure to announce label and actions ([40d8e47](https://github.com/MaTriXy/material-components-web/commit/40d8e472600544fcfe8b8b9d91c62cc014995296))
* **snackbar:** Update a11y structure to announce snackbar correctly ([a3176c8](https://github.com/MaTriXy/material-components-web/commit/a3176c8eaada1b6c61f0d678a193a26a25a773c5))
* **snackbar:** Use superclass properties without trailing underscores ([39b0b8e](https://github.com/MaTriXy/material-components-web/commit/39b0b8e06ef68d5b59515454907b5472ce75b842))
* **snackbar:** Use superclass properties without trailing underscores ([5ea0f3f](https://github.com/MaTriXy/material-components-web/commit/5ea0f3fc47e8bd18fcc8fd3af84fcecc17b3f800))
* **switch:** Adjust track width to 36px, align thumb and track. ([d716225](https://github.com/MaTriXy/material-components-web/commit/d71622574c25840013a517749df357f7f93bc4d6))
* **tab:** Use superclass properties without trailing underscores ([a4b2e61](https://github.com/MaTriXy/material-components-web/commit/a4b2e61d47b515a0ebbdee788e8462d800bea7f3))
* **tab-bar:** Use superclass properties without trailing underscores ([f2de07c](https://github.com/MaTriXy/material-components-web/commit/f2de07c606c8d57942d5f0022e90eecb41b3ad61))
* **tab-indicator:** Use superclass properties without trailing underscores ([d30a214](https://github.com/MaTriXy/material-components-web/commit/d30a214ace1c0ae41fd5d7f8ba4915035fd9235a))
* **tab-scroller:** Use superclass properties without trailing underscores ([96dba1d](https://github.com/MaTriXy/material-components-web/commit/96dba1d3127c9364cff5786a01be8c17f69ab0ee))
* **text-field:** Use superclass properties without trailing underscores ([e6165eb](https://github.com/MaTriXy/material-components-web/commit/e6165eb156d60f8f650c68931854136a1a44fc6e))
* **textfield:** affix outlined alignment Safari bug ([ad4df58](https://github.com/MaTriXy/material-components-web/commit/ad4df58c1e9ba7a893780dc5fe7886179a0361f9))
* **textfield:** autofill filled label not floating correctly ([abcdbcf](https://github.com/MaTriXy/material-components-web/commit/abcdbcfebdcb8a8abe386abb00cd33230e8ef7a1))
* **textfield:** error when notching outline with no label ([b0ed593](https://github.com/MaTriXy/material-components-web/commit/b0ed593ccbffe7dfec51c94527cbc17000385407)), closes [#6452](https://github.com/MaTriXy/material-components-web/issues/6452)
* **textfield:** helper text a11y interactions ([8a39352](https://github.com/MaTriXy/material-components-web/commit/8a39352c8a787663eecb42b46939b069729fc82c))
* update circular-progress import paths ([10e8c19](https://github.com/MaTriXy/material-components-web/commit/10e8c191a0c4c9eb1703f25b66668c640f5344a6))
* **textfield:** remove fullwidth variant ([69a35e8](https://github.com/MaTriXy/material-components-web/commit/69a35e80ceadb5ef9ffae87345eefbd80b383f51))
* **theme:** add validation to host-aware to ensure proper usage ([defa599](https://github.com/MaTriXy/material-components-web/commit/defa599a8bc17557602bbf35a8a5c760fbb053f1))
* **theme:** property() mixin not working with theme key strings ([c1fec42](https://github.com/MaTriXy/material-components-web/commit/c1fec424677fcb77dfc966ff1805d601a103fa30)), closes [#6158](https://github.com/MaTriXy/material-components-web/issues/6158)
* **theme:** Remove duplicate [@forward](https://github.com/forward) in theme index module ([b2e80a5](https://github.com/MaTriXy/material-components-web/commit/b2e80a5d91fc8552f22614e95f7670225f6b4248))
* mark all packages as side-effect-free ([be7cb05](https://github.com/MaTriXy/material-components-web/commit/be7cb05996a7281d1e0c12c0f4677e4d091a2329))
* update README to correct links. ([71e615b](https://github.com/MaTriXy/material-components-web/commit/71e615bc8fa757d22190641db0c2940e24bdf59b))
* update types and deprecate old ponyfill ([af332d5](https://github.com/MaTriXy/material-components-web/commit/af332d5bef3f826fa7a6078492d54f0444a3fee4))
* **auto-init:** Fixed issue with multiple default exports ([#5464](https://github.com/MaTriXy/material-components-web/issues/5464)) ([8ddd5c6](https://github.com/MaTriXy/material-components-web/commit/8ddd5c6dcbfa6d81a063b37aee4021ebf34d18f0))
* **base:** Remove trailing underscore from superclass properties ([62b5f37](https://github.com/MaTriXy/material-components-web/commit/62b5f37db092df4441abdf5e4ee0b32dceee8c7c))
* **button:** Correct misspelling of overflow ([99d2fc9](https://github.com/MaTriXy/material-components-web/commit/99d2fc961be8cd7e8316b40dcf9754a536d29991))
* **button:** Correct misspelling of overflow ([28d32f8](https://github.com/MaTriXy/material-components-web/commit/28d32f8e0d923099221fe7d3853177243e0fd243))
* **button:** Correct misspelling of overflow ([29debfe](https://github.com/MaTriXy/material-components-web/commit/29debfea704941e80f1d337880b4a18142c11561))
* **button:** Remove misspelled label-overlow-ellipsis ([e59906a](https://github.com/MaTriXy/material-components-web/commit/e59906a57e91604f918c8ccd350f93a9a802e412))
* **checkbox:** change checkbox event type from change to click and add some logic for IE browser ([#5316](https://github.com/MaTriXy/material-components-web/issues/5316)) ([2e491de](https://github.com/MaTriXy/material-components-web/commit/2e491de555d54f8d41474ccda156e5f9d0666bc4)), closes [#4893](https://github.com/MaTriXy/material-components-web/issues/4893)
* **checkbox:** Replace unique-id with custom color hash functio… ([#5404](https://github.com/MaTriXy/material-components-web/issues/5404)) ([7be9e4a](https://github.com/MaTriXy/material-components-web/commit/7be9e4a04387b9ca5f8afae6e4edcb3b37e6a86b))
* **checkbox:** Use secondary and on-secondary as default colors ([b95172e](https://github.com/MaTriXy/material-components-web/commit/b95172e69613c0defe82191b86ed1c1999b74400)), closes [#5730](https://github.com/MaTriXy/material-components-web/issues/5730)
* **checkbox:** Use superclass properties without trailing underscores ([2e218db](https://github.com/MaTriXy/material-components-web/commit/2e218dbf8810548de27b683ed6e25d5fb1cbbc23))
* **chips:** .d.ts file generated with syntax error ([d154836](https://github.com/MaTriXy/material-components-web/commit/d1548369f2311e164b0920ed651ba211d05543fa))
* **chips:** .d.ts file generated with syntax error ([#5577](https://github.com/MaTriXy/material-components-web/issues/5577)) ([98f7faa](https://github.com/MaTriXy/material-components-web/commit/98f7faa05fa7c88e0231a00942f4ff9dedf4e8c0))
* **chips:** Fix browser back nav in FF when removing chip with… ([#5537](https://github.com/MaTriXy/material-components-web/issues/5537)) ([a1a0deb](https://github.com/MaTriXy/material-components-web/commit/a1a0deb3ea47d5d89efdcab062e438218148b975))
* **chips:** Handle IE/Edge specific key names in keyboard navigation logic ([3657f88](https://github.com/MaTriXy/material-components-web/commit/3657f886327182c26f1d1555b2ac67c2128140b5))
* **chips:** Move touch target inside primary action ([ad3bbf7](https://github.com/MaTriXy/material-components-web/commit/ad3bbf7822d1fe26694b798299c48e8896971e25))
* **chips:** Use superclass properties without trailing underscores ([cf7747e](https://github.com/MaTriXy/material-components-web/commit/cf7747ef72efb4affe2dd920a6641f730f3bcfcd))
* **circular-progress:** Add .npmignore file to ignore typescript files when publishing ([#5801](https://github.com/MaTriXy/material-components-web/issues/5801)) ([f172b0f](https://github.com/MaTriXy/material-components-web/commit/f172b0f90a91d8d3d700763d1496bb7b9c1a8d51)), closes [#5800](https://github.com/MaTriXy/material-components-web/issues/5800)
* **circular-progress:** fix determinate transition typo & 4 color keyframes ([a301636](https://github.com/MaTriXy/material-components-web/commit/a3016368df53b1c7967d7d146a9ea53a24442fa9))
* **circular-progress:** Fix naming in package.json and add to jsBundleFactory ([86f7cad](https://github.com/MaTriXy/material-components-web/commit/86f7cad8330dbd600e478610eefd8dd92eb3d8c7))
* **circular-progress:** Force LTR layout ([6a40ef2](https://github.com/MaTriXy/material-components-web/commit/6a40ef217f597138ee2920d2160364649dbf5620))
* **circular-progress:** Switch mixins import to `[@use](https://github.com/use)` ([098ae32](https://github.com/MaTriXy/material-components-web/commit/098ae3285223af2532659dec233537a55c1183f5))
* **circularprogress:** Use superclass properties without trailing underscores ([da05f66](https://github.com/MaTriXy/material-components-web/commit/da05f66e10f8efe5c425cec7f140ed399b11bd3f))
* **data-table:** change svg attribute name viewbox to viewBox ([#5483](https://github.com/MaTriXy/material-components-web/issues/5483)) ([#5493](https://github.com/MaTriXy/material-components-web/issues/5493)) ([f3adce8](https://github.com/MaTriXy/material-components-web/commit/f3adce86f43c15d3e2311363bf317ff68a3bb99d))
* **data-table:** Fix pagination box height ([eb28b6e](https://github.com/MaTriXy/material-components-web/commit/eb28b6ecc65a9979ef0959eac5dbfde5b4d3b2dc))
* **data-table:** Fixed alignment of numeric header cell with sort button. ([2139200](https://github.com/MaTriXy/material-components-web/commit/2139200b3ed2b57d74a02701bfef23a983d19cdf))
* **data-table:** Fixed default feature targeting query params of sort mixins ([e33c49e](https://github.com/MaTriXy/material-components-web/commit/e33c49eaf9c0dbc601f3610af6358cbf2833229c))
* **data-table:** Fixed horizontal scrolling issue with pagination controls ([b065a4d](https://github.com/MaTriXy/material-components-web/commit/b065a4d2bd351b86277f5a2f4d512fb6c243c7ce))
* **data-table:** Hover styles for sortable header cell ([d580805](https://github.com/MaTriXy/material-components-web/commit/d5808057fcdf00364731e0896ef7031ac605cf55))
* **data-table:** Removed overflow-x from root element ([4ebce8d](https://github.com/MaTriXy/material-components-web/commit/4ebce8d787db92afb4c1f9d2a10268a62d188d43))
* **data-table:** Reverse the arrow direction icon for column sorting ([a7c827f](https://github.com/MaTriXy/material-components-web/commit/a7c827f17ce9be631484676ccb6b5f18604803ae))
* **data-table:** unable to redefine colors in class-based themi… ([#5751](https://github.com/MaTriXy/material-components-web/issues/5751)) ([4d48051](https://github.com/MaTriXy/material-components-web/commit/4d48051c1099f48e867cf08f070138a7abc719fc))
* **data-table:** unable to redefine colors in class-based theming ([4b45b66](https://github.com/MaTriXy/material-components-web/commit/4b45b662057edd8819f1a515db88e1c12254cc30))
* **datatable:** Use superclass properties without trailing underscores ([862d0d7](https://github.com/MaTriXy/material-components-web/commit/862d0d7bce4fc30a1947d1ff7cb7286c106dd9e5))
* **dialog:** Only equalize paddings for scrollable dialogs with titles, since there is no added divider between title/content in this case. ([8135cc0](https://github.com/MaTriXy/material-components-web/commit/8135cc085a5cd548cf8c8fba4bb43a21bcd3fd46))
* **dom:** Clear out announcer regions on document click ([c67667e](https://github.com/MaTriXy/material-components-web/commit/c67667e8e213ed4686889cb3962685444bd885c6))
* **drawer:** Use superclass properties without trailing underscores ([a66493c](https://github.com/MaTriXy/material-components-web/commit/a66493cd8e9717ce32218fb877ca2258ea6ee880))
* **floating-label:** Use superclass properties without trailing underscores ([5cea261](https://github.com/MaTriXy/material-components-web/commit/5cea2610f2f46bbe193683668044116d78b7e2d6))
* **floatinglabel:** Estimate hidden scroll width ([#5448](https://github.com/MaTriXy/material-components-web/issues/5448)) ([981ec9b](https://github.com/MaTriXy/material-components-web/commit/981ec9b6fd538caadb44f7469745de8f8954c89b))
* **form-field:** Use superclass properties without trailing underscores ([7fd792b](https://github.com/MaTriXy/material-components-web/commit/7fd792bb9841501ecbc35b4024a00e07216fb95b))
* **icon-button:** Use superclass properties without trailing underscores ([740860e](https://github.com/MaTriXy/material-components-web/commit/740860e789992163537cc7138d6c21672adb79d0))
* **line-ripple:** Use superclass properties without trailing underscores ([a4aae3d](https://github.com/MaTriXy/material-components-web/commit/a4aae3d3710ba5eb86f27dee230064dfccf2e73f))
* **linear-progress:** Temporary rollback of [#5656](https://github.com/MaTriXy/material-components-web/issues/5656) while updating downstream dependencies ([9cf5e98](https://github.com/MaTriXy/material-components-web/commit/9cf5e9842475e50046462aa1c6d18e326abaee17))
* **list:** ensure sass mixin works if leading is provided in px ([265ecba](https://github.com/MaTriXy/material-components-web/commit/265ecbad56c001c0fed391b6be66f0d5ec483838))
* **list:** No longer emits action event when disabled item selected ([f352d03](https://github.com/MaTriXy/material-components-web/commit/f352d03f4ed48c5019a0a3e10ef12689a5ab5619)), closes [#5571](https://github.com/MaTriXy/material-components-web/issues/5571)
* **list:** Remove obsolete non-interactive class & :not selectors ([2553e86](https://github.com/MaTriXy/material-components-web/commit/2553e86fee2753ec59f1fbc91764bf110ad9d3aa))
* **list:** Use superclass properties without trailing underscores ([4847dd7](https://github.com/MaTriXy/material-components-web/commit/4847dd7645adf463ea947fc2afb346df648a1ffc))
* **mdc-slider:** avoid server side rendering error ([95c7355](https://github.com/MaTriXy/material-components-web/commit/95c73550e886c2832aa42cd065552551b6690a61))
* **menu-surface:** Use margin_to_edge as a viewport margin in calculations for autopositioning. ([4b04cdb](https://github.com/MaTriXy/material-components-web/commit/4b04cdb0fc4da4831340b01292c118b120c1fcb1))
* **menusurface:** open and closed events not fired when already opened or closed ([9cff431](https://github.com/MaTriXy/material-components-web/commit/9cff4318f0fe8a79f8787afd148907328a5223d5))
* **menusurface:** synchronous quick menu does not close on button click ([45a6615](https://github.com/MaTriXy/material-components-web/commit/45a6615e33eb8a7e6fc37e9ef43a3be3682b6b0e))
* **notched-outline:** Restore component test ([#5449](https://github.com/MaTriXy/material-components-web/issues/5449)) ([4269133](https://github.com/MaTriXy/material-components-web/commit/4269133421f7058385255b0676be94c9c1170b2d))
* **select:** Deduplicate change events ([4ad1274](https://github.com/MaTriXy/material-components-web/commit/4ad12741e41c5b8e175f2bc8d5053daec6cedf18)), closes [#5570](https://github.com/MaTriXy/material-components-web/issues/5570)
* **select:** Fix notch outline width when floating ([#5319](https://github.com/MaTriXy/material-components-web/issues/5319)) ([1c494e5](https://github.com/MaTriXy/material-components-web/commit/1c494e5672c142f3f3451aa2270431844d35c88e))
* **select:** Fix redundant calculations & allow resyncing foundation to options ([ff4bc63](https://github.com/MaTriXy/material-components-web/commit/ff4bc632aeeefb8eca16d774db01f8f176479659)), closes [#5646](https://github.com/MaTriXy/material-components-web/issues/5646) [#5646](https://github.com/MaTriXy/material-components-web/issues/5646) [#5686](https://github.com/MaTriXy/material-components-web/issues/5686) [#5783](https://github.com/MaTriXy/material-components-web/issues/5783)
* **select:** Remove pointer events where unnecessary ([0e052b2](https://github.com/MaTriXy/material-components-web/commit/0e052b24f415b81fbffb45182030dd8b9d68ee98))
* **select:** Set aria-selected="false" properly ([730920f](https://github.com/MaTriXy/material-components-web/commit/730920fbba046b0a7c3821f52877504a78373f1f))
* **select:** Update disabled state ([f83e008](https://github.com/MaTriXy/material-components-web/commit/f83e00898fb57e49e38ef59b3458df4525332302))
* **select:** Update dropdown arrow icon transitions ([15d6544](https://github.com/MaTriXy/material-components-web/commit/15d65448e5dd8a29477b34754264644ad88f8421))
* **select:** Update markup in tests and README ([e3eacef](https://github.com/MaTriXy/material-components-web/commit/e3eacefcc0ca3ca89af34b3e4d3dc13c5a27570b))
* **slider:** mobile sliding regression ([e844443](https://github.com/MaTriXy/material-components-web/commit/e844443878b9711a306e72b951c7ea931b17d837)), closes [#5894](https://github.com/MaTriXy/material-components-web/issues/5894)
* **slider:** slider track not visible ([#5512](https://github.com/MaTriXy/material-components-web/issues/5512)) ([f2426d2](https://github.com/MaTriXy/material-components-web/commit/f2426d26e683591cee87b4107f990492b47ec837))
* **slider:** two change events fired on each up ([d10412c](https://github.com/MaTriXy/material-components-web/commit/d10412cb24150639acc617caef1c7fac4fb6e4bd))
* **slider:** use secondary custom property color for slider container ([#5132](https://github.com/MaTriXy/material-components-web/issues/5132)) ([aa8e43e](https://github.com/MaTriXy/material-components-web/commit/aa8e43e9afaa1e00080f149bbe497746b57a285a))
* **slider:** Visual bug when slider value is displayed as "-0" ([3fc3ab5](https://github.com/MaTriXy/material-components-web/commit/3fc3ab520ab5399c3b87b094e047a1751f7aa9af))
* **snackbar:** add explicit width for label to wrap in ie11 ([#5497](https://github.com/MaTriXy/material-components-web/issues/5497)) ([cd49033](https://github.com/MaTriXy/material-components-web/commit/cd4903304412d79be8da96499091259b5e954c80))
* **snackbar:** adjust mixins to meet spec ([#5477](https://github.com/MaTriXy/material-components-web/issues/5477)) ([f16f15b](https://github.com/MaTriXy/material-components-web/commit/f16f15b8fda0d8c283bed5551b78620bf2fd3b82))
* **switch:** add transform transition to switch control to avoid overflow-x issues ([8c11ea2](https://github.com/MaTriXy/material-components-web/commit/8c11ea2a3bd7962c6d895c5bd6b849f95b52d10c))
* **switch:** always set track to transparent border ([9a169f4](https://github.com/MaTriXy/material-components-web/commit/9a169f4b158a3148126ba38bcdfa9d163434d9bb))
* **switch:** fix strict generic checks ([7f5e0c2](https://github.com/MaTriXy/material-components-web/commit/7f5e0c23ffb2f547d9bfca6b68927b5861a3112b))
* **switch:** handle aria-checked correctly. ([#5202](https://github.com/MaTriXy/material-components-web/issues/5202)) ([#5357](https://github.com/MaTriXy/material-components-web/issues/5357)) ([d245a1a](https://github.com/MaTriXy/material-components-web/commit/d245a1a544c643b59f77cd2e01b7eb2c1182f6b9))
* **switch:** use CSS custom properties for theming ([d6315ef](https://github.com/MaTriXy/material-components-web/commit/d6315efe26e7baf45fd88244efbb24c612a95cb4))
* **textfield:** add placeholder mixins and fix disabled colors ([#5360](https://github.com/MaTriXy/material-components-web/issues/5360)) ([0a40ced](https://github.com/MaTriXy/material-components-web/commit/0a40ced406f96b5c84cf39457ffe880d00999714))
* **textfield:** add separate classes for leading/trailing icons ([#5367](https://github.com/MaTriXy/material-components-web/issues/5367)) ([70c708d](https://github.com/MaTriXy/material-components-web/commit/70c708deece4c2c0afe38a31a4989abf2b1c1743))
* **textfield:** change root element to <label> ([#5439](https://github.com/MaTriXy/material-components-web/issues/5439)) ([d8d9502](https://github.com/MaTriXy/material-components-web/commit/d8d95020ff94249f8755ca49aaa06a6e9f0813b0))
* **textfield:** clean up input padding ([8639c26](https://github.com/MaTriXy/material-components-web/commit/8639c269010b77b17f1a5052d57abcb5f7d2892a))
* **textfield:** core-styles now applies sub-element core-styles ([bcdad99](https://github.com/MaTriXy/material-components-web/commit/bcdad99bbf9ac4d2bbc09cf6378c0c040521e514)), closes [#5927](https://github.com/MaTriXy/material-components-web/issues/5927)
* **textfield:** hide filled-variant floating label at <52px ([#5553](https://github.com/MaTriXy/material-components-web/issues/5553)) ([5ff3380](https://github.com/MaTriXy/material-components-web/commit/5ff33802c22acf7d94fd94c9ccdcfcf901397d56))
* **textfield:** IE11 label overlapping placeholder ([781434a](https://github.com/MaTriXy/material-components-web/commit/781434a92f4dddc9b2d39853e1f5792e89e7b45b))
* **textfield:** incorrect mixin forward path ([#5554](https://github.com/MaTriXy/material-components-web/issues/5554)) ([3e782d8](https://github.com/MaTriXy/material-components-web/commit/3e782d8f84c0096f6a6de3e022017fbb05175fa2))
* **textfield:** move ripple to separate element ([c541ebe](https://github.com/MaTriXy/material-components-web/commit/c541ebe157a66e8d2e881fad16cc4dbe30b2c16b))
* **textfield:** outlined trailing icon's position ([#5496](https://github.com/MaTriXy/material-components-web/issues/5496)) ([93e2288](https://github.com/MaTriXy/material-components-web/commit/93e2288b6ef73c13402a1f5122e2f9a4523ed4a4))
* **textfield:** prevent placeholder styles from collapsing with minifiers ([d07c78d](https://github.com/MaTriXy/material-components-web/commit/d07c78daa83389ef428618d334b037da67740b99))
* **textfield:** remove absolute positioning from icons ([1e13d1d](https://github.com/MaTriXy/material-components-web/commit/1e13d1d5a68632f1b0b5a9134f657d59104969f4))
* **textfield:** remove deprecated dense variant in favor of density ([776291e](https://github.com/MaTriXy/material-components-web/commit/776291ef03205e4063b4040eb66f9648e16b4af6)), closes [#4142](https://github.com/MaTriXy/material-components-web/issues/4142)
* **textfield:** replace notched outline and ripple `<div>`s with `<span>` ([765caef](https://github.com/MaTriXy/material-components-web/commit/765caef189844153ac7e47f0102139dc938edbfb))
* **textfield:** textarea density label position is now correct ([2f8a227](https://github.com/MaTriXy/material-components-web/commit/2f8a227a289a56702fec6592a87cf8bab422326a))
* **textfield:** textarea min-width not set correctly for Chrome ([0a371b4](https://github.com/MaTriXy/material-components-web/commit/0a371b4fe4ca4452618a867aac1731c6d3136b91))
* **textfield:** update outlined textarea specs ([524b7b8](https://github.com/MaTriXy/material-components-web/commit/524b7b8127e74bc3d551bd3b81e951fc51682665))
* fix show/hide clauses in import-only files ([148e448](https://github.com/MaTriXy/material-components-web/commit/148e448de1290e3628fac6eae19609c8e1bffda3))
* **textfield:** use correct disabled colors for IE11 high contrast ([5353985](https://github.com/MaTriXy/material-components-web/commit/535398572daea2ec389c341f4e0c53cb33582b26))
* **typography:** ensure global variables can override styles with module system ([7ec9697](https://github.com/MaTriXy/material-components-web/commit/7ec96974ef0c0c743b1eaaec40524ddc9c7e99e5))
* **typography:** Separate @material/feature-targeting, was causing Sass test to fail ([772a03e](https://github.com/MaTriXy/material-components-web/commit/772a03ef057047f506bb858dead1d59db0fce50e))
* add missing SASS dependencies ([#5337](https://github.com/MaTriXy/material-components-web/issues/5337)) ([d2ae6e1](https://github.com/MaTriXy/material-components-web/commit/d2ae6e17d19e7139bce45a0f44ce4ba172bbb3e6))
* server-side rendering errors in linear progress and slider ([7d0b983](https://github.com/MaTriXy/material-components-web/commit/7d0b983a902deee6941d61906aa5a880628db4e9))
* **button:** Add `overflow: visible` to button. ([#4973](https://github.com/MaTriXy/material-components-web/issues/4973)) ([905e84e](https://github.com/MaTriXy/material-components-web/commit/905e84e4a2778dcc37202d85acf7bd7a306b0933))
* **button:** Adjust touch target size when density is applied ([#5112](https://github.com/MaTriXy/material-components-web/issues/5112)) ([e2506f4](https://github.com/MaTriXy/material-components-web/commit/e2506f4b3de7494767197c7c1510c019879f8ecf))
* **button:** Fix outline & ink color according to spec guidance ([#5268](https://github.com/MaTriXy/material-components-web/issues/5268)) ([ee1a68c](https://github.com/MaTriXy/material-components-web/commit/ee1a68c54fa9240a334b0462513b855d5dab4807))
* **button:** Fixed  parameter default value in height mixin ([#5244](https://github.com/MaTriXy/material-components-web/issues/5244)) ([b0cecf1](https://github.com/MaTriXy/material-components-web/commit/b0cecf1451c13fd8c159c1b0ca90b2a1e9b907a0))
* **checkbox:** Change minimum ripple size of checkbox & switch 24px => 28px ([#5140](https://github.com/MaTriXy/material-components-web/issues/5140)) ([3eae309](https://github.com/MaTriXy/material-components-web/commit/3eae309495f447c84ba493cb9cbb0058dc53cf6c))
* **checkbox:** Disabled state colors in IE11 high contrast mode ([#5263](https://github.com/MaTriXy/material-components-web/issues/5263)) ([d6a1d4b](https://github.com/MaTriXy/material-components-web/commit/d6a1d4bf81b828f214e8bbf941090ef7d8e91c58))
* **checkbox:** Fix checkbox terminology in sass mixins ([#5014](https://github.com/MaTriXy/material-components-web/issues/5014)) ([2161c02](https://github.com/MaTriXy/material-components-web/commit/2161c024d012ab90ea6580d53a59d17affcc0e20))
* **checkbox:** Fixed checkbox container fill color when animati… ([#4879](https://github.com/MaTriXy/material-components-web/issues/4879)) ([d393fb5](https://github.com/MaTriXy/material-components-web/commit/d393fb56cfc6428e29f49baa8c58353233a84daf))
* **checkbox:** Fixed hover focus colors for unchecked checkbox ([#4868](https://github.com/MaTriXy/material-components-web/issues/4868)) ([1d8fbf5](https://github.com/MaTriXy/material-components-web/commit/1d8fbf5dc8322149f18bbad0b11b4c6ecd913f21))
* **checkbox:** Remove RTL styles from checkbox ripple ([#5134](https://github.com/MaTriXy/material-components-web/issues/5134)) ([a646516](https://github.com/MaTriXy/material-components-web/commit/a6465161b31ebe79a2aecf38f918197e1d83a632))
* **checkbox:** screenshot test golden update ([#4735](https://github.com/MaTriXy/material-components-web/issues/4735)) ([0b44494](https://github.com/MaTriXy/material-components-web/commit/0b4449406d5168c7fcff7879d0ab1e62ff69b365))
* **checkbox:** screenshot test golden update ([#4735](https://github.com/MaTriXy/material-components-web/issues/4735)) ([adcf840](https://github.com/MaTriXy/material-components-web/commit/adcf840aa16127f412cc9bf046a809a95d008a15))
* **checkbox:** update disabled color values ([#5209](https://github.com/MaTriXy/material-components-web/issues/5209)) ([821871e](https://github.com/MaTriXy/material-components-web/commit/821871e04737c5b0c0afded9e8e885680ca25a1f))
* **chips:** Add box-sizing back to chip root ([#4807](https://github.com/MaTriXy/material-components-web/issues/4807)) ([cbee4e2](https://github.com/MaTriXy/material-components-web/commit/cbee4e279ed43a0559f113bf24af1d6ba8d726d1))
* **chips:** Add box-sizing back to chip root ([#4807](https://github.com/MaTriXy/material-components-web/issues/4807)) ([19a19b3](https://github.com/MaTriXy/material-components-web/commit/19a19b3183dfb7f8a4bb8005072f63bc99d93254))
* **chips:** Do not throw error if chip set becomes empty ([#5290](https://github.com/MaTriXy/material-components-web/issues/5290)) ([f978109](https://github.com/MaTriXy/material-components-web/commit/f978109c33d9e67aebe5af3e460174686eea7b4a))
* **chips:** Fix chips trailing icon margin ([#4720](https://github.com/MaTriXy/material-components-web/issues/4720)) ([5de76bc](https://github.com/MaTriXy/material-components-web/commit/5de76bcd062325917e9f9dd5e122b232adba0e9f))
* **chips:** Fix chips trailing icon margin ([#4720](https://github.com/MaTriXy/material-components-web/issues/4720)) ([41b1f74](https://github.com/MaTriXy/material-components-web/commit/41b1f74b010b9caee4319c273a021024f3c57ddd))
* **chips:** Ignore selection events in chip set ([#4878](https://github.com/MaTriXy/material-components-web/issues/4878)) ([94c6a00](https://github.com/MaTriXy/material-components-web/commit/94c6a000b46c3e39af4cf0795dbe2da584cfbf97))
* **chips:** Remove keyCode check ([#4966](https://github.com/MaTriXy/material-components-web/issues/4966)) ([e6304c4](https://github.com/MaTriXy/material-components-web/commit/e6304c46d0f9d14602c7924950db304850bb50d9))
* **chips:** Reset touch target when chip density mixin is applied. ([#5116](https://github.com/MaTriXy/material-components-web/issues/5116)) ([d3b515e](https://github.com/MaTriXy/material-components-web/commit/d3b515e894da3045b24816226306254516c6995a))
* **chips:** Stack trailing/leading icons above touch target el ([#5040](https://github.com/MaTriXy/material-components-web/issues/5040)) ([048d4b7](https://github.com/MaTriXy/material-components-web/commit/048d4b7bf4335f03c8f18051989ffc6fe1693b12))
* **chips:** Stop emitting events in handlers ([#4969](https://github.com/MaTriXy/material-components-web/issues/4969)) ([cfd81dc](https://github.com/MaTriXy/material-components-web/commit/cfd81dc8cc1648b03f69ebe1f8eb1c0b8e6ad27e))
* **core:** Fix canary release by excluding test files from default tsconfig ([#5317](https://github.com/MaTriXy/material-components-web/issues/5317)) ([c916008](https://github.com/MaTriXy/material-components-web/commit/c9160084f1f64800e74e0e69673c6b2beca22ee4))
* **data-table:** Add .npmignore to ignore typescript files when… ([#4992](https://github.com/MaTriXy/material-components-web/issues/4992)) ([dd422d1](https://github.com/MaTriXy/material-components-web/commit/dd422d10cd2f4cf8fbb1f58a849354756325dcb0))
* **data-table:** Fixed alignment of header cell title for numer… ([#4963](https://github.com/MaTriXy/material-components-web/issues/4963)) ([b6274a7](https://github.com/MaTriXy/material-components-web/commit/b6274a702a562f6a8ad1cc612af006809ced21d1))
* **data-table:** Minor fixes for data table layout ([#5037](https://github.com/MaTriXy/material-components-web/issues/5037)) ([37b1f93](https://github.com/MaTriXy/material-components-web/commit/37b1f93188e049c65a3422b742a076affab2e84d))
* **dialog:** Add noflip annotations for GSS compiler. ([#4769](https://github.com/MaTriXy/material-components-web/issues/4769)) ([d644e78](https://github.com/MaTriXy/material-components-web/commit/d644e78775996d8f519d3e7f261741f8c633e32f))
* **dialog:** Add noflip annotations for GSS compiler. ([#4769](https://github.com/MaTriXy/material-components-web/issues/4769)) ([5563a12](https://github.com/MaTriXy/material-components-web/commit/5563a122066b1ad6f08ce710438a18dcdac6a860))
* **dialog:** Fix scrolling content overflowing on Chrome/Android. ([#4746](https://github.com/MaTriXy/material-components-web/issues/4746)) ([f741ae0](https://github.com/MaTriXy/material-components-web/commit/f741ae0091b20cd8f9ac80bfb2f0a55176fdd6d2))
* **dialog:** Fix scrolling content overflowing on Chrome/Android. ([#4746](https://github.com/MaTriXy/material-components-web/issues/4746)) ([3e9abda](https://github.com/MaTriXy/material-components-web/commit/3e9abda8e7d7ac359f0161b34c4f4b24efc8f5f2))
* **dialog:** Move aria roles from dialog root to dialog surface… ([#5239](https://github.com/MaTriXy/material-components-web/issues/5239)) ([c704b71](https://github.com/MaTriXy/material-components-web/commit/c704b71d931dd0db191a30ff88a5d0c44f099300))
* **dialog:** Use 100vw for dialog max-width calculation. ([#4766](https://github.com/MaTriXy/material-components-web/issues/4766)) ([f918e0a](https://github.com/MaTriXy/material-components-web/commit/f918e0abc64868542da251c9bfcb6dcc97be3c3f)), closes [#4746](https://github.com/MaTriXy/material-components-web/issues/4746)
* **dialog:** Use 100vw for dialog max-width calculation. ([#4766](https://github.com/MaTriXy/material-components-web/issues/4766)) ([d0b8c89](https://github.com/MaTriXy/material-components-web/commit/d0b8c8923b6368aafc921c83ce9bc4bac17d9c27)), closes [#4746](https://github.com/MaTriXy/material-components-web/issues/4746)
* **elevation:** Update overlay color mixin ([#5331](https://github.com/MaTriXy/material-components-web/issues/5331)) ([b723dfa](https://github.com/MaTriXy/material-components-web/commit/b723dfa7848c4b96bc24bb148cc5f55f316625ee))
* **fab:** Add missing dep to fab package.json. ([#5236](https://github.com/MaTriXy/material-components-web/issues/5236)) ([e0f6fd9](https://github.com/MaTriXy/material-components-web/commit/e0f6fd931f677874dcad4d91c3d74a2125674e96))
* **fab:** Add overflow: hidden; to ripple target to fix bounded ripple. ([#5214](https://github.com/MaTriXy/material-components-web/issues/5214)) ([97cbbdc](https://github.com/MaTriXy/material-components-web/commit/97cbbdc28c1623acbc40c878e2b3d48c80c01cef))
* **fab:** Add overflow: visible to make touch target visible in… ([#5241](https://github.com/MaTriXy/material-components-web/issues/5241)) ([5850080](https://github.com/MaTriXy/material-components-web/commit/58500806e27a0931404631d76bc09646bc64caaf))
* **fab:** Adjust fab line-height ([#5254](https://github.com/MaTriXy/material-components-web/issues/5254)) ([525989b](https://github.com/MaTriXy/material-components-web/commit/525989b5d8dfe86bcb6f65e0f0f0fd138e4b4b76))
* **fab:** Adjust fab line-height to center text ([#5258](https://github.com/MaTriXy/material-components-web/issues/5258)) ([591a6ad](https://github.com/MaTriXy/material-components-web/commit/591a6ad449f98efa7bc00c8afdd2716a6fbe75d9))
* **fab:** clear text decoration ([#4865](https://github.com/MaTriXy/material-components-web/issues/4865)) ([b524a12](https://github.com/MaTriXy/material-components-web/commit/b524a12535eb9b74e322742e152e18a966f9a256))
* **fab:** Use FAB ripple target selector ([#5146](https://github.com/MaTriXy/material-components-web/issues/5146)) ([9d91acc](https://github.com/MaTriXy/material-components-web/commit/9d91acc0ec332bdda462075f534204ec2ea7af9c))
* **form-field:** Fix radio RTL alignment bug. ([#5064](https://github.com/MaTriXy/material-components-web/issues/5064)) ([ef99808](https://github.com/MaTriXy/material-components-web/commit/ef99808cba809294cb2d90903d12cdf930071f4d))
* **infrastructure:** Fix failing screenshot tests ([#4800](https://github.com/MaTriXy/material-components-web/issues/4800)) ([a9a41cb](https://github.com/MaTriXy/material-components-web/commit/a9a41cbb9ea9997566d89fb885867d6fe5fa4a42))
* **infrastructure:** Fix failing screenshot tests ([#4800](https://github.com/MaTriXy/material-components-web/issues/4800)) ([0fb049e](https://github.com/MaTriXy/material-components-web/commit/0fb049e34f1779fb7b7d1ece0754ec5836558b61))
* **infrastructure:** support ssr by removing the reference from window ([#4864](https://github.com/MaTriXy/material-components-web/issues/4864)) ([e5c5ea5](https://github.com/MaTriXy/material-components-web/commit/e5c5ea51d6052454fff54419416a5afe653b2965))
* **infrastructure:** update check-pkg-for-release.js ([#4857](https://github.com/MaTriXy/material-components-web/issues/4857)) ([0cd775c](https://github.com/MaTriXy/material-components-web/commit/0cd775c7905df563cfd83c8726d82dc224b59bcb))
* **linear-progress:** Fix indeterminate animation bug ([#5180](https://github.com/MaTriXy/material-components-web/issues/5180)) ([062ade5](https://github.com/MaTriXy/material-components-web/commit/062ade5c052cf00cefeee6e8e0acf7d16c4ce338))
* **linear-progress:** Prefix animation keyframes to prevent clashing ([#5155](https://github.com/MaTriXy/material-components-web/issues/5155)) ([fc0e474](https://github.com/MaTriXy/material-components-web/commit/fc0e4743be6d6187c31b745c935d18f5b7d2267b))
* **linear-progress:** Restore buffer after determinate is toggl… ([#5156](https://github.com/MaTriXy/material-components-web/issues/5156)) ([09b1598](https://github.com/MaTriXy/material-components-web/commit/09b1598116b26905f2f58eab84b977e035174c26))
* **linear-progress:** stop animation when closed ([#5006](https://github.com/MaTriXy/material-components-web/issues/5006)) ([4c4342d](https://github.com/MaTriXy/material-components-web/commit/4c4342d28c251f963498c117322532b7180d6196))
* **linear-progress:** Support high contrast mode ([#5190](https://github.com/MaTriXy/material-components-web/issues/5190)) ([d4141c9](https://github.com/MaTriXy/material-components-web/commit/d4141c954311888017a61c7e7fdcd0fd5c99bf1f))
* **list:** Add #adapter.listItemAtIndexHasClass to prevent user state change to disabled items ([#4922](https://github.com/MaTriXy/material-components-web/issues/4922)) ([b6d213c](https://github.com/MaTriXy/material-components-web/commit/b6d213c4c28090f631d2ce7a1dcdde30462c3003))
* **list:** Ensure disabled colors apply to primary and secondary text ([#5322](https://github.com/MaTriXy/material-components-web/issues/5322)) ([878a08b](https://github.com/MaTriXy/material-components-web/commit/878a08b7cf673ba45f124b400032928b2c273749))
* **menu:** Fix bug where TAB does not respect the default browser tab order. ([#4789](https://github.com/MaTriXy/material-components-web/issues/4789)) ([22237cd](https://github.com/MaTriXy/material-components-web/commit/22237cd468fa859091197bad231d02aef412533f))
* **menu:** Fix bug where TAB does not respect the default browser tab order. ([#4789](https://github.com/MaTriXy/material-components-web/issues/4789)) ([fac4c43](https://github.com/MaTriXy/material-components-web/commit/fac4c4328645676db88f8d2396dfa5ac15462d09))
* **menu:** In Windows high contrast mode, decrease opacity of disabled menu items. ([#4777](https://github.com/MaTriXy/material-components-web/issues/4777)) ([898e53e](https://github.com/MaTriXy/material-components-web/commit/898e53ed34ba9eda1581265f24f12ee937ef6de7))
* **menu:** In Windows high contrast mode, decrease opacity of disabled menu items. ([#4777](https://github.com/MaTriXy/material-components-web/issues/4777)) ([08e4dc1](https://github.com/MaTriXy/material-components-web/commit/08e4dc1e9fcb90de7d3fcb0144ef5e4f2712c131))
* **menu:** recompute index before marking selection ([#5047](https://github.com/MaTriXy/material-components-web/issues/5047)) ([90f6247](https://github.com/MaTriXy/material-components-web/commit/90f6247547bfbe754bd93b54d1965259daa746c9))
* **menu:** Remove code to focus on first/last element on TAB/SHIFT+TAB. ([#4786](https://github.com/MaTriXy/material-components-web/issues/4786)) ([d3f8cb3](https://github.com/MaTriXy/material-components-web/commit/d3f8cb3845b0c8d725023be1d3c69535b9b1fc5c))
* **menu:** Remove code to focus on first/last element on TAB/SHIFT+TAB. ([#4786](https://github.com/MaTriXy/material-components-web/issues/4786)) ([99af567](https://github.com/MaTriXy/material-components-web/commit/99af567357dd5c8b74c58a160b704f204ac51054))
* **menu:** Switch from aria-selected to aria-checked for selected menu item. ([#4779](https://github.com/MaTriXy/material-components-web/issues/4779)) ([ef198ea](https://github.com/MaTriXy/material-components-web/commit/ef198eac2698f77a4823fe6aa22f1cc350fa8b1c))
* **menu:** Switch from aria-selected to aria-checked for selected menu item. ([#4779](https://github.com/MaTriXy/material-components-web/issues/4779)) ([f4b0bf5](https://github.com/MaTriXy/material-components-web/commit/f4b0bf546756a67c1c6408a1e819e92bf9ce547a))
* **menu:** Vertically center the group icon ([#4862](https://github.com/MaTriXy/material-components-web/issues/4862)) ([d551dfd](https://github.com/MaTriXy/material-components-web/commit/d551dfde9dd377e7ca593565519ca49abd559d29))
* **menu-surface:** remove duplicate export from menu-surface ([#5200](https://github.com/MaTriXy/material-components-web/issues/5200)) ([0b120ae](https://github.com/MaTriXy/material-components-web/commit/0b120ae75f23ca0c30cec680f8e4145995e81dae))
* **radio:** Fix touch target margins: 0px => 4px. ([#5096](https://github.com/MaTriXy/material-components-web/issues/5096)) ([a48d06e](https://github.com/MaTriXy/material-components-web/commit/a48d06eae1f634a65fd24226d4a47f0cd253ba21))
* **radio:** update disabled color values ([#5210](https://github.com/MaTriXy/material-components-web/issues/5210)) ([491fddc](https://github.com/MaTriXy/material-components-web/commit/491fddc31c16f99206b1fa7dce37d43b742e86f5))
* **ripple:** Add overflow: hidden; to the bounded ripple mixin ([#5173](https://github.com/MaTriXy/material-components-web/issues/5173)) ([996b091](https://github.com/MaTriXy/material-components-web/commit/996b0910c2ceec75f99c0679714ebe474a63bca5))
* **ripple:** Always set even num when initial ripple size is ca… ([#5141](https://github.com/MaTriXy/material-components-web/issues/5141)) ([b26ad23](https://github.com/MaTriXy/material-components-web/commit/b26ad23e45ed66040cb1bb03e7a7f7f5d8321b53))
* **ripple:** Remove unnecessary overflow: hidden. ([#5191](https://github.com/MaTriXy/material-components-web/issues/5191)) ([5916d18](https://github.com/MaTriXy/material-components-web/commit/5916d18cfd2b3277665da6b61f44cc27095fff53))
* **rtl:** Removed mdc-rtl-include check from mdc-rtl-reflexive mixin ([#5001](https://github.com/MaTriXy/material-components-web/issues/5001)) ([6e7b191](https://github.com/MaTriXy/material-components-web/commit/6e7b1919f3690ef57f94f648ab49329aa875cef7))
* **select:** Do not fire change event on programmatic change ([#5255](https://github.com/MaTriXy/material-components-web/issues/5255)) ([ec72968](https://github.com/MaTriXy/material-components-web/commit/ec729683b46fb986a880f26870973337ec6788e5))
* **select:** Update screenshots for FF/Windows update. ([#4790](https://github.com/MaTriXy/material-components-web/issues/4790)) ([6ea503c](https://github.com/MaTriXy/material-components-web/commit/6ea503c3c0b84e0402dcffcd010e25b676d58c5e))
* **select:** Update screenshots for FF/Windows update. ([#4790](https://github.com/MaTriXy/material-components-web/issues/4790)) ([04aa6ff](https://github.com/MaTriXy/material-components-web/commit/04aa6ff6d2763ec66137a2f63d5a1ed915868695))
* **switch:** set track border to be transparent ([#5323](https://github.com/MaTriXy/material-components-web/issues/5323)) ([397905b](https://github.com/MaTriXy/material-components-web/commit/397905b4e34ff9769d3ae18464bc397a0b13050f))
* **tab-indicator:** Center content ([#4837](https://github.com/MaTriXy/material-components-web/issues/4837)) ([102d778](https://github.com/MaTriXy/material-components-web/commit/102d77820ec8ed58818840040e02d63027328780))
* **tabs:** Fix tab img icon styling. ([#5041](https://github.com/MaTriXy/material-components-web/issues/5041)) ([d0e6cd1](https://github.com/MaTriXy/material-components-web/commit/d0e6cd1903d3e72bab588629ba4c126e0519785e))
* **tabs:** Remove deprecated package mdc-tabs ([#4784](https://github.com/MaTriXy/material-components-web/issues/4784)) ([4f366a5](https://github.com/MaTriXy/material-components-web/commit/4f366a5d074366c63a21cad90ba1feda8b496eec))
* **testing:** Revert change from [#5299](https://github.com/MaTriXy/material-components-web/issues/5299). ([#5324](https://github.com/MaTriXy/material-components-web/issues/5324)) ([5fb62be](https://github.com/MaTriXy/material-components-web/commit/5fb62bead477f7db9a76d9c0adbfee4e9c110d37))
* Remove edge detection for CSS custom properties ([#5264](https://github.com/MaTriXy/material-components-web/issues/5264)) ([fe444ac](https://github.com/MaTriXy/material-components-web/commit/fe444ac29da5447419cf4c25edbdf934c6e388e4))
* **text-field:** Do not trigger shake animation when text field is empty ([#5097](https://github.com/MaTriXy/material-components-web/issues/5097)) ([4913db9](https://github.com/MaTriXy/material-components-web/commit/4913db9711bd9a2b69fd15ec650b98ca7027b257))
* **text-field:** Fix asterisk color of text field when input is invalid and disabled ([#4806](https://github.com/MaTriXy/material-components-web/issues/4806)) ([24054ed](https://github.com/MaTriXy/material-components-web/commit/24054edfaa6fd56351334aff4b116d4992790151))
* **text-field:** Fixes input text alignment on IE11 for densed text field ([#5136](https://github.com/MaTriXy/material-components-web/issues/5136)) ([892dd4e](https://github.com/MaTriXy/material-components-web/commit/892dd4ed42271be81cee3da21912c248f0df8533))
* **text-field:** Fixes input text alignment on IE11 for densed… ([#5147](https://github.com/MaTriXy/material-components-web/issues/5147)) ([c8f7693](https://github.com/MaTriXy/material-components-web/commit/c8f76938c8ec82d005196f425860585b0bfb8278))
* **text-field:** Updated shape mixins to set density scale ([#5207](https://github.com/MaTriXy/material-components-web/issues/5207)) ([719b57e](https://github.com/MaTriXy/material-components-web/commit/719b57e1c755c2886539032f728809cd47fab2a4))
* **top-app-bar:** "always collapsed" variant semantics in Short TopAppBar Foundation ([#5009](https://github.com/MaTriXy/material-components-web/issues/5009)) ([805d098](https://github.com/MaTriXy/material-components-web/commit/805d098aa73810659ecf9fb4d2d701181955eb54))
* **touch-target:** Add class to touch target wrapper. ([#5174](https://github.com/MaTriXy/material-components-web/issues/5174)) ([e7799b8](https://github.com/MaTriXy/material-components-web/commit/e7799b81a670590307e9014ecfbda0b637c96c98))
* move applyPassive to dom package for use in text-field ([#4747](https://github.com/MaTriXy/material-components-web/issues/4747)) ([ce0b1c5](https://github.com/MaTriXy/material-components-web/commit/ce0b1c5a3b18dff457ffe82aadca7954fcaecf1d))
* remove icontoggle ([#4783](https://github.com/MaTriXy/material-components-web/issues/4783)) ([5079213](https://github.com/MaTriXy/material-components-web/commit/507921382f9444a0465f748a404e878e247e736f))
* remove icontoggle ([#4783](https://github.com/MaTriXy/material-components-web/issues/4783)) ([a13089d](https://github.com/MaTriXy/material-components-web/commit/a13089d7d422e29fded52a65ca07bcdf9e60037f))
* update TypeScript version to 3.5.x and fix typing errors ([#4853](https://github.com/MaTriXy/material-components-web/issues/4853)) ([0657504](https://github.com/MaTriXy/material-components-web/commit/0657504ee1b59a6a686db91b5a3363287f784b30))
* Use head instead of body to detect edge pseudo var bug ([#4982](https://github.com/MaTriXy/material-components-web/issues/4982)) ([9e87478](https://github.com/MaTriXy/material-components-web/commit/9e8747840594dd435e04220dc9f4aa31eb153a88))
* **button:** Remove dense/stroked line-height tweaks to improve alignment ([#3028](https://github.com/MaTriXy/material-components-web/issues/3028)) ([8b5f595](https://github.com/MaTriXy/material-components-web/commit/8b5f595aaedd42e17ba95cdf8edfe3a76f346b1b))
* **button:** Update border-width to 1px ([#4606](https://github.com/MaTriXy/material-components-web/issues/4606)) ([be8747f](https://github.com/MaTriXy/material-components-web/commit/be8747f94574669cb5e7add1a7c54fa41a89cec7))
* **card:** Use on-surface color for action icons ([#4519](https://github.com/MaTriXy/material-components-web/issues/4519)) ([9f37016](https://github.com/MaTriXy/material-components-web/commit/9f37016490b37deaf87a23b9dc813f5233610635))
* **checkbox:** Fixed disabled checkbox styles for Edge browser ([#4602](https://github.com/MaTriXy/material-components-web/issues/4602)) ([7855a6b](https://github.com/MaTriXy/material-components-web/commit/7855a6b3da79ec7fabdd089779c5a6ee6487bd79))
* **chips:** Fix incorrect ripple effect on filter chip ([#4565](https://github.com/MaTriXy/material-components-web/issues/4565)) ([975bae2](https://github.com/MaTriXy/material-components-web/commit/975bae276b2d95152b9774b025cb7a4c145f4ef1))
* **chips:** Flip leading icon margin when used in RTL contexts ([#4380](https://github.com/MaTriXy/material-components-web/issues/4380)) ([ea15b2f](https://github.com/MaTriXy/material-components-web/commit/ea15b2f254c4bac91d90b781e01fc53b0651ad20))
* **feature-targeting:** fix incorrect list construction ([#4419](https://github.com/MaTriXy/material-components-web/issues/4419)) ([173f202](https://github.com/MaTriXy/material-components-web/commit/173f20256e99ded7f837d8ef5484b75b8b31a82d))
* **feature-targeting:** Move ripple styles into separate mixins ([#4454](https://github.com/MaTriXy/material-components-web/issues/4454)) ([720bef0](https://github.com/MaTriXy/material-components-web/commit/720bef02fe5d55cffe827614de89f6eac8b0526b))
* **floating-label:** Add missing import to mixins ([#4434](https://github.com/MaTriXy/material-components-web/issues/4434)) ([183d44e](https://github.com/MaTriXy/material-components-web/commit/183d44ed80a0be0eab6438b3b85f523ee1da39d5))
* **list:** Add cursor: pointer for interactive list items ([#4563](https://github.com/MaTriXy/material-components-web/issues/4563)) ([d2f0ccb](https://github.com/MaTriXy/material-components-web/commit/d2f0ccbbb2dc096f2c8be5d7ef924d8ee680ba59)), closes [#4557](https://github.com/MaTriXy/material-components-web/issues/4557)
* **list:** Include disabled list items in keyboard navigation and allow focus ([#4568](https://github.com/MaTriXy/material-components-web/issues/4568)) ([6e24280](https://github.com/MaTriXy/material-components-web/commit/6e242800d1fd327a9d856d291eda9e1db3f59d82))
* **list:** removed unused adapter.removeAttributeForElementIndex ([#4473](https://github.com/MaTriXy/material-components-web/issues/4473)) ([6b3a419](https://github.com/MaTriXy/material-components-web/commit/6b3a419650b20d4f50cff7c30b6de1951d532169))
* **list:** Update meta class to use caption typogrpahy style ([#4623](https://github.com/MaTriXy/material-components-web/issues/4623)) ([0826a78](https://github.com/MaTriXy/material-components-web/commit/0826a78d10a30139ededf18d88deca2f7fba0ab8))
* **menu:** Fix selection group list item spacing ([#4517](https://github.com/MaTriXy/material-components-web/issues/4517)) ([5183e01](https://github.com/MaTriXy/material-components-web/commit/5183e012d9130cb44405cc86d66ed297c23ca8b9))
* **menu:** Use on-surface color for graphic/meta content ([#4520](https://github.com/MaTriXy/material-components-web/issues/4520)) ([74b8d67](https://github.com/MaTriXy/material-components-web/commit/74b8d67e0117881e598f037e8550240835b361e7))
* **menu-surface:** Correct open animation issue ([#4371](https://github.com/MaTriXy/material-components-web/issues/4371)) ([ed4c945](https://github.com/MaTriXy/material-components-web/commit/ed4c94597bbfaa724c9f3abab692837f8645d63a))
* **menu-surface:** Fix anchorElement initialization ([#4462](https://github.com/MaTriXy/material-components-web/issues/4462)) ([2025c8b](https://github.com/MaTriXy/material-components-web/commit/2025c8b5eb9891ec3f159e2fde03f45d23f6bbed))
* **package:** Fix module declaration names in dist d.ts files ([#4476](https://github.com/MaTriXy/material-components-web/issues/4476)) ([872b39f](https://github.com/MaTriXy/material-components-web/commit/872b39f3602588604d9e51c250fcbcd28d651f72))
* **package:** Update fibers to the latest version 🚀 ([#4658](https://github.com/MaTriXy/material-components-web/issues/4658)) ([0590ebb](https://github.com/MaTriXy/material-components-web/commit/0590ebb1aea2f038d4f5bdf3d3103eb6607818be))
* **ripple:** Fixes issue where Chrome v74 shows black artifact on ripple surface on hover ([#4695](https://github.com/MaTriXy/material-components-web/issues/4695)) ([7a5e7ed](https://github.com/MaTriXy/material-components-web/commit/7a5e7ed3046b7506b1bf52388e659b53f16ab3c5))
* **ripple:** Removed will-change CSS property ([a0c7b81](https://github.com/MaTriXy/material-components-web/commit/a0c7b81f3391491bdb5c0b1dfe26eaa9a63e2cd1))
* **ripple:** Use mdc-dom.matches everywhere ([#4372](https://github.com/MaTriXy/material-components-web/issues/4372)) ([a2aa3c8](https://github.com/MaTriXy/material-components-web/commit/a2aa3c842e5d6f7ef35432222f5b6748c7eb8ccb)), closes [#4340](https://github.com/MaTriXy/material-components-web/issues/4340)
* **ripple:** Use standard element removal method ([#4638](https://github.com/MaTriXy/material-components-web/issues/4638)) ([ef07477](https://github.com/MaTriXy/material-components-web/commit/ef074775d2ce7c88ab3f8758277be15685c5e0ac))
* **select:** Fix enhanced select issue where it does not stay open on long press [#4173](https://github.com/MaTriXy/material-components-web/issues/4173) ([#4590](https://github.com/MaTriXy/material-components-web/issues/4590)) ([8286aa7](https://github.com/MaTriXy/material-components-web/commit/8286aa7321dc9fbd531ca4648e08fb141dc81d33))
* **select:** Fixes arrow direction on select focused state ([#4726](https://github.com/MaTriXy/material-components-web/issues/4726)) ([358546a](https://github.com/MaTriXy/material-components-web/commit/358546a375583bd0a90855e352767c54f926e3bb))
* **select:** Use correct shape category consistently with text-field ([#4553](https://github.com/MaTriXy/material-components-web/issues/4553)) ([bec2ef2](https://github.com/MaTriXy/material-components-web/commit/bec2ef2c0bcaf2e48a44ef146599c84a08145496))
* **shape:** Allow percentage based global overrides ([#4548](https://github.com/MaTriXy/material-components-web/issues/4548)) ([4bf7a86](https://github.com/MaTriXy/material-components-web/commit/4bf7a86ab48ee01136069d326a4d6ded7a7f883e))
* **shape:** Fix errors related to multi-value shape categories ([#4547](https://github.com/MaTriXy/material-components-web/issues/4547)) ([9f79d17](https://github.com/MaTriXy/material-components-web/commit/9f79d17c2e03fc38f2e7fe070dab0189e9e8d668))
* **tab:** Explicitly set margin to 0 on tabs for Safari ([#4654](https://github.com/MaTriXy/material-components-web/issues/4654)) ([28aa623](https://github.com/MaTriXy/material-components-web/commit/28aa6231682a1f169820c50127f8eed0a23fea1c))
* **tab:** Fix tab color variables to use color literals ([#4688](https://github.com/MaTriXy/material-components-web/issues/4688)) ([88734fe](https://github.com/MaTriXy/material-components-web/commit/88734fe77796f16bb03a6b0d17ab9b1f8ad523c7))
* **tab:** Fix tab icon color mixin to support SVG icons. ([#4540](https://github.com/MaTriXy/material-components-web/issues/4540)) ([5ad6570](https://github.com/MaTriXy/material-components-web/commit/5ad6570c0962c2114ae9fa2da2a16311d3dc01f7))
* **tab:** Update horizontal padding mixin ([#4678](https://github.com/MaTriXy/material-components-web/issues/4678)) ([d3ce9c9](https://github.com/MaTriXy/material-components-web/commit/d3ce9c9dfee4b6d2712eb4f06a04f48bf8f1fd0e))
* **tab:** Update moz-focusring to moz-focus-inner to match button ([#4567](https://github.com/MaTriXy/material-components-web/issues/4567)) ([968a054](https://github.com/MaTriXy/material-components-web/commit/968a054c8670aaab93c10af6ddb01e1069a9c030))
* **tab-indicator:** Remove child selector ([#4676](https://github.com/MaTriXy/material-components-web/issues/4676)) ([edbe0ba](https://github.com/MaTriXy/material-components-web/commit/edbe0ba28ca85579e010dbb0aa00ab467bdc3d5a))
* **tab-indicator:** Show border for high contrast ([#4666](https://github.com/MaTriXy/material-components-web/issues/4666)) ([5a52847](https://github.com/MaTriXy/material-components-web/commit/5a52847d7261b2374a58eb180fa8bbd6e12a7859))
* **tabs:** Disable firefox focus ring ([#4560](https://github.com/MaTriXy/material-components-web/issues/4560)) ([a99b7d4](https://github.com/MaTriXy/material-components-web/commit/a99b7d491894e4d6baeca1d1bac5e579416091d1))
* **text-field:** add classes constant ([#4608](https://github.com/MaTriXy/material-components-web/issues/4608)) ([22fa259](https://github.com/MaTriXy/material-components-web/commit/22fa259225a9f87e2c2ff4340cb6fd03c345f45b))
* **text-field:** Fix for input alignment in textfield with trailing icon ([#4478](https://github.com/MaTriXy/material-components-web/issues/4478)) ([b9c5fc6](https://github.com/MaTriXy/material-components-web/commit/b9c5fc6c684d82f63d007761214edf3ca21f99d4))
* **text-field:** Fix placeholder styles for text field fullwidth variant. ([#4385](https://github.com/MaTriXy/material-components-web/issues/4385)) ([3bd3636](https://github.com/MaTriXy/material-components-web/commit/3bd3636ccdd70cb9d3a22735d02c95e7affeb1ac))
* **text-field:** Fixed asterisk color where it stays in error color even after input is resolved ([#4576](https://github.com/MaTriXy/material-components-web/issues/4576)) ([ca502d4](https://github.com/MaTriXy/material-components-web/commit/ca502d4fdd24a7f5813de80e08488795b1fc060b))
* **text-field:** Fixes overlapping input with leading icon in absence of label ([#4637](https://github.com/MaTriXy/material-components-web/issues/4637)) ([64e459e](https://github.com/MaTriXy/material-components-web/commit/64e459e8d871c41cc03863d4160f1bd59837ee3e))
* **text-field:** Set char counter text not to wrap ([#4423](https://github.com/MaTriXy/material-components-web/issues/4423)) ([9b7dce7](https://github.com/MaTriXy/material-components-web/commit/9b7dce75b66091be807038475b097a6e70869a1c))
* **text-field:** Set character counter in setValue ([#4572](https://github.com/MaTriXy/material-components-web/issues/4572)) ([bce2e63](https://github.com/MaTriXy/material-components-web/commit/bce2e639317aa3f84f5e8c211ea99338cf210437))
* **text-field:** Update character counter to update when value is set. ([#4663](https://github.com/MaTriXy/material-components-web/issues/4663)) ([acfbe2d](https://github.com/MaTriXy/material-components-web/commit/acfbe2d590f18c306cc0a258071388c944d90f86))
* **text-field:** Update outline idle border color to match design guidance ([#4768](https://github.com/MaTriXy/material-components-web/issues/4768)) ([7fedeaf](https://github.com/MaTriXy/material-components-web/commit/7fedeaff4001ac7caf2946b9e4b14620a5588145))
* **top-app-bar:** Move comment line to appropriate section ([#4610](https://github.com/MaTriXy/material-components-web/issues/4610)) ([3e36555](https://github.com/MaTriXy/material-components-web/commit/3e3655539ad15e325e8c3b5bb894d2e5799ba9a4))
* **typography:** Use unquote for setting font-family. ([#4665](https://github.com/MaTriXy/material-components-web/issues/4665)) ([8d8f3fc](https://github.com/MaTriXy/material-components-web/commit/8d8f3fcb3f2940b071f761497490c1b0123e106b))
* Don't import * from focus-trap to avoid default export confusion ([#4485](https://github.com/MaTriXy/material-components-web/issues/4485)) ([6082dc3](https://github.com/MaTriXy/material-components-web/commit/6082dc363714d382859661102cd986a2b235b125))
* **card:** Corrected baseline shape value of card small => medium ([#4060](https://github.com/MaTriXy/material-components-web/issues/4060)) ([acb9443](https://github.com/MaTriXy/material-components-web/commit/acb94434a17da457a0da803523d2d8590f4afc7d))
* **card:** Update elevation to match spec ([#4040](https://github.com/MaTriXy/material-components-web/issues/4040)) ([a6b028d](https://github.com/MaTriXy/material-components-web/commit/a6b028d2cb2bf1a06a62ad99ae435691a683baf6))
* **checkbox:** Added missing clearTimeout call to destroy method ([#3674](https://github.com/MaTriXy/material-components-web/issues/3674)) ([7e5c3ca](https://github.com/MaTriXy/material-components-web/commit/7e5c3ca7e68ad722a3a65e1f8e2e6b5f76c5d038))
* **checkbox:** remove adapter.getNativeCb and move property hooks to component ([#4073](https://github.com/MaTriXy/material-components-web/issues/4073)) ([5ab68fe](https://github.com/MaTriXy/material-components-web/commit/5ab68fec33d6d243e56b003e2d82c520bae19620))
* **checkbox:** remove native control from getters/setters of foundation ([#3408](https://github.com/MaTriXy/material-components-web/issues/3408)) ([b0fe9cf](https://github.com/MaTriXy/material-components-web/commit/b0fe9cf255c0119347c66c61605c4c0f21eaa1a3))
* **notched-outline:** Auto position the notch and floating label based on corner size ([#3929](https://github.com/MaTriXy/material-components-web/issues/3929)) ([06daf52](https://github.com/MaTriXy/material-components-web/commit/06daf527163af74efebf8c0da88f75cef5c9ab2e))
* **radio:** remove getNativeControl from adapter ([#3785](https://github.com/MaTriXy/material-components-web/issues/3785)) ([476130e](https://github.com/MaTriXy/material-components-web/commit/476130efd32434e0491c97ef4de1a2643ce255bc))
* Future-proof Sass usage ([#3921](https://github.com/MaTriXy/material-components-web/issues/3921)) ([6fa2269](https://github.com/MaTriXy/material-components-web/commit/6fa2269fdb5bc24ec7a1c41e5eac6786010b0047))
* **checkbox:** remove register/deregisterEventlisteners from foundation ([#3402](https://github.com/MaTriXy/material-components-web/issues/3402)) ([430b338](https://github.com/MaTriXy/material-components-web/commit/430b338df635609ddf9ebc54a6c395d8bccba060))
* **checkbox:** support high contrast mode in Firefox on Windows ([#2927](https://github.com/MaTriXy/material-components-web/issues/2927)) ([2bd52c7](https://github.com/MaTriXy/material-components-web/commit/2bd52c7386ad59cc872ed30a0dfcee021cf17fab))
* **chips:** Add an event typedef for chip interaction events ([#2965](https://github.com/MaTriXy/material-components-web/issues/2965)) ([153e737](https://github.com/MaTriXy/material-components-web/commit/153e7375842aa6119e1e507d0818cfd315963b53))
* **chips:** Make event handlers on Chip public ([#2997](https://github.com/MaTriXy/material-components-web/issues/2997)) ([963e0c1](https://github.com/MaTriXy/material-components-web/commit/963e0c1052dfb2fe9c31c3a5a3a6c0c65e3ec40e))
* **chips:** Notify ChipSet when selected is set directly on the Chip ([#3601](https://github.com/MaTriXy/material-components-web/issues/3601)) ([891f30d](https://github.com/MaTriXy/material-components-web/commit/891f30d5925ff8a6c47fec50dae1cd73d8ea5b97))
* **chips:** Remove color change from selected filter chips ([#3093](https://github.com/MaTriXy/material-components-web/issues/3093)) ([19e3d7f](https://github.com/MaTriXy/material-components-web/commit/19e3d7f0d24797020f2813858cf08380232e2445))
* **chips:** Use required pixel value ([#4361](https://github.com/MaTriXy/material-components-web/issues/4361)) ([fdfd934](https://github.com/MaTriXy/material-components-web/commit/fdfd9347180d9d1642452b559d249e56fc3fb8eb))
* **demos:** Corrected HTML structure in demo index page for two-line list ([#3359](https://github.com/MaTriXy/material-components-web/issues/3359)) ([15f376c](https://github.com/MaTriXy/material-components-web/commit/15f376cab403283da58fea30c93972fec269cdd2))
* **dialog:** Add redlines to dialog screenshots; update to match spec ([#3602](https://github.com/MaTriXy/material-components-web/issues/3602)) ([4da83dd](https://github.com/MaTriXy/material-components-web/commit/4da83dd83134e80e4e736103e16889d812e60fd6))
* **dialog:** Apply max-width to same element as min-width ([#3749](https://github.com/MaTriXy/material-components-web/issues/3749)) ([2dac7e1](https://github.com/MaTriXy/material-components-web/commit/2dac7e11bb16c86a03445de050b0227de032842d))
* **dialog:** Cancel open's rAF when close is called ([#4087](https://github.com/MaTriXy/material-components-web/issues/4087)) ([2516c25](https://github.com/MaTriXy/material-components-web/commit/2516c25c1984c66d22d8a7876bd1731aa01e8291))
* **dialog:** Conform more closely with spec ([#3575](https://github.com/MaTriXy/material-components-web/issues/3575)) ([359710d](https://github.com/MaTriXy/material-components-web/commit/359710deee281200b3a65c14ae3b3ccef04118ff))
* **dialog:** Expose numbers on foundation ([#3346](https://github.com/MaTriXy/material-components-web/issues/3346)) ([8f35741](https://github.com/MaTriXy/material-components-web/commit/8f35741c0621a56b77b4f6722a76e026a600e345))
* **dialog:** Fixes transitionend event not always being called ([#3267](https://github.com/MaTriXy/material-components-web/issues/3267)) ([fe9d195](https://github.com/MaTriXy/material-components-web/commit/fe9d19596836859777a0ca207ea715220b8ae565))
* **dialog:** Increase z-index above Drawer ([#3597](https://github.com/MaTriXy/material-components-web/issues/3597)) ([c1bd45a](https://github.com/MaTriXy/material-components-web/commit/c1bd45a523347cdf8d1fb34d939b7cc1b9c4e974))
* **dialog:** Release focus after style changes on close ([#4069](https://github.com/MaTriXy/material-components-web/issues/4069)) ([e12997a](https://github.com/MaTriXy/material-components-web/commit/e12997a3c4e851f673a04bd3fde2ff51f47e2948))
* **dialog:** Wait for rAF/timeout to apply open class ([#3682](https://github.com/MaTriXy/material-components-web/issues/3682)) ([4fd076b](https://github.com/MaTriXy/material-components-web/commit/4fd076bcba0546e896147ae3a5541a61b613bd77))
* **drawer:** allow drawer below top app bar ([#4028](https://github.com/MaTriXy/material-components-web/issues/4028)) ([ebdb084](https://github.com/MaTriXy/material-components-web/commit/ebdb084ca505380a21e4e90215c51e86e61b4c58))
* **drawer:** check for existence of ANIMATE class name in isOpening condition ([#4078](https://github.com/MaTriXy/material-components-web/issues/4078)) ([a4fd0a6](https://github.com/MaTriXy/material-components-web/commit/a4fd0a6419a197521ea00d7c873be44cb2e3da30))
* **drawer:** Destroy list in destroy method ([#3474](https://github.com/MaTriXy/material-components-web/issues/3474)) ([325317c](https://github.com/MaTriXy/material-components-web/commit/325317cbf927c1c4c65adcffd9dad1dbb190049b))
* **drawer:** Fix drawer content to have momentum scroll on iOS ([#3578](https://github.com/MaTriXy/material-components-web/issues/3578)) ([c65be9b](https://github.com/MaTriXy/material-components-web/commit/c65be9bafbf936e80690b6310ad3a05ad2453118))
* **drawer:** Fix exports and closure tests ([#3424](https://github.com/MaTriXy/material-components-web/issues/3424)) ([8d53068](https://github.com/MaTriXy/material-components-web/commit/8d53068fdca10d88e8e5f4d2f9d2a854ff656da1))
* **drawer:** Fix issue where drawer fires opened event twice. ([#4027](https://github.com/MaTriXy/material-components-web/issues/4027)) ([72ef4e8](https://github.com/MaTriXy/material-components-web/commit/72ef4e8d2eb078095ba28f5a8eabf9c7585cf4e6))
* **drawer:** Fix restore & release focus order when closing the drawer ([#4304](https://github.com/MaTriXy/material-components-web/issues/4304)) ([dffbcc1](https://github.com/MaTriXy/material-components-web/commit/dffbcc138bf61c19371291b4b55269ffdc887aba))
* **drawer:** link to the es6 component js file in screenshot spec ([#3696](https://github.com/MaTriXy/material-components-web/issues/3696)) ([8d96a72](https://github.com/MaTriXy/material-components-web/commit/8d96a727bae77f514a4184ae217472e1485ef204))
* **drawer:** Modal --open state class needs display: flex ([#3431](https://github.com/MaTriXy/material-components-web/issues/3431)) ([533a46f](https://github.com/MaTriXy/material-components-web/commit/533a46fea5a79763bb4c3acccdb130e73e8e5b57))
* **drawer:** Remove list item children to be included in click target. ([#3480](https://github.com/MaTriXy/material-components-web/issues/3480)) ([cc3ae2f](https://github.com/MaTriXy/material-components-web/commit/cc3ae2f99bc58a0712bfd38f1d4370ab19e46f50))
* **drawer:** Remove redundant style ([#3731](https://github.com/MaTriXy/material-components-web/issues/3731)) ([716da5a](https://github.com/MaTriXy/material-components-web/commit/716da5a1739c6122704a4efca1b26e606967f4cb))
* **drawer:** Remove unnecessary Closure annotation ([#3935](https://github.com/MaTriXy/material-components-web/issues/3935)) ([61128be](https://github.com/MaTriXy/material-components-web/commit/61128be345fbfda4d80e4c72753cd56b2e9eee51))
* **drawer:** Upgrade focus-trap version in drawer & dialog ([#4217](https://github.com/MaTriXy/material-components-web/issues/4217)) ([ea37b07](https://github.com/MaTriXy/material-components-web/commit/ea37b07d0387c43528bf3a231bfeee90b17dcd2c))
* **drawer:** Use parentNode DOM API when selecting scrim to make it work with Shadow DOM ([#4265](https://github.com/MaTriXy/material-components-web/issues/4265)) ([385a223](https://github.com/MaTriXy/material-components-web/commit/385a22307defde1663eb9dd4caacca152b1e90a8))
* **drawer:** Use rAF/setTimeout for opening class ([#3683](https://github.com/MaTriXy/material-components-web/issues/3683)) ([26a6981](https://github.com/MaTriXy/material-components-web/commit/26a6981e7ccaa82113e58fa88968577dde88d374))
* **fab:** Separate mixins for regular FAB and Extended FAB ([#4082](https://github.com/MaTriXy/material-components-web/issues/4082)) ([003e95f](https://github.com/MaTriXy/material-components-web/commit/003e95f8dff12a3319d2808c1ccad62521eed627))
* **feature-targeting:** prevent accidental nesting of mdc-feature-targets mixin ([#4281](https://github.com/MaTriXy/material-components-web/issues/4281)) ([3405bc4](https://github.com/MaTriXy/material-components-web/commit/3405bc4d915a2c120ae2aeeab4cc0ed3572b3447))
* **floating-label:** Add alternate tag ([#3993](https://github.com/MaTriXy/material-components-web/issues/3993)) ([6307071](https://github.com/MaTriXy/material-components-web/commit/63070716763f79c0b9a88c6a874072fb5621ea12))
* **floating-label:** Enforce text alignment ([#3684](https://github.com/MaTriXy/material-components-web/issues/3684)) ([551e641](https://github.com/MaTriXy/material-components-web/commit/551e64161d5247f1a31ae5d69da42787b406d15e))
* **icon-button:** remove unused ARIA_LABEL string from constants ([#3591](https://github.com/MaTriXy/material-components-web/issues/3591)) ([bce1724](https://github.com/MaTriXy/material-components-web/commit/bce17242635b8845aa38fb4f86bdcacd32c06838))
* **icon-button:** Remove unused styles, update docs, code cleanup ([#2957](https://github.com/MaTriXy/material-components-web/issues/2957)) ([32b5b9d](https://github.com/MaTriXy/material-components-web/commit/32b5b9d641dabd6f1e2529334f3cdc8a87001444))
* **infrastructure:** Rework goog.module positioning ([#3098](https://github.com/MaTriXy/material-components-web/issues/3098)) ([fbbf58a](https://github.com/MaTriXy/material-components-web/commit/fbbf58aefbf3214cd71863817cab8d1120372e3c))
* **infrastructure:** Update ff screenshot tests ([#3540](https://github.com/MaTriXy/material-components-web/issues/3540)) ([16007f1](https://github.com/MaTriXy/material-components-web/commit/16007f173be985947a0417b7fef574603fe3d6fb))
* **infrastructure:** update saucelabs windows 8 to windows 10 IE11 browser ([#3234](https://github.com/MaTriXy/material-components-web/issues/3234)) ([547a980](https://github.com/MaTriXy/material-components-web/commit/547a980c93cfb0d93ccd42bedb0090217345ffc9))
* **list:** Accept array of index for selectedIndex API ([#4124](https://github.com/MaTriXy/material-components-web/issues/4124)) ([be070a4](https://github.com/MaTriXy/material-components-web/commit/be070a41dad9e50b045dccdb1d2094b15624e554))
* **list:** add list to webpack js bundler ([#3244](https://github.com/MaTriXy/material-components-web/issues/3244)) ([b95d4e7](https://github.com/MaTriXy/material-components-web/commit/b95d4e7d2bb1c153159741f3990e0d569d944e2a))
* **list:** Add support for activated ([#3388](https://github.com/MaTriXy/material-components-web/issues/3388)) ([5590412](https://github.com/MaTriXy/material-components-web/commit/5590412d2c80225e7523440ba2b2bfad086986f4))
* **list:** Always call followHref regardless of single-selection mode ([#3595](https://github.com/MaTriXy/material-components-web/issues/3595)) ([b556724](https://github.com/MaTriXy/material-components-web/commit/b556724a368c23619db28562dfcf57b0ef2849b3))
* **list:** Change private getter method to public ([#3473](https://github.com/MaTriXy/material-components-web/issues/3473)) ([f57c731](https://github.com/MaTriXy/material-components-web/commit/f57c7318bd1cb9fd56206b7657a139ac225bb274))
* **list:** Fix font size and placement for avatar graphic ([#4021](https://github.com/MaTriXy/material-components-web/issues/4021)) ([5abe685](https://github.com/MaTriXy/material-components-web/commit/5abe685a52224b15aabf52e24281e25471f02544))
* **list:** Follow hrefs on keypresses on links ([#3407](https://github.com/MaTriXy/material-components-web/issues/3407)) ([e6d6deb](https://github.com/MaTriXy/material-components-web/commit/e6d6deb5c2f804b356e014208d835a28557bf05a))
* **list:** Peace out whitespace ([#3997](https://github.com/MaTriXy/material-components-web/issues/3997)) ([19b5152](https://github.com/MaTriXy/material-components-web/commit/19b515259c58a93fbc7f3aaaf6472b1e0efebbc7))
* **list:** Update ARIA attributes for radio/checkbox based list ([#4055](https://github.com/MaTriXy/material-components-web/issues/4055)) ([76b404e](https://github.com/MaTriXy/material-components-web/commit/76b404e176431ab42d27fd3bb8aa71bf09276a40))
* **list:** Update clickable elements selector ([#3312](https://github.com/MaTriXy/material-components-web/issues/3312)) ([c8ded0a](https://github.com/MaTriXy/material-components-web/commit/c8ded0a3103efd0880157df6aef88a3a25b6f823))
* **list:** Update default notifyAction impl to emit object ([#4356](https://github.com/MaTriXy/material-components-web/issues/4356)) ([ed1aeb2](https://github.com/MaTriXy/material-components-web/commit/ed1aeb2cf34430b04bd17a0e59ce07a15a699f1d)), closes [#4355](https://github.com/MaTriXy/material-components-web/issues/4355)
* **list:** Update single line list to ellipsis ([#3460](https://github.com/MaTriXy/material-components-web/issues/3460)) ([60cf6c5](https://github.com/MaTriXy/material-components-web/commit/60cf6c528d1938879c0fd048fd8bf31101620757))
* **menu:** Allow anchor links as menu list items ([#3680](https://github.com/MaTriXy/material-components-web/issues/3680)) ([d312271](https://github.com/MaTriXy/material-components-web/commit/d3122716b8c9e21f9ac5c0f40e346fe8a280b68d))
* **menu:** Increase specificity of selection group class ([#4172](https://github.com/MaTriXy/material-components-web/issues/4172)) ([1d919ef](https://github.com/MaTriXy/material-components-web/commit/1d919efdf9356ab857a6d289f61ed87ae8228b4e))
* **menu:** Prevent endless loop from unexpected markup ([#3489](https://github.com/MaTriXy/material-components-web/issues/3489)) ([5dea634](https://github.com/MaTriXy/material-components-web/commit/5dea63476cc4d08e700a2ad6e52cb05f3cc49a48))
* **menu:** Read index property from list item event detail ([#4368](https://github.com/MaTriXy/material-components-web/issues/4368)) ([5eb5a01](https://github.com/MaTriXy/material-components-web/commit/5eb5a0185ac5a7f0f4a1be844e7e9cff23b146e7)), closes [#4356](https://github.com/MaTriXy/material-components-web/issues/4356)
* **menu:** Remove max-width ([#3583](https://github.com/MaTriXy/material-components-web/issues/3583)) ([c44ca61](https://github.com/MaTriXy/material-components-web/commit/c44ca615721358ac22adfcf92a8f6893fe8e345f))
* **menu:** Update adapter to check for focus before calling ([#2880](https://github.com/MaTriXy/material-components-web/issues/2880)) ([1548230](https://github.com/MaTriXy/material-components-web/commit/1548230677925fc689d388c16e4fb77e117c9a89))
* **menu:** Update styles to match guidance ([#3455](https://github.com/MaTriXy/material-components-web/issues/3455)) ([5c01746](https://github.com/MaTriXy/material-components-web/commit/5c0174671d6cd4c50148115b030ba1f1773da703))
* **menu:** Updated menu to use list's custom event ([#4151](https://github.com/MaTriXy/material-components-web/issues/4151)) ([a4e08f1](https://github.com/MaTriXy/material-components-web/commit/a4e08f1c5be7ca6379514794cbdd7f535093ed45))
* **menu:** Vertically center the group icon ([#4862](https://github.com/MaTriXy/material-components-web/issues/4862)) ([c5738ed](https://github.com/MaTriXy/material-components-web/commit/c5738ed64e97cba5177377814bd838c6cfa03e3c))
* **menu-surface:** Fix absolute positioning for scrollX ([#3609](https://github.com/MaTriXy/material-components-web/issues/3609)) ([4074535](https://github.com/MaTriXy/material-components-web/commit/4074535983321b41a10c2f5b57c887f6b139e388))
* **menu-surface:** Fix interpolation in calc ([#3445](https://github.com/MaTriXy/material-components-web/issues/3445)) ([7f14c72](https://github.com/MaTriXy/material-components-web/commit/7f14c72dab1e8ad99449a653f497397d37ef0aff))
* **menu-surface:** Raise z-index over MDC Dialog ([#4185](https://github.com/MaTriXy/material-components-web/issues/4185)) ([fa6f219](https://github.com/MaTriXy/material-components-web/commit/fa6f219f429303fc435094d5ba31b1b510f6d566))
* **menu-surface:** Remove overflow hidden during menu-surface animation. ([#3358](https://github.com/MaTriXy/material-components-web/issues/3358)) ([951a3ae](https://github.com/MaTriXy/material-components-web/commit/951a3ae4d1284cf717345207426d48e210e2909a))
* **notched-outline:** Add alignment ([#3349](https://github.com/MaTriXy/material-components-web/issues/3349)) ([ee93c61](https://github.com/MaTriXy/material-components-web/commit/ee93c61176f080bdf1f2d55838e47e593f0e2528))
* **notched-outline:** Add noflip annotation ([#3994](https://github.com/MaTriXy/material-components-web/issues/3994)) ([c60d42b](https://github.com/MaTriXy/material-components-web/commit/c60d42ba8218ebff8a23b7723b2c2b3d3cea28d0))
* **notched-outline:** Fix label overflow ([#4171](https://github.com/MaTriXy/material-components-web/issues/4171)) ([145db1f](https://github.com/MaTriXy/material-components-web/commit/145db1fbf26a6463a22a9ac008cb10217f2a3a65))
* **notched-outline:** fix missing shape functions import ([#4224](https://github.com/MaTriXy/material-components-web/issues/4224)) ([96f663e](https://github.com/MaTriXy/material-components-web/commit/96f663e53e30522798f9a7959213d4887e9f3f05))
* **notched-outline:** Remove unused dependency from scss ([#3044](https://github.com/MaTriXy/material-components-web/issues/3044)) ([85ecf11](https://github.com/MaTriXy/material-components-web/commit/85ecf118677b15a34e2f632f13be387c8cc4c859))
* **package:** Add source-map files to npm releases ([#4206](https://github.com/MaTriXy/material-components-web/issues/4206)) ([9d6375b](https://github.com/MaTriXy/material-components-web/commit/9d6375b2402d28e2d9a19d5ac0935d8ade58c673))
* **radio:** Add missing `[@import](https://github.com/import)` for theme mixins; add screenshot tests ([#3285](https://github.com/MaTriXy/material-components-web/issues/3285)) ([0d73d06](https://github.com/MaTriXy/material-components-web/commit/0d73d06bc9a7cbc293b7456209af7394965cb0c1))
* **ripple:** Change default color from black to on-surface ([#3554](https://github.com/MaTriXy/material-components-web/issues/3554)) ([e203aa4](https://github.com/MaTriXy/material-components-web/commit/e203aa45973c74d251c685a4a081880c2e65c1df))
* **ripple:** Clean deactivation timer and CSS when interrupted ([#3529](https://github.com/MaTriXy/material-components-web/issues/3529)) ([2eda390](https://github.com/MaTriXy/material-components-web/commit/2eda390084f0cab8a64af430a7cbc501f354b156))
* **ripple:** Deactivate on contextmenu event ([#3759](https://github.com/MaTriXy/material-components-web/issues/3759)) ([4d76e3f](https://github.com/MaTriXy/material-components-web/commit/4d76e3f4584545d9997d0edef6e1bf83dc2c9944))
* **ripple:** Expose focus/blur handlers  ([#2905](https://github.com/MaTriXy/material-components-web/issues/2905)) ([31d81ad](https://github.com/MaTriXy/material-components-web/commit/31d81ad48aa5efdb4d12a9cc57cb3fed878181fa))
* **ripple:** Prevent ripple from getting cut out. ([#3521](https://github.com/MaTriXy/material-components-web/issues/3521)) ([a8008f4](https://github.com/MaTriXy/material-components-web/commit/a8008f4ad97b4e530b8b5e51f6782d37ecc54724))
* **ripple:** Register focus/blur handlers in IE ([#3294](https://github.com/MaTriXy/material-components-web/issues/3294)) ([1186f9b](https://github.com/MaTriXy/material-components-web/commit/1186f9b3af61e5b8d3a9cca9ef8a691f6d3b2992))
* **ripple:** Suppress before/after when color is transparent ([#4112](https://github.com/MaTriXy/material-components-web/issues/4112)) ([2e2b227](https://github.com/MaTriXy/material-components-web/commit/2e2b2274216760e2a43485bce38ebef75dcdb507))
* **ripple:** Transition background-color to avoid flashes ([#3693](https://github.com/MaTriXy/material-components-web/issues/3693)) ([cbc1f95](https://github.com/MaTriXy/material-components-web/commit/cbc1f959d8f2608e5e67af316a70f76751f8fede))
* **select:** add adapter ([#3233](https://github.com/MaTriXy/material-components-web/issues/3233)) ([43b3ac1](https://github.com/MaTriXy/material-components-web/commit/43b3ac142435e2d31f9935887372b41bbe958c45))
* **select:** Add missing exports ([#4129](https://github.com/MaTriXy/material-components-web/issues/4129)) ([dbc429a](https://github.com/MaTriXy/material-components-web/commit/dbc429a1d02fd0e70343480b9a0b9573d26078a5))
* **select:** Add missing mixin ([#3435](https://github.com/MaTriXy/material-components-web/issues/3435)) ([e654526](https://github.com/MaTriXy/material-components-web/commit/e654526794156e57a9751257fb511f0a5cec91e1))
* **select:** Disabled color and opacity ([#3513](https://github.com/MaTriXy/material-components-web/issues/3513)) ([74bf144](https://github.com/MaTriXy/material-components-web/commit/74bf14435972bc70fec89410dcde540d753b221b))
* **select:** Enhanced select doesn't wrap focus ([#4083](https://github.com/MaTriXy/material-components-web/issues/4083)) ([c640d50](https://github.com/MaTriXy/material-components-web/commit/c640d50758f109bc2a19cbc8203b10d4a11ac426))
* **select:** Fix dropdown color/opacity and options background ([#3553](https://github.com/MaTriXy/material-components-web/issues/3553)) ([3e26342](https://github.com/MaTriXy/material-components-web/commit/3e263427621cfc22e96713c478b2f73c57e89279))
* **select:** Fix outlined select not changing color without label ([#3433](https://github.com/MaTriXy/material-components-web/issues/3433)) ([a1c0930](https://github.com/MaTriXy/material-components-web/commit/a1c0930db786e544e673056c5d73c216ba589308))
* **select:** Only add line ripple listeners when line ripple is present ([#3470](https://github.com/MaTriXy/material-components-web/issues/3470)) ([453b5c5](https://github.com/MaTriXy/material-components-web/commit/453b5c5a6ae8c793c4c65b43f35088113d46f93d))
* **select:** reduce adapter apis not used in MDCReact and update events to new pattern ([#3204](https://github.com/MaTriXy/material-components-web/issues/3204)) ([e29742a](https://github.com/MaTriXy/material-components-web/commit/e29742abe2556b6b9a9b57a145d57c0d8ffd666d))
* **select:** Remove blue background in IE on focus ([#3497](https://github.com/MaTriXy/material-components-web/issues/3497)) ([1eb86cc](https://github.com/MaTriXy/material-components-web/commit/1eb86ccb1d5d27955670c433ba50d14fe972aaf4)), closes [#3496](https://github.com/MaTriXy/material-components-web/issues/3496)
* **select:** Remove style customization for native select > option ([#4089](https://github.com/MaTriXy/material-components-web/issues/4089)) ([379c522](https://github.com/MaTriXy/material-components-web/commit/379c522f412c497cc288a1dd87a76b2757fe5ce3))
* **select:** Set transform origin for line ripple ([#3432](https://github.com/MaTriXy/material-components-web/issues/3432)) ([0ff23e1](https://github.com/MaTriXy/material-components-web/commit/0ff23e11fb8b5dfcc0e2a9f3b649959672bb4bd7))
* **shape:** Add noflip comments, fix RTL for categories ([#4116](https://github.com/MaTriXy/material-components-web/issues/4116)) ([62054f8](https://github.com/MaTriXy/material-components-web/commit/62054f88fd355ceeef685844c783cafaa1cd4f6c))
* **shape:** Rename surface term with component. ([#3761](https://github.com/MaTriXy/material-components-web/issues/3761)) ([81bb919](https://github.com/MaTriXy/material-components-web/commit/81bb919e16b55251f989597ae20d48a6d71869e3))
* **slider:** Don't throw error when markup min is greater than default max ([#3315](https://github.com/MaTriXy/material-components-web/issues/3315)) ([5fe0c62](https://github.com/MaTriXy/material-components-web/commit/5fe0c6265f8401891d39267685fcfefa7cb3e84c)), closes [#2269](https://github.com/MaTriXy/material-components-web/issues/2269)
* **snackbar:** Allow variables to be customized ([#3335](https://github.com/MaTriXy/material-components-web/issues/3335)) ([215d0c6](https://github.com/MaTriXy/material-components-web/commit/215d0c6854b61347c77cb216a31fcc333ce52a07))
* **snackbar:** Doesn't close while other element is focused ([#2183](https://github.com/MaTriXy/material-components-web/issues/2183)) ([e161cc0](https://github.com/MaTriXy/material-components-web/commit/e161cc00614d841f3c5dc86178036ddf99cf416a))
* **snackbar:** Rename action/dismiss classes and revise docs/tests ([#4203](https://github.com/MaTriXy/material-components-web/issues/4203)) ([673dba2](https://github.com/MaTriXy/material-components-web/commit/673dba2b25246cb702a49b0e51bb8193d02ecc80))
* **tab-bar:** Early exit ([#3386](https://github.com/MaTriXy/material-components-web/issues/3386)) ([f0ebfea](https://github.com/MaTriXy/material-components-web/commit/f0ebfea85844b915ac07554df31f11eea90fd29e))
* **tab-bar:** Move activateTab to adapter ([#3394](https://github.com/MaTriXy/material-components-web/issues/3394)) ([5007604](https://github.com/MaTriXy/material-components-web/commit/50076040bf7adfe2b7d8a4f727035ea18cd32f8b))
* **tab-bar:** Remove trailing comma from function. ([#3574](https://github.com/MaTriXy/material-components-web/issues/3574)) ([e201d24](https://github.com/MaTriXy/material-components-web/commit/e201d2474ada1e4f45a5171bf633c4ef34f697a2))
* **text-field:** Adjust the baseline of text field's helper text to match spec ([#3069](https://github.com/MaTriXy/material-components-web/issues/3069)) ([36acc28](https://github.com/MaTriXy/material-components-web/commit/36acc280a0ce248c2533c93cd39722b768464a46))
* **text-field:** Don't move caret when value has not changed ([#4160](https://github.com/MaTriXy/material-components-web/issues/4160)) ([d55ca11](https://github.com/MaTriXy/material-components-web/commit/d55ca11c7dfc22c8318aabb67ecd015502d97e98))
* **text-field:** Fix label shake bug. Update invalid screenshots to show required star. ([#3338](https://github.com/MaTriXy/material-components-web/issues/3338)) ([1245573](https://github.com/MaTriXy/material-components-web/commit/1245573ea4350682b6548af89a43171302624e63))
* **text-field:** Fix outlined disabled text color to match filled variant ([#3544](https://github.com/MaTriXy/material-components-web/issues/3544)) ([0da74d9](https://github.com/MaTriXy/material-components-web/commit/0da74d97ec2f5a0990aa9d439268aa4a42f4debc))
* **text-field:** Fix textarea-shape-radius mixin behavior for input ([#3982](https://github.com/MaTriXy/material-components-web/issues/3982)) ([1167289](https://github.com/MaTriXy/material-components-web/commit/1167289b9cb84f042e1437c0aa1a8daecade0f00))
* **text-field:** Fix textfield placeholder & outline stroke animation ([#4310](https://github.com/MaTriXy/material-components-web/issues/4310)) ([58c3b4d](https://github.com/MaTriXy/material-components-web/commit/58c3b4d2fbf4e245f7494f28f71b8d1105af963f))
* **text-field:** Hide extraneous border in FF in HC mode. ([#2931](https://github.com/MaTriXy/material-components-web/issues/2931)) ([418868a](https://github.com/MaTriXy/material-components-web/commit/418868af360cda223d6e7664e30a7426b1410cf3))
* **text-field:** Input position and textarea size ([#3321](https://github.com/MaTriXy/material-components-web/issues/3321)) ([5160241](https://github.com/MaTriXy/material-components-web/commit/51602411be29166dd10aec9d6aea6bac17756119)), closes [#2826](https://github.com/MaTriXy/material-components-web/issues/2826)
* **text-field:** Reset z-index property of chrome autofill box ([#4232](https://github.com/MaTriXy/material-components-web/issues/4232)) ([e718cb2](https://github.com/MaTriXy/material-components-web/commit/e718cb2ba8c33fa9b8af5b5d73097db9c02b1a07))
* **text-field:** Restrict resize to vertical for full width text area ([#4167](https://github.com/MaTriXy/material-components-web/issues/4167)) ([77a2bd4](https://github.com/MaTriXy/material-components-web/commit/77a2bd4cd9815023e2e97b91fbff422e58022b68))
* **text-field:** Send client position to line ripple for touch events ([#4084](https://github.com/MaTriXy/material-components-web/issues/4084)) ([95c0a98](https://github.com/MaTriXy/material-components-web/commit/95c0a98bad2ac6f4efa02c0e3b10fae75c32249e))
* **text-field:** Set the margin for text-area helper text ([#3290](https://github.com/MaTriXy/material-components-web/issues/3290)) ([64cc846](https://github.com/MaTriXy/material-components-web/commit/64cc8462c167e47c6292e08cbcb076b75048f9f8))
* **text-field:** Stop emitting unused CSS in Text Field & Select ([#3293](https://github.com/MaTriXy/material-components-web/issues/3293)) ([fe0b7bc](https://github.com/MaTriXy/material-components-web/commit/fe0b7bc257a2ba3f704fd6b9c8c54a16e1c169ed))
* **text-field:** Update caret color to match spec ([#2894](https://github.com/MaTriXy/material-components-web/issues/2894)) ([88fd0bf](https://github.com/MaTriXy/material-components-web/commit/88fd0bfa765b76663e08fa6626212b7c38b525d9))
* **text-field:** Update closure type for rippleFactory ([#4324](https://github.com/MaTriXy/material-components-web/issues/4324)) ([7a4a707](https://github.com/MaTriXy/material-components-web/commit/7a4a707d0576758f554938fcfa00e427cdd9e88e))
* **text-field:** Update to match spec ([#3397](https://github.com/MaTriXy/material-components-web/issues/3397)) ([e34b251](https://github.com/MaTriXy/material-components-web/commit/e34b251da8caf9a83c34d7c2cce54ddaca176616))
* **textfield:** move notched outline/label before input ([9e2f6c4](https://github.com/MaTriXy/material-components-web/commit/9e2f6c45016b1ccc665a271dc59134d32916123d))
* **textfield:** remove Chrome icons for date types ([4951e76](https://github.com/MaTriXy/material-components-web/commit/4951e7651ffbd99b382948e48306a23d2fd74fb1))
* **textfield:** Use theme mixin for asterisk color ([#3952](https://github.com/MaTriXy/material-components-web/issues/3952)) ([981b37e](https://github.com/MaTriXy/material-components-web/commit/981b37e8c6557213b162412502547a13eef769ce))
* **theme:** Allow CSS variables to be passed to mdc-theme-prop ([#3086](https://github.com/MaTriXy/material-components-web/issues/3086)) ([b47fe7d](https://github.com/MaTriXy/material-components-web/commit/b47fe7d6724a63e50bc1b8097f00deed5b227b1f))
* **theme:** Declare error variables as !default ([#3531](https://github.com/MaTriXy/material-components-web/issues/3531)) ([eebdcdc](https://github.com/MaTriXy/material-components-web/commit/eebdcdc9186747dd22f936639600f254dfbf2254))
* **theme:** do not throw error when setting custom props and null ([85a5272](https://github.com/MaTriXy/material-components-web/commit/85a5272dfeb7ad100598d480dec76b60679485f5))
* **theme:** Make $mdc-theme-on-error dark if $mdc-theme-error is light ([#3678](https://github.com/MaTriXy/material-components-web/issues/3678)) ([5b1348c](https://github.com/MaTriXy/material-components-web/commit/5b1348cee8302f12d552e8612d911a202be49ad5))
* **theme:** variable overrides not working with @use/with ([2d72f36](https://github.com/MaTriXy/material-components-web/commit/2d72f365991f17e21b34be523aef3fa32b2b2fdb))
* **top-app-bar:** Move scroll target initialization; improve test ([#4106](https://github.com/MaTriXy/material-components-web/issues/4106)) ([f799659](https://github.com/MaTriXy/material-components-web/commit/f799659ceefb2496461648bcec4d97431f6bb9a6))
* **top-app-bar:** Use superclass properties without trailing underscores ([863ac1b](https://github.com/MaTriXy/material-components-web/commit/863ac1b0f1723883565ca813d56bba0a1c8a832f))
* **touch-target:** Add missing dependency - touch target to com… ([#5098](https://github.com/MaTriXy/material-components-web/issues/5098)) ([9306bd0](https://github.com/MaTriXy/material-components-web/commit/9306bd0834b91af311c3bac1cb430bc0b0c9d20e))
* **typography:** Add alternate tag for line-height ([#3992](https://github.com/MaTriXy/material-components-web/issues/3992)) ([f6acae8](https://github.com/MaTriXy/material-components-web/commit/f6acae84aa3c018dd2bdb006aeed33268f64d201))
* **typography:** change $styles font-size to a Number ([6d1ea97](https://github.com/MaTriXy/material-components-web/commit/6d1ea9761de927c1653c621444e00172f74d76c7))
* **typography:** Updated demo to use div tag instead of line tag. ([#3298](https://github.com/MaTriXy/material-components-web/issues/3298)) ([3c250b6](https://github.com/MaTriXy/material-components-web/commit/3c250b6fbad4421f767ceb9a20cafaa11dda3b39))
* hot-patching closure annotations. ([#3024](https://github.com/MaTriXy/material-components-web/issues/3024)) ([d5b95ab](https://github.com/MaTriXy/material-components-web/commit/d5b95ab951afcc88368204fb07abb5107a3cde84))


### Build System

* set AMD module module names within UMD bundles ([#7233](https://github.com/MaTriXy/material-components-web/issues/7233)) ([9808de0](https://github.com/MaTriXy/material-components-web/commit/9808de09310368c6352a0d40db84a802069d743d))


### chore

* **list:** Remove all references to Element from MDCListAdapter ([#3398](https://github.com/MaTriXy/material-components-web/issues/3398)) ([53f42b9](https://github.com/MaTriXy/material-components-web/commit/53f42b9e73c5523e95128f580e0b745bd4ce2bc9))
* **tab:** Move computeIndicatorClientRect logic out of the foundation ([#3367](https://github.com/MaTriXy/material-components-web/issues/3367)) ([9cac7c0](https://github.com/MaTriXy/material-components-web/commit/9cac7c0e9671cbe93b861cb22b34045250f6959e)), closes [#3341](https://github.com/MaTriXy/material-components-web/issues/3341)


### Code Refactoring

* **animation:** Remove `transformStyleProperties` export ([#4453](https://github.com/MaTriXy/material-components-web/issues/4453)) ([aa44991](https://github.com/MaTriXy/material-components-web/commit/aa4499148b39d1e7a77d68822047df536946fdb6)), closes [/github.com/material-components/material-components-web/pull/4407#discussion_r258668567](https://github.com//github.com/material-components/material-components-web/pull/4407/issues/discussion_r258668567)
* **button:** Add ripple target as an inner element. ([#4890](https://github.com/MaTriXy/material-components-web/issues/4890)) ([dffefe6](https://github.com/MaTriXy/material-components-web/commit/dffefe6b20da243c1e8b85506949bc37c10b01a9))
* **checkbox:** Deprecated old checkbox theme mixin ([22d29cb](https://github.com/MaTriXy/material-components-web/commit/22d29cbb4e7847ae56bf923d70508d1b164c1af6))
* **chips:** Register handlers in component instead of foundation ([#3146](https://github.com/MaTriXy/material-components-web/issues/3146)) ([36e2755](https://github.com/MaTriXy/material-components-web/commit/36e27557bb3ed444c2eba1e1d7fd1095e33c5887))
* **circular-progress:** move all sizing params from CSS to markup ([58ce529](https://github.com/MaTriXy/material-components-web/commit/58ce529ccc29d3b172c1e774c70424eb54aac5dc))
* **dialog:** Split dialog Foundation#handleInteraction into #handleClick/#handleKeydown. ([#4655](https://github.com/MaTriXy/material-components-web/issues/4655)) ([36d516a](https://github.com/MaTriXy/material-components-web/commit/36d516a9a25a676a9aeb7fc052fce2c3709b31ba))
* **dialog:** Split dialog Foundation#handleInteraction into #handleClick/#handleKeydown. ([#4655](https://github.com/MaTriXy/material-components-web/issues/4655)) ([d650390](https://github.com/MaTriXy/material-components-web/commit/d6503909d93c2a8c686dbb1215e578f7c8c5cc81))
* **fab:** Deprecate legacy Fab theme mixins ([83bdd02](https://github.com/MaTriXy/material-components-web/commit/83bdd022246c1699de71346d5c162e1ded5a0836))
* **grid-list:** Deprecate component ([#5499](https://github.com/MaTriXy/material-components-web/issues/5499)) ([cf33f11](https://github.com/MaTriXy/material-components-web/commit/cf33f113dd89bbfb2873c9ce3fa1525076bfd4ec))
* **iconbutton:** Forward only theme mixins from MDC icon button index module. ([0a90693](https://github.com/MaTriXy/material-components-web/commit/0a906930027e2b55054be08aa8ce0d48dec8c25b))
* **iconbutton:** Move ripple target to inner element ([33c9a73](https://github.com/MaTriXy/material-components-web/commit/33c9a737af75f30f434565e98ada51b335495f0a))
* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([98b8434](https://github.com/MaTriXy/material-components-web/commit/98b843417ef6c0a10460532a37df389b0c7e936f))
* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([9372e49](https://github.com/MaTriXy/material-components-web/commit/9372e493954585c939f341486d0361efb87da806))
* **mdc-fab:** Move Ripple to inner Element. ([#4997](https://github.com/MaTriXy/material-components-web/issues/4997)) ([85b33b5](https://github.com/MaTriXy/material-components-web/commit/85b33b50eb1757656697bc04a44dfd0eb635358d))
* **notched-outline:** Refactor notched outline to use 3 divs ([#4035](https://github.com/MaTriXy/material-components-web/issues/4035)) ([9741233](https://github.com/MaTriXy/material-components-web/commit/974123325e427cb5878ab337111d9fa84abd455d))
* **radio:** forward only theme mixins from MDC radio index module ([72258f8](https://github.com/MaTriXy/material-components-web/commit/72258f89870242ba62c0ce25db680fdecb9640bc))
* **select:** consolidate state theming to single mixins ([e8bf5b2](https://github.com/MaTriXy/material-components-web/commit/e8bf5b2ac6c89778fa38791979e4be941e28db1c))
* **select:** Fix alignment issues, upgrade anchor to interactive element ([28d10a9](https://github.com/MaTriXy/material-components-web/commit/28d10a96e1d5e5762d5a056ac805070e9fb6a4e1)), closes [#5428](https://github.com/MaTriXy/material-components-web/issues/5428)
* **select:** Refactor select ([#5113](https://github.com/MaTriXy/material-components-web/issues/5113)) ([db7560e](https://github.com/MaTriXy/material-components-web/commit/db7560ee678ef4738690152d8b23c491030fc4a6))
* **slider:** Functional slider tick visuals with css background ([#4756](https://github.com/MaTriXy/material-components-web/issues/4756)) ([8f851d9](https://github.com/MaTriXy/material-components-web/commit/8f851d9ed2f75dc8b8956d15b3bb2619e59fa8a9))
* **snackbar:** Update a11y structure ([c60449b](https://github.com/MaTriXy/material-components-web/commit/c60449bc8a967e14436bec9471df99678a78515a))
* **text-field:** Change text-field--box to be the new default ([#2859](https://github.com/MaTriXy/material-components-web/issues/2859)) ([01b6be7](https://github.com/MaTriXy/material-components-web/commit/01b6be7c610bc16f4cdb7445a110997c7d4fd29c))
* **theme:** move CSS declarations to utility mixin ([96a6405](https://github.com/MaTriXy/material-components-web/commit/96a6405345ea1e1a7083bd08f8610384231d6607))
* **theme:** Rename validate-keys() to validate-theme() ([2fb068f](https://github.com/MaTriXy/material-components-web/commit/2fb068fb0f7a1b0e038ede3a2ab27a972e5b2ee4))
* **tooltip:** Moved the anchor element blur event listener from the component to within the foundation. ([0b4a4b2](https://github.com/MaTriXy/material-components-web/commit/0b4a4b2ebe245f2382cb08bbbc34e7ffb4f43763))
* **typography:** Rename typography Sass function from pxToRem() to px-to-rem() ([8f0a11e](https://github.com/MaTriXy/material-components-web/commit/8f0a11e32895f998c326ab4a10601a2e4d5e18db))
* migrate to the Sass module system ([#5453](https://github.com/MaTriXy/material-components-web/issues/5453)) ([faa9af3](https://github.com/MaTriXy/material-components-web/commit/faa9af310d1a18ec2c183830c84eb14d0492feab))
* Remove MDC theme's deep-get, used sass:map's get API instead. ([37fbae1](https://github.com/MaTriXy/material-components-web/commit/37fbae10d6fb993c0ea866959fb5564c052002cc))
* **top-app-bar:** Remove [de]registerEventHandler methods from adapters ([#4701](https://github.com/MaTriXy/material-components-web/issues/4701)) ([34bba89](https://github.com/MaTriXy/material-components-web/commit/34bba89a2d355fea8c01cf5c671a5fedfdad7b53))
* **top-app-bar:** Remove [de]registerEventHandler methods from adapters ([#4701](https://github.com/MaTriXy/material-components-web/issues/4701)) ([d8fe135](https://github.com/MaTriXy/material-components-web/commit/d8fe135160502c5755ccdf573d57a4a3b50e7d47))
* **touchtarget:** Rename mdc-touch-target-component => mdc… ([#5245](https://github.com/MaTriXy/material-components-web/issues/5245)) ([afe0dd1](https://github.com/MaTriXy/material-components-web/commit/afe0dd1bc240a7a88d76b0a3bf1a36044527babd))
* Swap MDCTopAppBar Sass Variable Word Order ([#4498](https://github.com/MaTriXy/material-components-web/issues/4498)) ([e851bae](https://github.com/MaTriXy/material-components-web/commit/e851bae0f69e17f4f7a627e82550cfdad33b930b))


### Documentation

* **select:** update markup to include new selectedText container ([47b500a](https://github.com/MaTriXy/material-components-web/commit/47b500a6cf888458b371734698b366fe2b4c3230))


### Features

* **banner:** Add disableAutoClose params for both banner actions to prevent the banner buttons from automatically closing the banner. Add adapter #notifyActionClicked method. ([b094eaa](https://github.com/MaTriXy/material-components-web/commit/b094eaa4e7a69132eb09f7b9d6c1d429a3f702a0))
* **banner:** Add Theming API support for graphic color and background color ([a0b8a90](https://github.com/MaTriXy/material-components-web/commit/a0b8a90c08a471b845dccc8a471bdd9650f61510))
* **banner:** Add Theming API support for max width and z-index ([e50b478](https://github.com/MaTriXy/material-components-web/commit/e50b478eb6ce6d54f0487a86572a20c645fac6c2))
* **banner:** Updating `theme-styles` mixin to emit custom properties. ([a6e1c07](https://github.com/MaTriXy/material-components-web/commit/a6e1c07025c66d0d29ac4c66584474a336b5ef26))
* **base:** add MDCObserverFoundation class ([33e6f50](https://github.com/MaTriXy/material-components-web/commit/33e6f50e915d5f2b70076fd0eb0e0d6654acba0c))
* **button:** add custom props to outlined button theme-styles ([bf405d2](https://github.com/MaTriXy/material-components-web/commit/bf405d22ae54eef77bbe437228540900aad2f0e0))
* **button:** add custom props to protected button theme-styles ([4ca11fe](https://github.com/MaTriXy/material-components-web/commit/4ca11fe76395824dff6b3e35d954af817ace1591))
* **button:** add custom props to text button theme-styles ([3dd6110](https://github.com/MaTriXy/material-components-web/commit/3dd61109132cf17b5a92a941ecc0f03b0a1cc8d5))
* **button:** add missing transitions to box-shadow/border ([3b92903](https://github.com/MaTriXy/material-components-web/commit/3b9290351308626b4699e2cbdaeb4dc7f04ce1d9))
* **button:** add static-styles-without-ripple for MWC consumption ([f4241a4](https://github.com/MaTriXy/material-components-web/commit/f4241a42a49d130fcf5b5a9df2239276628a85f1))
* **button:** add theme mixin that emits custom properties instead ([4c40586](https://github.com/MaTriXy/material-components-web/commit/4c405863bde72948dd131b07847b798cd8669764))
* **button:** add typography & state layer keys to theming API ([068fd50](https://github.com/MaTriXy/material-components-web/commit/068fd5028031778ada1f9f8469ac62ed60c9e7ef))
* **button:** consolidate states into button mixins ([637d15d](https://github.com/MaTriXy/material-components-web/commit/637d15da60919641e5571f280562c4fb3491c8f0))
* **button:** emit custom properties fill button theme-styles ([a80c8b2](https://github.com/MaTriXy/material-components-web/commit/a80c8b2c263b4f69a9df57e9837f7cb4ca438428))
* **button:** employ elevation token resolvers in theming API ([ebb5c73](https://github.com/MaTriXy/material-components-web/commit/ebb5c73bb87f1098d7e300372a811968a2d6c9f0))
* **button:** Introduced a new token: `"keep-touch-target"` to the `theme` mixin. ([21d1196](https://github.com/MaTriXy/material-components-web/commit/21d1196a7cae2760582c1cefb64e418e99f7d9b2))
* **button:** move icon-size to theming API ([85e9a6a](https://github.com/MaTriXy/material-components-web/commit/85e9a6ac3ca1c9395d0d955326c3c1a7c3fe1a04))
* **button:** resolve elevation keys in theme mixin ([843342f](https://github.com/MaTriXy/material-components-web/commit/843342f99a2f76895fedb1ad1b2ff88a96b3fd7d))
* **button:** Ripple styles do not update on hover for disabled buttons. ([bf86521](https://github.com/MaTriXy/material-components-web/commit/bf86521f45b74c35f2f443dfb41a0c8361b5cf2c))
* **button:** Support state-layer-color theming for buttons and icon-buttons ([127a44b](https://github.com/MaTriXy/material-components-web/commit/127a44b284698c40533b2e52cd0311ec689aa026))
* **button:** thread state keys through theme config ([05f2496](https://github.com/MaTriXy/material-components-web/commit/05f249666dff2bae35a1a6c1e7a5ed89eb193213))
* **checkbox:** Support state-layer-color theming for GM2 checkboxes ([9cec940](https://github.com/MaTriXy/material-components-web/commit/9cec9409719681ad4e33b7369fb402f7e4b787b1))
* **chips:** Expose "action" component ([03d34bb](https://github.com/MaTriXy/material-components-web/commit/03d34bbad14df501f5faf9d03e62c0727ef6f7da))
* **chips:** Expose "chip" component ([cbc57c6](https://github.com/MaTriXy/material-components-web/commit/cbc57c600f972ec88098d7ad9c4763f57dce0eb4))
* **chips:** Make light-theme tokens public ([51311e6](https://github.com/MaTriXy/material-components-web/commit/51311e69ec61d62c214e0020fb856c39919ee657))
* **chips:** Start deprecation of chip ([e683bdf](https://github.com/MaTriXy/material-components-web/commit/e683bdf4a0f6642b87f099b51425898dd4a1b644))
* **chips:** Start deprecation of chip root directory ([73a2271](https://github.com/MaTriXy/material-components-web/commit/73a227194d7c0caf305329f1a8b22eb801a6114b))
* **chips:** Start deprecation of chip set ([148e8cf](https://github.com/MaTriXy/material-components-web/commit/148e8cfccac563305b9fa6fd4a6e8602620d6426))
* **chips:** Start deprecation of chip trailing action ([9eeb35c](https://github.com/MaTriXy/material-components-web/commit/9eeb35c384c78a65215bf8885d5ebb5fb1592cd9))
* **chips:** Support presentational actions ([8c68530](https://github.com/MaTriXy/material-components-web/commit/8c685301d66ac6c8bc59b6b12930efd23804cce3))
* **datatable:** Expose `$custom-property-prefix` for internal usage ([cfd6949](https://github.com/MaTriXy/material-components-web/commit/cfd69490f088d578e2a9a6d06d386212e04048bd))
* **datatable:** Use generated tokens for Theming API ([bb77510](https://github.com/MaTriXy/material-components-web/commit/bb7751002a9f5c35137425219afb38c88d0bacc3))
* **datepicker:** datepicker textfield theming api ([a86d36f](https://github.com/MaTriXy/material-components-web/commit/a86d36fd2ac987f5a7ca160470964ff58b198300))
* **datepicker, select, textfield:** Support customizing label size on these components. ([c0d21ec](https://github.com/MaTriXy/material-components-web/commit/c0d21ecc9704bea1cb7c8cd83c1c6e2971f1d01b))
* **dialog:** Add `z-indez` token to dialog theme styles mixin ([93fc524](https://github.com/MaTriXy/material-components-web/commit/93fc524b7889f5789096c9be8799ed5b619aed43))
* **dialog:** Add a chaining class that suppresses scrim animations. ([819498d](https://github.com/MaTriXy/material-components-web/commit/819498d8c9bd8c5c72d2f7b12ec082795b6628d1))
* **dialog:** Adding `resize` and `orientationchange` event handlers into `MDCDialogFoundation`. ([1e06534](https://github.com/MaTriXy/material-components-web/commit/1e06534774df290b9a29210ee3bcf57515da6e43))
* **dialog:** Adding container-surface-tint as supported token for theme-API. ([446734f](https://github.com/MaTriXy/material-components-web/commit/446734f27bf1f7eadbf9d30c248649f46dd52cda))
* **dialog:** Adding styling for scroll bar dividers, and adding logic to show said dividers only when content is scrolled "behind" the header or footer of the dialog. ([e383944](https://github.com/MaTriXy/material-components-web/commit/e383944e9792ea1971c7814e0e63e2e00f99a468))
* **dialog:** Adds support for "surface-scrim" over full-screen dialogs. This prevents a "double scrim" from appearing when showing a secondary dialog over a full-screen dialog on larger screens. ([cddb035](https://github.com/MaTriXy/material-components-web/commit/cddb0355362acb031da308f98283f9d4ad9a2c84))
* **dialog:** Separate static styles from dialog core-styles mixin ([43d2eed](https://github.com/MaTriXy/material-components-web/commit/43d2eed2a908bae0d747b1ce4459b38cbd68c94a))
* **dom:** add forced-colors-mode mixin ([8416fb9](https://github.com/MaTriXy/material-components-web/commit/8416fb9195afcba61494bae1206dd1503dffb140))
* **dom:** add option to skip restoring focus on release focus ([5c0ab74](https://github.com/MaTriXy/material-components-web/commit/5c0ab74019c6a1925ee8ef7946d8df6d9494bf88))
* **elevation:** Create elevation resolver mixin ([5dfec7a](https://github.com/MaTriXy/material-components-web/commit/5dfec7a1445efb45a7fb4d96ce037cafab205f30))
* **elevation:** Create resolver function ([c18b592](https://github.com/MaTriXy/material-components-web/commit/c18b5925be3041e774b19f5f6f53f7d3a45d2240))
* **elevation:** Simplify box-shadow custom property support ([de48eff](https://github.com/MaTriXy/material-components-web/commit/de48eff0d803b4e6c93834904e486cfea47bb03a))
* **elevation:** Support custom properties in resolver ([07a7375](https://github.com/MaTriXy/material-components-web/commit/07a73750c0ebc1d05e19681c6f072cd5cceddfb6))
* **fab:** Add theming API to Extended FABs ([f19c86d](https://github.com/MaTriXy/material-components-web/commit/f19c86d13447d984b13b0e1d7e9651e498d8de04))
* **fab:** Added `$focus-outline-width` param to extended-padding() FAB mixin ([8ecd7c9](https://github.com/MaTriXy/material-components-web/commit/8ecd7c9a93c5b885fad9a1e6fd8d17da77c05360))
* **fab:** Added focus outline theme keys to FAB theme mixin ([d6d8d04](https://github.com/MaTriXy/material-components-web/commit/d6d8d04768f9904488a6814ec47a251a03313627))
* **fab:** Added theme mixin to primary FAB variant. ([f19bbc4](https://github.com/MaTriXy/material-components-web/commit/f19bbc4af6493f642dc4b5b45a2dc0083fa293f0))
* **fab:** border custom prop support & add CPs for padding ([a6b3101](https://github.com/MaTriXy/material-components-web/commit/a6b3101fb7641daab20db735b70421311534083b))
* **fab:** Make extended-light-theme tokens public ([736b7fd](https://github.com/MaTriXy/material-components-web/commit/736b7fda40fce0e45eb95ca28df7ae9a7426b365))
* **fab:** Make light-theme tokens public ([b281a40](https://github.com/MaTriXy/material-components-web/commit/b281a409a8d63105dcd7b00dd8cd4a3e274e3495))
* **fab:** Use elevation resolvers ([6e9fc4a](https://github.com/MaTriXy/material-components-web/commit/6e9fc4a423a4657cc5d718aaf13d360c3bd27709))
* **fab:** Use elevation resolvers in custom property themes ([3f691ec](https://github.com/MaTriXy/material-components-web/commit/3f691eccf61489d40e49bdf9f149b1591168c828))
* **fix:** Fix divider layout in right-to-left locales. ([f524626](https://github.com/MaTriXy/material-components-web/commit/f5246264d139124f6abf2cf5e9f8ca98762eb0f7))
* **floatinglabel:** Extract `static-styles` mixin ([419b23c](https://github.com/MaTriXy/material-components-web/commit/419b23cc64946c0df1986986872e0faa58c3e817))
* **floatinglabel:** Extract `theme-styles` mixin ([87809c7](https://github.com/MaTriXy/material-components-web/commit/87809c7103e24f1988763c1103fde000f413c4df))
* **focus:** Remove `focus-ring.theme-component` and `focus-ring.theme-component-derived` mixins. ([43f5323](https://github.com/MaTriXy/material-components-web/commit/43f5323bc078a4ed7df651a0170973194dd9031d))
* **focus ring:** BREAKING_CHANGE Renaming focus-ring files in preparation for splitting focus-ring into two variants. One with an outward entrance animation, and one with an inward animation. ([e8912fd](https://github.com/MaTriXy/material-components-web/commit/e8912fd3741e891a71a19b7370fa922358bdd278))
* **focus ring:** Defining styles for focus ring variant that animates inwards. ([16fbd30](https://github.com/MaTriXy/material-components-web/commit/16fbd30ffe8176e7a049663782c95456eaa95825))
* **focus-ring:** Add RTL support to focus ring mixin. ([65c10a6](https://github.com/MaTriXy/material-components-web/commit/65c10a622f0c2aee07daeccb7fa66109ba43db98))
* **focus-ring:** add Sass mixin for testing ([6a4b3f8](https://github.com/MaTriXy/material-components-web/commit/6a4b3f834d4f512a68e46f6fe56c4e52bc737004))
* **focus-ring:** Added a SASS function to help more easily mold the focus ring around its corresponding component's shape. ([32d8a96](https://github.com/MaTriXy/material-components-web/commit/32d8a96486823b6dfe077278114c12aed2a14bf5))
* **focus-ring:** Adds animation for focus-ring. ([c492898](https://github.com/MaTriXy/material-components-web/commit/c492898c238efd7a46476f4c0181e65bbbe04778))
* **focus-ring:** support variable shapes in outward variant ([311ab4d](https://github.com/MaTriXy/material-components-web/commit/311ab4d4aa4367ee99d505b89c1550cce81345e4))
* **focus-ring:** Update $ring-radius to support list type values  so a focus ring can follow custom shapes ([311f29a](https://github.com/MaTriXy/material-components-web/commit/311f29a60e0008ea8480d5fa418e570a96b6e694))
* **focusring:** Extra bottom offset for inward focus ring ([6fcd8d4](https://github.com/MaTriXy/material-components-web/commit/6fcd8d41839a069202e48f7dace96739ad21d078))
* **formfield:** Add `mdc-label` class to `<label>` ([55093ee](https://github.com/MaTriXy/material-components-web/commit/55093ee1e347fc68360a7fa1b45e1cc7f80cc683))
* **formfield:** Add `theme` mixin ([ed7e82d](https://github.com/MaTriXy/material-components-web/commit/ed7e82dedcea18db05621abd0a44a3c002cb65e8))
* **formfield:** Extract `static-styles` mixin ([d441d2a](https://github.com/MaTriXy/material-components-web/commit/d441d2a2ac5a4a69db1fd867a6bf959b1f7492cd))
* **formfield:** Extract `theme-styles` mixin ([48d3001](https://github.com/MaTriXy/material-components-web/commit/48d30012d6605a3038d912d455b98a5f528c2760))
* **iconbutton:** Add support for increased touch target to icon button. ([f43af56](https://github.com/MaTriXy/material-components-web/commit/f43af5633f08e8080daed2e976771448d3effadb))
* **linearprogress:** Add `bar-and-track-height` token ([51f9c0c](https://github.com/MaTriXy/material-components-web/commit/51f9c0c28888cc20bcfd982e3c3ee6d8701b276c))
* **linearprogress:** Implement `track-shape` token ([90291f2](https://github.com/MaTriXy/material-components-web/commit/90291f2e27c48df2958bdf5fd1854b79f032cf96))
* **linearprogress:** Implement separate `track-height` and `active-indicator-height` tokens ([3b5b55e](https://github.com/MaTriXy/material-components-web/commit/3b5b55e31a3f69bc1b4f380f57b9276bfb2ad4a8))
* **lineripple:** Extract `static-styles` mixin ([112715d](https://github.com/MaTriXy/material-components-web/commit/112715df5ae369f78b6ef12fe4aa88debb451ef2))
* **lineripple:** Extract `theme-styles` mixin ([1c8013f](https://github.com/MaTriXy/material-components-web/commit/1c8013f4e7f2b10ce1473177ec0f377da4592295))
* **list:** Add "deprecated" aliases for old list mixins / variables. ([f9cac96](https://github.com/MaTriXy/material-components-web/commit/f9cac96cc2ad0422d73140a65dcffc5e4e8ec519))
* **list:** Add public #getFocusedItemIndex to foundation. Also add a `forceUpdate` option to #setSelectedIndex that forces a UI update of the selected item. ([5d06051](https://github.com/MaTriXy/material-components-web/commit/5d060518804437aa1ae3152562f1bb78b1af4aa6))
* **list:** Add support for list-item-selected-container-color and list-item-selected-trailing-icon-color tokens. ([ece3e8d](https://github.com/MaTriXy/material-components-web/commit/ece3e8d2155abd93bc1f9bdcf2dddea9e6eaab56))
* **list:** Changing default value of `areDisabledItemsFocusable` to false. ([65c4116](https://github.com/MaTriXy/material-components-web/commit/65c411674c70291e64bf0deaca88f8b68586ba82))
* **list:** Fixes focus behavior on disabled list items when `areDisabledItemsFocusable` is set to `false`. ([2aa8050](https://github.com/MaTriXy/material-components-web/commit/2aa8050b46b7b170ab9ecc2a1fe9686ac40d79cc))
* **list:** Removes ripple styling on disabled list items. ([eaa0c3a](https://github.com/MaTriXy/material-components-web/commit/eaa0c3a8603d70489b22b68a2b0e6ec4284de3a5))
* **list:** Rename deprecated MDC list class names. ([941ca3b](https://github.com/MaTriXy/material-components-web/commit/941ca3b3c4c53ea296149a983b0159c5567e1b2c))
* **list:** Rename deprecated MDC list class names. ([a678806](https://github.com/MaTriXy/material-components-web/commit/a678806f5618f21a6bd28e3b881f92130b723f6e))
* **map-ext:** add a `map-get-or-err` helper function. ([d9f8210](https://github.com/MaTriXy/material-components-web/commit/d9f821042d192caddabfa88d0d95c54454cd9a58))
* **map-ext:** Rename `map-ext.map-get-or-err()` to `map-ext.get()` ([68edc03](https://github.com/MaTriXy/material-components-web/commit/68edc03c6b3b66bb2b92ea69ed28bf12f8b9b66d))
* **menu:** Add `static-styles` mixin ([a274583](https://github.com/MaTriXy/material-components-web/commit/a274583b97fd1fe27eaaca9cba5f890173bebb2e))
* **menu:** Add public #getSelectedIndex to foundation. ([f705e80](https://github.com/MaTriXy/material-components-web/commit/f705e8048ae60aceead575dfc35c8bb6233e9d23))
* **menu:** Added getter method to check fixed position status of menu ([fb76c50](https://github.com/MaTriXy/material-components-web/commit/fb76c5069ebe5f62a1b01f6b2f4613d7c6bdeaae))
* **menu:** HCM border-radius is no longer clipped ([6160219](https://github.com/MaTriXy/material-components-web/commit/6160219ff039dac7666f8cb04c53f7eb89e2062b))
* **menu:** working on theming API ([f1e0371](https://github.com/MaTriXy/material-components-web/commit/f1e0371502ee9bfe48f3501a63f70a42bfd79cb8))
* **menusurface:** Extract `static-styles` mixin ([de52246](https://github.com/MaTriXy/material-components-web/commit/de52246336da4a3629d8e85c18e482e8d8cdf1fe))
* **menusurface:** Extract `theme-styles` mixin ([a71501b](https://github.com/MaTriXy/material-components-web/commit/a71501b1332ccb95f49e48ee7c1463ce98a43130))
* **notchedoutline:** Extract `static-styles` mixin ([1bd3172](https://github.com/MaTriXy/material-components-web/commit/1bd317240624d58bf9025046386fd1b25d22227b))
* **notchedoutline:** Extract `theme-styles` mixin ([989ae2e](https://github.com/MaTriXy/material-components-web/commit/989ae2ecc5d9d9636628806a4984e182e44931ba))
* **radio:** Added theme mixin that declares custom properties in MDC radio ([b87ebf7](https://github.com/MaTriXy/material-components-web/commit/b87ebf74d4ca7de26552a9e55d79280a83ca05a9))
* **radio:** Added theme styles mixin to MDC radio ([464a002](https://github.com/MaTriXy/material-components-web/commit/464a00286cbccfa256beb879631690277776486f))
* **radio:** Added theme styles mixin to Radio ([5823407](https://github.com/MaTriXy/material-components-web/commit/5823407a71dc51fdf9919f3a85f62fcf125ec27b))
* **select:** Add #getUseDefaultValidation method to foundation. ([adeac05](https://github.com/MaTriXy/material-components-web/commit/adeac0549eb04c5d4cd050d2e52378f7edbfa37e))
* **select:** Add `text-field-leading-icon-size` and `text-field-trailing-icon-size` support for theming API. ([3777b03](https://github.com/MaTriXy/material-components-web/commit/3777b03cbed27a4569a72535c51ce7c33510fc76))
* **select:** Add support for `text-field-focus-active-indicator-height` theme key. ([de38de7](https://github.com/MaTriXy/material-components-web/commit/de38de7584a5552e93a3f92db5fb9d397fa2e986))
* **select:** add support for menu related tokens ([b5606a7](https://github.com/MaTriXy/material-components-web/commit/b5606a793c301932f9f28a2f7f55b37201fe2634))
* **select:** add support for supporting text related tokens ([6048fb5](https://github.com/MaTriXy/material-components-web/commit/6048fb5638e16e5eb1637cc2f617bc56e2955fb4))
* **select:** Allow styling bottom border radii in Material Selects. By default, to preserve compatibility with existing styling, border-radius still only styles top radii unless all four values are specified. ([83355c3](https://github.com/MaTriXy/material-components-web/commit/83355c32274a6b461016e449f663a389427364ba))
* **select:** do not emit styles when calling `theme-styles(())`. ([18b8f31](https://github.com/MaTriXy/material-components-web/commit/18b8f31e17972cdd2db5cae3c584035b535bf44b))
* **select:** Select foundation preserves describedby elements on validate ([7644d63](https://github.com/MaTriXy/material-components-web/commit/7644d63d5a4eed96766ec063ce76b8e22e362b46))
* **select:** Select foundation preserves describedby elements on validate ([901c83e](https://github.com/MaTriXy/material-components-web/commit/901c83e770dd7c0326c2013eaa5d7bf9dca30a6d))
* **select:** Select foundation preserves describedby elements on validate ([fa27ba6](https://github.com/MaTriXy/material-components-web/commit/fa27ba61d48c66d0d56b93039738380285d9ad4a))
* **slider:** Expose changing certain props after initialization to support MWC ([3f36ac7](https://github.com/MaTriXy/material-components-web/commit/3f36ac75c431ee228807e04e985d2064a3274bd7))
* **slider:** Moves native inputs into thumbs to improve a11y. ([47c7deb](https://github.com/MaTriXy/material-components-web/commit/47c7deb19df667d31f65d7742509fb883e4501f5))
* **snackbar:** Add support for secondary action button ([a9ff986](https://github.com/MaTriXy/material-components-web/commit/a9ff9866f237fbeebe94e655ae578b68ce675a04))
* **switch:** add custom property theming support ([f147a22](https://github.com/MaTriXy/material-components-web/commit/f147a2271bba2b4f1ae4df403baf86bac974b120))
* **switch:** add density custom property support ([598fccc](https://github.com/MaTriXy/material-components-web/commit/598fcccc8d8945c0527a0553a6a937ddfdd80a8f))
* **switch:** update theme keys ([00b5899](https://github.com/MaTriXy/material-components-web/commit/00b5899dcf803dcdf3795e70a970abafa247e1b3))
* **switch:** Use elevation token resolvers ([e1703be](https://github.com/MaTriXy/material-components-web/commit/e1703bed9ba624d450cddbc5f07b08eb822f46ef))
* **tabs:** Add theming API to tabs ([bd25779](https://github.com/MaTriXy/material-components-web/commit/bd25779b2bc6d10a00fbc19573f94a716f165cdf))
* **tabs:** Added theme-styles() mixin to tabs ([e38d744](https://github.com/MaTriXy/material-components-web/commit/e38d7440f43c3ffe31407f1a76a35c482c42f7c5))
* **test:** Add overline support to two- and three-line lists. ([38d1846](https://github.com/MaTriXy/material-components-web/commit/38d1846cca4f9abbcf2c073add3191bde0e03ffb))
* **test:** Add shape radius mixins to list. ([d5f1f7c](https://github.com/MaTriXy/material-components-web/commit/d5f1f7c722ada3b62265e12e47a6f714d5bd7351))
* **text-field:** add the ability to hide the asterisk required marker in floating labels ([f476fde](https://github.com/MaTriXy/material-components-web/commit/f476fdece526e3aa45441b2d11f7ac17f63e856f))
* **textfield:** $custom-property-prefix is no longer private variable (same as outlined textfield). ([d76666a](https://github.com/MaTriXy/material-components-web/commit/d76666ad4c53a619946d70b3991ca35ae5d87d04))
* **textfield:** Add `static-styles` mixin ([82554d7](https://github.com/MaTriXy/material-components-web/commit/82554d7709f8945af78415597d9b121afaddd1c0))
* **textfield:** Add character counter to theming api ([1d37bf6](https://github.com/MaTriXy/material-components-web/commit/1d37bf601f471b43f5b313bbc8ea58def2cc5c9f))
* **textfield:** changed the visibility of the mixin `filled-no-label` to public ([8879557](https://github.com/MaTriXy/material-components-web/commit/8879557e677d9b160a106e46279b1b6855926fb5))
* **textfield:** Changed visibility of $custom-property-prefix to public ([d96330c](https://github.com/MaTriXy/material-components-web/commit/d96330c085b4fe8fc59c7eb835d41ebca3a08422))
* **textfield:** Changed visibility of $custom-property-prefix to public ([f323399](https://github.com/MaTriXy/material-components-web/commit/f323399371aec4378186a05b5a839e53d9e464c0))
* **textfield:** Changed visibility of $custom-property-prefix to public. ([274610c](https://github.com/MaTriXy/material-components-web/commit/274610c77e6a9c9f19780b688cc6686a97e453a1))
* **theme:** Added `validate-theme-keys()` mixin to validate theme keys only ([457d89a](https://github.com/MaTriXy/material-components-web/commit/457d89aadf13d719af27435758feb8f6e254fe1e))
* **theme:** allow to specify varname prefix in custom-properties configuration ([f0a0bbc](https://github.com/MaTriXy/material-components-web/commit/f0a0bbc754058398bdef427d3646a0794a07047a))
* **tooltip:** Add mixin to set max-width of rich tooltip. ([cfec83c](https://github.com/MaTriXy/material-components-web/commit/cfec83c749a1b6b6602c4d2fa474d3e776e7c97b))
* **tooltip:** Adjust rich tooltip's theme and theme-styles mixins. ([7c73f61](https://github.com/MaTriXy/material-components-web/commit/7c73f6134470aaf1ef7f7ab931ba0c658116cf18))
* **tooltip:** Calls resolvers in theme-mixins to resolve typography tokens. ([66c5cbb](https://github.com/MaTriXy/material-components-web/commit/66c5cbb9446da83a6c48570e12b1ab71cae3c77f))
* **tooltip:** Fix rich tooltip title alignment (multiline titles should be start aligned). ([099ea3a](https://github.com/MaTriXy/material-components-web/commit/099ea3aa775d595a48f68e4e53ef7c69a12ef0a5))
* **tooltip:** Interactive rich tooltip content becomes scrollable if it extends beyond the max-height limit. ([0ad1283](https://github.com/MaTriXy/material-components-web/commit/0ad128337d689ca084fbda457a7204daa750b792))
* **tooltip:** No longer re-calculate persistent rich tooltip's position on scroll. ([5cb8e21](https://github.com/MaTriXy/material-components-web/commit/5cb8e2174bb381556fc684283748659b322dc158))
* **tooltip:** Updates to accessibility guidance states that we want all rich tooltips to be reachable via screenreader linear navigation. The idea is that the user should always be able to hear the message of a rich tooltip line-by-line regardless of if the tooltip is interactive, non-interactive, persistent, or non-persistent. ([5490e32](https://github.com/MaTriXy/material-components-web/commit/5490e32e718b4357ee6b58c329fdae28f89ea171))
* **tooltip:** When calculating rich tooltip width, we now take the viewport width into account. ([817002c](https://github.com/MaTriXy/material-components-web/commit/817002c296d5a9220c2b940e3383fdd42ca2aa87))
* **touch-target:** margin mixin now also allows custom property maps as arguments. ([dd99c87](https://github.com/MaTriXy/material-components-web/commit/dd99c87645f91ff535df8d50be84ffcfd643ae47))
* add elevation theming to menu ([86bde5c](https://github.com/MaTriXy/material-components-web/commit/86bde5c063e806f975d836d6a875f2fdaa7cdc67))
* add icon support to menu theming ([40b18d0](https://github.com/MaTriXy/material-components-web/commit/40b18d04314549060c2b4a28ed425cba9976687b))
* add simpler theming validation functions ([558c2be](https://github.com/MaTriXy/material-components-web/commit/558c2be6282cfe6db7f166d21350f866011955f8))
* **button:** m3 elevation + icon base theme modules ([2da3606](https://github.com/MaTriXy/material-components-web/commit/2da3606b97553ef152c9ef485432df2e0287b5de))
* **button:** Mixin styling for progress buttons ([2860d24](https://github.com/MaTriXy/material-components-web/commit/2860d244d9fc4c5bf47d3f03e7dc60bbfc56c7c9))
* **chips:** add focus ring styles ([783f6fd](https://github.com/MaTriXy/material-components-web/commit/783f6fd5a29a56f6c72917546b7426f196bf4cae))
* **chips:** Add theming Sass mixin to MDC Filter Chip ([8390093](https://github.com/MaTriXy/material-components-web/commit/83900936a87a32accaab8bc8a1bdc5a998fcf18f))
* **chips:** Add theming Sass mixin to MDC input & suggestion Chip ([860ad06](https://github.com/MaTriXy/material-components-web/commit/860ad06a1dd8bc76334ee5954109b4623f3682db))
* **chips:** Added elevation tint layer color support in chips ([c78ff04](https://github.com/MaTriXy/material-components-web/commit/c78ff042967de7cf823a9f9826f8f613be9e4846))
* **chips:** Added theme mixins to Assist Chip ([d4e16a6](https://github.com/MaTriXy/material-components-web/commit/d4e16a6c4876a3f144fdd1bade201f5b607b2bf6))
* **chips:** Export all non-deprecated members through chips index ([8647986](https://github.com/MaTriXy/material-components-web/commit/864798678626ba41619324bcd10cf5e070bdd147))
* **chips:** fix HCM chip styles ([86efd56](https://github.com/MaTriXy/material-components-web/commit/86efd56f6a2aa9870a8457900e686bc35d3cb3bc))
* **chips:** Rename action's exported members to avoid naming collisions ([b49359c](https://github.com/MaTriXy/material-components-web/commit/b49359c3581208ed7f84835c490a094699936f95))
* **chips:** Rename chip set's exported members to avoid naming collisions ([13db34b](https://github.com/MaTriXy/material-components-web/commit/13db34b342741b4bc35b3c6a65a74e2291e41100))
* **chips:** Rename chip's exported members to avoid naming collisions ([470bd34](https://github.com/MaTriXy/material-components-web/commit/470bd34e89b6683cd3a8f71bd1d3acfdf0aac5bf))
* **circularprogress:** Added theme mixin that declares custom properties in MDC circular progress ([826a3d8](https://github.com/MaTriXy/material-components-web/commit/826a3d8bede847f254702f7e652720b84d39234d))
* **circularprogress:** Added theme styles mixin to MDC circular progress ([a02fe49](https://github.com/MaTriXy/material-components-web/commit/a02fe49d397ba74b848b05b788f865193715d1bc))
* **data-table:** Implement row click feature to MDC data table ([8de07c0](https://github.com/MaTriXy/material-components-web/commit/8de07c02a50247f41cefcbd292b874b82f6d09b1))
* **data-table:** Include modifier keys in MDC data table row click event data ([5b40eb9](https://github.com/MaTriXy/material-components-web/commit/5b40eb9886f63aa9d8e8d571fb7aedeaf3d97892))
* **data-table:** separate table structure into its own mixin ([9f9d928](https://github.com/MaTriXy/material-components-web/commit/9f9d928b2c6701707c5e5d32414c0c4db6a4d564))
* **data-table:** use new select + list templates for pagination ([08398f8](https://github.com/MaTriXy/material-components-web/commit/08398f88046bfc1c3fad494b82c6e905d2fad890))
* **datatable:** Add `theme-styles` and `theme` mixins ([92b2556](https://github.com/MaTriXy/material-components-web/commit/92b2556cff2267b5f3e465c682b7dc032ba2be41))
* **dialog:** add a scrim-less dialog, that does not block interaction with the page ([2a6ddc1](https://github.com/MaTriXy/material-components-web/commit/2a6ddc1cff903da5e17766a214d76fc8cb3904d8))
* **dialog:** Add display mixin ([bebf5bf](https://github.com/MaTriXy/material-components-web/commit/bebf5bfdf0ca880e6ce4a4b8c2f13f62bf433abe))
* **dialog:** Add styling for floating sheets ([78305b6](https://github.com/MaTriXy/material-components-web/commit/78305b6d547b07aa06db04ad47b765b8f92851fa))
* **dialog:** Add styling for floating sheets with content padding ([3e20c1d](https://github.com/MaTriXy/material-components-web/commit/3e20c1de85fd72ff5efb3107c442036fc6317b4a))
* **dialog:** Add theme styles mixin to dialog ([21ece53](https://github.com/MaTriXy/material-components-web/commit/21ece536071235455a6905957f3c15dd3a7ddcf8))
* **Dialog:** Adds an API to hide the header for GMDC Fullscreen Dialog in non-fullscreen mode ([ab4aba1](https://github.com/MaTriXy/material-components-web/commit/ab4aba1afaba8f75042ed774f9e618f811bec45e))
* **Dialog:** Adds an API to set custom position for GMDC Dialog ([ea9b5b4](https://github.com/MaTriXy/material-components-web/commit/ea9b5b463c694804f79deaf8125c73779d34f5ce))
* **Dialog:** Adds an API to set custom z-index for GMDC Dialog ([96ea061](https://github.com/MaTriXy/material-components-web/commit/96ea061c1787cc329e64e9054ba1402c442a15f0))
* **fab:** Add support for container-surface-tint-layer-color ([e340b04](https://github.com/MaTriXy/material-components-web/commit/e340b04c53f1b8db0951fc51a3e368231f39a781))
* **fab:** create theming file for small fabs ([d082790](https://github.com/MaTriXy/material-components-web/commit/d082790f045f4542a5ebec082ba72ba0a106bcca))
* **fab:** prepare fab-extended for theming in MWC ([ce25bc3](https://github.com/MaTriXy/material-components-web/commit/ce25bc3ecc6836d6c46e3789ff6eeb6faf7c07cf))
* **focus:** Add focus ring component. ([587d8f8](https://github.com/MaTriXy/material-components-web/commit/587d8f871df33f9f7584d9e6612389e93c6eb04f))
* **focus-ring:** added a new mixin so we can override just the focus-ring color ([641ed08](https://github.com/MaTriXy/material-components-web/commit/641ed08513037285879a13708b95661d69c2f8b0))
* **focus-ring:** added a new mixin so we can override just the focus-ring radius ([7321d62](https://github.com/MaTriXy/material-components-web/commit/7321d6254d63f701b2f381c9cf11eb0708b56a6e))
* **iconbutton:** Add `.mdc-icon-button--display-flex` class that centers icon via flexbox. When using the new theme API, the icon button should have this class. ([8355e14](https://github.com/MaTriXy/material-components-web/commit/8355e14dc31c618a2102a846cd8cbefa08ad6007))
* **iconbutton:** Add link icon button Sass. ([9803d2d](https://github.com/MaTriXy/material-components-web/commit/9803d2dc1c88e44b43a56249916f474581f5382e))
* **iconbutton:** Add MDC theme mixin that declares custom properties. ([fa7520f](https://github.com/MaTriXy/material-components-web/commit/fa7520f6274cbab3ae7d8298554c4b0ff9e21a54))
* **iconbutton:** Add theme styles mixin. ([65aa63b](https://github.com/MaTriXy/material-components-web/commit/65aa63b0ca587845437a4ee2a0b47556574d800b))
* **linearprogress:** Added theme mixin that declares custom properties in MDC linear progress ([d25f340](https://github.com/MaTriXy/material-components-web/commit/d25f3404c0a8658f2639cd7845a98aef62063988))
* **list:** Add support for several new tokens ([cec7fb9](https://github.com/MaTriXy/material-components-web/commit/cec7fb9878e548f7f070c5b0f9572cf34e3cce36))
* **list:** Added boilerplate code for list theming API implementation ([df47894](https://github.com/MaTriXy/material-components-web/commit/df47894dbe5132b66af0df9c53a54d7d1030f397))
* **list:** Added Theming API to MDC list ([b18a873](https://github.com/MaTriXy/material-components-web/commit/b18a873dcb2800b3263d7636e829fa94b3c12d6d))
* **list:** Creates a `static-styles` mixin that holds all the non-themeable list styles. ([73ca9db](https://github.com/MaTriXy/material-components-web/commit/73ca9dbb058c47c557aff16137277a7bd33d0b8c))
* **list:** Creates a static-styles mixin that holds all the non-themeable list styles. ([58733ef](https://github.com/MaTriXy/material-components-web/commit/58733ef418bf8641a5b3b7fd33e8e2bb1d0e7b97))
* **list:** Defines a `theme` mixin for list component. Also adjusts the `theme-styles` mixin so that it emits custom properties. ([3cc30f6](https://github.com/MaTriXy/material-components-web/commit/3cc30f6adb6a5496601dd458a8a9ef40ffef7ff6))
* **mdc-list:** introduce selection change event ([7d8ea46](https://github.com/MaTriXy/material-components-web/commit/7d8ea4624e7dcdc5ce69edf1e747c77354457f42))
* **menu:** Adds option to prevent focus from being restored after an item action. ([65084ba](https://github.com/MaTriXy/material-components-web/commit/65084baffaca256dd9eb77aae8fbafd379d8da00))
* **menu:** allow preferentially opening surface below anchor ([261f2db](https://github.com/MaTriXy/material-components-web/commit/261f2db59382d561d6c89a7c41dafb6daad5a717))
* **MenuSurface:** Add opening event for menus. ([53b3cad](https://github.com/MaTriXy/material-components-web/commit/53b3cad2f5ef4d0c9d5cf03c752f27035dd7c818))
* **select:** add theme mixin to emit CSS Custom Properties. ([e74b7ba](https://github.com/MaTriXy/material-components-web/commit/e74b7ba7e4ffb1999c0ef80f45e2b08b01353930))
* **select:** Add theming mixin boilerplate code to select ([ae8a6a3](https://github.com/MaTriXy/material-components-web/commit/ae8a6a3a3e650fd068461d1236c5173c8e0467c8))
* **select:** Add validation getter methods. ([bdf1d37](https://github.com/MaTriXy/material-components-web/commit/bdf1d3771cd5a3c5b23a5cea63d3eaf97ded257d))
* **select:** Added theme mixins to MDC select ([dcfe49c](https://github.com/MaTriXy/material-components-web/commit/dcfe49c98ac25f5f5d64db021219d8a6c1caf6de))
* **select:** Copy over aria-label from option to selected text ([ecfee94](https://github.com/MaTriXy/material-components-web/commit/ecfee946fb16d47fa35a2f53d4d1ed3f5ecf7a9e))
* **select:** Copy over aria-label from option to selected text ([13e9b0d](https://github.com/MaTriXy/material-components-web/commit/13e9b0d1f2d795ecf7b9ab782e1dda0f25b603b1))
* **select:** Copy over aria-label from option to selected text ([c9b1a31](https://github.com/MaTriXy/material-components-web/commit/c9b1a31e424b9e90c4a112cd3175fffae112af88))
* **select:** start compatibility work for evolution lists ([e8554db](https://github.com/MaTriXy/material-components-web/commit/e8554dbbf4e9886dbf7a335c4953c1611c378b68))
* **slider:** Add `minRange` param to range sliders to request a minimum gap between the two thumbs. ([8fffcb5](https://github.com/MaTriXy/material-components-web/commit/8fffcb5ddfb93f1459d62c67f4a051b035bf9940))
* **slider:** Add an option to hide focus styles after pointer interaction. ([ec54d90](https://github.com/MaTriXy/material-components-web/commit/ec54d904621360bcb27e6d3cd1f33112e2a54aac))
* **slider:** Keep the slider value indicator within the bounds of the slider if possible. ([c047f7c](https://github.com/MaTriXy/material-components-web/commit/c047f7c19a9452aaced85ce1608b0bc2a63db223))
* **snackbar:** Added theme mixin that declares custom properties ([8647092](https://github.com/MaTriXy/material-components-web/commit/8647092f79d7838d85a1215f29fc1a08c57f02e8))
* **snackbar:** Added theme styles mixin ([59cf61d](https://github.com/MaTriXy/material-components-web/commit/59cf61d6b1e9ffbbfd67f999565e81fef423d63b))
* **switch:** Add high contrast mode focus ring to switch ([f31a833](https://github.com/MaTriXy/material-components-web/commit/f31a833fae6f132318068f30a24a12c6c0cc192f))
* **text-field:** Add theming mixin boilerplate code to text-field ([eb382f3](https://github.com/MaTriXy/material-components-web/commit/eb382f31889be98f4eebea1670b78c7c10f7016b))
* **text-field:** Added theme mixins to MDC text field ([344d528](https://github.com/MaTriXy/material-components-web/commit/344d528233437e5f9ff960913957022f05bbdc04))
* **textfield:** add support for several new tokens ([d71935c](https://github.com/MaTriXy/material-components-web/commit/d71935c8bf8dd6e1a4a7a38e57d02d3de4f56f67))
* **textfield:** Ensure Theming API feature consistency ([7134a77](https://github.com/MaTriXy/material-components-web/commit/7134a7752e5d06837e1eb3da7f2b49d6ba9fb72c))
* **tooltip:** Updating `handleDocumentClick` method to utilize a new `isInstanceOfElement` adapter method. ([9af09b9](https://github.com/MaTriXy/material-components-web/commit/9af09b967a7c01c6c45d2afb5cbb00f0e43904ce))
* add new class and mixin for open state of a menu item ([9a02b6e](https://github.com/MaTriXy/material-components-web/commit/9a02b6ef8e8f235c7bd07cd8c6ce9078a46dbb78))
* Add support for "mdc-deprecated-list-*" class names. ([9e52f55](https://github.com/MaTriXy/material-components-web/commit/9e52f554437fa438c9b4c266f8e87ff370ec5dea))
* Create token package with resolvers ([9405502](https://github.com/MaTriXy/material-components-web/commit/940550232c7925150e597c4f56433b7e5df59099))
* generate M3 tokens for v0.132 ([70b8ac1](https://github.com/MaTriXy/material-components-web/commit/70b8ac16e68eb842315374c551e597f02d3d3a1d))
* Indicate which thumb `valueToAriaValueTextFn` and `valueToValueIndicatorTextFn` functions are called for. ([b6510c8](https://github.com/MaTriXy/material-components-web/commit/b6510c8c1cc3a91937180f03418ea20a0cf2387b))
* Support '-5' density for text fields ([e457014](https://github.com/MaTriXy/material-components-web/commit/e4570146f182059e919d089d26bc6b2813015f10))
* Update icon button theme `size` function to be able to accept values with rem units. ([0e3dc8e](https://github.com/MaTriXy/material-components-web/commit/0e3dc8e3892e2cda93062eb64ff498dbc18203f3))
* **banner:** Add fixed-width mixin. ([c61db90](https://github.com/MaTriXy/material-components-web/commit/c61db90a5d3abb032cfa5940b0710770ba19c4a1))
* **banner:** Add mobile-stacked variant support to banner. ([a0b2db2](https://github.com/MaTriXy/material-components-web/commit/a0b2db26b550162d2e409489c5ded3381b7c7dc2))
* **banner:** Defining a z-index mixin. ([ccc64ee](https://github.com/MaTriXy/material-components-web/commit/ccc64eea393339f38e54054bbd8865f9f78618bf))
* **banner:** Expose layout method. ([4794b25](https://github.com/MaTriXy/material-components-web/commit/4794b25da9af4bfa7d48f5a6fc172efc45cfd999))
* **banner:** Update banner to be mobile friendly. ([dbc449b](https://github.com/MaTriXy/material-components-web/commit/dbc449b0972362ba3c7fc04e26900d0c3e3d8b66))
* **base:** add non-statics foundation constructor type ([e3ec22f](https://github.com/MaTriXy/material-components-web/commit/e3ec22f4579292c962ab81d7fee1d31b38b7d036))
* **base:** add observer mixin ([4ceb422](https://github.com/MaTriXy/material-components-web/commit/4ceb42220043f0ca90c57d77efec89ed29ae4508))
* **button:** Add focus indicator to link buttons in HCM. ([cad4896](https://github.com/MaTriXy/material-components-web/commit/cad4896899cc89b1354ba5df95c3870efbb99af5))
* **button:** Add in HCM support to the mdc button as an opt-in mixin. ([121e1f3](https://github.com/MaTriXy/material-components-web/commit/121e1f303f10e55c9cc5e6508bcd559c6ea7dc7b))
* **card:** Moving ripple into a `mdc-card__ripple` element rather than the `mdc-card__primary-action`. ([8ace3b8](https://github.com/MaTriXy/material-components-web/commit/8ace3b8106499cc9c126abde77258bcae7d5929d))
* **checkbox:** Add CSS custom properties to MDC checkbox for density theming ([9244508](https://github.com/MaTriXy/material-components-web/commit/9244508bd82ab65635169cfacd74f1a25ebaab7e))
* **checkbox:** Add validation to MDC Checkbox theme mixin ([2d5f32d](https://github.com/MaTriXy/material-components-web/commit/2d5f32d41cda48ca8e3c1d2244d6fb3bb4c6aa7d))
* **checkbox:** Added new theme mixin in checkbox to match token keys ([8e60818](https://github.com/MaTriXy/material-components-web/commit/8e608183652b1cd051981a4266cae66b5591a148))
* **checkbox:** Added new theme mixin in checkbox to match token keys ([33a9548](https://github.com/MaTriXy/material-components-web/commit/33a9548526d90fe41aae1e89c925720505fa5f85))
* **chips:** Expose "chipset" component ([d6c5bcf](https://github.com/MaTriXy/material-components-web/commit/d6c5bcf3743048e44d5462a2266804a7a75678a7))
* **chips:** Expose top-level resources ([fefc668](https://github.com/MaTriXy/material-components-web/commit/fefc668d77004762598e0cd88f3248a03a6aab1b))
* **chips:** Remove touch target wrapper selector from chip set spacing ([367d88b](https://github.com/MaTriXy/material-components-web/commit/367d88bdb32a24c73f935154d616d1d7abfd9dd8))
* **chips:** Truncate long chip labels by default ([f5c6db8](https://github.com/MaTriXy/material-components-web/commit/f5c6db8fc71c654c47c68a4c717f8d8995f43e30))
* **circular-progress:** do not require HTML without whitespaces ([8648b82](https://github.com/MaTriXy/material-components-web/commit/8648b8258f7f87edcc1d58a2bc7db3d78425508f))
* **data-table:** Add support for applying row checkbox density ([291b355](https://github.com/MaTriXy/material-components-web/commit/291b3553d20c5dda9c5a80e0dda0705b524f41a3))
* **dialog:** add custom property for z-index ([776c186](https://github.com/MaTriXy/material-components-web/commit/776c1868154e5b99a332f60927b78b32b82fe19f))
* **dialog:** Adds and defines styling for the "header bar" on a full-screen dialog. ([089de51](https://github.com/MaTriXy/material-components-web/commit/089de519c1c2f0378b9852dafd3ca5a304268a44))
* **dialog:** removing call to `#close` within `#destroy`. ([5631828](https://github.com/MaTriXy/material-components-web/commit/5631828e1541df22feb879a5310e57494ee722a3))
* **dom:** add tab key keyboard.ts ([dc9c840](https://github.com/MaTriXy/material-components-web/commit/dc9c8402374f46402c73f97e60206517e3186389))
* **fab:** Added mixin that auto-generates custom properties for Fab ([8530d35](https://github.com/MaTriXy/material-components-web/commit/8530d351494fc9a88e8e0dfd5e5d58de81a983d9))
* **fab:** Added mixin to auto-generate custom properties for Fab ([14767a8](https://github.com/MaTriXy/material-components-web/commit/14767a8db432f8834d74a31e1577c3557a38c6d9))
* **fix:** Ensure that secondary controls do not ripple. ([1f636b2](https://github.com/MaTriXy/material-components-web/commit/1f636b205b9609d19a96bef707ab87a0f8ca4f1a))
* **fix:** Remove old MDC list class names, preparing to release evolution. ([5f0fc44](https://github.com/MaTriXy/material-components-web/commit/5f0fc444a706626a106c2b36116a56e9dc5b8c79))
* **fix:** Remove the "evolution" prefix from list evolution's class names. ([0cde52f](https://github.com/MaTriXy/material-components-web/commit/0cde52f5a007f4b7da16afd45f7445d615d5a2f6))
* **fix:** Simplify divider styles to reflect new design guidance. ([f77c508](https://github.com/MaTriXy/material-components-web/commit/f77c508600d4b0f4ce4a66c63d1064b545149570))
* **iconbutton:** Add in HCM support to the mdc iconbutton as an opt-in mixin. ([fd61b04](https://github.com/MaTriXy/material-components-web/commit/fd61b04760d96fcc1c96e43ca8e0663d16f5a995))
* **linear-progress:** add getBuffer ([9c85d50](https://github.com/MaTriXy/material-components-web/commit/9c85d505bddf9c63ef52508c385ec59f1f947b8e))
* **linear-progress:** remove aria-valuemin/max attrs for indeterminate ([4321323](https://github.com/MaTriXy/material-components-web/commit/4321323e4bea2da8192b81ebdf8c6a9ee1e76aa0))
* **list:** Add missing "deprecated" aliases for old list mixin. ([302c7a9](https://github.com/MaTriXy/material-components-web/commit/302c7a960f3b2787f253908d963eaaaa0b8adfd4))
* **list:** Basic support for three-line lists. ([4bb5eea](https://github.com/MaTriXy/material-components-web/commit/4bb5eea2b81268d4dc2f838beccb44dd4ff2857d))
* **list:** Finalize list mixin/variable rename. ([c97d7d8](https://github.com/MaTriXy/material-components-web/commit/c97d7d88102f96c4c61a1b7c3329f3efac3727f4))
* **list:** support ctrl + a keyboard shortcut ([eefef49](https://github.com/MaTriXy/material-components-web/commit/eefef49d86c69b1985aa4e5fa5b8809ba1f0a1f4)), closes [#6366](https://github.com/MaTriXy/material-components-web/issues/6366)
* **list:** Update deprecated list class names so evolution can become default. ([606e767](https://github.com/MaTriXy/material-components-web/commit/606e767ef6d1d98461d8910ece874b65d0143981))
* **list:** Update styles to reference "deprecated" mixins/variables. ([3201cae](https://github.com/MaTriXy/material-components-web/commit/3201cae479a0dbf97c40dda1b9d32a5818d6ab62))
* **list:** Update styles to remove "evolution" prefix from mixins/variables. ([f9c9e39](https://github.com/MaTriXy/material-components-web/commit/f9c9e39d6c0cddf796de7e821ec59e199aeab851))
* **list:** Update the MDC component for List Evolution. ([766981c](https://github.com/MaTriXy/material-components-web/commit/766981c15a200b374a14c2ab80bf746824bf7434))
* **menu:** add maxHeight setter ([bf670da](https://github.com/MaTriXy/material-components-web/commit/bf670dad7247d7ac1db9bf00905921b5c09a5b4d))
* **menu-surface:** add option to always horizontally center on viewport ([23ea2d8](https://github.com/MaTriXy/material-components-web/commit/23ea2d85e760325371c2529af7c99316d876c044))
* **menu,select:** enable fixed menu position in mwc-select ([b9adb7a](https://github.com/MaTriXy/material-components-web/commit/b9adb7a0f6d2871bcd87664ab857fb62392c27d4)), closes [#2062](https://github.com/MaTriXy/material-components-web/issues/2062)
* **ripple:** add active() mixin for styling active styles. ([9f2e85f](https://github.com/MaTriXy/material-components-web/commit/9f2e85fb8453cab94f54eeb9e2d9e18600ed7fa0))
* **ripple:** Added theme styles and theme mixin to Ripple ([a2b0f4c](https://github.com/MaTriXy/material-components-web/commit/a2b0f4cee3278c71d3ee2905f60dd37af6ee507c))
* **segmented-button:** Add MDC segmented button into material-components-web ([596e984](https://github.com/MaTriXy/material-components-web/commit/596e984242fdef685dae49e2c84305e55c9ea724))
* **select:** add mixin for variable width ([30c11bf](https://github.com/MaTriXy/material-components-web/commit/30c11bfc24e426c0647645758e4f9d98f589e85c))
* **select:** allow programmatic change without firing event ([79ce087](https://github.com/MaTriXy/material-components-web/commit/79ce0878b3233592c3188548711b311e5706d3dd)), closes [#6166](https://github.com/MaTriXy/material-components-web/issues/6166)
* **shape:** add shape map theme value support ([ec31ae1](https://github.com/MaTriXy/material-components-web/commit/ec31ae1ed1e6483d972f0eddece0fbf30ac721c2))
* **slider:** Add hidden input to slider, to support forms submission. This is also prep for moving to use an \<input type="range"\> behind the scenes, in order to support touch-based AT's. ([b98d15d](https://github.com/MaTriXy/material-components-web/commit/b98d15d90b19e69066c0b417ee0d8b11ab733e20))
* **slider:** Add mixin to customize thumb color in the activated (hover, focus, pressed) state. ([94f50b2](https://github.com/MaTriXy/material-components-web/commit/94f50b260dd6cbf6cca5fbedd2a8681746e2cc1d))
* **slider:** Modify continuous slider to use step value by default, and give clients the option to customize step value for continuous sliders. ([7ad038e](https://github.com/MaTriXy/material-components-web/commit/7ad038e1d37171dc1fc931112b17f085533f7048))
* **slider:** Use input with type="range" to back slider component. This ensures that sliders can be adjusted with touch-based assistive technologies, as the current ARIA spec for sliders is not compatible with e.g. TalkBack/Android. ([9083b7d](https://github.com/MaTriXy/material-components-web/commit/9083b7d61b1dda2c5acefda6e8939870a358e98f))
* **snackbar:** Add 1px transparent border for high contrast support ([15a4d40](https://github.com/MaTriXy/material-components-web/commit/15a4d40dd708775c6120165422c9ebadee4c8f6f))
* **state:** make context aware ([b2fe352](https://github.com/MaTriXy/material-components-web/commit/b2fe3528bc1603df715c833abb5d905080681102))
* **switch:** add high-contrast mode focus shim mixin ([c91e8d1](https://github.com/MaTriXy/material-components-web/commit/c91e8d141bc8b519ae1d8c7d1771c0d5110e84ad))
* **switch:** add new component and foundation ([ef43e6d](https://github.com/MaTriXy/material-components-web/commit/ef43e6d9607c7e8d6495b4a82e2178059dbe37fa))
* **switch:** add updated density styles ([cb162da](https://github.com/MaTriXy/material-components-web/commit/cb162da374f5e5d613e6a4554f0e1efcdc443c04))
* **switch:** add updated RTL styles ([573dc7f](https://github.com/MaTriXy/material-components-web/commit/573dc7ffd479527a885e95f4c8ece270363a31cc))
* **switch:** update switch to new design spec ([0ce2fdb](https://github.com/MaTriXy/material-components-web/commit/0ce2fdb02a62bb31f945144aac58957989ecfba6))
* **textfield:** add autovalidation customization ([2ab716c](https://github.com/MaTriXy/material-components-web/commit/2ab716cbda14aca5a8b62cdae3c71c2d629b16f7))
* **textfield:** adding input-font-family mixin ([991fb99](https://github.com/MaTriXy/material-components-web/commit/991fb99f715872b49c89c44a6c98e82b4507fd14))
* **textfield:** adding input-font-size mixin ([207230e](https://github.com/MaTriXy/material-components-web/commit/207230eb81e8c10cd5f962725af8c0184b8f3b62))
* **theme:** add configuration support for custom-properties ([1f318ff](https://github.com/MaTriXy/material-components-web/commit/1f318ff0f033f9f51c8bf7f76ef997161ff62fd4))
* **theme:** add create-varname() for custom properties ([b522724](https://github.com/MaTriXy/material-components-web/commit/b5227247d730171c02bd71e9b44106cd179aaf2a))
* **theme:** add either() utility function ([5268222](https://github.com/MaTriXy/material-components-web/commit/5268222c432bb886add05cbb1779909117cf1620))
* **theme:** add key store ([07ff0c4](https://github.com/MaTriXy/material-components-web/commit/07ff0c452c896f9f8131532538742bed0ad207c9))
* **theme:** add map-ext.split() helper function ([ec22e1d](https://github.com/MaTriXy/material-components-web/commit/ec22e1da9746b38de654a18b0161c40c74e4e74f))
* **theme:** add state selector mixins ([d20dc6d](https://github.com/MaTriXy/material-components-web/commit/d20dc6dba8e8824645404d0eaafa763d8b026ef0))
* **theme:** add validation option to disallow custom properties ([fec7b42](https://github.com/MaTriXy/material-components-web/commit/fec7b42ca54baf37487cadaf96ac8cf559d6ccd0))
* **theme:** Added validation mixin to validate provided theme configuration keys ([1c156d6](https://github.com/MaTriXy/material-components-web/commit/1c156d69d76efcfa39c706f7f6ae74e96c2bd541))
* **theme:** allow custom property strings in theme.validate-theme() ([4e372fb](https://github.com/MaTriXy/material-components-web/commit/4e372fb4937f0fe71cce7c4c829b099f9f3dcf6b))
* **theme:** allow lists in replace maps ([d2959b1](https://github.com/MaTriXy/material-components-web/commit/d2959b16ca9a2e4574984b8e459993c9c9a2075a))
* **theme:** emit CSS var() declarations when provided a standalone custom prop ([1a3a396](https://github.com/MaTriXy/material-components-web/commit/1a3a396293df35d9621155e9168df35d39d83fee))
* **theme:** gss.annotate supports named arguments ([c50d20b](https://github.com/MaTriXy/material-components-web/commit/c50d20bab49d5c00dd0a74e8616d02d8d87fba89))
* **theme:** theme.property() supports custom prop declarations ([474836a](https://github.com/MaTriXy/material-components-web/commit/474836ad0f4f92d03ce7dd0c9f923b6ff9abac7c))
* **tooltip:** Add positioning adjustment and position specification for rich tooltips. Rich tooltips default to the END position and does not support CENTER positioning. ([384a8ee](https://github.com/MaTriXy/material-components-web/commit/384a8eeb163798df6655c8a49c36428ede852e15))
* **tooltip:** Added persistent variant for rich tooltips that shows/hides based on mouse clicks on the anchor element. Clicks on elements other than the anchor will also hide the persistent variant. ([9775856](https://github.com/MaTriXy/material-components-web/commit/9775856508a7256cb7dc93d0c3e47f6d87c08c93))
* **tooltip:** Adding foundation methods to allow users to configure the tooltip show and hide delay time. ([08db3d7](https://github.com/MaTriXy/material-components-web/commit/08db3d737fa49893d1c3d1d3f7dd07367dd9eaeb))
* **tooltip:** Adding logic to position the caret relative to the tooltip. ([76da787](https://github.com/MaTriXy/material-components-web/commit/76da7876cd1452cdabed5169bdbdfd06b4629cda))
* **tooltip:** Adding side positioning options for plain tooltips. ([ba9c296](https://github.com/MaTriXy/material-components-web/commit/ba9c29637109e300121c79a902df12310d9cf9fe))
* **tooltip:** Adding touchstart/touchend event listeners to tooltip. This allows tooltips attached to non-focusable elements to be surfaced on mobile. ([7cd26af](https://github.com/MaTriXy/material-components-web/commit/7cd26af4dd2033dacce75d2df2d179f81286fe71))
* **tooltip:** Adds `transform-origin` on tooltip surface so tooltip entrance animation has a direction based on its alignment with the anchor element. ([623af86](https://github.com/MaTriXy/material-components-web/commit/623af861e1852603fd4778fb0abbef58b427333c))
* **tooltip:** Adds logic for generating a new tooltip position when all "standard" positions for tooltip w/ caret are invalid. ([9bc0eff](https://github.com/MaTriXy/material-components-web/commit/9bc0effaf60a530bed8247f2bb9190dcbbbdec54))
* **tooltip:** Adds logic to determine valid position options for tooltip w/caret, and select which should be used. ([2ebfc53](https://github.com/MaTriXy/material-components-web/commit/2ebfc537439508ea08bcd99991eed4fe838f3550))
* **tooltip:** Adjust  tooltip position on `scroll` and `resize` events. This ensures that the tooltip remains pinned to the anchor element despite page movement. ([a415276](https://github.com/MaTriXy/material-components-web/commit/a41527604048d218879240aaaf04aff7389053d1))
* **tooltip:** Adjusting `transform-origin` for tooltips with caret so that the entrance animation originates from the caret. ([1a8d064](https://github.com/MaTriXy/material-components-web/commit/1a8d064838299e07e97e5f30470c76c03074ac42))
* **tooltip:** Adjusting logic and styles so the caret better matches spec. ([55ad2d7](https://github.com/MaTriXy/material-components-web/commit/55ad2d7d8f9bcc979f5334352620815d6ea9add6))
* **tooltip:** Adjusting tooltip positioning logic so that the tooltip remains within the viewport even if the anchor element is partially off-screen. ([482ff90](https://github.com/MaTriXy/material-components-web/commit/482ff909132b2e8f81791d7128cb0a3d2ff371a8))
* **tooltip:** Change rich tooltip to use position absolute instead of fixed and rely on a position relative parent element so that if the parent has a transform, perspective, or filter property set to something other than none, the positioning would still work. ([0c95c9f](https://github.com/MaTriXy/material-components-web/commit/0c95c9f7bf1e0d465e99fd7dd3f1497d37d871ff))
* **tooltip:** Creating an `mdc-tooltip__surface-animation` class that holds all the style properties responsible for animating the tooltip in and out of the page. The existing `mdc-tooltip__surface` class will hold all the style properties that impact the visual appearance of the tooltip. ([56fc269](https://github.com/MaTriXy/material-components-web/commit/56fc26962126e24a7c56124de7f36078409254a7))
* **tooltip:** Define styling to set the full-screen dialog size depending on the viewport size. ([fe13dd1](https://github.com/MaTriXy/material-components-web/commit/fe13dd1308dc695898b2c7d3dfbddccc7d38b420))
* **tooltip:** Emit event for tooltip shown. ([31e517c](https://github.com/MaTriXy/material-components-web/commit/31e517cea3002785ad2936ebc6ef12317b9d4133))
* Describe how to add child lists into a list item. ([758ce31](https://github.com/MaTriXy/material-components-web/commit/758ce31d94d065b93d09db0016ec86b56d9197ec))
* Modify NotifyOpening event to emit after adding the "--opening" class so that the banner's contentHeight is visible to listeners handling the `opening` event ([b2ddacf](https://github.com/MaTriXy/material-components-web/commit/b2ddacf738a9fc404225ff2c23169000dd69ddd1))
* **tooltip:** Expose `hide` and `isShown` methods in the MDCTooltip component. This allows MDC clients to create their own class to enforce only one tooltip being shown at a time. ([c5e18b0](https://github.com/MaTriXy/material-components-web/commit/c5e18b0203a3c474384bc5902a15855636ce849b))
* **tooltip:** Expose method that allows users to register additional scroll handlers on elements in the DOM. This should be used in situations where the tooltip anchor is a child of a scrollable element, and will ensure that the tooltip remains attached to the anchor when this element is scrolled. ([24609b8](https://github.com/MaTriXy/material-components-web/commit/24609b82225f763c1dc9da16b1ee9e0dd3c52197))
* **tooltip:** Fixes ordering of values provided to `tranform-origin`. ([25751d2](https://github.com/MaTriXy/material-components-web/commit/25751d2ed4061129f206bdbc6682052b0c76709e))
* **tooltip:** Hide rich tooltip if mouse leaves rich tooltip. Rich tooltip persists if mouse leaves rich tooltip and enters anchor. ([6d8574f](https://github.com/MaTriXy/material-components-web/commit/6d8574fe1db3a60dfb5a45ce8c6c6718700c2dfd))
* **tooltip:** Make persistent rich tooltips persist when click target is within the rich tooltip. ([fb194dd](https://github.com/MaTriXy/material-components-web/commit/fb194dd354d2c912f997c500347557edcba1440d))
* **tooltip:** Plain tooltips remain visible if the user hovers over them. ([ccce99c](https://github.com/MaTriXy/material-components-web/commit/ccce99cd630b5a49ed40ba95b0e3d3d6fea74801))
* **tooltip:** Reducing minimum threshold distance between tooltip and viewport from 32px to 8px. ([23491cf](https://github.com/MaTriXy/material-components-web/commit/23491cf85b8831896f95879e8aea258d5ca7f653))
* **tooltip:** Restore focus to the anchor element when the ESC button is pressed while the focus is in the tooltip for rich tooltips. Default rich tooltips should have focus restored to anchor and not have rich tooltips show. ([eabf9d5](https://github.com/MaTriXy/material-components-web/commit/eabf9d5c2d9b56e316db98f2d8e16bf12f1ef501))
* **tooltip:** Set up base sass for rich tooltip. Rich tooltips are currently in development and is not yet ready for use. ([4ae94ff](https://github.com/MaTriXy/material-components-web/commit/4ae94ff7816d87fde3285a0c2fd48b94ff0bbdab))
* **tooltip:** Set up rich tooltip to persist if mouse leaves anchor and enters rich tooltip. ([c927a5d](https://github.com/MaTriXy/material-components-web/commit/c927a5d05761d0a80f886b2b7627e600df38c467))
* **tooltip:** The aria-expanded attribute of the anchor element will only be changed for anchor elements with interactive rich tooltips. Non-interactive rich tooltip anchor elements do not have the aria-haspopup and aria-expanded attributes. ([c5dda80](https://github.com/MaTriXy/material-components-web/commit/c5dda809d5e4c110f3b4bb37c9646e572026d58d))
* **tooltip:** When the anchor element blurs, the rich tooltip will only be hidden if the focus is changed to a non-rich tooltip element. ([6871336](https://github.com/MaTriXy/material-components-web/commit/6871336f11f3cc7d94c6314dc049092e0427106c))
* **tooltip:** When the rich tooltip element focuses out, hide the rich tooltip if the new focused element is not the anchor element or an element within the rich tooltip. ([1085c3b](https://github.com/MaTriXy/material-components-web/commit/1085c3b2df7d3c1b528e1b9ba5557975fa959401))
* Added global variable to conditionally emit CSS selector fallback declarations ([7b0e2b3](https://github.com/MaTriXy/material-components-web/commit/7b0e2b3775d006126161bd688851d490d19e9558))
* **animation:** Add a linear animation method ([c250ec5](https://github.com/MaTriXy/material-components-web/commit/c250ec52ad1ce21943f4c7f521087bf2e647da00))
* **animation:** Create animation frame helper class ([e34e411](https://github.com/MaTriXy/material-components-web/commit/e34e411b1835efa3f275921ca8c9d33d6df92bec))
* **banner:** Add banner component into MDC catalog ([aa3a3e5](https://github.com/MaTriXy/material-components-web/commit/aa3a3e5a43b1e012e948c5f8f8b7c133d5ba6b0d))
* **banner:** Add fixed banner variant ([fd8af3d](https://github.com/MaTriXy/material-components-web/commit/fd8af3d435e12d28cfc393762c325cc2d1b03f13))
* **banner:** Update close() to use CloseReason and provide programmatic way of closing ([ff88df6](https://github.com/MaTriXy/material-components-web/commit/ff88df637a944de239b8860b5f0c38454cc6cc1b))
* **banner:** Update content to be leading as default and add support for optional centered. ([8d5b84f](https://github.com/MaTriXy/material-components-web/commit/8d5b84fb260506c69fa93246aee538db89db8fc3))
* **card:** Add transparent outline to elevated card, so card boundary is shown on high-contrast mode. ([c71ebfa](https://github.com/MaTriXy/material-components-web/commit/c71ebfa02b7f3203317255e377b5cb165a0cfeac))
* **checkbox:** Add CSS custom properties to MDC checkbox theme mixins ([66669e3](https://github.com/MaTriXy/material-components-web/commit/66669e3b668d0579ac71d6896240fd14d6a4322a))
* **checkbox:** Added theme configuration support to checkbox ([58eaa9f](https://github.com/MaTriXy/material-components-web/commit/58eaa9f027bb7ced126d3fe97cab5a0f627eb098))
* **checkbox:** Added theme configuration support to checkbox ([fbf73c2](https://github.com/MaTriXy/material-components-web/commit/fbf73c2a6633298d6d65cdfcb8f76151e0e9c600))
* **checkbox:** Separate static styles from checkbox styles ([4f55400](https://github.com/MaTriXy/material-components-web/commit/4f55400bbde3d85cacf379b7f7a80dd439952b3f))
* **checkbox:** Separate static styles from checkbox styles ([150f427](https://github.com/MaTriXy/material-components-web/commit/150f427a01a7b20783d287cebe40bb4d93a24ce3))
* **checkbox:** Separate static styles from checkbox styles ([ff87000](https://github.com/MaTriXy/material-components-web/commit/ff870005acef3cb26a6b4f378c012ffdb1061194))
* **circular-progress:** support track color ([e27c580](https://github.com/MaTriXy/material-components-web/commit/e27c5802fed20af29976f1f84bc39f9b59999ab5))
* **data-table:** Add progress indicator / loading feature to data table ([4497ace](https://github.com/MaTriXy/material-components-web/commit/4497acef8fd636b6ceef3cf055f664c92465e965))
* **data-table:** Added sort status label to sortable column header ([9833dc2](https://github.com/MaTriXy/material-components-web/commit/9833dc28775a02fa4c7c490ae5df1ed198bbb398))
* **data-table:** Added styles to support rows per page select menu in pagination ([3ee488f](https://github.com/MaTriXy/material-components-web/commit/3ee488f1c0f65972459f2dbc74b6c3365786df4b))
* **data-table:** Added support for column sorting feature in data table ([06ef147](https://github.com/MaTriXy/material-components-web/commit/06ef147b593d134fcd03f48fc3581d8fd6068865))
* **data-table:** Added support for sticky header row in data table ([599b8c3](https://github.com/MaTriXy/material-components-web/commit/599b8c3191a888e3debd94ad4934f741c5fb6e23))
* **data-table:** Make rows per page wrap in new line when overflows ([09abc92](https://github.com/MaTriXy/material-components-web/commit/09abc92198d1628c57eee5e75c58da52b223c322))
* **drawer:** allow custom properties in width() ([39e6f71](https://github.com/MaTriXy/material-components-web/commit/39e6f71e2e03b75512242d7520678c32c5af2b70))
* **drawer:** expose --mdc-theme-surface custom prop ([319bf66](https://github.com/MaTriXy/material-components-web/commit/319bf66dead88f67dba64f9d50a6f3f0d82aad72)), closes [#6466](https://github.com/MaTriXy/material-components-web/issues/6466)
* **elevation:** add custom props for overlay ([4c354a3](https://github.com/MaTriXy/material-components-web/commit/4c354a36d012e5d241f27380db1d0d9e70769c27))
* **fab:** Add focus outline mixins to MDC Fab ([7a9afaf](https://github.com/MaTriXy/material-components-web/commit/7a9afaf4b503bc0d1d135b8d88edd4a7ed02e52e))
* **fab:** Add focus outline mixins to MDC Fab ([0f60323](https://github.com/MaTriXy/material-components-web/commit/0f60323a8365901c4ff6fd956161b99d8f413927))
* **fab:** support css custom props for extended-padding ([01db890](https://github.com/MaTriXy/material-components-web/commit/01db890532f796ea3e66a9c7d76893bef8689d6f))
* **list:** add focus indicator in hi-contrast mode ([8602f1b](https://github.com/MaTriXy/material-components-web/commit/8602f1b4da404816513733a21973ec9cbc9acfa3))
* **list:** Add transparent-border for aria-activedescendant usage ([8388a9b](https://github.com/MaTriXy/material-components-web/commit/8388a9bf6f4db77656adcdd604125eb205694b10))
* **menu-surface:** Add transition to height for menu resizing animation. ([1e7cb61](https://github.com/MaTriXy/material-components-web/commit/1e7cb61989c95f9b86de3b1f6edb1773c12dfc97))
* **ripple:** Add will-change opt-out param ([e590b37](https://github.com/MaTriXy/material-components-web/commit/e590b376bf20bde50e6f6b62339c0bac2703ccf0))
* **rtl:** allow values to be theme keys and custom props ([afb1c11](https://github.com/MaTriXy/material-components-web/commit/afb1c11a9e9048ba7c2ed30e32e892ae483dfccc))
* **segmented-button:** add adapters and foundations ([#6165](https://github.com/MaTriXy/material-components-web/issues/6165)) ([6ed717d](https://github.com/MaTriXy/material-components-web/commit/6ed717dddf5f62dd5bfc621388ae07471775612f))
* **segmented-button:** Add component outlines ([#6222](https://github.com/MaTriXy/material-components-web/issues/6222)) ([a0f1202](https://github.com/MaTriXy/material-components-web/commit/a0f1202dc5cd67207877167558742d0b18bf0e32))
* **segmented-button:** Add initial Sass styles ([#6141](https://github.com/MaTriXy/material-components-web/issues/6141)) ([7555383](https://github.com/MaTriXy/material-components-web/commit/75553837cce5cb9d52d5561f5729d110e71af401))
* **segmented-button:** Add new package for segmented button ([#6073](https://github.com/MaTriXy/material-components-web/issues/6073)) ([d561860](https://github.com/MaTriXy/material-components-web/commit/d5618602a8ef45a1fdf753c3598afc5e1cadc95b))
* **segmented-button:** Add ripple and touch-target support ([#6277](https://github.com/MaTriXy/material-components-web/issues/6277)) ([e3b7462](https://github.com/MaTriXy/material-components-web/commit/e3b746208db04f3922fabba77986f9f02f422d75))
* **segmented-button:** Add select validations for singleSelect ([#6381](https://github.com/MaTriXy/material-components-web/issues/6381)) ([2e8c3dd](https://github.com/MaTriXy/material-components-web/commit/2e8c3dd2e0622957a373286f14720de36afb5ba4))
* **segmented-button:** Added foundation business logic ([#6198](https://github.com/MaTriXy/material-components-web/issues/6198)) ([e6e2301](https://github.com/MaTriXy/material-components-web/commit/e6e23019d567802c13d0bd6559a35291c48abc91))
* **segmented-button:** Implement components ([#6223](https://github.com/MaTriXy/material-components-web/issues/6223)) ([ac405ea](https://github.com/MaTriXy/material-components-web/commit/ac405eae1b80f719a80dc4fec663b763e73cdf5d))
* **select:** Add menu invalid class ([4ba3c9a](https://github.com/MaTriXy/material-components-web/commit/4ba3c9a319dad4101f4d24607a79c01390330acd))
* **select:** Add openMenu foundation method ([9b0b5f2](https://github.com/MaTriXy/material-components-web/commit/9b0b5f2e034a7f8ab0e68e3afbd7c246447f53e7))
* **select:** Add styles for high-contrast mode in IE ([05cc5c2](https://github.com/MaTriXy/material-components-web/commit/05cc5c20651eed3e40960074db919f0d030c46fb))
* **select:** changing density also also changes menu's list density ([68a2af1](https://github.com/MaTriXy/material-components-web/commit/68a2af131b82e9b50e70754a2d653d6305dac4b9))
* **select:** extend typeahead to work when menu closed but select focused ([a0dc2b5](https://github.com/MaTriXy/material-components-web/commit/a0dc2b5c4afbf3fd8274c752d43aeeeb11231e5f))
* **select:** flatten menu top when opened below ([912d902](https://github.com/MaTriXy/material-components-web/commit/912d9021dab7712e0ab711fcaffb3933a960c171))
* **select:** gracefully display long labels ([21c4e4e](https://github.com/MaTriXy/material-components-web/commit/21c4e4ed866944c090ae3d6dffe9f5e4725b7ffc))
* **select:** lower dropdown icon size and list leading padding when dense ([32aa236](https://github.com/MaTriXy/material-components-web/commit/32aa23641258671e0eac803c0f41ae78ecce32fd))
* **select:** make selected text more flexible ([2b420c5](https://github.com/MaTriXy/material-components-web/commit/2b420c5b318b7ada726dec774d9e09624bca9822))
* **select:** move selectedText into its own text node ([0bc41a9](https://github.com/MaTriXy/material-components-web/commit/0bc41a9c75392352e8a31eb9d46f1a1457ffe732))
* **select:** Replace hardcoded leading margins for options with dummy graphic ([7461aad](https://github.com/MaTriXy/material-components-web/commit/7461aad68924d0f3bb790987b01f802078ebc7df))
* **select:** support hidden input ([fda053e](https://github.com/MaTriXy/material-components-web/commit/fda053eb848395ebfa9266e4535013e1a3be8486)), closes [#5428](https://github.com/MaTriXy/material-components-web/issues/5428)
* **select:** truncate with ellipses by default ([83d83f1](https://github.com/MaTriXy/material-components-web/commit/83d83f131118073943a6a45923b37b3a961bd894))
* **select:** use floating label's required class ([d86ad3b](https://github.com/MaTriXy/material-components-web/commit/d86ad3b6081234359ff19547649f9d391ea8aa9e))
* **shape:** add shape custom properties ([0743288](https://github.com/MaTriXy/material-components-web/commit/0743288fb04dc8578f0b850d31fad6c00c97ea1c))
* **slider:** Add hooks into dragStart/dragEnd events to slider foundation. ([85a1fa9](https://github.com/MaTriXy/material-components-web/commit/85a1fa9eab3010f2c41f5f65ca80a7f34bc46b2c))
* **slider:** Add M2 version of slider. ([8158544](https://github.com/MaTriXy/material-components-web/commit/8158544774c50ba21b114f6fe24786816ba4c4fd))
* **slider:** Add support for customizing tick marks opacity, and document tick mark DOM structure for rendering tick marks before component initialization. ([238216f](https://github.com/MaTriXy/material-components-web/commit/238216fc466a1b0dd5f4f05f10a083949e1b99d9))
* **slider:** Add support for setting `aria-valuetext` on slider thumbs. ([fd608ff](https://github.com/MaTriXy/material-components-web/commit/fd608ff66bbb2f765fa1c092427fba9e61a074f3))
* **slider:** Add support for styling initial thumb/track before component JS initialization. ([08ca4d0](https://github.com/MaTriXy/material-components-web/commit/08ca4d0ec5f359bc3a20bd2a302fa6b733b5e135))
* **slider:** Add support for theming disabled colors. ([d52b165](https://github.com/MaTriXy/material-components-web/commit/d52b165b5869309705068ab58803cef426f1e590))
* **snackbar:** Update stacked layout to add an additional 8px on the label's right padding ([521afaf](https://github.com/MaTriXy/material-components-web/commit/521afaf6e3086285b040c06fc3dbc92f20dc9b06))
* **textfield:** allow disabled textareas to scroll and resize ([b9776b1](https://github.com/MaTriXy/material-components-web/commit/b9776b1d09b9ccfac38b3dc471dee2fd9fc8558a))
* **textfield:** support svg icons for textfield ([d91794c](https://github.com/MaTriXy/material-components-web/commit/d91794c7ecafbaef7150d2c88226b96d7e4c4ea6))
* **textfield:** Using touch-target-mixins to increase the touch target size on trailing icons on text fields. ([174c0be](https://github.com/MaTriXy/material-components-web/commit/174c0becfc802e4366e4814758f28cb1ecf2c75a))
* **theme:** add calc() string replacement to property mixin ([79414bf](https://github.com/MaTriXy/material-components-web/commit/79414bf9f93aae12bc394fd518b6cb401e5ddb26))
* **theme:** add deep-get utility ([fb5a4cd](https://github.com/MaTriXy/material-components-web/commit/fb5a4cdeb79de0412a9e0573db1dacb28e8186f3))
* **theme:** add new property mixin and custom property support ([51512a4](https://github.com/MaTriXy/material-components-web/commit/51512a4ac375a6175b4a533ff004ea90a4318c9e))
* **theme:** add shadow-dom host-aware helpers ([0a2e7fc](https://github.com/MaTriXy/material-components-web/commit/0a2e7fc8976e6481c9225609d7ff5354362472fa)), closes [#6295](https://github.com/MaTriXy/material-components-web/issues/6295)
* **theme:** add state helper functions ([0809012](https://github.com/MaTriXy/material-components-web/commit/08090126b4eff43f82188ee1dae5c8deda33d2ef))
* **theme:** custom property fallback values are now optional ([01de070](https://github.com/MaTriXy/material-components-web/commit/01de07011d8b4b121a061da66fafe610f5484a51))
* **tooltip:** Add 500ms delay before showing tooltip. ([a1c6559](https://github.com/MaTriXy/material-components-web/commit/a1c65593d3c1f594a35561569357bb657dd50408))
* **tooltip:** add position options for y-axis ([91ab1c6](https://github.com/MaTriXy/material-components-web/commit/91ab1c62a4e00ae844d444882582d2052aaf228a))
* **tooltip:** Add tooltip component into MDC catalog. ([b9394dc](https://github.com/MaTriXy/material-components-web/commit/b9394dc5da7db3b60497cf81aa5f26a5758d9b37))
* **tooltip:** Adding option to render tooltips as hidden from a screenreader. This should only be utilized in situations where the tooltip label hold information duplicated from an accessible name on the anchor element (e.g. tooltip label is the same as the aria-label on an icon button) ([546277d](https://github.com/MaTriXy/material-components-web/commit/546277d323c484ddf181afffed153f4f17c9f4a7))
* **tooltip:** Adding transparent border around tooltip so it is distinguished from the background in high contrast mode. ([02e372c](https://github.com/MaTriXy/material-components-web/commit/02e372c5f02afaf66e06e733a08c6c704c16843c))
* **tooltip:** Adjusting tooltip z-index so tooltip appears above other content on the page. ([c285200](https://github.com/MaTriXy/material-components-web/commit/c2852000d97ed49c5f8ab82b5911deb1c87a9025))
* **tooltip:** Adjustments to tooltip structure. ([19bea2a](https://github.com/MaTriXy/material-components-web/commit/19bea2ad3d6c6aa36e0d033af7adebd010dcd4fa))
* **tooltip:** Center align tooltip label text. ([5dac1f6](https://github.com/MaTriXy/material-components-web/commit/5dac1f624606fc92682a4266ffd68bea21e57069))
* **tooltip:** Creating method to clear any in-progress animations before starting new ones. ([61f1a8d](https://github.com/MaTriXy/material-components-web/commit/61f1a8d8599f6dfaa7fc6c64d661010df47839b7))
* **tooltip:** Defining a z-index mixin. ([f4848eb](https://github.com/MaTriXy/material-components-web/commit/f4848eb3b57d81fd4fed1396cdc22a83344ccd72))
* **tooltip:** Foundation will now send a notification when the tooltip has been hidden. Methods added into the adapter to allow for this functionality. ([9274f85](https://github.com/MaTriXy/material-components-web/commit/9274f8504a905e04f24fba8f6a0e246d7ae3a638))
* add custom property support for select, textfield, and notched outline ([ec23858](https://github.com/MaTriXy/material-components-web/commit/ec2385881f93b75641db661038aae439b4c217d1))
* **button:** Add button ripple-states mixin, for simpler customization of button ripple color. ([ed7f324](https://github.com/MaTriXy/material-components-web/commit/ed7f324636287e95e8d966866a7c72af94377cf6))
* **button:** Add overflow ellipsis mixin ([#5352](https://github.com/MaTriXy/material-components-web/issues/5352)) ([47949b0](https://github.com/MaTriXy/material-components-web/commit/47949b08e0a2ec82178c638d8074c34c745409b4))
* **button:** Expand outlined touch target to include side borders ([ce6cb70](https://github.com/MaTriXy/material-components-web/commit/ce6cb7024d1da3b0e4fb5e2c67ba269dbb3098ec))
* **card:** Add elevation overlay structure ([#5282](https://github.com/MaTriXy/material-components-web/issues/5282)) ([aa0eba4](https://github.com/MaTriXy/material-components-web/commit/aa0eba489a33cb523ae1b5ac5b0ab24995731456))
* **checkbox:** Add support for checkbox CSS-only `indeterminate` checkbox ([b273afa](https://github.com/MaTriXy/material-components-web/commit/b273afa93441e6d0375f7df33d5b69d8a7e1cfa8))
* **chips:** Add chips styling ([1db5c9f](https://github.com/MaTriXy/material-components-web/commit/1db5c9fc842292715f8b4603ce0b979066f1c639))
* **chips:** Add configurable primary action focus ([deb212d](https://github.com/MaTriXy/material-components-web/commit/deb212de41e1073f7ff00af92e5f37bad0d8c4b0))
* **chips:** Add elevation overlay structure ([#5279](https://github.com/MaTriXy/material-components-web/issues/5279)) ([3e560b3](https://github.com/MaTriXy/material-components-web/commit/3e560b33a8fbf820a404596d76ae5f743e57b6a2))
* **chips:** Add focus{in|out} handlers ([10af6cf](https://github.com/MaTriXy/material-components-web/commit/10af6cf39cb2ae0a7deb9a951960f115f6ecdace))
* **chips:** Add keyCode support ([82fa986](https://github.com/MaTriXy/material-components-web/commit/82fa986b95be4c16271df50effda1046d015d35c))
* **chips:** Add trailing action feature targeting test ([bec0659](https://github.com/MaTriXy/material-components-web/commit/bec0659206aee793e6970d59c73f7969ab540b69))
* **chips:** Announce when chips are removed ([b3f70eb](https://github.com/MaTriXy/material-components-web/commit/b3f70ebded85240e75c6d1553cc9d0382b22c31d))
* **chips:** Create trailing action business logic ([9ebee4c](https://github.com/MaTriXy/material-components-web/commit/9ebee4ceb998e5fa651d4f147e5e39d43600db6e))
* **chips:** Expose trailing action chip files ([6b48781](https://github.com/MaTriXy/material-components-web/commit/6b48781bf97d3b08b8f35b9eacde2b87748ae2e1))
* **chips:** Reposition trailing action touch target width mixin ([3846ce3](https://github.com/MaTriXy/material-components-web/commit/3846ce311f65156f24dbd229100e660f1285bf5f))
* **chips:** Restructure trailing action mixins ([05f5e15](https://github.com/MaTriXy/material-components-web/commit/05f5e1583b81bc00dbcd2ae21ee0acc43b3e13b4))
* **chips:** Use trailing action component in chip ([058cfd2](https://github.com/MaTriXy/material-components-web/commit/058cfd23caa5c00f29c90f3d2fc9b813581ba974))
* **circular-progress:** Add foundation methods to get isDeterminate and progress value ([7d8f9c8](https://github.com/MaTriXy/material-components-web/commit/7d8f9c8d73f16c01ed4a941ab9510377a0aae219))
* **circular-progress:** Add Sass styles and tests ([bd33cb5](https://github.com/MaTriXy/material-components-web/commit/bd33cb56bdab7139052aeedbeec363f17b4dfc40))
* **circular-progress:** Add TS for foundation, adapter, component with tests ([548b1d4](https://github.com/MaTriXy/material-components-web/commit/548b1d4057f21e066a4c494a57a0c068c23e18cd))
* **data-table:** Add base styles to support pagination. ([927fa90](https://github.com/MaTriXy/material-components-web/commit/927fa902c3297a5a7cc9436e82cb81f3aabe1b4b))
* **data-table:** Add foundation methods to support loading state. ([e75deb8](https://github.com/MaTriXy/material-components-web/commit/e75deb8540fa70236087d335c9cd6280bd643285))
* **data-table:** Added styles for table in loading state ([35a32aa](https://github.com/MaTriXy/material-components-web/commit/35a32aaeac17e290e2e9f9a1310c5a44a08f624a))
* **data-table:** Added styles to support column sorting. ([17b9699](https://github.com/MaTriXy/material-components-web/commit/17b9699c4454a107043e5a1f9874a091089dd112))
* **data-table:** Added support for row header cell and other a11y improvements. ([27533c1](https://github.com/MaTriXy/material-components-web/commit/27533c19e9c72c5a27a33aaa764c1b6a05175cf5))
* **data-table:** Foundation changes to support column sorting ([6ee0355](https://github.com/MaTriXy/material-components-web/commit/6ee03557260d0a23296e36cba5aaa76fe0cf96a6))
* **data-table:** Set progress indicator styles based on table body height ([c026422](https://github.com/MaTriXy/material-components-web/commit/c0264227393df8eb9259a2b24c23b31fe0ca84f3))
* **dialog:** Add elevation overlay structure ([#5283](https://github.com/MaTriXy/material-components-web/issues/5283)) ([b8bc4a2](https://github.com/MaTriXy/material-components-web/commit/b8bc4a26ea70356cc96de8fd3266890048f0a3ab))
* **dialog:** Add padding mixin ([ad0c0c1](https://github.com/MaTriXy/material-components-web/commit/ad0c0c1034d0b9257a62d3dd9f5d27aada99f1f7))
* **dom:** Add focus trap utility. ([#5505](https://github.com/MaTriXy/material-components-web/issues/5505)) ([63f357d](https://github.com/MaTriXy/material-components-web/commit/63f357dbf5c7e84c3961aafc09e0fb4f4a9c3cda))
* **dom:** Add keyboard support ([5f24faa](https://github.com/MaTriXy/material-components-web/commit/5f24faacb1ef8996ae81f3a1c1e43910ba67b024))
* **dom:** Create announcer utility ([32c1df1](https://github.com/MaTriXy/material-components-web/commit/32c1df133f07679b44ce34ed9d11e22035f8d3d9))
* **elevation:** Update elevation mixins ([#5304](https://github.com/MaTriXy/material-components-web/issues/5304)) ([ba879b6](https://github.com/MaTriXy/material-components-web/commit/ba879b68bde09d713faa5cd77aea9d2bd2759e33))
* **fab:** Add elevation overlay structure ([#5278](https://github.com/MaTriXy/material-components-web/issues/5278)) ([e89750d](https://github.com/MaTriXy/material-components-web/commit/e89750dc78ea521561a03e020f4414479de5a5b9))
* **fab:** Add outline in high-contrast mode ([deda86d](https://github.com/MaTriXy/material-components-web/commit/deda86d8cc4665b334c4d21c541a4a30244fee72))
* **floating-label:** add feature targeting for styles ([#5287](https://github.com/MaTriXy/material-components-web/issues/5287)) ([b240bcc](https://github.com/MaTriXy/material-components-web/commit/b240bcc1bbb3cfd1f753918ec1553dbe1bb6d007))
* **floating-label:** add required modifier class ([047e6b3](https://github.com/MaTriXy/material-components-web/commit/047e6b337899a57290283cb0387f33738853cbc2))
* **form-field:** Add support for space-between ([e84b9c8](https://github.com/MaTriXy/material-components-web/commit/e84b9c816d32da6dec058d92fc21dc5ac8fec787)), closes [#5747](https://github.com/MaTriXy/material-components-web/issues/5747)
* **formfield:** add nowrap class/prop to MDC/MWC ([c4b4bba](https://github.com/MaTriXy/material-components-web/commit/c4b4bba9659bf15207e79b1f63fcc9946404d9c7))
* **formfield:** Remove trailing underscores from private properties ([2f052d8](https://github.com/MaTriXy/material-components-web/commit/2f052d82433a852d65785b1054ce4665ad1f6265))
* **iconbutton:** Add icon button variant which supports toggling aria label. ([f838c6e](https://github.com/MaTriXy/material-components-web/commit/f838c6e55672268de4e6e3b31b154d4f9050242f))
* **iconbutton:** Remove trailing underscores from private properties ([119e214](https://github.com/MaTriXy/material-components-web/commit/119e21426d73305fe348798cb7ce88077995fdd0))
* **line-ripple:** add active/inactive states to line-ripple ([b6c7f62](https://github.com/MaTriXy/material-components-web/commit/b6c7f624bc7d88e2e371efcb125c7a6bac55eab7))
* **line-ripple:** add feature targeting for styles ([#5292](https://github.com/MaTriXy/material-components-web/issues/5292)) ([391674a](https://github.com/MaTriXy/material-components-web/commit/391674a2649800f07e3ac1993a5fce157391fbd9))
* **linear-progress:** Add foundation methods to fetch progress and determinate state. ([4dc45af](https://github.com/MaTriXy/material-components-web/commit/4dc45af6c4bc81f5734a24c160046d283c1e9a6d))
* **linearprogress:** Remove trailing underscores from private properties ([893eb18](https://github.com/MaTriXy/material-components-web/commit/893eb1876220e5313f9db37365049b8c2282109c))
* **list:** Add mixin for selected item's text color ([bd8ca96](https://github.com/MaTriXy/material-components-web/commit/bd8ca96788c9cb793288b6aa5c406b220be0bd9c))
* **menu:** Add elevation overlay structure ([#5280](https://github.com/MaTriXy/material-components-web/issues/5280)) ([7fd17ce](https://github.com/MaTriXy/material-components-web/commit/7fd17ce5ed73c86b987c8a8e4cd08ea444fff8b7))
* **menu:** Add mixin to flatten menu top when opened-below anchor ([1e17c49](https://github.com/MaTriXy/material-components-web/commit/1e17c49b360fd0e01c9a74b92978031534003b5b))
* **menu-surface:** Add support for flipping menu corner horizontally. ([7b44824](https://github.com/MaTriXy/material-components-web/commit/7b448240263b45c6b474c2f758cd1c02f3c708ad))
* **notched-outline:** add feature targeting for styles ([#5289](https://github.com/MaTriXy/material-components-web/issues/5289)) ([c483774](https://github.com/MaTriXy/material-components-web/commit/c4837746ccebf375daa4c5dd891fea533bb134f7))
* **progress-indicator:** Add common interface for progress indicators ([#5564](https://github.com/MaTriXy/material-components-web/issues/5564)) ([ea863cb](https://github.com/MaTriXy/material-components-web/commit/ea863cb918b9c096e36a7bc653d6661757e71b64))
* **ripple:** Reorganize ripple opacities ([008c4d3](https://github.com/MaTriXy/material-components-web/commit/008c4d3191f9c2a76732688504d2299420734cdd))
* **select:** Add mixin for min-width ([09f5919](https://github.com/MaTriXy/material-components-web/commit/09f591967a42e4dc27c0f7022d9ae71e94c07c3d))
* **select:** Auto-align width of menu to select by default ([1b3dd84](https://github.com/MaTriXy/material-components-web/commit/1b3dd846db4da7dcb1baaf2003e35e462cb799b7))
* **select:** Change root to inline-block & add fullwidth flag ([2673adb](https://github.com/MaTriXy/material-components-web/commit/2673adb74397d55c9dcd8e5fd86b3efc87a13a28))
* **select:** Create additional state mixins ([744d751](https://github.com/MaTriXy/material-components-web/commit/744d751a0c0f154d5d0d05def88203b68c3a26a5))
* **select:** Implement density ([610c68d](https://github.com/MaTriXy/material-components-web/commit/610c68d97646f523eaff0bb26c08baa5903e9211))
* **select:** introduce custom validity ([fd8f8f2](https://github.com/MaTriXy/material-components-web/commit/fd8f8f2b77b0a17e25f78b5a510b7afe4bbd230b))
* **select:** Support typeahead ([b0fdca4](https://github.com/MaTriXy/material-components-web/commit/b0fdca4921afd58de567bd53b29c9b6e44dac5c1)), closes [#5705](https://github.com/MaTriXy/material-components-web/issues/5705)
* **select:** Update behavior on upArrow/downArrow ([d92d8c9](https://github.com/MaTriXy/material-components-web/commit/d92d8c93ee6d9c030e6d373ac2b8670ac56417ad))
* **select:** Update helper-text interactions ([142b154](https://github.com/MaTriXy/material-components-web/commit/142b1549ee0cf40b1f1531e79e53fe5e826f254d)), closes [#5463](https://github.com/MaTriXy/material-components-web/issues/5463)
* **switch:** Add elevation overlay structure ([#5281](https://github.com/MaTriXy/material-components-web/issues/5281)) ([50f110a](https://github.com/MaTriXy/material-components-web/commit/50f110a6cf8100e594bdbd6c02ee278c39924008))
* **switch:** Restructure DOM ([#5312](https://github.com/MaTriXy/material-components-web/issues/5312)) ([0ec1fab](https://github.com/MaTriXy/material-components-web/commit/0ec1fabc39222cac4446c8e2b85d74d2a5d21e1a))
* **text-field:** Truncate floating label width w/ icons ([c141801](https://github.com/MaTriXy/material-components-web/commit/c141801d50516a18fe53d4bc78591cefb4f57623))
* **textfield:** add end-alignment ([#5356](https://github.com/MaTriXy/material-components-web/issues/5356)) ([847dd1a](https://github.com/MaTriXy/material-components-web/commit/847dd1ada08bb0fd905adac7b7836540a0dd7e9c))
* **textfield:** add filled class variant ([b70bc60](https://github.com/MaTriXy/material-components-web/commit/b70bc601ef570dab4598ae6f3ca51bbf884fac96))
* **textfield:** add filled textarea variant ([4497b86](https://github.com/MaTriXy/material-components-web/commit/4497b86ed8b3e0ee0781dd6f795aa1ff332d2a3b))
* **textfield:** add forced LTR input ([490fbdc](https://github.com/MaTriXy/material-components-web/commit/490fbdc092c5c59d63f83407b83b37fb524ed0e5))
* **textfield:** add prefix and suffix ([6601d24](https://github.com/MaTriXy/material-components-web/commit/6601d24afdc3a3d0bd2a9b3fcca68c35c9415ec1)), closes [#1892](https://github.com/MaTriXy/material-components-web/issues/1892)
* **textfield:** add specific label-floating class ([a88c8e4](https://github.com/MaTriXy/material-components-web/commit/a88c8e4dc873ae74a3afbae0dc8635dfaa03e67b))
* **textfield:** allow character counter to be moved outside of the textarea. ([84e7ed5](https://github.com/MaTriXy/material-components-web/commit/84e7ed5825d3109c229d0f1f6c3edf97a3548226))
* **textfield:** Create float transition mixin ([ca61b65](https://github.com/MaTriXy/material-components-web/commit/ca61b656fababdf25adaa307963d4f37e6d413ec))
* **textfield:** Limit notched outline max-width ([0ab62a6](https://github.com/MaTriXy/material-components-web/commit/0ab62a65b17192a94102231ca63f54adc39675ae))
* **textfield:** move resize handle for textareas to bottom corner ([ed52af7](https://github.com/MaTriXy/material-components-web/commit/ed52af7677ad37138b6660ca11fbdb209be05b46))
* **typography:** add container baseline mixins for flexbox ([69edc6e](https://github.com/MaTriXy/material-components-web/commit/69edc6e2899636cfccb117376bb64dc0a267c588))
* **typography:** add CSS custom properties ([6a56f38](https://github.com/MaTriXy/material-components-web/commit/6a56f387c498e80cbac1cac5de6b4963325ffda6))
* Add index stylesheets to each MDC Web package ([#5539](https://github.com/MaTriXy/material-components-web/issues/5539)) ([1814866](https://github.com/MaTriXy/material-components-web/commit/181486643532e2166dced95daff9da786af3bdd1))
* Add index stylesheets to mdc-image-list and mdc-layout-gr… ([#5546](https://github.com/MaTriXy/material-components-web/issues/5546)) ([3a85313](https://github.com/MaTriXy/material-components-web/commit/3a85313ac121703e8aeac583502adf9863d96a8e))
* Use [@use](https://github.com/use) syntax in material-components-web Sass file and… ([#5573](https://github.com/MaTriXy/material-components-web/issues/5573)) ([b4727e4](https://github.com/MaTriXy/material-components-web/commit/b4727e43aa17afe03b240402ded590c0516267d5))
* **auto-init:** initialize components once with multiple mdc.autoInit() calls ([#4691](https://github.com/MaTriXy/material-components-web/issues/4691)) ([218d2e5](https://github.com/MaTriXy/material-components-web/commit/218d2e552e019b29b0587442dc8bafa5107b680e))
* **button:** Add disabled state color mixins ([#5232](https://github.com/MaTriXy/material-components-web/issues/5232)) ([b5eb51e](https://github.com/MaTriXy/material-components-web/commit/b5eb51e942b8f233bc1a9a5cf4b4d0c94fb8ea57))
* **button:** Add support for increased touch target to button. ([#4948](https://github.com/MaTriXy/material-components-web/issues/4948)) ([1d7a2e6](https://github.com/MaTriXy/material-components-web/commit/1d7a2e623236b47046d719270ea1508ba9a3e224))
* **button:** Setup elevation overlay ([#5256](https://github.com/MaTriXy/material-components-web/issues/5256)) ([3cbee6d](https://github.com/MaTriXy/material-components-web/commit/3cbee6dac7cafbe8986bad0a8593d870b00f5f32))
* **checkbox:** Add disabled state color mixins ([#5167](https://github.com/MaTriXy/material-components-web/issues/5167)) ([01628ef](https://github.com/MaTriXy/material-components-web/commit/01628efaa65dce47571fe4d6b1fcc30ba547f259))
* **checkbox:** Add support for 48px touch target ([#5025](https://github.com/MaTriXy/material-components-web/issues/5025)) ([b5685a8](https://github.com/MaTriXy/material-components-web/commit/b5685a81736372701f38ae69f9d7480b5d52a01b))
* **checkbox:** Added mixin to customize checkbox touch dimension. ([#4697](https://github.com/MaTriXy/material-components-web/issues/4697)) ([ff2873e](https://github.com/MaTriXy/material-components-web/commit/ff2873ed9b0f1afdedd5c9ced8e2a02fbb0a3a87))
* **checkbox:** Added mixin to customize checkbox touch dimension. ([#4697](https://github.com/MaTriXy/material-components-web/issues/4697)) ([42e41d8](https://github.com/MaTriXy/material-components-web/commit/42e41d872a6ee48e1ab9a4907b6f277aafe0f2a2))
* **checkbox:** Move ripple to child node ([#4981](https://github.com/MaTriXy/material-components-web/issues/4981)) ([9712b24](https://github.com/MaTriXy/material-components-web/commit/9712b24b2e7d16b988b793df5b3802052071c87c))
* **checkbox:** Toggle selected class with state ([#4612](https://github.com/MaTriXy/material-components-web/issues/4612)) ([5f06dce](https://github.com/MaTriXy/material-components-web/commit/5f06dcec30371a192c837225e953513159461bfd))
* **checkbox:** Updated cssClasses constant of checkbox ([#4674](https://github.com/MaTriXy/material-components-web/issues/4674)) ([bb25680](https://github.com/MaTriXy/material-components-web/commit/bb25680971f749957908cffd967a88e5e949c4cb))
* **chip:** Add density mixin to chip. ([#5109](https://github.com/MaTriXy/material-components-web/issues/5109)) ([bdf3430](https://github.com/MaTriXy/material-components-web/commit/bdf3430781bc9b8efcff47695f613c253739b78c))
* **chips:** Add feature targeting for styles ([#4693](https://github.com/MaTriXy/material-components-web/issues/4693)) ([0fdb889](https://github.com/MaTriXy/material-components-web/commit/0fdb8896c7fdf851054a8cf5079cfa30aaec7be3))
* **chips:** Add keyboard navigation ([#4844](https://github.com/MaTriXy/material-components-web/issues/4844)) ([42065fe](https://github.com/MaTriXy/material-components-web/commit/42065fe416bcd1b082d0d55ad985084f3d018ded)), closes [#2259](https://github.com/MaTriXy/material-components-web/issues/2259)
* **chips:** Add setAttr adapter method ([#4736](https://github.com/MaTriXy/material-components-web/issues/4736)) ([b6a606d](https://github.com/MaTriXy/material-components-web/commit/b6a606d3a5fb405c233327836161116b4d48daf6))
* **chips:** Add setAttr adapter method ([#4736](https://github.com/MaTriXy/material-components-web/issues/4736)) ([1e21acf](https://github.com/MaTriXy/material-components-web/commit/1e21acf6e985d9b13de533392a70e0e68b71cecd))
* **chips:** Add setSelectedFromChipset method ([#4872](https://github.com/MaTriXy/material-components-web/issues/4872)) ([283bd55](https://github.com/MaTriXy/material-components-web/commit/283bd55c829dd132013acf41f7239579b7e6dea0))
* **chips:** Add support for increased touch target to chips. ([#4970](https://github.com/MaTriXy/material-components-web/issues/4970)) ([6aa109d](https://github.com/MaTriXy/material-components-web/commit/6aa109d5b0b5010f979fde78a31a18c3888e489c))
* **chips:** Consolidate interaction event handlers ([#5251](https://github.com/MaTriXy/material-components-web/issues/5251)) ([5729943](https://github.com/MaTriXy/material-components-web/commit/5729943baf1726e931e26907c78774f2caec404e))
* **chips:** Use index for all chip operations ([#4869](https://github.com/MaTriXy/material-components-web/issues/4869)) ([07078bb](https://github.com/MaTriXy/material-components-web/commit/07078bbb62d9f598461c7ff3c6b51c67d7b339de))
* **chips:** Use semantic button elements ([#4627](https://github.com/MaTriXy/material-components-web/issues/4627)) ([848a5eb](https://github.com/MaTriXy/material-components-web/commit/848a5eb4449c7098c3d9e366e49feb7bcde0744b))
* **chips:** Use semantic button elements ([#4627](https://github.com/MaTriXy/material-components-web/issues/4627)) ([741124d](https://github.com/MaTriXy/material-components-web/commit/741124d40cbf10bfc60a7f54a758fca2b6379ffd))
* **data-table:** Added data table component ([#4889](https://github.com/MaTriXy/material-components-web/issues/4889)) ([7d3380a](https://github.com/MaTriXy/material-components-web/commit/7d3380a8b55a8a2fdcdf1193d8309f2a561b922b))
* **density:** Add density subsystem to components ([#5059](https://github.com/MaTriXy/material-components-web/issues/5059)) ([73a5e4c](https://github.com/MaTriXy/material-components-web/commit/73a5e4cfb01f73922501241f9f24ac9c2d059547))
* **dialog:** Add feature targeting for styles ([#4524](https://github.com/MaTriXy/material-components-web/issues/4524)) ([3556a93](https://github.com/MaTriXy/material-components-web/commit/3556a93e9217d7f9e84dfc480e8c1a8b7d4760b0))
* **drawer:** Make list instance publicly accessible ([#4516](https://github.com/MaTriXy/material-components-web/issues/4516)) ([f46941c](https://github.com/MaTriXy/material-components-web/commit/f46941ca78095ae4e13ad996112186cf8eea8722))
* **fab:** Add feature targeting for styles ([#4526](https://github.com/MaTriXy/material-components-web/issues/4526)) ([1ba7bdd](https://github.com/MaTriXy/material-components-web/commit/1ba7bddd091b5de497651dade7b07d3805648908))
* **feature-targeting:** Rename main mixins to end with `-core-styles` ([#4404](https://github.com/MaTriXy/material-components-web/issues/4404)) ([3102351](https://github.com/MaTriXy/material-components-web/commit/3102351dc569ad86cb03d9875b9b528aade305f0))
* **form-field:** add feature targeting for styles ([#4521](https://github.com/MaTriXy/material-components-web/issues/4521)) ([cd04f82](https://github.com/MaTriXy/material-components-web/commit/cd04f826c2dcad24499b46194b9ad565493a5795))
* **grid-list:** Add feature targeting for styles ([#4534](https://github.com/MaTriXy/material-components-web/issues/4534)) ([a8a6660](https://github.com/MaTriXy/material-components-web/commit/a8a666093a014f1142f81bd7010e65664ef9921d))
* **icon-button:** Add feature targeting for styles ([#4536](https://github.com/MaTriXy/material-components-web/issues/4536)) ([a58f2d2](https://github.com/MaTriXy/material-components-web/commit/a58f2d2410264b20242bf613875bac669827d407))
* **list:** Add disabled class name to constants ([#4558](https://github.com/MaTriXy/material-components-web/issues/4558)) ([f2db177](https://github.com/MaTriXy/material-components-web/commit/f2db1770d3a9a96968b565e13bab6ad376f0324b))
* **list:** Add mixin for disabled text opacity ([#4861](https://github.com/MaTriXy/material-components-web/issues/4861)) ([d68f8a7](https://github.com/MaTriXy/material-components-web/commit/d68f8a7a641062ee29d68ae20119e994f4f9e2e8))
* add feature targeting for styles to tab-related packages ([#4838](https://github.com/MaTriXy/material-components-web/issues/4838)) ([c7efc10](https://github.com/MaTriXy/material-components-web/commit/c7efc10afea37f724c7c258e80dfd95a455f31d8))
* **dialog:** Add Adapter#getInitialFocusEl. ([#4719](https://github.com/MaTriXy/material-components-web/issues/4719)) ([1108307](https://github.com/MaTriXy/material-components-web/commit/1108307499b3d4e7684ef4f54d9c069ec44d029c))
* **dialog:** Add Adapter#getInitialFocusEl. ([#4719](https://github.com/MaTriXy/material-components-web/issues/4719)) ([bea1e76](https://github.com/MaTriXy/material-components-web/commit/bea1e76fc681b5b357fcddc232e7a06b53698c10))
* **dialog:** Add dialog mixin for dialogs with increased touch target buttons. ([#5024](https://github.com/MaTriXy/material-components-web/issues/5024)) ([2ef1ddd](https://github.com/MaTriXy/material-components-web/commit/2ef1ddd66b11709c7e22c674587e95c888a4842e))
* **drawer:** add feature targeting for styles ([#4877](https://github.com/MaTriXy/material-components-web/issues/4877)) ([4d65d29](https://github.com/MaTriXy/material-components-web/commit/4d65d29704dc627c39675ff2086eb4717149302a))
* **elevation:** Add elevation overlay mixins ([#5249](https://github.com/MaTriXy/material-components-web/issues/5249)) ([b4cfdc4](https://github.com/MaTriXy/material-components-web/commit/b4cfdc40b7c4a3d3fc48df2b68b7091552c27610))
* **fab:** Add support for increased touch target to mini FAB. ([#5231](https://github.com/MaTriXy/material-components-web/issues/5231)) ([0c4d8f3](https://github.com/MaTriXy/material-components-web/commit/0c4d8f3923f9a089132ed8dca4062b72d3576aca))
* **icon-button:** Add density mixin to icon button ([#5122](https://github.com/MaTriXy/material-components-web/issues/5122)) ([37d6458](https://github.com/MaTriXy/material-components-web/commit/37d64581dbaf73b53c1368ebeaba16727f6c9d86))
* **icon-button:** Add disabled state color mixins ([#5246](https://github.com/MaTriXy/material-components-web/issues/5246)) ([7161170](https://github.com/MaTriXy/material-components-web/commit/7161170f2e39b73b69b97dec11ebf94e1d3a10c4))
* **image-list:** Add feature targeting for styles ([#4535](https://github.com/MaTriXy/material-components-web/issues/4535)) ([0bfeabb](https://github.com/MaTriXy/material-components-web/commit/0bfeabb4cc4c5161be02e3879dc7f551f56c5ce2))
* **linear-progress:** add feature targeting for styles ([#4898](https://github.com/MaTriXy/material-components-web/issues/4898)) ([7ec18c6](https://github.com/MaTriXy/material-components-web/commit/7ec18c6c057254abd3bc11923cf82a702a9ee2b9))
* **list:** Add density mixin to list ([#5069](https://github.com/MaTriXy/material-components-web/issues/5069)) ([5132f89](https://github.com/MaTriXy/material-components-web/commit/5132f8997e5766f1cda216093f867f4ba253def0))
* **list:** Add setEnabled to foundation ([#5049](https://github.com/MaTriXy/material-components-web/issues/5049)) ([c2b4407](https://github.com/MaTriXy/material-components-web/commit/c2b4407376a74f7377aab4ffa99ed7267681ae77))
* **list:** Automatically use appropriate aria attribute for single selection list. ([#4479](https://github.com/MaTriXy/material-components-web/issues/4479)) ([077c809](https://github.com/MaTriXy/material-components-web/commit/077c80970b0cd2919f2f50bca83b44ae21074f70))
* **menu:** add setEnabled to allow dynamic enabling or disabling menu item ([#5054](https://github.com/MaTriXy/material-components-web/issues/5054)) ([4751d64](https://github.com/MaTriXy/material-components-web/commit/4751d64f122b5de91b59847e29f614c5566a9785))
* **menu:** add setSelectedIndex to set selected item in menu selection group ([#4620](https://github.com/MaTriXy/material-components-web/issues/4620)) ([b1e0888](https://github.com/MaTriXy/material-components-web/commit/b1e08887c6f2fb1cef0d173d4868634ddcbce66a))
* **menu:** add setSelectedIndex to set selected item in menu selection group ([#4620](https://github.com/MaTriXy/material-components-web/issues/4620)) ([3a280c6](https://github.com/MaTriXy/material-components-web/commit/3a280c60d3c4c1984b50e8d447d35af39831162f))
* **menu:** Added new API to manually set focus when menu is opened ([#4468](https://github.com/MaTriXy/material-components-web/issues/4468)) ([42ae5c3](https://github.com/MaTriXy/material-components-web/commit/42ae5c3295220c4b94d64ddfe92a2db27254b650))
* **menu:** Focus management features & accessibility improvements ([#4587](https://github.com/MaTriXy/material-components-web/issues/4587)) ([8d91b93](https://github.com/MaTriXy/material-components-web/commit/8d91b93b6622c279fd085f1a2dd53cf75542c03e))
* **radio:** Add density mixin to radio ([#5118](https://github.com/MaTriXy/material-components-web/issues/5118)) ([199534d](https://github.com/MaTriXy/material-components-web/commit/199534d61bcce7064d2762d0f2d837a8c1e3639b))
* **radio:** Add disabled state color mixins ([#5168](https://github.com/MaTriXy/material-components-web/issues/5168)) ([b5c6d66](https://github.com/MaTriXy/material-components-web/commit/b5c6d66b40765c4eacf079e91230506339c1346b))
* **radio:** Add support for 48px touch target ([#5032](https://github.com/MaTriXy/material-components-web/issues/5032)) ([87b0a4c](https://github.com/MaTriXy/material-components-web/commit/87b0a4c35e6162857f89026027c18f0c1b2697bf))
* **radio:** Move ripple to child element ([#4983](https://github.com/MaTriXy/material-components-web/issues/4983)) ([100ab37](https://github.com/MaTriXy/material-components-web/commit/100ab37d8619b7d976658c6085e653f7e1932bb4))
* **ripple:** Add support for ripple target to mixins. ([#4880](https://github.com/MaTriXy/material-components-web/issues/4880)) ([08dbe69](https://github.com/MaTriXy/material-components-web/commit/08dbe69656604b4fa3afacc677a17d1fa9c4d743))
* **rtl:** Added a flag to turn-off mdc-rtl CSS ([#4996](https://github.com/MaTriXy/material-components-web/issues/4996)) ([eb87f06](https://github.com/MaTriXy/material-components-web/commit/eb87f0667523d650dbee72a1f84b19eed03c0f5a))
* **slider:** add feature targeting for styles ([#4871](https://github.com/MaTriXy/material-components-web/issues/4871)) ([3ee2675](https://github.com/MaTriXy/material-components-web/commit/3ee2675e4214d65f9072e4f14bf0413ce771be7d))
* **snackbar:** add feature targeting for styles ([#4876](https://github.com/MaTriXy/material-components-web/issues/4876)) ([1b7aea1](https://github.com/MaTriXy/material-components-web/commit/1b7aea152dd9a8ae1d814052b8faf61290415136))
* **snackbar:** Add option for indefinite timeout ([#4998](https://github.com/MaTriXy/material-components-web/issues/4998)) ([4f11851](https://github.com/MaTriXy/material-components-web/commit/4f11851a3375a0eafd6b3d4a4f43db2edcb89951))
* **switch:** Add density support for switch component. ([#5124](https://github.com/MaTriXy/material-components-web/issues/5124)) ([2c793b4](https://github.com/MaTriXy/material-components-web/commit/2c793b43158cd583d490213e62d6f495fce1aa8f)), closes [#5104](https://github.com/MaTriXy/material-components-web/issues/5104)
* **switch:** add ripple opacity customization mixins ([#5126](https://github.com/MaTriXy/material-components-web/issues/5126)) ([8c0273f](https://github.com/MaTriXy/material-components-web/commit/8c0273fea6a8d64a5965f963fed288b0919e3142))
* **tab:** Add Tab Sass mixins targeting active state colors ([#4522](https://github.com/MaTriXy/material-components-web/issues/4522)) ([31376f7](https://github.com/MaTriXy/material-components-web/commit/31376f735dcdb92113b6d5cdc030f2d78eb9b73b))
* **tab:** Add text transform mixin ([#5144](https://github.com/MaTriXy/material-components-web/issues/5144)) ([22d7ad2](https://github.com/MaTriXy/material-components-web/commit/22d7ad2fb1796fbd71a3a5ee9c7ab2e77c60e34e))
* **tab:** Implement a base states color mixin for Tab ([#4421](https://github.com/MaTriXy/material-components-web/issues/4421)) ([35c3721](https://github.com/MaTriXy/material-components-web/commit/35c37218bdd4f1bcadec59de1d0c02ccb50bd0de))
* **tab:** Improved mixins ([#4675](https://github.com/MaTriXy/material-components-web/issues/4675)) ([252009f](https://github.com/MaTriXy/material-components-web/commit/252009fcd5a10f2c816ab487103d52d0280f2dd7))
* **tab-bar:** Add a mixin to set scroller animation ([#5172](https://github.com/MaTriXy/material-components-web/issues/5172)) ([d7c938a](https://github.com/MaTriXy/material-components-web/commit/d7c938a29a925e1be0d7af69d13d8c4b5d54f3cb))
* **tab-bar:** Add density mixin to tab-bar ([#5070](https://github.com/MaTriXy/material-components-web/issues/5070)) ([45dc002](https://github.com/MaTriXy/material-components-web/commit/45dc002e60a25a8a49c74a5f40b35faad04404f2))
* **tab-bar:** Allow activation of tab without previous active tab ([#4615](https://github.com/MaTriXy/material-components-web/issues/4615)) ([7d4124d](https://github.com/MaTriXy/material-components-web/commit/7d4124de70ba347c9e0db1c70ef279fa95f1a046))
* **tab-scroller:** Add incrementScrollImmediate to bypass animation ([#5184](https://github.com/MaTriXy/material-components-web/issues/5184)) ([2b878b3](https://github.com/MaTriXy/material-components-web/commit/2b878b3e7c4493e5a5a8b2b9d5558265486b6657)), closes [#5123](https://github.com/MaTriXy/material-components-web/issues/5123)
* **tab-scroller:** Mixin for scroll transition ([#5154](https://github.com/MaTriXy/material-components-web/issues/5154)) ([efda83d](https://github.com/MaTriXy/material-components-web/commit/efda83dbed6299225a32a5add8c9ca12217c25d0))
* **tabs:** Add active tab states mixin ([#4603](https://github.com/MaTriXy/material-components-web/issues/4603)) ([0e9f3f5](https://github.com/MaTriXy/material-components-web/commit/0e9f3f55251a811139e62d309c8c69572711dcfa))
* **text-field:** Add density mixin to text field variants ([#5066](https://github.com/MaTriXy/material-components-web/issues/5066)) ([a12101d](https://github.com/MaTriXy/material-components-web/commit/a12101d6d7d44a5add3d7e3301fc721dfa98ffc9))
* **text-field:** Add disabled state color mixins ([#5208](https://github.com/MaTriXy/material-components-web/issues/5208)) ([66299b6](https://github.com/MaTriXy/material-components-web/commit/66299b64613e8399af263d7021f93f9cdaf74ae3))
* **text-field:** Center align inner elements for dynamic height ([#4990](https://github.com/MaTriXy/material-components-web/issues/4990)) ([4d94b22](https://github.com/MaTriXy/material-components-web/commit/4d94b2202bbb754622725a87c3126ac7d88e7230))
* **text-field:** define icon's cssClasses ([#4614](https://github.com/MaTriXy/material-components-web/issues/4614)) ([816139c](https://github.com/MaTriXy/material-components-web/commit/816139c1a10647938f345ab7d40b94b3e2ce91ed))
* **theme:** Add support for arbitrary CSS vars with fallback ([#4470](https://github.com/MaTriXy/material-components-web/issues/4470)) ([0bfb393](https://github.com/MaTriXy/material-components-web/commit/0bfb393407727b9ad5e8de1e8dda6ea6a0ee21fd))
* **top-app-bar:** use mdc-icon-button styles instead of top app bar ([#4745](https://github.com/MaTriXy/material-components-web/issues/4745)) ([605f77e](https://github.com/MaTriXy/material-components-web/commit/605f77e50fe35ea9c7cc9e245a38af634655fa83))
* **top-app-bar:** use mdc-icon-button styles instead of top app bar ([#4745](https://github.com/MaTriXy/material-components-web/issues/4745)) ([f8c561c](https://github.com/MaTriXy/material-components-web/commit/f8c561c08172c6c43ea40f772af4c7577c271af9))
* **touch-target:** Add touch target mixins. ([#4940](https://github.com/MaTriXy/material-components-web/issues/4940)) ([b2e0fea](https://github.com/MaTriXy/material-components-web/commit/b2e0feac33cbdcb726e8b88ce5f1fb8fb3eef95c))
* Convert packages to TypeScript ([#4451](https://github.com/MaTriXy/material-components-web/issues/4451)) ([ad5743a](https://github.com/MaTriXy/material-components-web/commit/ad5743ae665d138c38a23ba36a3d2f63b5c388d5)), closes [#4225](https://github.com/MaTriXy/material-components-web/issues/4225)
* **button:** Add trailing icon support via label element ([#4159](https://github.com/MaTriXy/material-components-web/issues/4159)) ([fa41579](https://github.com/MaTriXy/material-components-web/commit/fa415797bed1126073fe7fb6aa421b179b51a4a4))
* **card:** add feature targeting for styles ([#4301](https://github.com/MaTriXy/material-components-web/issues/4301)) ([92db33b](https://github.com/MaTriXy/material-components-web/commit/92db33b7702e6e25889e5232528ca2847a54e503))
* **checkbox:** add feature targeting to remaining public mixins ([#4315](https://github.com/MaTriXy/material-components-web/issues/4315)) ([4bc18d1](https://github.com/MaTriXy/material-components-web/commit/4bc18d1e5d8681593c52d6c0f0f7e85132edfd29))
* **checkbox:** Declare all Sass variables as `!default` ([de6c833](https://github.com/MaTriXy/material-components-web/commit/de6c8332caa042caf277c83907d0078475028450)), closes [#3708](https://github.com/MaTriXy/material-components-web/issues/3708)
* **checkbox:** Support customizing the color of the stroke in the marked state ([#3412](https://github.com/MaTriXy/material-components-web/issues/3412)) ([7f47386](https://github.com/MaTriXy/material-components-web/commit/7f4738692fe686adcd559cd3bc9db8f618502e34))
* **chips:** Add a mixin to handle chip elevation transitions ([#3579](https://github.com/MaTriXy/material-components-web/issues/3579)) ([eadde7a](https://github.com/MaTriXy/material-components-web/commit/eadde7a9bba7281b9c3f712898dcf98df37d5bb7))
* **chips:** Add mixins to customize horizontal padding and icon margins ([#3530](https://github.com/MaTriXy/material-components-web/issues/3530)) ([43aeea4](https://github.com/MaTriXy/material-components-web/commit/43aeea4fcffb63997bcd919346623f37efbba05d))
* **chips:** make deselect and toggleSelect private. Update handleChipInteraction/Removal API ([#3617](https://github.com/MaTriXy/material-components-web/issues/3617)) ([73ab5a0](https://github.com/MaTriXy/material-components-web/commit/73ab5a0d0c38ad5fd2068a4a20a90915fc5c7fc8))
* **chips:** Move logic for calculating chip bounding rect into a foundation method ([#4243](https://github.com/MaTriXy/material-components-web/issues/4243)) ([b30f5e2](https://github.com/MaTriXy/material-components-web/commit/b30f5e2e5b6e0012be45f23791133e34fceae74b))
* **dialog:** Initial prototype ([#3413](https://github.com/MaTriXy/material-components-web/issues/3413)) ([9d133b2](https://github.com/MaTriXy/material-components-web/commit/9d133b2f3963bd8e4d8620025cd22df59976be06))
* **dialog:** Integrate with MDC List; add keyboard action handling ([#3594](https://github.com/MaTriXy/material-components-web/issues/3594)) ([7b6d86b](https://github.com/MaTriXy/material-components-web/commit/7b6d86bf77eeecd41e19e1181bd62e93e8c98538))
* **dialog:** Reverse buttons when stacked; allow toggling auto-stack ([#3573](https://github.com/MaTriXy/material-components-web/issues/3573)) ([2e7805b](https://github.com/MaTriXy/material-components-web/commit/2e7805bd7e876f7d85e6c909919d4961368bc0bf))
* **dialog:** Support default action button ([#3600](https://github.com/MaTriXy/material-components-web/issues/3600)) ([3aa18e2](https://github.com/MaTriXy/material-components-web/commit/3aa18e2619fe53f71f0453fd6ffb806587036df5))
* **dialog:** Support reporting action in ancestor element ([#3572](https://github.com/MaTriXy/material-components-web/issues/3572)) ([fcbef20](https://github.com/MaTriXy/material-components-web/commit/fcbef207866adfcdd8b5e45680573a43ec0f74ad))
* **dom:** Add closest ponyfill ([#3559](https://github.com/MaTriXy/material-components-web/issues/3559)) ([eddf66c](https://github.com/MaTriXy/material-components-web/commit/eddf66c9c03ac46d1a55236fb936f6b3eee9d7a9))
* **feature-targeting:** Elevation, ripple, theme, typography ([#4383](https://github.com/MaTriXy/material-components-web/issues/4383)) ([4c2a63c](https://github.com/MaTriXy/material-components-web/commit/4c2a63cec467e8e72e5704f3e77578873b9f8d00))
* **list:** add feature targeting for styles ([#4303](https://github.com/MaTriXy/material-components-web/issues/4303)) ([c994156](https://github.com/MaTriXy/material-components-web/commit/c9941566b466a0310636527f453812ac067549bc))
* **list:** Add notifyAction adapter for action on list item. ([#4144](https://github.com/MaTriXy/material-components-web/issues/4144)) ([6ed35b1](https://github.com/MaTriXy/material-components-web/commit/6ed35b1203fc07895a9861f9461198653970482e))
* **list:** Toggle radio checkbox ([#3546](https://github.com/MaTriXy/material-components-web/issues/3546)) ([f59b6e6](https://github.com/MaTriXy/material-components-web/commit/f59b6e67abbb0a7b5ec192995764d90d6d98aecd))
* **list:** Update list to toggle tabindex of radio/checkbox ([#3542](https://github.com/MaTriXy/material-components-web/issues/3542)) ([13abb24](https://github.com/MaTriXy/material-components-web/commit/13abb24232b18a54d85c7fde4f0b30a633977e05))
* **menu:** add feature targeting for styles ([#4278](https://github.com/MaTriXy/material-components-web/issues/4278)) ([97a8585](https://github.com/MaTriXy/material-components-web/commit/97a8585331695a63f0df358df281cfc73c5e96f7))
* **menu:** add feature targeting to remaining public mixins ([#4317](https://github.com/MaTriXy/material-components-web/issues/4317)) ([5928c00](https://github.com/MaTriXy/material-components-web/commit/5928c00f43b6ce0093174bf53eeed53357844d62))
* **menu:** Expose handleSelection API to public ([#3950](https://github.com/MaTriXy/material-components-web/issues/3950)) ([7f02a64](https://github.com/MaTriXy/material-components-web/commit/7f02a64fe23cd31aae76f58b373aa31ba8caca63))
* **menu-surface:** add feature targeting for styles ([#4279](https://github.com/MaTriXy/material-components-web/issues/4279)) ([56b8467](https://github.com/MaTriXy/material-components-web/commit/56b846787c5afa8ac9e1ddda6e54eb2a8479665e))
* **menu-surface:** Update setPosition adapter API to use numeric values ([#4351](https://github.com/MaTriXy/material-components-web/issues/4351)) ([701ed5c](https://github.com/MaTriXy/material-components-web/commit/701ed5cf40e2df22ec321c6e94c4e72f6d2e033d)), closes [#4273](https://github.com/MaTriXy/material-components-web/issues/4273)
* **radio:** add feature targeting for styles ([#4270](https://github.com/MaTriXy/material-components-web/issues/4270)) ([eb8b8f6](https://github.com/MaTriXy/material-components-web/commit/eb8b8f6aeb8e846f0af27c4ea56641966e61b99d))
* **radio:** add feature targeting to remaining public mixins ([#4318](https://github.com/MaTriXy/material-components-web/issues/4318)) ([9f8ee9e](https://github.com/MaTriXy/material-components-web/commit/9f8ee9e90d13f753752b417774cc8e68c82a9d92))
* **ripple:** Reduce press opacity by 25% ([#4350](https://github.com/MaTriXy/material-components-web/issues/4350)) ([f5d2170](https://github.com/MaTriXy/material-components-web/commit/f5d217055a8dbcb2899daeb60fa29593b97178ec))
* **select:** Add enhanced select variant ([#3949](https://github.com/MaTriXy/material-components-web/issues/3949)) ([35697a5](https://github.com/MaTriXy/material-components-web/commit/35697a579f51a9a76f6638b2faf414be311c1d88))
* **shape:** add feature targeting to public mixins ([#4384](https://github.com/MaTriXy/material-components-web/issues/4384)) ([e0860dd](https://github.com/MaTriXy/material-components-web/commit/e0860dd15223cc3282ffad542553edfefdc367b2))
* **shape:** Added Shape subsystem and integrated with all components ([#3626](https://github.com/MaTriXy/material-components-web/issues/3626)) ([d5f0897](https://github.com/MaTriXy/material-components-web/commit/d5f08976738aaeffe577a508ae652d3b1a302ee3))
* **snackbar:** Update to match latest design guidelines ([#4166](https://github.com/MaTriXy/material-components-web/issues/4166)) ([33d30e6](https://github.com/MaTriXy/material-components-web/commit/33d30e67dab414feb56e27d5c409d25d8e790682)), closes [#4005](https://github.com/MaTriXy/material-components-web/issues/4005) [#3981](https://github.com/MaTriXy/material-components-web/issues/3981) [#2916](https://github.com/MaTriXy/material-components-web/issues/2916) [#2628](https://github.com/MaTriXy/material-components-web/issues/2628) [#1466](https://github.com/MaTriXy/material-components-web/issues/1466) [#1398](https://github.com/MaTriXy/material-components-web/issues/1398) [#1258](https://github.com/MaTriXy/material-components-web/issues/1258) [#11](https://github.com/MaTriXy/material-components-web/issues/11) [#2813](https://github.com/MaTriXy/material-components-web/issues/2813)
* **switch:** add feature targeting for styles ([#4275](https://github.com/MaTriXy/material-components-web/issues/4275)) ([4836293](https://github.com/MaTriXy/material-components-web/commit/483629326eb7b8e27a58b47bf7df50cecf481de8))
* **tab:** Get tabs by their ID ([#4149](https://github.com/MaTriXy/material-components-web/issues/4149)) ([2d35220](https://github.com/MaTriXy/material-components-web/commit/2d352208ab8e5deb4a6116330c348d0447f008d9))
* **tab-bar:** Add focusOnActivate flag ([#3748](https://github.com/MaTriXy/material-components-web/issues/3748)) ([313618a](https://github.com/MaTriXy/material-components-web/commit/313618a52e930ecaeb5d3081735d719f30ca4e2b))
* **text-field:** Add focus API to component ([#4020](https://github.com/MaTriXy/material-components-web/issues/4020)) ([edcb939](https://github.com/MaTriXy/material-components-web/commit/edcb9393fd1e5578ff29d0a5d60d8649f7001326))
* **text-field:** Added support for character counter. ([#4244](https://github.com/MaTriXy/material-components-web/issues/4244)) ([0bcc0e7](https://github.com/MaTriXy/material-components-web/commit/0bcc0e77fdb588a9a736f03cc64bd7670d3b794e))
* **text-field:** Added support for text field without label ([#4285](https://github.com/MaTriXy/material-components-web/issues/4285)) ([bf956fa](https://github.com/MaTriXy/material-components-web/commit/bf956fa4edd6ed2e9c96a9bf1fe38f2ce7a85635))
* **typography:** add feature targeting for styles ([#4305](https://github.com/MaTriXy/material-components-web/issues/4305)) ([8691cf8](https://github.com/MaTriXy/material-components-web/commit/8691cf85abc44be0b878c325fc09e55d86e281a1))
* Add feature targeting support and apply to mdc-button ([#4228](https://github.com/MaTriXy/material-components-web/issues/4228)) ([531dffb](https://github.com/MaTriXy/material-components-web/commit/531dffb268fed231b05cccbd25e7c313aaa66e52))
* update default npm export to ES5 js files ([#3245](https://github.com/MaTriXy/material-components-web/issues/3245)) ([514f9f8](https://github.com/MaTriXy/material-components-web/commit/514f9f894a73999ef9740888944433acc7370669))
* **auto-init:** return initialized components ([#1333](https://github.com/MaTriXy/material-components-web/issues/1333)) ([19955bf](https://github.com/MaTriXy/material-components-web/commit/19955bfaa8b9e31b9f519246dcf501a647d49c57))
* **chips:** Expose method to begin chip exit animation ([#2845](https://github.com/MaTriXy/material-components-web/issues/2845)) ([eb00fd3](https://github.com/MaTriXy/material-components-web/commit/eb00fd33376b94fff3e7adbf0985ae93f8283018))
* **chips:** Make chip exit on trailing icon click optional ([#2893](https://github.com/MaTriXy/material-components-web/issues/2893)) ([9178d46](https://github.com/MaTriXy/material-components-web/commit/9178d460924284521cfbac1458f904e6ea31d912))
* **chips:** Pass chip ids instead of foundations in events  ([#3265](https://github.com/MaTriXy/material-components-web/issues/3265)) ([7ce0fba](https://github.com/MaTriXy/material-components-web/commit/7ce0fba6fd782ca25cc389ca07ec34bb0f09a54c))
* **dom:** Create `mdc-dom` package with `Element.matches()` ponyfill ([#3515](https://github.com/MaTriXy/material-components-web/issues/3515)) ([91d8fe8](https://github.com/MaTriXy/material-components-web/commit/91d8fe8a5da3e8b62fc6712037367d6f9ce575e2)), closes [#3413](https://github.com/MaTriXy/material-components-web/issues/3413) [#1104](https://github.com/MaTriXy/material-components-web/issues/1104)
* **drawer:** Allow customizing drawer width ([#3459](https://github.com/MaTriXy/material-components-web/issues/3459)) ([247f75f](https://github.com/MaTriXy/material-components-web/commit/247f75f3724ef1806efba0a1d5e94634743a3fa8))
* **drawer:** Improved navigation drawer  ([#3417](https://github.com/MaTriXy/material-components-web/issues/3417)) ([3aa211d](https://github.com/MaTriXy/material-components-web/commit/3aa211d53f7cec023225dcabcb818e87b7c19a79))
* **drawer:** New sass mixin to set z-index ([#3453](https://github.com/MaTriXy/material-components-web/issues/3453)) ([cf3084f](https://github.com/MaTriXy/material-components-web/commit/cf3084f11e86bae82b1611a5376a5e93910d6f72))
* **fab:** Add Extended FAB ([14cb0bf](https://github.com/MaTriXy/material-components-web/commit/14cb0bf562790c0f29b6ad8120be5ad3e6576d4c))
* **fab:** Enable padding customization ([#2959](https://github.com/MaTriXy/material-components-web/issues/2959)) ([1f5fd1f](https://github.com/MaTriXy/material-components-web/commit/1f5fd1f76117ae884113c6e5f8b7a094f5f50c45))
* **floating-label:** Add max-width mixin ([#2956](https://github.com/MaTriXy/material-components-web/issues/2956)) ([66f8bf7](https://github.com/MaTriXy/material-components-web/commit/66f8bf76cdb17902e7b21dddf83860fdf8d30c1c))
* **icon-button:** Add SVG support ([#3310](https://github.com/MaTriXy/material-components-web/issues/3310)) ([25fa51e](https://github.com/MaTriXy/material-components-web/commit/25fa51ee9041a6e83ac658451c9e826354b4c348))
* **icon-button:** update event handling to new standard ([#3165](https://github.com/MaTriXy/material-components-web/issues/3165)) ([531867e](https://github.com/MaTriXy/material-components-web/commit/531867e20da667add271ef19ea9e8ef5efcbfafe))
* **list:** Add arrow key a11y support.  ([#2871](https://github.com/MaTriXy/material-components-web/issues/2871)) ([7c06e9f](https://github.com/MaTriXy/material-components-web/commit/7c06e9f527f8b9efe38e55d2ce9eb78d9595b6f7))
* **list:** Add single selection ([#2970](https://github.com/MaTriXy/material-components-web/issues/2970)) ([cd1f972](https://github.com/MaTriXy/material-components-web/commit/cd1f9724f930e452bf29628192b8b6ef475abfd4))
* **list:** Updated two-line list to use typography baseline to match spec. ([#3085](https://github.com/MaTriXy/material-components-web/issues/3085)) ([4d11b37](https://github.com/MaTriXy/material-components-web/commit/4d11b373f31a310f030d423523083427cadc144b))
* **menu:** Adds new menu, menu-surface. ([#3311](https://github.com/MaTriXy/material-components-web/issues/3311)) ([6439c5b](https://github.com/MaTriXy/material-components-web/commit/6439c5bfc2222e079677f8719576db3fde4e9b97))
* **select:** Add outlined variant ([#2674](https://github.com/MaTriXy/material-components-web/issues/2674)) ([4863125](https://github.com/MaTriXy/material-components-web/commit/48631259955b282e43a9e7d3e42e3ab18018eb77))
* **switch:** Merge updated switch into master ([#3214](https://github.com/MaTriXy/material-components-web/issues/3214)) ([19724f1](https://github.com/MaTriXy/material-components-web/commit/19724f158bc33064384537ed77c766ce60b5627c)), closes [#2825](https://github.com/MaTriXy/material-components-web/issues/2825)
* **switch:** Move component specific logic out of foundation ([#3342](https://github.com/MaTriXy/material-components-web/issues/3342)) ([e1e4465](https://github.com/MaTriXy/material-components-web/commit/e1e44650b5e45dfbfb4fb7740964b1fee678d8a9))
* **tab:** Move event registration to component ([#3331](https://github.com/MaTriXy/material-components-web/issues/3331)) ([f2ac793](https://github.com/MaTriXy/material-components-web/commit/f2ac7936a23c847c78175ed043eca4350d18aa59))
* **tab-bar:** Launch tab, tab indicator, tab scroller, tab bar ([#3252](https://github.com/MaTriXy/material-components-web/issues/3252)) ([78bf4bc](https://github.com/MaTriXy/material-components-web/commit/78bf4bc30396890164f80f4e086feb1a473828bf))
* **tab-bar:** Support manual and automatic activation behavior ([#3303](https://github.com/MaTriXy/material-components-web/issues/3303)) ([7182fa1](https://github.com/MaTriXy/material-components-web/commit/7182fa18c5137c1416602fa122e4fa2920984cf1))
* **tab-indicator:** Remove transitionend event handling ([#3337](https://github.com/MaTriXy/material-components-web/issues/3337)) ([c8af69b](https://github.com/MaTriXy/material-components-web/commit/c8af69b1da53726f4856fafc64d88644fe29bfa0))
* **text-field:** add feature targeting for styles ([#5378](https://github.com/MaTriXy/material-components-web/issues/5378)) ([e8a9936](https://github.com/MaTriXy/material-components-web/commit/e8a993677858893965608a55931d7e54c84e8c5d))
* **text-field:** Add support for leading/trailing icons at the same time ([#3451](https://github.com/MaTriXy/material-components-web/issues/3451)) ([6b3cfe5](https://github.com/MaTriXy/material-components-web/commit/6b3cfe5f3ee1158593f63ff77b7537b36e87dcfb))
* **text-field:** New API to enable/disable native input validation for custom validity ([#3084](https://github.com/MaTriXy/material-components-web/issues/3084)) ([bd49920](https://github.com/MaTriXy/material-components-web/commit/bd49920469e7f72404f6ec995fd6329147cd2534))
* **text-field:** Support for types- color, date, datetime-local, etc ([#2854](https://github.com/MaTriXy/material-components-web/issues/2854)) ([0d02f1f](https://github.com/MaTriXy/material-components-web/commit/0d02f1f7c023a1912a35a2dac84e34708c113493))
* **textfield:** required outlined modifier for textarea ([b10d0d7](https://github.com/MaTriXy/material-components-web/commit/b10d0d7f1911b381a47d39b5d0bc4543089efb3e))
* **theme:** Add error and on-error support ([#3469](https://github.com/MaTriXy/material-components-web/issues/3469)) ([b10095f](https://github.com/MaTriXy/material-components-web/commit/b10095fb9d890bf8ae4e6a4fe88642c74aba9177))
* **theme:** Added new function for text emphasis opacities ([f841afe](https://github.com/MaTriXy/material-components-web/commit/f841afe2c0c9430b1cf8a2f845cbedd83824c24c))
* update to MIT license ([#3376](https://github.com/MaTriXy/material-components-web/issues/3376)) ([2cf8487](https://github.com/MaTriXy/material-components-web/commit/2cf84876fec45a0c8d31eff2ec47d48b11c8fdac))
* **typography:**  Update variable reference to work for newer versions of ruby-sass ([#3047](https://github.com/MaTriXy/material-components-web/issues/3047)) ([0dfad9a](https://github.com/MaTriXy/material-components-web/commit/0dfad9adc3a66169c9c765628a813f4ce065a45a))
* **typography:** New mixin to set exact baseline height of text elements. ([#3083](https://github.com/MaTriXy/material-components-web/issues/3083)) ([dd3817a](https://github.com/MaTriXy/material-components-web/commit/dd3817a84dd4d21f6addf51ad60056a1b2038e0f))
* **typography:** Reverted baseline mixin to use display inline-block because of IE issues ([#3297](https://github.com/MaTriXy/material-components-web/issues/3297)) ([ded07d0](https://github.com/MaTriXy/material-components-web/commit/ded07d07173a86e0a48982412bd5401d90ace463))


### Reverts

* **checkbox:** Added new theme mixin in checkbox to match token keys ([b4c3f51](https://github.com/MaTriXy/material-components-web/commit/b4c3f513eb1b42fa3844a265ccabb1e8644ea123))
* "fix(checkbox): change checkbox event type from change to click and add some logic for IE browser" ([ba30399](https://github.com/MaTriXy/material-components-web/commit/ba30399adc901ca090c90bb1cad9410c81ae5fd1))
* "Include tooltip directory for future copybara syncs." ([#6185](https://github.com/MaTriXy/material-components-web/issues/6185)) ([b0c456d](https://github.com/MaTriXy/material-components-web/commit/b0c456d330f31bc890c54d114de1d56ac23fee9f))
* feat(checkbox): Added theme configuration support to checkbox ([cf80012](https://github.com/MaTriXy/material-components-web/commit/cf800124fdaeea04b3fd45f8718a2980dd01a0df))
* Revert "feat(switch): Add elevation overlay structure (#5281)" (#5329) ([1fbf5bd](https://github.com/MaTriXy/material-components-web/commit/1fbf5bd1d84b7b02eb7f0a7aff2b9c3eed0b4d3d)), closes [#5281](https://github.com/MaTriXy/material-components-web/issues/5281) [#5329](https://github.com/MaTriXy/material-components-web/issues/5329)
* feat(chips): Consolidate interaction event handlers ([#5251](https://github.com/MaTriXy/material-components-web/issues/5251)) ([#5301](https://github.com/MaTriXy/material-components-web/issues/5301)) ([5e45d77](https://github.com/MaTriXy/material-components-web/commit/5e45d77f3e387eff356f5ce93336d4b872c725c4))
* fix(chips): Do not throw error if chip set becomes empty ([#5300](https://github.com/MaTriXy/material-components-web/issues/5300)) ([d10e8cd](https://github.com/MaTriXy/material-components-web/commit/d10e8cdf3cda4a735b1ae43bb17592f9383c8886))
* fix(select): Do not fire change event on programmatic change ([#5255](https://github.com/MaTriXy/material-components-web/issues/5255)) ([#5302](https://github.com/MaTriXy/material-components-web/issues/5302)) ([ad9dfe7](https://github.com/MaTriXy/material-components-web/commit/ad9dfe706de46d5dc131ad6615aa18f0e3b01133))
* Revert "refactor(menu-surface): Allow any type during migration (#5201)" (#5212) ([62d3a09](https://github.com/MaTriXy/material-components-web/commit/62d3a09b2d31c8c44b5c5ff1ff91fb26ad460b63)), closes [#5201](https://github.com/MaTriXy/material-components-web/issues/5201) [#5212](https://github.com/MaTriXy/material-components-web/issues/5212)


* fix(linear-progress) support aria attributes (#5248) ([7084b40](https://github.com/MaTriXy/material-components-web/commit/7084b403a4ab6be0856c670eebb39078a4fcbcfe)), closes [#5248](https://github.com/MaTriXy/material-components-web/issues/5248)


### BREAKING CHANGES

* **MenuSurface:** Adds #notifyOpening method to menu surface adapter.

PiperOrigin-RevId: 444830518
* **slider:** Adds #getValueIndicatorContainerWidth method to slider adapter.

PiperOrigin-RevId: 419837612
* **menu:** Adds new menu adapter method:

  /**
   * @return the attribute string if present on an element at the index
   * provided, null otherwise.
   */
  getAttributeFromElementAtIndex(index: number, attr: string): string|null;

PiperOrigin-RevId: 398575780
* **iconbutton:** MDC iconbutton `_index` Sass module will only export theme mixins.

PiperOrigin-RevId: 391773229
* **theme:** Renamed Sass mixins `validate-keys()` to `validate-theme()` in `@material/theme`

PiperOrigin-RevId: 390671152
* **fab:** Renamed Fab's mixins to deprecate legacy theme mixins.

PiperOrigin-RevId: 387378201
* **tooltip:** - Tooltips intended to be hidden from the screen reader should be annotated with `data-hide-tooltip-from-screenreader="true"` (in addition to using `data-tooltip-id` rather than `aria-describedby`.

PiperOrigin-RevId: 386490861
* Breaking change for the UMD-case where the exports are bound to a global variable. Previously the entry-point would appear in camel-case, but now it's matching the actual package name in dash-case. This is unfortunately not avoidable with the current Webpack tooling. i.e. previous UMD users relying on the globals (which are rather rare anyway), would need to switch from `window.mdc.circularProgress` to `window.mdc['circular-progress]`.
* **checkbox:** Renamed old checkbox theme mixin for deprecation

PiperOrigin-RevId: 384568221
* **iconbutton:** Icon button now requires an inner ripple element with
class `mdc-icon-button__ripple`. See README for details.

PiperOrigin-RevId: 372153409
* **typography:** Renamed typography Sass function from pxToRem() to px-to-rem()

PiperOrigin-RevId: 368489085
* **fix:** the old list implementation has been deprecated and now requires that class names use an "mdc-deprecated-list-*" prefix. The new implementation (list evolution), no longer uses a prefix ("mdc-evolution-list-*" is now just "mdc-list-*").

PiperOrigin-RevId: 364441086
* **snackbar:** Dom structure change, see README.md

PiperOrigin-RevId: 363926666
* **tooltip:**   Added adapter method:
  - registerAnchorEventHandler<K extends EventType>(
      evtType: K, handler: SpecificEventListener<K>): void;
  - deregisterAnchorEventHandler<K extends EventType>(
      evtType: K, handler: SpecificEventListener<K>): void;

PiperOrigin-RevId: 358401984
* **theme:** custom-properties.apply() has been renamed to declaration() to better align with css.declaration()

PiperOrigin-RevId: 355659381
* **tooltip:**   Added adapter methods:
  - getComputedStyleProperty(propertyName: string): string;
  - getParentBoundingRect(): ClientRect|null;

PiperOrigin-RevId: 352659136
* **tooltip:**   Added adapter method:
  - tooltipContainsElement(element: HTMLElement): boolean;
Rich tooltips are currently in development and is not yet ready for use.

PiperOrigin-RevId: 346325244
* Removed `deep-get()` API from mdc-theme, use `sass:map`'s get() API instead.

PiperOrigin-RevId: 345257138
* **tooltip:**   Added adapter method:
  - anchorContainsElement(element: HTMLElement): boolean;
Rich tooltips are currently in development and is not yet ready for use.

PiperOrigin-RevId: 345221617
* **slider:** Slider is now backed by an input of type="range". Additionally, adapter methods (focusInput, isInputFocused, registerInputEventHandler, deregisterInputEventHandler) were added.

PiperOrigin-RevId: 344116908
* **tooltip:**   Added adapter methods:
  - setAnchorAttribute(attr: string, value: string): void;
  - registerEventHandler<K extends EventType>(
        evtType: K, handler: SpecificEventListener<K>): void;
  - deregisterEventHandler<K extends EventType>(
        evtType: K, handler: SpecificEventListener<K>): void;
Rich tooltips are currently in development and is not yet ready for use.

PiperOrigin-RevId: 343894231
* **slider:** Adds slider adapter methods (get/setInputValue, get/setInputAttribute, removeInputAttribute). Slider DOM structure now contains a hidden input.

PiperOrigin-RevId: 343157208
* **banner:** Added wrapper div to text/graphic for mobile friendly view, see README.md for more info.

PiperOrigin-RevId: 339496476
* **textfield:** adapter method `getAttr` added on helper text subcomponent; adapter method `setInputAttr` and `removeInputAttr` added on main component

PiperOrigin-RevId: 336694998
* **banner:** Dom structure change, see README.md

PiperOrigin-RevId: 332891202
* **select:** selected text node now needs to be wrapped in an outer `mdc-select__selected-text-container` span; see README for updated markup

PiperOrigin-RevId: 331237284
* **datatable:** Header checkboxes will now be unchecked if layout is called when there are no rows.

PiperOrigin-RevId: 329616597
* **banner:** Updated adapter to use CloseReason types

PiperOrigin-RevId: 327517664
* **checkbox:** Renamed mixin `ripple()` => `ripple-styles()` in MDC checkbox

PiperOrigin-RevId: 327036276
* **checkbox:** Renamed mixin `ripple()` => `ripple-styles()` in MDC checkbox

PiperOrigin-RevId: 326643138
* **checkbox:** Renamed mixin `ripple()` => `ripple-styles()` in MDC checkbox

PiperOrigin-RevId: 326565296
* **theme:** $ie-fallback variable has been moved and renamed to $enable-fallback-declarations in `@material/theme/css`

PiperOrigin-RevId: 325324881
* **select:** select theming mixins which were previously "stateful" (e.g. `hover-label-color()`) are combined into the non-stateful mixin (e.g. `label-color()`). The default state of the mixin can be set as normal, or a Map of states can be provided to optionally set one or more states of the mixin (e.g. `label-color((hover: blue))`). See the `@material/theme/state` package for more details.

PiperOrigin-RevId: 325314602
* **radio:** MDC radio _index Sass module will only export theme mixins

PiperOrigin-RevId: 324724042
* **textfield:** the notched outline and label should now appear before the input in the text field's DOM structure for a11y navigation

PiperOrigin-RevId: 323667270
* **slider:** This upgrades the old slider to a new version of slider that adheres to the M2 design spec. Changes include:
- M2 design (primary instead of secondary color used, larger active track and thumb, improved tick marks UI)
- Range (two-thumb slider) slider
- Pointer events support (for browsers that support pointer events)
- High contrast mode support
- Improved accessibility (follows WAI-ARIA spec for slider)
- Bug fixes

PiperOrigin-RevId: 322199406
* **circular-progress:** DOM Changed. See README for updated markup. `$default-size`, `$stroke-width`, and `$container-side-length` variables removed.

PiperOrigin-RevId: 321231651
* **snackbar:** The right padding of the label for the `mdc-snackbar--stacked` variant will now have an additional 8px

PiperOrigin-RevId: 319021332
* **data-table:** New adapter method replacing `getTableBodyHeight()` => `getTableHeaderHeight()` and changed return types of this method.

PiperOrigin-RevId: 318845959
* **button:** Removes button theme-baseline() mixin, moves mixin contents to base button Sass.

PiperOrigin-RevId: 317867315
* **select:** Added adapter methods `isTypeaheadInProgress`, `typeaheadMatchItem`

PiperOrigin-RevId: 314800139
* **select:** Added adapter method `addMenuClass`, `removeMenuClass`

PiperOrigin-RevId: 314429861
* **theme:** `color-hash()` (and checkbox container-colors mixins) no longer works with `var()` values and now only works with custom property Maps created by `custom-properties.create()`

PiperOrigin-RevId: 313825202
* **select:** added adapter method `removeSelectAnchorAttr`

PiperOrigin-RevId: 313797376
* **select:** `density` mixin split into `filled-density`, `filled-with-leading-icon-density`; `height` mixin split into `filled-height`, `filled-with-leading-icon-height`

PiperOrigin-RevId: 313641646
* **select:** dropdown icon SVG markup now has `mdc-select__dropdown-icon-graphic` class.

PiperOrigin-RevId: 313465286
* **select:** non-outlined selects now require a `mdc-select--filled` class on its root

PiperOrigin-RevId: 313235538
* **data-table:** Added a wrapper element to data table's table element to fix horizontal scrolling issue when pagination controls are added.

PiperOrigin-RevId: 312342190
* **select:** empty space around `mdc-list-item__text` spans removed in select markup

PiperOrigin-RevId: 312306749
* **textfield:** mdc-text-field-SUB_ELEMENT imports have been removed

PiperOrigin-RevId: 312205289
* **select:** adapter method removeAttributeAtIndex removed.

PiperOrigin-RevId: 312133369
* **chips:** The chip adapter and foundation interfaces have changed. Chips now use the trailing action subcomponent.

PiperOrigin-RevId: 310991928
* **textfield:** textareas must now add a `mdc-text-field__resizer` span around the textarea (and internal counter if present) if they are resizable

PiperOrigin-RevId: 310979350
* **floating-label:** all labels that are part of a required field should now add the mdc-floating-label--required class for required fields to avoid a FOUC

PiperOrigin-RevId: 310594927
* **select:** variable `$outline-disabled-border` renamed to `$disabled-outline-color`; icon variable `$icon-opacity` removed, use alpha channel of `$icon-color` instead.

PiperOrigin-RevId: 310378848
* **textfield:** textareas with internal character counters must specify the `mdc-text-field--with-internal-counter` class. Character counters should move after the textarea element.

PiperOrigin-RevId: 309652879
* **select:** helper text now persistent by default, `mdc-select-helper-text--persistent` removed

PiperOrigin-RevId: 309485352
* **select:** DOM structure for dropdown icon changed; `$dropdown-color` renamed to `$dropdown-icon-color`, `$dropdown-opacity` removed, `$disabled-dropdown-opacity` removed.

PiperOrigin-RevId: 309450834
* **button:** Correct misspelling of overflow for button's label-overflow-ellipsis mixin

PiperOrigin-RevId: 308612698
* **button:** Correct misspelling of overflow for button's label-overflow-ellipsis mixin

PiperOrigin-RevId: 308602086
* **select:** `mdc-menu--fullwidth` class replaces custom width class for the menu markup in select

PiperOrigin-RevId: 308358555
* **textfield:** mdc-text-field--textarea must now include mdc-text-field--outlined modifier class

PiperOrigin-RevId: 308161624
* **select:** root of mdc-select is now an inline-block element, use custom width class (i.e. `demo-width-class`) on the root instead of the anchor for width adjustments; alternately, use the new `mdc-select--fullwidth` on the root to expand width to that of its parent container

PiperOrigin-RevId: 308144318
* **select:** HTML Markup significantly changed, see README; REMOVED adapter methods `isSelectedTextFocused`, `getSelectedTextAttr`, `setSelectedTextAttr`; ADDED adapter methods `isSelectAnchorFocused`, `getSelectAnchorAttr`, `setSelectAnchorAttr`; removed variables `outlined-dense-label-position-y`, `icon-padding`; added variables `minimum-height-for-filled-label`, `filled-baseline-top`, `selected-text-height`, `anchor-padding-left`, `anchor-padding-left-with-leading-icon`, `anchor-padding-right`.

PiperOrigin-RevId: 307906127
* **textfield:** Default textfields must now specify mdc-text-field--filled. Disabled outlined textfields no longer have a shaded background. Height mixin no longer specifies a baseline override, use typography's baseline-top mixin.

PiperOrigin-RevId: 307134283
* **textfield:** mdc-text-field--dense and associated mixins/variables have been removed. Use the density() mixin instead.

PiperOrigin-RevId: 301426122
* **textfield:** removed the following variables: `$input-padding`, `$input-padding-top`, `$input-padding-bottom`, `$outlined-input-padding-top`, `$outlined-input-padding-bottom`, `$input-border-bottom`

PiperOrigin-RevId: 300259065
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.

PiperOrigin-RevId: 299133963
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.

PiperOrigin-RevId: 298645833
* **typography:** `typography.baseline-top()` and `typography.baseline-bottom()` are now private. Use `typography.baseline()` for containers and `typography.text-baseline()` for text with $top and $bottom params.

PiperOrigin-RevId: 297926710
* **chips:** The touch target and text now appear inside the primary action element. Please see the readme for markup changes.

PiperOrigin-RevId: 294259413
* **textfield:** filled text fields must include a `<div class="mdc-text-field__ripple"></div>`

PiperOrigin-RevId: 292641405

Co-authored-by: Material Web Copybara Robot <59487319+material-web-copybara@users.noreply.github.com>
* **textfield:** Filled textfields will no longer show a floating label at certain densities. This can be overridden by setting `$mdc-text-field-minimum-height-for-filled-label: 40px`
* **chips:** Both `MDCChipAdapter` and `MDCChipSetAdapter` have new methods. `MDCChipSetFoundation` event handlers now accept the corresponding chip event detail interface as the sole argument. The `root` property has been removed from the `MDCChipRemovalEventDetail` interface.
* **line-ripple:** `mdc-line-ripple-color()` mixin has been renamed to `mdc-line-ripple-active-color()`
* **grid-list:** Per the deprecation notice for grid-list, this component has been
removed from MDC-Web. Some of its functionalities are available in the MDC Image List package instead. It is recommended that you migrate to the mdc-image-list package to continue to receive new features and updates.
* Four variables and a mixin in mdc-textfield were renamed to use a mdc-text-field- prefix when depended on via @import (formerly mdc-required-text-field-label-asterisk_, now required-label-asterisk_).
* **textfield:** icons must use `.mdc-text-field__icon--leading` or `.mdc-text-field__icon--trailing` classes. `mdc-text-field-icon-color()` mixin has been split into `mdc-text-field-leading-icon-color()` and `mdc-text-field-trailing-icon-color()`.

* chore(textfield): use --leading/trailing modifiers for icons

* chore(textfield): docs typo

* chore(textfield): revert hover fix

* chore(textfield): fix unclosed css block

* chore(textfield): separate position mixins for leading/trailing icons

* chore(textfield): restore two-icons position mixin

* chore(textfield): update component test with icon classes

* chore(textfield): update foundation test for preventDefault error
* **switch:** Added setNativeControlAttr method in mdc-switch adapter.
* **checkbox:** remove event listener for 'change' and add event listener for 'click'.

- Add handleClick() method in foundation to handle click event.
- Add setCheck() method into component to change check status.
* **switch:** Switch DOM structure has changed. See switch README for details
* **button:** Variable `$mdc-button-disabled-container-fill-color`
renamed to `$mdc-button-disabled-container-color`.
* Removed `$edgeOptOut` option from `mdc-theme-prop()` Sass mixin.
* **chips:** the handleInteraction and handleTrailingIconInteraction handlers have been removed from the MDCChipFoundation. The handleClick handler has been added to the MDCChipFoundation
* Adds new adapter methods to MDCLinearProgressAdapter.
* **elevation:** Functions moved into the _functions.scss file
* **touchtarget:** Renames mixin from mdc-touch-target-component => mdc-touch-target-margin
* **text-field:** Redundant mixins `mdc-text-field-textarea-fill-color`, `mdc-text-field-textarea-stroke-color`, `mdc-text-field-fullwidth-bottom-line-color` removed. Instead, use `mdc-text-field-fill-color`, `mdc-text-field-outline-color`, and `mdc-text-field-bottom-line-color` respectively to achieve the same effect.
* **checkbox:** `mdc-checkbox-ink-color` mixin now only applies to enabled checkboxes
* **linear-progress:** MDCLinearProgressAdapter adapter has new `forceLayout` method
* **select:** In MDCMenu and MDCMenuSurface, `hoistMenuToBody` adapter method removed.  In MDCSelect, HTML structure changed: the select anchor is now wrapped in a parent element, and the anchor's sibling is the select menu. Support for native select removed. Support added for select with no label. MDCSelectAdapter methods removed: `getValue`, `setValue`, `isMenuOpen`, `setSelectedIndex`, `checkValidity`, `setValid`, `toggleClassAtIndex`. MDCSelectAdapter methods added: `hasLabel`, `getSelectedMenuItem`, `setSelectedText`, `isSelectedTextFocused`, `get/setSelectedTextAttr`, `getAnchorElement`, `setMenuAnchorElement`, `setMenuAnchorCorner`, `setMenuWrapFocus`, `set/removeAttributeAtIndex`, `focusMenuItemAtIndex`, `getMenuItemValues`, `getMenuItemCount`, `getMenuItemCount`, `getMenuItemAttr`, `getMenuItemTextAtIndex`, `add/removeClassAtIndex`. MDCSelectFoundation `setValue` method removed; `getDisabled`, `handleMenuItemAction`, `getSelectedIndex`, `get/setRequired`, `init` added.
* **radio:** In Checkbox, Renamed sass variables `$mdc-radio-touch-area` => `$mdc-radio-ripple-size` & `$mdc-radio-ui-size` => `$mdc-radio-icon-size` to be consistent with checkbox. Also, removed `$mdc-radio-ui-pct` sass variable.
* **switch:** Renames switch variables $mdc-switch-tap-target-size => $mdc-switch-ripple-size, removes $mdc-switch-tap-target-initial-position and $mdc-switch-native-control-width.
* **list:** New adapter method listItemAtIndexHasClass
* **list:** Renamed mixin `mdc-list-item-shape-radius()` => `mdc-list-single-line-shape-radius()`
* **density:** Renamed sass mixins & variables in MDC Data Table - `mdc-data-table-header-row-height` => `mdc-data-table-header-cell-height` & `mdc-data-table-row-height` => `mdc-data-table-cell-height`. Also removed `mdc-button--dense` variant, use button's density mixin instead.
* **text-field:** Removed sass variable in notched outline - `$mdc-notched-outline-transition-duration`.
* **mdc-fab:** This changes the structure of the FAB element by moving the ripple from the outer element to an inner mdc-fab__ripple element.

OLD

```html
<button class="mdc-fab" aria-label="Favorite">
  <span class="mdc-fab__icon material-icons">favorite</span>
</button>
```

NEW

```html
<button class="mdc-fab" aria-label="Favorite">
  <div class="mdc-fab__ripple"></div>
  <span class="mdc-fab__icon material-icons">favorite</span>
</button>
```
* **radio:** Ripple has been moved to a child element. See readme for updates.
* **slider:** remove adapter methods `appendTrackMarkers`, `removeTrackMarkers `, `setLastTrackMarkersStyleProperty `, and add adapter method `setTrackMarkers`.
* **button:** This changes the structure of the button element by moving the ripple from the outer <button> element to an inner `mdc-button__ripple` element.

OLD
```
<button class="mdc-button">
  <span class="mdc-button__label">Hello World</span>
</button>
```

NEW
```
<button class="mdc-button">
  <div class="mdc-button__ripple"></div>
  <span class="mdc-button__label">Hello World</span>
</button>
```
* **chips:** MDCChipSetAdapter#removeChip has been replaced with MDCChipSetAdapter#removeChipAtIndex. MDCChipSetAdapter#setSelected has been replaced with MDCChipSetAdapter#selectChipAtIndex
* **chips:** Chips markup, adapters, foundations, and events have changed.
* **tabs:** removed deprecated mdc-tabs package.
* **menu:** The following adapter methods were removed: isFirstElementFocused, isLastElementFocused, focusFirstElement, focusLastElement. The following functionality to handle TAB on menusurface has been removed: "If TAB and last element is focused => Focus on first element", "If SHIFT + TAB and first element is focused => Focus on last element"
* **chips:** Add the setAttr method to the chip adapter.
* **top-app-bar:** Replaced adapter methods getParentElement, getSelectedElementIndex with getSelectedSiblingOfItemAtIndex, isSelectableItemAtIndex.
* **dialog:** Dialog Adapter#getInitialFocusEl has been added and Adapter#trapFocus first argument is now the initialFocusEl.
* **checkbox:** Removed `$mdc-checkbox-ui-pct` sass variable from `MDCCheckbox`
* **menu:** Replaced adapter methods getParentElement, getSelectedElementIndex with getSelectedSiblingOfItemAtIndex, isSelectableItemAtIndex.
* **dialog:** Dialog `Foundation#handleInteraction` has been split into two methods: `#handleClick` and `#handleKeydown`.
* **chips:** Update mdc-chip-leading-icon-margin and mdc-chip-trailing-icon-margin mixins signatures to take only left and right margin values.
* **menu:** The following adapter methods were removed: isFirstElementFocused, isLastElementFocused, focusFirstElement, focusLastElement. The following functionality to handle TAB on menusurface has been removed: "If TAB and last element is focused => Focus on first element", "If SHIFT + TAB and first element is focused => Focus on last element"
* **chips:** Add the setAttr method to the chip adapter.
* **top-app-bar:** Replaced adapter methods getParentElement, getSelectedElementIndex with getSelectedSiblingOfItemAtIndex, isSelectableItemAtIndex.
* **dialog:** Dialog Adapter#getInitialFocusEl has been added and Adapter#trapFocus first argument is now the initialFocusEl.
* **checkbox:** Removed `$mdc-checkbox-ui-pct` sass variable from `MDCCheckbox`
* **menu:** Replaced adapter methods getParentElement, getSelectedElementIndex with getSelectedSiblingOfItemAtIndex, isSelectableItemAtIndex.
* **dialog:** Dialog `Foundation#handleInteraction` has been split into two methods: `#handleClick` and `#handleKeydown`.
* **chips:** Update mdc-chip-leading-icon-margin and mdc-chip-trailing-icon-margin mixins signatures to take only left and right margin values.
* **menu:** New adapter methods to MDC List: `isRootFocused`. MDC Menu: Replaced adapter methods `isRootFocused`, `focusRoot` with `focusListRoot`. When using MDC List inside MDC Menu `tabindex` should be set on list root element where `role="menu"` is assigned.
* **list:** MDCList's `listElements` component API now includes disabled list items which previously returned only enabled list items.
* **menu:** Focus is no more set to first menu item when menu is opened. Introduced new API (`setDefaultFocusItemIndex()`) to set focus on specific menu item every time the menu is opened. Also introduced new foundation & adapter methods to incorporate this change. Please use `setDefaultFocusItemIndex(0)` method before menu open to retain previous behaviour.
* `$mdc-top-app-bar-prominent-dense-title-bottom-padding` is renamed to `$mdc-top-app-bar-dense-prominent-title-bottom-padding`
* **list:** removed #adapter.removeAttributeForElementIndex
* The previously deprecated mdc-icon-toggle package has been removed; use mdc-icon-button instead.
* **animation:** The `transformStyleProperties` array export has been removed from `mdc-animation`. Please use `getCorrectPropertyName(window, 'transform')` instead.
* **ripple:** `getMatchesProperty()` has been removed from `@material/ripple/util` and `@material/tab-scroller/util`. Use `matches()` from `@material/dom/ponyfill` instead.
* **feature-targeting:** The main mixins recently introduced to some packages in in v0.44.0 have been renamed from `mdc-foo` to `mdc-foo-core-styles`. (Importing baseline styles via `mdc-foo.scss` remains unaffected.)
* **list:** The default `MDCListAdapter.notifyAction()` implementation now emits an object of type `{index: number}` rather than a primitive `number` directly.
* **menu-surface:** `MDCMenuSurfaceAdapter.setPosition()` now expects an object with properties of type `number` rather than `string`. E.g., `setPosition({top: '5px', left: '10px'})` is now `setPosition({top: 5, left: 10})`.
* **menu:** Replaced menu's foundation methods `handleClick` and `handleSelection` with `handleItemAction` to handle list item action (i.e., list's custom event `MDCList:action`)
* **list:** Introduced new adapter method `getAttributeForElementIndex` to determine if target list item has `href` attribute and removed `followHref` adapter API.
* **chips:** Adds 3 new chips adapter methods: hasLeadingIcon, getRootBoundingClientRect, and getCheckmarkBoundingClientRect. Also adds a new foundation method: getDimensions.
* **list:** Introduced new adapter `isFocusInsideList` for MDC List for improved accessibility.
* **snackbar:** Snackbar's DOM and APIs have changed to match the latest design guidelines. See the Snackbar documentation for more information.
* **button:** We recommend placing each button's text label within a mdc-button__label element. This does not immediately break existing MDC Button usage, but updating is recommended to future-proof against potential upcoming changes.
* **tab:** MDCTabBar#getIndexOfTab(tab: MDCTab): boolean is now MDCTabBar#getIndexOfTabByID(id: string): boolean
* **notched-outline:** The notched outline has been changed from using an SVG for the outline to using 3 div elements. This approach resolves initial rendering issues as well as inconsistencies between the different types of outlines. Please refer to the Readme or the screenshot test pages for details and examples.
* **checkbox:** The component is now responsible for calling MDCCheckboxFoundation#handleChange when the checked and indeterminate properties change.
* **list:** Replaced toggleCheckbox adapter method with setCheckedCheckboxOrRadioAtIndex and added 3 more new adapter methods for improved accessibility.
* **fab:** Fab now has 2 separate mixins - `mdc-fab-shape-radius` for regular / mini Fab variants & `mdc-fab-extended-shape-radius` for Extended FAB variant.
* **select:** Several adapter APIs were added to support the enhanced variant. The drop-down arrow is now its own element. The change event is now MDCSelect:change for all variants. See the README for full details.
* **radio:** Removed getNativeControl from adapter, and subsequent foundation methods that called getNativeControl. Foundation methods removed: isChecked, setChecked, isDisabled, getValue, setValue.
* **shape:** Renamed shape global variables from `$mdc-shape-*-surface-radius` to `$mdc-shape-*-component-radius`
* **chips:** deselect and toggleSelect are private methods. handleChipInteraction and handleChipRemoval now accept chipId instead of an event.
* Anyone intending to build MDC Web's ES2015+ sources must directly import @material/foo/index. @material/foo will now resolve to UMD modules.
* **shape:** The previous contents of the mdc-shape package have been removed and replaced with mixins implementing the Shape system. This system implements only rounded corners to provide a straightforward CSS-only solution. Replaced all *-corner-radius component mixins with *-shape-radius mixins to integrate with Shape system.
* **dialog:** MDCDialog has been reimplemented to support more use cases, so APIs and the DOM structure have changed. See the mdc-dialog README for more information.
* **text-field:** Component API's for interacting with icons has changed. Please refer to the documentation. 
* **checkbox:** Remove foundation methods for set/get indeterminate, value, disabled. Add adapter methods: isIndeterminate, isChecked, hasNativeControl, setNativeControlDisabled. 
* **drawer:** Drawer variants have new DOM structure, mixins, and JS. MDCPersistentDrawer and MDCTemporaryDrawer components are replaced with a single MDCDrawer component which supports both.
* **list:** Please update calls to MDCListFoundation.handleKeydown to pass in isRootListItem and listItemIndex, and update both MDCListFoundation.handleFocusIn, MDCListFoundation.handleFocusOut to pass in listItemIndex
* **text-field:** This PR removes the margin-top from the mdc-text-field container. This can cause a UI to shift/change. 
* **checkbox:** Event registration adapter APIs have been removed and are now the responsibility of the component.
* **list:** Adds a followHref adapter API.
* **text-field:** Removes the default version of the text field and changes the new default variant to be the `--box` variant. Changes the box-sizing to border-box. 
* **tab-bar:** `getActiveTabIndex` adapter method renamed and `setActiveTab` adapter method added.
* **tab:** We've removed the `computeIndicatorClientRect` method from `MDCTabFoundation`
* **switch:** We've removed the `isChecked` and `isDisabled` methods from `MDCSwitchFoundation`. Please update any call to `MDCSwitchFoundation.handleChange` so it passes in the change event. And note that `isNativeControlChecked` and `isNativeControlDisabled` are no longer required methods in `MDCSwitchAdapter` 
* **tab-indicator:** Removes handleTransitionEnd foundation API. Removes [de]registerEventHandler adapter APIs.
* **menu:** Menu positioning logic has been split into its own package (mdc-menu-surface). mdc-menu is rebuilt to use mdc-menu-surface and mdc-list styles and JavaScript.
* **text-field:** The `mdc-text-field--upgraded` class has been removed. `mdc-text-field__input` position has changed by 2px to match spec. `mdc-text-field--textarea` width in IE and Edge now matches other browsers.

### What it does
* **tab:** Removes handleTransitionEnd foundation API. Removes [de]registerEventHandler adapter APIs. Event registration is now the component's responsibility.
* **icon-button:** Removes the previous data attributes and no longer dynamically changes the label. Allows developers to add both elements to the button, with one indicated as the on state by using a data-toggle-on attribute. State is now changed by adding/removing the mdc-icon-button--on class to the mdc-icon-button element. All icon elements should have the mdc-icon-button__icon class.
* **tab-bar:** Adds focusTabAtIndex and getFocusedTabIndex MDCTabBarAdapter APIs; adds focus MDCTab component API used by MDCTabBar.
* **typography:** Helper text and MDC List two-line text that uses new typography baseline mixin should strip the white-space.
* **chips:** `MDCChip` takes an `id`, no longer exposes its `foundation`, and has `selected` as a property. Custom event details require a `chipId` instead of `chipFoundation`. New methods added to `MDCChipSetAdapter` and `MDCChipSetFoundation`.
* **text-field:** Removed bottom margin from both text field and helper text.
* **snackbar:** Adds a new adapter method that is required `isFocused`. 
* **text-field:** Setting the validity state using `setValid` no longer ignores native input validation. New API `useNativeValidation` is introduced to enable / disable native validation for custom validity.
* **tab-bar:** mdc-tabs is deprecated and no longer bundled in the material-components-web package. You are encouraged to use the new mdc-tab-bar and related packages instead.
* **switch:** MDC Switch DOM structure and Sass APIs have changed, and JavaScript APIs have been added. See the documentation for more information.
* **icon-button:** Removed some adapter APIs (registerInteractionHandler, deregisterInteractionHandler) and shifted responsibility of event handling out of the foundation and into the component.
* **select:** Removed some adapter APIs (setDisabled, setSelectedIndex, getSelectedIndex, setValue, registerInteractionHandler, deregisterInteractionHandler) and shifted responsibility of event handling and programmatic select element updates out of the foundation and into the component.
* **chips:** `MDCChip`/`MDCChipSet` registerEventHandler adapter methods were removed, and corresponding handlers were made public in `MDCChipFoundation`/`MDCChipSetFoundation`.



# 0.36.0 (2018-06-04)





# [14.0.0](https://github.com/material-components/material-components-web/compare/v13.0.0...v14.0.0) (2022-04-27)


### Bug Fixes

* **button:** update HCM shim to use the existing focus-ring ([a657abb](https://github.com/material-components/material-components-web/commit/a657abb61a2c7d23c2bd92c3cbd54ed404d0bafe))
* **checkbox:** Add explicit system color for checkmark in HCM. ([8c4da22](https://github.com/material-components/material-components-web/commit/8c4da223a7d35c4ca0a4f27534ecdb13087d0f1b))
* **checkbox:** move forced-colors theme out of static styles ([bbd1126](https://github.com/material-components/material-components-web/commit/bbd11268f0ea4fd45205a642f1d26a4c4ff34e05))
* **checkbox:** Update checkbox theme styles mixin to accept css vars ([c14e977](https://github.com/material-components/material-components-web/commit/c14e977ee36c26074b04dea5ce37e2300e9d3735))
* **chips:** Fix typography selector in GMDC-Wiz chips theming ([43c7d87](https://github.com/material-components/material-components-web/commit/43c7d87dc0c928d74652ceaebebca51c69b6eaaf))
* **datatable:** Adjust data table last row border-radius to support setting row background-color. ([ba78e87](https://github.com/material-components/material-components-web/commit/ba78e87246af31e1fe7dd03241a7565f2892fd64))
* **dialog:** Render dividers in Firefox 94 on Windows HCM ([fae6c65](https://github.com/material-components/material-components-web/commit/fae6c652d7debc3e2875ab9049d806513ddc2421))
* **dialog:** Set default z-index for close button in FloatingSheet dialog. ([3366a71](https://github.com/material-components/material-components-web/commit/3366a71d72f48e946a3f3b314b315395fafb3a1f))
* **fab:** Add focus ring in HCM. ([d57ec74](https://github.com/material-components/material-components-web/commit/d57ec74c7e9afe5db07162202e6f05b28dd581db))
* **focus-ring:** add 2d padding customizability, RTL bugfix ([f81fb1d](https://github.com/material-components/material-components-web/commit/f81fb1d232901c17d5794499c26e746ccab1af19))
* **focus-ring:** box-sizing bugfix to content-box. If box-sizing border-box is inherited the ring spacing will collapse. ([e58552c](https://github.com/material-components/material-components-web/commit/e58552c6efa0442a36f441efe27cd01f3df2a524))
* **focus-ring:** ignore pointer events ([3ef470e](https://github.com/material-components/material-components-web/commit/3ef470efe6f1d213935dca37ad213030cdd30d88))
* **focus-ring:** RTL bugfix ([e00181e](https://github.com/material-components/material-components-web/commit/e00181e59cb1f29f4a8280f48b377a667a3e783b))
* **iconbutton:** Fixed max width and height for high contrast mode focus ring on icon buttons. Display only in forced colors mode. ([cf42927](https://github.com/material-components/material-components-web/commit/cf429277817af685fd0b23a21a2e10ddabc4b9ef))
* **iconbutton:** Set icon button ripple z-index to -1. ([586e740](https://github.com/material-components/material-components-web/commit/586e740ddcaa674c409d68ab5faf9ee8c61e2d91))
* **list:** Improve a11y for multi-select lists ([9736ddc](https://github.com/material-components/material-components-web/commit/9736ddce9c12f5485e746984225919568541e88d))
* **list:** Remove conflicting validation for checkbox list in setEnabled ([353ca7e](https://github.com/material-components/material-components-web/commit/353ca7e9f21b3589a17d25d8892198cba811dd13))
* **list:** Update lastSelectedIndex when toggling a checkbox range ([dcba26f](https://github.com/material-components/material-components-web/commit/dcba26fe1028cf151ebf34c5947082a49cc85f10))
* **menusurface:** Add a getOwnerDocument() method to MDCMenuSurfaceAdapter to provide a reference to the document that owns the menu surface DOM element. ([3486659](https://github.com/material-components/material-components-web/commit/348665978ce73694ad4518626dd70cdf5b984113))
* **radio:** Fix disabled state in Firefox Windows high contrast mode ([23043ac](https://github.com/material-components/material-components-web/commit/23043acd0e5341729230cc6e1840460977056115))
* **radio:** Modify theme styles Sass mixin validation to validate only keys ([390220e](https://github.com/material-components/material-components-web/commit/390220e422be57e8f38b74e04d8e8aba6082d333))
* **select:** Add border to select menu in HCM. ([5d80969](https://github.com/material-components/material-components-web/commit/5d809696c6699bf9563e8faf8f79ff6ebd78febf))
* **select:** revert down/up arrow on anchor changing selected index ([43d08ba](https://github.com/material-components/material-components-web/commit/43d08ba77e44dffbca99194ee18dbd202c8684f7))
* **slider:** Fix bug where secondary click moves slider thumb. ([3ab9565](https://github.com/material-components/material-components-web/commit/3ab956515feb5c861498b156e68493e6f7f2a578))
* **slider:** Fix IE11 bug - `unset` is unsupported in IE. ([f460e23](https://github.com/material-components/material-components-web/commit/f460e23dae619c6d09de114cc8c319972b7d1b10))
* **slider:** In updateUI, fix behavior to match jsdoc claim that when thumb param is undefined it updates both thumbs. Input attributes were not being updated at all. ([cc4ed13](https://github.com/material-components/material-components-web/commit/cc4ed13ccda7b44edce0070edd6ee215e98cc792))
* **slider:** Make the slider errors easier to debug by providing all relevant values in the error message. ([8687937](https://github.com/material-components/material-components-web/commit/868793776d9610ab068af706297a4f4599c7f6f1))
* **snackbar:** address Trusted Types violation ([cbd9358](https://github.com/material-components/material-components-web/commit/cbd9358a61e7626ebc12af2cdd3dc465e11ce8bf))
* **tooltip:** Adjusts logic in `validateTooltipWithCaretDistances` method. ([3e30054](https://github.com/material-components/material-components-web/commit/3e30054fb92c75b85d2f6186f4656d36ea05d6a1))
* **typography:** Fixes typography `theme-styles` mixin... the value being retreived from the `$theme` map and css property name was swapped. The mixin would request `font-size`/`font-weight`/`letter-spacing` from the `$theme` map (which expects `size`/`weight`/`tracking`)... so these values would always be `null`. ([32b3913](https://github.com/material-components/material-components-web/commit/32b391398aa70f2fbb917cd4649b84d87876cd8e))
* Remove /** [@override](https://github.com/override) */ tags from TypeScript code. ([c3cdff0](https://github.com/material-components/material-components-web/commit/c3cdff07b59adb0f44b40dbbca2cf05868138528))
* Simplify MDCAttachable interface to be any object (Function) that has `attachTo`. ([05db65e](https://github.com/material-components/material-components-web/commit/05db65ec07db5a230e2ba1144000046b09d4c44b))
* Snackbar action button ripple color is applied to the ripple element. ([4e66fb2](https://github.com/material-components/material-components-web/commit/4e66fb2e181b35ac47ae3a6863c101d3ff4f885e))
* Work around bug in Sass ([037285f](https://github.com/material-components/material-components-web/commit/037285f9bda55dfb2e011f7d58338b29bfa37b6b)), closes [sass/sass#3259](https://github.com/sass/sass/issues/3259)
* **switch:** Restore Firefox 94 HCM outlines ([39cf14b](https://github.com/material-components/material-components-web/commit/39cf14bc3b0ef053219328d36faaf2636e0f77f4))
* **textfield:** Fix breaking tests due to no valid pointerId being associated with pointer events. ([15db4f1](https://github.com/material-components/material-components-web/commit/15db4f1641bd3657ed230afacb41da84fb1077bc))
* **tooltip:** Only sends notification of a tooltip being hidden if `showTimeout` is not set (indicating that this tooltip is about to be re-shown). ([6ca8b8f](https://github.com/material-components/material-components-web/commit/6ca8b8f858f0d508a56cf09bcb4b11221f901acb))


### Features

* **banner:** Add disableAutoClose params for both banner actions to prevent the banner buttons from automatically closing the banner. Add adapter #notifyActionClicked method. ([b094eaa](https://github.com/material-components/material-components-web/commit/b094eaa4e7a69132eb09f7b9d6c1d429a3f702a0))
* **chips:** add focus ring styles ([783f6fd](https://github.com/material-components/material-components-web/commit/783f6fd5a29a56f6c72917546b7426f196bf4cae))
* **chips:** Added elevation tint layer color support in chips ([c78ff04](https://github.com/material-components/material-components-web/commit/c78ff042967de7cf823a9f9826f8f613be9e4846))
* **data-table:** separate table structure into its own mixin ([9f9d928](https://github.com/material-components/material-components-web/commit/9f9d928b2c6701707c5e5d32414c0c4db6a4d564))
* **dialog:** Add styling for floating sheets ([78305b6](https://github.com/material-components/material-components-web/commit/78305b6d547b07aa06db04ad47b765b8f92851fa))
* **dialog:** Add styling for floating sheets with content padding ([3e20c1d](https://github.com/material-components/material-components-web/commit/3e20c1de85fd72ff5efb3107c442036fc6317b4a))
* **Dialog:** Adds an API to hide the header for GMDC Fullscreen Dialog in non-fullscreen mode ([ab4aba1](https://github.com/material-components/material-components-web/commit/ab4aba1afaba8f75042ed774f9e618f811bec45e))
* **Dialog:** Adds an API to set custom position for GMDC Dialog ([ea9b5b4](https://github.com/material-components/material-components-web/commit/ea9b5b463c694804f79deaf8125c73779d34f5ce))
* **Dialog:** Adds an API to set custom z-index for GMDC Dialog ([96ea061](https://github.com/material-components/material-components-web/commit/96ea061c1787cc329e64e9054ba1402c442a15f0))
* **focus-ring:** added a new mixin so we can override just the focus-ring color ([641ed08](https://github.com/material-components/material-components-web/commit/641ed08513037285879a13708b95661d69c2f8b0))
* **focus-ring:** added a new mixin so we can override just the focus-ring radius ([7321d62](https://github.com/material-components/material-components-web/commit/7321d6254d63f701b2f381c9cf11eb0708b56a6e))
* **iconbutton:** Add link icon button Sass. ([9803d2d](https://github.com/material-components/material-components-web/commit/9803d2dc1c88e44b43a56249916f474581f5382e))
* **mdc-list:** introduce selection change event ([7d8ea46](https://github.com/material-components/material-components-web/commit/7d8ea4624e7dcdc5ce69edf1e747c77354457f42))
* **menu:** allow preferentially opening surface below anchor ([261f2db](https://github.com/material-components/material-components-web/commit/261f2db59382d561d6c89a7c41dafb6daad5a717))
* **MenuSurface:** Add opening event for menus. ([53b3cad](https://github.com/material-components/material-components-web/commit/53b3cad2f5ef4d0c9d5cf03c752f27035dd7c818))
* **select:** Add theming mixin boilerplate code to select ([ae8a6a3](https://github.com/material-components/material-components-web/commit/ae8a6a3a3e650fd068461d1236c5173c8e0467c8))
* **select:** Add validation getter methods. ([bdf1d37](https://github.com/material-components/material-components-web/commit/bdf1d3771cd5a3c5b23a5cea63d3eaf97ded257d))
* **select:** Added theme mixins to MDC select ([dcfe49c](https://github.com/material-components/material-components-web/commit/dcfe49c98ac25f5f5d64db021219d8a6c1caf6de))
* **slider:** Add `minRange` param to range sliders to request a minimum gap between the two thumbs. ([8fffcb5](https://github.com/material-components/material-components-web/commit/8fffcb5ddfb93f1459d62c67f4a051b035bf9940))
* **slider:** Add an option to hide focus styles after pointer interaction. ([ec54d90](https://github.com/material-components/material-components-web/commit/ec54d904621360bcb27e6d3cd1f33112e2a54aac))
* **slider:** Keep the slider value indicator within the bounds of the slider if possible. ([c047f7c](https://github.com/material-components/material-components-web/commit/c047f7c19a9452aaced85ce1608b0bc2a63db223))
* **state:** make context aware ([b2fe352](https://github.com/material-components/material-components-web/commit/b2fe3528bc1603df715c833abb5d905080681102))
* **switch:** Add high contrast mode focus ring to switch ([f31a833](https://github.com/material-components/material-components-web/commit/f31a833fae6f132318068f30a24a12c6c0cc192f))
* **text-field:** Add theming mixin boilerplate code to text-field ([eb382f3](https://github.com/material-components/material-components-web/commit/eb382f31889be98f4eebea1670b78c7c10f7016b))
* **text-field:** Added theme mixins to MDC text field ([344d528](https://github.com/material-components/material-components-web/commit/344d528233437e5f9ff960913957022f05bbdc04))
* **textfield:** adding input-font-size mixin ([207230e](https://github.com/material-components/material-components-web/commit/207230eb81e8c10cd5f962725af8c0184b8f3b62))
* **theme:** allow custom property strings in theme.validate-theme() ([4e372fb](https://github.com/material-components/material-components-web/commit/4e372fb4937f0fe71cce7c4c829b099f9f3dcf6b))
* add new class and mixin for open state of a menu item ([9a02b6e](https://github.com/material-components/material-components-web/commit/9a02b6ef8e8f235c7bd07cd8c6ce9078a46dbb78))
* Indicate which thumb `valueToAriaValueTextFn` and `valueToValueIndicatorTextFn` functions are called for. ([b6510c8](https://github.com/material-components/material-components-web/commit/b6510c8c1cc3a91937180f03418ea20a0cf2387b))
* **textfield:** adding input-font-family mixin ([991fb99](https://github.com/material-components/material-components-web/commit/991fb99f715872b49c89c44a6c98e82b4507fd14))
* Describe how to add child lists into a list item. ([758ce31](https://github.com/material-components/material-components-web/commit/758ce31d94d065b93d09db0016ec86b56d9197ec))


### BREAKING CHANGES

* **MenuSurface:** Adds #notifyOpening method to menu surface adapter.

PiperOrigin-RevId: 444830518
* **slider:** Adds #getValueIndicatorContainerWidth method to slider adapter.

PiperOrigin-RevId: 419837612





# [13.0.0](https://github.com/material-components/material-components-web/compare/v12.0.0...v13.0.0) (2021-09-24)


### Bug Fixes

* Fix missing $ripple-target param for ripple mixin ([1340ee9](https://github.com/material-components/material-components-web/commit/1340ee9f7507e6653537d081c53826b5c25b3e22))
* **banner:** Adjusting theme api selectors to use `mdc-button`. ([15981e9](https://github.com/material-components/material-components-web/commit/15981e9d95097895247fbcbd6ad9ad14c46be20e))
* **banner:** Correcting incorrect theme values passed through to button's `theme-mixin`. ([0de2f2e](https://github.com/material-components/material-components-web/commit/0de2f2edcb53e05a97ae79c7f5fc181033fbb0cc))
* **banner:** exclude source from npm package ([#7381](https://github.com/material-components/material-components-web/issues/7381)) ([d48a017](https://github.com/material-components/material-components-web/commit/d48a01771a5c5b080179ac34e4ef34146de5e209)), closes [#7360](https://github.com/material-components/material-components-web/issues/7360)
* **banner:** Removing `action-<state>-label-text-color` values from MDC `light-theme` map. ([d97f8f1](https://github.com/material-components/material-components-web/commit/d97f8f133c7d59bbddc49fe39dd9c714bcbb01d4))
* **button:** cleanup outlined button theme keys ([28d0d75](https://github.com/material-components/material-components-web/commit/28d0d75bb554be14171de19f50d082f837125f37))
* **button:** fix touch target reset in context of link buttons ([3b8d442](https://github.com/material-components/material-components-web/commit/3b8d4429e3373661fef202613389e4f2f00b33ad))
* **button:** remove negative padding around icons ([d470693](https://github.com/material-components/material-components-web/commit/d4706933f473925ec3a1ce6f7152208b31664538))
* **button:** remove rem/em transformers from typography theme-styles ([a395972](https://github.com/material-components/material-components-web/commit/a395972cfaf2260da9f50875a8fe772cc3c69d83))
* **button:** stack ripple behind content ([e1e69fd](https://github.com/material-components/material-components-web/commit/e1e69fd8e5fb5624173bc3836f92e6824596ad04))
* **density:** typo in variable exports ([6df682e](https://github.com/material-components/material-components-web/commit/6df682e746d1c417fe00376ba6ec33bd72159757))
* **dom:** Support providing an owner document for announcer messages. ([6236f35](https://github.com/material-components/material-components-web/commit/6236f3576a7f39f452175206f96c08b08315444b))
* **elevation:** reduce warnings when not providing elevation tokens ([adb9f1a](https://github.com/material-components/material-components-web/commit/adb9f1ad8c85e016bbe714d9b8f2d7d28e610f91))
* **iconbutton:** Fix icon button theme keys/light theme values based on updated tokens. ([42d175e](https://github.com/material-components/material-components-web/commit/42d175efc20e9b36eb86a843b23a60626d36e065))
* **menu:** apply elevation overlay to new lists ([0ad12ed](https://github.com/material-components/material-components-web/commit/0ad12ed3cffe78a27c7005e2ed9b83643ebb5114))
* **sass:** Wrap templated calc expressions in strings ([818f4ee](https://github.com/material-components/material-components-web/commit/818f4ee93de968dfaa9d64929b3edf2d9f8dbe01)), closes [#7391](https://github.com/material-components/material-components-web/issues/7391)
* **slider:** Reorder such that dragstart event is emitted before any other events when handling drag start. ([877e3fb](https://github.com/material-components/material-components-web/commit/877e3fb0dbdaf06cf3a9b4fb0fa731df2093901c))
* **slider:** Replace `innerHTML` with `firstChild` ([37d4db8](https://github.com/material-components/material-components-web/commit/37d4db86667c967ba173e318a124b72109cc1bb5))
* Fix compilation issues with TypeScript 4.4 ([7246447](https://github.com/material-components/material-components-web/commit/72464476cea3755fbcbb64df832e9933ea7b1170))
* **switch:** add pointer cursor ([12f5622](https://github.com/material-components/material-components-web/commit/12f5622e14b68c12542cb2bf7236c5a1f5492add))
* **switch:** distribute correct css ([#7292](https://github.com/material-components/material-components-web/issues/7292)) ([7b6bcb8](https://github.com/material-components/material-components-web/commit/7b6bcb85874e81f33956d1ec544aedcdc882ffed))
* **switch:** elevation theme custom properties not working ([2865629](https://github.com/material-components/material-components-web/commit/28656298a9c01bd585fdb995be7aa96d3c3395e7))
* **switch:** use correct colors for icons in all HCM themes ([d86fb6f](https://github.com/material-components/material-components-web/commit/d86fb6facd014e2c0c1a88108ddbb59595dea5ac))
* **theme:** ensure state selectors negate properly ([7249a30](https://github.com/material-components/material-components-web/commit/7249a3060c6b15eef338b44b77065b47e0b26d52))
* **tooltip:** Add a getActiveElement() method to MDCTooltipAdapter to delegate getting the active element from the correct document. ([e334676](https://github.com/material-components/material-components-web/commit/e3346766f22b23b6c1e04cb2821565d388d57054))
* **tooltip:** Adjust tooltip `focusout` handler. Ensures that interactive tooltips remain open when ChromeVox uses linear navigation to read non-focusable content inside the tooltip. ([7c96e6b](https://github.com/material-components/material-components-web/commit/7c96e6b98a25839d249e1d56478e919564b5ff07))
* **tooltip:** non-persistent tooltips disappear on scroll ([1f9259b](https://github.com/material-components/material-components-web/commit/1f9259b9d7821181d8655537cf80e95b9856dd7c))
* update combined mdc package to use new switch CSS ([077dcfc](https://github.com/material-components/material-components-web/commit/077dcfcfe483b8631f51cc16a89557d056b4db58)), closes [#7304](https://github.com/material-components/material-components-web/issues/7304)
* **tooltip:** allow the Mac zoom service to access plain tooltip contents ([510cf90](https://github.com/material-components/material-components-web/commit/510cf90f289177cf148b2d72cdb773047410731b))


### Code Refactoring

* **fab:** Deprecate legacy Fab theme mixins ([83bdd02](https://github.com/material-components/material-components-web/commit/83bdd022246c1699de71346d5c162e1ded5a0836))
* **iconbutton:** Forward only theme mixins from MDC icon button index module. ([0a90693](https://github.com/material-components/material-components-web/commit/0a906930027e2b55054be08aa8ce0d48dec8c25b))
* **theme:** Rename validate-keys() to validate-theme() ([2fb068f](https://github.com/material-components/material-components-web/commit/2fb068fb0f7a1b0e038ede3a2ab27a972e5b2ee4))


### Features

* **button:** add custom props to outlined button theme-styles ([bf405d2](https://github.com/material-components/material-components-web/commit/bf405d22ae54eef77bbe437228540900aad2f0e0))
* **button:** add custom props to protected button theme-styles ([4ca11fe](https://github.com/material-components/material-components-web/commit/4ca11fe76395824dff6b3e35d954af817ace1591))
* **button:** add custom props to text button theme-styles ([3dd6110](https://github.com/material-components/material-components-web/commit/3dd61109132cf17b5a92a941ecc0f03b0a1cc8d5))
* **button:** add missing transitions to box-shadow/border ([3b92903](https://github.com/material-components/material-components-web/commit/3b9290351308626b4699e2cbdaeb4dc7f04ce1d9))
* **button:** add static-styles-without-ripple for MWC consumption ([f4241a4](https://github.com/material-components/material-components-web/commit/f4241a42a49d130fcf5b5a9df2239276628a85f1))
* **button:** add theme mixin that emits custom properties instead ([4c40586](https://github.com/material-components/material-components-web/commit/4c405863bde72948dd131b07847b798cd8669764))
* **button:** emit custom properties fill button theme-styles ([a80c8b2](https://github.com/material-components/material-components-web/commit/a80c8b2c263b4f69a9df57e9837f7cb4ca438428))
* **button:** m3 elevation + icon base theme modules ([2da3606](https://github.com/material-components/material-components-web/commit/2da3606b97553ef152c9ef485432df2e0287b5de))
* **button:** resolve elevation keys in theme mixin ([843342f](https://github.com/material-components/material-components-web/commit/843342f99a2f76895fedb1ad1b2ff88a96b3fd7d))
* **chips:** Add theming Sass mixin to MDC Filter Chip ([8390093](https://github.com/material-components/material-components-web/commit/83900936a87a32accaab8bc8a1bdc5a998fcf18f))
* **chips:** Add theming Sass mixin to MDC input & suggestion Chip ([860ad06](https://github.com/material-components/material-components-web/commit/860ad06a1dd8bc76334ee5954109b4623f3682db))
* **chips:** Added theme mixins to Assist Chip ([d4e16a6](https://github.com/material-components/material-components-web/commit/d4e16a6c4876a3f144fdd1bade201f5b607b2bf6))
* **chips:** Export all non-deprecated members through chips index ([8647986](https://github.com/material-components/material-components-web/commit/864798678626ba41619324bcd10cf5e070bdd147))
* **chips:** Rename action's exported members to avoid naming collisions ([b49359c](https://github.com/material-components/material-components-web/commit/b49359c3581208ed7f84835c490a094699936f95))
* **chips:** Rename chip set's exported members to avoid naming collisions ([13db34b](https://github.com/material-components/material-components-web/commit/13db34b342741b4bc35b3c6a65a74e2291e41100))
* **chips:** Rename chip's exported members to avoid naming collisions ([470bd34](https://github.com/material-components/material-components-web/commit/470bd34e89b6683cd3a8f71bd1d3acfdf0aac5bf))
* **data-table:** Implement row click feature to MDC data table ([8de07c0](https://github.com/material-components/material-components-web/commit/8de07c02a50247f41cefcbd292b874b82f6d09b1))
* **data-table:** use new select + list templates for pagination ([08398f8](https://github.com/material-components/material-components-web/commit/08398f88046bfc1c3fad494b82c6e905d2fad890))
* **dialog:** Add theme styles mixin to dialog ([21ece53](https://github.com/material-components/material-components-web/commit/21ece536071235455a6905957f3c15dd3a7ddcf8))
* **dialog:** Separate static styles from dialog core-styles mixin ([43d2eed](https://github.com/material-components/material-components-web/commit/43d2eed2a908bae0d747b1ce4459b38cbd68c94a))
* **fab:** create theming file for small fabs ([d082790](https://github.com/material-components/material-components-web/commit/d082790f045f4542a5ebec082ba72ba0a106bcca))
* **fab:** prepare fab-extended for theming in MWC ([ce25bc3](https://github.com/material-components/material-components-web/commit/ce25bc3ecc6836d6c46e3789ff6eeb6faf7c07cf))
* **iconbutton:** Add `.mdc-icon-button--display-flex` class that centers icon via flexbox. When using the new theme API, the icon button should have this class. ([8355e14](https://github.com/material-components/material-components-web/commit/8355e14dc31c618a2102a846cd8cbefa08ad6007))
* **iconbutton:** Add MDC theme mixin that declares custom properties. ([fa7520f](https://github.com/material-components/material-components-web/commit/fa7520f6274cbab3ae7d8298554c4b0ff9e21a54))
* **iconbutton:** Add theme styles mixin. ([65aa63b](https://github.com/material-components/material-components-web/commit/65aa63b0ca587845437a4ee2a0b47556574d800b))
* **menu:** Added getter method to check fixed position status of menu ([fb76c50](https://github.com/material-components/material-components-web/commit/fb76c5069ebe5f62a1b01f6b2f4613d7c6bdeaae))
* **menu:** Adds option to prevent focus from being restored after an item action. ([65084ba](https://github.com/material-components/material-components-web/commit/65084baffaca256dd9eb77aae8fbafd379d8da00))
* **select:** start compatibility work for evolution lists ([e8554db](https://github.com/material-components/material-components-web/commit/e8554dbbf4e9886dbf7a335c4953c1611c378b68))
* **theme:** Added `validate-theme-keys()` mixin to validate theme keys only ([457d89a](https://github.com/material-components/material-components-web/commit/457d89aadf13d719af27435758feb8f6e254fe1e))


### BREAKING CHANGES

* **menu:** Adds new menu adapter method:

  /**
   * @return the attribute string if present on an element at the index
   * provided, null otherwise.
   */
  getAttributeFromElementAtIndex(index: number, attr: string): string|null;

PiperOrigin-RevId: 398575780
* **iconbutton:** MDC iconbutton `_index` Sass module will only export theme mixins.

PiperOrigin-RevId: 391773229
* **theme:** Renamed Sass mixins `validate-keys()` to `validate-theme()` in `@material/theme`

PiperOrigin-RevId: 390671152
* **fab:** Renamed Fab's mixins to deprecate legacy theme mixins.

PiperOrigin-RevId: 387378201





# [12.0.0](https://github.com/material-components/material-components-web/compare/v11.0.0...v12.0.0) (2021-07-27)


### Bug Fixes

* **base:** observer now listens to superclass properties ([88a33cd](https://github.com/material-components/material-components-web/commit/88a33cd70c0e87fcfb9e2ff58967f911ad71ace7))
* **button:** allow Mac zoom service to access button label ([29ac6ec](https://github.com/material-components/material-components-web/commit/29ac6ec1ef7316ecf03dc93ac0d63a3c09250052))
* **button:** Fix non-text buttons with icons to have reduced horizontal padding on the side with the icon. ([197f64f](https://github.com/material-components/material-components-web/commit/197f64fa2a4b78907261e820c5e1e8724777c92c))
* **chips:** Add documentation for action ([3db4d16](https://github.com/material-components/material-components-web/commit/3db4d1680bb4135c44042ac77521c8ff18032d14))
* **chips:** Add documentation for chip; update action docs ([22b83ad](https://github.com/material-components/material-components-web/commit/22b83adadc55d1d2ccf150bc4a4dc28432f1f453))
* **chips:** Add stubbed component methods along with tests ([06930c9](https://github.com/material-components/material-components-web/commit/06930c96b8a27ec886fc7873d7c0d0a4bec0761a))
* **chips:** Document chip set; add root readme ([5b6a460](https://github.com/material-components/material-components-web/commit/5b6a460167986caea058dd3f42c11c1edd761596))
* **chips:** Hide HCM focus indicator for presentational actions ([8c7d994](https://github.com/material-components/material-components-web/commit/8c7d994ae1699fd9e51ea80a073554d12959de3f))
* **chips:** Update chip set links ([4a7939c](https://github.com/material-components/material-components-web/commit/4a7939c9c3f3ec54bc486ee22567f9ca4e8f18bb))
* **circular-progress:** set explicit line-height to prevent inheritance ([e8e39ad](https://github.com/material-components/material-components-web/commit/e8e39ad19d9fae1ddbf065c9047905753ccd5754)), closes [#7118](https://github.com/material-components/material-components-web/issues/7118)
* **dialog:** prevent programmatic click on disabled default button ([e0c3462](https://github.com/material-components/material-components-web/commit/e0c346286a9656819302f04b0cf3f7b948429f74))
* **fab:** Fixed Fab ripple ([84f3db9](https://github.com/material-components/material-components-web/commit/84f3db9ed03fc414f347bfd88be384fe50646bd8)), closes [#7053](https://github.com/material-components/material-components-web/issues/7053)
* **icon-button:** prevent icon shift on press in IE11 ([8fc2927](https://github.com/material-components/material-components-web/commit/8fc29273c49f5bf5006f4df715bee85fbace9cb8))
* **linear-progress:** allow parent visibility prop to propagate to bar ([e543628](https://github.com/material-components/material-components-web/commit/e543628c3924a47ba63f5b7d58a2a931a260d1d3))
* **list:** Add core-styles mixin. ([fc7c4e5](https://github.com/material-components/material-components-web/commit/fc7c4e5ce2451ecd76f7ea3860b18a16e5f31bac))
* **list:** density configuration mixins do not account for leading avatars ([3674c62](https://github.com/material-components/material-components-web/commit/3674c6282db170dcf8331f93d779055c3852076b))
* **list:** Ensure trailing-only variants have leading padding in RTL contexts. ([81e2d4f](https://github.com/material-components/material-components-web/commit/81e2d4ff36518c586972aad4512b43d2bb0cd2d2))
* **list:** Fixed the selected + focused state of list item in HCM ([8ba3e29](https://github.com/material-components/material-components-web/commit/8ba3e298ca18cf8e7e11f07559e27287e74efeb8))
* **list:** Reset selectedIndex to UNSET_INDEX if #setSingleSelection(true) is called and there are no selected list items. ([4eecdea](https://github.com/material-components/material-components-web/commit/4eecdeaf09ed0429aa685ee35ea2ce7970af89cc))
* **list:** Selection lists without a selection focus first item. ([03f525f](https://github.com/material-components/material-components-web/commit/03f525f9ff880f27a43f2e50851a5dc6cd6b022c))
* **list:** Use more descriptive foundation method comments ([08d791f](https://github.com/material-components/material-components-web/commit/08d791f37a159f24686e97df983637947e2a1e87))
* **mdc-list:** invalid syntax in generated .d.ts bundle ([ce82846](https://github.com/material-components/material-components-web/commit/ce828464cdab59cac79add950fcac4f0310ce624))
* **menu:** correct menu opening delay ([a618380](https://github.com/material-components/material-components-web/commit/a6183801a07f109eff3ee209f42631340fbbe4b3)), closes [#5682](https://github.com/material-components/material-components-web/issues/5682) [#4411](https://github.com/material-components/material-components-web/issues/4411)
* **menu-surface:** slightly delay focus restoration to prevent lost focus on mobile devices ([9f68a93](https://github.com/material-components/material-components-web/commit/9f68a932e9d4168da10d8b9c3bb9191afcc3c68f))
* **ripple:** ensure custom properties are always emitted ([caa73ae](https://github.com/material-components/material-components-web/commit/caa73aeeea780ff65d4434fe1f38cec9396209c4))
* **rtl:** do not emit if a left/right value or replacement is null ([ec4ac52](https://github.com/material-components/material-components-web/commit/ec4ac5234c31df882a85a90af4d53b6797c8eb49))
* **rtl:** mixins work with pseudo elements ([f5b6110](https://github.com/material-components/material-components-web/commit/f5b6110d6a3c5ef1253165f5575ed3980748e19c))
* **switch:** export temporary deprecated version ([bd68539](https://github.com/material-components/material-components-web/commit/bd685395b652f448e889c123cda97efd77c85fcd))
* **switch:** misaligned handle when inside some flex containers ([ea1e1b8](https://github.com/material-components/material-components-web/commit/ea1e1b850795bd2b6ab7369a9c1e61d4b0d85f2e))
* **switch:** move ripple behind handle ([3e4c6dc](https://github.com/material-components/material-components-web/commit/3e4c6dca1921caa57e1097c03135a7ddf614f003))
* **switch:** overlay colors not showing and support -5 density ([33579e0](https://github.com/material-components/material-components-web/commit/33579e00bea179170016031fc3f24b70f57d74d2))
* **switch:** prevent collapsing in flex containers ([22f390c](https://github.com/material-components/material-components-web/commit/22f390c4364f0fc407106933154d68ae9e1ed950))
* **switch:** track colors can have opacity and not bleed through ([d923db7](https://github.com/material-components/material-components-web/commit/d923db73aa8db14c0d573208877d8cb6f4a57002))
* **tabscroller:** remove trailing underscore ([105b15b](https://github.com/material-components/material-components-web/commit/105b15b965e41bfaafedfb43e278cd5cb9d22195))
* **text-field:** remove disabled white patch in high contrast mode for Firefox 89+ ([17553e9](https://github.com/material-components/material-components-web/commit/17553e9f806551fba7d7b4d5c3b6de5df96db1af))
* prepare for [#7183](https://github.com/material-components/material-components-web/issues/7183) ([#7188](https://github.com/material-components/material-components-web/issues/7188)) ([77b94e8](https://github.com/material-components/material-components-web/commit/77b94e826c6c8c932bc5974855c645f7316f73af))
* **text-field:** show filled textarea label in Firefox 89+ high contrast ([90e08fc](https://github.com/material-components/material-components-web/commit/90e08fc6b82c805ab74d35b75b2e0c8fc72d6405))
* **textfield:** announce error message again if user blurs already invalid field ([75900a5](https://github.com/material-components/material-components-web/commit/75900a5a916249aa307626f7f6b441086146e1c0))
* **tooltip:** Adding missing `return` statement into `MDCTooltipComponent#isShown` method. ([4d95812](https://github.com/material-components/material-components-web/commit/4d95812f95ea60665fdab32a1ef8ff4d4e36a8b0))
* **tooltip:** Fixing component definition of MDCTooltipAdatper#deregisterAnchorEventHandler. ([d928692](https://github.com/material-components/material-components-web/commit/d928692b52157c91c46c9addf66f93ebdff09145))
* **tooltip:** Fixing logic for determining whether or not the user intends a tooltip to be hidden from the screenreader or not. ([cf5b9eb](https://github.com/material-components/material-components-web/commit/cf5b9eb86b764859ed8228377d4dd6dc7d2193c6))
* Remove lint check from test actions ([#7185](https://github.com/material-components/material-components-web/issues/7185)) ([1ee1fbf](https://github.com/material-components/material-components-web/commit/1ee1fbf01550f9ea19a72671e6fe360722d66385))
* **touch-target:** incorrect position in rtl when width is set ([bd1b4e9](https://github.com/material-components/material-components-web/commit/bd1b4e9d857f0b8fb7b5b9de9b8d5d78823f386d))


### Build System

* set AMD module module names within UMD bundles ([#7233](https://github.com/material-components/material-components-web/issues/7233)) ([9808de0](https://github.com/material-components/material-components-web/commit/9808de09310368c6352a0d40db84a802069d743d))


### Code Refactoring

* **checkbox:** Deprecated old checkbox theme mixin ([22d29cb](https://github.com/material-components/material-components-web/commit/22d29cbb4e7847ae56bf923d70508d1b164c1af6))
* **iconbutton:** Move ripple target to inner element ([33c9a73](https://github.com/material-components/material-components-web/commit/33c9a737af75f30f434565e98ada51b335495f0a))


### Features

* **base:** add MDCObserverFoundation class ([33e6f50](https://github.com/material-components/material-components-web/commit/33e6f50e915d5f2b70076fd0eb0e0d6654acba0c))
* **button:** Add focus indicator to link buttons in HCM. ([cad4896](https://github.com/material-components/material-components-web/commit/cad4896899cc89b1354ba5df95c3870efbb99af5))
* **button:** add typography & state layer keys to theming API ([068fd50](https://github.com/material-components/material-components-web/commit/068fd5028031778ada1f9f8469ac62ed60c9e7ef))
* **button:** employ elevation token resolvers in theming API ([ebb5c73](https://github.com/material-components/material-components-web/commit/ebb5c73bb87f1098d7e300372a811968a2d6c9f0))
* **button:** move icon-size to theming API ([85e9a6a](https://github.com/material-components/material-components-web/commit/85e9a6ac3ca1c9395d0d955326c3c1a7c3fe1a04))
* **card:** Moving ripple into a `mdc-card__ripple` element rather than the `mdc-card__primary-action`. ([8ace3b8](https://github.com/material-components/material-components-web/commit/8ace3b8106499cc9c126abde77258bcae7d5929d))
* **checkbox:** Added new theme mixin in checkbox to match token keys ([33a9548](https://github.com/material-components/material-components-web/commit/33a9548526d90fe41aae1e89c925720505fa5f85))
* **checkbox:** Added new theme mixin in checkbox to match token keys ([8e60818](https://github.com/material-components/material-components-web/commit/8e608183652b1cd051981a4266cae66b5591a148))
* **chips:** Support presentational actions ([8c68530](https://github.com/material-components/material-components-web/commit/8c685301d66ac6c8bc59b6b12930efd23804cce3))
* **dialog:** removing call to `#close` within `#destroy`. ([5631828](https://github.com/material-components/material-components-web/commit/5631828e1541df22feb879a5310e57494ee722a3))
* **dom:** add forced-colors-mode mixin ([8416fb9](https://github.com/material-components/material-components-web/commit/8416fb9195afcba61494bae1206dd1503dffb140))
* **elevation:** Create elevation resolver mixin ([5dfec7a](https://github.com/material-components/material-components-web/commit/5dfec7a1445efb45a7fb4d96ce037cafab205f30))
* **elevation:** Create resolver function ([c18b592](https://github.com/material-components/material-components-web/commit/c18b5925be3041e774b19f5f6f53f7d3a45d2240))
* **elevation:** Simplify box-shadow custom property support ([de48eff](https://github.com/material-components/material-components-web/commit/de48eff0d803b4e6c93834904e486cfea47bb03a))
* **elevation:** Support custom properties in resolver ([07a7375](https://github.com/material-components/material-components-web/commit/07a73750c0ebc1d05e19681c6f072cd5cceddfb6))
* **fab:** Added mixin that auto-generates custom properties for Fab ([8530d35](https://github.com/material-components/material-components-web/commit/8530d351494fc9a88e8e0dfd5e5d58de81a983d9))
* **fab:** Added mixin to auto-generate custom properties for Fab ([14767a8](https://github.com/material-components/material-components-web/commit/14767a8db432f8834d74a31e1577c3557a38c6d9))
* **fab:** Use elevation resolvers ([6e9fc4a](https://github.com/material-components/material-components-web/commit/6e9fc4a423a4657cc5d718aaf13d360c3bd27709))
* **fab:** Use elevation resolvers in custom property themes ([3f691ec](https://github.com/material-components/material-components-web/commit/3f691eccf61489d40e49bdf9f149b1591168c828))
* **iconbutton:** Add support for increased touch target to icon button. ([f43af56](https://github.com/material-components/material-components-web/commit/f43af5633f08e8080daed2e976771448d3effadb))
* **list:** Add public #getFocusedItemIndex to foundation. Also add a `forceUpdate` option to #setSelectedIndex that forces a UI update of the selected item. ([5d06051](https://github.com/material-components/material-components-web/commit/5d060518804437aa1ae3152562f1bb78b1af4aa6))
* **list:** Basic support for three-line lists. ([4bb5eea](https://github.com/material-components/material-components-web/commit/4bb5eea2b81268d4dc2f838beccb44dd4ff2857d))
* **menu:** Add public #getSelectedIndex to foundation. ([f705e80](https://github.com/material-components/material-components-web/commit/f705e8048ae60aceead575dfc35c8bb6233e9d23))
* **radio:** Added theme mixin that declares custom properties in MDC radio ([b87ebf7](https://github.com/material-components/material-components-web/commit/b87ebf74d4ca7de26552a9e55d79280a83ca05a9))
* **radio:** Added theme styles mixin to MDC radio ([464a002](https://github.com/material-components/material-components-web/commit/464a00286cbccfa256beb879631690277776486f))
* **radio:** Added theme styles mixin to Radio ([5823407](https://github.com/material-components/material-components-web/commit/5823407a71dc51fdf9919f3a85f62fcf125ec27b))
* **ripple:** Added theme styles and theme mixin to Ripple ([a2b0f4c](https://github.com/material-components/material-components-web/commit/a2b0f4cee3278c71d3ee2905f60dd37af6ee507c))
* **select:** Add #getUseDefaultValidation method to foundation. ([adeac05](https://github.com/material-components/material-components-web/commit/adeac0549eb04c5d4cd050d2e52378f7edbfa37e))
* **shape:** add shape map theme value support ([ec31ae1](https://github.com/material-components/material-components-web/commit/ec31ae1ed1e6483d972f0eddece0fbf30ac721c2))
* **slider:** Expose changing certain props after initialization to support MWC ([3f36ac7](https://github.com/material-components/material-components-web/commit/3f36ac75c431ee228807e04e985d2064a3274bd7))
* **switch:** add custom property theming support ([f147a22](https://github.com/material-components/material-components-web/commit/f147a2271bba2b4f1ae4df403baf86bac974b120))
* **switch:** add density custom property support ([598fccc](https://github.com/material-components/material-components-web/commit/598fcccc8d8945c0527a0553a6a937ddfdd80a8f))
* **switch:** add new component and foundation ([ef43e6d](https://github.com/material-components/material-components-web/commit/ef43e6d9607c7e8d6495b4a82e2178059dbe37fa))
* **switch:** add updated density styles ([cb162da](https://github.com/material-components/material-components-web/commit/cb162da374f5e5d613e6a4554f0e1efcdc443c04))
* **switch:** add updated RTL styles ([573dc7f](https://github.com/material-components/material-components-web/commit/573dc7ffd479527a885e95f4c8ece270363a31cc))
* **switch:** update switch to new design spec ([0ce2fdb](https://github.com/material-components/material-components-web/commit/0ce2fdb02a62bb31f945144aac58957989ecfba6))
* **switch:** update theme keys ([00b5899](https://github.com/material-components/material-components-web/commit/00b5899dcf803dcdf3795e70a970abafa247e1b3))
* **switch:** Use elevation token resolvers ([e1703be](https://github.com/material-components/material-components-web/commit/e1703bed9ba624d450cddbc5f07b08eb822f46ef))
* **tabs:** Add theming API to tabs ([bd25779](https://github.com/material-components/material-components-web/commit/bd25779b2bc6d10a00fbc19573f94a716f165cdf))
* **tabs:** Added theme-styles() mixin to tabs ([e38d744](https://github.com/material-components/material-components-web/commit/e38d7440f43c3ffe31407f1a76a35c482c42f7c5))
* **test:** Add overline support to two- and three-line lists. ([38d1846](https://github.com/material-components/material-components-web/commit/38d1846cca4f9abbcf2c073add3191bde0e03ffb))
* **test:** Add shape radius mixins to list. ([d5f1f7c](https://github.com/material-components/material-components-web/commit/d5f1f7c722ada3b62265e12e47a6f714d5bd7351))
* **theme:** add map-ext.split() helper function ([ec22e1d](https://github.com/material-components/material-components-web/commit/ec22e1da9746b38de654a18b0161c40c74e4e74f))
* **theme:** add state selector mixins ([d20dc6d](https://github.com/material-components/material-components-web/commit/d20dc6dba8e8824645404d0eaafa763d8b026ef0))
* **theme:** gss.annotate supports named arguments ([c50d20b](https://github.com/material-components/material-components-web/commit/c50d20bab49d5c00dd0a74e8616d02d8d87fba89))
* **theme:** theme.property() supports custom prop declarations ([474836a](https://github.com/material-components/material-components-web/commit/474836ad0f4f92d03ce7dd0c9f923b6ff9abac7c))
* **tooltip:** Adding foundation methods to allow users to configure the tooltip show and hide delay time. ([08db3d7](https://github.com/material-components/material-components-web/commit/08db3d737fa49893d1c3d1d3f7dd07367dd9eaeb))
* **tooltip:** Adds logic for generating a new tooltip position when all "standard" positions for tooltip w/ caret are invalid. ([9bc0eff](https://github.com/material-components/material-components-web/commit/9bc0effaf60a530bed8247f2bb9190dcbbbdec54))
* **tooltip:** Adds logic to determine valid position options for tooltip w/caret, and select which should be used. ([2ebfc53](https://github.com/material-components/material-components-web/commit/2ebfc537439508ea08bcd99991eed4fe838f3550))
* **tooltip:** Adjusting `transform-origin` for tooltips with caret so that the entrance animation originates from the caret. ([1a8d064](https://github.com/material-components/material-components-web/commit/1a8d064838299e07e97e5f30470c76c03074ac42))
* Create token package with resolvers ([9405502](https://github.com/material-components/material-components-web/commit/940550232c7925150e597c4f56433b7e5df59099))
* **tooltip:** Adjusting logic and styles so the caret better matches spec. ([55ad2d7](https://github.com/material-components/material-components-web/commit/55ad2d7d8f9bcc979f5334352620815d6ea9add6))
* **tooltip:** Fixes ordering of values provided to `tranform-origin`. ([25751d2](https://github.com/material-components/material-components-web/commit/25751d2ed4061129f206bdbc6682052b0c76709e))
* **tooltip:** Plain tooltips remain visible if the user hovers over them. ([ccce99c](https://github.com/material-components/material-components-web/commit/ccce99cd630b5a49ed40ba95b0e3d3d6fea74801))


### Reverts

* **checkbox:** Added new theme mixin in checkbox to match token keys ([b4c3f51](https://github.com/material-components/material-components-web/commit/b4c3f513eb1b42fa3844a265ccabb1e8644ea123))


### BREAKING CHANGES

* **tooltip:** - Tooltips intended to be hidden from the screen reader should be annotated with `data-hide-tooltip-from-screenreader="true"` (in addition to using `data-tooltip-id` rather than `aria-describedby`.

PiperOrigin-RevId: 386490861
* Breaking change for the UMD-case where the exports are bound to a global variable. Previously the entry-point would appear in camel-case, but now it's matching the actual package name in dash-case. This is unfortunately not avoidable with the current Webpack tooling. i.e. previous UMD users relying on the globals (which are rather rare anyway), would need to switch from `window.mdc.circularProgress` to `window.mdc['circular-progress]`.
* **checkbox:** Renamed old checkbox theme mixin for deprecation

PiperOrigin-RevId: 384568221
* **iconbutton:** Icon button now requires an inner ripple element with
class `mdc-icon-button__ripple`. See README for details.

PiperOrigin-RevId: 372153409





# [11.0.0](https://github.com/material-components/material-components-web/compare/v10.0.0...v11.0.0) (2021-04-15)


### Bug Fixes

* **banner:** Use role alertdialog. ([a07b6d4](https://github.com/material-components/material-components-web/commit/a07b6d486a7852a2089c9c13d5cf80d4ab65a425))
* **button:** add missing feature-targeting import ([71fe9a0](https://github.com/material-components/material-components-web/commit/71fe9a067878c810fe6a7d01b8e839764d7a802c))
* **button:** Fixed button's icon size scaling on browser zoom ([bc104ba](https://github.com/material-components/material-components-web/commit/bc104bae7c4e1bbcbedb085e6079432f06865cbf))
* **chips:** Expose deprecated resources in top-level TypeScript file ([67d780c](https://github.com/material-components/material-components-web/commit/67d780c795e2a61772f5d1639c202ced3fbc4dc4))
* **chips:** Fix incorrect references between deprecated and non-deprecated resources ([f8579b7](https://github.com/material-components/material-components-web/commit/f8579b7eaa22bf9da04ea5e4ec27418e001a0813))
* **chips:** Make chips wrap by default ([24255c4](https://github.com/material-components/material-components-web/commit/24255c408518dff48ed59c2529ee3d0496d6b40c))
* **chips:** Remove obsolete chips resources now in chips/deprecated/* ([87ac2fd](https://github.com/material-components/material-components-web/commit/87ac2fd5ca4ec7814216d16a0b0ef6a4474d7e92))
* **chips:** Remove obsolete resources ([40dd242](https://github.com/material-components/material-components-web/commit/40dd242d5ce4586002a8e5cb59ce2711572f1cf3))
* **chips:** rename deprecated trailing action classes ([48f4b67](https://github.com/material-components/material-components-web/commit/48f4b67fbd0d43377670673e56cb5868b3a11e1d))
* **chips:** Un-remove obsolete chips resources now in chips/deprecated/* ([7cf6782](https://github.com/material-components/material-components-web/commit/7cf67823ec45a93f5b458060b2ec632479d813c9))
* **chips:** Use deprecated chips in autoinit ([d2a39d3](https://github.com/material-components/material-components-web/commit/d2a39d300e3b9dee6c0d58d34522075f62b261c3))
* **circular-progress:** add annotation ([06dead2](https://github.com/material-components/material-components-web/commit/06dead2d69d09dfde582d0d9fb1473a61358a5f6))
* **dialog:** Add transparent border to dialog surface for HCM support. ([b2fa996](https://github.com/material-components/material-components-web/commit/b2fa996a1faa513fae691920cb339091d65b6c9b))
* **dialog:** Remove the unnecessary border on the dialog title when not needed, this adds an extra line in the UI on high contrast mode. With margins it is possible to keep the previous spacing and only add the border when needed. ([3344d12](https://github.com/material-components/material-components-web/commit/3344d12ad2eb74cfc4ef270290bcc0322ebe8566))
* **dom:** do not cache focusable elements in focus-trap ([7899e0f](https://github.com/material-components/material-components-web/commit/7899e0fe0a87cb255a5216333054207ef2687933))
* **fab:** add alternate decorator only when necessary ([0fd56a8](https://github.com/material-components/material-components-web/commit/0fd56a86b30846de63d7d1520dcecc4d5ece2347))
* **fab:** Apply extended shape radius in Extended FAB's theme mixin ([81911b7](https://github.com/material-components/material-components-web/commit/81911b7077801590c0f47bf17743f3b2b320b863))
* **list:** Correcting the selector mapping for CHILD_ELEMENTS_TO_TOGGLE_TABINDEX and FOCUSABLE_CHILD_ELEMENTS. ([8943b99](https://github.com/material-components/material-components-web/commit/8943b991fd04caab88ae543bad16ba9b47bc7634)), closes [#6829](https://github.com/material-components/material-components-web/issues/6829) [#6829](https://github.com/material-components/material-components-web/issues/6829)
* **list:** do not activate typeahead on certain modifier keys ([f1b1fd5](https://github.com/material-components/material-components-web/commit/f1b1fd5d3fa72c0a5dab305e3d7e782ff1421d7e))
* **progress-indicators:** hide from screenreaders on close ([d3a6862](https://github.com/material-components/material-components-web/commit/d3a6862af3ff4f0e157ebe95bd5f54a47fc14c48))
* **ripple:** Update states-selector() to use `:active:active` to match active specificity styles. ([faa7d32](https://github.com/material-components/material-components-web/commit/faa7d3226edbb15bdfca69e5ae98b2d7afdd861a))
* **select:** do not conduct anchor typeahead when modifier keys pressed ([6f678a9](https://github.com/material-components/material-components-web/commit/6f678a91a400ac3408e06523d18a134cf3513f6b))
* **select:** set hidden input value before firing change event ([2d6ba2c](https://github.com/material-components/material-components-web/commit/2d6ba2c239dfc7d4c2516507b11a32537c163852)), closes [#6904](https://github.com/material-components/material-components-web/issues/6904)
* **shape:** duplication bug with nested custom properties ([f77a4dd](https://github.com/material-components/material-components-web/commit/f77a4dd1a3eb4f6af2b5a7695081408de41211b7))
* **slider:** Fire custom `input` event on input change (i.e. value change via keyboard), mirroring the native `input` event behavior for range inputs. ([ec8f846](https://github.com/material-components/material-components-web/commit/ec8f8465f40bd13f61e2ad26c52314fc27fd5420))
* **slider:** Fix #quantize to use min value as the baseline. ([0f358dd](https://github.com/material-components/material-components-web/commit/0f358ddae37a8703b8b6f0b8e4de846a196d443a))
* **slider:** Fix JS floating point rounding errors by rounding values to a set number of decimal places based on the step size. ([6072ed6](https://github.com/material-components/material-components-web/commit/6072ed6040e1f65e099b876a4065fbb07378c186))
* **slider:** Fix track height. ([67eb0df](https://github.com/material-components/material-components-web/commit/67eb0df80920a53e04fc151b3ab065959e3e84dc))
* **slider:** Improve HCM borders, add missing [@noflip](https://github.com/noflip) annotations. ([e7202cb](https://github.com/material-components/material-components-web/commit/e7202cb576ff762664a3636ec01cebfa5a61be49))
* **slider:** Modify behavior such that for range sliders, presses in the middle of the range change the value (of the closest thumb). This provides a single-pointer alternative option to an otherwise gesture-based interaction. ([0b8cff7](https://github.com/material-components/material-components-web/commit/0b8cff73421489a5322dd39b8504c16ba0f26120))
* **slider:** Throttle slider UI updates. ([7d6a4bb](https://github.com/material-components/material-components-web/commit/7d6a4bb72f210c94161568f964e33cd8b06a8315))
* **slider:** Throw error for invalid initial values based on the step. ([3955d8d](https://github.com/material-components/material-components-web/commit/3955d8d3d2ba2766b59338f0ed7ae640388ce926))
* **tab:** Update ripple adapter to reflect sass ripple-target. ([97c4d40](https://github.com/material-components/material-components-web/commit/97c4d40356fcc89d9eb854ecf322ec7474aa597c))
* **theme:** do not emit when theme.property() replacements are null ([aa0aaf0](https://github.com/material-components/material-components-web/commit/aa0aaf026aae13532b3e3790992e9cc06397aa91))
* **theme:** parsing error when [@import-ing](https://github.com/import-ing) mdc-theme ([b62b126](https://github.com/material-components/material-components-web/commit/b62b1266d66734fcd9d60c7893ea048f83883f8f))
* **theme:** replace works for multiple replacements ([95322b1](https://github.com/material-components/material-components-web/commit/95322b11e3b0c938d9b4de56a1ba80d1ff42596b))
* update README to correct links. ([71e615b](https://github.com/material-components/material-components-web/commit/71e615bc8fa757d22190641db0c2940e24bdf59b))
* **tooltip:** flip precedence of data-tooltip-id and aria-describedby when finding TT id ([b2d22df](https://github.com/material-components/material-components-web/commit/b2d22df5b62003247fa5ca60a23b2ce8b6a17b33))
* **typography:** do not emit styles when setting null from global variable ([f5f1b61](https://github.com/material-components/material-components-web/commit/f5f1b613ce5c0dda39f617adbcfd2bb3f1862a74))


### Code Refactoring

* **snackbar:** Update a11y structure ([c60449b](https://github.com/material-components/material-components-web/commit/c60449bc8a967e14436bec9471df99678a78515a))
* **tooltip:** Moved the anchor element blur event listener from the component to within the foundation. ([0b4a4b2](https://github.com/material-components/material-components-web/commit/0b4a4b2ebe245f2382cb08bbbc34e7ffb4f43763))
* **typography:** Rename typography Sass function from pxToRem() to px-to-rem() ([8f0a11e](https://github.com/material-components/material-components-web/commit/8f0a11e32895f998c326ab4a10601a2e4d5e18db))


### Features

* **base:** add non-statics foundation constructor type ([e3ec22f](https://github.com/material-components/material-components-web/commit/e3ec22f4579292c962ab81d7fee1d31b38b7d036))
* **base:** add observer mixin ([4ceb422](https://github.com/material-components/material-components-web/commit/4ceb42220043f0ca90c57d77efec89ed29ae4508))
* **chips:** Expose "action" component ([03d34bb](https://github.com/material-components/material-components-web/commit/03d34bbad14df501f5faf9d03e62c0727ef6f7da))
* **chips:** Expose "chip" component ([cbc57c6](https://github.com/material-components/material-components-web/commit/cbc57c600f972ec88098d7ad9c4763f57dce0eb4))
* **chips:** Expose "chipset" component ([d6c5bcf](https://github.com/material-components/material-components-web/commit/d6c5bcf3743048e44d5462a2266804a7a75678a7))
* **chips:** Expose top-level resources ([fefc668](https://github.com/material-components/material-components-web/commit/fefc668d77004762598e0cd88f3248a03a6aab1b))
* **chips:** Remove touch target wrapper selector from chip set spacing ([367d88b](https://github.com/material-components/material-components-web/commit/367d88bdb32a24c73f935154d616d1d7abfd9dd8))
* **chips:** Start deprecation of chip ([e683bdf](https://github.com/material-components/material-components-web/commit/e683bdf4a0f6642b87f099b51425898dd4a1b644))
* **chips:** Start deprecation of chip root directory ([73a2271](https://github.com/material-components/material-components-web/commit/73a227194d7c0caf305329f1a8b22eb801a6114b))
* **chips:** Start deprecation of chip set ([148e8cf](https://github.com/material-components/material-components-web/commit/148e8cfccac563305b9fa6fd4a6e8602620d6426))
* **chips:** Start deprecation of chip trailing action ([9eeb35c](https://github.com/material-components/material-components-web/commit/9eeb35c384c78a65215bf8885d5ebb5fb1592cd9))
* **chips:** Truncate long chip labels by default ([f5c6db8](https://github.com/material-components/material-components-web/commit/f5c6db8fc71c654c47c68a4c717f8d8995f43e30))
* **dialog:** Adding `resize` and `orientationchange` event handlers into `MDCDialogFoundation`. ([1e06534](https://github.com/material-components/material-components-web/commit/1e06534774df290b9a29210ee3bcf57515da6e43))
* **dialog:** Adds support for "surface-scrim" over full-screen dialogs. This prevents a "double scrim" from appearing when showing a secondary dialog over a full-screen dialog on larger screens. ([cddb035](https://github.com/material-components/material-components-web/commit/cddb0355362acb031da308f98283f9d4ad9a2c84))
* **dom:** add option to skip restoring focus on release focus ([5c0ab74](https://github.com/material-components/material-components-web/commit/5c0ab74019c6a1925ee8ef7946d8df6d9494bf88))
* **dom:** add tab key keyboard.ts ([dc9c840](https://github.com/material-components/material-components-web/commit/dc9c8402374f46402c73f97e60206517e3186389))
* **fab:** Add theming API to Extended FABs ([f19c86d](https://github.com/material-components/material-components-web/commit/f19c86d13447d984b13b0e1d7e9651e498d8de04))
* **fab:** Added `$focus-outline-width` param to extended-padding() FAB mixin ([8ecd7c9](https://github.com/material-components/material-components-web/commit/8ecd7c9a93c5b885fad9a1e6fd8d17da77c05360))
* **fab:** Added focus outline theme keys to FAB theme mixin ([d6d8d04](https://github.com/material-components/material-components-web/commit/d6d8d04768f9904488a6814ec47a251a03313627))
* **fab:** Added theme mixin to primary FAB variant. ([f19bbc4](https://github.com/material-components/material-components-web/commit/f19bbc4af6493f642dc4b5b45a2dc0083fa293f0))
* **fab:** border custom prop support & add CPs for padding ([a6b3101](https://github.com/material-components/material-components-web/commit/a6b3101fb7641daab20db735b70421311534083b))
* **fix:** Ensure that secondary controls do not ripple. ([1f636b2](https://github.com/material-components/material-components-web/commit/1f636b205b9609d19a96bef707ab87a0f8ca4f1a))
* **fix:** Fix divider layout in right-to-left locales. ([f524626](https://github.com/material-components/material-components-web/commit/f5246264d139124f6abf2cf5e9f8ca98762eb0f7))
* **fix:** Remove old MDC list class names, preparing to release evolution. ([5f0fc44](https://github.com/material-components/material-components-web/commit/5f0fc444a706626a106c2b36116a56e9dc5b8c79))
* **fix:** Remove the "evolution" prefix from list evolution's class names. ([0cde52f](https://github.com/material-components/material-components-web/commit/0cde52f5a007f4b7da16afd45f7445d615d5a2f6))
* **fix:** Simplify divider styles to reflect new design guidance. ([f77c508](https://github.com/material-components/material-components-web/commit/f77c508600d4b0f4ce4a66c63d1064b545149570))
* **linear-progress:** add getBuffer ([9c85d50](https://github.com/material-components/material-components-web/commit/9c85d505bddf9c63ef52508c385ec59f1f947b8e))
* **list:** Add "deprecated" aliases for old list mixins / variables. ([f9cac96](https://github.com/material-components/material-components-web/commit/f9cac96cc2ad0422d73140a65dcffc5e4e8ec519))
* **list:** Add missing "deprecated" aliases for old list mixin. ([302c7a9](https://github.com/material-components/material-components-web/commit/302c7a960f3b2787f253908d963eaaaa0b8adfd4))
* **list:** Finalize list mixin/variable rename. ([c97d7d8](https://github.com/material-components/material-components-web/commit/c97d7d88102f96c4c61a1b7c3329f3efac3727f4))
* **list:** Rename deprecated MDC list class names. ([a678806](https://github.com/material-components/material-components-web/commit/a678806f5618f21a6bd28e3b881f92130b723f6e))
* **list:** Rename deprecated MDC list class names. ([941ca3b](https://github.com/material-components/material-components-web/commit/941ca3b3c4c53ea296149a983b0159c5567e1b2c))
* **list:** Update deprecated list class names so evolution can become default. ([606e767](https://github.com/material-components/material-components-web/commit/606e767ef6d1d98461d8910ece874b65d0143981))
* **list:** Update styles to reference "deprecated" mixins/variables. ([3201cae](https://github.com/material-components/material-components-web/commit/3201cae479a0dbf97c40dda1b9d32a5818d6ab62))
* **list:** Update styles to remove "evolution" prefix from mixins/variables. ([f9c9e39](https://github.com/material-components/material-components-web/commit/f9c9e39d6c0cddf796de7e821ec59e199aeab851))
* **menu:** add maxHeight setter ([bf670da](https://github.com/material-components/material-components-web/commit/bf670dad7247d7ac1db9bf00905921b5c09a5b4d))
* **menu-surface:** add option to always horizontally center on viewport ([23ea2d8](https://github.com/material-components/material-components-web/commit/23ea2d85e760325371c2529af7c99316d876c044))
* **ripple:** add active() mixin for styling active styles. ([9f2e85f](https://github.com/material-components/material-components-web/commit/9f2e85fb8453cab94f54eeb9e2d9e18600ed7fa0))
* **select:** allow programmatic change without firing event ([79ce087](https://github.com/material-components/material-components-web/commit/79ce0878b3233592c3188548711b311e5706d3dd)), closes [#6166](https://github.com/material-components/material-components-web/issues/6166)
* **slider:** Add mixin to customize thumb color in the activated (hover, focus, pressed) state. ([94f50b2](https://github.com/material-components/material-components-web/commit/94f50b260dd6cbf6cca5fbedd2a8681746e2cc1d))
* Add support for "mdc-deprecated-list-*" class names. ([9e52f55](https://github.com/material-components/material-components-web/commit/9e52f554437fa438c9b4c266f8e87ff370ec5dea))
* **switch:** add high-contrast mode focus shim mixin ([c91e8d1](https://github.com/material-components/material-components-web/commit/c91e8d141bc8b519ae1d8c7d1771c0d5110e84ad))
* **theme:** add configuration support for custom-properties ([1f318ff](https://github.com/material-components/material-components-web/commit/1f318ff0f033f9f51c8bf7f76ef997161ff62fd4))
* **theme:** add create-varname() for custom properties ([b522724](https://github.com/material-components/material-components-web/commit/b5227247d730171c02bd71e9b44106cd179aaf2a))
* **theme:** add key store ([07ff0c4](https://github.com/material-components/material-components-web/commit/07ff0c452c896f9f8131532538742bed0ad207c9))
* **tooltip:** Adding logic to position the caret relative to the tooltip. ([76da787](https://github.com/material-components/material-components-web/commit/76da7876cd1452cdabed5169bdbdfd06b4629cda))
* **tooltip:** Adding touchstart/touchend event listeners to tooltip. This allows tooltips attached to non-focusable elements to be surfaced on mobile. ([7cd26af](https://github.com/material-components/material-components-web/commit/7cd26af4dd2033dacce75d2df2d179f81286fe71))
* **tooltip:** Creating an `mdc-tooltip__surface-animation` class that holds all the style properties responsible for animating the tooltip in and out of the page. The existing `mdc-tooltip__surface` class will hold all the style properties that impact the visual appearance of the tooltip. ([56fc269](https://github.com/material-components/material-components-web/commit/56fc26962126e24a7c56124de7f36078409254a7))
* **tooltip:** Expose method that allows users to register additional scroll handlers on elements in the DOM. This should be used in situations where the tooltip anchor is a child of a scrollable element, and will ensure that the tooltip remains attached to the anchor when this element is scrolled. ([24609b8](https://github.com/material-components/material-components-web/commit/24609b82225f763c1dc9da16b1ee9e0dd3c52197))


### BREAKING CHANGES

* **typography:** Renamed typography Sass function from pxToRem() to px-to-rem()

PiperOrigin-RevId: 368489085
* **fix:** the old list implementation has been deprecated and now requires that class names use an "mdc-deprecated-list-*" prefix. The new implementation (list evolution), no longer uses a prefix ("mdc-evolution-list-*" is now just "mdc-list-*").

PiperOrigin-RevId: 364441086
* **snackbar:** Dom structure change, see README.md

PiperOrigin-RevId: 363926666
* **tooltip:**   Added adapter method:
  - registerAnchorEventHandler<K extends EventType>(
      evtType: K, handler: SpecificEventListener<K>): void;
  - deregisterAnchorEventHandler<K extends EventType>(
      evtType: K, handler: SpecificEventListener<K>): void;

PiperOrigin-RevId: 358401984





# [10.0.0](https://github.com/material-components/material-components-web/compare/v9.0.0...v10.0.0) (2021-02-05)


### Bug Fixes

* **data-table:** fix style ordering wrt select & use new variable-width mixin ([afb6889](https://github.com/material-components/material-components-web/commit/afb68894e63c9ed4bb3b3d523cbb4072480117a6)), closes [#6599](https://github.com/material-components/material-components-web/issues/6599)
* **dialog:** add property to customize suppressDefaultPressSelector ([772cc10](https://github.com/material-components/material-components-web/commit/772cc10686cc8994033a556ab70f4be106e902ee))
* **linear-progress:** fix RTL rendering ([c7c5da2](https://github.com/material-components/material-components-web/commit/c7c5da28f2cd2c1b54dd201d3797e112288fa86c))
* **list:** add support for density scaling. ([419e035](https://github.com/material-components/material-components-web/commit/419e035729c1ca1ee2b572ae4b1937e2d8cf04bc))
* **list:** add support for non-interactive list roles. ([fc8b045](https://github.com/material-components/material-components-web/commit/fc8b045f1127709c5929a3cd1c9c7d622db8ed42))
* **list:** ensure divider appears in IE high contrast mode. ([eff7b46](https://github.com/material-components/material-components-web/commit/eff7b46ac916d2eb130f7d826eee047c5f19e6f2))
* **menu:** Remove anchorSize height from calculations when anchored to bottom ([1631198](https://github.com/material-components/material-components-web/commit/16311983787cf46ccd22eaa4d6a076254cb32eea))
* **notched-outline:** fix notched outline no-label style ([99cfb6b](https://github.com/material-components/material-components-web/commit/99cfb6bd53f72240fe76852d0fdaa0b82e7dca39))
* **select:** debounce click on anchor ([b39094d](https://github.com/material-components/material-components-web/commit/b39094d145f9b96c1c75e2b5fcce7b76c9b31bf1))
* **select:** set aria-expanded false earlier when menu closes ([df00c2b](https://github.com/material-components/material-components-web/commit/df00c2b30342877eba7d1e21e8a57141739155a5))
* **slider:** Add aria-hidden to value indicator container, to avoid duplicate value announcements for screenreader users. ([9687353](https://github.com/material-components/material-components-web/commit/96873535640a2e9141ff8e17e64fcb5e28d90f53))
* **slider:** Adjust hidden input dimensions to take slider dimensions, such that screenreader focus indicators show a highlight around the entire slider. ([fd22355](https://github.com/material-components/material-components-web/commit/fd22355f72ab304aec043f53ced92fa9adfef457))
* **slider:** Fire custom change event on input change. ([07deaec](https://github.com/material-components/material-components-web/commit/07deaec27a6f92b9a00c7698c49d3e1a93e504ea))
* **slider:** Fix bug where value indicator container took space and could be hovered over / clicked when hidden. ([832668d](https://github.com/material-components/material-components-web/commit/832668d33389a0b6194d3d8ef53aa8c252aa8f5d))
* **slider:** Mark ripple event handler as passive. Fixes [#6746](https://github.com/material-components/material-components-web/issues/6746) ([abdd100](https://github.com/material-components/material-components-web/commit/abdd10065367738148866c165b339a3e3b9b1fc3))
* **slider:** Remove big step options. Now that we're using a native range input, big step is not customizable - we follow browser defaults for big step. ([ae27b44](https://github.com/material-components/material-components-web/commit/ae27b44b078ebdad3669b03abc9f28ed184db803))
* **slider:** Update both thumbs' value indicator UI's if layout is invoked with undefined `thumb`. ([489d4c2](https://github.com/material-components/material-components-web/commit/489d4c219d1747a8e5de3f210f00898c18201b24))
* **slider:** Use `pointer-events: none` instead of `visibility: hidden` to hide the value indicator container. Adding `visibility: hidden` removes the exit animation since the value indicator is immediately hidden. ([a94bd8d](https://github.com/material-components/material-components-web/commit/a94bd8deb879b0321e8227d26f338789ef3ffb90))
* **slider:** Use mouse/touch events on iOS, to work around pointer events bug. ([671d72d](https://github.com/material-components/material-components-web/commit/671d72d9544d3d1630966ec4e78b5705700defe7)), closes [#6715](https://github.com/material-components/material-components-web/issues/6715)
* **tabs:** Expose min width mixin and set to 90px per spec. ([c4ab987](https://github.com/material-components/material-components-web/commit/c4ab987221d5a3b9ab588321bb0347f5d665505a))
* **theme:** ensure either() works with false values ([8e66dbf](https://github.com/material-components/material-components-web/commit/8e66dbfeebe3d5fec438c69093d7f9941c0fbf10))
* **tooltip:** Adds "will-change" into CSS to prevent the tooltip from "jittering" when animating in. ([7a003ac](https://github.com/material-components/material-components-web/commit/7a003acf09345920d917cb4ab7c298a66e4fe184))
* **tooltip:** Change foundation to check for "dialog" on the anchor element's aria-haspopup attribute instead of checking for "true". ([b8a1a58](https://github.com/material-components/material-components-web/commit/b8a1a58e4ebb49a73725d2e7ae8aef09c07db09d))
* **tooltip:** Clear hideTimeout in handleAnchorMouseEnter so that the tooltip will not be hidden if the user rapidly moves the mouse in and out of the anchor element. ([365c693](https://github.com/material-components/material-components-web/commit/365c69360230540a67dd141f6bec999b2541a7e8))
* **tooltip:** Fix rich tooltip tests to not use aria-describedby to associate rich tooltips with their anchor elements. This is because interactive rich tooltips should not be used with aria-describedby per a11y guidance. ([251ac04](https://github.com/material-components/material-components-web/commit/251ac04c0a976d48a6be33cc7fcd76f6e2700aac))
* adjust meta baseline and update color mixins. ([07f3e01](https://github.com/material-components/material-components-web/commit/07f3e01b75306a7481c7077cd3ed12a87399958e))


### Code Refactoring

* Remove MDC theme's deep-get, used sass:map's get API instead. ([37fbae1](https://github.com/material-components/material-components-web/commit/37fbae10d6fb993c0ea866959fb5564c052002cc))


### Features

* **banner:** Add mobile-stacked variant support to banner. ([a0b2db2](https://github.com/material-components/material-components-web/commit/a0b2db26b550162d2e409489c5ded3381b7c7dc2))
* **button:** Add in HCM support to the mdc button as an opt-in mixin. ([121e1f3](https://github.com/material-components/material-components-web/commit/121e1f303f10e55c9cc5e6508bcd559c6ea7dc7b))
* **button:** consolidate states into button mixins ([637d15d](https://github.com/material-components/material-components-web/commit/637d15da60919641e5571f280562c4fb3491c8f0))
* **button:** thread state keys through theme config ([05f2496](https://github.com/material-components/material-components-web/commit/05f249666dff2bae35a1a6c1e7a5ed89eb193213))
* **checkbox:** Add CSS custom properties to MDC checkbox for density theming ([9244508](https://github.com/material-components/material-components-web/commit/9244508bd82ab65635169cfacd74f1a25ebaab7e))
* **checkbox:** Add validation to MDC Checkbox theme mixin ([2d5f32d](https://github.com/material-components/material-components-web/commit/2d5f32d41cda48ca8e3c1d2244d6fb3bb4c6aa7d))
* **circular-progress:** do not require HTML without whitespaces ([8648b82](https://github.com/material-components/material-components-web/commit/8648b8258f7f87edcc1d58a2bc7db3d78425508f))
* **dialog:** add custom property for z-index ([776c186](https://github.com/material-components/material-components-web/commit/776c1868154e5b99a332f60927b78b32b82fe19f))
* **dialog:** Adding styling for scroll bar dividers, and adding logic to show said dividers only when content is scrolled "behind" the header or footer of the dialog. ([e383944](https://github.com/material-components/material-components-web/commit/e383944e9792ea1971c7814e0e63e2e00f99a468))
* **dialog:** Adds and defines styling for the "header bar" on a full-screen dialog. ([089de51](https://github.com/material-components/material-components-web/commit/089de519c1c2f0378b9852dafd3ca5a304268a44))
* **iconbutton:** Add in HCM support to the mdc iconbutton as an opt-in mixin. ([fd61b04](https://github.com/material-components/material-components-web/commit/fd61b04760d96fcc1c96e43ca8e0663d16f5a995))
* **linear-progress:** remove aria-valuemin/max attrs for indeterminate ([4321323](https://github.com/material-components/material-components-web/commit/4321323e4bea2da8192b81ebdf8c6a9ee1e76aa0))
* **list:** support ctrl + a keyboard shortcut ([eefef49](https://github.com/material-components/material-components-web/commit/eefef49d86c69b1985aa4e5fa5b8809ba1f0a1f4)), closes [#6366](https://github.com/material-components/material-components-web/issues/6366)
* **list:** Update the MDC component for List Evolution. ([766981c](https://github.com/material-components/material-components-web/commit/766981c15a200b374a14c2ab80bf746824bf7434))
* **menu,select:** enable fixed menu position in mwc-select ([b9adb7a](https://github.com/material-components/material-components-web/commit/b9adb7a0f6d2871bcd87664ab857fb62392c27d4)), closes [#2062](https://github.com/material-components/material-components-web/issues/2062)
* **select:** add mixin for variable width ([30c11bf](https://github.com/material-components/material-components-web/commit/30c11bfc24e426c0647645758e4f9d98f589e85c))
* **slider:** Add hidden input to slider, to support forms submission. This is also prep for moving to use an \<input type="range"\> behind the scenes, in order to support touch-based AT's. ([b98d15d](https://github.com/material-components/material-components-web/commit/b98d15d90b19e69066c0b417ee0d8b11ab733e20))
* **slider:** Modify continuous slider to use step value by default, and give clients the option to customize step value for continuous sliders. ([7ad038e](https://github.com/material-components/material-components-web/commit/7ad038e1d37171dc1fc931112b17f085533f7048))
* **slider:** Use input with type="range" to back slider component. This ensures that sliders can be adjusted with touch-based assistive technologies, as the current ARIA spec for sliders is not compatible with e.g. TalkBack/Android. ([9083b7d](https://github.com/material-components/material-components-web/commit/9083b7d61b1dda2c5acefda6e8939870a358e98f))
* **snackbar:** Add 1px transparent border for high contrast support ([15a4d40](https://github.com/material-components/material-components-web/commit/15a4d40dd708775c6120165422c9ebadee4c8f6f))
* **theme:** add either() utility function ([5268222](https://github.com/material-components/material-components-web/commit/5268222c432bb886add05cbb1779909117cf1620))
* **theme:** add validation option to disallow custom properties ([fec7b42](https://github.com/material-components/material-components-web/commit/fec7b42ca54baf37487cadaf96ac8cf559d6ccd0))
* **theme:** Added validation mixin to validate provided theme configuration keys ([1c156d6](https://github.com/material-components/material-components-web/commit/1c156d69d76efcfa39c706f7f6ae74e96c2bd541))
* **theme:** allow lists in replace maps ([d2959b1](https://github.com/material-components/material-components-web/commit/d2959b16ca9a2e4574984b8e459993c9c9a2075a))
* **theme:** emit CSS var() declarations when provided a standalone custom prop ([1a3a396](https://github.com/material-components/material-components-web/commit/1a3a396293df35d9621155e9168df35d39d83fee))
* **tooltip:** Add positioning adjustment and position specification for rich tooltips. Rich tooltips default to the END position and does not support CENTER positioning. ([384a8ee](https://github.com/material-components/material-components-web/commit/384a8eeb163798df6655c8a49c36428ede852e15))
* **tooltip:** Added persistent variant for rich tooltips that shows/hides based on mouse clicks on the anchor element. Clicks on elements other than the anchor will also hide the persistent variant. ([9775856](https://github.com/material-components/material-components-web/commit/9775856508a7256cb7dc93d0c3e47f6d87c08c93))
* **tooltip:** Adds `transform-origin` on tooltip surface so tooltip entrance animation has a direction based on its alignment with the anchor element. ([623af86](https://github.com/material-components/material-components-web/commit/623af861e1852603fd4778fb0abbef58b427333c))
* **tooltip:** Adjust  tooltip position on `scroll` and `resize` events. This ensures that the tooltip remains pinned to the anchor element despite page movement. ([a415276](https://github.com/material-components/material-components-web/commit/a41527604048d218879240aaaf04aff7389053d1))
* **tooltip:** Adjusting tooltip positioning logic so that the tooltip remains within the viewport even if the anchor element is partially off-screen. ([482ff90](https://github.com/material-components/material-components-web/commit/482ff909132b2e8f81791d7128cb0a3d2ff371a8))
* **tooltip:** Change rich tooltip to use position absolute instead of fixed and rely on a position relative parent element so that if the parent has a transform, perspective, or filter property set to something other than none, the positioning would still work. ([0c95c9f](https://github.com/material-components/material-components-web/commit/0c95c9f7bf1e0d465e99fd7dd3f1497d37d871ff))
* **tooltip:** Define styling to set the full-screen dialog size depending on the viewport size. ([fe13dd1](https://github.com/material-components/material-components-web/commit/fe13dd1308dc695898b2c7d3dfbddccc7d38b420))
* **tooltip:** Expose `hide` and `isShown` methods in the MDCTooltip component. This allows MDC clients to create their own class to enforce only one tooltip being shown at a time. ([c5e18b0](https://github.com/material-components/material-components-web/commit/c5e18b0203a3c474384bc5902a15855636ce849b))
* **tooltip:** Hide rich tooltip if mouse leaves rich tooltip. Rich tooltip persists if mouse leaves rich tooltip and enters anchor. ([6d8574f](https://github.com/material-components/material-components-web/commit/6d8574fe1db3a60dfb5a45ce8c6c6718700c2dfd))
* **tooltip:** Reducing minimum threshold distance between tooltip and viewport from 32px to 8px. ([23491cf](https://github.com/material-components/material-components-web/commit/23491cf85b8831896f95879e8aea258d5ca7f653))
* **tooltip:** Restore focus to the anchor element when the ESC button is pressed while the focus is in the tooltip for rich tooltips. Default rich tooltips should have focus restored to anchor and not have rich tooltips show. ([eabf9d5](https://github.com/material-components/material-components-web/commit/eabf9d5c2d9b56e316db98f2d8e16bf12f1ef501))
* **tooltip:** Set up base sass for rich tooltip. Rich tooltips are currently in development and is not yet ready for use. ([4ae94ff](https://github.com/material-components/material-components-web/commit/4ae94ff7816d87fde3285a0c2fd48b94ff0bbdab))
* **tooltip:** Set up rich tooltip to persist if mouse leaves anchor and enters rich tooltip. ([c927a5d](https://github.com/material-components/material-components-web/commit/c927a5d05761d0a80f886b2b7627e600df38c467))
* **tooltip:** The aria-expanded attribute of the anchor element will only be changed for anchor elements with interactive rich tooltips. Non-interactive rich tooltip anchor elements do not have the aria-haspopup and aria-expanded attributes. ([c5dda80](https://github.com/material-components/material-components-web/commit/c5dda809d5e4c110f3b4bb37c9646e572026d58d))
* **tooltip:** When the anchor element blurs, the rich tooltip will only be hidden if the focus is changed to a non-rich tooltip element. ([6871336](https://github.com/material-components/material-components-web/commit/6871336f11f3cc7d94c6314dc049092e0427106c))
* Added global variable to conditionally emit CSS selector fallback declarations ([7b0e2b3](https://github.com/material-components/material-components-web/commit/7b0e2b3775d006126161bd688851d490d19e9558))
* **tooltip:** When the rich tooltip element focuses out, hide the rich tooltip if the new focused element is not the anchor element or an element within the rich tooltip. ([1085c3b](https://github.com/material-components/material-components-web/commit/1085c3b2df7d3c1b528e1b9ba5557975fa959401))


### BREAKING CHANGES

* **theme:** custom-properties.apply() has been renamed to declaration() to better align with css.declaration()
* **tooltip:**   Added adapter methods:
  - getComputedStyleProperty(propertyName: string): string;
  - getParentBoundingRect(): ClientRect|null;
* **tooltip:**   Added adapter method:
  - tooltipContainsElement(element: HTMLElement): boolean;
* Removed `deep-get()` API from mdc-theme, use `sass:map`'s get() API instead.
* **tooltip:**   Added adapter method:
  - anchorContainsElement(element: HTMLElement): boolean;
* **slider:** Slider is now backed by an input of type="range". Additionally, adapter methods (focusInput, isInputFocused, registerInputEventHandler, deregisterInputEventHandler) were added.
* **tooltip:**   Added adapter methods:
  - setAnchorAttribute(attr: string, value: string): void;
  - registerEventHandler<K extends EventType>(
        evtType: K, handler: SpecificEventListener<K>): void;
  - deregisterEventHandler<K extends EventType>(
        evtType: K, handler: SpecificEventListener<K>): void;
* **slider:** Adds slider adapter methods (get/setInputValue, get/setInputAttribute, removeInputAttribute). Slider DOM structure now contains a hidden input.
  

# [9.0.0](https://github.com/material-components/material-components-web/compare/v8.0.0...v9.0.0) (2020-12-29)


### Bug Fixes

* **data-table:** fix style ordering wrt select & use new variable-width mixin ([afb6889](https://github.com/material-components/material-components-web/commit/afb68894e63c9ed4bb3b3d523cbb4072480117a6)), closes [#6599](https://github.com/material-components/material-components-web/issues/6599)
* **list:** add support for density scaling. ([419e035](https://github.com/material-components/material-components-web/commit/419e035729c1ca1ee2b572ae4b1937e2d8cf04bc))
* **list:** add support for non-interactive list roles. ([fc8b045](https://github.com/material-components/material-components-web/commit/fc8b045f1127709c5929a3cd1c9c7d622db8ed42))
* **list:** ensure divider appears in IE high contrast mode. ([eff7b46](https://github.com/material-components/material-components-web/commit/eff7b46ac916d2eb130f7d826eee047c5f19e6f2))
* Adding tests. ([240c5f7](https://github.com/material-components/material-components-web/commit/240c5f74f381967ede9eb1fa13754d2f0282da9e))
* adjust meta baseline and update color mixins. ([07f3e01](https://github.com/material-components/material-components-web/commit/07f3e01b75306a7481c7077cd3ed12a87399958e))
* Document stylelint exceptions ([f89d8b8](https://github.com/material-components/material-components-web/commit/f89d8b8f295c80c7b7e691ec712a30de8a0b26d5))
* **notched-outline:** fix notched outline no-label style ([99cfb6b](https://github.com/material-components/material-components-web/commit/99cfb6bd53f72240fe76852d0fdaa0b82e7dca39))
* **select:** debounce click on anchor ([b39094d](https://github.com/material-components/material-components-web/commit/b39094d145f9b96c1c75e2b5fcce7b76c9b31bf1))
* **slider:** Adjust hidden input dimensions to take slider dimensions, such that screenreader focus indicators show a highlight around the entire slider. ([fd22355](https://github.com/material-components/material-components-web/commit/fd22355f72ab304aec043f53ced92fa9adfef457))
* **slider:** Fix bug where value indicator container took space and could be hovered over / clicked when hidden. ([832668d](https://github.com/material-components/material-components-web/commit/832668d33389a0b6194d3d8ef53aa8c252aa8f5d))
* **slider:** Remove big step options. Now that we're using a native range input, big step is not customizable - we follow browser defaults for big step. ([ae27b44](https://github.com/material-components/material-components-web/commit/ae27b44b078ebdad3669b03abc9f28ed184db803))
* **slider:** Update both thumbs' value indicator UI's if layout is invoked with undefined `thumb`. ([489d4c2](https://github.com/material-components/material-components-web/commit/489d4c219d1747a8e5de3f210f00898c18201b24))
* **tabs:** Expose min width mixin and set to 90px per spec. ([c4ab987](https://github.com/material-components/material-components-web/commit/c4ab987221d5a3b9ab588321bb0347f5d665505a))


### Code Refactoring

* Remove MDC theme's deep-get, used sass:map's get API instead. ([37fbae1](https://github.com/material-components/material-components-web/commit/37fbae10d6fb993c0ea866959fb5564c052002cc))


### Features

* **banner:** Add mobile-stacked variant support to banner. ([a0b2db2](https://github.com/material-components/material-components-web/commit/a0b2db26b550162d2e409489c5ded3381b7c7dc2))
* **checkbox:** Add CSS custom properties to MDC checkbox for density theming ([9244508](https://github.com/material-components/material-components-web/commit/9244508bd82ab65635169cfacd74f1a25ebaab7e))
* **checkbox:** Add validation to MDC Checkbox theme mixin ([2d5f32d](https://github.com/material-components/material-components-web/commit/2d5f32d41cda48ca8e3c1d2244d6fb3bb4c6aa7d))
* **circular-progress:** do not require HTML without whitespaces ([8648b82](https://github.com/material-components/material-components-web/commit/8648b8258f7f87edcc1d58a2bc7db3d78425508f))
* **linear-progress:** remove aria-valuemin/max attrs for indeterminate ([4321323](https://github.com/material-components/material-components-web/commit/4321323e4bea2da8192b81ebdf8c6a9ee1e76aa0))
* **list:** support ctrl + a keyboard shortcut ([eefef49](https://github.com/material-components/material-components-web/commit/eefef49d86c69b1985aa4e5fa5b8809ba1f0a1f4)), closes [#6366](https://github.com/material-components/material-components-web/issues/6366)
* **select:** add mixin for variable width ([30c11bf](https://github.com/material-components/material-components-web/commit/30c11bfc24e426c0647645758e4f9d98f589e85c))
* **slider:** Add hidden input to slider, to support forms submission. This is also prep for moving to use an \<input type="range"\> behind the scenes, in order to support touch-based AT's. ([b98d15d](https://github.com/material-components/material-components-web/commit/b98d15d90b19e69066c0b417ee0d8b11ab733e20))
* **slider:** Modify continuous slider to use step value by default, and give clients the option to customize step value for continuous sliders. ([7ad038e](https://github.com/material-components/material-components-web/commit/7ad038e1d37171dc1fc931112b17f085533f7048))
* **slider:** Use input with type="range" to back slider component. This ensures that sliders can be adjusted with touch-based assistive technologies, as the current ARIA spec for sliders is not compatible with e.g. TalkBack/Android. ([9083b7d](https://github.com/material-components/material-components-web/commit/9083b7d61b1dda2c5acefda6e8939870a358e98f))
* **theme:** Added validation mixin to validate provided theme configuration keys ([1c156d6](https://github.com/material-components/material-components-web/commit/1c156d69d76efcfa39c706f7f6ae74e96c2bd541))
* **tooltip:** Add positioning adjustment and position specification for rich tooltips. Rich tooltips default to the END position and does not support CENTER positioning. ([384a8ee](https://github.com/material-components/material-components-web/commit/384a8eeb163798df6655c8a49c36428ede852e15))
* **tooltip:** Added persistent variant for rich tooltips that shows/hides based on mouse clicks on the anchor element. Clicks on elements other than the anchor will also hide the persistent variant. ([9775856](https://github.com/material-components/material-components-web/commit/9775856508a7256cb7dc93d0c3e47f6d87c08c93))
* **tooltip:** Adjust  tooltip position on `scroll` and `resize` events. This ensures that the tooltip remains pinned to the anchor element despite page movement. ([a415276](https://github.com/material-components/material-components-web/commit/a41527604048d218879240aaaf04aff7389053d1))
* **tooltip:** Adjusting tooltip positioning logic so that the tooltip remains within the viewport even if the anchor element is partially off-screen. ([482ff90](https://github.com/material-components/material-components-web/commit/482ff909132b2e8f81791d7128cb0a3d2ff371a8))
* **tooltip:** Hide rich tooltip if mouse leaves rich tooltip. Rich tooltip persists if mouse leaves rich tooltip and enters anchor. ([6d8574f](https://github.com/material-components/material-components-web/commit/6d8574fe1db3a60dfb5a45ce8c6c6718700c2dfd))
* **tooltip:** Make persistent rich tooltips persist when click target is within the rich tooltip. ([fb194dd](https://github.com/material-components/material-components-web/commit/fb194dd354d2c912f997c500347557edcba1440d))
* **tooltip:** Reducing minimum threshold distance between tooltip and viewport from 32px to 8px. ([23491cf](https://github.com/material-components/material-components-web/commit/23491cf85b8831896f95879e8aea258d5ca7f653))
* **tooltip:** Restore focus to the anchor element when the ESC button is pressed while the focus is in the tooltip for rich tooltips. Default rich tooltips should have focus restored to anchor and not have rich tooltips show. ([eabf9d5](https://github.com/material-components/material-components-web/commit/eabf9d5c2d9b56e316db98f2d8e16bf12f1ef501))
* **tooltip:** Set up base sass for rich tooltip. Rich tooltips are currently in development and is not yet ready for use. ([4ae94ff](https://github.com/material-components/material-components-web/commit/4ae94ff7816d87fde3285a0c2fd48b94ff0bbdab))
* **tooltip:** Set up rich tooltip to persist if mouse leaves anchor and enters rich tooltip. ([c927a5d](https://github.com/material-components/material-components-web/commit/c927a5d05761d0a80f886b2b7627e600df38c467))
* **tooltip:** The aria-expanded attribute of the anchor element will only be changed for anchor elements with interactive rich tooltips. Non-interactive rich tooltip anchor elements do not have the aria-haspopup and aria-expanded attributes. ([c5dda80](https://github.com/material-components/material-components-web/commit/c5dda809d5e4c110f3b4bb37c9646e572026d58d))
* **tooltip:** When the anchor element blurs, the rich tooltip will only be hidden if the focus is changed to a non-rich tooltip element. ([6871336](https://github.com/material-components/material-components-web/commit/6871336f11f3cc7d94c6314dc049092e0427106c))
* **tooltip:** When the rich tooltip element focuses out, hide the rich tooltip if the new focused element is not the anchor element or an element within the rich tooltip. ([1085c3b](https://github.com/material-components/material-components-web/commit/1085c3b2df7d3c1b528e1b9ba5557975fa959401))
* Added global variable to conditionally emit CSS selector fallback declarations ([7b0e2b3](https://github.com/material-components/material-components-web/commit/7b0e2b3775d006126161bd688851d490d19e9558))


### BREAKING CHANGES

* **tooltip:**   Added adapter method:
  - tooltipContainsElement(element: HTMLElement): boolean;
Rich tooltips are currently in development and is not yet ready for use.

PiperOrigin-RevId: 346325244
* Removed `deep-get()` API from mdc-theme, use `sass:map`'s get() API instead.

PiperOrigin-RevId: 345257138
* **tooltip:**   Added adapter method:
  - anchorContainsElement(element: HTMLElement): boolean;
Rich tooltips are currently in development and is not yet ready for use.

PiperOrigin-RevId: 345221617
* **slider:** Slider is now backed by an input of type="range". Additionally, adapter methods (focusInput, isInputFocused, registerInputEventHandler, deregisterInputEventHandler) were added.

PiperOrigin-RevId: 344116908
* **tooltip:**   Added adapter methods:
  - setAnchorAttribute(attr: string, value: string): void;
  - registerEventHandler<K extends EventType>(
        evtType: K, handler: SpecificEventListener<K>): void;
  - deregisterEventHandler<K extends EventType>(
        evtType: K, handler: SpecificEventListener<K>): void;
Rich tooltips are currently in development and is not yet ready for use.

PiperOrigin-RevId: 343894231
* **slider:** Adds slider adapter methods (get/setInputValue, get/setInputAttribute, removeInputAttribute). Slider DOM structure now contains a hidden input.

PiperOrigin-RevId: 343157208





# [8.0.0](https://github.com/material-components/material-components-web/compare/v7.0.0...v8.0.0) (2020-11-02)


### Bug Fixes

* **banner:** Update image to graphic and support material icons ([346069c](https://github.com/material-components/material-components-web/commit/346069ccb2a831b37df62bf71135acad92fd69c3))
* **card:** ensure border-adjacent content renders correctly. ([790ca85](https://github.com/material-components/material-components-web/commit/790ca85fd643229e95f2d1c08811c8e0e5513805))
* **checkbox:** Use secondary and on-secondary as default colors ([b95172e](https://github.com/material-components/material-components-web/commit/b95172e69613c0defe82191b86ed1c1999b74400)), closes [#5730](https://github.com/material-components/material-components-web/issues/5730)
* **chip-set:** crash when only item is removed ([a653b68](https://github.com/material-components/material-components-web/commit/a653b68118e823ae30b1f47f87a4a8e5e69d9186))
* **chips:** Handle IE/Edge specific key names in keyboard navigation logic ([3657f88](https://github.com/material-components/material-components-web/commit/3657f886327182c26f1d1555b2ac67c2128140b5))
* **circular-progress:** Add .npmignore file to ignore typescript files when publishing ([#5801](https://github.com/material-components/material-components-web/issues/5801)) ([f172b0f](https://github.com/material-components/material-components-web/commit/f172b0f90a91d8d3d700763d1496bb7b9c1a8d51)), closes [#5800](https://github.com/material-components/material-components-web/issues/5800)
* **circular-progress:** Default all variables ([430fd02](https://github.com/material-components/material-components-web/commit/430fd025b07b3e15dd699620fbbfca75f74632a3))
* **circular-progress:** display properly inside button ([2bd09a7](https://github.com/material-components/material-components-web/commit/2bd09a706efb991fd71e171db8994f0282a1f02e))
* **circular-progress:** display properly inside button ([000d648](https://github.com/material-components/material-components-web/commit/000d6481570c361cf4c66b55c287eea434b6d11e)), closes [#6388](https://github.com/material-components/material-components-web/issues/6388)
* **circular-progress:** fix determinate transition typo & 4 color keyframes ([a301636](https://github.com/material-components/material-components-web/commit/a3016368df53b1c7967d7d146a9ea53a24442fa9))
* **circular-progress:** Fix naming in package.json and add to jsBundleFactory ([86f7cad](https://github.com/material-components/material-components-web/commit/86f7cad8330dbd600e478610eefd8dd92eb3d8c7))
* **circular-progress:** Force LTR layout ([6a40ef2](https://github.com/material-components/material-components-web/commit/6a40ef217f597138ee2920d2160364649dbf5620))
* **circular-progress:** Switch mixins import to `[@use](https://github.com/use)` ([098ae32](https://github.com/material-components/material-components-web/commit/098ae3285223af2532659dec233537a55c1183f5))
* **circular-progress:** use theme.property() for color mixins ([7bd5075](https://github.com/material-components/material-components-web/commit/7bd5075de978f8499f4cdc3b8359005184fa5192))
* **data-table:** Add noflip annotation to header cell text align ([843f636](https://github.com/material-components/material-components-web/commit/843f636c047b5371cd31b9ae4af76a7ec494b446))
* **data-table:** Check if data table has checkboxes on destroy ([164c073](https://github.com/material-components/material-components-web/commit/164c07365ef405a14e4375db71fbc55931aa9262))
* **data-table:** Fix icon misalignment in sort icon button when sorted down ([610c26c](https://github.com/material-components/material-components-web/commit/610c26c4a1c7928fec0e8d63be3bd76cb7ff76a0))
* **data-table:** Fix JS error in IE11 when setting multiple styles ([d548d7a](https://github.com/material-components/material-components-web/commit/d548d7a923393f4be11a7919542fa07f5a224d29))
* **data-table:** Fix pagination box height ([eb28b6e](https://github.com/material-components/material-components-web/commit/eb28b6ecc65a9979ef0959eac5dbfde5b4d3b2dc))
* **data-table:** Fix row checkbox cell's leading padding to match spec ([38ef450](https://github.com/material-components/material-components-web/commit/38ef4501f630351b32efd31ea2b870e0ed1b1b1d))
* **data-table:** Fixed default feature targeting query params of sort mixins ([e33c49e](https://github.com/material-components/material-components-web/commit/e33c49eaf9c0dbc601f3610af6358cbf2833229c))
* **data-table:** Hover styles for sortable header cell ([d580805](https://github.com/material-components/material-components-web/commit/d5808057fcdf00364731e0896ef7031ac605cf55))
* **data-table:** partial rollback of [#6390](https://github.com/material-components/material-components-web/issues/6390) ([da72839](https://github.com/material-components/material-components-web/commit/da72839f40a432c529bb24e5bc4514842627d3bf))
* **data-table:** Reverse the arrow direction icon for column sorting ([a7c827f](https://github.com/material-components/material-components-web/commit/a7c827f17ce9be631484676ccb6b5f18604803ae))
* **data-table:** Set progress indicator height to table body offset height ([c678a9d](https://github.com/material-components/material-components-web/commit/c678a9d34a3f694511f292c7a62e68749721b63c))
* **data-table:** unable to redefine colors in class-based themi… ([#5751](https://github.com/material-components/material-components-web/issues/5751)) ([4d48051](https://github.com/material-components/material-components-web/commit/4d48051c1099f48e867cf08f070138a7abc719fc))
* **data-table:** unable to redefine colors in class-based theming ([4b45b66](https://github.com/material-components/material-components-web/commit/4b45b662057edd8819f1a515db88e1c12254cc30))
* **datatable:** Fix updating the header checkbox when there are no rows in a datatable ([2ccf996](https://github.com/material-components/material-components-web/commit/2ccf996cc417b888d7ac4ceebdfa4160464a0bb1))
* **dom:** Make dom selectors in dom/announce tests scoped ([fc65fd0](https://github.com/material-components/material-components-web/commit/fc65fd00b91d388d0ad15e50a13567a8e1d425c0))
* **elevation:** Use relative path when importing theme Sass file. ([405a29a](https://github.com/material-components/material-components-web/commit/405a29a2016565f8cb269915c5f6c0d4df133c6d))
* **linear-progress:** disable animations when closed ([a831d47](https://github.com/material-components/material-components-web/commit/a831d4799b281729a932f0690b62b6bce1874799))
* **linear-progress:** performance for indeterminate animations in modern browsers ([fc0eb50](https://github.com/material-components/material-components-web/commit/fc0eb5013603a4d5cb4dbc0a999e94df64cc5005))
* **linear-progress:** Temporary rollback of [#5656](https://github.com/material-components/material-components-web/issues/5656) while updating downstream dependencies ([9cf5e98](https://github.com/material-components/material-components-web/commit/9cf5e9842475e50046462aa1c6d18e326abaee17))
* **list:** No longer emits action event when disabled item selected ([f352d03](https://github.com/material-components/material-components-web/commit/f352d03f4ed48c5019a0a3e10ef12689a5ab5619)), closes [#5571](https://github.com/material-components/material-components-web/issues/5571)
* **mdc-dialog:** second dialog `data-mdc-dialog-initial-focus` doesn't work ([a0ec7e2](https://github.com/material-components/material-components-web/commit/a0ec7e25d0ba26c2e85d5576e6af5e5d65b301a3))
* **menu-surface:** Use margin_to_edge as a viewport margin in calculations for autopositioning. ([4b04cdb](https://github.com/material-components/material-components-web/commit/4b04cdb0fc4da4831340b01292c118b120c1fcb1))
* **menusurface:** Fixing bug where body click listener is not being properly deregistered. ([5511c52](https://github.com/material-components/material-components-web/commit/5511c5254476c817b51bb2ae884f56d328348bd0)), closes [#6557](https://github.com/material-components/material-components-web/issues/6557)
* **menusurface:** synchronous quick menu does not close on button click ([45a6615](https://github.com/material-components/material-components-web/commit/45a6615e33eb8a7e6fc37e9ef43a3be3682b6b0e))
* **radio:** disabled state in IE high contrast mode ([774dcfc](https://github.com/material-components/material-components-web/commit/774dcfc8eb31e766afd0194c54edfe71a7ff7c3e))
* **segmented-button:** Fixed unit test in IE11 ([#6271](https://github.com/material-components/material-components-web/issues/6271)) ([b96fbfc](https://github.com/material-components/material-components-web/commit/b96fbfc7a9b75d7d58ecc53919c26b1cdd05d9ed))
* **segmented-button:** Move include statements to avoid nested classes ([#6380](https://github.com/material-components/material-components-web/issues/6380)) ([bcc5829](https://github.com/material-components/material-components-web/commit/bcc58290a7ac7bbbe191d00be003785017f94d29))
* **segmented-button:** Use empty clientRect in default adapter ([#6343](https://github.com/material-components/material-components-web/issues/6343)) ([9f9aac8](https://github.com/material-components/material-components-web/commit/9f9aac82595ec6eb117e101dc5e0ee0a22e81eee))
* **select:** Deduplicate change events ([4ad1274](https://github.com/material-components/material-components-web/commit/4ad12741e41c5b8e175f2bc8d5053daec6cedf18)), closes [#5570](https://github.com/material-components/material-components-web/issues/5570)
* **select:** do not emit change event when same value selected twice ([e07a708](https://github.com/material-components/material-components-web/commit/e07a7084134b6bbfb1d31a00e410b9d133f28863))
* **select:** ensure enough space for label when outlined menu opening above ([66b8ed7](https://github.com/material-components/material-components-web/commit/66b8ed7e62881b1b22b3b5a32730eac43d563cb7))
* **select:** float label on hidden-input initial value ([744bfe5](https://github.com/material-components/material-components-web/commit/744bfe5d8438b49d995ac5e2760d776a1df9838a))
* **select:** move label before selected text for screenreader a11y ([e139d62](https://github.com/material-components/material-components-web/commit/e139d626eefc941415b876597787753520a45ab1))
* **select:** prevent dropdown icon focus on IE ([b9dff0a](https://github.com/material-components/material-components-web/commit/b9dff0a19ee53e492ef9b06538dfe863214b5fc2)), closes [#6323](https://github.com/material-components/material-components-web/issues/6323)
* **select:** prevent helper text from announcing when hidden ([e056052](https://github.com/material-components/material-components-web/commit/e0560522fc2e390ee25a1968fdde3fde0cab6041))
* **select:** remove gap when outlined opened above with no label ([2fe7012](https://github.com/material-components/material-components-web/commit/2fe70126ae51043d1e733e6d4ec11452e7ed9bc4))
* **select:** remove min-width & dynamic width resizing ([d4cd83a](https://github.com/material-components/material-components-web/commit/d4cd83a857fdf072f547dc597db1f8b30d33a102))
* **select:** remove unnecessary bottom line focus selector ([32fb314](https://github.com/material-components/material-components-web/commit/32fb314cd0cc74f37f0d567a739c115daa96be95))
* **select:** revert 2fed2c1 that delegates to list for single selection logic ([38197b4](https://github.com/material-components/material-components-web/commit/38197b4434959cc8b47124233003c14d9c4a0fbf))
* **shape:** remove deprecated functions ([e2ea4a9](https://github.com/material-components/material-components-web/commit/e2ea4a99e1930ac4981f22a2b919bdbd31e75a95))
* **slider:** Fix bugs with setting slider position before component initialization: ([9110147](https://github.com/material-components/material-components-web/commit/9110147118180dc1de5c7d727fb3ecbe2507882f))
* **slider:** Move inactive track before active track, so active track consistently overlaps inactive track. ([0b7ac96](https://github.com/material-components/material-components-web/commit/0b7ac9609470218d4ed6229c7a624ed5f3984aa8))
* **slider:** Remove `width: 100%` to account for margin around slider track. ([16c563e](https://github.com/material-components/material-components-web/commit/16c563ef71555da9f02707b9f00abb4c5fc3df79))
* **snackbar:** remove use of [@at-root](https://github.com/at-root) ([98d0296](https://github.com/material-components/material-components-web/commit/98d02962b5f1edd9f541f19198dc3d1992720ea3))
* **snackbar:** Update a11y structure to announce label and actions ([40d8e47](https://github.com/material-components/material-components-web/commit/40d8e472600544fcfe8b8b9d91c62cc014995296))
* **snackbar:** Update a11y structure to announce snackbar correctly ([a3176c8](https://github.com/material-components/material-components-web/commit/a3176c8eaada1b6c61f0d678a193a26a25a773c5))
* **switch:** Adjust track width to 36px, align thumb and track. ([d716225](https://github.com/material-components/material-components-web/commit/d71622574c25840013a517749df357f7f93bc4d6))
* **switch:** always set track to transparent border ([9a169f4](https://github.com/material-components/material-components-web/commit/9a169f4b158a3148126ba38bcdfa9d163434d9bb))
* **switch:** use CSS custom properties for theming ([d6315ef](https://github.com/material-components/material-components-web/commit/d6315efe26e7baf45fd88244efbb24c612a95cb4))
* **textfield:** affix outlined alignment Safari bug ([ad4df58](https://github.com/material-components/material-components-web/commit/ad4df58c1e9ba7a893780dc5fe7886179a0361f9))
* **textfield:** autofill filled label not floating correctly ([abcdbcf](https://github.com/material-components/material-components-web/commit/abcdbcfebdcb8a8abe386abb00cd33230e8ef7a1))
* **textfield:** clean up input padding ([8639c26](https://github.com/material-components/material-components-web/commit/8639c269010b77b17f1a5052d57abcb5f7d2892a))
* **textfield:** error when notching outline with no label ([b0ed593](https://github.com/material-components/material-components-web/commit/b0ed593ccbffe7dfec51c94527cbc17000385407)), closes [#6452](https://github.com/material-components/material-components-web/issues/6452)
* **textfield:** helper text a11y interactions ([8a39352](https://github.com/material-components/material-components-web/commit/8a39352c8a787663eecb42b46939b069729fc82c))
* **textfield:** IE11 label overlapping placeholder ([781434a](https://github.com/material-components/material-components-web/commit/781434a92f4dddc9b2d39853e1f5792e89e7b45b))
* **textfield:** move notched outline/label before input ([9e2f6c4](https://github.com/material-components/material-components-web/commit/9e2f6c45016b1ccc665a271dc59134d32916123d))
* **textfield:** remove absolute positioning from icons ([1e13d1d](https://github.com/material-components/material-components-web/commit/1e13d1d5a68632f1b0b5a9134f657d59104969f4))
* **textfield:** remove Chrome icons for date types ([4951e76](https://github.com/material-components/material-components-web/commit/4951e7651ffbd99b382948e48306a23d2fd74fb1))
* **textfield:** remove deprecated dense variant in favor of density ([776291e](https://github.com/material-components/material-components-web/commit/776291ef03205e4063b4040eb66f9648e16b4af6)), closes [#4142](https://github.com/material-components/material-components-web/issues/4142)
* **textfield:** remove fullwidth variant ([69a35e8](https://github.com/material-components/material-components-web/commit/69a35e80ceadb5ef9ffae87345eefbd80b383f51))
* **theme:** add validation to host-aware to ensure proper usage ([defa599](https://github.com/material-components/material-components-web/commit/defa599a8bc17557602bbf35a8a5c760fbb053f1))
* **theme:** do not throw error when setting custom props and null ([85a5272](https://github.com/material-components/material-components-web/commit/85a5272dfeb7ad100598d480dec76b60679485f5))
* **theme:** property() mixin not working with theme key strings ([c1fec42](https://github.com/material-components/material-components-web/commit/c1fec424677fcb77dfc966ff1805d601a103fa30)), closes [#6158](https://github.com/material-components/material-components-web/issues/6158)
* server-side rendering errors in linear progress and slider ([7d0b983](https://github.com/material-components/material-components-web/commit/7d0b983a902deee6941d61906aa5a880628db4e9))
* update circular-progress import paths ([10e8c19](https://github.com/material-components/material-components-web/commit/10e8c191a0c4c9eb1703f25b66668c640f5344a6))
* **theme:** Remove duplicate [@forward](https://github.com/forward) in theme index module ([b2e80a5](https://github.com/material-components/material-components-web/commit/b2e80a5d91fc8552f22614e95f7670225f6b4248))
* **theme:** variable overrides not working with @use/with ([2d72f36](https://github.com/material-components/material-components-web/commit/2d72f365991f17e21b34be523aef3fa32b2b2fdb))
* **typography:** change $styles font-size to a Number ([6d1ea97](https://github.com/material-components/material-components-web/commit/6d1ea9761de927c1653c621444e00172f74d76c7))
* update types and deprecate old ponyfill ([af332d5](https://github.com/material-components/material-components-web/commit/af332d5bef3f826fa7a6078492d54f0444a3fee4))


### Code Refactoring

* **circular-progress:** move all sizing params from CSS to markup ([58ce529](https://github.com/material-components/material-components-web/commit/58ce529ccc29d3b172c1e774c70424eb54aac5dc))
* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([98b8434](https://github.com/material-components/material-components-web/commit/98b843417ef6c0a10460532a37df389b0c7e936f))
* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([9372e49](https://github.com/material-components/material-components-web/commit/9372e493954585c939f341486d0361efb87da806))
* **radio:** forward only theme mixins from MDC radio index module ([72258f8](https://github.com/material-components/material-components-web/commit/72258f89870242ba62c0ce25db680fdecb9640bc))
* **select:** consolidate state theming to single mixins ([e8bf5b2](https://github.com/material-components/material-components-web/commit/e8bf5b2ac6c89778fa38791979e4be941e28db1c))
* **theme:** move CSS declarations to utility mixin ([96a6405](https://github.com/material-components/material-components-web/commit/96a6405345ea1e1a7083bd08f8610384231d6607))


### Documentation

* **select:** update markup to include new selectedText container ([47b500a](https://github.com/material-components/material-components-web/commit/47b500a6cf888458b371734698b366fe2b4c3230))


### Features

* **animation:** Add a linear animation method ([c250ec5](https://github.com/material-components/material-components-web/commit/c250ec52ad1ce21943f4c7f521087bf2e647da00))
* **animation:** Create animation frame helper class ([e34e411](https://github.com/material-components/material-components-web/commit/e34e411b1835efa3f275921ca8c9d33d6df92bec))
* **banner:** Add banner component into MDC catalog ([aa3a3e5](https://github.com/material-components/material-components-web/commit/aa3a3e5a43b1e012e948c5f8f8b7c133d5ba6b0d))
* **banner:** Add fixed banner variant ([fd8af3d](https://github.com/material-components/material-components-web/commit/fd8af3d435e12d28cfc393762c325cc2d1b03f13))
* **banner:** Add fixed-width mixin. ([c61db90](https://github.com/material-components/material-components-web/commit/c61db90a5d3abb032cfa5940b0710770ba19c4a1))
* **banner:** Defining a z-index mixin. ([ccc64ee](https://github.com/material-components/material-components-web/commit/ccc64eea393339f38e54054bbd8865f9f78618bf))
* **banner:** Expose layout method. ([4794b25](https://github.com/material-components/material-components-web/commit/4794b25da9af4bfa7d48f5a6fc172efc45cfd999))
* **banner:** Update banner to be mobile friendly. ([dbc449b](https://github.com/material-components/material-components-web/commit/dbc449b0972362ba3c7fc04e26900d0c3e3d8b66))
* **banner:** Update close() to use CloseReason and provide programmatic way of closing ([ff88df6](https://github.com/material-components/material-components-web/commit/ff88df637a944de239b8860b5f0c38454cc6cc1b))
* **banner:** Update content to be leading as default and add support for optional centered. ([8d5b84f](https://github.com/material-components/material-components-web/commit/8d5b84fb260506c69fa93246aee538db89db8fc3))
* **button:** Expand outlined touch target to include side borders ([ce6cb70](https://github.com/material-components/material-components-web/commit/ce6cb7024d1da3b0e4fb5e2c67ba269dbb3098ec))
* **card:** Add transparent outline to elevated card, so card boundary is shown on high-contrast mode. ([c71ebfa](https://github.com/material-components/material-components-web/commit/c71ebfa02b7f3203317255e377b5cb165a0cfeac))
* **checkbox:** Add CSS custom properties to MDC checkbox theme mixins ([66669e3](https://github.com/material-components/material-components-web/commit/66669e3b668d0579ac71d6896240fd14d6a4322a))
* **checkbox:** Add support for checkbox CSS-only `indeterminate` checkbox ([b273afa](https://github.com/material-components/material-components-web/commit/b273afa93441e6d0375f7df33d5b69d8a7e1cfa8))
* **checkbox:** Added theme configuration support to checkbox ([58eaa9f](https://github.com/material-components/material-components-web/commit/58eaa9f027bb7ced126d3fe97cab5a0f627eb098))
* **checkbox:** Added theme configuration support to checkbox ([fbf73c2](https://github.com/material-components/material-components-web/commit/fbf73c2a6633298d6d65cdfcb8f76151e0e9c600))
* **checkbox:** Separate static styles from checkbox styles ([150f427](https://github.com/material-components/material-components-web/commit/150f427a01a7b20783d287cebe40bb4d93a24ce3))
* **checkbox:** Separate static styles from checkbox styles ([ff87000](https://github.com/material-components/material-components-web/commit/ff870005acef3cb26a6b4f378c012ffdb1061194))
* **checkbox:** Separate static styles from checkbox styles ([4f55400](https://github.com/material-components/material-components-web/commit/4f55400bbde3d85cacf379b7f7a80dd439952b3f))
* **chips:** Add chips styling ([1db5c9f](https://github.com/material-components/material-components-web/commit/1db5c9fc842292715f8b4603ce0b979066f1c639))
* **chips:** Add focus{in|out} handlers ([10af6cf](https://github.com/material-components/material-components-web/commit/10af6cf39cb2ae0a7deb9a951960f115f6ecdace))
* **chips:** Add keyCode support ([82fa986](https://github.com/material-components/material-components-web/commit/82fa986b95be4c16271df50effda1046d015d35c))
* **chips:** Add trailing action feature targeting test ([bec0659](https://github.com/material-components/material-components-web/commit/bec0659206aee793e6970d59c73f7969ab540b69))
* **chips:** Create trailing action business logic ([9ebee4c](https://github.com/material-components/material-components-web/commit/9ebee4ceb998e5fa651d4f147e5e39d43600db6e))
* **chips:** Expose trailing action chip files ([6b48781](https://github.com/material-components/material-components-web/commit/6b48781bf97d3b08b8f35b9eacde2b87748ae2e1))
* **chips:** Restructure trailing action mixins ([05f5e15](https://github.com/material-components/material-components-web/commit/05f5e1583b81bc00dbcd2ae21ee0acc43b3e13b4))
* **circular-progress:** Add foundation methods to get isDeterminate and progress value ([7d8f9c8](https://github.com/material-components/material-components-web/commit/7d8f9c8d73f16c01ed4a941ab9510377a0aae219))
* **circular-progress:** Add Sass styles and tests ([bd33cb5](https://github.com/material-components/material-components-web/commit/bd33cb56bdab7139052aeedbeec363f17b4dfc40))
* **circular-progress:** Add TS for foundation, adapter, component with tests ([548b1d4](https://github.com/material-components/material-components-web/commit/548b1d4057f21e066a4c494a57a0c068c23e18cd))
* **circular-progress:** support track color ([e27c580](https://github.com/material-components/material-components-web/commit/e27c5802fed20af29976f1f84bc39f9b59999ab5))
* **data-table:** Add base styles to support pagination. ([927fa90](https://github.com/material-components/material-components-web/commit/927fa902c3297a5a7cc9436e82cb81f3aabe1b4b))
* **data-table:** Add foundation methods to support loading state. ([e75deb8](https://github.com/material-components/material-components-web/commit/e75deb8540fa70236087d335c9cd6280bd643285))
* **data-table:** Add progress indicator / loading feature to data table ([4497ace](https://github.com/material-components/material-components-web/commit/4497acef8fd636b6ceef3cf055f664c92465e965))
* **data-table:** Add support for applying row checkbox density ([291b355](https://github.com/material-components/material-components-web/commit/291b3553d20c5dda9c5a80e0dda0705b524f41a3))
* **data-table:** Added styles for table in loading state ([35a32aa](https://github.com/material-components/material-components-web/commit/35a32aaeac17e290e2e9f9a1310c5a44a08f624a))
* **data-table:** Added styles to support column sorting. ([17b9699](https://github.com/material-components/material-components-web/commit/17b9699c4454a107043e5a1f9874a091089dd112))
* **data-table:** Added support for sticky header row in data table ([599b8c3](https://github.com/material-components/material-components-web/commit/599b8c3191a888e3debd94ad4934f741c5fb6e23))
* **data-table:** Foundation changes to support column sorting ([6ee0355](https://github.com/material-components/material-components-web/commit/6ee03557260d0a23296e36cba5aaa76fe0cf96a6))
* **data-table:** Set progress indicator styles based on table body height ([c026422](https://github.com/material-components/material-components-web/commit/c0264227393df8eb9259a2b24c23b31fe0ca84f3))
* **dom:** Add keyboard support ([5f24faa](https://github.com/material-components/material-components-web/commit/5f24faacb1ef8996ae81f3a1c1e43910ba67b024))
* **drawer:** expose --mdc-theme-surface custom prop ([319bf66](https://github.com/material-components/material-components-web/commit/319bf66dead88f67dba64f9d50a6f3f0d82aad72)), closes [#6466](https://github.com/material-components/material-components-web/issues/6466)
* **elevation:** add custom props for overlay ([4c354a3](https://github.com/material-components/material-components-web/commit/4c354a36d012e5d241f27380db1d0d9e70769c27))
* **fab:** Add focus outline mixins to MDC Fab ([0f60323](https://github.com/material-components/material-components-web/commit/0f60323a8365901c4ff6fd956161b99d8f413927))
* **fab:** Add focus outline mixins to MDC Fab ([7a9afaf](https://github.com/material-components/material-components-web/commit/7a9afaf4b503bc0d1d135b8d88edd4a7ed02e52e))
* **fab:** support css custom props for extended-padding ([01db890](https://github.com/material-components/material-components-web/commit/01db890532f796ea3e66a9c7d76893bef8689d6f))
* **form-field:** Add support for space-between ([e84b9c8](https://github.com/material-components/material-components-web/commit/e84b9c816d32da6dec058d92fc21dc5ac8fec787)), closes [#5747](https://github.com/material-components/material-components-web/issues/5747)
* **formfield:** add nowrap class/prop to MDC/MWC ([c4b4bba](https://github.com/material-components/material-components-web/commit/c4b4bba9659bf15207e79b1f63fcc9946404d9c7))
* **iconbutton:** Add icon button variant which supports toggling aria label. ([f838c6e](https://github.com/material-components/material-components-web/commit/f838c6e55672268de4e6e3b31b154d4f9050242f))
* **linear-progress:** Add foundation methods to fetch progress and determinate state. ([4dc45af](https://github.com/material-components/material-components-web/commit/4dc45af6c4bc81f5734a24c160046d283c1e9a6d))
* **list:** Add transparent-border for aria-activedescendant usage ([8388a9b](https://github.com/material-components/material-components-web/commit/8388a9bf6f4db77656adcdd604125eb205694b10))
* **menu:** Add mixin to flatten menu top when opened-below anchor ([1e17c49](https://github.com/material-components/material-components-web/commit/1e17c49b360fd0e01c9a74b92978031534003b5b))
* **menu-surface:** Add transition to height for menu resizing animation. ([1e7cb61](https://github.com/material-components/material-components-web/commit/1e7cb61989c95f9b86de3b1f6edb1773c12dfc97))
* **ripple:** Add will-change opt-out param ([e590b37](https://github.com/material-components/material-components-web/commit/e590b376bf20bde50e6f6b62339c0bac2703ccf0))
* **ripple:** Reorganize ripple opacities ([008c4d3](https://github.com/material-components/material-components-web/commit/008c4d3191f9c2a76732688504d2299420734cdd))
* **segmented-button:** add adapters and foundations ([#6165](https://github.com/material-components/material-components-web/issues/6165)) ([6ed717d](https://github.com/material-components/material-components-web/commit/6ed717dddf5f62dd5bfc621388ae07471775612f))
* **segmented-button:** Add component outlines ([#6222](https://github.com/material-components/material-components-web/issues/6222)) ([a0f1202](https://github.com/material-components/material-components-web/commit/a0f1202dc5cd67207877167558742d0b18bf0e32))
* **segmented-button:** Add initial Sass styles ([#6141](https://github.com/material-components/material-components-web/issues/6141)) ([7555383](https://github.com/material-components/material-components-web/commit/75553837cce5cb9d52d5561f5729d110e71af401))
* **segmented-button:** Add MDC segmented button into material-components-web ([596e984](https://github.com/material-components/material-components-web/commit/596e984242fdef685dae49e2c84305e55c9ea724))
* **segmented-button:** Add new package for segmented button ([#6073](https://github.com/material-components/material-components-web/issues/6073)) ([d561860](https://github.com/material-components/material-components-web/commit/d5618602a8ef45a1fdf753c3598afc5e1cadc95b))
* **segmented-button:** Add ripple and touch-target support ([#6277](https://github.com/material-components/material-components-web/issues/6277)) ([e3b7462](https://github.com/material-components/material-components-web/commit/e3b746208db04f3922fabba77986f9f02f422d75))
* **segmented-button:** Add select validations for singleSelect ([#6381](https://github.com/material-components/material-components-web/issues/6381)) ([2e8c3dd](https://github.com/material-components/material-components-web/commit/2e8c3dd2e0622957a373286f14720de36afb5ba4))
* **segmented-button:** Added foundation business logic ([#6198](https://github.com/material-components/material-components-web/issues/6198)) ([e6e2301](https://github.com/material-components/material-components-web/commit/e6e23019d567802c13d0bd6559a35291c48abc91))
* **segmented-button:** Implement components ([#6223](https://github.com/material-components/material-components-web/issues/6223)) ([ac405ea](https://github.com/material-components/material-components-web/commit/ac405eae1b80f719a80dc4fec663b763e73cdf5d))
* **select:** move selectedText into its own text node ([0bc41a9](https://github.com/material-components/material-components-web/commit/0bc41a9c75392352e8a31eb9d46f1a1457ffe732))
* **select:** support hidden input ([fda053e](https://github.com/material-components/material-components-web/commit/fda053eb848395ebfa9266e4535013e1a3be8486)), closes [#5428](https://github.com/material-components/material-components-web/issues/5428)
* **select:** truncate with ellipses by default ([83d83f1](https://github.com/material-components/material-components-web/commit/83d83f131118073943a6a45923b37b3a961bd894))
* **slider:** Add hooks into dragStart/dragEnd events to slider foundation. ([85a1fa9](https://github.com/material-components/material-components-web/commit/85a1fa9eab3010f2c41f5f65ca80a7f34bc46b2c))
* **slider:** Add M2 version of slider. ([8158544](https://github.com/material-components/material-components-web/commit/8158544774c50ba21b114f6fe24786816ba4c4fd))
* **slider:** Add support for customizing tick marks opacity, and document tick mark DOM structure for rendering tick marks before component initialization. ([238216f](https://github.com/material-components/material-components-web/commit/238216fc466a1b0dd5f4f05f10a083949e1b99d9))
* **slider:** Add support for setting `aria-valuetext` on slider thumbs. ([fd608ff](https://github.com/material-components/material-components-web/commit/fd608ff66bbb2f765fa1c092427fba9e61a074f3))
* **slider:** Add support for styling initial thumb/track before component JS initialization. ([08ca4d0](https://github.com/material-components/material-components-web/commit/08ca4d0ec5f359bc3a20bd2a302fa6b733b5e135))
* **slider:** Add support for theming disabled colors. ([d52b165](https://github.com/material-components/material-components-web/commit/d52b165b5869309705068ab58803cef426f1e590))
* **snackbar:** Update stacked layout to add an additional 8px on the label's right padding ([521afaf](https://github.com/material-components/material-components-web/commit/521afaf6e3086285b040c06fc3dbc92f20dc9b06))
* **textfield:** add autovalidation customization ([2ab716c](https://github.com/material-components/material-components-web/commit/2ab716cbda14aca5a8b62cdae3c71c2d629b16f7))
* **textfield:** add filled class variant ([b70bc60](https://github.com/material-components/material-components-web/commit/b70bc601ef570dab4598ae6f3ca51bbf884fac96))
* **textfield:** add forced LTR input ([490fbdc](https://github.com/material-components/material-components-web/commit/490fbdc092c5c59d63f83407b83b37fb524ed0e5))
* **textfield:** add prefix and suffix ([6601d24](https://github.com/material-components/material-components-web/commit/6601d24afdc3a3d0bd2a9b3fcca68c35c9415ec1)), closes [#1892](https://github.com/material-components/material-components-web/issues/1892)
* **textfield:** add specific label-floating class ([a88c8e4](https://github.com/material-components/material-components-web/commit/a88c8e4dc873ae74a3afbae0dc8635dfaa03e67b))
* **textfield:** Create float transition mixin ([ca61b65](https://github.com/material-components/material-components-web/commit/ca61b656fababdf25adaa307963d4f37e6d413ec))
* **textfield:** Limit notched outline max-width ([0ab62a6](https://github.com/material-components/material-components-web/commit/0ab62a65b17192a94102231ca63f54adc39675ae))
* **textfield:** Using touch-target-mixins to increase the touch target size on trailing icons on text fields. ([174c0be](https://github.com/material-components/material-components-web/commit/174c0becfc802e4366e4814758f28cb1ecf2c75a))
* **theme:** add calc() string replacement to property mixin ([79414bf](https://github.com/material-components/material-components-web/commit/79414bf9f93aae12bc394fd518b6cb401e5ddb26))
* **theme:** add deep-get utility ([fb5a4cd](https://github.com/material-components/material-components-web/commit/fb5a4cdeb79de0412a9e0573db1dacb28e8186f3))
* **theme:** add shadow-dom host-aware helpers ([0a2e7fc](https://github.com/material-components/material-components-web/commit/0a2e7fc8976e6481c9225609d7ff5354362472fa)), closes [#6295](https://github.com/material-components/material-components-web/issues/6295)
* **theme:** add state helper functions ([0809012](https://github.com/material-components/material-components-web/commit/08090126b4eff43f82188ee1dae5c8deda33d2ef))
* **tooltip:** Add 500ms delay before showing tooltip. ([a1c6559](https://github.com/material-components/material-components-web/commit/a1c65593d3c1f594a35561569357bb657dd50408))
* **tooltip:** add position options for y-axis ([91ab1c6](https://github.com/material-components/material-components-web/commit/91ab1c62a4e00ae844d444882582d2052aaf228a))
* **tooltip:** Add tooltip component into MDC catalog. ([b9394dc](https://github.com/material-components/material-components-web/commit/b9394dc5da7db3b60497cf81aa5f26a5758d9b37))
* **tooltip:** Adding option to render tooltips as hidden from a screenreader. This should only be utilized in situations where the tooltip label hold information duplicated from an accessible name on the anchor element (e.g. tooltip label is the same as the aria-label on an icon button) ([546277d](https://github.com/material-components/material-components-web/commit/546277d323c484ddf181afffed153f4f17c9f4a7))
* **tooltip:** Adding transparent border around tooltip so it is distinguished from the background in high contrast mode. ([02e372c](https://github.com/material-components/material-components-web/commit/02e372c5f02afaf66e06e733a08c6c704c16843c))
* **tooltip:** Adjusting tooltip z-index so tooltip appears above other content on the page. ([c285200](https://github.com/material-components/material-components-web/commit/c2852000d97ed49c5f8ab82b5911deb1c87a9025))
* **tooltip:** Adjustments to tooltip structure. ([19bea2a](https://github.com/material-components/material-components-web/commit/19bea2ad3d6c6aa36e0d033af7adebd010dcd4fa))
* **tooltip:** Center align tooltip label text. ([5dac1f6](https://github.com/material-components/material-components-web/commit/5dac1f624606fc92682a4266ffd68bea21e57069))
* **tooltip:** Creating method to clear any in-progress animations before starting new ones. ([61f1a8d](https://github.com/material-components/material-components-web/commit/61f1a8d8599f6dfaa7fc6c64d661010df47839b7))
* **tooltip:** Defining a z-index mixin. ([f4848eb](https://github.com/material-components/material-components-web/commit/f4848eb3b57d81fd4fed1396cdc22a83344ccd72))
* **tooltip:** Foundation will now send a notification when the tooltip has been hidden. Methods added into the adapter to allow for this functionality. ([9274f85](https://github.com/material-components/material-components-web/commit/9274f8504a905e04f24fba8f6a0e246d7ae3a638))
* **typography:** add container baseline mixins for flexbox ([69edc6e](https://github.com/material-components/material-components-web/commit/69edc6e2899636cfccb117376bb64dc0a267c588))
* add custom property support for select, textfield, and notched outline ([ec23858](https://github.com/material-components/material-components-web/commit/ec2385881f93b75641db661038aae439b4c217d1))


### Reverts

* "Include tooltip directory for future copybara syncs." ([#6185](https://github.com/material-components/material-components-web/issues/6185)) ([b0c456d](https://github.com/material-components/material-components-web/commit/b0c456d330f31bc890c54d114de1d56ac23fee9f))
* feat(checkbox): Added theme configuration support to checkbox ([cf80012](https://github.com/material-components/material-components-web/commit/cf800124fdaeea04b3fd45f8718a2980dd01a0df))


### BREAKING CHANGES

* **banner:** Added wrapper div to text/graphic for mobile friendly view, see README.md for more info.
* **typography:** `typography.baseline-top()` and `typography.baseline-bottom()` are now private. Use `typography.baseline()` for containers and `typography.text-baseline()` for text with $top and $bottom params.
* **banner:** Dom structure change, see README.md
* **select:** selected text node now needs to be wrapped in an outer `mdc-select__selected-text-container` span; see README for updated markup
* **datatable:** Header checkboxes will now be unchecked if layout is called when there are no rows.
* **banner:** Updated adapter to use CloseReason types
* **checkbox:** Renamed mixin `ripple()` => `ripple-styles()` in MDC checkbox
* **checkbox:** Renamed mixin `ripple()` => `ripple-styles()` in MDC checkbox
* **checkbox:** Renamed mixin `ripple()` => `ripple-styles()` in MDC checkbox
* **theme:** $ie-fallback variable has been moved and renamed to $enable-fallback-declarations in `@material/theme/css`
* **select:** select theming mixins which were previously "stateful" (e.g. `hover-label-color()`) are combined into the non-stateful mixin (e.g. `label-color()`). The default state of the mixin can be set as normal, or a Map of states can be provided to optionally set one or more states of the mixin (e.g. `label-color((hover: blue))`). See the `@material/theme/state` package for more details.
* **textfield:** adapter method `getAttr` added on helper text subcomponent; adapter method `setInputAttr` and `removeInputAttr` added on main component
* **textfield:** the notched outline and label should now appear before the input in the text field's DOM structure for a11y navigation
* **slider:** This upgrades the old slider to a new version of slider that adheres to the M2 design spec. Changes include:
- M2 design (primary instead of secondary color used, larger active track and thumb, improved tick marks UI)
- Range (two-thumb slider) slider
- Pointer events support (for browsers that support pointer events)
- High contrast mode support
- Improved accessibility (follows WAI-ARIA spec for slider)
* **circular-progress:** DOM Changed. See README for updated markup. `$default-size`, `$stroke-width`, and `$container-side-length` variables removed.
* **snackbar:** The right padding of the label for the `mdc-snackbar--stacked` variant will now have an additional 8px
* **data-table:** New adapter method replacing `getTableBodyHeight()` => `getTableHeaderHeight()` and changed return types of this method.
* **textfield:** Default textfields must now specify mdc-text-field--filled. Disabled outlined textfields no longer have a shaded background. Height mixin no longer specifies a baseline override, use typography's baseline-top mixin.
* **textfield:** mdc-text-field--dense and associated mixins/variables have been removed. Use the density() mixin instead.
* **textfield:** removed the following variables: `$input-padding`, `$input-padding-top`, `$input-padding-bottom`, `$outlined-input-padding-top`, `$outlined-input-padding-bottom`, `$input-border-bottom`
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.
* **radio:** MDC radio _index Sass module will only export theme mixins


# [7.0.0](https://github.com/material-components/material-components-web/compare/v6.0.0...v7.0.0) (2020-06-23)


### Bug Fixes

* **base:** Add EDITING and EDITABLE states to the chip. ([cf3b664](https://github.com/material-components/material-components-web/commit/cf3b664ab1f12b17ea827ad1e2870977b9836e5b))
* **base:** Causes internal text in a chip to not overflow and instead be truncated by ellipsis. ([b83d720](https://github.com/material-components/material-components-web/commit/b83d720ee41acb13e3e6ca69431f718c7887c1de))
* **base:** Make the root property public ([51d4535](https://github.com/material-components/material-components-web/commit/51d4535fe39a2448fbba1ec995bb9980357545fa))
* **base:** Remove "foundation_" from MDCComponent ([8c6d7e0](https://github.com/material-components/material-components-web/commit/8c6d7e0766d8958a8d4ffea35acee9d6841dafd4))
* **base:** Remove trailing underscore "adapter_" ([5b5f62f](https://github.com/material-components/material-components-web/commit/5b5f62f9397100a9dd97c257b930e686837c4ceb))
* **base:** Remove trailing underscore from superclass properties ([62b5f37](https://github.com/material-components/material-components-web/commit/62b5f37db092df4441abdf5e4ee0b32dceee8c7c))
* **button:** Correct misspelling of overflow ([29debfe](https://github.com/material-components/material-components-web/commit/29debfea704941e80f1d337880b4a18142c11561))
* **button:** Correct misspelling of overflow ([99d2fc9](https://github.com/material-components/material-components-web/commit/99d2fc961be8cd7e8316b40dcf9754a536d29991))
* **button:** Correct misspelling of overflow ([28d32f8](https://github.com/material-components/material-components-web/commit/28d32f8e0d923099221fe7d3853177243e0fd243))
* **button:** Move theme-baseline() into base Sass. ([080965f](https://github.com/material-components/material-components-web/commit/080965f3952b32105419558c0167873554234dd0))
* **button:** Remove misspelled label-overlow-ellipsis ([e59906a](https://github.com/material-components/material-components-web/commit/e59906a57e91604f918c8ccd350f93a9a802e412))
* **checkbox:** Use secondary and on-secondary as default colors ([b95172e](https://github.com/material-components/material-components-web/commit/b95172e69613c0defe82191b86ed1c1999b74400)), closes [#5730](https://github.com/material-components/material-components-web/issues/5730)
* **checkbox:** Use superclass properties without trailing underscores ([2e218db](https://github.com/material-components/material-components-web/commit/2e218dbf8810548de27b683ed6e25d5fb1cbbc23))
* **chips:** Handle IE/Edge specific key names in keyboard navigation logic ([3657f88](https://github.com/material-components/material-components-web/commit/3657f886327182c26f1d1555b2ac67c2128140b5))
* **chips:** Use superclass properties without trailing underscores ([cf7747e](https://github.com/material-components/material-components-web/commit/cf7747ef72efb4affe2dd920a6641f730f3bcfcd))
* **circular-progress:** Add .npmignore file to ignore typescript files when publishing ([#5801](https://github.com/material-components/material-components-web/issues/5801)) ([f172b0f](https://github.com/material-components/material-components-web/commit/f172b0f90a91d8d3d700763d1496bb7b9c1a8d51)), closes [#5800](https://github.com/material-components/material-components-web/issues/5800)
* **circular-progress:** fix determinate transition typo & 4 color keyframes ([a301636](https://github.com/material-components/material-components-web/commit/a3016368df53b1c7967d7d146a9ea53a24442fa9))
* **circular-progress:** Fix naming in package.json and add to jsBundleFactory ([86f7cad](https://github.com/material-components/material-components-web/commit/86f7cad8330dbd600e478610eefd8dd92eb3d8c7))
* **circular-progress:** Force LTR layout ([6a40ef2](https://github.com/material-components/material-components-web/commit/6a40ef217f597138ee2920d2160364649dbf5620))
* **circular-progress:** Switch mixins import to `[@use](https://github.com/use)` ([098ae32](https://github.com/material-components/material-components-web/commit/098ae3285223af2532659dec233537a55c1183f5))
* **circularprogress:** Use superclass properties without trailing underscores ([da05f66](https://github.com/material-components/material-components-web/commit/da05f66e10f8efe5c425cec7f140ed399b11bd3f))
* **data-table:** Fix pagination box height ([eb28b6e](https://github.com/material-components/material-components-web/commit/eb28b6ecc65a9979ef0959eac5dbfde5b4d3b2dc))
* **data-table:** Fixed alignment of numeric header cell with sort button. ([2139200](https://github.com/material-components/material-components-web/commit/2139200b3ed2b57d74a02701bfef23a983d19cdf))
* **data-table:** Fixed default feature targeting query params of sort mixins ([e33c49e](https://github.com/material-components/material-components-web/commit/e33c49eaf9c0dbc601f3610af6358cbf2833229c))
* **data-table:** Fixed horizontal scrolling issue with pagination controls ([b065a4d](https://github.com/material-components/material-components-web/commit/b065a4d2bd351b86277f5a2f4d512fb6c243c7ce))
* **data-table:** Hover styles for sortable header cell ([d580805](https://github.com/material-components/material-components-web/commit/d5808057fcdf00364731e0896ef7031ac605cf55))
* **data-table:** Make row checkbox table cell fixed even when table is wide ([a6ac8f6](https://github.com/material-components/material-components-web/commit/a6ac8f629b45e46d598b4b531fed8300fb5a8eef))
* **data-table:** not inverting text alignment in rtl ([bd8d1aa](https://github.com/material-components/material-components-web/commit/bd8d1aafab5c6da614135702f5814447de5ea448))
* **data-table:** Removed overflow-x from root element ([4ebce8d](https://github.com/material-components/material-components-web/commit/4ebce8d787db92afb4c1f9d2a10268a62d188d43))
* **data-table:** Reverse the arrow direction icon for column sorting ([a7c827f](https://github.com/material-components/material-components-web/commit/a7c827f17ce9be631484676ccb6b5f18604803ae))
* **data-table:** unable to redefine colors in class-based themi… ([#5751](https://github.com/material-components/material-components-web/issues/5751)) ([4d48051](https://github.com/material-components/material-components-web/commit/4d48051c1099f48e867cf08f070138a7abc719fc))
* **data-table:** unable to redefine colors in class-based theming ([4b45b66](https://github.com/material-components/material-components-web/commit/4b45b662057edd8819f1a515db88e1c12254cc30))
* **datatable:** Use superclass properties without trailing underscores ([862d0d7](https://github.com/material-components/material-components-web/commit/862d0d7bce4fc30a1947d1ff7cb7286c106dd9e5))
* **dialog:** Change scale(1) to `transform:none` ([9ea5207](https://github.com/material-components/material-components-web/commit/9ea52070f4f9693266a20311cce15700e84696c3))
* **dialog:** Only equalize paddings for scrollable dialogs with titles, since there is no added divider between title/content in this case. ([8135cc0](https://github.com/material-components/material-components-web/commit/8135cc085a5cd548cf8c8fba4bb43a21bcd3fd46))
* **dialog:** Use superclass properties without trailing underscores ([b4e2fe9](https://github.com/material-components/material-components-web/commit/b4e2fe9f4bf690968d0ac47da0ca4a64ee8d7a88))
* **dom:** Clear out announcer regions on document click ([c67667e](https://github.com/material-components/material-components-web/commit/c67667e8e213ed4686889cb3962685444bd885c6))
* **drawer:** Use superclass properties without trailing underscores ([a66493c](https://github.com/material-components/material-components-web/commit/a66493cd8e9717ce32218fb877ca2258ea6ee880))
* **floating-label:** Use superclass properties without trailing underscores ([5cea261](https://github.com/material-components/material-components-web/commit/5cea2610f2f46bbe193683668044116d78b7e2d6))
* **form-field:** Use superclass properties without trailing underscores ([7fd792b](https://github.com/material-components/material-components-web/commit/7fd792bb9841501ecbc35b4024a00e07216fb95b))
* **icon-button:** Use superclass properties without trailing underscores ([740860e](https://github.com/material-components/material-components-web/commit/740860e789992163537cc7138d6c21672adb79d0))
* **line-ripple:** Use superclass properties without trailing underscores ([a4aae3d](https://github.com/material-components/material-components-web/commit/a4aae3d3710ba5eb86f27dee230064dfccf2e73f))
* **linear-progress:** Temporary rollback of [#5656](https://github.com/material-components/material-components-web/issues/5656) while updating downstream dependencies ([9cf5e98](https://github.com/material-components/material-components-web/commit/9cf5e9842475e50046462aa1c6d18e326abaee17))
* **linear-progress:** Use superclass properties without trailing underscores ([8e17857](https://github.com/material-components/material-components-web/commit/8e17857d0a8d301f54fac64cc83804928ec1ff83))
* **list:** No longer emits action event when disabled item selected ([f352d03](https://github.com/material-components/material-components-web/commit/f352d03f4ed48c5019a0a3e10ef12689a5ab5619)), closes [#5571](https://github.com/material-components/material-components-web/issues/5571)
* **list:** Preserve aspect ratio of the original image when using it as the icon or avatar for a list. ([be4a19f](https://github.com/material-components/material-components-web/commit/be4a19f9f0668e4fc303d2e60e81473ac11d68be))
* **list:** Remove obsolete non-interactive class & :not selectors ([2553e86](https://github.com/material-components/material-components-web/commit/2553e86fee2753ec59f1fbc91764bf110ad9d3aa))
* **list:** Use superclass properties without trailing underscores ([4847dd7](https://github.com/material-components/material-components-web/commit/4847dd7645adf463ea947fc2afb346df648a1ffc))
* **menu:** Do not set selectedIndex for menu items that have a negative recomputedIndex. ([ef3a095](https://github.com/material-components/material-components-web/commit/ef3a095336a205fa9473a8c6e4940c3f9cccf5ea))
* **menu:** Use superclass properties without trailing underscores ([0008c8a](https://github.com/material-components/material-components-web/commit/0008c8a91a4da2c0c95fe092395cc575cbf23769))
* **menu-surface:** Use margin_to_edge as a viewport margin in calculations for autopositioning. ([4b04cdb](https://github.com/material-components/material-components-web/commit/4b04cdb0fc4da4831340b01292c118b120c1fcb1))
* **menu-surface:** Use superclass properties without trailing underscores ([62abbc8](https://github.com/material-components/material-components-web/commit/62abbc8d762c6c903d4a13817a0b71555764e0df))
* **menusurface:** open and closed events not fired when already opened or closed ([9cff431](https://github.com/material-components/material-components-web/commit/9cff4318f0fe8a79f8787afd148907328a5223d5))
* **menusurface:** synchronous quick menu does not close on button click ([45a6615](https://github.com/material-components/material-components-web/commit/45a6615e33eb8a7e6fc37e9ef43a3be3682b6b0e))
* **notched-outline:** Use superclass properties without trailing underscores ([49bf31d](https://github.com/material-components/material-components-web/commit/49bf31d5c9c3ee34e9a51ce3b254a9101c578045))
* **radio:** Use superclass properties without trailing underscores ([541638f](https://github.com/material-components/material-components-web/commit/541638fa2ba3410ca1055c5ae563face06fd20be))
* **ripple:** Use superclass properties without trailing underscores ([6167cd0](https://github.com/material-components/material-components-web/commit/6167cd0756a623502f7f84750dcda25226a59794))
* **select:** Also set font size for icon ([c113fc9](https://github.com/material-components/material-components-web/commit/c113fc942a88e2c53b2c36229b2ddff84e6d0eb5))
* **select:** clean up helper text interactions ([654934d](https://github.com/material-components/material-components-web/commit/654934dfaff71dae2b56bd2d4bb04303f5439c3e))
* **select:** Close menu on anchor click when menu is open ([8fa22aa](https://github.com/material-components/material-components-web/commit/8fa22aaccafa3b1ae09164b228d8e1b203337221))
* **select:** Deduplicate change events ([4ad1274](https://github.com/material-components/material-components-web/commit/4ad12741e41c5b8e175f2bc8d5053daec6cedf18)), closes [#5570](https://github.com/material-components/material-components-web/issues/5570)
* **select:** Fix redundant calculations & allow resyncing foundation to options ([ff4bc63](https://github.com/material-components/material-components-web/commit/ff4bc632aeeefb8eca16d774db01f8f176479659)), closes [#5646](https://github.com/material-components/material-components-web/issues/5646) [#5646](https://github.com/material-components/material-components-web/issues/5646) [#5686](https://github.com/material-components/material-components-web/issues/5686) [#5783](https://github.com/material-components/material-components-web/issues/5783)
* **select:** fix screenreader click interactions ([8904f3c](https://github.com/material-components/material-components-web/commit/8904f3cbe922c5b64f5b7297f23c49861ee13f07))
* **select:** fully separate density mixins for filled variants ([d66d22b](https://github.com/material-components/material-components-web/commit/d66d22bf9b9f221ff8b2d713b1e2fc9288f490df))
* **select:** Make compatible with rich list-items ([0a7895f](https://github.com/material-components/material-components-web/commit/0a7895f4d4c22296ad23b2d8a7e1a4dbe231b941))
* **select:** Remove pointer events where unnecessary ([0e052b2](https://github.com/material-components/material-components-web/commit/0e052b24f415b81fbffb45182030dd8b9d68ee98))
* **select:** Set aria-selected="false" properly ([730920f](https://github.com/material-components/material-components-web/commit/730920fbba046b0a7c3821f52877504a78373f1f))
* **select:** Update disabled state ([f83e008](https://github.com/material-components/material-components-web/commit/f83e00898fb57e49e38ef59b3458df4525332302))
* **select:** Update dropdown arrow icon transitions ([15d6544](https://github.com/material-components/material-components-web/commit/15d65448e5dd8a29477b34754264644ad88f8421))
* **select:** Update markup in tests and README ([e3eacef](https://github.com/material-components/material-components-web/commit/e3eacefcc0ca3ca89af34b3e4d3dc13c5a27570b))
* **select:** Use key constants from DOM package ([388b042](https://github.com/material-components/material-components-web/commit/388b042c7193f78874a8854664742fc7285f1386))
* **select:** Use superclass properties without trailing underscores ([c472bbb](https://github.com/material-components/material-components-web/commit/c472bbbd1aa5e362c227a1c5204601362444d22f))
* **slider:** avoid server side rendering error ([95c7355](https://github.com/material-components/material-components-web/commit/95c73550e886c2832aa42cd065552551b6690a61))
* **slider:** mobile sliding regression ([e844443](https://github.com/material-components/material-components-web/commit/e844443878b9711a306e72b951c7ea931b17d837)), closes [#5894](https://github.com/material-components/material-components-web/issues/5894)
* **slider:** two change events fired on each up ([d10412c](https://github.com/material-components/material-components-web/commit/d10412cb24150639acc617caef1c7fac4fb6e4bd))
* **snackbar:** Use superclass properties without trailing underscores ([39b0b8e](https://github.com/material-components/material-components-web/commit/39b0b8e06ef68d5b59515454907b5472ce75b842))
* **snackbar:** Use superclass properties without trailing underscores ([5ea0f3f](https://github.com/material-components/material-components-web/commit/5ea0f3fc47e8bd18fcc8fd3af84fcecc17b3f800))
* **switch:** always set track to transparent border ([9a169f4](https://github.com/material-components/material-components-web/commit/9a169f4b158a3148126ba38bcdfa9d163434d9bb))
* **switch:** use CSS custom properties for theming ([d6315ef](https://github.com/material-components/material-components-web/commit/d6315efe26e7baf45fd88244efbb24c612a95cb4))
* **tab:** Use superclass properties without trailing underscores ([a4b2e61](https://github.com/material-components/material-components-web/commit/a4b2e61d47b515a0ebbdee788e8462d800bea7f3))
* **tab-bar:** Use superclass properties without trailing underscores ([f2de07c](https://github.com/material-components/material-components-web/commit/f2de07c606c8d57942d5f0022e90eecb41b3ad61))
* **tab-indicator:** Use superclass properties without trailing underscores ([d30a214](https://github.com/material-components/material-components-web/commit/d30a214ace1c0ae41fd5d7f8ba4915035fd9235a))
* **tab-scroller:** Use superclass properties without trailing underscores ([96dba1d](https://github.com/material-components/material-components-web/commit/96dba1d3127c9364cff5786a01be8c17f69ab0ee))
* **text-field:** Use superclass properties without trailing underscores ([e6165eb](https://github.com/material-components/material-components-web/commit/e6165eb156d60f8f650c68931854136a1a44fc6e))
* **textfield:** clean up input padding ([8639c26](https://github.com/material-components/material-components-web/commit/8639c269010b77b17f1a5052d57abcb5f7d2892a))
* **textfield:** core-styles now applies sub-element core-styles ([bcdad99](https://github.com/material-components/material-components-web/commit/bcdad99bbf9ac4d2bbc09cf6378c0c040521e514)), closes [#5927](https://github.com/material-components/material-components-web/issues/5927)
* **textfield:** IE11 label overlapping placeholder ([781434a](https://github.com/material-components/material-components-web/commit/781434a92f4dddc9b2d39853e1f5792e89e7b45b))
* fix show/hide clauses in import-only files ([148e448](https://github.com/material-components/material-components-web/commit/148e448de1290e3628fac6eae19609c8e1bffda3))
* **textfield:** remove absolute positioning from icons ([1e13d1d](https://github.com/material-components/material-components-web/commit/1e13d1d5a68632f1b0b5a9134f657d59104969f4))
* mark all packages as side-effect-free ([be7cb05](https://github.com/material-components/material-components-web/commit/be7cb05996a7281d1e0c12c0f4677e4d091a2329))
* server-side rendering errors in linear progress and slider ([7d0b983](https://github.com/material-components/material-components-web/commit/7d0b983a902deee6941d61906aa5a880628db4e9))
* **textfield:** remove deprecated dense variant in favor of density ([776291e](https://github.com/material-components/material-components-web/commit/776291ef03205e4063b4040eb66f9648e16b4af6)), closes [#4142](https://github.com/material-components/material-components-web/issues/4142)
* **textfield:** textarea density label position is now correct ([2f8a227](https://github.com/material-components/material-components-web/commit/2f8a227a289a56702fec6592a87cf8bab422326a))
* **textfield:** textarea min-width not set correctly for Chrome ([0a371b4](https://github.com/material-components/material-components-web/commit/0a371b4fe4ca4452618a867aac1731c6d3136b91))
* **textfield:** update outlined textarea specs ([524b7b8](https://github.com/material-components/material-components-web/commit/524b7b8127e74bc3d551bd3b81e951fc51682665))
* **top-app-bar:** Use superclass properties without trailing underscores ([863ac1b](https://github.com/material-components/material-components-web/commit/863ac1b0f1723883565ca813d56bba0a1c8a832f))


### Code Refactoring

* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([98b8434](https://github.com/material-components/material-components-web/commit/98b843417ef6c0a10460532a37df389b0c7e936f))
* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([9372e49](https://github.com/material-components/material-components-web/commit/9372e493954585c939f341486d0361efb87da806))
* **select:** Fix alignment issues, upgrade anchor to interactive element ([28d10a9](https://github.com/material-components/material-components-web/commit/28d10a96e1d5e5762d5a056ac805070e9fb6a4e1)), closes [#5428](https://github.com/material-components/material-components-web/issues/5428)


### Features

* **button:** Add button ripple-states mixin, for simpler customization of button ripple color. ([ed7f324](https://github.com/material-components/material-components-web/commit/ed7f324636287e95e8d966866a7c72af94377cf6))
* **button:** Expand outlined touch target to include side borders ([ce6cb70](https://github.com/material-components/material-components-web/commit/ce6cb7024d1da3b0e4fb5e2c67ba269dbb3098ec))
* **checkbox:** Add support for checkbox CSS-only `indeterminate` checkbox ([b273afa](https://github.com/material-components/material-components-web/commit/b273afa93441e6d0375f7df33d5b69d8a7e1cfa8))
* **chips:** Add chips styling ([1db5c9f](https://github.com/material-components/material-components-web/commit/1db5c9fc842292715f8b4603ce0b979066f1c639))
* **chips:** Add configurable primary action focus ([deb212d](https://github.com/material-components/material-components-web/commit/deb212de41e1073f7ff00af92e5f37bad0d8c4b0))
* **chips:** Add focus{in|out} handlers ([10af6cf](https://github.com/material-components/material-components-web/commit/10af6cf39cb2ae0a7deb9a951960f115f6ecdace))
* **chips:** Add keyCode support ([82fa986](https://github.com/material-components/material-components-web/commit/82fa986b95be4c16271df50effda1046d015d35c))
* **chips:** Add trailing action feature targeting test ([bec0659](https://github.com/material-components/material-components-web/commit/bec0659206aee793e6970d59c73f7969ab540b69))
* **chips:** Create trailing action business logic ([9ebee4c](https://github.com/material-components/material-components-web/commit/9ebee4ceb998e5fa651d4f147e5e39d43600db6e))
* **chips:** Expose trailing action chip files ([6b48781](https://github.com/material-components/material-components-web/commit/6b48781bf97d3b08b8f35b9eacde2b87748ae2e1))
* **chips:** Reposition trailing action touch target width mixin ([3846ce3](https://github.com/material-components/material-components-web/commit/3846ce311f65156f24dbd229100e660f1285bf5f))
* **chips:** Restructure trailing action mixins ([05f5e15](https://github.com/material-components/material-components-web/commit/05f5e1583b81bc00dbcd2ae21ee0acc43b3e13b4))
* **chips:** Use trailing action component in chip ([058cfd2](https://github.com/material-components/material-components-web/commit/058cfd23caa5c00f29c90f3d2fc9b813581ba974))
* **circular-progress:** Add foundation methods to get isDeterminate and progress value ([7d8f9c8](https://github.com/material-components/material-components-web/commit/7d8f9c8d73f16c01ed4a941ab9510377a0aae219))
* **circular-progress:** Add Sass styles and tests ([bd33cb5](https://github.com/material-components/material-components-web/commit/bd33cb56bdab7139052aeedbeec363f17b4dfc40))
* **circular-progress:** Add TS for foundation, adapter, component with tests ([548b1d4](https://github.com/material-components/material-components-web/commit/548b1d4057f21e066a4c494a57a0c068c23e18cd))
* **data-table:** Add base styles to support pagination. ([927fa90](https://github.com/material-components/material-components-web/commit/927fa902c3297a5a7cc9436e82cb81f3aabe1b4b))
* **data-table:** Add foundation methods to support loading state. ([e75deb8](https://github.com/material-components/material-components-web/commit/e75deb8540fa70236087d335c9cd6280bd643285))
* **data-table:** Added sort status label to sortable column header ([9833dc2](https://github.com/material-components/material-components-web/commit/9833dc28775a02fa4c7c490ae5df1ed198bbb398))
* **data-table:** Added styles for table in loading state ([35a32aa](https://github.com/material-components/material-components-web/commit/35a32aaeac17e290e2e9f9a1310c5a44a08f624a))
* **data-table:** Added styles to support column sorting. ([17b9699](https://github.com/material-components/material-components-web/commit/17b9699c4454a107043e5a1f9874a091089dd112))
* **data-table:** Added styles to support rows per page select menu in pagination ([3ee488f](https://github.com/material-components/material-components-web/commit/3ee488f1c0f65972459f2dbc74b6c3365786df4b))
* **data-table:** Added support for column sorting feature in data table ([06ef147](https://github.com/material-components/material-components-web/commit/06ef147b593d134fcd03f48fc3581d8fd6068865))
* **data-table:** Added support for row header cell and other a11y improvements. ([27533c1](https://github.com/material-components/material-components-web/commit/27533c19e9c72c5a27a33aaa764c1b6a05175cf5))
* **data-table:** Foundation changes to support column sorting ([6ee0355](https://github.com/material-components/material-components-web/commit/6ee03557260d0a23296e36cba5aaa76fe0cf96a6))
* **data-table:** Make rows per page wrap in new line when overflows ([09abc92](https://github.com/material-components/material-components-web/commit/09abc92198d1628c57eee5e75c58da52b223c322))
* **data-table:** Set progress indicator styles based on table body height ([c026422](https://github.com/material-components/material-components-web/commit/c0264227393df8eb9259a2b24c23b31fe0ca84f3))
* **dialog:** Add padding mixin ([ad0c0c1](https://github.com/material-components/material-components-web/commit/ad0c0c1034d0b9257a62d3dd9f5d27aada99f1f7))
* **dom:** Add keyboard support ([5f24faa](https://github.com/material-components/material-components-web/commit/5f24faacb1ef8996ae81f3a1c1e43910ba67b024))
* **drawer:** allow custom properties in width() ([39e6f71](https://github.com/material-components/material-components-web/commit/39e6f71e2e03b75512242d7520678c32c5af2b70))
* **fab:** Add outline in high-contrast mode ([deda86d](https://github.com/material-components/material-components-web/commit/deda86d8cc4665b334c4d21c541a4a30244fee72))
* **floating-label:** add required modifier class ([047e6b3](https://github.com/material-components/material-components-web/commit/047e6b337899a57290283cb0387f33738853cbc2))
* **form-field:** Add support for space-between ([e84b9c8](https://github.com/material-components/material-components-web/commit/e84b9c816d32da6dec058d92fc21dc5ac8fec787)), closes [#5747](https://github.com/material-components/material-components-web/issues/5747)
* **formfield:** add nowrap class/prop to MDC/MWC ([c4b4bba](https://github.com/material-components/material-components-web/commit/c4b4bba9659bf15207e79b1f63fcc9946404d9c7))
* **formfield:** Remove trailing underscores from private properties ([2f052d8](https://github.com/material-components/material-components-web/commit/2f052d82433a852d65785b1054ce4665ad1f6265))
* **iconbutton:** Add icon button variant which supports toggling aria label. ([f838c6e](https://github.com/material-components/material-components-web/commit/f838c6e55672268de4e6e3b31b154d4f9050242f))
* **iconbutton:** Remove trailing underscores from private properties ([119e214](https://github.com/material-components/material-components-web/commit/119e21426d73305fe348798cb7ce88077995fdd0))
* **linear-progress:** Add foundation methods to fetch progress and determinate state. ([4dc45af](https://github.com/material-components/material-components-web/commit/4dc45af6c4bc81f5734a24c160046d283c1e9a6d))
* **linearprogress:** Remove trailing underscores from private properties ([893eb18](https://github.com/material-components/material-components-web/commit/893eb1876220e5313f9db37365049b8c2282109c))
* **list:** add focus indicator in hi-contrast mode ([8602f1b](https://github.com/material-components/material-components-web/commit/8602f1b4da404816513733a21973ec9cbc9acfa3))
* **list:** Add mixin for selected item's text color ([bd8ca96](https://github.com/material-components/material-components-web/commit/bd8ca96788c9cb793288b6aa5c406b220be0bd9c))
* **menu:** Add mixin to flatten menu top when opened-below anchor ([1e17c49](https://github.com/material-components/material-components-web/commit/1e17c49b360fd0e01c9a74b92978031534003b5b))
* **menu-surface:** Add support for flipping menu corner horizontally. ([7b44824](https://github.com/material-components/material-components-web/commit/7b448240263b45c6b474c2f758cd1c02f3c708ad))
* **ripple:** Reorganize ripple opacities ([008c4d3](https://github.com/material-components/material-components-web/commit/008c4d3191f9c2a76732688504d2299420734cdd))
* **rtl:** allow values to be theme keys and custom props ([afb1c11](https://github.com/material-components/material-components-web/commit/afb1c11a9e9048ba7c2ed30e32e892ae483dfccc))
* **select:** Add menu invalid class ([4ba3c9a](https://github.com/material-components/material-components-web/commit/4ba3c9a319dad4101f4d24607a79c01390330acd))
* **select:** Add mixin for min-width ([09f5919](https://github.com/material-components/material-components-web/commit/09f591967a42e4dc27c0f7022d9ae71e94c07c3d))
* **select:** Add openMenu foundation method ([9b0b5f2](https://github.com/material-components/material-components-web/commit/9b0b5f2e034a7f8ab0e68e3afbd7c246447f53e7))
* **select:** Add styles for high-contrast mode in IE ([05cc5c2](https://github.com/material-components/material-components-web/commit/05cc5c20651eed3e40960074db919f0d030c46fb))
* **select:** Auto-align width of menu to select by default ([1b3dd84](https://github.com/material-components/material-components-web/commit/1b3dd846db4da7dcb1baaf2003e35e462cb799b7))
* **select:** Change root to inline-block & add fullwidth flag ([2673adb](https://github.com/material-components/material-components-web/commit/2673adb74397d55c9dcd8e5fd86b3efc87a13a28))
* **select:** changing density also also changes menu's list density ([68a2af1](https://github.com/material-components/material-components-web/commit/68a2af131b82e9b50e70754a2d653d6305dac4b9))
* **select:** Create additional state mixins ([744d751](https://github.com/material-components/material-components-web/commit/744d751a0c0f154d5d0d05def88203b68c3a26a5))
* **select:** extend typeahead to work when menu closed but select focused ([a0dc2b5](https://github.com/material-components/material-components-web/commit/a0dc2b5c4afbf3fd8274c752d43aeeeb11231e5f))
* **select:** flatten menu top when opened below ([912d902](https://github.com/material-components/material-components-web/commit/912d9021dab7712e0ab711fcaffb3933a960c171))
* **select:** gracefully display long labels ([21c4e4e](https://github.com/material-components/material-components-web/commit/21c4e4ed866944c090ae3d6dffe9f5e4725b7ffc))
* **select:** Implement density ([610c68d](https://github.com/material-components/material-components-web/commit/610c68d97646f523eaff0bb26c08baa5903e9211))
* **select:** introduce custom validity ([fd8f8f2](https://github.com/material-components/material-components-web/commit/fd8f8f2b77b0a17e25f78b5a510b7afe4bbd230b))
* **select:** lower dropdown icon size and list leading padding when dense ([32aa236](https://github.com/material-components/material-components-web/commit/32aa23641258671e0eac803c0f41ae78ecce32fd))
* **select:** make selected text more flexible ([2b420c5](https://github.com/material-components/material-components-web/commit/2b420c5b318b7ada726dec774d9e09624bca9822))
* **select:** Replace hardcoded leading margins for options with dummy graphic ([7461aad](https://github.com/material-components/material-components-web/commit/7461aad68924d0f3bb790987b01f802078ebc7df))
* **select:** Support typeahead ([b0fdca4](https://github.com/material-components/material-components-web/commit/b0fdca4921afd58de567bd53b29c9b6e44dac5c1)), closes [#5705](https://github.com/material-components/material-components-web/issues/5705)
* **select:** Update behavior on upArrow/downArrow ([d92d8c9](https://github.com/material-components/material-components-web/commit/d92d8c93ee6d9c030e6d373ac2b8670ac56417ad))
* **select:** Update helper-text interactions ([142b154](https://github.com/material-components/material-components-web/commit/142b1549ee0cf40b1f1531e79e53fe5e826f254d)), closes [#5463](https://github.com/material-components/material-components-web/issues/5463)
* **select:** use floating label's required class ([d86ad3b](https://github.com/material-components/material-components-web/commit/d86ad3b6081234359ff19547649f9d391ea8aa9e))
* **shape:** add shape custom properties ([0743288](https://github.com/material-components/material-components-web/commit/0743288fb04dc8578f0b850d31fad6c00c97ea1c))
* **text-field:** Truncate floating label width w/ icons ([c141801](https://github.com/material-components/material-components-web/commit/c141801d50516a18fe53d4bc78591cefb4f57623))
* **textfield:** add filled class variant ([b70bc60](https://github.com/material-components/material-components-web/commit/b70bc601ef570dab4598ae6f3ca51bbf884fac96))
* **textfield:** add filled textarea variant ([4497b86](https://github.com/material-components/material-components-web/commit/4497b86ed8b3e0ee0781dd6f795aa1ff332d2a3b))
* **textfield:** add forced LTR input ([490fbdc](https://github.com/material-components/material-components-web/commit/490fbdc092c5c59d63f83407b83b37fb524ed0e5))
* **textfield:** add prefix and suffix ([6601d24](https://github.com/material-components/material-components-web/commit/6601d24afdc3a3d0bd2a9b3fcca68c35c9415ec1)), closes [#1892](https://github.com/material-components/material-components-web/issues/1892)
* **textfield:** add specific label-floating class ([a88c8e4](https://github.com/material-components/material-components-web/commit/a88c8e4dc873ae74a3afbae0dc8635dfaa03e67b))
* **textfield:** allow character counter to be moved outside of the textarea. ([84e7ed5](https://github.com/material-components/material-components-web/commit/84e7ed5825d3109c229d0f1f6c3edf97a3548226))
* **textfield:** allow disabled textareas to scroll and resize ([b9776b1](https://github.com/material-components/material-components-web/commit/b9776b1d09b9ccfac38b3dc471dee2fd9fc8558a))
* **textfield:** Create float transition mixin ([ca61b65](https://github.com/material-components/material-components-web/commit/ca61b656fababdf25adaa307963d4f37e6d413ec))
* **textfield:** Limit notched outline max-width ([0ab62a6](https://github.com/material-components/material-components-web/commit/0ab62a65b17192a94102231ca63f54adc39675ae))
* **textfield:** move resize handle for textareas to bottom corner ([ed52af7](https://github.com/material-components/material-components-web/commit/ed52af7677ad37138b6660ca11fbdb209be05b46))
* **textfield:** required outlined modifier for textarea ([b10d0d7](https://github.com/material-components/material-components-web/commit/b10d0d7f1911b381a47d39b5d0bc4543089efb3e))
* **textfield:** support svg icons for textfield ([d91794c](https://github.com/material-components/material-components-web/commit/d91794c7ecafbaef7150d2c88226b96d7e4c4ea6))
* **theme:** add new property mixin and custom property support ([51512a4](https://github.com/material-components/material-components-web/commit/51512a4ac375a6175b4a533ff004ea90a4318c9e))
* **theme:** custom property fallback values are now optional ([01de070](https://github.com/material-components/material-components-web/commit/01de07011d8b4b121a061da66fafe610f5484a51))
* **typography:** add container baseline mixins for flexbox ([69edc6e](https://github.com/material-components/material-components-web/commit/69edc6e2899636cfccb117376bb64dc0a267c588))


### BREAKING CHANGES

* **button:** Correct misspelling of overflow for button's label-overflow-ellipsis mixin
* **button:** Correct misspelling of overflow for button's label-overflow-ellipsis mixin
* **button:** Removes button theme-baseline() mixin, moves mixin contents to base button Sass.
* **chips:** The chip adapter and foundation interfaces have changed. Chips now use the trailing action subcomponent.
* **data-table:** Added a wrapper element to data table's table element to fix horizontal scrolling issue when pagination controls are added.
* **floating-label:** all labels that are part of a required field should now add the mdc-floating-label--required class for required fields to avoid a FOUC
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.
* **select:** Added adapter method `addMenuClass`, `removeMenuClass`
* **select:** Added adapter methods `isTypeaheadInProgress`, `typeaheadMatchItem`
* **select:** DOM structure for dropdown icon changed; `$dropdown-color` renamed to `$dropdown-icon-color`, `$dropdown-opacity` removed, `$disabled-dropdown-opacity` removed.
* **select:** HTML Markup significantly changed, see README; REMOVED adapter methods `isSelectedTextFocused`, `getSelectedTextAttr`, `setSelectedTextAttr`; ADDED adapter methods `isSelectAnchorFocused`, `getSelectAnchorAttr`, `setSelectAnchorAttr`; removed variables `outlined-dense-label-position-y`, `icon-padding`; added variables `minimum-height-for-filled-label`, `filled-baseline-top`, `selected-text-height`, `anchor-padding-left`, `anchor-padding-left-with-leading-icon`, `anchor-padding-right`.
* **select:** `density` mixin split into `filled-density`, `filled-with-leading-icon-density`; `height` mixin split into `filled-height`, `filled-with-leading-icon-height`
* **select:** `mdc-menu--fullwidth` class replaces custom width class for the menu markup in select
* **select:** adapter method removeAttributeAtIndex removed.
* **select:** added adapter method `removeSelectAnchorAttr`
* **select:** dropdown icon SVG markup now has `mdc-select__dropdown-icon-graphic` class.
* **select:** empty space around `mdc-list-item__text` spans removed in select markup
* **select:** helper text now persistent by default, `mdc-select-helper-text--persistent` removed
* **select:** non-outlined selects now require a `mdc-select--filled` class on its root
* **select:** root of mdc-select is now an inline-block element, use custom width class (i.e. `demo-width-class`) on the root instead of the anchor for width adjustments; alternately, use the new `mdc-select--fullwidth` on the root to expand width to that of its parent container
* **select:** variable `$outline-disabled-border` renamed to `$disabled-outline-color`; icon variable `$icon-opacity` removed, use alpha channel of `$icon-color` instead.
* **textfield:** Default textfields must now specify mdc-text-field--filled. Disabled outlined textfields no longer have a shaded background. Height mixin no longer specifies a baseline override, use typography's baseline-top mixin.
* **textfield:** mdc-text-field--dense and associated mixins/variables have been removed. Use the density() mixin instead.
* **textfield:** mdc-text-field--textarea must now include mdc-text-field--outlined modifier class
* **textfield:** mdc-text-field-SUB_ELEMENT imports have been removed
* **textfield:** removed the following variables: `$input-padding`, `$input-padding-top`, `$input-padding-bottom`, `$outlined-input-padding-top`, `$outlined-input-padding-bottom`, `$input-border-bottom`
* **textfield:** textareas must now add a `mdc-text-field__resizer` span around the textarea (and internal counter if present) if they are resizable
* **textfield:** textareas with internal character counters must specify the `mdc-text-field--with-internal-counter` class. Character counters should move after the textarea element.
* **theme:** `color-hash()` (and checkbox container-colors mixins) no longer works with `var()` values and now only works with custom property Maps created by `custom-properties.create()`
* **typography:** `typography.baseline-top()` and `typography.baseline-bottom()` are now private. Use `typography.baseline()` for containers and `typography.text-baseline()` for text with $top and $bottom params.


# [6.0.0](https://github.com/material-components/material-components-web/compare/v5.1.0...v6.0.0) (2020-04-22)

### Bug Fixes

* **auto-init:** Fixed issue with multiple default exports ([#5464](https://github.com/material-components/material-components-web/issues/5464)) ([8ddd5c6](https://github.com/material-components/material-components-web/commit/8ddd5c6dcbfa6d81a063b37aee4021ebf34d18f0))
* **button:** Fix outline & ink color according to spec guidance ([#5268](https://github.com/material-components/material-components-web/issues/5268)) ([ee1a68c](https://github.com/material-components/material-components-web/commit/ee1a68c54fa9240a334b0462513b855d5dab4807))
* **button:** Fixed  parameter default value in height mixin ([#5244](https://github.com/material-components/material-components-web/issues/5244)) ([b0cecf1](https://github.com/material-components/material-components-web/commit/b0cecf1451c13fd8c159c1b0ca90b2a1e9b907a0))
* **checkbox:** change checkbox event type from change to click and add some logic for IE browser ([#5316](https://github.com/material-components/material-components-web/issues/5316)) ([2e491de](https://github.com/material-components/material-components-web/commit/2e491de555d54f8d41474ccda156e5f9d0666bc4)), closes [#4893](https://github.com/material-components/material-components-web/issues/4893)
* **checkbox:** Disabled state colors in IE11 high contrast mode ([#5263](https://github.com/material-components/material-components-web/issues/5263)) ([d6a1d4b](https://github.com/material-components/material-components-web/commit/d6a1d4bf81b828f214e8bbf941090ef7d8e91c58))
* **checkbox:** Replace unique-id with custom color hash functio… ([#5404](https://github.com/material-components/material-components-web/issues/5404)) ([7be9e4a](https://github.com/material-components/material-components-web/commit/7be9e4a04387b9ca5f8afae6e4edcb3b37e6a86b))
* **checkbox:** update disabled color values ([#5209](https://github.com/material-components/material-components-web/issues/5209)) ([821871e](https://github.com/material-components/material-components-web/commit/821871e04737c5b0c0afded9e8e885680ca25a1f))
* **checkbox:** Use secondary and on-secondary as default colors ([b95172e](https://github.com/material-components/material-components-web/commit/b95172e69613c0defe82191b86ed1c1999b74400)), closes [#5730](https://github.com/material-components/material-components-web/issues/5730)
* **chips:** .d.ts file generated with syntax error ([d154836](https://github.com/material-components/material-components-web/commit/d1548369f2311e164b0920ed651ba211d05543fa))
* **chips:** .d.ts file generated with syntax error ([#5577](https://github.com/material-components/material-components-web/issues/5577)) ([98f7faa](https://github.com/material-components/material-components-web/commit/98f7faa05fa7c88e0231a00942f4ff9dedf4e8c0))
* **chips:** Do not throw error if chip set becomes empty ([#5290](https://github.com/material-components/material-components-web/issues/5290)) ([f978109](https://github.com/material-components/material-components-web/commit/f978109c33d9e67aebe5af3e460174686eea7b4a))
* **chips:** Fix browser back nav in FF when removing chip with… ([#5537](https://github.com/material-components/material-components-web/issues/5537)) ([a1a0deb](https://github.com/material-components/material-components-web/commit/a1a0deb3ea47d5d89efdcab062e438218148b975))
* **chips:** Handle IE/Edge specific key names in keyboard navigation logic ([3657f88](https://github.com/material-components/material-components-web/commit/3657f886327182c26f1d1555b2ac67c2128140b5))
* **chips:** Move touch target inside primary action ([ad3bbf7](https://github.com/material-components/material-components-web/commit/ad3bbf7822d1fe26694b798299c48e8896971e25))
* **circular-progress:** Add .npmignore file to ignore typescript files when publishing ([#5801](https://github.com/material-components/material-components-web/issues/5801)) ([f172b0f](https://github.com/material-components/material-components-web/commit/f172b0f90a91d8d3d700763d1496bb7b9c1a8d51)), closes [#5800](https://github.com/material-components/material-components-web/issues/5800)
* **circular-progress:** fix determinate transition typo & 4 color keyframes ([a301636](https://github.com/material-components/material-components-web/commit/a3016368df53b1c7967d7d146a9ea53a24442fa9))
* **circular-progress:** Fix naming in package.json and add to jsBundleFactory ([86f7cad](https://github.com/material-components/material-components-web/commit/86f7cad8330dbd600e478610eefd8dd92eb3d8c7))
* **circular-progress:** Force LTR layout ([6a40ef2](https://github.com/material-components/material-components-web/commit/6a40ef217f597138ee2920d2160364649dbf5620))
* **circular-progress:** Switch mixins import to `[@use](https://github.com/use)` ([098ae32](https://github.com/material-components/material-components-web/commit/098ae3285223af2532659dec233537a55c1183f5))
* **core:** Fix canary release by excluding test files from default tsconfig ([#5317](https://github.com/material-components/material-components-web/issues/5317)) ([c916008](https://github.com/material-components/material-components-web/commit/c9160084f1f64800e74e0e69673c6b2beca22ee4))
* **data-table:** change svg attribute name viewbox to viewBox ([#5483](https://github.com/material-components/material-components-web/issues/5483)) ([#5493](https://github.com/material-components/material-components-web/issues/5493)) ([f3adce8](https://github.com/material-components/material-components-web/commit/f3adce86f43c15d3e2311363bf317ff68a3bb99d))
* **data-table:** Fix pagination box height ([eb28b6e](https://github.com/material-components/material-components-web/commit/eb28b6ecc65a9979ef0959eac5dbfde5b4d3b2dc))
* **data-table:** Fixed default feature targeting query params of sort mixins ([e33c49e](https://github.com/material-components/material-components-web/commit/e33c49eaf9c0dbc601f3610af6358cbf2833229c))
* **data-table:** Hover styles for sortable header cell ([d580805](https://github.com/material-components/material-components-web/commit/d5808057fcdf00364731e0896ef7031ac605cf55))
* **data-table:** Reverse the arrow direction icon for column sorting ([a7c827f](https://github.com/material-components/material-components-web/commit/a7c827f17ce9be631484676ccb6b5f18604803ae))
* **data-table:** unable to redefine colors in class-based themi… ([#5751](https://github.com/material-components/material-components-web/issues/5751)) ([4d48051](https://github.com/material-components/material-components-web/commit/4d48051c1099f48e867cf08f070138a7abc719fc))
* **data-table:** unable to redefine colors in class-based theming ([4b45b66](https://github.com/material-components/material-components-web/commit/4b45b662057edd8819f1a515db88e1c12254cc30))
* **dialog:** Move aria roles from dialog root to dialog surface… ([#5239](https://github.com/material-components/material-components-web/issues/5239)) ([c704b71](https://github.com/material-components/material-components-web/commit/c704b71d931dd0db191a30ff88a5d0c44f099300))
* **elevation:** Update overlay color mixin ([#5331](https://github.com/material-components/material-components-web/issues/5331)) ([b723dfa](https://github.com/material-components/material-components-web/commit/b723dfa7848c4b96bc24bb148cc5f55f316625ee))
* **fab:** Add missing dep to fab package.json. ([#5236](https://github.com/material-components/material-components-web/issues/5236)) ([e0f6fd9](https://github.com/material-components/material-components-web/commit/e0f6fd931f677874dcad4d91c3d74a2125674e96))
* **fab:** Add overflow: visible to make touch target visible in… ([#5241](https://github.com/material-components/material-components-web/issues/5241)) ([5850080](https://github.com/material-components/material-components-web/commit/58500806e27a0931404631d76bc09646bc64caaf))
* **fab:** Adjust fab line-height ([#5254](https://github.com/material-components/material-components-web/issues/5254)) ([525989b](https://github.com/material-components/material-components-web/commit/525989b5d8dfe86bcb6f65e0f0f0fd138e4b4b76))
* **fab:** Adjust fab line-height to center text ([#5258](https://github.com/material-components/material-components-web/issues/5258)) ([591a6ad](https://github.com/material-components/material-components-web/commit/591a6ad449f98efa7bc00c8afdd2716a6fbe75d9))
* **floatinglabel:** Estimate hidden scroll width ([#5448](https://github.com/material-components/material-components-web/issues/5448)) ([981ec9b](https://github.com/material-components/material-components-web/commit/981ec9b6fd538caadb44f7469745de8f8954c89b))
* **linear-progress:** Temporary rollback of [#5656](https://github.com/material-components/material-components-web/issues/5656) while updating downstream dependencies ([9cf5e98](https://github.com/material-components/material-components-web/commit/9cf5e9842475e50046462aa1c6d18e326abaee17))
* **linear-progress:** support aria attributes (#5248) ([7084b40](https://github.com/material-components/material-components-web/commit/7084b403a4ab6be0856c670eebb39078a4fcbcfe)), closes [#5248](https://github.com/material-components/material-components-web/issues/5248)
* **list:** Ensure disabled colors apply to primary and secondary text ([#5322](https://github.com/material-components/material-components-web/issues/5322)) ([878a08b](https://github.com/material-components/material-components-web/commit/878a08b7cf673ba45f124b400032928b2c273749))
* **list:** No longer emits action event when disabled item selected ([f352d03](https://github.com/material-components/material-components-web/commit/f352d03f4ed48c5019a0a3e10ef12689a5ab5619)), closes [#5571](https://github.com/material-components/material-components-web/issues/5571)
* **menu-surface:** Use margin_to_edge as a viewport margin in calculations for autopositioning. ([4b04cdb](https://github.com/material-components/material-components-web/commit/4b04cdb0fc4da4831340b01292c118b120c1fcb1))
* **menusurface:** open and closed events not fired when already opened or closed ([9cff431](https://github.com/material-components/material-components-web/commit/9cff4318f0fe8a79f8787afd148907328a5223d5))
* **menusurface:** synchronous quick menu does not close on button click ([45a6615](https://github.com/material-components/material-components-web/commit/45a6615e33eb8a7e6fc37e9ef43a3be3682b6b0e))
* **notched-outline:** Restore component test ([#5449](https://github.com/material-components/material-components-web/issues/5449)) ([4269133](https://github.com/material-components/material-components-web/commit/4269133421f7058385255b0676be94c9c1170b2d))
* **radio:** update disabled color values ([#5210](https://github.com/material-components/material-components-web/issues/5210)) ([491fddc](https://github.com/material-components/material-components-web/commit/491fddc31c16f99206b1fa7dce37d43b742e86f5))
* **select:** Deduplicate change events ([4ad1274](https://github.com/material-components/material-components-web/commit/4ad12741e41c5b8e175f2bc8d5053daec6cedf18)), closes [#5570](https://github.com/material-components/material-components-web/issues/5570)
* **select:** Do not fire change event on programmatic change ([#5255](https://github.com/material-components/material-components-web/issues/5255)) ([ec72968](https://github.com/material-components/material-components-web/commit/ec729683b46fb986a880f26870973337ec6788e5))
* **select:** Fix notch outline width when floating ([#5319](https://github.com/material-components/material-components-web/issues/5319)) ([1c494e5](https://github.com/material-components/material-components-web/commit/1c494e5672c142f3f3451aa2270431844d35c88e))
* **slider:** slider track not visible ([#5512](https://github.com/material-components/material-components-web/issues/5512)) ([f2426d2](https://github.com/material-components/material-components-web/commit/f2426d26e683591cee87b4107f990492b47ec837))
* **slider:** two change events fired on each up ([d10412c](https://github.com/material-components/material-components-web/commit/d10412cb24150639acc617caef1c7fac4fb6e4bd))
* **slider:** use secondary custom property color for slider container ([#5132](https://github.com/material-components/material-components-web/issues/5132)) ([aa8e43e](https://github.com/material-components/material-components-web/commit/aa8e43e9afaa1e00080f149bbe497746b57a285a))
* **slider:** Visual bug when slider value is displayed as "-0" ([3fc3ab5](https://github.com/material-components/material-components-web/commit/3fc3ab520ab5399c3b87b094e047a1751f7aa9af))
* **snackbar:** add explicit width for label to wrap in ie11 ([#5497](https://github.com/material-components/material-components-web/issues/5497)) ([cd49033](https://github.com/material-components/material-components-web/commit/cd4903304412d79be8da96499091259b5e954c80))
* **snackbar:** adjust mixins to meet spec ([#5477](https://github.com/material-components/material-components-web/issues/5477)) ([f16f15b](https://github.com/material-components/material-components-web/commit/f16f15b8fda0d8c283bed5551b78620bf2fd3b82))
* **switch:** add transform transition to switch control to avoid overflow-x issues ([8c11ea2](https://github.com/material-components/material-components-web/commit/8c11ea2a3bd7962c6d895c5bd6b849f95b52d10c))
* **switch:** always set track to transparent border ([9a169f4](https://github.com/material-components/material-components-web/commit/9a169f4b158a3148126ba38bcdfa9d163434d9bb))
* **switch:** fix strict generic checks ([7f5e0c2](https://github.com/material-components/material-components-web/commit/7f5e0c23ffb2f547d9bfca6b68927b5861a3112b))
* **switch:** handle aria-checked correctly. ([#5202](https://github.com/material-components/material-components-web/issues/5202)) ([#5357](https://github.com/material-components/material-components-web/issues/5357)) ([d245a1a](https://github.com/material-components/material-components-web/commit/d245a1a544c643b59f77cd2e01b7eb2c1182f6b9))
* **switch:** set track border to be transparent ([#5323](https://github.com/material-components/material-components-web/issues/5323)) ([397905b](https://github.com/material-components/material-components-web/commit/397905b4e34ff9769d3ae18464bc397a0b13050f))
* **switch:** use CSS custom properties for theming ([d6315ef](https://github.com/material-components/material-components-web/commit/d6315efe26e7baf45fd88244efbb24c612a95cb4))
* **testing:** Revert change from [#5299](https://github.com/material-components/material-components-web/issues/5299). ([#5324](https://github.com/material-components/material-components-web/issues/5324)) ([5fb62be](https://github.com/material-components/material-components-web/commit/5fb62bead477f7db9a76d9c0adbfee4e9c110d37))
* **textfield:** add placeholder mixins and fix disabled colors ([#5360](https://github.com/material-components/material-components-web/issues/5360)) ([0a40ced](https://github.com/material-components/material-components-web/commit/0a40ced406f96b5c84cf39457ffe880d00999714))
* **textfield:** add separate classes for leading/trailing icons ([#5367](https://github.com/material-components/material-components-web/issues/5367)) ([70c708d](https://github.com/material-components/material-components-web/commit/70c708deece4c2c0afe38a31a4989abf2b1c1743))
* **textfield:** change root element to <label> ([#5439](https://github.com/material-components/material-components-web/issues/5439)) ([d8d9502](https://github.com/material-components/material-components-web/commit/d8d95020ff94249f8755ca49aaa06a6e9f0813b0))
* **textfield:** clean up input padding ([8639c26](https://github.com/material-components/material-components-web/commit/8639c269010b77b17f1a5052d57abcb5f7d2892a))
* **textfield:** hide filled-variant floating label at <52px ([#5553](https://github.com/material-components/material-components-web/issues/5553)) ([5ff3380](https://github.com/material-components/material-components-web/commit/5ff33802c22acf7d94fd94c9ccdcfcf901397d56))
* **textfield:** IE11 label overlapping placeholder ([781434a](https://github.com/material-components/material-components-web/commit/781434a92f4dddc9b2d39853e1f5792e89e7b45b))
* **textfield:** incorrect mixin forward path ([#5554](https://github.com/material-components/material-components-web/issues/5554)) ([3e782d8](https://github.com/material-components/material-components-web/commit/3e782d8f84c0096f6a6de3e022017fbb05175fa2))
* **textfield:** move ripple to separate element ([c541ebe](https://github.com/material-components/material-components-web/commit/c541ebe157a66e8d2e881fad16cc4dbe30b2c16b))
* **textfield:** outlined trailing icon's position ([#5496](https://github.com/material-components/material-components-web/issues/5496)) ([93e2288](https://github.com/material-components/material-components-web/commit/93e2288b6ef73c13402a1f5122e2f9a4523ed4a4))
* **textfield:** prevent placeholder styles from collapsing with minifiers ([d07c78d](https://github.com/material-components/material-components-web/commit/d07c78daa83389ef428618d334b037da67740b99))
* add missing SASS dependencies ([#5337](https://github.com/material-components/material-components-web/issues/5337)) ([d2ae6e1](https://github.com/material-components/material-components-web/commit/d2ae6e17d19e7139bce45a0f44ce4ba172bbb3e6))
* **textfield:** remove absolute positioning from icons ([1e13d1d](https://github.com/material-components/material-components-web/commit/1e13d1d5a68632f1b0b5a9134f657d59104969f4))
* **textfield:** remove deprecated dense variant in favor of density ([776291e](https://github.com/material-components/material-components-web/commit/776291ef03205e4063b4040eb66f9648e16b4af6)), closes [#4142](https://github.com/material-components/material-components-web/issues/4142)
* **textfield:** use correct disabled colors for IE11 high contrast ([5353985](https://github.com/material-components/material-components-web/commit/535398572daea2ec389c341f4e0c53cb33582b26))
* Remove edge detection for CSS custom properties ([#5264](https://github.com/material-components/material-components-web/issues/5264)) ([fe444ac](https://github.com/material-components/material-components-web/commit/fe444ac29da5447419cf4c25edbdf934c6e388e4))
* server-side rendering errors in linear progress and slider ([7d0b983](https://github.com/material-components/material-components-web/commit/7d0b983a902deee6941d61906aa5a880628db4e9))


### Code Refactoring

* migrate to the Sass module system ([#5453](https://github.com/material-components/material-components-web/issues/5453)) ([faa9af3](https://github.com/material-components/material-components-web/commit/faa9af310d1a18ec2c183830c84eb14d0492feab))
* **grid-list:** Deprecate component ([#5499](https://github.com/material-components/material-components-web/issues/5499)) ([cf33f11](https://github.com/material-components/material-components-web/commit/cf33f113dd89bbfb2873c9ce3fa1525076bfd4ec))
* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([98b8434](https://github.com/material-components/material-components-web/commit/98b843417ef6c0a10460532a37df389b0c7e936f))
* **linear-progress:** Restructure buffer DOM to allow translucent buffer ([9372e49](https://github.com/material-components/material-components-web/commit/9372e493954585c939f341486d0361efb87da806))
* **select:** Fix alignment issues, upgrade anchor to interactive element ([28d10a9](https://github.com/material-components/material-components-web/commit/28d10a96e1d5e5762d5a056ac805070e9fb6a4e1)), closes [#5428](https://github.com/material-components/material-components-web/issues/5428)
* **touchtarget:** Rename mdc-touch-target-component => mdc… ([#5245](https://github.com/material-components/material-components-web/issues/5245)) ([afe0dd1](https://github.com/material-components/material-components-web/commit/afe0dd1bc240a7a88d76b0a3bf1a36044527babd))


### Features

* **button:** Add disabled state color mixins ([#5232](https://github.com/material-components/material-components-web/issues/5232)) ([b5eb51e](https://github.com/material-components/material-components-web/commit/b5eb51e942b8f233bc1a9a5cf4b4d0c94fb8ea57))
* **button:** Add overflow ellipsis mixin ([#5352](https://github.com/material-components/material-components-web/issues/5352)) ([47949b0](https://github.com/material-components/material-components-web/commit/47949b08e0a2ec82178c638d8074c34c745409b4))
* **button:** Expand outlined touch target to include side borders ([ce6cb70](https://github.com/material-components/material-components-web/commit/ce6cb7024d1da3b0e4fb5e2c67ba269dbb3098ec))
* **button:** Setup elevation overlay ([#5256](https://github.com/material-components/material-components-web/issues/5256)) ([3cbee6d](https://github.com/material-components/material-components-web/commit/3cbee6dac7cafbe8986bad0a8593d870b00f5f32))
* **card:** Add elevation overlay structure ([#5282](https://github.com/material-components/material-components-web/issues/5282)) ([aa0eba4](https://github.com/material-components/material-components-web/commit/aa0eba489a33cb523ae1b5ac5b0ab24995731456))
* **checkbox:** Add support for checkbox CSS-only `indeterminate` checkbox ([b273afa](https://github.com/material-components/material-components-web/commit/b273afa93441e6d0375f7df33d5b69d8a7e1cfa8))
* **chips:** Add chips styling ([1db5c9f](https://github.com/material-components/material-components-web/commit/1db5c9fc842292715f8b4603ce0b979066f1c639))
* **chips:** Add elevation overlay structure ([#5279](https://github.com/material-components/material-components-web/issues/5279)) ([3e560b3](https://github.com/material-components/material-components-web/commit/3e560b33a8fbf820a404596d76ae5f743e57b6a2))
* **chips:** Add focus{in|out} handlers ([10af6cf](https://github.com/material-components/material-components-web/commit/10af6cf39cb2ae0a7deb9a951960f115f6ecdace))
* **chips:** Add keyCode support ([82fa986](https://github.com/material-components/material-components-web/commit/82fa986b95be4c16271df50effda1046d015d35c))
* **chips:** Add trailing action feature targeting test ([bec0659](https://github.com/material-components/material-components-web/commit/bec0659206aee793e6970d59c73f7969ab540b69))
* **chips:** Announce when chips are removed ([b3f70eb](https://github.com/material-components/material-components-web/commit/b3f70ebded85240e75c6d1553cc9d0382b22c31d))
* **chips:** Consolidate interaction event handlers ([#5251](https://github.com/material-components/material-components-web/issues/5251)) ([5729943](https://github.com/material-components/material-components-web/commit/5729943baf1726e931e26907c78774f2caec404e))
* **chips:** Create trailing action business logic ([9ebee4c](https://github.com/material-components/material-components-web/commit/9ebee4ceb998e5fa651d4f147e5e39d43600db6e))
* **chips:** Expose trailing action chip files ([6b48781](https://github.com/material-components/material-components-web/commit/6b48781bf97d3b08b8f35b9eacde2b87748ae2e1))
* **chips:** Restructure trailing action mixins ([05f5e15](https://github.com/material-components/material-components-web/commit/05f5e1583b81bc00dbcd2ae21ee0acc43b3e13b4))
* **circular-progress:** Add foundation methods to get isDeterminate and progress value ([7d8f9c8](https://github.com/material-components/material-components-web/commit/7d8f9c8d73f16c01ed4a941ab9510377a0aae219))
* **circular-progress:** Add Sass styles and tests ([bd33cb5](https://github.com/material-components/material-components-web/commit/bd33cb56bdab7139052aeedbeec363f17b4dfc40))
* **circular-progress:** Add TS for foundation, adapter, component with tests ([548b1d4](https://github.com/material-components/material-components-web/commit/548b1d4057f21e066a4c494a57a0c068c23e18cd))
* **data-table:** Add base styles to support pagination. ([927fa90](https://github.com/material-components/material-components-web/commit/927fa902c3297a5a7cc9436e82cb81f3aabe1b4b))
* **data-table:** Add foundation methods to support loading state. ([e75deb8](https://github.com/material-components/material-components-web/commit/e75deb8540fa70236087d335c9cd6280bd643285))
* **data-table:** Added styles for table in loading state ([35a32aa](https://github.com/material-components/material-components-web/commit/35a32aaeac17e290e2e9f9a1310c5a44a08f624a))
* **data-table:** Added styles to support column sorting. ([17b9699](https://github.com/material-components/material-components-web/commit/17b9699c4454a107043e5a1f9874a091089dd112))
* **data-table:** Foundation changes to support column sorting ([6ee0355](https://github.com/material-components/material-components-web/commit/6ee03557260d0a23296e36cba5aaa76fe0cf96a6))
* **data-table:** Set progress indicator styles based on table body height ([c026422](https://github.com/material-components/material-components-web/commit/c0264227393df8eb9259a2b24c23b31fe0ca84f3))
* **dialog:** Add elevation overlay structure ([#5283](https://github.com/material-components/material-components-web/issues/5283)) ([b8bc4a2](https://github.com/material-components/material-components-web/commit/b8bc4a26ea70356cc96de8fd3266890048f0a3ab))
* **dom:** Add focus trap utility. ([#5505](https://github.com/material-components/material-components-web/issues/5505)) ([63f357d](https://github.com/material-components/material-components-web/commit/63f357dbf5c7e84c3961aafc09e0fb4f4a9c3cda))
* **dom:** Add keyboard support ([5f24faa](https://github.com/material-components/material-components-web/commit/5f24faacb1ef8996ae81f3a1c1e43910ba67b024))
* **dom:** Create announcer utility ([32c1df1](https://github.com/material-components/material-components-web/commit/32c1df133f07679b44ce34ed9d11e22035f8d3d9))
* **elevation:** Add elevation overlay mixins ([#5249](https://github.com/material-components/material-components-web/issues/5249)) ([b4cfdc4](https://github.com/material-components/material-components-web/commit/b4cfdc40b7c4a3d3fc48df2b68b7091552c27610))
* **elevation:** Update elevation mixins ([#5304](https://github.com/material-components/material-components-web/issues/5304)) ([ba879b6](https://github.com/material-components/material-components-web/commit/ba879b68bde09d713faa5cd77aea9d2bd2759e33))
* **fab:** Add elevation overlay structure ([#5278](https://github.com/material-components/material-components-web/issues/5278)) ([e89750d](https://github.com/material-components/material-components-web/commit/e89750dc78ea521561a03e020f4414479de5a5b9))
* **fab:** Add outline in high-contrast mode ([deda86d](https://github.com/material-components/material-components-web/commit/deda86d8cc4665b334c4d21c541a4a30244fee72))
* **fab:** Add support for increased touch target to mini FAB. ([#5231](https://github.com/material-components/material-components-web/issues/5231)) ([0c4d8f3](https://github.com/material-components/material-components-web/commit/0c4d8f3923f9a089132ed8dca4062b72d3576aca))
* **floating-label:** add feature targeting for styles ([#5287](https://github.com/material-components/material-components-web/issues/5287)) ([b240bcc](https://github.com/material-components/material-components-web/commit/b240bcc1bbb3cfd1f753918ec1553dbe1bb6d007))
* **form-field:** Add support for space-between ([e84b9c8](https://github.com/material-components/material-components-web/commit/e84b9c816d32da6dec058d92fc21dc5ac8fec787)), closes [#5747](https://github.com/material-components/material-components-web/issues/5747)
* **formfield:** add nowrap class/prop to MDC/MWC ([c4b4bba](https://github.com/material-components/material-components-web/commit/c4b4bba9659bf15207e79b1f63fcc9946404d9c7))
* **icon-button:** Add disabled state color mixins ([#5246](https://github.com/material-components/material-components-web/issues/5246)) ([7161170](https://github.com/material-components/material-components-web/commit/7161170f2e39b73b69b97dec11ebf94e1d3a10c4))
* **iconbutton:** Add icon button variant which supports toggling aria label. ([f838c6e](https://github.com/material-components/material-components-web/commit/f838c6e55672268de4e6e3b31b154d4f9050242f))
* **line-ripple:** add active/inactive states to line-ripple ([b6c7f62](https://github.com/material-components/material-components-web/commit/b6c7f624bc7d88e2e371efcb125c7a6bac55eab7))
* **line-ripple:** add feature targeting for styles ([#5292](https://github.com/material-components/material-components-web/issues/5292)) ([391674a](https://github.com/material-components/material-components-web/commit/391674a2649800f07e3ac1993a5fce157391fbd9))
* **linear-progress:** Add foundation methods to fetch progress and determinate state. ([4dc45af](https://github.com/material-components/material-components-web/commit/4dc45af6c4bc81f5734a24c160046d283c1e9a6d))
* **menu:** Add elevation overlay structure ([#5280](https://github.com/material-components/material-components-web/issues/5280)) ([7fd17ce](https://github.com/material-components/material-components-web/commit/7fd17ce5ed73c86b987c8a8e4cd08ea444fff8b7))
* **menu:** Add mixin to flatten menu top when opened-below anchor ([1e17c49](https://github.com/material-components/material-components-web/commit/1e17c49b360fd0e01c9a74b92978031534003b5b))
* **menu-surface:** Add support for flipping menu corner horizontally. ([7b44824](https://github.com/material-components/material-components-web/commit/7b448240263b45c6b474c2f758cd1c02f3c708ad))
* **notched-outline:** add feature targeting for styles ([#5289](https://github.com/material-components/material-components-web/issues/5289)) ([c483774](https://github.com/material-components/material-components-web/commit/c4837746ccebf375daa4c5dd891fea533bb134f7))
* **progress-indicator:** Add common interface for progress indicators ([#5564](https://github.com/material-components/material-components-web/issues/5564)) ([ea863cb](https://github.com/material-components/material-components-web/commit/ea863cb918b9c096e36a7bc653d6661757e71b64))
* **ripple:** Reorganize ripple opacities ([008c4d3](https://github.com/material-components/material-components-web/commit/008c4d3191f9c2a76732688504d2299420734cdd))
* **switch:** Add elevation overlay structure ([#5281](https://github.com/material-components/material-components-web/issues/5281)) ([50f110a](https://github.com/material-components/material-components-web/commit/50f110a6cf8100e594bdbd6c02ee278c39924008))
* **switch:** Restructure DOM ([#5312](https://github.com/material-components/material-components-web/issues/5312)) ([0ec1fab](https://github.com/material-components/material-components-web/commit/0ec1fabc39222cac4446c8e2b85d74d2a5d21e1a))
* **text-field:** Add disabled state color mixins ([#5208](https://github.com/material-components/material-components-web/issues/5208)) ([66299b6](https://github.com/material-components/material-components-web/commit/66299b64613e8399af263d7021f93f9cdaf74ae3))
* **text-field:** add feature targeting for styles ([#5378](https://github.com/material-components/material-components-web/issues/5378)) ([e8a9936](https://github.com/material-components/material-components-web/commit/e8a993677858893965608a55931d7e54c84e8c5d))
* **text-field:** Truncate floating label width w/ icons ([c141801](https://github.com/material-components/material-components-web/commit/c141801d50516a18fe53d4bc78591cefb4f57623))
* **textfield:** add end-alignment ([#5356](https://github.com/material-components/material-components-web/issues/5356)) ([847dd1a](https://github.com/material-components/material-components-web/commit/847dd1ada08bb0fd905adac7b7836540a0dd7e9c))
* **textfield:** add filled class variant ([b70bc60](https://github.com/material-components/material-components-web/commit/b70bc601ef570dab4598ae6f3ca51bbf884fac96))
* **textfield:** add forced LTR input ([490fbdc](https://github.com/material-components/material-components-web/commit/490fbdc092c5c59d63f83407b83b37fb524ed0e5))
* **textfield:** add prefix and suffix ([6601d24](https://github.com/material-components/material-components-web/commit/6601d24afdc3a3d0bd2a9b3fcca68c35c9415ec1)), closes [#1892](https://github.com/material-components/material-components-web/issues/1892)
* Add index stylesheets to each MDC Web package ([#5539](https://github.com/material-components/material-components-web/issues/5539)) ([1814866](https://github.com/material-components/material-components-web/commit/181486643532e2166dced95daff9da786af3bdd1))
* Add index stylesheets to mdc-image-list and mdc-layout-gr… ([#5546](https://github.com/material-components/material-components-web/issues/5546)) ([3a85313](https://github.com/material-components/material-components-web/commit/3a85313ac121703e8aeac583502adf9863d96a8e))
* Use [@use](https://github.com/use) syntax in material-components-web Sass file and… ([#5573](https://github.com/material-components/material-components-web/issues/5573)) ([b4727e4](https://github.com/material-components/material-components-web/commit/b4727e43aa17afe03b240402ded590c0516267d5))
* **textfield:** add specific label-floating class ([a88c8e4](https://github.com/material-components/material-components-web/commit/a88c8e4dc873ae74a3afbae0dc8635dfaa03e67b))
* **textfield:** allow character counter to be moved outside of the textarea. ([84e7ed5](https://github.com/material-components/material-components-web/commit/84e7ed5825d3109c229d0f1f6c3edf97a3548226))
* **textfield:** Create float transition mixin ([ca61b65](https://github.com/material-components/material-components-web/commit/ca61b656fababdf25adaa307963d4f37e6d413ec))
* **textfield:** Limit notched outline max-width ([0ab62a6](https://github.com/material-components/material-components-web/commit/0ab62a65b17192a94102231ca63f54adc39675ae))
* **typography:** add container baseline mixins for flexbox ([69edc6e](https://github.com/material-components/material-components-web/commit/69edc6e2899636cfccb117376bb64dc0a267c588))


### Reverts

* Revert "feat(switch): Add elevation overlay structure (#5281)" (#5329) ([1fbf5bd](https://github.com/material-components/material-components-web/commit/1fbf5bd1d84b7b02eb7f0a7aff2b9c3eed0b4d3d)), closes [#5281](https://github.com/material-components/material-components-web/issues/5281) [#5329](https://github.com/material-components/material-components-web/issues/5329)
* "fix(checkbox): change checkbox event type from change to click and add some logic for IE browser" ([ba30399](https://github.com/material-components/material-components-web/commit/ba30399adc901ca090c90bb1cad9410c81ae5fd1))
* feat(chips): Consolidate interaction event handlers ([#5251](https://github.com/material-components/material-components-web/issues/5251)) ([#5301](https://github.com/material-components/material-components-web/issues/5301)) ([5e45d77](https://github.com/material-components/material-components-web/commit/5e45d77f3e387eff356f5ce93336d4b872c725c4))
* fix(chips): Do not throw error if chip set becomes empty ([#5300](https://github.com/material-components/material-components-web/issues/5300)) ([d10e8cd](https://github.com/material-components/material-components-web/commit/d10e8cdf3cda4a735b1ae43bb17592f9383c8886))
* fix(select): Do not fire change event on programmatic change ([#5255](https://github.com/material-components/material-components-web/issues/5255)) ([#5302](https://github.com/material-components/material-components-web/issues/5302)) ([ad9dfe7](https://github.com/material-components/material-components-web/commit/ad9dfe706de46d5dc131ad6615aa18f0e3b01133))


### BREAKING CHANGES

* **select:** HTML Markup significantly changed, see README; REMOVED adapter methods `isSelectedTextFocused`, `getSelectedTextAttr`, `setSelectedTextAttr`; ADDED adapter methods `isSelectAnchorFocused`, `getSelectAnchorAttr`, `setSelectAnchorAttr`; removed variables `outlined-dense-label-position-y`, `icon-padding`; added variables `minimum-height-for-filled-label`, `filled-baseline-top`, `selected-text-height`, `anchor-padding-left`, `anchor-padding-left-with-leading-icon`, `anchor-padding-right`.
* **text-field:** Redundant mixins `mdc-text-field-textarea-fill-color`, `mdc-text-field-textarea-stroke-color`, `mdc-text-field-fullwidth-bottom-line-color` removed. Instead, use `mdc-text-field-fill-color`, `mdc-text-field-outline-color`, and `mdc-text-field-bottom-line-color` respectively to achieve the same effect.
* **textfield:** mdc-text-field--dense and associated mixins/variables have been removed. Use the density() mixin instead.
* **textfield:** removed the following variables: `$input-padding`, `$input-padding-top`, `$input-padding-bottom`, `$outlined-input-padding-top`, `$outlined-input-padding-bottom`, `$input-border-bottom`
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.
* **linear-progress:** DOM for linear progress buffer changed. MDCLinearProgressAdapter method `getBuffer`, `getPrimaryBar`, `setStyle` removed. MDCLinearProgressAdapter method `setBufferBarStyle`, `setPrimaryBarStyle` added.
* **typography:** `typography.baseline-top()` and `typography.baseline-bottom()` are now private. Use `typography.baseline()` for containers and `typography.text-baseline()` for text with $top and $bottom params.
* **chips:** The touch target and text now appear inside the primary action element. Please see the readme for markup changes.
* **textfield:** filled text fields must include a `<div class="mdc-text-field__ripple"></div>`
* **textfield:** Filled textfields will no longer show a floating label at certain densities. This can be overridden by setting `$mdc-text-field-minimum-height-for-filled-label: 40px`
* **chips:** Both `MDCChipAdapter` and `MDCChipSetAdapter` have new methods. `MDCChipSetFoundation` event handlers now accept the corresponding chip event detail interface as the sole argument. The `root` property has been removed from the `MDCChipRemovalEventDetail` interface.
* **line-ripple:** `mdc-line-ripple-color()` mixin has been renamed to `mdc-line-ripple-active-color()`
* **textfield:** Default textfields must now specify mdc-text-field--filled. Disabled outlined textfields no longer have a shaded background. Height mixin no longer specifies a baseline override, use typography's baseline-top mixin.

* Four variables and a mixin in mdc-textfield were renamed to use a mdc-text-field- prefix when depended on via @import (formerly mdc-required-text-field-label-asterisk_, now required-label-asterisk_).
* **textfield:** icons must use `.mdc-text-field__icon--leading` or `.mdc-text-field__icon--trailing` classes. `mdc-text-field-icon-color()` mixin has been split into `mdc-text-field-leading-icon-color()` and `mdc-text-field-trailing-icon-color()`.
* **switch:** Added setNativeControlAttr method in mdc-switch adapter.
* **checkbox:** remove event listener for 'change' and add event listener for 'click'.
- Add handleClick() method in foundation to handle click event.
- Add setCheck() method into component to change check status.
* **switch:** Switch DOM structure has changed. See switch README for details
* **button:** Variable `$mdc-button-disabled-container-fill-color`
renamed to `$mdc-button-disabled-container-color`.
* Removed `$edgeOptOut` option from `mdc-theme-prop()` Sass mixin.
* **chips:** the handleInteraction and handleTrailingIconInteraction handlers have been removed from the MDCChipFoundation. The handleClick handler has been added to the MDCChipFoundation
* Adds new adapter methods to MDCLinearProgressAdapter.
* **elevation:** Functions moved into the _functions.scss file
* **touchtarget:** Renames mixin from mdc-touch-target-component => mdc-touch-target-margin
* **grid-list:** Per the deprecation notice for grid-list, this component has been
removed from MDC-Web. Some of its functionalities are available in the MDC Image List package instead. It is recommended that you migrate to the mdc-image-list package to continue to receive new features and updates.


# 4.0.0 (2019-11-02)

# [4.0.0](https://github.com/material-components/material-components-web/compare/v3.2.0...v4.0.0) (2019-11-02)

### Bug Fixes

* **button:** Add `overflow: visible` to button. ([#4973](https://github.com/material-components/material-components-web/issues/4973)) ([905e84e](https://github.com/material-components/material-components-web/commit/905e84e))
* **button:** Adjust touch target size when density is applied ([#5112](https://github.com/material-components/material-components-web/issues/5112)) ([e2506f4](https://github.com/material-components/material-components-web/commit/e2506f4))
* **checkbox:** Change minimum ripple size of checkbox & switch 24px => 28px ([#5140](https://github.com/material-components/material-components-web/issues/5140)) ([3eae309](https://github.com/material-components/material-components-web/commit/3eae309))
* **checkbox:** Fix checkbox terminology in sass mixins ([#5014](https://github.com/material-components/material-components-web/issues/5014)) ([2161c02](https://github.com/material-components/material-components-web/commit/2161c02))
* **checkbox:** Remove RTL styles from checkbox ripple ([#5134](https://github.com/material-components/material-components-web/issues/5134)) ([a646516](https://github.com/material-components/material-components-web/commit/a646516))
* **chips:** Ignore selection events in chip set ([#4878](https://github.com/material-components/material-components-web/issues/4878)) ([94c6a00](https://github.com/material-components/material-components-web/commit/94c6a00))
* **chips:** Remove keyCode check ([#4966](https://github.com/material-components/material-components-web/issues/4966)) ([e6304c4](https://github.com/material-components/material-components-web/commit/e6304c4))
* **chips:** Reset touch target when chip density mixin is applied. ([#5116](https://github.com/material-components/material-components-web/issues/5116)) ([d3b515e](https://github.com/material-components/material-components-web/commit/d3b515e))
* **chips:** Stack trailing/leading icons above touch target el ([#5040](https://github.com/material-components/material-components-web/issues/5040)) ([048d4b7](https://github.com/material-components/material-components-web/commit/048d4b7))
* **chips:** Stop emitting events in handlers ([#4969](https://github.com/material-components/material-components-web/issues/4969)) ([cfd81dc](https://github.com/material-components/material-components-web/commit/cfd81dc))
* **data-table:** Minor fixes for data table layout ([#5037](https://github.com/material-components/material-components-web/issues/5037)) ([37b1f93](https://github.com/material-components/material-components-web/commit/37b1f93))
* **fab:** Add overflow: hidden; to ripple target to fix bounded ripple. ([#5214](https://github.com/material-components/material-components-web/issues/5214)) ([97cbbdc](https://github.com/material-components/material-components-web/commit/97cbbdc))
* **fab:** Use FAB ripple target selector ([#5146](https://github.com/material-components/material-components-web/issues/5146)) ([9d91acc](https://github.com/material-components/material-components-web/commit/9d91acc))
* **form-field:** Fix radio RTL alignment bug. ([#5064](https://github.com/material-components/material-components-web/issues/5064)) ([ef99808](https://github.com/material-components/material-components-web/commit/ef99808))
* **linear-progress:** Fix indeterminate animation bug ([#5180](https://github.com/material-components/material-components-web/issues/5180)) ([062ade5](https://github.com/material-components/material-components-web/commit/062ade5))
* **linear-progress:** Prefix animation keyframes to prevent clashing ([#5155](https://github.com/material-components/material-components-web/issues/5155)) ([fc0e474](https://github.com/material-components/material-components-web/commit/fc0e474))
* **linear-progress:** Restore buffer after determinate is toggl… ([#5156](https://github.com/material-components/material-components-web/issues/5156)) ([09b1598](https://github.com/material-components/material-components-web/commit/09b1598))
* **linear-progress:** Support high contrast mode ([#5190](https://github.com/material-components/material-components-web/issues/5190)) ([d4141c9](https://github.com/material-components/material-components-web/commit/d4141c9))
* **list:** Add #adapter.listItemAtIndexHasClass to prevent user state change to disabled items ([#4922](https://github.com/material-components/material-components-web/issues/4922)) ([b6d213c](https://github.com/material-components/material-components-web/commit/b6d213c))
* **menu:** Vertically center the group icon ([#4862](https://github.com/material-components/material-components-web/issues/4862)) ([c5738ed](https://github.com/material-components/material-components-web/commit/c5738ed))
* **menu-surface:** remove duplicate export from menu-surface ([#5200](https://github.com/material-components/material-components-web/issues/5200)) ([0b120ae](https://github.com/material-components/material-components-web/commit/0b120ae))
* **radio:** Fix touch target margins: 0px => 4px. ([#5096](https://github.com/material-components/material-components-web/issues/5096)) ([a48d06e](https://github.com/material-components/material-components-web/commit/a48d06e))
* **ripple:** Add overflow: hidden; to the bounded ripple mixin ([#5173](https://github.com/material-components/material-components-web/issues/5173)) ([996b091](https://github.com/material-components/material-components-web/commit/996b091))
* **ripple:** Always set even num when initial ripple size is ca… ([#5141](https://github.com/material-components/material-components-web/issues/5141)) ([b26ad23](https://github.com/material-components/material-components-web/commit/b26ad23))
* **ripple:** Remove unnecessary overflow: hidden. ([#5191](https://github.com/material-components/material-components-web/issues/5191)) ([5916d18](https://github.com/material-components/material-components-web/commit/5916d18))
* **tabs:** Fix tab img icon styling. ([#5041](https://github.com/material-components/material-components-web/issues/5041)) ([d0e6cd1](https://github.com/material-components/material-components-web/commit/d0e6cd1))
* **text-field:** Do not trigger shake animation when text field is empty ([#5097](https://github.com/material-components/material-components-web/issues/5097)) ([4913db9](https://github.com/material-components/material-components-web/commit/4913db9))
* **text-field:** Fixes input text alignment on IE11 for densed text field ([#5136](https://github.com/material-components/material-components-web/issues/5136)) ([892dd4e](https://github.com/material-components/material-components-web/commit/892dd4e))
* **text-field:** Fixes input text alignment on IE11 for densed… ([#5147](https://github.com/material-components/material-components-web/issues/5147)) ([c8f7693](https://github.com/material-components/material-components-web/commit/c8f7693))
* **text-field:** Updated shape mixins to set density scale ([#5207](https://github.com/material-components/material-components-web/issues/5207)) ([719b57e](https://github.com/material-components/material-components-web/commit/719b57e))
* **touch-target:** Add class to touch target wrapper. ([#5174](https://github.com/material-components/material-components-web/issues/5174)) ([e7799b8](https://github.com/material-components/material-components-web/commit/e7799b8))
* **touch-target:** Add missing dependency - touch target to com… ([#5098](https://github.com/material-components/material-components-web/issues/5098)) ([9306bd0](https://github.com/material-components/material-components-web/commit/9306bd0))


### Code Refactoring

* **button:** Add ripple target as an inner element. ([#4890](https://github.com/material-components/material-components-web/issues/4890)) ([dffefe6](https://github.com/material-components/material-components-web/commit/dffefe6))
* **mdc-fab:** Move Ripple to inner Element. ([#4997](https://github.com/material-components/material-components-web/issues/4997)) ([85b33b5](https://github.com/material-components/material-components-web/commit/85b33b5))
* **select:** Refactor select ([#5113](https://github.com/material-components/material-components-web/issues/5113)) ([db7560e](https://github.com/material-components/material-components-web/commit/db7560e))
* **slider:** Functional slider tick visuals with css background ([#4756](https://github.com/material-components/material-components-web/issues/4756)) ([8f851d9](https://github.com/material-components/material-components-web/commit/8f851d9))


### Features

* **button:** Add support for increased touch target to button. ([#4948](https://github.com/material-components/material-components-web/issues/4948)) ([1d7a2e6](https://github.com/material-components/material-components-web/commit/1d7a2e6))
* **checkbox:** Add disabled state color mixins ([#5167](https://github.com/material-components/material-components-web/issues/5167)) ([01628ef](https://github.com/material-components/material-components-web/commit/01628ef))
* **checkbox:** Add support for 48px touch target ([#5025](https://github.com/material-components/material-components-web/issues/5025)) ([b5685a8](https://github.com/material-components/material-components-web/commit/b5685a8))
* **checkbox:** Move ripple to child node ([#4981](https://github.com/material-components/material-components-web/issues/4981)) ([9712b24](https://github.com/material-components/material-components-web/commit/9712b24))
* **chip:** Add density mixin to chip. ([#5109](https://github.com/material-components/material-components-web/issues/5109)) ([bdf3430](https://github.com/material-components/material-components-web/commit/bdf3430))
* **chips:** Add keyboard navigation ([#4844](https://github.com/material-components/material-components-web/issues/4844)) ([42065fe](https://github.com/material-components/material-components-web/commit/42065fe)), closes [#2259](https://github.com/material-components/material-components-web/issues/2259)
* **chips:** Add setSelectedFromChipset method ([#4872](https://github.com/material-components/material-components-web/issues/4872)) ([283bd55](https://github.com/material-components/material-components-web/commit/283bd55))
* **chips:** Add support for increased touch target to chips. ([#4970](https://github.com/material-components/material-components-web/issues/4970)) ([6aa109d](https://github.com/material-components/material-components-web/commit/6aa109d))
* **chips:** Use index for all chip operations ([#4869](https://github.com/material-components/material-components-web/issues/4869)) ([07078bb](https://github.com/material-components/material-components-web/commit/07078bb))
* **density:** Add density subsystem to components ([#5059](https://github.com/material-components/material-components-web/issues/5059)) ([73a5e4c](https://github.com/material-components/material-components-web/commit/73a5e4c))
* **dialog:** Add dialog mixin for dialogs with increased touch target buttons. ([#5024](https://github.com/material-components/material-components-web/issues/5024)) ([2ef1ddd](https://github.com/material-components/material-components-web/commit/2ef1ddd))
* **icon-button:** Add density mixin to icon button ([#5122](https://github.com/material-components/material-components-web/issues/5122)) ([37d6458](https://github.com/material-components/material-components-web/commit/37d6458))
* **list:** Add density mixin to list ([#5069](https://github.com/material-components/material-components-web/issues/5069)) ([5132f89](https://github.com/material-components/material-components-web/commit/5132f89))
* **list:** Add mixin for disabled text opacity ([#4861](https://github.com/material-components/material-components-web/issues/4861)) ([d68f8a7](https://github.com/material-components/material-components-web/commit/d68f8a7))
* **radio:** Add density mixin to radio ([#5118](https://github.com/material-components/material-components-web/issues/5118)) ([199534d](https://github.com/material-components/material-components-web/commit/199534d))
* **radio:** Add disabled state color mixins ([#5168](https://github.com/material-components/material-components-web/issues/5168)) ([b5c6d66](https://github.com/material-components/material-components-web/commit/b5c6d66))
* **radio:** Add support for 48px touch target ([#5032](https://github.com/material-components/material-components-web/issues/5032)) ([87b0a4c](https://github.com/material-components/material-components-web/commit/87b0a4c))
* **radio:** Move ripple to child element ([#4983](https://github.com/material-components/material-components-web/issues/4983)) ([100ab37](https://github.com/material-components/material-components-web/commit/100ab37))
* **ripple:** Add support for ripple target to mixins. ([#4880](https://github.com/material-components/material-components-web/issues/4880)) ([08dbe69](https://github.com/material-components/material-components-web/commit/08dbe69))
* **snackbar:** Add option for indefinite timeout ([#4998](https://github.com/material-components/material-components-web/issues/4998)) ([4f11851](https://github.com/material-components/material-components-web/commit/4f11851))
* **switch:** Add density support for switch component. ([#5124](https://github.com/material-components/material-components-web/issues/5124)) ([2c793b4](https://github.com/material-components/material-components-web/commit/2c793b4)), closes [#5104](https://github.com/material-components/material-components-web/issues/5104)
* **switch:** add ripple opacity customization mixins ([#5126](https://github.com/material-components/material-components-web/issues/5126)) ([8c0273f](https://github.com/material-components/material-components-web/commit/8c0273f))
* **tab:** Add text transform mixin ([#5144](https://github.com/material-components/material-components-web/issues/5144)) ([22d7ad2](https://github.com/material-components/material-components-web/commit/22d7ad2))
* **tab-bar:** Add a mixin to set scroller animation ([#5172](https://github.com/material-components/material-components-web/issues/5172)) ([d7c938a](https://github.com/material-components/material-components-web/commit/d7c938a))
* **tab-bar:** Add density mixin to tab-bar ([#5070](https://github.com/material-components/material-components-web/issues/5070)) ([45dc002](https://github.com/material-components/material-components-web/commit/45dc002))
* **tab-scroller:** Add incrementScrollImmediate to bypass animation ([#5184](https://github.com/material-components/material-components-web/issues/5184)) ([2b878b3](https://github.com/material-components/material-components-web/commit/2b878b3)), closes [#5123](https://github.com/material-components/material-components-web/issues/5123)
* **tab-scroller:** Mixin for scroll transition ([#5154](https://github.com/material-components/material-components-web/issues/5154)) ([efda83d](https://github.com/material-components/material-components-web/commit/efda83d))
* **text-field:** Add density mixin to text field variants ([#5066](https://github.com/material-components/material-components-web/issues/5066)) ([a12101d](https://github.com/material-components/material-components-web/commit/a12101d))
* **text-field:** Center align inner elements for dynamic height ([#4990](https://github.com/material-components/material-components-web/issues/4990)) ([4d94b22](https://github.com/material-components/material-components-web/commit/4d94b22))
* **touch-target:** Add touch target mixins. ([#4940](https://github.com/material-components/material-components-web/issues/4940)) ([b2e0fea](https://github.com/material-components/material-components-web/commit/b2e0fea))


### BREAKING CHANGES

* **checkbox:** `mdc-checkbox-ink-color` mixin now only applies to enabled checkboxes
* **chips:** Chips markup, adapters, foundations, and events have changed.
* **select:** In MDCMenu and MDCMenuSurface, `hoistMenuToBody` adapter method removed.  In MDCSelect, HTML structure changed: the select anchor is now wrapped in a parent element, and the anchor's sibling is the select menu. Support for native select removed. Support added for select with no label. MDCSelectAdapter methods removed: `getValue`, `setValue`, `isMenuOpen`, `setSelectedIndex`, `checkValidity`, `setValid`, `toggleClassAtIndex`. MDCSelectAdapter methods added: `hasLabel`, `getSelectedMenuItem`, `setSelectedText`, `isSelectedTextFocused`, `get/setSelectedTextAttr`, `getAnchorElement`, `setMenuAnchorElement`, `setMenuAnchorCorner`, `setMenuWrapFocus`, `set/removeAttributeAtIndex`, `focusMenuItemAtIndex`, `getMenuItemValues`, `getMenuItemCount`, `getMenuItemCount`, `getMenuItemAttr`, `getMenuItemTextAtIndex`, `add/removeClassAtIndex`. MDCSelectFoundation `setValue` method removed; `getDisabled`, `handleMenuItemAction`, `getSelectedIndex`, `get/setRequired`, `init` added.
* **radio:** In Checkbox, Renamed sass variables `$mdc-radio-touch-area` => `$mdc-radio-ripple-size` & `$mdc-radio-ui-size` => `$mdc-radio-icon-size` to be consistent with checkbox. Also, removed `$mdc-radio-ui-pct` sass variable.
* **switch:** Renames switch variables $mdc-switch-tap-target-size => $mdc-switch-ripple-size, removes $mdc-switch-tap-target-initial-position and $mdc-switch-native-control-width.
* **list:** New adapter method listItemAtIndexHasClass
* **list:** Renamed mixin `mdc-list-item-shape-radius()` => `mdc-list-single-line-shape-radius()`
* **linear-progress:** MDCLinearProgressAdapter adapter has new `forceLayout` method
* **text-field:** Removed sass variable in notched outline - `$mdc-notched-outline-transition-duration`.
* **mdc-fab:** This changes the structure of the FAB element by moving the ripple from the outer element to an inner mdc-fab__ripple element.

  OLD

  ```html
  <button class="mdc-fab" aria-label="Favorite">
    <span class="mdc-fab__icon material-icons">favorite</span>
  </button>
  ```

  NEW

  ```html
  <button class="mdc-fab" aria-label="Favorite">
    <div class="mdc-fab__ripple"></div>
    <span class="mdc-fab__icon material-icons">favorite</span>
  </button>
  ```

* **radio:** Ripple has been moved to a child element. See readme for updates.
* **slider:** remove adapter methods `appendTrackMarkers`, `removeTrackMarkers `, `setLastTrackMarkersStyleProperty `, and add adapter method `setTrackMarkers`.
* **button:** This changes the structure of the button element by moving the ripple from the outer <button> element to an inner `mdc-button__ripple` element.

  OLD

  ```html
  <button class="mdc-button">
    <span class="mdc-button__label">Hello World</span>
  </button>
  ```

  NEW

  ```html
  <button class="mdc-button">
    <div class="mdc-button__ripple"></div>
    <span class="mdc-button__label">Hello World</span>
  </button>
  ```
* **chips:** MDCChipSetAdapter#removeChip has been replaced with MDCChipSetAdapter#removeChipAtIndex. MDCChipSetAdapter#setSelected has been replaced with MDCChipSetAdapter#selectChipAtIndex
* **density:** Renamed sass mixins & variables in MDC Data Table - `mdc-data-table-header-row-height` => `mdc-data-table-header-cell-height` & `mdc-data-table-row-height` => `mdc-data-table-cell-height`. Also removed `mdc-button--dense` variant, use button's density mixin instead.

**Note: For older changes, see the [changelog archive](CHANGELOG_ARCHIVE.md).**
