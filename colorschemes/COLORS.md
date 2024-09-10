# Color schemes

Inspired by the [Zorin OS](https://zorin.com/os/) [color schemes](https://github.com/ZorinOS/zorin-desktop-themes)

---

**Template Colors:**

<img src="./../images/colorschemes/cyan.png" alt="default" width="30%"/>

<img src="./../images/colorschemes/blue.png" alt="blue" width="30%"/>

<img src="./../images/colorschemes/coral.png" alt="coral" width="30%"/>

<img src="./../images/colorschemes/gray.png" alt="gray" width="30%"/>

<img src="./../images/colorschemes/green.png" alt="green" width="30%"/>

<img src="./../images/colorschemes/purple.png" alt="purple" width="30%"/>

<img src="./../images/colorschemes/red.png" alt="red" width="30%"/>

<img src="./../images/colorschemes/yellow.png" alt="yellow" width="30%"/>

---

### Custom colors

To add the theme to Jellyfin, copy the following line to Dashboard > General > Custom CSS:

```
@import url('https://cdn.jsdelivr.net/gh/stpnwf/ZestyTheme@latest/theme.css');
```

**If** you didn't like any of the presets and would like to have custom colors, replace the R, G, B values below and paste it **underneath** the theme's `@import...` line:

```
:root {
    --accent: R, G, B;
    --accent-off: R, G, B;
    --dark: R, G, B;
    --darkest: R, G, B;
    --dark-highlight: R, G, B;
    --dark-apparent: R, G, B;
}
```

**Then** use a color picker on the *background color* anywhere in Settings or Dashboard, set `--dark-apparent` to that value, and save it. **Now you are done.**

If you don't do this, the backdrop gradient will not blend perfectly into the background on *mobile*. The background color is affected by the `--accent` color, so `--dark apparent` needs to be calculated for every color combination, hence why I made the presets...

If you'd like to make your own custom login wallpaper to match it, in line with the ones I made, follow the instructions in `images/colorschemes/base.svg` and add this following line to Custom CSS as well:

```
#loginPage {background: url(link-to-your-custom-wallpaper.jpg) !important;}
```

To make custom gradients open `images/gradients/coarse-gradients/gradient.ai` in **Adobe Illustrator** (couldn't get one in that shape in Inkscape :/), choose the gradient tool and change all the colors to your `--dark-apparent` including the ones with 0 opacity. Export to PNG with 72 p/in resolution and XXXX anti-aliasing. Then import the output from Illustrator along with `images/gradients/noise.png` to GIMP or Photoshop (or the template `gradient-noise.xfc`). Then put the noise layer on top and set the blending options to `Multiply`¹. Export to PNG.

Add the following line to Dashboard > General > Custom CSS as well:

```
.layout-desktop .backgroundContainer {background: url("link-to-your-custom-gradient.png") no-repeat center center;}
```

---
Color Breakdown

    --accent: R, G, B; 
    --accent-off: R, G, B; 
    --dark: R, G, B;                Used for some details where a color too dark or too light wouldn't be ideal
    --darkest: R, G, B;             Used for field's bg, text color when accent/accent-off becomes the bg color, etc.
    --dark-highlight: R, G, B;      Lighter than dark, used for dark highlights. BG in login page, etc.
    --dark-apparent: R, G, B;       Only used in mobile layout. It is the color of the gradient over the backdrop image.

    --white: R, G, B;               Used for the BG of the play button
    --white-off: R, G, B;           Used for the BG of the AppleTV-esque bar

    --jade-green: R, G, B;          Used for watched check
    --honey-yellow: R, G, B;        Used for the rating star color
    --cherry-red: R, G, B;          Used for the shutdown button

---

Notes: 
 
 Lighter `--accent` colors work better, as colorful colors will make the background color look very saturated - since the accent color is overlayed on top of the background.

 ¹ Overlaying the noise onto the gradient exported from Illustrator is necessary to decrease the color banding from the original file. This is an issue with gradients from both Illustrator and Inkscape, and looks better if managed with noise. 
 
