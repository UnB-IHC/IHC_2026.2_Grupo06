# Guia de Acessibilidade: Introdução e fundamentos

# Introdução

A acessibilidade digital é essencial para garantir que pessoas com diferentes capacidades possam utilizar sistemas e serviços digitais com autonomia. No Brasil, existem 18,6 milhões de pessoas com deficiência, segundo a PNAD Contínua (NASCIMENTO et al., 2023, p. 6). A ausência de recursos acessíveis pode impedir atividades cotidianas, como finalizar uma compra devido à falta de descrição de um botão. Além disso, a acessibilidade beneficia pessoas idosas e com baixo letramento digital (NASCIMENTO et al., 2023, p. 5).

Nesse contexto, a acessibilidade também representa um direito garantido por lei. O artigo 63 da Lei Brasileira de Inclusão estabelece a obrigatoriedade de acessibilidade nos sítios da internet (NASCIMENTO et al., 2023, p. 7).

## Avaliação de usabilidade

A avaliação de usabilidade permite identificar dificuldades enfrentadas pelos usuários durante a interação com uma interface (UI), contribuindo para o desenvolvimento de sistemas mais intuitivos, eficientes e satisfatórios.

Entre os métodos utilizados, destaca-se a avaliação heurística, que permite identificar problemas de usabilidade por meio da inspeção de especialistas, utilizando princípios previamente estabelecidos.

Embora os testes de usabilidade forneçam informações detalhadas sobre a experiência dos usuários, eles geralmente demandam mais tempo, equipe e recursos. Por isso, a avaliação heurística é uma alternativa ágil e de baixo custo para identificar problemas, inclusive nas etapas iniciais do desenvolvimento (MACIEL; MEDEIROS, 2026).

# Fundamentos da Acessibilidade Digital

A acessibilidade digital considera que pessoas possuem diferentes capacidades e necessidades ao interagir com sistemas e conteúdos web. Por isso, uma interface deve permitir que usuários com diferentes tipos de deficiência, limitações temporárias ou necessidades situacionais consigam navegar e utilizar seus recursos com autonomia e segurança.

## Diversidade de usuários e necessidades de acesso

As deficiências podem ser congênitas, adquiridas ou temporárias, influenciando a maneira como cada pessoa interage com a web (NASCIMENTO et al., 2023).

| Perfil do usuário | Necessidades e recursos de acesso |
|---|---|
| Deficiência visual | Leitores de tela e ampliadores de tela. |
| Deficiência física | Teclado, joysticks, comandos de voz e movimentos dos olhos. |
| Deficiência auditiva | Legendas e interpretação em Libras. |
| Pessoas neurodiversas | Conteúdo objetivo, organizado e com poucas distrações. |

A acessibilidade também beneficia pessoas idosas e com baixo letramento digital. Dessa forma, a avaliação de interfaces deve considerar diferentes perfis de usuários, e não apenas um padrão único de interação.

A NBR 17225:2025 considera necessidades relacionadas a limitações para enxergar, ouvir, falar, mover-se ou compreender, incluindo condições permanentes, temporárias e situacionais.

## Legislação e normas de acessibilidade

A acessibilidade digital é um direito fundamentado em documentos internacionais e na legislação brasileira, conforme:

- **Declaração Universal dos Direitos Humanos (1948):** estabelece direitos fundamentais aplicáveis a todas as pessoas.
- **Convenção sobre os Direitos das Pessoas com Deficiência (2006):** reconhece os direitos das pessoas com deficiência e foi incorporada ao ordenamento brasileiro em 2009, com status de emenda constitucional.
- **Lei Brasileira de Inclusão (Lei nº 13.146/2015):** o artigo 63 determina a obrigatoriedade de acessibilidade nos sítios da internet, abrangendo organizações com sede ou representação comercial no Brasil.

## Níveis de conformidade adotados no guia

Para classificar os resultados das avaliações, o guia estabelece três níveis próprios de conformidade, baseados na distinção entre requisitos obrigatórios e recomendações da NBR 17225:2025.

| Nível | Critério | Interpretação |
|---|---|---|
| **Nível 1** | Atende aos requisitos obrigatórios mínimos. | Ainda apresenta requisitos obrigatórios não atendidos e barreiras de acessibilidade a corrigir. |
| **Nível 2** | Atende a todos os requisitos obrigatórios. | Representa a conformidade regular, alinhada ao nível AA da WCAG 2.2. |
| **Nível 3** | Atende aos requisitos obrigatórios e às recomendações. | Aproxima-se da conformidade plena, incorporando boas práticas de acessibilidade e usabilidade. |

### Priorização das correções

Durante a avaliação, as falhas nos requisitos obrigatórios devem receber prioridade de correção. Após seu atendimento, recomenda-se avançar para as recomendações e boas práticas.

O Nível 3 também considera boas práticas complementares, como as apresentadas no Guia de Acessibilidade do Reino Unido (UK), e princípios de usabilidade.

**Importante:** os três níveis apresentados são uma classificação própria deste guia, construída com base na NBR 17225:2025. Não devem ser confundidos com os níveis oficiais de conformidade da WCAG (A, AA e AAA).

---
 
<div class="grid cards" markdown>

-   :material-eye:{ .lg .middle } __Perceptível__

    Avaliação da percepção das informações na interface, considerando cores, contraste, textos, imagens, recursos audiovisuais, responsividade e zoom.

    [:octicons-arrow-right-24: Ver Documentação](perceptivel.md)

-   :material-keyboard:{ .lg .middle } __Operável__

    Avaliação da interação com a interface, considerando navegação por teclado, foco, links, botões, controles, animações, movimentos e limites de tempo.

    [:octicons-arrow-right-24: Ver Documentação](operavel.md)

-   :material-text-box-check:{ .lg .middle } __Compreensível__

    Análise da clareza e previsibilidade da interface, considerando formulários, mensagens de erro, linguagem, conteúdo e orientações aos usuários.

    [:octicons-arrow-right-24: Ver Documentação](compreensivel.md)

-   :material-code-tags:{ .lg .middle } __Robusto__

    Avaliação da estrutura técnica e semântica do código, considerando elementos HTML, WAI-ARIA, cabeçalhos, regiões, listas e tabelas.

    [:octicons-arrow-right-24: Ver Documentação](robusto.md)

-   :material-magnify:{ .lg .middle } __Heurísticas de Usabilidade__

    Inspeção heurística baseada nas **10 heurísticas de Nielsen** e nas **15 heurísticas para Governo Eletrônico (e-Gov)**, com destaque para os critérios aplicáveis a serviços públicos digitais.

    [:octicons-arrow-right-24: Ver Documentação](heuristicas.md)

-   :material-test-tube:{ .lg .middle } __Testes e Ferramentas__

    Métodos de avaliação de acessibilidade por meio de testes automáticos e manuais, utilizando ferramentas como **WAVE, Lighthouse e NVDA**.

    [:octicons-arrow-right-24: Ver Documentação](testes_ferramentas.md)

-   :material-clipboard-check-outline:{ .lg .middle } __Checklist__

    Métodos de avaliação por meio do checklist, utilizando as normas da **WCAG, ABNT, Guia UK, Heuríscas**.

    [:octicons-arrow-right-24: Ver Documentação](checklist.md)

</div>

---

## Referências

Para consultar as normas, diretrizes e materiais utilizados neste princípio, acesse a página de [**Acesse as referências bibliográficas.**](referencias.md)