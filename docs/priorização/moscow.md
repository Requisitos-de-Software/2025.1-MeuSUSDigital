# MoSCoW

## Introdução
Este documento apresenta a priorização de requisitos para um sistema de venda de ingressos e gestão de cinemas, utilizando a técnica **MoSCoW**. Essa metodologia categoriza os requisitos em quatro grupos: **Must Have** (obrigatórios), **Should Have** (importantes), **Could Have** (desejáveis) e **Won't Have** (não prioritários). O objetivo é garantir o foco nas funcionalidades críticas para o sucesso do produto, alinhando-se às necessidades do usuário e às restrições técnicas.

---

## Metodologia
A priorização seguiu os critérios:
- **Must Have**: Requisitos essenciais para o funcionamento básico do sistema.
- **Should Have**: Funcionalidades importantes, mas que podem ser adiadas sem comprometer o lançamento.
- **Could Have**: Recursos desejáveis, porém não urgentes.
- **Won't Have**: Itens excluídos do escopo atual devido a baixo impacto ou complexidade.

---

## Tabela de Requisitos

<table>
    <tr>
        <th style="text-align:center">Categoria</th>
        <th>ID</th>
        <th>Requisito</th>
        <th>Rastreabilidade</th>
    </tr>
        <td rowspan="27" style="text-align:center; vertical-align:middle">Must Have</td>
        <td>RQ44</td>
        <td>Interface acessível para pessoas com deficiência visual (leitores de tela) e baixovisão</td>
        <td>IS35, AI25, ST05</td>
    </tr>
    <tr>
        <td>RQ43</td>
        <td>Interface intuitiva, com navegação fácil e boa usabilidade</td>
        <td>IS28</td>
    </tr>
    <tr>
        <td>RQ16</td>
        <td>Exibir resumo da compra e permitir aplicação de cupom de desconto</td>
        <td>AI13, AI29</td>
    </tr>
    <tr>
        <td>RQ4</td>
        <td>Autenticar usuário por e-mail e senha</td>
        <td>AI04</td>
    </tr>
    <tr>
        <td>RQ41</td>
        <td>Garantir uptime de 99,5% para funções críticas</td>
        <td>AI28</td>
    </tr>
        <tr>
        <td>RQ37</td>
        <td>Criar e editar perfil do usuário, gerenciar dados pessoais e métodos de pagamento</td>
        <td>AI31</td>
    </tr>
        <tr>
        <td>RQ21</td>
        <td>Recuperação de conta: enviar link de redefinição de senha por e-mail, recuperar e-mail via CPF e redefinir com código</td>
        <td>AI18, AI19, AI20</td>
    </tr>
    <tr>
        <td>RQ9</td>
        <td>Permitir compra de ingressos com cartão de crédito, débito ou Pix</td>
        <td>IS5, AI14, Q02</td>
    </tr>
    <tr>
        <td>RQ33</td>
        <td>Permitir alteração de preferências de idioma</td>
        <td>IS25</td>
    </tr>
    <tr>
        <td>RQ45</td>
        <td>Contraste de interface conforme WCAG A/AA</td>
        <td>AI25</td>
    </tr>
        <tr>
        <td>RQ8</td>
        <td>Exibir sessões com data, horário, idioma, formato e sala</td>
        <td>IS4, ST01, AI08, Q01</td>
    </tr>
    <tr>
        <td>RQ3</td>
        <td>Navegar por abas: Home, Filmes, Cinemas, Snack Bar, Club e Mais</td>
        <td>AI03</td>
    </tr>
    <tr>
        <td>RQ5</td>
        <td>Buscar filmes por nome</td>
        <td>AI04</td>
    </tr>
    <tr>
        <td>RQ18</td>
        <td>Disponibilizar ingresso digital no app, eliminando a necessidade de impressão</td>
        <td>IS9, ST03</td>
    </tr>
        <tr>
        <td>RQ12</td>
        <td>Exibir mapa da sala com indicação gráfica de assentos ocupados, livres e especiais, e permitir seleção pelos usuários</td>
        <td>IS8, AI09</td>
    </tr>
    <tr>
        <td>RQ2</td>
        <td>Detectar localização automaticamente e permitir alteração manual</td>
        <td>IS2, AI02</td>
    </tr>
    <tr>
        <td>RQ55</td>
        <td>Validar e-mail e senha antes de criação ou redefinição de conta</td>
        <td>AI34</td>
    </tr>
    <tr>
        <td>RQ54</td>
        <td>Ocultar parcialmente o e-mail recuperado para segurança (exibir com asteriscos)</td>
        <td>AI33</td>
    </tr>
        <tr>
        <td>RQ51</td>
        <td>Exibir mapa de assentos com indicação gráfica clara de ocupação e disponibilidade</td>
        <td>IS31</td>
    </tr>
        <tr>
        <td>RQ48</td>
        <td>Proteger dados de pagamento e histórico do usuário com criptografia</td>
        <td>IS32, Q10</td>
    </tr>
        <tr>
        <td>RQ7</td>
        <td>Exibir informações do filme (título, sinopse, gênero, duração, direção, elenco, distribuidor, origem)</td>
        <td>IS3, AI07</td>
    </tr>
        <tr>
        <td>RQ53</td>
        <td>Manter informações da sessão (filme, data, hora e sala) visíveis em todas as etapas do fluxo de compra</td>
        <td>AI27</td>
    </tr>
        <tr>
        <td>RQ13</td>
        <td>Exigir seleção de ao menos um assento antes de prosseguir</td>
        <td>AI10</td>
    </tr>
        <tr>
        <td>RQ11</td>
        <td>Permitir compra de múltiplos ingressos em uma única transação</td>
        <td>IS7</td>
    </tr>
        <tr>
        <td>RQ17</td>
        <td>Gerar QR Code e chave Pix para pagamentos via Pix</td>
        <td>AI15</td>
    </tr>
        <tr>
        <td>RQ46</td>
        <td>Garantir legenda clara para cores e ícones no mapa de assentos</td>
        <td>AI22</td>
    </tr>
        <tr>
        <td>RQ47</td>
        <td>Atualizar automaticamente o valor total conforme seleção de ingressos e produtos</td>
        <td>AI23</td>
    </tr>
        <td rowspan="13" style="text-align:center; vertical-align:middle">Should Have</td>
        <td>RQ40</td>
        <td>Tempo de resposta de até 3 segundos em telas críticas (seleção de assentos, pagamento)</td>
        <td>IS29, Q09, Q12</td>
    </tr>
    <tr>
        <td>RQ1</td>
        <td>Exibir na tela inicial filmes em cartaz, com pôsteres, novidades e promoções</td>
        <td>IS1, AI01</td>
    </tr>
    <tr>
        <td>RQ14</td>
        <td>Definir tipo de ingresso por assento (inteira, meia, convênio, voucher)</td>
        <td>AI11</td>
    </tr>
    <tr>
        <td>RQ25</td>
        <td>Oferecer fluxo de compra simplificado, com o mínimo de toques até a confirmação</td>
        <td>IS17</td>
    </tr>
    <tr>
        <td>RQ38</td>
        <td>Mensagens de erro claras e confirmações de ações para o usuário</td>
        <td>ST05, IS37</td>
    </tr>
        <tr>
        <td>RQ19</td>
        <td>Salvar automaticamente ingressos na seção “Meus Ingressos” após confirmação de compra</td>
        <td>AI16</td>
    </tr>
        <tr>
        <td>RQ57</td>
        <td>Validar dados pessoais no perfil antes de salvar</td>
        <td>AI36</td>
    </tr>
        <tr>
        <td>RQ26</td>
        <td>Permitir salvar ingressos na carteira digital do dispositivo (Google Wallet, Apple Wallet, etc.)</td>
        <td>IS18</td>
    </tr>
        <tr>
        <td>RQ28</td>
        <td>Alertar usuário sobre pontos suficientes para ingresso grátis e antes da expiração</td>
        <td>IS20</td>
    </tr>
        <tr>
        <td>RQ39</td>
        <td>Exibir avaliações e permitir que usuários avaliem filmes com escala de 1 a 5 estrelas</td>
        <td>IS15</td>
    </tr>
        </tr>
        <tr>
        <td>RQ35</td>
        <td>Exibir notificações e promoções com título, descrição e validade</td>
        <td>AI32</td>
    </tr>
        </tr>
        <tr>
        <td>RQ10</td>
        <td>Armazenar cartões de pagamento cadastrados para uso em compras futuras</td>
        <td>IS6</td>
    </tr>
        </tr>
        <tr>
        <td>RQ27</td>
        <td>Permitir uso de pontos acumulados para desconto em ingressos e produtos</td>
        <td>IS19, Q03</td>
    </tr>
            <td rowspan="16" style="text-align:center; vertical-align:middle">Could Have</td>
        <td>RQ36</td>
        <td>Impedir avanço para pagamento com carrinho vazio</td>
        <td>AI30</td>
    </tr>
    <tr>
        <td>RQ42</td>
        <td>Sistema responsivo e adaptável a diferentes tamanhos de tela (smartphone e tablet)</td>
        <td>AI24</td>
    </tr>
    <tr>
        <td>RQ6</td>
        <td>Listar filmes em cartaz, pré-venda e futuros lançamentos</td>
        <td>AI06</td>
    </tr>
    <tr>
        <td>RQ56</td>
        <td>Remover automaticamente promoções expiradas da interface</td>
        <td>AI35</td>
    </tr>
    <tr>
        <td>RQ49</td>
        <td>Autenticação por biometria ou PIN para operações sensíveis</td>
        <td>IS33</td>
    </tr>
        <tr>
        <td>RQ20</td>
        <td>Permitir criação de conta (nome, e-mail, senha, CPF) e login com Google/redes sociais</td>
        <td>AI17, IS26</td>
    </tr>
        <tr>
        <td>RQ22</td>
        <td>Exibir histórico de filmes assistidos (data, horário, cinema) e histórico de compras na bomboniere</td>
        <td>IS13, IS14</td>
    </tr>
        <tr>
        <td>RQ24</td>
        <td>Exibir trailers dentro do app</td>
        <td>IS16</td>
    </tr>
        <tr>
        <td>RQ29</td>
        <td>Sugerir cinemas com base no histórico de visitas e na localização atual</td>
        <td>IS21</td>
    </tr>
        <tr>
        <td>RQ23</td>
        <td>Filtrar filmes por categoria e exibir avaliações de público e plataformas externas</td>
        <td>IS15</td>
    </tr>
        <tr>
        <td>RQ31</td>
        <td>Permitir notificações personalizadas (ex.: “avise-me quando o filme X entrar em cartaz”)</td>
        <td>IS23</td>
    </tr>
        <tr>
        <td>RQ30</td>
        <td>Permitir que o usuário salve cinemas como favoritos</td>
        <td>IS22</td>
    </tr>
        <tr>
        <td>RQ50</td>
        <td>Notificações push customizáveis pelo usuário</td>
        <td>IS34</td>
    </tr>
        <tr>
        <td>RQ34</td>
        <td>Disponibilizar área dedicada ao Cinemark Club: ingressos, pontos acumulados e validade</td>
        <td>IS12</td>
    </tr>
        <tr>
        <td>RQ15</td>
        <td>Integrar bomboniere ao app para compra antecipada de itens e retirada rápida</td>
        <td>IS11, AI12</td>
    </tr>
        <tr>
        <td>RQ32</td>
        <td>Exibir recomendações de filmes baseadas em histórico e preferências</td>
        <td>IS24</td>
    </tr>
            <td rowspan="1" style="text-align:center; vertical-align:middle">Won't Have</td>
        <td>RQ52</td>
        <td>Limitar quantidade máxima de 20 unidades por item no Snack Bar</td>
        <td>AI26</td>
    </tr>
</table>

---

![](../assets/moscow/must.png)  
![](../assets/moscow/should.png)
![](../assets/moscow/could.png)  
![](../assets/moscow/wont.png)  

---

## Gravação com Usuário
- [Link para a gravação](https://youtu.be/qba_o8SSdFc)  

---

## Bibliografia
 - Interaction Design Foundation - IxDF. (2015, November 18). Making Your UX Life Easier with the MoSCoW. Interaction Design Foundation - IxDF. Disponível em: <https://www.interaction-design.org/literature/article/making-your-ux-life-easier-with-the-moscow>. Acesso em: 04 maio 2025.

---

## Histórico de Versão

| Versão | Data       | Descrição                          | Autor(es)     | Revisor(es) |
|--------|------------|------------------------------------|---------------|-------------|
| `1.0`  | 04/05/2025 | Criação do Documento | [Davi Camilo](https://github.com/Davicamilo23) | Todos |
| `1.1`  | 04/05/2025 | Incluindo dados da reunião | [Artur de Camargos](https://github.com/ArturDCR) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.2`  | 04/05/2025 | Atualização do link da reunião com o suário | [Artur de Camargos](https://github.com/ArturDCR) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.3`  | 04/05/2025 | Inclusão da bibliografia | [Artur de Camargos](https://github.com/ArturDCR) | [Davi Camilo](https://github.com/Davicamilo23) |
| `1.4`  | 09/05/2025 | Inclusão da tabela de requisitos | [Artur de Camargos](https://github.com/ArturDCR) | [Davi Camilo](https://github.com/Davicamilo23) |
