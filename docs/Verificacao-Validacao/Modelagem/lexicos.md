## Introdução

Esse documento tem como objetivo realizar a verificação do artefato [Léxicos](../../Modelagem/lexico.md) a partir do método de inspeção

## Checklist de Verificação do Léxico

| ID | Descrição | Referência | Status |
|-----|----------|------------|--------|
| 1   | Todos os termos relevantes do domínio foram identificados e documentados?                              | [Software Engineering](#software-engineering) | Sim |
| 2   | Há uma categorização clara dos termos (ex.: objeto, estado, verbo)?                                     | [Software Engineering](#software-engineering) | Sim |
| 3   | Cada termo está claramente definido, sem ambiguidades?                                                 | [Software Engineering](#software-engineering) | Sim |
| 4   | As definições estão alinhadas com o escopo do projeto e compreensíveis para todas as partes interessadas?| [Software Engineering](#software-engineering) | Sim |
| 5   | Existe consistência nas definições ao longo de todo o léxico?                                           | [Software Engineering](#software-engineering) | Sim |
| 6   | Os termos são usados de maneira uniforme nos demais documentos de requisitos?                          | [Software Engineering](#software-engineering) | Sim |
| 7   | As definições refletem corretamente o uso dos termos no contexto específico do sistema em desenvolvimento?| [A strategy for conceptual model acquisition](#requirements-engineering) | Sim |
| 8   | Existem relações entre os termos (sinônimos, antônimos, hierarquia de conceitos) devidamente especificadas?| [A strategy for conceptual model acquisition](#requirements-engineering) | Incompleto |
| 9   | Os termos estão relacionados a outros conceitos importantes para o projeto?                            | [A strategy for conceptual model acquisition](#requirements-engineering) | Sim |
| 10  | O léxico cobre todas as áreas e funcionalidades do sistema ?                         | [A strategy for conceptual model acquisition](#requirements-engineering) | Sim |
| 11  | Os termos contribuem para uma melhor compreensão do impacto do sistema no negócio?                      | [A strategy for conceptual model acquisition](#requirements-engineering) | Sim |
| 12  | O léxico possui controle de versão para garantir que as alterações sejam rastreadas ao longo do tempo?  | [Software Engineering](#software-engineering) | Incompleto |
| 13  | Existe um processo definido para atualizar o léxico conforme novos termos surgem?                      | [Software Engineering](#software-engineering) | Sim |
| 14  | O documento do léxico é de fácil leitura e está acessível para todos os membros da equipe?              | [Software Engineering](#software-engineering) | Sim |
| 15  | As definições estão livres de jargões técnicos que possam causar confusão?                              | [Software Engineering](#software-engineering) | Sim |
| 16  | O impacto de cada termo no sistema foi considerado no desenvolvimento de funcionalidades?               | [A strategy for conceptual model acquisition](#requirements-engineering) | Sim |

## Problemas encontrados

- Durante a inspeção foi constatado que as relações entre os termos se restringe apenas a sinônimos
- Não existe um controle de versão para cada um dos termos, apenas um histórico de versão geral

## Referências

<a id="software-engineering">1.</a> Sommerville, I. (2011). Software Engineering (9th Edition). Addison-Wesley.

<a id="requirements-engineering">2.</a> [Leite, J. C. S. do Prado, & Franco, A. P. M. (1993). A strategy for conceptual model acquisition. Proceedings of the IEEE International Symposium on Requirements Engineering (RE'93)](https://ieeexplore.ieee.org/document/324853).

## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 04/09/2024 | 1.0 | Criação do documento e checklists | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |
| 05/09/2024 | 1.1 | Adição das referências | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |
| 06/09/2024 | 1.2 | Adição dos status e dos problemas encontrados | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |

</center>
