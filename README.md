# DiscordThemes
Simply-Theme your discord with ease

```css
/**
 * @name Example-Theme
 * @website https://github.com/yourpov/Simply-Theme
*/

@import url('https://raw.githubusercontent.com/yourpov/Simply-Theme/refs/heads/main/Assets/Base.css');

/* Customizable Settings */
:root {
  --background: url('https://i.imgur.com/zN6oYGF.png');   /* Main background */
  --backgroundsize: auto;                                /* Background scaling */
  --backgroundblur: 15px;                                 /* Blur on background */

  --popout: url('https://i.imgur.com/zN6oYGF.png');       /* Popout background */
  --popoutsize: cover;                                    /* Popout scaling */
  --popoutblur: 15px;                                     /* Popout blur */

  --transparencyalpha: 0.65;                              /* Global transparency */
  --transparencycolor: 3,3,3;                             /* Transparency color */
  --accentcolor: 100, 100, 100, 0.4;                      /* Accent color (RGBA) */
  --messagetransparency: 0.1;                             /* Message box transparency */
  --guildchanneltransparency: 0.1;                        /* Channel list transparency */
  --memberlisttransparency: 0;                            /* Member list transparency */

  --backdropsize: var(--backgroundsize);                  /* Backdrop size */
  --backdropblur: 80px;                                   /* Backdrop blur */

  --version1_0_5: none;                                   /* Internal flag */
}
```
