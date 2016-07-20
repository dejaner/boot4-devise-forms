##Bootstrap 4.0 - Default Devise Views (using haml)

The default views created by Devise converted to HAML and integrated with Bootstrap 4 styling.

```
rails generate devise:views
```

In support of blog post:

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

July 20, 2016: Using Devise 4.2.0 and Bootstrap 4.0.0.alpha3

###Author

Joan Hughes

<http://www.linkedin.com/in/jehughes>

###License
The MIT License (MIT)

Joan Hughes @ [http://joanswork.com](http://joanswork.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
