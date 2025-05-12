# A DESENVOLVER...
<!-- # Casos de Uso

## Introdução

Casos de uso descrevem como os usuários interagem com um sistema para atingir objetivos específicos. Eles representam sequências de ações realizadas pelos usuários (atores) e as respostas esperadas do sistema, servindo como base para a especificação de requisitos funcionais.

Neste projeto, os casos de uso foram utilizados para documentar as principais funcionalidades do aplicativo **Cinemark**, com o intuito de apoiar o desenvolvimento e entendimento dos fluxos de interação.

---

## Metodologia

Para a modelagem dos casos de uso, seguimos a notação UML, com foco na clareza e rastreabilidade dos requisitos. O diagrama é composto por:

* **Atores**, que representam os usuários do sistema (ex: cliente do app);
* **Casos de uso**, que representam funcionalidades acessíveis;
* **Relações** como dependência, extensão ou inclusão entre os casos de uso;
* **Sistema**, que agrupa os casos de uso.

Adicionalmente, utilizamos a persona [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) como base para simular cenários reais e construir os fluxos de maneira centrada no usuário.

<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos da notação de casos de uso</p></font>

| Nome                 | Função                                           |                    Exemplo                    |
| -------------------- | ------------------------------------------------ | :-------------------------------------------: |
| Ator                 | Representa quem interage com o sistema           |      ![ator](../assets/usecase/ator.png)      |
| Elipse (caso de uso) | Representa uma funcionalidade acessada pelo ator |    ![elipse](../assets/usecase/elipse.png)    |
| Retângulo (sistema)  | Representa os limites do sistema                 | ![retangulo](../assets/usecase/retangulo.png) |
| Flechas (relações)   | Indicam interações e dependências                |    ![flecha](../assets/usecase/flecha.png)    |

---

## Diagrama de Casos de Uso

A Figura 1 apresenta o diagrama de casos de uso elaborado com base nos requisitos elicitados:

<font size="3"><p style="text-align: center"><b>Figura 1</b>: Diagrama de casos de uso do app Cinemark</p></font>

<img src="../../assets/usecase/diagrama-cinemark.png" class="usecaseElement">

<font size="2"><p style="text-align: center"><b>Fonte: [Arthur Evangelista](https://github.com/arthurevg) e [Euller Júlio](https://github.com/Potatoyz908)</b></p></font>

---

## Especialização dos Casos de Uso

Os casos de uso foram agrupados por fluxo funcional do sistema. Cada tabela abaixo descreve um caso de uso em detalhes, com seus fluxos principais, alternativos e de exceção.

> *(Sugestão: você pode começar criando uma tabela por vez conforme documenta cada caso. Aqui está um exemplo pronto para “Selecionar Sessão” que você pode copiar e adaptar):*

<font size="3"><p style="text-align: center">Tabela 2: Selecionar Sessão</p></font>

| UC01                  | Informações                                                                                                                          |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Descrição**         | Permite ao usuário escolher uma sessão específica para um filme                                                                      |
| **Ator**              | Usuário                                                                                                                              |
| **Pré-condições**     | Estar logado no app; possuir conexão com a internet                                                                                  |
| **Ação**              | O usuário navega até a aba de filmes, escolhe um filme e seleciona uma sessão                                                        |
| **Fluxo principal**   | <ul><li>O usuário acessa o filme</li><li>O sistema exibe a lista de sessões</li><li>O usuário escolhe data, horário e sala</li></ul> |
| **Fluxo alternativo** | <ul><li>O sistema sugere sessões com base na localização e histórico do usuário</li></ul>                                            |
| **Fluxo de exceção**  | <ul><li>O sistema não encontra sessões disponíveis</li><li>O sistema exibe uma mensagem de erro</li></ul>                            |
| **Pós-condições**     | A sessão é selecionada e o sistema redireciona para a seleção de assentos                                                            |
| **Rastreabilidade**   | [RQ8](../elicitacao/requisitos/#rq8), [RQ29](../elicitacao/requisitos/#rq29)                                                         |
| **Data de Criação**   | 10/05/2025                                                                                                                           |

---

## Bibliografia

> LUCIDCHART. Diagrama de Caso de Uso UML. Disponível em: [https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml). Acesso em: 10 maio 2025.
> PRESSMAN, Roger. Engenharia de Software. McGraw-Hill, 2016.
> REPOSITÓRIO: Requisitos de Software – UnB FGA. Disponível em: [https://requisitos-de-software.github.io/](https://requisitos-de-software.github.io/)

---

## Histórico de Versões

| Versão | Data       | Descrição                              | Autor(es)                                                                                           | Revisor(es)                                       |
| ------ | ---------- | -------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------- |
| 1.0    | 11/05/2025 | Criação da estrutura inicial da página | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) | -->