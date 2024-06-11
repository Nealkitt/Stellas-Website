# Garden Features
## General Garden Features
### SkyMart
Shows Copper Prices inside SkyMart by the coin to copper ratio
- Higher Number is better for Profit
### Numbers
#### Crop Milestones
- Shows Crop Milestones in the Stack Size in the Desk Menu
#### Average Milestone
- Shows Average Crop Milestone level, Adds all, of them together then divides by the number of them, Max Average Crop Milestone is 46
- Unlike the other Features in this category, this does not have anything to do with stack size
#### Crop Upgrades
- Shows Crop Upgrades in the stack size of the Desk Menu
#### Composter Upgrades
- Shows Upgrades in the Stack Size of the Composter
### Custom Keybinds

Allows you to set different keybinds for most keys while holding a Farming Tool

- Allows rebinding the following controls

    Attack, Use Item, Move Left, Move Right, Move Forward, Move Back, Jump, and Sneak

    - Multiple keys on the same action are not allowed
### Farming Lane
<details>
<summary>How to Configure</summary>
- Go to the Start of your Farming Lane<br>

- Type /shlanedetection<br>

- Continue Farming until you pass two ends of the lane<br> 

- It should now be fully configured and notify you when you finish each lane<br>

</details>
#### Lane Switch Notification
- Displays a Sound when you're  X (customizable) seconds away from the end of the current lane
    - Supports Customizing Sound, Text, Repeat Duration (How often it repeats), and Pitch
#### Distance Display
- Displays a HUD element of how far away you are from the end of the lane
#### Corner Waypoints
- Shows the corner of the Lane as a waypoint of the current lane you're farming
### Garden Level
#### Display
- Displays a HUD Element for your Garden Level in the format<br>
     "Garden Level X (XP/XP To Level)" 
#### Overflow
- Changes various Garden Level Displays to show past the SkyBlock max level in the same scaling (10,000 per level past 15)
#### Overflow Chat
- Shows Messages for the previous feature each time you pass a milestone, 
### Farming Weight
- Farming Weight is a Calculation from "Elite Farmers" More info can be found on<br>
[Elitebots Website](https://elitebot.dev/info)
#### Display
- Adds a Display for your current Farming Weight
#### Leaderboard Ranking
- Shows your Leaderboard placement if you are in the top 10,000 Farmers on EliteBot
#### Overtake ETA
- Shows how long until you'll pass the next player , If you're below 10,000 it will show how long until you're tracked on the leaderboard 
#### Show LB Change
- Shows if you've lost positions upon entering garden while offline after entering the Garden, 
#### Always ETA
- Always show Overtake ETA even when not Farming in Garden
#### ETA Goal
- Allows you to Set a custo mnumber of position you want to track
#### Show below 200
- Shows your weight even if you're below position 200, by default it does not display.
#### Show Outside Garden
- Shows the Farming Weight display /outside the Garden

### Dicer RNG Drop Tracker
- Displays What Drops you've gotten with the Melon/Pumpkin Dicer, Like other Trackers it can be customized more from inventories, such as displaying only this Session or Total since mod install
#### Compact Format
- Changes the Display from Seperate rows for each Drops to a Colored X/X/X/X Format, taking less Vertical Space
#### Hide Chat
- Hides the messages from Dicers
### Money per Hour
- Shows the Money per hour of various Crops
#### Only Show Top
- Customizes how many crops on the list you see
#### Extend Top List
- Adds the current crop for the tool you're holding into the list, even if it's not in the top threshold set above
#### Always On
- Displays it even if you're not farming in Garden, this does not enable it outside Garden
#### Compact Mode 
- Hides the position and name of the crop (Still shows the Icon) to take up less Horizontal Space
#### Compact Price
- Compacts the price by rounding, EG 11,423,132 to 11.4M
#### Use Custom
- Allows you to set what the Money/H Defaults to (Eg: Sell Offer, NPC, Instasell)
#### Merge Seeds
- Merges the Wheat and Seed price together 
#### Include X
- Various Toggles to add profit from Bountiful, Mooshroom Cow, Armor Drops, Dicer Drops
#### Hide Title
- Hides the first line of the Money/H Display to compact it even further
### Next Jacob's Contest
#### Show Jacob's Contest
- Adds a HUD Element with what the next Jacob's Contest is
#### Outside Garden
- Shows the HUD Element outside garden
#### In Other GUIs 
- Shows the Jacob's Contest Display in other Farming GUIs
#### Fetch Contests
- If you haven't opened calendar, fetch the Contests from Elitebots API
#### Share Contests
- Allows you to share Contests to the Elitebots API so other people can use the previous feature without opening
#### Warning
- Displays a Warning for Upcoming Jacob's Contest
#### Warning Time
- Customize the amount of seconds before a Contest you're notified
#### Popup Warning
- Pops up with a window when the game is out of focus
#### Warn For
- Allows you to Customize which crops you want to look forward to
### Armor Drop Tracker
#### Enabled
- Tracks all drops you get from Armor
#### Hide Chat
- Hides the messages from farming armor drops
### Anita Shop
#### Medal Prices
- Shows the Price per Gold Medal in Anita's Shop (Higher is Better)
#### Extra Farming Fortune
- Adds Price and Current tier to the Anita Farming Forunte Upgrade
- Since the Anita Menu item disappears when it's maxed, it is not visible after that
### Farming Fortune Display
#### FF Display 
- Shows your Farming Fortune and Crop Fortune combined for the tool you're holding as a HUD Element
#### Farming Fortune Guide
- Shows possible farming fortune, and breaks down the ways you can get it for a specific crop, or global buffs, sorted by lowest price to highest
- Also visible by typing /ff
### Tooltip Tweaks
#### Compact Descriptions
- Compacts a lot of parts of the descriptions of tools, Shrinks T3 Hoes Description by ~20%
#### Breakdown Hotkey
- Allows to set a hotkey for a more detailed breakdown of the ways the tool gives you farming fortune
#### Tooltip Format
- Shows Crop-Specific farming fortune in the tooltip
- Unsure if this actually does anything since they added crop specific fortune as a stat
#### Total Crop Milestone
- Adds a progress bar to Max Milestone in the Crop Milestone Inventory
- Hypixel implemented this feature if you are past Milestone 20
### Yaw And Pitch
#### Enable
- Adds a HUD Display to show yaw and pitch, fades out without mouse movement
#### Precision
- Adds Precision to the Yaw/Pitch to allow you to get the exact position for farming
#### Show Without Tool
- Does not require a tool in your hand for the HUD Display
#### Show Outside Garden
- Allows it to be shown outside Garden
#### Ignore Timeout
- Stops it from timing out after not moving your mouse
### Sensitivity Reducer
#### Mode
- Lets you switch between off, holding keybind, or holding any farming tool
#### Reducing Factor
- Divides your Sensitivity by the amount Specified
#### Show GUI
- Adds a HUD Display to show if the feature is currently working
#### Only in Ground
- If you are not on the ground disable Sensitivity Reducer to allow mouse movement to behave as Normal
#### Disable in Barn
- If you're in the barn, disable Sensitivity Reducer to allow movement to behave as normal
### Crop Start Location
#### Enable
- Shows the waypoint for the start of the farming location if you're holding a farming tool
#### Crop Location Mode
- Allows selecting where the Waypoint will Display
- Choose between Last Farmed, and where it's set to start 
- "/shcropstartlocation" sets the starting location
### Plot Menu Highlighting
#### Enabled
- Highlights Plots based on their Status set below
#### Statuses 
- Select which status to display
- Options are "Pasting, Current Plot, Pests, Sprays, and Locked"
### Garden Plot Icon
- Allows you to select an item in your inventory to replace the Plot item for
- This is why you see the axe in the Bottom Right corner of the Plot Menu
- Also has a Reset Button
### Garden Commands
#### Warp Commands
- Adds secondary commands for hypixel commands for: "/home" for "/warp garden", "/barn" for "/plottp barn", and "/tp plot" for /plottp plot"
#### Hotkeys
- Allows you to set hotkeys for the previous warps stated that only work in garden
### Atomspheric Filter Display
#### Enabled
- Adds a display to show the currently active Atomspheric Filter Display
#### Only Show Buff
- Compacts it by not showing the current season, instead only showing the buff from the season
#### Abbreviate Season
- Abbreviates the season to compact it
#### Abbreviate Perk
- Abbreviate the perk it gives to compact it
#### Outside Garden
- Enables the Feature outside the Garden
### Plot Price
- Shows the Unlock price for plots in coins if the compost was bought from bazaar
### Fungi Cutter Warning
- Adds a title to warn you if you're breaking the wrong mushroom with the Fungi Cutter
### Burrowing Spores
- Displays when you drop a Burrowing Spore while farming mushrooms
### Wild Strawberry
- Displays a notification when you drop Wild Strawberry Dye
### FF for Contest
- Shows the Lowest farming fortune with your BPS rate that you need to get a medal
### Contest Time Needed
- Shows how long with your current farming fortune and BPS rate you need to farm for a medal
### Custom BPS
- Override BPS rate to the one set below
### Contest Summary
- Summarizes various stats on how you did during the Farming Contest
### Enable Plot Borders
- Shows Plot Borders when doing F3+G
### Copy Milestone Data
- Allows you to copy incorrect crop milestone data
### Logbook Stats
- Shows Stats on your Visitor Logbook

## Visitor Garden Features
### Visitor Timer
#### Visitor Timer
- Adds a HUD Display for how many visitors you currently have, and how long until the next one
#### Sixth Visitor Estimate
- Estimates when the "Sixth visitor" will be available, because the counter for the next visitor counts down even when it's full
#### Sixth Visitor Warning
- Adds a Title for when the Sixth Visitor is available