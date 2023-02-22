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
<em class="subtext">Session 4 (02/21/23)</em>

**Nightal 23 - 1489DR "The Year of the Warrior Princess"**  
_[Caer-Dineval](./locations/caer-dineval.md)_

- You set out for [Caer-Konig](./locations/caer-konig.md), and make it there after a few hours of walking.

_[Caer-Konig](./locations/caer-konig.md)_

- When you arrive in the town, you happen to walk by the Northern Light Inn, where a white dragonborn pops out of the snow accusing you of being thieves. You accuse him back while also establishing this is Trovus, the speaker of Caer-Konig. A couple of women from the inn come out and help the speaker in, asking you to come back when you have time to help them with their actual thief problem.
- You make your way to the Frozenfar Expeditions, where you meet Atenas Swift, he tells you that Garret's expedition had come through here and that Jarthra Farzassh would know more.
- Jarthra tells you that Garret has planned on using a base camp she told him about. She then tells you where that is, and offers to guide you there for a fee, which you turn down.
- Gimble buys a couple of dogs, Gerrty and Gumdrop, along with ridding saddles for both of them. Bruno buys a dog sled. You now have an axebeak and two dogs in the party.

_Kelvin's Cairn_

- You travel for a good part of the day, part of that through a blizzard, and finally make it to the base camp where you discover the rest of Garret's dog team, and a set of tattered tents.
- You make your way up the side of the mountain, and are bleated at by some mountain goats. Maybe they where trying to warn you, or maybe they are just jerks, but soon after that an avalanche crashed into your party. Most of you successfully got out of the way of the sliding snow and rocks. Leopold and Greg however got caught in the landslide. Thankfully they survived, and other then being exhausted by the ordeal where none the worse for wear. The rest of you dug them out, and kept making your way up the mountain.
- Farther up the mountain you came across Garret who had fallen into a crevasse. You pulled him out and he told you of a yeti attack farther up the mountain. He said he was traveling with a halfling named Perilou Fishfinger, a goliath named Mokingo Growling Bear Akannathi, and a tiefling named Astrix. He was pretty sure Mokingo was dead as last he saw the man had engaged the yeti hand to hand.
- The party then climbed up a fairly sheer area, making it to the top where they discovered a cave. Outside of it was a dead goliath, who has been stripped of his meat. Inside was a mother yeti and a yeti tyke who was playing with the halfling as if she was a ball. Leopold read their thoughts and discovered that the yeti's where having a grand time, while Perilou was not.
- Bruno set an alarm spell at the entrance of the cave, and then the party lead by Mightor went in. Mightor grabbed the yeti tyke and threatened it harm unless the yeti kept back. With Milla and Leopold's uncanny abilities, communication was possible with the beast, and she pleaded with the party to just leave and not to harm her son. As the halfling was escorted away, the alarm spell went off, and party was alerted to the yeti father approaching from behind. Mightor through the psionically aided communication was able to demand their passage, and the whole party with the recovered Perilou was able to make it to safety. Elmfrid then used his ability to increase gravity to cause a small avalanche to temporally seal in the yetis.
- Perilou corroborated what Garret had told the party, and added that Astrix has fled up the mountain last she saw. The party continued their climb where they discovered poor Astrix's frozen body, with her last action trying and failing to start a fire. Along with her was an unknown dwarf who must have frozen up here before Astrix got there. In his belonging where a miner's pack, inside of which contained the needed tools to start a fire, making Astrix's fate even more cruel. On her body a potion of invisibility and a wizard's spellbook where found.
- The party and surviving members of Garret's expedition made their way down the mountain, and across the wilderness back to Caer-Konig in the early hours of the morning.

_[Caer-Konig](./locations/caer-konig.md)_

Session Ended on morning of `Nightal 24 - 1489DR` after a long rest.

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