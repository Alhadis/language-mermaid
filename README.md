Mermaid language support for Atom
=================================

Syntax highlighting for [Mermaid][1] diagrams.

Currently in-development; intended to address [`github/linguist#5578`][2].


Supported graph types
---------------------
* [x] Flowchart
* [x] Sequence diagram
* [x] Class diagram
* [x] State diagram
* [x] Entity relationship diagram
* [x] User journey
* [x] Gantt
* [x] Pie chart
* [x] Requirement diagram
* [x] Gitgraph
* [ ] C4C diagram


Installing in Atom
------------------
You'll need [Git][3], because this won't ever appear in Atom's package registry:

~~~shell
# On Unix-like platforms
cd ~/.atom/packages && git clone https://github.com/Alhadis/language-mermaid.git
~~~

~~~batchfile
:: For Windows users
cd %HOMEPATH%\.atom\packages
git clone "https://github.com/Alhadis/language-mermaid.git"
~~~


<!-- Referenced Links --------------------------------------------------------->
[1]: https://github.com/mermaid-js/mermaid
[2]: https://github.com/github/linguist/issues/5578
[3]: https://git-scm.com/downloads
