# FlakeScanner

## FlakyAppRepo Suite

The subjects in FlakyAppRepo suite are listed below.

| App Name | Version | \#LOC | \#Stars  | Category|Github website|
|--|--|--|--|--|--|
| Amaze File Manager | 3.4.3 | 92.2k | 2.8k | Tools|https://github.com/TeamAmaze/AmazeFileManager|
| Youtube Extractor | 2.0.0 | 2.7k | 519 | Video Players|https://github.com/HaarigerHarald/android-youtubeExtractor|
| AntennaPod | 1.8.1 | 102.6k | 2.7k | Music \& Audio|https://github.com/AntennaPod/AntennaPod/tree/aca6e3|
| Backpack Design | 2.0.7 | 84.2k | 363 | Productivity |https://github.com/Skyscanner/backpack-android|
| Barista | 3.5.0 | 67.9k | 1.2k | Productivity |https://github.com/AdevintaSpain/Barista|
| CameraView | 2.6.1 | 40.5k | 2.9k | Photography|https://github.com/google/cameraview|
| Catroid | 0.9.69 | 457.5k | 0 | Education|https://github.com/souravmunjal/clonecat|
| City Localizer | 1.1 | 4k | 0 | Travel \& Local|https://github.com/lszymans/CityLocalizer|
| ConnectBot | 1.9.6 | 119.7k | 1.4k | Communication|https://github.com/connectbot/connectbot|
| DuckDuckGo | 5.43.0 | 211.3k | 1.2k | Tools|https://github.com/duckduckgo/Android|
| Espresso | 1.0 | 17.3k | 1.1k | Maps \& Navigation|https://github.com/TonnyL/Espresso|
| Firefox Focus| 8.5.1 | 44.5k | 1.6k | Communication|https://github.com/mozilla-mobile/focus-android|
| Firefox Lite | 2.18 | 1598.4k | 212 | Communication|https://github.com/mozilla-tw/FirefoxLite.git|
| FlexBox | 2.0.1 | 29.2k | 15.2k | Libraries & Demo |https://github.com/google/flexbox-layout|
| GnuCash | 2.4.0 | 90.1k | 1k | GnuCash|https://github.com/codinguser/gnucash-android|
| IBS FoodAnalyzer | 1.2 | 26.1k | 0 | Health \& Fitness|https://github.com/lundjohan/IBSFoodAnalyzer|
| Google I/O | 7.0.14 | 73.5k | 19.6k | Books \& Reference|https://github.com/google/iosched|
| Just Weather | 1.0.0 | 5.9k | 65 | Weather|https://github.com/kidinov/Just-Weather|
| Kaspresso | 1.1.0 | 66.3k | 774 | Productivity|https://github.com/KasperskyLab/Kaspresso|
| KeePassDroid | 2.5.3 | 159.7k | 1.2k | Tools|https://github.com/bpellin/keepassdroid|
| KickMaterial | 1.0 | 79.1k | 1.6k | Crowdfunding|https://github.com/byoutline/kickmaterial|
| KISS Launcher | 3.11.9 | 27.2k | 1.4k | Personalisation|https://github.com/Neamar/KISS|
| MedLog | 1.0 | 65k | 0 | Medical|https://github.com/CMPUT301F18T17/MedLog|
| Minimal To Do | 1.2 | 27.5k | 1.8k | Productivity|https://github.com/avjinder/Minimal-Todo|
| MoneyManagerEx | 02.14.994 | 170k | 265 | Finance|https://github.com/moneymanagerex/moneymanagerex|
| My Expenses | 3.0.7.1 | 1835.6k | 248 | Finance|https://github.com/mtotschnig/MyExpenses|
| NYBus | 1.0 | 6.9k | 272 | Transport|https://github.com/MindorksOpenSource/NYBus|
| Omni Notes | 6.0.5 | 105.9k | 2k | Productivity|https://github.com/federicoiosue/Omni-Notes|
| OpenTasks | 1.2.4 | 448k | 724 | Productivity|https://github.com/dmfs/opentasks|
| ownCloud | 2.14.2 | 333.7k | 2.9k | Productivity|https://github.com/owncloud/android.git|
| Sunflower | 0.1.6 | 5.3k | 10.1k | Gardening|https://github.com/android/sunflower|
| Surveyor | 13.3.0 | 290.4k | 13 | Communication|https://github.com/rapidpro/surveyor|
| WordPress | 14.2-rc-2 | 461.7k | 2.3k | Productivity|https://github.com/wordpress-mobile/WordPress-Android|

## Test names for Flaky Tests detected by FlakeScanner
https://github.com/FlakyTest/FlakyTests/blob/main/Supplementary_material_for_FlakeScanner.pdf

## FlakeScanner

FlakeScanner is a tool to detect flaky tests for Android apps. The tool is released as a binary file. We will open source FlakeScanner after the publication.

### Requirement
- java 11
- scala 2.13
- adb (Android Debug Bridge)

### Usage

To use, download the FlakeScanner.jar file. Then, use `java` to execute it with appropriate flags.

```
Usage: FlakeScanner [options] appName testPackage apkPath testRunnerClsPath testClassPath testMethodPath

  --adbPath <value>
  --debug
  --disable-ddm-log
  --apkInstallOpts <value>
  --deviceName <value>     Use default device if not supplied
  --max-runs <value>
  --config-from-file <value>
  --test-hang-timeout <value>
  --given-passed <value>
  --strategy <value>
  appName
  testPackage
  apkPath
  testRunnerClsPath
  testClassPath
  testMethodPath
```

