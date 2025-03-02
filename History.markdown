## 1.4.0 / 2015-12-25

## Minor Enhancements

  * Bump Sass to v3.4 and above. (#40)
  * Strip byte order mark from generated compressed Sass/SCSS (#39)
  * Strip BOM by default, but don't add in the `@charset` by default (#42)

## Development Fixes

  * Add Jekyll 2 & 3 to test matrix (#41)

## 1.3.0 / 2014-12-07

### Minor Enhancements

  * Include line number in syntax error message (#26)
  * Raise a `Jekyll::Converters::Scss::SyntaxError` instead of just a `StandardError` (#29)

### Development Fixes

  * Fix typo in SCSS converter spec filename (#27)
  * Add tests for custom syntax error handling (#29)

## 1.2.1 / 2014-08-30

  * Only include something in the sass load path if it exists (#23)

## 1.2.0 / 2014-07-31

### Minor Enhancements

  * Allow user to specify style in safe mode. (#16)

### Development Fixes

  * Only include the `lib/` files in the gem. (#17)

## 1.1.0 / 2014-07-29

### Minor Enhancements

  * Implement custom load paths (#14)
  * Lock down sass configuration when in safe mode. (#15)

## 1.0.0 / 2014-05-06

  * Birthday!
  * Don't use core extensions (#2)
  * Allow users to set style of outputted CSS (#4)
  * Determine input syntax based on file extension (#9)
