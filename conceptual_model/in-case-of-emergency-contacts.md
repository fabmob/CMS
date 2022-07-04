In Case of Emergency contacts
=============================

[JSON Schema](schemas/in-case-of-emergency-contacts.schema.json)


Attributes
----------

| Name                   | Type
| -----------------------|----------
| contacts               | Array of [emergency contacts](#emergency-contact)


Definitions
-----------


## Emergency contact

| Name              | Type                                                  | Required | Format
| ------------------|-------------------------------------------------------|----------|---------------------------------
| lastName          | [string](field-types.md#string-field)                 | yes      | -
| firstName         | [string](field-types.md#string-field)                 | yes      | -
| phoneNumber       | [phone number](field-types.md#phone-number-field)     | yes      | -
| emailField        | [email](field-types.md#email-field)                   | no       | -

