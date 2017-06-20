# Utilu Nightly Tester Tools

3.7.1.4 / 2017-06-20
====================

 * Reverted default extension separator from comma to new line, except for input fields because they don't support newlines
 * Added a hidden preference nightly.extensionSeparator to optionally customize the extension separator
 * Marked extension as multi-process compatible
 * Updated maxVersions for applications
 * Minor changes and improvements

3.7.1.3 / 2016-09-23
====================

 * Improved Customize Title bar Variable Application Update Channel
 * Updated maxVersions for applications
 * Minor changes and improvements

3.7.1.2 / 2016-08-31
====================

 * Optimized the order of the Customize Title bar Variables
 * Added Customize Title bar Variable Application Title and Version
 * Added Customize Title bar Variable Application Display Version
 * Added Customize Title bar Variable Application Beta Version (only filled when applicable)
 * Removed Gecko Build Identifier, since it used PlatformBuildID, just like XUL Platform Build Identifier
 * Removed Gecko Version, since it used PlatformVersion, just like XUL Platform Version
 * Removed unused image file
 * Updated maxVersions for applications
 * Fixed indenting issue
 * Add pushlog feature for all branches
 * Use comma between entries when copying the list of extensions
 * Updated development section of readme and about:nightly
 * Changed the text about where bugs and feature requests are filed in the readme file
 * Applied new default style to all changelogs

3.7.1.1 / 2015-09-10
====================

 * Repository: Created a repository for Utilu Nightly Tester Tools
 * Changed extension name to Utilu Nightly Tester Tools
 * Changed extension ID to {8620c15f-30dc-4dba-a131-7c5d20cf4a40}
 * Removed all partially incomplete translations
 * Removed excessive white space before line endings
 * Removed unused variables module
 * Removed references to End-of-life (EOL) extensions
 * Fixed indentation by always using spaces and never using tabs
 * Removed copy to Pastebin functionality which had become non-working due to API changes
 * Replaced non-working copy to Pastebin functionality by copy text to Clipboard functionality
 * Added spaces between the extensions when copying the list of extensions to the Clipboard
 * Removed non-working image hosts
 * Increased the size of the Customize Title bar window
 * Improved default Customized Title bar title
 * Optimized the order of the Customize Title bar Variables
 * Added Customize Title bar Variable Application Version Pretty
 * Added Customize Title bar Variable Application Update Channel
 * Added Customize Title bar Variable Application Update Channel Pretty (Release, ESR, beta, Aurora, Nighty, Default)
 * Added Customize Title bar Variable Application Version and Channel
 * Added Customize Title bar Variable Number of visible tabs
 * Fixed missing vendor in Title bar Customization in Thunderbird
 * Marked Crash me options which do not cause a crash as such
 * Removed the unused CSS files
 * Cleaned and optimized the remaining CSS files
 * Updated and synced feature lists
 * Updated maxVersions for applications
 * Minor changes and improvements

3.7.1 / 2015-05-26
====================

 * The extension is now signed. Mozilla began requiring all extensions to be signed in order for them to be installable in Release and Beta versions of Firefox. Signing is done through addons.mozilla.org (AMO) and has become mandatory for all extensions.

3.7 / 2013-10-29
====================

 * Include sv-SE locale from BabelZilla (#160)
 * Move extension appmenu entry for Firefox into the secondary pane, and place under Addons menu (#157)
 * Change toolbar button's behavior to offer copy to clipboard if no text box is selected (#153)
 * Add "Build Identifier" Toolbar Icon to SeaMonkey's main window (#154)
 * Overlay Thunderbird's AppMenu (#100)

3.6 / 2013-08-06
====================

 * Include zh-CN locales from BabelZilla. (#143)
 * Make dtd entities for Customize Title bar more localization friendly. (#140)
 * Set file extension in filepicker to avoid silent overwrites. (#124)
 * Add basic Seamonkey support to title bar customization. (#31)
 * Fix for illegal characters in MPL 2.0 headers. (#133)

3.5 / 2013-04-25
====================

 * Use CurProcD as a fallback when referencing GRE specific files. (#115)
 * Detect the application version automatically and setup the right compatibility pref. (#52)
 * Favor the new nsIFilePicker::ShowAsync method in saveScreenshot(). (#112)
 * Remove usage of nsISupportsArray due to its deprecation. (#121)
 * Use getAddonsByTypes() to only retrieve extensions for getExtensionList(). (#94)

3.4 / 2013-02-19
====================

 * Use GreD instead CurProcD to reference GRE specific files. (#115)
 * Update checkCompatibility preferences for compatibility. (#103)
 * Add privacy context to saveScreenshot() due to Bug 795065. (#99)
 * Make columns of 'Customize Title bar' dialog's tree resizable. (#25)
 * Re-license under MPL2. (#39, #98)
 * Update 'Contributors' section automatically in about:nightly. (#58)
 * Don't register aboutNightly component for 'profile-after-change' notification. (#57)
 * Don't call callback function when iterating over Extension Manager's extensions list. (#88)
 * Include about:nightly in the extensions' menupopup for Thunderbird. (#56)
 * Let nightlyApp.openNotification() fallback to notificationBox in legacy Fx. (#81)
 * Open customize.xul (Customize Title bar) as a resizable window. (#55)
 * Add pushlog-to-tip menuitem. (#61)
 * Include changeset info in the Insert/Copy Build ID menuitem and in 'Customize Title bar'. (#65)

3.3 / 2012-05-02
====================

 * Repository: Transfer ownership of the extension from Mossop to the Automation Services team (#46)
 * Updates for extensions.checkCompatibility prefs up to 15.0a1 (#54)
 * Restart prompt for setting / resetting compatibility prefs is missing icon (#53)
 * Enable 'compatible by default' feature by not registering binary crashme components (#44)

3.2.2 / 2012-03-16
====================

 * Repository: Add Ant build script to build the extension (#35, #36)
 * Repository: Add binaries for crash me extension (#33)
 * Repository: Reorganize repository and documentation (#28)
 * Update list of contributors (#38)
 * Update maxVersions for applications (#37)
 * Allow title bar customization in Thunderbird (#24)
 * Version 3.1 loses ability to customize title bar with just window title (#18)
 * Enhance pushlog feature to support Aurora channel (#13)
