Collection of various telephone related codes.

- `pretty_tap.lua` - human readable mappings of codes used e.g. in TAP
  files
- `tel-code-gen.py` - generates tel-codes.lua
- `tel-codes.lua` - more human readable mappings of country codes, currency codes, carrier codes, etc. - relatively large (10 MiB or so)

The point of all the lua code is for being able to use this in a
program that has a lua interpreter included for customization.

Usage example: [libxfsx and bed][1]


2017, Georg Sauthoff <mail@gms.tf>


## License

The generator script `tel-code-gen.py` is licensed under the
[GPLv3+][gpl].

The lua code is just a collection of dictionaries containing
trivial data, thus I consider this public domain.

[1]: https://github.com/gsauthof/libxfsx
[gpl]: https://www.gnu.org/licenses/gpl-3.0.en.html
