# IggyBot
IggyBot currently has five main features.
- Submitting prey to the prey backends
- Submitting herbs to the herb backends
- Checking the prey count
- Checking herb storage
- Searching up details for specific herbs
- WIP - Weekly staff reminders

IggyBot is written in python and uses the Google Sheets API and Discord API.(API’s are software code that enables communication between different applications. Think of it as letting Google Sheets code talk to my code. IggyBot is running on Google Cloud Console which is the interface for GCP (Google Cloud Platform)’s hosting services. 

# Running on the Cloud
IggyBot runs on GCP( Google Cloud Platform) which you should be able to access if you have access to the service account. Just follow this video, it explains it better than I can: [Host Discord Bot on Google Cloud for FREE ! No limit 24/7 Online](https://www.youtube.com/watch?v=RfJUm-LKNBw&list=WL&index=8) (Skip to 1:05 if you still have access to the service account)
If access to the service account is gone then just watch from the start. The video is a bit dated but some simple googling should fix that.


# Running Locally 
1. Click the big green button that says "Code" either download the ZIP file or clone the repo. 
2. Download python if it's not already on your system
3. Enter the repo on your terminal( a combo of `cd` and `ls -al` will get you there) and run `pip install -r requirements.txt`
5. Do python iggyBot.py and if it runs without errors you are good.
  
**NOTE:** The other file you need for the google API access and the bot token are in #techinal in the thread "prey/herb submission bot" in the pins

https://docs.google.com/document/d/1XDTgs8LkHStqlmMvqYTzX5OGDCn8L2c9AYFOk7-p7F0/edit?usp=sharing
