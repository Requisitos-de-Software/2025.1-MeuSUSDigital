# Introspecção

## Introdução

A introspecção é uma técnica de elicitação que visa compreender as características desejáveis de um sistema para seu sucesso, considerando as percepções do engenheiro de requisitos. Essa técnica consiste em imaginar como seria a execução de uma tarefa específica, considerando os recursos disponíveis no momento, como equipamentos, tempo e ambiente, e refletir sobre quais funcionalidades e comportamentos seriam desejáveis no sistema. Durante essa técnica, o engenheiro se coloca no lugar de um usuário potencial, refletindo sobre como seria a execução de uma tarefa específica, levando em conta recursos como equipamentos, tempo e ambiente, e analisando quais funcionalidades e comportamentos seriam ideais para o sistema.

No processo de introspecção, o engenheiro de requisitos assume o papel de um usuário potencial, utilizando experiências passadas ou simulações para projetar suas expectativas, necessidades e frustrações. Esse exercício permite identificar requisitos funcionais e não funcionais importantes para o desenvolvimento do sistema, mesmo sem a participação direta de usuários reais.

---

## Metodologia

A introspecção foi conduzida de forma direta e individual, com base nas experiências pessoais dos participantes ao utilizarem aplicativos de cinema. Cada integrante se colocou no lugar de um usuário típico, refletindo sobre situações reais vividas durante a escolha de um filme, compra de ingressos, chegada ao cinema e uso de funcionalidades dentro dos aplicativos.

Não foram utilizados protótipos ou interfaces visuais durante a técnica; o foco esteve na observação subjetiva de necessidades, expectativas, comportamentos e frustrações enquanto usuários. A partir desses relatos, foram identificados requisitos funcionais e não funcionais que poderiam contribuir para a melhoria da experiência do usuário em um sistema voltado para exibição e compra de ingressos de cinema.

---

## Cronograma

A tabela 1 apresenta o cronograma da elicitação e as funções dos membros responsáveis pela técnica.

<font size="3"><p style="text-align: center">Tabela 1: Cronograma da Introspecção.</p></font>

| Nome                                                   | Data | Função            |
| ------------------------------------------------------ | ---- | ----------------- |
| [Arthur Evangelista de Oliveira](https://github.com/arthurevg) | 02/05/2025 | Analista de requisitos |
| [Euller Júlio da Silva](https://github.com/Potatoyz908) | 02/05/2025 | Analista de requisitos |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

---

## Relato Introspectivo
Durante o processo de introspecção, nos colocamos no lugar de usuários frequentes de aplicativos de cinema, considerando desde o momento em que decidimos assistir a um filme até a experiência completa de ida ao cinema. O relato completo pode ser encontrado abaixo e também no seguinte [link](https://docs.google.com/document/d/1Pm_DnCimXhM9ytfqsZnnv4eh21U2sqBZmh0-3c49Jys/edit?usp=sharing).

<details> <summary><strong>Relato de Arthur Evangelista</strong></summary>
Durante a introspecção, observou-se que usuários de aplicativos de cinema costumam buscar por funcionalidades que facilitem o acesso a lançamentos e promoções de filmes. É desejável que o sistema identifique automaticamente a localização do usuário para sugerir cinemas próximos, mas também permita alteração manual;

A experiência ideal do usuário ao acessar o aplicativo inclui visualizar facilmente os filmes em cartaz, juntamente com sessões disponíveis, datas, horários, sinopse, idioma (legendado/dublado), gênero e formato (2D, 3D, XD, etc). A compra de ingressos pelo aplicativo deve ser prática, aceitando múltiplas formas de pagamento como cartão de crédito, débito e Pix. Para evitar retrabalho, é recomendável que os métodos de pagamento possam ser armazenados de forma segura;

Outro ponto observado é a preferência por adquirir múltiplos ingressos em uma única transação, especialmente para quem vai ao cinema com familiares ou amigos. O uso do ingresso diretamente pelo aplicativo, inclusive offline, é um diferencial importante, pois evita a necessidade de impressão ou conexão com a internet no momento da entrada na sala;

Em relação à escolha de assentos, é valorizada a possibilidade de selecionar posições específicas com base em uma visualização clara do mapa da sala, incluindo a indicação de lugares ocupados e disponíveis. Além disso, espera-se que o sistema permita a compra antecipada de produtos da bomboniere, como pipoca e refrigerante, com retirada expressa no balcão;

Para usuários associados a programas como o Cinemark Club, é desejável que o aplicativo possua uma seção dedicada, exibindo ingressos, pontos acumulados e a data de expiração dos mesmos, com alertas antes da perda dos pontos. Um histórico de filmes assistidos, com informações sobre datas, horários e salas, também é útil, assim como o histórico de compras na bomboniere, possibilitando repetir pedidos anteriores com facilidade.


</details> <details> <summary><strong>Relato de Euller Júlio</strong></summary>
A introspecção identificou que a navegação intuitiva e o bom desempenho do aplicativo são fatores essenciais para uma boa experiência do usuário. Funcionalidades críticas, como seleção de assentos e etapas de pagamento, devem carregar rapidamente e operar sem travamentos;

Usuários valorizam filtros de busca por categoria de filme (ação, comédia, terror, etc.) e classificações de público ou de plataformas como IMDb. É considerado positivo que trailers sejam exibidos diretamente no aplicativo, sem redirecionamento para outras plataformas;

O fluxo de compra ideal é simplificado, permitindo a finalização da transação com poucos toques, incluindo escolha de assento, pagamento e confirmação. A funcionalidade de salvar ingressos automaticamente em carteiras digitais, como Google Wallet, aumenta a conveniência do usuário;

Outro aspecto importante é a integração com sistemas de pontos, permitindo o uso de pontos como desconto em ingressos ou produtos. Notificações automáticas sobre pontos disponíveis ou prestes a expirar são consideradas valiosas;

A sugestão de cinemas com base em localização atual e histórico de uso é desejável, desde que acompanhada da opção de salvar cinemas favoritos. Notificações personalizadas, como lembretes sobre estreias ou sobre a compra antecipada de ingressos, são funcionalidades que agregam valor;

Recomendações personalizadas baseadas em histórico e preferências são bem-vindas, pois reduzem o tempo gasto na escolha de um filme. Além disso, usuários esperam poder configurar preferências de idioma no app;

A integração com redes sociais é considerada uma vantagem, pois facilita o login e o compartilhamento de informações. Por fim, espera-se que o sistema adote boas práticas de acessibilidade, como suporte a leitores de tela e contraste adequado, além de mecanismos de segurança como autenticação por biometria ou PIN para proteção de dados sensíveis.

</details>

---

## Requisitos Elicitados

Os requisitos elicitados a partir da introspecção foram divididos em duas categorias principais: funcionais e não funcionais. A Tabela 2 apresenta os Requisitos Funcionais (RF), enquanto a Tabela 3 reúne os Requisitos Não Funcionais (RNF), ambos originados da atividade introspectiva.

---

## Legenda das tabelas 2 e 3

- **RFx**: Requisito Funcional nº x  
- **RNFx**: Requisito Não-Funcional nº x  
- **ISx**: Requisito nº x elicitado pela introspecção  
- **Implementado**: “Sim” se já existir no app atual; “Não” caso contrário  

## Tabela 2 – Requisitos Funcionais

| Tipo  | Descrição                                                                                                                                                       | ID   | Implementado |
|-------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|--------------|
| RF1   | Exibir na tela inicial os filmes em cartaz, com pôsteres e promoções.                                                                                           | <a id="IS01"></a>IS01  | Sim          |
| RF2   | Detectar automaticamente a localização do usuário e sugerir cinemas próximos, com opção de troca manual.                                                        | <a id="IS02"></a>IS02  | Sim          |
| RF3   | Ao selecionar um filme, exibir suas informações: título, sinopse, gênero, elenco e classificação indicativa.                                                    | <a id="IS03"></a>IS03  | Sim          |
| RF4   | Exibir sessões disponíveis para o filme escolhido, com data, horário, idioma (legendado/dublado), formato (2D/3D/XD/IMAX) e sala.                              | <a id="IS04"></a>IS04  | Sim          |
| RF5   | Permitir compra de ingressos pelo app usando cartão de crédito, débito ou Pix.                                                                                  | <a id="IS05"></a>IS05  | Sim          |
| RF6   | Armazenar cartões de pagamento cadastrados, para uso rápido em compras futuras.                                                                                 | <a id="IS06"></a>IS06  | Sim          |
| RF7   | Permitir compra de múltiplos ingressos em uma única transação.                                                                                                   | <a id="IS07"></a>IS07  | Sim          |
| RF8   | Exibir o mapa da sala com indicação clara de assentos ocupados e livres e permitir seleção de assentos diretamente pelo mapa.                                   | <a id="IS08"></a>IS08  | Sim          |
| RF9   | Disponibilizar ingresso digital no app, eliminando a necessidade de impressão.                                                                                   | <a id="IS09"></a>IS09  | Sim          |
| RF10  | Permitir acesso ao ingresso em modo offline, sem depender de conexão à internet na hora da sessão.                                                              | <a id="IS10"></a>IS10 | Não          |
| RF11  | Integrar a bomboniere ao app para compra antecipada de itens (pipoca, refrigerante etc.) e retirada rápida no balcão.                                           | <a id="IS11"></a>IS11 | Sim          |
| RF12  | Disponibilizar área dedicada ao Cinemark Club, mostrando ingressos, pontos acumulados e data de expiração.                                                      | <a id="IS12"></a>IS12 | Sim          |
| RF13  | Exibir histórico de filmes assistidos, com data, horário e cinema, para consulta posterior.                                                                      | <a id="IS13"></a>IS13 | Sim          |
| RF14  | Exibir histórico de compras na bomboniere e permitir repetição de pedidos anteriores.                                                                            | <a id="IS14"></a>IS14 | Sim          |
| RF15  | Permitir filtrar filmes por categoria (ação, comédia, terror etc.) e exibir avaliações do público ou de plataformas como IMDb.                                  | <a id="IS15"></a>IS15 | Não          |
| RF16  | Exibir trailers dentro do próprio aplicativo, sem redirecionar para plataformas externas.                                                                        | <a id="IS16"></a>IS16 | Não          |
| RF17  | Oferecer um fluxo de compra simplificado, com poucos toques desde a seleção de assento até a confirmação do pagamento.                                          | <a id="IS17"></a>IS17 | Não          |
| RF18  | Salvar ingressos automaticamente na carteira digital do dispositivo (Google Wallet, Apple Wallet etc).                                                          | <a id="IS18"></a>IS18 | Não          |
| RF19  | Permitir uso de pontos acumulados para desconto em ingressos e produtos da bomboniere.                                                                           | <a id="IS19"></a>IS19 | Sim          |
| RF20  | Alertar automaticamente o usuário quando tiver pontos suficientes para entrada grátis ou desconto, e antes de expirar pontos.                                   | <a id="IS20"></a>IS20 | Não          |
| RF21  | Sugerir cinemas com base no histórico de visitas e na localização atual do usuário.                                                                              | <a id="IS21"></a>IS21 | Não          |
| RF22  | Permitir que o usuário salve cinemas como favoritos para facilitar acessos futuros.                                                                              | <a id="IS22"></a>IS22 | Não          |
| RF23  | Permitir criação de notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz” ou “lembre-me 1 dia antes da sessão”).                       | <a id="IS23"></a>IS23 | Não          |
| RF24  | Oferecer recomendações de filmes baseadas no histórico de visualizações e preferências de gênero do usuário.                                                     | <a id="IS24"></a>IS24 | Não          |
| RF25  | Permitir que o usuário altere suas preferências de idioma para uma experiência personalizada.                                                                    | <a id="IS25"></a>IS25 | Não          |
| RF26  | Integrar o login do aplicativo com redes sociais para facilitar o acesso e compartilhamento de informações.                                                      | <a id="IS26"></a>IS26 | Não          |
| RF27  | Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.                                                        | <a id="IS27"></a>IS27 | Não          |
| RF28|Feedback visual/sonoro em transições de tela (loading, sucesso, erro) |<a id="IS37"></a>IS37|Sim|
| RF29|O sistema deve permitir ao usuário excluir permanentemente sua conta, incluindo a remoção dos dados associados, com confirmação prévia da ação. |<a id="IS38"></a>IS38|Sim|
| RF30|O sistema deve permitir ao usuário realizar logout de sua conta, encerrando a sessão atual e retornando à tela de login. |<a id="IS39"></a>IS39|Sim|

<font size="3"><p style="text-align: center">Fonte: [Arthur Evangelista de Oliveira](https://github.com/arthurevg) e [Euller Júlio da Silva](https://github.com/Potatoyz908), 2025.</p></font>

## Tabela 3 – Requisitos Não Funcionais

| Tipo   | Descrição                                                                                                                                      | ID   | Implementado |
|--------|-------------------------------------------------------------------------------------------------------------------------------------------------|------|--------------|
| RNF1   | Interface intuitiva, com navegação fácil e boa usabilidade.                                                                                     | <a id="IS28"></a>IS28 | Sim          |
| RNF2   | Resposta instantânea em telas críticas (seleção de assentos, pagamento), sem travamentos.                                                       | <a id="IS29"></a>IS29 | Sim          |
| RNF3   | Ingresso disponível offline, para acesso sem conexão com internet.                                                                              | <a id="IS30"></a>IS30 | Não          |
| RNF4   | Mapa de assentos com indicação gráfica clara de ocupação e disponibilidade.                                                                     | <a id="IS31"></a>IS31 | Sim          |
| RNF5   | Dados de pagamento e histórico do usuário protegidos (armazenamento seguro).                                                                    | <a id="IS32"></a>IS32 | Sim          |
| RNF6   | Autenticação por biometria ou PIN para operações sensíveis (pagamentos, acesso a dados pessoais).                                               | <a id="IS33"></a>IS33 | Sim          |
| RNF7   | Notificações push customizáveis pelo usuário (ex.: “lembre-me 1 dia antes”).                                                                    | <a id="IS34"></a>IS34 | Não          |
| RNF8   | Interface acessível para pessoas com deficiência visual, incluindo suporte para leitores de tela.                                               | <a id="IS35"></a>IS35 | Não          |
| RNF9   | Garantir um bom contraste nas interfaces do aplicativo para melhorar a legibilidade para usuários com deficiência visual, com opção de ajuste. | <a id="IS36"></a>IS36 | Não          |

<font size="3"><p style="text-align: center">Fonte: [Arthur Evangelista de Oliveira](https://github.com/arthurevg) e [Euller Júlio da Silva](https://github.com/Potatoyz908), 2025.</p></font>

---

## Bibliografia

> 1. SERRANO, Milene; SERRANO, Maurício. "Requisitos - Aula 07". *UnB Gama*. Disponível em: [https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf](https://aprender3.unb.br/pluginfile.php/3096086/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf)

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 02/05/2025 | Criação da página 'introspecção', contendo introdução, metodologia, relato introspectivo e os requisitos elicitados | [Arthur Evangelista](https://github.com/arthurevg) e [Euller Júlio](https://github.com/Potatoyz908) | [Davi Camilo](https://github.com/Davicamilo23) e [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.1`  | 04/05/2025 | Ajuste na formatação | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg)  |
| `1.2`  | 04/05/2025 | Correção dos IDs dos requisitos não funcionais (RNF) | [Euller Júlio](https://github.com/Potatoyz908) | [Gabriel Henrique Castelo](https://github.com/GabrielCastelo-31) |
| `1.3`  | 11/05/2025 | Ajustes na tabela de requisitos funcionais (RF) | [Euller Júlio](https://github.com/Potatoyz908) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.4`  | 11/05/2025 | Ajustes no conteúdo de introspecção e relatos | [Euller Júlio](https://github.com/Potatoyz908) | [Gabriel Henrique Castelo](https://github.com/GabrielCastelo-31) |
| `1.5`  | 12/05/2025 | Adição do cronograma da técnica | [Davi Camilo](https://github.com/Davicamilo23) | [Tiago Antunes](https://github.com/tiagobalieiro) |
