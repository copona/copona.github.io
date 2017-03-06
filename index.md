## Welcome to Copona

Copona is an ecommerce engine, based on Opencart.

We have incorporated numerous improvements, including:


### Core Changes ###

* Simpler installation process which automatically creates configuration files where needed.

* Search engine friendly URL's are enabled automatically on supported configurations.

* More secure password hashing functions

* More modern codebase, targetting PHP5.6 as the mimimum supported version. 
      
 * Rewritten to avoid use of functions that have been deprecated in PHP7.1 (openssl replaces mcrypt throughout)
            
* New metadata table, to enable more efficient storage and retrieval of data.
 
* Simplified code base - removing features from the core install which would be better suited to being add-ons, such as the Openbay system


### Admin Changes ###

* New feature: Product Groups

* Ability to save changes to a product and continue editing it, rather than being returned to main menu.

* Admin menu - saved in session, not flickering anymore

* Language management - languages loaded by code, from Directory name from DB

* Smarter product duplication: When a product is copied, the word ' (copy)' is added to to the name of new product

* Autocomplete now has "keepDropdown" property - if it's set to true - dropdown will not disapear oin choose.

* Alert message in admin, if form has been changed and not saved.


### Works in progress ####

* From admin interface, it would be useful to be able to view products that are in a category, as well as products that use a specific option.

* Moving away from the VQMOD architecture for extending core functionality.


### Need more explanation ####

* Default Tax Class

* Tax with vat input for products

* Category Filtering in admin with autocomplete
