French DGFIP Information
========================

A person's French DGFIP information

TODO: improve information on tax notices, add information of persons attached 
to declarants.

[JSON Schema](schemas/fr-dgfip-information.schema.json)

Attributes
----------


| Name                   | Type     
| -----------------------|----------
| declarant1             | [DGFIP identity](#dgfip-identity)
| declarant2             | [DGFIP identity](#dgfip-identity)
| taxNotices             | [DGFIP tax notice](#dgfip-tax-notice)


Definitions
-----------

### DGFIP Identity

| Name                   | Type                                                  | Required | Format
| -----------------------|-------------------------------------------------------|----------|---------------------------------
| lastName               | [string](field-types.md#string-field)                 | no       | -
| birthName              | [string](field-types.md#string-field)                 | no       | -
| firstName              | [string](field-types.md#string-field)                 | no       | -
| middleNames            | [string](field-types.md#string-field)                 | no       | -
| birthDate              | [date](field-types.md#date-field)                     | no       | -
| birthPlace             | [city](field-types.md#city-field)                     | no       | -
| birthCountry           | [country](field-types.md#country-field)               | no       | -
| email                  | [email](field-types.md#email-field)                   | no       | -
| primaryPostalAddress   | [postal address](field-types.md#postal-address-field) | no       | -
| secondaryPostalAddress | [postal address](field-types.md#postal-address-field) | no       | -
| primaryPhoneNumber     | [phone number](field-types.md#phone-number-field)     | no       | -


### DGFIP Tax Notice

| Name                   | Type                                                  | Required | Format
| -----------------------|-------------------------------------------------------|----------|---------------------------------
| declarationYear        | [integer](field-types.md#integer-field)               | no       | -
| numberOfShares         | [integer](field-types.md#integer-field)               | no       | -
| grossIncome            | [number](field-types.md#number-field)                 | no       | -
| taxableIncome          | [number](field-types.md#number-field)                 | no       | -
| referenceTaxIncome     | [number](field-types.md#number-field)                 | no       | -
| taxAmount              | [number](field-types.md#number-field)                 | no       | -
