
## version 1.0

- now use django authentification contrib and django-registration application to manage legacy authentification.
- default django openid store is now in `django_authopenid.openid_store`
- you could now set a custom openid store by settings settings.OPENID_STORE
- association of different openids is now possible when the user is logged.

