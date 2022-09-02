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
| source            | string     | where Data was captured. If it was certified, the certification authority becomes the source of the Data. Source is a domain name (standardized)
| certificationDate | datetime   | If the Data was certified, and when.

Some additional attributes may be defined for some fields. See
[Field types](field-types.md).


Main Entities
-------------

- [Personal Information](personal-information.md)
- [Identity](identity.md)
- [Favorites](favorites.md)
- [Driving Licence](driving-licence.md)
- [ICE Contacts](in-case-of-emergency-contacts.md)
- [French CAF Informations](fr-caf-information.md)
- [French DGFIP Information](fr-dgfip-information.md)
- [French MESRI Information](fr-mesri-information.md)


