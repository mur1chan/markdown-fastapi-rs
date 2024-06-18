# markdown-to-html
 
## Information
This is only a subset of this repository: https://github.com/mur1chan/frontend

i needed a way to quickly display markdown input in html. the html should be rendered serversided. so instead of using a library based only on python, i came up with the idea of writing my own, but with rust. so i used pyo3 and maturin to create a python library from the rust code. 

just out of curiosity i tested how significant the differences really were. this was the result: 
markdown2 average time: 0.20264388871192932 seconds
markdown-to-html-rs average time: 0.002178431272506714 seconds

the test was simply how fast it can output the same content with 1000 iterations in html, so nothing big in itself. nevertheless, the results were surprising how big the differences are between my code and the biggest python library. 

Translated with DeepL.com (free version)
