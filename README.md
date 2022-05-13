# Qualys_SumoLogic
Qualys to sumo logic


First, you will need to open up the Qualys Config file and figure out what you need to fill this in. This should only be one time to test the functionality of the script.

After you have the config file attempt to run the script and pull the report and upload to a sumo logic hosted collector.

If all of this works it is highly suggested to put this script in an AWS lambda function, where you save the contents of the config file in KMS and call that from the function.
