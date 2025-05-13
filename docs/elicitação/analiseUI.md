# Análise de Interface de Usuário

## Introdução

A análise de interface de usuário (UI) é uma técnica de elicitação de requisitos que visa entender as interações dos usuários com a interface de um sistema. Essa técnica se concentra em avaliar os elementos visuais, fluxos de navegação e comportamentos esperados para garantir que o sistema ofereça uma experiência intuitiva e eficiente. A análise de UI permite identificar requisitos funcionais e não funcionais que melhoram a usabilidade, acessibilidade e a satisfação geral do usuário.

Durante o processo de análise, o engenheiro de requisitos observa a interface e as interações com ela, levando em consideração aspectos como layout, design visual, consistência, feedback ao usuário, entre outros. O objetivo é identificar pontos de melhoria na interface, compreender as expectativas dos usuários e garantir que os requisitos de usabilidade sejam atendidos.

---

## Participantes

| Nome                                                   | Papel                  |
| ------------------------------------------------------ | ----------------------- |
| [Arthur Evangelista de Oliveira](https://github.com/arthurevg) | Analista de requisitos |
| [Euller Júlio da Silva](https://github.com/Potatoyz908) | Analista de requisitos |

---

## Metodologia

A análise de interface de usuário foi realizada de forma colaborativa, com os participantes avaliando diferentes telas do aplicativo *Cinemark*. Para cada tela, foram observados elementos como a disposição dos botões, navegação, feedback visual e interação do usuário com as funcionalidades disponíveis. Os participantes também avaliaram a consistência do design, a facilidade de uso e a acessibilidade do sistema.

A análise foi conduzida de forma qualitativa, sem a utilização de protótipos ou testes com usuários reais. O foco foi identificar pontos de melhoria na interface que poderiam otimizar a experiência do usuário e atender melhor às suas necessidades e expectativas.

---

## Demonstração Visual

A seguir, apresentamos um vídeo demonstrando as telas analisadas na técnica de Análise de Interface de Usuário. A gravação tem como objetivo ilustrar visualmente os elementos de interação, fluxos de navegação e características observadas durante a avaliação.
Ótimo! Se o vídeo está hospedado no **YouTube**, você pode incorporá-lo facilmente na página da Análise de Interface de Usuário com um bloco HTML ou Markdown compatível com MkDocs.

Aqui está o trecho que você pode adicionar **logo após a seção Metodologia**:

---

## Demonstração Visual

A seguir, apresentamos um vídeo demonstrando as principais telas analisadas na técnica de Análise de Interface de Usuário. A gravação tem como objetivo ilustrar visualmente os elementos de interação, fluxos de navegação e características observadas durante a avaliação.

<div style="text-align: center;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/zF4ibDKKBdE" frameborder="0" allowfullscreen></iframe>
</div>
<div style="text-align: center;">
Gravado por <a href="https://github.com/Potatoyz908" target="_blank">Euller Júlio</a>.
</div>

> O vídeo apresenta exemplos reais das interações observadas no app Cinemark, como tela inicial, seleção de sessões, escolha de assentos, navegação pelo catálogo de filmes, uso do Snack Bar, login, pagamento, carrinho e configurações de perfil.

---

## Tabela 1 - de Análise de Telas

| Tela                                | Responsável | Funcionalidades                                                                                                                                  | Elementos de Interação                                                                                                            | Observações / Regras de Negócio                                                                                                                                             |
| ----------------------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Tela inicial (home)                |[Arthur Evangelista de Oliveira](https://github.com/arthurevg)     | Exibir filmes em cartaz, novidades, ofertas, parcerias; acessar notificações, pedidos e carrinho; alterar localização.                          | Carrossel de filmes, ofertas, promoções e anúncios, botões de navegação inferior (Home, Filmes, Cinemas, Snack Bar, Club, Mais), ícones de localização, notificações, carrinho e pedidos. | O botão de pedidos é pequeno e sobreposto a anúncios; idealmente deveria estar em aba separada.                                                                             |
| Login                               |[Arthur Evangelista de Oliveira](https://github.com/arthurevg)     | Autenticar usuário.                                                                                                                               | Campos de e-mail/senha, botão de login, link para cadastro e recuperação de senha.                                                 | Exige e-mail válido e senha correta.                                                                                                                                         |
| Catálogo de filmes                  |[Arthur Evangelista de Oliveira](https://github.com/arthurevg)     | Buscar filmes pelo nome; listar filmes em cartaz, em pré-venda e futuros lançamentos.                                                             | Botão de busca; Lista de filmes com imagem, botão de seleção, filtros (cartaz, pré-venda, em breve).                             | Filmes em cartaz ou pré-venda direcionam para fluxo de compra; futuros lançamentos mostram apenas informações.                                                            |
| Seleção de poltronas               |[Arthur Evangelista de Oliveira](https://github.com/arthurevg)     | Permitir ao usuário escolher os assentos desejados na sala selecionada.                                                                           | Mapa visual da sala de cinema com representação fiel da disposição dos assentos; Cores/ícones diferenciando assentos: Disponíveis, ocupados, selecionados, especiais (ex: cadeirantes); Legenda com explicação das cores; Informações da sessão (filme, local, sala, data e horário) no topo da tela. | Deve ser possível selecionar mais de um assento por vez; O layout da sala muda conforme a planta de sala; Não deve permitir continuar sem selecionar ao menos um assento; |
| Seleção de Ingressos               |[Arthur Evangelista de Oliveira](https://github.com/arthurevg)     | Permitir ao usuário definir o tipo de ingresso (inteira, meia, parceria, voucher etc.) para cada assento selecionado.                             | Lista de ingressos com opções de categoria (inteira, meia-entrada, convênio, voucher); Campo de seleção de tipo de ingresso por assento; Preço de cada tipo de ingresso ao lado da opção; Informações da sessão (filme, data, hora, sala, cinema) visíveis na tela; Botão de continuar (prossegue para o Snack Bar); | Os preços variam conforme o tipo de ingresso e convênios disponíveis; Não é possível continuar sem definir o tipo para todos os assentos selecionados;                      |
| Snack Bar                          |[Arthur Evangelista de Oliveira](https://github.com/arthurevg)     | Permitir que o usuário adicione produtos alimentícios (pipoca, refrigerante, combos etc.) à sua compra antes do pagamento.                        | Lista de produtos divididos por categorias: Pipocas, Bebidas, Doces, Combos; Imagem de cada item com nome, descrição (opcional), preço e botão de adicionar/remover quantidade; | O usuário pode seguir sem adicionar nenhum item (opção "Pular"); Combos podem ter descontos em relação à compra dos itens separadamente; Quantidade máxima por item pode ser limitada. |
| Meus ingressos                     |[Arthur Evangelista de Oliveira](https://github.com/arthurevg)     | Acessar ingressos comprados.                                                                                                                      | Lista de ingressos, botão para exibição das informações do ingresso                                                                | Disponível somente após confirmação do pagamento.                                                                                                                           |
| Pagamento                          |[Euller Júlio da Silva](https://github.com/Potatoyz908)     | Finalizar a compra dos ingressos e produtos selecionados, informando valor total, método de pagamento e confirmação.                              | Resumo da compra (ingressos, snack bar, sessão); Campo para aplicar cupom de desconto; Valor total da compra atualizado com ou sem cupom; Botões de método de pagamento: Cartão de crédito, cartão de débito e pix; Campos de preenchimento de dados do cartão (caso necessário); Botão “Confirmar pagamento”; | Ao concluir o pagamento, os ingressos são salvos automaticamente na tela “Meus pedidos”; Pagamentos por Pix devem gerar QR Code e chave copia e cola chave Pix.               |
| Cadastro / criar conta             |[Euller Júlio da Silva](https://github.com/Potatoyz908)     | Permitir criação de conta com dados pessoais e confirmação por e-mail.                                                                            | Campos: nome, como gostaria de ser chamado, data de nascimento, e-mail, telefone, CPF (opção de usar para nota fiscal), cidade, senha; botão "Cadastrar". | Após clicar em "Cadastrar", envia código de confirmação para o e-mail; após confirmação, sugere ativar biometria com opção de fazer depois.                                 |
| Recuperar email/senha              |[Euller Júlio da Silva](https://github.com/Potatoyz908)     | Permitir recuperar e-mail pelo CPF ou redefinir senha.                                                                                            | Opções na tela de login: "Recuperar meu e-mail" e "Esqueci minha senha"; campo CPF (para recuperar e-mail); botões "Ok" e "Caso tenha esquecido sua senha, clique aqui"; campo e-mail (para redefinir senha); envio de código para confirmação. | Para recuperar e-mail, exibe e-mail mascarado e retorna para a tela de login; para redefinir senha, solicita e-mail e envia código de verificação para permitir definir nova senha. |
| Seleção de sessão e horário        |[Euller Júlio da Silva](https://github.com/Potatoyz908)     | Permitir ao usuário escolher uma sessão específica de um filme selecionado.                                                                       | Lista de sessões com: Horário da sessão; Tipo de sala (Ex: XD, IMAX); Idioma (dublado ou legendado); Tipo de exibição (2D ou 3D); Nome do cinema; | Deve exibir as sessões apenas do cinema definido pela localização do usuário; O redirecionamento após a escolha da sessão deve passar automaticamente os dados da sessão para a tela seguinte. |
| Carrinho                           |[Euller Júlio da Silva](https://github.com/Potatoyz908)     | Exibir resumo da compra, permitir aplicar cupom de desconto, prosseguir para pagamento.                                                          | Lista de itens (ingressos, produtos do Snack Bar); botão "Adicionar cupom de desconto"; botão "Prosseguir para pagamento"; subtotal e total atualizados automaticamente | Deve atualizar o valor total conforme itens e cupons aplicados; permite remoção de itens do carrinho; não permite prosseguir se o carrinho estiver vazio.                  |
| Perfil / Configurações             |[Euller Júlio da Silva](https://github.com/Potatoyz908)     | Permitir acesso a configurações e personalização da conta.                                                                                        | Menu “Mais” com as opções: Pedidos, Notificações, Meus dados, Senha e biometria, Pagamento, Promoções, Termos e Condições, Atendimento, Sobre o app, Avaliar na Google Play | Cada opção leva a uma tela específica; permite editar dados pessoais, alterar senha, ativar/desativar biometria e gerenciar métodos de pagamento; acesso a suporte e informações legais. |
| Notificações / promoções           |[Euller Júlio da Silva](https://github.com/Potatoyz908)     | Exibir notificações recentes e promoções disponíveis.                                                                                             | Lista de notificações e promoções com título, descrição e, em alguns casos, imagem; botão ou link “Ver mais”                      | Promoções possuem validade e podem desaparecer após expirar; algumas notificações direcionam para páginas específicas (como filmes ou eventos).                               |

<font size="3"><p style="text-align: center">Fonte: [Arthur Evangelista de Oliveira](https://github.com/arthurevg) e [Euller Júlio da Silva](https://github.com/Potatoyz908), 2025.</p></font>

---

## Requisitos Elicitados
Os requisitos elicitados a partir da análise de interfaces de usuário foram organizados de forma estruturada para facilitar a visualização do comportamento esperado do sistema. As tabelas 2 e 3 apresentam os Requisitos Funcionais (RF) e os não funcionais (RNF) identificados, agrupados por tela, com suas respectivas funcionalidades, elementos de interação e regras de negócio observadas durante a atividade de avaliação.

---

## Legenda das Tabelas 2 e 3

- *RF*: Requisito Funcional  
- *RNF*: Requisito Não Funcional  
- *AIx*: Requisito elicitado por Análise de Interface

## Tabela 2 - Requisitos Funcionais


| Tipo | Descrição                                                                                                                            | ID   | Implementado |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------ | ---- | ------------ |
| RF   | O sistema deve exibir filmes em cartaz, novidades, ofertas e parcerias na tela inicial.                                              | AI01 | Sim          |
| RF   | O sistema deve permitir alterar manualmente a localização do usuário.                                                                | AI02 | Sim          |
| RF   | O sistema deve permitir navegação por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais.                                           | AI03 | Sim          |
| RF   | O sistema deve autenticar o usuário por e-mail e senha.                                                                              | AI04 | Sim          |
| RF   | O sistema deve permitir busca de filmes por nome.                                                                                    | AI05 | Sim          |
| RF   | O sistema deve listar filmes em cartaz, pré-venda e futuros lançamentos.                                                             | AI06 | Sim          |
| RF   | O sistema deve exibir informações dos filmes (nome, gênero, duração, sinopse, direção, elenco, distribuidor e origem).               | AI07 | Sim          |
| RF   | O sistema deve permitir ao usuário escolher uma sessão específica (data, horário, sala, tipo de exibição e idioma).                  | AI08 | Sim          |
| RF   | O sistema deve exibir um mapa visual da sala com opções de assentos diferenciadas (disponíveis, ocupados, selecionados e especiais). | AI09 | Sim          |
| RF   | O sistema deve obrigar a seleção de ao menos um assento antes de prosseguir.                                                         | AI10 | Sim          |
| RF   | O sistema deve permitir definir o tipo de ingresso para cada assento (inteira, meia, convênio, voucher).                             | AI11 | Sim          |
| RF   | O sistema deve permitir adicionar produtos do Snack Bar à compra.                                                                    | AI12 | Sim          |
| RF   | O sistema deve exibir resumo da compra e permitir aplicação de cupom de desconto.                                                    | AI13 | Sim          |
| RF   | O sistema deve oferecer métodos de pagamento: cartão de crédito, débito e Pix.                                                       | AI14 | Sim          |
| RF   | O sistema deve gerar QR Code e chave Pix para pagamentos via Pix.                                                                    | AI15 | Sim          |
| RF   | O sistema deve salvar automaticamente os ingressos na seção "Meus Ingressos" após confirmação do pagamento.                          | AI16 | Sim          |
| RF   | O sistema deve permitir criação de conta com nome, e-mail e senha.                                                                   | AI17 | Sim          |
| RF   | O sistema deve enviar link de recuperação de senha para e-mail cadastrado.                                                           | AI18 | Sim          |
| RF   | O sistema deve permitir recuperar e-mail do usuário através do CPF.                                                                  | AI19 | Sim          |
| RF   | O sistema deve permitir redefinir senha com envio de código de verificação por e-mail.                                               | AI20 | Sim          |
| RF   | O sistema deve exibir o resumo da compra no carrinho e permitir aplicar cupom de desconto.                                           | AI29 | Sim          |
| RF   | O sistema deve impedir o avanço para pagamento com carrinho vazio.                                                                   | AI30 | Sim          |
| RF   | O sistema deve permitir editar dados pessoais, alterar senha e gerenciar métodos de pagamento no perfil/configurações.               | AI31 | Sim          |
| RF   | O sistema deve exibir notificações e promoções com título, descrição e validade.                                                     | AI32 | Sim          |

<font size="3"><p style="text-align: center">Fonte: [Arthur Evangelista de Oliveira](https://github.com/arthurevg) e [Euller Júlio da Silva](https://github.com/Potatoyz908), 2025.</p></font>

## Tabela 3 - Requisitos Não Funcionais

| Tipo | Descrição                                                                                                              | ID   | Implementado |
| ---- | ---------------------------------------------------------------------------------------------------------------------- | ---- | ------------ |
| RNF  | O sistema deve garantir que o botão de pedidos não fique sobreposto a anúncios na tela inicial.                        | AI21 | Não          |
| RNF  | O sistema deve apresentar legenda clara para as cores e ícones do mapa de assentos.                                    | AI22 | Sim          |
| RNF  | O sistema deve atualizar automaticamente o valor total conforme seleção de ingressos e produtos.                       | AI23 | Sim          |
| RNF  | O sistema deve ser responsivo e ajustar-se a diferentes tamanhos de tela (smartphone e tablet).                        | AI24 | Sim          |
| RNF  | O sistema deve assegurar contraste adequado de texto e ícones para acessibilidade (WCAG A/AA).                         | AI25 | Não          |
| RNF  | O sistema deve permitir no máximo 20 unidades por item no Snack Bar.                                                   | AI26 | Sim          |
| RNF  | O sistema deve manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra. | AI27 | Sim          |
| RNF  | O sistema deve garantir uptime de 99,5% para funções críticas (compra e pagamento).                                    | AI28 | Sim          |
| RNF  | O sistema deve ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos).                        | AI33 | Sim          |
| RNF  | O sistema deve validar e-mails e senhas antes de permitir a redefinição ou criação de conta.                           | AI34 | Sim          |
| RNF  | O sistema deve garantir que promoções expiradas sejam removidas automaticamente da tela de notificações.               | AI35 | Sim          |
| RNF  | O sistema deve garantir que dados pessoais editados no perfil sejam validados antes de serem salvos.                   | AI36 | Sim          |

<font size="3"><p style="text-align: center">Fonte: [Arthur Evangelista de Oliveira](https://github.com/arthurevg) e [Euller Júlio da Silva](https://github.com/Potatoyz908), 2025.</p></font>

---

## Bibliografia
> 1. Cinemark Brasil. Disponível em: <https://www.cinemark.com.br>. Acesso em: 3 maio 2025.
> 2. WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 03/04/2025 | Criação da página 'Análise de UI', contendo introdução, metodologia, análise e os requisitos elicitados | [Arthur Evangelista](https://github.com/arthurevg) e [Euller Júlio](https://github.com/Potatoyz908) | [Davi Camilo](https://github.com/Davicamilo23) e [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.1`  | 04/05/2025 | Ajuste na formatação | [Davi Camilo](https://github.com/Davicamilo23) | [Euller Júlio](https://github.com/Potatoyz908) |
| `1.2`  | 11/05/2025 | Adição da seção "Demonstração Visual" com vídeo no YouTube sobre as interações analisadas | [Euller Júlio](https://github.com/Potatoyz908) | [Arthur Evangelista](https://github.com/arthurevg) |
