# MD-11 Bug Reports
This is the official bug report repository for the TFDi Design MD-11. You may report bugs relating to all of the aircraft systems, models and textures.


## What to Report
**Please report:**
 - WASM crashes (DIRTY state): identified by systems suddenly freezing and not responding to further input
 - Unusable autoflight (flight plans that cannot be drawn/flown, PROF behavior so bad you cannot continue, etc.)
 - Engine management issues (unresponsive/unusable throttle, unexpected shutdown, etc.)
 - Your general feedback on textures, sounds, and systems (keeping in mind that this is an early, in-development copy)
 - Usability/quality-of-life items (default mappings that do not work, etc.)
 
**Please do NOT report:**
- Minor systems inaccuracies
- Visual items

**Known issues/limitations:**
There are many. Among them are:
- The analog standby and ISFD currently coexist
- EFB does not control the aircraft
- AP VOR tracking is not implemented
- P3D version is not yet available
- Switches and buttons do not (yet) make sound
- This release includes only the GE passenger variant
- There are no lights, except for pressing the dome light button which will flood the cockpit with light
- Payload management is not yet available
- ~~Panel states do not work~~ (Fixed as of 0.6.0-alpha)

## Reporting Bugs
Before submitting an issue, you should verify that your issue [has not already been reported](https://github.com/invernyx/md11-bugs/issues?q=is%3Aissue+is%3Aopen+label%3Abug%2C%22verification+required%22). If it has, please add a comment to the existing issue instead of creating a new one with any further information you may be able to present.

To report a bug, please create a [new issue](https://github.com/invernyx/md11-bugs/issues/new/choose) using the respective bug report template. Using the incorrect template will mean that we don't have the information we require, so we may close the issue and ask you to refile it under the correct template.

## Stale issues
Issues will go stale if we have not received the information we required after 12 days. We will then bump you on the issue, letting you know the issue is stale. If we do not receive a response within 48 hours, we will close the issue and you will be required to resubmit.
