# Adobe Analytics Release Notes

## October 11, 2018 <a id="october-11-2018"></a>

### Adobe Analytics Extension 1.4 <a id="adobe-analytics-extension-1-4"></a>

#### Features <a id="features"></a>

* Migrated the tracking cookie name to the extension configuration.

#### Bug Fixes <a id="bug-fixes"></a>

* Fixed a bug so set variables don't crash when no trackerProperties object is available.

## June 5, 2018 <a id="june-5-2018"></a>

### Adobe Analytics Extension 1.3 <a id="adobe-analytics-extension-1-3"></a>

#### Features <a id="features-1"></a>

* Updated Adobe Analytics extension to support [AppMeasurement 2.9](https://marketing.adobe.com/resources/help/en_US/sc/appmeasurement/release/c_release_notes_mjs.html).
* Added "Make tracker globally accessible" feature in the Adobe Analytics extension, which enables the tracker to be scoped globally under `windows.s`.

**Bug Fixes**

* Fixed a bug that caused list view to reset when returning from detail view
* Fixed a few bugs to improve loading of resources in the revision selector
* Fixed a bug where multiple rules were overwriting s.events in the Adobe Analytics extension

## March 20, 2018 <a id="march-20-2018"></a>

### Adobe Analytics Extension 1.2 <a id="adobe-analytics-extension-1-2"></a>

#### Features <a id="features-2"></a>

* Updates AppMeasurement.js to 2.8.0
* Adds support for server-side forwarding

## February 8, 2018 <a id="february-8-2018"></a>

### Adobe Analytics Extension 1.1 <a id="adobe-analytics-extension-1-1"></a>

#### Features <a id="features-3"></a>

* AppMeasurement has been updated to version 2.6
* The initialized Analytics tracker is now exposed through a shared module in the Launch extension so other extensions can include code to interact with it.

#### Bug fixes <a id="bug-fixes-1"></a>

* Fixed an error in the Adobe Analytics Extension that caused "Error, missing Report Suite ID in AppMeasurement initialization" to appear in the browser console.

