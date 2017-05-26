## Assembly Area

The assembly area is a meeting point designated \(safe\) place where people can gather or must report to during an emergency or a fire drill etc. [^1]

This may also be known as: evacuation area, muster point, assembly point.

**Geometry**: Node, Way

**Tags**:

`emergency=assembly_point`

## Dedicated Shelter

A dedicated emergency shelter is a place for people to live temporarily when they cannot live in their previous residence, similar to homeless shelters. [^2]

Dedicated shelters are purposed-built facilities, and designed _exclusively_ as a shelter for emergencies as opposed to multi-functional facilities that were designed primarily for another purpose.

**Geometry**: Way

**Tags**:

```
social_facility=shelter
social_facility:for=displaced
social_facility:capacity=*
shelter_type=earthquake;floods;debris_flow
name=*
```

## Multi-purpose Shelter

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

### Additional Tags

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

