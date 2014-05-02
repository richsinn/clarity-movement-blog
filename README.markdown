**NOTE:** This is a fork of the awesome [wordpress-on-heroku](https://github.com/mchung/wordpress-on-heroku) project template, which helps you upload a [Wordpress application](http://wordpress.org) to [Herkou](http://heroku.com). This is *only a project template* - the template is not enough to a upload a Wordpress app to Heroku. The Wordpress app is uploaded to Heroku via the [heroku-buildpack-wordpress](https://github.com/mchung/heroku-buildpack-wordpress) project. You can follow the instructions on the [original project's github page](http://mchung.github.com/heroku-buildpack-wordpress/).

The way to use this project template is to fork it, modify it to your specifications, and then upload it to your Heroku instance (which is how this fork is using it).

The rest of the README below is exactly as how it appears in the
original [wordpress-on-heroku](https://github.com/mchung/wordpress-on-heroku) project template's github page.

# Wordpress on Heroku

This is where changes to your Wordpress site are made.  Changes committed to this directory will overwrite all the vendor defaults.

Generally, you'll be interested in adding plugins, adding themes, and modifying wordpress.conf.erb.
```
└── config                # Config files
    ├── public            # Public directory
    │   └── wp-content    # Themes & plugins
    │       ├── plugins
    │       └── themes
    └── vendor            # Config files for vendored apps
        ├── nginx
        │   └── conf      # nginx.conf + wordpress.conf.erb
        └── php           # php.ini
            └── etc       # php-fpm.conf
```

For everything you ever wanted to know about running Wordpress on Heroku, check out my [heroku-buildpack-wordpress](http://github.com/mchung/heroku-buildpack-wordpress).