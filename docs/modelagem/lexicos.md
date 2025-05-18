# Léxicos

## Introdução

O método de Léxicos é utilizado na engenharia de requisitos para descrever, em linguagem natural estruturada, os termos e conceitos relevantes do domínio do sistema. Cada entrada léxica é classificada como **verbo**, **objeto** ou **estado**, com seus respectivos sinônimos, noções e impactos, promovendo uma compreensão comum entre todos os stakeholders.

A estrutura de cada termo léxico é composta por:

* **Tipo**: (Verbo, Objeto ou Estado)
* **Sinônimos**: outras formas de se referir ao termo
* **Noção**: definição ou contexto do termo no sistema
* **Impacto**: quais funcionalidades ou elementos são afetados por esse termo
* **Rastreabilidade**: requisito(s) elicitado(s) ao qual o termo está relacionado

---

## Léxicos Criados

### 1. **Reservar Sala**

* **Tipo**: Verbo
* **Sinônimos**: Agendar sala, Solicitar sala, Alugar sala
* **Noção**: Ação realizada por um usuário para garantir o uso exclusivo de uma sala de cinema para fins particulares, como eventos, festas ou sessões privadas.
* **Impacto**: Ao reservar uma sala, o sistema deve verificar disponibilidade, coletar informações do evento, registrar a reserva e gerar confirmação. Afeta diretamente o módulo de reservas, a agenda de salas e o fluxo de pagamento.
* **Rastreabilidade**: [RQ59](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer reservas de salas para eventos.

---

### 2. **Preferência de Idioma**

* **Tipo**: Objeto
* **Sinônimos**: Idioma, Configuração de idioma, Idioma da interface
* **Noção**: Representa a configuração escolhida pelo usuário para a linguagem da interface do aplicativo. Pode incluir opções como português, inglês, espanhol, etc.
* **Impacto**: Ao modificar essa configuração, a interface deve ser imediatamente ajustada para o idioma escolhido. Afeta a experiência do usuário e a apresentação de todos os textos exibidos no sistema.
* **Rastreabilidade**: [RQ33](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Permitir alteração de preferências de idioma.


---

## Referências Bibliográficas

> SALES, André Barros de. *Requisitos – Aula 10: Léxicos*. Universidade de Brasília, 2025. Disponível em: `<https://aprender3.unb.br>` (material interno da disciplina). Acesso em: 18 maio 2025.

> LEITE, J. C. S. do Prado; FRAGOSO, Gerson H. *Manual de Engenharia de Requisitos – Vol. 1: Fundamentos*. 2. ed. Rio de Janeiro: LTC, 2014.

> PAULA FILHO, Wilson de Pádua. *Engenharia de Software: Fundamentos, Métodos e Padrões*. 2. ed. Rio de Janeiro: LTC, 2009.

---

## Histórico de Versão

| Versão | Data       | Descrição                                     | Autor(es)                                      | Revisor(es)                                       |
| ------ | ---------- | --------------------------------------------- | ---------------------------------------------- | ------------------------------------------------- |
| `1.0`  | 13/05/2025 | Criação do Documento                          | [Davi Camilo](https://github.com/Davicamilo23) | Todos                                             |
| `1.1`  | 18/05/2025 | Adição da introdução, metodologia e referências | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.2`  | 18/05/2025 | Adição dos léxicos dos requisitos RQ59 e RQ33 | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |