# high level workflow

identify doctors -> collect public domain coi information -> do something with it

# things done

wget https://files.digital.nhs.uk/assets/ods/current/epraccur.zip

unzip epraccur.zip

grep  "HURLEY GROUP" > hurleygps.csv

added first names manually where discoverable via google

fetch results from open corporates for names in our hurleygps csv and save result as a json
http://localhost:8888/notebooks/wptd-opencorporates.ipynb

# resources

see resources.md
