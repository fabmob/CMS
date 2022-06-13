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
| personalInformations  | `urn:cms:personal-informations:read` | [Personal informations](../conceptual_model/personal-informations.md)
| civilStatus           | `urn:cms:civil-status:read`          | [Civil status](../conceptual_model/civil-status.md)
