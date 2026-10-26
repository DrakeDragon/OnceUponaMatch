# 🧚 Once Upon a Match

A fairytale match-three puzzle game for phones, made with love for Mom. It has 360 hand-tuned levels across 12 classic tales, and the levels never run out.

Everything lives in one file (`index.html`). There is nothing to install and no account to make.

## Play

Open the GitHub Pages link for this repository in any phone or computer browser. On a phone, use **Share → Add to Home Screen** and it opens like an app, full screen.

An internet connection is only needed to load two fonts. If the fonts can't load, the game still works with a plain fallback font.

## The Game

- **Match three:** swap neighbouring tiles, or tap one tile and then a neighbour. Match 3 or more of the same picture to clear them.
- **Special tiles:** match 4 for a line clearer, an L or T shape for a bomb, and 5 for a rainbow tile. Swap a special tile with any neighbour to set it off.
- **Quest goals:** every level has a clear goal shown at the top of the screen: collect certain tiles, clear sparkle dust, guide a friend to the bottom, reach a score, or a mix of these.

### Companions
Each tale has three companions, such as the Scarecrow, the Tin Woodman and the Lion. They charge up as you match their colour. When one is ready, tap it, tap a tile to preview the effect, and tap again to use it. One clears a row, one blasts an area, and one removes a whole colour.

### The Fairy Wand
A fairy-dust meter fills as you play. When it's full, one tap casts a wish that helps with the current goal.

### Restore the Picture
Every level won for the first time restores a piece of that chapter's grayscale picture. Finishing all 30 levels brings the whole scene to colour.

### Storybook Cards and Story Pages
- 108 collectible cards, 9 for each tale.
- Earn a card every 5 levels, plus one from the Daily Gift.
- Each card reveal comes with a story page. Each chapter has 6 pages that tell that fairytale in order.

## Made to Be Gentle
- No timers and no lives. Play as long as you like.
- Unlimited undo.
- A free "+5 moves" (up to 3 per level) when you run out.
- Hints appear after a short pause. They can be turned off in Settings.
- The first levels teach one idea at a time, very slowly.
- Progress saves automatically. Closing the page and coming back resumes exactly where you left off.
- Settings include the player's name, larger text sizes, sound effects, and music.

## The 12 Tales
1. The Emerald Road (Wizard of Oz)
2. The Enchanted Castle (Beauty and the Beast)
3. The Midnight Ball (Cinderella)
4. The Cottage in the Woods (Snow White)
5. Beneath the Waves (The Little Mermaid)
6. The Briar Tower (Sleeping Beauty)
7. Gingerbread Lane (Hansel and Gretel)
8. Beanstalk Heights (Jack and the Beanstalk)
9. Grandmother's Path (Little Red Riding Hood)
10. Down the Rabbit Hole (Alice in Wonderland)
11. The Sultan's Bazaar (Aladdin)
12. The Tall Tower (Rapunzel)

After chapter 12 the tales begin again with new levels and no end.

## Difficulty
Levels 1–6 are very gentle. After that, the number of moves allowed shrinks slowly over roughly the next 150 levels, and bigger boards, a sixth tile colour and layered sparkle dust appear later on. All levels are generated from the level number, so everyone plays the same levels in the same order.

## Hosting on GitHub Pages
1. Create a new repository (public).
2. Upload `index.html`, `.nojekyll` and `README.md` to the root of the repository.
3. Go to **Settings → Pages**. Under **Build and deployment**, set the source to **Deploy from a branch**, choose `main` and the `/ (root)` folder, then Save.
4. After a minute or two, the game is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Saved Progress
Progress is stored in the browser's `localStorage` on the device where it's played (key `onceUponAMatch.v1`). It stays on that device and browser. Clearing the site's data, or using private browsing, erases it. To start over, use **Settings → Start over**.

## Technical Notes
- Single-file HTML, CSS and vanilla JavaScript. No libraries and no build step is needed to play.
- All art is emoji and generated SVG. Sound is synthesized with the Web Audio API, so there are no image or audio files.
- Designed portrait-first for phones, and also works on tablets and desktops.

## Credits
All fairytales used are public domain. Made by Tim, with Claude.
