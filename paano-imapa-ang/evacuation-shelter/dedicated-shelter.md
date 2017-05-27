## Dedicated shelter

A dedicated emergency shelter is a place for people to live temporarily when they cannot live in their previous residence, similar to homeless shelters. [^1]

Dedicated shelters are purposed-built facilities, and designed _exclusively_ as a shelter for emergencies as opposed to multi-functional facilities that were designed primarily for another purpose.

### **Geometry**

Set a [node](http://wiki.openstreetmap.org/wiki/Node)[![](http://wiki.openstreetmap.org/w/images/thumb/7/76/Osm_element_node.svg/20px-Osm_element_node.svg.png "Node")](http://wiki.openstreetmap.org/wiki/Elements#Node) or draw as an [area](http://wiki.openstreetmap.org/wiki/Area)[![](http://wiki.openstreetmap.org/w/images/thumb/e/e6/Osm_element_area.svg/20px-Osm_element_area.svg.png "Area")](http://wiki.openstreetmap.org/wiki/Elements#Area_.28closed_way.29) along the building outline, as may be appropriate.

**Tags**:

```
social_facility=shelter
social_facility:for=displaced
social_facility:capacity=*
shelter_type=floods;earthquake;tsunami;debris_flow;tsunami
name=*
```

---

## Multi-purpose shelter

A multi-purpose emergency shelter is a place for people to live temporarily when they cannot live in their previous residence, similar to homeless shelters. [^2]

Multi-purpose shelters normally serves a different function, and turns into temporary shelters during emergencies.

### **Geometry**

Set a [node](http://wiki.openstreetmap.org/wiki/Node)[![](http://wiki.openstreetmap.org/w/images/thumb/7/76/Osm_element_node.svg/20px-Osm_element_node.svg.png "Node")](http://wiki.openstreetmap.org/wiki/Elements#Node) or draw as an [area](http://wiki.openstreetmap.org/wiki/Area)[![](http://wiki.openstreetmap.org/w/images/thumb/e/e6/Osm_element_area.svg/20px-Osm_element_area.svg.png "Area")](http://wiki.openstreetmap.org/wiki/Elements#Area_.28closed_way.29) along the building outline, as may be appropriate.

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

