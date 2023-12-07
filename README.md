# PLEASE DO NOT USE THIS, IT IS NOT COMPLETE AND IS AN ACTIVE WORK-IN-PROGRESS. ISSUES HAVE BEEN DISABLED FOR THIS REASON. 

# Timer
Core plugin for CS2 Surf Servers. This project is aimed to be fully open-source with the goal of uniting all of CS2 surf towards building the game mode.

# Goals
*Note: This is not definitive/complete and simply serves as a reference for what we should try to achieve. Subject to change.*

- [ ] Database
  - [ ] MySQL database schema ([W.I.P Design Diagram](https://dbdiagram.io/d/CS2Surf-Timer-DB-Schema-6560b76b3be1495787ace4d2))
  - [ ] Plugin auto-create tables for easier install? 
  - [X] Base database class implementation
- [ ] Zoning
  - [ ] Start/End trigger touch hooks
  - [ ] Spawn zone triggers from coordinates (DB)
  - [ ] Support for stages/checkpoints
  - [ ] Support for bonuses
  - [ ] Load zone information for official maps from CS2 Surf upstream? (Optional)
  - [ ] Custom zone drawing/editing in-game? (Similar to CS:GO SurfTimer)
- [ ] Surf configs
  - [X] Server settings configuration
  - [ ] Plugin configuration
  - [X] Database configuration
- [ ] Timing
  - [X] Base timer class implementation
  - [X] Base timer HUD implementation 
  - [ ] Save/load set times (DB)
  - [ ] Practice Mode
  - [ ] Announce records to Discord
  - [ ] Stretch goal: sub-tick timing
- [ ] Player Data
  - [X] Base player class
  - [ ] Player stat classes 
  - [ ] Profile implementation (DB)
  - [ ] Points/Skill Groups (DB)
  - [ ] Player settings (DB)
- [ ] Replays
- [ ] Angle style implementation
- [ ] Paint
