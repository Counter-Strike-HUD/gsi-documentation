# :file_folder: goldsrc-gsi AMXX commands

We need a few AMXX commands which will help the streamer to fully controll and get specific data for him.

## Access
Only players with flag `l` can controll the commands.

## Commands
**gsi_set_streamer** *steamid/id* - Decides which player will get the GSI data. When observer get selected, his POV player will be provided in the GSI under `player` field (current specatated player).

**gsi_get_streamer** - writes nick and steamid of the player which is observer

**gsi_live** - It tells the plugin that game has started, `phase`, it can't be `warmup` anymore.

**gsi_set_uri** - Sets remote stream URL. Config value will get overwritten in this game session.

**gsi_set_heartbeat** - Sets the update frequency. Config value will get overwritten in this game session.

**gsi_get_uri** - Gets current remote stream URL.

**gsi_get_heartbeat** - Get the update frequency.