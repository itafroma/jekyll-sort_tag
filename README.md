# Jekyll Sort Tag

This is a really simple plugin for Jekyll that provides a
`{% sort %}` Liquid tag to compliment Liquid's built-in
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
{% sort}
Barbara
Alice
Christine
{% endsort %}
```

## Copyright and license

This plugin is copyright © 2013–2015 [Mark Trapp][1]. All rights reserved. It is made
available via the MIT license. A copy of the license can be found in the
`LICENSE` file.

## Related links

* [Canonical project page][2]
* [RubyGems project page][3]

[1]: https://marktrapp.com "Mark Trapp’s website"
[2]: https://marktrapp.com/projects/jekyll-sort-tag "Jekyll Sort Tag project page"
[3]: https://rubygems.org/gems/jekyll-itafroma-sort_tag "RubyGems project page"
