# First Game 
![Welcome!](images/Tutorial1-Welcome.png)
Welcome to your first MakeCode Arcade game!


In this tutorial, you'll build a complete game from scratch.

By the end, you'll have:
- 🎮 A player you can control
- 🗺️ A map to explore
- 💎 A treasure to collect
- 👾 An enemy to avoid




Click **Next** when you're ready!

## It's time to start! @showhint

## Step 1 Create The Player 


Let's create the hero that the player will control!

Click the **Sprites** category, then drag a **`set mySprite to sprite`** block into the workspace.

Next, click the gray image and draw your own character or pick 1 from the gallery.

> 💡 **Tip:** Keep your sprite 16×16 pixels so it's easy to control.

```blocks
let hero = sprites.create(img`
. . . . . . f f f f . . . . . . 
. . . . f f f 2 2 f f f . . . . 
. . . f f f 2 2 2 2 f f f . . . 
. . f f f e e e e e e f f f . . 
. . f f e 2 2 2 2 2 2 e e f . . 
. . f e 2 f f f f f f 2 e f . . 
. . f f f f e e e e f f f f . . 
. f f e f b f 4 4 f b f e f f . 
. f e e 4 1 f d d f 1 4 e e f . 
. . f e e d d d d d d e e f . . 
. . . f e e 4 4 4 4 e e f . . . 
. . e 4 f 2 2 2 2 2 2 f 4 e . . 
. . 4 d f 2 2 2 2 2 2 f d 4 . . 
. . 4 4 f 4 4 5 5 4 4 f 4 4 . . 
. . . . . f f f f f f . . . . . 
. . . . . f f . . f f . . . . . 
`, SpriteKind.Player)
```


