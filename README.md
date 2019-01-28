# ltec5200.ray.pillers.us

This is the source for [my project](http://ltec5200.ray.pillers.us), hosted by [GitHub Pages](https://pages.github.com/).

## Theme

[Landing Page Jekyll theme](https://github.com/swcool/landing-page-theme/tree/4a8191d7e9e9b8fbdc7007f37d4b4e02f9351f29)

## Notes

### Setup Dev Env

**Setup:** [How to Set Up a Jekyll Development Site on Ubuntu 16.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jekyll-development-site-on-ubuntu-16-04)

- Setup in WLS Ubuntu.
- Didn't open firewall.
<!-- - [Nokogiri requires a few more `apt` packages.](http://www.nokogiri.org/tutorials/installing_nokogiri.html#install_with_included_libraries__recommended_)
  - At the time of this writing: `sudo apt-get install build-essential patch ruby-dev zlib1g-dev liblzma-dev` -->

Then just need to `cd` into this git repo and run the dev server:

```bash
cd ltec5200.ray.pillers.us
jekyll serve
```

For simplicity later, I made a bash script in WLS's home: `~/jekyll_serve_ltec5200.ray.pillers.us.sh`.
For more Jekyll details, read [documentation](http://jekyllrb.com/).

## License
The contents of this repository are licensed under the [Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

## Version
1.0.1
