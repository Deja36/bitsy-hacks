
# bitsy-hacks
A collection of re-usable scripts for [Adam Le Doux](https://twitter.com/adamledoux)'s [Bitsy Game Maker](https://ledoux.itch.io/bitsy).

## contents
 - 👥 [avatar by room](/dist/avatar%20by%20room.js): change the avatar in certain rooms
 - 🔈 [basic sfx](/dist/basic%20sfx.js): "walk" and "talk" sound effect support
 - 😌 [bitsymuse](/dist/bitsymuse.js): A variety of Bitsy sound and music handlers
 - 😴 [canvas replacement](/dist/canvas%20replacement.js): WebGLazy bitsy integration (this one's mostly just for me)
 - ⛔️ [close on ending](/dist/close%20on%20ending.js): Prevents from playing past an ending
 - ➿ [corrupt](/dist/corrupt.js): corrupts gamedata at runtime
 - 🅰 [custom text effect](/dist/custom%20text%20effect.js): make {custom}text effects{custom}
 - 🔝 [direction in dialog](/dist/direction%20in%20dialog.js): provides a variable with player direction
 - ↔ [directional avatar](/dist/directional%20avatar.js): flips the player's sprite based on directional movement
 - 🖼 [dynamic background](/dist/dynamic%20background.js): HTML background matching bitsy background
 - 📝 [edit dialog from dialog](/dist/edit%20dialog%20from%20dialog.js): edit dialog from dialog (yes really)
 - 🖌 [edit image from dialog](/dist/edit%20image%20from%20dialog.js): edit sprites, items, and tiles from dialog
 - 🔚 [end-from-dialog](/dist/end-from-dialog.js): trigger an ending from dialog, including narration text
 - 🚪 [exit-from-dialog](/dist/exit-from-dialog.js): exit to another room from dialog, including conditionals
 - 🔡 [expose variables](/dist/expose%20variables.js): exposes the bitsy variable map globally
 - 🛰 [external-game-data](/dist/external-game-data.js): separate Bitsy game data from your (modded) HTML for easier development
 - 🌐 [favicon-from-sprite](/dist/favicon-from-sprite.js): generate a browser favicon (tab icon) from a Bitsy sprite, including animation!
 - 💕 [follower](/dist/follower.js): makes a single sprite follow the player
 - 🎮 [gamepad input](/dist/gamepad%20input.js): HTML5 gamepad support
 - 🕷 [itsy-bitsy](/dist/itsy-bitsy.js): for when bitsy's not small enough
 - ☕ [javascript dialog](/dist/javascript%20dialog.js): execute arbitrary javascript from dialog
 - 🔀 [logic-operators-extended](/dist/logic-operators-extended.js): adds conditional logic operators
 - 👨‍👨‍👧‍👧 [multi-sprite avatar](/dist/multi-sprite%20avatar.js): make the player big
 - 📎 [noclip](/dist/noclip.js): walk through wall tiles, sprites, items, exits, and endings
 - 🔄 [online](/dist/online.js): multiplayer bitsy
 - ⬛ [opaque tiles](/dist/opaque%20tiles.js): tiles which hide the player
 - 📃 [paragraph-break](/dist/paragraph-break.js): Adds paragraph breaks to the dialogue parser
 - ⏳ [permanent items](/dist/permanent%20items.js): prevent some items from being picked up
 - 🛑 [solid items](/dist/solid%20items.js): treat some items like sprites that can be placed multiple times
 - ⏱️ [stopwatch](/dist/stopwatch.js): time player actions
 - 🏰 [tracery processing](/dist/tracery%20processing.js): process all dialog text with a tracery grammar
 - 🎞 [transitions](/dist/transitions.js): customizable WebGL transitions
 - 👁️‍🗨️ [transparent dialog](/dist/transparent%20dialog.js): makes the dialog box have a transparent background
 - 🏁 [transparent sprites](/dist/transparent%20sprites.js): makes all sprites have transparent backgrounds
 - ❄ [unique items](/dist/unique%20items.js): items which, when picked up, remove all other instances of that item from the game

![Imgur](https://i.imgur.com/peRLLHn.gif)![Imgur](https://i.imgur.com/yg81aH2.gif)![Imgur](https://i.imgur.com/r7AUHX4.gif)




## how to use
Each script has a short "HOW TO USE" section included in the comments. For steps which say to `Copy-paste this script into a script tag after the bitsy source `, open your exported bitsy game and scroll to the bottom of the file (at the time of writing, it looks like this):
```html
</script>

</head>


<!-- DOCUMENT BODY -->
<body onload='startExportedGame()'>
  <!-- GAME CANVAS -->
  <canvas id='game'></canvas>
</body>


</html>
```

then edit it to look like this:

```html
</script>

<script>
  // and then paste your code here!
</script>

</head>


<!-- DOCUMENT BODY -->
<body onload='startExportedGame()'>
  <!-- GAME CANVAS -->
  <canvas id='game'></canvas>
</body>


</html>
```

## Further reading
- [Writing hacks with this repo's source code](https://github.com/seleb/bitsy-hacks/wiki)
- [Claire Morley's "A Bitsy Tutorial"](http://www.clairemorleyart.com/a-bitsy-tutorial)
- [Bitsy games!](https://itch.io/games/tag-bitsy)

- [Andrew Yolland's Borksy](https://ayolland.itch.io/borksy): Hack helper
- [ruin's image-to-bitsy](https://ruin.itch.io/image-to-bitsy): Artistic aid
- [Fontsy](https://seansleblanc.itch.io/Fontsy): Typographic tool