# Cenários

## Introdução
Os cenários são narrativas textuais que descrevem situações específicas de uso, detalhando as interações entre usuários e sistemas em contextos reais. Segundo Barbosa (2010), eles são ferramentas fundamentais no processo de design de Interação Humano-Computador (IHC), pois permitem compreender as necessidades, comportamentos e objetivos dos usuários, facilitando a concepção de soluções mais alinhadas às suas expectativas. Essas narrativas, escritas em linguagem natural, promovem o envolvimento de todos os stakeholders no processo de desenvolvimento, tornando-se instrumentos eficazes para a comunicação e validação de ideias durante as fases de projeto e avaliação de sistemas interativos.

No contexto do aplicativo Cinemark Digital, os cenários elaborados visam representar de forma detalhada como diferentes perfis de usuários interagem com o sistema para atingir objetivos específicos, como filtrar filmes por categoria, assistir a trailers ou consultar avaliações.

## Metodologia

Os cenários foram criados a partir da análise dos [requisitos levantados](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) na fase de elicitação, mapeando fluxos de uso com base nas descrições de funcionalidades. Cada passo foi revisado internamente pela equipe, garantindo que todas as pré-condições, restrições e exceções estivessem contempladas.


## 2.1 Cenário 1: Filtrar filmes por categoria e exibir avaliações

O primeiro cenário, apresentado na Tabela 1, faz referência ao requisito não-implementado [RQ23](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/): Filtrar filmes por categoria e exibir avaliações de público e plataformas externas.

**Tabela 1: Cenário de filtrar filmes por categoria e exibir avaliações**

| Item     | Descrição                                                                                  |
|-----------|--------------------------------------------------------------------------------------------|
| Objetivo  | Permitir que o usuário encontre filmes disponíveis por categoria e veja suas avaliações.  |
| Contexto  | Local: Tela inicial do aplicativo Cinemark Digital.</br>Tempo: Aproximadamente 1 min.</br>Pré-condição: Existirem filmes cadastrados para a categoria selecionada.                     |
| Atores    | Usuário do aplicativo Cinemark Digital.                                                    |
| Recursos  | Internet; Smartphone com o aplicativo Cinemark Digital instalado.                          |
| Episódios | 1. Usuário seleciona a opção de filtrar filmes na tela inicial.</br>2. Usuário escolhe a categoria desejada.</br>3. Aplicativo exibe filmes da categoria.</br>4. Sistema mostra avaliações de público e de plataformas externas.          |
| Restrições| Usuário só pode filtrar categorias com filmes cadastrados.</br>Aplicativo deve exibir avaliações em tempo real.                                           |
| Exceções  | Erro de conexão à internet: mensagem de falha ao carregar.</br>Sem filmes na categoria: exibe "Nenhum filme disponível nesta categoria".   |

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

## 2.2 Cenário 2: Exibir trailers dentro do app

O segundo cenário, apresentado na Tabela 2, faz referência ao requisito não-implementado [RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/): Exibir trailers dentro do app.

**Tabela 2: Cenário de exibir trailers dentro do app**

| Item     | Descrição                                                                       |
|-----------|---------------------------------------------------------------------------------|
| Objetivo  | Permitir que o usuário visualize trailers de filmes sem sair do aplicativo.     |
| Contexto  | Local: Página de detalhes do filme.</br>Tempo: Aproximadamente 30 s.</br>Pré-condição: Trailer disponível para o filme.                   |
| Atores    | Usuário do aplicativo Cinemark Digital.                                         |
| Recursos  | Internet; Dispositivo móvel com o aplicativo Cinemark Digital instalado.               |
| Episódios | 1. Usuário acessa detalhes do filme.</br>2. Aplicativo exibe botão "Assistir Trailer".</br>3. Usuário toca e reproduz trailer no player incorporado.</br>4. Usuário pode pausar, avançar ou fechar o trailer. |
| Restrições| Trailer deve reproduzir em alta definição compatível.</br>Player deve suportar controles básicos.               |
| Exceções  | Erro de carregamento: exibe "Trailer indisponível no momento".</br>Falha de rede: permite recarregar. |

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

## 2.3 Cenário 3: Reservar salas para eventos

O terceiro cenário, apresentado na Tabela 3, faz referência ao requisito não implementado [RQ59](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Reservar salas para eventos.

**Tabela 3: Cenário de reservar salas para eventos**

| Item       | Descrição                                                                                                                                                                                                                           |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário reserve uma sala de cinema para eventos privados, como aniversários, sessões fechadas ou encontros corporativos.                                                                                             |
| Contexto   | Local: Menu "Mais" > Opção "Reservar Sala".</br>Tempo: 3 a 5 minutos.</br>Pré-condição: Usuário autenticado; existência de salas disponíveis.                                                                                       |
| Atores     | Usuário autenticado.                                                                                                                                                                                                                |
| Recursos   | Internet; aplicativo Cinemark instalado em smartphone.                                                                                                                                                                              |
| Episódios  | 1. Usuário acessa o menu "Mais" e clica em "Reservar Sala".</br>2. Escolhe data, horário e quantidade de pessoas.</br>3. Seleciona uma sala disponível.</br>4. Preenche os dados da reserva.</br>5. Confirma e realiza o pagamento. |
| Restrições | Reserva limitada a salas disponíveis; número mínimo e máximo de pessoas deve ser respeitado.                                                                                                                                        |
| Exceções   | Sem salas disponíveis: sistema sugere datas e horários alternativos.</br>Falha no pagamento: sistema notifica erro e permite nova tentativa.                                                                                        |

<p align="center"><br>
Autor: <a href="https://github.com/Potatoyz908">Euller Júlio</a>, 2025.</p>

## 2.4 Cenário 4: Alterar preferências de idioma

O quarto cenário, apresentado na Tabela 4, faz referência ao requisito não implementado [RQ33](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Permitir alteração de preferências de idioma.

**Tabela 4: Cenário de alterar preferências de idioma**

| Item       | Descrição                                                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário altere o idioma da interface do aplicativo para melhor compreensão e personalização da experiência.                                                                   |
| Contexto   | Local: Menu "Mais" > Configurações > Idioma.</br>Tempo: Cerca de 1 minuto.</br>Pré-condição: Usuário autenticado.                                                                            |
| Atores     | Usuário logado no aplicativo.                                                                                                                                                                |
| Recursos   | Internet; aplicativo Cinemark instalado em dispositivo móvel.                                                                                                                                |
| Episódios  | 1. Usuário acessa a aba "Mais".</br>2. Entra em "Configurações".</br>3. Escolhe "Preferências de Idioma".</br>4. Seleciona novo idioma.</br>5. Confirma alteração e vê interface atualizada. |
| Restrições | O idioma escolhido deve estar disponível no sistema.                                                                                                                                         |
| Exceções   | Idioma não carregado corretamente: sistema mantém idioma anterior e exibe alerta.                                                                                                            |

<p align="center"><br>
Autor: <a href="https://github.com/Potatoyz908">Euller Júlio</a>, 2025.</p>

## 2.5 Cenário 5: Exibir recomendações de filmes baseadas em histórico e preferências

O quinto cenário, apresentado na Tabela 5, faz referência ao requisito não implementado [RQ32](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Exibir recomendações de filmes baseadas em histórico e preferências.

**Tabela 5: Cenário de exibir recomendações de filmes baseadas em histórico e preferências**

| Item           | Descrição                                                                                                                                                                                                                   |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Oferecer ao usuário sugestões de filmes baseadas em seu histórico de visualização e preferências cadastradas.                                                                                                               |
| Contexto   | Local: Página inicial do aplicativo ou seção "Para Você".<br>Tempo: Imediato após login.<br>Pré-condição: Usuário possuir histórico de navegação ou ter informado preferências ao sistema.                                             |
| Atores     | Usuário do aplicativo Cinemark Digital.                                                                                                                                                                                     |
| Recursos   | Conexão com a internet; aplicativo Cinemark Digital instalado e logado com perfil pessoal.                                                                                                                                  |
| Episódios  | 1. Usuário acessa o aplicativo.<br>2. O sistema analisa o histórico e preferências do perfil.<br>3. O sistema exibe recomendações personalizadas com base nesses dados.<br>4. Usuário pode explorar as sugestões apresentadas. |
| Restrições | Recomendação personalizada depende de dados mínimos no histórico.<br>Filmes sugeridos devem estar em cartaz ou em pré-venda.                                                                                                |
| Exceções   | Histórico vazio: sistema exibe sugestões populares ou mais bem avaliadas.<br>Falha na análise de dados: exibe aviso "Não foi possível carregar recomendações".                                                              |

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

## 2.6 Cenário 6: Fornecer comparação de preços entre cinemas

O sexto cenário, apresentado na Tabela 6, faz referência ao requisito não implementado [RQ58](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Fornecer comparação de preços entre cinemas.

**Tabela 6: Cenário de fornecer comparação de preços entre cinemas**

| Item           | Descrição                                                                                                                                                                                                |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário compare os preços de ingressos e combos para um mesmo filme em diferentes cinemas.                                                                                                |
| Contexto   | Local: Página de detalhes do filme ou seleção de sessão.<br>Tempo: Aproximadamente 1 minuto.<br>Pré-condição: Existência de múltiplos cinemas com o filme selecionado em cartaz.                      |
| Atores     | Usuário do aplicativo Cinemark Digital.                                                                                                                                                                  |
| Recursos   | Conexão com a internet; GPS habilitado (opcional para ordenar cinemas por proximidade); aplicativo Cinemark Digital atualizado.                                                                                                         |
| Episódios  | 1. Usuário seleciona um filme.<br>2. O sistema lista cinemas que exibem o filme.<br>3. Usuário solicita comparação de preços.<br>4. O sistema apresenta tabela comparativa com valores de ingresso e combos. |
| Restrições | Sistema só compara preços entre cinemas Cinemark com dados atualizados.<br>Preços devem incluir taxas e promoções aplicáveis.                                                                           |
| Exceções   | Cinema com dados indisponíveis: exibir aviso "Informações de preço indisponíveis para este cinema".<br>Erro de rede: exibir mensagem "Falha ao carregar preços, tente novamente".                        |

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

## 2.7 Cenário 7: Fornecer um Hub para crítica de filmes

O sétimo cenário, apresentado na Tabela 7, faz referência ao requisito não implementado [RQ60](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Fornecer um Hub para crítica de filmes.

**Tabela 7: Cenário para Fornecer um Hub para crítica de filmes.**

| Item       | Descrição                                                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Oferecer aos usuários do aplicativo Cinemark um espaço integrado para criar, compartaltilhar e acessar críticas de filmes, promovendo interação social e auxiliando na decisão de escolha de filmes com base em opiniões de outros espectadores. |
| Contexto   | O aplicativo Cinemark atualmente permite compra de ingressos, consulta de horários de sessões e visualização de trailers. No entanto, não há um espaço dedicado para críticas ou discussões sobre filmes. O Hub de Crítica visa preencher essa lacuna, incentivando a comunidade de cinéfilos a compartilhar análises, avaliações (como notas de 1 a 5) e debates, integrando-se às funcionalidades existentes (ex.: exibição de filmes em cartaz). |
| Atores     | Crítico: Usuário que escreve e publica críticas.<br>Leitor: Usuário que consome críticas e interage com elas (curtidas, comentários).<br>Administrador Cinemark: Responsável por moderar conteúdo e gerenciar o Hub.<br>Sistema do Aplicativo: Processa e armazena críticas, notas e interações. |
| Recursos   | Internet; aplicativo Cinemark instalado em dispositivo móvel. |
| Episódios  | **Acesso ao Hub de Críticas**:<br>1- Usuário abre o app e seleciona "Críticas" no menu de um filme.<br>2- Sistema exibe críticas recentes e avaliação média.<br>3- Usuário visualiza opiniões e decide assistir ao filme.<br><br>**Publicação de uma Crítica**:<br>1- Trigger: Usuário clica em "Escrever Crítica".<br>2- Ação: Preenche texto, adiciona nota, marca spoiler e publica.<br>3- Resultado: Crítica é exibida no filme e em seu perfil.<br><br>**Interação com Críticas**:<br>1- Trigger: Leitor curte ou comenta uma crítica.<br>2- Ação: Sistema registra a interação e notifica o crítico.<br>3- Resultado: Engajamento aumenta a visibilidade da crítica.<br><br>**Moderação de Conteúdo**:<br>1- Trigger: Usuário denuncia uma crítica como inadequada.<br>2- Ação: Administrador avalia e remove conteúdo ofensivo.<br>3- Resultado: Crítica é excluída ou mantida, com feedback ao denunciante. |
| Restrições | **Técnicas**:<br>1- Limite de 500 caracteres por crítica para garantir objetividade.<br>2- Latência máxima de 2 segundos para carregamento de críticas.<br><br>**Negócio**:<br>1- Críticas não podem conter promoção de concorrentes.<br>2- Integração com o design atual do app (sem alterar fluxo de compra).<br><br>**Legais**:<br>1- Cumprimento da LGPD para armazenamento de dados de usuários.<br>2- Proibição de discurso de ódio ou spoilers não marcados. |
| Exceções   | 1- **Falha ao Publicar Crítica**<br>Causa: Perda de conexão com a internet.<br>Ação: Sistema salva rascunho localmente e notifica o usuário.<br><br>2- **Crítica com Conteúdo Inadequado**<br>Causa: Filtro automático não detecta palavrões.<br>Ação: Administrador remove manualmente após denúncia.<br><br>3- **Sobrecarga do Sistema**<br>Causa: Pico de acesso durante lançamento de um filme aguardado.<br>Ação: Sistema prioriza carregamento de críticas mais relevantes (com base em curtidas).<br><br>4- **Avaliação de Filme Não Lançado**<br>Causa: Usuário tenta criticar um filme sem sessões disponíveis.<br>Ação: Sistema bloqueia a publicação até a data de estreia. |

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur De Camargos</a>, 2025.</p>

## 2.8 Cenário 8: Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial

O oitavo cenário, apresentado na Tabela 8, faz referência ao requisito não implementado [RQ67](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.

**Tabela 8: Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.**

| Item       | Descrição                                                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Facilitar e tornar visível o acesso à compra de ingressos no aplicativo Cinemark, garantindo que os usuários encontrem a funcionalidade de forma rápida e intuitiva, com um botão dedicado ou atalho direto no menu inicial. |
| Contexto   | Atualmente, a compra de ingressos está disponível no aplicativo, mas sua localização não é imediatamente visível, exigindo múltiplos cliques ou navegação por menus. Essa mudança visa reduzir etapas e destacar a funcionalidade como prioridade na interface. |
| Atores     | Usuário do Aplicativo: Cliente que deseja comprar ingressos.<br>Equipe de Design/UX: Responsável por implementar a mudança na interface.<br>Sistema do Aplicativo: Exibe o botão/atalho e direciona para a compra. |
| Recursos   | Interface atualizada do aplicativo;<br>Ferramentas de desenvolvimento front-end (ex.: React Native, Figma);<br>Integração com a API de vendas de ingressos. |
| Episódios  | **Acesso Rápido ao Ingresso**:<br>1- Usuário abre o app e visualiza o botão "Comprar Ingresso" no menu inicial.<br>2- Sistema redireciona para a seleção de filme, cinema e sessão.<br>3- Usuário conclui a compra em poucas etapas.<br><br>**Personalização de Atalho**:<br>1- Trigger: Usuário pressiona e segura o ícone do app (atalho).<br>2- Ação: Sistema exibe opção "Comprar Ingresso" no menu de contexto.<br>3- Resultado: Redirecionamento direto para a página de compra. |
| Restrições | **Técnicas**:<br>1- O botão deve ser compatível com todas as versões do app (Android e iOS).<br>2- Tempo de carregamento da página de compra não pode exceder 3 segundos.<br><br>**Negócio**:<br>1- O botão não deve sobrepor anúncios patrocinados.<br>2- Manter o padrão visual da marca (cores, tipografia).<br><br>**Legais**:<br>1- Acessibilidade garantida para usuários com deficiência visual (ex.: leitor de tela). |
| Exceções   | 1- **Botão Não Renderizado**<br>Causa: Falha no carregamento da interface.<br>Ação: Sistema exibe mensagem "Recarregar Página" e loga o erro.<br><br>2- **Conectividade Interrompida**<br>Causa: Usuário perde internet durante o acesso.<br>Ação: App salva progresso localmente e retoma ao reconectar.<br><br>3- **Serviço de Ingressos Indisponível**<br>Causa: API de vendas fora do ar.<br>Ação: Sistema exibe mensagem educada e sugere tentar novamente mais tarde. |

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur De Camargos</a>, 2025.</p>

## 2.9 Cenário 9: Sugerir cinemas para o usuário

O 9º cenário, apresentado na Tabela 9, faz referência ao requisito não implementado [RQ29](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Sugerir cinemas com base no histórico de visitas e na localização atual.

**Tabela 9: Cenário de sugerir cinemas com base no histórico de visitas e na localização atual**

| Item       | Descrição                                                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Sugerir ao usuário cinemas próximos com base em seu histórico de visitas e localização atual                                                              |
| Contexto   | Local: Tela inicial do aplicativo após o login <br>Tempo: Após a abertura do app (até 10 segundos) <br>Pré-condição: Localização ativada no dispositivo e histórico de visitas registrado no perfil do usuário                                                                     |
| Atores     | Usuário logado no aplicativo.                                                                                                                                                                |
| Recursos   | Internet; aplicativo Cinemark instalado em dispositivo móvel; Histórico de visitas aos cinemas; GPS do dispositivo ativado; Banco de dados de cinemas ativos na cidade;                                                                                                                                |
| Episódios  | 1. Usuário abre o aplicativo<br>2. O sistema obtém a localização atual do usuário.<br>3. O sistema recupera o histórico de cinemas visitados anteriormente.</br>4. O sistema consulta cinemas próximos compatíveis com os estilos de visita anteriores.</br>5. O sistema ordena os resultados por proximidade e afinidade.</br>6. O sistema apresenta a lista personalizada ao usuário. |
| Restrições | Usuário deve autorizar previamente o uso da localização atual.                                                                                                                                         |
| Exceções   | Usuário sem histórico de visitas: O sistema exibe sugestões baseadas apenas na proximidade. <br>Sem localização atual: O sistema exibe uma mensagem sugerindo que o usuário ative o GPS. |

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Gabriel Castelo</a>, 2025.</p>

## 2.91 Cenário 10: Salvar cinemas como favoritos

O 10º cenário, apresentado na Tabela 10, faz referência ao requisito não implementado [RQ30](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Permitir que o usuário salve cinemas como favoritos.

**Tabela 10: Cenário de salvar cinemas como favoritos**

| Item       | Descrição                                                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário marque cinemas específicos como favoritos para acessá-los rapidamente no futuro.                                                            |
| Contexto   | Usuário visualiza detalhes ou listas de cinemas no aplicativo.                                                                   |
| Atores     | Usuário logado no aplicativo.                                                                                                                                                                |
| Recursos   | Internet; aplicativo Cinemark instalado em dispositivo móvel; Interface de cinemas; lista de cinemas favoritos do usuário; Banco de dados de cinemas ativos na cidade;                                                                                                                                |
| Episódios  | 1. O usuário navega pela lista ou detalhes de cinemas.<br>2. O usuário clica no botão ou ícone "Favoritar" próximo ao cinema desejado..<br>3. O sistema adiciona o cinema selecionado à lista de favoritos do usuário.</br>4. O usuário recebe uma confirmação visual de que o cinema foi salvo.</br>5. O usuário acessa posteriormente a lista de cinemas favoritos diretamente na interface principal do aplicativo. |
| Restrições | O usuário deve estar logado no sistema                                                                                                                                         |
| Exceções   | Se o cinema já estiver na lista de favoritos, o sistema informa que o cinema já foi adicionado anteriormente. |

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Gabriel Castelo</a>, 2025.</p>

## 2.9 Cenário 11: Permitir salvar ingressos na carteira digital do dispositivo

O décimo primeiro cenário, apresentado na Tabela 11, faz referência ao requisito [RQ26](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc).

**Tabela 11: Cenário de permitir salvar ingressos na carteira digital do dispositivo.**

| Item       | Descrição                                                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário adicione seu ingresso do aplicativo diretamente na carteira digital do dispositivo (como Google Wallet ou Apple Wallet) para facilitar o acesso ao ingresso. |
| Contexto   | Local: Tela de detalhes do pedido ou confirmação de compra.<br>Tempo: Imediato após a compra ou na tela de detalhes do ingresso.<br>Pré-condição: Usuário tenha um ingresso válido e carteira digital compatível instalada. |
| Atores     | Usuário do aplicativo Cinemark Digital. |
| Recursos   | Conexão com a internet; aplicativo Cinemark instalado e logado; carteira digital compatível instalada no dispositivo. |
| Episódios  | 1. Usuário acessa o aplicativo e vai até "Meus Pedidos".<br>2. Usuário seleciona um ingresso válido para salvar na carteira digital.<br>3. O sistema apresenta a opção de adicionar à carteira digital.<br>4. O usuário confirma a adição.<br>5. O ingresso é adicionado à carteira digital do dispositivo. |
| Restrições | O dispositivo do usuário deve ser compatível com a funcionalidade de carteira digital (Google Wallet ou Apple Wallet). <br>O ingresso deve ser válido para ser adicionado à carteira digital. |
| Exceções   | Falha ao adicionar o ingresso: exibir mensagem "Erro ao salvar na carteira digital". <br>Carteira digital não compatível: exibir mensagem "Seu dispositivo não suporta esta funcionalidade". |

<p align="center"><br>
Autor: <a href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a>, 2025.</p>

## 2.10 Cenário 12: Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas

O décimo segundo cenário, apresentado na Tabela 12, faz referência ao requisito [RQ39](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/): Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas.

**Tabela 12: Cenário de exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas**

| Item       | Descrição                                                                                                                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que os usuários vejam as avaliações de outros e também possam avaliar filmes, usando uma escala de 1 a 5 estrelas. |
| Contexto   | Local: Tela de detalhes do filme ou seção de avaliações. <br>Tempo: Imediato após o carregamento da página do filme. <br>Pré-condição: O filme deve ter sido lançado e ter avaliações disponíveis ou o usuário deve já ter assistido o filme. |
| Atores     | Usuário do aplicativo Cinemark Digital. |
| Recursos   | 	Conexão com a internet; aplicativo Cinemark Digital instalado e logado; sistema de avaliação integrado. |
| Episódios  | 1. Usuário acessa o aplicativo e vai até a página do filme. <br>2. O sistema exibe as avaliações anteriores de outros usuários. <br>3. O usuário pode clicar nas estrelas para dar sua própria avaliação. <br>4. O sistema registra a avaliação e a exibe. |
| Restrições | A avaliação deve ser feita apenas por usuários que já assistiram ao filme. <br>O sistema deve permitir a alteração da avaliação por um período de tempo após a primeira avaliação. |
| Exceções   | Avaliação não registrada: exibir mensagem "Erro ao registrar avaliação, tente novamente". <br>Falta de avaliações: exibir mensagem "Este filme ainda não possui avaliações". |

<p align="center"><br>
Autor: <a href="https://github.com/tiagobalieiro">Tiago Antunes Balieiro</a>, 2025.</p>

---

## Referências Bibliográficas

> **SOMMERVILLE**, Ian. *Engenharia de Software*. 10. ed. Boston: Pearson Education Limited, 2016. Disponível em: <https://www.pearson.com/en-us/subject-catalog/p/software-engineering/P200000003258/9780137503148.> Acesso em: 18 maio 2025.


> BARBOSA, Simone Diniz Junqueira; SILVA, Bruno Santana da; SILVEIRA, Milene Selbach; GASPARINI, Isabela; DARIN, Ticianne; BARBOSA, Gabriel Diniz Junqueira. *Interação Humano-Computador e Experiência do Usuário*. Autopublicação, 2021. Disponível em: https://leanpub.com/ihc-ux Acesso em: 18 maio 2025.

---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 13/05/2025 | Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23) | Todos |
| `1.1`  | 18/05/2025 | Adição da introdução, metodologia, cenários 1 e 2, e referências  | [Arthur Evangelista](https://github.com/arthurevg) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.2`  | 18/05/2025 | Correção nas Referências Bibliográficas | [Euller Júlio](https://github.com/Potatoyz908) | [Artur de Camargos](https://github.com/ArturDCR) |
| `1.3`  | 18/05/2025 | Adição dos cenários 3 (RQ59 - Reservar Sala) e 4 (RQ33 - Alterar Idioma)                         | [Euller Júlio](https://github.com/Potatoyz908)      | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.3.1`  | 18/05/2025 | Correção no Cenário 3 | [Euller Júlio](https://github.com/Potatoyz908)      | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.4`  | 18/05/2025 | Adição dos cenários 5 (RQ32 - Exibir recomendações de filmes baseadas em histórico e preferências) e 6 (RQ58 - Fornecer comparação de preços entre cinemas) | [Davi Camilo](https://github.com/Davicamilo23) | [Euller Júlio](https://github.com/Potatoyz908) |
| `1.5`  | 18/05/2025 | Adição dos cenários 7 (RQ60 - Cenário para Fornecer um Hub para crítica de filmes.) e 8 (RQ67- Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.) | [Artur de Camargos](https://github.com/ArturDCR) | [Tiago Antunes Balieiro](https://github.com/TiagoBalieiro) |
| `1.6`  | 18/05/2025 | Adição do cenário 9 (RQ29 - Sugerir cinemas com base no histórico de visitas e na localização atual) e 10 (RQ30 - Salvar cinemas como favoritos) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.7`  | 18/05/2025 | Adição dos cenários 11 (RQ26 - Permitir salvar ingressos na carteira digital do dispositivo.) e 12 (RQ39- Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas.) | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Euller Júlio](https://github.com/Potatoyz908) |
