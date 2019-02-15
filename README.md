# <img src="https://purepng.com/public/uploads/large/purepng.com-hired-gun-graves-skinsplashartchampionleague-of-legendsskingraves-3315199260108xiqj.png" height="120"><img src="https://cacophony.org.nz/sites/default/files/gopher.png" height="120">
# Mafia (Werewolf) Party Game
All information about this game can be found here https://github.com/HakanSunay/Mafia-Werewolf-Party-Game/

## Download
```$ go get github.com/HakanSunay/mafia-game/```

## Usage

```$ mafia-game```

## Gameplay
``` > Tell me your name, babe! ```

``` Gopherino ```

``` > Gopherino joined the room ```

...

1. You will be asked to enter a valid username.
2. You can now either CREATE or JOIN a ROOM or chat with other players in the Lobby.
3. Whatever your decision is, the game can only be started by the room creator when a minimum of 6 players gather.
4. Random hidden roles are assigned to all of the players.
5. Everyone falls asleep.
6. The _Mafia_ members wake up, the chat is opened for Mafia members only and they vote to eliminate someone and fall asleep.
7. The _Doctor_ wakes up, the chat is opened only for him and he is prompted to select a player to save and then he falls asleep as well.
8. Everybody wakes up, the chat is opened for everyone and they vote to choose the mafia to send to prison.
9. The chosen suspect is arrested.
10. Go back to 5, until: 
* MAFIA members become 0, then CITIZENS win.
* CITIZENS(incl the DOCTOR) become 1 or less than 1, then MAFIA win.
* You might find it interesting that when CITIZENS(incl Doctor) and MAFIA both become 1, MAFIA win, this is because MAFIA will just shoot the alive CITIZEN..

## LOBBY COMMANDS
* ``#CREATE_ROOM roomName`` - a simple command to create rooms

* ``#JOIN_ROOM roomName``- use it to join an existing room, that IS NOT PLAYING

* ``#ROOMS`` - lists all rooms - in LOBBY and IN-GAME
## IN-GAME COMMANDS
* ``#PLAYERS`` - lists all the players that are alive
* ``#VOTE playerName`` - this is the main command of the game, the doctor uses it to save possible victims,
the citizens use it to imprison possible mafiozos and the mafia use it to murder citizens.
