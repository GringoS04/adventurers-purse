# Changelog

All notable changes to LootPal, newest first.

LootPal is in **early alpha**. Versions stay below 1.0 until the core is settled. Small fixes raise the last number (0.3.1), new features the middle one (0.4.0).

---

## 0.8.0 · 2026-10-23

### Added
- **Table name** in Save & load, for example *Curse of the Crimson Crown*. It's used in the save file's name and shown when loading, so you know which campaign a code or file belongs to.
- **Last backup** reminder: Save & load shows when the last backup was made and how many payments happened since. A small gold dot on the tab means there are payments that aren't backed up yet.

### Changed
- Save & load explains that a save holds the whole table: players, purses, coins, settings and the ledger.

---

## 0.7.1 · 2026-10-23

### Changed
- Removing a coin now asks twice. The first tap on × turns it red and explains what happens; tap again within a few seconds to remove.
- **Start a new table** (formerly *Reset example table*) moved from Party to **Save & load**, next to saving, with a reminder to make a save code first.

---

## 0.7.0 · 2026-10-23

### Added
- **Status card** under the purse: the character's name with tiles for **Wealth** (total worth as small coins, plus the wealth title) and **Weight** (weight, description, belt bar). With weight off, Wealth takes the full width. More tiles can follow.
- The status card folds away with a tap on its headline. Folded, it still shows the total worth as small coins. Each device remembers it.
- Purse weight is on again for new tables, since the status card can be folded away. Existing tables keep their setting.

### Changed
- The round buttons (receipt, 123, pencil) glow pale silver when open, so gold stays with the payment itself.

---

## 0.6.1 · 2026-10-23

### Changed
- Gold is back on the payment itself: Pay | Receive and Give | Take, and the selected tag for who gets it (players, Whole party). Also on the round buttons (receipt, 123, pencil), the settings and the weight icon.
- The **Done** button under the typed amount now looks like the Pay | Receive switch (leather with a glowing gold border) instead of solid gold.
- New players are added after the other players, before the party purse.

### Fixed
- Adding a player did nothing in some browsers (including the claude.ai version). The same problem stopped **Done** from closing the typed amount. Both work now, by tap and by Enter.

---

## 0.6.0 · 2026-10-23

### Changed
- Calmer colours. Gold is kept for the main action (slide knob, Done, primary buttons), the logo and deeds. Selected things (character, Pay | Receive, tags, open buttons, active tab) glow pale parchment, and small accents like the wealth title are muted bronze. Gold, silver and copper on screen now mostly mean coins.

---

## 0.5.0 · 2026-10-23

### Changed
- **Pay | Receive** moved up next to the character's name, like the GM's Give | Take. The slide bar sits higher, and small phones need less scrolling.
- **Total worth** and **purse weight** moved out of the leather card into their own line below it. The belt bar now runs the full width.
- Long names shrink a little to fit next to Pay | Receive.
- Pay | Receive (and the GM's Give | Take) made bigger: as tall as the name and title together. Pay and Give, the actions used most, are never narrower than Receive and Take, in any language.
- Pay | Receive and Give | Take now work like a switch: the highlight glides to the chosen side with a glowing gold border, and you can swipe across the switch as well as tap it.
- Total worth shown as small coins, like the big amount.
- Amounts in the line under the amount, the ledger and the GM's book now show each coin in its own colour, so *6g 2s 15c* is easier to read.

---

## 0.4.0 · 2026-10-23

### Added
- App icon (leather pouch) for the home screen and the browser tab. Add LootPal to the home screen and it opens full screen like an app.

---

## 0.3.0 · 2026-10-23

### Added
- New name and logo: **LootPal** (formerly QuestPouch).
- Party purse: **Split in party** tag in the receipt. With no amount counted, it fills in everything in the purse. Tap coins down to share less.
- Small icons on the bottom tabs (Party, Customize, Save & load, Ledger).
- Full documentation in the README, essentials first.

### Changed
- Receipt reordered. Players: *To whom?* first (NPC is the default), then *Which NPC?*, then *For what?*. GM: *From who or what?*, quick picks, then *For what?*.
- Receipt button now shows a character with a pouch. The old receipt icon moved to the Ledger tab.
- Round buttons (receipt, 123, pencil) share one look: bronze with a gold icon while open. A closed receipt with something filled in shows a gold ring and dot.
- The pencil now closes Customize when tapped again.
- Opening the receipt no longer pops up the keyboard.
- Header logo made smaller.

### Removed
- The separate "Share out everything" button on the party purse. *Split in party* does the same job.

### Fixed
- iPhone zoomed in when tapping a text field in the receipt and couldn't zoom back. Fields now use a size iPhones don't zoom on.
- German ledger lines read "an der Schmied". The German examples now leave out the article.

---

## 0.2.0 · 2026-10-22

### Added
- German language. LootPal follows the language of the phone or browser, and you can switch under **Customize → Language**. The choice is kept per device.
- Names LootPal gave (Player 1, Game Master, Gold…) switch with the language. Names you chose stay.

### Fixed
- Layout on narrow phones with longer German words (tabs, GM buttons, slide bar).

---

## 0.1.0

First version on GitHub, then called QuestPouch.

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
