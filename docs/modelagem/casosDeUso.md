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
[Falar sobre e colocaro diagrama aqui]

## Requisitos Utilizados

### **Tabela 1: Requisitos utilizados no Diagrama de Casos de Uso**

| Id   | Descrição                                                   | Implementado |
| ---- | ----------------------------------------------------------- | ------------ |
| [IS15](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS15) | Filtrar Filmes por Categoria e Exibir Avaliações de Público | Não          |
| [IS16](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/introspec%C3%A7%C3%A3o/#IS16) | Exibir Trailers dentro do App                               | Não          |


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
---
## Referências Bibliográficas

> LUCID SOFTWARE PORTUGUÊS. Tutorial de Caso de Uso UML [vídeo]. YouTube, 2018. Disponível em: https://www.youtube.com/watch?v=ab6eDdwS3rA. Acesso em: 17 maio 2025.

> LUCIDCHART. Use Case Diagrams in Lucidchart [software]. Disponível em: https://www.lucidchart.com/pages/uml-use-case-diagram. Acesso em: 17 maio 2025.

---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 11/05/2025 | Criação da estrutura inicial da página | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.1`  | 17/05/2025 | Adição da Introdução, metodologia, componentes e símbolos, Tabelas 1, 2 e 3, e referências  | [Arthur Evangelista](https://github.com/arthurevg) | [Davi Camilo](https://github.com/Davicamilo23) |
