# Three Level Scale

## Introdução

A **Three Level Scale** (Escala de Três Níveis) é uma técnica simples e eficaz para priorizar requisitos em projetos de software ou gestão de produtos. Ela classifica os requisitos em três categorias distintas com base em sua **importância** e **urgência**, permitindo que as equipes foquem no que é essencial para o sucesso do projeto.

A priorização é definida pela combinação de **importância** (contribuição para objetivos estratégicos) e **urgência** (necessidade de entrega imediata). Cada requisito é classificado em uma das quatro categorias, sendo três delas prioritárias:

|  | **Importante**          | **Não Importante**       |
|---|-------------------------|--------------------------|
| **Urgente**             | **Alta Prioridade**      | **Não Fazer!**          |
| **Não Urgente**         | **Média Prioridade**     | **Baixa Prioridade**    |

### Detalhamento das Categorias:
1. **Alta Prioridade**
   - **Critérios**: Requisitos **importantes** e **urgentes**.
   - **Exemplos**:
     - Necessários para conformidade legal ou contratual.
     - Capacidades críticas para o próximo lançamento (ex: funcionalidade essencial do MVP).
     - Impactam diretamente os resultados do negócio se não forem entregues.

2. **Média Prioridade**
   - **Critérios**: Requisitos **importantes**, mas **não urgentes**.
   - **Exemplos**:
     - Funcionalidades valorizadas pelos clientes, mas que podem ser adiadas para uma versão futura.
     - Melhorias que agregam valor, mas não bloqueiam o lançamento inicial.

3. **Baixa Prioridade**
   - **Critérios**: Requisitos **não importantes** e **não urgentes**.
   - **Exemplos**:
     - Recursos "desejáveis" que os clientes podem viver sem (ex: temas personalizados).
     - Melhorias incrementais sem impacto significativo no sucesso do produto.

4. **Não Fazer!**
   - **Critérios**: Requisitos **urgentes** (por pressão política ou stakeholders), mas **não importantes**.
   - **Recomendação**: Ignorar ou descartar, pois não contribuem para os objetivos estratégicos.

---

## Metodologia

Após estudo da técnica, entramos em contato, e marcamos uma reunião, com um cliente. Desta forma, garantindo que relevância e peso real para as classificações de cada requisito. Na reunião foi utilizado um quadro virtual do Miro para auxílio visual.

---

## Cronograma

A tabela 1 apresenta o cronograma da priorização e as funções dos membros responsáveis pela técnica.

<font size="3"><p style="text-align: center">Tabela 1: Cronograma do Three Level Scale.</p></font>

| Nome                                                   | Data       | Função                 |
| ------------------------------------------------------ | ---------- | ---------------------- |
| [Davi Camilo Menezes](https://github.com/Davicamilo23) | 04/05/2025 | Mediador |
| [Gabriel Henrique Castelo Costa](https://github.com/GabrielCastelo-31) | 04/05/2025 | Mediador |
| [Pedro Everton de Paula](https://github.com/pedroeverton217) | 04/05/2025 | Mediador |
| João Victor Marques | 04/05/2025 | Usuário do aplicativo |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

---

## Gravação com Usuário

<iframe width="560" height="315" src="https://www.youtube.com/embed/uQsFbIhIGkc?si=jYnT16yrmblp8EBd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
---

## Tabela 2 - Priorização dos Requisitos

| ID   | Descrição                                                                                                             | Prioridade | Rastreabilidade |
| ---- | --------------------------------------------------------------------------------------------------------------------- | --- | --- |
| RQ01  | Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções.                                          | ALTA | [IS01](../elicitação/introspecção.md#IS01), [AI01](../elicitação/analiseUI.md#AI01)            |
| RQ02  | Detectar localização automaticamente e permitir alteração manual.                                                      | NÃO FAZER | [IS02](../elicitação/introspecção.md#IS02), [AI02](../elicitação/analiseUI.md#AI02)            |
| RQ03  | Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais.                                                       | ALTA | [AI03](../elicitação/analiseUI.md#AI03)                 |
| RQ04  | Autenticar usuário por e-mail e senha.                                                                                 | ALTA | [AI04](../elicitação/analiseUI.md#AI04)                 |
| RQ05  | Buscar filmes por nome.                                                                                                |ALTA| [AI05](../elicitação/analiseUI.md#AI05)                 |
| RQ06  | Listar filmes em cartaz, pré-venda e futuros lançamentos.                                                              | ALTA | [AI06](../elicitação/analiseUI.md#AI06)                 |
| RQ07  | Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem).                 | NÃO FAZER | [IS03](../elicitação/introspecção.md#IS03), [AI07](../elicitação/analiseUI.md#AI07)            |
| RQ08  | Exibir sessões com data, horário, idioma, formato e sala.                                                              | ALTA | [IS04](../elicitação/introspecção.md#IS04), [ST01](../elicitação/storytelling.md#ST01), [AI08](../elicitação/analiseUI.md#AI08), [Q01](../elicitação/questionario.md#Q01)      |
| RQ09  | Permitir compra de ingressos com cartão de crédito, débito ou Pix.                                                     | ALTA | [IS05](../elicitação/introspecção.md#IS05), [AI14](../elicitação/analiseUI.md#AI14), [Q02](../elicitação/questionario.md#Q02)            |
| RQ10 | Armazenar cartões de pagamento cadastrados para uso em compras futuras.                                                | NÃO FAZER | [IS06](../elicitação/introspecção.md#IS06)                  |
| RQ11 | Permitir compra de múltiplos ingressos em uma única transação.                                                         | ALTA | [IS07](../elicitação/introspecção.md#IS07)                  |
| RQ12 | Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais, e permitir seleção pelos usuários. | ALTA | [IS08](../elicitação/introspecção.md#IS08), [AI09](../elicitação/analiseUI.md#AI09)            |
| RQ13 | Exigir seleção de ao menos um assento antes de prosseguir.                                                             | MÉDIA | [AI10](../elicitação/analiseUI.md#AI10)                 |
| RQ14 | Definir tipo de ingresso por assento (inteira, meia, convênio, voucher).                                               | ALTA | [AI11](../elicitação/analiseUI.md#AI11)                 |
| RQ15 | Integrar bomboniere ao app para compra antecipada de itens e retirada rápida.                                          | MÉDIA | [IS11](../elicitação/introspecção.md#IS11), [AI12](../elicitação/analiseUI.md#AI12)           |
| RQ16 | Exibir resumo da compra e permitir aplicação de cupom de desconto.                                                     | ALTA | [AI13](../elicitação/analiseUI.md#AI13), [AI29](../elicitação/analiseUI.md#AI29)           |
| RQ17 | Gerar QR Code e chave Pix para pagamentos via Pix.                                                                     | MÉDIA | [AI15](../elicitação/analiseUI.md#AI15)                 |
| RQ18 | Disponibilizar ingresso digital no app, eliminando a necessidade de impressão.                                         | ALTA | [IS09](../elicitação/introspecção.md#IS09), [ST03](../elicitação/storytelling.md#ST03)                  |
| RQ19 | Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra.                                | ALTA | [AI16](../elicitação/analiseUI.md#AI16)                 |
| RQ20 | Permitir criação de conta (nome, e-mail, senha, CPF) e login com Google/redes sociais.                                 | MÉDIA | [AI17](../elicitação/analiseUI.md#AI17), [IS26](../elicitação/introspecção.md#IS26)           |
| RQ21 | Recuperação de conta: enviar link de redefinição de senha por e-mail, recuperar e-mail via CPF e redefinir com código. | ALTA | [AI18](../elicitação/analiseUI.md#AI18), [AI19](../elicitação/analiseUI.md#AI19), [AI20](../elicitação/analiseUI.md#AI20)     |
| RQ22 | Exibir histórico de filmes assistidos (data, horário, cinema) e histórico de compras na bomboniere.                    | BAIXA | [IS13](../elicitação/introspecção.md#IS13), [IS14](../elicitação/introspecção.md#IS14)           |
| RQ23 | Filtrar filmes por categoria e exibir avaliações de público e plataformas externas.                                    | NÃO FAZER | [IS15](../elicitação/introspecção.md#IS15)                 |
| RQ24 | Exibir trailers dentro do app.                                                                                         | BAIXA | [IS16](../elicitação/introspecção.md#IS16)                 |
| RQ25 | Oferecer fluxo de compra simplificado, com o mínimo de toques até a confirmação.                                       | ALTA | [IS17](../elicitação/introspecção.md#IS17)                 |
| RQ26 | Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc).                      |BAIXA | [IS18](../elicitação/introspecção.md#IS18)                 |
| RQ27 | Permitir uso de pontos acumulados para desconto em ingressos e produtos.                                               | NÃO FAZER| [IS19](../elicitação/introspecção.md#IS19), [Q03](../elicitação/questionario.md#Q03)                 |
| RQ28 | Alertar usuário sobre pontos suficientes para ingresso grátis e antes da expiração.                                    |NÃO FAZER| [IS20](../elicitação/introspecção.md#IS20)                 |
| RQ29 | Sugerir cinemas com base no histórico de visitas e na localização atual.                                               |MÉDIA| [IS21](../elicitação/introspecção.md#IS21)                 |
| RQ30 | Permitir que o usuário salve cinemas como favoritos.                                                                   | MÉDIA| [IS22](../elicitação/introspecção.md#IS22)                 |
| RQ31 | Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”).                              | BAIXA| [IS23](../elicitação/introspecção.md#IS23)                 |
| RQ32 | Exibir recomendações de filmes baseadas em histórico e preferências.                                                   |NÃO FAZER| [IS24](../elicitação/introspecção.md#IS24)                 |
| RQ33 | Permitir alteração de preferências de idioma.                                                                          |ALTA| [IS25](../elicitação/introspecção.md#IS25)                 |
| RQ34 | Disponibilizar área dedicada ao Cinemark Club: ingressos, pontos acumulados e validade.                                |MÉDIA| [IS12](../elicitação/introspecção.md#IS12)                 |
| RQ35 | Exibir notificações e promoções com título, descrição e validade.                                                      |MÉDIA| [AI32](../elicitação/analiseUI.md#AI32)                 |
| RQ36 | Impedir avanço para pagamento com carrinho vazio.                                                                      |ALTA| [AI30](../elicitação/analiseUI.md#AI30)                 |
| RQ37 | Criar e editar perfil do usuário, gerenciar dados pessoais e métodos de pagamento.                                     |ALTA| [AI31](../elicitação/analiseUI.md#AI31)                 |
| RQ38 | Mensagens de erro claras e confirmações de ações para o usuário.                                                       |ALTA| [ST05](../elicitação/storytelling.md#ST05), [IS37](../elicitação/introspecção.md#IS37) |
| RQ39 | Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas.                                 |NÃO FAZER| [IS15](../elicitação/introspecção.md#IS15)|
| RQ40 | Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento).                                |ALTA| [IS29](../elicitação/introspecção.md#IS29), [Q09](../elicitação/questionario.md#Q09), [Q12](../elicitação/questionario.md#Q12)                 |
| RQ41 | Garantir uptime de 99,5% para funções críticas.                                                                        |ALTA| [AI28](../elicitação/analiseUI.md#AI28)                 |
| RQ42 | Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet).                                    | ALTA| [AI24](../elicitação/analiseUI.md#AI24)                 |
| RQ43 | Interface intuitiva, com navegação fácil e boa usabilidade.                                                            | ALTA| [IS28](../elicitação/introspecção.md#IS28)                 |
| RQ44 | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixo-visão.                              |ALTA| [IS35](../elicitação/introspecção.md#IS35), [IS36](../elicitação/introspecção.md#IS36), [AI25](../elicitação/analiseUI.md#AI25), [ST05](../elicitação/storytelling.md#ST05)           |
| RQ45 | Contraste de interface conforme WCAG A/AA.                                                                             |ALTA| [AI25](../elicitação/analiseUI.md#AI25)                 |
| RQ46 | Garantir legenda clara para cores e ícones no mapa de assentos.                                                        |NÃO FAZER| [AI22](../elicitação/analiseUI.md#AI22)                 |
| RQ47 | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos.                                      |NÃO FAZER| [AI23](../elicitação/analiseUI.md#AI23)                 |
| RQ48 | Proteger dados de pagamento e histórico do usuário com criptografia.                                                   |ALTA| [IS32](../elicitação/introspecção.md#IS32), [Q10](../elicitação/questionario.md#Q10)                 |
| RQ49 | Autenticação por biometria ou PIN para operações sensíveis.                                                            |ALTA| [IS33](../elicitação/introspecção.md#IS33)                 |
| RQ50 | Notificações push customizáveis pelo usuário.                                                                          | BAIXA| [IS34](../elicitação/introspecção.md#IS34)                 |
| RQ51 | Exibir mapa de assentos com indicação gráfica clara de ocupação e disponibilidade.                                     |ALTA| [IS31](../elicitação/introspecção.md#IS31)                 |
| RQ52 | Limitar quantidade máxima de 20 unidades por item no Snack Bar.                                                        |NÃO FAZER| [AI26](../elicitação/analiseUI.md#AI26)                 |
| RQ53 | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra.                |BAIXA| [AI27](../elicitação/analiseUI.md#AI27)                 |
| RQ54 | Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos).                                       |ALTA| [AI33](../elicitação/analiseUI.md#AI33)                 |
| RQ55 | Validar e-mail e senha antes de criação ou redefinição de conta.                                                       |ALTA| [AI34](../elicitação/analiseUI.md#AI34)                 |
| RQ56 | Remover automaticamente promoções expiradas da interface.                                                              |ALTA| [AI35](../elicitação/analiseUI.md#AI35)                 |
| RQ57 | Validar dados pessoais no perfil antes de salvar.                                                                      |ALTA| [AI36](../elicitação/analiseUI.md#AI36)                 |

---

## Conclusão

Dos 57 requisitos elicitados, 6 foram classificados com Baixa prioridade, 7 classificados com Média prioridade, 13 classificados como Não Fazer, e 31 classificados com Alta prioridade.

---

## Bibliografia

> WIEGERS, K; BEATTY, J. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.

---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 04/05/2025 | Criação do Documento | [Davi](https://github.com/Davicamilo23) | Todos |
| `1.1`  | 04/05/2025 | Realização da Técnica e Registro dos Resultados | [Pedro Everton](https://github.com/pedroeverton217), [Davi Camilo](https://github.com/Davicamilo23) e [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.2` | 13/05/2025 | Correção na Bibliografia | [Pedro Everton](https://github.com/pedroeverton217) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.3`  | 13/05/2025 | Adição do cronograma da técnica, ajuste na tabela 2 e adição da rastreabilidade | [Davi Camilo](https://github.com/Davicamilo23) | [Pedro Everton](https://github.com/pedroeverton217) |
| `1.3.1`  | 14/05/2025 | Correção do link da reunião| [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Pedro Everton](https://github.com/pedroeverton217) |
