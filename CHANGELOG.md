# Change Log

All notable changes to the "sync-scroll" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [2.0.0]

- Extension not enabled by default (configurable using `"syncScroll.enabled": true`)
- Default scroll mode to normal (keep persistence)
- Bump dependencies
- Cleanup whole repository (lint + old files)

## [1.3.0]

- Add command to jump to corresponding position in the next panel
- Add command to copy selections to all corresponding positions.
- Fix the issue of the output panel which shouldn't be involved in the scrolling sync.

## [1.2.0]

- Add corresponding line highlight feature.
- Fix offset issue when switching from OFFSET to NORMAL mode.

## [1.1.1]

- Persist the toggle state and mode
- Fix back and forth scroll issue in diff(selecting file to compare)/scm(viewing file changes) case.

## [1.1.0]

- Add sync mode to choose different ways to scroll.
- Get rid of the scrolling delay.
- Fix the issue that cannot toggle on/off when not focus on any editor.

## [1.0.0]

- Initial release of Sync Scroll
- Splitted panels into scroll synchronized mode.
