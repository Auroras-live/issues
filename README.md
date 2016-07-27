# Auroras.live Issue Tracker
This repo is used to track issues relating to Auroras.live, which includes the iOS / Android mobile apps, the Pebble watch app, as well as the API, the website, and other associated sites.

## Getting support
If you're famililar with GitHub, then feel free to create an issue about a bug you've encountered. If you've never used GitHub before and would like to report an issue, send an email to `support@auroras.live`. If you'd like to check on an existing issue, click ["Issues"](https://github.com/Auroras-live/issues/issues) above

## Feature Requests
If you'd like to request a feature, please email us at `support@auroras.live` first. The issue tracker is for reporting bugs, and tracking confirmed and existing bugs or feature requests.

## Good issue reporting
A good bug report covers a few questions:

 - **Who**: Or rather, _what device_ were you using? We need to know the device name (e.g. Nexus 5, iPhone 5 32gb) and what operating system (Marshmallow, 9.0.1 etc.)
 - **What**: Covers a few things:
   - **What** were you doing when the bug occurred? For example, "Trying to open the Cressy webcam image"
   - **What** network were you using? (e.g. 3G, 4G, WiFi, EDGE etc.)
   - **What** did you expect to happen? This is useful if the bug is not readily apparent
 - **When**: When were you trying to do the thing that caused the bug? For example "at 1:19am" or "After midnight on Monday". This helps narrow down times in server-side and client-side logs
 - **Where**: Where were you when you came across the issue? Were you in an elevator? In the middle of the forest? At the beach? At home? This is useful for diagnosing weather and phone reception issues
 
A bad bug report tells you nothing. If you dropped your car off at a mechanic and said "it's broken, can you fix it? Thanks, bye!", they'd stop you and ask a bunch of questions.

## What does and doesn't consitute a bug?
This app is built on information from the SWPC, with weather info from MET.no. As a result, some things aren't bugs with Auroras.live, but are actually problems with the source data. Examples of bugs and non-bugs may include:

 - Not a bug: The weather shows that it is raining, but it's actually sunny outside (incorrect info from met.no)
 - A bug: I'm in City X, but it's showing weather for City Z (possible issue with auroras.live)
 - Not a bug: The Kp in 4 hours is 3, but the forecast says it's 5 (forecasted data from SWPC, not calculated by us)
 - A bug: The Kp is showing as -1 (issue with auroras.live)

Eseentially, if it involves some off-looking data, it's probably the source that is causing the issue. If it looks outright wrong, that's probably on our end. 
