IPA
===
This contains YAML data for representing the International Phonetic Alphabet (IPA) in HTML.

I just wanted to play around with IPA and thought I might as well share the data. You can view an HTML example of the data on [my website][] where I’ve just looped through the YAML data and put it in a table with [Liquid][] in [Jekyll][].

Empty fields are represented with the null value `~`, and the blank (dark) fields are represented with `blank`, although you can change the value by replacing Line 31

```yaml
voiceless: &blank blank
```

with

```yaml
voiceless: &blank whateveryouwant
```

Reference
---------
This is based on [the official IPA chart of 2015][reference].


[my website]: http://ndarville.com/asides/ipa
[liquid]: http://shopify.github.io/liquid/
[jekyll]: https://jekyllrb.com
[reference]: https://en.wikipedia.org/wiki/File:The_International_Phonetic_Alphabet_(revised_to_2015).pdf
