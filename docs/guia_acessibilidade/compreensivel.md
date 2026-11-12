# Compreensível

O princípio da **Compreensibilidade** estabelece que as informações e o funcionamento das interfaces devem ser claros e previsíveis. Isso envolve desde a linguagem utilizada até a identificação e correção de erros em formulários.

As aplicações devem buscar, no mínimo, os níveis A e AA das WCAG, considerando também as necessidades reais dos usuários que dependem de recursos de acessibilidade (NASCIMENTO et al., 2023, p. 20-21).

## Formulários e mensagens de erro

A navegação deve apresentar comportamentos previsíveis, evitando mudanças inesperadas de contexto, como a abertura automática de novas janelas ou abas. Quando essas mudanças forem necessárias, devem ser previamente informadas ou ocorrer a partir de uma ação do usuário, conforme os critérios 3.2.1 e 3.2.2, ambos de nível A.

Além disso, mecanismos de ajuda devem permanecer em posições consistentes entre as páginas (critério 3.2.6). Os mecanismos de navegação repetidos devem manter a mesma ordem relativa (critério 3.2.3, nível AA), e componentes com a mesma funcionalidade devem apresentar identificações consistentes (critério 3.2.4, nível AA) (W3C, 2023).

Durante o preenchimento de formulários, devem ser fornecidos rótulos e instruções claras. Quando ocorrerem erros, eles precisam ser identificados e descritos em texto, com sugestões de correção sempre que possível.

| **Critério WCAG** | **Orientação** | **Nível** |
|---|---|---|
| 3.3.1 | Identificar e descrever erros em texto. | A |
| 3.3.2 | Fornecer rótulos e instruções para o preenchimento. | A |
| 3.3.3 | Apresentar sugestões de correção para erros identificados. | AA |
| 3.3.4 | Permitir revisar, confirmar ou corrigir informações antes de ações importantes. | AA |
| 3.3.7 | Reduzir a necessidade de inserir novamente informações já fornecidas. | A |
| 3.3.8 | Garantir que os mecanismos de autenticação sejam acessíveis. | AA |

A ABNT NBR 17225:2025 também estabelece orientações para mensagens de erro e formulários:

| **Requisito ABNT** | **Orientação** | **Classificação** |
|---|---|---|
| 5.9.9 | Descrever o erro em texto e identificar o campo correspondente. | Requisito |
| 5.9.10 | Fornecer sugestões de correção quando conhecidas. | Requisito |
| 5.9.11 | Permitir reverter, verificar ou confirmar informações. | Recomendação |
| 5.9.12 | Permitir reverter, verificar ou confirmar informações em formulários críticos. | Requisito |

Recomenda-se utilizar elementos HTML semânticos adequados, manter os formulários objetivos e apresentar mensagens de erro visíveis e próximas aos campos correspondentes. Essas práticas facilitam a identificação dos problemas e a correção das informações (NASCIMENTO et al., 2023, p. 30-31; ABNT, 2025, p. 23-24).

## Linguagem e conteúdo

O idioma principal da página deve ser identificado programaticamente, por meio do atributo `lang` no HTML ou da informação correspondente no cabeçalho HTTP. Essa identificação permite que tecnologias assistivas interpretem corretamente o conteúdo (critério 3.1.1, nível A).

Quando houver mudanças de idioma em trechos específicos, elas também devem ser identificadas programaticamente (critério 3.1.2, nível AA). Essas orientações são contempladas pelos requisitos 5.13.2 e 5.13.3 da ABNT NBR 17225:2025 (W3C, 2023; ABNT, 2025, p. 30).

Outros critérios relacionados à compreensão da linguagem são:

| **Critério WCAG** | **Orientação** | **Nível** |
|---|---|---|
| 3.1.3 | Disponibilizar definições para palavras incomuns, expressões idiomáticas e jargões. | AAA |
| 3.1.4 | Oferecer recursos para identificar o significado de abreviações. | AAA |
| 3.1.5 | Disponibilizar recursos complementares para textos que exigem habilidades de leitura superiores ao nível do ensino médio inferior. | AAA |
| 3.1.6 | Fornecer recursos para identificar a pronúncia correta de palavras ambíguas. | AAA |

Para facilitar a compreensão, podem ser utilizados glossários, listas de descrição, explicações no próprio texto e links para definições. Em conteúdos mais complexos, também podem ser oferecidos resumos, ilustrações, imagens, símbolos, versões em áudio ou em língua de sinais.

Essas alternativas tornam o conteúdo mais acessível a pessoas com diferentes níveis de habilidade de leitura e compreensão (W3C, 2023).

## Referências bibliográficas

Para consultar as normas, diretrizes e materiais utilizados neste princípio, acesse a página de [Acesse as referências bibliográficas](referencias.md).