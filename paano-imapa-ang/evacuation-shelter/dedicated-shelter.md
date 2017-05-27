## Dedicated shelter

---

A dedicated emergency shelter is a place for people to live temporarily when they cannot live in their previous residence, similar to homeless shelters. [^1]

Dedicated shelters are purposed-built facilities, and designed _exclusively_ as a shelter for emergencies as opposed to multi-functional facilities that were designed primarily for another purpose.

**Geometry**: Area

**Tags**:

```
social_facility=shelter
social_facility:for=displaced
social_facility:capacity=*
shelter_type=floods;earthquake;tsunami;debris_flow;tsunami
name=*
```

## Multi-purpose shelter

---

A multi-purpose emergency shelter is a place for people to live temporarily when they cannot live in their previous residence, similar to homeless shelters. [^2]

Multi-purpose shelters normally serves a different function, and turns into temporary shelters during emergencies.

**Geometry**: Area

**Tags**:

Tags are similar to dedicated shelters, except for the `emergency:` prefix before tags.

```
amenity=school
emergency:social_facility=shelter
emergency:social_facility:for=displaced
emergency:social_facility:capacity=*
emergency:shelter_type=earthquake;floods;debris_flow
name=*
```

> These `emergency:` tags has been adopted by the OSMtw community [^3]

Example of a "Covered Court" tagged an emergency shelter during tyhpoons:

```
leisure=sports_centre
sport=multi
name=Palakasan Covered Court
emergency:social_facility=shelter
emergency:social_facility:for=displaced
emergency:social_facility:capacity=*
emergency:shelter_type=typhoon
```

[^1]: [Emergency Shelter](https://en.wikipedia.org/wiki/Emergency_shelter)

