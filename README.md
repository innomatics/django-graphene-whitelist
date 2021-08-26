# graphene-django-whitelist

Secure a django-graphene application by whitelisting only your allowed client queries.

Superusers are permitted to run any query.

To add to the list of allowed queries, superuser can run the query wih the `Query-Whitelist=append` header.

TODO:
- Implement hashing and database lookup
- Implement caching
- Implement counts and last used async writes 
