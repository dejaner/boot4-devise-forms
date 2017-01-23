##Bootstrap 4.0 - Default Devise Views (using haml)

The default views created by Devise converted to HAML and integrated with Bootstrap 4 styling.

```
rails generate devise:views
```

In support of blog post: [Examples: Bootstrap 4 Devise Forms (using haml)](http://joanswork.com/bootstrap-4-devise-forms/)

####Features:

* Converted to HAML.

* Forms placed on a Bootstrap card.

* Form structure updated with Bootstrap classes.

* Forms use the Bootstrap grid with right justifed labels.

* Classes added to organize further customization.

* (Most) English language text move to a locale file.


####Files to pay attention to:
* app/views/devise
* assets/stylesheets/custom_devise.scss
* config/locales/devise_forms.em.yml


###Version

Using Devise 4.2.0 and Bootstrap 4.0.0.alpha3

###Author

Joan Hughes @ [http://72breezy.io](http://72breezy.io)

<http://www.linkedin.com/in/jehughes>

###License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE.md)

