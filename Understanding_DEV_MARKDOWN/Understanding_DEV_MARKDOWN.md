# Markdown

# Títulos

`# Título (1)`  
`## Título (2)`  
`### Título (3)`  
`#### Título (4)`  
`##### Título (5)`  
`###### Título (6)`  

---

### Comentarios

`[comment]: <> (Comentario)`

---

### Parágrafos

[comment]: <> (Identar - Deixa o fundo cinza dando destaque ao texto)

    Identar o arquivo utilizando tab
    (Deixa o fundo mais escuro)

---

### Itálico

[comment]: <> (* * ou _ _)

*Enfatizar - Itálico*  
_Enfatizar - Itálico_

`*Enfatizar - Itálico*`  
`_Enfatizar - Itálico_`

---

### Negrito

[comment]: <> (** ** ou __ __)

**Enfaze - Negrito**  
__Enfaze - Negrito__

`**Enfaze - Negrito**`  
`__Enfaze - Negrito__`

---

### Cortado

[comment]: <> (~~ ~~)

~~Enfaze - Cortado~~  

`~~Enfaze - Cortado~~`

---

### Lista Não Ordenadas

- Tarefa - 1
- Tarefa - 2
    - MiniTarefa - 2.1
    - MiniTarefa - 2.2
- Tarefa - 3

```
- Tarefa - 1  
- Tarefa - 2 
    - MiniTarefa - 2.1  
    - MiniTarefa - 2.2  
- Tarefa - 3
```

### Lista Ordenada

1. Tarefa - 1
2. Tarefa - 2
3. Tarefa - 3

```
1. Tarefa - 1 
2. Tarefa - 2 
3. Tarefa - 3 
```

---

1. Tarefa - 1
2. Tarefa - 2
    1. Tarefa - 2.1
    2. Tarefa - 2.2
3. Tarefa - 3  

```
1. Tarefa - 1
2. Tarefa - 2
    1. Tarefa - 2.1
    2. Tarefa - 2.2
3. Tarefa - 3 
```

---

### Lista de Tarefa

- [X] Tarefa - 1
- [X] Tarefa - 2
    - [X] Tarefa - 2.1
    - [X] Tarefa - 2.2
- [ ] Tarefa - 3


```
- [X] Tarefa - 1 
- [X] Tarefa - 2 
    - [X] Tarefa - 2.1
    - [X] Tarefa - 2.2 
- [ ] Tarefa - 3
```  

### Listas mistas

+ Tarefa  
  1. Tarefa 1
  2. Tarefa 2
  3. Tarefa 3
+ Filmes
  - Filme 1
  - Filme 2
  - Filme 3
+ Provas
  - [X] Prova 1
  - [X] Prova 2
  - [X] Prova 3

```
+ Tarefa   
  1. Tarefa 1  
  2. Tarefa 2  
  3. Tarefa 3  
+ Filmes  
  - Filme 1  
  - FIlme 2  
  - Filme 3  
+ Provas  
  - [X] Prova 1 
  - [X] Prova 2  
  - [X] Prova 3  
```
---

### Links

[comment]: <> ( [Nome que aparece] "link" "Comentario" )

Meu [GitHub](https://github.com/Bruno-Petroski "GitHub")

`Meu [GitHub](https://github.com/Bruno-Petroski "GitHub")`

---

### Imagem

[comment]: <> ( [Nome que aparece] "link" "Comentario" )

![Gato Legal](assetsMD/cool_cat.png)

Via Arquivo  
`![Gato Legal](assets/cool_cat.png)`

---

![Goiaba](https://static.tuasaude.com/media/article/1b/bc/beneficios-da-goiaba_13191_l.webp)

Via Link  
`![Goiaba](https://static.tuasaude.com/media/article/1b/bc/beneficios-da-goiaba_13191_l.webp)`

### Citações

> Esse texto será envolto pelo elemento html blockquote.  

`> Esse texto será envolto pelo elemento html blockquote.`

---

### Código

`Formatação de codigo`  
\`Formatação de codigo\`  

---

### Trechos de Código

```
if var > 0 then
    display "Valor Positivo"
else
    display "Valor Negativo"
```

Basta inserir um bloco de "código" dentro de: \`\`\` (Código aqui!) \`\`\` ou \~\~\~ (Código aqui!)\~\~\~

~~~
if var > 0 then
        display "Valor Positivo"
    else
        display "Valor Negativo"
~~~

### Linhas Divisorias

[comment]: <> ("---" Faz uma linha)
[comment]: <> ("***" Faz uma linha)

---
Basta utilizar --- ou ***
***

### Tabelas

| Cod |  Nome   | Nota | Dica |
| --- | :-----: | ---: | ---- |
| 1   |  Bruno  | 10.0 | H3F8 |
| 2   |  João   | 10.0 | H4E2 |
| 3   | Roberto | 10.0 | 0F2E |
| 4   |  Diego  | 10.0 | H30F |
| 5   | Arthur  | 10.0 | D9F3 |
| 6   |  Julia  | 10.0 | 8FA2 |

---

```
Cod | Nome    | Nota | Dica  
--- |:-------:|-----:| ----  
1   | Bruno   | 10.0 | H3F8  
2   | João    | 10.0 | H4E2  
3   | Roberto | 10.0 | 0F2E  
4   | Diego   | 10.0 | H30F  
5   | Arthur  | 10.0 | D9F3  
6   | Julia   | 10.0 | 8FA2 
```

>Com a extensão "Markdown All in One" do VSCode, você pode utilizar "ALT + SHIFT + F" para formatar a tabela!!    
>
> ![Tabela Formatada](assetsMD/Tabela%20Formatada.png)

### Emojis

Inserir emojis muda de acordo com o interpretador;

#### VsCode

Apenas dar copiar e colar emojis da [Emojoipedia](https://emojipedia.org);  
😟😟😟 x

#### GitHub

Apenas usar os comandos demonstrados [nesta pagina](https://gist.github.com/rxaviers/7360908);  
`:blush:` 😊  
`:smirk:` 😏  
`:smiley:` 😃