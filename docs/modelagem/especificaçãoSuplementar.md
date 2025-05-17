# Especificação Suplementar

## 1. Introdução

Este artefato tem como objetivo complementar os modelos de [Casos de Uso](https://requisitos-de-software.github.io/2025.1-Cinemark/modelagem/casosDeUso/) do sistema Cinemark ao reunir os requisitos não funcionais que influenciam diretamente na qualidade do produto final. Diferentemente dos requisitos funcionais, esses requisitos descrevem características como desempenho, confiabilidade, facilidade de uso, manutenção e suporte. São atributos essenciais para garantir que o sistema seja robusto, confiável, eficiente e agradável para o usuário.

## 2. Metodologia

A elaboração deste artefato seguiu os princípios do modelo FURPS+, amplamente utilizado na engenharia de software para organizar requisitos não funcionais. Este modelo sistematiza os requisitos de qualidade em cinco categorias principais: Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade, além de uma categoria complementar indicada pelo símbolo "+". Cada uma dessas categorias contempla aspectos específicos do sistema, proporcionando uma visão ampla e estruturada das qualidades esperadas do software.

* **F** – *Funcionalidade*: aspectos que tratam das funções, regras de negócio, segurança e interoperabilidade.
* **U** – *Usabilidade*: requisitos relacionados à facilidade de uso, acessibilidade, interface e experiência do usuário.
* **R** – *Confiabilidade*: envolve disponibilidade, tolerância a falhas, segurança e consistência do sistema.
* **P** – *Desempenho*: cobre tempo de resposta, eficiência de processamento e capacidade do sistema.
* **S** – *Suportabilidade*: diz respeito à facilidade de manutenção, adaptabilidade, portabilidade e escalabilidade.
* **+** – requisitos adicionais, como restrições legais, licenças, requisitos físicos, entre outros.

## 3. Requisitos Não Funcionais

### Tabela 1: Visão Geral dos RNFs

| ID   | Descrição Resumida                                       | Categoria       |
| ---- | -------------------------------------------------------- | --------------- |
| [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Tempo de resposta ≤ 3 s em telas críticas                | Desempenho      |
| [RQ41](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Disponibilidade ≥ 99,5% para funções críticas            | Confiabilidade  |
| [RQ42](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Interface responsiva para smartphones e tablets          | Usabilidade     |
| [RQ43](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Navegação intuitiva                                      | Usabilidade     |
| [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Conformidade com WCAG A/AA                               | Usabilidade     |
| [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Tempo máximo de inicialização do app: 2 s                | Desempenho      |
| [RQ46](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Atualização dinâmica do valor total em tempo real        | Desempenho      |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Criptografia de dados sensíveis em trânsito e repouso    | Confiabilidade  |
| [RQ48](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Autenticação multifator para operações críticas          | Confiabilidade  |
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Customização de notificações                             | Usabilidade     |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Limite de 20 itens por pedido no Snack Bar               | Suportabilidade |
| [RQ51](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Persistência de sessão em caso de interrupção inesperada | Suportabilidade |
| [RQ52](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Suporte offline para exibição de ingressos               | Usabilidade     |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Uso de bibliotecas open‑source licenciadas               | Suportabilidade |
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Log de auditoria para rastreabilidade de ações           | Confiabilidade  |
| [RQ55](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Atualização automática de dependências de segurança      | Suportabilidade |
| [RQ56](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Monitoramento de performance em tempo real               | Desempenho      |
| [RQ57](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Backup diário de banco de dados                          | Confiabilidade  |
| [RQ63](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Uso máximo de 150 MB de memória em operação normal       | Suportabilidade |
| [RQ66](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Acesso offline ao ingresso na hora da sessão             | Usabilidade     |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

 ---

### Tabela 2: Detalhamento do RQ40

| ID   | Descrição                                                                                               | Categoria Detalhada            | Métrica                                                        |
| ---- | ------------------------------------------------------------------------------------------------------- | ------------------------------ | -------------------------------------------------------------- |
| [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | O sistema deve responder às interações nas telas críticas (seleção de assentos e pagamento) em até 3 s. | Desempenho – Tempo de Resposta | Tempo médio de resposta medido em ambiente de testes de carga. |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

### Tabela 3: Detalhamento do RQ41

| ID   | Descrição                                                                                       | Categoria Detalhada              | Métrica                                                      |
| ---- | ----------------------------------------------------------------------------------------------- | -------------------------------- | ------------------------------------------------------------ |
| [RQ41](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | As funcionalidades críticas devem permanecer disponíveis pelo menos 99,5% do tempo em cada mês. | Confiabilidade – Disponibilidade | Percentual de tempo de atividade monitorado automaticamente. |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

### Tabela 4: Detalhamento do RQ42

| ID   | Descrição                                                                                                               | Categoria Detalhada          | Métrica                                           |
| ---- | ----------------------------------------------------------------------------------------------------------------------- | ---------------------------- | ------------------------------------------------- |
| [RQ42](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | A interface do aplicativo deve se adaptar a diferentes tamanhos de tela (smartphones e tablets), mantendo legibilidade. | Usabilidade – Adaptabilidade | Testes de compatibilidade em diversas resoluções. |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

### Tabela 5: Detalhamento do RQ46

| ID                                                                                                | Descrição                                                                                                       | Categoria Detalhada                  | Métrica                                                                         |
| ------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------------------------------ | ------------------------------------------------------------------------------- |
| [RQ46](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | O sistema deve atualizar dinamicamente o valor total conforme a seleção de ingressos e produtos, em tempo real. | Usabilidade – Feedback em Tempo Real | Tempo entre a seleção e a atualização do valor exibido (esperado: < 1 segundo). |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### Tabela 6: Detalhamento do RQ47

| ID                                                                                                | Descrição                                                                                                | Categoria Detalhada      | Métrica                                                                     |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------ | --------------------------------------------------------------------------- |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Os dados sensíveis (pagamento e histórico do usuário) devem ser criptografados em trânsito e em repouso. | Segurança – Criptografia | Verificação de uso de protocolos HTTPS e criptografia AES nos dados salvos. |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### Tabela 7: Detalhamento do RQ48

| ID                                                                                                | Descrição                                                                                                                | Categoria Detalhada      | Métrica                                                                 |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ------------------------ | ----------------------------------------------------------------------- |
| [RQ48](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | O sistema deve exigir autenticação multifator para realizar operações críticas, como alteração de dados e cancelamentos. | Segurança – Autenticação | Percentual de operações críticas protegidas por autenticação adicional. |

<font size="3"><p style="text-align: center">Fonte: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

---

## 4. Referências Bibliográficas

> **IEEE.** *IEEE Recommended Practice for Software Requirements Specifications – IEEE* Std 830-1998. Disponível em: [https://professor.pucgoias.edu.br/sitedocente/admin/arquivosUpload/17785/material/IEEE830.pdf](https://professor.pucgoias.edu.br/sitedocente/admin/arquivosUpload/17785/material/IEEE830.pdf). Acesso em: 17 de maio 2025.

> **IBM CORPORATION.** *Using Rational RequisitePro*. [S.l.]: IBM, ano. Disponível em: [https://public.dhe.ibm.com/software/rational/docs/documentation/manuals/docsetml271/Rational_RequisitePro/Documentation/reqpro_users.pdf](IBM CORPORATION. Using Rational RequisitePro. [S.l.]: IBM, ano. Disponível em: https://public.dhe.ibm.com/software/rational/docs/documentation/manuals/docsetml271/Rational_RequisitePro/Documentation/reqpro_users.pdf). Acesso em: 17 de maio de 2025.

> **BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações.** Secretaria-Executiva. Diretoria de Tecnologia da Informação. Coordenação Geral de Sistemas. Especificação suplementar. Versão 1.0, [s.l.], [s.d.]. Disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1390972>. Acesso em: 17 maio 2025.

> **SERRANO**, Milene; **SERRANO**, Maurício. *Requisitos – Aula 13*. Universidade de Brasília, Campus Gama (UnB Gama). Material de aula. Disponível em <https://aprender3.unb.br/pluginfile.php/3096129/mod_resource/content/2/SiglaProjeto_EspecificacaoSuplementar.pdf>. Acesso em 17 de maio de 2025.


---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 13/05/2025 | Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23) | Todos |
| `1.1`  | 17/05/2025 | Adição de introdução, metodologia, tabelas 1, 2, 3 e 4, e referências | [Arthur Evangelista](https://github.com/arthurevg) | Todos |
| `1.2`  | 17/05/2025 | Adição do detalhamento dos requisitos RQ46, R47 e RQ48 com suas respectivas tabelas (5, 6 e 7) | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
