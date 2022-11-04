# Code
Pada bagian ini, akan dibahas versi dasar pembuatan blok kode yang dirancang oleh [John Gruber](https://en.wikipedia.org/wiki/John_Gruber). Untuk versi terbaru dari pembuatan blok kode, harap kunjungi  [Fenced Code Blocks](../3-Extended%20Syntax/FencedCode.md).

Untuk membuat blok kode sederhana, pada dasarnya hanya diperlukan :
- satu atau dua tick marks```(`) ```untuk _inline code_  
- satu tab atau empat spasi untuk _code blocks_. 

## Syntax Markdown
### Inline Code

Contoh: 
```markdown
ketik `pip install numpy pandas tensorflow` untuk memasang packages tersebut pada python Anda.
```
###### Preview:
ketik `pip install numpy pandas tensorflow` untuk memasang packages tersebut pada python Anda. 

### Code Block
Contoh : 

	import os
	import pandas
	import tensorflow

	def main():
		# Put your code here

	if __name__ = __main__:
		main()


Versi extended dari codeblock  yaitu [Fenced Code Blocks](../3-Extended%20Syntax/FencedCode.md) telah memiliki fitur untuk *highlighting text* berdasarkan bahasa pemrograman agar blok kode dapat terlihat lebih menarik. 

Kembali ke [Basic Syntax](./Basic%20Syntax.md)    
Kembali ke [Home](/)
