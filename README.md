# high level workflow

identify doctors -> collect public domain coi information -> do something with it

# things done

wget https://files.digital.nhs.uk/assets/ods/current/epraccur.zip

unzip epraccur.zip

grep  "HURLEY GROUP" > hurleygps.csv

added first names manually where discoverable via google

fetch results from open corporates for names in our hurleygps csv and save result as a json
https://github.com/drcjar/wptd2/blob/master/wptd-opencorporates.ipynb

discovery that names are not unique identifiers

refined UI

added feature to declare something on someone

import directorships from opencorporates

# resources

see resources.md
