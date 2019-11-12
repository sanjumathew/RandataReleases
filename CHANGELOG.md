## <small>[1.2.2 (2019-11-11)](https://github.com/sanjumathew/Randata/releases/tag/v1.2.2)</small>
#### Bug Fixes
* Fixed issue with Auto Updater

#### Features
* Added control over downloading and installing updates.

## <small>[1.2.1 (2019-11-08)](https://github.com/sanjumathew/Randata/releases/tag/v1.2.1)</small>
#### Bug Fixes
* Added check to detect renderer(only on live reloading) when creating predicates folder.
* Fixed issue where confirmation message was shown for unmodified files while closing all tabs.
* Added duplicate check while pasting schema.
* Removed blocking success messages and added toast instead.
* Added custom progress bar since ngx-bootstrap was not behaving properly for lesser values.

#### Features
* Added column clone functionality.
* Major Change: Added Tab System for enabling multiple project creation simultaneously.
* Added logic refer column names in predicates.
* Modified Predicates modal to predicates manager.

## <small>1.2.0 (2019-10-18) (Unpublished)</small>
#### Bug Fixes
* Fixed issue with CSV schema import when there were spaces between commas.

#### Platform Updates
* Updated Angular from v7 to v8 and Electron from v4 to v6.

## <small>[1.1.1 (2019-05-20)](https://github.com/sanjumathew/Randata/releases/tag/v1.1.1)</small>

#### Bug Fixes
* Fixed issue with devtools opening automatically
* Fixed issue while canceling save and open file dialog.

#### Features
* Added Hotkey detection.

## <small>[1.1.0 (2019-05-19)](https://github.com/sanjumathew/Randata/releases/tag/v1.1.0)</small>

#### Bug Fixes
* Reimplemented data generation to avoid blocking event loop.

#### Features
* Added Auto Update

#### Performance Improvements
* Made improvements to electron detection for debug purposes.
* Added loader and progress bar while data is being generated.

## <small>[1.0.0 (2019-05-10)](https://github.com/sanjumathew/Randata/releases/tag/v1.0.0)</small>
Initial Release
#### Features
* Generating random data. 
* Ability to preview data.
* Ability to provide blank percent.
* Ability to add predicates.
* Ability to save data to an external file.
* Ability to open, save, save as, copy or paste table schema. 
* Ability to test and attach predicate to generated data.
* Ability to use RegEx to customize data generation.

