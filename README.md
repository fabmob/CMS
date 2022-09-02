Compte Mobilité Standardisé
===========================

Version française [disponible ici](./README.fr.md).

Repository for all the documentation of the work produced by the
"Compte Mobilité Standardisé" work group.

Purpose and goals
-----------------

User accounts are a cornerstone of the services provided by mobility and MaaS operators. These accounts store regular personal Data, mobility preferences or even historic of travel. Mobility as a Service (MaaS) usually requires that multiples services, each with their own user account, cooperates and share personal Data in a secure and GDPR-compliant way.

The French MaaS ecosystem (PTA, MaaS and mobility service providers) identified several key functions to be covered by a standard:
  - CM01 - Create, modify and delete a user account with standardised Data formats and description
- CM02 - Provide SSO services to an external service provider
- CM03 - Access and manage personal Data stored by another service provider
- CM04 - Create and modify a user account hosted by an external service provider
- CM05 - Privacy policies and protection
- CM06 - Travel preferences
- CM07 - Fraud detection and mitigation
- CM08 - Create dependencies between different roles like end-user - and actual debitor
- CM09 - Collect and manage Data and documents that entitle benefits

CMS standard leverages OpenIDConnect for SSO purposes and specifies scopes to be used to implement mobility projects with good GDPR practices in place.


Governance
----------

See [CMS Work Group Governance](Gouvernance_du_GT_Compte_Mobilite_Standardise-CMS.pdf)


Resources
---------

- [Data model](conceptual_model/)
- [Authentication and API](api/)


Contact
---------

Pour toute question, contactez 
[ghislain@fabmob.io](mailto:ghislain@fabmob.io).
