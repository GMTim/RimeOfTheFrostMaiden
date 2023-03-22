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
<em class="subtext">Session 7 (03/14/23)</em>  
**Nightal 27 - 1489DR "The Year of the Warrior Princess"**  
_[Easthaven](./locations/easthaven.md)_

- The morning has arrived when Sephek Kaltro was finally set to arrive in Easthaven. As the party got going, Elmfrid decided to go watch the only real road into and out of town. After a few hours he saw a caravan approach and begin to setup shop on the outskirts of town. Under the guise of an interested shopper, he approached and was greeted by a dwarven women named Torg. Once he spotted the man, and realized he was going anywhere anytime soon he went back to the party to tell them what he saw.
- While Elmfrid was doing that, most of the party went to Captain Imdara in order to get their reward for defeating the ghost. Once there Nobu saw that she had a large collection of weapons, and asked about a scimitar. Imdara gave her one from her Drizzt replica collection, a blue sword that says "Icing Death (Not Magical)" on the side. They then returned to the inn as well.
- Meanwhile, why all of that other stuff was going on Mightor had started to make giant snowballs outside the inn. Soon the children of the town took notice, and a giant full on snowball war broke out. Nobu and Elmfid decided to join while the rest of the party went back inside to wait and see if they could figure out what Sephek was up to.
- A while later, around evening, the snowball war ended in a draw and the exhausted children all went home. Around that time, Sephek and some other folks from the caravan showed up at the bar and ordered drinks. The party, surprised to see their quarry come to them where trying to think of ways to separate him from his companions. It soon became clear that his companions didn't really seem to interact with him, and eventually he took notice of the parties interest in him. He started to stare at the party, and Mightor took this opportunity to try and pick a fight with him. However the man was too collected to rise to the bait, and simply looked away. Eventually after enjoying his drink he got up and walked out of the inn alone. Most of the party followed after him, with Mightor and Deathlord staying behind to find out more about the man's companions and to delay them following along.
- Turns out the companions didn't like Sephek, thought he was weirdly cold, distant, and a little bit terrifying. He would wonder off on his own, and just as randomly reappear. Mightor and Deathlord then kept drinking with them until Mightor got a message sent from Elmfrid.
- Outside, the rest of the party chased after Sephek, he moved quickly and surefootedly down side street and allies, while the party followed him on foot and in the air. Finally the man came to a stop in a dark ally and confronted the party. Burno told the man all the evil things he had done, and asked what he had to say in his defense. The man freely admitted it, and as soon as he did Elmfrid launched a magical attack.
- As the battle raged on, Mightor and Deathlord where alerted to what was happening began to make their way over there. Mightor leaping though the city roof to roof with his magical jump spell, and Deathlord trying to keep up. In the battle Bruno extracted the mans true Sephek Kaltro Chosen of Auril. It was also discovered the man didn't like fire, though seemed to take other types of punishment uncomplaining. He also nearly killed Nobu with his icy blades, running him through despite his shielding magic. In the end Sephek tried to run away, but Mightor from on high leapt down at him catching his head with his hooves and exploding it into the ground.
- After that the party cleaned up the battle site, and took the man's body to the lake. There they dumped it into the water where an icy block formed around it and dragged it into the depths. The party then all returned to the inn and had a long rest.

Session Ended on morning of `Nightal 28 - 1489DR`.

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