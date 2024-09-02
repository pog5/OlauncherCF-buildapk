# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### 🚀 Features

- *(translation)* Manually select language
- *(permission)* Remove internet permisisons, and everything that needed it
- Change text size
- List hidden apps
- Option to set language from system settings
- Option to set language from system settings
- Changelogs for v9
- Toggle date and time independently (#88)
- Add korean to settings
- Implements #82 (#136)
- Implement #102 (#160)
- *(german)* Update german string (#175)
- Replace some texts with images, enable uninstall of apps throug… (#204)
- Add two new actions: show recents and open quick settings
- Add swipe up gesture
- Add toggle for "open apps automatically" (#236)
- Add vietnamese
- Generate changelog with git cliff

### 🐛 Bug Fixes

- *(landscape)* Add language menu to landscape layout xml
- Fix double tap2lock
- Text size string
- Add layout to landscape-layout
- Add layout to landscape-layout
- *(settings)* Language list doubled
- Remove strings, use resources
- Use packageName for applias identifier instead of appLabel (#103)
- Hidden apps string hardcoded (#126)
- Set app language to system language (#128)
- Swipe app names black if not set
- Home alignment when click area is exetended (#176)
- Remove non-free dependencies
- *(homescreen)* This fixes the homescreen alignment bug (#185), while also being a general code improvement commit (#187)
- *(homescreen)* Place apps that are only in work profile on home screen (#188)
- German translation (#191)
- Move 'backToHomeScreen()' to onResume to not show home shortly before opening an app
- #172
- Set swipe right app
- Set app name right when it is added to the home screen, not just at showing the fragment (#202)
- Version number
- Work icon size and work icon position
- Text size in settings
- #209
- This improves a lot of code concerend with locking the screen. This fixes #180
- Build singed apk (#239)
- Crash on double tap gesture
- Fix crash on keyboard enter (closes #244)
- #251
- Tip not beeing removed; refactor: simpify firstOpen variable
- Double tap app name (#265)
- Backup
- Change log action
- Release action
- Name in relase action
- Release action
- *(CI)* Release action
- *(CI)* Changelog generation
- *(CI)* Changelog
- *(CI)* Changelog

### 🚜 Refactor

- Migrate to jetpack compose (#30)
- Replace string with string resourece (#97)
- Improve text resize behaviour and set broader limits (#207)
- Replace deprecated function calls
- Adapt translation files
- Use different method of opening quicksettings (thanks @The-Repo-Club)

### 📚 Documentation

- *(translation)* Add italian translation

### 🎨 Styling

- Deutsch -> german
- Reorder langs in readme
- Clarify strings
- Code clean up
- README
- Remove dead code

### ⚙️ Miscellaneous Tasks

- *(version)* Update version code
- Clean up code
- Change deprecated code
- Remove unused strings
- Remove more ads
- Removed more unused strings
- Removed even more unused strings
- Removed unused constants and xml layout
- Remove mode dead code
- Change version code
- Add pull request template for translations
- Rename translation template
- Rename pull_request_template
- Add version number to settings to improve debugging
- Change version code
- Version number, preapre for next release
- Bump version number
- Update version number
- Version number
- Version number
- Version number
- Update dependencies
- Update dependencies
- Version number
- Version number
- Version number
- Version number
- Version number
- Version number
- Version number
- Version number
- Version number
- Issue templates
- Version number
- Version number
- Version number
- Version number
- Version number
- Version number
- Version number
- Bump version number
- Replace images
- Update english f-droid description
- Remove unused file
- *(CI)* Clean up old changelogs and auto generate changelogs

### ◀️ Revert

- Settings text changin size (i guess it was better as it was before)
- Use Scrollview instead of jetpack compose in settings (to fix scroll behavior)

### Add

- European Portuguese (#68)

### Fixed

- Crash on initialising navController in MainActivity
- App click listener in app list
- Search view text color
- Wallpaper issue in Marshmallow (Android 6.0)
- App start crash in Android 8.0
- Apps blinking when home button pressed
- Not showing date if phone is set to 24 hour time format
- App drawer closing unexpectedly when swiping after partial search
- Default wallpaper not working
- App list refreshing unnecessarily
- Theme change glitch on cold app start
- Home apps not changin color on pressed
- Extra space after apps when right aligned
- Non-transparent navigation bar in Android 10
- Gravity issue in home apps text
- App list not updating immediately after install/uninstall
- Not showing the triple lock message
- Nav bar not showing in certain conditions
- Hidden apps set getting empty
- Crash when a hidden app list contains an uninstalled app
- Home apps not opening if userhandle is empty
- Crashing while opening dual/cloned apps
- Some work apps not opening
- Wallpaper worker not cancelled when setting black wallpaper
- Some apps not being added on home screen
- Screen timeout resetting to 30 seconds if screen timeout lock is enabled
- Some calendar apps not showing up
- Showing message dialog again and again
- Pressing enter not opening the first app in list
- Daily wallpaper not updating correctly
- App drawer swipe down to dismiss not working sometimes

### Refactoring

- Moved some logic from view to viewmodel

### Updated

- List of fallback wallpaper urls

### Build

- Add build action
- Update build action
- Update kotlin version
- Setup apk signing
- Apk signing
- Fix
- Fix variable
- Trying out something. Maybe I understand the docs wrong

### Release

- Version number

### Teset

- Fix serialize test

### Translations

- Add translations for Lithuanian (#230)

<!-- generated by git-cliff -->
