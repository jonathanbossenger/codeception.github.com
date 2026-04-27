---
layout: page
title: Codeception Changelog
---

<div class="alert alert-warning">Download specific version at <a href="/builds">builds page</a></div>

# Changelog



### lib-innerbrowser 4.1.0: 4.1.0

Released by [![](https://avatars.githubusercontent.com/u/20659830?v=4&s=16){:height="16" width="16"} W0rma](https://github.com/W0rma) on 2026/02/18 06:25:58 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



## What's Changed
* chore(deps): add support for phpunit 13 in https://github.com/Codeception/lib-innerbrowser/pull/85
* chore(ci): remove obsolete workaround for php > 8.5 in https://github.com/Codeception/lib-innerbrowser/pull/86


**Full Changelog**: https://github.com/Codeception/lib-innerbrowser/compare/4.0.8...4.1.0


### Codeception 5.3.5: 5.3.5

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2026/02/18 06:22:46 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* PHP 8.5: Avoid accessing deprecated $http_response_header by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6924
* Add support for PHPUnit 13 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6925


**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.3.4...5.3.5


### lib-web 2.1.0: 2.1.0

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2026/02/06 15:23:02 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



# [2.1.0](https://github.com/Codeception/lib-web/compare/2.0.1...2.1.0) (2026-02-06)


### Features

* add support for phpunit 13 ([[#23](https://github.com/Codeception/lib-web/issues/23)](https://github.com/Codeception/lib-web/issues/23)) ([a030a3a](https://github.com/Codeception/lib-web/commit/a030a3a22fc8e856b5957086794ed5403c7992d9))






### module-phpbrowser 4.0.0: 4.0.0

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2026/01/23 13:25:25 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



# [4.0.0](https://github.com/Codeception/module-phpbrowser/compare/3.0.2...4.0.0) (2026-01-23)


### Features

* allow symfony 8 ([0c65e95](https://github.com/Codeception/module-phpbrowser/commit/0c65e956c1b355d0edb5b4c279265255ac4ac3f6))


### BREAKING CHANGES

* The native object return type was added to the doRequest() method of the Guzzle connector.
That might break code extending from this class.






### Codeception 5.3.4: 5.3.4

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2026/01/14 12:07:18 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* Use attributes syntax in gherkin:snippets by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6917
* PHP 8.5: Fix usage of deprecated $http_response_header by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6919
* Do not expect the register_argc_argv ini setting in cli for php >= 8.5 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6921


**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.3.3...5.3.4


### module-yii2 v2.0.5: v2.0.5

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2025/12/18 19:07:02 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



## What's Changed
* Fix missing recreateComponents in configureClient() breaks tests after v2 upgrade by **[Eseperio](https://github.com/Eseperio)** in https://github.com/Codeception/module-yii2/pull/143

## New Contributors
* **[Eseperio](https://github.com/Eseperio)** made their first contribution in https://github.com/Codeception/module-yii2/pull/143

**Full Changelog**: https://github.com/Codeception/module-yii2/compare/v2.0.4...v2.0.5


### Codeception 5.3.3: 5.3.3

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/12/17 15:19:44 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* Fix empty data provider case by **[joester89](https://github.com/joester89)** in https://github.com/Codeception/Codeception/pull/6866
* Fix Composer `branch-alias` for feature releases 5.3.x by **[llaville](https://github.com/llaville)** in https://github.com/Codeception/Codeception/pull/6879
* Add guard before deleting directory by **[fabacino](https://github.com/fabacino)** in https://github.com/Codeception/Codeception/pull/6877
* Remove Reflection*::setAccessible() usage by **[Disservin](https://github.com/Disservin)** in https://github.com/Codeception/Codeception/pull/6869
* Update RunProcess.php: Removing MailCatcher by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/Codeception/pull/6815
* update readme links by **[Arhell](https://github.com/Arhell)** in https://github.com/Codeception/Codeception/pull/6882
* chore: allow installation of lib-asserts v3 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6887
* Replace backtick with shell_exec to prevent php8.5 deprecation by **[craig-mcmahon](https://github.com/craig-mcmahon)** in https://github.com/Codeception/Codeception/pull/6892
* Readme updated: Contribution link fixed by **[Sunsetboy](https://github.com/Sunsetboy)** in https://github.com/Codeception/Codeception/pull/6895
* Update Cest.php: Minor rewording by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/Codeception/pull/6897
* Update composer.json: Updating description by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/Codeception/pull/6896
* Fix test for lib-asserts v3 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6899
* Avoid declaring nullable parameter implicitly in BuildCest by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6900
* Add support for never return type in DryRun by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6901
* Fix ci when using behat/gherkin v4.15 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6902
* Test against PHP 8.5 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6903
* CI: fix module-phpbrowser test in experimental build by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6904
* Bump actions/checkout from 3 to 6 by **[dependabot](https://github.com/dependabot)**[bot] in https://github.com/Codeception/Codeception/pull/6893
* Remove obsolete version check in tests by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6907
* Add support for iterable return type in DryRun by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6906
* Add support for symfony 8 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6898
* Use upper-cased suite names by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6909
* Update readme.md: Cleaning up Installation by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/Codeception/pull/6911
* Update Run.php: Adding `codecept run -g failed` by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/Codeception/pull/6910

## New Contributors
* **[joester89](https://github.com/joester89)** made their first contribution in https://github.com/Codeception/Codeception/pull/6866
* **[llaville](https://github.com/llaville)** made their first contribution in https://github.com/Codeception/Codeception/pull/6879
* **[Disservin](https://github.com/Disservin)** made their first contribution in https://github.com/Codeception/Codeception/pull/6869
* **[Sunsetboy](https://github.com/Sunsetboy)** made their first contribution in https://github.com/Codeception/Codeception/pull/6895
* **[dependabot](https://github.com/dependabot)**[bot] made their first contribution in https://github.com/Codeception/Codeception/pull/6893

**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.3.2...5.3.3


### lib-innerbrowser 4.0.8: 4.0.8

Released by [![](https://avatars.githubusercontent.com/u/20659830?v=4&s=16){:height="16" width="16"} W0rma](https://github.com/W0rma) on 2025/12/15 13:16:59 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



## What's Changed
* Fix PHP 8.5 deprecation warning in https://github.com/Codeception/lib-innerbrowser/pull/81
* Fix use statements (docs) in https://github.com/Codeception/lib-innerbrowser/pull/83
* Fix type error for element without form in https://github.com/Codeception/lib-innerbrowser/pull/82
* Allow symfony 8 in https://github.com/Codeception/lib-innerbrowser/pull/84


**Full Changelog**: https://github.com/Codeception/lib-innerbrowser/compare/4.0.7...4.0.8


### lib-xml 1.1.1: 1.1.1

Released by [![](https://avatars.githubusercontent.com/u/20659830?v=4&s=16){:height="16" width="16"} W0rma](https://github.com/W0rma) on 2025/12/05 14:23:54 / [Repository](https://github.com/Codeception/lib-xml)   / [Releases](https://github.com/Codeception/lib-xml/releases)



## What's Changed
* Test against PHP 8.5 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-xml/pull/9
* Allow symfony/css-selector v8 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-xml/pull/10


**Full Changelog**: https://github.com/Codeception/lib-xml/compare/1.1.0...1.1.1


### lib-web 2.0.1: 2.0.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/11/27 21:15:41 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



## What's Changed
* Test against PHP 8.5 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-web/pull/19
* Allow Symfony 8 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-web/pull/20
* Update Web.php: Added hints that `seeCurrentUrlEquals` etc. are only … by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/lib-web/pull/18


**Full Changelog**: https://github.com/Codeception/lib-web/compare/2.0.0...2.0.1


### module-doctrine 3.3.0: 3.3.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/11/13 08:09:32 / [Repository](https://github.com/Codeception/module-doctrine)   / [Releases](https://github.com/Codeception/module-doctrine/releases)



## What's Changed
* Update Doctrine.php: Typo by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/module-doctrine/pull/43
* Remove Reflection*::setAccessible() calls by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/44
* Enable native lazy objects if possible to fix the CI when using symfony 8 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/45
* Fix deprecation warnings in doctrine/collections:2.4 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/46
* Drop PHP 8.1 + test against PHP 8.5 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/48
* Fix test with object id by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/47


**Full Changelog**: https://github.com/Codeception/module-doctrine/compare/3.2.0...3.3.0


### lib-innerbrowser 4.0.7: 4.0.7

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/10/23 05:53:45 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



## What's Changed
* Chore: allow codeception/lib-web v2 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-innerbrowser/pull/80


**Full Changelog**: https://github.com/Codeception/lib-innerbrowser/compare/4.0.6...4.0.7


### lib-xml 1.1.0: 1.1.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/09/22 05:26:43 / [Repository](https://github.com/Codeception/lib-xml)   / [Releases](https://github.com/Codeception/lib-xml/releases)



## What's Changed
* Test against PHP 8.3 + 8.4, drop PHP 8.0 + 8.1 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-xml/pull/5
* Add support for codeception/lib-web v2 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-xml/pull/8

**Full Changelog**: https://github.com/Codeception/lib-xml/compare/1.0.3...1.1.0


### lib-web 2.0.0: 2.0.0

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2025/09/04 11:39:54 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



# [2.0.0](https://github.com/Codeception/lib-web/compare/1.0.7...2.0.0) (2025-09-04)


### Bug Fixes

* **ci:** correct branch name ([f901da6](https://github.com/Codeception/lib-web/commit/f901da66668ddaeb8bb9dd2b1e8b19dd83e96b99))






### module-phpbrowser 3.0.2: 3.0.2

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2025/09/04 10:46:47 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



## [3.0.2](https://github.com/Codeception/module-phpbrowser/compare/3.0.1...3.0.2) (2025-09-04)


### Bug Fixes

* Merge pull request [[#39](https://github.com/Codeception/module-phpbrowser/issues/39)](https://github.com/Codeception/module-phpbrowser/issues/39) from leobedrosian/fix-multipart-format-nested-arrays ([ff2ecb3](https://github.com/Codeception/module-phpbrowser/commit/ff2ecb354e5a48f80a492595ecb588b125fc9013))
* use local server in tests httpstat.us is down ([66fc8c5](https://github.com/Codeception/module-phpbrowser/commit/66fc8c5599a0191d31b7c9dd4618fe751ed92ea4))






### module-yii2 v2.0.4: v2.0.4

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2025/05/31 06:53:23 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



## [2.0.4](https://github.com/Codeception/module-yii2/compare/v2.0.3...v2.0.4) (2025-05-31)


### Bug Fixes

* fixes [[#131](https://github.com/Codeception/module-yii2/issues/131)](https://github.com/Codeception/module-yii2/issues/131) yiilogger may not be initialized in _failed ([b480bf1](https://github.com/Codeception/module-yii2/commit/b480bf18befdc8ede138f2f3a6b09a8989d11cb9))






### Codeception 5.3.2: 5.3.2

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/05/26 07:51:41 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* Rollback getSubscribedEvents Extension refactor by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6862

**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.3.1...5.3.2


### Codeception 5.3.1: 5.3.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/05/13 23:25:43 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* Issue 6857: Upddate Actor::__call() to have return type 'mixed' by **[troy-rudolph](https://github.com/troy-rudolph)** in https://github.com/Codeception/Codeception/pull/6858
* Fix auto-injection of the tester property by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6856

## New Contributors
* **[troy-rudolph](https://github.com/troy-rudolph)** made their first contribution in https://github.com/Codeception/Codeception/pull/6858

**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.3.0...5.3.1


### Codeception 5.2.2: 5.2.2

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/05/07 12:49:57 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* 5.2: Fix loading keywords in behat/gherkin v4.12 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6855


**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.2.1...5.2.2


### Codeception 5.3.0: 5.3.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/05/06 19:04:29 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* Update readme.md by **[rossaddison](https://github.com/rossaddison)** in https://github.com/Codeception/Codeception/pull/6834
* Fix loading keywords in behat/gherkin v4.12 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6839
* Update Scenario.php: Adding default value to `current()` by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/Codeception/pull/6798
* Simplify Step classes by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6842
* Simplify reporter classes by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6803
* Simplify Subscriber classes by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6843
* Fix AssertsTest CI pipeline by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6847
* Simplify Test classes by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6845
* Simplify Template classes by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6844
* Simplify Util classes by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6846
* Simplify src root classes by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6849
* Remove PHP 8.1 Support by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6848
* Migrate commands to use AsCommand attribute by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6850
* Add PHPStan by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/Codeception/pull/6851

## New Contributors
* **[rossaddison](https://github.com/rossaddison)** made their first contribution in https://github.com/Codeception/Codeception/pull/6834

**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.2.1...5.3.0


### module-doctrine 3.2.0: 3.2.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/04/25 05:14:21 / [Repository](https://github.com/Codeception/module-doctrine)   / [Releases](https://github.com/Codeception/module-doctrine/releases)



## What's Changed
* Update Doctrine.php: Adding upgrade instructions by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/module-doctrine/pull/29
* Declare nullable parameter types explicitly by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/31
* Fix support for doctrine/dbal v2 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/32
* PHP 8.4: Fix E_STRICT deprecation by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/module-doctrine/pull/34

**Full Changelog**: https://github.com/Codeception/module-doctrine/compare/3.1.0...3.2.0


### module-yii2 v2.0.3: v2.0.3

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2025/04/01 13:18:15 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



## [2.0.3](https://github.com/Codeception/module-yii2/compare/v2.0.2...v2.0.3) (2025-04-01)


### Bug Fixes

* server params refactor broke  format ([8c789c9](https://github.com/Codeception/module-yii2/commit/8c789c94c1eb8c4ae0b5873c3a17ea9fda31994d))






### module-yii2 v2.0.2: v2.0.2

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2025/03/02 16:01:43 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



## [2.0.2](https://github.com/Codeception/module-yii2/compare/v2.0.1...v2.0.2) (2025-03-02)


### Bug Fixes

* improve exception handling and code consistency ([d72f144](https://github.com/Codeception/module-yii2/commit/d72f1446146bed998de2c2df9e6f2da3228883c8))






### module-yii2 v2.0.1: v2.0.1

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2025/02/27 08:26:23 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



## [2.0.1](https://github.com/Codeception/module-yii2/compare/v2.0.0...v2.0.1) (2025-02-27)


### Bug Fixes

* check using isset instead of !== null for possibly non-existent property ([e30e595](https://github.com/Codeception/module-yii2/commit/e30e595d19ac059305dd2ff78ceb2df2c0ee621f))






### module-yii2 v2.0.0: v2.0.0

Released by [![](https://avatars.githubusercontent.com/in/15368?v=4&s=16){:height="16" width="16"} github-actions[bot]](https://github.com/apps/github-actions) on 2025/02/26 15:02:27 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



# [2.0.0](https://github.com/Codeception/module-yii2/compare/v1.1.12...v2.0.0) (2025-02-26)


### Bug Fixes

* call fixtures method ([5ff8868](https://github.com/Codeception/module-yii2/commit/5ff88682d0a9e2c0d8044bca04b85009ceb1c81e))
* **ci:** github token name ([e045ef5](https://github.com/Codeception/module-yii2/commit/e045ef59bff449c4ba92ee5ba4eb2a670b5f6b4f))
* **ci:** use dry run for automated release ([d8111f0](https://github.com/Codeception/module-yii2/commit/d8111f00cb5e1fe5395f0b255e53ff5eb31bba56))
* **cs:** add rules for docblocks ([0d98125](https://github.com/Codeception/module-yii2/commit/0d981258ef962f1bd3cbe948bba29221631a272f))
* **cs:** indent in phpdoc ([97610ed](https://github.com/Codeception/module-yii2/commit/97610ed08b341ab33c37ba4b9d49409eaef51438))
* dont add mails that were not sent ([7adc7f7](https://github.com/Codeception/module-yii2/commit/7adc7f7bda798139818853569c9b1d3fd3d5d9cf))
* load mailmethod config ([d536116](https://github.com/Codeception/module-yii2/commit/d53611637e9ce5291bd13ea1a5704f60828cd12c))
* phpstan types ([ab5ccc5](https://github.com/Codeception/module-yii2/commit/ab5ccc555c1907b7d19253a6435433f35bb76fe5))
* recreate baseline ([f9131bd](https://github.com/Codeception/module-yii2/commit/f9131bdf8f9b59192f20152a90a8c716c7fa8157))
* remove localeurls dependency and test case ([3bba227](https://github.com/Codeception/module-yii2/commit/3bba2271fb23ea145ff3dab666044a07599ac5c7))
* remove unused dep ([e763dee](https://github.com/Codeception/module-yii2/commit/e763dee616f1b75da68e8fe4a940ce8a99292ae2))
* run phpstan after codeception build ([9cff2c0](https://github.com/Codeception/module-yii2/commit/9cff2c0549fd380e5ad78e5537945acd97d9eae6))
* **sa:** use Assert::fail so that phpstan understand code doesn't continue ([117117e](https://github.com/Codeception/module-yii2/commit/117117e6cb6c4b5030b4072c5de34660973a1661))
* use runtimeexception when applicable ([4df941f](https://github.com/Codeception/module-yii2/commit/4df941fb8e49179eff1c5cec0d011843c71e5177))
* variable rename ([619fb2d](https://github.com/Codeception/module-yii2/commit/619fb2d13074183a8d7b52b443348e075825292d))


### Features

* allow mails to be intercepted using events ([dca7c44](https://github.com/Codeception/module-yii2/commit/dca7c446877d1e4143db9deb86a499df40af59ef))
* drop php8.1 php8.2 ([0b08f64](https://github.com/Codeception/module-yii2/commit/0b08f6481a93807dd7e9ce8b8ab22e937b25e923))
* Merge pull request [[#119](https://github.com/Codeception/module-yii2/issues/119)](https://github.com/Codeception/module-yii2/issues/119) from TavoNiievez/php_features ([49393a4](https://github.com/Codeception/module-yii2/commit/49393a454bcfaa323fd5cbdd3b51b3f01dfeb063))






### lib-web 1.0.7: 1.0.7

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2025/02/23 14:06:56 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



* Declare nullable parameter types explicitly for PHP 8.4 compatibility by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-web/pull/12
* Test against PHP 8.4 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-web/pull/13
* Support PHPUnit 12 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-web/pull/14



### Codeception 5.2.1: 5.2.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/02/20 15:01:00 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* Support PHPUnit 12 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/Codeception/pull/6826
* Fix missing absolute path resolving in ParamsLoader by **[garvinhicking](https://github.com/garvinhicking)** in https://github.com/Codeception/Codeception/pull/6828

**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.2.0...5.2.1


### Codeception 5.2.0: 5.2.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2025/02/16 20:31:08 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* Fix FAIL message color highlighting by **[antonvolokha](https://github.com/antonvolokha)** in [#6754](https://github.com/Codeception/Codeception/issues/6754)
* Update the codebase to PHP 8.1 by **[TavoNiievez](https://github.com/TavoNiievez)** in [#6747](https://github.com/Codeception/Codeception/issues/6747)
* generate:cest: Adding `declare(strict_types=1);` and return type `void` to generated files by **[ThomasLandauer](https://github.com/ThomasLandauer)** in [#6736](https://github.com/Codeception/Codeception/issues/6736)
* Declare nullable parameter types explicitly by **[W0rma](https://github.com/W0rma)** in [#6774](https://github.com/Codeception/Codeception/issues/6774) , [#6775](https://github.com/Codeception/Codeception/issues/6775)
* chore: Included githubactions in the dependabot config ([#6471](https://github.com/Codeception/Codeception/issues/6471)) by **[SamMousa](https://github.com/SamMousa)** in [#6783](https://github.com/Codeception/Codeception/issues/6783)
* Added new option --disable-coverage-php to skip coverage.serialized report by **[adrenalinkin](https://github.com/adrenalinkin)** in [#6761](https://github.com/Codeception/Codeception/issues/6761)
* chore: add branch alias for main to fix composer install with dev deps by **[SamMousa](https://github.com/SamMousa)** in [#6787](https://github.com/Codeception/Codeception/issues/6787)
* chore(ci): prevent test CI running twice on PR branches by **[SamMousa](https://github.com/SamMousa)** in [#6788](https://github.com/Codeception/Codeception/issues/6788)
* Simplify classes by **[TavoNiievez](https://github.com/TavoNiievez)** in [#6767](https://github.com/Codeception/Codeception/issues/6767) , [#6750](https://github.com/Codeception/Codeception/issues/6750) , [#6764](https://github.com/Codeception/Codeception/issues/6764)
* PHP 8.4: `E_STRICT` deprecation by **[W0rma](https://github.com/W0rma)** in [#6802](https://github.com/Codeception/Codeception/issues/6802)
* Fix PHP 8.4 deprecation. by **[kagg-design](https://github.com/kagg-design)** in [#6811](https://github.com/Codeception/Codeception/issues/6811)
* Fix test suite names in bootstrap command by **[W0rma](https://github.com/W0rma)** in [#6813](https://github.com/Codeception/Codeception/issues/6813)
* Docs (minor) by **[ThomasLandauer](https://github.com/ThomasLandauer)** in [#6804](https://github.com/Codeception/Codeception/issues/6804) , [#6805](https://github.com/Codeception/Codeception/issues/6805) , [#6806](https://github.com/Codeception/Codeception/issues/6806) , 6807 , [#6792](https://github.com/Codeception/Codeception/issues/6792) , [#6810](https://github.com/Codeception/Codeception/issues/6810) , [#6751](https://github.com/Codeception/Codeception/issues/6751) , [#6744](https://github.com/Codeception/Codeception/issues/6744)

## New Contributors
* **[antonvolokha](https://github.com/antonvolokha)** made their first contribution in https://github.com/Codeception/Codeception/pull/6754
* **[adrenalinkin](https://github.com/adrenalinkin)** made their first contribution in https://github.com/Codeception/Codeception/pull/6761
* **[kagg-design](https://github.com/kagg-design)** made their first contribution in https://github.com/Codeception/Codeception/pull/6811

**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.1.2...5.2.0


### lib-innerbrowser 4.0.6: 4.0.6

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2025/02/14 07:04:31 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



## What's Changed
* Support PHPUnit 12 by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-innerbrowser/pull/77
* PHP 8.4: Fix E_STRICT deprecation by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-innerbrowser/pull/74


**Full Changelog**: https://github.com/Codeception/lib-innerbrowser/compare/4.0.5...4.0.6


### module-yii2 1.1.12: 1.1.12

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2024/12/09 14:36:21 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- Un-finalized module class (@samdark)


### module-yii2 1.1.11: 1.1.11

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2024/12/08 10:21:37 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- Fix PHP 8.4 deprecation warnings (@W0rma)
- Fix broken `amLoggedInAs()` (@warkadiuszz)
- Improved typing (@SamMousa)


### lib-innerbrowser 4.0.5: 4.0.5

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/09/13 05:15:37 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Fix name of unsetHttpHeader method [#71](https://github.com/Codeception/lib-innerbrowser/issues/71)


### lib-innerbrowser 4.0.4: 4.0.4

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/09/13 05:14:55 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Declare nullable parameter types explicitly by **[W0rma](https://github.com/W0rma)** in https://github.com/Codeception/lib-innerbrowser/pull/70
* InnerBrowser.php: Deprecate `deleteHeader` in favor of `unsetHeader` by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/lib-innerbrowser/pull/69


### Codeception 5.1.2: 5.1.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/03/07 07:22:27 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Prevent unrelated error from being displayed if a scenario step has failed by **[craig-mcmahon](https://github.com/craig-mcmahon)** in [#6743](https://github.com/Codeception/Codeception/issues/6743)
* Replace Laravel5 with Laravel module in module installation suggestion by **[W0rma](https://github.com/W0rma)** in [#6742](https://github.com/Codeception/Codeception/issues/6742)


### Codeception 5.1.1: 5.1.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/02/23 21:53:22 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Reimplemented coverage:exclude option for PHPUnit 11 in [#6739](https://github.com/Codeception/Codeception/issues/6739)
* Improved output of Bootstrap command  by **[ThomasLandauer](https://github.com/ThomasLandauer)** in [#6735](https://github.com/Codeception/Codeception/issues/6735)


### module-doctrine 3.1.0: 3.1.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2024/02/17 22:38:06 / [Repository](https://github.com/Codeception/module-doctrine)   / [Releases](https://github.com/Codeception/module-doctrine/releases)



## What's Changed
* Support doctrine/orm v3 + doctrine/dbal v4 by **[W0rma](https://github.com/W0rma)** and **[Victor-Truhanovich](https://github.com/Victor-Truhanovich)** in https://github.com/Codeception/module-doctrine/pull/26
* Test against PHP 8.2 + 8.3 by **[W0rma](https://github.com/W0rma)**
* Remove version number from the module name by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/module-doctrine/pull/28



### lib-xml 1.0.3: 1.0.3

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/02/06 21:06:24 / [Repository](https://github.com/Codeception/lib-xml)   / [Releases](https://github.com/Codeception/lib-xml/releases)



* Removed dependency on PHPUnit


### lib-web 1.0.6: 1.0.6

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/02/06 20:50:54 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



* Support PHPUnit 11 by **[Naktibalda](https://github.com/Naktibalda)** in https://github.com/Codeception/lib-web/pull/11
* Adding details to `grabAttributeFrom()` by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/lib-web/pull/10



### Codeception 5.1.0: 5.1.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/02/04 13:52:44 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Support PHPUnit 11

Note: PHPUnit 11 does not support excluding files from code coverage report


### lib-innerbrowser 4.0.3: 4.0.3

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/02/02 20:37:41 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Support PHPUnit 11 by **[Naktibalda](https://github.com/Naktibalda)** in https://github.com/Codeception/lib-innerbrowser/pull/67


### lib-web 1.0.5: 1.0.5

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2024/01/13 11:56:59 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



* Fixing Markdown Code Syntax by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/lib-web/pull/9


### module-yii2 1.1.10: 1.1.10

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2024/01/10 05:57:11 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- [#93](https://github.com/Codeception/module-yii2/issues/93): Fix symfony/browser-kit incompatibility (@jafaripur)
- [#91](https://github.com/Codeception/module-yii2/issues/91): Fix parallel sessions with `$I->haveFriend()` when no session is active (@michaelarnauts)


### Codeception 5.0.13: 5.0.13

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/12/22 19:46:56 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Add actor to Cest tests dataProviders by **[weeg](https://github.com/weeg)** in [#6696](https://github.com/Codeception/Codeception/issues/6696)
* Support symfony 7 by **[W0rma](https://github.com/W0rma)** in [#6723](https://github.com/Codeception/Codeception/issues/6723)
* Avoid infinite loop while waiting for all running tests to finish by **[MarcelBolten](https://github.com/MarcelBolten)** in [#6710](https://github.com/Codeception/Codeception/issues/6710)
* Add missing "Attribute::IS_REPEATABLE" to DataProvider attribute by **[Fahl-Design](https://github.com/Fahl-Design)** in [#6715](https://github.com/Codeception/Codeception/issues/6715)
* Support binary data intest examples by **[pongee](https://github.com/pongee)** in [#6708](https://github.com/Codeception/Codeception/issues/6708)
* Improve rendering of $I->assertThat step by **[jtheuerkauf](https://github.com/jtheuerkauf)** in [#6719](https://github.com/Codeception/Codeception/issues/6719)


### module-phpbrowser 3.0.1: 3.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/12/08 19:46:06 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



* Support for symfony/browser-kit v7



### lib-xml 1.0.2: 1.0.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/12/08 19:33:31 / [Repository](https://github.com/Codeception/lib-xml)   / [Releases](https://github.com/Codeception/lib-xml/releases)



* Support symfony/css-selector v7


### lib-web 1.0.4: 1.0.4

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/12/01 11:38:48 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



* Support Symfony 7 by **[Naktibalda](https://github.com/Naktibalda)** in https://github.com/Codeception/lib-web/pull/8


### lib-innerbrowser 4.0.2: 4.0.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/12/01 11:28:55 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Support Symfony 7.x by **[pfuhrmann](https://github.com/pfuhrmann)** in https://github.com/Codeception/lib-innerbrowser/pull/66


### lib-web 1.0.3: 1.0.3

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/11/27 06:43:46 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



* Minor: Newer array syntax by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/lib-web/pull/6



### lib-innerbrowser 4.0.1: 4.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/11/16 16:25:42 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Use FQN for public methods by **[erickskrauch](https://github.com/erickskrauch)** in https://github.com/Codeception/lib-innerbrowser/pull/63
* Fix numeric key in form by **[janfejtek](https://github.com/janfejtek)** in https://github.com/Codeception/lib-innerbrowser/pull/64


### Codeception 5.0.12: 5.0.12

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/10/15 18:28:39 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Wait for all tests to finish before accessing the serialized test results by **[MarcelBolten](https://github.com/MarcelBolten)** in [#6702](https://github.com/Codeception/Codeception/issues/6702)
* Updated Support Ukraine link in version string


### Codeception 5.0.11: 5.0.11

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/08/22 06:53:38 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



## What's Changed
* fix sharding for empty tests file by **[SamMousa](https://github.com/SamMousa)** in https://github.com/Codeception/Codeception/pull/6667
* Add AllowDynamicProperties attribute to Unit by **[erickskrauch](https://github.com/erickskrauch)** in https://github.com/Codeception/Codeception/pull/6666
* Include mock expectations in assertion count  by **[rene-bos](https://github.com/rene-bos)** in https://github.com/Codeception/Codeception/pull/6672
* Allow multiple test dependencies by **[mbrodala](https://github.com/mbrodala)** in https://github.com/Codeception/Codeception/pull/6676
* Fix JUnitReporter compatibility with PHPUnit 10.3 by **[Naktibalda](https://github.com/Naktibalda)** in https://github.com/Codeception/Codeception/pull/6685

## New Contributors
* **[rene-bos](https://github.com/rene-bos)** made their first contribution in https://github.com/Codeception/Codeception/pull/6672
* **[mbrodala](https://github.com/mbrodala)** made their first contribution in https://github.com/Codeception/Codeception/pull/6676

**Full Changelog**: https://github.com/Codeception/Codeception/compare/5.0.10...5.0.11


### module-phalcon5 v2.0.1: v2.0.1

Released by [![](https://avatars.githubusercontent.com/u/1073784?v=4&s=16){:height="16" width="16"} niden](https://github.com/niden) on 2023/08/03 17:54:06 / [Repository](https://github.com/Codeception/module-phalcon5)   / [Releases](https://github.com/Codeception/module-phalcon5/releases)



Fixed getRawBody() return type [[#8](https://github.com/Codeception/module-phalcon5/issues/8)](https://github.com/Codeception/module-phalcon5/issues/8)


### module-yii2 1.1.9: 1.1.9

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2023/06/16 03:52:10 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- [#85](https://github.com/Codeception/module-yii2/issues/85): Fix the case for "yii" namespace in phpdoc (@ilyaplot)
- [#86](https://github.com/Codeception/module-yii2/issues/86): Use correct type declaration for amOnPage method (@erickskrauch)
- [#88](https://github.com/Codeception/module-yii2/issues/88): Enable object override to InitDbFixture during FixturesStore initialization (@PoohOka)


### lib-web 1.0.2: 1.0.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/04/18 20:33:22 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



* Mentioning `<html>` tag requirement by **[ThomasLandauer](https://github.com/ThomasLandauer)** in https://github.com/Codeception/lib-web/pull/4


### Codeception 5.0.10: 5.0.10

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/03/14 07:27:00 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* JUnitReporter: Fixed compatibility with PHPUnit 10.0.16 [#6656](https://github.com/Codeception/Codeception/issues/6656)
* Recorder extension: Fixed type error [#6643](https://github.com/Codeception/Codeception/issues/6643) by **[thomashohn](https://github.com/thomashohn)**
* Validate test filter pattern without warning [#6641](https://github.com/Codeception/Codeception/issues/6641) by **[dmitryuk](https://github.com/dmitryuk)**


### Codeception 5.0.9: 5.0.9

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/02/11 14:42:09 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* JUnitReporter: Do not set 'useless' testsuite attribute in strict mode [#6635](https://github.com/Codeception/Codeception/issues/6635) by **[gileri](https://github.com/gileri)**
* Fixed static $defaultName deprecated in _completion command [#6633](https://github.com/Codeception/Codeception/issues/6633) by **[dmitryuk](https://github.com/dmitryuk)**
* Replaced object property assertions removed from PHPUnit 10



### module-yii2 1.1.8: 1.1.8

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/02/10 18:54:49 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



* Fix last commit error by **[sunnyphp](https://github.com/sunnyphp)** in https://github.com/Codeception/module-yii2/pull/73
* update links by **[Arhell](https://github.com/Arhell)** in https://github.com/Codeception/module-yii2/pull/75
* PHP 8.1: parse_str(): Passing null to parameter `[#1](https://github.com/Codeception/module-yii2/issues/1)` ($string) of type string is deprecated by **[uaoleg](https://github.com/uaoleg)** in https://github.com/Codeception/module-yii2/pull/80
* Upgrade dependencies to support PHPUnit 10 by **[Naktibalda](https://github.com/Naktibalda)** in https://github.com/Codeception/module-yii2/pull/82



### module-laminas 3.0.2: 3.0.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/02/09 06:36:25 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



* Support codeception/lib-innerbrowser v4


### Codeception 5.0.8: 5.0.8

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/02/03 21:58:10 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Supports PHPUnit 10


### lib-innerbrowser 4.0.0: 4.0.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/02/03 19:33:48 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Support for PHPUnit 10


### Codeception 5.0.7: 5.0.7

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/01/14 20:06:31 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Disabled phpcs checks in generated action files [#6621](https://github.com/Codeception/Codeception/issues/6621)
* `$I->wantTo()` no longer changes test title at runtime [#6622](https://github.com/Codeception/Codeception/issues/6622)
* Display correct failed step when failures and errors happened during test run [#6623](https://github.com/Codeception/Codeception/issues/6623)
* Fixed indentation of `step_decorators` in config files generated by `bootstrap` [#6624](https://github.com/Codeception/Codeception/issues/6624)
* Enabled `Conditional`, `Retry` and `tryTo` decorators in acceptance suite generated by `bootstrap` [#6624](https://github.com/Codeception/Codeception/issues/6624)  
* Improved handling of anonymous classes in parser [#6626](https://github.com/Codeception/Codeception/issues/6626)


### module-cli 2.0.1: 2.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2023/01/13 18:58:12 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)



* Unset SHELL_VERBOSITY environment variable before execution of command [#13](https://github.com/Codeception/module-cli/issues/13) 


### Codeception 5.0.6: 5.0.6

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/12/28 14:20:04 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Fixed `canSee` assertions in Unit format [#6610](https://github.com/Codeception/Codeception/issues/6610)
* `tryTo` methods must return boolean result [#6614](https://github.com/Codeception/Codeception/issues/6614)
* Fixed various issues with handling of `@skip` and `@incomplete` annotations and attributes in Cest format [#6617](https://github.com/Codeception/Codeception/issues/6617)
* Stopped adding `__mocked` field to mocks created by Stub library [#6620](https://github.com/Codeception/Codeception/issues/6620)
* Fixed deprecated string syntax in Run command [#6618](https://github.com/Codeception/Codeception/issues/6618) by **[shtiher-pp](https://github.com/shtiher-pp)**


### Codeception 5.0.5: 5.0.5

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/11/20 11:33:41 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Don't disable test shuffling when --shard option is used ([#6605](https://github.com/Codeception/Codeception/issues/6605))
* Provided typed signatures for attributes ([#6600](https://github.com/Codeception/Codeception/issues/6600)) by **[mdoelker](https://github.com/mdoelker)**
* Support for Attributes in generated Actions files ([#6593](https://github.com/Codeception/Codeception/issues/6593)) by **[yesdevnull](https://github.com/yesdevnull)**
* Fixed expectNotToPerformAssertions in unit tests ([#6602](https://github.com/Codeception/Codeception/issues/6602)) by **[yesdevnull](https://github.com/yesdevnull)**


### module-laminas 3.0.1: 3.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/11/20 11:03:09 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



* Add public getter to access the application instance by **[fourhundredfour](https://github.com/fourhundredfour)** in https://github.com/Codeception/module-laminas/pull/20
* grabServiceFromContainer: Returned service is not always object by **[svycka](https://github.com/svycka)** in https://github.com/Codeception/module-laminas/pull/23


### Codeception 5.0.4: 5.0.4

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/10/30 19:21:03 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Execute FailFast subscriber before module _failed hooks [#6586](https://github.com/Codeception/Codeception/issues/6586) by **[yesdevnull](https://github.com/yesdevnull)**
* Fixed parsing of **[skip](https://github.com/skip)** annotation [#6596](https://github.com/Codeception/Codeception/issues/6596)
* Undeprecated untyped method arguments in Cest format [#6591](https://github.com/Codeception/Codeception/issues/6591)
* Removed unnecessary overrides of $resultAggregator property in Unit format and TestCaseWrapper [#6590](https://github.com/Codeception/Codeception/issues/6590)
* Print failure/error/warning/skipped/incomplete messages in HTML reports [#6595](https://github.com/Codeception/Codeception/issues/6595)
* Fixed counting of successful tests [#6595](https://github.com/Codeception/Codeception/issues/6595)


### lib-innerbrowser 3.1.3: 3.1.3

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/10/03 15:36:06 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



## What's Changed
* fix: checkbox handling by **[SamMousa](https://github.com/SamMousa)** in https://github.com/Codeception/lib-innerbrowser/pull/60


**Full Changelog**: https://github.com/Codeception/lib-innerbrowser/compare/3.1.2...3.1.3


### Codeception 5.0.3: 5.0.3

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/09/30 15:48:28 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Fixed passing test result to dependent tests in unit tests ([#6580](https://github.com/Codeception/Codeception/issues/6580))
* Fixed `TypeError` when **[coversNothing](https://github.com/coversNothing)** annotation is used by Slamdunk ([#6582](https://github.com/Codeception/Codeception/issues/6582))
* `codecept init unit` creates `tests/Support` directory ([#6578](https://github.com/Codeception/Codeception/issues/6578))
* Fixed phar file url in `self-update` command by **[voku](https://github.com/voku)** ([#6563](https://github.com/Codeception/Codeception/issues/6563))
* Added message how to exit Codeception console by **[ThomasLandauer](https://github.com/ThomasLandauer)** ([#6561](https://github.com/Codeception/Codeception/issues/6561))
* Improved compatibility with PHPUnit 10


### lib-xml 1.0.1: 1.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/09/11 14:13:11 / [Repository](https://github.com/Codeception/lib-xml)   / [Releases](https://github.com/Codeception/lib-xml/releases)



* Fixed param annotations


### Codeception 5.0.2: 5.0.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/08/20 18:24:07 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Fixed remote code coverage for namespaced suites ([#6533](https://github.com/Codeception/Codeception/issues/6533))
* Fixed data provider in abstract Cest class **[p-golovin](https://github.com/p-golovin)** ([#6560](https://github.com/Codeception/Codeception/issues/6560))
* Fixed issue when include groups and test groups empty **[geega](https://github.com/geega)** ([#6557](https://github.com/Codeception/Codeception/issues/6557))


### Codeception 5.0.1: 5.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/08/13 16:49:00 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Propagate --ext and --override parameters to included test suites by **[calvinalkan](https://github.com/calvinalkan)** ([#6536](https://github.com/Codeception/Codeception/issues/6536))
* Fixed false negative message about stecman/symfony-console-completion package by **[geega](https://github.com/geega)** ([#6541](https://github.com/Codeception/Codeception/issues/6541))
* Fixed a number of issues in template functionality ([#6552](https://github.com/Codeception/Codeception/issues/6552))
* Fixed DataProvider, to properly load dataProviders from abstract classes by **[Basster](https://github.com/Basster)** ([#6549](https://github.com/Codeception/Codeception/issues/6549))


### Codeception 4.2.2: 4.2.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/08/13 13:56:22 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Propagate --ext and --override parameters to included test suites ([#6536](https://github.com/Codeception/Codeception/issues/6536))
* Fixed false negative message about stecman/symfony-console-completion package ([#6541](https://github.com/Codeception/Codeception/issues/6541))


### module-phpbrowser 2.5.0: 2.5.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/08/06 13:44:12 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



* 2.5 branch makes Codeception 5 compatible with Symfony 4.4 components


### Codeception 5.0.0: 5.0.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/07/28 08:41:10 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



#### 5.0.0

[Blog post](https://codeception.com/07-28-2022/codeception-5.html)

Summary of all differences from Codeception 4

##### Added

* Basic attribute support
* `--shard`, `--grep`, `--filter` options
* Test can be filtered by data provider case number or name
* Tests of all formats are reported as useless if they perform no assertions and `reports_useless_tests` setting is enabled
* Array of variables can be passed to all `pause` functions/methods
* Dynamic configuration with parameters can use arrays and other non-string types ([#6409](https://github.com/Codeception/Codeception/issues/6409))
* `codecept_pause` function and `$this->pause()` in unit tests ([#6387](https://github.com/Codeception/Codeception/issues/6387))
* Interactive console is executed in the scope of paused test class.
* New code coverage settings:
  - `path_coverage` - enables path and branch coverage
  - `strict_covers_annotation` - marks test as risky if it has `@covers` annotation but executes some other code
  - `ignore_deprecated_code` - doesn't collect code coverage for code having `@deprecated` annotation
  - `disable_code_coverage_ignore` - ignores `@codeCoverageIgnore`, `@codeCoverageIgnoreStart` and `@codeCoverageIgnoreEnd` annotations
* Optional value to `fail-fast` option
* Dynamic configuration with parameters can use arrays and other non-string types

##### Changed

* PHPUnit is no longer the engine of Codeception, but TestCase format is still supported and assertions are still used
* Generators create namespaced test suites by default
* Replaced Hoa Console with PsySH in `codecept console`
* Used Symfony VarDumper in `codecept_debug`
* Fixed DotReporter output format
* Module `after` and `failed` hooks are executed in reverse order
* Introduced strict typing and other features of PHP 7 and 8.
* Cest format can use data providers from other classes
* Fixed injecting dependencies to actor in Cest and Gherkin formats [#6506](https://github.com/Codeception/Codeception/issues/6506)
* Variadic parameters can be skipped in dependency injection [#6505](https://github.com/Codeception/Codeception/issues/6505)
* Deprecated untyped method arguments in Cest format [#6521](https://github.com/Codeception/Codeception/issues/6521)

##### Removed

* `JSON` and `TAP` report formats
* Code coverage blacklist functionality
* `generate:cept` command (`Cept` format itself is deprecated)
* Deprecated class aliases:
  - Codeception\TestCase\Test
  - Codeception\Platform\Group
  - Codeception\Platform\Group
  - Codeception\TestCase
* Settings
  - `log_incomplete_skipped`
  - `paths.log` (replaced by `paths.output`)
  - Suite setting `class_name` (replaced by `actor`)
  - Global setting `actor` (replaced by `actor_prefix`)
* `Configuration::logDir` method (replaced by `Configuration::outputDir` in 2.0)
* Custom reporters implementing TestListener are no longer supported and must be converted to Extensions

##### Supported versions

* PHP 8
* PHPUnit 9 (prepared for upcoming PHPUnit 10)
* Symfony 4.4 - 6.x


### Codeception 5.0.0-RC8: 5.0.0-RC8

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/07/28 08:25:46 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Deprecated untyped method arguments in Cest format [#6521](https://github.com/Codeception/Codeception/issues/6521)
* Improved code style of generated files [#6522](https://github.com/Codeception/Codeception/issues/6522)
* Removed "Powered by PHPUnit" message [#6520](https://github.com/Codeception/Codeception/issues/6520)


### Codeception 5.0.0-RC7: 5.0.0-RC7

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/07/22 05:52:09 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Fixed injecting dependencies to actor in Cest and Gherkin formats [#6506](https://github.com/Codeception/Codeception/issues/6506)
* Variadic parameters can be skipped in dependency injection [#6505](https://github.com/Codeception/Codeception/issues/6505)


### module-datafactory 3.0.0: 3.0.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/07/18 16:39:04 / [Repository](https://github.com/Codeception/module-datafactory)   / [Releases](https://github.com/Codeception/module-datafactory/releases)



* Support for Codeception 5.0


### module-yii2 1.1.7: 1.1.7

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/07/15 18:10:54 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



* Fix compatibility with Codeception 5.0.0-RC6 [#72](https://github.com/Codeception/module-yii2/issues/72) 


### Codeception 5.0.0-RC6: 5.0.0-RC6

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/07/12 07:13:56 / [Repository](https://github.com/Codeception/Codeception)   / [Releases](https://github.com/Codeception/Codeception/releases)



* Added new attributes (Prepare, Env, BeforeClass,AfterClass, Given, When, Then)
* Class level attributes are applied to all methods
* Codeception attributes are supported in unit tests
* Cest format can use data providers from other classes



### module-yii2 1.1.6: 1.1.6

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2022/06/21 11:05:32 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- [#8](https://github.com/Codeception/module-yii2/issues/8): Add log from Yii to artifacts when test fails (@aywan)
- [#65](https://github.com/Codeception/module-yii2/issues/65): Codeception 5 support (@developedsoftware and **[TavoNiievez](https://github.com/TavoNiievez)**)



### module-phalcon5 v2.0.0: v2.0.0

Released by [![](https://avatars.githubusercontent.com/u/1073784?v=4&s=16){:height="16" width="16"} niden](https://github.com/niden) on 2022/06/03 15:20:26 / [Repository](https://github.com/Codeception/module-phalcon5)   / [Releases](https://github.com/Codeception/module-phalcon5/releases)



Supports PHP versions: 8.0, 8.1

* Use of Codeception v5+
* Use of Phalcon 5.0.0RC1+
* Corrected namespaces
* Cosmetic changes


### module-phpbrowser 1.0.3: 1.0.3

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/05/21 13:52:31 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



* Updated dependencies


### module-phpbrowser 2.0.3: 2.0.3

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/05/21 13:49:33 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



* Updated dependencies


### lib-innerbrowser 3.1.2: 3.1.2

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/04/09 08:51:34 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Removed dontSeeCheckboxIsChecked parameter type declaration to permit arrays
* Fixed formatting of Crawler and CrawlerNot constraint failure messages


### lib-web 1.0.1: 1.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/04/09 08:19:47 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)



* Removed dontSeeCheckboxIsChecked parameter type declaration to permit arrays and match seeCheckboxIsChecked


### module-phpbrowser 3.0.0: 3.0.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/03/20 09:45:52 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



* Support for Codeception 5


### lib-innerbrowser 3.1.1: 3.1.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/03/11 10:36:11 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Fix constraint names


### lib-innerbrowser 3.1.0: 3.1.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/03/11 10:18:41 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Extracted constraints , exception and interfaces shared with module-webdriver to codeception/lib-web


### lib-xml 1.0.0: Initial release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/03/11 10:04:52 / [Repository](https://github.com/Codeception/lib-xml)   / [Releases](https://github.com/Codeception/lib-xml/releases)






### lib-web 1.0.0: Initial release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/03/11 08:38:48 / [Repository](https://github.com/Codeception/lib-web)   / [Releases](https://github.com/Codeception/lib-web/releases)






### lib-innerbrowser 3.0.1: 3.0.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/03/06 10:41:21 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Raised lowest supported version of  symfony 4 components to avoid deprecation warnings on PHP 8.


### module-laminas 3.0.0: 3.0.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/02/20 15:37:34 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



* Support for Codeception 5


### lib-innerbrowser 3.0.0: 3.0.0

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2022/02/19 18:36:23 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Compatibility with Codeception 5


### lib-innerbrowser 2.0.2: 2.0.2

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2022/02/01 17:42:05 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



## What's Changed
* Prevent "Uncaught TypeError: explode(): Argument [#2](https://github.com/Codeception/lib-innerbrowser/issues/2) ($string) must be of type string, null given" by **[Fahl-Design](https://github.com/Fahl-Design)** in https://github.com/Codeception/lib-innerbrowser/pull/47
* Fix compatibility with symfony/dom-crawler < 5.3.0-BETA-1 by **[nrocy](https://github.com/nrocy)** in https://github.com/Codeception/lib-innerbrowser/pull/50

**Full Changelog**: https://github.com/Codeception/lib-innerbrowser/compare/2.0.1...2.0.2


### module-yii2 1.1.5: 1.1.5

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2022/01/10 10:29:36 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- [#54](https://github.com/Codeception/module-yii2/issues/54): Annotate throws with FQN (@DBX12)
- [#56](https://github.com/Codeception/module-yii2/issues/56): Move tests from codeception/yii2-tests (@DBX12)
- [#59](https://github.com/Codeception/module-yii2/issues/59): Allow installing on PHP 8.1.1 (@Krakozaber)



### module-phpbrowser 2.0.2: 2.0.2

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/21 15:23:57 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



* **Small bug fix**: Fix some types (https://github.com/Codeception/module-phpbrowser/pull/21)


### lib-innerbrowser 2.0.1: 2.0.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/21 02:04:00 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Update dependencies (https://github.com/Codeception/lib-innerbrowser/pull/48)


### module-laminas 1.3.1: 1.3.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/18 14:39:53 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



## What's Changed

* Update dependencies by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/module-laminas/pull/21


### module-phpbrowser 2.0.1: 2.0.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/18 14:26:57 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



* Update dependencies by **[TavoNiievez](https://github.com/TavoNiievez)** and **[Naktibalda](https://github.com/Naktibalda)** in https://github.com/Codeception/module-phpbrowser/pull/20


### module-phalcon5 v1.0.1: v1.0.1

Released by [![](https://avatars.githubusercontent.com/u/1073784?v=4&s=16){:height="16" width="16"} niden](https://github.com/niden) on 2021/12/16 13:04:49 / [Repository](https://github.com/Codeception/module-phalcon5)   / [Releases](https://github.com/Codeception/module-phalcon5/releases)



Corrections for Packagist descriptions and PHP minimum version


### module-phalcon5 v1.0.0: v1.0.0

Released by [![](https://avatars.githubusercontent.com/u/1073784?v=4&s=16){:height="16" width="16"} niden](https://github.com/niden) on 2021/12/15 18:51:06 / [Repository](https://github.com/Codeception/module-phalcon5)   / [Releases](https://github.com/Codeception/module-phalcon5/releases)



Initial release of the Codeception module for Phalcon 5.


### module-datafactory 2.0.0: 2.0.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/07 15:00:26 / [Repository](https://github.com/Codeception/module-datafactory)   / [Releases](https://github.com/Codeception/module-datafactory/releases)



## What's Changed

* PHP 7.4 or higher is required.
* Support PHP 8.1
* Updated code base to PHP 7.4 by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/module-datafactory/pull/9 and https://github.com/Codeception/module-datafactory/pull/14
* Documentation changes by **[DavertMik](https://github.com/DavertMik)** in https://github.com/Codeception/module-datafactory/pull/11
* The changelog has been added to the Readme file, by **[Arhell](https://github.com/Arhell)** in https://github.com/Codeception/module-datafactory/pull/13

**Full Changelog**: https://github.com/Codeception/module-datafactory/compare/1.1.0...2.0.0


### module-cli 2.0.0: 2.0.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/07 06:11:12 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)



## What's Changed

* PHP 7.4 or higher is required.
* Support PHP 8.1
* Updated code base to PHP 7.4 by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/module-cli/pull/10
* The changelog has been added to the Readme file, by **[Arhell](https://github.com/Arhell)** in https://github.com/Codeception/module-cli/pull/9

**Full Changelog**: https://github.com/Codeception/module-cli/compare/1.1.1...2.0.0


### module-laminas 1.3.0: 1.3.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/07 05:44:00 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



## What's Changed

* PHP 7.4 or higher is required.
* Updated code base to PHP 7.4 by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/module-laminas/pull/18

**Full Changelog**: https://github.com/Codeception/module-laminas/compare/1.2.1...1.3.0


### module-phpbrowser 2.0.0: 2.0.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/07 05:24:45 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)



## What's Changed

* PHP 7.4 or higher is required.
* Updated code base to PHP 7.4 by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/module-phpbrowser/pull/12 and https://github.com/Codeception/module-phpbrowser/pull/17
* Cast uri to string by **[Naktibalda](https://github.com/Naktibalda)** in https://github.com/Codeception/module-phpbrowser/pull/14
* The changelog has been added to the Readme file, by **[Arhell](https://github.com/Arhell)** in https://github.com/Codeception/module-phpbrowser/pull/16

**Full Changelog**: https://github.com/Codeception/module-phpbrowser/compare/1.0.2...2.0.0


### lib-innerbrowser 2.0.0: 2.0.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/12/07 05:16:00 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



## What's Changed

* PHP 7.4 or higher is required.
* Updated code base to PHP 7.4 by **[TavoNiievez](https://github.com/TavoNiievez)** in https://github.com/Codeception/lib-innerbrowser/pull/45
* The changelog has been added to the Readme file, by **[Arhell](https://github.com/Arhell)** in https://github.com/Codeception/lib-innerbrowser/pull/43

**Full Changelog**: https://github.com/Codeception/lib-innerbrowser/compare/1.5.0...2.0.0


### module-yii2 1.1.4: 1.1.4

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2021/11/26 05:58:14 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- Allow PHP 8.1 (@saatsazov)


### module-laminas 1.2.1: 1.2.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/10/19 17:56:16 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



Fix incorrect type hint ([#19](https://github.com/Codeception/module-laminas/issues/19)) by **[olexp](https://github.com/olexp)** and **[TavoNiievez](https://github.com/TavoNiievez)** .


### module-laminas 1.2.0: addFactoryToContainer

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2021/10/16 08:01:31 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



* Add addFactoryToContainer method [#17](https://github.com/Codeception/module-laminas/issues/17) by **[olexp](https://github.com/olexp)** 


### module-laminas 1.1.0: 1.1.0

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/10/06 00:34:16 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



- Support for PHP versions lower than 7.3 is removed.
- Code standards updated to PHP 7.3 by **[TavoNiievez](https://github.com/TavoNiievez)** .
- Remove dependency on laminas/laminas-console ([#13](https://github.com/Codeception/module-laminas/issues/13)) by **[javabudd](https://github.com/javabudd)** .
- Various documentation improvements by **[Naktibalda](https://github.com/Naktibalda)** and **[Arhell](https://github.com/Arhell)** .


### lib-innerbrowser 1.5.1: 1.5.1

Released by [![](https://avatars.githubusercontent.com/u/64917965?v=4&s=16){:height="16" width="16"} TavoNiievez](https://github.com/TavoNiievez) on 2021/08/30 15:40:07 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



- Fix symfony/dom-crawler 5.3 deprecation ([#41](https://github.com/Codeception/lib-innerbrowser/issues/41)) by **[simonhammes](https://github.com/simonhammes)**
- Require Codeception 4.x by **[TavoNiievez](https://github.com/TavoNiievez)** 


### module-yii2 1.1.3: 1.1.3

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2021/05/24 20:06:33 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- Add ability to specify application class in config ([#48](https://github.com/Codeception/module-yii2/issues/48))


### module-phalcon4 v1.0.7: v1.0.7

Released by [![](https://avatars.githubusercontent.com/u/3289702?v=4&s=16){:height="16" width="16"} Jeckerson](https://github.com/Jeckerson) on 2021/05/18 18:21:15 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



Updated code base to PHP 7.2 ([#14](https://github.com/Codeception/module-phalcon4/issues/14)):
- Added strict types
- Added return types
- Added some type hints
- Removed unnecessary qualifiers
- sha1 by default instead of md5.


### lib-innerbrowser 1.5.0: Hidden field, delete requests, code quality

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2021/04/23 07:01:58 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Submit value of hidden field if checkbox is unchecked and matching hidden field exists [#36](https://github.com/Codeception/lib-innerbrowser/issues/36)
* Send request body in DELETE requests (partially reverts change made in 1.4.2) [#38](https://github.com/Codeception/lib-innerbrowser/issues/38)
* Improved code quality [#37](https://github.com/Codeception/lib-innerbrowser/issues/37)


### module-phalcon4 v1.0.6: v1.0.6

Released by [![](https://avatars.githubusercontent.com/u/3289702?v=4&s=16){:height="16" width="16"} Jeckerson](https://github.com/Jeckerson) on 2021/04/13 21:30:04 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



* Fixed Request service redefinition ([#7](https://github.com/Codeception/module-phalcon4/issues/7))


### lib-innerbrowser 1.4.2: Don't set request body for DELETE and OPTIONS requests

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2021/04/06 05:29:20 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)






### module-datafactory 1.1.0: Added Custom Store

Released by [![](https://avatars.githubusercontent.com/u/220264?v=4&s=16){:height="16" width="16"} DavertMik](https://github.com/DavertMik) on 2021/03/16 19:42:52 / [Repository](https://github.com/Codeception/module-datafactory)   / [Releases](https://github.com/Codeception/module-datafactory/releases)



Custom Store can be used for Data Factory. See [#2](https://github.com/Codeception/module-datafactory/issues/2) 


### lib-innerbrowser 1.4.1: Fix grabTextFrom TypeError

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2021/03/02 08:03:49 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Fix Type Error on PHP 8 when array is passed to grabTextFrom[#30](https://github.com/Codeception/lib-innerbrowser/issues/30) 


### module-phalcon4 v1.0.5: v1.0.5

Released by [![](https://avatars.githubusercontent.com/u/3289702?v=4&s=16){:height="16" width="16"} Jeckerson](https://github.com/Jeckerson) on 2021/02/10 22:09:30 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



Changed
* Removed limitation of PHP 8.0 version in composer.json


### lib-innerbrowser 1.4.0: 

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2021/01/29 18:19:08 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Added redirect methods https://github.com/Codeception/lib-innerbrowser/pull/29


### lib-innerbrowser 1.3.6: 

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2021/01/17 11:25:06 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Don't set request body for HEAD requests [#26](https://github.com/Codeception/lib-innerbrowser/issues/26) 



### lib-innerbrowser 1.3.5: 

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2021/01/02 19:01:35 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Fixed filling of fields that are linked to form using `form` attribute https://github.com/Codeception/Codeception/issues/6022


### module-datafactory 1.0.1: PHP8 support

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/12/30 15:56:46 / [Repository](https://github.com/Codeception/module-datafactory)   / [Releases](https://github.com/Codeception/module-datafactory/releases)






### module-yii2 1.1.2: 1.1.2

Released by [![](https://avatars.githubusercontent.com/u/47294?v=4&s=16){:height="16" width="16"} samdark](https://github.com/samdark) on 2020/12/28 11:32:21 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



- PHP 8 support [#18](https://github.com/Codeception/module-yii2/issues/18) by **[samdark](https://github.com/samdark)**
- Fix for support `Instance::of()` in configuration [#21](https://github.com/Codeception/module-yii2/issues/21) by **[antonovsky](https://github.com/antonovsky)**
- Initialize `$_SERVER['QUERY_STRING']` to mimic normal behavior of most webservers by **[eborned](https://github.com/eborned)**


### module-cli 1.1.1: Preparation for PHPUnit 10

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/12/26 16:58:43 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)



Use wrapper for assertRegExp method


### module-laminas 1.0.0: First release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/11/25 07:58:15 / [Repository](https://github.com/Codeception/module-laminas)   / [Releases](https://github.com/Codeception/module-laminas/releases)



* Renamed module-zf2 to module-laminas
* Supports PHP 8


### module-cli 1.1.0: Add grabShellOutput method

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/11/16 06:27:24 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)






### module-phpbrowser 1.0.2: Support PHP 8

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/10/24 15:29:51 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)






### module-cli 1.0.4: Support PHP 8

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/10/23 17:52:08 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)



* Support PHP 8 (no code change)
* Deleted local copy of generated documentation


### lib-innerbrowser 1.3.4: Support PHP 8

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/10/22 06:23:10 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



No code changes


### lib-innerbrowser 1.3.3: 

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/10/11 19:05:11 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Added missing http codes.
* Improved documentation of Ajax methods


### module-cli 1.0.3: Documentation improvements

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/10/11 18:35:08 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)






### module-yii2 1.1.1: 1.1.1

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/08/28 06:53:33 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



* Change default value of transaction parameter to true [#4](https://github.com/Codeception/module-yii2/issues/4) by **[SaloEater](https://github.com/SaloEater)** 
* Fix ModuleException parameters, handle undefined [#12](https://github.com/Codeception/module-yii2/issues/12) by **[smichae](https://github.com/smichae)** 
* Validation errors for haveRecord method [#10](https://github.com/Codeception/module-yii2/issues/10) by **[ianikanov](https://github.com/ianikanov)** 


### module-phalcon4 v1.0.4: v1.0.4

Released by [![](https://avatars.githubusercontent.com/u/7444246?v=4&s=16){:height="16" width="16"} ruudboon](https://github.com/ruudboon) on 2020/08/26 09:34:29 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



Fixed
- Session To Use Session Manager 


### module-phpbrowser 1.0.1: Support Guzzle 7.x

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/07/05 15:35:51 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)






### lib-innerbrowser 1.3.2: 

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/07/05 14:22:41 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* Updated (dont)seeCurrentUrlMatches methods to use wrapper method instead of deprecated assert(Not)RegExp method.
* Fixed various code smells reported by PhpStorm


### lib-innerbrowser 1.3.1: PHPUnit9 compatibility

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/02/20 14:52:13 / [Repository](https://github.com/Codeception/lib-innerbrowser)   / [Releases](https://github.com/Codeception/lib-innerbrowser/releases)



* proceedSeeInField casts value to string before comparison


### module-cli 1.0.2: Fixed dontSeeInShellOutput for older versions of PHPUnit

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/02/07 17:34:52 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)






### module-cli 1.0.1: Compatibility with PHPUnit 9

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/02/07 17:11:44 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)



Use assertStringNotContainsString instead of assertNotContains in dontSeeInShellOutput


### module-yii2 1.1.0: Module implements Codeception's MultiSession

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/02/01 19:26:08 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)



[#3](https://github.com/Codeception/module-yii2/issues/3) by **[mytskine](https://github.com/mytskine)** 


### module-zf2 1.0.3: 

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/01/29 15:19:36 / [Repository](https://github.com/Codeception/module-zf2)   / [Releases](https://github.com/Codeception/module-zf2/releases)



* Use doctrine entitymanager from config
* Add persisted services before bootstrap


### module-zf2 1.0.2: Empty request content can't be null

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/01/23 17:55:51 / [Repository](https://github.com/Codeception/module-zf2)   / [Releases](https://github.com/Codeception/module-zf2/releases)



[#2](https://github.com/Codeception/module-zf2/issues/2) 


### module-zf2 1.0.1: Add Server parameters to ZendRequest

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2020/01/22 15:14:48 / [Repository](https://github.com/Codeception/module-zf2)   / [Releases](https://github.com/Codeception/module-zf2/releases)






### module-phalcon4 1.0.3: v1.0.3

Released by [![](https://avatars.githubusercontent.com/u/7444246?v=4&s=16){:height="16" width="16"} ruudboon](https://github.com/ruudboon) on 2020/01/11 17:02:24 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



Fixed
- Dependencies


### module-phalcon4 1.0.2: v1.0.2

Released by [![](https://avatars.githubusercontent.com/u/7444246?v=4&s=16){:height="16" width="16"} ruudboon](https://github.com/ruudboon) on 2020/01/07 12:32:16 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



Fixed
- Replacing service in DI from functional test not working


### module-phalcon4 1.0.1: v1.0.1

Released by [![](https://avatars.githubusercontent.com/u/7444246?v=4&s=16){:height="16" width="16"} ruudboon](https://github.com/ruudboon) on 2020/01/06 11:26:42 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



Removed composer.lock
Updated dependencies
Updated SQL schema
Updated DocBlocks


### module-phalcon4 1.0.0: v1.0.0

Released by [![](https://avatars.githubusercontent.com/u/7444246?v=4&s=16){:height="16" width="16"} ruudboon](https://github.com/ruudboon) on 2020/01/06 09:32:56 / [Repository](https://github.com/Codeception/module-phalcon4)   / [Releases](https://github.com/Codeception/module-phalcon4/releases)



Initial release of the Codeception module for Phalcon 4.


### module-yii2 1.0.1: Use stable versions of codeception and innerbrowser

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2019/10/25 17:33:04 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)






### module-yii2 1.0.0: Initial release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2019/10/19 15:29:42 / [Repository](https://github.com/Codeception/module-yii2)   / [Releases](https://github.com/Codeception/module-yii2/releases)






### module-phpbrowser 1.0.0: Initial release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2019/10/19 15:28:32 / [Repository](https://github.com/Codeception/module-phpbrowser)   / [Releases](https://github.com/Codeception/module-phpbrowser/releases)






### module-zf2 1.0.0: Initial release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2019/10/18 11:24:38 / [Repository](https://github.com/Codeception/module-zf2)   / [Releases](https://github.com/Codeception/module-zf2/releases)






### module-datafactory 1.0.0: Initial release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2019/10/18 11:07:51 / [Repository](https://github.com/Codeception/module-datafactory)   / [Releases](https://github.com/Codeception/module-datafactory/releases)






### module-cli 1.0.0: Initial release

Released by [![](https://avatars.githubusercontent.com/u/395992?v=4&s=16){:height="16" width="16"} Naktibalda](https://github.com/Naktibalda) on 2019/10/18 11:07:08 / [Repository](https://github.com/Codeception/module-cli)   / [Releases](https://github.com/Codeception/module-cli/releases)





