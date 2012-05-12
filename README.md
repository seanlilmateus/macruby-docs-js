[macruby-docs.user.js](https://github.com/joakimk/macruby-docs-js/raw/master/macruby-docs.user.js) - A userscript that adds MacRuby/RubyMotion syntax to Apple's Objective-C/Cocoa docs.

After installing and visiting [apple docs](https://developer.apple.com/library/mac/#documentation/Cocoa/Reference/Foundation/Classes/NSString_Class/Reference/NSString.html), you should see "MacRuby" sections within the documenation:

![Example](https://github.com/joakimk/macruby-docs-js/raw/master/example.png)

Development instructions
---

This project uses ruby to get a web server setup for development. You also need to make sure you have node and coffee-script installed.

    git clone git@github.com:joakimk/macruby-docs-js.git
    cd macruby-docs-js
    # [sudo] gem install bundler
    bundle
    rake

Open run_specs.html to run the specs.

Install the extension using tools/macruby-docs-dev.user.js to use the local development version.
