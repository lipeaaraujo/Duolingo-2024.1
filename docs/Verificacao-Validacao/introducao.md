É amplamente reconhecido que a engenharia de requisitos é composta por três etapas principais: elicitação, modelagem e análise. A análise, sendo um dos pilares dessa disciplina, tem como objetivo revisar todos os artefatos produzidos até então, realizando uma verificação e validação detalhadas. Esse processo é essencial para garantir a consistência, completude e correção dos artefatos, proporcionando mais segurança e confiança no que está sendo desenvolvido. Dessa forma, assegura-se que o produto final atenda efetivamente às necessidades e expectativas do cliente.

Nesse contexto, a análise é conduzida por meio de duas atividades principais: verificação e validação, como dito anteriormente. A verificação concentra-se em garantir que os artefatos estão corretos e consistentes, de acordo com suas especificações. Para isso, todos os artefatos passam por revisões rigorosas, visando assegurar que eles fazem sentido dentro das regras e normas estabelecidas. No entanto, é importante destacar que a verificação não examina a relação entre os artefatos e o universo de informação do qual eles foram extraídos, esse aspecto é abordado pela validação.

Consequetemente, a etapa de verificação pode se apresentar de diversas maneiras e as principais delas são: a inspeção, o uso de estratégias formais e a reutilização de domínios. A inspeção envolve uma revisão sistemática e detalhada dos artefatos produzidos até o momento.Logo, o objetivo é tentar identificar defeitos, como erros de omissão, ambiguidade, inconsistência e redundâncias, que podem comprometer a confiabilidade dos artefatos.

## Metodologia

Portanto, para a realização da verificação dos artefatos produzidos até o momento o nosso grupo escolheu como método de verificação a inspeção criado pelo Fagan. Entretanto houve uma adaptação desse método a fim de melhor se adequar as necessidades da matéria e o nível de experiência dos integrantes.

Assim, houve inicialmente um **planejamento** para avaliar todos os artefatos que seriam inspecionados, após isso fizemos uma **preparação** construindo check-lists para cada artefato a ser análisado e por fim realizamos o a **inspeção** preenchendo os check-lists produzidos.

Para a construção dos check-lists usamos a seguinte estrutura:

| ID | Descrição | Referência | Status |
|----|-----------|------------|--------|
| ID do critério | Descrição do critério | Referência da qual foi retirado | Sim/Não/Incompleto/Não se aplica |

Sendo que os critérios de status de cada elemento é definido como: 

- **Sim**: Critério totalmente atendido
- **Não**: Critério não atendido
- **Incompleto**: O critério foi parcialmente atendido, explicando em qual parte o artefato falhou
- **Não se aplica**: O critério não pode ser verificado devido ao contexto do projeto

E por fim, ao final de cada documento criamos o tópico **Problemas encontrados** com o intuito de aprensentar uma breve conclusão da inspeção focado nos problemas.
