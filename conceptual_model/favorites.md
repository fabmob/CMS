Favorites
=========

[JSON Schema](schemas/favorites.schema.json)


Attributes
----------


| Name                   | Type
| -----------------------|----------
| adresses               | Array of [named addresses](#named-address)
| transportationModes    | Array of strings: <br/>- pedestrian<br/>- public-transport<br/>- car<br/>- bicycle<br/>- taxi<br/>- chauffeur<br/>- scooter<br/>- moped<br/>- motorcycle<br/>- carshare<br/>- train<br/>- coach


Definitions
-----------


### Named address

| Name              | Type                                                  | Required | Format
| ------------------|-------------------------------------------------------|----------|---------------------------------
| name              | string                                                | yes      | any
| value             | [postal address](field-types.md#postal-address-field) | yes      | -

