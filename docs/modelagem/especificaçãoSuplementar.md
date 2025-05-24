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

| ID                                                                                                          | Descrição Resumida                                                                                                                                   | Categoria      |
| ----------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Tempo de resposta ≤ 3 s em telas críticas (seleção de assentos, pagamento).                            | Desempenho     |
| [RQ41](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Disponibilidade ≥ 99,5 % para funções críticas.                                       | Confiabilidade |
| [RQ42](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet).                    | Usabilidade    |
| [RQ43](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Interface intuitiva, com navegação fácil e boa usabilidade.                                             | Usabilidade    |
| [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixa visão.              | Usabilidade    |
| [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Contraste de interface conforme WCAG A/AA.                                              | Usabilidade    |
| [RQ46](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Garantir legenda clara para cores e ícones no mapa de assentos.                                         | Usabilidade    |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Atualizar automaticamente o valor total conforme seleção de ingressos e produtos.                | Desempenho     |
| [RQ48](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Proteger dados de pagamento e histórico do usuário com criptografia.                                   | Segurança      |
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Autenticação por biometria ou PIN para operações sensíveis.                                             | Segurança      |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Notificações push customizáveis pelo usuário.                                                       | Funcionalidade |
| [RQ51](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Exibir mapa de assentos com indicação gráfica clara de ocupação e disponibilidade.                     | Usabilidade    |
| [RQ52](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Limitar quantidade máxima de 20 unidades por item no Snack Bar.                                        | Funcionalidade |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra.| Usabilidade    |
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Ocultar parcialmente o e‑mail recuperado para segurança (exibir com asteriscos).                      | Segurança      |
| [RQ55](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Validar e‑mail e senha antes de criação ou redefinição de conta.                                       | Confiabilidade |
| [RQ56](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Remover automaticamente promoções expiradas da interface.                                              | Confiabilidade |
| [RQ57](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Validar dados pessoais no perfil antes de salvar.                                                      | Confiabilidade |
| [RQ63](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | O aplicativo deve ser leve e usar pouca memória do dispositivo.                                          | Desempenho     |
| [RQ66](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Permitir acesso ao ingresso offline, sem depender de conexão à internet na hora da sessão.             | Confiabilidade |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

 ---

## 4. Funcionalidade

### Tabela 2: Detalhamento do RQ50

| ID                                                                                                | Descrição                                                                                    | Categoria Detalhada           | Métrica                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| [RQ50](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | O sistema deve permitir que o usuário personalize as notificações push, incluindo o tipo de evento, o horário de envio e o conteúdo da notificação. | Funcionalidade – Notificações | Percentual de usuários que personalizam suas notificações e tempo de resposta para aplicar as mudanças. |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>


### Tabela 3: Detalhamento do RQ52

| ID                                                                                                | Descrição                                                                                    | Categoria Detalhada           | Métrica                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| [RQ52](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | O sistema deve limitar a quantidade máxima de 20 unidades por item no Snack Bar, garantindo que o usuário não possa adicionar mais unidades de um item ao carrinho do que o permitido. | Funcionalidade – Limitação de Quantidade | Percentual de tentativas de adicionar mais de 20 unidades que foram bloqueadas corretamente pelo sistema. |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>

## 5. Usabilidade
## 6. Confiabilidade
## 7. Desempenho

### Tabela 2: Detalhamento do RQ40

| ID   | Descrição                                                                                               | Categoria Detalhada            | Métrica                                                        |
| ---- | ------------------------------------------------------------------------------------------------------- | ------------------------------ | -------------------------------------------------------------- |
| [RQ40](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | O sistema deve responder às interações nas telas críticas (seleção de assentos e pagamento) em até 3 s. | Desempenho – Tempo de Resposta | Tempo médio de resposta medido em ambiente de testes de carga. |

<font size="3"><p style="text-align: center">Autor: [Arthur Evangelista de Oliveira](https://github.com/arthurevg).</p></font>

## 8. Segurança
## 9. Suportabilidade



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

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### Tabela 6: Detalhamento do RQ47

| ID                                                                                                | Descrição                                                                                                | Categoria Detalhada      | Métrica                                                                     |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- | ------------------------ | --------------------------------------------------------------------------- |
| [RQ47](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | Os dados sensíveis (pagamento e histórico do usuário) devem ser criptografados em trânsito e em repouso. | Segurança – Criptografia | Verificação de uso de protocolos HTTPS e criptografia AES nos dados salvos. |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### Tabela 7: Detalhamento do RQ48

| ID                                                                                                | Descrição                                                                                                                | Categoria Detalhada      | Métrica                                                                 |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ | ------------------------ | ----------------------------------------------------------------------- |
| [RQ48](https://requisitos-de-software.github.io/2025.1-Cinemark/elicita%C3%A7%C3%A3o/requisitosElicitados/) | O sistema deve exigir autenticação multifator para realizar operações críticas, como alteração de dados e cancelamentos. | Segurança – Autenticação | Percentual de operações críticas protegidas por autenticação adicional. |

<font size="3"><p style="text-align: center">Autor: [Davi Camilo](https://github.com/Davicamilo23), 2025.</p></font>

### Tabela 8: Detalhamento do RQ45

| ID                                                                                                | Descrição                                                                                   | Categoria Detalhada                 | Métrica                                                                         |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ----------------------------------- | ------------------------------------------------------------------------------- |
| [RQ45](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | A interface deve apresentar contraste visual de acordo com os critérios da norma WCAG A/AA. | Usabilidade – Acessibilidade Visual | Verificação de contraste mínimo de 4.5:1 para textos normais, segundo WCAG 2.1. |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

### Tabela 9: Detalhamento do RQ49

| ID                                                                                                | Descrição                                                                                                                  | Categoria Detalhada                | Métrica                                                                   |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- | ------------------------------------------------------------------------- |
| [RQ49](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | O sistema deve permitir autenticação por biometria (impressão digital ou reconhecimento facial) ou PIN em ações sensíveis. | Segurança – Autenticação de Acesso | Percentual de funcionalidades críticas que exigem autenticação adicional. |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>

### Tabela 10: Detalhamento do RQ66

| ID                                                                                                | Descrição                                                                                    | Categoria Detalhada           | Métrica                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| [RQ66](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | O sistema deve permitir o acesso ao ingresso mesmo sem conexão à internet, durante a sessão. | Usabilidade – Suporte Offline | Acesso local ao ingresso digital armazenado em cache ou memória do app (sem necessidade de conexão). |

<font size="3"><p style="text-align: center">Autor: [Euller Júlio](https://github.com/Potatoyz908), 2025.</p></font>


### Tabela 12: Detalhamento do RQ51

| ID                                                                                                | Descrição                                                                                    | Categoria Detalhada           | Métrica                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| [RQ51](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | O sistema deve exibir um mapa gráfico de assentos, indicando claramente os assentos disponíveis e ocupados, com a possibilidade de filtrar por tipo de assento (normal, VIP, etc.). | Usabilidade – Interface Gráfica | Percentual de usuários que conseguem identificar os assentos disponíveis com sucesso em até 3 segundos. |

<font size="3"><p style="text-align: center">Autor: [Tiago Antunes Balieiro](https://github.com/tiagobalieiro), 2025.</p></font>


### Tabela 14: Detalhamento do RQ44

| ID                                                                                                | Descrição                                                                                    | Categoria Detalhada           | Métrica                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| [RQ44](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | Interface acessível para pessoas com deficiência visual (leitores de tela) e baixa visão. | Usabilidade (Acessibilidade) | Conformidade com WCAG 2.1 (nível AA). Testes com leitores de tela (TalkBack e VoiceOver) alcançam 95% de funcionalidade acessível. |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos](https://github.com/ArturDCR), 2025.</p></font>

### Tabela 15: Detalhamento do RQ53

| ID                                                                                                | Descrição                                                                                    | Categoria Detalhada           | Métrica                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| [RQ53](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra. | Usabilidade (Consistência de Interface) | 100% dos usuários identificam as informações da sessão sem recarregar a tela. Layout persiste em cabeçalho fixo ou barra lateral durante o fluxo. |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos](https://github.com/ArturDCR), 2025.</p></font>

### Tabela 16: Detalhamento do RQ63

| ID                                                                                                | Descrição                                                                                    | Categoria Detalhada           | Métrica                                                                                              |
| ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- |
| [RQ63](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | O aplicativo deve ser leve e usar pouca memória do dispositivo. | Desempenho (Eficiência de Recursos) | Consumo de memória não excede 150 MB em uso contínuo. Compatibilidade com dispositivos Android (API 24+) e iOS (versão 12+). |

<font size="3"><p style="text-align: center">Autor: [Artur de Camargos](https://github.com/ArturDCR), 2025.</p></font>

### Tabela 17: Detalhamento do RQ43

| ID                                                                                                | Descrição                                                                                                          | Categoria Detalhada                    | Métrica                                                                                  |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | -------------------------------------- | ---------------------------------------------------------------------------------------- |
| [RQ43](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | A interface do sistema deve ser intuitiva, com navegação fácil e boa usabilidade para todos os perfis de usuário.  | Usabilidade – Facilidade de Navegação  | Número médio de cliques para realizar tarefas principais (esperado: ≤ 3 cliques).        |

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

### Tabela 18: Detalhamento do RQ54

| ID                                                                                                | Descrição                                                                                                          | Categoria Detalhada                    | Métrica                                                                                  |
| ------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ | -------------------------------------- | ---------------------------------------------------------------------------------------- |
| [RQ54](https://requisitos-de-software.github.io/2025.1-Cinemark/elicitação/requisitosElicitados/) | O sistema deve ocultar parcialmente o e-mail recuperado, exibindo parte do endereço com asteriscos para segurança. | Segurança – Proteção de Dados Pessoais | Padrão de mascaramento aplicado corretamente (ex.: j\*\*\*@g\*\*\*.com); 100% dos casos. |

<p align="center"><br>
Autor: <a href="https://github.com/GabrielCastelo-31">Gabriel Castelo</a>, 2025.</p>

---

## 4. Referências Bibliográficas

> **IEEE.** *IEEE Recommended Practice for Software Requirements Specifications – IEEE* Std 830-1998. Disponível em: [https://professor.pucgoias.edu.br/sitedocente/admin/arquivosUpload/17785/material/IEEE830.pdf](https://professor.pucgoias.edu.br/sitedocente/admin/arquivosUpload/17785/material/IEEE830.pdf). Acesso em: 17 de maio 2025.

> **IBM CORPORATION.** *Using Rational RequisitePro*. [S.l.]: IBM, ano. Disponível em: [https://public.dhe.ibm.com/software/rational/docs/documentation/manuals/docsetml271/Rational_RequisitePro/Documentation/reqpro_users.pdf](IBM CORPORATION. Using Rational RequisitePro. [S.l.]: IBM, ano. Disponível em: https://public.dhe.ibm.com/software/rational/docs/documentation/manuals/docsetml271/Rational_RequisitePro/Documentation/reqpro_users.pdf). Acesso em: 17 de maio de 2025.

> **BRASIL. Ministério da Ciência, Tecnologia, Inovações e Comunicações.** Secretaria-Executiva. Diretoria de Tecnologia da Informação. Coordenação Geral de Sistemas. Especificação suplementar. Versão 1.0, [s.l.], [s.d.]. Disponível em: <https://aprender3.unb.br/mod/resource/view.php?id=1390972>. Acesso em: 17 maio 2025.

> **SERRANO**, Milene; **SERRANO**, Maurício. *Requisitos – Aula 13*. Universidade de Brasília, Campus Gama (UnB Gama). Material de aula. Disponível em <https://aprender3.unb.br/pluginfile.php/3096129/mod_resource/content/2/SiglaProjeto_EspecificacaoSuplementar.pdf>. Acesso em 17 de maio de 2025.

> **WIEGERS, Karl; BEATTY, Joy.** Software Requirements. 3. ed. Redmond: Microsoft Press, 2013.


---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 13/05/2025 | Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23) | Todos |
| `1.1`  | 17/05/2025 | Adição de introdução, metodologia, tabelas 1, 2, 3 e 4, e referências | [Arthur Evangelista](https://github.com/arthurevg) | Todos |
| `1.2`  | 17/05/2025 | Adição do detalhamento dos requisitos RQ46, RQ47 e RQ48 com suas respectivas tabelas (5, 6 e 7) | [Davi Camilo](https://github.com/Davicamilo23) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.3`  | 17/05/2025 | Adição das tabelas 8, 9 e 10 com os requisitos RQ45 (contraste), RQ49 (biometria) e RQ66 (offline) | [Euller Júlio](https://github.com/Potatoyz908) | [Arthur Evangelista](https://github.com/arthurevg) |
| `1.3.1`  | 17/05/2025 | Correções na tabela 1 |  [Arthur Evangelista](https://github.com/arthurevg) | [Euller Júlio](https://github.com/Potatoyz908)|
| `1.4`  | 18/05/2025 | Adição do detalhamento dos requisitos RQ50, RQ51 e RQ52 com suas respectivas tabelas (11, 12 e 13) |  [Tiago Antunes Balieiro](https://github.com/tiagobalieiro) | [Artur de Camargos Rodrigues](https://github.com/ArturDCR)|
| `1.5`  | 18/05/2025 | Adição do detalhamento dos requisitos RQ44, RQ53 e RQ63 com suas respectivas tabelas (14, 15 e 16) | [Artur de Camargos Rodrigues](https://github.com/ArturDCR) | [Tiago Antunes Balieiro](https://github.com/tiagobalieiro)|
| `1.6`  | 18/05/2025 | Adição do detalhamento dos requisitos RQ43 e RQ54 com suas respectivas tabelas (17 e 18) | [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Euller Júlio](https://github.com/Potatoyz908)|
| `1.7`  | 18/05/2025 | Padroniza autoria das tabelas como "Autor:"| [Gabriel Castelo](https://github.com/GabrielCastelo-31) | [Davi Camilo](https://github.com/Davicamilo23) |
