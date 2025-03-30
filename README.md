# KeyConf Website

The KeyConf24 conference happens on 19 Sep 2024 in Vienna.
This is the website hosted on https://keyconf.dev

## Building the site locally

Run when using Docker compose:

```
docker-compose up
```

Run plain docker with:

```
podman run -it --rm -p 4000:4000 -p 35729:35729 -v .:/srv/jekyll -v jekyll_data:/usr/gem jekyll/jekyll:4 bundle exec jekyll serve --livereload
```

Then open your browser on http://0.0.0.0:4000/

## Theme Details

**Demo:** https://themes.3rdwavemedia.com/bootstrap-templates/startup/devconf-free-bootstrap-5-conference-template-for-tech-conferences-and-events/

DevConf is a free Bootstrap 5 conference template perfect for building marketing sites for tech conferences and events. 

### Author & License

This Bootstrap template is made by UX/UI designer [Xiaoying Riley](https://twitter.com/3rdwave_themes) for developers and is 100% FREE as long as you **keep the footer attribution link**. You do not have the rights to resell, sublicense or redistribute (even for free) the template on its own or as a separate attachment from any of your work.

If you'd like to **use the template without the footer attribution link**, you can [buy the **commercial license** via the theme website](https://themes.3rdwavemedia.com/bootstrap-templates/free/devconf-free-bootstrap-5-conference-template-for-tech-conferences-and-events/)

### Credits
- [Bootstrap](https://getbootstrap.com/)
- [FontAwesome](https://fontawesome.com/)
- [Google fonts](https://fonts.google.com/)
- Image Credit - [EuropeanaTech Conference](https://www.flickr.com/photos/europeanaimages2/albums/72157669104892268) and [TechCrunch](https://www.flickr.com/photos/techcrunch/) [Creative Commons 2.0 license](https://creativecommons.org/licenses/by/2.0/deed.en) (All images are shown for demonstration purposes only)
