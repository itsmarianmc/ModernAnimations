<img width=800 src="https://raw.githubusercontent.com/itsmarianmc/ModernAnimations/raw/master/assets/preview.png">

# ModernAnimations
More modern, better and smoother animations that make your Discord client more enjoyable to use.

<br>

<!-- Installation -->
# Install
## Vencord
- Paste the downloaded file into ```%appdata%\Vencord\themes```
- Open the Vencord **Themes** Tab inside the Discord settings
- Go to the **Themes** tab
- Search for **ModernAnimations** (if you don't see the Theme click on "**⟳ Load Missing Themes**" symbol)
- Switch the checkbox from **✗** to **✓**
- Reload Discord to apply changes

## BetterDiscord

<br>

<!-- Compatibility -->
# Compatibility with Third-Parties
### [Horizontial Server List](https://betterdiscord.app/theme/Horizontal%20Server%20List)
If you are using the “Horizontal Server List” addon, activate the loading of the URL for this addon in the “Third-Party Content” section at the bottom of the stylesheet or paste the following code:
```css
/*--------------------------------------------------------------
                    Horizontal Server List
---------------------------------------------------------------*/

/* Server selected pill */
.containerDefault_c69b6d {
	transition: transform var(--transition-time) var(--ease-in-out),
				width var(--transition-time) var(--ease-in-out);
}

/* Remove to set to bottom */
.pill_e5445c.wrapper__58105 {
	transform: translateX(67.5px) rotate(180deg) !important;
}

.listItem__650eb:hover .pill_e5445c.wrapper__58105 {
	transform: translateX(60px) rotate(180deg) !important;
	right: 100px !important;
}
```

### [ReadAllNotificationsButton](https://betterdiscord.app/plugin/ReadAllNotificationsButton)
If you are using the “Read All Notifications Button” addon, activate the loading of the URL for this addon in the “Third-Party Content” section at the bottom of the stylesheet or paste the following code:
```css
/*--------------------------------------------------------------
                   ReadAllNotificationsButton
---------------------------------------------------------------*/

.vc-ranb-button.button__201d5.lookBlank__201d5.sizeMin__201d5.grow__201d5 {
	transition: transform var(--transition-time) var(--ease-in-out);
}

.vc-ranb-button.button__201d5.lookBlank__201d5.sizeMin__201d5.grow__201d5:hover {
	transform: scale(1.05);
}
```

### [SpotifyControls](https://betterdiscord.app/plugin/SpotifyControls)
If you are using the “Read All Notifications Button” addon, activate the loading of the URL for this addon in the “Third-Party Content” section at the bottom of the stylesheet or paste the following code:
```css
/*--------------------------------------------------------------
                        SpotifyControls
---------------------------------------------------------------*/

/* Progress Bar */
.barFill_a562c8 {
	transition: width var(--transition-time) var(--ease-in-out);
}

/* Grabber for Progress bar*/
.grabber_a562c8 {
	cursor: grab;
}

/* Buttons and Cover */
.vc-spotify-button,
#vc-spotify-album-image {
	transition: transform var(--transition-time) var(--ease-in-out);
}

.vc-spotify-button:hover,
#vc-spotify-album-image:hover {
	transform: scale(1.075) !important;
}
```
<br>

<!-- Contact -->
# Contact
More supported plugins and themes, as well as updated will be coming soon...
<br>
If you want to have a plugin or certain elements animated, you can also contact me via <a href="https://discord.com/users/860122608682795028" target="_blank">Discord</a> and, if you have already designed your own animation, send me your code snippet.
<br>
**Star** and **Watch** this project to stay updated!

<!-- Copyright and Inforation-->
<h1></h1>
<p align="center">
    <span>&copy; 2025 <a href="https://github.com/itsmarianmc/">itsmarian</a> | All rights reserved.</span>
</p>
<p align="center">
    <sub><sub>Vencord, as well as BetterDiscord are against Discord's Terms of Service and can potentially ban your Discord account. I do not endorse Vencord or BetterDiscord and disassociate myself from these services and am merely providing a service and am not affiliated with these services.</sub></sub>
</p>