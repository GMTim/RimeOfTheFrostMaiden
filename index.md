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
<em class="subtext">Session 6 (03/07/23)</em>  
**Nightal 26 - 1489DR "The Year of the Warrior Princess"**  
_[Easthaven](./locations/easthaven.md)_

- On the evening before your quarry is set to arrive, you staying at the White Lady Inn, and a halfling named Rinaldo invited you to a seance. There he channels the White Lady, a spirit of a long deceased woman whom the inn gets it's name. You find out that the Duergar are in all three cities around Lac Dinneshere. You also find out that in life, she was a slaver and an evil woman, though she did not want to impart that information to you. You quickly come to the realization that she is more than just a channeled presence, that she's also a poltergeist. Based on how strong her presence was here, you came to the conclusion that whatever she was haunting, it must have been brought much closer then it was originally. Rinaldo then remembers that they just brought in some piece of a boat from out on the lake, and that it's in the town hall right now.
- Elmfrid decided to scout out the city, and while flying by the town hall he saw an object in a back room through a window. Taking a closer look he spotted a large ships figurehead, and tied to it a soaking wet woman all in white with white hair. When he looked away and back up she was no longer there. Returning to the party, it was decided that now was the time to deal with this while the city slept, and you all went and woke up Captain Imdara. Annoyed, but willing to humor you, she opened the town hall for you to investigate. You gave he a bag of salt, and asked her to ring the building with it. She seemed dubious at first, but agreed to do it anyway. Once inside, you concocted a plan to keep the woman busy while Bruno with his knowledge of true names, and this ghostly woman in particular, would work a ritual designed to bind her to the ethereal plane so you could figure out a more permeant solution.
- With your plan in place, you all rushed in to confront the ghost, where Deathlord immediately froze up. It turns out the figurehead is made out of the same crystal as the one Deathlord found before, and a presence in the crystal had wormed its way into her thoughts, pretending to be here. While she stood wrestling with what she thought as her own thoughts, the White Lady added Bruno. She tried to posses him, but his dwarven stubbornness cast her back. And a barrage of magics from the other wizards in the party hurt and confused her. She tried again on others, each time being barraged by magics, until she finally possessed Elmfrid.
- Using Elmfrid's natural ability to fly, she took to the air and avoided the rest of your attempts to grab him. Milla then cast feather fall on him in an effort to thwart his ability to fly, but he quickly compensated by simply flapping down when the need arose. He made it out the front door of the town hall cackling with glee, until ghost hit salt circle. Harshly and painfully the White Lady was thrown back way from the salt, while Elmfrid, still under the effect of Feather Fall drifted down to the snowy ground. Dumbfounded, Captain Imdara saw the whole thing, but Elmfrid assured her they had everything under control before making his way back inside the hall.
- While this was happening, Bruno using the figurehead as a focus for his ritual, began to understand that a second presence was with them. A malevolent being in the figurehead had coils of black ethereal rope bound around the White Lady. Along with that, Bruno could see tendrils of black reaching out, including a thin one reaching over to Deathlord's pack. He could also her the inner argument in Deathlord's mind, and realized one of the voiced was not actually Deathlord's. When Burno completed the ritual, binding the ghost to the ethereal for a year and a day (he hoped), he made a passing thread at the being, who simply laughed at him.
- After the battle, you found out the figurehead had been brought here, because it was causing folks near it to become corrupted, and so it was decided to try and destroy it, but so far nothing seems to be able to. Captain Imdara charged the party with finding out how to deal with it, and other crystals that may be found. Also, as the party discussed the events of that evening the revelation of Duergar in the area came up, and Captain Imdara also charged them with keeping her informed about that as well. Offering a reward for information and actions taken against them. She also offered them a reward for the nights work, and asked them to find her tomorrow after she has had a chance to sleep. The party then returns to the White Lady Inn for a long rest.


Session Ended on morning of `Nightal 27 - 1489DR`.

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