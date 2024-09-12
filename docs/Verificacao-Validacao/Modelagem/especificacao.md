## Introdução

Esse documento tem como objetivo realizar a verificação do artefato [Especificação Suplementar](../../Modelagem/especificacao.md) a partir do método de inspeção

## Checklist de Verificação da Especificação Suplementar

| ID  | Descrição | Referência | Status |
|-----|-----------|------------|--------|
| 1   | O documento cobre todos os requisitos não funcionais do sistema (desempenho, segurança, usabilidade, etc.)?       | [Software Requirements](#software-requirements) | Sim |
| 2   | Estão descritas todas as restrições e condições operacionais para o sistema?                                      | [Software Requirements](#software-requirements) | Sim |
| 3   | As descrições dos requisitos suplementares são claras e precisas, sem ambiguidades?                               | [Software Requirements](#software-requirements) | Sim |
| 4   | Todos os requisitos estão documentados em um formato padronizado e compreensível?                                 | [Software Requirements](#software-requirements) | Sim |
| 5   | Existe consistência entre os requisitos suplementares e os requisitos funcionais especificados em outros documentos? | [Software Requirements](#software-requirements) | Sim |
| 6   | As dependências entre requisitos funcionais e não funcionais estão claramente indicadas?                           | [Software Requirements](#software-requirements) | Não |
| 7   | Os requisitos suplementares refletem as necessidades do projeto no contexto específico do sistema?                | [IEEE Std 830-1998](#ieee-std)                   | Sim |
| 8   | Foram consideradas as condições reais de operação, como restrições de hardware, conectividade e ambiente de produção? | [IEEE Std 830-1998](#ieee-std)                   | Incompleto |
| 9   | Os requisitos suplementares são verificáveis e mensuráveis (ex.: requisitos de desempenho com métricas definidas, como tempo de resposta ou taxa de erros)? | [IEEE Std 830-1998](#ieee-std)                   | Sim |
| 10  | Os requisitos suplementares indicam claramente como eles impactam o design, desenvolvimento e manutenção do sistema? | [IEEE Std 830-1998](#ieee-std)                   | Não |
| 11  | A especificação suplementar possui controle de versão para garantir o rastreamento de alterações?                  | [Software Requirements](#software-requirements) | Incompleto |
| 12  | Há um processo definido para revisão e atualização dos requisitos suplementares à medida que o projeto evolui?    | [Software Requirements](#software-requirements) | Incompleto |
| 13  | Existe uma tabela de conteúdo ou índice que facilite a navegação pelo documento?                                   | [Software Requirements](#software-requirements) | Sim |

## Problemas Encontrados

- Durante a inspeção foi constatado a ausência de qualquer documentação das dependências entre os requisitos funcionais e não funcionais.
- Nem todas as condições reais de operação foram abordadas
- Embora exista a divisão dos requisitos em tópicos, os impactos não foram claramente documentados.
- Não existe um controle de versão para cada um dos requisitos, apenas um histórico de versão geral
- Não existe uma documentação clara do processo para revisão e atualização dos requisitos, porém o documento está organizado em tópicos e tabelas, elementos que contribuem para revisão e atualização dos requisitos na especificação suplementar.

## Referências

<a id="software-requirements">1.</a> Wiegers, K. E., & Beatty, J. (2013). Software Requirements (3rd Edition). Microsoft Press.

<a id="ieee-std">2.</a> [IEEE Std 830-1998, IEEE Recommended Practice for Software Requirements Specifications.](https://ieeexplore.ieee.org/document/720574)

## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 04/09/2024 | 1.0 | Criação do documento e checklists | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |
| 05/09/2024 | 1.1 | Adição das referências | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |
| 06/09/2024 | 1.2 | Adição dos status e dos problemas encontrados | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |

</center>
