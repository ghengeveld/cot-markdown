Markdown parser for Cotonti
===========================

Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you 
to write using an easy-to-read, easy-to-write plain text format, then convert 
it to structurally valid XHTML (or HTML).

This plugin uses the PHP Markdown implementation by Michel Fortin:
http://michelf.com/projects/php-markdown/

Installation
------------

Simply upload the plugin folder to your /plugins directory and enable the 
plugin in your Administration panel. You can now choose Markdown from the 
parser list when creating or editing a page. Alternatively you can set 
Markdown as the default parser for pages in the Pages module configuration or 
as the default site-wide parser in the Main Settings configuration screen.

Configuration
-------------

The plugin has one configurable setting. By choosing between HTML or XHTML you 
determine how non-closing HTML tags will be closed (with /> or simply >).