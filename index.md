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
<em class="subtext">Session 5 (02/28/23)</em>  
**Nightal 24 - 1489DR "The Year of the Warrior Princess"**  
_[Caer-Konig](./locations/caer-konig.md)_

- On the morning of Nightal 24, your group decided to make it's way down to Easthaven, to wait for Sephek Kaltro. You spent many hours walking there.

_[Easthaven](./locations/easthaven.md)_

- You get to Easthaven in time to see a wizard being burned at the stake, his many terrible crimes where listed before he was set to the torch by Imdra Arlaggath, the elven captain of Easthaven's militia.
- After the crowd dispersed, Imdar spots your group, and asks you to do her a favor. Some fishermen have gone missing, and along with that folks talking about seeing something out in the lake. She asks you to walk the shore of the lake and find out what happened to the fishermen, and see if there is any truth to the sightings. She offers you gold, or free room and board, you decide to take the free room and board.

_Howling Caverns_

- You head out to walk the shore, and about an hour later you come across a fishing boat. The boat still has all of the gear and supplies in it a fisher would need, but no sign of the men. Near by is a set of cliffs usually only accessible by boat, but now accessible by frozen lake water. Tracks from the boat make you believe the fishermen might have gone into caves in the side of the cliff.
- You make your way into the southern most cave, walking along a frozen river up to a water fall. There Milla spots a bag in the ice, and in an effort to free it accidentally shattered some of the ice, which quickly formed into some sort of water elemental and tried to land-drown her. You forced it to drop her, and it fled toward the nearby lake, which you where happy to let it do.
- After climbing up the frozen waterfall, you come to a icy bridge above you. You decide to climb up where you find a set of caverns that wail loudly like a woman screeching, an effect you determine to be caused by the wind blowing into the caves. You also find an old campsite where an unknown dwarf had been staying. They kept a journal, but most of it was ruined beyond comprehension. The bits not ruined read as follows:
  - The cave are sacred to the frost giants. The carvings on the wall suggest that the giants came here to drown themselves. Did they use the hot spring as a sacrificial pool? 
  - The wind truly sounds like a wailing woman. One could easily go mad in this place.
  - I think there's someone living in these caves. Shortly after discovering the hot spring, I heard what sounded like a granny singing. When the song ended with a shrill laugh, dread sunk its teeth in me. Ye gods, that horrible cackle! I shall leave these caves in the morning and never return.
- After that you continued along the frozen river, and came across a large pool where you could clearly see the remains of many giants deep in it's frozen waters. You could also smell something terrible with a hint of something savory up ahead.
- Elmfrid decided to scout ahead by flying up to a passage above the rest of the party, and then spotted an old woman cooking something in a large stew pot. The old woman made a show of adding in some meat to the stew, and then a human foot. Elmfrid retreated to the party, and when they tried to decide what to do next, a sea hag rushed them. Trying to make them flee with her terrifying visage. When this failed, she called on the dead of the caverns to rise up, which caused the frozen skeletons to begin clawing their way out of the ice. The party wasted no time in putting the boots to the hag, and she attempted to surrender calling for a parley. Deathlord then killed her without hearing her out, which caused the cave they where in to start to collapse.
- Gimble and Greg, who had already started to flee, made it out of the cave in time to see a pack of dire wolves also flee. The rest of the party took some time and figured out that the cauldron was in fact a powerful magic item called the Cauldron of Plenty, and was being used by the hag in a fowl way. They dumped it out and then took it with them as they fled just before the collapse of the cave.
- Unfortunately Deathlord and Bruno got trapped in the falling rocks. Quick thinking from Milla and an unusual use of feather fall, allowed her to save Deathlord, but Bruno's chest had been caved in by the falling rocks (pun intended).
- Unknown to the rest of the party, Bruno's soul had been plucked up by Moradin, the All-Father, into His holy forge made of a star. There He offered Bruno a choice, he could return to the living as a dwarf in truth, but his drow side would be forged and sent back as well. Or he could join Moradin in the forge forever more. Bruno chose to return to the living, and so Moradin worked his soul on the forge, purging him of his drow side and putting it back in to his now healed body.

_[Easthaven](./locations/easthaven.md)_

- The party made their way back to Easthaven, where Imdra gave them not only the room and board, but also 100gp and a rapier to Milla from her personal collection. She also agreed to train Mightor in the way of the Fighter. After that you all decided to hunker down until Nightal 27, when Sephek Kaltro was suppose to make his way into town.

Session Ended on morning of `Nightal 27 - 1489DR` after a 3 days of downtime.

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