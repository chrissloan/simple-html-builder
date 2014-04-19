simple-html-builder
===================

Create simple HTML static pages using some popular buzz words.

## Uses:

* RVM (ruby-2.0.0) or rbenv (ruby 2.0.0)
* Compass (with Susy 2.0.0 for responsive layout)
* Haml
* Coffeescript
* Guard (to compile all this stuff)
* adsf (small server to run compiled files)

## Setup

1. Clone and `cd` into directory; allow rvmrc do it's thing
2. $ `bundle`
3. $ `bundle execute guard start` (or just $ `guard`)
4. In a new terminal instance, $ `cd public && adsf` to start the server

## Lay-o-land

* Edit files in the **/src** folder
* Sprite image files can be dropped into the **public/images/sprites** directory
* Sprites are named with a class: **.spt-NAMEOFFILE**
* All files from **src/** will be generated directly into the **public** folder while Guard is watching
* Replace the Google Analytic Tracking Account number with your number if needed; otherwise delete it
* Change the meta tags as needed
* Use of [Susy](http://susy.oddbird.net/guides/getting-started/) for responsive grid structure.

### Notabene

If the sprites folder is left empty, Guard-compass will fail as it looks for images to compile. To alleviate, either comment out the sprite compass include helper in the scss file or add images to the sprites folder. There is a 1x1 pixel temp.png file there now for example.
