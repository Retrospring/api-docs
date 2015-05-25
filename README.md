# service-docs

Documentation for Retrospring's public API

## Localization

To translate a specific document into your language, create a folder for your language based on [ISO-639-1 language code standard](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) and place the translated document into the same structure as the original one.

So `en/sleipnir/user.md` becomes `de/sleipnir/user.md` for example.

## Contribute

If you want to contribute a translation into your language, please fork this repository and make your changes, afterwards make a pull request, so we can check on the translation and approve it's addition.

People that contribute wrong translations on purpose won't get any following PRs accepted.

## Requesting API additions, removals, or changes

File an RFC in rfc/ via a Pull Request, written in English.

## Format

See [rfc/0001-api-docs-format.md](rfc/0001-api-docs-format.md)

### RFC Format

[Rust RFC format](https://github.com/rust-lang/rfcs/blob/master/0000-template.md)
