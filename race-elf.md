::: ddtitle Elf
    Elf Race
    Elven
    Elven Race

***Your elf character has a variety of natural abilities, the result of thousands of years of elven refinement.***

::: wikitable Elven Race
    ::: table_part Source
        SRD
    ::: table_part Subraces
        [High Elf](race-elf.md#high-elf)
    ::: table_part Size
        Medium
    ::: table_part Languages
        Common, Elvish
    ::: table_part Base Speed
        30 ft.

[TOC]

## Ability Score Increase

Your Dexterity score increases by 2.

## Age

Although elves reach physical maturity at about the same age as humans, the elven understanding of adulthood goes beyond physical growth to encompass worldly experience. An elf typically claims adulthood and an adult name around the age of 100 and can live to be 750 years old.

## Alignment

Elves love freedom, variety, and self-expression, so they lean strongly toward the gentler aspects of chaos. They value and protect others’ freedom as well as their own, and they are more often good than not.

## Size

Elves range from under 5 to over 6 feet tall and have slender builds. Your size is Medium.

## Speed

Your base walking speed is 30 feet.

## Darkvision

Accustomed to twilight forests and the night sky, you have superior vision in dark and dim conditions. You can see in dim light within 60 feet of you as if it were bright light, and in darkness as if it were dim light. You can’t discern color in darkness, only shades of gray.

## Keen Senses

You have proficiency in the Perception skill.

## Fey Ancestry

You have advantage on saving throws against being charmed, and magic can’t put you to sleep.

## Trance

Elves don’t need to sleep. Instead, they meditate deeply, remaining semiconscious, for 4 hours a day. (The Common word for such meditation is “trance.”) While meditating, you can dream after a fashion; such dreams are actually mental exercises that have become reflexive through years of practice. After resting in this way, you gain the same benefit that a human does from 8 hours of sleep.

## Languages

You can speak, read, and write Common and Elvish. Elvish is fluid, with subtle intonations and intricate grammar. Elven literature is rich and varied, and their songs and poems are famous among other races. Many bards learn their language so they can add Elvish ballads totheir repertoires.

# Subraces

There are several types of elves in the world. You can choose one of the elven subraces and gain their benefits:

## High Elf

***As a high elf, you have a keen mind and a mastery of at least the basics of magic. In many fantasy gaming worlds, there are two kinds of high elves. One type is haughty and reclusive, believing themselves to be superior to non-­‐‑elves and even other elves. The other type is more common and more friendly, and often encountered among humans and other races.***

::: wikitable High Elf subrace
    ::: table_part Source
        SRD
    ::: table_part Region
        -

### Ability Score Increase

Your Intelligence score increases by 1.

### Elf Weapon Training

You have proficiency with the longsword,shortsword, shortbow, and longbow.

### Cantrip

You know one cantrip of your choice from the wizard spell list. Intelligence is your spellcasting ability for it.

::: load_json spells=data/md/dnd-wiki/spells.json
    <table class="wiki-table spell-list">
        <thead>
            <th>Spell</th>
            <th>Source</th>
        </thead>
        <tbody>
            {% for spell in spells %}
                {% if contains("Wizard", spell['classes']) %}
                    {% if spell['level'] == 0 %}
                        <tr>
                            <td>{{ spell['name'] }}</td>
                            <td>
                            {% if spell['source'] == 'SRD' %}
                                <span class="srd">
                            {% else %}
                                <span class="hbrw">
                            {% endif%}
                                    {{ spell['source'] }}
                                </span>
                            </td>
                        </tr>
                    {% endif %}
                {% endif %}
            {% endfor %}
        </tbody>
    </table>

### Extra Language

You can speak, read and write one extra language of your choice.
