# Meows For'bots Project
Primary purpose of this project is both to add some fun functionality to Twitch streaming, but also incorporating information from the Twitch API into a Discord bot. In essence, this would be two different bots, one for Twitch chat and one for Discord.

# Functionality Goals
## Discord
- Linking fun stats from Twitch chat to Discord
- Announcing Go Live notifications
- Minigames (may start as simple as high-low, but can program more complex games)
- Full configuration (server specific mentions, multiple channels, toggling functions)

## Twitch
- Track extra gimmick for subscribers/followers (i.e. collecting "items" for each month of subbing)
- Song request handler (Spotify API?)
- Prediction / Ads / Poll Announcement
- Timeout redeem handler
- Chat auditing? (+2 / -2'ing)
- OBS hook in for redeems?
- Chat counting record
- ... and maybe more? We will see!

# Necessary Integrations for Plans
- Bungie API for Destiny for pulling Destiny items / FFXIV third party API for pulling XIV items
- Spotify API for song requesting directly
- Twitch API for reading channel states, chat, and other information
- OBS Connectivity for changing stream elements based on chat
- Discord API for sending messages and relaying user information
