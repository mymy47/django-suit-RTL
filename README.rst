===========
Django Suit v2 RTL
===========

**Modern theme for Django admin interface**.

Django Suit is alternative theme/skin/extension for `Django <http://www.djangoproject.com>`_ administration interface.

* Project home: http://djangosuit.com/
* Live demo v2.0 alpha 1 LTR: http://v2.djangosuit.com/admin/


Install
=======

* 1- Install Django Suit v2-dev RTL using pip or easy_install:

::

    pip install -e git+https://github.com/mymy47/django-suit-RTL#egg=django_suit

* 2- Create SuitConfig class and add it to the INSTALLED_APPS before django.contrib.admin app:

::

    # my_project_app/apps.py
    from suit.apps import DjangoSuitConfig
    
    class SuitConfig(DjangoSuitConfig):
        layout = 'horizontal'

::

    INSTALLED_APPS = (
        ...
        'my_project_app.apps.SuitConfig',
        'django.contrib.admin',
    )


License
=======

* Django Suit is licensed under `Creative Commons Attribution-NonCommercial 3.0 <http://creativecommons.org/licenses/by-nc/3.0/>`_ license.
* Licence and pricing: http://djangosuit.com/pricing/


Docs & Support
==============

* Documentation v2 LTR: http://django-suit.readthedocs.org/en/v2/
* Support: http://djangosuit.com/support/
* Follow `on Twitter <http://twitter.com/DjangoSuit>`_ to get latest news


Preview
=======


.. image:: http://s9.picofile.com/file/8338619776/django_suit_RTL_preview.png
