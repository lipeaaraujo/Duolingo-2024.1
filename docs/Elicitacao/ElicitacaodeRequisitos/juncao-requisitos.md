# Junção dos Requisitos

Este documento agrupa todos os requisitos elicitados no projeto, abrangendo todas as técnicas de elicitação utilizadas, brainstorming, observação e introspecção, storytelling e protocolo de análise.

## Requisitos Elicitados

### Legenda para as Tabelas 01 e 02:

- **RFx**: Requisito Funcional n° x
- **RNFx**: Requisito Não-Funcional n° x
- **BSx**: Requisito n° x da técnica de Brainstorming
- **MMx**: Requisito n° x da técnica do Mapa Mental
- **STx**: Requisito n° x da técnica de Storytelling
- **APx**: Requisito n° x da técnica de Análise de Protocolo

<center>

### Tabela 01 - Requisitos

| Tipo | ID | Rastreabilidade | Descrição |
| - | - | - | - |
| RF01 | 01 | [BS01](brainstorm.md#tabela-01-requisitos-funcionais), [ST01](storytelling.md#tabela-01-requisitos-funcionais), [MM01](observacao.md#tabela-01-requisitos-funcionais) | O aplicativo deve ter uma variedade de cursos e idiomas |
| RF02 | 02 | [ST02](storytelling.md#tabela-01-requisitos-funcionais) | O usuário deve poder refazer as lições |
| RF03 | 03 | [BS02](brainstorm.md#tabela-01-requisitos-funcionais), [ST03](storytelling.md#tabela-01-requisitos-funcionais) | O aplicativo deve ter um sistema de revisão de conteúdo |
| RF04 | 04 | [ST09](storytelling.md#tabela-01-requisitos-funcionais), [MM06](observacao.md#tabela-01-requisitos-funcionais), [AP12](protocolo.md#tabela-01-requisitos-funcionais) | O aplicativo deve permitir o cadastro e gerenciamento de contas |
| RF05 | 05 | [MM07](observacao.md#tabela-01-requisitos-funcionais) | O perfil do usuário deve exibir informações importantes |
| RF06 | 06 | [MM11](observacao.md#tabela-01-requisitos-funcionais) | O aplicativo deve exibir as coleções de erros, palavras aprendidas e histórias estudadas |
| RF07 | 07 | [BS03](brainstorm.md#tabela-01-requisitos-funcionais), [MM03](observacao.md#tabela-01-requisitos-funcionais) | Os cursos oferecidos devem ser divididos em seções |
| RF08 | 08 | [BS04](brainstorm.md#tabela-01-requisitos-funcionais), [MM02](observacao.md#tabela-01-requisitos-funcionais) | As seções devem estar divididas em unidades |
| RF09 | 09 | [BS05](brainstorm.md#tabela-01-requisitos-funcionais), [MM04](observacao.md#tabela-01-requisitos-funcionais) | As unidades devem estar divididas em lições |
| RF10 | 10 | [BS06](brainstorm.md#tabela-01-requisitos-funcionais), [ST01](storytelling.md#tabela-01-requisitos-funcionais), [AP01](protocolo.md#tabela-01-requisitos-funcionais) | As lições devem abranger questões de fala, de escrita, de leitura e de escuta |
| RF11 | 11 | [BS07](brainstorm.md#tabela-01-requisitos-funcionais), [ST08](storytelling.md#tabela-01-requisitos-funcionais), [MM05](observacao.md#tabela-01-requisitos-funcionais), [AP04](protocolo.md#tabela-01-requisitos-funcionais), [AP07](protocolo.md#tabela-01-requisitos-funcionais) | O aplicativo deve dar feedback durante a realização das questões |
| RF12 | 12 | [BS08](brainstorm.md#tabela-01-requisitos-funcionais), [ST10](storytelling.md#tabela-01-requisitos-funcionais) | O usuário deve ser capaz de monitorar seu progresso no curso |
| RF13 | 13 | [BS09](brainstorm.md#tabela-01-requisitos-funcionais) | O usuário deve receber notificações |
| RF14 | 14 | [BS10](brainstorm.md#tabela-01-requisitos-funcionais), [MM09](observacao.md#tabela-01-requisitos-funcionais), [AP10](protocolo.md#tabela-01-requisitos-funcionais) | O aplicativo deve oferecer um sistema de missões ao usuário |
| RF15 | 15 | [BS11](brainstorm.md#tabela-01-requisitos-funcionais), [MM10](observacao.md#tabela-01-requisitos-funcionais) | O aplicativo deve ter um sistema de recompensas |
| RF16 | 16 | [BS12](brainstorm.md#tabela-01-requisitos-funcionais), [MM14](observacao.md#tabela-01-requisitos-funcionais), [ST07](storytelling.md#tabela-01-requisitos-funcionais), [AP09](protocolo.md#tabela-01-requisitos-funcionais) | O aplicativo deve ter um sistema de competição |
| RF17 | 17 | [BS13](brainstorm.md#tabela-01-requisitos-funcionais), [ST04](storytelling.md#tabela-01-requisitos-funcionais), [ST05](storytelling.md#tabela-01-requisitos-funcionais), [MM08](observacao.md#tabela-01-requisitos-funcionais), [AP13](protocolo.md#tabela-01-requisitos-funcionais) | O aplicativo deve ter um sistema de amizades |
| RF18 | 18 | [BS14](brainstorm.md#tabela-01-requisitos-funcionais), [MM12](observacao.md#tabela-01-requisitos-funcionais), [AP08](protocolo.md#tabela-01-requisitos-funcionais) | O aplicativo deve ter um sistema de controle da frequência de estudo do usuário |
| RF19 | 19 | [BS15](brainstorm.md#tabela-01-requisitos-funcionais) | O aplicativo deve ser personalizável as necessidades do usuário |
| RF20 | 20 | [ST11](storytelling.md#tabela-01-requisitos-funcionais) | Permitir o usuário encerrar uma lição prematuramente |
| RF21 | 21 | [MM17](observacao.md#tabela-01-requisitos-funcionais) | Permite a sincronização com a conta de outras plataformas |
| RF22 | 22 | [MM13](observacao.md#tabela-01-requisitos-funcionais) | O aplicativo oferece conquistas para marcos específicos no aprendizado |
| RF23 | 23 | [MM15](observacao.md#tabela-01-requisitos-funcionais), [AP12](protocolo.md#tabela-01-requisitos-funcionais) | O aplicativo deve fornecer uma loja |
| RF24 | 24 | [MM16](observacao.md#tabela-01-requisitos-funcionais) | O aplicativo deve permitir a compra de recursos a partir de dinheiro real |
| RF25 | 25 | [AP02](protocolo.md#tabela-01-requisitos-funcionais) | O usuário pode reproduzir os áudios quantos vezes desejar |
| RF26 | 26 | [AP03](protocolo.md#tabela-01-requisitos-funcionais) | Permite alterar a velocidade de reprodução de áudios |
| RF27 | 27 | [AP05](protocolo.md#tabela-01-requisitos-funcionais) | Novas palavras devem ser visualmente destacas e deve-se mostrar a sua tradução |
| RF28 | 28 | [AP06](protocolo.md#tabela-01-requisitos-funcionais) | Permite pular ou adiar questões de fala e escuta |
| RF29 | 29 | [AP11](protocolo.md#tabela-01-requisitos-funcionais) | Permite o compartilhamento do perfil e de conquistas |
| RF30 | 30 | [MM18](observacao.md#tabela-01-requisitos-funcionais) | O usuário deve ser capaz de gerenciar o seu perfil |
| RF31 | 31 | [MM19](observacao.md#tabela-01-requisitos-funcionais) | Um nível deve ser dívido em lições |
| RF32 | 32 | [MM20](observacao.md#tabela-01-requisitos-funcionais) | O usuário deve ser capaz de reportar um problema |
| RF33 | 33 | [MM21](observacao.md#tabela-01-requisitos-funcionais) | O aplicativo deve fornecer um conjunto de notícias/novidades para o usuario |
| RF34 | 34 | [MM22](observacao.md#tabela-01-requisitos-funcionais) | O aplicativo permite ao usuário utilizar os seus respectivos itens |
| RNF35 | 35 | [BS16](brainstorm.md#tabela-02-requisitos-nao-funcionais), [ST13](storytelling.md#tabela-02-requisitos-nao-funcionais) | As lições do aplicativo devem ser interativas |
| RNF36 | 36 | [BS17](brainstorm.md#tabela-02-requisitos-nao-funcionais), [MM30](observacao.md#tabela-02-requisitos-nao-funcionais) | Deve existir um feedback imediato após a realização de uma questão |
| RNF37 | 37 | [BS18](brainstorm.md#tabela-02-requisitos-nao-funcionais), [ST16](storytelling.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve possuir funcionalidades no modo off-line |
| RNF38 | 38 | [BS19](brainstorm.md#tabela-02-requisitos-nao-funcionais), [ST18](storytelling.md#tabela-02-requisitos-nao-funcionais), [MM23](observacao.md#tabela-02-requisitos-nao-funcionais), [AP17](protocolo.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve ser gamificado |
| RNF39 | 39 | [BS20](brainstorm.md#tabela-02-requisitos-nao-funcionais) | A maioria das funcionalidades devem ser gratuitas |
| RNF40 | 40 | [BS21](brainstorm.md#tabela-02-requisitos-nao-funcionais), [MM25](observacao.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve suportar muitos usuários simultaneamente |
| RNF41 | 41 | [BS22](brainstorm.md#tabela-02-requisitos-nao-funcionais), [MM28](observacao.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve apresentar uma navegação simples |
| RNF42 | 42 | [BS23](brainstorm.md#tabela-02-requisitos-nao-funcionais), [MM27](observacao.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve apresentar uma interface intuitiva |
| RNF43 | 43 | [BS24](brainstorm.md#tabela-02-requisitos-nao-funcionais), [ST12](storytelling.md#tabela-02-requisitos-nao-funcionais) | As lições devem ser curtas e objetivas |
| RNF44 | 44 | [BS26](brainstorm.md#tabela-02-requisitos-nao-funcionais), [ST14](storytelling.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve estar disponível 24 horas diárias, 7 dias por semana e em qualquer local |
| RNF45 | 45 | [ST15](storytelling.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve estar disponível em diversos tipos de dispositivos, como exemplo, Androids e IOSs|
| RNF46 | 46 | [ST17](storytelling.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve ser acessível para qualquer idade |
| RNF47 | 47 | [ST19](storytelling.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve estar disponível em diversos idiomas |
| RNF48 | 48 | [ST20](storytelling.md#tabela-02-requisitos-nao-funcionais) | O aplicativo deve permitir a sincronização de contas em dispositivos diferentes |
| RNF49 | 49 | [MM26](observacao.md#tabela-02-requisitos-nao-funcionais) | As transações dentro da loja devem ser seguras |
| RNF50 | 50 | [MM29](observacao.md#tabela-02-requisitos-nao-funcionais), [AP15](protocolo.md#tabela-02-requisitos-nao-funcionais) | As lições devem ter conteúdo confiável e verificado |
| RNF51 | 51 | [AP14](protocolo.md#tabela-02-requisitos-nao-funcionais) | As mensagens de feedback devem ser claras e objetivas |
| RNF52 | 52 | [AP16](protocolo.md#tabela-02-requisitos-nao-funcionais) | O design do aplicativo deve ser padronizado |
| RNF53 | 53 | [MM32](observacao.md#tabela-02-requisitos-nao-funcionais) | O aplicativo não deve ocupar mais do que 500 MB de armazenamento |
| RNF54 | 54 | [MM35](observacao.md#tabela-02-requisitos-nao-funcionais)  | As resposta a ações do usuário não podem ultrapassar 1,5 segundo |
| RNF55 | 55 | [MM36](observacao.md#tabela-02-requisitos-nao-funcionais)  | O sistema deve suportar versões anteriores |
| RNF56 | 56 | [MM37](observacao.md#tabela-02-requisitos-nao-funcionais)  | O design deve ser responsivo |
| RNF57 | 57 | [MM38](observacao.md#tabela-02-requisitos-nao-funcionais)  | As ilustrações e animações devem seguir um estilo coerente com a identidade visual do aplicativo |

</center>

## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 01/08/2024 | 1.0 | Criação do documento | [Guilherme Silva Dutra](https://github.com/GuiDutra21), [Julio Roberto](https://github.com/JulioR2022), [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Raquel Ferreira Andrade](https://github.com/raquel-andrade) |
| 01/08/2024 | 1.1 | Adição da legenda das tabelas | [Guilherme Silva Dutra](https://github.com/GuiDutra21), [Raquel Ferreira Andrade](https://github.com/raquel-andrade) |
| 19/08/2024 | 1.2 | Ajustes no documento | [Guilherme Silva Dutra](https://github.com/GuiDutra21), [Julio Roberto](https://github.com/JulioR2022)|

</center>