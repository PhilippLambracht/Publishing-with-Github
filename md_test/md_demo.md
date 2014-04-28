Eine Demonstration mit Markdown
=================================
Erst mal ein paar basics
-------------------------

* Ungeordnete Liste
* Weiterer Punk
  * Unterpunkt

1. Geornete List
2. zweites Element

> Dies ist ein Zitat


Speziell bei Github
--------------------

kein_kursiv

Autolinking http://philipplambracht.github.io/Publishing-with-Github/


Darstellen von Codeblocks
```
function test() {
  console.log("notice the blank line before this function?");
}
```

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
