# esx_housing

Made it for ESX Legacy
This script hasn't been tested on previous versions of ESX, so compatibility is not assured.

[FEATURES]
- Players are able to disconnect in their house, at entering the server the house where he stayed in will load automatically.
- Highly optimized (0.01ms) (client), in server-side the database is loaded on startup, so the script uses the cached JSON for all internal queries.
- House sync interval, all houses are synced within the clients in real time, for the database, houses are being syncronized with Config.SyncInterval, by default every 1 minute, all the houses that has been changed, (keys, inventory, etc) are updated on the database instead of updating them for every single change.
- Almost everything configurable (prices, interiors, coords, keys).
- Players can give keys to other players allowing them to access his house in case he's not online, invites are working as well also owners have the option to reset the keys, sell the house in their [F5 Menu].
- Adminstration has a house creating menu.
- Houses can get removed automatically when they are unused for more time than allowed on the config.


- No logging is provided, you should add yours wherever you want to get things logged.
