# Fenced Code Blocks
Fenced Code blocks merupakan pengembangan dari blok kode standar markdown yang memiliki keunggulan dari segi estetika dan fleksibilitas penggunaan.

Fenced Code Blocks ini memiliki fitur  Syntax Highlighting untuk bahasa pemrograman tertentu seperti yang terlampir pada tabel di bagian akhir halaman ini.

Fenced code blocks diawali dan diakhiri dengan tiga buah tickmarks (\`\`\` )  atau tiga buah tide (\~\~\~) tanda pembuka dapat diiringi dengan nama jenis bahasa yang digunakan pada kode yang ditulis.


## Markdown Syntax
~~~
```jenis bahasa

your code here

```
~~~

#### Contoh: 
 ~~~
 ```json
{
"firstName": "John",
"lastName": "Smith",
"age": 25
}
```
~~~
Di render menjadi: 
 ```json
{
"firstName": "John",
"lastName": "Smith",
"age": 25
}
```


Daftar Bahasa Pemrograman yang disupport oleh ***fenced code blocks markdown***:

| Language | Available language mode(s) |
| --- | ---| 
|ASP.NET|`asp`, `aspx`|
|C|`c`|
|C++|`c++`, `cpp`, `cplusplus`|
|C#|`cs`, `csharp`|
|Clojure|`clj`, `cljc`, `cljx`, `clojure`|
|CSS|`css`, `less`, `sass`, `scss`,   `styl`, `stylus`|
|cURL|`curl`|
|D|`d`|
|Dart|`dart`|
|Diff|`diff`|
|Docker|`dockerfile`|
|Erlang|`erl`, `erlang`|
|Go|`go`|
|GraphQL|`gql`, `graphql`|
|Groovy|`gradle`, `groovy`|
|Handlebars|`handlebars`, `hbs`|
|HTML/XML|`html`, `xhtml`, `xml`|
|HTTP|`http`|
|Java|`java`|
|JavaScript|`coffeescript`, `ecmascript`, `javascript`,   `js`, `node`|
|JSX|`jsx`|
|JSON|`json`|
|Julia|`jl`, `julia`|
|Kotlin|`kotlin`, `kt`|
|Liquid|`liquid`|
|Lua|`lua`|
|Markdown|`markdown`|
|Objective-C|`objc`, `objectivec`|
|Objective-C++|`objc++`, `objcpp`, `objectivecpp`,   `objectivecplusplus`|
|OCaml|`ocaml`, `ml`|
|Perl|`perl`, `pl`|
|PHP|`php`|
|PowerShell|`powershell`, `ps1`|
|Python|`py`, `python`|
|R|`r`|
|React|`jsx`|
|Ruby|`jruby`, `macruby`, `rake`, `rb`, `rbx`, `ruby`|
|Rust|`rs`, `rust`|
|Scala|`scala`|
|Shell|`bash`, `sh`, `shell`, `zsh`|
|Solidity|`sol`, `solidity`|
|SQL|`cql`, `mssql`, `mysql`, `plsql`,    `postgres`,   `postgresql`, `pgsql`, `sql`, `sqlite`|
|Swift|`swift`|
|TypeScript|`ts`, `typescript`|
|YAML|`yaml`, `yml`|

Untuk daftar lengkap bahasa pemrograman yang bisa di-*highlight* oleh [[Obsidian]], bisa diakses [di sini](https://prismjs.com/#supported-languages)

Kembali ke [Extended Syntax](./ExtendedSyntax.md)      
Kembali ke [Home](/)