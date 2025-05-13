## Introdução

A partir das técnicas de elicitação aplicadas (storytelling, questionário, introspecção e análise de interface de usuário), foram levantados e documentados os requisitos do sistema. A Tabela 1 apresenta os requisitos elicitados, categorizando-os em requisitos funcionais (RF) e não funcionais (RNF), bem como seu status atual de implementação e a rastreabilidade com as fontes que os originaram.

---

## Metodologia

A elicitação dos requisitos foi realizada utilizando quatro técnicas: **storytelling**, **questionário**, **introspecção** e **análise de interface de usuário**. Cada técnica foi aplicada para identificar funcionalidades e características do sistema, resultando na documentação apresentada na Tabela 1.

Os requisitos foram classificados em **Requisitos Funcionais (RF)** e **Requisitos Não Funcionais (RNF)**, com rastreabilidade às fontes que os originaram. A Tabela 1 também apresenta o status de implementação de cada requisito na data atual (04/05/2025), permitindo o acompanhamento do progresso do projeto.

---

##  Legenda da tabela 1

- RQx: Requisito Nº X
- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- IS: Requisito elicitado pela técnica de [Introspecção](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/)
- AI: Requisito elicitado pela técnica de [Análise de Interface de Usuário (UI)](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/)
- ST: Requisito elicitado pela técnica de [Storytelling](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/storytelling/)
- Q: Requisito elicitado pela técnica de [Questionário](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario/)

## Tabela 1 – Requisitos Elicitados (Versão 1)

| ID   | Descrição                                                                                                             | Rastreabilidade      | Categoria | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | -------------------- | --------- | ------------ |
| RQ01  | Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções.                                          | [IS01](../elicitação/introspecção.md#IS01), [AI01](../elicitação/analiseUI.md#AI01)            | RF        | Sim          |
| RQ02  | Detectar localização automaticamente e permitir alteração manual.                                                      | [IS02](../elicitação/introspecção.md#IS02), [AI02](../elicitação/analiseUI.md#AI02)            | RF        | Sim          |
| RQ03  | Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais.                                                       | [AI03](../elicitação/analiseUI.md#AI03)                 | RF        | Sim          |
| RQ04  | Autenticar usuário por e-mail e senha.                                                                                 | [AI04](../elicitação/analiseUI.md#AI04)                 | RF        | Sim          |
| RQ05  | Buscar filmes por nome.                                                                                                | [AI05](../elicitação/analiseUI.md#AI05)                 | RF        | Sim          |
| RQ06  | Listar filmes em cartaz, pré-venda e futuros lançamentos.                                                              | [AI06](../elicitação/analiseUI.md#AI06)                 | RF        | Sim          |
| RQ07  | Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem).                 | [IS03](../elicitação/introspecção.md#IS03), [AI07](../elicitação/analiseUI.md#AI07)            | RF        | Sim          |
| RQ08  | Exibir sessões com data, horário, idioma, formato e sala.                                                              | [IS04](../elicitação/introspecção.md#IS04), [ST01](../elicitação/storytelling.md#ST01), [AI08](../elicitação/analiseUI.md#AI08), [Q01](../elicitação/questionario.md#Q01)      | RF        | Sim          |
| RQ09  | Permitir compra de ingressos com cartão de crédito, débito ou Pix.                                                     | [IS05](../elicitação/introspecção.md#IS05), [AI14](../elicitação/analiseUI.md#AI14), [Q02](../elicitação/questionario.md#Q02)            | RF        | Sim          |
| RQ10 | Armazenar cartões de pagamento cadastrados para uso em compras futuras.                                                | [IS06](../elicitação/introspecção.md#IS06)                  | RF        | Sim          |
| RQ11 | Permitir compra de múltiplos ingressos em uma única transação.                                                         | [IS07](../elicitação/introspecção.md#IS07)                  | RF        | Sim          |
| RQ12 | Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais, e permitir seleção pelos usuários. | [IS08](../elicitação/introspecção.md#IS08), [AI09](../elicitação/analiseUI.md#AI09)            | RF        | Sim          |
| RQ13 | Exigir seleção de ao menos um assento antes de prosseguir.                                                             | [AI10](../elicitação/analiseUI.md#AI10)                 | RF        | Sim          |
| RQ14 | Definir tipo de ingresso por assento (inteira, meia, convênio, voucher).                                               | [AI11](../elicitação/analiseUI.md#AI11)                 | RF        | Sim          |
| RQ15 | Integrar bomboniere ao app para compra antecipada de itens e retirada rápida.                                          | [IS11](../elicitação/introspecção.md#IS11), [AI12](../elicitação/analiseUI.md#AI12)           | RF        | Sim          |
| RQ16 | Exibir resumo da compra e permitir aplicação de cupom de desconto.                                                     | [AI13](../elicitação/analiseUI.md#AI13), [AI29](../elicitação/analiseUI.md#AI29)           | RF        | Sim          |
| RQ17 | Gerar QR Code e chave Pix para pagamentos via Pix.                                                                     | [AI15](../elicitação/analiseUI.md#AI15)                 | RF        | Sim          |
| RQ18 | Disponibilizar ingresso digital no app, eliminando a necessidade de impressão.                                         | [IS09](../elicitação/introspecção.md#IS09), [ST03](../elicitação/storytelling.md#ST03)                  | RF        | Sim          |
| RQ19 | Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra.                                        | [AI16](../elicitação/analiseUI.md#AI16)                 | RF        | Sim          |
| RQ20 | Permitir criação de conta (nome, e-mail, senha, CPF) e login com Google/redes sociais.                                      | [AI17](../elicitação/analiseUI.md#AI17), [IS26](../elicitação/introspecção.md#IS26)           | RF        | Parcial          |
| RQ21 | Recuperação de conta: enviar link de redefinição de senha por e-mail, recuperar e-mail via CPF e redefinir com código. | [AI18](../elicitação/analiseUI.md#AI18), [AI19](../elicitação/analiseUI.md#AI19), [AI20](../elicitação/analiseUI.md#AI20)     | RF        | Sim          |
| RQ22 | Exibir histórico de filmes assistidos (data, horário, cinema) e histórico de compras na bomboniere.                    | [IS13](../elicitação/introspecção.md#IS13), [IS14](../elicitação/introspecção.md#IS14)           | RF        | Sim          |
| RQ23 | Filtrar filmes por categoria e exibir avaliações de público e plataformas externas.                                    | [IS15](../elicitação/introspecção.md#IS15)                 | RF        | Não          |
| RQ24 | Exibir trailers dentro do app.                                                                                         | [IS16](../elicitação/introspecção.md#IS16)                 | RF        | Não          |
| RQ25 | Oferecer fluxo de compra simplificado, com o mínimo de toques até a confirmação.                                       | [IS17](../elicitação/introspecção.md#IS17)                 | RF        | Não          |
| RQ26 | Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc).                      | [IS18](../elicitação/introspecção.md#IS18)                 | RF        | Não          |
| RQ27 | Permitir uso de pontos acumulados para desconto em ingressos e produtos.                                               | [IS19](../elicitação/introspecção.md#IS19), [Q03](../elicitação/questionario.md#Q03)                 | RF        | Sim          |
| RQ28 | Alertar usuário sobre pontos suficientes para ingresso grátis e antes da expiração.                                    | [IS20](../elicitação/introspecção.md#IS20)                 | RF        | Não          |
| RQ29 | Sugerir cinemas com base no histórico de visitas e na localização atual.                                               | [IS21](../elicitação/introspecção.md#IS21)                 | RF        | Não          |
| RQ30 | Permitir que o usuário salve cinemas como favoritos.                                                                   | [IS22](../elicitação/introspecção.md#IS22)                 | RF        | Não          |
| RQ31 | Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”).                              | [IS23](../elicitação/introspecção.md#IS23)                 | RF        | Não          |
| RQ32 | Exibir recomendações de filmes baseadas em histórico e preferências.                                                   | [IS24](../elicitação/introspecção.md#IS24)                 | RF        | Não          |
| RQ33 | Permitir alteração de preferências de idioma.                                                                          | [IS25](../elicitação/introspecção.md#IS25)                 | RF        | Não          |
| RQ34 | Disponibilizar área dedicada ao Cinemark Club: ingressos, pontos acumulados e validade.                                | [IS12](../elicitação/introspecção.md#IS12)                 | RF        | Sim          |
| RQ35 | Exibir notificações e promoções com título, descrição e validade.                                                      | [AI32](../elicitação/analiseUI.md#AI32)                 | RF        | Sim          |
| RQ36 | Impedir avanço para pagamento com carrinho vazio.                                                                      | [AI30](../elicitação/analiseUI.md#AI30)                 | RF        | Sim          |
| RQ37 | Criar e editar perfil do usuário, gerenciar dados pessoais e métodos de pagamento.                                     | [AI31](../elicitação/analiseUI.md#AI31)                 | RF        | Sim          |
| RQ38 | Mensagens de erro claras e confirmações de ações para o usuário.                                                       | [ST05](../elicitação/storytelling.md#ST05), [IS37](../elicitação/introspecção.md#IS37) | RF        | Sim      |
| RQ39 | Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas.                                 | [IS15](../elicitação/introspecção.md#IS15)| RF        | Não          |
| RQ40 | Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento).                                | [IS29](../elicitação/introspecção.md#IS29), [Q09](../elicitação/questionario.md#Q09), [Q12](../elicitação/questionario.md#Q12)                 | RNF       | Sim          |
| RQ41 | Garantir uptime de 99,5% para funções críticas.                                                                        | [AI28](../elicitação/analiseUI.md#AI28)                 | RNF       | Sim          |
| RQ42 | Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet).                                    | [AI24](../elicitação/analiseUI.md#AI24)                 | RNF       | Sim          |
| RQ43 | Interface intuitiva, com navegação fácil e boa usabilidade.                                                            | [IS28](../elicitação/introspecção.md#IS28)                 | RNF       | Sim          |
| RQ44 | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão.                              | [IS35](../elicitação/introspecção.md#IS35), [IS36](../elicitação/introspecção.md#IS36), [AI25](../elicitação/analiseUI.md#AI25), [ST05](../elicitação/storytelling.md#ST05)           | RNF       | Não          |
| RQ45 | Contraste de interface conforme WCAG A/AA.                                                                             | [AI25](../elicitação/analiseUI.md#AI25)                 | RNF       | Não          |
| RQ46 | Garantir legenda clara para cores e ícones no mapa de assentos.                                                        | [AI22](../elicitação/analiseUI.md#AI22)                 | RNF       | Sim          |
| RQ47 | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos.                                      | [AI23](../elicitação/analiseUI.md#AI23)                 | RNF       | Sim          |
| RQ48 | Proteger dados de pagamento e histórico do usuário com criptografia.                                                   | [IS32](../elicitação/introspecção.md#IS32), [Q10](../elicitação/questionario.md#Q10)                 | RNF       | Sim          |
| RQ49 | Autenticação por biometria ou PIN para operações sensíveis.                                                            | [IS33](../elicitação/introspecção.md#IS33)                 | RNF       | Sim          |
| RQ50 | Notificações push customizáveis pelo usuário.                                                                          | [IS34](../elicitação/introspecção.md#IS34)                 | RNF       | Não          |
| RQ51 | Exibir mapa de assentos com indicação gráfica clara de ocupação e disponibilidade.                                     | [IS31](../elicitação/introspecção.md#IS31)                 | RNF       | Sim          |
| RQ52 | Limitar quantidade máxima de 20 unidades por item no Snack Bar.                                                        | [AI26](../elicitação/analiseUI.md#AI26)                 | RNF       | Sim          |
| RQ53 | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra.                | [AI27](../elicitação/analiseUI.md#AI27)                 | RNF       | Sim          |
| RQ54 | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos).                                       | [AI33](../elicitação/analiseUI.md#AI33)                 | RNF       | Sim          |
| RQ55 | Validar e-mail e senha antes de criação ou redefinição de conta.                                                       | [AI34](../elicitação/analiseUI.md#AI34)                 | RNF       | Sim          |
| RQ56 | Remover automaticamente promoções expiradas da interface.                                                              | [AI35](../elicitação/analiseUI.md#AI35)                 | RNF       | Sim          |
| RQ57 | Validar dados pessoais no perfil antes de salvar.                                                                      | [AI36](../elicitação/analiseUI.md#AI36)                 | RNF       | Sim          |
| RQ58 | Fornecer comparação de preços entre cinemas.                                                                          | [Q04](../elicitação/questionario.md#Q04)                 | RF       | Não          |
| RQ59 | Fornecer reservas de salas para eventos.                                                                              | [Q05](../elicitação/questionario.md#Q05)                 | RF       | Não          |
| RQ60 | Fornecer um Hub para crítica de filmes.                                                                               | [Q06](../elicitação/questionario.md#Q06)                 | RF       | Não          |
| RQ61 | Manter a conta logada após o login.                                                                                   | [Q07](../elicitação/questionario.md#Q07)                 | RF       | Sim          |
| RQ62 | Permitir que o usuário cancele compras.                                                                               | [Q08](../elicitação/questionario.md#Q08)                 | RF       | Sim          |
| RQ63 | O aplicativo deve ser leve e usar pouca memória do dispositivo.                                                       | [Q11](../elicitação/questionario.md#Q11)                 | RNF       | Sim          |
| RQ64 | Permitir que o usuário exclua permanentemente sua conta.                                                       | [IS38](../elicitação/introspecção.md#IS38)                 | RF       | Sim          |
| RQ65 | Permitir ao usuário realizar logout de sua conta.                                                       | [IS39](../elicitação/introspecção.md#IS39)                 | RF       | Sim          |
| RQ66 | Permitir acesso ao ingresso offline, sem depender de conexão à internet na hora da sessão.                                                       | [IS10](../elicitação/introspecção.md#IS10), [IS30](../elicitação/introspecção.md#IS30)                 | RF/RNF       | Não          |
| RQ67 | Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.                                                       | [IS27](../elicitação/introspecção.md#IS27)                 | RF       | Não          |


**Observações:**

- **RQ20:** O login com Google e redes sociais ainda não foi implementado.


<font size="3"><p style="text-align: center">Autor(a): [Arthur Evangelista de Oliveira](https://github.com/arthurevg), 2025.</p></font>

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  04/05/2025 |  Criação do Documento com Introdução, metodologia, e tabela com os requisitos elicitados |[Arthur Evangelista](https://github.com/arthurevg) | Todos |
| `1.1`  |  04/05/2025 | Ajuste na formatação | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.2`  |  04/05/2025 | Correções na rastreabilidade de alguns itens | [Arthur Evangelista](https://github.com/arthurevg)| [Artur de Camargos](https://github.com/ArturDCR) |
| `1.3`  |  04/05/2025 | Correções na rastreabilidade do RQ38 | [Euller Júlio](https://github.com/Potatoyz908) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.4`  |  11/05/2025 | Correções na tabela de requisitos elicitados | [Euller Júlio](https://github.com/Potatoyz908) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.5`  | 12/05/2025 | Ajuste na legenda da tabela 1, na rastreabilidade e adição de RQ66 e RQ67 | [Davi Camilo](https://github.com/Davicamilo23) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
