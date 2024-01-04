# Introdução ao Markdown no GitHub

O Markdown é uma linguagem de marcação simples e poderosa usada em muitas plataformas para formatar textos. No GitHub, o Markdown permite que você estilize e organize seu conteúdo de forma clara e eficaz, exploraremos algumas das funções básicas do Markdown e como utilizá-las no GitHub.

## Titulos

Para criar um titulo você pode usar até seis níveis colocando a cerquilha na frente do texto ``#``. Quando você usa dois ou mais cabeçalhos, o GitHub gera automaticamente um sumário.

```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```

# Título 1

## Título 2

### Título 3

#### Título 4

##### Título 5

###### Título 6

## Parágrafos

Você pode criar um parágrafo deixando uma linha em branco entre as linhas de texto.

## Notas de rodapé

No texto principal onde você deseja adicionar a nota de rodapé, você insere um número entre colchetes, como ``[^1]``.

No final do seu documento ou seção, você adiciona a nota de rodapé correspondente. O número deve ser idêntico ao usado no texto principal, seguido por dois pontos e o texto da nota.

```
    Este é um exemplo de texto[^1].

    [^1]: Aqui está a nota de rodapé correspondente.
```

## Estilos de textos

Negrito:

```
    **texto** ou __texto__
```

Usando **texto** em negrito.

Itálico:

```
    *texto* ou _texto_
```

Usando *texto* em Itálico.

Tachado:

```
    ~~texto~~
```

Usando o ~~texto~~ tachado.

Subscrito:

```
    <sub>texto</sub>
```

Este é o texto `<sub>`subscrito.`</sub>`

Sobrescrito:

```
    <sup>texto</sup>
```

Este é o texto `<sup>`sobrescrito `</sup>`.

## linha de separação

A linha de separação é criada usando três ou mais caracteres iguais ``*`` ou ``_``, seguidos de um espaço. Por exemplo ``***``.

---

## Blocos de codigos

Você pode usar três crases para iniciar e encerrar um bloco de código. Especificar a linguagem após os três backticks pode ajudar na formatação, fornecendo realce de sintaxe.

````
```python
 print("Hello, world!")
```
````


```python
    print("Hello, world!")
```

ou apenas um tab.

    print("Hello, world!")

## Texto de referencia

Você pode usar o sinal de maior ``>`` no início da linha ou do trecho que deseja citar. Ao renderizar, o texto citado terá uma formatação especial, geralmente com um recuo.

> Este repositório foi construído usando o GitHub Docs.

## Links

Para criar um link embutido colocando o texto do link entre colchetes ``[ ]`` e colocando a URL entre parênteses ``( )``.

[GitHub Docs](https://docs.github.com/pt)

## Imagens

Você pode exibir uma imagem adicionando ``!`` antes do colchetes ``[ ]`` e coloque a url entre parenteses ``( )``.
    ![imagem](https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png)

## Emojis

[Repositório](https://github.com/ikatyang/emoji-cheat-sheet/tree/master) para os Emojis.

## Listas

### Não ordenadas:

Para fazer uma listas não ordenadas coloque um desses três simbolos ``*``, ``-`` ou ``+`` na frente da cada linha.

* linha 1

+ linha 2

- linha 3

### Ordenadas:

Para ordenar a lista, coloque um número na frente de cada linha seguido de um ponto.

1. linha 1
2. linha 2
3. linha 3

## Listas aninhadas:

Você pode criar uma lista aninhada recuando um ou mais itens da lista abaixo de outro item.

Lista nao ordenada:

1. Primeiro item da lista nao ordenada.

   - Primeiro item da lista aninhada nao ordenada.

   * Segundo item da lista aninhada nao ordenada.

   + Terceiro item da lista aninhada nao ordenada.

Lista ordenada:

1. Primeiro item da lista ordenada.
   1. Primeiro item da lista aninhada ordenada.
   2. Segundo item da lista aninhada ordenada.
   3. Terceiro item da lista aninhada ordenada.

## Listas de tarefas

Para criar uma lista de tarefas usando uma combinação de listas e colchetes. As listas de tarefas são úteis para gerenciar tarefas, bugs ou outros itens que precisam ser marcados como concluídos. Veja como você pode criar uma lista de tarefas:

    - [ ]

- [ ] item 1
- [ ] item 2
- [ ] item 3

Quando concluido basta colocar um ``X`` entre os colchetes.

    - [x]

- [X] item 1
- [X] item 2
- [X] item 3

## Alertas

Alertas, uma funcionalidade do Markdown inspirada na sintaxe de blockquote, permitem destacar informações vitais. No GitHub, esses alertas aparecem com designações visuais específicas, diferenciando-os conforme sua relevância. Para mais informações leia a [**documentação**](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts).

```
> [!NOTE]
> Informações úteis que os usuários devem saber, mesmo ao folhear o conteúdo.

> [!TIP]
> Conselhos úteis para fazer as coisas melhor ou com mais facilidade.

> [!IMPORTANT]
> Informações importantes que os usuários precisam saber para atingir seu objetivo.

> [!WARNING]
> Informações urgentes que necessitam de atenção imediata do usuário para evitar problemas.

> [!CAUTION]
> Aconselha sobre riscos ou resultados negativos de determinadas ações.
```

> [!NOTE]
> Informações úteis que os usuários devem saber, mesmo ao folhear o conteúdo.

> [!TIP]
> Conselhos úteis para fazer as coisas melhor ou com mais facilidade.

> [!IMPORTANT]
> Informações importantes que os usuários precisam saber para atingir seu objetivo.

> [!WARNING]
> Informações urgentes que necessitam de atenção imediata do usuário para evitar problemas.

> [!CAUTION]
> Aconselha sobre riscos ou resultados negativos de determinadas ações.

## Criar uma tabela

Para construir tabelas utilize o caractere da Barra vertical (pipe) ``|`` para separar as colunas e hífens ``-`` para definir o cabeçalho. As colunas são delimitadas pelas barras verticais, e é essencial deixar uma linha vazia acima da tabela para sua formatação adequada. Para mais informações leia a [**documentação**](https://docs.github.com/pt/get-started/writing-on-github/working-with-advanced-formatting/organizing-information-with-tables#creating-a-table)

```
| Primeiro cabeçalho  | Segundo cabeçalho  |
| ------------------- | ------------------ |
| Célula de conteúdo  | Célula de conteúdo |
| Célula de conteúdo  | Célula de conteúdo |
```

| Primeiro cabeçalho  | Segundo cabeçalho   |
| -------------------- | -------------------- |
| Célula de conteúdo | Célula de conteúdo |
| Célula de conteúdo | Célula de conteúdo |

As barras verticais em cada extremo da tabela são opcionais. As células podem ter largura variada e não precisam estar alinhadas perfeitamente com as colunas. Deve ter no mínimo três hifens em cada coluna da linha do cabeçalho.

### Formatar conteúdo dentro da tabela

Você pode alinhar o texto à esquerda, à direita ou no centro de uma coluna incluindo dois pontos ``:`` à esquerda, direita ou nos dois lados dos hifens que estão dentro da linha de cabeçalho.

```
| Alinhada à Esquerda | Center-aligned | Alinhado à direita|
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```

| Alinhada à Esquerda | Center-aligned | Alinhado à direita |
| :------------------- | :------------: | ------------------: |
| git status           |   git status   |          git status |
| git diff             |    git diff    |            git diff |

Para incluir uma barra vertical ``|`` como conteúdo dentro da célula, use ``\`` antes da barra vertical:

```
| Nome     | Caractere |
| ---      | ---       |
| Crase | `         |
| Pipe     | \|        |
```

| Nome  | Caractere |
| ----- | --------- |
| Crase | `         |
| Pipe  | \|        |

## Criando uma seção recolhida

Você pode ocultar temporariamente partes do seu Markdown usando uma seção expansível que permite ao leitor decidir se quer visualizar ou não.

* Use o elemento ``<details>`` para envolver o conteúdo que você deseja recolher.
* Use o elemento ``<summary>`` para fornecer um título ou descrição curta que os leitores verão antes de expandir o conteúdo.

```
<details>

<summary>Dicas para seções recolhidas</summary>

### É possível adicionar um cabeçalho

Você pode adicionar texto em uma seção recolhida.

Você também pode adicionar uma imagem ou um bloco de código.

</details>
```

<details>

<summary>Dicas para seções recolhidas</summary>

### É possível adicionar um cabeçalho

Você pode adicionar texto em uma seção recolhida.

Você também pode adicionar uma imagem ou um bloco de código.

```ruby
   puts "Hello World"
```

</details>
