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
- [**Caer-Dineval**](./locations/caer-dineval.md)
- [**Caer-Konig**](./locations/caer-konig.md)
- [**Easthaven**](./locations/easthaven.md)
- [**Targos**](./locations/targos.md)

## [Session Notes](./past-sessions.md)
<em class="subtext">Session 8 (03/21/23)</em>  
**Nightal 28 - 1489DR “The Year of the Warrior Princess”**  
_[Easthaven](./locations/easthaven.md)_

- The party left Easthaven and made their way back to Bryn Shander to take care of some unfinished business. Making it there in a few hours.

_[Bryn Shander](./locations/bryn-shander.md)_

- Once in Bryn Shander, Bruno got in contact with the folks at Black Iron Blades to see to repaying the rest of his debt to them. Mightor and Nobu both commissioned some armor while there, which took a couple of days to complete. Bruno worked the runes for friend into Mightor’s armor, a symbol that all dwarves should recognize.
- Deathlord took the cursed crystal to Mishann the priest of the Morning Lord, and with her help was able to remove the curse and unbind the item from her. Deathlord also learned from the priest that the crystal was once part of the terrible Crenshinibon, an evil malevolent magic item first defeated by Drizzt Do’Urden hundreds of years ago and thought long gone.
- Milla was arrested for attempting to purchase a set of thieves tools. Deathlord came and bailed her out. When her things where returned to her she discovered that a set of thieves tools has been slipped in with her other belongings.
- Mightor, board while waiting for his armor discovered an underground casino/fight club. After besting the regulars in a fight, Mightor and Elmfrid where alerted to the fact that the club would pay for beasts that would make a good fight. It was up to the party to figure out how to capture and surreptitiously get those creatures to the club. But they would be paid for any they did.


Session Ended on morning of `Hammer 1 - 1490DR`.

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