cordova-plugin-inappbrowser
-----------------------------
To install this plugin, follow the [Command-line Interface Guide](http://cordova.apache.org/docs/en/edge/guide_cli_index.md.html#The%20Command-line%20Interface).

If you are not using the Cordova Command-line Interface, follow [Using Plugman to Manage Plugins](http://cordova.apache.org/docs/en/edge/guide_plugin_ref_plugman.md.html).

###Note:
For some reason CoreGraphics framework isn't being auto added to project (even thought its specified in the plugin.xml so it has to be manually added when using this plugin otherwise you'll get a build error.

###Install Plugin
cordova plugins add https://github.com/cemerson/cordova-inappbrowser-ce.git

###Remove Plugin
cordova plugins rm org.apache.cordova.core.inappbrowser-ce

###Usage Examples:
####window.open() no options:
    window.open('http://www.ign.com','_blank');

####window.open() with fancy options!:
    window.open('http://www.ign.com','_blank','vw=568,vh=1004,vx=200,vy=0,buttoncolorbg=#BA8C3C');

####window.open() with PDFs
    (nothing special to note here - same options from above apply)