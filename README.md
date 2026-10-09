# jungle-stickers
A jungle sticker book for toddlers. Tap an animal to stick it on the scene, drag it around, and hear its name and sound.
# 🦁 Jungle Stickers

A simple, colourful sticker book for toddlers, made for my 2-year-old grandson.
Pick an animal, pop it onto the jungle, and drag it wherever you like.

**Live demo:** https://YOUR-USERNAME.github.io/jungle-stickers/

## Features

- 🌴 Bright jungle scene with trees, vines, leaves and flowers
- 🐘 About 90 stickers: jungle animals, farm animals, pets, sea creatures, bugs, dinosaurs, and a few plants and fruits
- 👆 Tap an animal in the tray to pop it onto the scene
- ✋ Drag stickers around, tap one to make it wiggle
- 🔊 Says the animal's name and sound out loud ("Cow! Moo!"), with a sound on/off button
- ↩️ Big undo button and a clear button that needs a second tap, so little fingers can't wipe the picture
- 💾 The picture is saved on the device, so it's still there next time

## Designed for small hands

- Large buttons and stickers, with no text to read and no menus
- Works on phones, tablets and desktop with touch or mouse
- Add it to the home screen for a full-screen, app-like feel

## Running it

It's a single `index.html` file with no build step and no dependencies.
Open it in a browser, or host it free with GitHub Pages
(**Settings → Pages → Deploy from branch → main / root**).

## Customising

Animals are listed in one array near the top of the script:

```js
["🦁", "Lion", "Roar!"]   // [emoji, name, sound]
```

Add, remove or reorder entries to change what appears in the tray.
Leave the sound empty (`""`) for animals that just say their name.

## Notes

- Stickers are emoji, so their look depends on the device (Apple, Android, Windows).
- Spoken names use the browser's built-in speech, which needs https (GitHub Pages provides this).
- Saved pictures are stored per device and are not synced.

## Licence

MIT. Free to use, change and share.
