# Dragon's Horde Gift Exchange Manager - Dragon Master's Manual

## Setup

Players (the horde) bring wrapped gifts (the hoard) and place them in a central area that is visible to all players. Each player can now register in the application by entering their name and creating their character. The game will require at least one player to be the Dragon Master (DM). The DM will be the referee. They will apply the rules, settle disputes and run the application. The DM will also supply one unwrapped gift to the game. This should be a "zonk" gift (one that may not be very desirable). Players may be forced to choose this gift by some elements of the game. 

## Character Creation

When you begin the game, you will start out with the player management screen. Here, you can add new players, remove existing players, load a players list from a file, or use the setting icon to load a previously saved game. Each player can have a chance to roll dice to determine their attributes and their class. Their class is based on the character's highest attribute. High strength will yield a warrior, dexterity will become a thief, intelligent characters will be magicians and characters with high charisma will be bards. The player can then choose their character's look by selecting an image from the menu. Alternatively, they may accept the random character they were assigned initially. 

For larger groups, it may be easier to skip the character creation process. Instead, you can modify the players.csv file located in the streaming assets folder, which contains a list of player names. Then, on the player management screen, load this file to automatically generate a character for each name in the players.csv file.

## Starting the Game

Once all players are registered on the player management screen, press start game button to begin. The players will be placed in the queue in a random order and the first player is selected automatically. 

## Turn Mechanics

During a player's first turn, they have two options.

- Unwrap a gift from the hoard: The player selects a gift, unwraps it, and reveals it to the group. After revealing, their turn ends. 

- Use an ability to claim a gift from the horde: Each player begins with an ability to take a gift from another player (steal). Using this ability has a chance to fail and consequences for that failure. The application will prompt you to select the player being stolen from and will then roll a d20 to determine success or failure. Each player can only use their ability once unless otherwise determined by the rules of the application.

  - On a successful steal, the victim hands over the gift to the player and that player's turn ends. The victim now gets another chance to either select an unwrapped gift or use their ability if they haven't already used it.

  - On a failed roll, the player attempting to steal has been caught by the DM and must throw themselves at the mercy of the DM. The DM has the opportunity to either allow the player to choose a gift from the hoard or the DM may choose one for them. This could include the revealed "zonk" gift.

  - Since there is a chance of failure, there is no limit to how many times a gift can be stolen.

## Ending the Game

The game ends when all players have taken a turn. The final gift will be presented to the DM to thank them for their service. 

## Rule Variants

### Key of the Chosen

If you would like to add the Key of the Chosen element to your game there is some additional setup. The DM or sponsor will also need to provide a bonus gift and physical key to represent the key of the chosen. The bonus prize will be a desirable prize (gift cards are perfect) and should be kept wrapped or otherwise hidden. I recommend using a treasure chest to keep with the theme. The key will also begin hidden.

When the setting is activated in the application, each player who opens a gift from the table has a chance of the key "choosing" them. The game will notify you when this happens. The chance of being chosen increases each time a player opens a gift and resets to a base chance when a player is chosen. 

When a player is chosen, present them with the physical key prop. The key is now linked to that player's gift. If someone steals from that player, they also steal the key. If another player is chosen by the key, the previously chosen player keeps their gift, but presents the key to the new chosen player. The key is now linked to the new players gift and given up during a steal. 

At the end of the game, reveal the bonus prize and present it to the person who ended up with the key. 

### Cards of Redemption

The Cards of Redemption are designed to provide the steal victim with an advantage after losing their gift. After being stolen from, the victim will have the chance to take another gift from the hoard or draw a card. Each card will provide the player with a unique ability. For instance, it may give them the ability to steal a gift with a bonus to the roll, or it may provide the option of peeking under the wrapping paper of two gifts and selecting the one they prefer. The application will provide a description of the ability, and the use of the ability is completely optional.

## Auto Save
After each turn, a snapshot of the game is saved just in case the application crashes or some other calamity occurs. You can load a saved game in the settings menu.

## Restart
If you'd like to restart the game without losing your player list, use the restart button in the settings menu. This will randomize the turn order again.

