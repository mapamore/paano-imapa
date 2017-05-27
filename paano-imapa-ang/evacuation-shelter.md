# Evacuation Facilities

Local governemnts identify assembly areas,  and maintain shelters for use during emergencies and other humanitarian crises.

> When using tags, remember that not all are needed, but as many as possible \(when known\) should be used.

**Table of Contents**

1. [Assembly Area](#assembly-area)  
2. [Dedicated Shelter](#dedicated-shelter)  
3. [Multi-purpose Shelter](#multi-purpose-shelter) 
4. [Evacuation Camp](#evacuation-camp)  
5. [Additional Tags](#extratags)

## Assembly Area

---

The assembly area is a meeting point designated \(safe\) place where people can gather or must report to during an emergency or a fire drill etc. [^1]

This may also be known as: evacuation area, muster point, assembly point.

**Geometry**: Node, Way

**Tags**:

`emergency=assembly_point`

## Dedicated shelter

---

A dedicated emergency shelter is a place for people to live temporarily when they cannot live in their previous residence, similar to homeless shelters. [^2]

Dedicated shelters are purposed-built facilities, and designed _exclusively_ as a shelter for emergencies as opposed to multi-functional facilities that were designed primarily for another purpose.

**Geometry**: Way

**Tags**:

```
social_facility=shelter
social_facility:for=displaced
social_facility:capacity=*
shelter_type=floods;earthquake;tsunami;debris_flow;tsunami
name=*
```

## 

## Multi-purpose shelter

---

A multi-purpose emergency shelter is a place for people to live temporarily when they cannot live in their previous residence, similar to homeless shelters. [^2]

Multi-purpose shelters normally serves a different function, and turns into temporary shelters during emergencies.

**Geometry**: Way

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

## Evacuation Camp

---

Evacuation camps are temporary communities for people displaced by humanitarian or or other emergency crisis, and host shelters and other facilities for large groups of people.

Even if their nature is temporary, mapping these sites in OSM offers a quick way to share open data about camps and communities between humanitarian agencies. The data can be archived after the site closes.

**WARNING**: Before mapping any displaced community, communicate with other humanitarian actors and be _**wary of mapping such communities in conflict areas**_. The safety of the residents must come first.

Example of evacuation camp tagging:

###### Common

```
amenity=social_faciity
social_facility=shelter
social_facility:for=displaced
name=*
short=*
owner=*
operator=
operator:type=
access=
capacity=
landuse=residential
fixme=boundary is approximated
```

###### Extra

```
temporary=yes
start_date=2017-05-24
```

#### Other facilities

Other facilities and services in the camp may also be tagged:

###### Toilets

```
amenity=toilets
```

###### Water sources

```
/*potable water*/
amenity=drinking_water //implies potable water
drinking_water=yes //explicity indication of potability

/*water tap*/
amenity=water_point
drinking_water=no

/*water wells, hand-pumped*/
man_made=water_well
pump=manual
```

###### Kitchen

```
amenity=kitchen
```

###### Clinic

```
amenity=clinic
```

###### Place of Worship

```
amenity=place_of_worship
religion=*
```

###### Kitchen

```
/*non-residential facility that provides prepared meals*/
social_facility=soup_kitchen

/*communal kitchen*/
amenity=kitchen
```

###### Place of Worship

```
amenity=place_of_worship
religion=*
```

###### Wash Center

```
amenity=wash_center
```

### Additional Tags - Great to have, but optional.

---

Additional tags may be used to provide better context to the information:

###### Operator

```
emergency:operator=San Juan City
emergency:operator:type=government
emergency:operator:phone=+63*
```

###### Facility

```
emergency:social_facility:opening_hours=closed 
emergency:social_facility:phone=+63*
emergency:social_facility:source=San Juan CDRRMO
```

###### Address

```
addr:city=San Juan
addr:district=1
addr:village=Barangay
addr:housenumber=123
addr:street=Sesame Street
addr:full=123 Sesame Street, Neighborhood, Barangay, Municipality
```

[^1]: [Meeting point](https://en.wikipedia.org/wiki/Meeting_point)

[^2]: [Emergency Shelter](https://en.wikipedia.org/wiki/Emergency_shelter)

