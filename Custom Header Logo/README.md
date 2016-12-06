This addon is technically deprecated, but some people preferred it over /u/Cryptonaut's logo addon.

# Addon: Custom Header Logo
Set an image as your logo

![](https://i.imgur.com/j6gnRSO.png)

## Installation
copy the following CSS into the *bottom* of your stylesheet, uload your logo, and edit the addon to fit your logo.

```css
/* Addon: Custom Header Logo */

#header .pagename {  height: 0 }
#header .pagename a {padding:0;position:absolute;text-indent:-9999px;margin:0;top:-108px;background:url(%%logo%%);background-position:0 0;background-repeat:no-repeat;left: 0;z-index: 10;}
#header .pagename a:hover {background-color:transparent;}
.submit-page #header-bottom-left {top: 46px;}
.submit-page #header .pagename a { position: relative; margin-top: 12px; top: 0;}

#header .pagename a {
    margin-top:    34px; /* Space from top */
    width:         424px; /* Width of image */
    height:        42px;  /* Height of your image */
    background-size: contain;
}

/* End Addon */
```