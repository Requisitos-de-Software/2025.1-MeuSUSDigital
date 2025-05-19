## Introdução

  O diagrama de casos de uso é um artefato de modelagem comportamental na UML que representa, de forma simplificada, as interações entre atores externos e o sistema. Por meio de casos de uso, descrevemos funcionalidades sob a ótica do usuário, focando nos objetivos que devem ser alcançados e nos resultados práticos gerados.

  Cada caso de uso sintetiza uma sequência de ações que inicia com uma solicitação do ator e termina com uma resposta do sistema, entregando valor tangível ao usuário. Para cenários complexos, recomenda-se enriquecer a descrição com detalhes em linguagem natural, prática conhecida como escrita expandida de casos de uso.

## Metodologia

  Para a construção do diagrama de casos de uso do sistema Cinemark, adotamos uma abordagem clássica em UML. Utilizamos o LucidChart para elaborar a representação gráfica, garantindo consistência nos símbolos e clareza na disposição dos elementos.

## Componentes e Símbolos

  A seguir, apresentamos os principais componentes de um diagrama de casos de uso, com explicações sobre seus significados e representações gráficas.

### Atores

  São as entidades externas que interagem com o sistema, podem ser usuários ou outros sistemas. No diagrama, são representados por ícones que lembram pessoas.

<p align="center">Figura 1: Ator no diagrama.</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/ator.png" alt="Ator no diagrama" width="250px">
</p>

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

### Sistema (Cenário)

  Define o perímetro funcional do diagrama, demarcando quais casos de uso estão dentro do escopo do sistema. É ilustrado como uma caixa retangular que envolve todos os casos de uso.

<p align="center">Figura 2: Caixa de sistema delimitando o cenário.</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/sistema.png" alt="sistema no diagrama, representado por uma retângulo com título na parte superior" width="250px">
</p>

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

### Casos de Uso

  Cada caso de uso corresponde a uma ação ou serviço que o sistema oferece ao ator. Representado por elipses horizontais, seu nome deve empregar verbos no infinitivo, como “Filtrar filmes” ou “Assistir trailer”.


<p align="center">Figura 3: Casos de uso representados por elipses.</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/casoDeUso.png" width="250px">
</p>

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

### Relacionamentos


 - **Associação:** conecta atores a casos de uso, indicando participação direta do ator na execução do caso. É representada por uma linha simples ligando o ícone do ator à elipse do caso de uso.

- **Inclusão:** indica reutilização de comportamento comum entre casos de uso (ex.: “Aplicar cupom” incluído em “Comprar ingresso”). Usa-se a estereotipagem «incluir».

- **Extensão** adiciona variações opcionais a um caso base (ex.: “Filtrar por categoria” estendendo “Exibir filmes”). Usa-se a estereotipagem «extender».

- **Generalização:** modela especializações de casos de uso ou atores, mostrando que um elemento filho herda o comportamento ou características do elemento pai. É representada por uma seta com ponta oca apontando para o pai.


<p align="center">Figura 4: Exemplos de relacionamentos.</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/relacionamentos.png" alt="exemplo de como cada relacionamento é representado" width="250px">
</p>

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

## Diagrama de Casos de Uso
A Figura 1 demonstra o Diagrama de casos de uso, com ênfase nas funcionalidades não implementadas

<p align="center"><br>
Figura 1: Diagrama de casos de uso do aplicativo CInemark</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2025.1-Cinemark/main/docs/assets/modelagem/DiagramaCasosUso.png" alt="Diagrama de casos de uso do aplicativo cinemark">
</p>

<p align="center"><br>
Autor: <a href="https://github.com/arthurevg">Arthur Evangelista</a>, 2025.</p>

## Requisitos Utilizados

### **Tabela 1: Requisitos utilizados no Diagrama de Casos de Uso**

| Id   | Descrição                                                   | Implementado |
| ---- | ----------------------------------------------------------- | ------------ |
| [IS15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS15) | Filtrar Filmes por Categoria e Exibir Avaliações de Público | Não          |
| [IS16](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS16) | Exibir Trailers dentro do App                               | Não          |
| [IS24](../elicitação/introspecção.md#IS24) | Exibir recomendações de filmes baseadas em histórico e preferências | Não |
| [Q04](../elicitação/questionario.md#Q04) | Fornecer comparação de preços entre cinemas | Não |
| [Q05](../elicitação/questionario.md#Q05) | Permitir reserva de salas para eventos | Não |
| [IS25](../elicitação/introspecção.md#IS25) | 	Permitir alteração de preferências de idioma | Não |
| [IS18](../elicitação/introspecção.md#IS18) | 	Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc). | Não |
| [IS15](../elicitação/introspecção.md#IS15) | 	Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas. | Não |


## Especialização dos Casos de Uso

As tabelas a seguir apresentam as especializações detalhadas dos casos de uso.

### **Tabela 2: Filtrar Filmes por Categoria e Exibir Avaliações**

| Campo               | Descrição                                                                                             |
| ------------------- | ----------------------------------------------------------------------------------------------------- |
| **UC**              | UC01                                                                                                  |
| **Descrição**       | O usuário pode filtrar filmes por categoria e visualizar as avaliações de público interno e externas. |
| **Ator**            | Usuário                                                                                               |
| **Pré-condições**   | Acesso à internet; existência de filmes com categorias e avaliações cadastradas.                      |
| **Ação**            | O usuário selecionou categorias de filmes e solicitou exibição das avaliações correspondentes.        |
| **Fluxo Principal** | 1. O usuário acessa o aplicativo.  </br>2. Seleciona a opção "Filtrar por Categoria". </br>3. O sistema apresenta as categorias disponíveis. </br>4. O usuário escolhe uma ou mais categorias. </br>5. O sistema lista filmes filtrados e exibe avaliações de público e de plataformas externas.|
   | **Fluxo Alternativo** | Usuário não escolhe categoria: o sistema exibe todos os filmes com suas avaliações correspondentes. |
   | **Fluxo de Exceção**| Falha ao obter avaliações externas: o sistema exibe apenas as avaliações internas e notifica o usuário. |
   | **Pós-condições**   | A lista de filmes filtrados e suas avaliações são apresentadas ao usuário.                         |
   | **Data de Criação** | 17/05/2025                                                                                        |
   | **Rastreabilidade** | [IS15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS15)|

   <font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

### **Tabela 3: Exibir Trailers dentro do App**

| Campo               | Descrição                                                                    |
| ------------------- | ---------------------------------------------------------------------------- |
| **UC**              | UC02                                                                         |
| **Descrição**       | O usuário pode assistir trailers de filmes diretamente dentro do aplicativo. |
| **Ator**            | Usuário                                                                      |
| **Pré-condições**   | Acesso à internet; trailers vinculados aos filmes disponíveis no sistema.    |
| **Ação**            | O usuário solicitou a reprodução de um trailer em um filme específico.       |
| **Fluxo Principal** | 1. O usuário acessa o aplicativo. </br>2. Seleciona um filme.</br>3. Clica no botão "Assistir Trailer".</br>4. O sistema reproduz o trailer dentro do app.|
| **Fluxo Alternativo** | Usuário interrompe a reprodução antes do fim: o sistema para o vídeo e retorna à tela de detalhes. |
| **Fluxo de Exceção**| Falha de conexão ou erro no carregamento: o sistema exibe mensagem de erro e sugere tentar novamente. |
| **Pós-condições**   | O trailer foi reproduzido com sucesso ou tratou o erro conforme o fluxo de exceção.          |
| **Data de Criação** | 17/05/2025                                                           | 
|**Rastreabilidade** | [IS16](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS16)                           

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

### **Tabela 4: Exibir recomendações de filmes baseadas em histórico e preferências**

| Campo                 | Descrição                                                                                                                                                                                                                                     |
| --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UC**                | UC03                                                                                                                                                                                                                                          |
| **Descrição**         | O sistema exibe recomendações personalizadas de filmes com base no histórico de visualização e preferências do usuário.                                                                                                                       |
| **Ator**              | Usuário                                                                                                                                                                                                                                       |
| **Pré-condições**     | Acesso à internet; usuário com histórico de interações e/ou preferências já registradas.                                                                                                                                                         |
| **Ação**              | O usuário acessa a seção de recomendações.                                                                                                                                                                                                    |
| **Fluxo Principal**   | 1. O usuário acessa o aplicativo.  <br>2. Navega até a seção "Recomendações para Você".  <br>3. O sistema analisa o histórico de visualizações e preferências salvas.  <br>4. O sistema exibe uma lista personalizada de filmes recomendados. |
| **Fluxo Alternativo** | Usuário sem histórico ou preferências: o sistema exibe filmes populares ou mais bem avaliados como sugestões iniciais.                                                                                                                        |
| **Fluxo de Exceção**  | Falha na análise de dados do usuário: o sistema notifica a falha e exibe sugestões genéricas.                                                                                                                                                 |
| **Pós-condições**     | Recomendações são apresentadas e o usuário pode explorá-las ou salvar para assistir depois as que desejar.                                                                                                                                                   |
| **Data de Criação**   | 17/05/2025                                                                                                                                                                                                                                    |
| **Rastreabilidade**   | [IS24](../elicitação/introspecção.md#IS24)                                                                                                                                                |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### **Tabela 5: Fornecer comparação de preços entre cinemas**

| Campo                 | Descrição                                                                                                                                                                                                                                                  |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UC**                | UC04                                                                                                                                                                                                                                                       |
| **Descrição**         | O usuário pode comparar os preços de ingressos e combos entre diferentes cinemas para o mesmo filme.                                                                                                                                                       |
| **Ator**              | Usuário                                                                                                                                                                                                                                                    |
| **Pré-condições**     | Acesso à internet; existência de dados de preços atualizados dos cinemas Cinemark.                                                                                                                                                                        |
| **Ação**              | O usuário acessa a seção de comparação de preços para um filme específico.                                                                                                                                                                                 |
| **Fluxo Principal**   | 1. O usuário acessa o aplicativo.  <br>2. Seleciona um filme desejado.  <br>3. O sistema identifica cinemas próximos com sessões disponíveis.  <br>4. O sistema apresenta uma tabela comparativa de preços de ingressos e combos para os cinemas listados. |
| **Fluxo Alternativo** | Caso o filme não esteja disponível em mais de um cinema: o sistema apresenta os preços apenas do cinema disponível.                                                                                                                                        |
| **Fluxo de Exceção**  | Falha na obtenção de preços de um cinema: o sistema exibe os demais e sinaliza a ausência temporária de dados do cinema com falha.                                                                                                                                             |
| **Pós-condições**     | O usuário visualiza e compara os preços, podendo escolher o cinema com melhor custo-benefício.                                                                                                                                                             |
| **Data de Criação**   | 17/05/2025                                                                                                                                                                                                                                                 |
| **Rastreabilidade**   | [Q04](../elicitação/questionario.md#Q04)                                                                                                                                                             |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### **Tabela 6: Reservar salas para eventos**
| Campo                 | Descrição                                                                                                                                                                                                                                                                                                         |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UC**                | UC05                                                                                                                                                                                                                                                                                                              |
| **Descrição**         | Permitir que o usuário reserve uma sala de cinema para eventos privados, como aniversários, reuniões ou sessões fechadas.                                                                                                                                                                                         |
| **Ator**              | Usuário                                                                                                                                                                                                                                                                                                           |
| **Pré-condições**     | Acesso à internet; login efetuado; disponibilidade de salas em datas e horários válidos.                                                                                                                                                                                                                          |
| **Ação**              | O usuário acessa a opção de reserva de salas e preenche os dados solicitados.                                                                                                                                                                                                                                     |
| **Fluxo Principal**   | 1. O usuário acessa o app. <br>2. Entra na seção "Reservar Sala".<br>3. Informa data, horário e número estimado de pessoas.<br>4. O sistema exibe as salas disponíveis.<br>5. O usuário seleciona a sala desejada.<br>6. O sistema solicita confirmação e dados de pagamento.<br>7. O usuário confirma a reserva. |
| **Fluxo Alternativo** | Usuário cancela a reserva antes da confirmação final: o sistema retorna à tela inicial da funcionalidade.                                                                                                                                                                                                         |
| **Fluxo de Exceção**  | Nenhuma sala disponível na data/hora: o sistema informa indisponibilidade e sugere horários alternativos.                                                                                                                                                                                                         |
| **Pós-condições**     | A reserva da sala é registrada no sistema e o usuário recebe um comprovante.                                                                                                                                                                                                                                      |
| **Data de Criação**   | 18/05/2025                                                                                                                                                                                                                                                                                                        |
| **Rastreabilidade**   | [Q05](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/questionario/#Q05)                                                                                                                                                                                                            |

<font size="3"><p style="text-align: center">Fonte: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

### **Tabela 7: Alterar preferências de idioma**

| Campo                 | Descrição                                                                                                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **UC**                | UC06                                                                                                                                                                                                                           |
| **Descrição**         | O usuário pode alterar o idioma da interface do aplicativo, escolhendo entre as opções disponíveis.                                                                                                                            |
| **Ator**              | Usuário                                                                                                                                                                                                                        |
| **Pré-condições**     | Estar autenticado no aplicativo.                                                                                                                                                                                               |
| **Ação**              | O usuário acessa as configurações de conta e altera a preferência de idioma.                                                                                                                                                   |
| **Fluxo Principal**   | 1. O usuário acessa o aplicativo.<br>2. Vai ao menu "Mais" ou "Perfil".<br>3. Acessa "Preferências de Idioma".<br>4. Seleciona o novo idioma desejado.<br>5. O sistema aplica a mudança imediatamente ou após reinicialização. |
| **Fluxo Alternativo** | O usuário cancela a alteração antes de confirmar: o idioma permanece o mesmo.                                                                                                                                                  |
| **Fluxo de Exceção**  | O idioma selecionado não está disponível ou há falha na aplicação da mudança: o sistema exibe mensagem de erro.                                                                                                                |
| **Pós-condições**     | O idioma da interface é alterado com sucesso, refletindo em todas as telas subsequentes.                                                                                                                                       |
| **Data de Criação**   | 18/05/2025                                                                                                                                                                                                                     |
| **Rastreabilidade**   | [IS25](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS25)                                                                                                                         |


<font size="3"><p style="text-align: center">Fonte: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

### **Tabela 8: Permitir salvar ingressos na carteira digital do dispositivo.**

| Campo                 | Descrição                                                                                                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **UC**                | UC07                                                                                                                                                                                                                           |
| **Descrição**         | O usuário pode salvar seus ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc).                                                                                                                            |
| **Ator**              | Usuário                                                                                                                                                                                                                        |
| **Pré-condições**     | Acesso à internet; login efetuado; ter comprado ao menos um ingresso no aplicativo; usuário deve possuir uma carteira digital no dispositivo.                                                                                                                                                                                               |
| **Ação**              | O usuário acessa o seu pedido e seleciona a opção de adicionar a carteira digital.                                                                                                                                                   |
| **Fluxo Principal**   | 1. O usuário acessa o aplicativo.<br>2. Vai ao menu "Mais".<br>3. Acessa "Pedidos".<br>4. Seleciona o pedido.<br>5. Seleciona a opção de adicionar na carteira digital do dispositivo. |
| **Fluxo Alternativo** | O usuário opta por não adicionar o ingresso à carteira digital: o sistema cancela a operação e retorna para a tela de detalhes do pedido.                                                                                                                                                 |
| **Fluxo de Exceção**  | O usuário não possui uma carteira digital no dispositivo: o sistema retorna à tela do pedido e exibe mensagem de erro.                                                                                                                 |
| **Pós-condições**     | O ingresso é salvo na carteira digital e o sistema retorna à tela do pedido exibindo uma mensagem de sucesso.                                                                                                                                       |
| **Data de Criação**   | 19/05/2025                                                                                                                                                                                                                     |
| **Rastreabilidade**   | [IS18](../elicitação/introspecção.md#IS18)                                                                                                                        |


<font size="3"><p style="text-align: center">Fonte: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

### **Tabela 9: Permitir que usuários avaliem filmes com escala de 1 a 5 estrelas.**
| Campo                 | Descrição                                                                                                                                                                                                                      |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **UC**                | UC08                                                                                                                                                                                                                           |
| **Descrição**         | O usuário pode avaliar filmes em uma escala de 1 a 5 estrelas.                                                                                                                            |
| **Ator**              | Usuário                                                                                                                                                                                                                        |
| **Pré-condições**     | Acesso à internet; login efetuado; existência de filmes cadastrados no sistema.                                                                                                                                                                                               |
| **Ação**              | O usuário avalia um filme.                                                                                                                                                   |
| **Fluxo Principal**   | 1. O usuário acessa o aplicativo.<br>2. Seleciona um filme.<br>3. Clica em um dos cinco botões em formato de estrela.<br>4. O sistema registra a avaliação. |
| **Fluxo Alternativo** | O usuário opta por não avaliar o filme: o sistema esconde a região de avaliação.                                                                                                                                                 |
| **Fluxo de Exceção**  | Falha no registro da avaliação: o sistema notifica a falha e pede para tentar novamente em alguns minutos.                                                                                                                 |
| **Pós-condições**     | A avaliação do filme é apresentada ao usuário.                                                                                                                                       |
| **Data de Criação**   | 19/05/2025                                                                                                                                                                                                                     |
| **Rastreabilidade**   | [IS15](../elicitação/introspecção.md#IS15)                                                                                                                        |


<font size="3"><p style="text-align: center">Fonte: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

### Tabela 10: Sugerir cinemas personalizados

| Campo                 | Descrição                                                                                                                                                                                                                                      |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UC**                | UC09 – Sugerir Cinemas Personalizados                                                                                                                                                                                                          |
| **Descrição**         | O sistema sugere automaticamente uma lista de cinemas com base no histórico de visitas e na localização atual do usuário.                                                                                                                      |
| **Ator**              | Usuário                                                                                                                                                                                               |
| **Pré-condições**     | O usuário deve estar logado, o histórico de visitas deve estar registrado e a localização ativada no dispositivo.                                                                                                                              |
| **Ação**              | O usuário abre o app e acessa a área de sugestões de cinema.                                                                                                                                                                                   |
| **Fluxo Principal**   | 1. O usuário abre o aplicativo;<br>2. O sistema identifica a localização atual;<br>3. O sistema acessa o histórico de visitas;<br>4. O sistema cruza os dados e gera sugestões personalizadas;<br>5. O usuário visualiza os cinemas sugeridos. |
| **Fluxo Alternativo** | Se não houver histórico suficiente, o sistema utiliza apenas a localização para sugerir cinemas bem avaliados próximos.                                                                                                                    |
| **Fluxo de Exceção**  | Se a localização não estiver ativada, o sistema exibe uma mensagem solicitando permissão de acesso.                                                                                                                                        |
| **Pós-condições**     | O sistema exibe uma lista de cinemas sugeridos e registra o comportamento de navegação do usuário para futuras sugestões.                                                                                                                      |
| **Data de Criação**   | 18/05/2025                                                                                                                                                                                                                                     |
| **Rastreabilidade**   | [IS21](../elicitação/introspecção.md#IS21)                                                                                                                                                                |

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### **Tabela 11: Salvar cinema como favorito**

| Campo                 | Descrição                                                                                                                                                                                                                                                      |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **UC**                | UC10 – Salvar Cinema como Favorito                                                                                                                                                                                                                             |
| **Descrição**         | Permite que o usuário adicione cinemas à sua lista de favoritos para facilitar o acesso futuro.                                                                                                                                                                |
| **Ator**              | Usuário                                                                                                                                                                                               |
| **Pré-condições**     | O usuário deve estar autenticado e o cinema deve estar disponível na base de dados.                                                                                                                                                                            |
| **Ação**              | O usuário acessa a página de um cinema e clica na opção de favoritar.                                                                                                                                                                                          |
| **Fluxo Principal**   | 1. O usuário acessa a página de detalhes de um cinema;<br>2. O usuário clica no ícone de "favoritar";<br>3. O sistema verifica se o cinema já está salvo;<br>4. O sistema adiciona o cinema à lista de favoritos;<br>5. O sistema confirma visualmente a ação. |
| **Fluxo Alternativo** | Se o cinema já estiver favoritado, o sistema oferece a opção de "remover dos favoritos".                                                                                                                                                                   |
| **Fluxo de Exceção**  | Se o usuário não estiver logado, o sistema redireciona para a tela de login.                                                                                                                                                                               |
| **Pós-condições**     | O cinema é salvo na lista pessoal de favoritos do usuário e poderá ser acessado rapidamente no futuro.                                                                                                                                                         |
| **Data de Criação**   | 18/05/2025                                                                                                                                                                                                                                                     |
| **Rastreabilidade** |[IS22](../elicitação/introspecção.md#IS22)                                                                                                                                                                                                     |
<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

***

## Referências Bibliográficas

> LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML [vídeo]. YouTube, 2018. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 17 maio 2025.

> LUCIDCHART. Use Case Diagrams in Lucidchart [software]. Disponível em: https://www.lucidchart.com/pages/uml-use-case-diagram. Acesso em: 17 maio 2025.

---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 11/05/2025 | Criação da estrutura inicial da página | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.1`  | 17/05/2025 | Adição da Introdução, metodologia, componentes e símbolos, Tabelas 1, 2 e 3, Diagrama de casos de uso e referências  | [Arthur Evangelista](https://github.com/arthurevg) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.2`  | 17/05/2025 | Adição dos requisitos RQ32 (Exibir recomendações de filmes baseadas em histórico e preferências) e RQ58 (Fornecer comparação de preços entre cinemas) e suas respectivas tabelas (4 e 5) com a especialização dos casos de uso | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.3`  | 18/05/2025 | Adição das Tabelas 6 e 7 com os casos de uso para RQ59 (Reservar salas para eventos) e RQ33 (Alterar preferências de idioma); atualização da Tabela 1 com novos requisitos | [Euller Júlio](https://github.com/Potatoyz908) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.4`  | 18/05/2025 | Adição das Tabelas 8 e 9 com os casos de uso para RQ26 (Salvar ingresso na carteira digital) e RQ39 (Avaliar filmes); atualização da Tabela 1 com novos requisitos | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos Rodrigues](https://github.com/ArturDCR) |
| `1.5`  | 19/05/2025 | Adição da Tabela 10 com o caso de uso para RQ29 (Sugerir cinemas personalizados) e da Tabela 11 com o caso de uso para RQ30 (Salvar cinema como favorito)| [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro)
