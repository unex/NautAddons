# Addon: Remove sidebar image

![](https://i.imgur.com/jWn0fgj.png)

## Installation
copy the following CSS into the *bottom* of your stylesheet

```css
/* ADDON: REMOVE SIDEBAR IMAGE */

.side:before { display: none }

.side .titlebox h1.redditname { top:               calc(308px - 80px) }
.titlebox .fancy-toggle-button { top:              calc(314px - 80px) }
.titlebox span.subscribers { top:                  calc(336px - 80px) }
#search { top:                                     calc(384px - 80px) }
.submit .morelink { top:                           calc(442px - 80px) }
.side { margin-top:                                calc(282px - 80px) }
.comments-page .side .linkinfo { top:              calc(494px - 80px) }
.comments-page .side { margin-top:                 calc(400px - 80px) }
.search-page .side .titlebox h1.redditname { top:  calc(256px - 80px) }
.search-page .titlebox .fancy-toggle-button { top: calc(276px - 80px) }
.search-page .titlebox span.subscribers { top:     calc(300px - 80px) }
.search-page .morelink { top:                      calc(350px - 80px) }
.search-page .side {  margin-top:                  calc(234px - 80px) }

/* END ADDON */
```