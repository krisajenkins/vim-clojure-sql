# vim-clojure-sql

A very simple plugin to enable SQL syntax highlighting inside strings in a
Clojure file. If you can handle the visual trip of two syntax highlighters
co-existing, this plugin will provide.

Works with the standard [vimclojure][vimclojure] plugin.

## Installation

* Be using the [vimclojure][vimclojure] plugin already!
* Install [Pathogen][pathogen]. (You're already using Pathogen, right?)
* Clone this project into `~/.vim/bundle/vim-clojure-sql`.

## Usage

Whenever you edit a Clojure file, strings starting with `"SELECT`, `"INSERT`,
`"UPDATE`, `"DELETE`, `"CREATE` or `"DROP` will be highlighted as SQL.

Matches are case-sensitive, because that's my preference, but it's trivial to
fork & change the matching rules to suit your coding style.

## Notes

This repo serves as a reasonable recipe for embedded Vim syntax highlighting in
general. The next time I'm there, I'll probably write a plugin for SQL inside
Hibernate XML files. Highlighting code inside docstrings is another obvious use
of this approach.

## Credits

Thanks to [Max Bane][maxbane] who figured out the hard stuff when when [mixing Tex with Python][tex_python_stackoverflow].

## See Also

[vim-java-sql][vim-java-sql] - the same plugin for SQL inside Java files.

[pathogen]: https://github.com/tpope/vim-pathogen/
[vimclojure]: https://github.com/kotarak/vimclojure
[maxbane]: http://clml.uchicago.edu/~max/
[tex_python_stackoverflow]: http://stackoverflow.com/questions/5176972/trouble-using-vims-syn-include-and-syn-region-to-embed-syntax-highlighting
[vim-java-sql]: https://github.com/krisajenkins/vim-java-sql
