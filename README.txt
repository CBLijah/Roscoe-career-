PRO WRESTLING: THE JOURNEY — Launch Candidate
Roscoe Wallace / The Prodigy

WHAT THIS IS
A self-contained HTML career simulator containing the features through Phase 10.5,
plus a final integration patch removing the old 520-week (10-year) career limit.

HOW TO HOST USING GITHUB PAGES
1. Create a NEW GitHub repository for this game. Keep it separate from WEW.
2. Upload index.html to the repository's root directory.
3. In the repository, go to Settings > Pages.
4. Select Deploy from a branch, choose main and / (root), then Save.
5. Open the published Pages URL once GitHub reports deployment success.

LOCAL SAVES — IMPORTANT
The game uses browser localStorage. A save created while opening an HTML file may
not automatically appear at the GitHub Pages address, because that is a different
browser origin. In the OLD game first, use Save / Import > complete backup export.
Then in the hosted website use Save / Import to restore that backup.

Always download a new complete backup before switching versions or browsers.
Private/incognito modes, browser-data deletion, and different devices can lose
access to local-only saves. No automatic cloud sync exists.

WHAT WAS TESTED
- All 17 major site tabs loaded in a mobile-sized Chromium session, without JS errors.
- Version 11 backup inspection passed; tampered backup rejected.
- A fresh browser-instance reconstruction retained the saved career and world.
- Both career and world advanced successfully beyond week 520 to week 521.
- Game Health reported an intentionally inconsistent match record.
- Entrance > live match > final-bell flow passed, including mid-match reload,
  exactly one result recorded, and complete backup export.

NOT YET CERTIFIED
- Live GitHub Pages deployment and hosted import/reload have not been tested.
- Full multi-decade balancing and every legacy save format need additional testing.
- This is a playable launch candidate, not a claim that every possible scenario is bug-free.

Use of real wrestling promotion names in this project refers to a fictional,
alternate-history game simulation; it is not affiliated with those promotions.
