# megamekstats (1.0.1)
Pulls the current stats from a MegaMek server, such as logged-in users.

***

1.  To install the dependancies run:

        ./installdeps

2.   Run it the first time to set your preferences

        ./listusers

3.   To change the preferences later run:

        ./listusers prefs

4.   Add this to your crontab:

        crontab -e

        * * * * * /root/megamekstats/listusers > /dev/null 2>&1

# This will update the HTML page every minute. The html file has a refresh option which will pull in the new one every minute or so.

