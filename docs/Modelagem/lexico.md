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
| Nome do léxico | O que o termo significa | Efeito, uso ou ocorrência do termo na aplicação ou o efeito da aplicação sobre o termo | Termos diferentes que tem significado similar |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), 2024

</center>

Importante ressaltar que este documento, assim como outros do projeto, pode sofrer constantes mudanças ao decorrer que o contexto do aplicativo é estudado e novos termos são levantados.

## Vocábulo

<center>

### Tabela 03 - Objetos

| Símbolo | Noção | Impacto | Sinônimos |
|---------|-------|---------|-----------|
| <a id="aba">Aba</a> | Conjunto de elementos visuais logicamente relacionados podendo ser interativos ou não que ocupam a totalidade da tela do aparelho | As [abas](#aba) são usadas para organizar diferentes funcionalidades e conteúdos, como o [perfil](#perfil) do [usuário](#usuario), as [lições](#licao), as [divisões](#divisao) e as [configurações](#configuracoes). O uso de [abas](#aba) permite que o [usuário](#usuario) [navegue](#navegar) facilmente entre diferentes partes do aplicativo, mantendo uma experiência organizada e eficiente. | Guia, Seção, Página |
| <a id="bloqueio-de-ofensiva">Bloqueio de Ofensiva</a> | Um recurso que protege a sequência de dias consecutivos de estudo do [usuário](#usuario), conhecido como [ofensiva](#ofensiva), caso ele não consiga estudar em um dia específico | O [bloqueio de ofensiva](#bloqueio-de-ofensiva) pode ser [comprado](#comprar) para garantir que o [usuário](#usuario) não perca sua sequência, mantendo sua motivação e continuidade no [aprendizado](#aprender). Isso é particulamente útil para [usuários](#usuario) que valorizam sua consistência diária e buscar evitar interrupções | Proteção de Ofensiva, Escudo de Sequência, Backup de Ofensiva |
| <a id="bau">Baú</a> | Um item virtual no Duolingo que contém [recompensas](#recompensas), como [cristais](#cristais) ou outros recursos, que podem ser usados pelo [usuário](#usuario) na plataforma | Os [baús](#bau) são oferecidos como prêmios por alcançar certos marcos, vencer competições ou concluir [missões](#missao). Abrir um [baú](#bau) oferece ao [usuário](#usuario) uma sensação de surpresa e incentivo, reforçando o engajamento e o desejo de continuar progredindo | Caixa de Recompensas, Cofre, Tesouro |
| <a id="campo">Campo</a> | Uma área de entrada ou exibição de dados em uma [interface](#campo) de [usuário](#usuario), onde o [usuário](#usuario) pode inserir, selecionar ou visualizar informações específicas | Os [campos](#campo) facilitam a interação do [usuário](#usuario) com o sistema, permitindo a coleta e apresentação de dados de maneira estruturada | Área de entrada, Formulário, Box de entrada |
| <a id="colecoes">Coleções</a> | Reunião ordenada de objetos de mesmo interesse.  | Permite reunir um conjunto de informações importantes, como [erros](#erro), para o [aprendizado](#aprender) do [usuário](#usuario). | Conjuntos, repositórios, agrupamentos |
| <a id="configuracoes">Configurações</a> | Um conjunto de opções que permite ao [usuário](#usuario) [personalizar](#personalizar) e ajustar o funcionamento do aplicativo de acordo com suas preferências e necessidades. | As [configurações](#configuracoes) são fundamentais para oferecer uma experiência de [usuário](#usuario) personalizada, permitindo que cada indivíduo adapte o uso do aplicativo conforme suas necessidades e preferências pessoais.| Preferências, Ajustes, Opções |
| <a id="conta">Conta</a> | Registro de um [usuário](#usuario) em uma plataforma ou serviço online | Permite [personalizar](#personalizar) a experiência com base nas preferências do [usuário](#usuario) | Cadastro, login |
| <a id="conquistas">Conquistas</a> | Conjunto de metas alcançadas, metas estas definidas pelo Duolingo. | Auxilia o [usuário](#usuario) a construir um sentimento de sucesso e [progresso](#progresso) em seus estudos.  | Metas, objetivos |
| <a id="cristais">Cristais</a> | Moeda de troca do Duolingo, usada para realizar [compras](#comprar) dentro da plataforma | Os cristais permitem ao [usuário](#usuario) [comprar](#comprar) [vidas](#vida), [baús](#bau), [bloqueios de ofensiva](#bloqueio-de-ofensiva) e outros recursos que podem melhorar a experiência de [aprendizado](#aprender), desbloquear funcionalidades ou oferecer [recompensas](#recompensas). Servem como incentivo para o engajamento e [progresso](#progresso) contínuo no aplicativo | Moeda, Dinheiro, Crédito virtual |
| <a id="curso">Curso</a> | Um conjunto estruturado de [lições](#licao) e atividades projetadas para ensinar uma língua ou outro conteúdo de maneira progressiva e organizada. | Cada [curso](#curso) é composto por várias [seções](#secao), [unidades](#unidade) e [lições](#licao) que cobrem diferentes aspectos da língua, como gramática, vocabulário, e pronúncia. O [curso](#curso) é personalizado para o nível de proficiência do [usuário](#usuario) e pode incluir exercícios de escrita, leitura, escuta, e fala. | Programa de estudos, sequência de lições |
| <a id="desempenho">Desempenho</a> | O nível de eficiência e eficácia com que alguém executa uma tarefa ou atividade. | Avaliação do [progresso](#progresso) e sucesso do [usuário](#usuario) ao longo do [curso](#curso). Isso pode incluir a precisão nas respostas, a frequência de uso da plataforma, e a consistência na conclusão das [lições](#licao). O [desempenho](#desempenho) é medido por métricas como a quantidade de [lições](#licao) completadas, a manutenção de [ofensivas](#ofensiva), e o número de [pontos de experiência (XP)](#pontos-de-xp) acumulados. | Eficiência de aprendizado, Nível de habilidade |
| <a id="divisao">Divisão</a> | Refere-se a um nível ou categoria dentro das [ligas](#liga) de competição do Duolingo, onde os [usuários](#usuario) são agrupados com base em seu [desempenho](#desempenho) semanal | As [divisões](#divisao) determinam o grau de competição entre os [usuários](#usuario). Conforme o [usuário](#usuario) acumula mais [pontos ou experiência](#pontos-de-xp), ele pode avançar para [divisões](#divisao) superiores, enfrentando desafios mais difíceis e competidores mais habilidosos. Cada [divisão](#divisao) oferece uma sensação de progressão e pode fornecer [recompensas](#recompensas) ou reconhecimento para aqueles que alcançam os primeiros lugares | Nível, Categoria, Classe |
| <a id="erro">Erro</a> | Uma resposta ou ação incorreta que desvia do resultado esperado ou correto | Resposta incorreta fornecida durante uma [lição](#licao) ou [questão](#questao). | Falha, Engano |
| <a id="estrela">Estrela</a> | Refere-se a uma [recompensa](#recompensas) visual ou pontuação que o usuário recebe após completar com sucesso uma [lição](#licao) ou atividade no Duolingo | As [estrelas](#estrela) servem como um indicador de [desempenho](#desempenho) e sucesso, motivando o [usuário](#usuario) a alcançar um bom [desempenho](#desempenho) em cada conteúdo. Elas podem ser usadas para medir o [progresso](#progresso) dentro de uma [unidade](#unidade) e incentiver o [usuário](#usuario) a manter um alto nível de acerto | Pontuação, Emblema, Selo de aprovação |
| <a id="feedback">Feedback</a> | Informação retornada a uma pessoa sobre seu [desempenho](#desempenho), visando orientá-la na melhoria de suas ações ou decisões futuras. | Respostas fornecidas ao [usuário](#usuario) após a conclusão de cada exercício ou [lição](#licao). Esse [feedback](#feedback) pode ser positivo, reforçando uma resposta correta, ou corretivo, explicando por que uma resposta estava errada e como melhorá-la. |  Retorno, Avaliação, Comentário |
| <a id="formulario">Formulário</a> | Um documento ou [interface](#interface) digital contendo [campos](#campo) para preenchimento de informações específicas | Qualquer [interface](#interface) onde o [usuário](#usuario) precisa inserir informações ou responder a perguntas | Questionário, Ficha |
| <a id="idioma-padrao">Idioma padrão</a> | O idioma principal ou oficial utilizado em um determinado contexto, sistema ou plataforma. | Idioma que o [usuário](#usuario) seleciona como a língua base para a [interface](#interface) e para a [aprendizagem](#aprender) de outros idiomas. | Idioma base, Língua principal |
| <a id="interface">Interface</a> | A forma e o design de uma plataforma ou sistema com o qual os [usuários](#usuario) interagem para realizar tarefas ou acessar informações. |  Layout e aos elementos visuais da plataforma que os [usuários](#usuario) utilizam para aprender um idioma.  |  Layout, Tela. |
| <a id="licao">Lição</a> | Uma unidade de ensino focada em um tópico específico, com intuito de exercitar habilidades ou conhecimentos específicos. | Parte do [curso](#curso) que oferece uma série de exercícios e atividades destinadas a ensinar e reforçar um aspecto particular do idioma, como vocabulário, gramática ou pronúncia | Exercício |
| <a id="liga">Liga</a> | Um sistema de competição semanal onde os [usuários](#usuario) são agrupados em uma classificação com base em seu desempenho e quantidade de [pontos de experiência](#pontos-de-xp) | As [ligas](#liga) incentivam a competição saudável entre [usuários](#usuario), promovendo o [aprendizado](#aprender) contínuo ao [recompensar](#recompensas) aqueles que obtêm as melhoras classificações com prêmios, como [cristais](#cristais) e posições em [divisões](#divisao) superiores. Subir de [liga](#liga) é uma forma de reconhecimento dentro da comunidade do Duolingo | Classificação, Torneio, Ranking |
| <a id="loja">Loja</a> | Um local, físico ou virtual, onde produtos ou serviços são oferecidos para venda | Seção dentro da plataforma onde os [usuários](#usuario) podem [comprar](#comprar) itens virtuais usando a moeda do Duolingo ([cristais](#cristais)) | Seção de compras, Comércio digital |
| <a id="missao">Missão</a> | Uma tarefa ou objetivo específico que deve ser completado para alcançar um determinado resultado ou recompensa | Objetivos ou desafios que os [usuários](#usuario) devem completar dentro da plataforma | Desafio, objetivo, tarefa |
| <a id="nivel">Nível</a> | Uma posição ou estágio em uma escala de progressão ou habilidade. | Conjunto de [lições](#licao) abordam o mesmo tema | Grau |
| <a id="notificacao">Notificação</a> | Uma mensagem ou alerta que informa o [usuário](#usuario) sobre eventos ou atualizações importantes | Aviso enviado para informar os [usuários](#usuario) sobre novos eventos, atualizações, ou ações relacionadas à sua [conta](#conta). | Aviso, mensagem |
| <a id="ofensiva">Ofensiva</a> | Uma ação ou comportamento que é agressivo | Sequência ininterrupta de dias que o [usuário](#usuario) acessou o Duolingo | Sequência, continuidade |
| <a id="perfil">Perfil</a> | Conjunto de informações e características que descrevem uma pessoa ou entidade em um sistema ou plataforma | Página individual do [usuário](#usuario) que contém informações pessoais, [configurações](#configuracoes) e dados de [progresso](#progresso) | Página de usuário, identidade digital |
| <a id="pontos-de-xp">Pontos de XP</a> | Medida quantificável de [progresso](#progresso) ou experiência acumulada em um sistema de aprendizado ou jogo. | Quantificar o [progresso](#progresso) e o engajamento do [usuário](#usuario) na plataforma. | Pontuação de aprendizado |
| <a id="pop-up">Pop-up</a> | Uma janela ou mensagem que aparece temporariamente sobre a [interface](#interface) principal de um aplicativo ou site para fornecer informações ou interações adicionais. | Janela ou caixa de diálogo que surge sobre a [interface](#interface) principal para informar o usuário sobre atualizações, dicas, [recompensas](#recompensas), ou ações necessárias. | Caixa de diálogo |
| <a id="progresso">Progresso</a> | Refere-se ao avanço ou desenvolvimento do [usuário](#usuario) em seu [aprendizado](#aprender) de idiomas dentro da plataforma, medido por fatores como a conclusão de [lições](#licao), acumulação de [XP](#pontos-de-xp), e desbloqueio de [níveis](#nivel) e [unidades](#unidade). | O [progresso](#progresso) é visualizado através da [trilha de aprendizado](#trilha-de-aprendizado), [estrelas](#estrela), e outras métricas que incentivam o [usuário](#usuario) a continuar aprendendo. É uma representação tangível do empenho e da dedicação do [usuário](#usuario), motivando-o a atingir novos marcos e metas pessoais. | Avanço, Desenvolvimento, Evolução. |
| <a id="questao">Questão</a> | Uma pergunta ou problema que deve ser respondido ou resolvido. | Exercício ou item de prática que testa o conhecimento do usuário sobre o idioma em estudo. | Exercício |
| <a id="recompensas">Recompensas</a> | Benefícios ou prêmios recebidos em troca de alcançar objetivos ou completar [lições](#licao). | Incentivos dados aos [usuários](#usuario) por atingir marcos ou completar atividades no processo de [aprendizado](#aprender). | Prêmios, Incentivos |
| <a id="secao">Seção</a> | Um conjunto de [unidades](#unidade) temáticas dentro de um [curso](#curso) no Duolingo, agrupando conteúdos relacionados que o [usuário](#usuario) deve completar para avançar no [aprendizado](#aprender) do idioma | As [seções](#secao) estruturam o [curso](#curso) em partes gerenciáveis, ajudando o [usuário](#usuario) a focar em áreas específicas do idioma antes de progredir para tópicos mais avançados. Completar uma seção frequentemente resulta em [desbloquear](#desbloquear) novas áreas do [curso](#curso) | Módulo, Capítulo |
| <a id="termos-de-servico">Termos de Serviço</a> | Conjunto de regras e diretrizes que regulam o uso de um serviço ou plataforma, definindo direitos e responsabilidades dos [usuários](#usuario) e do provedor. | Documento legal que estabelece as condições sob as quais os [usuários](#usuario) podem acessar e utilizar a plataforma. |  Condições de uso, políticas de uso |
| <a id="trilha-de-aprendizado">Trilha de Aprendizado</a> | Marcação visual da trilha de aprendizagem, [lições](#licao) [concluidas](#concluido), de um [usuário](#usuario) do Duolingo  | Facilita a observação do [progresso](#progresso) individual | Trilha de Progresso, Jornada de Aprendizado |
| <a id="unidade">Unidade</a> | Divisão de conteúdo acadêmico que agrega diversos [níveis](#nivel) com um conteúdo específico, formando uma parte estruturada e sequencial do [curso](#curso) de idiomas | A [unidade](#unidade) organiza o aprendizado em blocos temáticos, permitindo ao [usuário](#usuario) focar em tópicos específicos e construir seu conhecimento de forma progressiva. Completar uma [unidade](#unidade) geralmente implica em [desbloquear](#desbloquear) novos conteúdos e [níveis](#nivel) no [curso](#curso) | Capítulo, Seção, Módulo |
| <a id="usuario">Usuário</a> | Pessoa que utiliza um serviço, aplicativo ou sistema para realizar atividades específicas. | Alguém que se [cadastra](#cadastrar) na plataforma para aprender um novo idioma. | Membro, Cliente |
| <a id="vida">Vida</a> | Um recurso ou unidade que representa a quantidade de tentativas ou ações que um [usuário](#usuario) pode realizar antes de precisar esperar para recuperar ou renovar esse recurso. | Recurso que limita o número de [erros](#erro) que um [usuário](#usuario) pode cometer em exercícios antes de ter que aguardar um período de tempo ou realizar ações específicas para recuperar [vidas](#vida) | Tentativas, Chances |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), [Guilherme Silva Dutra](https://github.com/GuiDutra21), 2024

</center>

<center>

### Tabela 04 - Verbos

| Símbolo | Noção | Impacto | Sinônimos |
|---------|-------|---------|-----------|
| <a id="aprender">Aprender</a> | Refere-se ao ato de adquirir conhecimento ou habilidade em um novo idioma através de [lições](#licao), exercícios e atividades na plataforma | O objetivo central do Duolingo, onde o [usuário](#usuario) progride em seu [aprendizado](#aprender) de idiomas por meio de conteúdo interativo e [feedback](#feedback) instantâneo | Estudar, Absorver, Dominar |
| <a id="cadastrar">Cadastrar</a> | Ato de criar uma nova [conta](#conta) em plataformas e serviços | Permite que o [usuário](#usuario) usufrua das funcionalidades da plataforma/serviço | Registrar |
| <a id="competir">Competir</a> | Refere-se à participação do [usuário](#usuario) em [ligas](#liga), desafios ou competições dentro da plataforma Duolingo, visando se destacar entre outros [usuários](#usuario) em termos de progresso ou pontos | Promove a motivação do [usuário](#usuario) ao engajá-lo em uma dinâmica de competição saudável, incentivando o uso contínuo e o avanço no aprendizado | Disputar, Concorrer, Competição |
| <a id="comprar">Comprar</a> | Trocar [cristais](#cristais) por itens na loja | No Duolingo, é utilizado para fornecer itens que melhoram a experiência do [usuário](#usuario) | Escambo, Troca, Obter |
| <a id="configurar">Configurar</a> | Ajustar preferências pessoais, como notificações, idioma, ou aparência do aplicativo | Permite ao [usuário](#usuario) [personalizar](#personalizar) a experiência de uso, tornando a plataforma mais adequada às suas necessidades e hábitos | Ajustar, Personalizar, Definir |
| <a id="desbloquear">Desbloquear</a> | Ato de tornar acessível um conteúdo ou funcionalidade que estava inicialmente restrito ou inacessível | Incentiva o [progresso](#progresso), recompensando o [usuário](#usuario) por completar [lições](#licao) ou alcançar metas, e permitindo o acesso a novos desafios ou áreas de aprendizado | Liberar, Acessar, Abrir |
| <a id="deslogar">Deslogar</a> | Ação de sair da [conta](#conta) do [usuário](#usuario), encerrando a sessão atual na plataforma | Desconecta o [usuário](#usuario), protegendo suas informações pessoais e liberando o dispositivo para outro [usuário](#usuario) | Sair, Desconectar, Encerrar sessão |
| <a id="excluir">Excluir</a> | Remover permanentemente uma [conta](#conta), dado, ou [progresso](#progresso) do [usuário](#usuario) na plataforma | Pode ser usado para apagar uma [conta](#conta) ou remover um conteúdo específico que o [usuário](#usuario) não deseja mais manter | Deletar, Remover, Apagar |
| <a id="logar">Logar</a> | Ação de autenticar-se na plataforma, inserindo credenciais para acessar uma [conta](#conta) | Permite ao [usuário](#usuario) acessar seu [perfil](#perfil), [progresso](#progresso), e configurações pessoais | Entrar, Conectar, Autenticar-se |
| <a id="navegar">Navegar</a> | Explorar as diferentes seções, funcionalidades e conteúdos disponíveis na plataforma | O [usuário](#usuario) pode percorrer diferentes áreas do aplicativo para acessar [lições](#licao), [perfis](#perfil), [configurações](#configuracoes), entre outros | Explorar, Percorrer, Acessar |
| <a id="praticar">Praticar</a> | Reforçar o [aprendizado](#aprender) de idiomas por meio de atividades ou exercícios repetitivos | Auxilia na fixação de conhecimento e na melhoria da fluência, com exercícios voltados para áreas que o [usuário](#usuario) precisa aprimorar | Treinar, Exercitar, Repetir |
| <a id="personalizar">Personalizar</a> | Adaptar a experiência de [aprendizado](#aprender) ou o ambiente da aplicação conforme as preferências do [usuário](#usuario) | O [usuário](#usuario) pode alterar [configurações](#configuracoes) e escolher opções que tornem o uso da plataforma mais alinhado com suas necessidades e estilo de [aprendizado](#aprender) | Customizar, Ajustar, Modificar |
| <a id="reportar">Reportar</a> | Informar ou registrar um problema, erro ou conteúdo inadequado encontrado na plataforma | Melhora a qualidade da experiência ao permitir que os [usuários](#usuario) comuniquem problemas que possam ser corrigidos pela equipe de suporte | Denunciar, Informar, Relatar |
| <a id="revisar">Revisar</a> | Revisitar [lições](#licao) ou conteúdo já aprendido para reforçar o conhecimento e garantir a retenção | Ajuda a solidificar o aprendizado e identificar áreas onde o [usuário](#usuario) pode ter dificuldades | Repassar, Relembrar, Rever |
| <a id="salvar">Salvar</a> | Guardar [progresso](#progresso), [configurações](#configuracoes) ou dados do [perfil](#perfil) do [usuário](#usuario) | Garante que as mudanças feitas ou o [progresso](#progresso) alcançado não sejam perdidos e possam ser acessados posteriormente | Armazenar, Guardar, Gravar |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>

<center>

### Tabela 05 - Estados

| Símbolo | Noção | Impacto | Sinônimos |
|---------|-------|---------|-----------|
| <a id="bloqueado">Bloqueado</a> | Indicação que um conteúdo, [lição](#licao) ou função não está acessível ao [usuário](#usuario) no momento | O [usuário](#usuario) deve concluir pré-requisitos para desbloquear certo conteúdo. Pode ser utilizado para manter o engajamento, incentivando o [progresso](#progresso) dentro da plataforma | Restringido, Inacessível, Fechado |
| <a id="concluido">Concluído</a> | Refere-se a uma [lição](#licao), [unidade](#unidade) ou [seção](#secao) que foi finalizada pelo [usuário](#usuario) | Indica que o usuário completou e atingiu todos os objetivos relacionados. Pode resultar em [recompensas](#recompensas) e [progresso](#progresso) na plataforma | Finalizado, Completado, Feito |
| <a id="desabilitado">Desabilitado</a> | Indica que uma funcionalidade ou opção está temporariamente ou permanentemente inativa para o [usuário](#usuario) | Falta de permissões, status da [conta](#conta) ou [configurações](#configuracoes) do sistema. A funcionalidade pode não funcionar ou o [usuário](#usuario) pode ser incapaz de interagir até que ela seja [habilitada](#habilitado) novamente | Inativo, Desativado, Indisponível |
| <a id="disponivel">Disponível</a> | Estado de uma [lição](#licao), [unidade](#unidade) ou [seção](#secao) que está acessível ao [usuário](#usuario) | O [usuário](#usuario) pode iniciar ou interagir com o conteúdo em questão sem restrições | Acessível, Aberto, Pronto |
| <a id="habilitado">Habilitado</a> | Indica que uma funcionalidade ou opção está ativa e pronta para ser utilizada pelo [usuário](#usuario) | O [usuário](#usuario) tem permissão para acessar essa funcionalidade | Ativado, Disponível, Permitido |
| <a id="incompleto">Incompleto</a> | Estado de uma [lição](#licao) ou [missão](#missao) que o [usuário](#usuario) começou, mas não finalizou | Indica que o [usuário](#usuario) precisa retornar para concluir uma atividade. Pode impactar o [progresso](#progresso) geral ou o desbloqueio de novos conteúdos | Parcial, Não finalizado, Inacabado |
| <a id="logado">Logado</a> | Estado em que o [usuário](#usuario) está autenticado no sistema com suas credenciais | Permite ao usuário acessar funcionalidades e dados personalizados, como [progresso](#progresso), [coleções](#colecoes) e preferências | Autenticado, Conectado, Identificado |
| <a id="nao-logado">Não-logado</a> | Estado em que o [usuário](#usuario) não está autenticado no sistema com suas credenciais | O acesso a funcionalidades e dados personalizados pode ser limitado ou indisponível | Desconectado, Anônimo, Deslogado |
| <a id="offline">Offline</a> | Estado do aplicativo quando não há conexão com a internet, limitando certas funcionalidades | Funcionalidades que requerem conexão podem estar limitadas ou indisponíveis, mas o [progresso](#progresso) pode ser [sincronizado](#sincronizado) posteriormente | Sem conexão, Desconectado, Modo avião |
| <a id="premium">Premium</a> | Recurso ou funcionalidade que está disponível apenas para assinantes da versão paga do Duolingo | [Usuários](#usuario) Premium têm acesso a funcionalidades exclusivas, como remoção de anúncios, conteúdos adicionais e suporte prioritário | Atualizado, Alinhado, Harmonizado |
| <a id="sincronizado">Sincronizado</a> | Estado em que o [progresso](#progresso) do [usuário](#usuario) foi atualizado e [salvo](#salvar) nos servidores do Duolingo | Garante que o [usuário](#usuario) possa acessar suas informações atualizadas em qualquer dispositivo ou plataforma sem perda de dados | Atualizado, Alinhado, Harmonizado |

**Autores**: [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), 2024

</center>


## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 15/08/2024 | 1.0 | Criação do documento, introdução e metodologia | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 15/08/2024 | 1.1 | Adição das tabelas de objetos, verbos e estados | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 16/08/2024 | 1.2 | Descrição dos objetos, verbos e estados | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Julio Roberto](https://github.com/JulioR2022), [Guilherme Silva Dutra](https://github.com/GuiDutra21) |
| 17/08/2024 | 1.3 | Adicionando links e alguns termos | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |
| 07/09/2024 | 1.4 | Adicionando verbo "competir" | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |

</center>
