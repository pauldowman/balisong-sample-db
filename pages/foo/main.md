This is a post about *foo*.

text can be *italic* or

* bullet point 1
* bullet point 2

Some HTML rendered:

{{lol.html | html}}

And the same HTML as code source:

{{lol.html | code(html)}}

Here is some sample Ruby code:

{{sample.rb | code(ruby)}}

Here is some Ruby code with only specified lines being rendered:

{{sample.rb | code(ruby, 2-4)}}

Here is some plain text:

{{something.txt | text}}

And a picture of a cat:

{{lolcat.jpg | image}}

And a file to download:
{{something.zip | download}}

