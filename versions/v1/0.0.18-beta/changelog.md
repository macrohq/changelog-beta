# v0.0.18-beta

### 🪲 Bug Fixes
 - A recent change made the "connect your google calendar" button disappear on the home screen, requiring people to connect in preferences. This is now updated along with some other GCal fixes.
 - We were sending a lot of API calls so we've consolidated that a bit to prevent server overload.
 - Airtime was broken for a fwew people due to simultaneous socket connections. Now, we ensure only one connection exists so airtime should no longer be at 0%!
 - The video got a bit blurry at times with this new Zoom SDK. We've added some resolution updates to prevent this from happening.
