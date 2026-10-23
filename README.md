<p align="center"><img src="lootpal-logo.png" alt="LootPal" width="420"></p>

# LootPal

An interactive coin purse for tabletop RPGs. Count coins with a tap, slide to pay, and let the Game Master hand out treasure. LootPal keeps track of who has what, makes change automatically and writes everything into a ledger.

Everything runs in one file, `index.html`. No server, no account, no installation.

LootPal is in early alpha. See the [changelog](CHANGELOG.md) for what's new.

---

## Contents

**The essentials**

1. [Getting started](#1-getting-started)
2. [Paying and receiving](#2-paying-and-receiving)
3. [The Game Master](#3-the-game-master)
4. [Save your table](#4-save-your-table)

**More detail**

5. [The receipt: who and what for](#5-the-receipt-who-and-what-for)
6. [The party purse](#6-the-party-purse)
7. [Ledger and undo](#7-ledger-and-undo)
8. [The purse screen in detail](#8-the-purse-screen-in-detail)
9. [Party settings](#9-party-settings)
10. [Customize](#10-customize)
11. [Good to know](#11-good-to-know)
12. [Put it online with GitHub Pages](#12-put-it-online-with-github-pages)

---

# The essentials

## 1. Getting started

Open LootPal and you get an example table: **Player 1**, **Player 2**, **Player 3** and the **Game Master**. Each player starts with 5 gold, 10 silver and 25 copper.

1. Tap a name in the row at the top to pick whose purse you are looking at.
2. Tap the coins to count an amount.
3. Slide the big gold knob all the way to the right to pay.

To rename someone, tap their name on the purse and type. Add or remove players under the **Party** tab at the bottom.

## 2. Paying and receiving

Choose **Pay** or **Receive** above the amount.

- **Tap** a coin to add one. **✕** clears the amount.
- **Slide** to confirm. Nothing happens until you slide all the way.
- **Change is automatic.** Pay 3 copper with only silver in the purse, and LootPal breaks a silver coin and gives you the change. The line under the amount tells you before you slide.
- When paying, you can't count more than the purse holds. Receiving has no limit.

Players pay an NPC by default. To pay another player instead, see [The receipt](#5-the-receipt-who-and-what-for).

**Made a mistake?** Every transaction shows a message with **Undo**.

## 3. The Game Master

Tap **Game Master** in the character row. The GM's coffers are **unlimited**, so coins go straight to the players.

- **Give or Take.** The switch at the top. *Give* hands out treasure and rewards. *Take* collects fines, taxes or tolls, and LootPal checks that everyone can pay.
- **Who gets it.** The tags under the coins. **Whole party** is the default and shares the amount between all players. Tap a single player to give only to them.
- Count the amount and slide, as with a player.

More GM tools (Split or Each, Mixed bag, Repeat, the GM's book) are described in [More for the Game Master](#more-for-the-game-master).

## 4. Save your table

LootPal saves itself in the browser it runs in, but browsers can forget, for example when you clear your history. **Make a backup after each session** under the **Save & load** tab:

- **Save code.** A line of letters and numbers holding the whole table. Copy it into a note or a message to yourself.
- **Save file.** Downloads the table as a small `.json` file.
- **Load.** Paste a code or pick a file. LootPal shows what it holds and asks before replacing the current table.

Save codes and files also move a table to another phone or browser.

---

# More detail

## 5. The receipt: who and what for

The round button with the character and pouch (left of the amount) opens the receipt. Everything in it is optional and goes into the ledger.

**When a player pays:**

1. **To whom?** NPC is the default. Tap another player to pay a companion, and the coins go straight into their purse.
2. **Which NPC?** For example *the blacksmith*. Only shown when paying an NPC.
3. **For what?** For example *a longsword*.

**When a player receives:** *From who or what?* (for example *the innkeeper* or *a chest*), then *For what?*

**When the GM gives:** *From who or what?* (for example *a noble knight*), quick picks (*Treasure*, *Loot*, *Reward*, *Bounty*), then *For what?* When taking, the quick picks are *Tax*, *Fine*, *Toll* and *Theft*.

The ledger then reads like a sentence: *Player 1 to the blacksmith for a longsword*.

When the receipt is closed but something is filled in, its button shows a gold ring and a small dot.

### More for the Game Master

- **Several players.** Hold a name in the tags to add or remove more players.
- **Split or Each.** With several players chosen, *Split* divides the amount between them and *Each* gives the full amount to every one of them. What doesn't divide evenly stays in the coffers.
- **Mixed bag.** Pays treasure out as a random mix of coin types with exactly the same value, like a real hoard. Off by default.
- **Repeat.** After a payout, a **↻ Repeat** button appears under the empty amount. One tap sets up the same payout again.
- **The Game Master's book.** Shown under the GM's purse and in the ledger: how much the players paid in, how much the GM paid out, and every player's current purse.

## 6. The party purse

A shared purse for the group. Add it under **Party → + Add a party purse**.

- Players pay into it like paying a companion.
- It gets no share of "Whole party" payouts from the GM, and no starting purse.
- **To share it out**, open the receipt on the party purse and tap **Split in party**. With no amount counted, it fills in everything in the purse. Tap coins down to share less. What doesn't divide evenly stays in the purse.
- It can also pay an NPC, like a player.

## 7. Ledger and undo

The **Ledger** tab shows the latest entries: who paid whom, what for, and how much. Rename a character and their old entries follow.

**Undo.** Besides the message after each transaction, the ledger has an undo button for the latest transactions. Undo lasts until you reload the page.

**Deeds.** When deeds are on, each character's deeds are shown at the top of the ledger. Tap an earned deed to hear its tune.

## 8. The purse screen in detail

**Faster counting**

- **Hold** a coin to count up, faster and faster.
- **Drag** up or down on a coin to wind the amount.
- **123** opens fields to type the amount. Handy for big treasure.
- **Swipe** sideways across the amount to switch between Pay and Receive.

**The round buttons.** Receipt (left top), 123 (left bottom), pencil to edit coins (right top), ✕ to clear (right bottom). A button turns bronze with a gold icon while it is open.

**Stacks.** Every coin in the purse is drawn, ten to a stack. Every full fifty goes into a small pouch with a count, so 137 silver shows two pouches (×2) and 37 loose coins. While you count an amount, coins that will leave fade out, change you get back shows as dashed coins, and the number below shows the change, for example **10 → 9**.

**Title and weight.** The small label under the name is the wealth title, for example *Comfortable*. If purse weight is switched on, a line shows the weight, a description like *Tugs at your belt* and a belt bar.

## 9. Party settings

Under the **Party** tab:

- **Who's at the table.** Rename or remove players. Leave the name empty when adding to get *Player 4*, *Player 5* and so on. Removing asks twice.
- **+ Add a party purse.** See [The party purse](#6-the-party-purse).
- **Starting purse.** What new players start with. Set everything to 0 for empty purses. **Give everyone the starting purse** sets every player's purse to it (asks twice, and can be undone).
- **Name of the NPC tag.** Change "NPC" to something that fits your world, for example *The Realm* or *Merchants*.
- **Start over.** Back to the example table (asks twice).

## 10. Customize

Under the **Customize** tab, or the pencil next to the amount:

**Coins.** Up to six coin types. For each coin: name, short name (used in amounts like *6g 2s*), colour, shape (round, holed, square, triangle, hexagon, diamond) and worth. The cheapest coin is the base and is always worth 1. Every other coin is worth a whole number of base coins, so uneven systems like 12 pence to the shilling work too. Removing a coin, or resetting to gold, silver and copper, changes everyone's coins at their value, so nobody gets richer or poorer.

**Wealth & weight.**

- **Wealth title** (on by default). A ladder of titles from *Penniless* to *Wealthy*. Rename the steps and set the amounts to fit your campaign.
- **Purse weight** (off by default). Weight, description and belt bar. Set grams or ounces per coin and when the belt is full.

**Deeds** (off by default). Six small achievements per character, such as *First Purchase* or *Dragon's Hoard*, each with its own lute tune.

**Language.** English or German. See [Good to know](#11-good-to-know).

**Sound settings.** Volume, and each sound on or off: counting coins (metal on metal), paying and receiving (coins on a wooden table and a leather pouch), deed tunes, a flourish for GM payouts, and vibration on phones that support it. The **Sound on** button at the top switches all sound at once.

## 11. Good to know

- **One table per device.** Each phone or browser keeps its own table. Syncing between phones is planned, but not there yet. Until then, move tables with a save code or file.
- **Languages.** LootPal speaks English and German. It picks the language of the phone or browser, and you can switch under **Customize → Language**. The choice is kept per device, so a German player and an English GM can share a save code. Names LootPal gave, like *Player 1* or *Gold*, change with the language. Names you chose stay as they are.
- **On your home screen.** Open LootPal in the browser and choose **Add to Home Screen** (iPhone: the share button in Safari; Android: the ⋮ menu in Chrome). It gets the LootPal icon and opens full screen like an app. On iPhone, the home-screen app keeps its own table, separate from Safari, so move an existing table over with a save code.
- **Your data stays with you.** Nothing is sent anywhere. The only thing loaded from the internet is the font.
- **Online and claude.ai versions are separate.** Tables don't carry over between them, except through a save code or file.
- **Shorter save codes.** Untick *Include the ledger* when making a save code.
- **Older saves.** Save codes and files from earlier versions, including the time LootPal was called QuestPouch, still load.

## 12. Put it online with GitHub Pages

1. Create a new repository on GitHub, for example `lootpal`.
2. Click **Add file → Upload files** and upload all the files: `index.html`, `manifest.webmanifest`, the icons (`apple-touch-icon.png`, `favicon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`), `lootpal-logo.png`, this README and the CHANGELOG. Commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute or two, LootPal is live at `https://<your-username>.github.io/lootpal/`.

To update it later, upload a new `index.html` over the old one. You can also open `index.html` straight from your computer by double-clicking it.
