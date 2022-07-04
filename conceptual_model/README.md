Data model
==========


Principles
----------

One goal is to be able to share data about the identity of
a transportation user.

For each claim we want to be able to know the data source, and
if it has been certified.

We defined for this purpose special data types, each with the following 
attributes :

| Name              | Type       | Description
| ------------------|------------|---------------------------------
| value             | any        | The claim value
| source            | string     | Source of the data
| certificationDate | datetime   | If the data was certified, and when.

Some additional attributes may be defined for some fields. See
[Field types](field-types.md).


Main Entities
-------------

- [Personal Informations](personal-informations.md)
- [Civil status](civil-status.md)
- [Favorites](favorites.md)
- [Driving Licence](driving-licence.md)


