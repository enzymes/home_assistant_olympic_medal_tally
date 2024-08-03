# Olympic Medal Tally with Home Assistant and Node RED
Home Assistant can keep a medal tally for your country and notify you of medal wins - needs Node RED.

- Announces on your smart speaker (and lights flashing in your country's colors) when there's a medal win for your country
- Lets you know what type of medal has just been won and what place you are on the medal tally (and if you've changed rankings)
- Notifies you on your mobile's Home Assistant app for when your country wins another medal (plus their ranking on the medal table)
- Checks for medal updates every 5 minutes
- Switch to turn notifications on or off

* Read setup notes below screenshots for configuration you will need to do *

<img src="https://github.com/enzymes/home_assistant_olympic_medal_tally/blob/main/olympic_medal_tally.png">

<img src="https://github.com/enzymes/home_assistant_olympic_medal_tally/blob/main/olympic_medal_notification.png">

## INITIAL SET UP CONFIGURATION YOU NEED TO DO IN NODE-RED

Look in the comments for spots where you need to make edits to the Node RED flow.

- Choose which country you are tracking
- Update URL for Paralympics
- Update URL for hosting location of "win.mp3" music and "applause.mp3"
- Set up notifications for your mobile
- Set up announcements on your smart speaker (we have a Google speakers)
- Flash lamps in your country's colours (Australia is green and gold)

## HOME ASSISTANT CONFIGURATION

Use the YAML files in your system for initialisation of variables required 

