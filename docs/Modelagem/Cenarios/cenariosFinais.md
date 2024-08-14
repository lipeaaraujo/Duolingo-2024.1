# Resultado dos Cenários

Após o levantamento dos cenários realizado por amplas as duplas, fizemos uma análise dos cenários autorados por cada dupla e realizamos a junção em uma única tabela de cenários produzidos. Após a tabela 1 de cenários produzidos, localiza-se a especificação de acordo com o Modelo de Cenário de cada um dos cenários.

Durante a reunião gravada, foram também levantados 2 requisitos novos de autoria das duas duplas durante a discussão de outros cenários relevantes.

<center>

### Tabela 1: Cenários Produzidos

| ID   | Titulo                                    | Rastreabilidade |
|------|-------------------------------------------|-----------------|
| CN1  | Escolher curso                            | [Dupla 1](cenarios1.md#cn1-escolha-de-um-idioma), [Dupla 2](cenarios2.md#cn1---escolher-curso) |
| CN2  | Refazer uma nível                         | [Dupla 1](cenarios1.md#cn2---refazer-lição) |
| CN3  | Cadastrar conta                         | [Dupla 1](cenarios1.md#cn3---cadastro-de-conta) |
| CN4  | Excluir conta                             | [Dupla 2](cenarios2.md#cn5---excluir-a-conta) |
| CN5  | Fazer lições                              | [Dupla 1](cenarios1.md#cn4---fazer-lições), [Dupla 2](cenarios2.md#cn6---fazer-lições) |
| CN6  | Acompanhar progresso                      | [Dupla 1](cenarios1.md#cn5---acompanhamento-de-progresso), [Dupla 2](cenarios2.md#cn8---monitorar-o-progresso) |
| CN7  | Personalizar conta                        | [Dupla 2](cenarios2.md#cn4---personalizar-a-conta) |
| CN8  | Personalizar o aplicativo                 | [Dupla 1](cenarios1.md#cn6---personalização--às-necessidades-do-usuário), [Dupla 2](cenarios2.md#cn9---personalizar-o-aplicativo) |
| CN9  | Receber notificações                      | [Dupla 2](cenarios2.md#cn10---receber-notificações) |
| CN10 | Realizar missões                          | [Dupla 2](cenarios2.md#cn11---realizar-missões) |
| CN11 | Receber recompensas                       | [Dupla 2](cenarios2.md#cn12---receber-recompensas) |
| CN12 | Competir em uma divisão                   | [Dupla 2](cenarios2.md#cn13---competir-em-uma-divisão) |
| CN13 | Manter uma ofensiva                       | [Dupla 2](cenarios2.md#cn14---manter-uma-ofensiva) |
| CN14 | Utilizar a loja                           | [Dupla 1](cenarios1.md#cn8---fazer-compra-na-loja), [Dupla 2](cenarios2.md#cn15---utilizar-a-loja) |
| CN15 | Navegar entre interfaces                  | [Dupla 2](cenarios2.md#cn16---navegar-entre-interfaces) |
| CN16 | Escolher o idioma base do Duolingo        | [Dupla 1](cenarios1.md#cn7---escolher-o-idioma-base-do-duolingo) |
| CN17 | Fazer login no Duolingo                   | Dupla 1, Dupla 2 |
| CN18 | Sair da conta                             | Dupla 1, Dupla 2 |

**Autores**: [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), 2024

</center>

## CN1 - Escolher curso

Na tabela 2 está determinado o Cenário 1, que descreve a escolha de curso disponível por parte do usuário no Duolingo

<center>

### Tabela 2: CN1 - Escolher curso

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Escolher um **curso** |
| Objetivo  | Permitir que o **usuário** selecione o **curso** de idioma que deseja aprender |
| Contexto  | Local: Em casa <br>  Pré-condições: Ter acesso a internet e ter o aplicativo instalado |
| Recursos  | Aplicativo **Duolingo**.<br>Acesso a internet.<br> Dispositivo celulares e semelhantes|
| Atores  | O **usuário** do **Duolingo** |
| Episódios |  O **usuário** pega o celular.<br>O **usuário** abre o **Duolingo**.<br> Seleciona a **aba** de escolha de **curso**.<br> Seleciona o **curso** desejado.<br> **Clica** no botão "continuar".<br> Responde uma breve pesquisa.<br> O aplicativo abre a primeira **lição** do **curso** escolhido.  |
| Restrição  | O **curso** escolhido deve estar disponível na lista de **cursos** oferecidos pelo aplicativo **Duolingo** |
| Exceção  | O **usuário** pode não encontrar o **curso** desejado.</br>Queda de internet antes de concluir o processo de escolha.<br> O aparelho celular não funcionar corretamente. |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN2 - Refazer nível

Na tabela 3 está determinado o CN2, que descreve como refazer um **nível concluido**.

<center>

### Tabela 3: CN2

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Refazer **nível**       |
| Objetivo  | o **usuário** deseja refazer um **nível concluido**     |
| Contexto  |  Local: Em casa.<br>Pré-condições: Ter acesso a internet, ter o aplicativo instalado e ter concluido a lição previamente    |
| Recursos  | Aplicativo **Duolingo**.<br> Dispositivo celulares e semelhantes.<br> Acesso à internet.       |
| Atores  | O **usuário** do **Duolingo**       |
| Episódios | O **usuário** pega o celular.<br>**Usuário** abre o **Duolingo**.<br>**Usuário** seleciona o **nível** desejado.<br>**Usuário** clica na opção "Revisar".<br> O **Duolingo** inicia a **lição**. |
| Restrição  |  O **nível** deve estar concluido      |
| Exceção  | Queda de internet antes de concluir a **lição**.<br> O aparelho celular não funcionar corretamente.</br>O **nível** não estar disponível para revisão, caso o conteúdo tenha sido alterado ou removido |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN3 - Cadastrar conta

Na tabela 4 está determinada a CN3, que descreve como o **usuário** pode **cadastrar conta** no **Duolingo**.

<center>

### Tabela 4: CN3

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Cadastrar conta**        |
| Objetivo  | o **usuário** deseja **cadastrar conta** no **Duolingo**     |
| Contexto  | Local: Em casa <br>  Pré-condições: Ter acesso a internet e ter o aplicativo instalado    |
| Recursos  |  Aplicativo **Duolingo**.<br>Dispositivo celulares e semelhantes.<br> Acesso à internet.       |
| Atores  | O **usuário** do **Duolingo**       |
| Episódios |O **usuário** deseja cadastrar uma **conta**.</br>O **usuário** pega o celular.<br>O **usuário** abre o **Duolingo**.<br>O **usuário** acessa a tela de registro.</br>Preenche o formulário com dados pessoais <br> O **usuário** concorda com os **termos de serviço**<br>A **conta** é criada e o **usuário** é direcionado ao tela inicial |
| Restrição  |  O **usuário** deve fornecer informações válidas e únicas.    |
| Exceção  | Queda de internet antes de concluir o processo de criação.<br> O aparelho celular não funcionar corretamente.     |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN4 - Excluir conta

Na tabela 5 está determinado o Cenário 4, que descreve o processo de exclusão de uma conta no Duolingo.

<center>

### Tabela 5: CN5

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Excluir conta** |
| Objetivo  | Permitir que o **usuário** exclua permanentemente sua **conta** e todos os dados associados |
| Contexto  | Local: Na faculdade <br>  Pré-condições: Ter acesso a internet, ter o aplicativo instalado e ter conta registrada   |
| Recursos  | Aplicativo **Duolingo**.<br>Acesso à internet<br>Dispositivo celulares e semelhantes. |
| Atores  | O **usuário** do **Duolingo** |
| Episódios |O **usuário** deseja **excluir conta** pessoal.</br>O **usuário** acessa as **configurações** da conta<br>Ele seleciona a opção de **excluir conta**<br>O **Duolingo** solicita confirmação da exclusão<br>A **conta** é permanentemente excluída do sistema |
| Restrição  | A exclusão da **conta** deve ser irreversível e todas as informações do **usuário** devem ser removidas. |
| Exceção  | Queda de internet antes de concluir o processo de criação.<br> O aparelho celular não funcionar corretamente. </br>A exclusão pode ser interrompida se o usuário não confirmar a ação ou se houver problemas de conexão |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN5 - Fazer lição

Na tabela 6 está determinado a CN5 , que descreve como o usuário pode fazer uma lição por completo.

<center>

### Tabela 6: CN5

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Fazer lição**       |
| Objetivo  | Permitir que o **usuário** complete **lições** para aprender um novo idioma.   |
| Contexto  |  Local: Na praia.<br>Pré-condições: Ter acesso a internet, ter o aplicativo instalado e ter iniciado algum **curso** no **Duolingo**.    |
| Recursos  |  Aplicativo **Duolingo**.<br>Dispositivo celulares e semelhantes.<br> Acesso à internet. |
| Atores  | O **usuário** do **Duolingo**       |
| Episódios | O **usuário** deseja fazer uma **lição**.<br>O **usuário** pega o celular.<br>**Usuário** abre o **Duolingo**.<br>**Usuário** seleciona **lição** desejada.<br>**Usuário** clica na opção "Começar".<br> O **Duolingo** inicia a **lição**.</br> **Usuario** responde uma **questão**.<br>**Duolingo** mostra um **pop-up** de **feedback**.<br>**Usuário** termina a **lição**.<br>**Duolingo** mostra **metricas de desempenho**.      |
| Restrição  |  A **lição** deve estar disponível. |
| Exceção  | Queda de internet antes de concluir a **lição**.<br> O aparelho celular não funcionar corretamente. <br>  A **lição** não estar disponível.     |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN6 - Acompanhar progresso

Na tabela 7 está determinada a CN6, que descreve como acompanhar o progresso individual.

<center>

### Tabela 7: CN6 

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Acompanhar progresso        |
| Objetivo  | O **usuário** deseja acompanhar seu progresso nos cursos do **Duolingo**.     |
| Contexto  | Local: No ônibus <br> Pré-condições: Ter acesso a internet, estar logado em uma conta e ter o aplicativo instalado   |
| Recursos  | Aplicativo **Duolingo**.<br> Dispositivo celulares e semelhantes.<br> Acesso à internet.       |
| Atores  | O **usuário** do **Duolingo**       |
| Episódios | O usuário deseja acompanhar seu progresso.<br>O **usuário** pega o celular.<br>O **usuário** abre o **Duolingo**.<br>  O **usuário** acessa a **aba** de detalhes da **seção** atual <br> O usuário verifica o **histórico de níveis**, conceitos aprendidos |
| Restrição  |  O progresso deve ser atualizado em tempo real |
| Exceção  | Queda de internet ao tentar acessar a **aba** de progresso.<br> Dados de progresso não atualizados corretamente. <br> O aparelho celular não funcionar corretamente.    |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN7 - Personalizar conta

Na tabela 8 está determinado o Cenário 7, que descreve como o **usuário** pode **personalizar** suas **configurações** no **Duolingo**.

<center>

### Tabela 8: CN7

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Personalizar** **conta** |
| Objetivo  | Permitir que o **usuário** ajuste suas preferências e personalize seu **perfil** |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a internet, estar **logado** em uma conta e ter o aplicativo instalado |
| Recursos  | Aplicativo **Duolingo**.<br>Dispositivo celulares e semelhantes.<br> Acesso à internet.|
| Atores  | O **usuário** do **Duolingo** |
| Episódios | O **usuário** deseja **personalizar** sua **conta**.<br>O **usuário** pega o celular.<br>O **usuário** abre o **Duolingo**.<br>O **usuário** seleciona o ícone do **perfil**.<br>O **usuário** seleciona o ícone de configuração.<br> O **usuário** ajusta as preferências de idioma, metas de estudo, e outras configurações pessoais<br>As alterações são salvas e refletidas no perfil |
| Restrição  | As opções de personalização disponíveis devem estar em conformidade com os recursos do aplicativo |
| Exceção  | Queda de internet ao tentar *personalizar*.<br> O aparelho celular não funcionar corretamente.  |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN8 - Personalizar o aplicativo

Na tabela 9 está determinado o Cenário 8, que descreve a funcionalidade de personalização do aplicativo **Duolingo**.

<center>

### Tabela 9: CN8

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Personalizar** o aplicativo |
| Objetivo  | Realizar uma **personalização** no aplicativo a partir de uma **preferência** do usuário |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a **internet**, estar logado em uma conta e ter o aplicativo instalado|
| Recursos  | Dispositivo celular ou semelhantes.<br> Acesso à **internet**.<br> Aplicativo do **Duolingo**.  |
| Atores  | **Usuário** do Duolingo |
| Episódios | O **usuário** deseja personalizar o aplicativo, <br> O **usuário** acessa o aplicativo do **Duolingo** no celular, <br> O **usuário** acessa a tela de **perfil**, <br> O **usuário** acessa o ícone de configurações, <br> O **usuário** modifica uma das **configurações** disponível, <br> O app **Duolingo** se comporta com base nas configurações do usuário |
| Restrição  | A **personalização** precisa estar disponível como configuração no **Duolingo** |
| Exceção  | Configuração não disponível no **Duolingo**. <br> Queda de internet ao tentar **personalizar** <br> O aparelho celular não funcionar corretamente. |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN9 - Receber notificações

Na tabela 10 está determinado o Cenário 9, que descreve a funcionalidade de recebimento de **notificações** no **Duolingo**.

<center>

### Tabela 10: CN9

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Receber **notificações** |
| Objetivo  | Receber uma **notificação** de alguma novidade ou lembrete para realizar uma **lição** |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a **internet**,ter o aplicativo instalado e estar logado em uma conta |
| Recursos  | Dispositivo celular ou semelhantes, <br> Acesso à **internet**, <br> Aplicativo **Duolingo**  |
| Atores  | **Usuário** do Duolingo |
| Episódios | O **usuário** está ou não utilizando o celular, <br> O app **Duolingo** envia uma **notificação** com uma novidade ou lembrete, <br> O dispositivo torna a **notificação** visível, <br> O **usuário** visualiza a **notificação**, <br> O **usuário** interage com a **notificação** |
| Restrição  | O **usuário** habilitar as **notificações** do **Duolingo** |
| Exceção  | O **usuário** estar com as **notificações** desabilitadas.</br> Aparelho sem conexão a internet, <br> O aparelho celular não funcionar corretamente. |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN10 - Realizar missões

Na tabela 11 está determinado o Cenário 10, que descreve a funcionalidade de realizar **missões** dentro do **Duolingo**.

<center>

### Tabela 11: CN10

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Realizar **missões** |
| Objetivo  | Realizar uma **missão** disponibilizada dentro do aplicativo **Duolingo** para o **usuário** |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a internet, estar **logado** em uma conta |
| Recursos  | Dispositivo celular ou semelhantes, <br> Acesso à **internet**, <br> Aplicativo do **Duolingo**  |
| Atores  | **Usuário** do **Duolingo** |
| Episódios | O **usuário** deseja realizar uma **missão** no **Duolingo**, <br> O **usuário** acessa o aplicativo do **Duolingo**, <br> O **usuário** acessa a tela de **missões**, <br> O **usuário** verifica a **missão** a ser feita, <br> O **usuário** realiza a **missão** |
| Restrição  | O **usuário** estar inscrito em um **curso**, <br> O app **Duolingo** disponibilizar uma **missão** para o **usuário** |
| Exceção  | O **usuário** não estar inscrito em um **curso**, <br> O app **Duolingo** não ter disponibilizado uma **missão** para o **usuário**, <br> Queda de internet durante o uso <br> O aparelho celular não funcionar corretamente. |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN11 - Receber recompensas

Na tabela 12 está determinado o Cenário 11, que descreve a funcionalidade de recebimento de **recompensas** no **Duolingo**.

<center>

### Tabela 12: CN11

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Receber **recompensas** |
| Objetivo  | Receber uma **recompensa** após a conclusão de uma **lição** ou **missão** |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a internet, estar logado em uma conta |
| Recursos  | Dispositivo celular ou semelhantes, <br> Acesso à internet, <br> Aplicativo **Duolingo**  |
| Atores  | **Usuário** do Duolingo |
| Episódios | O **usuário** deseja realizar uma **lição** ou **missão**, <br> O **usuário** acessa o aplicativo do **Duolingo** no celular, <br> O **usuário** começa uma **lição** ou **missão**, <br> O **usuário** conclui a **lição** ou **missão**, <br> O **Duolingo** fornece uma **recompensa** ao **usuário** |
| Restrição  | O **usuário** estar inscrito em um **curso**, <br> O **usuário** começar uma **lição**, **missão** ou objetivo, <br> O **usuário** concluir uma **lição**, **missão** ou objetivo |
| Exceção  | O **usuário** não estar inscrito em um **curso**, <br> O **usuário** não conseguir começar uma **lição** ou **missão**, <br> O **usuário** não concluir a **lição** ou **missão** por completo, <br> Queda de internet durante o uso <br> O aparelho celular não funcionar corretamente. |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Samuel Alves Silva](https://github.com/samuelalvess), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN12 - Competir em uma divisão

Na tabela 13 está determinado o CN12, que descreve a funcionalidade de competição em uma **divisão** no **Duolingo**.

<center>

### Tabela 13: CN12

| Elemento | Descrição     |
|----------|---------------------|f
| Titulo  | Competir em uma **divisão** |
| Objetivo  | Participar de uma competição em formato de **divisão** disputada por quantidade de **pontos de XP** com duração de 1 semana |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a internet, estar logado em uma conta |
| Recursos  | Dispositivo celular ou semelhantes, <br> Acesso à internet, <br> Aplicativo do **Duolingo** instalado |
| Atores  | **Usuário** do **Duolingo** |
| Episódios | O **usuário** deseja competir em uma **divisão** no **Duolingo**, <br> O **usuário** acessa o **Duolingo** no celular, <br> O **usuário** realiza uma **lição** ou **missão**, <br> O **Duolingo** fornece **pontos de XP** ao **usuário**, <br> O **usuário** recebe uma classificação com base nos **pontos de XP** que adquiriu durante a semana |
| Restrição  | O **usuário** estar em uma **divisão**, <br> O **usuário** poder obter **pontos de XP** |
| Exceção  | Queda de internet durante a utilização do aplicativo, <br> O aparelho celular não funcionar corretamente, <br> O **usuário** não estar inscrito em um **curso**, <br> O **usuário** não estar participando de nenhuma **divisão**, <br> O **usuário** não ser capaz de realizar **lições** ou **missões**, <br> Queda de internet durante o uso <br> O aparelho celular não funcionar corretamente. |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), [Samuel Alves Silva](https://github.com/samuelalvess), 2024

</center>

## CN13 - Manter uma ofensiva

Na tabela 15 está determinado o Cenário 14, que descreve a funcionalidade de manter uma **ofensiva** no **Duolingo**.

<center>

### Tabela 14: CN13

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Manter uma **ofensiva** |
| Objetivo  | Manter uma sequência de dias de **ofensiva** com a realização de **lições** |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a **internet**, estar **logado** em uma conta e não acessou o **Duolingo** no dia |
| Recursos  | Dispositivo celular ou semelhantes, <br> Acesso à **internet**, <br> Aplicativo do **Duolingo** instalado |
| Atores  | **Usuário** do Duolingo |
| Episódios | O **usuário** deseja manter uma **ofensiva** no **Duolingo**, <br> O **usuário** acessa o **Duolingo** no celular, <br> O **usuário** acessa o **curso** que está inscrito, <br> O **usuário** realiza uma **lição** do **curso**, <br> O **Duolingo** incrementa os dias de **ofensiva** |
| Restrição  | O **usuário** estar inscrito em um **curso**, <br> O **usuário** ser capaz de realizar uma **lição** |
| Exceção  | Queda de internet durante a utilização do aplicativo, <br> O aparelho celular não funcionar corretamente, <br> O **usuário** não estar inscrito em um **curso** |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), [Samuel Alves Silva](https://github.com/samuelalvess), 2024

</center>

## CN14 - Utilizar a loja

Na tabela 16 está determinado o Cenário 15, que descreve a funcionalidade de utilizar a **loja** do **Duolingo**.

<center>

### Tabela 15: CN14

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Utilizar a **loja** |
| Objetivo  | Fazer utilização da **loja** dentro do app para adquirir recursos, usando os **cristais**, que podem ser utilizados dentro do **Duolingo** |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a **internet**, estar **logado** em uma conta |
| Recursos  | Dispositivo celular ou semelhantes, <br> Acesso à **internet**, <br> Aplicativo **Duolingo** instalado |
| Atores  | **Usuário** do **Duolingo** |
| Episódios | O **usuário** acessar a **loja** no **Duolingo**, <br> O **usuário** acessa o **Duolingo** no celular, <br> O **usuário** acessa a **aba** da **loja**, <br> O **usuário** realiza a compra desejada, <br> O **usuário** utiliza o que comprou dentro do **Duolingo** |
| Restrição  | O **usuário** ter **cristais** disponíveis comprar recursos na **loja** |
| Exceção  | Queda de internet durante a utilização do aplicativo, <br> O aparelho celular não funcionar corretamente, <br> O **usuário** não ter **cristais** suficientes para comprar o recurso desejado |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), [Samuel Alves Silva](https://github.com/samuelalvess), 2024

</center>

## CN15 - Navegar entre interfaces

Na tabela 17 está determinado o Cenário 16, que descreve a funcionalidade de **navegar** entre **interfaces** no **Duolingo**.

<center>

### Tabela 16: CN15

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Navegar** entre **interfaces** |
| Objetivo  | Permitir a fácil e intuitiva navegação entre as diferentes **interfaces** do **Duolingo** |
| Contexto  | Local: Em casa <br> Pré-condições: Ter acesso a **internet** |
| Recursos  | Dispositivo celular ou semelhantes, <br> Acesso à **internet**, <br> Aplicativo **Duolingo** instalado |
| Atores  | **Usuário** do Duolingo |
| Episódios | O **usuário** utilizar o **Duolingo**, <br> O **usuário** acessa o **Duolingo** no celular, <br> O **Duolingo** mostra sua **interface**, <br> O **usuário** navega pelas **interfaces**, <br> O **usuário** encontra a **aba** desejada |
| Restrição  | O app **Duolingo** apresentar uma **interface** intuitiva e navegável, <br> O **usuário** conseguir localizar a **aba** desejada |
| Exceção  | Queda de internet antes de concluir a navegação, <br> O aparelho celular não funcionar corretamente, <br> O **usuário** não conseguir localizar uma **aba** desejada na **interface**, <br> A interface ser confusa para o **usuário**, <br> Queda de internet durante o uso <br> O aparelho celular não funcionar corretamente. |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022),[Samuel Alves Silva](https://github.com/samuelalvess), 2024

</center>

## CN16 - Escolher o idioma base do Duolingo

Na tabela 17 está determinada a CN16, que descreve como alterar o **idioma base** do **Duolingo**.

<center>

### Tabela 17: CN16

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | Escolher o **idioma base** do **Duolingo** |
| Objetivo  | Fazer uma escolha de **idioma base** no **Duolingo** |
| Contexto  | Local: Em casa <br>  Pré-condições: Ter acesso a internet e ter o aplicativo instalado |
| Recursos  | Aplicativo **Duolingo**, <br> Dispositivo celulares e semelhantes. <br> Acesso à internet. |
| Atores  | O **usuário** do **Duolingo** |
| Episódios | O **usuário** deseja escolher um **idioma base** no **Duolingo**, <br> O **usuário** pega o celular, <br> O **usuário** abre o **Duolingo**, <br> Seleciona a **aba** de escolha de idiomas, <br> O **usuário** busca pelo **idioma base** desejado. <br> Seleciona o **curso** que deseja aprender, dentre os disponiveis no **idioma base** escolhido, <br> Clica no botão de continuar, <br> Responde uma breve pesquisa, <br> O aplicativo abre a primeira **lição** do **curso** escolhido. |
| Restrição | O **curso** que deseja estudar está disponível no **idioma base**, <br> O idioma desejado está disponível no aplicativo |
| Exceção  | Queda de internet antes de concluir a pesquisa.<br> O aparelho celular não funcionar corretamente |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), [Samuel Alves Silva](https://github.com/samuelalvess), 2024

</center>

## CN17 - Fazer login no Duolingo

Na Tabela 18 está detalhada a CN17, que descreve o processo de **fazer login** em uma conta no **Duolingo**

<center>

### Tabela 18 - CN17

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Fazer login** no Duolingo |
| Objetivo  | **Fazer login** dentro do aplicativo do **Duolingo** |
| Contexto  | Local: Em casa <br>  Pré-condições: Ter acesso a internet, ter o aplicativo instalado e já ter uma conta criada |
| Recursos  | Aplicativo **Duolingo**, <br> Dispositivo celulares e semelhantes. <br> Acesso à internet. |
| Atores  | O **usuário** do **Duolingo** |
| Episódios | O **usuário** deseja **fazer login** em sua conta no **Duolingo**, <br> O **usuário** pega o celular, <br>O **usuário** abre o **Duolingo**, <br> O app **Duolingo** direciona o **usuário** para uma tela com as contas salvas no dispositivo, </br> O **usuário** seleciona a opção de adicionar uma nova **conta** </br> O **usuário** seleciona a opção que já tem uma **conta** criada, <br> O **Duolingo** direciona o **usuário** para um **formulário** de login, <br> O **usuário** preenche os dados da **conta**, <br> O **Duolingo** loga o **usuário** e redireciona para a **aba** inicial |
| Restrição  | O **usuário** inserir os dados corretos da **conta** |
| Exceção  | Queda de internet antes de concluir o login,<br> O aparelho celular não funcionar corretamente, <br> O **usuário** inserir dados incorretos da **conta** |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## CN18 - Sair da conta

Na Tabela 19 está detalhada a CN18, que descreve o processo de sair de uma conta no Duolingo

<center>

### Tabela 19 - CN18

| Elemento | Descrição     |
|----------|---------------------|
| Titulo  | **Sair da conta** |
| Objetivo  | **Sair da conta** atualmente **logada** dentro do aplicativo **Duolingo** |
| Contexto  | Local: Em casa <br>  Pré-condições: Ter acesso a internet |
| Recursos  | Aplicativo **Duolingo**, <br> Dispositivo celulares e semelhantes. <br> Acesso à internet. |
| Atores  | O **usuário** do **Duolingo** |
| Episódios | O **usuário** deseja sair de sua **conta** no **Duolingo**, <br> O **usuário** pega o celular, <br>O **usuário** abre o **Duolingo**, <br> O **usuário** acessa a tela de **perfil**, </br> O **usuário** acessa o ícone de **configurações**, </br> O **usuário** seleciona a opção de **sair da conta**, </br> O **Duolingo** desconecta da conta do **usuário**, <br> O **Duolingo** direciona para a **aba** de gerência de **contas** |
| Restrição  | Tem que estar **logado** em uma **conta** |
| Exceção  | Queda de internet antes de sair, <br> O aparelho celular não funcionar corretamente |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## Gravação

<center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/LiEHN3q2Mpg?si=QJKGkaJ9CMYewftw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

**Vídeo 1**: Junção dos cenários

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 13/08/2024 | 1.0 | Criação do documento e junção dos cenários | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Gabryel Nicolas S de Sousa](https://github.com/gabryelns), [Julio Roberto](https://github.com/JulioR2022) |
| 14/08/2024 | 1.1 | Adição da rastreabilidade | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 14/08/2024 | 1.2 | Ajuste do documento | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022) |

</center>