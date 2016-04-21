# Fred's List Final

## Description
This is the last time we will be playing with Fred's list this semester. 
Using django-all-auth implement at least 2 different social authentication options in addition to the username/password option. 

## Normal Mode

### Auth
* Implement at least 2 different social login options.  One of them must be one not done in class.
* Ensure that at least 1 view is secured to only authenticated users
* Ensure that a user can use the secured view after only logging in via a social application
* Ensure that a token is generated and can be used to authenticate to the api side

### Admin
* Add filters for posts for date and city
* Add a custom action for the ads that will allow multiple to be archived
* Add a search function on the admin that will search through all ads

### Models
* Replace any view ordering with a model level ordering
* Add `default_related_name` to models instead of multiple custom names on the fields
* Add `unique_together` on the city model to make city and state unique

### URLs
* Add namespacing to your urls for each app

## Hard Mode
* Using the rest of the built in urls style the templates and make your main system use them to manage email addresses, social accounts and password change forms. 

## Resources
* [Github Repo](https://github.com/tiy-lv-python-2016-02/freds-list-final)
* [Documentation](http://django-allauth.readthedocs.org/en/latest/overview.html)
* [AllAuth Github](https://github.com/pennersr/django-allauth)
* [Admin Docs](https://docs.djangoproject.com/en/1.9/ref/contrib/admin/)
* [Meta Models](https://docs.djangoproject.com/en/1.9/ref/models/options/)
