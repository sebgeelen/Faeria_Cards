# Faeria Cards Builder

## About Faeria
Faeria combines the core values of Strategy Card Games together with a Living Board, giving you the ability to shape the board as you play to create mind-blowing strategies. Each game of Faeria is not only unique, beautiful and fast-paced but also highly competitive.

More about Faeria on [Faeria.com](https://www.faeria.com)

## About Faeria Cards Builder
Faeria Cards Builder is a public git repository to allow Faeria communities to create deck building features or any community-related features arising from this.

## How to use
Faeria Cards Builder is composed of 3 main things:
- Merlin_shortened.csv: contains the actual code for each cards
- Card Anatomy: contains all the files related to building a card layout
- Cards Illustrations: contains the illustrations for each Faeria cards

### Merlin
Merlin is our own coding languages for cards. Inside the shortened version, you'll be able to pull: card_id;card_name;card_type;gold;faeria;lake;forest;mountain;desert;power;life;text;codex;number_in_codex;_codex_id

### Different functions
Here is a listing and their meaning of the functions used on the Merlin_shortened.csv file:
- {ranged_attack}: _Ranged:_ Can attack up to 5 spaces away in a straight line. Can't move and attack in the same turn.
- {charge|}: _Charge {0}:_ Can move up to {0} spaces in a straight line.
- {gift}: _Gift:_ Does something when you play this card from your hand.
- {production}: _Production:_ Does something at the start of each of your turns.
- {combat}: _Combat:_ Does something whenever this creature fights another creature.
- {protector}: _Protection:_ The next time this creature would take damage, it ignores it and loses Protection instead.
- {taunt}: _Taunt:_ Opponent's creatures adjacent to this one can't do anything else than attacking it.
- {haste}: _Haste:_ Can attack, harvest and move the turn you play it.
- {last_words}: _Last Words:_ Does something when this creature dies.
- {deathtouch}: _Deathtouch:_ Instantly destroy any creature this creature damages.
- {aquatic}: _Aquatic:_ Can move in the ocean and lakes, but not on other lands.
- {jump}: _Jump:_ Can move up to 2 spaces, jumping over anything in its way.
- {flying}: _Flying:_ Can move over the ocean.
- {activate}: _Activate:_ Once per turn, you may click structure to activate its effect.
- {options|option_1|option_2}: _Choose one:_ Allows you to choose between different options.
- {faeria|}: _Faeria {0}:_ Receives {0} Faeria

## When is this git updated?
Each time a new master version is published on our platforms (Steam, iOS, Android etc.), this git is updated. This should happen once per week but on some occasion, it might happen multiple times per week.

## Usage
Even though this is a public repository, everyone here is subject to our [Terms & Conditions](https://www.faeria.com/legal-mentions)
