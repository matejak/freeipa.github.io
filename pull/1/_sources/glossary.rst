Glossary
========

.. glossary::
   :sorted:

   CA
      A certificate authority: a service that issues and signs certificates.
      See :doc:`/page/PKI`.

   HBAC
      Host-based access control: rules that determine which users may access
      which hosts through particular services.

   keytab
      A file containing Kerberos principals and their secret keys. Services
      can use a keytab to authenticate without an interactive password prompt.

   KRA
      A key recovery authority: a service used to archive and recover secrets.

   principal
      A named identity in Kerberos, such as a user or a service. A principal
      includes a name and a :term:`realm`.

   realm
      A Kerberos administrative domain. FreeIPA realm names conventionally use
      the upper-case form of the primary DNS domain name.

   trust
      A relationship between identity domains that allows identities from one
      domain to authenticate for access to resources in another. Authorization
      remains subject to access policies. See :doc:`/page/Trusts`.
