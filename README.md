# Jekyll Sort Tag

This is a really simple plugin for Jekyll that provides a
`{% raw %}{% sort %}{% endraw %}` Liquid tag to compliment Liquid's built-in
`sort` filter.

## Installation

This plugin is provided as a gem:

```sh
gem install jekyll-itafroma-sort_tag
```

Once the gem is installed, include it in your Jekyll site's configuration:

```yaml
gems: ['jekyll/itafroma/sort_tag']
```

## Usage

Wrap the output you’d like to sort with the tag:

```liquid
{% raw %}
{% sort}
Barbara
Alice
Christine
{% endsort %}
{% endraw %}
```

## Copyright and license

This plugin is copyright © 2013 [Mark Trapp][1]. All rights reserved. It is made
available via the MIT license. A copy of the license can be found in the
`LICENSE` file.

## Related links

* [Canonical project page][6]
* [RubyGems project page][7]

[1]: http://marktrapp.com "Mark Trapp’s website"
[2]: http://marktrapp.com/projects/jekyll-sort-tag "Jekyll Sort Tag project page"
[3]: https://rubygems.org/gems/jekyll-itafroma-sort_tag "RubyGems project page"
