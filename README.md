# vim-clojure-sql

A very simple plugin to enable SQL syntax highlighting inside string in a Clojure file. Works with the standard [vimclojure][vimclojure] plugin.

## Installation

* Be using the [vimclojure][vimclojure] plugin already!
* Install [Pathogen][pathogen]. (You're already using Pathogen, right?)
* Clone this project into `~/.vim/bundle/vim-clojure-sql`.

## Usage

Whenever you edit a clojure file, strings starting with `"SELECT`, `"CREATE` or `"DROP` will be highlighted as SQL.

Matches are case-sensitive, because that's my preference, but it's trivial to fork & change the matching rules to suit your preferences.

## Credits

Thanks to [Max Bane][maxbane] who figured out the hard stuff when when [mixing Tex with Python][tex_python_stackoverflow].

[pathogen]: https://github.com/tpope/vim-pathogen/
[vimclojure]: https://github.com/kotarak/vimclojure
[maxbane]: http://clml.uchicago.edu/~max/
[tex_python_stackoverflow]: http://stackoverflow.com/questions/519753/vimembedded-syntax-highligting
