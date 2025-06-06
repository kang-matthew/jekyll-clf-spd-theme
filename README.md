# jekyll-clf-spd-theme

Playing around with Jekyll CLF Theme. Added the following components:
- Hero - image banner for pages
- Card - clickable image rectangles with text
- People Card - to display staff info in a listing of people
- People Focus Card - to display staff info w/ greater info (biography)

And made some modifications, including but not limited to:
- Added and set default font to Whitney
- Added sub-menu hover dropdown to navigation. Needs improvement for mobile.
- Hardcoded footer w/ SPD, added land acknowledgemnet
- Hardcoded og-image to SPD
- Changed the unit background-color

---
# jekyll-clf-theme

Welcome to your new UBC CS Faculty Jekyll theme! In this directory, you'll find the files you need to be able to package up your theme into a gem. Put your layouts in `_layouts`, your includes in `_includes`, your sass files in `_sass` and any other assets in `assets`.

To experiment with this code, add some sample content and run `bundle exec jekyll serve` – this directory is setup just like a Jekyll site!


## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "jekyll-clf-theme", git: "git@github.com:ubc-cpsc/jekyll-clf-theme"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: jekyll-clf-theme
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install jekyll-clf-theme

## Usage

TODO: Write usage instructions here. Describe your available layouts, includes, sass and/or assets.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ubc-cpsc/jekyll-clf-theme.git. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## UBC HTML CLF

- Based on https://clf.ubc.ca
- With HTML templates available at
https://github.com/UBCCM/clf-html-template

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `jekyll-clf-theme.gemspec` accordingly.

## Release

The version number in the `jekyll-clf-theme.gemspec` just needs to be updated when you want to release. Commit and push that and away you go.__


## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

