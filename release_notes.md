###In Development
  -

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.11.3...master)

###v1.11.3 - 2014-02-18
  - [#93](https://github.com/MehdiK/Humanizer/pull/93): added non-generic DehumanizeTo for Enums unknown at compile time

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.10.1...v1.11.3)

###v1.10.1 - 2014-02-15
  - [#89](https://github.com/MehdiK/Humanizer/pull/89): added `ToRoman` and `FromRoman` extensions
  - [#82](https://github.com/MehdiK/Humanizer/pull/82): fixed Greek locale code

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.9.1...v1.10.1)

###v1.9.1 - 2014-02-12
  - [#78](https://github.com/MehdiK/Humanizer/pull/78): added support for billions to `ToWords`

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.8.1...v1.9.1)

###v1.8.16 - 2014-02-12
  - [#81](https://github.com/MehdiK/Humanizer/pull/81): fixed issue with localised methods returning null in Windows Store apps
  - Created [Humanizr.net](http://humanizr.net) website as GitHub pages

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.8.1...v1.8.16)

###v1.8.1 - 2014-02-04
  - [#73](https://github.com/MehdiK/Humanizer/pull/73): added `ToWords` implementation for Arabic

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.7.1...v1.8.1)

###v1.7.1 - 2014-02-31
  - [#68](https://github.com/MehdiK/Humanizer/pull/68): `DateTime.Humanize()` now supports future dates

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.6.1...v1.7.1)

###v1.6.1 - 2014-01-27
  - [#69](https://github.com/MehdiK/Humanizer/pull/69): changed the return type of `DehumanizeTo<TTargetEnum>` to `TTargetEnum`

####Potential breaking change
The return type of `DehumanizeTo<TTargetEnum>` was changed from `Enum` to `TTargetEnum` to make the API a lot easier to work with.
That also potentially means that your calls to the old method may be broken.
Depending on how you were using the method you might have to either drop the now redundant cast to `TTargetEnum` in your code, or 
fix it based on your requirements.

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.5.1...v1.6.1)

###v1.5.1 - 2014-01-23
  - [#65](https://github.com/MehdiK/Humanizer/pull/65): added precision to `TimeSpan.Humanize`

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.4.1...v1.5.1)

###v1.4.1 - 2014-01-20
  - [#62](https://github.com/MehdiK/Humanizer/pull/62): added `ShowQuantityAs` parameter to `ToQuantity`

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.3.1...v1.4.1)

###v1.3.1 - 2014-14-01
  - [#51](https://github.com/MehdiK/Humanizer/pull/51): added Spanish translation for `DateTime.Humanize`
  - [#52](https://github.com/MehdiK/Humanizer/pull/52): added Arabic translation for `DateTime.Humanize`
  - [#53](https://github.com/MehdiK/Humanizer/pull/53): added `Hyphenate` as an overload for `Dasherize`
  - [#54](https://github.com/MehdiK/Humanizer/pull/54): added Portuguese translation for `DateTime.Humanize`
  - [#55](https://github.com/MehdiK/Humanizer/pull/55): added Arabic translation for `TimeSpan.Humanize`

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.1.0...v1.3.1)

###v1.1.0 - 2014-01-01
  - [#37](https://github.com/MehdiK/Humanizer/pull/37): added `ToQuantity` method
  - [#43](https://github.com/MehdiK/Humanizer/pull/43): 
    - added `Plurality` enum
    - can call `Singularize` on singular and `Pluralize` on plural words
    - `ToQuantity` can be called on words with unknown plurality

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.0.29...v1.1.0)

###v1.0.29 - 2013-12-25
  - [#26](https://github.com/MehdiK/Humanizer/pull/26): added Norwegian (nb-NO) localization for `DateTime.Humanize()`
  - [#33](https://github.com/MehdiK/Humanizer/pull/33): 
    - changed to Portable Class Library with support for .Net 4+, SilverLight 5, Windows Phone 8 and Win Store applications
    - symbols nuget package is published so you can step through Humanizer code while debugging your code

[Commits](https://github.com/MehdiK/Humanizer/compare/v1.0.0...v1.0.29)

###v1.0.0 - 2013-11-10
No release history before this point: check out http://www.mehdi-khalili.com/humanizer-v1 for the feature-set at V1
