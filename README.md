# oauth2_django

**Description**

Secure Django application with OAuth2 authentication and authorization. 
Manages OAuth2 applications and tokens. 
Supports various grant types. 
Leverages `django-oauth-toolkit` for efficient implementation.

**Installation**

1. Install the required package:

```bash
pip install django-oauth-toolkit
```
2. Add `'oauth2_provider'` to your `INSTALLED_APPS` setting in your Django project's settings.py file.
   
   ```bash
   INSTALLED_APPS = [
    # ... other apps
    'oauth2_provider',
   ]
   ```
3. Include OAuth2 URL patterns in your project's `urls.py` file.

   ```bash
   from oauth2_provider import urls as oauth2_urls

    urlpatterns = [
        # ... other URL patterns
        path('o/', include(oauth2_urls)),
    ]
   ```
**Usage**

Refer to the django-oauth-toolkit documentation for detailed instructions: https://django-oauth-toolkit.readthedocs.io/

**Contributing**

We welcome contributions! Please submit a pull request.









