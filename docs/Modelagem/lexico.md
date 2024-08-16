# Léxico

Por definição, o léxico é um repertório de termos e palavras que existem dentro de uma língua específica. No levantamento de requisitos o léxico é um artefato que permite a definição de termos e expressões que existem dentro do contexto de um sistema de software.

A importância do léxico vem de proporcionar um entendimento comum e definir de forma unificada os termos usados no domínio do sistema, ajudando a evitar ambiguidades, reduzir mal-entendidos para que todos os envolvidos consigam ter a mesma visão sobre o sistema.

## Metodologia

O levantamento dos termos e palavras irá acontecer pelo o estudo e análise do contexto e ambiente do aplicativo Duolingo, utilizando como referência os [Requisitos Priorizados](../Elicitacao/priorizacao/priorizados.md) e o processo de desenvolvimento dos [Cenários](Cenarios/cenariosFinais.md) e os [Casos de Uso]() onde estes termos serão utilizados em conjunto. 

Cada termo ou símbolo, dependendo de suas características, será classificado de acordo com uma das classificações definidas na tabela 01 abaixo:

<center>

### Tabela 01 - Classificações 

| Objeto | Verbo | Estado |
|--------|-------|--------|
| Objetos representam coisas concretas ou abstratas que podem fazer parte do sistema ou ambiente, geralmente referem-se a substantivos ou entidades. | Verbos indicam ações, estados ou ocorrências | Verbos são as ações ou operações que podem ser realizadas dentro do sistema que afetam os objetos ou descrevem o comportamento do sistema | Estados representam as possíveis situações ou condições que um objeto pode se encontrar dentro do sistema ou seu ambiente |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), 2024

</center>

Após a definição da classificação, cada símbolo será descrito por sua **noção**, **impacto** e **sinônimos**, a tabela 02 abaixo define a forma que cada símbolo ou palavra será definida ao léxico:

<center>

### Tabela 02 - Modelo de Léxico

| Símbolo | Noção | Impacto | Sinônimos |
|---------|-------|---------|-----------|
| Nome do léxico | Denotação: o que o termo significa | Conotação: efeito, uso ou ocorrência do termo na aplicação ou o efeito da aplicação sobre o termo | Termos diferentes que tem significado similar |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), 2024

</center>

Importante ressaltar que este documento, assim como outros do projeto, pode sofrer constantes mudanças ao decorrer que o contexto do aplicativo é estudado e novos termos são levantados.

## Vocábulo

<center>

### Tabela 03 - Objetos

| Símbolo | Noção | Impacto | Sinônimos |
|---------|-------|---------|-----------|
| [Aba]() | Conjunto de elementos visuais logicamente relacionados podendo ser interativos ou não que ocupam a totalidade da tela do aparelho| As abas são usadas para organizar diferentes funcionalidades e conteúdos, como o perfil do **usuário**, as **lições**, as **divisões** e as configurações. O uso de abas permite que o usuário navegue facilmente entre diferentes partes do aplicativo, mantendo uma experiência organizada e eficiente. |Guia, Seção, Página |
| [Trilha de Aprendizado]() | Denotação: marcação visual da trilha de aprendizagem, lições concluidas, de um **usuário** do Duolingo  | facilita a observação do progresso individual | trilha de progresso, jornada de aprendizado |
| [Campo]() |Uma área de entrada ou exibição de dados em uma **interface** de **usuário**, onde o **usuário** pode inserir, selecionar ou visualizar informações específicas | Os **campos** facilitam a interação do **usuário** com o sistema, permitindo a coleta e apresentação de dados de maneira estruturada | Termos diferentes que tem significado similar  Área de entrada, Formulário, Box de entrada |
| [Coleções]() |Reunião ordenada de objetos de mesmo interesse.  | Permite reunir um conjunto de irnforções importantes, como erros, para o aprendizado do usuário. | Conjuntos, repositórios, agrupamentos |
| [Configurações]() |Um conjunto de opções que permite ao usuário personalizar e ajustar o funcionamento do aplicativo de acordo com suas preferências e necessidades. | As **configurações** são fundamentais para oferecer uma experiência de usuário personalizada, permitindo que cada indivíduo adapte o uso do aplicativo conforme suas necessidades e preferências pessoais.| Preferências, Ajustes, Opções |
| [Conta]() | Registro de um usuário em uma plataforma ou serviço online | Permite personalizar a experiência com base nas preferências do usuário | Cadastro, login |
| [Conquistas]() | Conjunto de metas alcançadas, metas estas definidas pelo **Duolingo**. | Auxilia o **usuário** a construir um sentimento de sucesso e progresso em seus estudos.  | Metas, objetivos |
| [Coroa]() | Denotação: o que o termo significa | Conotação: efeito, uso ou ocorrência do termo na aplicação ou o efeito da aplicação sobre o termo | Termos diferentes que tem significado similar |
| [Cristais]() | Denotação: moeda de troca do **Duolingo** | Conotação: permite comprar itens e baús | Moeda, dinheiro |
| [Curso]() | Um conjunto estruturado de lições e atividades projetadas para ensinar uma língua ou outro conteúdo de maneira progressiva e organizada. | Cada curso é composto por várias unidades e lições que cobrem diferentes aspectos da língua, como gramática, vocabulário, e pronúncia. O curso é personalizado para o nível de proficiência do usuário e pode incluir exercícios de escrita, leitura, escuta, e fala. | Progama de estudos, sequência de lições |
| [Desempenho]() | O nível de eficiência e eficácia com que alguém executa uma tarefa ou atividade. | No Duolingo, "desempenho" refere-se à avaliação do progresso e sucesso do usuário ao longo do curso. Isso pode incluir a precisão nas respostas, a frequência de uso da plataforma, e a consistência na conclusão das lições. O desempenho é medido por métricas como a quantidade de lições completadas, a manutenção de séries diárias, e o número de pontos de experiência (XP) acumulados. | Eficiência de aprendizado, Nível de habilidade |
| [Divisão]() | A separação ou categorização de um todo em partes menores e organizadas. | No Duolingo, "divisão" pode se referir à estrutura organizacional dos cursos em diferentes seções, unidades, níveis e lições. Cada curso é dividido em unidades, que por sua vez são divididas em lições. | Segmentação, categorização |
| [Erro]() | Uma resposta ou ação incorreta que desvia do resultado esperado ou correto |  No Duolingo, "erro" refere-se a uma resposta incorreta fornecida durante uma lição ou exercício. | Falha, engano |
| [Feedback]() |Informação retornada a uma pessoa sobre seu desempenho, visando orientá-la na melhoria de suas ações ou decisões futuras. | No Duolingo, "feedback" refere-se às respostas fornecidas ao usuário após a conclusão de cada exercício ou lição. Esse feedback pode ser positivo, reforçando uma resposta correta, ou corretivo, explicando por que uma resposta estava errada e como melhorá-la. |  Retorno, avaliação, comentário |
| [Formulário]() |Um documento ou interface digital contendo campos para preenchimento de informações específicas | No Duolingo, "formulário" pode se referir a qualquer interface onde o usuário precisa inserir informações ou responder a perguntas | Questionário, ficha |
| [Idioma padrão]() | O idioma principal ou oficial utilizado em um determinado contexto, sistema ou plataforma. | No Duolingo, "idioma padrão" refere-se ao idioma que o usuário seleciona como a língua base para a interface e para a aprendizagem de outros idiomas. | Idioma base, língua principal |
| [Interface]() | A forma e o design de uma plataforma ou sistema com o qual os usuários interagem para realizar tarefas ou acessar informações. |  No Duolingo, "interface" refere-se ao layout e aos elementos visuais da plataforma que os usuários utilizam para aprender um idioma.  |  Layout, tela. |
| [Lição]() | Uma unidade de ensino focada em um tópico específico, com intuito de exercitar habilidades ou conhecimentos especificos. | No Duolingo, uma "lição" é uma parte do curso que oferece uma série de exercícios e atividades destinadas a ensinar e reforçar um aspecto particular do idioma, como vocabulário, gramática ou pronúncia | Exercício |
| [Loja]() |Um local, físico ou virtual, onde produtos ou serviços são oferecidos para venda | No Duolingo, a "loja" refere-se à seção dentro da plataforma onde os usuários podem comprar itens virtuais usando a moeda do Duolingo (cristaiis) | Seção de compras, Comércio digital |
| [Missão]() | Uma tarefa ou objetivo específico que deve ser completado para alcançar um determinado resultado ou recompensa | No Duolingo, "missão" refere-se a objetivos ou desafios que os usuários devem completar dentro da plataforma | Desafio, objetivo, tarefa |
| [Nível]() | Uma posição ou estágio em uma escala de progressão ou habilidade. | No Duolingo, é um Conjunto de **lições** abordam o mesmo tema | Grau |
| [Notificação]() | Uma mensagem ou alerta que informa o usuário sobre eventos ou atualizações importantes | No Duolingo, uma "notificação" é um aviso enviado para informar os usuários sobre novos eventos, atualizações, ou ações relacionadas à sua conta. | Aviso, mensagem |
| [Ofensiva]() | Uma ação ou comportamento que é agressivo | No Duolingo, refere-se á sequência ininterrupyta de dias que o **usuário** acessou o Duoling | Sequência, continuidade |
| [Perfil]() | Conjunto de informações e características que descrevem uma pessoa ou entidade em um sistema ou plataforma | No Duolingo, o "perfil" refere-se à página individual do usuário que contém informações pessoais, configurações e dados de progresso | Página de usuário, identidade digital |
| [Pontos de XP]() |Medida quantificável de progresso ou experiência acumulada em um sistema de aprendizado ou jogo. | No Duolingo, "pontos de XP" (Experiência) são usados para quantificar o progresso e o engajamento do usuário na plataforma. | Pontuação de aprendizado |
| [Pop-up]() | Uma janela ou mensagem que aparece temporariamente sobre a interface principal de um aplicativo ou site para fornecer informações ou interações adicionais. | No Duolingo, um "pop-up" refere-se a uma janela ou caixa de diálogo que surge sobre a interface principal para informar o usuário sobre atualizações, dicas, recompensas, ou ações necessárias. | Caixa de diálogo |
| [Questão]() | Uma pergunta ou problema que deve ser respondido ou resolvido. | No Duolingo, uma "questão" refere-se a um exercício ou item de prática que testa o conhecimento do usuário sobre o idioma em estudo. | Exercício |
| [Recompensas]() | Benefícios ou prêmios recebidos em troca de alcançar objetivos ou completar tarefas. |  No Duolingo, "recompensas" são incentivos dados aos usuários por atingir marcos ou completar atividades no processo de aprendizado. | Prêmios, incentivos |
| [Termos de Serviço]() | Conjunto de regras e diretrizes que regulam o uso de um serviço ou plataforma, definindo direitos e responsabilidades dos usuários e do provedor. | No Duolingo, os "Termos de Serviço" são o documento legal que estabelece as condições sob as quais os usuários podem acessar e utilizar a plataforma. |  Condições de uso, políticas de uso |
| [Usuário]() |  Pessoa que utiliza um serviço, aplicativo ou sistema para realizar atividades específicas. | No Duolingo, um "usuário" é alguém que se registra na plataforma para aprender um novo idioma. | Membro, Cliente |
| [Vida]() | Um recurso ou unidade que representa a quantidade de tentativas ou ações que um usuário pode realizar antes de precisar esperar para recuperar ou renovar esse recurso. | No Duolingo, "vida" é um recurso que limita o número de erros que um usuário pode cometer em exercícios antes de ter que aguardar um período de tempo ou realizar ações específicas para recuperar vidas | Tentativas,chances |


**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

<center>

### Tabela 04 - Verbos

| Símbolo | Noção | Impacto | Sinônimos |
|---------|-------|---------|-----------|
| [Aprender]() | Refere-se ao ato de adquirir conhecimento ou habilidade em um novo idioma através de lições, exercícios e atividades na plataforma | O objetivo central do Duolingo, onde o usuário progride em seu aprendizado de idiomas por meio de conteúdo interativo e feedback instantâneo | Estudar, Absorver, Dominar |
| [Cadastrar]() | Ato criar uma nova conta em plataformas e serciços | Permite que o usuário usurfrua das funcionalidades da plataforma/serviço | Registrar |
| [Comprar]() | Trocar cristais por itens naa loja | No duolingo, é utilizado para fornecer itens que melhore a experiência do usuário  | Escambo, troca, obter |
| [Configurar]() | Ajustar preferências pessoais, como notificações, idioma, ou aparência do aplicativo | Permite ao usuár o personalizar a experiência de uso, tornando a plataforma mais adequada às suas necessidades e hábitos | Ajustar, Personalizar, Definir |
| [Desbloquear]() | Ato de tornar acessível um conteúdo ou funcionalidade que estava inicialmente restrito ou inacessível | Incentiva o progresso, recompensando o usuário por completar tarefas ou alcançar metas, e permitindo o acesso a novos desafios ou áreas de aprendizado | Liberar, Acessar, Abrir |
| [Excluir]() | Remover permanentemente uma conta, dado, ou progresso do usuário na plataforma | Pode ser usado para apagar uma conta ou remover um conteúdo específico que o usuário não deseja mais manter | Deletar, Remover, Apagar |
| [Logar]() | Ação de autenticar-se na plataforma, inserindo credenciais para acessar uma conta | Permite ao usuário acessar seu perfil, progresso, e configurações pessoais | Entrar, Conectar, Autenticar-se |
| [Deslogar]() | Ação de sair da conta do usuário, encerrando a sessão atual na plataforma | Desconecta o usuário, protegendo suas informações pessoais e liberando o dispositivo para outro usuário | Sair, Desconectar, Encerrar sessão |
| [Navegar]() | Explorar as diferentes seções, funcionalidades e conteúdos disponíveis na plataforma | O usuário pode percorrer diferentes áreas do aplicativo para acessar lições, perfis, configurações, entre outros | Explorar, Percorrer, Acessar |
| [Praticar]() | Reforçar o aprendizado de idiomas por meio de atividades ou exercícios repetitivos | Auxilia na fixação de conhecimento e na melhoria da fluência, com exercícios voltados para áreas que o usuário precisa aprimorar | Treinar, Exercitar, Repetir |
| [Personalizar]() | Adaptar a experiência de aprendizado ou o ambiente da aplicação conforme as preferências do usuário | O usuário pode alterar configurações e escolher opções que tornem o uso da plataforma mais alinhado com suas necessidades e estilo de aprendizado | Customizar, Ajustar, Modificar |
| [Reportar]() | Informar ou registrar um problema, erro ou conteúdo inadequado encontrado na plataforma | Melhora a qualidade da experiência ao permitir que os usuários comuniquem problemas que possam ser corrigidos pela equipe de suporte | Denunciar, Informar, Relatar |
| [Revisar]() | Revisitar lições ou conteúdo já aprendido para reforçar o conhecimento e garantir a retenção | Ajuda a solidificar o aprendizado e identificar áreas onde o usuário pode ter dificuldades | Repassar, Relembrar, Rever |
| [Salvar]() | Guardar progresso, configurações ou dados do perfil do usuário | Garante que as mudanças feitas ou o progresso alcançado não sejam perdidos e possam ser acessados posteriormente | Armazenar, Guardar, Gravar |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

<center>

### Tabela 05 - Estados

| Símbolo | Noção | Impacto | Sinônimos |
|---------|-------|---------|-----------|
| [Bloqueado]() | Indicação que um conteúdo, lição ou função não está acessível ao usuário no momento | O usuário deve concluir pré-requisitos para desbloquear certo conteúdo. Pode ser utilizado para manter o engajamento, incentivando o progresso dentro da plataforma | Restringido, Inacessível, Fechado |
| [Concluído]() | Refere-se a uma lição, unidade ou seção que foi finalizado pelo usuário | Indica que o usuário completou e atingiu todos os objetivos relacionados. Pode resultar em recompensas e progresso na plataform | Finalizado, Completado, Feito |
| [Desabilitado]() | Indica que uma funcionalidade ou opção está temporariamente ou permanentemente inativa para o usuário | Falta de permissões, status da conta ou configurações do sistema. A funcionalidade pode não funcionar ou o usuário pode ser incapaz de interagir até que ela seja habilitada novamente | Inativo, Desativado, Indisponível |
| [Disponível]() | Estado de uma lição ou conteúdo que está acessível ao usuário | O usuário pode iniciar ou interagir com o conteúdo em questão sem restrições | Acessível, Aberto, Pronto |
| [Habilitado]() | Indica que uma funcionalidade ou opção está ativa e pronta para ser utilizada pelo usuário | O usuário tem permissão para acessar essa funcionalidade | Ativado, Disponível, Permitido |
| [Incompleto]() | Estado de uma lição ou habilidade que o usuário começou, mas não finalizou | Indica que o usuário precisa retornar para concluir uma atividade. Pode impactar o progresso geral ou o desbloqueio de novos conteúdos | Parcial, Não finalizado, Inacabado |
| [Logado]() | Estado em que o usuário está autenticado no sistema com suas credenciais | Permite ao usuário acessar funcionalidades e dados personalizados, como progresso, histórico e preferências | Autenticado, Conectado, Identificado |
| [Não-logado]() | o que o termo significa | O acesso a funcionalides e dados personalizados pode ser limitado ou indisponível | Desconectado, Anônimo, Deslogado |
| [Offline]() | Estado do aplicativo quando não há conexão com a internet, limitando certas funcionalidades | Funcionalidades que requerem conexão podem estar limitadas ou indisponíveis, mas o progresso pode ser sincronizado posteriormente | Sem conexão, Desconectado, Modo avião |
| [Premium]() | Recurso ou funcionalidade que está disponível apenas para assinantes da versão paga do Duolingo | Usuários Premium têm acesso a funcionalidades exclusivas, como remoção de anúncios, conteúdos adicionais e suporte prioritário | Atualizado, Alinhado, Harmonizado |
| [Sincronizado]() | Estado em que o progresso do usuário foi atualizado e salvo nos servidores do Duolingo | Garante que o usuário possa acessar suas informações atualizadas em qualquer dispositivo ou plataforma sem perda de dados | Atualizado, Alinhado, Harmonizado |



**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>


## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 15/08/2024 | 1.0 | Criação do documento, introdução e metodologia | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 15/08/2024 | 1.1 | Adição das tabelas de objetos, verbos e estados | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 16/08/2024 | 1.2 | Descrição dos objetos, verbos e estados | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |
| 16/08/2024 | 1.3 | Conclusão do léxico | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022)|

</center>
