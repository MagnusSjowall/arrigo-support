---
layout: main
title: Releases - Frontend
description: Change Log
---
# Change Log
## Next Releases

## 1.0.140

*2021-04-08*

- Hotfix: Add building name to CMA-input plus some restyling (#588)
- Hotfix: Add more descriptive placeholders to meter inputs (#589)
- Feature: Queries/Mutations errors handling (#581) 
- Fix: QR scanner (#586) 
- Hotfix: Fix issue with folder configs that was not cleared when logging out of Arrigo (#587)
- Fix: Feature toggle Load/Save signals feature (#583) 
- Feature: ETreport addons (#570) 

## 1.0.136
- Minor improvements
- Hotfix: Added path to static resources (#584)
- Hotfix: Portgroup with sortorder, edit order only selected terminal portgroups (#575)

## 1.0.130

*2021-03-29*

- Hotfix: YMS History should not display closed or welcome events (#573)
- Hotfix: Undefined variables in animation views (#572)
- Hotfix: Closing time for YMS screen (#571)

## 1.0.127

*2021-03-24*

- Hotfix: No longer cutting edges on add menu (#569)
- Hotfix: Plus button no longer overlaps delete button (#568)
- Hotfix: Symbol cache in listview (#566)
- Hotfix: Filling in User correctly when entering admin view (#564)
- Hotfix: Numeric Maneuver Backspace Fail (#563)
- Hotfix: More contrast on radio buttons and checkboxes (#562)

## 1.0.123

*2021-03-17*

- Hotfix: Bump CW2 to fix button icon centering in Views (#565)

## 1.0.121

*2021-03-12*

- Hotfix: Search in selectlist on meter (#558)

## 1.0.120

*2021-03-09*

- Hotfix: Web socket connectivity in views (#554)

- Hotfix: Menuitems will now grow in height if they are really long. (#552)
- Hotfix: Confirmation when creating new building or meter (#550)
- Hotfix: Added translation for meter icon hovering (#551)

## 1.0.118

*2021-02-26*

### Fixes/Improvments
- Hotfix: Font too big in area Views (Issue: 19275) (#546) 
- Hotfix: Factor as default on meter (#544) 
- Hotfix: Default to correct date in meterDetails panel (#545)
- Hotfix: Add indicator to MeterValueRow instead of italic numbers (#543)

## 1.0.114

*2021-02-24*

### New Features
- Feature: Alarm signals collection (#515)
- Feature: CSV export in charts (#517)
- Feature: Make linkicon accept full url-paths as feature. (#526)
- Feature: Global CSV Export (#531)
- Feature: Custom default route (#529)
- Feature: Chart axis/grid improvements (#532)
- Feature: Historical charts help side panel (#536)
- Feature: Multi language support (#540)

### Fixes/Improvments
- Fix: Calculated meters drag and drop (#535)
- Fix: Add condition for language change in translationManager (#542)

## 1.0.113

*2021-02-22*

- Hotfix: YMS new messages (#538)
- Hotfix: Fix overflow issue with AlarmRow title text (#537)
- Hotfix: View feature now expands more dynamic to viewport (#534)
- Hotfix: Allow ETreport to show temperature with decimals (#533)
- Hotfix: YMS Issues from Feedback (#530)

## 1.0.109

*2021-02-12*

- Hotfix: Rotate2D stopped working after changes in cw2 package 1.0.30 (#528)
- Hotfix: Indication in meters list (#524)
- Hotfix: Refetch navigation list data on updates. (#525)
- Hotfix: Add missing translations to UserCredentials in admin view (#520)
- Hotfix: Fix reload loop when changing API's (#522)
- Hotfix: Bump CW2 to fix issue when loading non-svg symbols (#523)
- HotFix: Hiding User Admin and Collection cart from EMS. (#521)
- Hotfix: Corrected LinkIcon order (#519)
- Hotfix: Resolve async issues with large SVGs (#518)
- Hotfix: Solved dead image due to pop (#516)

## 1.0.98

*2021-02-04*
### New Features
- Feature: Added toolbox feature to Calculated meters (#472)
  When custom formula is used, a small set of logic in a toolbox is presented
- Feature: Account changer (#464)
	If you are logged in on multiple accounts, you have an option to select account during startup.
- Feature: Extension of clear functionality for FilterFeature (#492)
	Improved Reset options in filters
- Feature: User admin view EXOScada (#491)
	Finally you can get User Administration View from Arrigo Local! Feature is located at top right in popupmenu on user avatar.
- Feature: Fix a typo in the cookie string (#502)
	Improved browserupdate when new version exist on server
- Feature: Chart Ruler and Controls (#501)
	Improved data detail in charts, hover to se details of data points
- Feature: Convert command bar (#507)
	Conversion of command bar element in views is now supported
- Feature: Collect signals for chart (#506)
	Add signals to chart view. For now Digital and Analog history values is supported.
	Alarm history and Real time values is near future.

### Fixes/Improvements
- Fix: Sidepanel overlapping content (#446)
  Sidepanel pushes content so overlapping of information is avoided. All buttons is visible always.

- Fix: Scanning QR with meternumber should now redirect correctly (#460)
- Fix: Added verification feedback to Calculated meters (#459)
    You will be notified in UI.
- Fix: Moving the pin on map will now trigger a confirmation box (#462)
    Cards with map and location will now confirm your reposition of the map pin.

- Fix: Widgets patch (#461)
    Minor fixes.
- Fix: Navigation node loading (#469)
    Sometimes the tree got stuck in loading state. 
- Fix: Meterslist offline support (#471)
    Improved offline experience
- Fix: Offline mode notification (#477)
    Automatically close offline notifications
- Fix: Auto scroll input into view (#481)
    Scroll meter value input into view, if not visible.
- Fix: Reset inputs to default after offline change of value. (#483)
    Reset to defaults after offline mutation.
- Fix: Network errors update (#476)
- Hotfix: View observer & Network errors (#490)
    Avoids broken pictures in animation views due to long session time
- Hotfix: Fixed a stylingissue in the Meter Details calendar (#509)
- Hotfix: Added null check in admin view (#510)
- Hotfix: Increased width of meter value inputs on phone (#511)
- Hotfix: Added a min-height to the folder header on mobile. (#512)
- Hotfix: Pass real null value instead of string (#513)

## 1.0.94

*2021-01-27*

### New Features

- Feature: Added toolbox feature to Calculated meters (#472)

**Fixes/Improvements**

- Fix: Meterslist offline support (#471)
- Fix: Offline mode notification (#477)
- Fix: Auto scroll input into view (#481)
- Reset inputs to default after offline mutation. (#483)
- Fix: Network errors update (#476)
- Hotfix: Allow longer meter texts in MeterRow (#495)
- Fix: Reading validation now compares the correct values (#494)
- Hotfix: Remove validation while offline (#498)
- Clear all notifications after discard or sync offline mutations
- No validation of readings while offline
- Hotfix: Auto-reload application if new version has been published to the server (#497)
- Add initial version check middleware to GraphQLManager
- Remove unused ApolloWrapper component
- Add new translations for Version detection
- Display notification and reload browser if new X-Frontend-Version header mismatches with value in localStorage
- Add new LongPressContainer component to show a notification of current version number
- Add link to release notes from version notification
- Pass a hard reload argument to location.reload to assure source reload from server
- Update version message
- Tweek timing of logo long press
- Update public/translations.json
- Hotfix: Clear all notifications after discard or sync offline mutations (#496)
- Hotfix: Null check X-Frontend-Version header on login (#499)
- 

## 1.0.90

*2021-01-22*

### New Features
Account Selector
Now displaying an Account Selector when switching between different accounts in multiple tabs

### Fixes/Improvements

- Meter Value Reading validation now allowing inputed value to be the same as the previous one
- Added translations to Meter Value validation
- Generic formatting of Numeric input values
- Improved Offline Sync view, and redirects when going online again
- Scrolling inputs into view when using number inputs
- QR scanning
  QR scanning should now redirect to the correct meter when scanning a QR code containing a meter number
- Maps
  Moving the building/meter location-pin on the map will now trigger a confirmation box, this is to prevent unintentional clicks in the map, resulting in changing location.
- Feedback when verifying formula for Calculated meters
  Now giving some additional feedback when verifying a formula for calculated meters.
- Offline mode
  Now supports offline mode for meter-list.
- Other
  Several bugfixes for added stability, security and performance.

## 1.0.82

*2021-01-13*

### New Features

**Mobile Overlay Panel**
– Allows for listed content to be displayed in a more mobile-friendly panel on mobile devices.
The panel pops from the bottom in overlay mode to get all the focus until action is taken.

**Offline support in MetersList**
– When using the `MetersList` offline, all the mutations are now stored until the device is online again. When online again, action is required to determine which mutations to sync.

**Manual Meters Filter**
– A checkbox that when ticked, filters out only the manual meters in `MetersList`

**Permissions on Entities**
– Permission checks on entities. Determines if the user is permitted to perform CRUD operations.

**Manual Meter Presets**
– Possibility to add a presets to manual meters. Presets determines if the default input type should be “Consumption” or “Reading”, and if the default resolution should be “Year”,“Month”,“Day” or “Hour”.

**Connecting Buildings To Users**
– Interface to set which buildings a user is permitted to see and handle.

**Calculated Meters**
– Updated interface for the old Calculated meter feature. Now with drag and drop support. (Only available after account has been migrated)

**Account changer**
– Solves problem with being signed in to different accounts on different tabs. The `AccountChanger` allows to be able to pick which account to proceed with.

**DynamicListElement new types (Text & TextSelect)**
– `DynamicWidgets` accepts new text element types, with prefilled options to be selected on edit mode

**DynamicWidget refresh on hash update**
– `DynamicWidget` loads content from API, so that if there's a change on widget file configuration the widget updates by itself without the need of refreshing the page

**DynamicWidget access level**
– Users are only able to update `DynamicWidget` element values if they have required access level

**Applied filters indicator**
– Visual indicator that is displayed near the filter toggle so the user knows there are filters applied

### Fixes/Improvements

- Format of numbers depending on localization.
- Meter Reading validation on `MeterChanges`.
- `ClimateDataNormalYears` dataset merge. (fixes error with duplicate months being displayed)
- Remove possibility to perform meter change on calculated meters.
- `MetersList` performance enhancements. Enable caching of queries, giving instant feedback.
- `SidePanel` rendering on iPhone (Safari specifically)
- Correct indication of locked meter values.
- Display building connection in `MeterDetails` panel
- Change of `ET-data` x-values for reference lines.
- Remove swipe-button on mobile devices.
- General mobile device adaption.
- Default to current time when creating meter readings.
- Deletion of metervalues in `MetersList`
- Performance optimization `EnergyWidget` query
- Add missing metervalue indicators, depending on meter value type. (prognosis, calculated etc.)
- Clear navigation redux store on logout. This prevents error when switching accounts.
- Verification feedback to Calculated meters
- Scanning QR with meternumber now redirects correctly
- Confirmation when moving Building pin
- Redirecting to `reading` or `consumption` depending on default preset upon scanning QR code
- Loading of required features' packages based on routes and folders' configurations (`PackageLoader` patch) improvement
- Node libraries versions upgrade
- CW2 package update
- Several fixes/improvements on Arrigo Views features
- Re-rendering issues caused by folder switch swipe function (mobile feature) fix
- Service worker resets on version bumps to prevent cache from now showing new content
- Notifications layout revamp
- `DynamicWidget` errors presentation improvement
- Folder title on `Dashboard` inherited widgets
