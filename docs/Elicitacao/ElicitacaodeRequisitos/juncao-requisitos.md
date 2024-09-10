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
| RF01 | 01 | [BS01](brainstorm.md#bs01), [ST01](storytelling.md#st01), [MM01](observacao.md#mm01) | O aplicativo deve ter uma variedade de cursos e idiomas |
| RF02 | 02 | [ST02](storytelling.md#st02) | O usuário deve poder refazer as lições |
| RF03 | 03 | [BS02](brainstorm.md#bs02), [ST03](storytelling.md#st03) | O aplicativo deve ter um sistema de revisão de conteúdo |
| RF04 | 04 | [ST09](storytelling.md#st09), [MM06](observacao.md#mm06) | O aplicativo deve permitir o cadastro e gerenciamento de contas |
| RF05 | 05 | [MM07](observacao.md#mm07) | O perfil do usuário deve exibir informações importantes |
| RF06 | 06 | [MM11](observacao.md#mm11) | O aplicativo deve exibir as coleções de erros, palavras aprendidas e histórias estudadas |
| RF07 | 07 | [BS03](brainstorm.md#bs03), [MM03](observacao.md#mm03) | Os cursos oferecidos devem ser divididos em seções |
| RF08 | 08 | [BS04](brainstorm.md#bs04), [MM02](observacao.md#mm02) | As seções devem estar divididas em unidades |
| RF09 | 09 | [BS05](brainstorm.md#bs05), [MM04](observacao.md#mm04) | As unidades devem estar divididas em lições |
| RF10 | 10 | [BS06](brainstorm.md#bs06), [ST01](storytelling.md#st01), [AP01](protocolo.md#ap01) | As lições devem abranger questões de fala, de escrita, de leitura e de escuta |
| RF11 | 11 | [BS07](brainstorm.md#bs07), [ST08](storytelling.md#st08), [MM05](observacao.md#mm05), [AP04](protocolo.md#ap04), [AP07](protocolo.md#ap07) | O aplicativo deve dar feedback durante a realização das questões |
| RF12 | 12 | [BS08](brainstorm.md#bs08), [ST10](storytelling.md#st10) | O usuário deve ser capaz de monitorar seu progresso no curso |
| RF13 | 13 | [BS09](brainstorm.md#bs09) | O usuário deve receber notificações |
| RF14 | 14 | [BS10](brainstorm.md#bs10), [MM09](observacao.md#mm09), [AP10](protocolo.md#ap10) | O aplicativo deve oferecer um sistema de missões ao usuário |
| RF15 | 15 | [BS11](brainstorm.md#bs11), [MM10](observacao.md#mm10) | O aplicativo deve ter um sistema de recompensas |
| RF16 | 16 | [BS12](brainstorm.md#bs12), [MM14](observacao.md#mm14), [ST07](storytelling.md#st07), [AP09](protocolo.md#ap09) | O aplicativo deve ter um sistema de competição |
| RF17 | 17 | [BS13](brainstorm.md#bs13), [ST04](storytelling.md#st04), [ST05](storytelling.md#st05), [MM08](observacao.md#mm08), [AP13](protocolo.md#ap13) | O aplicativo deve ter um sistema de amizades |
| RF18 | 18 | [BS14](brainstorm.md#bs14), [MM12](observacao.md#mm12), [AP08](protocolo.md#ap08) | O aplicativo deve ter um sistema de controle da frequência de estudo do usuário |
| RF19 | 19 | [BS15](brainstorm.md#bs15) | O aplicativo deve ser personalizável as necessidades do usuário |
| RF20 | 20 | [ST11](storytelling.md#st11) | Permitir o usuário encerrar uma lição prematuramente |
| RF21 | 21 | [MM17](observacao.md#mm17) | Permite a sincronização com a conta de outras plataformas |
| RF22 | 22 | [MM13](observacao.md#mm13) | O aplicativo oferece conquistas para marcos específicos no aprendizado |
| RF23 | 23 | [MM15](observacao.md#mm15), [AP12](protocolo.md#ap12) | O aplicativo deve fornecer uma loja |
| RF24 | 24 | [MM16](observacao.md#mm16) | O aplicativo deve permitir a compra de recursos a partir de dinheiro real |
| RF25 | 25 | [AP02](protocolo.md#ap02) | O usuário pode reproduzir os áudios quantos vezes desejar |
| RF26 | 26 | [AP03](protocolo.md#ap03) | Permite alterar a velocidade de reprodução de áudios |
| RF27 | 27 | [AP05](protocolo.md#ap05) | Novas palavras devem ser visualmente destacas e deve-se mostrar a sua tradução |
| RF28 | 28 | [AP06](protocolo.md#ap06) | Permite pular ou adiar questões de fala e escuta |
| RF29 | 29 | [AP11](protocolo.md#ap11) | Permite o compartilhamento do perfil e de conquistas |
| RF30 | 30 | [MM18](observacao.md#mm18) | O usuário deve ser capaz de gerenciar o seu perfil |
| RF31 | 31 | [MM19](observacao.md#mm19) | Um nível deve ser dívido em lições |
| RF32 | 32 | [MM20](observacao.md#mm20) | O usuário deve ser capaz de reportar um problema |
| RF33 | 33 | [MM21](observacao.md#mm21) | O aplicativo deve fornecer um conjunto de notícias/novidades para o usuario |
| RF34 | 34 | [MM22](observacao.md#mm22) | O aplicativo permite ao usuário utilizar os seus respectivos itens |
| RNF35 | 35 | [BS16](brainstorm.md#bs16), [ST13](storytelling.md#st13) | As lições do aplicativo devem ser interativas |
| RNF36 | 36 | [BS17](brainstorm.md#bs17), [MM30](observacao.md#mm30) | Deve existir um feedback imediato após a realização de uma questão |
| RNF37 | 37 | [BS18](brainstorm.md#bs18), [ST16](storytelling.md#st16) | O aplicativo deve possuir funcionalidades no modo off-line |
| RNF38 | 38 | [BS19](brainstorm.md#bs19), [ST18](storytelling.md#st18), [MM23](observacao.md#mm23), [AP17](protocolo.md#ap17) | O aplicativo deve ser gamificado |
| RNF39 | 39 | [BS20](brainstorm.md#bs20) | A maioria das funcionalidades devem ser gratuitas |
| RNF40 | 40 | [BS21](brainstorm.md#bs21), [MM25](observacao.md#mm25) | O aplicativo deve suportar muitos usuários simultaneamente |
| RNF41 | 41 | [BS22](brainstorm.md#bs22), [MM28](observacao.md#mm28) | O aplicativo deve apresentar uma navegação simples |
| RNF42 | 42 | [BS23](brainstorm.md#bs23), [MM27](observacao.md#mm27) | O aplicativo deve apresentar uma interface intuitiva |
| RNF43 | 43 | [BS24](brainstorm.md#bs24), [ST12](storytelling.md#st12) | As lições devem ser curtas e objetivas |
| RNF44 | 44 | [BS26](brainstorm.md#bs26), [ST14](storytelling.md#st14) | O aplicativo deve estar disponível 24 horas diárias, 7 dias por semana e em qualquer local |
| RNF45 | 45 | [ST15](storytelling.md#st15) | O aplicativo deve estar disponível em diversos tipos de dispositivos, como exemplo, Androids e IOSs|
| RNF46 | 46 | [ST17](storytelling.md#st17) | O aplicativo deve ser acessível para qualquer idade |
| RNF47 | 47 | [ST19](storytelling.md#st19) | O aplicativo deve estar disponível em diversos idiomas |
| RNF48 | 48 | [ST20](storytelling.md#st20) | O aplicativo deve permitir a sincronização de contas em dispositivos diferentes |
| RNF49 | 49 | [MM26](observacao.md#mm26) | As transações dentro da loja devem ser seguras |
| RNF50 | 50 | [MM29](observacao.md#mm29), [AP15](protocolo.md#ap15) | As lições devem ter conteúdo confiável e verificado |
| RNF51 | 51 | [AP14](protocolo.md#ap14) | As mensagens de feedback devem ser claras e objetivas |
| RNF52 | 52 | [AP16](protocolo.md#ap16) | O design do aplicativo deve ser padronizado |
| RNF53 | 53 | [MM32](observacao.md#mm32) | O aplicativo não deve ocupar mais do que 500 MB de armazenamento |
| RNF54 | 54 | [MM35](observacao.md#mm35)  | As resposta a ações do usuário não podem ultrapassar 1,5 segundo |
| RNF55 | 55 | [MM36](observacao.md#mm36)  | O sistema deve suportar versões anteriores |
| RNF56 | 56 | [MM37](observacao.md#mm37)  | O design deve ser responsivo |
| RNF57 | 57 | [MM38](observacao.md#mm38)  | As ilustrações e animações devem seguir um estilo coerente com a identidade visual do aplicativo |

</center>

## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 01/08/2024 | 1.0 | Criação do documento | [Guilherme Silva Dutra](https://github.com/GuiDutra21), [Julio Roberto](https://github.com/JulioR2022), [Felipe Amorim de Araújo](https://github.com/lipeaaraujo), [Raquel Ferreira Andrade](https://github.com/raquel-andrade) |
| 01/08/2024 | 1.1 | Adição da legenda das tabelas | [Guilherme Silva Dutra](https://github.com/GuiDutra21), [Raquel Ferreira Andrade](https://github.com/raquel-andrade) |
| 19/08/2024 | 1.2 | Ajustes no documento | [Guilherme Silva Dutra](https://github.com/GuiDutra21), [Julio Roberto](https://github.com/JulioR2022)|
| 10/09/2024 | 1.3 | Corrigindo rastreabilidade dos requisitos | [Felipe Amorim de Araújo](https://github.com/lipeaaraujo) |

</center>