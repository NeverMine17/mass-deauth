DO NOT USE THIS SCRIPT AGAINST NETWORKS YOU DON'T OWN OR DON'T HAVE PERMISSION TO ATTACK!
-----------------------------------------------------------------------------------------

If you need to reach me for whatever reason, regarding this script, you can email me <rfkiller@openmailbox.com>, or via the GitHub [page] for this script. This script was originally heavily influenced by [Leg3nd's Elegant Mass DeAuth Script], and greatly improved with help from [Trevelyn] of [WeakNet Labs] as well as some suggestions by Justin Welenofsky (hope I spelled that right).

RFKiller's Mass-Deauth Script TODO list:
- [ ] fix issue #1 (variable `$ourAPmac` being ignored)
- [x] add run-as-root check
- [x] check for required programs before running
- [x] ask for user input so user doesn't need to edit script manually before running it.
- [x] add commandline arguments/options
- [x] give users choice of using commandline options or being asked for variables at runtime.

### Usage: 

    ./mass-deauth.sh [OPTIONS] [ARGUMENTS]

### Example: 

    ./mass-deauth.sh -d 10 -w 30 -i wlan0

If you have any suggestions, bug reports, "feature" requests, etc., - contact me and I will do what I can. Don't forget to stop over at [WeakNet Labs][4] and say "Hi" to Trevelyn! He is developing some really interesting projects, so check them out while you're there!

  [page]: https://github.com/RFKiller/mass-deauth
  [Leg3nd's Elegant Mass DeAuth Script]: http://jasagerpwn.googlecode.com/svn/trunk/src/deauth.sh
  [Trevelyn]: https://www.facebook.com/80211hacker "Trevelyn"
  [WeakNet Labs]: http://weaknetlabs.com "WeakNet Labs"
