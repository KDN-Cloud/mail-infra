# mail-infra

>Self-hosting mail was a great run — over 10 years across multiple VPS systems — but the maintenance overhead eventually outweighed the satisfaction. Our family's domains now live on Fastmail, and I haven't looked back.

Mail cluster diagram created with draw.io. Replicated Mail stores and replicated LDAP directory as a source for any of its lookups. 

[MAIL INFRA DIAGRAM](https://github.com/KDN-Cloud/mail-infra/blob/main/Mail%20Diagram/pdf/Mail%20Diagram.pdf)

## Mail Services

* Dovecot + Xapian FTS
* Postfix
* Rspamd + DKIM + ARC
* OpenDMARC
* OpenLDAP
* Cyrus SASL
* Roundcube Webmail

Directory source [LDAP Mail Schema](https://github.com/variablenix/ldap-mail-schema/blob/master/postfix-book.schema)
