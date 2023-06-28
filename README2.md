### Why fork ?

Make a better html/pdf edition. Better reading experience for latest version. Thanks for author

### Pandoc cmd

html: pandoc -s --toc -N --highlight-style=pygments -o understandinges6.html --metadata title="understandinges6"  00-Introduction.md 01-Block-Bindings.md  02-Strings-and-Regular-Expressions.md  03-Functions.md  04-Objects.md  05-Destructuring.md  06-Symbols.md  07-Sets-And-Maps.md  08-Iterators-And-Generators.md  09-Classes.md  10-Arrays.md  11-Promises.md  12-Proxies-and-Reflection.md  13-Modules.md  A-Other-Changes.md  B-ECMAScript-7.md  

pdf: pandoc --toc -N --highlight-style=pygments --pdf-engine=xelatex -o understandinges6.pdf  00-Introduction.md 01-Block-Bindings.md  02-Strings-and-Regular-Expressions.md  03-Functions.md  04-Objects.md  05-Destructuring.md  06-Symbols.md  07-Sets-And-Maps.md  08-Iterators-And-Generators.md  09-Classes.md  10-Arrays.md  11-Promises.md  12-Proxies-and-Reflection.md  13-Modules.md  A-Other-Changes.md  B-ECMAScript-7.md  
