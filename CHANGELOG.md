### 1.3.0
- Fixed only being visible on host (this was caused by my silly mistake)
- A small fix to not use shotguns from modded moons.

#### 1.2.1
- No longer breaks if another mod adds in a shotgun that has no spawn prefab.
- Changed to load with a patch instead of the scene loaded event so that this mod doesn't break when somebody else's mod exceptions in that event.

#### 1.2.0
- Price now syncs between host and clients
- Fixed problem where flags were set to hide and dont save

#### 1.1.0
- Made the buyable shotgun its own prefab instead of just using vanilla one.
     - This should hopefully fix some issues where the host was the only one who could see or interact with the shotgun.

#### 1.0.4
- Fixed white block icon and interaction bug that happens with Brutal Company Minus

#### 1.0.3
- Small fix for scan node error

#### 1.0.2
- Changes to how I register the items

#### 1.0.1
- Added terminal info for shotguns
- Fixed bought shotguns only being visible on host
- Fixed shotguns disappearing in item store when quitting to main menu and starting/loading a new game.

#### 1.0.0
- Initial release