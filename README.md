Devise Views with Formtastic and HAML
=====================================

Tested with Devise 2.0.4, Formtastic 2.1.1 and HAML 3.1.4

Installation
------------

Copy all views into your Project and add the locales to your localization file.

To enable HTML5 Form Validations for your Project you need the following setting in your `/config/initializers/formtastic.rb`:

    Formtastic::FormBuilder.perform_browser_validations = true


