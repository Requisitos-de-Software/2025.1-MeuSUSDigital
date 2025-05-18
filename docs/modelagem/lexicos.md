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

<p align="center"><br>
Autor: <a href="https://github.com/Potatoyz908">Euller Júlio</a>, 2025.</p>

---

### 2. **Preferência de Idioma**

* **Tipo**: Objeto
* **Sinônimos**: Idioma, Configuração de idioma, Idioma da interface
* **Noção**: Representa a configuração escolhida pelo usuário para a linguagem da interface do aplicativo. Pode incluir opções como português, inglês, espanhol, etc.
* **Impacto**: Ao modificar essa configuração, a interface deve ser imediatamente ajustada para o idioma escolhido. Afeta a experiência do usuário e a apresentação de todos os textos exibidos no sistema.
* **Rastreabilidade**: [RQ33](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Permitir alteração de preferências de idioma.


<p align="center"><br>
Autor: <a href="https://github.com/Potatoyz908">Euller Júlio</a>, 2025.</p>

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

### 7. **Exibir Recomendações de Filmes**

- **Tipo**: Verbo
- **Sinônimos**: Sugerir filmes, Recomendação personalizada, Indicar títulos
- **Noção**: Ação em que o sistema apresenta sugestões de filmes ao usuário com base em seu histórico de visualização, avaliações e preferências cadastradas no aplicativo.
- **Impacto**: Melhora a personalização da experiência do usuário, aumentando o engajamento e a probabilidade de escolha de um filme por parte do usuário. Exige análise de dados comportamentais e preferência do usuário para entregar recomendações relevantes.
- **Rastreabilidade**: [RQ32](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir recomendações de filmes baseadas em histórico e preferências.

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

---

### 8. **Recomendações de Filmes**

- **Tipo**: Objeto
- **Sinônimos**: Sugestões, Indicações, Lista personalizada
- **Noção**: Conjunto de filmes apresentados ao usuário com base em dados como seu histórico, preferências e comportamento de uso.
- **Impacto**: Influencia diretamente a decisão do usuário, aumentando as chances do mesmo assistir a um filme recomendado. Deve ser exibido em local de fácil acesso, com informações claras e atrativas.
- **Rastreabilidade**: [RQ32](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Exibir recomendações de filmes baseadas em histórico e preferências.

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

---

### 9. **Comparar Preços de Ingressos**

- **Tipo**: Verbo
- **Sinônimos**: Ver preços, Analisar valores, Checar tarifas
- **Noção**: Ação em que o usuário solicita a exibição de preços de ingressos e combos para um mesmo filme em diferentes cinemas disponíveis.
- **Impacto**: Permite ao usuário tomar decisões mais econômicas e conscientes. O sistema deve coletar e apresentar os preços de forma clara, organizada e atualizada, respeitando as regras de cada cinema Cinemark.
- **Rastreabilidade**: [RQ58](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer comparação de preços entre cinemas.

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

---

### 10. **Tabela Comparativa de Preços**

- **Tipo**: Objeto
- **Sinônimos**: Comparação de preços, Série de valores, Lista de tarifas
- **Noção**: Tabela exibida ao usuário com os preços de ingressos e combos em diferentes cinemas para o mesmo filme.
- **Impacto**: Facilita a comparação direta, promovendo escolhas mais vantajosas para o usuário. Deve incluir o local dos cinemas, horários e valores totais, respeitando promoções e taxas aplicáveis.
- **Rastreabilidade**: [RQ58](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer comparação de preços entre cinemas.

<p align="center"><br>
Autor: <a href="https://github.com/Davicamilo23">Davi Camilo</a>, 2025.</p>

### 11. **Fornecer um Hub para crítica de filmes**

- **Tipo**: Objeto
- **Sinônimos**: Central de Críticas, Seção de Avaliações, Espaço de Opiniões
- **Noção**: Área centralizada no aplicativo Cinemark onde usuários podem ler, escrever e interagir com críticas e avaliações de filmes em cartaz ou futuros lançamentos.
- **Impacto**: Permite que usuários compartilhem opiniões, influenciem decisões de outros espectadores e engajem com a comunidade.
- **Rastreabilidade**: [RQ60](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer um Hub para crítica de filmes.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

### 12. **Fornecer um Hub para crítica de filmes**

- **Tipo**: Verbo
- **Sinônimos**: Disponibilizar espaço para críticas, Oferecer seção de avaliações
- **Noção**: Ação de implementar e manter uma área dedicada no aplicativo para que críticas de filmes sejam centralizadas e acessíveis.
- **Impacto**: Melhora a experiência do usuário ao agregar informações relevantes e promover interação social.
- **Rastreabilidade**: [RQ60](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Fornecer um Hub para crítica de filmes.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

### 13. **Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial**

- **Tipo**: Objeto
- **Sinônimos**: Compra de ingressos, Seção de ingressos, Botão de ingressos
- **Noção**: Funcionalidade ou elemento de interface que permite ao usuário visualizar, selecionar e comprar ingressos para sessões de cinema de forma rápida e intuitiva.
- **Impacto**: Reduz atritos na jornada do usuário, aumentando conversões de vendas e satisfação.
- **Rastreabilidade**: [RQ67](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

### 14. **Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial**

- **Tipo**: Verbo
- **Sinônimos**: Simplificar compra de ingressos, Otimizar visibilidade de ingressos
- **Noção**: Ação de garantir que a interface do aplicativo priorize e torne óbvio o caminho para comprar ingressos (ex.: botão fixo, atalho no menu).
- **Impacto**: Acelera o processo de compra e reduz a taxa de abandono de carrinho.
- **Rastreabilidade**: [RQ67](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/#tabela-1-requisitos-elicitados-versao-1) – Tornar o acesso aos ingressos fácil e visível na interface, com botão dedicado ou atalho no menu inicial.

<p align="center"><br>
Autor: <a href="https://github.com/ArturDCR">Artur de Camargos</a>, 2025.</p>

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
| `1.4`  | 18/05/2025 | Adição dos léxicos 7 e 8 (referentes ao RQ32), e 9 e 10 (referentes ao RQ58) | [Davi Camilo](https://github.com/Davicamilo23) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) |
| `1.5`  | 18/05/2025 | Adição dos léxicos 11 e 12 (referentes ao RQ60), e 13 e 14 (referentes ao RQ67) | [Artur de Camargos](https://github.com/ArturDCR) | [Tiago Antunes](https://github.com/TiagoBalieiro) |
| `1.6`  | 18/05/2025 | Correção dos léxicos dos requisitos RQ59 e RQ33 | [Euller Júlio](https://github.com/Potatoyz908) | [Tiago Antunes](https://github.com/TiagoBalieiro) |

