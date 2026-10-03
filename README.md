# megamekstats (1.0.0)
Pulls the current stats from a MegaMek server, such as logged-in users.

***

1.  To install the dependancies run:

        ./installdeps

2.   Add this to your crontab:

        crontab -e

        * * * * * /root/megamekstats/listusers > /dev/null 2>&1

# This will update the file every minute. The html file has a refresh option
# which will pull in the new one every minute or so.

