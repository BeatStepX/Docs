#Beat Step X
[Video](https://www.youtube.com/watch?v=s6vm0xBc-rA)
### About the Project

#### Site
The site is build as SPA(Single-page Application), this mean when you start listen to a music you can go through pages listen that music without stop(like SoundCloud), this facilitate find new musics.

#### Game
The game is build in JS (TypeScript compiled to JS) using WebGL,
#### Game Modes
Besides the classic score mode will have:

##### Campaign Mode
Go through map, unlocking new missions.

##### Challenge Mode
Can be daily, weekly and monthly.

##### Challenge User
You can challenge another user to beat your score doing a bet, you bet first and play after. Could be single challenge or 'best of three'.

##### Multiplayer



#### Crew, clubs, clans(idk how call it)
The game will have some competitivity between groups, modes like "Challenge Group"

#### Music
At the beginning of the project I'm thinking in accept only musics that have Creative Commons to facilitate the process.

#### Steps
Each music can have multiple steps, but only one would be the official one.
The steps would be simple to import because it's basic as '.sma', each steps has:
- Music ID
- User ID (StepMaker)
- Step Type (3k, 4k... until 7k)
- Notes
- Level
- Offset
- Bpms
   - beat
   - bpm
- Warps
   - beat
   - distance
- Stop
   - beat
   - time

I already have a '.sm' converter.

In notes, instead of line breaks I use '**|**'(vertical bar) to simplify cross platform.

### How the project is separate
Currently I'm using this Git repositories.
- Site, Api and Admin. (Probably I will separate)
- Site Template.
- Game.
- Desktop Wrapper for the *Game* (AKA Standalone version).
- Game Server(for multiplayer).
- Game Map(Map system for the Campaign Mode).

#### Some Considerations
- I'm not good at english.
