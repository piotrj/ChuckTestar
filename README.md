# Chuck testr RSpec formatter

The gem is a game changer... Nope! It's just **Chuck TestR - Chuck's Testa RSpec formatter**

## Requirements

It requires only `rspec` gem, obviously. It only works with OS X for now.

## Installation

If you are using bundler, add this to your `Gemfile`:

    gem 'ChuckTestar'

Or install the gem manually with `gem install ChuckTestar`.

## Usage

To start using the formatter you can either specify it in the rspec's command line options or add it to `.rspec` file:

- With `.rspec` file

Add this line to your `.rspec` file:

    --format ChuckTestar

- With command line options

    rspec spec/* --format ChuckTestar

### TODO

- Add license
- Add growl notifications
- Specs
- Support for Linux
