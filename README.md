# ZestyTheme

A minimal and elegant theme for Jellyfin based on/inspired by [Ultrachromic](https://github.com/CTalvio/Ultrachromic), [Glassmorphism](https://github.com/alexyle/jellyfin-theme), [Scyfin](https://github.com/loof2736/scyfin), [JellyTheme](https://github.com/alexyle/jellyfin-theme) & [Zombie](https://github.com/MakD/zombie-release/tree/main).

**Now with two login wallpaper options: minimal and stylish!**<br>
Compatible with 10.9.10+ & Tablets!

---

### **Screenshots:**

<img src="./images/home.jpg" alt="home" width="100%"/>
<img src="./images/nice-guys.jpg" alt="movies" width="100%"/>
<img src="./images/avatar.jpg" alt="tv-shows" width="100%"/>
<img src="./images/player.jpg" alt="player" width="100%"/>

Two login wallpaper options: Minimal and Stylish.

<img src="./images/login.jpg" alt="login" width="100%"/>

**Mobile:**

<img src="./images/phone.jpg" alt="phone" width="100%"/>

---

## Installing

To add the theme to Jellyfin, copy the following line to Dashboard > General > Custom CSS:

```
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/theme.css');
```
Then, if you haven't already, enable Backdrops for _every_ device using this theme (Settings > Display > Backdrops).¹

## Color schemes

Add **one** of the following @import lines _if_ you'd like to change the default colors to one of the presets below (optional):

### Cyan
<img src="./images/colorschemes/cyan.png" alt="default" width="30%"/>

The default color scheme.

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-cyan.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/cyan.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Blue

<img src="./images/colorschemes/blue.png" alt="blue" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/blue.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-blue.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/blue.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Coral

<img src="./images/colorschemes/coral.png" alt="coral" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/coral.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-coral.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/coral.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Gray

<img src="./images/colorschemes/gray.png" alt="gray" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/gray.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-gray.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/gray.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Green

<img src="./images/colorschemes/green.png" alt="green" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/green.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-green.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/green.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Purple

<img src="./images/colorschemes/purple.png" alt="purple" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/purple.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-purple.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/purple.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Red

<img src="./images/colorschemes/red.png" alt="red" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/red.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-red.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/red.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>

### Yellow

<img src="./images/colorschemes/yellow.png" alt="yellow" width="30%"/>

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/colorschemes/yellow.css');
```

<details>
 <summary>Preview</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/comp-yellow.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/yellow.jpg" alt="default" width="100%"/>
 </div>
</details>
<br>
<br>

For more info on custom colors [click here](./colorschemes/COLORS.md). For more color schemes check out MakD's [Zombie Repo](https://github.com/MakD/zombie-release/tree/main#color-palettes).

### Alt login wallpaper
Finally, _if_ you would like to use the alternative(stylish) login wallpaper, add the line below to your Custom CSS as well:

```css
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/login-alt.css');
```

This is a comparison between the minimal(default) and stylish versions of the login wallpaper:

<details>
 <summary>Blue</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-blue.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-blue.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Coral</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-coral.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-coral.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Cyan</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-cyan.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-cyan.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Gray</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-gray.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-gray.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Green</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-green.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-green.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Purple</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-purple.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-purple.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Red</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-red.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-red.jpg" alt="default" width="100%"/>
 </div>
</details>

<details>
 <summary>Yellow</summary>
 <div class="collapsible-content">
    <img src="./images/colorschemes/previews/minimal-yellow.jpg" alt="default" width="100%"/>
    <img src="./images/colorschemes/previews/stylish-yellow.jpg" alt="default" width="100%"/>
 </div>
</details>

---

### Notes:

 ¹ You must enable Backdrops on *every* device you plan to use this on, otherwise theme **WILL** look broken.

 This theme looks best with background images whose content is skewed the right. [As demonstrated here](./images/extras/bg-guide.jpg).

 I don't use the Live TV feature and neither Music Videos, so theme may look broken there. Not opposed to theming it, but hard to since I don't use it...

 I plan to get to theming TV mode (Settings > Display > Display Mode > TV) soon™. Looks broken right now.

---

### Disclaimer:

 Theme has only been tested at 1080p (16:9), on both the app and the web interface. So it _may_ look broken on 720p, 2K and 4K screens or different screen ratios. Please report any issues.

 Theme is still **WIP**, and may look broken in some areas. Please report any issues.

 I am _not_ the most knowledgeable in CSS, but I will do my best to maintain it... PRs are welcome :)

---

**Things I'd like to do, if I can figure out how to (HELP WANTED):**

 Add profile pics back:

<figure>
    <img src="./images/actor.jpg" alt="actor-page" width="65%">
    <figcaption>It doesn't seem possible to remove just the poster while keeping the profile pics & season posters...</figcaption>
</figure>

 Add season posters back:

<figure>
    <img src="./images/season.jpg" alt="season-poster" width="65%"/>
    <figcaption>It doesn't seem possible to remove just the poster while keeping the profile pics & season posters...</figcaption>
</figure>

 Turn seasons into a carousel to prevent this behavior:

<img src="./images/caroussel.jpg" alt="season-caroussel" width="65%"/>

 Make it so there is no "overflowing" entries in Genres after I increased Poster size

<img src="./images/genres.jpg" alt="genres" width="65%"/>
