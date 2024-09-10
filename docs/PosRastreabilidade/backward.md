# Backward-From

## Introdução

A abordagem Backward From é uma técnica de rastreabilidade de requisitos que parte dos resultados finais ou das funcionalidades implementadas, retornando às suas origens para garantir o alinhamento com os objetivos iniciais do projeto. Isto garante que cada funcionalidade implementada esteja conectada a um requisito original, o que acaba por facilitar os processos de validação do sistema.

## Metodologia
Para construir a matriz de rastreabilidade backward-from, foi utilizada como base a [baseline]() de requistos. A partir dela foi identificado a partir de quais técnicas de elicitação utilizadas ao longo do trabalho os requisitos se originaram.

### Legenda para as Tabelas 01:

- **RFx**: Requisito Funcional n° x
- **RNFx**: Requisito Não-Funcional n° x
- **BSx**: Requisito n° x da técnica de Brainstorming
- **MMx**: Requisito n° x da técnica do Mapa Mental
- **STx**: Requisito n° x da técnica de Storytelling
- **APx**: Requisito n° x da técnica de Análise de Protocolo

<center>

### Tabela 01 - Backward-From

| Tipo | ID | Técnica de elicitação | Descrição |
| - | - | - | - |
| <a id="rf01">RF01</a> | 01 | [BS01](../ElicitacaodeRequisitos/brainstorm.md#bs01), [ST07](../ElicitacaodeRequisitos/storytelling.md#st07), [MM01](../ElicitacaodeRequisitos/observacao.md#mm01) | O aplicativo deve ter uma variedade de cursos e idiomas | 
| <a id="rf02">RF02</a> | 02 | [ST02](../ElicitacaodeRequisitos/storytelling.md#st02) | O usuário deve poder refazer as lições |
|<a id="rf03">RF03</a> | 03 | [BS02](../ElicitacaodeRequisitos/brainstorm.md#bs02), [ST03](../ElicitacaodeRequisitos/storytelling.md#st03) |O aplicativo deve ter um sistema de revisão de conteúdo | 
| <a id="rf04">RF04</a> | 04 | [ST09](../ElicitacaodeRequisitos/storytelling.md#st09), [MM06](../ElicitacaodeRequisitos/observacao.md#mm06) | O aplicativo deve permitir o cadastro e gerenciamento de contas | 
| <a id="rf05">RF05</a> | 05 | [MM07](../ElicitacaodeRequisitos/observacao.md#mm07) | O perfil do usuário deve exibir informações importantes | 
| <a id="rf06">RF06</a> | 06 | [MM11](../ElicitacaodeRequisitos/observacao.md#mm11) | O aplicativo deve exibir as coleções de erros, palavras aprendidas e histórias estudadas | 
| <a id="rf07">RF07</a> | 07 | [BS03](../ElicitacaodeRequisitos/brainstorm.md#bs03), [MM02](../ElicitacaodeRequisitos/observacao.md#mm02) | Os cursos oferecidos devem ser divididos em seções | 
| <a id="rf08">RF08</a> | 08 | [BS04](../ElicitacaodeRequisitos/brainstorm.md#bs04), [MM03](../ElicitacaodeRequisitos/observacao.md#mm03) | As seções devem estar divididas em unidades |
| <a id="rf09">RF09</a> | 09 | [BS05](../ElicitacaodeRequisitos/brainstorm.md#bs05), [MM04](../ElicitacaodeRequisitos/observacao.md#mm04) | As unidades devem estar divididas em lições |
| <a id="rf10">RF10</a> | 10 | [BS06](../ElicitacaodeRequisitos/brainstorm.md#bs06), [ST01](../ElicitacaodeRequisitos/storytelling.md#st01), [AP01](../ElicitacaodeRequisitos/protocolo.md#ap01) | As lições devem abranger questões de fala, de escrita, de leitura e de escuta |
| <a id="rf11">RF11</a> | 11 | [BS07](../ElicitacaodeRequisitos/brainstorm.md#bs07), [ST08](../ElicitacaodeRequisitos/storytelling.md#st08), [MM05](../ElicitacaodeRequisitos/observacao.md#mm05), [AP04](../ElicitacaodeRequisitos/protocolo.md#ap04), [AP07](../ElicitacaodeRequisitos/protocolo.md#ap07) | O aplicativo deve dar feedback durante a realização das questões |
| <a id="rf12">RF12</a> | 12 | [BS08](../ElicitacaodeRequisitos/brainstorm.md#bs08), [ST10](../ElicitacaodeRequisitos/storytelling.md#st10) | O usuário deve ser capaz de monitorar seu progresso no curso |
| <a id="rf13">RF13</a> | 13 | [BS09](../ElicitacaodeRequisitos/brainstorm.md#bs09) | O usuário deve receber notificações |
| <a id="rf14">RF14</a> | 14 | [BS10](../ElicitacaodeRequisitos/brainstorm.md#bs10), [MM09](../ElicitacaodeRequisitos/observacao.md#mm09), [AP10](../ElicitacaodeRequisitos/protocolo.md#ap10) | O aplicativo deve oferecer um sistema de missões ao usuário |
| <a id="rf15">RF15</a> | 15 | [BS11](../ElicitacaodeRequisitos/brainstorm.md#bs11), [MM10](../ElicitacaodeRequisitos/observacao.md#mm10) | O aplicativo deve ter um sistema de recompensas | 
| <a id="rf16">RF16</a> | 16 | [BS12](../ElicitacaodeRequisitos/brainstorm.md#bs12), [MM14](../ElicitacaodeRequisitos/observacao.md#mm14), [ST07](../ElicitacaodeRequisitos/storytelling.md#st07), [AP09](../ElicitacaodeRequisitos/protocolo.md#ap09) | O aplicativo deve ter um sistema de competição | 
| <a id="rf17">RF17</a> | 17 | [BS13](../ElicitacaodeRequisitos/brainstorm.md#bs13), [ST04](../ElicitacaodeRequisitos/storytelling.md#st04), [ST05](../ElicitacaodeRequisitos/storytelling.md#st05), [MM08](../ElicitacaodeRequisitos/observacao.md#mm08), [AP13](../ElicitacaodeRequisitos/protocolo.md#ap13) | O aplicativo deve ter um sistema de amizades |
| <a id="rf18">RF18</a> | 18 | [BS14](../ElicitacaodeRequisitos/brainstorm.md#bs14), [MM12](../ElicitacaodeRequisitos/observacao.md#mm12), [AP08](../ElicitacaodeRequisitos/protocolo.md#ap08) | O aplicativo deve ter um sistema de controle da frequência de estudo do usuário | 
| <a id="rf19">RF19</a> | 19 | [BS15](../ElicitacaodeRequisitos/brainstorm.md#bs15) | O aplicativo deve ser personalizável às necessidades do usuário |
| <a id="rf20">RF20</a> | 20 | [ST11](../ElicitacaodeRequisitos/storytelling.md#st11) | Permitir o usuário encerrar uma lição prematuramente | 
| <a id="rf21">RF21</a> | 21 | [MM17](../ElicitacaodeRequisitos/observacao.md#mm17) | Permite a sincronização com a conta de outras plataformas | 
| <a id="rf22">RF22</a> | 22 | [MM13](../ElicitacaodeRequisitos/observacao.md#mm13) | O aplicativo oferece conquistas para marcos específicos no aprendizado | 
| <a id="rf23">RF23</a>  | 23 | [MM15](../ElicitacaodeRequisitos/observacao.md#mm15), [AP12](../ElicitacaodeRequisitos/protocolo.md#ap12) | O aplicativo deve fornecer uma loja | 
| <a id="rf24">RF24</a> | 24 | [MM16](../ElicitacaodeRequisitos/observacao.md#mm16) | O aplicativo deve permitir a compra de recursos a partir de dinheiro real |
| <a id="rf25">RF25</a> | 25 | [AP02](../ElicitacaodeRequisitos/protocolo.md#ap02) | O usuário pode reproduzir os áudios quantos vezes desejar |
| <a id="rf26">RF26</a> | 26 | [AP03](../ElicitacaodeRequisitos/protocolo.md#ap03) | Permite alterar a velocidade de reprodução de áudios |
| <a id="rf27">RF27</a> | 27 | [AP05](../ElicitacaodeRequisitos/protocolo.md#ap05) | Novas palavras devem ser visualmente destacadas e deve-se mostrar a sua tradução | 
| <a id="rf28">RF28</a> | 28 | [AP06](../ElicitacaodeRequisitos/protocolo.md#ap06) | Permite pular ou adiar questões de fala e escuta |
| <a id="rf29">RF29</a> | 29 | [AP11](../ElicitacaodeRequisitos/protocolo.md#ap11) | Permite o compartilhamento do perfil e de conquistas | 
| <a id="rf30">RF30</a> | 30 | [MM18](../ElicitacaodeRequisitos/observacao.md#mm18) | O usuário deve ser capaz de gerenciar o seu perfil | 
| <a id="rf31">RF31</a> | 31 | [MM19](../ElicitacaodeRequisitos/observacao.md#mm19) | Um nível deve ser dívido em lições |
| <a id="rf32">RF32</a> | 32 | [MM20](../ElicitacaodeRequisitos/observacao.md#mm20) | O usuário deve ser capaz de reportar um problema |
| <a id="rf33">RF33</a> | 33 | [MM21](../ElicitacaodeRequisitos/observacao.md#mm21) | O aplicativo deve fornecer um conjunto de notícias/novidades para o usuario | 
| <a id="rf34">RF34</a> | 34 | [MM22](../ElicitacaodeRequisitos/observacao.md#mm22) | O aplicativo permite ao usuário utilizar os seus respectivos itens | 
| <a id="rnf35">RNF35</a> | 35 | [BS16](../ElicitacaodeRequisitos/brainstorm.md#bs16), [ST13](../ElicitacaodeRequisitos/storytelling.md#st13) | As lições do aplicativo devem ser interativas |
| <a id="rnf36">RNF36</a> | 36 | [BS17](../ElicitacaodeRequisitos/brainstorm.md#bs17), [MM30](../ElicitacaodeRequisitos/observacao.md#mm30) | Deve existir um feedback imediato após a realização de uma questão |
| <a id="rnf37">RNF37</a> | 38 | [BS18](../ElicitacaodeRequisitos/brainstorm.md#bs18), [ST16](../ElicitacaodeRequisitos/storytelling.md#st16) | O aplicativo deve possuir funcionalidades no modo off-line |
| <a id="rnf38">RNF38</a> | 38 | [BS19](../ElicitacaodeRequisitos/brainstorm.md#bs19), [ST18](../ElicitacaodeRequisitos/storytelling.md#st18), [MM23](../ElicitacaodeRequisitos/observacao.md#mm23), [AP17](../ElicitacaodeRequisitos/protocolo.md#ap17) | O aplicativo deve ser gamificado | 
| <a id="rnf39">RNF39</a> | 39 | [BS20](../ElicitacaodeRequisitos/brainstorm.md#bs20) | A maioria das funcionalidades devem ser gratuitas |
| <a id="rnf40">RNF40</a> | 40 | [BS21](../ElicitacaodeRequisitos/brainstorm.md#bs21), [MM25](../ElicitacaodeRequisitos/observacao.md#mm25) | O aplicativo deve suportar muitos usuários simultaneamente | 
| <a id="rnf41">RNF41</a> | 41 | [BS22](../ElicitacaodeRequisitos/brainstorm.md#bs22), [MM28](../ElicitacaodeRequisitos/observacao.md#mm28) | O aplicativo deve apresentar uma navegação simples |
| <a id="rnf42">RNF42</a> | 42 | [BS23](../ElicitacaodeRequisitos/brainstorm.md#bs23), [MM27](../ElicitacaodeRequisitos/observacao.md#mm27) | O aplicativo deve apresentar uma interface intuitiva | 
| <a id="rnf43">RNF43</a> | 43 | [BS24](../ElicitacaodeRequisitos/brainstorm.md#bs24), [ST12](../ElicitacaodeRequisitos/storytelling.md#st12) | As lições devem ser curtas e objetivas |
| <a id="rnf44">RNF44</a> | 44 | [BS26](../ElicitacaodeRequisitos/brainstorm.md#bs26), [ST14](../ElicitacaodeRequisitos/storytelling.md#st14) | O aplicativo deve estar disponível a qualquer horário e local |
| <a id="rnf45">RNF45</a> | 45 | [ST15](../ElicitacaodeRequisitos/storytelling.md#st15) |  O aplicativo deve estar disponível em diversos tipos de dispositivos, como exemplo, Androids e IOSs |
| <a id="rnf46">RNF46</a> | 46 | [ST17](../ElicitacaodeRequisitos/storytelling.md#st17) | O aplicativo deve ser acessível para qualquer idade | 
| <a id="rnf47">RNF47</a> | 47 | [ST19](../ElicitacaodeRequisitos/storytelling.md#st19) | O aplicativo deve estar disponível em diversos idiomas | 
| <a id="rnf48">RNF48</a> | 48 | [ST20](../ElicitacaodeRequisitos/storytelling.md#st20) | O aplicativo deve permitir a sincronização de contas em dispositivos diferentes |
| <a id="rnf49">RNF49</a> | 49 | [MM26](../ElicitacaodeRequisitos/observacao.md#mm26) | As transações dentro da loja devem ser seguras | 
| <a id="rnf50">RNF50</a> | 50 | [MM29](../ElicitacaodeRequisitos/observacao.md#mm29), [AP15](../ElicitacaodeRequisitos/protocolo.md#ap15) | As lições devem ter conteúdo confiável e verificado | Alta Prioridade, M |
| <a id="rnf51">RNF51</a> | 51 | [AP14](../ElicitacaodeRequisitos/protocolo.md#ap14) | As mensagens de feedback devem ser claras e objetivas |
| <a id="rnf52">RNF52</a> | 52 | [AP16](../ElicitacaodeRequisitos/protocolo.md#ap16) | O design do aplicativo deve ser padronizado | 
| <a id="rnf53">RNF53</a> | 53 | [MM34](../ElicitacaodeRequisitos/observacao.md#mm34) | O aplicativo não deve ocupar mais do que 500 MB de armazenamento |
| <a id="rnf54">RNF54</a> | 54 | [MM35](../ElicitacaodeRequisitos/observacao.md#mm35)  | As resposta a ações do usuário não podem ultrapassar 1,5 segundo |
| <a id="rnf55">RNF55</a> | 55 | [MM36](../ElicitacaodeRequisitos/observacao.md#mm36)  | O sistema deve suportar versões anteriores |
| <a id="rnf56">RNF56</a> | 56 | [MM37](../ElicitacaodeRequisitos/observacao.md#mm37)  | O design deve ser responsívo |
| <a id="rnf57">RNF57</a> | 57 | [MM38](../ElicitacaodeRequisitos/observacao.md#mm38)  | As ilustrações e animações devem seguir um estilo coerente com a identidade visual do aplicativo |

</center>

## Referências
- SAYÃO, L. F.; LEITE, J. C. S. P. Rastreabilidade de Requisitos no Ciclo de Vida de Software. Revista Brasileira de Engenharia de Software. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastreabilidade5.pdf>

## Histórico de Versão

<center>

| Data | Versão | Descrição | Autor |
| ---- | ------ | --------- | ----- |
| 10/09/2024 | 1.0 | Criação do documento | [Julio Roberto](https://github.com/JulioR2022) |

</center>