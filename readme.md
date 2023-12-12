<h2>Areas</h2>
<p><a href="https://github.com/Serilum/Areas"><img src="https://serilum.com/assets/data/logo/areas.png"></a></p><h2>Download</h2>
<p>You can download Areas on CurseForge and Modrinth:</p><p>&nbsp;&nbsp;CurseForge: &nbsp;&nbsp;<a href="https://curseforge.com/minecraft/mc-mods/areas">https://curseforge.com/minecraft/mc-mods/areas</a><br>&nbsp;&nbsp;Modrinth: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="https://modrinth.com/mod/areas">https://modrinth.com/mod/areas</a></p>
<h2>Issue Tracker</h2>
<p>To keep a better overview of all mods, the issue tracker is located in a separate repository.<br>&nbsp;&nbsp;For issues, ideas, suggestions or anything else, please follow this link:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;-> <a href="https://serilum.com/url/issue-tracker">Issue Tracker</a></p>
<h2>Pull Requests</h2>
<p>Because of the way mod loader files are bundled into one jar, some extra information is needed to do a PR.<br>&nbsp;&nbsp;A wiki page entry about it is available here:</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;-> <a href="https://serilum.com/url/pull-requests">Pull Request Information</a></p>
<h2>Mod Description</h2>
<p><a href="https://serilum.com/" rel="nofollow"><img src="https://github.com/Serilum/.cdn/blob/main/description/header/header.png" alt="" width="838" height="400"></a><br><br><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/header.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files/all?filter-status=1&filter-game-version=1738749986:75125" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_20.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files/all?filter-status=1&filter-game-version=1738749986:73407" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_19.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files/all?filter-status=1&filter-game-version=1738749986:73250" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_18.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files/all?filter-status=1&filter-game-version=1738749986:73242" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_17.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files/all?filter-status=1&filter-game-version=1738749986:70886" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_16.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files/all?filter-status=1&filter-game-version=1738749986:68722" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_15.png"></a><a href="https://legacy.curseforge.com/minecraft/mc-mods/areas/files/all?filter-status=1&filter-game-version=1738749986:64806" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/versions/1_14.png"></a><br><br><strong><span style="font-size:24px">Requires the library mod&nbsp;<a style="font-size:24px" href="https://www.curseforge.com/minecraft/mc-mods/collective" rel="nofollow">Collective</a>.</span></strong><strong>&nbsp;<br><br> &nbsp; &nbsp;This mod is part of <span style="color:#008000"><a style="color:#008000" href="https://curseforge.com/minecraft/modpacks/the-vanilla-experience" rel="nofollow">The Vanilla Experience</a></span>.</strong><br><span style="font-size:18px">Areas is a mod which allows any player to easily created named areas in a world. This can be an area, region, zone, town, kingdom etc. This is done with a placed sign. On it you specify the radius, optionally the rgb value and the name. This means that the radius around the sign is now considered an area. Whenever a player enters this area, they receive a message at the top of the GUI with (by default) "Enter the area.". And when they leave "Leaving the area.". This can both be changed in the config.<br><br>Names are randomly selected when the sign does not contain one. There is a global RGB value for the messages specified in the config, but this can also be a unique value again specified on the sign. See the examples below for a better idea of how it works!<br><br>You can make areas overlap in order to create different area shapes. The join/leave message will only show when entering for the first time or leaving every overlapping zone.</span></p>
<p><span style="font-size:14px;color:#008000"><strong>Works in multiplayer, but players must also have the mod installed on their client.</strong></span><br><br><br><strong><span style="font-size:20px">Configurable:</span> <span style="color:#008000;font-size:14px"><a style="color:#008000" href="https://serilum.com/url/issue-trackerwiki/how-to-configure-mods" rel="nofollow">(&nbsp;how do I configure?&nbsp;)</a></span><br></strong><span style="font-size:12px"><strong>giveUnnamedAreasRandomName</strong>&nbsp;(default = true): When enabled, gives signs without an area name a randomly chosen one from a preset list.</span><br><span style="font-size:12px"><strong>radiusAroundPlayerToCheckForSigns</strong>&nbsp;(default = 100, min 0, max 1000): The radius in blocks around the player in which to check for area signs.</span><br><span style="font-size:12px"><strong>defaultAreaRadius</strong>&nbsp;(default = 30, min 0, max 1000): The default radius for areas when it's left empty on the sign. It will be added automatically.</span><br><span style="font-size:12px"><strong>sendChatMessages</strong>&nbsp;(default = false): When enabled, sends the player the area notifications in chat.</span><br><span style="font-size:12px"><strong>showHUDMessages</strong>&nbsp;(default = true): When enabled, sends the player the area notifications in the HUD on screen.</span><br><span style="font-size:12px"><strong>showEnterMessage</strong>&nbsp;(default = true): Whether a message should be sent when a player enters an area.</span><br><span style="font-size:12px"><strong>enterPrefix</strong>&nbsp;(default = "Entering "): The prefix of the message whenever a player enters an area.</span><br><span style="font-size:12px"><strong>enterSuffix</strong>&nbsp;(default = "."): The suffix of the message whenever a player enters an area.</span><br><span style="font-size:12px"><strong>showLeaveMessage</strong>&nbsp;(default = true): Whether a message should be sent when a player leaves an area.</span><br><span style="font-size:12px"><strong>leavePrefix</strong>&nbsp;(default = "Leaving "): The prefix of the message whenever a player leaves an area.</span><br><span style="font-size:12px"><strong>leaveSuffix</strong>&nbsp;(default = "."): The suffix of the message whenever a player leaves an area.</span><br><br><span style="font-size:12px"><strong>showHUDTextShadow</strong>&nbsp;(default = true): Whether the text shown should be drawn with a shadow.</span><br><span style="font-size:12px"><strong>HUDMessageFadeDelayMs</strong>&nbsp;(default = 4000, min 100, max 360000): The delay in ms after which the HUD message should fade out.</span><br><span style="font-size:12px"><strong>HUDMessageHeightOffset</strong>&nbsp;(default = 10, min 0, max 3000): The vertical offset (y coord) for the HUD message. This determines how far down the message should be on the screen. Can be changed to prevent GUIs from overlapping.</span><br><span style="font-size:12px"><strong>HUD_FontSizeScaleModifier</strong>&nbsp;(default = 1.0, min 0, max 10.0): Increases the font size of the text in the HUD message. If you change this value, make sure to test the different GUI scale settings in-game. 6.0 is considered large.</span><br><span style="font-size:12px"><strong>HUD_RGB_R</strong>&nbsp;(default = 100, min 0, max 255): The red RGB value for the HUD message.</span><br><span style="font-size:12px"><strong>HUD_RGB_G</strong>&nbsp;(default = 200, min 0, max 255): The green RGB value for the HUD message.</span><br><span style="font-size:12px"><strong>HUD_RGB_B</strong>&nbsp;(default = 50, min 0, max 255): The blue RGB value for the HUD message.</span><br><br><br><span style="font-size:24px"><strong>Commands:</strong></span><br><span style="font-size:14px"><em>/areas</em> - Shows all area signs around the player.<br></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/a.jpg" width="1000" height="555"></picture></p>
</div>
<p>&nbsp;</p>
<p><br><span style="font-size:24px"><strong>Examples:</strong></span><br><span style="font-size:14px"><strong>To create an area with a radius of 10, use one of these prefixes. They do the same, choose which one you prefer:</strong></span><br><em><em>This will create an area with a random name by default.</em></em><br><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/b.jpg" width="1141" height="342"></picture><br><br><br><strong><span style="font-size:18px"><strong>A simple example; a desert island area with a radius of 10:</strong></span><br><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/c.jpg" width="1142" height="600"></picture><br></strong><span style="font-size:14px"><strong><br>Entering the desert island:</strong></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/d.gif" width="1000" height="518"></picture></p>
</div>
<p><span style="font-size:14px"><strong><br>When breaking the sign, the area ceases to exist:</strong></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/e.gif" width="1000" height="522"></picture></p>
</div>
<p>&nbsp;</p>
<p><br><span style="font-size:14px"><strong>Another example with a <span style="color:#f00;font-size:14px">custom colour</span>; A savanna village area with the rgb value after the [RGB] prefix:</strong></span><br><em>These three signs result in exactly the same.</em><br><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/f.jpg" width="1141" height="342"></picture>&nbsp;<br><span style="font-size:14px"><strong>Entering the savanna village:</strong></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/g.gif" width="1000" height="520"></picture></p>
</div>
<p>&nbsp;</p>
<p><span style="font-size:14px"><strong>Leaving the savanna village:</strong></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/h.gif" width="1000" height="520"></picture></p>
</div>
<p>&nbsp;<br><br><br><span style="font-size:18px"><strong>An area being randomly named with a radius of 30:</strong></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/i.gif" width="1000" height="522"></picture></p>
</div>
<p>&nbsp;<br><span style="font-size:18px"><strong>Another randomly named area with a radius of 20:</strong></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/j.gif" width="1000" height="522"></picture></p>
</div>
<p>&nbsp;</p>
<p><br><br><span style="font-size:18px"><strong>And another example with an unnamed area with a radius of 5 by not entering a name, and the config option 'giveUnnamedAreasRandomName' set to false:</strong></span></p>
<div class="spoiler">
<p><picture><img src="https://github.com/Serilum/.cdn/raw/main/projects/areas/k.gif"></picture></p>
</div>
<p><br>------------------<br><br><span style="font-size:24px"><strong>You may freely use this mod in any modpack, as long as the download remains hosted within the CurseForge or Modrinth ecosystem.</strong></span><br><br><span style="font-size:18px"><a style="font-size:18px;color:#008000" href="https://serilum.com/" rel="nofollow">Serilum.com</a> contains an overview and more information on all mods available.</span><br><br><span style="font-size:14px">Comments are disabled as I'm unable to keep track of all the separate pages on each mod.</span><span style="font-size:14px"><br>For issues, ideas, suggestions or anything else there is the&nbsp;<a style="font-size:14px;color:#008000" href="https://serilum.com/url/issue-tracker" rel="nofollow">Github repo</a>. Thanks!</span><span style="font-size:6px"><br><br></span><a href="https://ricksouth.com/donate" rel="nofollow"><img src="https://github.com/Serilum/.cdn/raw/main/description/shields/donation_rounded.svg" alt="" width="306" height="50"></a></p>