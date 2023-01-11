# Field extra widgets

Provides two helper widgets for the Field API:

Hidden: this widget doesn't show anything on the edit form, and as a consequence
prevents the user from modifying the content of the widget. This is useful in
some situations where using hook_field_access() is not suitable
(for example when you want to have different edit forms for different users).

Read-only: this widget shows the content of the field on the edit form,
but doesn't allow the user to edit it. The content is rendered using one of the
formatter of the field.

## Installation

- Install this module using the official
  [Backdrop CMS instructions](https://backdropcms.org/user-guide/modules).

## Issues

Bugs and feature requests should be reported in the
[Issue Queue](https://github.com/backdrop-contrib/field_extrawidgets/issues).

## Current Maintainer

[Justin Keiser](https://github.com/keiserjb)

## Credits

- Ported to Backdrop CMS by [Justin Keiser](https://github.com/keiserjb).
- Many thanks to the creators of the
[Drupal project](https://www.drupal.org/project/field_extrawidgets).
- Created for Drupal by [Damien Tournoud](https://www.drupal.org/u/damien-tournoud).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
