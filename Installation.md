# Tiny Tiny RSS Reader for Android #

  1. [Download](http://code.google.com/p/ttrss-reader/downloads/list) Tiny Tiny RSS Reader;
  1. Move the downloaded _.apk_ to your sdcard;
  1. Check your settings to allow application installation: go to _Settings_, _Applications_, and check _Unknown sources_;
  1. Open the _.apk_ file;

Alternatively, you can use the QR code below:

![http://i47.tinypic.com/jhfygl.png](http://i47.tinypic.com/jhfygl.png)

# Set up Tiny Tiny RSS #

Tiny Tiny RSS need to be set up to use its API. Please follow those few steps:

  1. Go to your Tiny Tiny RSS instance;
  1. Go to Preferences;
  1. In the Advanced section, set Enable external API to yesyes;
  1. Save the changes;

# DEPRECATED: for ttrss-reader version < 0.2.0: Set up Tiny Tiny RSS for xml-rpc #
Tiny Tiny RSS need to be set up in order to provide xml-rpc support. Please follow those few steps:

  1. Download [XML-RPC for PHP](http://phpxmlrpc.sourceforge.net/);
  1. Extract the _lib_ folder from the archive, and upload it to the _lib/xmlrpc/_ folder of your Tiny Tiny RSS instance;

Additionally, _PHP_ must be set to not display notices and warnings. To do so:

  1. Open your _php.ini_ file;
  1. Look for the line starting by _error\_reporting_;
  1. Change it by _error\_reporting = E\_ALL & ~E\_NOTICE & ~E\_WARNING_;