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
- [**Lonelywood**](./locations/lonelywood.md)
- [**Targos**](./locations/targos.md)
- [**Termalaine**](./locations/termalaine.md)

## [Session Notes](./past-sessions.md)
<em class="subtext">Session 12 (06/20/23)</em>  
**Hammer 2 - 1490DR “Year of the Star Walker's Return”** 
_[Lonelywood](./locations/lonelywood.md)_

- Party explores ruins.
- Bruno sacrifices hand and gains allegiance of holy warrior interned at the site.
- Party finds White Moose with many other animals, all of which have been uplifted by a druid. Moose attacks party who kills it.
- Party finds crazy druid with an awakened berry bush and another dead druid. Druid kills Greg and nearly kills Milla before being killed.
- Greg turns out to have been a doppelgänger, possible the whole time!
- Berry bush joins party.

Session Ended late `Hammer 2 - 1490RD` in an ancient elven ruin near [Lonelywood](./locations/lonelywood.md).

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