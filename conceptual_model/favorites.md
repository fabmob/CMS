Favorites
=========

[JSON Schema](schemas/favorites.schema.json)


Attributes
----------


| Name                   | Type
| -----------------------|----------
| adresses               | Array of [named addresses](#named-address)
| transportationModes    | Array of strings: <br/>- pedestrian<br/>- bus<br/>- metro<br/>- trolleyBus<br/>- tram<br/>- water<br/>- funicular<br/>- cableway<br/>- car<br/>- bicycle<br/>- taxi<br/>- chauffeur<br/>- scooter<br/>- moped<br/>- motorcycle<br/>- carshare<br/>- train<br/>- coach<br/>- air


Definitions
-----------


### Named address

| Name              | Type                                                  | Required | Format
| ------------------|-------------------------------------------------------|----------|---------------------------------
| name              | string                                                | yes      | any
| value             | [postal address](field-types.md#postal-address-field) | yes      | -

