---
---
## Player Characters
- Bruno Dwarfmin the Dwarf
- Deathlord of Supreme Darkness the Human
- Elmfrid Thinbristle the Owlin
- Gimble Murnig the Gnome
- "Greg" Egregkpholdur the Hobgoblin 
- Leopold the _Human_
- Milla Mistlyl the Kalashtar
- Nobu the Kobold

## [Locations](./locations/locations.md)
- [**Bryn Shander**](./locations/bryn-shander.md)

## [Session Notes](./past-sessions.md)
<em class="subtext">Session 1 (01/24/23)</em>

**Nightal 20 - 1489DR "The Year of the Warrior Princess"**  
_Bryn Shander_

- Met a group of dwarves (Hruna, Korux, Storn) who lost a load of ore on the way to Bryn Shander from Kelvin's Cairn. They claim to have been accosted by a yeti, and forced to flee. Their injuries would agree with them. They have offered each member of your party a "fat shiny gem" for returning their ore to the Blackiron Blades smithy in Bryn Shander.
- You visited The Northlook Inn and Tavern, and secured a set of rooms for the next 10 day.
- You met a dwarf at The Northlook Inn named Hlin Trollbane. He offered to pay you each 100gp to murder a man he suspects of being a serial killer. The man, Sephek Kaltro is traveling with a nefarious group known as Torg's Caravan. The killings have taken place in Byrn Shander, Targos, and Easthaven.
- Hlin Trollbane told you everything he knows about yeti's, which is they are smart, mean, strong, and will ambush you. They are not venomous or prone to extended stalkings or revenge. They are not susceptible to the cold.
- Milla overheard in The Northlook that Speaker Masthew in Termalaine had to close the mine due to a gang of kobolds endangering the mines. Apparently anyone who clears them out can expect to be well compensated.
- Leopold overheard in The Northlook that a white moose has been terrorizing Lonelywood. It has so far completely evaded capture by all the hunters and trappers who have sought it out.
- Gimble learned of Mishann, an elven worshipper of Amaunator, or as she was quick to point out The Morninglord.
- The party went and met with Duvessa Shane, Speaker of Bryn Shander, and learned about the sacrifices each town makes in an attempt to appease Auril, the goddess of winter. Some towns sacrifices warmth, some food, and some people. You know for a fact Bryn Shander and Easthaven sacrifice people. Byrn Shander uses a lottery system of folks who live in the town.

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