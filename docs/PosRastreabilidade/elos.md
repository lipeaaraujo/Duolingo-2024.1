## Introdução

Este documento apresenta os Elos de rastreabilidade dos requisitos elicitados. Tais Elos são oriundos do meta-modelo de toranzo que apresenta 4 níveis principais de classificação de informação: Ambiental, Organizacional, Gerencial e Desenvolvimento. A partir disso, cada nível de informação pode possuir 6 tipos de elos que são de: Satisfação, Recurso, Responsabilidade, Representação, Alocados e Agregação.

A rastreabilidade depende desses Elos para estabelecer e manter conexões claras entre os requisitos e os artefatos, garantindo que o desenvolvimento seja coerente e alinhado com os objetivos do sistema.

## Metodologia

Em relação a metodologia adotada, nos concentramos em aplicar a rastreabilidade através do Elos acima mencionados. Porém, tendo em vista o contexto da disciplina, esse processo foi restrito apenas ao nível do Desenvolvimento. Além disso, usamos como fonte os requisitos registrados na [baseline](../baseline) e na [matriz de rastreabilidade forward-from](../forward) para viabilizar a execuçaõ desses Elos.

Ademais, utilizamos tabelas com a seguinte estrutura para documentar os Elos:

|ID| Elementos Rastreáveis| Elo | Justificativa |
|--|----------------------|-----|---------------|
|Identificador daquele Elo| Quais são os artefatos e requisitos do Elo |O Elo propiamente dito | Por que desse Elo existir|

<center>

**Tabela 1** - Molde parra as demais tabelas do documento

</center>

## Elos do nível de Desenvolvimento

A seguir, serão registrados os elos de rastreabilidade de desenvolvimento.

### Elos de satisfação

|ID| Elementos Rastreáveis| Elo | Justificativa |
|--|----------------------|-----|---------------|
| ELO1S | - [RF01]() O aplicativo deve ter uma variedade de cursos e idiomas <br> - [US21]() Escolher um curso | O requisito [RF01]() satisfaz parcialmente os critérios de aceitação da [US21]()  | Ao fornecer ao usuário uma variedade de cursos, consequentemente cumprimos a primeira metade dos critérios de aceitação da [US21]() |
| ELO2S | - [RF01]() O aplicativo deve ter uma variedade de cursos e idiomas <br> - [US43]() Acessibilidade por idioma | A História de Usuário [US43]() satisfaz parcialmente o requisito [RF01]() | Ao permitir ao usuário que ele escolha o idioma padrão do aplicativo dentre uma certa variedade cumprimos uma parte do requsito [RF01]() |
| ELO3S| - [RF02]() O usuário deve poder refazer as lições <br> - [Meta do i*- Revisar Conteúdo]()  | O requisito [RF02]() satisfaz parcialmente a [Meta do i*- Revisar Conteúdo]() | Ao refazer alguma lição automaticamente o usuário está revisando algum conteúdo | 
| ELO4S | - [RF03]() O aplicativo deve ter um sistema de revisão de conteúdo <br> - [US14]() Revisar conteúdo | Os criteiros de aceitação da [US14]() satisfazem o requisito [RF03]() | Ao cumprir todos os criteérios de aceitação da [US14]() é garantido que um sistema de revisão de conteúdo foi implementado  |
| ELO5S  | - [RF04]() O aplicativo deve permitir o cadastro e gerenciamento de contas <br> - [EO03]() Gerência de conta | O épico [EO03]() satisfaz o requisito [RF04]() | Ao implementar todas as histórias de usuário presentes no épico [EO03]() é permitido ao usuário criar a sua conta, excluir, visualizar os dados da conta, excluir a conta e demais elementos da gerência, assim o requisito [RF04]() é aplicado |
| ELO6S  | - [RF05]() O perfil do usuário deve exibir informações importantes <br> - [US02]() Visualizar informações no perfil | A [US02]()  satisfaz o requisito [RF05]() | Ao cumprir todas os critérios de aceitação da [US02]() é mostrado as principais informações do perfil o que garante a implementação do requisito [RF05]() |
| ELO7S | - [RF06]() O aplicativo deve exibir as coleções de erros, palavras aprendidas e histórias estudadas <br> - [US19]() Visualizar as coleções de erros, palavras e histórias | A história de usuário [US19]() satisfaz o requisito [RF06]() | Ao cumprir todos os critérios de aceitação da História de Usuário [US19]() é diretamente implementado o requisito [RF06]() |
| ELO8S  | - [RF10]() As lições devem abranger questões de fala, de escrita, de leitura e de escuta <br> - [US13]() Praticar uma lição | A História de Usuário [US13]() satisfaz o requisito [RF10]() | Ao cumprir o seguinte critério de aceitação dessa US: As questões devem abranger exercícios de fala, leitura, escrita e escuta é diretemente implementado o requisito [RF10]()  |
| ELO9S  | - [RF11]() O aplicativo deve dar feedback durante a realização das questões <br> - [US16]() Receber feedback das questões | A História de Usuário [US16]() satisfaz o requisito [RF11]() | Ao cumprir os critérios de aceitação da [US16]() um feedack é garantido ao usuário ao realizar uma questão, cumprindo assim o requisito [RF11]() |
| ELO10S  | - [RF12]() O usuário deve ser capaz de monitorar seu progresso no curso <br> - [EO07]() Progresso | O Épico [EO07]() satisfaz o requisito [RF12]()  |   |
| ELO11S  | - [RF13]() O usuário deve receber notificações <br> - [US11]() Receebr lembretes diários, atualizações da liga, novidades e atualizações sobre amigos | A história de Usuário [US11]() satisfaz o requisito [RF13]()  |   |
| ELO12S  | - [RF14]() O aplicativo deve oferecer um sistema de missões ao usuário	 <br> - [EO10]() Missões | O Épico [EO10]() satisfaz o requisito [RF14]()  |   |
| ELO13S  | - [RF15]() O sistema deve oferecer um sistema de recompensa ao usuário <br> -[EO12]() Recompensas | O Épico [EO12]() satisfaz o requisito [RF15]()  |   |
| ELO14S  | - [RF16]() O sistema deve ter um sistema de competição <br> -[EO09]() Competição | O Épico [EO09]() satisfaz o requisito [RF16]()  |   |
| ELO15S  | - [RF17]() O aplicativo deve ter um sistema de amizade <br> - [EO02]() Amigos | O Épico [EO02]() satisfaz o requisito [RF17]()  |   |
| ELO16S  | - [RF18]() 	O aplicativo deve ter um sistema de controle da frequência de estudo do usuário <br> - [EO13]() Ofensiva| O Épico [EO13]() satisfaz o requisito [RF18]()  |   |
| ELO17S  | - [RF19]() O aplicativo deve ser personalizável às necessidades do usuário <br> - [EO08]() Personalização | O Épico [EO08]() satisfaz o requisito [RF18]()  |   |
| ELO18S  | - [RF22]() O aplicativo oferece conquistas para marcos específicos no aprendizado <br> - [US20]() Visualizar as conquistas | A História de Usuário [US20]() satisfaz o requisito [RF22]()  |   |
| ELO19S  | - [RF23]() O aplicativo deve fornecer uma loja <br> - [EO11]() Loja| O Épico [EO11]() satisfaz o requisito [RF23]() |   |
| ELO20S  | - [RF24]() O aplicativo deve permitir a compra de recursos a partir de dinheiro real <br> - [US30]() Comprar com dinheiro real na loja | A História de Usuário [US30]() satisfaz o requisito [RF24]() |   |
| ELO21S  | - []() <br> -[]() | []() []()  |   |
| ELO22S  | - []() <br> -[]() | []() []()  |   |
| ELO23S  | - []() <br> -[]() | []() []()  |   |
| ELO24S  | - []() <br> -[]() | []() []()  |   |
| ELO25S  | - []() <br> -[]() | []() []()  |   |
| ELO26S  | - []() <br> -[]() | []() []()  |   |
| ELO27S  | - []() <br> -[]() | []() []()  |   |
| ELO28S  | - []() <br> -[]() | []() []()  |   |

<center>

**Tabela 2** - Elos do tipo satisfação

</center>


### Elos de recurso

<center>

**Tabela 3** - Elos do tipo recurso

</center>

### Elos de representação

<center>

**Tabela 4** - Elos do tipo representação

| ID | Elementos Rastreáveis | Elo | Justificativa |
|----|-----------------------|-----|---------------|
| ELO1RP | [RF01](../Elicitacao/priorizacao/priorizados.md#rf01): O aplicativo deve ter uma variedade de cursos e idiomas <br> [CN1](../Modelagem/Cenarios/cenariosFinais.md#cn1-escolher-curso): Escolher curso | O cenário [CN1](../Modelagem/Cenarios/cenariosFinais.md#cn1-escolher-curso) representa parcialmente o requisito [RF01](../Elicitacao/priorizacao/priorizados.md#rf01) | |
| ELO2RP | [RF04](../Elicitacao/priorizacao/priorizados.md#rf04): O aplicativo deve permitir o cadastro e gerenciamento de contas <br> [Diagrama do I* - Conta](../ModelagemAgil/i-estrela.md#gerencia-de-conta) | O [Diagrama do I* - Conta](../ModelagemAgil/i-estrela.md#gerencia-de-conta) representa o requisito [RF04](../Elicitacao/priorizacao/priorizados.md#rf04) | |
| ELO3RP | [RF02](../Elicitacao/priorizacao/priorizados.md#rf02): O usuário deve poder refazer as lições <br> [CN2](../Modelagem/Cenarios/cenariosFinais.md#cn2-revisar-nivel): Revisar nível | O cenário [CN2](../Modelagem/Cenarios/cenariosFinais.md#cn2-revisar-nivel) representa o requisito [RF02](../Elicitacao/priorizacao/priorizados.md#rf02) |
| ELO4RP | [RF04](../Elicitacao/priorizacao/priorizados.md#rf04): O aplicativo deve permitir o cadastro e gerenciamento de contas <br> [CN3](../Modelagem/Cenarios/cenariosFinais.md#cn3-cadastrar-conta): Cadastrar conta | O cenário [CN3](../Modelagem/Cenarios/cenariosFinais.md#cn3-cadastrar-conta) representa parcialmente o requisito [RF04](../Elicitacao/priorizacao/priorizados.md#rf04) |
| ELO5RP | [RF04](../Elicitacao/priorizacao/priorizados.md#rf04): O aplicativo deve permitir o cadastro e gerenciamento de contas <br> [CN4](../Modelagem/Cenarios/cenariosFinais.md#cn4-excluir-conta): Excluir conta | O cenário [CN4](../Modelagem/Cenarios/cenariosFinais.md#cn4-excluir-conta) representa parcialmente o requisito [RF04](../Elicitacao/priorizacao/priorizados.md#rf04) |
| ELO6RP | [RF12](../Elicitacao/priorizacao/priorizados.md#rf12): O usuário deve ser capaz de monitorar seu progresso no curso <br> [CN6](../Modelagem/Cenarios/cenariosFinais.md#cn6-acompanhar-progresso): Acompanhar progresso | O cenário [CN6](../Modelagem/Cenarios/cenariosFinais.md#cn6-acompanhar-progresso) representa o requisito [RF12](../Elicitacao/priorizacao/priorizados.md#rf12) |
| ELO7RP | [RF30](../Elicitacao/priorizacao/priorizados.md#rf30): O usuário deve ser capaz de gerenciar o seu perfil <br> [CN7](../Modelagem/Cenarios/cenariosFinais.md#cn7-personalizar-perfil): Personalizar perfil | O cenário [CN7](../Modelagem/Cenarios/cenariosFinais.md#cn7-personalizar-perfil) representa parcialmente o requisito [RF30](../Elicitacao/priorizacao/priorizados.md#rf30) |
| ELO8RP | [RF19](../Elicitacao/priorizacao/priorizados.md#rf19): O aplicativo deve ser personalizável às necessidades do usuário <br> [CN8](../Modelagem/Cenarios/cenariosFinais.md#cn8-personalizar-o-aplicativo): Personalizar o aplicativo | O cenário [CN8](../Modelagem/Cenarios/cenariosFinais.md#cn8-personalizar-o-aplicativo) representa o requisito [RF19](../Elicitacao/priorizacao/priorizados.md#rf19) |
| ELO9RP | [RF13](../Elicitacao/priorizacao/priorizados.md#rf13): O usuário deve receber notificações <br> [CN9](../Modelagem/Cenarios/cenariosFinais.md#cn9-receber-notificacoes): Receber notificações | O cenário [CN9](../Modelagem/Cenarios/cenariosFinais.md#cn9-receber-notificacoes) representa o requisito [RF13](../Elicitacao/priorizacao/priorizados.md#rf13) |
| ELO10RP | [RF14](../Elicitacao/priorizacao/priorizados.md#rf14): O aplicativo deve oferecer um sistema de missões ao usuário <br> [CN10](../Modelagem/Cenarios/cenariosFinais.md#cn10-concluir-missao): Concluir missão | O cenário [CN10](../Modelagem/Cenarios/cenariosFinais.md#cn10-concluir-missao) representa o requisito [RF14](../Elicitacao/priorizacao/priorizados.md#rf14) |
| ELO11RP | [RF15](../Elicitacao/priorizacao/priorizados.md#rf15): O aplicativo deve ter um sistema de recompensas <br> [CN11](../Modelagem/Cenarios/cenariosFinais.md#cn11-conquistar-recompensa): Conquistar recompensa | O cenário [CN11](../Modelagem/Cenarios/cenariosFinais.md#cn11-conquistar-recompensa) representa o requisito [RF15](../Elicitacao/priorizacao/priorizados.md#rf15) |
| ELO12RP | [RF16](../Elicitacao/priorizacao/priorizados.md#rf02): O aplicativo deve ter um sistema de competição <br> [CN12](../Modelagem/Cenarios/cenariosFinais.md#cn12-competir-em-uma-divisao) |
| ELO13RP | [RF18](../Elicitacao/priorizacao/priorizados.md#rf18): O aplicativo deve ter um sistema de controle da frequência de estudo do usuário <br> [CN13](../Modelagem/Cenarios/cenariosFinais.md#cn13-manter-uma-ofensiva): Manter uma ofensiva |
| ELO14RP | [RF23](../Elicitacao/priorizacao/priorizados.md#rf23): O aplicativo deve fornecer uma loja <br> [CN14](../Modelagem/Cenarios/cenariosFinais.md#cn14-comprar-na-loja) |
| ELO15RP | [RNF41](../Elicitacao/priorizacao/priorizados.md#rnf41): O aplicativo deve apresentar uma navegação simples <br> [CN15](../Modelagem/Cenarios/cenariosFinais.md#cn15-navegar-entre-interfaces): Navegar entre interfaces |
| ELO16RP | [RF04](../Elicitacao/priorizacao/priorizados.md#rf04): O aplicativo deve permitir o cadastro e gerenciamento de contas <br> [CN17](../Modelagem/Cenarios/cenariosFinais.md#cn17-logar-no-duolingo): Logar no Duolingo |
| ELO17RP | [RF04](../Elicitacao/priorizacao/priorizados.md#rf04): O aplicativo deve permitir o cadastro e gerenciamento de contas [CN18](../Modelagem/Cenarios/cenariosFinais.md#cn18-deslogar-da-conta): Deslogar da conta |
| ELO18RP | [RF04](../Elicitacao/priorizacao/priorizados.md#rf04): O aplicativo deve permitir o cadastro e gerenciamento de contas <br> [CN20](../Modelagem/Cenarios/cenariosFinais.md#cn20-trocar-senha-da-conta): Trocar senha de conta |
| ELO19RP | [RF04](../Elicitacao/priorizacao/priorizados.md#rf04): O aplicativo deve permitir o cadastro e gerenciamento de contas <br> [CN21](../Modelagem/Cenarios/cenariosFinais.md#cn21-trocar-e-mail-da-conta): Trocar e-mail da conta |
| ELO20RP | [RF38](../Elicitacao/priorizacao/priorizados.md#rf38): O aplicativo deve ser gamificado <br> [CN19](../Modelagem/Cenarios/cenariosFinais.md#cn19-utilizar-bloqueio-de-ofensiva): Utilizar bloqueio de ofensiva |
| ELO21RP | [RF38](../Elicitacao/priorizacao/priorizados.md#rf38): O aplicativo deve ser gamificado <br> [CN22](../Modelagem/Cenarios/cenariosFinais.md#cn22-perder-vida) |
| ELO22RP | [RF38](../Elicitacao/priorizacao/priorizados.md#rf38): O aplicativo deve ser gamificado <br> [CN23](../Modelagem/Cenarios/cenariosFinais.md#cn23-impedir-o-usuario-de-concluir-licao): Impedir o usuário de concluir lição |
| ELO23RP | [RF06](../Elicitacao/priorizacao/priorizados.md#rf06): O aplicativo deve exibir as coleções de erros, palavras aprendidas e histórias estudadas <br> [CN24](../Modelagem/Cenarios/cenariosFinais.md#cn24-acessar-colecoes): Acessar coleções |
| ELO24RP | [RF22](../Elicitacao/priorizacao/priorizados.md#rf22): O aplicativo oferece conquistas para marcos específicos no aprendizado <br> [CN25](../Modelagem/Cenarios/cenariosFinais.md#cn25-acessar-conquistas): Acessar conquistas |

</center>

### Elos de agregação

<center>

**Tabela 5** - Elos do tipo agregação

</center>

## Histórico de versão

## Referências

1. SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://aprender3.unb.br/pluginfile.php/2692882/mod_resource/content/3/05_20_sayao.pdf. Acesso em: 9 de setembro de 2024.

