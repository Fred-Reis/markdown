# **Título**

Citação usa-se o sinal de maior no inicio

> **Lorem** _ipsum_ justo lectus neque ultricies curae sociosqu etiam semper, at augue habitant proin habitasse tempor amet ante. nunc egestas felis quisque augue habitant lacinia aliquam, venenatis eget posuere vivamus platea potenti accumsan ut, ad donec fusce urna in nunc. 
>ad est a tempus quisque consequat dolor sagittis ante dapibus ornare, augue tempus sollicitudin pellentesque etiam luctus lacus nec et, blandit litora faucibus vulputate torquent egestas orci leo neque. sociosqu risus hendrerit sodales lorem commodo aliquam felis, vestibulum aliquam euismod vulputate justo semper per, nullam libero non eros himenaeos magna. 

--- 


# Lista_1

item1
item2
item3

# Lista_2

item1 item2 item3

# Lista_3

* item1
* item2
* item3

# Lista_4

* item1
  * subitem1
  * subitem2
    * sub_subitem1
* item2
  * subitem1
  * subitem2
* item3

# Lista_5

* item1

* item2

* item3

# Lista_6

1. item1
2. item2
3. item3

# Lista_7

1. item 
    1. subitem
1. item2
1. item3

# Lista_8

5. item1
    1. subitem
    1. subitem
    1. subitem
1. item2
1. item3

# Lista_9

5\. item1  
4\. item2  (dois espacos)  
1\. item3


# Link

colocar o texto entre  chaves [ ] e a url  entre parenteses( )      
> `[texto] (URL, 'texto quando passar o mouse')`

[Texto a ser exibido](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet, 'GitHub')


# Imagem

inserir imagem é igual ao link mas com ! no comeco   
> `![Nome da imagem](URL_LINK)`


![git](https://www.pinclipart.com/picdir/middle/207-2071102_es7-snippets-react-native-icon-png-clipart.png)

# Imagem_2

Agora com imagem local

![git](assets/git.png)

# Imagem com link

imagem com  link externo cria imagem dentro de um [ ]
 e o link entre ( )  
 >   `[![Nome da imagem](endereço_IMAGEM)](URL_LINK)`



[![GIT](assets/git.png)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet, 'GITHUB')

# Imagem com link_2

imagem com link externo mais link da mesma forma que anterior, mas com 2 links 

> `[![Nome da imagem](URL_LINK_IMAGEM)](URL_LINK)`



[![GIT](https://www.pinclipart.com/picdir/middle/207-2071102_es7-snippets-react-native-icon-png-clipart.png)](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet, 'GITHUB')

    
# Tabelas

os pipes "|" separam as clonunas e 3 tracos "-" criam linhas  horizontais. As colunas se auto alinham

| Cabecalho | Para | Tabelas |  
| --- | --- | --- |
| nome | valor1 | valor 2 |
| e ai | por | diante |

# Alinhamento das Tabelas

 levando em consideração que a linha abaixo do cabecalho é o guia` | --- | --- | --- |` os `":"` dois pontos são a flag
se eu quiser alinhado à esquerda eu ponho os doi pontos no inicio dos traços `| :--- |`, se quiser ao centro ponho os pontos nas duas extremidades `| :---: |`, e à esquerda, os dois pontos tbm à esquerda `| ---: |`

| Cabecalho | Para | Tabelas |  
| :--- | :---: | ---: |
| nome | valor1 | valor 2 |
| e ai | por | diante |

 
 # Códigos em linha

para inserir em linha apenas destacando algumas palavras: 
coloca - se crase ` por volta da palavra 

Informe os parâmetros `userName` e `password` e chame a função `login()`.

# Códigos em linha 2

quando a crase fizer parte do código, como com templates string do JS colocasse duas crases `` por volta de tudo, e tudo sera código e a crase interna será ignorada

`` const response = `my name is ${name}`;``

# Códigos por bloco

usando o espaço 4 vezes

    // coment
    
    const handleSubmit = async (form) => {
      console.log(form)
    }

# Códigos por bloco 2

usando 3 crases por volta de todo o bloco

```
// coment

const handleSubmit = async (form) => {
  console.log(form)
}
```

# Syntax Highlighting

usando 3 crases e colocando javascript, js ou jsx no inicio

```javascript
// coment

const handleSubmit = async (form) => {
  console.log(form)
}
```

```js
// coment

const handleSubmit = async (form) => {
  console.log(form)
}
```

```jsx
// coment

const handleSubmit = async (form) => {
  console.log(form)
}
```

# Badges

#### Link para criar seus badges e links para icones:

### [**Crie seu Badges aqui**](https://shields.io/category/social)

### [**Icones em svg**](https://shields.io/category/social)

---

![Imagem](https://img.shields.io/badge/ReactNative-v_0.60-blue)

[![Imagem](https://img.shields.io/badge/Node-v_12.13.1-339933)](https://nodejs.org/en/)

![Imagem](https://img.shields.io/badge/Yarn-v_1.22.4-2C8EBB?logo=Yarn)


![Imagem](https://img.shields.io/github/followers/Fred-Reis?style=social)

![Imagem](https://img.shields.io/github/followers/Fred-Reis?label=Followers)

[![GitHub](https://img.shields.io/badge/GitHub-000?logo=github)](https://github.com/Fred-Reis)

[![GitHub](https://img.shields.io/badge/GitHub-Meu_Perfil-000?logo=github)](https://github.com/Fred-Reis)

[![GitHub](https://img.shields.io/badge/Meu_Perfil-GitHub-000?logo=github)](https://github.com/Fred-Reis)

![Imagem](https://img.shields.io/badge/ReactNative-v_0.60-61DAFB?logo=react)

![Imagem](https://img.shields.io/badge/Yarn-v_1.22.4-2C8EBB?logo=Yarn)

[![Imagem](https://img.shields.io/badge/Node-v_12.13.1-339933?logo=node.js)](https://nodejs.org/en/)

[![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/frederico-reis-dev/)

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin)](https://www.linkedin.com/in/frederico-reis-dev/)

[![Linkedin](https://img.shields.io/badge/LinkedIn-Frederico_Reis-0077B5?logo=linkedin)](https://www.linkedin.com/in/frederico-reis-dev/, "Frederico Reis")

[![Linkedin](https://img.shields.io/badge/Frederico_Reis-LinkedIn-0077B5?logo=linkedin)](https://www.linkedin.com/in/frederico-reis-dev/, "Frederico Reis")

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=social&logo=linkedin)](https://www.linkedin.com/in/frederico-reis-dev/)

![Javascript](https://img.shields.io/badge/_-Javascript-F7DF1E?logo=Javascript)

![Markdown](https://img.shields.io/badge/>-Markdown-000000?logo=Markdown)

[![Markdown](https://img.shields.io/badge/Curso-Aprenda_Markdown-EC5252?logo=udemy)](https://www.udemy.com/share/101vTQ/)









