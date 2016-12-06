# Addon: Material nav
A more material version of the header navigation

![](https://i.imgur.com/pU3Z7II.png)

## Installation
copy the following CSS into the *bottom* of your stylesheet.

```css
/* ADDON: MATERIAL NAV */

#header-bottom-left { top: 132px;  }
#header .tabmenu { margin: 0; height: 64px; line-height: 64px; }
#header-img.default-header, #header-img { display: inline-block; margin: 10px 12px 0 0; }
#header .tabmenu { display: inline-block; letter-spacing: .1px; }
#header .tabmenu li { display: inline-block; }
#header .tabmenu li a { margin: 0; line-height: inherit; font-weight: 700; padding: 0 12px; height: 64px; color: #fff; border-bottom: 2px solid rgba(255,255,255,0); transition: border-bottom-color .1s ease-out; }
#header .tabmenu li:hover a {border-bottom-color: rgba(255,255,255,.5); }
#header .tabmenu li.selected a { padding-bottom: 0; height: 64px; border-color: #fff }

#header .tabmenu:before {
    height: 64px;
    background: #212121;
    opacity: .5;
}

    /* REMOVE IF USING LOGO ADDON */
    #header .pagename a { position: absolute; left: 0; top: -80px; }
    /* END REMOVE */

/* END ADDON */
```