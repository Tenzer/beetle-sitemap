# Beetle-Sitemap

Creates a sitemap.xml file for the HTML files inside a [Beetle](https://github.com/cknv/beetle) output directory.

In order to use this plugin, you first have to add `beetle_sitemap` to the list of plugins in your Beetle `config.yaml` file and add a `site` setting for the plugin. `site` should be set to the full root of where the site will be accessible at, including the protocol, ie: `site: http://tenzer.dk`.

When that's done you can run `beetle sitemap` to generate a sitemap.xml file of the HTML files in the output directory, so you should have ran `beetle render` first. You can also run them directly after each other if you run `beetle render sitemap`.
