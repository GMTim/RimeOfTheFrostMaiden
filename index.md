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
- [**Targos**](./locations/targos.md)

## [Session Notes](./past-sessions.md)
<em class="subtext">Session 3 (02/07/23)</em>

**Nightal 22 - 1489DR "The Year of the Warrior Princess"**  
_[Bryn Shander](./locations/bryn-shander.md)_

- You set out and head towards Torgos, which takes a few hours of your morning to get to.

_[Targos](./locations/targos.md)_

- Outside of the wooden palisades of Targos, you are met by a panicked dog. Following it, you are led to the home of Keegan and Garret Velryn. Keegan tells you the dog, named Guy, was the lead of his husband Garret's dog team. He was leading an expedition up Kelvin's Cairn, and if this dog is here that means something terrible has happened. Keegan, worried about his husband, has asked your group to find him and hopefully return him safely home. He offered your group free rooms at the Luskan Arms, the local inn in Targos. He also offered you a few small scrimshaw figurings, but you turned them down. Keegan then tells you that he doesn't know where Garret's base camp would be, but that he traveled to the Frozenfar Expeditions in Caer-Konig, and someone there might know.
- Your party set out from Targos, spending most of the day to walk around to Caer-Dineval on your way to Caer-Konig.

_[Caer-Dineval](./locations/caer-dineval.md)_

- As _night_ approached, and the winter cold threatened to drop the temperature even more, you decided to stop over in Caer-Dineval. Asking around, you discover that the inn, Dinev's Rest, was permanently closed. However the tavern, The Uphill Climb, might have a fire you could sleep next to. You make your way to the tavern, where you meet a burly tavern keep named Roark. He allows you use of his extra rooms in exchange for you finding out what happened to the town's speaker, Crannoc Siever. He tells you he is up in the old Caer, and has in the past months surrounded himself with outsiders from the south. He also tells you that you can't miss the man, he is very loud.
- Deciding that you have time that evening, you approach the Caer, and after a bit of scouting, make your presence known. An albino tiefling woman named Avarice (a typical example of a tiefling name). She invites you into a cozy and warm study, and assures you that the speaker is simply ill, but will recover. She accepts your writ as emissaries of the Host Tower without any hesitation, though Milla did detect a bit of sly understanding in her when she did. As you had a pleasant discussion, she asked you that if you'd be willing, to check out the dock's where the frozen ferry is. Saying no more about why. She also subtly would steer the conversation away from why she was here in the north in the first place.
- Death Lord, wishing to be away from the warmth, took her leave, and on a whim decided to check out the ferry alone. There she discovered a ferry frozen in the lake, and when she climbed aboard found the door was slightly ajar. She lit a torch and went in, going below decks to discover a table with some parchments and a black crystal on a chain. She took the crystal and the parchments (written in dwarven) and attempted to leave when she was ambushed by a duergar. Thankfully, before entering the ferry she had cast false life on herself, and with the added protection was able to withstand several blows from the duergar's warpick. She successfully fled into the night, and got safely back to the tavern, a little worse for wear.
- Looking over the papers, the party discovered that there is some duergar fortress near by in the mountains, it's exact location unknown, and that the duergar are planing something that suggests they mean to destroy the ten towns. The parchements don't explain the plan, but it's not hard to read between the lines.
- The party durning their stay discovers that Torg's Caravan, the company that Sephek Kaltro, the serial killer you've been hired to murder, will be in Easthaven on Nightal 27. Five days from when you discovered this information.
- The party then rests that night looking to head out to Caer-Konig, and the Frozenfar Expeditions in the morning.

Session Ended on morning of `Nightal 23 - 1489DR` after a long rest.

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