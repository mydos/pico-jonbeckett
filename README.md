# pico-jonbeckett

A simple theme for the [Pico](http://picocms.org/) CMS using [BootStrap](http://getbootstrap.com).

### Demonstration

You can see the theme in action at **[jonbeckett.com](http://jonbeckett.com)**.

### Installation Instructions

* Copy the contents of the theme folder into the "themes" folder of your Pico installation.
* Edit the /config/config.php file of your Pico install as follows: <code>$config['theme'] = 'pico-jonbeckett';</code>

### Notes

* If you want to use Disqus, add <code>$config["disqus"]="username";</code> to the config file, and use the "post" template for blog posts.
* If you want to make a blog, create a folder within content called "blog", and put your posts in it. Then make a content file in the root of content with the template "blog", and it will list your posts.
* The theme is a very basic implementation of Bootstrap, which should serve as a good starting point for further development.
* At the time of release to GitHub, the theme had been tested on Pico v.1.0, and Bootstrap v.3.3.6. jQuery 1.12.3 is bundled.
