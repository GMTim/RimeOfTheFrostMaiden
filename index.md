---
---
## Player Characters
- Bruno Dwarfmin the Dwarf
- Deathlord of Supreme Darkness the Human
- Elmfrid Thinbristle the Owlin
- Gimble Murnig the Gnome
- "Greg" Egregkpholdur the Hobgoblin 
- Leopold the _Human_
- Mightor the Minotaur
- Milla Mistlyl the Kalashtar
- Nobu the Kobold

## [Locations](./locations/locations.md)
- [**Bryn Shander**](./locations/bryn-shander.md)

## [Session Notes](./past-sessions.md)
<em class="subtext">Session 2 (01/31/23)</em>

**Nightal 20 - 1489DR "The Year of the Warrior Princess"**  
_[Bryn Shander](./locations/bryn-shander.md)_

- You set out to find the lost ore coming from Kelvin's Cairn to Bryn Shander. You traveled for hours into the late afternoon and then evening, finally finding the site where the dwarves at been attacked. However, after a thorough investigation, you discovered that the ore had been found and taken by some small creatures, a large wagon, and some bears. You followed their tracks, but found yourselves caught up in a deadly blizzard. Thankfully, Nobu was able to guild you through the worst of it and you came upon the wagon. You discovered the wagon was owned by goblins, and being dragged by a couple of polar bears. After some tense moments, the goblins agreed to give you the ore in exchange for you murdering their leader. After some debate, you dragged this fat and warm goblin out of the wagon, and despite his efforts, tied him up and threw him to the bears. The rest of the goblins invited you to wait out the blizzard, which took a few more hours to settle down. After which you used a floating disk spell to drag the sled of ore back to Bryn Shander where you where each awarded a gem worth 50gp. Exhausted after spending the whole night in the wilderness you went to sleep.

**Nightal 21 - 1489DR "The Year of the Warrior Princess"**  
_[Bryn Shander](./locations/bryn-shander.md)_

- You questioned your next steps, and decided to spend the rest of the day in Bryn Shander, before making your way to one of the other Ten Towns the next day. Most of you traded in your gems for coin, and all of you purchased a set of Snow Shoes to make walking the roads much easier.
- Nobu wandered around town, and after much rejection was asked to find a Snow Snipe. He later learned that this was not a real animal, but a joke one of the residents of Bryn Shander played on him.
- Bruno indebted himself to the dwarves of the Blackiron Blades in exchange for partially financing a set of Chainmail. With the help of Mightor his debt is already mostly repaid.
- Elmfrid set about telling the tale of the goblins from the night before, leaving out the pack made with goblins, and instead explaining the party had simply killed them all.
- The party heard that Targos has a band of adventurers planning an expedition up the side of Kelvin's Cairn, where they will look for Oyaminartok, a goliath werepolar bear. There might still be time to join their expedition.
- The party heard that Caer-Konig is being beset by vandals and thieves that skulk about unseen. The town speaker, a dragonborn named Trovus, could use some help catching these interlopers.
- Milla has begun the exciting journey to speaking Abyssal, the language of the lower planes. Assisted by Deathlord.
- Leopold has created a set of introduction papers designed to look as official and authoritative as possible, working through the day and night, and with the assistance of the others in the party who already have similar documentation.

Session Ended on morning of `Nightal 22 - 1489DR` after a long rest.

<script>
    function shuffleArray(array) {
        for (let i = array.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [array[i], array[j]] = [array[j], array[i]];
        }
    }
    window.addEventListener("load", (event) => {
        let button = document.getElementById("player-characters")
        button.addEventListener("click", (clickEvent) => {
            let unorderedList = button.nextElementSibling
            let items = []
            for (let item of unorderedList.children) { items.push(item) }
            for (let item of items) { item.remove() }
            shuffleArray(items)
            for (let item of items) { unorderedList.appendChild(item) }
        })
    })
</script>