# Aemulo 2.0 Release Notes

After three years of development I can finally start an Aemulo 2.0 beta. This update marks a major milestone for the future of the app. Over the past three years I have been working away at creating my own version of nfcd. Gone are the days of "Failed to connect to nfcd" errors. This long process involved writing my own drivers, libraries for working with many different specifications and protocols and of course a lot of caffeine. 

This major change brings two amazing benefits to Aemulo. Firstly, something people have wanted for a long time, Trollstore support. Secondly I can now begin work on much finer emulation and reading. 

Testing for Aemulo 2.0 is going to take a little while and I've decided to do it in the open. The beta builds will not have any DRM. Distribution of releases without consent from myself is not permitted. Below is the changelogs for each version including what features will be enabled and bugs fixed.


## Build 792
- Create a Tag Info view and option to save tag.
- Reading EMV Cards (Bank Cards) is significantly faster.

## Build 631
- Fix regression where socket connection can't be made on devices prior to iPhone 12.
- Fix bug where the session cancel button caused a hang.

## Build 589
- Fix the bug on iPhone 12/13/14 where connections could not be made.

## Build 563
- Fix a bug where a failed chip connection would result in an app crash.

## Build 548
- The first public build of Aemulo 2. Primary objective for this build is testing reliability of drivers across multiple different device types, versions and jailbreaks.
- Currently the UI is very limited and the only feature enabled is basic reading. This is by design and more features will be enabled over the next few days and weeks.
