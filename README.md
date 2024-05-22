# ZestyTheme


 
A minimal and elegant theme for Jellyfin based/inspired by [Ultrachromic](https://github.com/CTalvio/Ultrachromic), [Glassmorphism](https://github.com/alexyle/jellyfin-theme), [Scyfin](https://github.com/loof2736/scyfin) & [JellyTheme](https://github.com/alexyle/jellyfin-theme).
 
Compatible with 10.9.x!

---

**Screenshots:**

<img src="./images/home.jpg" alt="home" width="100%"/>
<img src="./images/nice-guys.jpg" alt="movies" width="100%"/>
<img src="./images/avatar.jpg" alt="tv-shows" width="100%"/>
<img src="./images/player.jpg" alt="player" width="100%"/>
<img src="./images/login.jpg" alt="login" width="100%"/>
Mobile:
<img src="./images/phone.jpg" alt="phone" width="100%"/>

---

### Installing

To add theme to Jellyfin, copy the following line to Dashboard > General > Custom CSS:

`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/theme.css');`

<img src="./images/electric-cyan.png" alt="default" width="30%"/>



Plus **one** of the following lines **if** you'd like to change the default colors to one of the presets below (optional):


`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/blue.css');`

<img src="./images/blue.png" alt="blue" width="30%"/>


`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/coral.css');`

<img src="./images/coral.png" alt="coral" width="30%"/>


`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/gray.css');`

<img src="./images/gray.png" alt="gray" width="30%"/>


`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/green.css');`

<img src="./images/green.png" alt="green" width="30%"/>


`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/purple.css');`

<img src="./images/purple.png" alt="purple" width="30%"/>


`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/red.css');`

<img src="./images/red.png" alt="red" width="30%"/>


`@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/yellow.css');`

<img src="./images/yellow.png" alt="yellow" width="30%"/>


Then enable Backdrops in Jellyfin (Settings > Display > Backdrops) if you haven't already.¹ 

For more info on custom colors [click here](./colorschemes/COLORS.md)

---

Notes: 

 ¹ You must enable Backdrops on *every* device you plan to use this on.

---

Disclaimer:

 I am _not_ knowledgeable in CSS, but if the end result looks how I want it to, despite how hacky or messy the code may be, that's still a win in my books... PRs are welcome.
 
 Theme has only been tested at 1080p (16:9), on both the app and the web interface. So it _may_ look broken on 720p, 2K and 4K screens or different screen ratios.

---

**Things I'd like to do, if I can figure out how to:** 

Add profile pics back:

<img src="./images/actor.jpg" alt="actor-page" width="65%"/>

 Add season posters back:
 
<img src="./images/season.jpg" alt="season-poster" width="65%"/>

 Turn seasons into a carousel to prevent this behavior:
 
<img src="./images/caroussel.jpg" alt="season-caroussel" width="65%"/>

 Make so there is no "overflowing" entries in Genres after having increased Poster size

<img src="./images/genres.jpg" alt="genres" width="65%"/>
