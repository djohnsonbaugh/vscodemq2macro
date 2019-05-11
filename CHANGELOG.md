# Change Log

All notable changes to the "vscodemq2" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [0.6.0]
- Custom Icon for .mac and .inc - vscode-icons extension is a prerequisite.

## [0.3.0]
- Added /while
- Added recognition of unsupported commands from optional plugins
- Added various shortened versions of commands

## [0.0.3]
- Fixed Block Comments Bug - it was not working inside Subroutines
- Added /deletevar
- Fixed issue with /declare where default value was a variable reference

## [0.0.2]

- Added support for Variable labels having embedded variables - i.e. ${Junk${name}} - impacted /declare /varset/vardata/varcalc and variable references in general
- Fixed issue where commands that do some sort of modification /squelch would fail if preceeding a command that was a block like  /if () { } 
- Fixed issue in Formulas where (10*(1+3) > 1) would fail

## [0.0.1]

- Initial release