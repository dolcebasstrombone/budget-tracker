# budget-tracker

```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

use indexed db for offline, see 18.4
use service worker, see 19.4
add service worker to root of /public
manifest.json will have name, short_name, icons, theme_color, background_color, start_url, display
deploy to heroku using mongodb atlas
screenshot of app in readme

submit live page and repo
```