# Storytelling

## Introdução

Storytelling é a atividade de passar para outras pessoas ideias, crenças, ou experiências de diferentes tipos. No contexto da Engenharia de Software, é considerada uma técnica de elicitação de requisitos, na qual são coletadas histórias para ajudar a esclarecer as necessidades das partes interessadas.

---

## Metodologia

Através de uma videoconferência com um usuário do aplicativo Cinemark, a técnica foi conduzida por 2 facilitadores. A ferramenta utilizada para a gravação da sessão foi o Microsoft Teams. O usuário foi orientado sobre a técnica, teve tempo suficiente e um ambiente seguro para contar as histórias. Após a sessão foi feita uma análise do conteúdo gerado, do qual foram retirados os requisitos apresentados.

## Participantes

| Nome               | Papel                  |
| ------------------ | -----------------------|
| [Gabriel Castelo](https://github.com/GabrielCastelo-31) | Analista de requisitos |
| [Tiago Antunes](https://github.com/TiagoBalieiro)     | Analista de requisitos |
| Gabriel Villela   | Usuário do aplicativo|

---

## Link da gravação da sessão

<iframe width="560" height="315" src="https://www.youtube.com/embed/OHllSImnMqc?si=3Q9UxiKKIUTtkXL3&amp;start=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

## História do usuário

Gabriel, um universitário de 22 anos apaixonado por cinema, tem o hábito de planejar suas idas às salas de exibição com antecedência. Para isso, acessa frequentemente o site da rede Cinemark, buscando de forma ágil e prática os horários das sessões disponíveis. A atualização semanal da programação é muito importante para ele, pois garante acesso às estreias e permite organizar sua agenda sem surpresas.

Mesmo utilizando outros serviços digitais para tarefas cotidianas, Gabriel ainda recorre ao site da Cinemark quando deseja uma visão abrangente dos horários de exibição. Para ele, ter todas as opções em um só lugar é essencial para não perder nenhum título de seu interesse.

Ele acredita que a experiência poderia ser ainda mais fluida se, após a compra de ingressos, fosse possível acessá-los diretamente em seu celular, incluindo informações como o assento e a sala, eliminando a necessidade de e-mails ou impressões físicas. Isso agilizaria sua entrada na sala e aumentaria sua comodidade.

Ao utilizar o aplicativo, Gabriel acha necessário a disponibilidade de ferramentas de acessibilidade. Ele reconhece o esforço da plataforma em atender públicos com diferentes necessidades, o que, em sua visão, agrega valor à experiência do usuário. Como estudante universitário atento às inovações digitais, ele também destaca a importância de um aplicativo funcional que concentre todos esses recursos, oferecendo uma jornada otimizada em qualquer lugar, a qualquer momento.

## Requisitos elicitados

Os requisitos identificados com o storytelling seguem a seguir:

**Legenda:**

- ST: Requisitos de <span>Storytelling</span>
- RF: Requisitos <span>Funcionais</span>
- RNF: Requisitos não <span>Funcionais</span>

| Tipo | Descrição                                                                            | ID   | Implementado |
| ---- | ------------------------------------------------------------------------------------ | ---- | ------------ |
| RF   | Eu, como usuário, desejo visualizar os horários dos filmes.                          | ST01 | Sim          |
| RF   | Eu, como usuário, desejo que os horários dos filmes sejam atualizados semanalmente.  | ST02 | Sim          |
| RF   | Eu, como usuário, desejo poder ver o meu ingresso.                                   | ST03 | Sim          |
| RF   | Eu, como usuário, desejo ver o número da minha poltrona.                             | ST04 | Sim          |
| RF   | Eu, como usuário, desejo que o aplicativo tenha acessibilidade.                      | ST05 | Não          |
| RNF  | Eu, como usuário, desejo utilizar o aplicativo em dispositivos móveis.               | ST06 | Sim          |

<font size="3"><p style="text-align: center">Fonte: [Gabriel Castelo](https://github.com/GabrielCastelo-31) e [Tiago Antunes](https://github.com/TiagoBalieiro), 2025.</p></font>

---

## Conclusão

Por meio do storytelling, foram criadas narrativas que representavam situações reais de uso do aplicativo. Essas histórias ajudaram a equipe a visualizar o contexto de uso, identificar possíveis problemas e necessidades não evidentes, contribuindo para a definição de requisitos mais centrados no usuário. As conclusões extraídas dessas narrativas estão incorporadas na seção de [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/).

## Bibliografia

[1] CIANCARINI, Paolo; FARINA, Mirko; OKONICHA, Ozioma; SMIRNOVA, Marina; SUCCI, Giancarlo. Software as storytelling: A systematic literature review. Computer Science Review, 2023. Disponível em: https://www.sciencedirect.com/science/article/abs/pii/S157401372200051X. Acesso em: 01 maio 2025.

---

## Histórico de Versão

| Versão | Data          | Descrição                          | Autor(es)     |  Revisor(es)  |
| ------ | ------------- | ---------------------------------- | ------------- | ------------- |
| `1.0`  | 01/05/2025 | Criação do documento inicial | [Tiago Antunes](https://github.com/TiagoBalieiro) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.1`  | 04/05/2025 | Ajuste na formatação | [Davi Camilo](https://github.com/Davicamilo23) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.2`  | 04/05/2025 | Ajuste na formatação da tabela de requisitos | [Tiago Antunes](https://github.com/TiagoBalieiro) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.3`  | 12/05/2025 | Adição da conclusão | [Arthur Evangelista](https://github.com/arthurevg) | [Artur de Camargos Rodrigues](https://github.com/ArturDCR) |
| `1.4`  | 12/05/2025 | Adição da tabela de participantes | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |[Tiago Antunes](https://github.com/TiagoBalieiro)  |
| `1.5`  | 12/05/2025 | Adição da história do usuário| [Gabriel Castelo](https://github.com/GabrielCastelo-31) |[Tiago Antunes](https://github.com/TiagoBalieiro)  |
