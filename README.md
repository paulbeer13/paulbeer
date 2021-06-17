# Project-Challenge
## Import Requirements Python.
Voordat de code werkt, is het nodig om de volgende libraries te importeren.

* import discord
* from discord.ext import commands
* from riotwatcher import LolWatcher
* import json


## Discord Bot.
Vervolgens heeft de discord bot 2 commands.

1. .ping
2. .stats

### .ping
Wanneer dit word ingevoert reageert de discord bot met pong en de reactietijd in ms.

### .stats
Bijvoorbeeld: .stats Speler123 haalt de ingame gegevens van Speler123 op uit de League of Legends API.
Vervolgens weergeeft hij de divies, tier en winrate van de ingegeven speler.
