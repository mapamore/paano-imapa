| Feature | Local | Geometry | Basic | Extended | Advanced | General note | Note for experienced users | FIXME |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Barangay Hall |  | Way | amenity=townhalltownhall:type=villagename=\* | addr=\*building=public<p>admin\_level=10 | contact:_=_building:levels=\* |  |  |  |
| Sub-offices |  | Point | office=administrativename=\* | addr:floor=_addr:unit=_admin\_level=10 | contact:_=_ |  |  |  |
| Tanod Stations, permanently manned |  |  | amenity=policename=Barangay X Outpostoperator=Barangay X |  | contact:_=_ | Only if stations are permanently manned, like the duty post of shift OIC. |  |  |
|  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |
| Place name |  | Node | name=Payapaplace=village |  | admin\_level=10designation=barangayis\_in:town=_ \(or, is\_in:city=_\)is\_in:suburb=Poblacion | Node should be placed in the commons \(park, basketball court, or right outside the barangay hall\). Correct: PayapaIncorrect: “Barangay Payapa” |  |  |
| Boundary |  | Relation |  |  | boundary=administrativeadmin\_level=10type=boundary |  | Place node should be designed as “admin\_centre” in the boundary relation. |  |
| Sitio or Purok Name |  | Node | name=Payapaplace=neighbourhood |  | admin\_level=11designation=sitio \(or purok\)is\_in:village=_is\_in:town=_ \(or, is\_in:city=\*\)is\_in:suburb=Poblacion | Use only the proper name, drop “Sitio” or “Purok” prefix. Correct: PayapaIncorrect: “Sitio Payapa” |  |  |
|  |  |  |  |  |  |  |  |  |
| Health / Wellness Centers |  | Way | amenity=clinicname=\* |  |  |  |  |  |
| Pharmacy | Botika sa Barangay |  | amenity=pharmacyoperator:type=publicname=\* | opening\_hours=Mo-Fr 08:30-16:00; Sa 10:00-15:00; PH off |  |  |  |  |
| Daycare Center |  |  | amenity=kindergartenname=\* |  |  |  |  | kindergarten x childcare |
| Stage |  |  | amenity=theatretheatre:type=amphi |  |  |  |  |  |
| Multi-purpose Building |  |  | building=publicamenity=community\_centre |  |  |  |  |  |
| Flag pole |  | Node | man\_made=flag\_pole |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |
| LANDUSE and Planning |  |  |  |  |  |  |  |  |
| Residential |  | Way | landuse=residential |  |  |  |  |  |
| Business establishments |  |  | landuse=retail |  |  |  |  |  |
| Offices |  |  | landuse=commerical |  |  |  |  |  |
| Large, institutional complexes |  |  | landuse=institutional |  |  |  | May be used for religious, government, corporate, or community “complexes” or “compounds” |  |
| Factories, workshops,  and industrial warehouses |  |  | landuse=industrial |  |  |  |  |  |
| Farmland |  |  | landuse=farmland | crop=\* |  |  |  |  |
| Fish farms |  |  | landuse=aquacultureaquaculture=fish |  |  |  |  |  |
| Vegetables orchard |  |  | landuse=orchard |  |  |  |  |  |
| Kitchen garden |  |  |  |  |  |  |  |  |
| Mining and quarry |  |  | landuse=quarryresource=aggregate |  |  |  |  |  |
| Landfill |  |  | landuse=landfill |  |  |  |  |  |
| Garden |  |  | leisure=garden |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |
| Waterworks |  |  |  |  |  |  |  |  |
| Public water points |  | Node | amenity=drinking\_water |  |  |  |  |  |
| Water well, and pumps |  | Node | man\_made=water\_well |  |  |  |  |  |
| Bulk water |  |  | amenity=water\_pointdrinking\_water=yes |  |  |  |  |  |
| Pipeline |  |  | man\_made=pipelinesubstance=water |  |  |  |  |  |
| Pipeline, valve |  |  | pipeline=valve |  |  |  |  |  |
| Pipeline, marker |  |  | pipeline=markersupport=ground |  |  |  |  |  |
| Water storage | Tangke |  | building=storage\_tankcontent=waterman\_made=storage\_tank |  |  |  |  |  |
| Water tower |  |  | man\_made=water\_tower |  |  |  |  |  |
| Water Works |  |  | man\_made=water\_works |  |  |  |  |  |
| Water reservoir |  |  | landuse=reservoirman\_made=reservoir\_coveredreservoir\_type=water\_storage |  |  |  |  |  |
| Spring | Bukal |  | drinking\_water=yesnatural=spring |  |  |  |  |  |
| Stream | Sapa, Creek |  | waterway=stream |  |  |  |  |  |
| Ditch | Irrigation canal |  | waterway=ditch |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |
| Recycling and Waste Disposal |  |  |  |  |  |  |  |  |
| Dumpster |  |  | amenity=waste\_disposal |  |  |  |  |  |
| Trash can / Rubbish bins |  |  | amenity=waste\_basket |  |  |  |  |  |
| Sanitary dump |  |  | amenity=sanitary\_dump\_station |  |  |  |  |  |
| Recycling Center |  |  | amenity=recyclingrecycling\_type=centre |  |  |  |  |  |
| Recycling container |  |  | amenity=recyclingrecycling\_type=container |  | recycling:cardboard=yesrecycling:_=_ |  |  |  |



