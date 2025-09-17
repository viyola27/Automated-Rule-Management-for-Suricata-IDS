This is a Python Script with the following functionalities:
  Update: Option that downloads rules to the 'rules.DB' from URLs listed down in the 'repos.DB' within MySQL or any equivalent database.
  
  Push: Option that appends all the downloaded rules available in the 'rules.DB' to the either '/var/lib/suricata/rules' or '/usr/local/etc/suricata/rules', and also enable these new rules under 'suricata.yaml' configuration file.
  
  -If the last 'Push' was done 5-hours before, then the Python script should automatically Update the rules and Push it to the Suricata Rule Directory.
