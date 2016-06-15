Sendy Prestashop newsletter module
=============

This module is compatible with Prestashop 1.6+ (tested on 1.6.5).

This module is based on Prestashop's block newsletter module, modified to include the possibility of automatically subscribing users to a given Sendy newsletter. It retains all the functionality of the default newsletter module.

It uses a combination of AJAX and PHP curl to smoothly add a subscriber to the list and provide feedback.

Features
---------

* AJAX powered sign up form
* Sendy installation does not have to be on the same server

Set up requirements
-------------------

* You will need to have PHP curl extension enabled
* If your server uses a firewall, you will need to allow the connection to the server that  your Sendy is installed on


How to install
--------------

* Download this repository
* Repack the `sendynewsletter` folder
* Upload it in your Prestashop backoffice in the Modules section
* Alternatively upload the `sendynewsletter` folder directly to your `modules` folder