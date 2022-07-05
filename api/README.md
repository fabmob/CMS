Authentication and API
======================


Authentication
--------------

CMS API require [OpenID Connect 1.0](https://openid.net/connect/) for 
authentication.


Authorization
-------------

A client application who need to fetch CMS data for a particular user need
to ask some specific OAuth2 scopes. Exemples of CMS scopes:

- `urn:cms:personal-informations:read`: read access to the user's basic 
  personal informations
- `urn:cms:civil-status:read`: read access to the user's civil status


Fetching data
-------------

Most of the claims will be available from the [`UserInfo` OpenID Connect 
endpoint](https://openid.net/specs/openid-connect-core-1_0.html#UserInfo).

In the future, we may describe some others endpoints to suit some specific 
needs.


Claims
------

| name                  | required scope                       | Schema
| ----------------------|--------------------------------------|-------
| personalInformation   | `urn:cms:personal-information:read`  | [Personal information](../conceptual_model/personal-information.md)
| civilStatus           | `urn:cms:civil-status:read`          | [Civil status](../conceptual_model/civil-status.md)
| favorites             | `urn:cms:favorites:read`             | [Favorites](../conceptual_model/favorites.md)
| drivingLicence        | `urn:cms:driving-licence:read`       | [Driving Licence](../conceptual_model/driving-licence.md)
| ICE                   | `urn:cms:ice-contacts:read`          | [In Case Of Emergency contacts](../conceptual_model/in-case-of-emergency-contacts.md)
| CAF                   | `urn:cms:fr-caf-information:read`    | [French CAF Information](../conceptual_model/fr-caf-information.md)
| DGFIP                 | `urn:cms:fr-dgfip-information:read`  | [French DGFIP Information](../conceptual_model/fr-dgfip-information.md)
| MESRI                 | `urn:cms:fr-mesri-information:read`  | [French MESRI Information](../conceptual_model/fr-mesri-information.md)
