# Tcp Easter Eggs

<script src="https://cdn.jsdelivr.net/gh/mabo461/tcpeastereggs@master/TcpEasterEggs.js"></script>
<style>
.myButton {
	box-shadow:inset 0px 1px 0px 0px #54a3f7;
	background:linear-gradient(to bottom, #007dc1 5%, #0061a7 100%);
	background-color:#007dc1;
	border-radius:3px;
	border:1px solid #124d77;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:13px;
	padding:6px 24px;
	text-decoration:none;
	text-shadow:0px 1px 0px #154682;
}
.myButton:hover {
	background:linear-gradient(to bottom, #0061a7 5%, #007dc1 100%);
	background-color:#0061a7;
}
.myButton:active {
	position:relative;
	top:1px;
}

</style>

**Examples:**

<button class="myButton" onclick="tcpEasterEggs.spawnGhosts()">Spawn Ghosts</button>

<button class="myButton" onclick="tcpEasterEggs.popupFriend()">Popup Friend</button>

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
 - **friendPctVisible** (Default 75) Percent of the friend to display.
 - **idleFriendsEnabledChance** (Default 10) Percent of page loads that the idle display will have a chance to be activated.
 - **showFriendIdleTimeout** (Default 60) Number of seconds of idle time before friend will popup.
 - **showFriendActiveInterval** (Default 10) Number of seconds between friend popup while activated.
 - **banishFriendsOnActivity** (Default true) Hide all active friend popups on user activity.
 - **maxIdleFriendsDisplay** (Default 100) Maximum number of idle friends to display on the screen at one time.

**Usage:**

*Keyboard trigger:*

    Up, Up, Down, Down, Left, Right, Left, Right, B, A

*Manually trigger the ghosts to spawn:*

    tcpEasterEggs.spawnGhosts();

*Manually trigger a friend to popup:*

    tcpEasterEggs.popupFriend();
	
*Enable the chance for idle popup friends*

	tcpEasterEggs.initIdleFriends();
