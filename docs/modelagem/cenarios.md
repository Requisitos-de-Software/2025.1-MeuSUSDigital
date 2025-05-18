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