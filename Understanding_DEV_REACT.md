# GIT
## Configurações Previas

- `git config --global user.email "e-mail"`;
- `git config --global user.user "Nome"`;
  - Definie e-mail e nome de usuario;

## Comandos Git

- `git init`;
  - Inicializar um repositório;

---

- `git status`;
  - Verifica o status dos arquivos (Untracked/Unstaged e Tracked/Staged);

---

- `git clone`;
  - Clona um repositório remoto;

---

- `git add .` ;
- `git add "arquivo"`;
  - Reconhece um arquivo (Stage);

---

- `git commit -m "Comentario"`;
  - Consolida as alteraços adicionadas no stage;
  
---

- `git remote add origin "url do repositório"`;
- `git remote -v`;
  - Linka o repositório local ao remoto;

---

- `git branch -M main`;
  - Renomeia a branch a qual os arquivos serão sincronizados.;

---

- `git push -u origin main` (ou branch desejada);
- `git push`;
  - Envia as alterações do repositório local ao remoto (Sincronizar);

---

- `git pull`;
  - Contrario do `git push`, envia as alterações do repositorio remoto ao local.



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

---

`- Tarefa - 1`  
`- Tarefa - 2`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`- MiniTarefa - 2.1`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`- MiniTarefa - 2.2`  
`- Tarefa - 3`  

### Lista Ordenada

1. Tarefa - 1
2. Tarefa - 2
3. Tarefa - 3

--- 

`1. Tarefa - 1`  
`2. Tarefa - 2`  
`3. Tarefa - 3`  

--- 

1. Tarefa - 1
2. Tarefa - 2
    1. Tarefa - 2.1
    2. Tarefa - 2.2
3. Tarefa - 3

---

`1. Tarefa - 1`  
`1. Tarefa - 2`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`1. Tarefa - 2.1`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`1. Tarefa - 2.2`  
`1. Tarefa - 3`  

---

### Lista de Tarefa
- [X] Tarefa - 1
- [X] Tarefa - 2
    - [X] Tarefa - 2.1
    - [X] Tarefa - 2.2
- [ ] Tarefa - 3

---

`- [X] Tarefa - 1`  
`- [X] Tarefa - 2`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`- [X] Tarefa - 2.1`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`- [X] Tarefa - 2.2`  
`- [ ] Tarefa - 3`  

### Listas mistas

+ Tarefa  
  1. Tarefa 1
  2. Tarefa 2
  3. Tarefa 3
+ Filmes
  1. Filme 1
  2. FIlme 2
  3. Filme 3
+ Provas
  - [X] Prova 1
  - [X] Prova 2
  - [X] Prova 3

---

`+ Tarefa  `  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`1. Tarefa 1`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`2. Tarefa 2`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`3. Tarefa 3`  
`+ Filmes`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`1. Filme 1`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`2. FIlme 2`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`3. Filme 3`  
`+ Provas`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`- [X] Prova 1`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`- [X] Prova 2`  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`- [X] Prova 3`  

---

### Links

[comment]: <> ( [Nome que aparece] "link" "Comentario" )

Meu [GitHub](https://github.com/Bruno-Petroski "GitHub")

`Meu [GitHub](https://github.com/Bruno-Petroski "GitHub")`

---

### Imagem

[comment]: <> ( [Nome que aparece] "link" "Comentario" )

![Gato Legal](../Understanding-React-Bruno-Petroski-Enghi/assets/cool_cat.jpg)

Via Arquivo  
`![Gato Legal](../Understanding-React-Bruno-Petroski-Enghi/assets/cool_cat.jpg)`

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

`Cod | Nome    | Nota | Dica`  
`--- |:-------:|-----:| ----`  
`1   | Bruno   | 10.0 | H3F8`  
`2   | João    | 10.0 | H4E2`  
`3   | Roberto | 10.0 | 0F2E`  
`4   | Diego   | 10.0 | H30F`  
`5   | Arthur  | 10.0 | D9F3`  
`6   | Julia   | 10.0 | 8FA2` 

>Com a extensão "Markdown All in One" do VSCode, você pode utilizar "ALT + SHIFT + F" para formatar a tabela!!    
>
> ![Tabela Formatada](assets/Tabela%20Formatada.png)

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




  