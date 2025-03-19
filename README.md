<img src="https://avatars1.githubusercontent.com/u/54474115?s=460&v=4" width="100" alt="" data-canonical-src="https://avatars1.githubusercontent.com/u/54474115?s=460&v=4">  &nbsp;&nbsp;
<img src="https://gamemonetize.com/images/construct2logo.png" width="100" alt="" data-canonical-src="https://gamemonetize.com/images/construct2logo.png">

# GameMonetize.com-SDK Construct 2
This repository contains the GameMonetize.com SDK for HTML5 Construct 2 games. This allows you to display advertisements in the games published within the GameMonetize.com network. https://GameMonetize.com


<b>For Construct 3, please visit:</b></br>
<a href="https://drive.google.com/file/d/1qwhm5drPwjzdWMc01qH-NQzTJmINGudG/">Download the plugin</a> or visit <a href="https://www.construct.net/en/make-games/addons/448/gamemonetize-com-sdk">Construct 3 Addons here</a>

# STEP 1:
<a href="https://drive.google.com/file/d/13l-YeEqS733TK48aQR193BCDe9-4fS2V/">Download the plugin</a> and extract the file to C:\Program Files\Construct 2\exporters\html5\plugins
<p>Download here: <a href="https://drive.google.com/file/d/13l-YeEqS733TK48aQR193BCDe9-4fS2V/">https://drive.google.com/file/d/13l-YeEqS733TK48aQR193BCDe9-4fS2V/</a></p>

# STEP 2:
Select the new plugin within Construct 2 by right-clicking on Object Types and insert your gameId in the properties tab.
You can find these values within your GameMonetize control panel after creating a new game.

# STEP 3:
Right-click Object types in the 'Projects' tab, select Insert New Object and select 'GameMonetize' in the 'Monetization' category.
<p><img src="https://gamemonetize.com/images/construct/construct1.png"  width="800" alt=""></p>

# STEP 4:
Click 'GameMonetize' and insert your GameId in from your account on game
<p><img src="https://gamemonetize.com/images/construct/construct2.png"  width="800" alt=""></p>

# STEP 5:
Double click the GRAY area to create an event to be tied with an advertisement request. You can also tie the following steps to an existing event in your game flow.
<p><img src="https://gamemonetize.com/images/construct/construct3.png"  width="800" alt=""></p>

# STEP 6:
Choose 'Init SDK' as an action to tie to an event in your game flow.
<p><img src="https://gamemonetize.com/images/construct/construct4.png"  width="800" alt=""></p>

# STEP 7:
You can now call the 'Show Banner' action - whenever and as often as you want. We will make sure to reject any premature calls.
<p><img src="https://gamemonetize.com/images/construct/construct5.png"  width="800" alt=""></p>

# TIP: Pause/Resume events
Add events for pause and resume game. You have to stop your game and mute all sound & music when you see an advertisement.

# FAQ
<h2>How to upload a game files?</h2>
<p><b>Answer</b>: When your game is ready to upload, you need to compress all game files to .ZIP file - Root folder of .ZIP file must include index.html and game files</p>
<h2><b>Implementation self-hosted games.</b></h2>
<p>In the case where a developer wants to self-host their game, please contact us on at: info@gamemonetize.com</p>

# Support:
If you have any technical questions or comments, please email us at:
info@gamemonetize.com

Or simply check documentation on:
https://gamemonetize.com/sdk
