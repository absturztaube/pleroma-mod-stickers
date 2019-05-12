# Pleroma Mod Stickers

This mod adds a sticker picker to pleroma-fe. it currently only supports LINE stickers.

This script only works with https://github.com/absturztaube/pleroma-mod-loader

## Installation

Do this in your pleroma-mods directory

```
sudo -u pleroma git clone https://github.com/absturztaube/pleroma-mod-stickers.git
sudo -u pleroma mkdir pleroma-mod-stickers/stickers
```
### adding stickers

each subfolder in the stickers represents a sticker pack. to add new stickers do the following

replace `$pack` with the name of the pack (you can choose whatever name you like)

```
sudo -u mkdir pleroma-mod-stickers/stickers/$pack
```

copy your line stickers (including `tab_on@2x.png` and `productInfo.meta`) to the newly created directoy

add the directory name to the config in mod.js 

