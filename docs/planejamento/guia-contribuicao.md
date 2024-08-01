# Guia de contribuição

Este documento serve como guia para ajudar e padronizar a contribuição em nosso projeto, contendo os padrões de branch, commit e pull-request

## Como contribuir?

Antes de começar, clone o repositório para o seu computador local 

É importante que toda nova adição deve ser criada como uma **issue** antes de ser implementada. **Verifique se uma issue retratando a mesma modificação ainda não existe!**

Para começar a contribuir no projeto, crie uma **nova branch** para a **issue** em questão e após isso abra um **pull-request** com suas modificações. Qualquer contribuição somente irá para a branch principal (**main**) após a aprovação do **pull-request**

<center>

![Diagrama de Pull Request](../assets/images/diagrama-pr.png)

**Figura 01** - Diagrama de Pull-Request
</center>

A seguir segue os templates e padrões de contribuição do projeto:

## Padrão de criação de issue

### Título da issue (problema)

```
### Descrição

(breve descrição do problema)
Realizar de a criação do artefato... e subir para documentação...

### Tarefas

(separe as tarefas a serem realizadas)
- Criar artefato
- ...
- Subir página para documentação
- ...
```

## Padrão de criação de branch

`<numero-da-issue>-<nome-branch>`

Para criar uma nova branch, utilize o número da issue correspondente e depois o nome da branch.

Exemplo:

- **issue: #74 - Documento de modelagem**
- branch: `74-documento-modelagem`

Utilizar o número da issue facilita o processo de localizar branches específicas.

## Padrão de commit

`(<nome-branch>) <descricao>`

Para criar um commit novo, utilize o nome da branch que a commit será feita e depois a descrição da commit, lembre-se de adicionar todos os co-authored necessários

Exemplo:

- branch: 74-documento-modelagem
- commit: `(documento-modelagem) adicionando página de modelagem`

## Padrão de pull-request

### Título (baseado na issue ou branch)

```
### Descrição

Esse pull request introduz... (descreva a adição ou modificação realizada na branch)

### Motivação e Contexto

Essa modificação foi realizada para... dentro do contexto que... (descreva o motivo da modificação e o contexto para sua realização)
```
## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 30/07/2024 | 1.0 | Criação do documento | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 31/07/2024 | 1.1 | Adicionando diagrama de pull-request e padrão de criação issue | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 31/07/2024 | 1.2 | Centralizando imagem | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |

</center>