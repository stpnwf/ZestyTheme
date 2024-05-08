# ZestyTheme


 
A minimal and elegant theme for Jellyfin based/inspired by [Ultrachromic](https://github.com/CTalvio/Ultrachromic), [Glassmorphism](https://github.com/alexyle/jellyfin-theme), [Scyfin](https://github.com/loof2736/scyfin) & [JellyTheme](https://github.com/alexyle/jellyfin-theme).
 

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

**If** you'd like to change the default colors, replace the RGB values and add these lines **underneath** `@import...`:

```
:root {--accent: R, G, B;}
:root {--accent-off: R, G, B;}
:root {--dark: R, G, B;}
:root {--darkest: R, G, B;}
:root {--dark-highlight: R, G, B;}
:root {--dark-apparent: R, G, B;}
```

---

Notes: 

 Backdrops need to be enabled in Jellyfin (Settings > Display > Backdrops) for backdrop to display properly.

 Check `theme.css` to see what each color does.
 
 **If** you change the dafault accent color, **and** use Jellyfin on mobile, you **will** want to use a color picker on the background color anywhere in Settings and set `--dark-apparent` to that value. Otherwise the backdrop grandient will look broken on mobile.

---

Disclaimer:

 I am _not_ knowledgeable in CSS, but if the end result looks how I want it to, despite how hacky or messy the code may be, that's still a win in my books... PRs are welcome.
 
 Theme has only been tested at 1080p, on both the app and the web interface. So it _may_ look broken on 720p, 2K and 4K screens.

---

**Things I'd like to do, if I can figure out how to:** 

Add profile pics back:
<img src="./images/actor.jpg" alt="actor-page" width="65%"/>
 Add season posters back:
<img src="./images/season.jpg" alt="season-poster" width="65%"/>
 Turn seasons into a carousel to prevent this behavior:
<img src="./images/caroussel.jpg" alt="season-caroussel" width="65%"/>
