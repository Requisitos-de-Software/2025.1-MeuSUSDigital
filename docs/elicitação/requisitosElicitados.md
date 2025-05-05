## Introdução

A partir das técnicas de elicitação aplicadas (storytelling, questionário, introspecção e análise de interface de usuário), foram levantados e documentados os requisitos do sistema. A Tabela 1 apresenta os requisitos elicitados, categorizando-os em requisitos funcionais (RF) e não funcionais (RNF), bem como seu status atual de implementação e a rastreabilidade com as fontes que os originaram.

---

## Metodologia

A elicitação dos requisitos foi realizada utilizando quatro técnicas: **storytelling**, **questionário**, **introspecção** e **análise de interface de usuário**. Cada técnica foi aplicada para identificar funcionalidades e características do sistema, resultando na documentação apresentada na Tabela 1.

Os requisitos foram classificados em **Requisitos Funcionais (RF)** e **Requisitos Não Funcionais (RNF)**, com rastreabilidade às fontes que os originaram. A Tabela 1 também apresenta o status de implementação de cada requisito na data atual(04/05/2025), permitindo o acompanhamento do progresso do projeto.

---

##  Legenda da tabela 1

- RQx: Requisiyo Nº X
- RF: Requisito Funcional
- RNF: Requisito Não Funcional
- IS: Requisito elicitado pela técnica de [Introspeccção](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/)
- AI: Requisito elicitado pela técnica de [Análise de Interfaces de Usuário(UI)](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/analiseUI/)
- ST: Requisito elicitado pela técnica de [Storytelling](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/storytelling/)
- XX: Requisito elicitado pela técnica de [Questionário](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario/)

## Tabela 1 – Requisitos Elicitados (Versão 1)

| ID   | Descrição                                                                                                             | Rastreabilidade      | Categoria | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | -------------------- | --------- | ------------ |
| RQ1  | Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções                                          | IS1, AI01            | RF        | Sim          |
| RQ2  | Detectar localização automaticamente e permitir alteração manual                                                      | IS2, AI02            | RF        | Sim          |
| RQ3  | Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais                                                       | AI03                 | RF        | Sim          |
| RQ4  | Autenticar usuário por e-mail e senha                                                                                 | AI04                 | RF        | Sim          |
| RQ5  | Buscar filmes por nome                                                                                                | AI05                 | RF        | Sim          |
| RQ6  | Listar filmes em cartaz, pré-venda e futuros lançamentos                                                              | AI06                 | RF        | Sim          |
| RQ7  | Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem)                 | IS3, AI07            | RF        | Sim          |
| RQ8  | Exibir sessões com data, horário, idioma, formato e sala                                                              | IS4, ST01, AI08, Q01      | RF        | Sim          |
| RQ9  | Permitir compra de ingressos com cartão de crédito, débito ou Pix                                                     | IS5, AI14, Q02            | RF        | Sim          |
| RQ10 | Armazenar cartões de pagamento cadastrados para uso em compras futuras                                                | IS6                  | RF        | Sim          |
| RQ11 | Permitir compra de múltiplos ingressos em uma única transação                                                         | IS7                  | RF        | Sim          |
| RQ12 | Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais, e permitir seleção pelos usuários | IS8, AI09            | RF        | Sim          |
| RQ13 | Exigir seleção de ao menos um assento antes de prosseguir                                                             | AI10                 | RF        | Sim          |
| RQ14 | Definir tipo de ingresso por assento (inteira, meia, convênio, voucher)                                               | AI11                 | RF        | Sim          |
| RQ15 | Integrar bomboniere ao app para compra antecipada de itens e retirada rápida                                          | IS11, AI12           | RF        | Sim          |
| RQ16 | Exibir resumo da compra e permitir aplicação de cupom de desconto                                                     | AI13, AI29           | RF        | Sim          |
| RQ17 | Gerar QR Code e chave Pix para pagamentos via Pix                                                                     | AI15                 | RF        | Sim          |
| RQ18 | Disponibilizar ingresso digital no app, eliminando a necessidade de impressão                                         | IS9, ST03                  | RF        | Sim          |
| RQ19 | Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra                                        | AI16                 | RF        | Sim          |
| RQ20 | Permitir criação de conta (nome, e-mail, senha, CPF) e login com Google/redes sociais                                      | AI17, IS26           | RF        | Parcial          |
| RQ21 | Recuperação de conta: enviar link de redefinição de senha por e-mail, recuperar e-mail via CPF e redefinir com código | AI18, AI19, AI20     | RF        | Sim          |
| RQ22 | Exibir histórico de filmes assistidos (data, horário, cinema) e histórico de compras na bomboniere                    | IS13, IS14           | RF        | Sim          |
| RQ23 | Filtrar filmes por categoria e exibir avaliações de público e plataformas externas                                    | IS15                 | RF        | Não          |
| RQ24 | Exibir trailers dentro do app                                                                                         | IS16                 | RF        | Não          |
| RQ25 | Oferecer fluxo de compra simplificado, com o mínimo de toques até a confirmação                                       | IS17                 | RF        | Não          |
| RQ26 | Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc.)                      | IS18                 | RF        | Não          |
| RQ27 | Permitir uso de pontos acumulados para desconto em ingressos e produtos                                               | IS19, Q03                 | RF        | Sim          |
| RQ28 | Alertar usuário sobre pontos suficientes para ingresso grátis e antes da expiração                                    | IS20                 | RF        | Não          |
| RQ29 | Sugerir cinemas com base no histórico de visitas e na localização atual                                               | IS21                 | RF        | Não          |
| RQ30 | Permitir que o usuário salve cinemas como favoritos                                                                   | IS22                 | RF        | Não          |
| RQ31 | Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”)                              | IS23                 | RF        | Não          |
| RQ32 | Exibir recomendações de filmes baseadas em histórico e preferências                                                   | IS24                 | RF        | Não          |
| RQ33 | Permitir alteração de preferências de idioma                                                                          | IS25                 | RF        | Não          |
| RQ34 | Disponibilizar área dedicada ao Cinemark Club: ingressos, pontos acumulados e validade                                | IS12                 | RF        | Sim          |
| RQ35 | Exibir notificações e promoções com título, descrição e validade                                                      | AI32                 | RF        | Sim          |
| RQ36 | Impedir avanço para pagamento com carrinho vazio                                                                      | AI30                 | RF        | Sim          |
| RQ37 | Criar e editar perfil do usuário, gerenciar dados pessoais e métodos de pagamento                                     | AI31                 | RF        | Sim          |
| RQ38 | Mensagens de erro claras e confirmações de ações para o usuário                                                       | ST05, IS37 | RF        | Sim      |
| RQ39 | Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas                                 | IS15| RF        | Não          |
| RQ40 | Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento)                                | IS29, Q09, Q12                 | RNF       | Sim          |
| RQ41 | Garantir uptime de 99,5% para funções críticas                                                                        | AI28                 | RNF       | Sim          |
| RQ42 | Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet)                                    | AI24                 | RNF       | Sim          |
| RQ43 | Interface intuitiva, com navegação fácil e boa usabilidade                                                            | IS28                 | RNF       | Sim          |
| RQ44 | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão                              | IS35, AI25, ST05           | RNF       | Não          |
| RQ45 | Contraste de interface conforme WCAG A/AA                                                                             | AI25                 | RNF       | Não          |
| RQ46 | Garantir legenda clara para cores e ícones no mapa de assentos                                                        | AI22                 | RNF       | Sim          |
| RQ47 | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos                                      | AI23                 | RNF       | Sim          |
| RQ48 | Proteger dados de pagamento e histórico do usuário com criptografia                                                   | IS32, Q10                 | RNF       | Sim          |
| RQ49 | Autenticação por biometria ou PIN para operações sensíveis                                                            | IS33                 | RNF       | Sim          |
| RQ50 | Notificações push customizáveis pelo usuário                                                                          | IS34                 | RNF       | Não          |
| RQ51 | Exibir mapa de assentos com indicação gráfica clara de ocupação e disponibilidade                                     | IS31                 | RNF       | Sim          |
| RQ52 | Limitar quantidade máxima de 20 unidades por item no Snack Bar                                                        | AI26                 | RNF       | Sim          |
| RQ53 | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra                | AI27                 | RNF       | Sim          |
| RQ54 | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos)                                       | AI33                 | RNF       | Sim          |
| RQ55 | Validar e-mail e senha antes de criação ou redefinição de conta                                                       | AI34                 | RNF       | Sim          |
| RQ56 | Remover automaticamente promoções expiradas da interface                                                              | AI35                 | RNF       | Sim          |
| RQ57 | Validar dados pessoais no perfil antes de salvar                                                                      | AI36                 | RNF       | Sim          |
| RQ58 | Fornecer comparação de preços entre cinemas.                                                                          | Q04                 | RF       | Não          |
| RQ59 | Fornecer reservas de salas para eventos.                                                                              | Q05                 | RF       | Não          |
| RQ60 | Fornecer um Hub para crítica de filmes.                                                                               | Q06                 | RF       | Não          |
| RQ61 | Manter a conta logada após o login.                                                                                   | Q07                 | RF       | Sim          |
| RQ62 | Permitir que o usuário cancele compras.                                                                               | Q08                 | RF       | Sim          |
| RQ63 | O aplicativo deve ser leve e usar pouca memória do dispositivo.                                                       | Q11                 | RNF       | Sim          |

**Observações:**

- **RQ20:** O login com google e redes sociais ainda não foi implementado.


<font size="3"><p style="text-align: center">Autor(a): [Arthur Evangelista de Oliveira](https://github.com/arthurevg), 2025.</p></font>

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  |  04/05/2025 |  Criação do Documento com Introdução, metodologia, e tabela com os requisitos elicitados |[Arthur Evangelista](https://github.com/arthurevg) | Todos |
| `1.1`  |  04/05/2025 | Ajuste na formatação | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.2`  |  04/05/2025 | Correções na rastreabilidade de alguns itens | [Arthur Evangelista](https://github.com/arthurevg)| [Artur de Camargos](https://github.com/ArturDCR) |
| `1.3`  |  04/05/2025 | Correções na rastreabilidade do RQ38 | [Euller Júlio](https://github.com/Potatoyz908) | [Artur de Camargos](https://github.com/ArturDCR) |

