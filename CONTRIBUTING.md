# Contribute to astr-i18n

Thank you for joining the i18n project for ASTR! We appreciate your effort on bringing ASTR to more people. 

## Resources

Before you start translating strings, here are some resources you may need in translation:

- The [astr-i18n](https://hosted.weblate.org/projects/astr-i18n/astr/) project weblate portal: This is where you summit your translation. DO NOT directly make pull request on this repository. If you find key missing or anything wrong, please summit a issue in this repo.
- The [Message Format Syntax](https://vue-i18n.intlify.dev/guide/essentials/syntax.html) of Vue-i18n: This contain some i18n syntax being used in ASTR.

## Translation Rules

There are some rules that required translators to follow:

1. DO NOT PUT POLITICAL, RACIST AND ANY ILLEGAL CONTENT IN TRANSLATIONS.
2. The root language of astr-18n is `en_US`, if there are missing key in other language it will fallback to use `en_US`. Please always use `en_US` as reference. 
3. Strings containing `@:` are [Linked Messages](https://vue-i18n.intlify.dev/guide/essentials/syntax.html#linked-messages), please copy the same string to targeting language.
4. Strings containing `{...}` are [Interpolated Messages](https://vue-i18n.intlify.dev/guide/essentials/syntax.html#interpolations), you are able to move the `{...}` to correct places and DO NOT modifiy anything in bracket.
5. Some special chars like `{ } @ $ |` required [Literal interpolation](https://vue-i18n.intlify.dev/guide/essentials/syntax.html#literal-interpolation), please warp them into `{'...'}`, for example: `xxx@abc.com` -> `xxx{'@'}abc.com`.

If you have any problem or feedback related to translation, please summit your issue in this repository. We are looking forward to your contribution.






