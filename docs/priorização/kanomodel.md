# Modelo Kano

## Introdução

A técnica de priorização Kano é uma abordagem voltada para entender o impacto emocional dos requisitos no usuário final. Desenvolvida por Noriaki Kano, essa técnica classifica os requisitos com base em como eles influenciam a satisfação ou a insatisfação do cliente. Em vez de apenas considerar fatores técnicos ou de negócio, o modelo foca em como cada funcionalidade pode surpreender, agradar, ser esperada ou até mesmo gerar frustração.

As categorias principais do modelo são:

- **Basic Needs (Necessidades Básicas)**: requisitos essenciais que o usuário espera. A ausência causa insatisfação; a presença é simplesmente “o mínimo” e não gera encantamento.  
- **Satisfiers (Satisfação)**: funcionalidades cujo grau de desempenho se traduz diretamente em satisfação. Quanto melhor forem, mais satisfeito o usuário ficará.  
- **Delight (Encantamento)**: recursos inesperados que surpreendem positivamente o usuário. Não são esperados, mas sua presença eleva muito a percepção de valor do sistema.  
- **Indifferent (Indiferente)**: aspectos que não afetam a satisfação ou insatisfação do usuário, independentemente de estarem presentes ou ausentes.  
- **Reverse (Reverso)**: características que, quando presentes, podem gerar insatisfação em alguns usuários e, quando ausentes, podem causar satisfação em outros.

---

## Metodologia

Para a aplicação da técnica de priorização do modelo Kano, foi desenvolvido um questionário com base nos critérios definidos para os requisitos do sistema. O questionário foi disponibilizado para um grupo de usuários selecionados, que responderam de acordo com suas preferências e expectativas sobre as funcionalidades do sistema. As respostas foram então analisadas para categorizar as funcionalidades em diferentes categorias do modelo Kano, como é possíver observar na tabela 1.


 <figure>
    <font size="3"><p style="text-align: center"><b>Figura 1</b>: Tabela do Modelo Kano</p></font>
    <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/kanoModel/tabelaKano.png" alt="Tabela do modelo kano cada dado cruzado leva a uma característica Ksno diferente">
    <figcaption>Fonte: <a href="https://www.interaction-design.org/literature/article/the-kano-model-a-tool-to-prioritize-the-users-wants-and-desires">The Kano Model – A tool to prioritize the users’ wants and desires</a>, 2025.</figcaption>
</figure> 
---

## Link da gravação da sessão

<iframe 
  width="560" 
  height="315" 
  src="https://www.youtube.com/embed/eQLjzQcJc6Y" 
  title="YouTube video player" 
  frameborder="0" 
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
  allowfullscreen>
</iframe>

---

## Priorização 



### Legenda da Tabela 1

- **ID**: Identificador único do requisito.  
- **Descrição**: Texto que descreve o requisito de forma clara e objetiva.  
- **Rastreabilidade**: Código(s) de origem de onde o requisito foi elicitado (por introspecção _ISx_, por análise de interface _AIx_, por estudo de caso _STx_, etc.).  
- **Categoria**: Tipo de requisito (RF = Requisito Funcional).  
- **Classificação**: Classificação do requisito segundo o Modelo Kano:
  - **Básico** (Basic Needs): ausência causa insatisfação, presença não gera entusiasmo.  
  - **Satisfatório** (Satisfiers): satisfação cresce à medida que o desempenho aumenta.  
  - **Encantador** (Delight): surpresa positiva, não esperada, gera alto impacto.  
  - **Indiferente** (Indifferent): presença ou ausência não altera a satisfação.  
  - **Reverso** (Reverse): presença pode gerar insatisfação em parte dos usuários.

### Tabela 1 – Requisitos Priorizados conforme Modelo Kano(Versão 1)

| ID   | Descrição                                                                                                             | Rastreabilidade      | Categoria | Classificação |
| ---- | --------------------------------------------------------------------------------------------------------------------- | -------------------- | --------- | ------------ |
| RQ1  | Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções                                          | IS1, AI01            | RF        | Básico          |
| RQ2  | Detectar localização automaticamente e permitir alteração manual                                                      | IS2, AI02            | RF        | Indiferente          |
| RQ3  | Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais                                                       | AI03                 | RF        | Básico          |
| RQ4  | Autenticar usuário por e-mail e senha                                                                                 | AI04                 | RF        | Básico         |
| RQ5  | Buscar filmes por nome                                                                                                | AI05                 | RF        | Satisfatório          |
| RQ6  | Listar filmes em cartaz, pré-venda e futuros lançamentos                                                              | AI06                 | RF        | Encantador          |
| RQ7  | Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem)                 | IS3, AI07            | RF        | Básico          |
| RQ8  | Exibir sessões com data, horário, idioma, formato e sala                                                              | IS4, ST01, AI08      | RF        | Básico          |
| RQ9  | Permitir compra de ingressos com cartão de crédito, débito ou Pix                                                     | IS5, AI14            | RF        | Básico          |
| RQ10 | Armazenar cartões de pagamento cadastrados para uso em compras futuras                                                | IS6                  | RF        | Indiferente          |
| RQ11 | Permitir compra de múltiplos ingressos em uma única transação                                                         | IS7                  | RF        | Básico          |
| RQ12 | Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais, e permitir seleção pelos usuários | IS8, AI09            | RF        | Básico          |
| RQ13 | Exigir seleção de ao menos um assento antes de prosseguir                                                             | AI10                 | RF        | Básico          |
| RQ14 | Definir tipo de ingresso por assento (inteira, meia, convênio, voucher)                                               | AI11                 | RF        | Básico          |
| RQ15 | Integrar bomboniere ao app para compra antecipada de itens e retirada rápida                                          | IS11, AI12           | RF        | Indiferente         |
| RQ16 | Exibir resumo da compra e permitir aplicação de cupom de desconto                                                     | AI13, AI29           | RF        | Básico          |
| RQ17 | Gerar QR Code e chave Pix para pagamentos via Pix                                                                     | AI15                 | RF        | Básico          |
| RQ18 | Disponibilizar ingresso digital no app, eliminando a necessidade de impressão                                         | IS9                  | RF        | Satisfatório        |
| RQ19 | Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra                                        | AI16                 | RF        | Básico          |
| RQ20 | Permitir criação de conta (nome, e-mail, senha, CPF) e login com Google/redes sociais                                      | AI17, IS26           | RF        | Encantador          |
| RQ21 | Recuperação de conta: enviar link de redefinição de senha por e-mail, recuperar e-mail via CPF e redefinir com código | AI18, AI19, AI20     | RF        | Básico          |
| RQ22 | Exibir histórico de filmes assistidos (data, horário, cinema) e histórico de compras na bomboniere                    | IS13, IS14           | RF        | Indiferente          |
| RQ23 | Filtrar filmes por categoria e exibir avaliações de público e plataformas externas                                    | IS15                 | RF        | Encantador          |
| RQ24 | Exibir trailers dentro do app                                                                                         | IS16                 | RF        | Encantador          |
| RQ25 | Oferecer fluxo de compra simplificado, com o mínimo de toques até a confirmação                                       | IS17                 | RF        | Satisfatório          |
| RQ26 | Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc.)                      | IS18                 | RF        | Satisfatório          |
| RQ27 | Permitir uso de pontos acumulados para desconto em ingressos e produtos                                               | IS19                 | RF        | Satisfatório          |
| RQ28 | Alertar usuário sobre pontos suficientes para ingresso grátis e antes da expiração                                    | IS20                 | RF        | Indiferente          |
| RQ29 | Sugerir cinemas com base no histórico de visitas e na localização atual                                               | IS21                 | RF        | Indiferente          |
| RQ30 | Permitir que o usuário salve cinemas como favoritos                                                                   | IS22                 | RF        | Indiferente         |
| RQ31 | Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”)                              | IS23                 | RF        | Encantador          |
| RQ32 | Exibir recomendações de filmes baseadas em histórico e preferências                                                   | IS24                 | RF        | Indiferente          |
| RQ33 | Permitir alteração de preferências de idioma                                                                          | IS25                 | RF        | Satisfatório          |
| RQ34 | Disponibilizar área dedicada ao Cinemark Club: ingressos, pontos acumulados e validade                                | IS12                 | RF        | Satisfatório          |
| RQ35 | Exibir notificações e promoções com título, descrição e validade                                                      | AI32                 | RF        | Indiferente          |
| RQ36 | Impedir avanço para pagamento com carrinho vazio                                                                      | AI30                 | RF        | Básico         |
| RQ37 | Criar e editar perfil do usuário, gerenciar dados pessoais e métodos de pagamento                                     | AI31                 | RF        | Básico          |
| RQ38 | Mensagens de erro claras e confirmações de ações para o usuário                                                       | ST05, IS28 | RF        | Básico     |
| RQ39 | Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas                                 | IS15| RF        | Encantador         |


<font size="3"><p style="text-align: center">Autores: [Arthur Evangelista de Oliveira](https://github.com/arthurevg) e [Euller Júlio da Silva](https://github.com/Potatoyz908).</p></font>

---

## Bibliografia
 - KANO MODEL. **The Kano Model – A Tool to Prioritize the Users’ Wants and Desires**. Interaction Design Foundation. Disponível em: <https://www.interaction-design.org/literature/article/the-kano-model-a-tool-to-prioritize-the-users-wants-and-desires>. Acesso em: 04 maio 2025.

---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 04/05/2025 | Criação da página 'Kano Model', contendo introdução, metodologia e tabela de priorização de requisitos| [Arthur Evangelista](https://github.com/arthurevg) e [Euller Júlio](https://github.com/Potatoyz908) | Todos |
| `1.1`  | 05/05/2025 | Adição da tabela do Modelo Kano| [Arthur Evangelista](https://github.com/arthurevg)  |[Euller Júlio](https://github.com/Potatoyz908) |
