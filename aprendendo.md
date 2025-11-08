# h1
## h2
### h3
#### h4
##### h5
###### h6

*italico*
**negrito**
~~texto riscado~~
**frase em negrito e *aqui é italico e negrito***

```markdown
    *italico*
    **negrito**
    ~~texto riscado~~
    **frase em negrito e *aqui é italico e negrito***
    
```


# boas praticas comentadas alem de usar as bolinhas de lista nao ordenada

- usar apenas um h1 por documento para o titulo
- h2 para seções principais e h3 para subseções
- manter a hierarquia lógica facilita a leitura e navegaçao
- evitar pular niveis de hierarquia, muito importante, I.As se beneficiam de arquivos .md escritos da maneira correta
- nas caixas de codigo, depois do ``` de abertura, especificar a linguagem ex 
```java
    public class Aprendendo;
```

```javascript
    const mensagem = "ola mundo"
    console.log(`Mensagem: ${mensagem}`)
```
testando o inline: `sudo apt update`
`sudo apt install git -y`
## asd

h1 com linha
=

h2 com traço
-

usando caixa que nao pega os simbolos:
```
   pra fazer essa caixinha use:
   "```"
        conteudo, ignore "" pois sem ela eu nao conseguiria demonstrar isso
   "```" 
```

### listas nao ordenadas e aninhadas
- padaria
    - bolo
    - pao
    - queijadinha
### listas ordenadas e aninhadas

1. topico 1
2. topico 2
    1. subtopico 1
    2. subtopico 2

### lista com checkbox

- [ ] tareafa nao concluida (vizualização muda de acordo com o vizualizador)
- [x] tarefa concluida (vizualização muda de acordo com o vizualizador)

### links externos em palavras 
[Youtube](https://youtube.com)

### links internos/ancoras

basicamente pra fazer funcionar voce precisa criar uma palavra chave que dessa maneira: {#secao1} porem entre parenteses
ex:

[Ir para o capitulo 2](#capitulo2)



## capitulo 2 {#capitulo2}


tambem existem links especificos como email, tel,  

[discar telefone](tel:+359540065)
[enviar email](mailto:email@exemplo.exe)

### imagens
é importante ter o texto alternativo caso a imagem quebre, padrao igual no html

![gatinho fofo](https://preview.redd.it/how-do-people-achieve-this-horrendously-low-quality-for-v0-0pj367gkplmc1.jpeg?width=640&crop=smart&auto=webp&s=cbd639118e74e7130e2a2747a8cd2f03dc64255e)

mas da pra colocar imagens com links também
[![texto alternativo](https://preview.redd.it/how-do-people-achieve-this-horrendously-low-quality-for-v0-0pj367gkplmc1.jpeg?width=640&crop=smart&auto=webp&s=cbd639118e74e7130e2a2747a8cd2f03dc64255e)](https://github.com/devguina)

clique na imagem para ver a interação ^^

## tabelas 

| Nome | idade | cidade|
|------:|:-------:|:--------|
| joao| 21     | campo belo|

podendo alinhar a direita, esquerda ou centralizado
|:texto alinhado a esquerda| -> alinha esquerda
|texto alinhado a direita:| segundo pipe -> alinha a direita
|: texto centralizado:|

mais complexo que isso, vá de html dentro do markdown, ele aceita pra muita coisa.

