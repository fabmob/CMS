Favorites
=========

[JSON Schema](schemas/favorites.schema.json)


Attributes
----------


| Name                   | Type
| -----------------------|----------
| adresses               | Array of [named addresses](#named-address)


Definitions
-----------


### Named address

| Name              | Type                                                  | Required | Format
| ------------------|-------------------------------------------------------|----------|---------------------------------
| name              | string                                                | yes      | any
| value             | [postal address](field-types.md#postal-address-field) | yes      | -

