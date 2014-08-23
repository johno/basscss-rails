# BASSCSS for Rails

Include BASSCSS, the next-level CSS toolkit, in your Rails apps through the assets pipeline.

Repackaged from <https://github.com/jxnblk/basscss> by Brent Jackson.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'basscss'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install basscss

##### Using Sass

You will then need to require the stylesheet in your application.scss:

```scss
@import "basscss/basscss";
```

There's also a lite version of BASSCSS, which can be included instead:

```scss
@import "basscss/basscss-lite";
```

##### Using CSS

Or, in your application.css:

```css
*= require basscss/basscss;
```

Or, for BASSCSS lite:

```css
*= require basscss/basscss-lite;
```

## Usage

Further documentation can be found on the BASSCSS website: <http://www.basscss.com/docs/>

## Contributing

1. Fork it ( https://github.com/johnotander/basscss/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request

## Acknowledgements

  * The CSS toolkit is written by Brent Jackson: <https://github.com/jxnblk/basscss>

More documentation available at <http://www.basscss.com/docs/>.
