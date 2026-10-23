# Changelog

All notable changes to LootPal, newest first.

LootPal is in **early alpha**. The middle number marks milestones (for example sync between phones, or equipment). The last number counts uploads within a milestone. 1.0 is the full companion, tested at the table.

---

## 0.2.4 · 2026-10-23

### Changed
- The pouch is now oiled saddle-brown leather instead of red, in the header and in the app icon, so it sits calmly with the rest of the app.
- New app icon: the pouch on forest-green leather with gold-thread stitching, without the metal frame. It stands out on a home screen and fits every phone's icon shape.

---

## 0.2.3 · 2026-10-23

### Added
- The pouch from the app icon now sits beside the LootPal wordmark in the header.

---

## 0.2.2 · 2026-10-23

### Added
- **Undo on the purse:** a round ↶ button where the ✕ sits while counting. It shows whenever there's something to undo and no amount is being counted. The ledger keeps its undo too.

### Changed
- Undo survives a reload: the last few transactions can still be undone after the page reloads or the phone locks.

---

## 0.2.1 · 2026-10-23

### Added
- Footer credit: By Mapventures · Grímur Fjeldsted · 2026.

---

## 0.2.0 · 2026-10-23

### Added
- New name and logo: **LootPal**.
- **App icon** (leather pouch) for the home screen and the browser tab. Added to the home screen, LootPal opens full screen like an app.
- **German.** LootPal follows the language of the phone or browser, and you can switch under **Customize → Language**. The choice is kept per device. Names LootPal gave (Player 1, Game Master, Gold…) switch with the language; names you chose stay.
- **Status card** under the purse: the character's name with tiles for **Wealth** (total worth as small coins, plus the wealth title) and **Weight** (weight, description, belt bar). With weight off, Wealth takes the full width. More tiles can follow.
- The status card folds away with a tap on its headline. Folded, it still shows the total worth as small coins. Each device remembers it.
- Party purse: **Split in party** tag in the receipt. With no amount counted, it fills in everything in the purse. Tap coins down to share less. What doesn't divide evenly stays in the purse.
- **Table name** in Save & load, for example *Curse of the Crimson Crown*. It's used in the save file's name and shown when loading, so you know which campaign a code or file belongs to.
- **Last backup** reminder: Save & load shows when the last backup was made and how many payments happened since. A small gold dot on the tab means there are payments that aren't backed up yet.
- Small icons on the bottom tabs (Party, Customize, Save & load, Ledger).
- Footer with the version number and a link to this changelog.
- Full documentation in the README, essentials first.

### Changed
- **Receipt** reordered. Players: *To whom?* first (NPC is the default), then *Which NPC?*, then *For what?*. Receiving and the GM: *From who or what?*, the GM's quick picks, then *For what?*. Opening the receipt no longer pops up the keyboard.
- The receipt button shows a character with a pouch. The old receipt icon moved to the Ledger tab.
- **Pay | Receive** moved up next to the character's name, like the GM's Give | Take. The slide bar sits higher, and small phones need less scrolling.
- Pay | Receive and Give | Take are as tall as the name and title together. Pay and Give, the actions used most, are never narrower than Receive and Take, in any language.
- Pay | Receive and Give | Take work like a switch: the highlight glides to the chosen side with a glowing gold border, and you can swipe across the switch as well as tap it.
- Long names shrink a little to fit next to Pay | Receive.
- **Total worth** and **purse weight** moved out of the leather card into the status card. The belt bar runs the full width and fills from green to red.
- Amounts in the line under the amount, the ledger and the GM's book show each coin in its own colour, so *6g 2s 15c* is easier to read.
- **Colours:** gold is kept for the payment itself (Pay | Receive, the selected tag for who gets it, the slide knob), primary buttons, the settings, the logo and deeds. The round buttons (receipt, 123, pencil) glow pale silver when open, and a filled-in receipt shows a ring and a dot. The selected character, Split | Each and Mixed bag are pale parchment; the wealth title and Repeat are muted bronze. Gold, silver and copper on screen now mostly mean coins.
- The **Done** button under the typed amount looks like the Pay | Receive switch (leather with a glowing gold border) instead of solid gold.
- The pencil closes Customize when tapped again.
- **Purse weight** is on for new tables. Existing tables keep their setting.
- New players are added after the other players, before the party purse.
- Removing a coin asks twice. The first tap on × turns it red and explains what happens; tap again within a few seconds to remove.
- **Start a new table** (formerly *Reset example table*) moved from Party to **Save & load**, next to saving, with a reminder to make a save code first.
- Save & load explains that a save holds the whole table: players, purses, coins, settings and the ledger.
- The separate "Share out everything" button on the party purse is gone. *Split in party* does the same job.
- Header logo made smaller.

### Fixed
- iPhone zoomed in when tapping a text field in the receipt and couldn't zoom back. Fields now use a size iPhones don't zoom on.
- Adding a player did nothing in some browsers (including the claude.ai version). The same problem stopped **Done** from closing the typed amount. Both work now, by tap and by Enter.
- German ledger lines read "an der Schmied". The German examples now leave out the article.
- Layout on narrow phones with longer German words (tabs, GM buttons, slide bar).

---

## 0.1.0

First version on GitHub.

- Character purses with stacked coins, tap, hold or drag to count, or type the amount.
- Slide to pay or receive, with automatic change.
- Medieval sounds: coins on an oak table, metal on metal when counting, a leather pouch.
- Game Master with unlimited coffers: give or take, whole party or chosen players, split or each, mixed bag, repeat last payout, the Game Master's book.
- Party purse.
- Receipt: what it's for and who it's to or from, written into the ledger.
- Ledger with undo.
- Custom coins: up to six, with name, worth, colour, shape and weight.
- Wealth titles, purse weight and deeds (optional).
- Starting purse and party settings.
- Save codes and save files.
