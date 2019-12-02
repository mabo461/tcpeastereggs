# Tcp Easter Eggs

**Installation:**

     <script src="TcpEasterEggs.js"></script>

**Configuration:**

    tcpEasterEggs.configure({ 'configOption1': 'value1', 'configOption2': 'value2' });

**Configuration Options:**

 - **ghostCount** (Default 85) : Number of ghosts to spawn.
 - **ghostSpawnDuration** (Default 15) : Duration (in seconds) ghostCount will be spawn in.
 - **ghostMinHeight** (Default 75) : Minimum height (in pixels) the ghost image will be displayed.
 - **ghostMaxHeight** (Default 350) : Maximum height (in pixels) the ghost image will be displayed.
 - **ghostMinLifeSpan** (Default 0.5) : Minumum time (in seconds) the ghost will be displayed.
 - **ghostMaxLifeSpan** (Default 10) : Maximum time (in seconds) the ghost will be displayed.
 - **friendHeight** (Default 250) : Height (in pixels) of the friend.
 - **friendLifeSpan** (Default 6) : Time (in seconds) the friend will be displayed.
 - **friendPctVisible** (Default 0.75) Percent of the friend to display.
 - **idleFriendsEnabledChance** (Default 25) Percent of pages load that the idle display will even be activated.
 - **showFriendIdleTimeout** (Default 30) Number of seconds of idle time before friend will popup.
 - **showFriendActiveInterval** (Default 5) Number of seconds between friend popup while activated.
 - **banishFriendsOnActivity** (Default true) Hide all active friend popups on user activity.


**Usage:**

*Keyboard trigger:*

    Up, Up, Down, Down, Left, Right, Left, Right, B, A

*Manually trigger the ghosts to spawn:*

    tcpEasterEggs.spawnGhosts();

*Manually trigger a friend to popup:*

    tcpEasterEggs.popupFriend();

