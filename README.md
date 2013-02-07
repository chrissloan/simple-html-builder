simple-html-builder
===================

Create simple HTML static pages using some popular buzz words.

## Uses:

* RVM (ruby-1.9.3) => Must be installed
* Compass
* Haml
* Coffeescript
* Guard (to compile all this stuff)

## Setup

1. Clone and `cd` into directory; allow rvmrc do it's thing
2. $ bundle
3. $ bundle execute guard start (or just `guard`)

## Lay-o-land

* Edit files in the **/src** folder
* Sprite image files can be dropped into the **public/images/sprites** directory
* Sprites are named with a class: .spt-NAMEOFFILE
* All files from src/ will be generated directly into the **public** folder while Guard is watching


### Notabene

If the sprites folder is left empty, Guard-compass will fail as it looks for images to compile. To alleviate, either comment out the sprite compass include helper in the scss file or add images to the sprites folder. There is a 1x1 pixel temp.png file there now for example.
