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
<em class="subtext">Session 9 (04/18/23)</em>  
**Hammer 1 - 1490DR “Year of the Star Walker's Return”**  
_[Bryn Shander](./locations/bryn-shander.md)_

- On the morning of Hammer 1, you left Bryn Shander and made your way around to Termalaine.

_[Termalaine](./locations/termalaine.md)_

- You reached Termalaine around midday. There you heard a crier asking folks to help clear the mines of Kobolds. You inquire, and are directed to the Town Hall, where you meet Speaker Oarus. He informs you that the kobolds invaded the mines, and murdered some of the miners, and he hasn't been able to get anyone to go back in since. No one except one man, Jipip Hillsbane. But he was never seen again.
- You came up with a plan to send in Nobu while the rest of you took up residence outside of the mines. Nobu then shed his winter clothing, and made his way though the mines. He found a set of human footprints that mysteriously disappeared, and eventually the kobolds.
- At first he tried to claim that he was alone, but something about his story didn't sit right with the kobold leader Trex. Trex then ordered two of his kobolds to keep Nobu there, and went to the mine entrance where he parlayed with the rest of the party. The party then found out that the kobolds didn't hurt anyone and simply sought shelter in the mines. Together with the kobold leader you postulated that something else must have killed the miners. Kobolds had gone missing as well.
- Trex then lead the you all back down to Nobu, where Milla heard a psychic voice in her head. After some effort she discovered a petrified Illithid, and inside it's skull a psi crystal. It showed her an large squid like ship amongst a vast sea of other ships like it, but then something happened to it, and it crashed into the ice and snow.
- You have agreed to speak to the town to try and get them to allow the kobolds to immigrate. However, you feel like without some explanation of what happened to the miners, your pleas would fall on deaf ears. So you have decided to try and hunt down whatever it was that killed the other miners and kobolds, and use it to prove the kobolds didn't harm anyone.

Session Ended mid afternoon on `Hammer 1 - 1490RD` in the mines of Termalaine.

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