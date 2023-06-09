## LuxmedHunter
Simple tool to notify about available slot in LUX MED medical care service using pushover notifications.
___
My twist of Luxmed appointments notifier, inspiration taken from:  
https://github.com/pawliczka/LuxmedSniper  
https://github.com/m-grzesiak/yalma

Mainly done to accomplish the same things as their projects but to train my skills in more Pythonic & OOP ways.  
And to use dataframes. I love dataframes.
___

To use it, create `config.yaml` based on the `config_template.yaml` with your details and run the `luxmed_runner`.  
You shall use polish letters/alphabet for names, capitalization doesn't matter. The name of service, city, doctor should be a string, as visible in the phone app. To help, the bot saves
list of cities and services to text files on the first run. `doctor_name` and `clinic_name` are optional - to
dial in the search (they can be left empty).
___

Please be advised that running too many queries against LuxMed API may result in locking your LuxMed account.
Breaching the 'fair use policy' for the first time locks the account temporarily for 1 day.
Breaching it again locks it indefinitely and manual intervention with "Patient Portal Support"
is required to unlock it.
