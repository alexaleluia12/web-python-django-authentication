# Authorization Django

## references
- [Will Vincent](https://wsvincent.com/django-user-authentication-tutorial-login-and-logout/)
- [Django Doc](https://docs.djangoproject.com/en/2.1/ref/contrib/auth/)


```txt

basically add this to project/settins.py
  path('account/', include('django.contrib.auth.urls')),


have this functionality
  accounts/login/ [name='login']
  accounts/logout/ [name='logout']
  accounts/password_change/ [name='password_change']
  accounts/password_change/done/ [name='password_change_done']
  accounts/password_reset/ [name='password_reset']
  accounts/password_reset/done/ [name='password_reset_done']
  accounts/reset/<uidb64>/<token>/ [name='password_reset_confirm']
  accounts/reset/done/ [name='password_reset_complete']

```