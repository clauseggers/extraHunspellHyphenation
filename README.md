# Extra hyphenation files for the Suite of MacOS Affinity applications*
\* and other MacOS applications that make use of `Hunspell` dictionaries.

*Hunspell is based in principle on the algorithmic approach [Franklin M. Liang developed in his 1983 PhD thesis.](https://tug.org/docs/liang/)
Raph Levien wrote a shorter explanation when Hunspell was [committed to Mozilla in 1998](https://github.com/hunspell/hyphen/blob/master/README.hyphen).*

This repository contains a compilation of [Hunspell](https://hunspell.github.io) hyphenation files that do not come included with installs of the [Affinity](https://affinity.serif.com/) apps.

*No spelling dictionaries are included in this repo, this is just hyphenation. Installing the spelling dictionaries can have performance implications, hence it is better to install them in this context.*

### Sources
The source of many of these hyphenations files are
* https://wiki.documentfoundation.org/Language/Support
* https://github.com/LibreOffice/dictionaries
* https://extensions.libreoffice.org/?q=hyphenation&action_doExtensionSearch=Search
* https://extensions.openoffice.org/en/search?query=hyphenation
* https://addons.mozilla.org/en-US/firefox/language-tools/
* https://aur.archlinux.org/packages?SeB=n&K=hunspell-

Rename the downloaded `*.oxt` to `*.zip` and unzip it.
The files shall be converted to `UTF-8` before inclusion in this repository.

### Installing
To install these hyphenation files, copy them to `~/Library/Spelling/` and restart your Affinity apps, or install them to `/Library/Spelling/` and restart your Macintosh.

### Contributing
Pull requests are welcomed. Please have them formatted in UTF-8, and in the correctly named [ISO 639](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) language and [ISO 3166](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes) folder.

* The folder must be named `[ISO 639-1]_[ISO ISO 3166-1 alpha-2]`. If no ISO 639-1 has been assigned use the ISO 639-2/T code.
* The filename must be `hyph_[ISO 639-1]_[ISO ISO 3166-1 alpha-2].UTF-8.dic`.
* Please include a copy of the license in the folder.
* Please include a `README.txt` which includes the source and date of the hyphenation dictionary. Use one of the existing `README.txt` as a template for your own.

### License
Please check which license the particular hyphenation file is published by, and include the relevant license file enclosed in the language directory.