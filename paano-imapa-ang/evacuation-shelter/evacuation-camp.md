## Evacuation Camp

---

Evacuation camps are temporary communities for people displaced by humanitarian or or other emergency crisis, and host shelters and other facilities for large groups of people.

Even if their nature is temporary, mapping these sites in OSM offers a quick way to share open data about camps and communities between humanitarian agencies. The data can be archived after the site closes.

### **Geometry**

Set a [node](http://wiki.openstreetmap.org/wiki/Node)[![](http://wiki.openstreetmap.org/w/images/thumb/7/76/Osm_element_node.svg/20px-Osm_element_node.svg.png "Node")](http://wiki.openstreetmap.org/wiki/Elements#Node) or draw as an [area](http://wiki.openstreetmap.org/wiki/Area)[![](http://wiki.openstreetmap.org/w/images/thumb/e/e6/Osm_element_area.svg/20px-Osm_element_area.svg.png "Area")](http://wiki.openstreetmap.org/wiki/Elements#Area_.28closed_way.29) along the building outline, as may be appropriate.

> **WARNING**: Before mapping any displaced community, communicate with other humanitarian actors and be _**wary of mapping such communities in conflict areas**_. The safety of the residents must come first.



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

---

#### Other facilities

Other facilities and services in the camp may also be tagged:

**Geometry: **Set a [node](http://wiki.openstreetmap.org/wiki/Node)[![](http://wiki.openstreetmap.org/w/images/thumb/7/76/Osm_element_node.svg/20px-Osm_element_node.svg.png "Node")](http://wiki.openstreetmap.org/wiki/Elements#Node) or draw as an [area](http://wiki.openstreetmap.org/wiki/Area)[![](http://wiki.openstreetmap.org/w/images/thumb/e/e6/Osm_element_area.svg/20px-Osm_element_area.svg.png "Area")](http://wiki.openstreetmap.org/wiki/Elements#Area_.28closed_way.29) along the building outline, as may be appropriate,



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



