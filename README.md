GameEd-bot
============

A bot to play cards or use as a mafia moderator

Made with discord.py

(Invite link in image)

[![GameEd](https://media.discordapp.net/attachments/720681623577690176/734896506917617664/joker_card_3.png?width=150&height=150)](https://discord.com/api/oauth2/authorize?client_id=700167135288098876&permissions=470150259&scope=bot)

Key features:
-------------
- Playing cards between player direct messages
   * Plus a "table" for moving around/managing cards
- Polls/role assignments for playing mafia
- Picking a random person in the voice channel with you

Help commands:
-------------
`card_help`

AKA: `csos` `chelp`

- Help with card-playing commands. 
- Displays like a "pamphlet" in guild channels, but shows a complete list of card commands in direct messages.


`mafia_help`

AKA: `msos` `melp` `mhelp`

- Help with playing mafia, shows command names and basic descriptions of commands.


`help_help`

AKA: `meta-help` `help` `SOS` `hh`

- Misc. commands and their basic descriptions.


Ways to join/leave a card game:
-------------------------------
`mention_card_game`

AKA: `mcg`

- Everyone mentioned joins a card game.
- You are included in the card game, regardless of if you mention yourself.
- People know they are in a card game by being directly messaged by the bot.

`react_card_game`

AKA: `rcg`

- Everyone who reacts to the bot's message with a ticket joins the game
- People know they are in a card game by being directly messaged by the bot.

`voice_card_game`

AKA: `vcg`

- Everyone in the voice channel with you is added to a card game
- People know they are in a card game by being directly messaged by the bot.

`join_card_game`

AKA: `jcg`

- Mentioned people join the game of the first person mentioned
- The author will be added to the game of the first person mentioned (you don't need to mention yourself)

`leave_card_game`

AKA: `lcg`

- Leave whatever card game you're in
- Works anywhere the bot is

Dealing cards:
-------------

`shuffle`

AKA: `sh`

- Shuffle the deck
- Doesn't work if the deck was already dealt to people

`deal_cards_evenly`

AKA: `dce`

- Divides the cards evenly among everyone

`deal_cards_numerically`

AKA: `dcn` `dnc`

- Takes the first integer you say, and gives everyone that number of cards

`reset_deck`

AKA: `rd`

- Resets the deck to an unshuffled list

Card-playing commands:
---------------------

`play_card`

AKA: `pc`

- Play the card you name the suit and rank of

`draw_card`

AKA: `dc`

- Gives you a random card from the discard pile (AKA the "Nobody" section of the deck)

Getting card info:
-----------------

`my_cards`

AKA: `mc`

- Directly messages you your cards

`get_stats`

AKA: `gs`

- Says how many cards everyone has

`cards_play_time`

AKA: `cpt` `cgt`

- How long you've been playing cards
- In minutes and seconds

Bulk card commands:
-------------------

`get_cards`

AKA: `gc`

- Takes the first integer number of cards you say and gives you that many cards

`remove_n_cards`

AKA: `rnc`

- Takes the first integer you say and removes that many cards
- Removes the cards from the total list of cards __or__ the "Nobody" section of the deck (AKA the discard pile)

`fish_cards`

AKA: `fish`

- This command was made for playing go fish with
- Fish the rank you name from the first person you mention

Table commands:
--------------

`table_put`

AKA: `tp` `tc`

- Put the card you name the rank and suit of from your hand of cards onto the table

`table_take`

AKA: `tt` `untable`

- Take the card you name the rank and suit of from the table
- You can untable anyone's cards

`table_random`

AKA: `tr` `rt`

- Tables a random card from the discard/"Nobody" section
- Doesn't save the random card to the table's "Nobody" section

`table_nobody`

AKA: `tn` `nt`

- Puts a random, unassigned card from the deck onto the table's "Nobody" section
- Takes the card from the deck
- Saves the card to the table's "Nobody" section

`table`

AKA: `t`

- Sends the game "table"

Ways to join/leave a mafia game:
---------------------------

- One mafia person out of every four players
- If you have more than 8 players you get extra roles
  - A doctor
   - Picks one person to try saving each night
  - A seer
   - Can check if a person is mafia or not each night
  - Two masons
   - Gets told about the other mason (both are villagers)
- If everyone joins using `join_mafia_game`, you won't get the bonus roles


`mention_mafia_game`

AKA: `mmg`

- Start a mafia game with whoever you mention


`voice_mafia_game`

AKA: `vmg`

- Start a mafia game with whoever you're in a voice channel with


`react_mafia_game`

AKA: `rmg`

- Start a mafia game with whoever reacts to my message


`leave_mafia_game`

AKA: `lmg` `ml` `lm`

- You leave the mafia game (works in any channel, or if you DM me)


`join_mafia_game`

AKA: `jmg`

- Join the mafia game of the first person you mention


Polls:
-----

`nighttime`

AKA: `night_poll np`

- Triggers the nighttime poll
  - Mafia members vote for someone to leave the game
  - The seer clicks the icon of the person they'd like to learn more about
  - The doctor clicks the icon of the person they want to try saving


`daytime`

AKA: `day_poll dp`

- Triggers the daytime poll
- Villagers vote someone out


Mafia info commands:
--------------------

`mafia_play_time`

AKA: `mpt` `mgt`

- How long you've been playing mafia for, in minutes and seconds

Misc. commands:
---------------

`space`

AKA: `sky`

- Displays a clear night sky


`add_gamEd`

AKA: `ad` `ge`

- Gives a link to invite the bot to another server


`someone_voice`

AKA: `sv` `vs`

- Picks a random person in the voice channel with you
  - Good for playing games like truth or dare!
