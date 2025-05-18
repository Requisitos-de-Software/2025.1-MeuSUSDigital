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

### 3. **Filtrar Filmes**

* **Tipo**: Verbo  
* **Sinônimos**: Selecionar por categoria, Classificar filmes, Aplicar filtro de gênero  
* **Noção**: Ação realizada pelo usuário para limitar a exibição de filmes com base em categorias ou gêneros disponíveis, como ação, comédia, drama etc.  
* **Impacto**: Ao realizar o filtro, o sistema deve consultar os dados cadastrados de filmes, aplicar os critérios definidos e exibir apenas os resultados compatíveis. Isso influencia a navegação e a personalização da experiência do usuário.  
* **Rastreabilidade**: [RQ23](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Filtrar filmes por categoria e exibir avaliações de público e plataformas externas.

---

### 4. **Avaliações de Filmes**

* **Tipo**: Objeto  
* **Sinônimos**: Opiniões, Notas, Reviews  
* **Noção**: Representa as notas e comentários fornecidos tanto por usuários da plataforma quanto por sistemas externos de avaliação (como IMDb, Rotten Tomatoes etc.).  
* **Impacto**: Essas avaliações são exibidas junto aos detalhes dos filmes, impactando a decisão do usuário sobre assistir ou não. O sistema deve buscar e apresentar essas informações de forma clara e atualizada.  
* **Rastreabilidade**: [RQ23](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Filtrar filmes por categoria e exibir avaliações de público e plataformas externas.

---

### 5. **Assistir Trailer**

* **Tipo**: Verbo  
* **Sinônimos**: Ver prévia, Reproduzir trailer, Ver vídeo promocional  
* **Noção**: Ação em que o usuário inicia a reprodução de um vídeo promocional (trailer) de um filme dentro do próprio aplicativo.  
* **Impacto**: Ao assistir ao trailer, o sistema deve reproduzir o conteúdo audiovisual sem necessidade de redirecionamento externo. Isso melhora a experiência do usuário e pode influenciar o interesse em assistir ao filme.  
* **Rastreabilidade**: [RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir trailers dentro do app.

---

### 6. **Trailer**

* **Tipo**: Objeto  
* **Sinônimos**: Prévia, Vídeo de divulgação, Teaser  
* **Noção**: Conteúdo audiovisual curto, destinado à divulgação de um filme, contendo cenas selecionadas para atrair o público.  
* **Impacto**: Os trailers devem estar associados aos filmes e disponíveis para reprodução dentro do app. Devem estar integrados a um player funcional e acessível.  
* **Rastreabilidade**: [RQ24](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir trailers dentro do app.


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
| `1.3`  | 18/05/2025 | Adição dos léxicos 3, 4, 5 e 6 (RQ23 e RQ24) | [Arthur Evangelista](https://github.com/arthurevg) | [Euller Júlio](https://github.com/Potatoyz908) |