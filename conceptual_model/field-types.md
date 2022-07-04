### Boolean field

| Name              | Type     | Required | Format
| ------------------|----------|----------|----------------------
| value             | boolean  | yes      | -
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### String field

| Name              | Type     | Required | Format
| ------------------|----------|----------|----------------------
| value             | string   | yes      | any
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### Integer field

| Name              | Type     | Required | Format
| ------------------|----------|----------|----------------------
| value             | integer  | yes      | -
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### Number field

| Name              | Type     | Required | Format
| ------------------|----------|----------|----------------------
| value             | number   | yes      | -
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)

### Date field

| Name              | Type     | Required | Format
| ------------------|----------|----------|---------------------------------
| value             | string   | yes      | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### Email field

| Name              | Type     | Required | Format
| ------------------|----------|----------|---------------------------------
| value             | string   | yes      | [RFC 5322](https://datatracker.ietf.org/doc/html/rfc5322#section-3.4)
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### Postal address field

| Name              | Type     | Required | Format
| ------------------|----------|----------|---------------------------------
| value             | string   | yes      | AFNOR NF Z 10-011
| source            | string   | no       | any
| certificationDate | dstring  | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### Phone number field

| Name              | Type     | Required | Format
| ------------------|----------|----------|---------------------------------
| value             | string   | yes      | [E.164 Standard](https://www.itu.int/rec/T-REC-E.164/)
| mobile            | boolean  | yes      | -
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### Gender field

| Name              | Type     | Required | Format
| ------------------|----------|----------|---------------------------------
| value             | number   | yes      | [ISO/IEC 5218](https://en.wikipedia.org/wiki/ISO/IEC_5218)
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)


### Country field

| Name              | Type     | Required | Format
| ------------------|----------|----------|---------------------------------
| value             | string   | no*      | any
| isoValue          | string   | no*      | [ISO 3166-1 alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3)
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)

\* one of `value` and `isoValue` attributes must be set.


### City field

| Name              | Type     | Required | Format
| ------------------|----------|----------|---------------------------------
| inseeValue        | string   | no*      | [French INSEE City code](https://www.insee.fr/fr/information/6051727)
| name              | string   | no*      | any
| source            | string   | no       | any
| certificationDate | string   | no       | [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601)

\* one of `inseeValue` and `name` attributes must be set.
