# Aprendendo Markdown


## Formatação de texto e ALERTS
Você pode indicar ênfase com negrito, itálico, strikethrough, subscrito ou texto sobrescrito em campos de comentário e .mdficheiros.


1. Ousado	** ** ou __ __	atalho= Command+B (Mac) ou Ctrl+B (Windows/Linux)Tradução -> **This is bold text**

2. Itálico	* *ou _ _     	atalho= Command+I (Mac) ou Ctrl+I (Windows/Linux)Tradução	_This text is italicized_

3. Strikethrough ~~ ~~ou ~ ~	Nenhuma	~~This was mistaken text~~

4. Ousado e aninhado itálico	** ** e _ _	nenhum atalho **This text is _extremely_ important**

5. Tudo arrojado e itálico	*** ***	***All this text is important***

6. Subscrito	<sub> </sub>	Nenhuma	atalho This is a <sub>subscript</sub> text

7. Superescrição	<sup> </sup>	nenhum atalho 	This is a <sup>superscript</sup> text

8. Sublinhar	<ins> </ins> 	nenhum atalho This is an <ins>underlined</ins> text
## Figuras
Você pode exibir uma imagem adicionando ! e envolvendo o texto alternativo em [ ]. O texto alternativo é um texto curto que equivale às informações da imagem. Em seguida, coloque o link da imagem entre parênteses ().

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](/../../../../github/docs/blob/main/assets/images/electrocat.png)

## Trecho de código
O Trecho de código no arquivo .md é feito abrindo o código com três crases e fechando-o com três crases (```). Sempre uma linha única para abrir e uma linha única para fechar

```
Código aqui
```

E o código pode ser formatado dependendo da linguagem, desde linguagens de programação diversas como Java, Python e R, até bash ou mermaid, passando por CSS e HTML. Como? Apenas escrever na primeira linha, ao lado das três crases a linguagem usada

![imagem-exemplo](~/Imagens/IMAGEM.png)

```python
#Exemplo de python
ola = 'Olá mundo'
print(ola)

```

Ele é útil para facilitar a leitura de código, para que fique formatado, com cores e pautado de acordo com cada linguagem, além de facilitar pois os blocos de código possuem a opção de colar o bloco inteiro quando formatados adequadamente