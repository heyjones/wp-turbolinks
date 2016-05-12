WP Turbolinks
=========================

An implementation of the updated Rails 5.0 feature, Turbolinks, for WordPress.

https://github.com/turbolinks/turbolinks

Installation
============

Download a zip of the repository and put in a *wp-turbolinks* directory inside
*wp-content/plugins*.

Go to the plugins page and activate it.

Warnings
========

For Turbolinks to work you have to write your JavaScript in a certain way, in particular, document ready events have to be idempotent.  There are several articles popping up describing the problem and potential solutions to them.  This article from Yehuda Katz sums it up pretty well: https://plus.google.com/106300407679257154689/posts/A65agXRynUn.

Please make sure you read about the pros and cons of Turbolinks before installing it on your site.  You may have to make significant changes to your JavaScript for it to work well.

About
=====

Version: 0.1

Updated by Chris Jones - <http://heyjones.com>

Created by Adam Pope of Storm Consultancy - <http://www.stormconsultancy.co.uk>

Storm Consultancy are a web design and development agency based in Bath, UK.

If you are looking for a [Bath WordPress Developer](http://www.stormconsultancy.co.uk/services/bath-wordpress-developers), then [get in touch](http://www.stormconsultancy.co.uk/contact)!

Credits
=======

This is based off of the work by @dhh on the new Turbolinks gem for Rails.

https://github.com/turbolinks/turbolinks

We have also included the jQuery.Turblinks plugin by kossnocorp

https://github.com/kossnocorp/jquery.turbolinks
